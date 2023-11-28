 QAbstractItemView Class

QAbstractItemView 类提供项目视图类的基本功能。[更多的...](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QAbstractItemView>                                |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QColumnView](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qabstractitemview-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qabstractitemview-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[DragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragDropMode-enum)** { NoDragDrop, DragOnly, DropOnly, DragDrop, InternalMove } |
| ----- | ------------------------------------------------------------ |
| enum  | **[EditTrigger](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EditTrigger-enum)** { NoEditTriggers, CurrentChanged, DoubleClicked, SelectedClicked, EditKeyPressed, …, AllEditTriggers } |
| flags | **[EditTriggers](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EditTrigger-enum)** |
| enum  | **[ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum)** { EnsureVisible, PositionAtTop, PositionAtBottom, PositionAtCenter } |
| enum  | **[ScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollMode-enum)** { ScrollPerItem, ScrollPerPixel } |
| enum  | **[SelectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionBehavior-enum)** { SelectItems, SelectRows, SelectColumns } |
| enum  | **[SelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)** { SingleSelection, ContiguousSelection, ExtendedSelection, MultiSelection, NoSelection } |

## 特性

| **[alternatingRowColors](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alternatingRowColors-prop)** : bool**[autoScroll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoScroll-prop)** : bool**[autoScrollMargin](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoScrollMargin-prop)** : int**[defaultDropAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultDropAction-prop)** : Qt::DropAction**[dragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropMode-prop)** : DragDropMode**[dragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)** : bool**[dragEnabled](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)** : bool**[editTriggers](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editTriggers-prop)** : EditTriggers | **[horizontalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollMode-prop)** : ScrollMode**[iconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)** : QSize**[selectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionBehavior-prop)** : SelectionBehavior**[selectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)** : SelectionMode**[showDropIndicator](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showDropIndicator-prop)** : bool**[tabKeyNavigation](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabKeyNavigation-prop)** : bool**[textElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)** : Qt::TextElideMode**[verticalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollMode-prop)** : ScrollMode |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                                      | **[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QAbstractItemView)**(QWidget **parent* = nullptr) |
| ------------------------------------ | ------------------------------------------------------------ |
| virtual                              | **[~QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QAbstractItemView)**() |
| bool                                 | **[alternatingRowColors](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alternatingRowColors-prop)**() const |
| int                                  | **[autoScrollMargin](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoScrollMargin-prop)**() const |
| void                                 | **[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)**(const QModelIndex &*index*) |
| QModelIndex                          | **[currentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex)**() const |
| Qt::DropAction                       | **[defaultDropAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultDropAction-prop)**() const |
| QAbstractItemView::DragDropMode      | **[dragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropMode-prop)**() const |
| bool                                 | **[dragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)**() const |
| bool                                 | **[dragEnabled](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)**() const |
| QAbstractItemView::EditTriggers      | **[editTriggers](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editTriggers-prop)**() const |
| bool                                 | **[hasAutoScroll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoScroll-prop)**() const |
| QAbstractItemView::ScrollMode        | **[horizontalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollMode-prop)**() const |
| QSize                                | **[iconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)**() const |
| virtual QModelIndex                  | **[indexAt](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)**(const QPoint &*point*) const = 0 |
| QWidget *                            | **[indexWidget](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexWidget)**(const QModelIndex &*index*) const |
| bool                                 | **[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)**(const QModelIndex &*index*) const |
| QAbstractItemDelegate *              | **[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)**() const |
| QAbstractItemDelegate *              | **[itemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForColumn)**(int *column*) const |
| virtual QAbstractItemDelegate *      | **[itemDelegateForIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForIndex)**(const QModelIndex &*index*) const |
| QAbstractItemDelegate *              | **[itemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForRow)**(int *row*) const |
| virtual void                         | **[keyboardSearch](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardSearch)**(const QString &*search*) |
| QAbstractItemModel *                 | **[model](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model)**() const |
| void                                 | **[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)**(const QModelIndex &*index*) |
| void                                 | **[resetHorizontalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollMode-prop)**() |
| void                                 | **[resetVerticalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollMode-prop)**() |
| QModelIndex                          | **[rootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootIndex)**() const |
| virtual void                         | **[scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)**(const QModelIndex &*index*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) = 0 |
| QAbstractItemView::SelectionBehavior | **[selectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionBehavior-prop)**() const |
| QAbstractItemView::SelectionMode     | **[selectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)**() const |
| QItemSelectionModel *                | **[selectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionModel)**() const |
| void                                 | **[setAlternatingRowColors](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alternatingRowColors-prop)**(bool *enable*) |
| void                                 | **[setAutoScroll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoScroll-prop)**(bool *enable*) |
| void                                 | **[setAutoScrollMargin](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoScrollMargin-prop)**(int *margin*) |
| void                                 | **[setDefaultDropAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultDropAction-prop)**(Qt::DropAction *dropAction*) |
| void                                 | **[setDragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropMode-prop)**(QAbstractItemView::DragDropMode *behavior*) |
| void                                 | **[setDragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)**(bool *overwrite*) |
| void                                 | **[setDragEnabled](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)**(bool *enable*) |
| void                                 | **[setDropIndicatorShown](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showDropIndicator-prop)**(bool *enable*) |
| void                                 | **[setEditTriggers](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editTriggers-prop)**(QAbstractItemView::EditTriggers *triggers*) |
| void                                 | **[setHorizontalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollMode-prop)**(QAbstractItemView::ScrollMode *mode*) |
| void                                 | **[setIconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)**(const QSize &*size*) |
| void                                 | **[setIndexWidget](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIndexWidget)**(const QModelIndex &*index*, QWidget **widget*) |
| void                                 | **[setItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegate)**(QAbstractItemDelegate **delegate*) |
| void                                 | **[setItemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForColumn)**(int *column*, QAbstractItemDelegate **delegate*) |
| void                                 | **[setItemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForRow)**(int *row*, QAbstractItemDelegate **delegate*) |
| virtual void                         | **[setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)**(QAbstractItemModel **model*) |
| void                                 | **[setSelectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionBehavior-prop)**(QAbstractItemView::SelectionBehavior *behavior*) |
| void                                 | **[setSelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)**(QAbstractItemView::SelectionMode *mode*) |
| virtual void                         | **[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)**(QItemSelectionModel **selectionModel*) |
| void                                 | **[setTabKeyNavigation](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabKeyNavigation-prop)**(bool *enable*) |
| void                                 | **[setTextElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)**(Qt::TextElideMode *mode*) |
| void                                 | **[setVerticalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollMode-prop)**(QAbstractItemView::ScrollMode *mode*) |
| bool                                 | **[showDropIndicator](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showDropIndicator-prop)**() const |
| virtual int                          | **[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)**(int *column*) const |
| QSize                                | **[sizeHintForIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForIndex)**(const QModelIndex &*index*) const |
| virtual int                          | **[sizeHintForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)**(int *row*) const |
| bool                                 | **[tabKeyNavigation](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabKeyNavigation-prop)**() const |
| Qt::TextElideMode                    | **[textElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)**() const |
| QAbstractItemView::ScrollMode        | **[verticalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollMode-prop)**() const |
| virtual QRect                        | **[visualRect](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)**(const QModelIndex &*index*) const = 0 |

## 重新实施公共职能

| virtual QVariant | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *query*) const override |
| ---------------- | ------------------------------------------------------------ |
|                  |                                                              |

## 公共老虎机

| void         | **[clearSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)**() |
| ------------ | ------------------------------------------------------------ |
| void         | **[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit)**(const QModelIndex &*index*) |
| virtual void | **[reset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)**() |
| void         | **[scrollToBottom](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToBottom)**() |
| void         | **[scrollToTop](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToTop)**() |
| virtual void | **[selectAll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)**() |
| void         | **[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentIndex)**(const QModelIndex &*index*) |
| virtual void | **[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)**(const QModelIndex &*index*) |
| void         | **[update](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)**(const QModelIndex &*index*) |

## 信号

| void | **[activated](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)**(const QModelIndex &*index*) |
| ---- | ------------------------------------------------------------ |
| void | **[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)**(const QModelIndex &*index*) |
| void | **[doubleClicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doubleClicked)**(const QModelIndex &*index*) |
| void | **[entered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entered)**(const QModelIndex &*index*) |
| void | **[iconSizeChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)**(const QSize &*size*) |
| void | **[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)**(const QModelIndex &*index*) |
| void | **[viewportEntered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEntered)**() |

## 受保护类型

| enum | **[CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum)** { MoveUp, MoveDown, MoveLeft, MoveRight, MoveHome, …, MovePrevious } |
| ---- | ------------------------------------------------------------ |
| enum | **[DropIndicatorPosition](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropIndicatorPosition-enum)** { OnItem, AboveItem, BelowItem, OnViewport } |
| enum | **[State](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)** { NoState, DraggingState, DragSelectingState, EditingState, ExpandingState, …, AnimatingState } |

## 受保护的功能

| QPoint                                      | **[dirtyRegionOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirtyRegionOffset)**() const |
| ------------------------------------------- | ------------------------------------------------------------ |
| QAbstractItemView::DropIndicatorPosition    | **[dropIndicatorPosition](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropIndicatorPosition)**() const |
| virtual bool                                | **[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit-1)**(const QModelIndex &*index*, QAbstractItemView::EditTrigger *trigger*, QEvent **event*) |
| void                                        | **[executeDelayedItemsLayout](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#executeDelayedItemsLayout)**() |
| virtual int                                 | **[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)**() const = 0 |
| virtual void                                | **[initViewItemOption](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initViewItemOption)**(QStyleOptionViewItem **option*) const |
| virtual bool                                | **[isIndexHidden](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)**(const QModelIndex &*index*) const = 0 |
| virtual QModelIndex                         | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QAbstractItemView::CursorAction *cursorAction*, Qt::KeyboardModifiers *modifiers*) = 0 |
| void                                        | **[scheduleDelayedItemsLayout](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scheduleDelayedItemsLayout)**() |
| void                                        | **[scrollDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollDirtyRegion)**(int *dx*, int *dy*) |
| virtual QModelIndexList                     | **[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)**() const |
| virtual QItemSelectionModel::SelectionFlags | **[selectionCommand](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionCommand)**(const QModelIndex &*index*, const QEvent **event* = nullptr) const |
| void                                        | **[setDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDirtyRegion)**(const QRegion &*region*) |
| virtual void                                | **[setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)**(const QRect &*rect*, QItemSelectionModel::SelectionFlags *flags*) = 0 |
| void                                        | **[setState](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setState)**(QAbstractItemView::State *state*) |
| virtual void                                | **[startDrag](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)**(Qt::DropActions *supportedActions*) |
| QAbstractItemView::State                    | **[state](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#state)**() const |
| virtual int                                 | **[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)**() const = 0 |
| virtual QRegion                             | **[visualRegionForSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)**(const QItemSelection &*selection*) const = 0 |

## 重新实现受保护的功能

| virtual void  | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QDragEnterEvent **event*) override |
| ------------- | ------------------------------------------------------------ |
| virtual void  | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **event*) override |
| virtual void  | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **event*) override |
| virtual void  | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **event*) override |
| virtual bool  | **[event](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| virtual bool  | **[eventFilter](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)**(QObject **object*, QEvent **event*) override |
| virtual void  | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **event*) override |
| virtual bool  | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void  | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **event*) override |
| virtual void  | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **event*) override |
| virtual void  | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) override |
| virtual void  | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **event*) override |
| virtual void  | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **event*) override |
| virtual void  | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **event*) override |
| virtual void  | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **event*) override |
| virtual void  | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **event*) override |
| virtual void  | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **event*) override |
| virtual bool  | **[viewportEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)**(QEvent **event*) override |
| virtual QSize | **[viewportSizeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)**() const override |

## 受保护的插槽

| virtual void | **[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)**(QWidget **editor*, QAbstractItemDelegate::EndEditHint *hint*) |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[commitData](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitData)**(QWidget **editor*) |
| virtual void | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(const QModelIndex &*current*, const QModelIndex &*previous*) |
| virtual void | **[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)**(const QModelIndex &*topLeft*, const QModelIndex &*bottomRight*, const QList< int> &*roles* = QList< int>()) |
| virtual void | **[editorDestroyed](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editorDestroyed)**(QObject **editor*) |
| virtual void | **[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)**(const QModelIndex &*parent*, int *start*, int *end*) |
| virtual void | **[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)**(const QModelIndex &*parent*, int *start*, int *end*) |
| virtual void | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**(const QItemSelection &*selected*, const QItemSelection &*deselected*) |
| virtual void | **[updateGeometries](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)**() |

## 详细说明

QAbstractItemView 类是每个使用[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。QAbstractItemView 是一个抽象类，本身无法实例化。它提供了一个标准接口，用于通过信号和槽机制与模型进行互操作，使子类能够及时了解其模型的更改。此类提供对键盘和鼠标导航、视口滚动、项目编辑和选择的标准支持。键盘导航实现了此功能：

|       按键        |                        功能性                        |
| :---------------: | :--------------------------------------------------: |
|      方向键       |                更改当前项目并选择它。                |
|    Ctrl+箭头键    |               更改当前项目但不选择它。               |
|   Shift+箭头键    | 更改当前项目并选择它。先前选择的项目不会被取消选择。 |
|    Ctrl+空格键    |                 切换当前项目的选择。                 |
|  选项卡/后选项卡  |         将当前项目更改为下一个/上一个项目。          |
|     首页/结束     |          选择模型中的第一个/最后一个项目。           |
| 向上翻页/向下翻页 |       按视图中可见行数向上/向下滚动显示的行。        |
|      Ctrl+A       |                选择模型中的所有项目。                |

请注意，上表假设[selection mode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)允许操作。例如，如果选择模式为，则无法选择项目[QAbstractItemView::NoSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)。

QAbstractItemView 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

继承QAbstractItemView的视图类只需要实现自己的特定于视图的功能，例如绘制项目、返回项目的几何形状、查找项目等。

QAbstractItemView 提供了常见的插槽，例如[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit)（） 和[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentIndex)()。还提供了许多受保护的插槽，包括[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)(),[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)(),[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)(),[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)（）， 和[currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)()。

根项由以下方式返回[rootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootIndex)() 和当前项目[currentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex)()。要确保某个项目可见，请使用[scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)()。

QAbstractItemView 的一些功能与滚动有关，例如[setHorizontalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollMode-prop)（） 和[setVerticalScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollMode-prop)()。要设置滚动条的范围，您可以例如重新实现视图的[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（） 功能：

```
void MyView::resizeEvent(QResizeEvent *event) {
    horizontalScrollBar()->setRange(0, realWidth - width());
    ...
}
```

请注意，在显示小部件之前，范围不会更新。

其他几个函数与选择控制有关；例如[setSelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)（）， 和[setSelectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionBehavior-prop)()。此类提供了一个默认的选择模型来使用（[selectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionModel)())，但这可以通过使用替换[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)() 与一个实例[QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

为了完全控制项目的显示和编辑，您可以指定一个委托[setItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegate)()。

QAbstractItemView提供了很多受保护的功能。有些与编辑有关，例如，[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit)（）， 和[commitData](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitData)()，而其他的是键盘和鼠标事件处理程序。

**注意：**如果你继承了QAbstractItemView并且打算更新viewport的内容，你应该使用viewport->[update](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)（） 代替[update](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 因为所有绘画操作都在视口上进行。

**也可以看看**[View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#view-classes),[Model/View Programming](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QAbstractItemView::CursorAction

该枚举描述了在项目之间导航的不同方式，

| 持续的                            | 价值 | 描述                     |
| --------------------------------- | ---- | ------------------------ |
| `QAbstractItemView::MoveUp`       | `0`  | 移至当前项目上方的项目。 |
| `QAbstractItemView::MoveDown`     | `1`  | 移至当前项目下方的项目。 |
| `QAbstractItemView::MoveLeft`     | `2`  | 移至当前项目左侧的项目。 |
| `QAbstractItemView::MoveRight`    | `3`  | 移至当前项目右侧的项目。 |
| `QAbstractItemView::MoveHome`     | `4`  | 移至左上角项目。         |
| `QAbstractItemView::MoveEnd`      | `5`  | 移至右下角项目。         |
| `QAbstractItemView::MovePageUp`   | `6`  | 将当前项目上移一页。     |
| `QAbstractItemView::MovePageDown` | `7`  | 将当前项目下移一页。     |
| `QAbstractItemView::MoveNext`     | `8`  | 移至当前项目之后的项目。 |
| `QAbstractItemView::MovePrevious` | `9`  | 移至当前项目之前的项目。 |

**也可以看看**[moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)()。

### enum QAbstractItemView::DragDropMode

描述视图可以执行的各种拖放事件。默认情况下，视图不支持拖放 ( `NoDragDrop`)。

| 持续的                            | 价值 | 描述                                             |
| --------------------------------- | ---- | ------------------------------------------------ |
| `QAbstractItemView::NoDragDrop`   | `0`  | 不支持拖放。                                     |
| `QAbstractItemView::DragOnly`     | `1`  | 视图支持拖动自己的项目                           |
| `QAbstractItemView::DropOnly`     | `2`  | 该视图接受滴                                     |
| `QAbstractItemView::DragDrop`     | `3`  | 视图支持拖放                                     |
| `QAbstractItemView::InternalMove` | `4`  | 视图仅接受来自自身的移动（**而不是复制）操作。** |

请注意，所使用的模型需要提供对拖放操作的支持。

**也可以看看**[setDragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropMode-prop)（） 和[Using drag and drop with item views](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#using-drag-and-drop-with-item-views)。

### enum QAbstractItemView::DropIndicatorPosition

此枚举指示相对于当前鼠标位置处的索引的放置指示器的位置：

| 持续的                          | 价值 | 描述                                                         |
| ------------------------------- | ---- | ------------------------------------------------------------ |
| `QAbstractItemView::OnItem`     | `0`  | 该项目将被删除到索引中。                                     |
| `QAbstractItemView::AboveItem`  | `1`  | 该项目将被放置在索引上方。                                   |
| `QAbstractItemView::BelowItem`  | `2`  | 该项目将降至索引以下。                                       |
| `QAbstractItemView::OnViewport` | `3`  | 该项目将被拖放到视口中没有项目的区域。每个视图处理拖放到视口上的项目的方式取决于所使用的底层模型的行为。 |

### 枚举 QAbstractItemView:: EditTrigger 标志 QAbstractItemView:: EditTriggers

该枚举描述了将启动项目编辑的操作。

| 持续的                               | 价值 | 描述                                       |
| ------------------------------------ | ---- | ------------------------------------------ |
| `QAbstractItemView::NoEditTriggers`  | `0`  | 无法编辑。                                 |
| `QAbstractItemView::CurrentChanged`  | `1`  | 每当当前项目发生更改时，编辑就会开始。     |
| `QAbstractItemView::DoubleClicked`   | `2`  | 双击项目时开始编辑。                       |
| `QAbstractItemView::SelectedClicked` | `4`  | 单击已选择的项目时开始编辑。               |
| `QAbstractItemView::EditKeyPressed`  | `8`  | 当在项目上按下平台编辑键时，编辑开始。     |
| `QAbstractItemView::AnyKeyPressed`   | `16` | 当在某个项目上按下任意键时，编辑就会开始。 |
| `QAbstractItemView::AllEditTriggers` | `31` | 上述所有操作均开始编辑。                   |

EditTriggers 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < EditTrigger> 的类型定义。它存储 EditTrigger 值的 OR 组合。

### enum QAbstractItemView::ScrollHint

| 持续的                                | 价值 | 描述                           |
| ------------------------------------- | ---- | ------------------------------ |
| `QAbstractItemView::EnsureVisible`    | `0`  | 滚动以确保该项目可见。         |
| `QAbstractItemView::PositionAtTop`    | `1`  | 滚动以将项目放置在视口的顶部。 |
| `QAbstractItemView::PositionAtBottom` | `2`  | 滚动以将项目放置在视口的底部。 |
| `QAbstractItemView::PositionAtCenter` | `3`  | 滚动以将项目放置在视口的中心。 |

### enum QAbstractItemView::ScrollMode

描述滚动条的行为方式。将滚动模式设置为 ScrollPerPixel 时，单步长将自动调整，除非使用显式设置[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。将单步长设置为-1即可恢复自动调整。

| 持续的                              | 价值 | 描述                           |
| ----------------------------------- | ---- | ------------------------------ |
| `QAbstractItemView::ScrollPerItem`  | `0`  | 该视图将一次滚动一项内容。     |
| `QAbstractItemView::ScrollPerPixel` | `1`  | 视图将一次滚动一个像素的内容。 |

### enum QAbstractItemView::SelectionBehavior

| 持续的                             | 价值 | 描述           |
| ---------------------------------- | ---- | -------------- |
| `QAbstractItemView::SelectItems`   | `0`  | 选择单个项目。 |
| `QAbstractItemView::SelectRows`    | `1`  | 仅选择行。     |
| `QAbstractItemView::SelectColumns` | `2`  | 仅选择列。     |

### enum QAbstractItemView::SelectionMode

此枚举指示视图如何响应用户选择：

| 持续的                                   | 价值 | 描述                                                         |
| ---------------------------------------- | ---- | ------------------------------------------------------------ |
| `QAbstractItemView::SingleSelection`     | `1`  | 当用户选择一个项目时，任何已选择的项目都会变为未选择状态。用户可以通过在单击所选项目时按 Ctrl 键来取消选择所选项目。 |
| `QAbstractItemView::ContiguousSelection` | `4`  | 当用户以通常的方式选择一个项目时，选择将被清除并选择新的项目。但是，如果用户在单击某个项目时按下 Shift 键，则当前项目和单击的项目之间的所有项目都将被选中或取消选择，具体取决于单击的项目的状态。 |
| `QAbstractItemView::ExtendedSelection`   | `3`  | 当用户以通常的方式选择一个项目时，选择将被清除并选择新的项目。但是，如果用户在单击某个项目时按下 Ctrl 键，则所单击的项目将被切换，而所有其他项目将保持不变。如果用户在单击某个项目时按下 Shift 键，则当前项目和单击的项目之间的所有项目都将被选择或取消选择，具体取决于单击的项目的状态。通过将鼠标拖动到多个项目上可以选择多个项目。 |
| `QAbstractItemView::MultiSelection`      | `2`  | 当用户以通常的方式选择一个项目时，该项目的选择状态会被切换，而其他项目则保持不变。可以通过将鼠标拖动到多个项目上来切换它们。 |
| `QAbstractItemView::NoSelection`         | `0`  | 无法选择项目。                                               |

最常用的模式是 SingleSelection 和 ExtendedSelection。

### enum QAbstractItemView::State

描述视图可以处于的不同状态。这通常仅在重新实现您自己的视图时才有意义。

| 持续的                                  | 价值 | 描述                             |
| --------------------------------------- | ---- | -------------------------------- |
| `QAbstractItemView::NoState`            | `0`  | 这是默认状态。                   |
| `QAbstractItemView::DraggingState`      | `1`  | 用户正在拖动项目。               |
| `QAbstractItemView::DragSelectingState` | `2`  | 用户正在选择项目。               |
| `QAbstractItemView::EditingState`       | `3`  | 用户正在小部件编辑器中编辑项目。 |
| `QAbstractItemView::ExpandingState`     | `4`  | 用户正在打开项目的分支。         |
| `QAbstractItemView::CollapsingState`    | `5`  | 用户正在关闭项目分支。           |
| `QAbstractItemView::AnimatingState`     | `6`  | 项目视图正在执行动画。           |

## 财产文件

### alternatingRowColors : bool

该属性保存是否使用交替颜色绘制背景

如果此属性为`true`，则将使用以下方式绘制项目背景[QPalette::Base](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorRole-enum)和[QPalette::AlternateBase](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorRole-enum); 否则背景将使用[QPalette::Base](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorRole-enum)颜色。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **alternatingRowColors**() const           |
| ---- | ------------------------------------------ |
| void | **setAlternatingRowColors**(bool *enable*) |

### autoScroll : bool

该属性保存是否启用拖动移动事件中的自动滚动

如果此属性设置为 true（默认值），则[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果用户在视口边缘的 16 像素范围内拖动，则会自动滚动视图的内容。如果当前项发生更改，则视图将自动滚动以确保当前项完全可见。

此属性仅在视口接受放置时才有效。通过将此属性设置为 false 可以关闭自动滚动。

**访问功能：**

| bool | **hasAutoScroll**() const        |
| ---- | -------------------------------- |
| void | **setAutoScroll**(bool *enable*) |

### autoScrollMargin : int

该属性保存触发自动滚动时区域的大小

此属性控制触发自动滚动的视口边缘区域的大小。默认值为 16 像素。

**访问功能：**

| int  | **autoScrollMargin**() const          |
| ---- | ------------------------------------- |
| void | **setAutoScrollMargin**(int *margin*) |

### defaultDropAction : [Qt::DropAction](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum)

该属性保存 QAbstractItemView::drag() 中默认使用的放置操作

如果未设置该属性，则当支持的操作支持 CopyAction 时，放置操作为 CopyAction。

**访问功能：**

| Qt::DropAction | **defaultDropAction**() const                         |
| -------------- | ----------------------------------------------------- |
| void           | **setDefaultDropAction**(Qt::DropAction *dropAction*) |

**也可以看看**[showDropIndicator](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showDropIndicator-prop)和[dragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)。

### dragDropMode : [DragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragDropMode-enum)

该属性保存视图将执行的拖放事件

**访问功能：**

| QAbstractItemView::DragDropMode | **dragDropMode**() const                                     |
| ------------------------------- | ------------------------------------------------------------ |
| void                            | **setDragDropMode**(QAbstractItemView::DragDropMode *behavior*) |

**也可以看看**[showDropIndicator](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showDropIndicator-prop)和[dragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)。

### dragDropOverwriteMode : bool

该属性保存视图的拖放行为

如果其值为`true`，则所选数据在放置时将覆盖现有项目数据，而移动数据将清除该项目。如果其值为`false`，则当删除数据时，所选数据将作为新项目插入。移动数据时，该项目也会被删除。

默认值为`false`，如[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类。在里面[QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类，另一方面，该属性已设置为`true`.

注意：这并不是为了防止覆盖项目。模型的 flags() 实现应该通过不返回来实现[Qt::ItemIsDropEnabled](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)。

**访问功能：**

| bool | **dragDropOverwriteMode**() const              |
| ---- | ---------------------------------------------- |
| void | **setDragDropOverwriteMode**(bool *overwrite*) |

**也可以看看**[dragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropMode-prop)。

### dragEnabled : bool

该属性保存视图是否支持拖动自己的项目

**访问功能：**

| bool | **dragEnabled**() const           |
| ---- | --------------------------------- |
| void | **setDragEnabled**(bool *enable*) |

**也可以看看**[showDropIndicator](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showDropIndicator-prop),[DragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragDropMode-enum),[dragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)， 和[acceptDrops](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptDrops-prop)。

### editTriggers : [EditTriggers](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EditTrigger-enum)

该属性保存哪些操作将启动项目编辑

该属性是由以下定义的标志选择[EditTrigger](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EditTrigger-enum)，使用 OR 运算符组合。仅当在此属性中设置了执行的操作时，视图才会启动项目的编辑。

**访问功能：**

| QAbstractItemView::EditTriggers | **editTriggers**() const                                     |
| ------------------------------- | ------------------------------------------------------------ |
| void                            | **setEditTriggers**(QAbstractItemView::EditTriggers *triggers*) |

### horizontalScrollMode : [ScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollMode-enum)

视图如何在水平方向滚动其内容

此属性控制视图如何水平滚动其内容。滚动可以按像素或按项目进行。它的默认值来自于样式[QStyle::SH_ItemView_ScrollMode](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleHint-enum)风格提示。

**访问功能：**

| QAbstractItemView::ScrollMode | **horizontalScrollMode**() const                             |
| ----------------------------- | ------------------------------------------------------------ |
| void                          | **setHorizontalScrollMode**(QAbstractItemView::ScrollMode *mode*) |
| void                          | **resetHorizontalScrollMode**()                              |

### iconSize : [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存项目图标的大小

当视图可见时设置此属性将导致项目再次布局。

**访问功能：**

| QSize | **iconSize**() const                 |
| ----- | ------------------------------------ |
| void  | **setIconSize**(const QSize &*size*) |

**通知器信号：**

| void | **iconSizeChanged**(const QSize &*size*) |
| ---- | ---------------------------------------- |
|      |                                          |

### selectionBehavior : [SelectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionBehavior-enum)

该属性保存视图使用的选择行为

该属性保存选择是否按单个项目、行或列进行。

**访问功能：**

| QAbstractItemView::SelectionBehavior | **selectionBehavior**() const                                |
| ------------------------------------ | ------------------------------------------------------------ |
| void                                 | **setSelectionBehavior**(QAbstractItemView::SelectionBehavior *behavior*) |

**也可以看看**[SelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)和[SelectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionBehavior-enum)。

### selectionMode : [SelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)

该属性保存视图运行的选择模式

此属性控制用户是否可以选择一个或多个项目，以及在多项目选择中，选择是否必须是连续的项目范围。

**访问功能：**

| QAbstractItemView::SelectionMode | **selectionMode**() const                                    |
| -------------------------------- | ------------------------------------------------------------ |
| void                             | **setSelectionMode**(QAbstractItemView::SelectionMode *mode*) |

**也可以看看**[SelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)和[SelectionBehavior](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionBehavior-enum)。

### showDropIndicator : bool

该属性保存在拖动项目并放置时是否显示放置指示器。

**访问功能：**

| bool | **showDropIndicator**() const            |
| ---- | ---------------------------------------- |
| void | **setDropIndicatorShown**(bool *enable*) |

**也可以看看**[dragEnabled](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop),[DragDropMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragDropMode-enum),[dragDropOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragDropOverwriteMode-prop)， 和[acceptDrops](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptDrops-prop)。

### tabKeyNavigation : bool

该属性保存是否启用带有选项卡和后选项卡的项目导航。

**访问功能：**

| bool | **tabKeyNavigation**() const           |
| ---- | -------------------------------------- |
| void | **setTabKeyNavigation**(bool *enable*) |

### textElideMode : [Qt::TextElideMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextElideMode-enum)

此属性保存省略文本中“...”的位置。

所有项目视图的默认值为[Qt::ElideRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextElideMode-enum)。

**访问功能：**

| Qt::TextElideMode | **textElideMode**() const                      |
| ----------------- | ---------------------------------------------- |
| void              | **setTextElideMode**(Qt::TextElideMode *mode*) |

### verticalScrollMode : [ScrollMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollMode-enum)

视图如何在垂直方向滚动其内容

此属性控制视图如何垂直滚动其内容。滚动可以按像素或按项目进行。它的默认值来自于样式[QStyle::SH_ItemView_ScrollMode](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleHint-enum)风格提示。

**访问功能：**

| QAbstractItemView::ScrollMode | **verticalScrollMode**() const                               |
| ----------------------------- | ------------------------------------------------------------ |
| void                          | **setVerticalScrollMode**(QAbstractItemView::ScrollMode *mode*) |
| void                          | **resetVerticalScrollMode**()                                |

## 成员函数文档

### `[explicit]`QAbstractItemView::QAbstractItemView([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的内容构造一个抽象项目视图*parent*。

### `[virtual noexcept]`QAbstractItemView::~QAbstractItemView()

破坏了景色。

### `[signal]`void QAbstractItemView::activated(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当由指定的项目时，发出此信号*index*由用户激活。如何激活物品取决于平台；例如，单击或双击该项目，或者在该项目为当前项目时按 Return 或 Enter 键。

**也可以看看**[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)(),[doubleClicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doubleClicked)(),[entered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entered)（）， 和[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)()。

### `[slot]`void QAbstractItemView::clearSelection()

取消选择所有选定的项目。当前索引不会改变。

**也可以看看**[setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（） 和[selectAll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()。

### `[signal]`void QAbstractItemView::clicked(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

单击鼠标左键时会发出此信号。鼠标单击的项目由以下指定*index*。仅当索引有效时才会发出该信号。

**也可以看看**[activated](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)(),[doubleClicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doubleClicked)(),[entered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entered)（）， 和[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)()。

### `[virtual protected slot]`void QAbstractItemView::closeEditor([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **editor*, [QAbstractItemDelegate::EndEditHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EndEditHint-enum) *hint*)

关闭给定的*editor*，并释放它。这*hint*用于指定视图应如何响应编辑操作的结束。例如，提示可能指示应打开视图中的下一项进行编辑。

**也可以看看**[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit)（） 和[commitData](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitData)()。

### void QAbstractItemView::closePersistentEditor(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

在给定的位置关闭项目的持久编辑器*index*。

**也可以看看**[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)（） 和[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)()。

### `[virtual protected slot]`void QAbstractItemView::commitData([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **editor*)

提交数据在*editor*到模型。

**也可以看看**[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)()。

### `[virtual protected slot]`void QAbstractItemView::currentChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*current*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*previous*)

当新项目成为当前项目时，将调用此槽。前一个当前项目由*previous*索引，以及新项目*current*指数。

如果您想了解项目的更改，请参阅[dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)（） 信号。

### [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::currentIndex() const

返回当前项目的模型索引。

**也可以看看**[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentIndex)()。

### `[virtual protected slot]`void QAbstractItemView::dataChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*topLeft*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*bottomRight*, const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< int> &*roles* = QList< int>())

当具有给定的项目时调用此插槽*roles*在模型中进行了更改。更改的项目是来自*topLeft*到*bottomRight*包括的。如果仅更改一项*topLeft*==*bottomRight*。

这*roles*已更改的容器可以是空容器（意味着一切都已更改），也可以是包含已更改角色子集的非空容器。

**笔记：**：[Qt::ToolTipRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)Qt 提供的视图中的 dataChanged() 不支持。

### `[protected]`[QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::dirtyRegionOffset() const

返回视图中脏区域的偏移量。

如果你使用[scrollDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollDirtyRegion)() 并实施[paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)() 的子类[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，您应该使用此函数返回的偏移量来平移绘制事件给出的区域。

**也可以看看**[scrollDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollDirtyRegion)（） 和[setDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDirtyRegion)()。

### `[signal]`void QAbstractItemView::doubleClicked(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当双击鼠标按钮时会发出此信号。鼠标双击的项目由*index*。仅当索引有效时才会发出该信号。

**也可以看看**[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)（） 和[activated](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)()。

### `[override virtual protected]`void QAbstractItemView::dragEnterEvent([QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（QDragEnterEvent *事件）。

使用给定的值调用该函数*event*当拖放操作进入小部件时。如果拖动是在有效的放置位置上（例如在接受放置的项目上），则事件被接受；否则它会被忽略。

**也可以看看**[dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（） 和[startDrag](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)()。

### `[override virtual protected]`void QAbstractItemView::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

当被拖动的项目离开视图时调用此函数。这*event*描述拖放操作的状态。

### `[override virtual protected]`void QAbstractItemView::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

使用给定的值连续调用该函数*event*在小部件上进行拖放操作期间。例如，如果用户将所选内容拖动到视图的右边缘或下边缘，它可能会导致视图滚动。在这种情况下，该事件将被接受；否则它将被忽略。

**也可以看看**[dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（） 和[startDrag](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)()。

### `[override virtual protected]`void QAbstractItemView::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

使用给定的值调用该函数*event*当小部件上发生放置事件时。如果模型接受偶数位置，则接受放置事件；否则它会被忽略。

**也可以看看**[startDrag](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)()。

### `[protected]`[QAbstractItemView::DropIndicatorPosition](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropIndicatorPosition-enum) QAbstractItemView::dropIndicatorPosition() const

返回放置指示器相对于最近项目的位置。

### `[slot]`void QAbstractItemView::edit(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

开始编辑与给定对应的项目*index*如果它是可编辑的。

请注意，此函数不会更改当前索引。由于当前索引定义了要编辑的下一个和上一个项目，因此用户可能会发现键盘导航无法按预期工作。要提供一致的导航行为，请调用[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentIndex)() 在此函数之前具有相同的模型索引。

**也可以看看**[QModelIndex::flags](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)()。

### `[virtual protected]`bool QAbstractItemView::edit(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemView::EditTrigger](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EditTrigger-enum) *trigger*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

开始编辑项目*index*`true`，如果需要的话创建一个编辑器，如果视图是则返回[State](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)就是现在[EditingState](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum); 否则返回`false`.

引起编辑过程的操作描述为*trigger*，并且关联的事件由以下方式指定*event*。

可以通过指定强制编辑*trigger*成为[QAbstractItemView::AllEditTriggers](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EditTrigger-enum)。

**也可以看看**[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)()。

### `[virtual protected slot]`void QAbstractItemView::editorDestroyed([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **editor*)

当给定的*editor*已被摧毁。

**也可以看看**[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)()。

### `[signal]`void QAbstractItemView::entered(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当鼠标光标进入指定的项目时发出此信号*index*。需要启用鼠标跟踪才能使用此功能。

**也可以看看**[viewportEntered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEntered)(),[activated](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)(),[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)(),[doubleClicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doubleClicked)（）， 和[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)()。

### `[override virtual protected]`bool QAbstractItemView::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::event](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`bool QAbstractItemView::eventFilter([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **object*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QObject::eventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)（QObject *观看，QEvent *事件）。

### `[protected]`void QAbstractItemView::executeDelayedItemsLayout()

执行计划的布局，无需等待事件处理开始。

**也可以看看**[scheduleDelayedItemsLayout](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scheduleDelayedItemsLayout)()。

### `[override virtual protected]`void QAbstractItemView::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

使用给定的值调用该函数*event*当小部件获得焦点时。默认情况下，该事件被忽略。

**也可以看看**[setFocus](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus-1)（） 和[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)()。

### `[override virtual protected]`bool QAbstractItemView::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QAbstractItemView::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

使用给定的值调用该函数*event*当小部件失去焦点时。默认情况下，该事件被忽略。

**也可以看看**[clearFocus](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)（） 和[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)()。

### `[pure virtual protected]`int QAbstractItemView::horizontalOffset() const

返回视图的水平偏移量。

在基类中，这是一个纯虚函数。

**也可以看看**[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)()。

### `[pure virtual]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::indexAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

返回项目在视口坐标处的模型索引*point*。

在基类中，这是一个纯虚函数。

**也可以看看**[visualRect](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QAbstractItemView::indexWidget(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回给定项目的小部件*index*。

**也可以看看**[setIndexWidget](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIndexWidget)()。

### `[virtual protected, since 6.0]`void QAbstractItemView::initViewItemOption([QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*具有视图调色板、字体、状态、对齐方式等的结构。

**注意：**此方法的实现应检查[version](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#version-var)接收到的结构中，填充实现熟悉的所有成员，并在返回之前将版本成员设置为实现支持的成员。

这个函数是在Qt 6.0中引入的。

### `[override virtual protected]`void QAbstractItemView::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)（QInputMethodEvent *事件）。

### `[override virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *query*) const

重新实现：[QWidget::inputMethodQuery(Qt::InputMethodQuery query) const](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)。

### `[pure virtual protected]`bool QAbstractItemView::isIndexHidden(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回`true`是否由给定引用的项目*index*隐藏在视图中，否则返回`false`。

隐藏是视图特定的功能。例如在[TableView](https://doc-qt-io.translate.goog/qt-6/qml-qtquick-tableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)列可以标记为隐藏或行[TreeView](https://doc-qt-io.translate.goog/qt-6/qml-qtquick-treeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

在基类中，这是一个纯虚函数。

### bool QAbstractItemView::isPersistentEditorOpen(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回是否为索引处的项目打开持久编辑器*index*。

**也可以看看**[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)（） 和[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)()。

### [QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemView::itemDelegate() const

返回此视图和模型使用的项目委托。这是一组[setItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegate)()，或默认值。

**也可以看看**[setItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegate)()。

### [QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemView::itemDelegateForColumn(int *column*) const

返回此视图和给定模型使用的项目委托*column*。您可以致电[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)() 获取指向给定索引的当前委托的指针。

**也可以看看**[setItemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForColumn)(),[itemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForRow)（）， 和[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)()。

### `[virtual, since 6.0]`[QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemView::itemDelegateForIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回此视图和给定模型使用的项目委托*index*。

这个函数是在Qt 6.0中引入的。

**也可以看看**[setItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegate)(),[setItemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForRow)（）， 和[setItemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForColumn)()。

### [QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemView::itemDelegateForRow(int *row*) const

返回此视图和给定模型使用的项目委托*row*，或者`nullptr`如果尚未分配代表。您可以致电[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)() 获取指向给定索引的当前委托的指针。

**也可以看看**[setItemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForRow)(),[itemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForColumn)（）， 和[setItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegate)()。

### `[override virtual protected]`void QAbstractItemView::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

使用给定的值调用该函数*event*当按键事件发送到小部件时。默认实现处理基本的光标移动，例如上、下、左、右、Home、PageUp 和 PageDown；这[activated](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)如果当前索引有效并且按下激活键（例如 Enter 或 Return，具体取决于平台），则发出 () 信号。此功能是通过按键启动编辑的地方，例如，如果按 F2。

**也可以看看**[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit)(),[moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)(),[keyboardSearch](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardSearch)（）， 和[tabKeyNavigation](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabKeyNavigation-prop)。

### `[virtual]`void QAbstractItemView::keyboardSearch(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*search*)

移动到并选择与字符串最匹配的项目*search*。如果没有找到任何项目，则不会发生任何事情。

在默认实现中，如果出现以下情况，搜索将被重置：*search*为空，或者距离上次搜索的时间间隔已过[QApplication::keyboardInputInterval](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardInputInterval-prop)()。

### [QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemView::model() const

返回此视图所呈现的模型。

**也可以看看**[setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)()。

### `[override virtual protected]`void QAbstractItemView::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)(QMouseEvent *e)。

使用给定的值调用该函数*event*当在小部件内双击鼠标按钮时。如果双击有效项目，则会发出[doubleClicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doubleClicked)() 信号和调用[edit](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#edit)() 的项目。

### `[override virtual protected]`void QAbstractItemView::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

使用给定的值调用该函数*event*当鼠标移动事件发送到小部件时。如果正在进行选择并且新项目移至选择范围内，则扩展选择；如果拖动正在进行中，则会继续。

### `[override virtual protected]`void QAbstractItemView::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(QMouseEvent *e)。

使用给定的值调用该函数*event*当光标位于小部件内时按下鼠标按钮。如果按下有效项目，它将成为当前项目。该函数发出[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)（） 信号。

### `[override virtual protected]`void QAbstractItemView::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(QMouseEvent *e)。

使用给定的值调用该函数*event*当释放鼠标按钮时，在小部件上发生鼠标按下事件后。如果用户在您的小部件内按下鼠标，然后将鼠标拖动到另一个位置，然后释放鼠标按钮，您的小部件将收到释放事件。该函数将发出[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)() 表示是否按下某个项目。

### `[pure virtual protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::moveCursor([QAbstractItemView::CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum) *cursorAction*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*)

返回一个[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)基于给定的对象指向视图中的下一个对象*cursorAction*和键盘修饰符指定*modifiers*。

在基类中，这是一个纯虚函数。

### void QAbstractItemView::openPersistentEditor(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

在给定的项目上打开持久编辑器*index*。如果不存在编辑器，委托将创建一个新编辑器。

**也可以看看**[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)（） 和[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)()。

### `[signal]`void QAbstractItemView::pressed(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当按下鼠标按钮时会发出此信号。鼠标按下的项目由*index*。仅当索引有效时才会发出该信号。

使用[QGuiApplication::mouseButtons](https://doc-qt-io.translate.goog/qt-6/qguiapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseButtons)() 函数获取鼠标按钮的状态。

**也可以看看**[activated](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)(),[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)(),[doubleClicked](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doubleClicked)（）， 和[entered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entered)()。

### `[virtual slot]`void QAbstractItemView::reset()

重置视图的内部状态。

**警告：**此函数将重置打开的编辑器、滚动条位置、选择等。现有更改将不会被提交。如果您想在重置视图时保存更改，您可以重新实现此函数，提交更改，然后调用超类的实现。

### `[override virtual protected]`void QAbstractItemView::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

使用给定的值调用该函数*event*当调整大小事件发送到小部件时。

**也可以看看**[QWidget::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)()。

### [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::rootIndex() const

返回模型根项的模型索引。根项是视图顶级项的父项。根可能无效。

**也可以看看**[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)()。

### `[virtual protected slot]`void QAbstractItemView::rowsAboutToBeRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

当行即将被删除时，将调用此槽。删除的行是给定的行*parent*从*start*到*end*包括的。

**也可以看看**[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)()。

### `[virtual protected slot]`void QAbstractItemView::rowsInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

插入行时会调用此槽。新行是给定的行*parent*从*start*到*end*包括的。基类实现调用模型上的 fetchMore() 以检查更多数据。

**也可以看看**[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)()。

### `[protected]`void QAbstractItemView::scheduleDelayedItemsLayout()

安排事件处理开始时要执行的视图中的项目布局。

即使在处理事件之前多次调用scheduleDelayedItemsLayout()，视图也只会进行一次布局。

**也可以看看**[executeDelayedItemsLayout](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#executeDelayedItemsLayout)()。

### `[protected]`void QAbstractItemView::scrollDirtyRegion(int *dx*, int *dy*)

准备视图以滚动 (*dx*,*dy*）通过向相反方向移动脏区域的像素。仅当您在视图子类中实现滚动视口时，才需要调用此函数。

如果你实施[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)() 的子类[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，在调用之前调用此函数[QWidget::scroll](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scroll)() 在视口上。或者，只需致电[update](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)()。

**也可以看看**[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)(),[dirtyRegionOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirtyRegionOffset)（）， 和[setDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDirtyRegion)()。

### `[pure virtual]`void QAbstractItemView::scrollTo(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

如有必要，滚动视图以确保该项目位于*index*是可见的。视图将尝试根据给定的位置来定位项目*hint*。

在基类中，这是一个纯虚函数。

### `[slot]`void QAbstractItemView::scrollToBottom()

将视图滚动到底部。

**也可以看看**[scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)（） 和[scrollToTop](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToTop)()。

### `[slot]`void QAbstractItemView::scrollToTop()

将视图滚动到顶部。

**也可以看看**[scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)（） 和[scrollToBottom](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToBottom)()。

### `[virtual slot]`void QAbstractItemView::selectAll()

选择视图中的所有项目。此函数将使用选择时在视图上设置的选择行为。

**也可以看看**[setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)(),[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)（）， 和[clearSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)()。

### `[virtual protected]`[QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) QAbstractItemView::selectedIndexes() const

此便利函数返回视图中所有选定和非隐藏项目索引的列表。该列表不包含重复项，并且未排序。

**也可以看看**[QItemSelectionModel::selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)()。

### `[virtual protected slot]`void QAbstractItemView::selectionChanged(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selected*, const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deselected*)

当选择更改时会调用此槽。先前的选择（可能为空）由以下方式指定*deselected*，以及新的选择*selected*。

**也可以看看**[setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)()。

### `[virtual protected]`[QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) QAbstractItemView::selectionCommand(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, const [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event* = nullptr) const

返回更新指定的选择模型时要使用的 SelectionFlags*index*。结果取决于当前[selectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)()，以及用户输入事件*event*，这可以是`nullptr`。

重新实现此函数来定义您自己的选择行为。

**也可以看看**[setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)()。

### [QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemView::selectionModel() const

返回当前选择模型。

**也可以看看**[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)（） 和[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)()。

### `[slot]`void QAbstractItemView::setCurrentIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

将当前项目设置为位于的项目*index*。

除非当前选择模式是[NoSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，该项目也被选中。请注意，此函数还会更新用户执行的任何新选择的起始位置。

要将某个项目设置为当前项目而不选择它，请调用

```
selectionModel()->setCurrentIndex(index, QItemSelectionModel::NoUpdate);
```

**也可以看看**[currentIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex)(),[currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)（）， 和[selectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)。

### `[protected]`void QAbstractItemView::setDirtyRegion(const [QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*region*)

标记给定的*region*为脏并安排更新。如果您正在实现自己的视图子类，则只需调用此函数。

**也可以看看**[scrollDirtyRegion](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollDirtyRegion)（） 和[dirtyRegionOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirtyRegionOffset)()。

### void QAbstractItemView::setIndexWidget(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

设置给定的*widget*在给定的项目上*index*，将小部件的所有权传递给视口。

如果*index*无效（例如，如果您传递根索引），该函数将不执行任何操作。

给定的*widget*的[autoFillBackground](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)属性必须设置为 true，否则小部件的背景将是透明的，同时显示模型数据和给定的项目*index*。

如果将索引小部件 A 替换为索引小部件 B，则索引小部件 A 将被删除。例如，在下面的代码片段中，[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象将被删除。

```
setIndexWidget(index, new QLineEdit);
...
setIndexWidget(index, new QTextEdit);
```

此函数只能用于在与数据项相对应的可见区域内显示静态内容。如果您想显示自定义动态内容或实现自定义编辑器小部件，请子类[QStyledItemDelegate](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)反而。

**也可以看看**[indexWidget](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexWidget)（） 和[Delegate Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#delegate-classes)。

### void QAbstractItemView::setItemDelegate([QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **delegate*)

将此视图及其模型的项目委托设置为*delegate*。如果您想要完全控制项目的编辑和显示，这非常有用。

任何现有委托都将被删除，但不会被删除。[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不拥有所有权*delegate*。

**警告：**您不应在视图之间共享委托的同一实例。这样做可能会导致不正确或不直观的编辑行为，因为连接到给定委托的每个视图都可能会收到[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)() 信号，并尝试访问、修改或关闭已关闭的编辑器。

**也可以看看**[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)()。

### void QAbstractItemView::setItemDelegateForColumn(int *column*, [QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **delegate*)

设置给定的项目*delegate*该视图和模型用于给定的*column*。上的所有项目*column*将由以下人员绘制和管理*delegate*而不是使用默认委托（即[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)())。

任何现有的列委托*column*会被删除，但不会被删除。[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不拥有所有权*delegate*。

**注意：**如果委托已分配给行和列，则行委托将优先并管理相交单元格索引。

**警告：**您不应在视图之间共享委托的同一实例。这样做可能会导致不正确或不直观的编辑行为，因为连接到给定委托的每个视图都可能会收到[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)() 信号，并尝试访问、修改或关闭已关闭的编辑器。

**也可以看看**[itemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForColumn)(),[setItemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForRow)（）， 和[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)()。

### void QAbstractItemView::setItemDelegateForRow(int *row*, [QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **delegate*)

设置给定的项目*delegate*该视图和模型用于给定的*row*。上的所有项目*row*将由以下人员绘制和管理*delegate*而不是使用默认委托（即[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)())。

任何现有的行委托*row*会被删除，但不会被删除。[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不拥有所有权*delegate*。

**注意：**如果委托已分配给行和列，则行委托（即此委托）将优先并管理相交单元格索引。

**警告：**您不应在视图之间共享委托的同一实例。这样做可能会导致不正确或不直观的编辑行为，因为连接到给定委托的每个视图都可能会收到[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)() 信号，并尝试访问、修改或关闭已关闭的编辑器。

**也可以看看**[itemDelegateForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegateForRow)(),[setItemDelegateForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemDelegateForColumn)（）， 和[itemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDelegate)()。

### `[virtual]`void QAbstractItemView::setModel([QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **model*)

设置*model*以便呈现视图。

此函数将创建并设置一个新的选择模型，替换之前设置的任何模型[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)()。但是，旧的选择模型不会被删除，因为它可能在多个视图之间共享。如果不再需要旧的选择模型，我们建议您将其删除。这是通过以下代码完成的：

```
QItemSelectionModel *m = view->selectionModel();
view->setModel(new model);
delete m;
```

如果旧模型和旧选择模型都没有父对象，或者它们的父对象是长寿命对象，则最好将它们称为[deleteLater](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deleteLater)() 函数显式删除它们。

视图*不会*取得模型的所有权，除非它是模型的父对象，因为模型可能在许多不同的视图之间共享。

**也可以看看**[model](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model)(),[selectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionModel)（）， 和[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)()。

### `[virtual slot]`void QAbstractItemView::setRootIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

将根项设置为给定的项*index*。

**也可以看看**[rootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootIndex)()。

### `[pure virtual protected]`void QAbstractItemView::setSelection(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *flags*)

应用选择*flags*到矩形内或被矩形接触的项目，*rect*。

当实现你自己的 itemview setSelection 时应该调用[selectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionModel)()->select(selection, flags)，其中选择为空[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或一个[QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)包含包含在中的所有项目*rect*。

**也可以看看**[selectionCommand](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionCommand)（） 和[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)()。

### `[virtual]`void QAbstractItemView::setSelectionModel([QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **selectionModel*)

将当前选择模型设置为给定的*selectionModel*。

请注意，如果您致电[setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)() 在此函数之后，给定*selectionModel*将被视图创建的替换。

**注意：**如果不再需要旧的选择模型，则由应用程序自行删除；即，如果它没有被其他视图使用。当其父对象被删除时，这将自动发生。但是，如果它没有父对象，或者父对象是长期存在的对象，则最好调用其[deleteLater](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deleteLater)() 函数显式删除它。

**也可以看看**[selectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionModel)(),[setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)（）， 和[clearSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)()。

### `[protected]`void QAbstractItemView::setState([QAbstractItemView::State](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum) *state*)

将项目视图的状态设置为给定的*state*。

**也可以看看**[state](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#state)()。

### `[virtual]`int QAbstractItemView::sizeHintForColumn(int *column*) const

返回指定的宽度大小提示*column*如果没有模型，则为 -1。

此函数用于具有水平标题的视图，以根据给定的内容查找标题部分的大小提示*column*。

**也可以看看**[sizeHintForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)()。

### [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::sizeHintForIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回指定项目的尺寸提示*index*或无效索引的无效大小。

**也可以看看**[sizeHintForRow](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)（） 和[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)()。

### `[virtual]`int QAbstractItemView::sizeHintForRow(int *row*) const

返回指定的高度大小提示*row*如果没有模型，则为 -1。

返回的高度是使用给定的大小提示计算的*row*的items，即返回值为item中最大的高度。请注意，要控制行的高度，您必须重新实现[QAbstractItemDelegate::sizeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)（） 功能。

此函数用于具有垂直标题的视图，以根据给定的内容查找标题部分的大小提示*row*。

**也可以看看**[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)()。

### `[virtual protected]`void QAbstractItemView::startDrag([Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) *supportedActions*)

通过使用给定的调用drag->exec()来开始拖动*supportedActions*。

### `[protected]`[QAbstractItemView::State](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum) QAbstractItemView::state() const

返回项目视图的状态。

**也可以看看**[setState](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setState)()。

### `[override virtual protected]`void QAbstractItemView::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QObject::timerEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。

使用给定的值调用该函数*event*当计时器事件发送到小部件时。

**也可以看看**[QObject::timerEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)()。

### `[slot]`void QAbstractItemView::update(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

更新给定的占用区域*index*。

### `[virtual protected slot]`void QAbstractItemView::updateGeometries()

更新视图的子部件的几何形状。

### `[pure virtual protected]`int QAbstractItemView::verticalOffset() const

返回视图的垂直偏移量。

在基类中，这是一个纯虚函数。

**也可以看看**[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)()。

### `[signal]`void QAbstractItemView::viewportEntered()

当鼠标光标进入视口时会发出此信号。需要启用鼠标跟踪才能使用此功能。

**也可以看看**[entered](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entered)()。

### `[override virtual protected]`bool QAbstractItemView::viewportEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::viewportEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)（QEvent *事件）。

这个函数用来处理工具提示，What's This? 模式，如果给定*event*是一个[QEvent::ToolTip](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)，或一个[QEvent::WhatsThis](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。它将所有其他事件传递到其基类 viewportEvent() 处理程序。

返回`true`如果*event*已被识别和处理；否则，返回`false`。

### `[override virtual protected]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::viewportSizeHint() const

重新实现：[QAbstractScrollArea::viewportSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)。

### `[pure virtual]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::visualRect(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回视口中项目占据的矩形*index*。

如果您的项目显示在多个区域中，则 VisualRect 应返回包含索引的主要区域，而不是索引可能包含、触摸或导致绘制的完整区域。

在基类中，这是一个纯虚函数。

**也可以看看**[indexAt](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)（） 和[visualRegionForSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)()。

### `[pure virtual protected]`[QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemView::visualRegionForSelection(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selection*) const

返回给定项目的视口中的区域*selection*。

在基类中，这是一个纯虚函数。

**也可以看看**[visualRect](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)（） 和[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)()。