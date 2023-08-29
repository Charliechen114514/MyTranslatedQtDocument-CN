# QHashIterator Class

template <typename Key, typename T> class QHashIterator

The QHashIterator class provides a Java-style const iterator for [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash) and [QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp). [More...](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include <QHashIterator>                                     |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:  | QT += core                                                   |

- [List of all members, including inherited members](https://doc-qt-io.translate.goog/qt-6/qhashiterator-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## Public Functions

|                         | **[QHashIterator](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHashIterator)**(const QHash<Key, T> &*hash*) |
| ----------------------- | ------------------------------------------------------------ |
| bool                    | **[findNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)**(const T &*value*) |
| bool                    | **[hasNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)**() const |
| const Key &             | **[key](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)**() const |
| QHashIterator::Item     | **[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)**() |
| QHashIterator::Item     | **[peekNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)**() const |
| void                    | **[toBack](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)**() |
| void                    | **[toFront](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)**() |
| const T &               | **[value](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)**() const |
| QHashIterator<Key, T> & | **[operator=](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QHash<Key, T> &*container*) |

## Detailed Description

[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash) has both [Java-style iterators](https://doc-qt-io.translate.goog/qt-6/java-style-iterators.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#java-style-iterators) and [STL-style iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators). STL-style iterators are more efficient and should be preferred.

QHashIterator<Key, T> allows you to iterate over a [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash) (or a [QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)). If you want to modify the hash as you iterate over it, use [QMutableHashIterator](https://doc-qt-io.translate.goog/qt-6/qmutablehashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) instead.

The QHashIterator constructor takes a [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash) as argument. After construction, the iterator is located at the very beginning of the hash (before the first item). Here's how to iterate over all the elements sequentially:

```
QHash<int, QWidget *> hash;
...
QHashIterator<int, QWidget *> i(hash);
while (i.hasNext()) {
    i.next();
    qDebug() << i.key() << ": " << i.value();
}
```

The [next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 函数返回哈希中的下一项并推进迭代器。这[key](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)() 函数返回最后被跳过的项目的键和值。

与 STL 样式的迭代器不同，Java 样式的迭代器指向项*之间*而不是直接*指向*项。第一次致电[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 将迭代器前进到第一项和第二项之间的位置，并返回第一项；第二次致电[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)() 将迭代器前进到第二项和第三项之间的位置；等等。

![img](https://doc.qt.io/qt-6/images/javaiterators1.png)

如果您想查找特定值的所有出现位置，请使用[findNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)() 循环中。例如：

```
QHashIterator<int, QWidget *> i(hash);
while (i.findNext(widget)) {
    qDebug() << "Found widget " << widget << " under key "
             << i.key();
}
```

可以在同一个哈希上使用多个迭代器。如果在 QHashIterator 处于活动状态时修改哈希值，则 QHashIterator 将继续迭代原始哈希值，忽略修改后的副本。

**也可以看看**[QMutableHashIterator](https://doc-qt-io.translate.goog/qt-6/qmutablehashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QHashIterator::QHashIterator(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<Key, T> &*hash*)

构造一个迭代器用于遍历*hash*。迭代器设置为位于哈希的前面（第一项之前）。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### [QHashIterator](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHashIterator)<Key, T> &QHashIterator::operator=(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<Key, T> &*container*)

使迭代器运行*hash*。迭代器设置为位于哈希的前面（第一项之前）。

**也可以看看**[toFront](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)（） 和[toBack](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)()。

### void QHashIterator::toFront()

将迭代器移动到容器的前面（第一项之前）。

**也可以看看**[toBack](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toBack)（） 和[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### void QHashIterator::toBack()

将迭代器移动到容器的后面（最后一项之后）。

**也可以看看**[toFront](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toFront)()。

### bool QHashIterator::hasNext() const

`true`如果迭代器前面至少有一项，即迭代器不在*容器*的后面，则返回；否则返回`false`.

**也可以看看**[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### const Key &QHashIterator::key() const

返回使用遍历函数之一跳过的最后一项的键（[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)(),[findNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)())。

**也可以看看**[value](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

### bool QHashIterator::findNext(const T &*value*)

搜索次数*value*从当前迭代器位置开始向前。返回`true`（键，值）对是否具有值*value*被发现；否则返回`false`.

通话结束后，如果*value*找到后，迭代器就位于匹配项之后；否则，迭代器位于容器的后面。

### QHashIterator::Item QHashIterator::next()

返回下一项并将迭代器前进一个位置。

称呼[key](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)() 返回值来获取项目的键，以及[value](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)() 来获取值。

在位于容器后面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)（） 和[peekNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#peekNext)()。

### QHashIterator::Item QHashIterator::peekNext() const

返回下一项而不移动迭代器。

称呼[key](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)() 返回值来获取项目的键，以及[value](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)() 来获取值。

在位于容器后面的迭代器上调用此函数会导致未定义的结果。

**也可以看看**[hasNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasNext)（） 和[next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)()。

### const T &QHashIterator::value() const

返回使用遍历函数之一跳过的最后一项的值 ([next](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)(),[findNext](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)())。

**也可以看看**[key](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)()。