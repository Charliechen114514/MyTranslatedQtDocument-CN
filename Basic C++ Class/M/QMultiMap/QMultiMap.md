#  QMultiMap Class

template < typename Key, typename T> class QMultiMap

QMultiMap 类是一个模板类，它提供具有多个等效键的关联数组。

| Header: | #include < QMultiMap>                                        |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:  | QT += core                                                   |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qmultimap-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qmultimap-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QMultiMap 是[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
| class | **[iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| class | **[key_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-key-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
|       | **[ConstIterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ConstIterator-typedef)** |
|       | **[Iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Iterator-typedef)** |
|       | **[const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef)** |
|       | **[difference_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#difference_type-typedef)** |
|       | **[key_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_type-typedef)** |
|       | **[key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_value_iterator-typedef)** |
|       | **[mapped_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapped_type-typedef)** |
|       | **[size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef)** |

## 公共职能

|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)**() |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-1)**(std::initializer_list< std::pair< Key, T>> *list*) |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-2)**(const QMap< Key, T> &*other*) |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-3)**(QMap< Key, T> &&*other*) |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-4)**(const std::multimap< Key, T> &*other*) |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-5)**(std::multimap< Key, T> &&*other*) |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-7)**(const QMultiMap< Key, T> &*other*) |
|                                                              | **[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap-6)**(QMultiMap< Key, T> &&*other*) |
|                                                              | **[~QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QMultiMap)**() |
| auto                                                         | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange)**() & |
| auto                                                         | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange-1)**() const & |
| auto                                                         | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange-2)**() && |
| auto                                                         | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange-3)**() const && |
| QMultiMap::iterator                                          | **[begin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() |
| QMultiMap::const_iterator                                    | **[begin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin-1)**() const |
| QMultiMap::const_iterator                                    | **[cbegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)**() const |
| QMultiMap::const_iterator                                    | **[cend](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)**() const |
| void                                                         | **[clear](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| QMultiMap::const_iterator                                    | **[constBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)**() const |
| QMultiMap::const_iterator                                    | **[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)**() const |
| QMultiMap::const_iterator                                    | **[constFind](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFind)**(const Key &*key*) const |
| QMultiMap::const_iterator                                    | **[constFind](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFind-1)**(const Key &*key*, const T &*value*) const |
| QMultiMap::const_key_value_iterator                          | **[constKeyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constKeyValueBegin)**() const |
| QMultiMap::const_key_value_iterator                          | **[constKeyValueEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constKeyValueEnd)**() const |
| bool                                                         | **[contains](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)**(const Key &*key*) const |
| bool                                                         | **[contains](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains-1)**(const Key &*key*, const T &*value*) const |
| QMultiMap::size_type                                         | **[count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**(const Key &*key*) const |
| QMultiMap::size_type                                         | **[count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)**(const Key &*key*, const T &*value*) const |
| QMultiMap::size_type                                         | **[count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-2)**() const |
| bool                                                         | **[empty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#empty)**() const |
| QMultiMap::iterator                                          | **[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() |
| QMultiMap::const_iterator                                    | **[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end-1)**() const |
| QPair< QMultiMap::iterator, QMultiMap::iterator>             | **[equal_range](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#equal_range)**(const Key &*key*) |
| QPair< QMultiMap::const_iterator, QMultiMap::const_iterator> | **[equal_range](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#equal_range-1)**(const Key &*key*) const |
| QMultiMap::iterator                                          | **[erase](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)**(QMultiMap::const_iterator *pos*) |
| QMultiMap::iterator                                          | **[erase](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase-1)**(QMultiMap::const_iterator *first*, QMultiMap::const_iterator *last*) |
| QMultiMap::iterator                                          | **[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)**(const Key &*key*) |
| QMultiMap::const_iterator                                    | **[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-1)**(const Key &*key*) const |
| QMultiMap::const_iterator                                    | **[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-3)**(const Key &*key*, const T &*value*) const |
| T &                                                          | **[first](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)**() |
| const T &                                                    | **[first](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first-1)**() const |
| const Key &                                                  | **[firstKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstKey)**() const |
| QMultiMap::iterator                                          | **[insert](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)**(const Key &*key*, const T &*value*) |
| QMultiMap::iterator                                          | **[insert](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-1)**(QMultiMap::const_iterator *pos*, const Key &*key*, const T &*value*) |
| bool                                                         | **[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)**() const |
| Key                                                          | **[key](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)**(const T &*value*, const Key &*defaultKey* = Key()) const |
| QMultiMap::key_iterator                                      | **[keyBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)**() const |
| QMultiMap::key_iterator                                      | **[keyEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)**() const |
| QMultiMap::key_value_iterator                                | **[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)**() |
| QMultiMap::const_key_value_iterator                          | **[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin-1)**() const |
| QMultiMap::key_value_iterator                                | **[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)**() |
| QMultiMap::const_key_value_iterator                          | **[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd-1)**() const |
| QList< Key>                                                  | **[keys](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)**() const |
| QList< Key>                                                  | **[keys](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys-1)**(const T &*value*) const |
| T &                                                          | **[last](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)**() |
| const T &                                                    | **[last](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last-1)**() const |
| const Key &                                                  | **[lastKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastKey)**() const |
| QMultiMap::iterator                                          | **[lowerBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lowerBound)**(const Key &*key*) |
| QMultiMap::const_iterator                                    | **[lowerBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lowerBound-1)**(const Key &*key*) const |
| QMultiMap::size_type                                         | **[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)**(const Key &*key*) |
| QMultiMap::size_type                                         | **[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove-1)**(const Key &*key*, const T &*value*) |
| QMultiMap::size_type                                         | **[removeIf](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeIf)**(Predicate *pred*) |
| QMultiMap::iterator                                          | **[replace](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)**(const Key &*key*, const T &*value*) |
| QMultiMap::size_type                                         | **[size](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)**() const |
| void                                                         | **[swap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QMultiMap< Key, T> &*other*) |
| T                                                            | **[take](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)**(const Key &*key*) |
| std::multimap< Key, T>                                       | **[toStdMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toStdMultiMap)**() const & |
| QList< Key>                                                  | **[uniqueKeys](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniqueKeys)**() const |
| QMultiMap< Key, T> &                                         | **[unite](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unite)**(const QMultiMap< Key, T> &*other*) |
| QMultiMap< Key, T> &                                         | **[unite](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unite-1)**(QMultiMap< Key, T> &&*other*) |
| QMultiMap::iterator                                          | **[upperBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#upperBound)**(const Key &*key*) |
| QMultiMap::const_iterator                                    | **[upperBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#upperBound-1)**(const Key &*key*) const |
| T                                                            | **[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)**(const Key &*key*, const T &*defaultValue* = T()) const |
| QList< T>                                                    | **[values](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)**() const |
| QList< T>                                                    | **[values](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values-1)**(const Key &*key*) const |
| QMultiMap< Key, T> &                                         | **[operator=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QMultiMap< Key, T> &*other*) |
| QMultiMap< Key, T> &                                         | **[operator=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(QMultiMap< Key, T> &&*other*) |

## 相关非会员

| qsizetype          | **[erase_if](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase_if)**(QMultiMap< Key, T> &*map*, Predicate *pred*) |
| ------------------ | ------------------------------------------------------------ |
| bool               | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QMultiMap< Key, T> &*lhs*, const QMultiMap< Key, T> &*rhs*) |
| QMultiMap< Key, T> | **[operator+](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)**(const QMultiMap< Key, T> &*lhs*, const QMultiMap< Key, T> &*rhs*) |
| QMultiMap< Key, T> | **[operator+=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)**(QMultiMap< Key, T> &*lhs*, const QMultiMap< Key, T> &*rhs*) |
| QDataStream &      | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QDataStream &*out*, const QMultiMap< Key, T> &*map*) |
| bool               | **[operator==](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QMultiMap< Key, T> &*lhs*, const QMultiMap< Key, T> &*rhs*) |
| QDataStream &      | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*in*, QMultiMap< Key, T> &*map*) |

## 详细说明

QMultiMap< Key, T> 是 Qt 的泛型之一[container classes](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它存储（键，值）对并提供键的快速查找。

QMultiMap 和[QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供非常相似的功能。差异是：

- [QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供比 QMultiMap 平均更快的查找速度。（看[Algorithmic Complexity](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity)了解详情。）
- 当迭代一个[QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，项目是任意排序的。使用 QMultiMap，项目始终按键排序。
- a 的密钥类型[QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)必须提供运算符 ==() 和全局[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)（键）功能。QMultiMap 的键类型必须提供指定全序的operator< ()。从 Qt 5.8.1 开始，使用指针类型作为键也是安全的，即使底层运算符 < () 不提供全序。

这是一个 QMultiMap 示例[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)键和`int`值：

```
QMultiMap< QString, int> multimap;
```

要将（键，值）对插入多重映射，您可以使用[insert](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()：

```
multimap.insert("a", 1);
multimap.insert("b", 3);
multimap.insert("c", 7);
multimap.insert("c", -5);
```

这会将以下三个（键，值）对插入到 QMultiMap 中：("a", 1)、("b", 3)、("c", 7) 和 ("c", -5)；请注意，允许重复的键。

要查找值，请使用[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)（） 或者[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()：

```
int num2 = multimap.value("a"); // 1
int num3 = multimap.value("thirteen"); // not found; 0
int num3 = 0;
auto it = multimap.constFind("b");
if (it != multimap.cend()) {
    num3 = it.value();
}
```

如果地图中不存在具有指定键的项目，这些函数将返回[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。

如果你想检查地图是否包含某个键，请使用[contains](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()：

```
int timeout = 30;
if (multimap.contains("TIMEOUT"))
    timeout = multimap.value("TIMEOUT");

// better:
auto it = multimap.find("TIMEOUT");
if (it != multimap.end())
    timeout = it.value();
```

还有一个[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)() 重载，如果没有具有指定键的项目，则使用第二个参数作为默认值：

```
int timeout = multimap.value("TIMEOUT", 30);
```

如果您想浏览 QMultiMap 中存储的所有（键，值）对，您可以使用迭代器。QMultiMap 两者都提供[Java-style iterators](https://doc-qt-io.translate.goog/qt-6/java-style-iterators.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#java-style-iterators)（[QMultiMapIterator](https://doc-qt-io.translate.goog/qt-6/qmultimapiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QMutableMultiMapIterator](https://doc-qt-io.translate.goog/qt-6/qmutablemultimapiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)） 和[STL-style iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)（[QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。以下是如何迭代 QMultiMap< [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), int> 使用 Java 风格的迭代器：

```
QMultiMapIterator< QString, int> i(multimap);
while (i.hasNext()) {
    i.next();
    cout < <  qPrintable(i.key()) < <  ": " < <  i.value() < <  endl;
}
```

下面是相同的代码，但这次使用了 STL 风格的迭代器：

```
for (auto i = multimap.cbegin(), end = multimap.cend(); i != end; ++i)
    cout < <  qPrintable(i.key()) < <  ": " < <  i.value() < <  endl;
```

这些项目按升序键顺序遍历。

QMultiMap 允许每个键有多个值。如果你打电话[insert](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)() 使用映射中已存在的键，将插入一个新的（键，值）对。例如：

```
multimap.insert("plenty", 100);
multimap.insert("plenty", 2000);
// multimap.size() == 2
```

如果要检索单个键的所有值，可以使用values(const Key &key)，它返回一个[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T>:

```
QList< int> values = multimap.values("plenty");
for (auto i : std::as_const(values))
    cout < <  i < <  endl;
```

共享相同键的项目可以从最近插入到最近插入。另一种方法是调用[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)() 获取第一个带有键的项目的 STL 样式迭代器并从那里迭代：

```
auto i = multimap.find("plenty");
while (i != map.end() && i.key() == "plenty") {
    cout < <  i.value() < <  endl;
    ++i;
}

// better:
auto [i, end] = multimap.equal_range("plenty");
while (i != end) {
    cout < <  i.value() < <  endl;
    ++i;
}
```

如果您只需要从映射中提取值（而不是键），您还可以使用基于范围：

```
QMap< QString, int> multimap;
...
for (int value : std::as_const(multimap))
    cout < <  value < <  endl;
```

可以通过多种方式从多重地图中删除项目。一种方法是打电话[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)(); 这将删除具有给定密钥的任何项目。另一种方法是使用[QMutableMultiMapIterator::remove](https://doc-qt-io.translate.goog/qt-6/qmutablemultimapiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。此外，您可以使用以下命令清除整个地图[clear](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

可以通过调用合并两个多地图[unite](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unite)()、使用运算符+() 以及使用运算符+=()。例子：

```
QMultiMap< QString, int> map1, map2, map3;

map1.insert("plenty", 100);
map1.insert("plenty", 2000);
// map1.size() == 2

map2.insert("plenty", 5000);
// map2.size() == 1

map3 = map1 + map2;
// map3.size() == 3
```

QMultiMap 的键和值数据类型必须是[assignable data types](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#assignable-data-types)。这涵盖了您可能遇到的大多数数据类型，但编译器不允许您存储例如[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为一个值；相反，存储一个[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*。另外，QMultiMap的键类型必须提供operator< ()。[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用它来保持其项目的排序，并假设两个键`x`和`y`相等（如果 和`x <  y`都不`y <  x`为真）。

例子：

```
#ifndef EMPLOYEE_H
#define EMPLOYEE_H

class Employee
{
public:
    Employee() {}
    Employee(const QString &name, QDate dateOfBirth);
    ...

private:
    QString myName;
    QDate myDateOfBirth;
};

inline bool operator< (const Employee &e1, const Employee &e2)
{
    if (e1.name() != e2.name())
        return e1.name() <  e2.name();
    return e1.dateOfBirth() <  e2.dateOfBirth();
}

#endif // EMPLOYEE_H
```

在示例中，我们首先比较员工的姓名。如果相等，我们会比较他们的出生日期来打破平局。

**也可以看看**[QMultiMapIterator](https://doc-qt-io.translate.goog/qt-6/qmultimapiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QMutableMultiMapIterator](https://doc-qt-io.translate.goog/qt-6/qmutablemultimapiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### QMultiMap::ConstIterator

Qt 风格的同义词[QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QMultiMap::Iterator

Qt 风格的同义词[QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QMultiMap::const_key_value_iterator

QMultiMap::const_key_value_iterator typedef 提供了一个 STL 风格的迭代器[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QMultiMap::const_key_value_iterator 本质上与[QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不同之处在于，operator*() 返回一个键/值对而不是一个值。

**也可以看看**[QKeyValueIterator](https://doc-qt-io.translate.goog/qt-6/qkeyvalueiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QMultiMap::difference_type

ptrdiff_t 的类型定义。提供 STL 兼容性。

### `[alias]`QMultiMap::key_type

键的类型定义。提供 STL 兼容性。

### QMultiMap::key_value_iterator

QMultiMap::key_value_iterator typedef 提供了一个 STL 风格的迭代器[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QMultiMap::key_value_iterator 本质上与[QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不同之处在于，operator*() 返回一个键/值对而不是一个值。

**也可以看看**[QKeyValueIterator](https://doc-qt-io.translate.goog/qt-6/qkeyvalueiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QMultiMap::mapped_type

T 的 Typedef。为 STL 兼容性而提供。

### `[alias]`QMultiMap::size_type

typedef 为 int。提供 STL 兼容性。

## 成员函数文档

### `[since 6.4]`auto QMultiMap::asKeyValueRange() &

### `[since 6.4]`auto QMultiMap::asKeyValueRange() &&

### `[since 6.4]`auto QMultiMap::asKeyValueRange() const &

### `[since 6.4]`auto QMultiMap::asKeyValueRange() const &&

返回一个范围对象，该对象允许以键/值对的形式迭代此多重映射。例如，这个范围对象可以在基于范围的 for 循环中与结构化绑定声明结合使用：

```
QMultiMap< QString, int> map;
map.insert("January", 1);
map.insert("February", 2);
// ...
map.insert("December", 12);

for (auto [key, value] : map.asKeyValueRange()) {
    cout < <  qPrintable(key) < <  ": " < <  value < <  endl;
    --value; // convert to JS month indexing
}
```

请注意，通过这种方式获得的键和值都是对多重映射中的键和值的引用。具体来说，改变值将修改映射本身。

该功能是在 Qt 6.4 中引入的。

**也可以看看**[QKeyValueIterator](https://doc-qt-io.translate.goog/qt-6/qkeyvalueiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QMultiMap::QMultiMap()

构造一个空的多重地图。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### QMultiMap::QMultiMap(std::initializer_list< std::pair< Key, T>> *list*)

使用初始值设定项列表中每个元素的副本构造一个多重映射*list*。

### `[explicit, since 6.0]`QMultiMap::QMultiMap(const [QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key, T> &*other*)

构造一个多重映射作为副本*other*。

这个函数是在Qt 6.0中引入的。

### `[explicit, since 6.0]`QMultiMap::QMultiMap([QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key, T> &&*other*)

如果*other*被共享，构造一个多重映射作为副本*other*。否则，通过移动元素来构造多重映射*other*。

这个函数是在Qt 6.0中引入的。

### `[explicit]`QMultiMap::QMultiMap(const std::multimap< Key, T> &*other*)

构造一个副本*other*。

**也可以看看**[toStdMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toStdMultiMap)()。

### `[explicit]`QMultiMap::QMultiMap(std::multimap< Key, T> &&*other*)

通过移动构建多重地图*other*。

**也可以看看**[toStdMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toStdMultiMap)()。

### `[default]`QMultiMap::QMultiMap(const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*other*)

构造一个副本*other*。

此操作发生在[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)，因为 QMultiMap 是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这使得从函数返回 QMultiMap 的速度非常快。如果共享实例被修改，它将被复制（写时复制），这需要[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### `[default]`QMultiMap::QMultiMap([QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &&*other*)

移动构造一个 QMultiMap 实例，使其指向与*other*正在指着。

### `[default]`QMultiMap::~QMultiMap()

破坏多重地图。对多重映射中的值的引用以及该多重映射上的所有迭代器都将变得无效。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::begin()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一项。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::begin() const

这是一个过载功能。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::cbegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[cend](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::cend() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个项目之后的虚构项目。

**也可以看看**[cbegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### void QMultiMap::clear()

从多重地图中删除所有项目。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::constBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::constEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个项目之后的虚构项目。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::constFind(const Key &*key*) const

返回一个 const 迭代器，指向带有 key 的项*key*在多地图中。

如果多图不包含带有键的项目*key*，函数返回[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

**也可以看看**[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)() 和 QMultiMap::constFind()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::constFind(const Key &*key*, const T &*value*) const

返回一个指向带有 key 的项的迭代器*key*和价值*value*在地图中。

如果地图不包含此类项目，则该函数返回[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

**也可以看看**[QMap::constFind](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFind)()。

### [QMultiMap::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QMultiMap::constKeyValueBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一个条目。

**也可以看看**[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)()。

### [QMultiMap::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QMultiMap::constKeyValueEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个条目之后的虚构条目。

**也可以看看**[constKeyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constKeyValueBegin)()。

### bool QMultiMap::contains(const Key &*key*) const

返回`true`多重映射是否包含带有键的项目*key*; 否则返回`false`.

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-2)()。

### bool QMultiMap::contains(const Key &*key*, const T &*value*) const

返回`true`多重映射是否包含带有键的项目*key*和价值*value*; 否则返回`false`.

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-2)()。

### [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::count(const Key &*key*) const

返回与键关联的项目数*key*。

**也可以看看**[contains](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[QMultiMap::count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-2)()。

### [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::count(const Key &*key*, const T &*value*) const

返回带有键的项目数*key*和价值*value*。

**也可以看看**[contains](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[QMultiMap::count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-2)()。

### [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::count() const

这是一个过载功能。

与...一样[size](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### bool QMultiMap::empty() const

提供此函数是为了兼容 STL。它相当于[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()，如果地图为空则返回true；否则返回 false。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::end()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个项目之后的虚构项目。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::end() const

这是一个过载功能。

### QPair< [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QMultiMap::equal_range(const Key &*key*)

返回一对界定值范围的迭代器`[first, second)`，这些值存储在*key*。

### QPair< [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QMultiMap::equal_range(const Key &*key*) const

这是一个过载功能。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::erase([QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *pos*)

删除迭代器指向的（键，值）对*pos*来自多重映射，并返回到映射中下一项的迭代器。

**注意：**迭代器*pos*必须有效且可取消引用。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### `[since 6.0]`[QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::erase([QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *first*, [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *last*)

删除迭代器范围 [ 指向的 (key, value) 对*first*,*last*）来自多地图。返回多重映射中最后一个删除元素后面的项目的迭代器。

**注意：**该范围`[first, last)` *必须*是 中的有效范围`*this`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::find(const Key &*key*)

返回一个指向带有 key 的项的迭代器*key*在多地图中。

如果多图不包含带有键的项目*key*，函数返回[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

如果地图包含多个带有键的项目*key*，此函数返回一个指向最近插入的值的迭代器。其他值可以通过递增迭代器来访问。例如，下面是一些使用相同键迭代所有项目的代码：

```
auto i = multimap.find("plenty");
while (i != map.end() && i.key() == "plenty") {
    cout < <  i.value() < <  endl;
    ++i;
}

// better:
auto [i, end] = multimap.equal_range("plenty");
while (i != end) {
    cout < <  i.value() < <  endl;
    ++i;
}
```

**也可以看看**[constFind](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFind)(),[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)(),[values](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)(),[lowerBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lowerBound)（）， 和[upperBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#upperBound)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::find(const Key &*key*) const

这是一个过载功能。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::find(const Key &*key*, const T &*value*) const

这是一个过载功能。

返回指向具有给定项的常量迭代器*key*和*value*在地图中。

如果地图不包含此类项目，则该函数返回[end](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

如果地图包含多个具有指定的项目*key*，此函数返回一个指向最近插入的值的 const 迭代器。

### T &QMultiMap::first()

返回对多重映射中第一个值的引用，即映射到最小键的值。该函数假设多重映射不为空。

当非共享（或调用 const 版本）时，这会在以下位置执行[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)。

**也可以看看**[last](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)(),[firstKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstKey)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### const T &QMultiMap::first() const

这是一个过载功能。

### const Key &QMultiMap::firstKey() const

返回对多重映射中最小键的引用。该函数假设多重映射不为空。

这执行于[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)。

**也可以看看**[lastKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastKey)(),[first](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)(),[keyBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::insert(const Key &*key*, const T &*value*)

使用 key 插入一个新项目*key*和一个值*value*。

如果地图中已经存在具有相同键的项目，则此函数将简单地创建一个新项目。（此行为不同于[replace](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)()，它会覆盖现有项目的值。）

**也可以看看**[replace](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)()。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::insert([QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *pos*, const Key &*key*, const T &*value*)

这是一个过载功能。

使用 key 插入一个新项目*key*和价值*value*并有提示*pos*建议在哪里进行插入。

如果[constBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)() 用作提示，表示*key*小于多重映射中的任何键，同时[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)() 表明*key*（严格）大于多重映射中的任何键。否则提示应满足条件（*pos*- 1).[key](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)() < *key*< = 位置。[key](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)()。如果提示*pos*是错误的，它会被忽略并完成常规插入。

如果提示正确并且多重映射未共享，则插入按摊销执行[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)。

如果地图中已经存在具有相同键的项目，则此函数将简单地创建一个新项目。

从排序数据创建多重映射时，首先插入最大的键[constBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)() 比按排序顺序插入要快[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)（）， 自从[constEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)() - 1（需要检查提示是否有效）需要[logarithmic time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#logarithmic-time)。

**注意：**请小心提示。从较旧的共享实例提供迭代器可能会崩溃，但也存在一个风险，即它会默默地破坏多重映射和*pos*多地图。

### bool QMultiMap::isEmpty() const

`true`如果多图不包含项目则返回；否则返回 false。

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### Key QMultiMap::key(const T &*value*, const Key &*defaultKey* = Key()) const

这是一个过载功能。

返回第一个有值的键*value*， 或者*defaultKey*如果多重地图不包含有价值的项目*value*。如果不*defaultKey*如果函数返回一个[default-constructed key](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。

这个函数可能会很慢（[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)）， 因为[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的内部数据结构针对按键（而不是按值）快速查找进行了优化。

**也可以看看**[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)（） 和[keys](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)()。

### [QMultiMap::key_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-key-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::keyBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一个键。

**也可以看看**[keyEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)（） 和[firstKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstKey)()。

### [QMultiMap::key_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-key-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::keyEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个键之后的虚构项目。

**也可以看看**[keyBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)（） 和[lastKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastKey)()。

### [QMultiMap::key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_value_iterator-typedef) QMultiMap::keyValueBegin()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一个条目。

**也可以看看**[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)()。

### [QMultiMap::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QMultiMap::keyValueBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中的第一个条目。

**也可以看看**[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)()。

### [QMultiMap::key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_value_iterator-typedef) QMultiMap::keyValueEnd()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个条目之后的虚构条目。

**也可以看看**[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)()。

### [QMultiMap::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QMultiMap::keyValueEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向多重映射中最后一个条目之后的虚构条目。

**也可以看看**[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key> QMultiMap::keys() const

返回一个列表，其中包含按升序排列的多重映射中的所有键。在多重映射中多次出现的键也会在列表中多次出现。

保证与使用的顺序相同[values](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)()。

该函数创建一个新列表，在[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)。可以通过迭代来避免所需的时间和内存使用[keyBegin](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)（） 到[keyEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)()。

**也可以看看**[values](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)（） 和[key](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key> QMultiMap::keys(const T &*value*) const

这是一个过载功能。

返回包含与值关联的所有键的列表*value*按升序排列。

这个函数可能会很慢（[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)）， 因为[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的内部数据结构针对按键（而不是按值）快速查找进行了优化。

### T &QMultiMap::last()

返回对多重映射中最后一个值的引用，即映射到最大键的值。该函数假设地图不为空。

当非共享（或调用 const 版本）时，这会在以下位置执行[logarithmic time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#logarithmic-time)。

**也可以看看**[first](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#first)(),[lastKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastKey)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### const T &QMultiMap::last() const

这是一个过载功能。

### const Key &QMultiMap::lastKey() const

返回对多重映射中最大键的引用。该函数假设多重映射不为空。

这执行于[logarithmic time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#logarithmic-time)。

**也可以看看**[firstKey](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstKey)(),[last](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#last)(),[keyEnd](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)（）， 和[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::lowerBound(const Key &*key*)

返回一个指向第一个带有 key 的项目的迭代器*key*在地图中。如果地图不包含带有键的项目*key*，该函数返回一个迭代器，指向具有更大键的最近项。

例子：

```
QMultiMap< int, QString> multimap;
multimap.insert(1, "one");
multimap.insert(5, "five");
multimap.insert(5, "five (2)");
multimap.insert(10, "ten");

multimap.lowerBound(0);      // returns iterator to (1, "one")
multimap.lowerBound(1);      // returns iterator to (1, "one")
multimap.lowerBound(2);      // returns iterator to (5, "five")
multimap.lowerBound(5);      // returns iterator to (5, "five")
multimap.lowerBound(6);      // returns iterator to (10, "ten")
multimap.lowerBound(10);     // returns iterator to (10, "ten")
multimap.lowerBound(999);    // returns end()
```

如果地图包含多个带有键的项目*key*，此函数返回一个指向最近插入的值的迭代器。其他值可以通过递增迭代器来访问。例如，下面是一些使用相同键迭代所有项目的代码：

```
QMap< QString, int> multimap;
...
QMap< QString, int>::const_iterator i = multimap.lowerBound("HDR");
QMap< QString, int>::const_iterator upperBound = multimap.upperBound("HDR");
while (i != upperBound) {
    cout < <  i.value() < <  endl;
    ++i;
}
```

**也可以看看**[upperBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#upperBound)（） 和[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::lowerBound(const Key &*key*) const

这是一个过载功能。

### [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::remove(const Key &*key*)

删除所有具有该密钥的项目*key*从多地图。返回删除的项目数。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)（） 和[take](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)()。

### [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::remove(const Key &*key*, const T &*value*)

删除所有具有该密钥的项目*key*和价值*value*从多地图。返回删除的项目数。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)（） 和[take](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)()。

### `[since 6.1]`template < typename Predicate> [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::removeIf(Predicate *pred*)

删除谓词所属的所有元素*pred*从多重映射返回 true。

该函数支持采用 type 参数`QMultiMap< Key, T>::iterator`或 type 参数的谓词`std::pair< const Key &, T &>`。

返回删除的元素数（如果有）。

该功能是在 Qt 6.1 中引入的。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)（） 和[take](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)()。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::replace(const Key &*key*, const T &*value*)

使用 key 插入一个新项目*key*和一个值*value*。

如果已经有一个带有该密钥的项目*key*，该项目的值被替换为*value*。

如果有多个带有该密钥的项目*key*，最近插入的项目的值被替换为*value*。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### [QMultiMap::size_type](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef) QMultiMap::size() const

返回多重映射中的（键，值）对的数量。

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[count](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-2)()。

### `[noexcept]`void QMultiMap::swap([QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*other*)

交换多张地图*other*有了这个多地图。这个操作非常快并且永远不会失败。

### T QMultiMap::take(const Key &*key*)

用钥匙移除物品*key*来自多重映射并返回与其关联的值。

如果该项目不存在于多重映射中，该函数仅返回一个[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。如果有多个项目*key*在映射中，仅删除并返回最近插入的一个。

如果不使用返回值，[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)() 效率更高。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### std::multimap< Key, T> QMultiMap::toStdMultiMap() const &

返回与此等效的 STL 多重映射[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key> QMultiMap::uniqueKeys() const

返回一个列表，其中包含映射中按升序排列的所有键。在映射中多次出现的键在返回的列表中仅出现一次。

### [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &QMultiMap::unite(const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*other*)

将所有项目插入*other*映射到这张地图中。如果两个映射都有一个键，则生成的映射将多次包含该键。

### [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &QMultiMap::unite([QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &&*other*)

将所有项目从*other*映射到这张地图中。如果两个映射都有一个键，则生成的映射将多次包含该键。

如果*other*被共享，则项目将被复制。

### [QMultiMap::iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::upperBound(const Key &*key*)

返回一个迭代器，指向紧随最后一个带有 key 的项目之后的项目*key*在地图中。如果地图不包含带有键的项目*key*，该函数返回一个迭代器，指向具有更大键的最近项。

例子：

```
QMultiMap< int, QString> multimap;
multimap.insert(1, "one");
multimap.insert(5, "five");
multimap.insert(5, "five (2)");
multimap.insert(10, "ten");

multimap.upperBound(0);      // returns iterator to (1, "one")
multimap.upperBound(1);      // returns iterator to (5, "five")
multimap.upperBound(2);      // returns iterator to (5, "five")
multimap.lowerBound(5);      // returns iterator to (5, "five (2)")
multimap.lowerBound(6);      // returns iterator to (10, "ten")
multimap.upperBound(10);     // returns end()
multimap.upperBound(999);    // returns end()
```

**也可以看看**[lowerBound](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lowerBound)（） 和[find](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)()。

### [QMultiMap::const_iterator](https://doc-qt-io.translate.goog/qt-6/qmultimap-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMultiMap::upperBound(const Key &*key*) const

这是一个过载功能。

### T QMultiMap::value(const Key &*key*, const T &*defaultValue* = T()) const

返回与键关联的值*key*。

如果多图不包含带有键的项目*key*，函数返回*defaultValue*。如果不*defaultValue*被指定，该函数返回一个[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。如果有多个项目*key*在多映射中，返回最近插入的值。

**也可以看看**[key](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)(),[values](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)（）， 和[contains](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> QMultiMap::values() const

返回包含映射中所有值的列表，按键的升序排列。如果一个键与多个值关联，则其所有值都将出现在列表中，而不仅仅是最近插入的值。

**也可以看看**[keys](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< T> QMultiMap::values(const Key &*key*) const

返回包含与键关联的所有值的列表*key*，从最近插入的到最近最少插入的。

**也可以看看**[keys](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

### `[default]`[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &QMultiMap::operator=(const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*other*)

分配*other*到此多重映射并返回对此多重映射的引用。

### `[default]`[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &QMultiMap::operator=([QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &&*other*)

移动分配*other*对此[QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

## 相关非会员

### `[since 6.1]`template < typename Key, typename T, typename Predicate> qsizetype erase_if([QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*map*, Predicate *pred*)

删除谓词所属的所有元素*pred*从多重映射返回 true*map*。

该函数支持采用 type 参数`QMultiMap< Key, T>::iterator`或 type 参数的谓词`std::pair< const Key &, T &>`。

返回删除的元素数（如果有）。

该功能是在 Qt 6.1 中引入的。

### bool operator!=(const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*lhs*, const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*rhs*)

返回`true`如果*lhs*不等于*rhs*; 否则返回`false`.

如果两个多重映射包含相同的（键，值）对且顺序相同（这对于重复键很重要），则它们被视为相等。

该功能需要键和值类型来实现`operator==()`。

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### template < typename Key, typename T> [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> operator+(const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*lhs*, const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*rhs*)

返回一个包含所有项目的地图*lhs*地图除了所有项目*rhs*。如果两个映射都有一个键，则生成的映射将多次包含该键。

**也可以看看**[operator+=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b-eq)()。

### template < typename Key, typename T> [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> operator+=([QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*lhs*, const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*rhs*)

将所有项目插入*rhs*映射到*lhs*映射并返回结果映射。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)（） 和[operator+](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-2b)()。

### template < typename Key, typename T> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator< < ([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*out*, const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*map*)

写入多图*map*流式传输*out*。

该功能需要键和值类型来实现`operator< < ()`。

**也可以看看**[Format of the QDataStream operators](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### bool operator==(const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*lhs*, const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*rhs*)

返回`true`如果*lhs*等于*rhs*; 否则返回 false。

如果两个多重映射包含相同的（键，值）对且顺序相同（这对于重复键很重要），则它们被视为相等。

该功能需要键和值类型来实现`operator==()`。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

### template < typename Key, typename T> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*in*, [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMultiMap)< Key, T> &*map*)

从流中读取地图*in*进入*map*。

该功能需要键和值类型来实现`operator>>()`。

**也可以看看**[Format of the QDataStream operators](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。