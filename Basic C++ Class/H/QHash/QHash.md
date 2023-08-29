# QHash Class

template <typename Key, typename T> class QHash

QHash 类是一个模板类，它提供基于哈希表的字典。[更多的...](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include <QHash>                                             |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:  | QT += core                                                   |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qhash-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qhash-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QHash 是[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
| class | **[iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| class | **[key_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-key-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
|       | **[ConstIterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ConstIterator-typedef)** |
|       | **[Iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Iterator-typedef)** |
|       | **[const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef)** |
|       | **[difference_type](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#difference_type-typedef)** |
|       | **[key_type](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_type-typedef)** |
|       | **[key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_value_iterator-typedef)** |
|       | **[mapped_type](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapped_type-typedef)** |
|       | **[size_type](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size_type-typedef)** |

## 公共职能

|                                 | **[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)**() |
| ------------------------------- | ------------------------------------------------------------ |
|                                 | **[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash-1)**(std::initializer_list<std::pair<Key, T>> *list*) |
|                                 | **[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash-2)**(const QHash<Key, T> &*other*) |
|                                 | **[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash-3)**(QHash<Key, T> &&*other*) |
|                                 | **[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash-4)**(InputIterator *begin*, InputIterator *end*) |
|                                 | **[~QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QHash)**() |
| auto                            | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange)**() & |
| auto                            | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange-1)**() const & |
| auto                            | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange-2)**() && |
| auto                            | **[asKeyValueRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#asKeyValueRange-3)**() const && |
| QHash::iterator                 | **[begin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() |
| QHash::const_iterator           | **[begin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin-1)**() const |
| qsizetype                       | **[capacity](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)**() const |
| QHash::const_iterator           | **[cbegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)**() const |
| QHash::const_iterator           | **[cend](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)**() const |
| void                            | **[clear](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| QHash::const_iterator           | **[constBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)**() const |
| QHash::const_iterator           | **[constEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)**() const |
| QHash::const_iterator           | **[constFind](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constFind)**(const Key &*key*) const |
| QHash::const_key_value_iterator | **[constKeyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constKeyValueBegin)**() const |
| QHash::const_key_value_iterator | **[constKeyValueEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constKeyValueEnd)**() const |
| bool                            | **[contains](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)**(const Key &*key*) const |
| qsizetype                       | **[count](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**(const Key &*key*) const |
| qsizetype                       | **[count](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)**() const |
| QHash::iterator                 | **[emplace](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplace)**(const Key &*key*, Args &&... *args*) |
| QHash::iterator                 | **[emplace](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#emplace-1)**(Key &&*key*, Args &&... *args*) |
| bool                            | **[empty](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#empty)**() const |
| QHash::iterator                 | **[end](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() |
| QHash::const_iterator           | **[end](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end-1)**() const |
| QHash::iterator                 | **[erase](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase)**(QHash::const_iterator *pos*) |
| QHash::iterator                 | **[find](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)**(const Key &*key*) |
| QHash::const_iterator           | **[find](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-1)**(const Key &*key*) const |
| QHash::iterator                 | **[insert](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)**(const Key &*key*, const T &*value*) |
| void                            | **[insert](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert-1)**(const QHash<Key, T> &*other*) |
| bool                            | **[isEmpty](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)**() const |
| Key                             | **[key](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)**(const T &*value*) const |
| Key                             | **[key](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key-1)**(const T &*value*, const Key &*defaultKey*) const |
| QHash::key_iterator             | **[keyBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)**() const |
| QHash::key_iterator             | **[keyEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)**() const |
| QHash::key_value_iterator       | **[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)**() |
| QHash::const_key_value_iterator | **[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin-1)**() const |
| QHash::key_value_iterator       | **[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)**() |
| QHash::const_key_value_iterator | **[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd-1)**() const |
| QList< Key>                     | **[keys](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)**() const |
| QList< Key>                     | **[keys](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys-1)**(const T &*value*) const |
| float                           | **[load_factor](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#load_factor)**() const |
| bool                            | **[remove](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)**(const Key &*key*) |
| qsizetype                       | **[removeIf](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeIf)**(Predicate *pred*) |
| void                            | **[reserve](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)**(qsizetype *size*) |
| qsizetype                       | **[size](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)**() const |
| void                            | **[squeeze](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)**() |
| void                            | **[swap](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QHash<Key, T> &*other*) |
| T                               | **[take](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)**(const Key &*key*) |
| T                               | **[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)**(const Key &*key*) const |
| T                               | **[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-1)**(const Key &*key*, const T &*defaultValue*) const |
| QList<  T>                      | **[values](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)**() const |
| bool                            | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QHash<Key, T> &*other*) const |
| QHash<Key, T> &                 | **[operator=](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QHash<Key, T> &*other*) |
| QHash<Key, T> &                 | **[operator=](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(QHash<Key, T> &&*other*) |
| bool                            | **[operator==](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QHash<Key, T> &*other*) const |
| T &                             | **[operator[\]](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)**(const Key &*key*) |
| const T                         | **[operator[\]](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d-1)**(const Key &*key*) const |

## 相关非成员

| qsizetype     | **[erase_if](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#erase_if)**(QHash<Key, T> &*hash*, Predicate *pred*) |
| ------------- | ------------------------------------------------------------ |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)**(const QUrl &*url*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash)**(const QStringRef &*key*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash)**(const QMqttTopicFilter &*filter*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash)**(const QOcspResponse &*response*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash)**(const QGeoCoordinate &*coordinate*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-1x)**(const QDateTime &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-1)**(const QMqttTopicName &*name*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-1)**(const QSslCertificate &*key*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-2x)**(QDate *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-2)**(QSslEllipticCurve *curve*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-3x)**(QTime *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-3)**(const QSslError &*key*, size_t *seed*) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-4x)**(const std::pair<T1, T2> &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-5)**(char *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-6)**(uchar *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-7)**(signed char *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-8)**(ushort *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-9)**(short *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-10)**(uint *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-11)**(int *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-12)**(ulong *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-13)**(long *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-14)**(quint64 *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-15)**(qint64 *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-16)**(char8_t *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-17)**(char16_t *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-18)**(char32_t *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-19)**(wchar_t *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-20)**(float *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-21)**(double *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-22)**(long double *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-23)**(const QChar *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-24)**(const QByteArray &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-25)**(const QBitArray &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-26)**(const QString &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-27)**(QLatin1StringView *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-28)**(const T **key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-29)**(std::nullptr_t *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-30)**(const QHash<Key, T> &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-31)**(QPoint *key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-32)**(const QSet<  T> &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-33)**(const QVersionNumber &*key*, size_t *seed* = 0) |
| size_t        | **[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHash-34)**(const QTypeRevision &*key*, size_t *seed* = 0) |
| size_t        | **[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)**(const void **p*, size_t *len*, size_t *seed* = 0) |
| size_t        | **[qHashMulti](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMulti)**(size_t *seed*, const T &... *args*) |
| size_t        | **[qHashMultiCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMultiCommutative)**(size_t *seed*, const T &... *args*) |
| size_t        | **[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)**(InputIterator *first*, InputIterator *last*, size_t *seed* = 0) |
| size_t        | **[qHashRangeCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRangeCommutative)**(InputIterator *first*, InputIterator *last*, size_t *seed* = 0) |
| QDataStream & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QDataStream &*out*, const QHash<Key, T> &*hash*) |
| QDataStream & | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*in*, QHash<Key, T> &*hash*) |

## 详细说明

QHash<Key, T> 是 Qt 的泛型之一[container classes](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它存储（键，值）对并提供与键关联的值的快速查找。

QHash 提供了非常相似的功能[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。差异是：

- QHash 提供比[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。（看[Algorithmic Complexity](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity)了解详情。）
- 当迭代一个[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，项目始终按键排序。使用 QHash，项目是任意排序的。
- a 的密钥类型[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)必须提供运算符<()。QHash 的键类型必须提供operator==() 和一个名为的全局哈希函数[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)（） （看[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)）。

这是一个 QHash 示例[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)键和`int`值：

```
QHash<QString, int> hash;
```

要将（键，值）对插入到哈希中，可以使用operator[] ()：

```
hash["one"] = 1;
hash["three"] = 3;
hash["seven"] = 7;
```

这会将以下三个（键，值）对插入到 QHash 中：（“一”，1）、（“三”，3）和（“七”，7）。将项目插入哈希的另一种方法是使用[insert](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()：

```
hash.insert("twelve", 12);
```

要查找值，请使用运算符[] () 或[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()：

```
int num1 = hash["thirteen"];
int num2 = hash.value("thirteen");
```

如果哈希中不存在具有指定键的项目，这些函数将返回[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。

如果您想检查哈希是否包含特定键，请使用[contains](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()：

```
int timeout = 30;
if (hash.contains("TIMEOUT"))
    timeout = hash.value("TIMEOUT");
```

还有一个[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)() 重载，如果没有具有指定键的项目，则使用第二个参数作为默认值：

```
int timeout = hash.value("TIMEOUT", 30);
```

一般来说，我们建议您使用[contains](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)() 而不是用operator[] () 在哈希中查找键。原因是，如果不存在具有相同键的项（除非散列是 const），则operator[] () 会默默地将一个项插入到散列中。例如，以下代码片段将在内存中创建 1000 个项目：

```
// WRONG
QHash<int, QWidget *> hash;
...
for (int i = 0; i < 1000; ++i) {
    if (hash[i] == okButton)
        cout << "Found button at index " << i << endl;
}
```

为了避免这个问题，请在上面的代码中替换`hash[i]`为。`hash.value(i)`

在内部，QHash 使用哈希表来执行查找。该哈希表会自动增长以提供快速查找，而不会浪费太多内存。您仍然可以通过调用来控制哈希表的大小[reserve](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)() 如果您已经知道 QHash 将包含大约多少项，但这对于获得良好的性能不是必需的。您也可以致电[capacity](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)() 检索哈希表的大小。

如果从表中删除项目，QHash 不会自动收缩。要最小化哈希使用的内存，请调用[squeeze](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

如果要浏览 QHash 中存储的所有（键，值）对，可以使用迭代器。QHash 两者都提供[Java-style iterators](https://doc-qt-io.translate.goog/qt-6/java-style-iterators.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#java-style-iterators)（[QHashIterator](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QMutableHashIterator](https://doc-qt-io.translate.goog/qt-6/qmutablehashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)） 和[STL-style iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)（[QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。以下是如何迭代 QHash<[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), int> 使用 Java 风格的迭代器：

```
QHashIterator<QString, int> i(hash);
while (i.hasNext()) {
    i.next();
    cout << qPrintable(i.key()) << ": " << i.value() << endl;
}
```

下面是相同的代码，但使用了 STL 风格的迭代器：

```
for (auto i = hash.cbegin(), end = hash.cend(); i != end; ++i)
    cout << qPrintable(i.key()) << ": " << i.value() << endl;
```

QHash 是无序的，因此不能假设迭代器的序列是可预测的。如果需要按键订购，请使用[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QHash 只允许每个键有一个值。如果你打电话[insert](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)() 使用 QHash 中已存在的键，之前的值将被删除。例如：

```
hash.insert("plenty", 100);
hash.insert("plenty", 2000);
// hash.value("plenty") == 2000
```

如果需要在哈希表中存储同一个键的多个条目，请使用[QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

如果您只需要从哈希中提取值（而不是键），您还可以使用基于范围：

```
QHash<QString, int> hash;
...
for (int value : std::as_const(hash))
    cout << value << endl;
```

可以通过多种方式从哈希中删除项目。一种方法是打电话[remove](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)(); 这将删除具有给定密钥的任何项目。另一种方法是使用[QMutableHashIterator::remove](https://doc-qt-io.translate.goog/qt-6/qmutablehashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。此外，您可以使用以下命令清除整个哈希值[clear](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

QHash 的 key 和 value 数据类型必须是[assignable data types](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#assignable-data-types)。例如，您不能存储[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为一个值；相反，存储一个[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*。



#### 哈希函数

QHash 的键类型除了是可分配的数据类型之外还有其他要求：它必须提供运算符 ==()，并且还必须有一个哈希函数，该函数为键类型的参数返回哈希值。

散列函数根据键计算数值。它可以使用任何可以想象的算法，只要给定相同的参数它总是返回相同的值。换句话说，如果`e1 == e2`，则`hash(e1) == hash(e2)`也必须成立。然而，为了获得良好的性能，哈希函数应尽可能尝试为不同的键返回不同的哈希值。

`K`可以以两种不同的方式提供密钥类型的散列函数。

第一种方法是重载`qHash()`in`K`的命名空间。该`qHash()`函数必须具有以下签名之一：

```
size_t qHash(K key, size_t seed);
size_t qHash(const K &key, size_t seed);

size_t qHash(K key);        // deprecated, do not use
size_t qHash(const K &key); // deprecated, do not use
```

双参数重载采用无符号整数，该整数应用于散列函数的计算。该种子由 QHash 提供，旨在防止一系列[algorithmic complexity attacks](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity-attacks)。

**注意：**在 Qt 6 中，可以定义`qHash()`仅采用一个参数的重载；对此的支持已被弃用。从 Qt 7 开始，将强制使用两个参数重载。如果为某个键类型同时定义了单参数和双参数重载，则 QHash 将使用后者（请注意，您可以简单地定义双参数版本，并使用种子参数的默认值）。

提供哈希函数的第二种方法是通过专门化`std::hash`键类型的类`K`，并为其提供合适的函数调用运算符：

```
namespace std {
template <> struct hash<K>
{
    // seed is optional
    size_t operator()(const K &key, size_t seed = 0) const;
};
}
```

种子参数与 的含义相同`qHash()`，可以省略。

第二种方式允许在 QHash 和 C++ 标准库无序关联容器之间重用相同的哈希函数。如果为某个类型同时提供了`qHash()`重载和`std::hash`特化，则`qHash()`首选重载。

以下是可用作 QHash 中键的 C++ 和 Qt 类型的部分列表：任何整数类型（char、unsigned long 等）、任何指针类型、[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。对于所有这些，`<QHash>`标头定义了一个[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 函数计算适当的哈希值。许多其他 Qt 类也声明了[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)其类型的重载；请参阅每个类的文档。

如果您想使用其他类型作为键，请确保提供operator==() 和哈希实现。

便利性[qHashMulti](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMulti)可以使用()函数来实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 对于自定义类型，通常希望从多个字段生成哈希值：

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

inline bool operator==(const Employee &e1, const Employee &e2)
{
    return e1.name() == e2.name()
           && e1.dateOfBirth() == e2.dateOfBirth();
}

inline size_t qHash(const Employee &key, size_t seed)
{
    return qHashMulti(seed, key.name(), key.dateOfBirth());
}

#endif // EMPLOYEE_H
```

在上面的例子中，我们依赖于 Qt 自己的实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)（） 为了[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)分别为我们提供员工姓名和出生日期的哈希值。

请注意，实施[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)Qt 提供的 () 重载可能随时更改。你**不能**依赖这样的事实：[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 将在不同的 Qt 版本中给出相同的结果（对于相同的输入）。

#### 算法复杂性攻击

所有哈希表都容易受到特定类别的拒绝服务攻击，其中攻击者仔细地预先计算一组不同的密钥，这些密钥将在哈希表的同一存储桶中进行哈希处理（甚至具有完全相同的哈希值）价值）。该攻击旨在获得最坏情况的算法行为（O(n) 而不是摊销 O(1)，请参阅[Algorithmic Complexity](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#algorithmic-complexity)了解详细信息）当数据输入表时。

为了避免这种最坏情况的行为，哈希值的计算由[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 可以通过随机种子加盐，从而消除攻击的范围。该种子由 QHash 每个进程自动生成一次，然后由 QHash 作为双参数重载的第二个参数传递。[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)（） 功能。

默认情况下启用 QHash 的这种随机化。尽管程序永远不应该依赖于特定的 QHash 顺序，但在某些情况下您可能暂时需要确定性行为，例如用于调试或回归测试。要禁用随机化，请将环境变量定义`QT_HASH_SEED`为值 0。或者，您可以调用[QHashSeed::setDeterministicGlobalSeed](https://doc-qt-io.translate.goog/qt-6/qhashseed.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDeterministicGlobalSeed)（） 功能。

**也可以看看**[QHashIterator](https://doc-qt-io.translate.goog/qt-6/qhashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QMutableHashIterator](https://doc-qt-io.translate.goog/qt-6/qmutablehashiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QSet](https://doc-qt-io.translate.goog/qt-6/qset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### QHash::ConstIterator

Qt 风格的同义词[QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QHash::Iterator

Qt 风格的同义词[QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### QHash::const_key_value_iterator

QHash::const_key_value_iterator typedef 提供了一个 STL 风格的 const 迭代器[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)。

QHash::const_key_value_iterator 本质上与[QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不同之处在于，operator*() 返回一个键/值对而不是一个值。

**也可以看看**[QKeyValueIterator](https://doc-qt-io.translate.goog/qt-6/qkeyvalueiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QHash::difference_type

ptrdiff_t 的类型定义。提供 STL 兼容性。

### `[alias]`QHash::key_type

键的类型定义。提供 STL 兼容性。

### QHash::key_value_iterator

QHash::key_value_iterator typedef 提供了一个 STL 风格的迭代器[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)。

QHash::key_value_iterator 本质上与[QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不同之处在于，operator*() 返回一个键/值对而不是一个值。

**也可以看看**[QKeyValueIterator](https://doc-qt-io.translate.goog/qt-6/qkeyvalueiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[alias]`QHash::mapped_type

T 的 Typedef。为 STL 兼容性而提供。

### `[alias]`QHash::size_type

typedef 为 int。提供 STL 兼容性。

## 成员函数文档

### T QHash::value(const Key &*key*) const

### T QHash::value(const Key &*key*, const T &*defaultValue*) const

这是一个过载功能。

返回与关联的值*key*。

如果哈希值不包含以下项*key*，函数返回*defaultValue*，或一个[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)如果未提供此参数。

### Key QHash::key(const T &*value*) const

### Key QHash::key(const T &*value*, const Key &*defaultKey*) const

返回映射到的第一个键*value*。如果哈希不包含映射到的项目*value*，返回*defaultKey*，或一个[default-constructed key](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)如果未提供此参数。

这个函数可能会很慢（[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)）， 因为[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部数据结构针对按键（而不是按值）快速查找进行了优化。

### `[since 6.4]`auto QHash::asKeyValueRange() &

### `[since 6.4]`auto QHash::asKeyValueRange() &&

### `[since 6.4]`auto QHash::asKeyValueRange() const &

### `[since 6.4]`auto QHash::asKeyValueRange() const &&

返回一个范围对象，该对象允许以键/值对的形式迭代此哈希。例如，这个范围对象可以在基于范围的 for 循环中与结构化绑定声明结合使用：

```
QHash<QString, int> hash;
hash.insert("January", 1);
hash.insert("February", 2);
// ...
hash.insert("December", 12);

for (auto [key, value] : hash.asKeyValueRange()) {
    cout << qPrintable(key) << ": " << value << endl;
    --value; // convert to JS month indexing
}
```

请注意，通过这种方式获得的键和值都是对哈希中的键和值的引用。具体来说，改变值将修改哈希本身。

该功能是在 Qt 6.4 中引入的。

**也可以看看**[QKeyValueIterator](https://doc-qt-io.translate.goog/qt-6/qkeyvalueiterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template < typename Args> [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::emplace(Key &&*key*, Args &&... *args*)

### template < typename Args> [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::emplace(const Key &*key*, Args &&... *args*)

将新元素插入到容器中。这个新元素是使用就地构建的*args*作为其构建的论据。

返回指向新元素的迭代器。

### QHash::QHash()

构造一个空哈希。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### QHash::QHash(std::initializer_list<std::pair<Key, T>> *list*)

使用初始值设定项列表中每个元素的副本构造一个哈希*list*。

### QHash::QHash(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*other*)

构造一个副本*other*。

此操作发生在[constant time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constant-time)，因为 QHash 是[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这使得从函数返回 QHash 的速度非常快。如果共享实例被修改，它将被复制（写时复制），这需要[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### QHash::QHash([QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &&*other*)

移动构造一个 QHash 实例，使其指向与*other*正在指着。

### template < typename InputIterator> QHash::QHash(InputIterator *begin*, InputIterator *end*)

使用迭代器范围 [ 中每个元素的副本构造一个哈希*begin*,*end*）。范围迭代的元素必须是具有可分别转换为和`first`的`second`数据成员（如`QPair`、`std::pair`等）的对象；或者迭代器必须具有和成员函数，分别返回可转换的键和可转换的值。`Key``T``key()``value()``Key``T`

### QHash::~QHash()

破坏哈希值。对散列中的值以及该散列的所有迭代器的引用都将变得无效。

### [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::begin()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一项。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::begin() const

这是一个过载功能。

### qsizetype QHash::capacity() const

返回桶的数量[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部哈希表。

该函数的唯一目的是提供一种微调的手段[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内存使用情况。一般来说，您很少需要调用此函数。如果您想知道哈希中有多少项，请调用[size](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

**也可以看看**[reserve](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)（） 和[squeeze](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::cbegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[cend](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cend)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::cend() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一项之后的虚构项。

**也可以看看**[cbegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cbegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### void QHash::clear()

从哈希中删除所有项目并释放其使用的所有内存。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::constBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::constEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一项之后的虚构项。

**也可以看看**[constBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constBegin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::constFind(const Key &*key*) const

返回一个指向具有以下项的迭代器*key*在哈希中。

如果哈希值不包含以下项*key*，函数返回[constEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

**也可以看看**[find](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)()。

### [QHash::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QHash::constKeyValueBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一个条目。

**也可以看看**[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)()。

### [QHash::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QHash::constKeyValueEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一个条目之后的虚构条目。

**也可以看看**[constKeyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constKeyValueBegin)()。

### bool QHash::contains(const Key &*key*) const

`true`如果散列包含带有以下项的项目，则返回*key*; 否则返回`false`.

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)（） 和[QMultiHash::contains](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains-1)()。

### qsizetype QHash::count(const Key &*key*) const

返回与关联的项目数*key*。

**也可以看看**[contains](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)()。

### qsizetype QHash::count() const

这是一个过载功能。

与...一样[size](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### bool QHash::empty() const

提供此函数是为了兼容 STL。它相当于[isEmpty](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)()，如果哈希为空则返回true；否则返回`false`.

### [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::end()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一项之后的虚构项。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[constEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#constEnd)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::end() const

这是一个过载功能。

### [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::erase([QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *pos*)

删除与迭代器关联的（键，值）对*pos*从哈希中获取，并返回到哈希中下一项的迭代器。

这个函数永远不会导致[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)重新散列其内部数据结构。这意味着它可以在迭代时安全地调用，并且不会影响哈希中项目的顺序。例如：

```
QHash<QObject *, int> objectHash;
...
QHash<QObject *, int>::iterator i = objectHash.find(obj);
while (i != objectHash.end() && i.key() == obj) {
    if (i.value() == 0) {
        i = objectHash.erase(i);
    } else {
        ++i;
    }
}
```

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)(),[take](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)（）， 和[find](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)()。

### [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::find(const Key &*key*)

返回一个指向具有以下项的迭代器*key*在哈希中。

如果哈希值不包含以下项*key*，函数返回[end](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

如果哈希包含多个项目*key*，此函数返回一个指向最近插入的值的迭代器。其他值可以通过递增迭代器来访问。例如，下面是一些使用相同键迭代所有项目的代码：

```
QHash<QString, int> hash;
...
QHash<QString, int>::const_iterator i = hash.find("HDR");
while (i != hash.end() && i.key() == "HDR") {
    cout << i.value() << endl;
    ++i;
}
```

**也可以看看**[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)（） 和[values](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)()。

### [QHash::const_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-const-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::find(const Key &*key*) const

这是一个过载功能。

### [QHash::iterator](https://doc-qt-io.translate.goog/qt-6/qhash-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::insert(const Key &*key*, const T &*value*)

插入一个新项目*key*和一个值*value*。

如果已经有一个项目带有*key*，该项目的值被替换为*value*。

### void QHash::insert(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*other*)

将所有项目插入*other*散列到这个散列中。

如果两个哈希值共用一个键，则其值将替换为存储在*other*。

### bool QHash::isEmpty() const

`true`如果哈希不包含任何项目，则返回；否则返回 false。

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。

### [QHash::key_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-key-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::keyBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一个键。

**也可以看看**[keyEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)()。

### [QHash::key_iterator](https://doc-qt-io.translate.goog/qt-6/qhash-key-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QHash::keyEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一个键之后的虚构项。

**也可以看看**[keyBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)()。

### [QHash::key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_value_iterator-typedef) QHash::keyValueBegin()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一个条目。

**也可以看看**[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)()。

### [QHash::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QHash::keyValueBegin() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向哈希中的第一个条目。

**也可以看看**[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)()。

### [QHash::key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key_value_iterator-typedef) QHash::keyValueEnd()

返回一个[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一个条目之后的虚构条目。

**也可以看看**[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)()。

### [QHash::const_key_value_iterator](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#const_key_value_iterator-typedef) QHash::keyValueEnd() const

返回一个常量[STL-style iterator](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)指向散列中最后一个条目之后的虚构条目。

**也可以看看**[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key> QHash::keys() const

返回一个列表，其中包含哈希中的所有键（按任意顺序）。

保证与使用的顺序相同[values](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)()。

该函数创建一个新列表，在[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)。可以通过迭代来避免所需的时间和内存使用[keyBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyBegin)（） 到[keyEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyEnd)()。

**也可以看看**[values](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#values)（） 和[key](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< Key> QHash::keys(const T &*value*) const

这是一个过载功能。

返回包含与值关联的所有键的列表*value*，以任意顺序。

这个函数可能会很慢（[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)）， 因为[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部数据结构针对按键（而不是按值）快速查找进行了优化。

### float QHash::load_factor() const

返回当前的负载系数[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部哈希表。这与[capacity](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)()/[size](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。所使用的实现旨在将负载因子保持在 0.25 到 0.5 之间。这可以避免出现太多会降低性能的哈希表冲突。

即使负载因子较低，哈希表的实现也具有非常低的内存开销。

此方法纯粹出于诊断目的而存在，您很少需要自己调用它。

**也可以看看**[reserve](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)（） 和[squeeze](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)()。

### bool QHash::remove(const Key &*key*)

删除具有以下内容的项目*key*来自哈希值。如果散列中存在该键并且该项已被删除，则返回 true，否则返回 false。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)（） 和[take](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)()。

### `[since 6.1]`template < typename Predicate> qsizetype QHash::removeIf(Predicate *pred*)

删除谓词所属的所有元素*pred*从哈希中返回 true。

该函数支持采用 type 参数`QHash<Key, T>::iterator`或 type 参数的谓词`std::pair<const Key &, T &>`。

返回删除的元素数（如果有）。

该功能是在 Qt 6.1 中引入的。

**也可以看看**[clear](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)（） 和[take](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#take)()。

### void QHash::reserve(qsizetype *size*)

确保[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部哈希表至少有空间可以存储*size*项，而无需增加哈希表。

这意味着哈希表将至少包含 2 **size*桶以确保良好的性能

此函数对于需要构建巨大哈希并希望避免重复重新分配的代码非常有用。例如：

```
QHash<QString, int> hash;
hash.reserve(20000);
for (int i = 0; i < 20000; ++i)
    hash.insert(keys[i], values[i]);
```

理想情况下，*size*应该是哈希中预期的最大项目数。[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)然后将选择允许存储的最小可能数量的桶*size*表中的项目，而无需增加内部哈希表。如果*size*被低估了，最糟糕的情况就是[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)会慢一点。

一般来说，您很少需要调用此函数。[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部哈希表会自动增长以提供良好的性能，而不会浪费太多内存。

**也可以看看**[squeeze](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#squeeze)（） 和[capacity](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)()。

### qsizetype QHash::size() const

返回哈希中的项目数。

**也可以看看**[isEmpty](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)（） 和[count](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-1)()。

### void QHash::squeeze()

减小了尺寸[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内部哈希表以节省内存。

该函数的唯一目的是提供一种微调的手段[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)的内存使用情况。一般来说，您很少需要调用此函数。

**也可以看看**[reserve](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reserve)（） 和[capacity](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capacity)()。

### void QHash::swap([QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*other*)

交换哈希值*other*用这个哈希值。这个操作非常快并且永远不会失败。

### T QHash::take(const Key &*key*)

删除项目*key*从哈希中获取并返回与其关联的值。

如果哈希中不存在该项目，该函数将简单地返回一个[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)。

如果不使用返回值，[remove](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)() 效率更高。

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T> QHash::values() const

返回一个列表，其中包含哈希中的所有值（按任意顺序）。

保证与使用的顺序相同[keys](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)()。

该函数创建一个新列表，在[linear time](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#linear-time)。可以通过迭代来避免所需的时间和内存使用[keyValueBegin](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueBegin)（） 到[keyValueEnd](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyValueEnd)()。

**也可以看看**[keys](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keys)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

### bool QHash::operator!=(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*other*) const

返回`true`如果*other*不等于这个哈希值；否则返回`false`.

如果两个哈希包含相同的（键，值）对，则认为它们相等。

该函数需要值类型来实现`operator==()`。

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &QHash::operator=(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*other*)

分配*other*到此哈希并返回对此哈希的引用。

### [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &QHash::operator=([QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &&*other*)

移动分配*other*对此[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)实例。

### bool QHash::operator==(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*other*) const

返回`true`如果*other*等于这个哈希值；否则返回 false。

如果两个哈希包含相同的（键，值）对，则认为它们相等。

该函数需要值类型来实现`operator==()`。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

### T &QHash::operator[] (const Key &*key*)

返回与关联的值*key*作为可修改的参考。

如果哈希值不包含以下项*key*，该函数插入一个[default-constructed value](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-constructed-value)到哈希中*key*，并返回对其的引用。

**也可以看看**[insert](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)（） 和[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

### const T QHash::operator[] (const Key &*key*) const

这是一个过载功能。

与...一样[value](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value)()。

## 相关非成员

### `[since 6.1]`template <typename Key, typename T, typename Predicate> qsizetype erase_if([QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*hash*, Predicate *pred*)

删除谓词所属的所有元素*pred*从哈希值返回 true*hash*。

该函数支持采用 type 参数`QHash<Key, T>::iterator`或 type 参数的谓词`std::pair<const Key &, T &>`。

返回删除的元素数（如果有）。

该功能是在 Qt 6.1 中引入的。

### size_t qHash(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*url*, size_t *seed* = 0)

返回哈希值*url*。如果指定的话，*seed*用于初始化哈希。

### size_t qHash(const [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### template <typename T1, typename T2> size_t qHash(const std::pair<T1, T2> &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

类型`T1`和`T2`必须由 qHash() 支持。

### size_t qHash(char *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([uchar](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uchar-typedef) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(signed char *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([ushort](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ushort-typedef) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(short *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([uint](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uint-typedef) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(int *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([ulong](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ulong-typedef) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(long *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([quint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint64-typedef) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### `[since 6.0]`size_t qHash(char8_t *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### `[since 6.0]`size_t qHash(char16_t *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### `[since 6.0]`size_t qHash(char32_t *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### `[since 6.0]`size_t qHash(wchar_t *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### size_t qHash(float *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(double *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(long double *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(const [QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(const [QBitArray](https://doc-qt-io.translate.goog/qt-6/qbitarray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### size_t qHash([QLatin1StringView](https://doc-qt-io.translate.goog/qt-6/qlatin1stringview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### template < typename T> size_t qHash(const T **key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### `[since 6.0]`size_t qHash(std::nullptr_t *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### template <typename Key, typename T> size_t qHash(const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

类型`T`必须受 qHash() 支持。

### `[since 6.0]`size_t qHash([QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### template < typename T> size_t qHash(const [QSet](https://doc-qt-io.translate.goog/qt-6/qset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T> &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

哈希值与元素的顺序无关*key*，即包含相同元素的集合哈希为相同值。

### size_t qHash(const [QVersionNumber](https://doc-qt-io.translate.goog/qt-6/qversionnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

### `[since 6.0]`size_t qHash(const [QTypeRevision](https://doc-qt-io.translate.goog/qt-6/qtyperevision.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*key*, size_t *seed* = 0)

返回哈希值*key*， 使用*seed*为计算提供种子。

这个函数是在Qt 6.0中引入的。

### size_t qHashBits(const void **p*, size_t *len*, size_t *seed* = 0)

返回 size 内存块的哈希值*len*由 指向*p*， 使用*seed*为计算提供种子。

使用该函数仅用于实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 用于您自己的自定义类型。例如，您可以通过以下方式实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)std::vector<int> 的 () 重载：

```
inline size_t qHash(const std::vector<int> &key, size_t seed = 0)
{
    if (key.empty())
        return seed;
    else
        return qHashBits(&key.front(), key.size() * sizeof(int), seed);
}
```

这利用了 std::vector 连续布置其数据的事实。如果情况并非如此，或者包含的类型有填充，您应该使用[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)（） 反而。

值得重复的是 qHashBits() 的实现 - 就像[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)Qt 提供的 () 重载 - 可能随时更改。您**不能**依赖 qHashBits() 在不同的 Qt 版本中给出相同的结果（对于相同的输入）这一事实。

**也可以看看**[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)（） 和[qHashRangeCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRangeCommutative)()。

### `[constexpr, since 6.0]`template < typename T> size_t qHashMulti(size_t *seed*, const T &... *args*)

返回哈希值*args*， 使用*seed*通过连续应用来播种计算[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 到每个元素并将哈希值组合成一个。

请注意，参数的顺序很重要。如果顺序不重要，请使用[qHashMultiCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMultiCommutative)（） 反而。如果您正在散列原始内存，请使用[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)(); 如果您要散列一个范围，请使用[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)()。

提供这个功能是为了方便实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 用于您自己的自定义类型。例如，您可以通过以下方式实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 类的重载`Employee`：

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

inline bool operator==(const Employee &e1, const Employee &e2)
{
    return e1.name() == e2.name()
           && e1.dateOfBirth() == e2.dateOfBirth();
}

inline size_t qHash(const Employee &key, size_t seed)
{
    return qHashMulti(seed, key.name(), key.dateOfBirth());
}

#endif // EMPLOYEE_H
```

这个函数是在Qt 6.0中引入的。

**也可以看看**[qHashMultiCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMultiCommutative)和[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)。

### `[constexpr, since 6.0]`template < typename T> size_t qHashMultiCommutative(size_t *seed*, const T &... *args*)

返回哈希值*args*， 使用*seed*通过连续应用来播种计算[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 到每个元素并将哈希值组合成一个。

参数的顺序并不重要。如果顺序很重要，请使用[qHashMulti](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMulti)() 相反，因为它可能会产生更好质量的散列。如果您正在散列原始内存，请使用[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)(); 如果您要散列一个范围，请使用[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)()。

提供这个功能是为了方便实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 用于您自己的自定义类型。

这个函数是在Qt 6.0中引入的。

**也可以看看**[qHashMulti](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashMulti)和[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)。

### template < typename InputIterator> size_t qHashRange(InputIterator *first*, InputIterator *last*, size_t *seed* = 0)

返回范围 [ 的哈希值*first*,*last*）， 使用*seed*通过连续应用来播种计算[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 到每个元素并将哈希值组合成一个。

该函数的返回值取决于范围内元素的顺序。这意味着

```
{0, 1, 2}
```

和

```
{1, 2, 0}
```

哈希为**不同的**值。如果顺序不重要（例如对于哈希表），请使用[qHashRangeCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRangeCommutative)（） 反而。如果您正在散列原始内存，请使用[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)()。

使用该函数仅用于实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 用于您自己的自定义类型。例如，您可以通过以下方式实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)std::vector<int> 的 () 重载：

```
inline size_t qHash(const std::vector<int> &key, size_t seed = 0)
{
    return qHashRange(key.begin(), key.end(), seed);
}
```

值得重复的是 qHashRange() 的实现 - 就像[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)Qt 提供的 () 重载 - 可能随时更改。您**不能**依赖 qHashRange() 在不同的 Qt 版本中给出相同的结果（对于相同的输入），即使[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 表示元素类型。

**也可以看看**[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)（） 和[qHashRangeCommutative](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRangeCommutative)()。

### template < typename InputIterator> size_t qHashRangeCommutative(InputIterator *first*, InputIterator *last*, size_t *seed* = 0)

返回范围 [ 的哈希值*first*,*last*）， 使用*seed*通过连续应用来播种计算[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 到每个元素并将哈希值组合成一个。

该函数的返回值不取决于范围内元素的顺序。这意味着

```
{0, 1, 2}
```

和

```
{1, 2, 0}
```

散列到**相同的**值。如果顺序很重要，例如，对于向量和数组，请使用[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)（） 反而。如果您正在散列原始内存，请使用[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)()。

使用该函数仅用于实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 用于您自己的自定义类型。例如，您可以通过以下方式实现[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)std::unordered_set<int> 的 () 重载：

```
inline size_t qHash(const std::unordered_set<int> &key, size_t seed = 0)
{
    return qHashRangeCommutative(key.begin(), key.end(), seed);
}
```

值得重复的是 qHashRangeCommutative() 的实现 - 就像[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)Qt 提供的 () 重载 - 可能随时更改。您**不能**依赖 qHashRangeCommutative() 在不同的 Qt 版本中给出相同的结果（对于相同的输入）的事实，即使[qHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashx)() 表示元素类型。

**也可以看看**[qHashBits](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashBits)（） 和[qHashRange](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qHashRange)()。

### template <typename Key, typename T> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator<<([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*out*, const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*hash*)

写入哈希值*hash*流式传输*out*。

该功能需要键和值类型来实现`operator<<()`。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename Key, typename T> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*in*, [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QHash)<Key, T> &*hash*)

从流中读取哈希值*in*进入*hash*。

该功能需要键和值类型来实现`operator>>()`。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。