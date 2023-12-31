# QLinkedList Class

template < typename T > class QLinkedList

QLinkedList类是一个提供链表的模板类。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include <QLinkedList>                                       |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core5Compat) target_link_libraries(mytarget PRIVATE Qt6::Core5Compat) |
| qmake:  | QT += core5compat                                            |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QLinkedList 是[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
| class | **[iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
|       | **[ConstIterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ConstIterator-typedef)** |
|       | **[Iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Iterator-typedef)** |
|       | **[const_pointer](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_pointer-typedef)** |
|       | **[const_reference](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reference-typedef)** |
|       | **[const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef)** |
|       | **[difference_type](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#difference_type-typedef)** |
|       | **[pointer](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pointer-typedef)** |
|       | **[reference](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reference-typedef)** |
|       | **[reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reverse_iterator-typedef)** |
|       | **[size_type](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef)** |
|       | **[value_type](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value_type-typedef)** |

## 公共职能

|                                     | **[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)**() |
| ----------------------------------- | ------------------------------------------------------------ |
|                                     | **[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList-1)**(const QLinkedList<  T >  &*other*) |
|                                     | **[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList-2)**(std::initializer_list<  T >  *list*) |
|                                     | **[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList-3)**(InputIterator *first*, InputIterator *last*) |
|                                     | **[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList-4)**(QLinkedList<  T >  &&*other*) |
|                                     | **[~QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QLinkedList)**() |
| void                                | **[append](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)**(const T &*value*) |
| T &                                 | **[back](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#back)**() |
| const T &                           | **[back](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#back-1)**() const |
| QLinkedList::iterator               | **[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() |
| QLinkedList::const_iterator         | **[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin-1)**() const |
| QLinkedList::const_iterator         | **[cbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)**() const |
| QLinkedList::const_iterator         | **[cend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)**() const |
| void                                | **[clear](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| QLinkedList::const_iterator         | **[constBegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)**() const |
| QLinkedList::const_iterator         | **[constEnd](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)**() const |
| bool                                | **[contains](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)**(const T &*value*) const |
| int                                 | **[count](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**(const T &*value*) const |
| int                                 | **[count](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)**() const |
| QLinkedList::const_reverse_iterator | **[crbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crbegin)**() const |
| QLinkedList::const_reverse_iterator | **[crend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crend)**() const |
| bool                                | **[empty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#empty)**() const |
| QLinkedList::iterator               | **[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() |
| QLinkedList::const_iterator         | **[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end-1)**() const |
| bool                                | **[endsWith](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endsWith)**(const T &*value*) const |
| QLinkedList::iterator               | **[erase](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)**(QLinkedList::iterator *pos*) |
| QLinkedList::iterator               | **[erase](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase-1)**(QLinkedList::iterator *begin*, QLinkedList::iterator *end*) |
| T &                                 | **[first](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)**() |
| const T &                           | **[first](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first-1)**() const |
| T &                                 | **[front](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#front)**() |
| const T &                           | **[front](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#front-1)**() const |
| QLinkedList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)**(QLinkedList::iterator *before*, const T &*value*) |
| bool                                | **[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)**() const |
| T &                                 | **[last](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)**() |
| const T &                           | **[last](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last-1)**() const |
| void                                | **[pop_back](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop_back)**() |
| void                                | **[pop_front](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop_front)**() |
| void                                | **[prepend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)**(const T &*value*) |
| void                                | **[push_back](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push_back)**(const T &*value*) |
| void                                | **[push_front](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push_front)**(const T &*value*) |
| QLinkedList::reverse_iterator       | **[rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)**() |
| QLinkedList::const_reverse_iterator | **[rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin-1)**() const |
| int                                 | **[removeAll](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)**(const T &*value*) |
| void                                | **[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)**() |
| void                                | **[removeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)**() |
| bool                                | **[removeOne](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeOne)**(const T &*value*) |
| QLinkedList::reverse_iterator       | **[rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)**() |
| QLinkedList::const_reverse_iterator | **[rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend-1)**() const |
| int                                 | **[size](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)**() const |
| bool                                | **[startsWith](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startsWith)**(const T &*value*) const |
| void                                | **[swap](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QLinkedList<  T >  &*other*) |
| T                                   | **[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)**() |
| T                                   | **[takeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)**() |
| std::list<  T >                     | **[toStdList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toStdList)**() const |
| bool                                | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QLinkedList<  T >  &*other*) const |
| QLinkedList<  T >                   | **[operator+](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)**(const QLinkedList<  T >  &*other*) const |
| QLinkedList<  T >  &                | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)**(const QLinkedList<  T >  &*other*) |
| QLinkedList<  T >  &                | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq-1)**(const T &*value*) |
| QLinkedList<  T >  &                | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(const QLinkedList<  T >  &*other*) |
| QLinkedList<  T >  &                | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-1)**(const T &*value*) |
| QLinkedList<  T >  &                | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QLinkedList<  T >  &*other*) |
| bool                                | **[operator==](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QLinkedList<  T >  &*other*) const |

## 静态公共成员

| QLinkedList<  T > | **[fromStdList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromStdList)**(const std::list<  T >  &*list*) |
| ----------------- | ------------------------------------------------------------ |
|                   |                                                              |

## 相关非成员

| QDataStreamIfHasOStreamOperatorsContainer<QLinkedList<  T > , T> | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-2)**(QDataStream &*out*, const QLinkedList<  T >  &*list*) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| QDataStreamIfHasIStreamOperatorsContainer<QLinkedList<  T > , T> | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*in*, QLinkedList<  T >  &*list*) |

## 详细说明

QLinkedList<  T >  是 Qt 的泛型之一[container classes](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它存储值列表并提供基于迭代器的访问以及[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)插入和删除。

[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T >  和 QLinkedList<  T >  提供类似的功能。概述如下：

- 对于大多数目的来说，[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)是正确使用的类。它基于索引的API比QLinkedList基于迭代器的API更方便。它的项目占据相邻的内存位置。它还可以扩展到可执行文件中更少的代码。
- 如果您需要一个真实的链表，并保证[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)在列表中间插入以及对项目而不是索引的迭代器，请使用 QLinkedList。

下面是一个存储整数的 QLinkedList 和一个存储整数的 QLinkedList 的示例[QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值观：

```
QLinkedList<int> integerList;
QLinkedList<QTime> timeList;
```

QLinkedList 存储项目列表。默认构造函数创建一个空列表。要将项目插入列表中，可以使用运算符<<()：

```
QLinkedList<QString> list;
list << "one" << "two" << "three";
// list: ["one", "two", "three"]
```

如果您想获取链接列表中的第一项或最后一项，请使用[first](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)（） 或者[last](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。如果要从列表的任一端删除项目，请使用[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)（） 或者[removeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)()。如果要删除列表中给定值的所有出现，请使用[removeAll](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)()。

一个常见的要求是删除列表中的第一个或最后一个项目并对其执行某些操作。为此，QLinkedList提供了[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)（） 和[takeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)()。这是一个循环，一次从列表中删除一个项目并调用`delete`它们：

```
QLinkedList<QWidget *> list;
...
while (!list.isEmpty())
    delete list.takeFirst();
```

QLinkedList 的值类型必须是[assignable data type](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#assignable-data-type)。这涵盖了大多数常用的数据类型，但是编译器不允许您将 QWidget 存储为值；相反，存储一个 QWidget *。一些功能有额外的要求；例如，[contains](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[removeAll](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)() 期望值类型支持`operator==()`。这些要求是按功能记录的。

如果要在列表中间插入、修改或删除项目，则必须使用迭代器。QLinkedList 两者都提供[Java-style iterators](https://doc-qt-io.translate.goog/qt-6/java-style-iterators.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#java-style-iterators)（[QLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QMutableLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qmutablelinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)） 和[STL-style iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)（[QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。有关详细信息，请参阅这些类的文档。

**也可以看看**[QLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QMutableLinkedListIterator](https://doc-qt-io.translate.goog/qt-6/qmutablelinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### QLinkedList::ConstIterator

Qt 风格的同义词[QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QLinkedList::Iterator

Qt 风格的同义词[QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QLinkedList::const_pointer

const T * 的类型定义。提供 STL 兼容性。

### QLinkedList::const_reference

const T & 的 Typedef。提供 STL 兼容性。

### QLinkedList::const_reverse_iterator

QLinkedList::const_reverse_iterator typedef 提供了一个 STL 风格的 const 反向迭代器[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

它只是 的 typedef `std::reverse_iterator<QLinkedList::const_iterator>`。

**警告：**隐式共享容器上的迭代器的工作方式与 STL 迭代器不同。当迭代器在容器上处于活动状态时，您应该避免复制该容器。欲了解更多信息，请阅读[Implicit sharing iterator problem](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#implicit-sharing-iterator-problem)。

**也可以看看**[QLinkedList::rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)(),[QLinkedList::rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)(),[QLinkedList::reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reverse_iterator-typedef)， 和[QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QLinkedList::difference_type

ptrdiff_t 的类型定义。提供 STL 兼容性。

### QLinkedList::pointer

T * 的类型定义。提供 STL 兼容性。

### QLinkedList::reference

T & 的类型定义。提供 STL 兼容性。

### QLinkedList::reverse_iterator

QLinkedList::reverse_iterator typedef 提供了一个 STL 风格的非常量反向迭代器[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

它只是 的 typedef `std::reverse_iterator<QLinkedList::iterator>`。

**警告：**隐式共享容器上的迭代器的工作方式与 STL 迭代器不同。当迭代器在容器上处于活动状态时，您应该避免复制该容器。欲了解更多信息，请阅读[Implicit sharing iterator problem](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#implicit-sharing-iterator-problem)。

**也可以看看**[QLinkedList::rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)(),[QLinkedList::rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)(),[QLinkedList::const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef)， 和[QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QLinkedList::size_type

typedef 为 int。提供 STL 兼容性。

### QLinkedList::value_type

T 的 Typedef。为 STL 兼容性而提供。

## 成员函数文档

### QLinkedList::QLinkedList()

构造一个空列表。

### QLinkedList::QLinkedList(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*)

构造一个副本*other*。

此操作发生在[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)，因为 QLinkedList 是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这使得从函数返回 QLinkedList 的速度非常快。如果共享实例被修改，它将被复制（写时复制），这需要[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### QLinkedList::QLinkedList(std::initializer_list<  T >  *list*)

从 std::initializer_list 指定的构造列表*list*。

仅当编译器支持 C++11 初始值设定项列表时才启用此构造函数。

### template < typename InputIterator> QLinkedList::QLinkedList(InputIterator *first*, InputIterator *last*)

使用迭代器范围 [ 中的内容构造一个列表*first*,*last*）。

的值类型`InputIterator`必须可转换为`T`。

### QLinkedList::QLinkedList([QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &&*other*)

移动构造一个 QLinkedList 实例，使其指向与*other*正在指着。

### QLinkedList::~QLinkedList()

销毁列表。对该列表中的值以及该列表上的所有迭代器的引用都将变得无效。

### void QLinkedList::append(const T &*value*)

刀片*value*在列表的末尾。

例子：

```
QLinkedList<QString> list;
list.append("one");
list.append("two");
list.append("three");
// list: ["one", "two", "three"]
```

这与 list.insert( 相同[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)(),*value*）。

**也可以看看**[operator<<](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)(),[prepend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)（）， 和[insert](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### T &QLinkedList::back()

提供此函数是为了兼容 STL。它相当于[last](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### const T &QLinkedList::back() const

这是一个过载功能。

### [QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::begin()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中的第一项。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::begin() const

这是一个过载功能。

### [QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::cbegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[cend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)()。

### [QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::cend() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中最后一项之后的虚构项。

**也可以看看**[cbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### void QLinkedList::clear()

删除列表中的所有项目。

**也可以看看**[removeAll](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)()。

### [QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::constBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::constEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中最后一项之后的虚构项。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### bool QLinkedList::contains(const T &*value*) const

`true`如果列表包含出现则返回*value*; 否则返回`false`.

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[QLinkedListIterator::findNext](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findNext)（） 和[QLinkedListIterator::findPrevious](https://doc-qt-io.translate.goog/qt-6/qlinkedlistiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findPrevious)()。

### int QLinkedList::count(const T &*value*) const

返回出现的次数*value*在列表中。

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[contains](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()。

### int QLinkedList::count() const

与...一样[size](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### [QLinkedList::const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef) QLinkedList::crbegin() const

返回一个常量[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),[rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)（）， 和[rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)()。

### [QLinkedList::const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef) QLinkedList::crend() const

返回一个常量[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中最后一项。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)(),[rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)（）， 和[rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)()。

### bool QLinkedList::empty() const

提供此函数是为了兼容 STL。它相当于[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)`true`() ，如果列表为空则返回。

### [QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::end()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中最后一项之后的虚构项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QLinkedList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::end() const

这是一个过载功能。

### bool QLinkedList::endsWith(const T &*value*) const

如果列表`true`不为空且其最后一项等于*value*; 否则返回`false`.

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[last](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### [QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::erase([QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *pos*)

删除迭代器指向的项*pos*从列表中，并返回一个迭代器到列表中的下一个项目（可能是[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)())。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### [QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::erase([QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *begin*, [QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *end*)

这是一个过载功能。

从中删除所有项目*begin*最多（但不包括）*end*。

### T &QLinkedList::first()

返回对列表中第一项的引用。该函数假设列表不为空。

**也可以看看**[last](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)（） 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### const T &QLinkedList::first() const

这是一个过载功能。

### `[static]`[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  QLinkedList::fromStdList(const std::list<  T >  &*list*)

返回一个[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)包含数据的对象*list*。中元素的顺序[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与中相同*list*。

例子：

```
std::list<double> stdlist;
list.push_back(1.2);
list.push_back(0.5);
list.push_back(3.14);

QLinkedList<double> list = QLinkedList<double>::fromStdList(stdlist);
```

**也可以看看**[toStdList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toStdList)()。

### T &QLinkedList::front()

提供此函数是为了兼容 STL。它相当于[first](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)()。

### const T &QLinkedList::front() const

这是一个过载功能。

### [QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLinkedList::insert([QLinkedList::iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *before*, const T &*value*)

刀片*value*在迭代器指向的项前面*before*。返回一个指向插入项的迭代器。

**也可以看看**[erase](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)()。

### bool QLinkedList::isEmpty() const

`true`如果列表不包含任何项目则返回；否则返回 false。

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### T &QLinkedList::last()

返回对列表中最后一项的引用。该函数假设列表不为空。

**也可以看看**[first](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)（） 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### const T &QLinkedList::last() const

这是一个过载功能。

### void QLinkedList::pop_back()

提供此函数是为了兼容 STL。它相当于[removeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)()。

### void QLinkedList::pop_front()

提供此函数是为了兼容 STL。它相当于[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)()。

### void QLinkedList::prepend(const T &*value*)

刀片*value*在列表的开头。

例子：

```
QLinkedList<QString> list;
list.prepend("one");
list.prepend("two");
list.prepend("three");
// list: ["three", "two", "one"]
```

这与 list.insert( 相同[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),*value*）。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 和[insert](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### void QLinkedList::push_back(const T &*value*)

提供此函数是为了兼容 STL。它相当于附加（*value*）。

### void QLinkedList::push_front(const T &*value*)

提供此函数是为了兼容 STL。它相当于前置(*value*）。

### [QLinkedList::reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reverse_iterator-typedef) QLinkedList::rbegin()

返回一个[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),[crbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crbegin)（）， 和[rend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)()。

### [QLinkedList::const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef) QLinkedList::rbegin() const

这是一个过载功能。

### int QLinkedList::removeAll(const T &*value*)

删除所有出现的*value*在列表中。

例子：

```
QList<QString> list;
list << "sun" << "cloud" << "sun" << "rain";
list.removeAll("sun");
// list: ["cloud", "rain"]
```

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### void QLinkedList::removeFirst()

删除列表中的第一项。

这与擦除相同（[begin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)())。

**也可以看看**[removeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)（） 和[erase](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)()。

### void QLinkedList::removeLast()

删除列表中的最后一项。

**也可以看看**[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)（） 和[erase](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)()。

### bool QLinkedList::removeOne(const T &*value*)

删除第一次出现的*value*在列表中。`true`成功回报；否则返回`false`.

例子：

```
QList<QString> list;
list << "sun" << "cloud" << "sun" << "rain";
list.removeOne("sun");
// list: ["cloud", "sun", "rain"]
```

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### [QLinkedList::reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reverse_iterator-typedef) QLinkedList::rend()

返回一个[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中最后一项。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)(),[crend](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crend)（）， 和[rbegin](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)()。

### [QLinkedList::const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef) QLinkedList::rend() const

这是一个过载功能。

### int QLinkedList::size() const

返回列表中的项目数。

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[count](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)()。

### bool QLinkedList::startsWith(const T &*value*) const

如果列表`true`不为空且其第一项等于*value*; 否则返回`false`.

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[first](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)()。

### void QLinkedList::swap([QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*)

掉期清单*other*有了这个清单。这个操作非常快并且永远不会失败。

### T QLinkedList::takeFirst()

删除列表中的第一项并将其返回。

如果不使用返回值，[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)() 效率更高。

**也可以看看**[takeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)（） 和[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)()。

### T QLinkedList::takeLast()

删除列表中的最后一项并将其返回。

如果不使用返回值，[removeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)() 效率更高。

**也可以看看**[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)（） 和[removeLast](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)()。

### std::list<  T >  QLinkedList::toStdList() const

返回一个 std::list 对象，其中包含此对象中包含的数据[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。例子：

```
QLinkedList<double> list;
list << 1.2 << 0.5 << 3.14;

std::list<double> stdlist = list.toStdList();
```

**也可以看看**[fromStdList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromStdList)()。

### bool QLinkedList::operator!=(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*) const

返回`true`如果*other*不等于此列表；否则返回`false`.

如果两个列表包含相同顺序的相同值，则认为它们相等。

该函数需要值类型来实现`operator==()`。

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  QLinkedList::operator+(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*) const

返回一个列表，其中包含此列表中的所有项目，后跟*other*列表。

**也可以看看**[operator+=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &QLinkedList::operator+=(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*)

追加以下项目*other*list 到此列表并返回对此列表的引用。

**也可以看看**[operator+](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)（） 和[append](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)()。

### [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &QLinkedList::operator+=(const T &*value*)

这是一个过载功能。

追加*value*到列表中。

### [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &QLinkedList::operator<<(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*)

追加以下项目*other*list 到此列表并返回对此列表的引用。

**也可以看看**[operator+=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)（） 和[append](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)()。

### [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &QLinkedList::operator<<(const T &*value*)

这是一个过载功能。

追加*value*到列表中。

### [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &QLinkedList::operator=(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*)

分配*other*到此列表并返回对此列表的引用。

### bool QLinkedList::operator==(const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*other*) const

返回`true`如果*other*等于这个列表；否则返回 false。

如果两个列表包含相同顺序的相同值，则认为它们相等。

该函数需要值类型来实现`operator==()`。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

## 相关非成员

### template < typename T > QDataStreamIfHasOStreamOperatorsContainer<[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T > , T> operator<<([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*out*, const [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*list*)

写入链表*list*流式传输*out*。

该函数需要值类型来实现`operator<<()`。

**也可以看看**[Format of the QDataStream operators](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template < typename T > QDataStreamIfHasIStreamOperatorsContainer<[QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T > , T> operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*in*, [QLinkedList](https://doc-qt-io.translate.goog/qt-6/qlinkedlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLinkedList)<  T >  &*list*)

从流中读取链表*in*进入*list*。

该函数需要值类型来实现`operator>>()`。

**也可以看看**[Format of the QDataStream operators](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。
