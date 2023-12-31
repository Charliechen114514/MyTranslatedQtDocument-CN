# QLinkedListIterator Class

template < typename T> class QLinkedListIterator

QLinkedListIterator 类提供了一个 Java 风格的常量迭代器[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include < QLinkedListIterator>                              |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core5Compat) target_link_libraries(mytarget PRIVATE Qt6::Core5Compat) |
| qmake:  | QT += core5compat                                            |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共职能

|                           | **[QLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedListIterator)**(const QLinkedList< T> &*list*) |
| ------------------------- | ------------------------------------------------------------ |
| bool                      | **[findNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)**(const T &*value*) |
| bool                      | **[findPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)**(const T &*value*) |
| bool                      | **[hasNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)**() const |
| bool                      | **[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)**() const |
| const T &                 | **[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)**() |
| const T &                 | **[peekNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)**() const |
| const T &                 | **[peekPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekPrevious)**() const |
| const T &                 | **[previous](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)**() |
| void                      | **[toBack](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)**() |
| void                      | **[toFront](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)**() |
| QLinkedListIterator< T> & | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QLinkedList< T> &*container*) |

## 详细说明

[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)两者都有[Java-style iterators](https://doc-qt-io.translate.goog/qt-6/java-style-iterators.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#java-style-iterators)和[STL-style iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)。Java风格的迭代器比STL风格的迭代器更高级并且更容易使用；另一方面，它们的效率稍低。

QLinkedListIterator< T> 允许您迭代[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T>。如果您想在迭代列表时修改列表，请使用[QMutableLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qmutablelinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> 代替。

QLinkedListIterator 构造函数采用[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为论证。构造后，迭代器位于列表的最开头（第一项之前）。以下是按顺序迭代所有元素的方法：

```
QLinkedList<float> list;
...
QLinkedListIterator<float> i(list);
while (i.hasNext())
    qDebug() << i.next();
```

这[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 函数返回列表中的下一项并推进迭代器。与 STL 样式的迭代器不同，Java 样式的迭代器指向项*之间*而不是直接*指向*项。第一次致电[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 将迭代器前进到第一项和第二项之间的位置，并返回第一项；第二次致电[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 将迭代器前进到第二项和第三项之间的位置，并返回第二项；等等。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\L\QLinkedListIterator(Java Style)\QLinkedListIterator\javaiterators1.png)

以下是如何以相反的顺序迭代元素：

```
QLinkedListIterator<float> i(list);
i.toBack();
while (i.hasPrevious())
    qDebug() << i.previous();
```

如果您想查找特定值的所有出现位置，请使用[findNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)（） 或者[findPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)() 循环中。

可以在同一个列表上使用多个迭代器。如果在 QLinkedListIterator 处于活动状态时修改列表，则 QLinkedListIterator 将继续迭代原始列表，忽略修改后的副本。

**也可以看看**[QMutableLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qmutablelinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QLinkedListIterator::QLinkedListIterator(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> &*list*)

构造一个迭代器用于遍历*list*。迭代器设置为位于列表的前面（第一项之前）。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### [QLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedListIterator)< T> &QLinkedListIterator::operator=(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> &*container*)

使迭代器运行*list*。迭代器设置为位于列表的前面（第一项之前）。

**也可以看看**[toFront](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)（） 和[toBack](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)()。

### void QLinkedListIterator::toFront()

将迭代器移动到容器的前面（第一项之前）。

**也可以看看**[toBack](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)（） 和[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### void QLinkedListIterator::toBack()

将迭代器移动到容器的后面（最后一项之后）。

**也可以看看**[toFront](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)（） 和[previous](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### bool QLinkedListIterator::hasNext() const

`true`如果迭代器前面至少有一项，即迭代器不在*容器*的后面，则返回；否则返回`false`.

**也可以看看**[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)（） 和[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### bool QLinkedListIterator::hasPrevious() const

`true`如果迭代器后面至少有一项，即迭代器不在*容器*的前面，则返回；否则返回`false`.

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)（） 和[previous](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### bool QLinkedListIterator::findNext(const T &*value*)

搜索次数*value*从当前迭代器位置开始向前。返回`true`如果*value*被发现；否则返回`false`.

通话结束后，如果*value*找到后，迭代器就位于匹配项之后；否则，迭代器位于容器的后面。

**也可以看看**[findPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)()。

### bool QLinkedListIterator::findPrevious(const T &*value*)

搜索次数*value*从当前迭代器位置向后开始。返回`true`如果*value*被发现；否则返回 false。

通话结束后，如果*value*找到后，迭代器就位于匹配项之前；否则，迭代器位于容器的前面。

**也可以看看**[findNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)()。

### const T &QLinkedListIterator::next()

返回下一项并将迭代器前进一个位置。

在位于容器后面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)(),[peekNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)（）， 和[previous](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### const T &QLinkedListIterator::peekNext() const

返回下一项而不移动迭代器。

在位于容器后面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)(),[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)（）， 和[peekPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekPrevious)()。

### const T &QLinkedListIterator::peekPrevious() const

返回前一项而不移动迭代器。

在位于容器前面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)(),[previous](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)（）， 和[peekNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)()。

### const T &QLinkedListIterator::previous()

返回前一项并将迭代器向后移动一个位置。

在位于容器前面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasPrevious)(),[peekPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekPrevious)（）， 和[next](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。
