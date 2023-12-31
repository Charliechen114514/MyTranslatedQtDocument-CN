# QList Class

template < typename T> class QList

QList类是一个提供动态数组的模板类。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QList>                                            |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:        | QT += core                                                   |
| Inherited By: | [QBluetoothServiceInfo::Alternative](https://doc-qt-io.translate.goog/qt-6/qbluetoothserviceinfo-alternative.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QBluetoothServiceInfo::Sequence](https://doc-qt-io.translate.goog/qt-6/qbluetoothserviceinfo-sequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QByteArrayList](https://doc-qt-io.translate.goog/qt-6/qbytearraylist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QMqttUserProperties](https://doc-qt-io.translate.goog/qt-6/qmqttuserproperties.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QNdefMessage](https://doc-qt-io.translate.goog/qt-6/qndefmessage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QQueue](https://doc-qt-io.translate.goog/qt-6/qqueue.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QSignalSpy](https://doc-qt-io.translate.goog/qt-6/qsignalspy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QStack](https://doc-qt-io.translate.goog/qt-6/qstack.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QTestEventList](https://doc-qt-io.translate.goog/qt-6/qtesteventlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QVector](https://doc-qt-io.translate.goog/qt-6/qvector.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QVulkanInfoVector](https://doc-qt-io.translate.goog/qt-6/qvulkaninfovector.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QXmlStreamAttributes](https://doc-qt-io.translate.goog/qt-6/qxmlstreamattributes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlist-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qlist-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QList 是[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
| class | **[iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
|       | **[ConstIterator](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ConstIterator-typedef)** |
|       | **[Iterator](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Iterator-typedef)** |
|       | **[const_pointer](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_pointer-typedef)** |
|       | **[const_reference](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reference-typedef)** |
|       | **[const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef)** |
|       | **[difference_type](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#difference_type-typedef)** |
|       | **[parameter_type](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parameter_type-typedef)** |
|       | **[pointer](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pointer-typedef)** |
|       | **[reference](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reference-typedef)** |
|       | **[reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reverse_iterator-typedef)** |
|       | **[rvalue_ref](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rvalue_ref-typedef)** |
|       | **[size_type](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef)** |
|       | **[value_type](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value_type-typedef)** |

## 公共职能

|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-1)**() |
| ----------------------------- | ------------------------------------------------------------ |
|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-2)**(qsizetype *size*) |
|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-3)**(qsizetype *size*, QList::parameter_type *value*) |
|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-4)**(std::initializer_list< T> *args*) |
|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-5)**(InputIterator *first*, InputIterator *last*) |
|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-7)**(QList< T> &&*other*) |
|                               | **[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QList-8)**(const QList< T> &*other*) |
|                               | **[~QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QList)**() |
| void                          | **[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)**(QList::parameter_type *value*) |
| void                          | **[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append-2)**(QList::rvalue_ref *value*) |
| void                          | **[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append-3)**(const QList< T> &*value*) |
| void                          | **[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append-4)**(QList< T> &&*value*) |
| QList::const_reference        | **[at](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#at)**(qsizetype *i*) const |
| QList::reference              | **[back](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#back)**() |
| QList::const_reference        | **[back](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#back-1)**() const |
| QList::iterator               | **[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() |
| QList::const_iterator         | **[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin-1)**() const |
| qsizetype                     | **[capacity](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)**() const |
| QList::const_iterator         | **[cbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)**() const |
| QList::const_iterator         | **[cend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)**() const |
| void                          | **[clear](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| QList::const_iterator         | **[constBegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)**() const |
| QList::const_pointer          | **[constData](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constData)**() const |
| QList::const_iterator         | **[constEnd](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)**() const |
| const T &                     | **[constFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFirst)**() const |
| const T &                     | **[constLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constLast)**() const |
| bool                          | **[contains](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)**(const AT &*value*) const |
| qsizetype                     | **[count](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**(const AT &*value*) const |
| qsizetype                     | **[count](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)**() const |
| QList::const_reverse_iterator | **[crbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crbegin)**() const |
| QList::const_reverse_iterator | **[crend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crend)**() const |
| QList::pointer                | **[data](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)**() |
| QList::const_pointer          | **[data](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data-1)**() const |
| QList::iterator               | **[emplace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplace)**(qsizetype *i*, Args &&... *args*) |
| QList::iterator               | **[emplace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplace-1)**(QList::const_iterator *before*, Args &&... *args*) |
| QList::reference              | **[emplaceBack](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplaceBack)**(Args &&... *args*) |
| QList::reference              | **[emplace_back](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplace_back)**(Args &&... *args*) |
| bool                          | **[empty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#empty)**() const |
| QList::iterator               | **[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() |
| QList::const_iterator         | **[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end-1)**() const |
| bool                          | **[endsWith](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endsWith)**(QList::parameter_type *value*) const |
| QList::iterator               | **[erase](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)**(QList::const_iterator *pos*) |
| QList::iterator               | **[erase](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase-1)**(QList::const_iterator *begin*, QList::const_iterator *end*) |
| QList< T> &                   | **[fill](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fill)**(QList::parameter_type *value*, qsizetype *size* = -1) |
| T &                           | **[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)**() |
| const T &                     | **[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first-1)**() const |
| QList< T>                     | **[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first-2)**(qsizetype *n*) const |
| QList::reference              | **[front](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#front)**() |
| QList::const_reference        | **[front](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#front-1)**() const |
| qsizetype                     | **[indexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)**(const AT &*value*, qsizetype *from* = 0) const |
| QList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)**(qsizetype *i*, QList::parameter_type *value*) |
| QList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-1)**(qsizetype *i*, qsizetype *count*, QList::parameter_type *value*) |
| QList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-2)**(QList::const_iterator *before*, QList::parameter_type *value*) |
| QList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-3)**(QList::const_iterator *before*, qsizetype *count*, QList::parameter_type *value*) |
| QList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-4)**(QList::const_iterator *before*, QList::rvalue_ref *value*) |
| QList::iterator               | **[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-5)**(qsizetype *i*, QList::rvalue_ref *value*) |
| bool                          | **[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)**() const |
| T &                           | **[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)**() |
| const T &                     | **[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last-1)**() const |
| QList< T>                     | **[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last-2)**(qsizetype *n*) const |
| qsizetype                     | **[lastIndexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastIndexOf)**(const AT &*value*, qsizetype *from* = -1) const |
| qsizetype                     | **[length](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#length)**() const |
| QList< T>                     | **[mid](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mid)**(qsizetype *pos*, qsizetype *length* = -1) const |
| void                          | **[move](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#move)**(qsizetype *from*, qsizetype *to*) |
| void                          | **[pop_back](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop_back)**() |
| void                          | **[pop_front](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pop_front)**() |
| void                          | **[prepend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)**(QList::rvalue_ref *value*) |
| void                          | **[prepend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend-1)**(QList::parameter_type *value*) |
| void                          | **[push_back](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push_back)**(QList::parameter_type *value*) |
| void                          | **[push_back](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push_back-1)**(QList::rvalue_ref *value*) |
| void                          | **[push_front](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push_front)**(QList::rvalue_ref *value*) |
| void                          | **[push_front](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#push_front-1)**(QList::parameter_type *value*) |
| QList::reverse_iterator       | **[rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)**() |
| QList::const_reverse_iterator | **[rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin-1)**() const |
| void                          | **[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)**(qsizetype *i*, qsizetype *n* = 1) |
| qsizetype                     | **[removeAll](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)**(const AT &*t*) |
| void                          | **[removeAt](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAt)**(qsizetype *i*) |
| void                          | **[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)**() |
| qsizetype                     | **[removeIf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeIf)**(Predicate *pred*) |
| void                          | **[removeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)**() |
| bool                          | **[removeOne](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeOne)**(const AT &*t*) |
| QList::reverse_iterator       | **[rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)**() |
| QList::const_reverse_iterator | **[rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend-1)**() const |
| void                          | **[replace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)**(qsizetype *i*, QList::parameter_type *value*) |
| void                          | **[replace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace-1)**(qsizetype *i*, QList::rvalue_ref *value*) |
| void                          | **[reserve](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)**(qsizetype *size*) |
| void                          | **[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)**(qsizetype *size*) |
| void                          | **[shrink_to_fit](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shrink_to_fit)**() |
| qsizetype                     | **[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)**() const |
| QList< T>                     | **[sliced](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliced)**(qsizetype *pos*, qsizetype *n*) const |
| QList< T>                     | **[sliced](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliced-1)**(qsizetype *pos*) const |
| void                          | **[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)**() |
| bool                          | **[startsWith](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startsWith)**(QList::parameter_type *value*) const |
| void                          | **[swap](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QList< T> &*other*) |
| void                          | **[swapItemsAt](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swapItemsAt)**(qsizetype *i*, qsizetype *j*) |
| T                             | **[takeAt](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeAt)**(qsizetype *i*) |
| QList::value_type             | **[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)**() |
| QList::value_type             | **[takeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)**() |
| T                             | **[value](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)**(qsizetype *i*) const |
| T                             | **[value](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-1)**(qsizetype *i*, QList::parameter_type *defaultValue*) const |
| bool                          | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QList< T> &*other*) const |
| QList< T>                     | **[operator+](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)**(const QList< T> &*other*) const & |
| QList< T>                     | **[operator+](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-1)**(const QList< T> &*other*) && |
| QList< T>                     | **[operator+](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-2)**(QList< T> &&*other*) const & |
| QList< T>                     | **[operator+](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-3)**(QList< T> &&*other*) && |
| QList< T> &                   | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)**(const QList< T> &*other*) |
| QList< T> &                   | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq-1)**(QList< T> &&*other*) |
| QList< T> &                   | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq-2)**(QList::parameter_type *value*) |
| QList< T> &                   | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq-3)**(QList::rvalue_ref *value*) |
| bool                          | **[operator<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt)**(const QList< T> &*other*) const |
| QList< T> &                   | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QList::parameter_type *value*) |
| QList< T> &                   | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-1)**(const QList< T> &*other*) |
| QList< T> &                   | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-2)**(QList< T> &&*other*) |
| QList< T> &                   | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-3)**(QList::rvalue_ref *value*) |
| bool                          | **[operator<=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-eq)**(const QList< T> &*other*) const |
| QList< T> &                   | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(std::initializer_list< T> *args*) |
| QList< T> &                   | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(const QList< T> &*other*) |
| QList< T> &                   | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-2)**(QList< T> &&*other*) |
| bool                          | **[operator==](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QList< T> &*other*) const |
| bool                          | **[operator>](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt)**(const QList< T> &*other*) const |
| bool                          | **[operator>=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-eq)**(const QList< T> &*other*) const |
| QList::reference              | **[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)**(qsizetype *i*) |
| QList::const_reference        | **[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d-1)**(qsizetype *i*) const |

## 相关非 成员

| qsizetype     | **[erase](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase-2)**(QList< T> &*list*, const AT &*t*) |
| ------------- | ------------------------------------------------------------ |
| qsizetype     | **[erase_if](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase_if)**(QList< T> &*list*, Predicate *pred*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash)**(const QList< T> &*key*, size_t *seed* = 0) |
| QDataStream & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-4)**(QDataStream &*out*, const QList< T> &*list*) |
| QDataStream & | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*in*, QList< T> &*list*) |

## 详细说明

QList< T> 是 Qt 的泛型之一[container classes](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它将其项目存储在相邻的内存位置并提供基于索引的快速访问。[QVector](https://doc-qt-io.translate.goog/qt-6/qvector.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> 曾经是 Qt 5 中的不同类，但现在是 QList 的简单别名。

QList< T> 和[QVarLengthArray](https://doc-qt-io.translate.goog/qt-6/qvarlengtharray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> 提供类似的 API 和函数。它们通常可以互换，但会产生性能影响。以下是用例概述：

- QList 应该是您默认的第一选择。
- [QVarLengthArray](https://doc-qt-io.translate.goog/qt-6/qvarlengtharray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供一个在堆栈上保留空间的数组，但如果需要，可以动态增长到堆上。它非常适合用于通常较小的短期容器。
- 如果你需要一个真正的链表，这保证[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity)在列表中间插入并使用项目迭代器而不是索引，请使用 std::list。

**注：** QList 和[QVarLengthArray](https://doc-qt-io.translate.goog/qt-6/qvarlengtharray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)两者都保证 C 兼容的数组布局。

**注意：** Qt 5 中的 QList 并不总是具有 C 兼容的数组布局，我们经常建议使用[QVector](https://doc-qt-io.translate.goog/qt-6/qvector.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)相反，为了获得更可预测的性能。Qt 6 中的情况不再如此，两个类现在共享一个实现并且可以互换使用。

下面是一个存储整数的 QList 和一个存储整数的 QList 的示例[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值观：

```
QList<int> integerList;
QList<QString> stringList;
```

QList 将其项目存储在连续内存的数组中。通常，创建的列表具有初始大小。例如，以下代码构造一个包含 200 个元素的 QList：

```
QList<QString> list(200);
```

元素会自动初始化[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。如果要使用不同的值初始化列表，请将该值作为第二个参数传递给构造函数：

```
QList<QString> list(200, "Pass");
```

您也可以致电[fill](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fill)() 随时用值填充列表。

QList 使用从 0 开始的索引，就像 C++ 数组一样。要访问特定索引位置处的项目，可以使用运算符[]()。在非常量列表上，operator[]() 返回对可在赋值左侧使用的项的引用：

```
if (list[0] == "Liz")
    list[0] = "Elizabeth";
```

对于只读访问，另一种语法是使用[at](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#at)():

```
for (qsizetype i = 0; i < list.size(); ++i) {
    if (list.at(i) == "Alfonso")
        cout << "Found Alfonso at position " << i << endl;
}
```

[at](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#at)() 可能比运算符 [] () 更快，因为它永远不会导致[deep copy](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deep-copy)发生。

访问 QList 中存储的数据的另一种方法是调用[data](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。该函数返回一个指向列表中第一项的指针。您可以使用指针直接访问和修改列表中存储的元素。如果您需要将 QList 传递给接受普通 C++ 数组的函数，则指针也很有用。

如果要查找列表中特定值的所有出现位置，请使用[indexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)（） 或者[lastIndexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastIndexOf)()。前者从给定的索引位置开始向前搜索，后者向后搜索。如果找到匹配项，两者都会返回匹配项的索引；否则，它们返回-1。例如：

```
qsizetype i = list.indexOf("Harumi");
if (i != -1)
    cout << "First occurrence of Harumi is at position " << i << endl;
```

如果您只想检查列表是否包含特定值，请使用[contains](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()。如果您想找出特定值在列表中出现的次数，请使用[count](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)()。

QList 提供了以下基本函数来添加、移动和删除项目：[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)(),[replace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)(),[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)(),[prepend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)(),[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)()。除了[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)(),[prepend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)（） 和[replace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)()，这些函数可能会很慢（[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)）对于大型列表，因为它们需要将列表中的许多项目在内存中移动一个位置。如果您想要一个在中间提供快速插入/删除的容器类，请使用 std::list 代替。

与普通 C++ 数组不同，QList 可以通过调用随时调整大小[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。如果新大小大于旧大小，QList 可能需要重新分配整个列表。QList 尝试通过预分配实际数据所需两倍的内存来减少重新分配的次数。

如果您正在逐步构建 QList 并提前知道它将包含多少个元素，您可以调用[reserve](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)()，要求QList预先分配一定量的内存。您也可以致电[capacity](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)() 找出 QList 实际分配了多少内存。

请注意，使用非常量运算符和函数可能会导致 QList 进行数据的深层复制，因为[隐式共享](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QList 的值类型必须是[assignable data type](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#assignable-data-type)。这涵盖了大多数常用的数据类型，但是编译器不允许您存储例如[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为一个值；相反，存储一个[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*。一些函数有额外的要求；例如，[indexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)（） 和[lastIndexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastIndexOf)() 期望值类型支持`operator==()`。这些要求是按函数记录的。

要迭代项目，请参阅[Iterating over Containers](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iterating-over-containers)。

除了QList之外，Qt还提供[QVarLengthArray](https://doc-qt-io.translate.goog/qt-6/qvarlengtharray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，一个非常低级的类，几乎没有针对速度进行优化的函数。

#### 有关使用 Qt 容器的更多信息

有关 Qt 容器相互比较以及与 STL 容器比较的详细讨论，请参阅[Understand the Qt Containers](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://marcmutz.wordpress.com/effective-qt/containers/)。

### 最大大小和内存不足情况

QList 的最大大小取决于架构。大多数 64 位系统可以分配超过 2 GB 的内存，典型限制为 2^63 字节。实际值还取决于管理数据块所需的开销。因此，在 32 位平台上，预计最大大小为 2 GB 减去开销，在 64 位平台上，最大大小为 2^63 字节减去开销。QList 中可以存储的元素数量是该最大大小除以所存储元素的大小。

当内存分配失败时，QList使用[Q_CHECK_PTR](https://doc-qt-io.translate.goog/qt-6/qtassert-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_CHECK_PTR)宏，`std::bad_alloc`如果应用程序正在使用异常支持进行编译，则会引发异常。如果禁用异常，则内存不足是未定义的行为。

请注意，操作系统可能会对持有大量已分配内存（尤其是大的连续块）的应用程序施加进一步的限制。此类注意事项、此类行为的配置或任何缓解措施均超出了 Qt API 的范围。

##  成员类型文档

### `[alias]`QList::ConstIterator

Qt 风格的同义词[QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QList::Iterator

Qt 风格的同义词[QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QList::const_pointer

提供 STL 兼容性。

### `[alias]`QList::const_reference

提供 STL 兼容性。

### `[alias]`QList::const_reverse_iterator

QList::const_reverse_iterator typedef 提供了一个 STL 风格的 const 反向迭代器[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**警告：**隐式共享容器上的迭代器的工作方式与 STL 迭代器不同。当迭代器在容器上处于活动状态时，您应该避免复制该容器。欲了解更多信息，请阅读[Implicit sharing iterator problem](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#implicit-sharing-iterator-problem)。

**警告：**迭代器在以下情况下无效：[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。考虑到默认情况下所有迭代器都是无效的。此规则的例外情况已明确记录。

**也可以看看**[QList::rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)(),[QList::rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)(),[QList::reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reverse_iterator-typedef)， 和[QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QList::difference_type

提供 STL 兼容性。

### `[alias]`QList::parameter_type

### `[alias]`QList::pointer

提供 STL 兼容性。

### `[alias]`QList::reference

提供 STL 兼容性。

### `[alias]`QList::reverse_iterator

QList::reverse_iterator typedef 提供了一个 STL 风格的非常量反向迭代器[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**警告：**隐式共享容器上的迭代器的工作方式与 STL 迭代器不同。当迭代器在容器上处于活动状态时，您应该避免复制该容器。欲了解更多信息，请阅读[Implicit sharing iterator problem](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#implicit-sharing-iterator-problem)。

**警告：**迭代器在以下情况下无效：[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。考虑到默认情况下所有迭代器都是无效的。此规则的例外情况已明确记录。

**也可以看看**[QList::rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)(),[QList::rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)(),[QList::const_reverse_iterator](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_reverse_iterator-typedef)， 和[QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QList::rvalue_ref

### `[alias]`QList::size_type

提供 STL 兼容性。

### `[alias]`QList::value_type

提供 STL 兼容性。

## 成员函数文档

### void QList::prepend(QList::parameter_type *value*)

### void QList::prepend(QList::rvalue_ref *value*)

 *value*在列表的开头。

例子：

```
QList<QString> list;
list.prepend("one");
list.prepend("two");
list.prepend("three");
// list: ["three", "two", "one"]
```

这与 list.insert(0,*value*）。

通常此操作相对较快（摊销[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)）。[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)能够在列表数据的开头分配额外的内存并沿该方向增长，而无需在每次操作时重新分配或移动数据。但是，如果您想要一个保证的容器类[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)前置，使用 std::list 代替，但更喜欢[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)否则。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 和[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### template < typename Args> QList::reference QList::emplaceBack(Args &&... *args*)

### template < typename Args> QList::reference QList::emplace_back(Args &&... *args*)

将新元素添加到容器的末尾。这个新元素是使用就地构建的*args*作为其构建的论据。

返回对新元素的引用。

例子：

```
QList<QString> list{"one", "two"};
list.emplaceBack(3, 'a');
qDebug() << list;
// list: ["one", "two", "aaa"]
```

还可以使用返回的引用来访问新创建的对象：

```
QList<QString> list;
auto &ref = list.emplaceBack();
ref = "one";
// list: ["one"]
```

这与 list.emplace(list.[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)(),*args*）。

**也可以看看**[emplace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplace)。

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::insert(qsizetype *i*, QList::parameter_type *value*)

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::insert(qsizetype *i*, QList::rvalue_ref *value*)

 *value*在索引位置*i*在列表中。如果*i*为 0 时，该值将添加到列表的前面。如果*i*是[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()，该值被附加到列表中。

例子：

```
QList<QString> list = {"alpha", "beta", "delta"};
list.insert(2, "gamma");
// list: ["alpha", "beta", "gamma", "delta"]
```

对于大型列表，此操作可能会很慢（[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time))，因为它需要移动索引处的所有项目*i*并在内存中再增加一位。如果您想要一个提供快速的容器类[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)() 函数，请使用 std::list 代替。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)(),[prepend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)（）， 和[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::insert([QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *before*, QList::parameter_type *value*)

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::insert([QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *before*, QList::rvalue_ref *value*)

这是一个重载函数。

 *value*在迭代器指向的项前面*before*。返回一个指向插入项的迭代器。

### void QList::replace(qsizetype *i*, QList::parameter_type *value*)

### void QList::replace(qsizetype *i*, QList::rvalue_ref *value*)

替换索引位置处的项目*i*和*value*。

*i*必须是列表中的有效索引位置（即，0 <=*i*<[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)())。

**也可以看看**[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)（） 和[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### void QList::push_front(QList::parameter_type *value*)

### void QList::push_front(QList::rvalue_ref *value*)

提供此函数是为了兼容 STL。它相当于前置(*value*）。

### QList< T> QList::operator+(QList< T> &&*other*) &&

### QList< T> QList::operator+(const QList< T> &*other*) &&

### QList< T> QList::operator+(QList< T> &&*other*) const &

### QList< T> QList::operator+(const QList< T> &*other*) const &

返回一个列表，其中包含此列表中的所有项目，后跟*other*列表。

**也可以看看**[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### QList::QList()

构造一个空列表。

**也可以看看**[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### `[explicit]`QList::QList(qsizetype *size*)

构造一个初始大小为的列表*size*元素。

元素被初始化为[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。

**也可以看看**[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### QList::QList(qsizetype *size*, QList::parameter_type *value*)

构造一个初始大小为的列表*size*元素。每个元素都初始化为*value*。

**也可以看看**[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)（） 和[fill](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fill)()。

### QList::QList(std::initializer_list< T> *args*)

从 std::initializer_list 给出的列表构造一个列表*args*。

### template < typename InputIterator> QList::QList(InputIterator *first*, InputIterator *last*)

使用迭代器范围 [ 中的内容构造一个列表*first*,*last*）。

的值类型`InputIterator`必须可转换为`T`。

### `[default]`QList::QList(QList< T> &&*other*)

Move 构造一个 QList 实例，使其指向与*other*正在指着。

### `[default]`QList::QList(const QList< T> &*other*)

构造一个副本*other*。

此操作需要[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity)，因为 QList 是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这使得从函数返回 QList 的速度非常快。如果共享实例被修改，它将被复制（写时复制），这需要[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity)。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### `[default]`QList::~QList()

销毁列表。

### void QList::append(QList::parameter_type *value*)

 *value*在列表的末尾。

例子：

```
QList<QString> list;
list.append("one");
list.append("two");
QString three = "three";
list.append(three);
// list: ["one", "two", "three"]
// three: "three"
```

这与调用 resize([size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)() + 1) 并赋值*value*到列表中新的最后一个元素。

这个操作比较快，因为[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通常会分配比所需更多的内存，因此它可以增长而无需每次重新分配整个列表。

**也可以看看**[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)(),[prepend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepend)（）， 和[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### void QList::append(QList::rvalue_ref *value*)

这是一个重载函数。

例子：

```
QList<QString> list;
list.append("one");
list.append("two");
QString three = "three";
list.append(std::move(three));
// list: ["one", "two", "three"]
// three: ""
```

### void QList::append(const QList< T> &*value*)

这是一个重载函数。

追加以下项目*value*列到这个列表中。

**也可以看看**[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)（） 和[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### `[since 6.0]`void QList::append(QList< T> &&*value*)

这是一个重载函数。

移动项目*value*列表到此列表的末尾。

这个函数是在Qt 6.0中引入的。

**也可以看看**[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)（） 和[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### QList::const_reference QList::at(qsizetype *i*) const

返回索引位置处的项目*i*在列表中。

*i*必须是列表中的有效索引位置（即，0 <=*i*<[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)())。

**也可以看看**[value](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)（） 和[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)()。

### QList::reference QList::back()

提供此函数是为了兼容 STL。它相当于[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### QList::const_reference QList::back() const

这是一个重载函数。

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::begin()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中的第一项。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::begin() const

这是一个重载函数。

### qsizetype QList::capacity() const

返回在不强制重新分配的情况下可以存储在列表中的最大项目数。

该函数的唯一目的是提供一种微调的手段[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的内存使用情况。一般来说，您很少需要调用此函数。如果您想知道列表中有多少项目，请致电[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

**注意：**静态分配的列表将报告容量为 0，即使它不为空。

**警告：**分配的内存块中的可用空间位置未定义。换句话说，您不应该假设空闲内存始终位于列表的末尾。您可以致电[reserve](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)() 确保末尾有足够的空间。

**也可以看看**[reserve](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)（） 和[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

### [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::cbegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中的第一项。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[cend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)()。

### [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::cend() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中最后一项的后面。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[cbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### void QList::clear()

从列表中删除所有元素。

如果不共享此列表，则[capacity](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)() 被保留。使用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)() 去化过剩产能。

**注意：**在 5.7 之前的 Qt 版本中（对于[QVector](https://doc-qt-io.translate.goog/qt-6/qvector.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）和 6.0（对于[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)），该函数释放了列表使用的内存，而不是保留容量。

**也可以看看**[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)（） 和[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

### [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::constBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中的第一项。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### QList::const_pointer QList::constData() const

返回指向列表中存储的数据的常量指针。该指针可用于访问列表中的项目。

**警告：**指针在分离时或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

此函数主要用于将列表传递给接受普通 C++ 数组的函数。

**也可以看看**[data](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（） 和[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)()。

### [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::constEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中最后一项的后面。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### const T &QList::constFirst() const

返回对列表中第一项的常量引用。该函数假设列表不为空。

**也可以看看**[constLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constLast)(),[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（）， 和[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)()。

### const T &QList::constLast() const

返回对列表中最后一项的常量引用。该函数假设列表不为空。

**也可以看看**[constFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFirst)(),[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（）， 和[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### template < typename AT> bool QList::contains(const AT &*value*) const

`true`如果列表包含出现则返回*value*; 否则返回`false`.

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[indexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)（） 和[count](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)()。

### template < typename AT> qsizetype QList::count(const AT &*value*) const

返回出现的次数*value*在列表中。

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[contains](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### qsizetype QList::count() const

这是一个重载函数。

与...一样[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### QList::const_reverse_iterator QList::crbegin() const

返回一个常量[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中的第一项。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),[rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)（）， 和[rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)()。

### QList::const_reverse_iterator QList::crend() const

返回一个常量[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中最后一项的后面。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)(),[rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)（）， 和[rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)()。

### QList::pointer QList::data()

返回指向列表中存储的数据的指针。该指针可用于访问和修改列表中的项目。

例子：

```
QList<int> list(10);
int *data = list.data();
for (qsizetype i = 0; i < 10; ++i)
    data[i] = 2 * i;
```

**警告：**指针在分离时或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

此函数主要用于将列表传递给接受普通 C++ 数组的函数。

**也可以看看**[constData](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constData)（） 和[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)()。

### QList::const_pointer QList::data() const

这是一个重载函数。

### template < typename Args > [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::emplace(qsizetype *i*, Args &&... *args*)

通过在位置插入新元素来扩展容器*i*。这个新元素是使用就地构建的*args*作为其构建的论据。

返回新元素的迭代器。

例子：

```
QList<QString> list{"a", "ccc"};
list.emplace(1, 2, 'b');
// list: ["a", "bb", "ccc"]
```

**注意：**保证元素将在开始时就位创建，但之后可能会被复制或移动到正确的位置。

**也可以看看**[emplaceBack](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplaceBack)。

### template < typename Args > [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::emplace([QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *before*, Args &&... *args*)

这是一个重载函数。

在迭代器指向的项前面创建一个新元素*before*。这个新元素是使用就地构建的*args*作为其构建的论据。

返回新元素的迭代器。

### bool QList::empty() const

提供此函数是为了兼容 STL。它相当于[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()，`true`如果列表为空则返回；否则返回`false`.

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::end()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向列表中最后一项的后面。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::end() const

这是一个重载函数。

### bool QList::endsWith(QList::parameter_type *value*) const

如果`true`此列表不为空且其最后一项等于*value*; 否则返回`false`.

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::erase([QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *pos*)

删除迭代器指向的项*pos*从列表中，并返回一个迭代器到列表中的下一个项目（可能是[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)())。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**注：**当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，此函数仅使指定位置或之后的迭代器无效。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)（） 和[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::erase([QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *begin*, [QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *end*)

这是一个重载函数。

从中删除所有项目*begin*最多（但不包括）*end*。返回一个指向相同项目的迭代器*end*在通话之前提及。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**注：**当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，此函数仅使指定位置或之后的迭代器无效。

### QList< T> &QList::fill(QList::parameter_type *value*, qsizetype *size* = -1)

分配*value*到列表中的所有项目。如果*size*与 -1（默认值）不同，列表大小调整为*size*预先。

例子：

```
QList<QString> list(3);
list.fill("Yes");
// list: ["Yes", "Yes", "Yes"]

list.fill("oh", 5);
// list: ["oh", "oh", "oh", "oh", "oh"]
```

**也可以看看**[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### T &QList::first()

返回对列表中第一项的引用。该函数假设列表不为空。

**也可以看看**[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)(),[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（）， 和[constFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFirst)()。

### const T &QList::first() const

这是一个重载函数。

### `[since 6.0]`QList< T> QList::first(qsizetype *n*) const

返回包含第一个的子列表*n*该列表的元素。

**注意：**当以下情况时，行为未定义*n*< 0 或*n*>[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

这个函数是在Qt 6.0中引入的。

**也可以看看**[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)（） 和[sliced](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliced)()。

### QList::reference QList::front()

提供此函数是为了兼容 STL。它相当于[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)()。

### QList::const_reference QList::front() const

这是一个重载函数。

### template < typename AT> qsizetype QList::indexOf(const AT &*value*, qsizetype *from* = 0) const

返回第一次出现的索引位置*value*在列表中，从索引位置向前搜索*from*。如果没有匹配的项目，则返回 -1。

例子：

```
QList<QString> list{"A", "B", "C", "B", "A"};
list.indexOf("B");            // returns 1
list.indexOf("B", 1);         // returns 1
list.indexOf("B", 2);         // returns 3
list.indexOf("X");            // returns -1
```

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[lastIndexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastIndexOf)（） 和[contains](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()。

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::insert(qsizetype *i*, qsizetype *count*, QList::parameter_type *value*)

这是一个重载函数。

 *count*的副本*value*在索引位置*i*在列表中。

例子：

```
QList<double> list = {2.718, 1.442, 0.4342};
list.insert(1, 3, 9.9);
// list: [2.718, 9.9, 9.9, 9.9, 1.442, 0.4342]
```

### [QList::iterator](https://doc-qt-io.translate.goog/qt-6/qlist-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QList::insert([QList::const_iterator](https://doc-qt-io.translate.goog/qt-6/qlist-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *before*, qsizetype *count*, QList::parameter_type *value*)

 *count*的副本*value*在迭代器指向的项前面*before*。返回一个指向第一个插入项的迭代器。

### bool QList::isEmpty() const

`true`如果列表大小为 0，则返回；否则返回`false`.

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)（） 和[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### T &QList::last()

返回对列表中最后一项的引用。该函数假设列表不为空。

**也可以看看**[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)(),[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（）， 和[constLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constLast)()。

### const T &QList::last() const

这是一个重载函数。

### `[since 6.0]`QList< T> QList::last(qsizetype *n*) const

返回包含最后一个的子列表*n*该列表的元素。

**注意：**当以下情况时，行为未定义*n*< 0 或*n*>[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

这个函数是在Qt 6.0中引入的。

**也可以看看**[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)（） 和[sliced](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliced)()。

### template < typename AT> qsizetype QList::lastIndexOf(const AT &*value*, qsizetype *from* = -1) const

返回该值最后一次出现的索引位置*value*在列表中，从索引位置向后搜索*from*。如果*from*为 -1（默认值），则从最后一项开始搜索。如果没有匹配的项目，则返回 -1。

例子：

```
QList<QString> list = {"A", "B", "C", "B", "A"};
list.lastIndexOf("B");        // returns 3
list.lastIndexOf("B", 3);     // returns 3
list.lastIndexOf("B", 2);     // returns 1
list.lastIndexOf("X");        // returns -1
```

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[indexOf](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### qsizetype QList::length() const

与...一样[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)（） 和[count](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)()。

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)（） 和[count](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)()。

### QList< T> QList::mid(qsizetype *pos*, qsizetype *length* = -1) const

返回一个子列表，其中包含此列表中的元素，从位置开始*pos*。如果*length*是-1（默认值），之后的所有元素*pos*被包含在内; 否则*length*元素（或所有剩余元素，如果少于*length*元素）包括在内。

### void QList::move(qsizetype *from*, qsizetype *to*)

将项目移动到索引位置*from*到索引位置*to*。

### void QList::pop_back()

提供此函数是为了兼容 STL。它相当于[removeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)()。

### void QList::pop_front()

提供此函数是为了兼容 STL。它相当于[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)()。

### void QList::push_back(QList::parameter_type *value*)

提供此函数是为了兼容 STL。它相当于附加（*value*）。

### void QList::push_back(QList::rvalue_ref *value*)

这是一个重载函数。

### QList::reverse_iterator QList::rbegin()

返回一个[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中的第一项。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),[crbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crbegin)（）， 和[rend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rend)()。

### QList::const_reverse_iterator QList::rbegin() const

这是一个重载函数。

### void QList::remove(qsizetype *i*, qsizetype *n* = 1)

删除*n*列表中的元素，从索引位置开始*i*。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**注：**当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，此函数仅使指定位置或之后的迭代器无效。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)(),[replace](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)（）， 和[fill](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fill)()。

### template < typename AT> qsizetype QList::removeAll(const AT &*t*)

删除所有比较等于的元素*t*从列表中。返回删除的元素数（如果有）。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**也可以看看**[removeOne](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeOne)()。

### void QList::removeAt(qsizetype *i*)

删除索引位置的元素*i*。相当于

```
remove(i);
```

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**注：**当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，此函数仅使指定位置或之后的迭代器无效。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### void QList::removeFirst()

删除列表中的第一项。调用此函数相当于调用remove(0)。该列表不能为空。如果列表可以为空，则调用[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)() 在调用该函数之前。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)(),[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### `[since 6.1]`template < typename Predicate> qsizetype QList::removeIf(Predicate *pred*)

删除谓词所属的所有元素*pred*从列表中返回 true。返回删除的元素数（如果有）。

该函数是在 Qt 6.1 中引入的。

**也可以看看**[removeAll](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)()。

### void QList::removeLast()

删除列表中的最后一项。调用此函数相当于调用remove([size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)() - 1)。该列表不能为空。如果列表可以为空，则调用[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)() 在调用该函数之前。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)(),[takeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)(),[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### template < typename AT> bool QList::removeOne(const AT &*t*)

删除第一个比较等于的元素*t*从列表中。返回元素是否确实被删除。

元素删除将保留列表的容量，并且不会减少分配的内存量。要释放额外容量并释放尽可能多的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

**也可以看看**[removeAll](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)()。

### QList::reverse_iterator QList::rend()

返回一个[STL-style](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)反向迭代器以相反的顺序指向列表中最后一项的后面。

**警告：**返回的迭代器在分离或当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被修改。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)(),[crend](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#crend)（）， 和[rbegin](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rbegin)()。

### QList::const_reverse_iterator QList::rend() const

这是一个重载函数。

### void QList::reserve(qsizetype *size*)

尝试分配内存至少*size*元素。

如果您事先知道列表有多大，则应该调用此函数以防止重新分配和内存碎片。如果您经常调整列表的大小，您也可能会获得更好的性能。

如果对需要多少空间有疑问，通常最好使用上限*size*，或者最可能大小的高估计（如果严格的上限比这个大得多）。如果*size*是低估的，一旦超过保留大小，列表将根据需要增长，这可能会导致分配比最佳高估更大的分配，并且会减慢触发它的操作。

**警告：** reserve() 保留内存，但不会更改列表的大小。访问列表当前末尾之外的数据是未定义的行为。如果需要访问列表当前末尾之外的内存，请使用[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

**也可以看看**[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)(),[capacity](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)（）， 和[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### `[since 6.0]`void QList::resize(qsizetype *size*)

将列表的大小设置为*size*。如果*size*大于当前大小，元素添加到末尾；新元素初始化为[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。如果*size*小于当前大小，则从末尾删除元素。

如果不共享此列表，则[capacity](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)() 被保留。使用[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)() 去化过剩产能。

**注意：**在 5.7 之前的 Qt 版本中（对于[QVector](https://doc-qt-io.translate.goog/qt-6/qvector.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp);[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在 6.0 之前缺少 resize()），该函数释放列表使用的内存而不是保留容量。

这个函数是在Qt 6.0中引入的。

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### void QList::shrink_to_fit()

提供此函数是为了兼容 STL。它相当于[squeeze](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

### qsizetype QList::size() const

返回列表中的项目数。

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[resize](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### `[since 6.0]`QList< T> QList::sliced(qsizetype *pos*, qsizetype *n*) const

返回一个子列表，其中包含*n*此列表的元素，从位置开始*pos*。

**注意：**当以下情况时，行为未定义*pos*< 0,*n*< 0，或*pos*+*n*>[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

这个函数是在Qt 6.0中引入的。

**也可以看看**[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)（） 和[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### `[since 6.0]`QList< T> QList::sliced(qsizetype *pos*) const

这是一个重载函数。

返回一个子列表，其中包含此列表中从位置开始的元素*pos*并延伸至其末端。

**注意：**当以下情况时，行为未定义*pos*< 0 或*pos*>[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

这个函数是在Qt 6.0中引入的。

**也可以看看**[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)（） 和[last](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)()。

### void QList::squeeze()

释放存储项目不需要的任何内存。

该函数的唯一目的是提供一种微调的手段[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的内存使用情况。一般来说，您很少需要调用此函数。

**也可以看看**[reserve](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)（） 和[capacity](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)()。

### bool QList::startsWith(QList::parameter_type *value*) const

如果`true`此列表不为空且其第一项等于*value*; 否则返回`false`.

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[first](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)()。

### void QList::swap(QList< T> &*other*)

掉期清单*other*有了这个清单。这个操作非常快并且永远不会失败。

### void QList::swapItemsAt(qsizetype *i*, qsizetype *j*)

交换索引位置的物品*i*项目位于索引位置*j*。该函数假设两者*i*和*j*至少为 0 但小于[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。为了避免失败，请测试两者*i*和*j*至少为 0 且小于[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### T QList::takeAt(qsizetype *i*)

删除索引位置的元素*i*并返回它。

相当于

```
T t = at(i);
remove(i);
return t;
```

**注：**当[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，此函数仅使指定位置或之后的迭代器无效。

**也可以看看**[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)（） 和[takeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)()。

### QList::value_type QList::takeFirst()

删除列表中的第一项并将其返回。该函数假设列表不为空。为避免失败，请致电[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)() 在调用该函数之前。

**也可以看看**[takeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeLast)（） 和[removeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFirst)()。

### QList::value_type QList::takeLast()

删除列表中的最后一项并将其返回。该函数假设列表不为空。为避免失败，请致电[isEmpty](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)() 在调用该函数之前。

如果不使用返回值，[removeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)() 效率更高。

**也可以看看**[takeFirst](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeFirst)（） 和[removeLast](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeLast)()。

### T QList::value(qsizetype *i*) const

返回索引位置处的值*i*在列表中。

如果索引*i*超出范围，函数返回[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。如果你确定*i*在范围内，您可以使用[at](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#at)() 代替，速度稍快一些。

**也可以看看**[at](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#at)（） 和[operator[\]](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)()。

### T QList::value(qsizetype *i*, QList::parameter_type *defaultValue*) const

这是一个重载函数。

如果索引*i*越界，函数返回*defaultValue*。

### bool QList::operator!=(const QList< T> &*other*) const

返回`true`如果*other*不等于此列表；否则返回`false`.

如果两个列表包含相同顺序的相同值，则认为它们相等。

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### QList< T> &QList::operator+=(const QList< T> &*other*)

追加以下项目*other*list 到此列表并返回对此列表的引用。

**也可以看看**[operator+](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)（） 和[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)()。

### `[since 6.0]`QList< T> &QList::operator+=(QList< T> &&*other*)

这是一个重载函数。

这个函数是在Qt 6.0中引入的。

**也可以看看**[operator+](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)（） 和[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)()。

### QList< T> &QList::operator+=(QList::parameter_type *value*)

这是一个重载函数。

追加*value*到列表中。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 和[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)()。

### QList< T> &QList::operator+=(QList::rvalue_ref *value*)

这是一个重载函数。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 和[operator<<](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)()。

### bool QList::operator<(const QList< T> &*other*) const

`true`如果此列表是则返回[lexically less than](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://en.cppreference.com/w/cpp/algorithm/lexicographical_compare) *other*; 否则返回`false`.

此函数要求值类型具有 的实现`operator<()`。

### QList< T> &QList::operator<<(QList::parameter_type *value*)

追加*value*到列表并返回对此列表的引用。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 和[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### QList< T> &QList::operator<<(const QList< T> &*other*)

追加*other*到列表并返回对该列表的引用。

### `[since 6.0]`QList< T> &QList::operator<<(QList< T> &&*other*)

这是一个重载函数。

这个函数是在Qt 6.0中引入的。

### QList< T> &QList::operator<<(QList::rvalue_ref *value*)

这是一个重载函数。

**也可以看看**[append](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 和[operator+=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### bool QList::operator<=(const QList< T> &*other*) const

`true`如果此列表是则返回[lexically less than or equal to](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://en.cppreference.com/w/cpp/algorithm/lexicographical_compare) *other*; 否则返回`false`.

此函数要求值类型具有 的实现`operator<()`。

### QList< T> &QList::operator=(std::initializer_list< T> *args*)

分配值的集合*args*对此[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

### `[default]`QList< T> &QList::operator=(const QList< T> &*other*)

分配*other*到此列表并返回对此列表的引用。

### `[default]`QList< T> &QList::operator=(QList< T> &&*other*)

移动分配*other*对此[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

### bool QList::operator==(const QList< T> &*other*) const

返回`true`如果*other*等于这个列表；否则返回`false`.

如果两个列表包含相同顺序的相同值，则认为它们相等。

此函数要求值类型具有 的实现`operator==()`。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

### bool QList::operator>(const QList< T> &*other*) const

`true`如果此列表是则返回[lexically greater than](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://en.cppreference.com/w/cpp/algorithm/lexicographical_compare) *other*; 否则返回`false`.

此函数要求值类型具有 的实现`operator<()`。

### bool QList::operator>=(const QList< T> &*other*) const

`true`如果此列表是则返回[lexically greater than or equal to](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://en.cppreference.com/w/cpp/algorithm/lexicographical_compare) *other*; 否则返回`false`.

此函数要求值类型具有 的实现`operator<()`。

### QList::reference QList::operator[](qsizetype *i*)

返回索引位置处的项目*i*作为可修改的参考。

*i*必须是列表中的有效索引位置（即，0 <=*i*<[size](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)())。

请注意，使用非常量运算符可能会导致[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)进行深复制。

**也可以看看**[at](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#at)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

### QList::const_reference QList::operator[](qsizetype *i*) const

这是一个重载函数。

与在（*i*）。

## 相关非成员

### `[since 6.1]`template <typename T, typename AT> qsizetype erase(QList< T> &*list*, const AT &*t*)

删除所有比较等于的元素*t*从列表中*list*。返回删除的元素数（如果有）。

**注：**不同于[QList::removeAll](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll),*t*不允许是对内部元素的引用*list*。如果您不能确定情况并非如此，请复印一份*t*并用副本调用此函数。

该函数是在 Qt 6.1 中引入的。

**也可以看看**[QList::removeAll](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAll)（） 和[erase_if](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase_if)。

### `[since 6.1]`template <typename T, typename Predicate> qsizetype erase_if(QList< T> &*list*, Predicate *pred*)

删除谓词所属的所有元素*pred*从列表中返回 true*list*。返回删除的元素数（如果有）。

该函数是在 Qt 6.1 中引入的。

**也可以看看**[erase](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)。

### template < typename T> size_t qHash(const QList< T> &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

该函数需要为值类型重载qHash() `T`。

### template < typename T> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator<<([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*out*, const QList< T> &*list*)

写清单*list*流式传输*out*。

该函数需要值类型来实现`operator<<()`。

**也可以看看**[Format of the QDataStream operators](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template < typename T> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*in*, QList< T> &*list*)

从流中读取列表*in*进入*list*。

该函数需要值类型来实现`operator>>()`。

**也可以看看**[Format of the QDataStream operators](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。
