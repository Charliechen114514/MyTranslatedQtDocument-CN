#  QAbstractItemModel Class

QAbstractItemModel 类提供项目模型类的抽象接口。[更多的...](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QAbstractItemModel>                               |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:        | QT += core                                                   |
| Inherits:     | [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QAbstractItemModelReplica](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodelreplica.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QAbstractListModel](https://doc-qt-io.translate.goog/qt-6/qabstractlistmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QAbstractProxyModel](https://doc-qt-io.translate.goog/qt-6/qabstractproxymodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QAbstractTableModel](https://doc-qt-io.translate.goog/qt-6/qabstracttablemodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QConcatenateTablesProxyModel](https://doc-qt-io.translate.goog/qt-6/qconcatenatetablesproxymodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QFileSystemModel](https://doc-qt-io.translate.goog/qt-6/qfilesystemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QHelpContentModel](https://doc-qt-io.translate.goog/qt-6/qhelpcontentmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QPdfBookmarkModel](https://doc-qt-io.translate.goog/qt-6/qpdfbookmarkmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QStandardItemModel](https://doc-qt-io.translate.goog/qt-6/qstandarditemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum class | **[CheckIndexOption](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckIndexOption-enum)** { NoOption, IndexIsValid, DoNotUseParent, ParentIsInvalid } |
| ---------- | ------------------------------------------------------------ |
| flags      | **[CheckIndexOptions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckIndexOption-enum)** |
| enum       | **[LayoutChangeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutChangeHint-enum)** { NoLayoutChangeHint, VerticalSortHint, HorizontalSortHint } |

## 公共职能

|                                 | **[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QAbstractItemModel)**(QObject **parent* = nullptr) |
| ------------------------------- | ------------------------------------------------------------ |
| virtual                         | **[~QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QAbstractItemModel)**() |
| virtual QModelIndex             | **[buddy](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buddy)**(const QModelIndex &*index*) const |
| virtual bool                    | **[canDropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canDropMimeData)**(const QMimeData **data*, Qt::DropAction *action*, int *row*, int *column*, const QModelIndex &*parent*) const |
| virtual bool                    | **[canFetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canFetchMore)**(const QModelIndex &*parent*) const |
| bool                            | **[checkIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkIndex)**(const QModelIndex &*index*, QAbstractItemModel::CheckIndexOptions *options* = CheckIndexOption::NoOption) const |
| virtual bool                    | **[clearItemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearItemData)**(const QModelIndex &*index*) |
| virtual int                     | **[columnCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)**(const QModelIndex &*parent* = QModelIndex()) const = 0 |
| virtual QVariant                | **[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)**(const QModelIndex &*index*, int *role* = Qt::DisplayRole) const = 0 |
| virtual bool                    | **[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)**(const QMimeData **data*, Qt::DropAction *action*, int *row*, int *column*, const QModelIndex &*parent*) |
| virtual void                    | **[fetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)**(const QModelIndex &*parent*) |
| virtual Qt::ItemFlags           | **[flags](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)**(const QModelIndex &*index*) const |
| virtual bool                    | **[hasChildren](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasChildren)**(const QModelIndex &*parent* = QModelIndex()) const |
| bool                            | **[hasIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasIndex)**(int *row*, int *column*, const QModelIndex &*parent* = QModelIndex()) const |
| virtual QVariant                | **[headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)**(int *section*, Qt::Orientation *orientation*, int *role* = Qt::DisplayRole) const |
| virtual QModelIndex             | **[index](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#index)**(int *row*, int *column*, const QModelIndex &*parent* = QModelIndex()) const = 0 |
| bool                            | **[insertColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumn)**(int *column*, const QModelIndex &*parent* = QModelIndex()) |
| virtual bool                    | **[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)**(int *column*, int *count*, const QModelIndex &*parent* = QModelIndex()) |
| bool                            | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)**(int *row*, const QModelIndex &*parent* = QModelIndex()) |
| virtual bool                    | **[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)**(int *row*, int *count*, const QModelIndex &*parent* = QModelIndex()) |
| virtual QMap< int, QVariant>    | **[itemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemData)**(const QModelIndex &*index*) const |
| virtual QModelIndexList         | **[match](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#match)**(const QModelIndex &*start*, int *role*, const QVariant &*value*, int *hits* = 1, Qt::MatchFlags *flags* = Qt::MatchFlags(Qt::MatchStartsWith\|Qt::MatchWrap)) const |
| virtual QMimeData *             | **[mimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)**(const QModelIndexList &*indexes*) const |
| virtual QStringList             | **[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)**() const |
| bool                            | **[moveColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveColumn)**(const QModelIndex &*sourceParent*, int *sourceColumn*, const QModelIndex &*destinationParent*, int *destinationChild*) |
| virtual bool                    | **[moveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveColumns)**(const QModelIndex &*sourceParent*, int *sourceColumn*, int *count*, const QModelIndex &*destinationParent*, int *destinationChild*) |
| bool                            | **[moveRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveRow)**(const QModelIndex &*sourceParent*, int *sourceRow*, const QModelIndex &*destinationParent*, int *destinationChild*) |
| virtual bool                    | **[moveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveRows)**(const QModelIndex &*sourceParent*, int *sourceRow*, int *count*, const QModelIndex &*destinationParent*, int *destinationChild*) |
| virtual void                    | **[multiData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#multiData)**(const QModelIndex &*index*, QModelRoleDataSpan *roleDataSpan*) const |
| virtual QModelIndex             | **[parent](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)**(const QModelIndex &*index*) const = 0 |
| bool                            | **[removeColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumn)**(int *column*, const QModelIndex &*parent* = QModelIndex()) |
| virtual bool                    | **[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)**(int *column*, int *count*, const QModelIndex &*parent* = QModelIndex()) |
| bool                            | **[removeRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)**(int *row*, const QModelIndex &*parent* = QModelIndex()) |
| virtual bool                    | **[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)**(int *row*, int *count*, const QModelIndex &*parent* = QModelIndex()) |
| virtual QHash< int, QByteArray> | **[roleNames](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#roleNames)**() const |
| virtual int                     | **[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)**(const QModelIndex &*parent* = QModelIndex()) const = 0 |
| virtual bool                    | **[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)**(const QModelIndex &*index*, const QVariant &*value*, int *role* = Qt::EditRole) |
| virtual bool                    | **[setHeaderData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderData)**(int *section*, Qt::Orientation *orientation*, const QVariant &*value*, int *role* = Qt::EditRole) |
| virtual bool                    | **[setItemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemData)**(const QModelIndex &*index*, const QMap< int, QVariant> &*roles*) |
| virtual QModelIndex             | **[sibling](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sibling)**(int *row*, int *column*, const QModelIndex &*index*) const |
| virtual void                    | **[sort](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sort)**(int *column*, Qt::SortOrder *order* = Qt::AscendingOrder) |
| virtual QSize                   | **[span](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#span)**(const QModelIndex &*index*) const |
| virtual Qt::DropActions         | **[supportedDragActions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDragActions)**() const |
| virtual Qt::DropActions         | **[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)**() const |

## 公共老虎机

| virtual void | **[revert](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revert)**() |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[submit](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#submit)**() |

## 信号

| void | **[columnsAboutToBeInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsAboutToBeInserted)**(const QModelIndex &*parent*, int *first*, int *last*) |
| ---- | ------------------------------------------------------------ |
| void | **[columnsAboutToBeMoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsAboutToBeMoved)**(const QModelIndex &*sourceParent*, int *sourceStart*, int *sourceEnd*, const QModelIndex &*destinationParent*, int *destinationColumn*) |
| void | **[columnsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsAboutToBeRemoved)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void | **[columnsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsInserted)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void | **[columnsMoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsMoved)**(const QModelIndex &*sourceParent*, int *sourceStart*, int *sourceEnd*, const QModelIndex &*destinationParent*, int *destinationColumn*) |
| void | **[columnsRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsRemoved)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void | **[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)**(const QModelIndex &*topLeft*, const QModelIndex &*bottomRight*, const QList< int> &*roles* = QList< int>()) |
| void | **[headerDataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerDataChanged)**(Qt::Orientation *orientation*, int *first*, int *last*) |
| void | **[layoutAboutToBeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutAboutToBeChanged)**(const QList< QPersistentModelIndex> &*parents* = QList< QPersistentModelIndex>(), QAbstractItemModel::LayoutChangeHint *hint* = QAbstractItemModel::NoLayoutChangeHint) |
| void | **[layoutChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutChanged)**(const QList< QPersistentModelIndex> &*parents* = QList< QPersistentModelIndex>(), QAbstractItemModel::LayoutChangeHint *hint* = QAbstractItemModel::NoLayoutChangeHint) |
| void | **[modelAboutToBeReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelAboutToBeReset)**() |
| void | **[modelReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelReset)**() |
| void | **[rowsAboutToBeInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeInserted)**(const QModelIndex &*parent*, int *start*, int *end*) |
| void | **[rowsAboutToBeMoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeMoved)**(const QModelIndex &*sourceParent*, int *sourceStart*, int *sourceEnd*, const QModelIndex &*destinationParent*, int *destinationRow*) |
| void | **[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void | **[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void | **[rowsMoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsMoved)**(const QModelIndex &*sourceParent*, int *sourceStart*, int *sourceEnd*, const QModelIndex &*destinationParent*, int *destinationRow*) |
| void | **[rowsRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsRemoved)**(const QModelIndex &*parent*, int *first*, int *last*) |

## 受保护的功能

| void            | **[beginInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertColumns)**(const QModelIndex &*parent*, int *first*, int *last*) |
| --------------- | ------------------------------------------------------------ |
| void            | **[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)**(const QModelIndex &*parent*, int *first*, int *last*) |
| bool            | **[beginMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveColumns)**(const QModelIndex &*sourceParent*, int *sourceFirst*, int *sourceLast*, const QModelIndex &*destinationParent*, int *destinationChild*) |
| bool            | **[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)**(const QModelIndex &*sourceParent*, int *sourceFirst*, int *sourceLast*, const QModelIndex &*destinationParent*, int *destinationChild*) |
| void            | **[beginRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveColumns)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void            | **[beginRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveRows)**(const QModelIndex &*parent*, int *first*, int *last*) |
| void            | **[beginResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginResetModel)**() |
| void            | **[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)**(const QModelIndex &*from*, const QModelIndex &*to*) |
| void            | **[changePersistentIndexList](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndexList)**(const QModelIndexList &*from*, const QModelIndexList &*to*) |
| QModelIndex     | **[createIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createIndex)**(int *row*, int *column*, const void **ptr* = nullptr) const |
| QModelIndex     | **[createIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createIndex-1)**(int *row*, int *column*, quintptr *id*) const |
| void            | **[endInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertColumns)**() |
| void            | **[endInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertRows)**() |
| void            | **[endMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveColumns)**() |
| void            | **[endMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveRows)**() |
| void            | **[endRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveColumns)**() |
| void            | **[endRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveRows)**() |
| void            | **[endResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endResetModel)**() |
| QModelIndexList | **[persistentIndexList](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#persistentIndexList)**() const |

## 受保护的插槽

| virtual void | **[resetInternalData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetInternalData)**() |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

QAbstractItemModel 类定义了项目模型必须使用的标准接口，以便能够与模型/视图体系结构中的其他组件进行互操作。它不应该直接实例化。相反，您应该将其子类化以创建新模型。

QAbstractItemModel 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它可以用作 QML 中的项目视图元素或 Qt Widgets 模块中的项目视图类的基础数据模型。

如果您需要一个与项目视图（例如 QML 的列表视图元素或 C++ 小部件）一起使用的模型[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，你应该考虑子类化[QAbstractListModel](https://doc-qt-io.translate.goog/qt-6/qabstractlistmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QAbstractTableModel](https://doc-qt-io.translate.goog/qt-6/qabstracttablemodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)而不是这个类。

底层数据模型作为表的层次结构向视图和委托公开。如果不使用层次结构，则模型是一个简单的行和列表。每个项目都有一个由指定的唯一索引[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

![img](.\QAbstractItemModel\modelindex-no-parent.png)

可以通过模型访问的每一项数据都有一个关联的模型索引。您可以使用以下命令获取此模型索引[index](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#index)（） 功能。每个索引可能有一个[sibling](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sibling)（） 指数; 子项目有一个[parent](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)（） 指数。

每个项目都有许多与其关联的数据元素，可以通过指定角色来检索它们（请参阅[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)）到模型的[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（） 功能。可以使用以下命令同时获取所有可用角色的数据[itemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemData)（） 功能。

每个角色的数据是使用特定的设置[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)。各个角色的数据分别设置为[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)()，或者可以为所有角色设置[setItemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemData)()。

可以通过以下方式查询项目[flags](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)（） （看[Qt::ItemFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)）以查看是否可以选择、拖动或以其他方式操作它们。

如果一个项目有子对象，[hasChildren](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasChildren)() 返回`true`对应的索引。

该模型有一个[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 和一个[columnCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)() 代表层次结构的每个级别。可以插入和删除行和列[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)(),[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)(),[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)（）， 和[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)()。

该模型发出信号来指示变化。例如，[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)每当模型提供的数据项发生更改时，就会发出 ()。模型提供的标头的更改导致[headerDataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerDataChanged)() 被发射。如果底层数据的结构发生变化，模型可以发出[layoutChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutChanged)() 向任何附加视图指示它们应该重新显示任何显示的项目，同时考虑到新的结构。

可以使用以下命令搜索通过模型可用的项目以获取特定数据[match](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#match)（） 功能。

要对模型进行排序，您可以使用[sort](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sort)()。

### 子类化

**注意：**子类化模型的一些通用指南可在[Model Subclassing Reference](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-subclassing-reference)。

当子类化 QAbstractItemModel 时，至少你必须实现[index](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#index)(),[parent](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)(),[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)(),[columnCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)（）， 和[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。这些函数用于所有只读模型，并构成可编辑模型的基础。

您还可以重新实现[hasChildren](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasChildren)() 为执行以下操作的模型提供特殊行为[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)（） 价格昂贵。这使得模型可以限制视图请求的数据量，并且可以用作实现模型数据的惰性填充的方法。

要在模型中启用编辑，您还必须实现[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)()，并重新实现[flags](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)() 确保`ItemIsEditable`返回。您还可以重新实现[headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)（） 和[setHeaderData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderData)() 来控制模型标题的呈现方式。

这[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)（） 和[headerDataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerDataChanged)() 信号必须在重新实现时显式发出[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)（） 和[setHeaderData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderData)() 函数分别。

自定义模型需要创建模型索引以供其他组件使用。为此，请致电[createIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createIndex)() 具有该项目的适当行号和列号，以及它的标识符（作为指针或整数值）。这些值的组合对于每个项目必须是唯一的。自定义模型通常在其他重新实现的函数中使用这些唯一标识符来检索项目数据并访问有关项目的父项和子项的信息。请参阅[Simple Tree Model Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-simpletreemodel-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)有关唯一标识符的更多信息。

没有必要支持中定义的每个角色[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)。根据模型中包含的数据类型，可能仅对实现[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)() 函数返回一些更常见角色的有效信息。大多数模型至少提供项目数据的文本表示[Qt::DisplayRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)，并且表现良好的模型还应该为[Qt::ToolTipRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)和[Qt::WhatsThisRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)。支持这些角色使模型能够与标准 Qt 视图一起使用。但是，对于某些处理高度专业化数据的模型，仅为用户定义的角色提供数据可能比较合适。

为可调整大小的数据结构提供接口的模型可以提供以下实现[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)(),[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)(),[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)（），和[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)()。实现这些功能时，重要的是在模型尺寸发生变化*之前*和*之后*通知任何连接的视图：

- 一个[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)() 执行必须调用[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)()在将新行插入数据结构*之前，以及*[endInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertRows)()*之后立即*。
- 一个[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)() 执行必须调用[beginInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertColumns)()在将新列插入数据结构*之前，以及*[endInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertColumns)()*之后立即*。
- A[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)() 执行必须调用[beginRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveRows)()在从数据结构中删除行*之前，以及*[endRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveRows)()*之后立即*。
- A[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)() 执行必须调用[beginRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveColumns)()在从数据结构中删除列*之前，以及*[endRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveColumns)()*之后立即*。

*这些函数发出的私有*信号使附加组件有机会在任何数据变得不可用之前采取行动。使用这些开始和结束函数封装插入和删除操作还使模型能够管理[persistent model indexes](https://doc-qt-io.translate.goog/qt-6/qpersistentmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)正确。**如果您希望正确处理选择，则必须确保调用这些函数。**如果插入或删除带有子项的项目，则无需为子项调用这些函数。换句话说，父项目将照顾其子项目。

要创建增量填充的模型，您可以重新实现[fetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)（） 和[canFetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canFetchMore)()。如果重新执行[fetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)() 将行添加到模型中，[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)（） 和[endInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertRows)必须调用 ()。

### 线程安全

成为一个[subclass of QObject](https://doc-qt-io.translate.goog/qt-6/threads-qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accessing-qobject-subclasses-from-other-threads), QAbstractItemModel 不是[thread-safe](https://doc-qt-io.translate.goog/qt-6/qrandomgenerator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reentrancy-and-thread-safety)。任何 QAbstractItemModel 模型相关的 API 只能从模型对象所在的线程调用。如果 QAbstractItemModel 与视图连接，则意味着 GUI 线程，因为那是视图所在的位置，它将从以下位置调用模型： GUI 线程。使用后台线程来填充或修改模型的内容是可能的，但需要小心，因为后台线程无法直接调用任何与模型相关的 API。相反，您应该将更新排队并在主线程中应用它们。这可以通过以下方式完成[queued connections](https://doc-qt-io.translate.goog/qt-6/threads-qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#signals-and-slots-across-threads)。

**也可以看看**[Model Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-classes),[Model Subclassing Reference](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-subclassing-reference),[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Using drag and drop with item views](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#using-drag-and-drop-with-item-views),[Simple Tree Model Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-simpletreemodel-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Editable Tree Model Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-editabletreemodel-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Fetch More Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-fetchmore-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举类 QAbstractItemModel:: CheckIndexOption 标志 QAbstractItemModel:: CheckIndexOptions

该枚举可用于控制执行的检查[QAbstractItemModel::checkIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkIndex)()。

| 持续的                                                  | 价值     | 描述                                                         |
| ------------------------------------------------------- | -------- | ------------------------------------------------------------ |
| `QAbstractItemModel::CheckIndexOption::NoOption`        | `0x0000` | 未指定检查选项。                                             |
| `QAbstractItemModel::CheckIndexOption::IndexIsValid`    | `0x0001` | 模型索引传递给[QAbstractItemModel::checkIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkIndex)() 被检查为有效的模型索引。 |
| `QAbstractItemModel::CheckIndexOption::DoNotUseParent`  | `0x0002` | 不执行任何涉及传递给的索引父级的使用情况的检查[QAbstractItemModel::checkIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkIndex)()。 |
| `QAbstractItemModel::CheckIndexOption::ParentIsInvalid` | `0x0004` | 模型索引的父级传递给[QAbstractItemModel::checkIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkIndex)() 被检查为无效模型索引。如果同时指定了此选项和 DoNotUseParent，则忽略此选项。 |

CheckIndexOptions 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < CheckIndexOption> 的类型定义。它存储 CheckIndexOption 值的 OR 组合。

### enum QAbstractItemModel::LayoutChangeHint

该枚举描述了模型更改布局的方式。

| 持续的                                   | 价值 | 描述               |
| ---------------------------------------- | ---- | ------------------ |
| `QAbstractItemModel::NoLayoutChangeHint` | `0`  | 没有可用的提示。   |
| `QAbstractItemModel::VerticalSortHint`   | `1`  | 正在对行进行排序。 |
| `QAbstractItemModel::HorizontalSortHint` | `2`  | 正在对列进行排序。 |

请注意，VerticalSortHint 和 HorizontalSortHint 的含义是项目在同一父级中移动，而不是移动到模型中的不同父级，并且不会过滤掉或过滤掉。

## 成员函数文档

### `[explicit]`QAbstractItemModel::QAbstractItemModel([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

使用给定的内容构造一个抽象项目模型*parent*。

### `[virtual noexcept]`QAbstractItemModel::~QAbstractItemModel()

破坏抽象项目模型。

### `[protected]`void QAbstractItemModel::beginInsertColumns(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

开始列插入操作。

重新实现时[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)() 在子类中，必须在将数据插入模型的基础数据存储*之前调用此函数。*

这*parent*索引对应于插入新列的父级；*first*和*last*是插入后新列的列号。

| ![img](.\QAbstractItemModel\modelview-begin-insert-columns.png)插入列 | 指定要插入到模型项目中的列范围的第一个和最后一个列号。例如，如图所示，我们在第4列之前插入三列，所以*first*是 4 并且*last*是 6：`beginInsertColumns(parent, 4, 6);`这将插入三个新列作为第 4、5 和 6 列。 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![img](.\QAbstractItemModel\modelview-begin-append-columns.png)追加列 | 要追加列，请将它们插入到最后一列之后。例如，如图所示，我们将三列附加到六个现有列的集合（以第 5 列结束），因此*first*是 6 并且*last*是 8：`beginInsertColumns(parent, 6, 8);`这会将两个新列附加为第 6、7 和 8 列。 |

**注意：**该函数发出[columnsAboutToBeInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsAboutToBeInserted)() 信号，在插入数据之前，连接的视图（或代理）必须处理该信号。否则，视图可能会处于无效状态。

**也可以看看**[endInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertColumns)()。

### `[protected]`void QAbstractItemModel::beginInsertRows(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

开始行插入操作。

重新实现时[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)() 在子类中，必须在将数据插入模型的基础数据存储*之前调用此函数。*

这*parent*索引对应于插入新行的父级；*first*和*last*是新行插入后将具有的行号。

| ![img](.\QAbstractItemModel\modelview-begin-insert-rows.png)插入行 | 指定要插入到模型项目中的行范围的第一个和最后一个行号。例如，如图所示，我们在第2行之前插入三行，所以*first*是 2 并且*last*是 4：`beginInsertRows(parent, 2, 4);`这将插入三个新行作为第 2、3 和 4 行。 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![img](.\QAbstractItemModel\modelview-begin-append-rows.png)追加行 | 要追加行，请将它们插入到最后一行之后。例如，如图所示，我们将两行追加到 4 个现有行的集合中（以第 3 行结束），因此*first*是 4 并且*last*是 5：`beginInsertRows(parent, 4, 5);`这会将两个新行添加为第 4 行和第 5 行。 |

**注意：**该函数发出[rowsAboutToBeInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeInserted)() 信号，在插入数据之前，连接的视图（或代理）必须处理该信号。否则，视图可能会处于无效状态。

**也可以看看**[endInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertRows)()。

### `[protected]`bool QAbstractItemModel::beginMoveColumns(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceFirst*, int *sourceLast*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationChild*)

开始列移动操作。

重新实现子类时，此方法简化了模型中实体的移动。此方法负责移动模型中的持久索引，否则您需要自己完成此操作。使用 beginMoveColumns 和[endMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveColumns)是发射的替代方案[layoutAboutToBeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutAboutToBeChanged)和[layoutChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutChanged)直接与[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)。

这*sourceParent*索引对应于从中移动列的父级；*sourceFirst*和*sourceLast*是要移动的列的第一个和最后一个列号。这*destinationParent*索引对应于这些列移动到的父级。这*destinationChild*是将列移动到的列。也就是说，该列的索引*sourceFirst*在*sourceParent*将成为专栏*destinationChild*在*destinationParent*，然后是所有其他列，直到*sourceLast*。

但是，当在同一父级中向下移动列时（*sourceParent*和*destinationParent*相等），这些列将被放置在*destinationChild*指数。也就是说，如果您希望移动第 0 列和第 1 列，使它们成为第 1 列和第 2 列，*destinationChild*应为 3。在这种情况下，源列的新索引`i`（介于*sourceFirst*和*sourceLast*) 等于`(destinationChild-sourceLast-1+i)`.

请注意，如果*sourceParent*和*destinationParent*是相同的，您必须确保*destinationChild*不在范围内*sourceFirst*和*sourceLast*+ 1. 您还必须确保不会尝试将列移动到其自己的子级或祖先之一。`false`如果任一条件为真，则此方法返回，在这种情况下您应该中止移动操作。

**也可以看看**[endMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveColumns)()。

### `[protected]`bool QAbstractItemModel::beginMoveRows(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceFirst*, int *sourceLast*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationChild*)

开始行移动操作。

重新实现子类时，此方法简化了模型中实体的移动。此方法负责移动模型中的持久索引，否则您需要自己完成此操作。使用 beginMoveRows 和[endMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveRows)是发射的替代方案[layoutAboutToBeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutAboutToBeChanged)和[layoutChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutChanged)直接与[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)。

这*sourceParent*索引对应于行被移动的父级；*sourceFirst*和*sourceLast*是要移动的行的第一行和最后一行的行号。这*destinationParent*索引对应于这些行移动到的父级。这*destinationChild*是行将移动到的行。也就是说，行的索引*sourceFirst*在*sourceParent*将成为行*destinationChild*在*destinationParent*，然后是所有其他行，直到*sourceLast*。

但是，当在同一父级中向下移动行时（*sourceParent*和*destinationParent*相等），行将被放置在*destinationChild*指数。也就是说，如果您希望移动第 0 行和第 1 行，使它们成为第 1 行和第 2 行，*destinationChild*应为 3。在这种情况下，源行的新索引`i`（介于*sourceFirst*和*sourceLast*) 等于`(destinationChild-sourceLast-1+i)`.

请注意，如果*sourceParent*和*destinationParent*是相同的，您必须确保*destinationChild*不在范围内*sourceFirst*和*sourceLast*+ 1. 您还必须确保不会尝试将行移动到其自己的子级或祖先之一。`false`如果任一条件为真，则此方法返回，在这种情况下您应该中止移动操作。

| ![img](.\QAbstractItemModel\modelview-move-rows-1.png)将行移动到另一个父级 | 指定要在模型中移动的源父级中的行范围的第一个和最后一个行号。还要指定目标父级中要将范围移动到的行。例如，如图所示，我们将源中第 2 行到第 4 行的三行移动，因此*sourceFirst*是 2 并且*sourceLast*是 4。我们将这些项目移动到目的地的第 2 行上方，因此*destinationChild*是 2。`beginMoveRows(sourceParent, 2, 4, destinationParent, 2);`这会将源中的三行 2、3 和 4 移动为目标中的 2、3 和 4。其他受影响的兄弟姐妹也相应流离失所。 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![img](.\QAbstractItemModel\modelview-move-rows-2.png)移动行以附加到另一个父级 | 要将行追加到另一个父行，请将它们移动到最后一行之后。例如，如图所示，我们将三行移动到现有 6 行的集合（以第 5 行结束），因此*destinationChild*是 6：`beginMoveRows(sourceParent, 2, 4, destinationParent, 6);`这会将目标行移动到目标父级的末尾，即 6、7 和 8。 |
| ![img](.\QAbstractItemModel\modelview-move-rows-3.png)将同一父级中的行向上移动 | 要在同一父级中移动行，请指定要将它们移动到的行。例如，如图所示，我们将一项从第 2 行移动到第 0 行，因此*sourceFirst*和*sourceLast*是 2 和*destinationChild*是 0。`beginMoveRows(parent, 2, 2, parent, 0);`请注意，其他行可能会相应地移位。另请注意，在同一父级中移动项目时，不应尝试无效或无操作的移动。在上面的示例中，项目 2 在移动之前位于第 2 行，因此无法将其移动到第 2 行（它已经在其中）或第 3 行（无操作，因为第 3 行意味着在第 3 行上方，它已经在其中） |
| ![img](.\QAbstractItemModel\modelview-move-rows-4.png)将同一父级中的行向下移动 | 要在同一父级中移动行，请指定要将它们移动到的行。例如，如图所示，我们将一项从第 2 行移动到第 4 行，因此*sourceFirst*和*sourceLast*是 2 和*destinationChild*是 4。`beginMoveRows(parent, 2, 2, parent, 4);`请注意，其他行可能会相应地移位。 |

**也可以看看**[endMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveRows)()。

### `[protected]`void QAbstractItemModel::beginRemoveColumns(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

开始列移除操作。

重新实现时[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)() 在子类中，您必须在从模型的基础数据存储中删除数据*之前调用此函数。*

这*parent*索引对应于从中删除新列的父级；*first*和*last*是要删除的第一列和最后一列的列号。

| ![img](.\QAbstractItemModel\modelview-begin-remove-columns.png)删除列 | 指定要从模型中的项目中删除的列范围的第一个和最后一个列号。例如，如图所示，我们删除第4列到第6列的三列，所以*first*是 4 并且*last*是 6：`beginRemoveColumns(parent, 4, 6);` |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

**注意：**该函数发出[columnsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnsAboutToBeRemoved)() 表示在删除数据之前连接的视图（或代理）必须处理的信号。否则，视图可能会处于无效状态。

**也可以看看**[endRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveColumns)()。

### `[protected]`void QAbstractItemModel::beginRemoveRows(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

开始行删除操作。

重新实现时[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)() 在子类中，您必须在从模型的基础数据存储中删除数据*之前调用此函数。*

这*parent*索引对应于从中删除新行的父级；*first*和*last*是要删除的行的行号。

| ![img](.\QAbstractItemModel\modelview-begin-remove-rows.png)删除行 | 指定要从模型中的项目中删除的行范围的第一个和最后一个行号。例如，如图所示，我们删除第2行到第3行的两行，所以*first*是 2 并且*last*是 3：`beginRemoveRows(parent, 2, 3);` |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

**注意：**该函数发出[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)() 表示在删除数据之前连接的视图（或代理）必须处理的信号。否则，视图可能会处于无效状态。

**也可以看看**[endRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveRows)()。

### `[protected]`void QAbstractItemModel::beginResetModel()

开始模型重置操作。

重置操作可将任何附加视图中的模型重置为其当前状态。

**注意：**附加到该模型的任何视图也将被重置。

当模型被重置时，这意味着从模型报告的任何先前数据现在都无效并且必须再次查询。这也意味着当前项目和任何选定的项目将变得无效。

当模型从根本上改变其数据时，有时调用此函数比发出更容易[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)() 当底层数据源或其结构发生更改时通知其他组件。

在重置模型或代理模型中的任何内部数据结构之前，您必须调用此函数。

该函数发出信号[modelAboutToBeReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelAboutToBeReset)()。

**也可以看看**[modelAboutToBeReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelAboutToBeReset)(),[modelReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelReset)（）， 和[endResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endResetModel)()。

### `[virtual]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::buddy(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回由 表示的项目的伙伴的模型索引*index*。当用户想要编辑某个项目时，视图将调用此函数来检查是否应该编辑模型中的另一个项目。然后，视图将使用伙伴项返回的模型索引构造一个委托。

该函数的默认实现将每个项目作为其自己的伙伴。

### `[virtual]`bool QAbstractItemModel::canDropMimeData(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*, [Qt::DropAction](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) *action*, int *row*, int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*) const

返回`true`模型是否可以接受掉落*data*。此默认实现仅检查是否*data*列表中至少有一种格式[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)（） 而如果*action*是模型中的[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)()。

如果您想测试是否可以在您的自定义模型中重新实现此函数*data*可以被丢弃在*row*,*column*,*parent*和*action*。如果您不需要该测试，则无需重新实现此功能。

**也可以看看**[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)（） 和[Using drag and drop with item views](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#using-drag-and-drop-with-item-views)。

### `[virtual invokable]`bool QAbstractItemModel::canFetchMore(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*) const

`true`如果有更多数据可用则返回*parent*; 否则返回`false`.

默认实现始终返回`false`.

如果 canFetchMore() 返回`true`，则[fetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)应调用 () 函数。这是[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 例如。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[fetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)()。

### `[protected]`void QAbstractItemModel::changePersistentIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*from*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*to*)

改变[QPersistentModelIndex](https://doc-qt-io.translate.goog/qt-6/qpersistentmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)等于给定的*from*给定的模型索引*to*型号索引。

如果没有持久模型索引等于给定的*from*找到模型索引，没有任何改变。

**也可以看看**[persistentIndexList](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#persistentIndexList)（） 和[changePersistentIndexList](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndexList)()。

### `[protected]`void QAbstractItemModel::changePersistentIndexList(const [QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) &*from*, const [QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) &*to*)

改变{[QPersistentModelIndex](https://doc-qt-io.translate.goog/qt-6/qpersistentmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)}es 等于给定中的索引*from*给定的模型索引列表*to*型号索引列表。

如果没有持久模型索引等于给定中的索引*from*找到模型索引列表，没有任何改变。

**也可以看看**[persistentIndexList](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#persistentIndexList)（） 和[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)()。

### bool QAbstractItemModel::checkIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemModel::CheckIndexOptions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckIndexOption-enum) *options* = CheckIndexOption::NoOption) const

该函数检查是否*index*是该模型的合法模型索引。合法模型索引要么是无效模型索引，要么是满足以下所有条件的有效模型索引：

- 指数模型为`this`；
- 索引行大于或等于零；
- 索引的行数小于索引父级的行数；
- 索引列大于或等于零；
- 索引的列小于索引父级的列数。

这*options*争论可能会改变其中一些检查。如果*options*包含`IndexIsValid`，那么*index*必须是有效的索引；这在重新实现诸如以下功能时很有用[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（） 或者[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)()，期望有效的索引。

如果*options*包含`DoNotUseParent`，然后将调用的检查[parent](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)() 被省略；这允许从[parent](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)() 重新实现（否则，这将导致无休止的递归和崩溃）。

如果*options*不包含`DoNotUseParent`，并且包含`ParentIsInvalid`，则执行附加检查：检查父索引是否无效。这在实现平面模型（例如列表或表）时非常有用，其中模型索引不应具有有效的父索引。

如果所有检查都成功，则该函数返回 true，否则返回 false。这允许使用该功能[Q_ASSERT](https://doc-qt-io.translate.goog/qt-6/qtassert-qtcore-proxy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_ASSERT)以及类似的其他调试机制。如果某些检查失败，则会在日志记录类别中打印一条警告消息`qt.core.qabstractitemmodel.checkindex`，其中包含一些可能对调试失败有用的信息。

**注意：**此函数是一个调试助手，用于实现您自己的项目模型。当开发复杂模型以及构建复杂模型层次结构时（例如使用代理模型），调用此函数非常有用，以便捕获与意外传递给某些对象的非法模型索引（如上所述）相关的错误。[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)API。

**警告：**请注意，将非法索引传递给项目模型是未定义的行为，因此应用程序必须避免这样做，并且不要依赖项目模型可以用来优雅地处理非法索引的任何“防御”编程。

**也可以看看**[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[virtual, since 6.0]`bool QAbstractItemModel::clearItemData(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

删除存储在给定角色的所有角色中的数据*index*。`true`成功则返回；否则返回`false`. 这[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)如果数据被成功删除，则应发出 () 信号。基类实现返回`false`

这个函数是在Qt 6.0中引入的。

**也可以看看**[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)(),[itemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemData)(),[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)（）， 和[setItemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemData)()。

### `[pure virtual invokable]`int QAbstractItemModel::columnCount(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex()) const

返回给定子级的列数*parent*。

在大多数子类中，列数与*parent*。

例如：

```
int MyModel::columnCount(const QModelIndex &parent) const
{
    Q_UNUSED(parent);
    return 3;
}
```

**注意：**在实现基于表的模型时，当父级有效时，columnCount() 应返回 0。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)()。

### `[private signal]`void QAbstractItemModel::columnsAboutToBeInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

该信号在将列插入模型之前发出。新项目将位于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)（） 和[beginInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertColumns)()。

### `[private signal]`void QAbstractItemModel::columnsAboutToBeMoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceStart*, int *sourceEnd*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationColumn*)

该信号在模型内移动列之前发出。将移动的项目是介于*sourceStart*和*sourceEnd*包含在内，在给定的情况下*sourceParent*物品。他们将被转移到*destinationParent*从列开始*destinationColumn*。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)()。

### `[private signal]`void QAbstractItemModel::columnsAboutToBeRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

该信号在从模型中删除列之前发出。要删除的项目是介于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)（） 和[beginRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveColumns)()。

### `[private signal]`void QAbstractItemModel::columnsInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

将列插入模型后会发出此信号。新项目是介于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)（） 和[beginInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertColumns)()。

### `[private signal]`void QAbstractItemModel::columnsMoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceStart*, int *sourceEnd*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationColumn*)

在模型内移动列后会发出此信号。之间的项目*sourceStart*和*sourceEnd*包含在内，在给定的情况下*sourceParent*项目已移至*destinationParent*从列开始*destinationColumn*。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)()。

### `[private signal]`void QAbstractItemModel::columnsRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

从模型中删除列后会发出此信号。删除的项目是介于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)（） 和[beginRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveColumns)()。

### `[protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::createIndex(int *row*, int *column*, const void **ptr* = nullptr) const

为给定创建模型索引*row*和*column*与内部指针*ptr*。

当使用[QSortFilterProxyModel](https://doc-qt-io.translate.goog/qt-6/qsortfilterproxymodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，它的索引有自己的内部指针。不建议在模型外部访问此内部指针。使用[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)() 函数代替。

此函数提供模型子类必须使用的一致接口来创建模型索引。

### `[protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::createIndex(int *row*, int *column*, [quintptr](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quintptr-typedef) *id*) const

为给定创建模型索引*row*和*column*与内部标识符，*id*。

此函数提供模型子类必须使用的一致接口来创建模型索引。

**也可以看看**[QModelIndex::internalId](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#internalId)()。

### `[pure virtual invokable]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::data(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, int *role* = Qt::DisplayRole) const

返回给定下存储的数据*role*对于所提及的项目*index*。

**注意：**如果没有要返回的值，则返回**无效值**（默认构造）[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum),[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)（）， 和[headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)()。

### `[signal]`void QAbstractItemModel::dataChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*topLeft*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*bottomRight*, const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< int> &*roles* = QList< int>())

每当现有项目中的数据发生更改时，就会发出此信号。

如果这些项目属于同一父项，则受影响的项目是*topLeft*和*bottomRight*包括的。如果这些项目没有相同的父项，则行为未定义。

重新实现时[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)() 函数中，必须显式发出该信号。

可选的*roles*参数可用于指定实际修改了哪些数据角色。角色参数中的空向量意味着所有角色都应被视为已修改。角色参数中元素的顺序没有任何相关性。

**也可以看看**[headerDataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerDataChanged)(),[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)（）， 和[layoutChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutChanged)()。

### `[virtual]`bool QAbstractItemModel::dropMimeData(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*, [Qt::DropAction](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) *action*, int *row*, int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*)

处理*data*由以给定结尾的拖放操作提供*action*。

返回`true`数据和操作是否由模型处理；否则返回`false`.

指定的*row*,*column*和*parent*指示模型中操作结束的项目的位置。模型有责任在正确的位置完成操作。

例如，对某个项目执行放置操作[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可能会导致新项目被插入为指定项目的子项*row*,*column*， 和*parent*，或作为该项目的兄弟项目。

什么时候*row*和*column*为 -1 表示删除的数据应被视为直接删除*parent*。通常这意味着将数据附加为*parent*。如果*row*和*column*大于或等于零，这意味着下降发生在指定的之前*row*和*column*在指定的*parent*。

这[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)调用 () 成员来获取可接受的 MIME 类型列表。此默认实现假设默认实现[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)()，它返回单个默认 MIME 类型。如果你重新实现[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)() 在您的自定义模型中返回多个 MIME 类型，您必须重新实现此函数才能使用它们。

**也可以看看**[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)(),[canDropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canDropMimeData)（）， 和[Using drag and drop with item views](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#using-drag-and-drop-with-item-views)。

### `[protected]`void QAbstractItemModel::endInsertColumns()

结束列插入操作。

重新实现时[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)() 在子类中，您必须在将数据插入模型的底层数据存储*后调用此函数。*

**也可以看看**[beginInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertColumns)()。

### `[protected]`void QAbstractItemModel::endInsertRows()

结束行插入操作。

重新实现时[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)() 在子类中，您必须在将数据插入模型的底层数据存储*后调用此函数。*

**也可以看看**[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)()。

### `[protected]`void QAbstractItemModel::endMoveColumns()

结束列移动操作。

实现子类时，您必须在模型的基础数据存储中移动数据*后调用此函数。*

**也可以看看**[beginMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveColumns)()。

### `[protected]`void QAbstractItemModel::endMoveRows()

结束行移动操作。

实现子类时，您必须在模型的基础数据存储中移动数据*后调用此函数。*

**也可以看看**[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)()。

### `[protected]`void QAbstractItemModel::endRemoveColumns()

结束列删除操作。

重新实现时[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)() 在子类中，您必须在从模型的底层数据存储中删除数据*后调用此函数。*

**也可以看看**[beginRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveColumns)()。

### `[protected]`void QAbstractItemModel::endRemoveRows()

结束行删除操作。

重新实现时[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)() 在子类中，您必须在从模型的底层数据存储中删除数据*后调用此函数。*

**也可以看看**[beginRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveRows)()。

### `[protected]`void QAbstractItemModel::endResetModel()

完成模型重置操作。

您必须在重置模型或代理模型中的任何内部数据结构后调用此函数。

该函数发出信号[modelReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelReset)()。

**也可以看看**[beginResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginResetModel)()。

### `[virtual invokable]`void QAbstractItemModel::fetchMore(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*)

获取具有由 指定的父级的项目的任何可用数据*parent*指数。

如果您要增量填充模型，请重新实现此功能。

默认实现不执行任何操作。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[canFetchMore](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canFetchMore)()。

### `[virtual invokable]`[Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum) QAbstractItemModel::flags(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回给定的项目标志*index*。

`ItemIsEnabled`基类实现返回启用该项目 ( ) 并允许选择它 ( )的标志组合`ItemIsSelectable`。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)。

### `[virtual invokable]`bool QAbstractItemModel::hasChildren(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex()) const

返回`true`如果*parent*有孩子；否则返回`false`.

使用[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 在父级上找出子级的数量。

请注意，如果同一索引具有标志，则使用此方法报告特定索引 hasChildren 是未定义的行为[Qt::ItemNeverHasChildren](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)放。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[parent](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)（） 和[index](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#index)()。

### `[invokable]`bool QAbstractItemModel::hasIndex(int *row*, int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex()) const

`true`如果模型返回有效则返回[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)为了*row*和*column*和*parent*，否则返回`false`。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

### `[virtual invokable]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::headerData(int *section*, [Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, int *role* = Qt::DisplayRole) const

返回给定的数据*role*和*section*在标头中指定*orientation*。

对于水平标题，节号对应于列号。类似地，对于垂直标题，节号对应于行号。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum),[setHeaderData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderData)（）， 和[QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[signal]`void QAbstractItemModel::headerDataChanged([Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, int *first*, int *last*)

每当标题发生更改时都会发出此信号。这*orientation*指示水平或垂直标题是否已更改。标题中的部分来自*first*到*last*需要更新。

重新实现时[setHeaderData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderData)() 函数中，必须显式发出该信号。

如果您要更改列数或行数，则不需要发出此信号，而是使用开始/结束函数（请参阅[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类描述以获取详细信息）。

**也可以看看**[headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)(),[setHeaderData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderData)（）， 和[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)()。

### `[pure virtual invokable]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::index(int *row*, int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex()) const

返回给定指定的模型中项目的索引*row*,*column*和*parent*指数。

当在子类中重新实现该函数时，调用[createIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createIndex)() 生成模型索引，其他组件可以使用该索引来引用模型中的项目。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[createIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createIndex)()。

### `[invokable]`bool QAbstractItemModel::insertColumn(int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

在给定值之前插入一列*column*在的子项目中*parent*指定的。

返回`true`该列是否已插入；否则返回`false`.

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)(),[insertRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)（）， 和[removeColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumn)()。

### `[virtual invokable]`bool QAbstractItemModel::insertColumns(int *column*, int *count*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

在支持此功能的型号上，插入*count*在给定之前将新列添加到模型中*column*。每个新列中的项目将是由*parent*型号索引。

如果*column*为 0 时，这些列将添加到任何现有列的前面。

如果*column*是[columnCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)()，这些列将附加到任何现有列。

如果*parent*没有孩子，单行*count*列已插入。

返回`true`列是否成功插入；否则返回`false`.

基类实现不执行任何操作并返回`false`。

如果您实现自己的模型，如果您想支持插入，则可以重新实现此函数。或者，您可以提供自己的 API 来更改数据。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)(),[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)(),[beginInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertColumns)（）， 和[endInsertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertColumns)()。

### `[invokable]`bool QAbstractItemModel::insertRow(int *row*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

在给定值之前插入一行*row*在的子项目中*parent*指定的。

**注意：**该函数调用的是虚方法[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)。

返回`true`该行是否被插入；否则返回`false`.

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)(),[insertColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumn)（）， 和[removeRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)()。

### `[virtual invokable]`bool QAbstractItemModel::insertRows(int *row*, int *count*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

**注意：**此函数的基类实现不执行任何操作并返回`false`。

在支持此功能的型号上，插入*count*在给定之前将行放入模型中*row*。新行中的项目将是由 表示的项目的子项*parent*型号索引。

如果*row*为 0 时，这些行将添加到父级中任何现有行的前面。

如果*row*是[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)()，行将附加到父级中的任何现有行。

如果*parent*没有孩子，单列*count*行已插入。

返回`true`行是否成功插入；否则返回`false`.

如果您实现自己的模型，如果您想支持插入，则可以重新实现此函数。或者，您可以提供自己的 API 来更改数据。无论哪种情况，您都需要致电[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)（） 和[endInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertRows)() 通知其他组件模型已更改。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)(),[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)(),[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)（）， 和[endInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endInsertRows)()。

### `[virtual]`[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< int, [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QAbstractItemModel::itemData(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回一个映射，其中包含给定项目的模型中所有预定义角色的值*index*。

如果您想要扩展此函数的默认行为以在地图中包含自定义角色，请重新实现此函数。

**也可以看看**[setItemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemData)(),[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)， 和[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。

### `[signal]`void QAbstractItemModel::layoutAboutToBeChanged(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QPersistentModelIndex](https://doc-qt-io.translate.goog/qt-6/qpersistentmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*parents* = QList< QPersistentModelIndex>(), [QAbstractItemModel::LayoutChangeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutChangeHint-enum) *hint* = QAbstractItemModel::NoLayoutChangeHint)

该信号在模型布局更改之前发出。连接到该信号的组件使用它来适应模型布局的变化。

子类应在发出layoutAboutToBeChanged()后更新所有持久模型索引。

可选的*parents*参数用于提供有关模型布局的哪些部分正在更改的更具体的通知。空列表表示整个模型布局的更改。中元素的顺序*parents*清单并不重要。可选的*hint*参数用于提示模型重新布局时发生的情况。

**也可以看看**[layoutChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutChanged)（） 和[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)()。

### `[signal]`void QAbstractItemModel::layoutChanged(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QPersistentModelIndex](https://doc-qt-io.translate.goog/qt-6/qpersistentmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*parents* = QList< QPersistentModelIndex>(), [QAbstractItemModel::LayoutChangeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutChangeHint-enum) *hint* = QAbstractItemModel::NoLayoutChangeHint)

每当模型暴露的项目的布局发生变化时，就会发出此信号；例如，当模型已排序时。当视图收到此信号时，它应该更新项目的布局以反映此更改。

当子类化时[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QAbstractProxyModel](https://doc-qt-io.translate.goog/qt-6/qabstractproxymodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，确保你发出[layoutAboutToBeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutAboutToBeChanged)() 在更改项目顺序或更改向视图公开的数据结构之前，并在更改布局后发出 layoutChanged() 。

可选的*parents*参数用于提供有关模型布局的哪些部分正在更改的更具体的通知。空列表表示整个模型布局的更改。中元素的顺序*parents*清单并不重要。可选的*hint*参数用于提示模型重新布局时发生的情况。

子类应在发出layoutChanged() 之前更新任何持久模型索引。换句话说，当结构发生变化时：

- 发射[layoutAboutToBeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutAboutToBeChanged)
- 记住[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)那将会改变
- 更新您的内部数据
- 称呼[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)()
- 发出布局更改

**也可以看看**[layoutAboutToBeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutAboutToBeChanged)(),[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)(),[headerDataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerDataChanged)(),[modelReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelReset)（）， 和[changePersistentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changePersistentIndex)()。

### `[virtual invokable]`[QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) QAbstractItemModel::match(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*start*, int *role*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*value*, int *hits* = 1, [Qt::MatchFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MatchFlag-enum) *flags* = Qt::MatchFlags(Qt::MatchStartsWith|Qt::MatchWrap)) const

返回列中项目的索引列表*start*给定下存储数据的索引*role*匹配指定的*value*。执行搜索的方式由*flags*给予。返回的列表可能为空。另请注意，如果使用代理模型，则列表中结果的顺序可能与模型中的顺序不对应。不能依赖结果的顺序。

搜索从*start*索引，一直持续到匹配数据项的个数等于*hits*，搜索到达最后一行，或者搜索到达*start*再次 - 取决于是否`MatchWrap`指定*flags*。如果您想搜索所有匹配的项目，请使用*hits*= -1。

默认情况下，此函数将对所有项目执行基于字符串的换行比较，搜索以指定的搜索词开头的项目*value*。

**注意：**此函数的默认实现仅搜索列。重新实现此函数以包含不同的搜索行为。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

### `[virtual]`[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemModel::mimeData(const [QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) &*indexes*) const

返回一个对象，其中包含与列表相对应的序列化数据项*indexes*指定的。用于描述编码数据的格式是从[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)（） 功能。此默认实现使用默认实现返回的默认 MIME 类型[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)()。如果你重新实现[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)() 在您的自定义模型中返回更多 MIME 类型，请重新实现此函数以使用它们。

如果列表中的*indexes*为空，或者没有受支持的 MIME 类型，`nullptr`则返回而不是序列化的空列表。

**也可以看看**[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)（） 和[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)()。

### `[virtual]`[QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::mimeTypes() const

返回允许的 MIME 类型列表。默认情况下，内置模型和视图使用内部 MIME 类型：`application/x-qabstractitemmodeldatalist`。

在自定义模型中实现拖放支持时，如果您将返回默认内部 MIME 类型以外的格式的数据，请重新实现此函数以返回 MIME 类型列表。

如果您在自定义模型中重新实现此函数，则还必须重新实现调用它的成员函数：[mimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)（） 和[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)()。

**也可以看看**[mimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)（） 和[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)()。

### `[private signal]`void QAbstractItemModel::modelAboutToBeReset()

当[beginResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginResetModel)() 在模型的内部状态（例如持久模型索引）失效之前被调用。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[beginResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginResetModel)（） 和[modelReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelReset)()。

### `[private signal]`void QAbstractItemModel::modelReset()

当[endResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endResetModel)() 在模型的内部状态（例如持久模型索引）失效后被调用。

请注意，如果模型被重置，则应认为之前从模型检索的所有信息均无效。这包括但不限于[rowCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)（） 和[columnCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)(),[flags](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)()，通过检索数据[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（）， 和[roleNames](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#roleNames)()。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[endResetModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endResetModel)（） 和[modelAboutToBeReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelAboutToBeReset)()。

### `[invokable]`bool QAbstractItemModel::moveColumn(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceColumn*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationChild*)

在支持此功能的模型上，移动*sourceColumn*从*sourceParent*到*destinationChild*在下面*destinationParent*。

返回`true`列是否成功移动；否则返回`false`.

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[moveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveColumns)（） 和[moveRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveRow)()。

### `[virtual invokable]`bool QAbstractItemModel::moveColumns(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceColumn*, int *count*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationChild*)

在支持此功能的模型上，移动*count*以给定开头的列*sourceColumn*在父母之下*sourceParent*到专栏*destinationChild*在父母之下*destinationParent*。

返回`true`列是否成功移动；否则返回`false`.

基类实现不执行任何操作并返回`false`。

如果你实现自己的模型，如果你想支持移动，你可以重新实现这个功能。或者，您可以提供自己的 API 来更改数据。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[beginMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveColumns)（） 和[endMoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveColumns)()。

### `[invokable]`bool QAbstractItemModel::moveRow(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceRow*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationChild*)

在支持此功能的模型上，移动*sourceRow*从*sourceParent*到*destinationChild*在下面*destinationParent*。

返回`true`行是否成功移动；否则返回`false`.

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[moveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveRows)（） 和[moveColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveColumn)()。

### `[virtual invokable]`bool QAbstractItemModel::moveRows(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceRow*, int *count*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationChild*)

在支持此功能的模型上，移动*count*以给定开头的行*sourceRow*在父母之下*sourceParent*划船*destinationChild*在父母之下*destinationParent*。

返回`true`行是否成功移动；否则返回`false`.

基类实现不执行任何操作并返回`false`。

如果你实现自己的模型，如果你想支持移动，你可以重新实现这个功能。或者，您可以提供自己的 API 来更改数据。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)（） 和[endMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endMoveRows)()。

### `[virtual, since 6.0]`void QAbstractItemModel::multiData(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QModelRoleDataSpan](https://doc-qt-io.translate.goog/qt-6/qmodelroledataspan.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *roleDataSpan*) const

填充*roleDataSpan*与给定的请求数据*index*。

默认实现将简单地调用[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)() 对于跨度中的每个角色。子类可以重新实现此函数以更有效地向视图提供数据：

```
void MyModel::multiData(const QModelIndex &index, QModelRoleDataSpan roleDataSpan) const
{
    for (QModelRoleData &roleData : roleDataSpan) {
        int role = roleData.role();

        // ... obtain the data for index and role ...

        roleData.setData(result);
    }
}
```

在上面的代码片段中，`index`整个调用都是相同的。这意味着访问必要的数据结构以检索信息`index`只能进行一次（将相关代码提升到循环之外）。

的用法[QModelRoleData::setData](https://doc-qt-io.translate.goog/qt-6/qmodelroledata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)()，或类似的[QVariant::setValue](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValue)()，鼓励建造一个[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)单独并使用简单的赋值运算符；这是因为前者允许重新使用已经分配给[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)存储在 a 内的对象[QModelRoleData](https://doc-qt-io.translate.goog/qt-6/qmodelroledata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，而后者总是分配新的变体，然后销毁旧的变体。

请注意，视图可能会使用先前调用中已使用的跨度来调用 multiData()，因此可能已经包含一些数据。因此，如果模型无法返回给定角色的数据，则必须清除相应角色中的数据。[QModelRoleData](https://doc-qt-io.translate.goog/qt-6/qmodelroledata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。这可以通过调用来完成[QModelRoleData::clearData](https://doc-qt-io.translate.goog/qt-6/qmodelroledata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearData)()，或类似地通过设置默认构造[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 等等。未能清除数据将导致视图认为“旧”数据应该用于相应的角色。

最后，为了避免代码重复，子类也可能决定重新实现[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)() 就 multiData() 而言，通过仅提供一个元素的跨度：

```
QVariant MyModel::data(const QModelIndex &index, int role) const
{
    QModelRoleData roleData(role);
    multiData(index, roleData);
    return roleData.data();
}
```

**注意：**模型不允许修改跨度中的角色，或重新排列跨度元素。这样做会导致未定义的行为。

**注意：**向此函数传递无效的模型索引是非法的。

这个函数是在Qt 6.0中引入的。

**也可以看看**[QModelRoleDataSpan](https://doc-qt-io.translate.goog/qt-6/qmodelroledataspan.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。

### `[pure virtual invokable]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::parent(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回具有给定值的模型项的父项*index*。如果该项目没有父项，则无效[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被返回。

公开树数据结构的模型中使用的常见约定是只有第一列中的项目才有子项。对于这种情况，当在子类中重新实现此函数时，返回的列[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将为 0。

在子类中重新实现此函数时，请注意避免调用[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)成员函数，例如[QModelIndex::parent](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)()，因为属于您的模型的索引将简单地调用您的实现，从而导致无限递归。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[createIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createIndex)()。

### `[protected]`[QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) QAbstractItemModel::persistentIndexList() const

返回在模型中存储为持久索引的索引列表。

### `[invokable]`bool QAbstractItemModel::removeColumn(int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

删除给定的*column*从子项目*parent*指定的。

`true`如果列被删除则返回；否则返回`false`.

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)(),[removeRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（）， 和[insertColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumn)()。

### `[virtual invokable]`bool QAbstractItemModel::removeColumns(int *column*, int *count*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

在支持此功能的型号上，删除*count*以给定开头的列*column*在父母之下*parent*来自模型。

返回`true`列是否已成功删除；否则返回`false`.

基类实现不执行任何操作并返回`false`。

如果你实现自己的模型，如果你想支持删除，你可以重新实现这个函数。或者，您可以提供自己的 API 来更改数据。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[removeColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumn)(),[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)(),[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)(),[beginRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveColumns)（）， 和[endRemoveColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveColumns)()。

### `[invokable]`bool QAbstractItemModel::removeRow(int *row*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

删除给定的*row*从子项目*parent*指定的。

`true`如果该行被删除则返回；否则返回`false`.

这是一个方便的函数，调用[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)()。这[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实施[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)（） 什么也没做。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)(),[removeColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumn)（）， 和[insertRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)()。

### `[virtual invokable]`bool QAbstractItemModel::removeRows(int *row*, int *count*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex())

在支持此功能的型号上，删除*count*以给定开头的行*row*在父母之下*parent*来自模型。

返回`true`是否成功删除行；否则返回`false`.

基类实现不执行任何操作并返回`false`。

如果你实现自己的模型，如果你想支持删除，你可以重新实现这个函数。或者，您可以提供自己的 API 来更改数据。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[removeRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)(),[removeColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumns)(),[insertColumns](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumns)(),[beginRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveRows)（）， 和[endRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endRemoveRows)()。

### `[virtual protected slot]`void QAbstractItemModel::resetInternalData()

该槽在模型重置时清除内部数据后立即调用。

这个槽为具体代理模型的子类提供了便利，例如[QSortFilterProxyModel](https://doc-qt-io.translate.goog/qt-6/qsortfilterproxymodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)维护额外的数据。

```
class CustomDataProxy : public QSortFilterProxyModel
{
    Q_OBJECT
public:
    CustomDataProxy(QObject *parent)
      : QSortFilterProxyModel(parent)
    {
    }

    ...

    QVariant data(const QModelIndex &index, int role) override
    {
        if (role != Qt::BackgroundRole)
            return QSortFilterProxyModel::data(index, role);

        if (m_customData.contains(index.row()))
            return m_customData.value(index.row());
        return QSortFilterProxyModel::data(index, role);
    }

private slots:
    void resetInternalData()
    {
        m_customData.clear();
    }

private:
  QHash< int, QVariant> m_customData;
};
```

**注意：**由于错误，Qt 5.0 中缺少此插槽。

**也可以看看**[modelAboutToBeReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelAboutToBeReset)（） 和[modelReset](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelReset)()。

### `[virtual slot]`void QAbstractItemModel::revert()

让模型知道它应该丢弃缓存的信息。此功能通常用于行编辑。

**也可以看看**[submit](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#submit)()。

### `[virtual]`[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< int, [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QAbstractItemModel::roleNames() const

返回模型的角色名称。

Qt 设置的默认角色名称是：

|                           Qt 角色                            | QML 角色名称 |
| :----------------------------------------------------------: | :----------: |
| [Qt::DisplayRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum) |     展示     |
| [Qt::DecorationRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum) |     装饰     |
| [Qt::EditRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum) |     编辑     |
| [Qt::ToolTipRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum) |   工具提示   |
| [Qt::StatusTipRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum) |   状态提示   |
| [Qt::WhatsThisRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum) |   这是什么   |

### `[pure virtual invokable]`int QAbstractItemModel::rowCount(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent* = QModelIndex()) const

返回给定值下的行数*parent*。当父级有效时，意味着 rowCount 返回父级的子级数。

**注意：**在实现基于表的模型时，当父级有效时 rowCount() 应返回 0。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[columnCount](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)()。

### `[private signal]`void QAbstractItemModel::rowsAboutToBeInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

该信号在将行插入模型之前发出。新项目将位于*start*和*end*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)（） 和[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)()。

### `[private signal]`void QAbstractItemModel::rowsAboutToBeMoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceStart*, int *sourceEnd*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationRow*)

该信号在模型内移动行之前发出。将移动的项目是介于*sourceStart*和*sourceEnd*包含在内，在给定的情况下*sourceParent*物品。他们将被转移到*destinationParent*从该行开始*destinationRow*。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)()。

### `[private signal]`void QAbstractItemModel::rowsAboutToBeRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

该信号在从模型中删除行之前发出。将被删除的项目是介于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)（） 和[beginRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveRows)()。

### `[private signal]`void QAbstractItemModel::rowsInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

将行插入模型后会发出此信号。新项目是介于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[insertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRows)（） 和[beginInsertRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginInsertRows)()。

### `[private signal]`void QAbstractItemModel::rowsMoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sourceParent*, int *sourceStart*, int *sourceEnd*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*destinationParent*, int *destinationRow*)

在模型内移动行后会发出此信号。之间的项目*sourceStart*和*sourceEnd*包含在内，在给定的情况下*sourceParent*项目已移至*destinationParent*从该行开始*destinationRow*。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[beginMoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginMoveRows)()。

### `[private signal]`void QAbstractItemModel::rowsRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *first*, int *last*)

从模型中删除行后会发出此信号。删除的项目是介于*first*和*last*包含在内，在给定的情况下*parent*物品。

**注意：**连接到该信号的组件使用它来适应模型尺寸的变化。它只能由[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，并且不能在子类代码中显式发出。

**注意：**这是一个私人信号。它可以用于信号连接，但不能由用户发射。

**也可以看看**[removeRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRows)（） 和[beginRemoveRows](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginRemoveRows)()。

### `[virtual invokable]`bool QAbstractItemModel::setData(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*value*, int *role* = Qt::EditRole)

设置*role*该项目的数据位于*index*到*value*。

`true`成功则返回；否则返回`false`.

这[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)如果数据设置成功，则应发出 () 信号。

基类实现返回`false`. 这个功能和[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)对于可编辑模型，必须重新实现 ()。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum),[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（）， 和[itemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemData)()。

### `[virtual]`bool QAbstractItemModel::setHeaderData(int *section*, [Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*value*, int *role* = Qt::EditRole)

设置给定的数据*role*和*section*在标头中指定*orientation*到*value*提供。

返回`true`标头数据是否已更新；否则返回`false`.

当重新实现这个函数时，[headerDataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerDataChanged)() 信号必须显式发出。

**也可以看看**[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)和[headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)()。

### `[virtual]`bool QAbstractItemModel::setItemData(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, const [QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< int, [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*roles*)

设置项目的角色数据*index*到相关值*roles*，对于每一个[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)。

`true`成功则返回；否则返回`false`.

不在其中的角色*roles*不会被修改。

**也可以看看**[setData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)(),[data](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（）， 和[itemData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemData)()。

### `[virtual invokable]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::sibling(int *row*, int *column*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回兄弟姐妹*row*和*column*对于位于*index*，或无效的[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果该位置没有兄弟姐妹。

sibling() 只是一个方便的函数，它查找项目的父项，并使用它来检索指定项中子项的索引*row*和*column*。

可以选择覆盖此方法以进行特定于实现的优化。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[index](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#index)(),[QModelIndex::row](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#row)（）， 和[QModelIndex::column](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#column)()。

### `[virtual invokable]`void QAbstractItemModel::sort(int *column*, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::AscendingOrder)

对模型进行排序*column*在给定的*order*。

基类实现不执行任何操作。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

### `[virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemModel::span(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回由 表示的项目的行和列跨度*index*。

**注意：**目前不使用跨度。

### `[virtual slot]`bool QAbstractItemModel::submit()

让模型知道它应该将缓存信息提交到永久存储。此功能通常用于行编辑。

`true`如果没有错误则返回；否则返回`false`.

**也可以看看**[revert](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revert)()。

### `[virtual]`[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) QAbstractItemModel::supportedDragActions() const

返回此模型中的数据支持的操作。

默认实现返回[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)()。如果您希望支持其他操作，请重新实现此功能。

supportedDragActions() 用于[QAbstractItemView::startDrag](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)() 作为发生拖动时的默认值。

**也可以看看**[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum)和[Using drag and drop with item views](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#using-drag-and-drop-with-item-views)。

### `[virtual]`[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) QAbstractItemModel::supportedDropActions() const

返回此模型支持的放置操作。

默认实现返回[Qt::CopyAction](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum)。如果您希望支持其他操作，请重新实现此功能。您还必须重新实现[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)() 函数来处理附加操作。

**也可以看看**[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)(),[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum)， 和[Using drag and drop with item views](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#using-drag-and-drop-with-item-views)。