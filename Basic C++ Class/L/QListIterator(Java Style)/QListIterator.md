# QListIterator Class

template < typename T> class QListIterator

QListIterator 类提供了一个 Java 风格的 const 迭代器[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QQueue](https://doc-qt-io.translate.goog/qt-6/qqueue.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include < QListIterator>                                    |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:  | QT += core                                                   |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlistiterator-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共职能

|                     | **[QListIterator](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListIterator)**(const QList< T> &*list*) |
| ------------------- | ------------------------------------------------------------ |
| bool                | **[findNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)**(const T &*value*) |
| bool                | **[findPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)**(const T &*value*) |
| bool                | **[hasNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)**() const |
| bool                | **[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)**() const |
| const T &           | **[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)**() |
| const T &           | **[peekNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)**() const |
| const T &           | **[peekPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekPrevious)**() const |
| const T &           | **[previous](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)**() |
| void                | **[toBack](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)**() |
| void                | **[toFront](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)**() |
| QListIterator< T> & | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QList< T> &*container*) |

## 详细说明

[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)两者都有[Java-style iterators](https://doc-qt-io.translate.goog/qt-6/java-style-iterators.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#java-style-iterators)和[STL-style iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)。STL 风格的迭代器效率更高，应该是首选。

使用迭代器的另一种方法是使用索引位置。最多[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)成员函数将索引作为其第一个参数，从而可以在不使用迭代器的情况下访问、修改和删除项目。

QListIterator< T> 允许您迭代[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T>，一个[QQueue](https://doc-qt-io.translate.goog/qt-6/qqueue.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> 或[QStack](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T>。如果您想在迭代列表时修改列表，请使用[QMutableListIterator](https://doc-qt-io.translate.goog/qt-6/qmutablelistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> 代替。

QListIterator 构造函数采用[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为论证。构造后，迭代器位于列表的最开头（第一项之前）。以下是按顺序迭代所有元素的方法：

```
QList<float> list;
...
QListIterator<float> i(list);
while (i.hasNext())
    float f = i.next();
```

这[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 函数返回列表中的下一项并推进迭代器。与 STL 样式的迭代器不同，Java 样式的迭代器指向项*之间*而不是直接*指向*项。第一次致电[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 将迭代器前进到第一项和第二项之间的位置，并返回第一项；第二次致电[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 将迭代器前进到第二项和第三项之间的位置，并返回第二项；等等。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\L\QListIterator(Java Style)\QListIterator\javaiterators1.png)

以下是如何以相反的顺序迭代元素：

```
QListIterator<float> i(list);
i.toBack();
while (i.hasPrevious())
    float f = i.previous();
```

如果您想查找特定值的所有出现位置，请使用[findNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)（） 或者[findPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)() 循环中。

可以在同一个列表上使用多个迭代器。如果在 QListIterator 处于活动状态时修改列表，则 QListIterator 将继续迭代原始列表，忽略修改后的副本。

**也可以看看**[QMutableListIterator](https://doc-qt-io.translate.goog/qt-6/qmutablelistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QListIterator::QListIterator(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> &*list*)

构造一个迭代器用于遍历*list*。迭代器设置为位于列表的前面（第一项之前）。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### [QListIterator](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListIterator)< T> &QListIterator::operator=(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> &*container*)

使迭代器运行*list*。迭代器设置为位于列表的前面（第一项之前）。

**也可以看看**[toFront](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)（） 和[toBack](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)()。

### void QListIterator::toFront()

将迭代器移动到容器的前面（第一项之前）。

**也可以看看**[toBack](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)（） 和[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### void QListIterator::toBack()

将迭代器移动到容器的后面（最后一项之后）。

**也可以看看**[toFront](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)（） 和[previous](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### bool QListIterator::hasNext() const

`true`如果迭代器前面至少有一项，即迭代器不在*容器*的后面，则返回；否则返回`false`.

**也可以看看**[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)（） 和[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### const T &QListIterator::next()

返回下一项并将迭代器前进一个位置。

在位于容器后面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)(),[peekNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)（）， 和[previous](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### const T &QListIterator::peekNext() const

返回下一项而不移动迭代器。

在位于容器后面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)(),[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)（）， 和[peekPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekPrevious)()。

### bool QListIterator::hasPrevious() const

`true`如果迭代器后面至少有一项，即迭代器不在*容器*的前面，则返回；否则返回`false`.

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)（） 和[previous](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### const T &QListIterator::previous()

返回前一项并将迭代器向后移动一个位置。

在位于容器前面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)(),[peekPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekPrevious)（）， 和[next](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### const T &QListIterator::peekPrevious() const

返回前一项而不移动迭代器。

在位于容器前面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)(),[previous](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)（）， 和[peekNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)()。

### bool QListIterator::findNext(const T &*value*)

搜索次数*value*从当前迭代器位置开始向前。返回`true`如果*value*被发现；否则返回`false`.

通话结束后，如果*value*找到后，迭代器就位于匹配项之后；否则，迭代器位于容器的后面。

**也可以看看**[findPrevious](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)()。

### bool QListIterator::findPrevious(const T &*value*)

搜索次数*value*从当前迭代器位置向后开始。返回`true`如果*value*被发现；否则返回 false。

通话结束后，如果*value*找到后，迭代器就位于匹配项之前；否则，迭代器位于容器的前面。

**也可以看看**[findNext](https://doc-qt-io.translate.goog/qt-6/qlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)()。
