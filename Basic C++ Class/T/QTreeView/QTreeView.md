#  QTreeView Class

QTreeView 类提供树视图的默认模型/视图实现。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QTreeView>                                        |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QHelpContentWidget](https://doc-qt-io.translate.goog/qt-6/qhelpcontentwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) and [QTreeWidget](https://doc-qt-io.translate.goog/qt-6/qtreewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtreeview-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

| **[allColumnsShowFocus](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allColumnsShowFocus-prop)** : bool**[animated](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#animated-prop)** : bool**[autoExpandDelay](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoExpandDelay-prop)** : int**[expandsOnDoubleClick](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandsOnDoubleClick-prop)** : bool**[headerHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerHidden-prop)** : bool**[indentation](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentation-prop)** : int | **[itemsExpandable](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsExpandable-prop)** : bool**[rootIsDecorated](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootIsDecorated-prop)** : bool**[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)** : bool**[uniformRowHeights](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformRowHeights-prop)** : bool**[wordWrap](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)** : bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|               | **[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTreeView)**(QWidget **parent* = nullptr) |
| ------------- | ------------------------------------------------------------ |
| virtual       | **[~QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTreeView)**() |
| bool          | **[allColumnsShowFocus](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allColumnsShowFocus-prop)**() const |
| int           | **[autoExpandDelay](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoExpandDelay-prop)**() const |
| int           | **[columnAt](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnAt)**(int *x*) const |
| int           | **[columnViewportPosition](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnViewportPosition)**(int *column*) const |
| int           | **[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)**(int *column*) const |
| bool          | **[expandsOnDoubleClick](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandsOnDoubleClick-prop)**() const |
| QHeaderView * | **[header](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#header)**() const |
| int           | **[indentation](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentation-prop)**() const |
| QModelIndex   | **[indexAbove](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAbove)**(const QModelIndex &*index*) const |
| QModelIndex   | **[indexBelow](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexBelow)**(const QModelIndex &*index*) const |
| bool          | **[isAnimated](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#animated-prop)**() const |
| bool          | **[isColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isColumnHidden)**(int *column*) const |
| bool          | **[isExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExpanded)**(const QModelIndex &*index*) const |
| bool          | **[isFirstColumnSpanned](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFirstColumnSpanned)**(int *row*, const QModelIndex &*parent*) const |
| bool          | **[isHeaderHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerHidden-prop)**() const |
| bool          | **[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)**(int *row*, const QModelIndex &*parent*) const |
| bool          | **[isSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)**() const |
| bool          | **[itemsExpandable](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsExpandable-prop)**() const |
| void          | **[resetIndentation](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentation-prop)**() |
| bool          | **[rootIsDecorated](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootIsDecorated-prop)**() const |
| void          | **[setAllColumnsShowFocus](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allColumnsShowFocus-prop)**(bool *enable*) |
| void          | **[setAnimated](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#animated-prop)**(bool *enable*) |
| void          | **[setAutoExpandDelay](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoExpandDelay-prop)**(int *delay*) |
| void          | **[setColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnHidden)**(int *column*, bool *hide*) |
| void          | **[setColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidth)**(int *column*, int *width*) |
| void          | **[setExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExpanded)**(const QModelIndex &*index*, bool *expanded*) |
| void          | **[setExpandsOnDoubleClick](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandsOnDoubleClick-prop)**(bool *enable*) |
| void          | **[setFirstColumnSpanned](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFirstColumnSpanned)**(int *row*, const QModelIndex &*parent*, bool *span*) |
| void          | **[setHeader](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeader)**(QHeaderView **header*) |
| void          | **[setHeaderHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerHidden-prop)**(bool *hide*) |
| void          | **[setIndentation](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentation-prop)**(int *i*) |
| void          | **[setItemsExpandable](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsExpandable-prop)**(bool *enable*) |
| void          | **[setRootIsDecorated](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootIsDecorated-prop)**(bool *show*) |
| void          | **[setRowHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHidden)**(int *row*, const QModelIndex &*parent*, bool *hide*) |
| void          | **[setSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)**(bool *enable*) |
| void          | **[setTreePosition](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTreePosition)**(int *index*) |
| void          | **[setUniformRowHeights](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformRowHeights-prop)**(bool *uniform*) |
| void          | **[setWordWrap](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)**(bool *on*) |
| int           | **[treePosition](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#treePosition)**() const |
| bool          | **[uniformRowHeights](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformRowHeights-prop)**() const |
| bool          | **[wordWrap](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)**() const |

## 重载的公共职能

| virtual void        | **[dataChanged](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)**(const QModelIndex &*topLeft*, const QModelIndex &*bottomRight*, const QList<int> &*roles* = QList<int>()) override |
| ------------------- | ------------------------------------------------------------ |
| virtual QModelIndex | **[indexAt](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)**(const QPoint &*point*) const override |
| virtual void        | **[keyboardSearch](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardSearch)**(const QString &*search*) override |
| virtual void        | **[reset](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)**() override |
| virtual void        | **[scrollTo](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)**(const QModelIndex &*index*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) override |
| virtual void        | **[selectAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)**() override |
| virtual void        | **[setModel](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)**(QAbstractItemModel **model*) override |
| virtual void        | **[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)**(const QModelIndex &*index*) override |
| virtual void        | **[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)**(QItemSelectionModel **selectionModel*) override |
| virtual QRect       | **[visualRect](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)**(const QModelIndex &*index*) const override |

## 公共槽

| void | **[collapse](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapse)**(const QModelIndex &*index*) |
| ---- | ------------------------------------------------------------ |
| void | **[collapseAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapseAll)**() |
| void | **[expand](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expand)**(const QModelIndex &*index*) |
| void | **[expandAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandAll)**() |
| void | **[expandRecursively](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandRecursively)**(const QModelIndex &*index*, int *depth* = -1) |
| void | **[expandToDepth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandToDepth)**(int *depth*) |
| void | **[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)**(int *column*) |
| void | **[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)**(int *column*) |
| void | **[showColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showColumn)**(int *column*) |
| void | **[sortByColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortByColumn)**(int *column*, Qt::SortOrder *order*) |

## 信号

| void | **[collapsed](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapsed)**(const QModelIndex &*index*) |
| ---- | ------------------------------------------------------------ |
| void | **[expanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expanded)**(const QModelIndex &*index*) |

## protected function

| virtual void | **[drawBranches](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBranches)**(QPainter **painter*, const QRect &*rect*, const QModelIndex &*index*) const |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[drawRow](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRow)**(QPainter **painter*, const QStyleOptionViewItem &*option*, const QModelIndex &*index*) const |
| void         | **[drawTree](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawTree)**(QPainter **painter*, const QRegion &*region*) const |
| int          | **[indexRowSizeHint](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexRowSizeHint)**(const QModelIndex &*index*) const |
| int          | **[rowHeight](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowHeight)**(const QModelIndex &*index*) const |

## 重新实现protected function

| virtual void            | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **event*) override |
| ----------------------- | ------------------------------------------------------------ |
| virtual void            | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(const QModelIndex &*current*, const QModelIndex &*previous*) override |
| virtual void            | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **event*) override |
| virtual int             | **[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)**() const override |
| virtual bool            | **[isIndexHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)**(const QModelIndex &*index*) const override |
| virtual void            | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) override |
| virtual void            | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **event*) override |
| virtual void            | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **event*) override |
| virtual void            | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **event*) override |
| virtual void            | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **event*) override |
| virtual QModelIndex     | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QAbstractItemView::CursorAction *cursorAction*, Qt::KeyboardModifiers *modifiers*) override |
| virtual void            | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void            | **[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)**(const QModelIndex &*parent*, int *start*, int *end*) override |
| virtual void            | **[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)**(const QModelIndex &*parent*, int *start*, int *end*) override |
| virtual void            | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual QModelIndexList | **[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)**() const override |
| virtual void            | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**(const QItemSelection &*selected*, const QItemSelection &*deselected*) override |
| virtual void            | **[setSelection](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)**(const QRect &*rect*, QItemSelectionModel::SelectionFlags *command*) override |
| virtual int             | **[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)**(int *column*) const override |
| virtual void            | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **event*) override |
| virtual void            | **[updateGeometries](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)**() override |
| virtual int             | **[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)**() const override |
| virtual bool            | **[viewportEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)**(QEvent **event*) override |
| virtual QSize           | **[viewportSizeHint](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)**() const override |
| virtual QRegion         | **[visualRegionForSelection](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)**(const QItemSelection &*selection*) const override |

## 受保护槽

| void | **[columnCountChanged](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCountChanged)**(int *oldCount*, int *newCount*) |
| ---- | ------------------------------------------------------------ |
| void | **[columnMoved](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnMoved)**() |
| void | **[columnResized](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnResized)**(int *column*, int *oldSize*, int *newSize*) |
| void | **[rowsRemoved](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsRemoved)**(const QModelIndex &*parent*, int *start*, int *end*) |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\T\QTreeView\QTreeView\windows-treeview.png)

QTreeView 实现模型中项目的树表示。此类用于提供以前由该类提供的标准层次结构列表`QListView`，但使用 Qt 模型/视图体系结构提供的更灵活的方法。

QTreeView 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QTreeView 实现了定义的接口[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，允许它显示由派生的模型提供的数据[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级。

构建显示模型数据的树视图很简单。在下面的示例中，目录的内容由[QFileSystemModel](https://doc-qt-io.translate.goog/qt-6/qfilesystemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并显示为树：

```
    QFileSystemModel *model = new QFileSystemModel;
    model->setRootPath(QDir::currentPath());
    QTreeView *tree = new QTreeView(splitter);
    tree->setModel(model);
```

模型/视图架构确保树视图的内容随着模型的变化而更新。

具有子项的项目可以处于展开（子项可见）或折叠（子项隐藏）状态。当这个状态改变时[collapsed](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapsed)（） 或者[expanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expanded)() 信号与相关项目的型号索引一起发出。

用于指示层次结构级别的缩进量由[indentation](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentation-prop)财产。

树视图中的标题是使用[QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类并且可以使用隐藏`header()->hide()`。请注意，每个标头都配置有其[stretchLastSection](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stretchLastSection-prop)属性设置为 true，确保视图不会浪费为其标题分配的任何空间。如果此值设置为 true，则此属性将覆盖标题中最后一部分设置的调整大小模式。

默认情况下，树视图中除第一列外的所有列均可移动。要禁用这些列的移动，请使用[QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的[setSectionsMovable](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSectionsMovable)（） 功能。有关重新排列部分的更多信息，请参阅[Moving Header Sections](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moving-header-sections)。

### 按键绑定

QTreeView 支持一组键绑定，使用户能够在视图中导航并与项目内容交互：

|   钥匙   |                             行动                             |
| :------: | :----------------------------------------------------------: |
|   向上   | 将光标移动到上一行同一列中的项目。如果当前项目的父项没有更多行可导航到，则光标将移动到父项之前的同级项的最后一行中的相关项。 |
|   向下   | 将光标移动到下一行同一列中的项目。如果当前项目的父项没有更多行可供导航，则光标将移动到父项之后的同级项的第一行中的相关项。 |
|   左边   |        通过折叠分支来隐藏当前项目的子项（如果存在）。        |
|    减    |                          与左相同。                          |
|  正确的  |        通过展开分支来显示当前项目的子项（如果存在）。        |
|    加    |                          与右相同。                          |
|   星号   |            展开当前项目及其所有子项（如果存在）。            |
| 向上翻页 |                     将光标向上移动一页。                     |
| 向下翻页 |                     将光标向下移动一页。                     |
|    家    |  将光标移动到模型中第一个顶级项目的第一行的同一列中的项目。  |
|   结尾   | 将光标移动到模型中最后一个顶级项目的最后一行的同一列中的项目。 |
|    F2    | 在可编辑模型中，这将打开当前项目进行编辑。Escape 键可用于取消编辑过程并恢复对显示数据的任何更改。 |

### 提高绩效

可以向视图提供有关其正在处理的数据的提示，以便在显示大量项目时提高其性能。对于旨在显示具有相同高度的项目的视图，可以采取的一种方法是设置[uniformRowHeights](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformRowHeights-prop)属性为真。

**也可以看看**[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTreeWidget](https://doc-qt-io.translate.goog/qt-6/qtreewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#view-classes),[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Dir View Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-dirview-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### allColumnsShowFocus : bool

此属性保存项目是否应使用所有列显示键盘焦点

如果该属性为`true`所有列都会显示焦点，否则只有一列会显示焦点。

默认为 false。

**访问功能：**

| bool | **allColumnsShowFocus**() const           |
| ---- | ----------------------------------------- |
| void | **setAllColumnsShowFocus**(bool *enable*) |

### animated : bool

该属性保存是否启用动画

如果此属性是`true`树视图，则会为分支的展开和折叠设置动画。如果此属性为`false`，树视图将立即展开或折叠分支而不显示动画。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isAnimated**() const         |
| ---- | ------------------------------ |
| void | **setAnimated**(bool *enable*) |

### autoExpandDelay : int

此属性保存在拖放操作期间打开树中的项目之前的延迟时间。

此属性保存用户在节点自动打开或关闭之前必须等待该节点的时间（以毫秒为单位）。如果时间设置小于 0，则不会激活。

默认情况下，此属性的值为 -1，表示禁用自动扩展。

**访问功能：**

| int  | **autoExpandDelay**() const         |
| ---- | ----------------------------------- |
| void | **setAutoExpandDelay**(int *delay*) |

### expandsOnDoubleClick : bool

该属性保存项目是否可以通过双击展开。

该属性保存用户是否可以通过双击来展开和折叠项目。默认值是true。

**访问功能：**

| bool | **expandsOnDoubleClick**() const           |
| ---- | ------------------------------------------ |
| void | **setExpandsOnDoubleClick**(bool *enable*) |

**也可以看看**[itemsExpandable](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsExpandable-prop)。

### headerHidden : bool

该属性保存是否显示标题。

如果此属性为`true`，则不会显示标题，否则将显示标题。默认值为 false。

**访问功能：**

| bool | **isHeaderHidden**() const       |
| ---- | -------------------------------- |
| void | **setHeaderHidden**(bool *hide*) |

**也可以看看**[header](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#header)()。

### indentation : int

树视图中项目的缩进。

此属性保存树视图中每个级别的项目的缩进（以像素为单位）。对于顶级项目，缩进指定从视口边缘到第一列中的项目的水平距离；对于子项，它指定它们相对于父项的缩进。

默认情况下，此属性的值取决于样式。因此，当样式更改时，此属性也会随之更新。调用 setIndentation() 会停止更新，调用 resetIndentation() 将恢复默认行为。

**访问功能：**

| int  | **indentation**() const     |
| ---- | --------------------------- |
| void | **setIndentation**(int *i*) |
| void | **resetIndentation**()      |

### itemsExpandable : bool

该属性保存项目是否可由用户扩展。

该属性保存用户是否可以交互地展开和折叠项目。

默认情况下，该属性为`true`。

**访问功能：**

| bool | **itemsExpandable**() const           |
| ---- | ------------------------------------- |
| void | **setItemsExpandable**(bool *enable*) |

### rootIsDecorated : bool

该属性保存是否显示用于展开和折叠顶级项目的控件

带有子项的项目通常显示有用于展开和折叠它们的控件，从而允许显示或隐藏其子项。如果此属性为 false，则不会为顶级项目显示这些控件。这可用于使单级树结构看起来像简单的项目列表。

默认情况下，该属性为`true`。

**访问功能：**

| bool | **rootIsDecorated**() const         |
| ---- | ----------------------------------- |
| void | **setRootIsDecorated**(bool *show*) |

### sortingEnabled : bool

该属性保存是否启用排序

如果此属性为`true`，则为树启用排序；如果该属性为 false，则不启用排序。默认值为 false。

**注意：**为了避免性能问题，建议将项目插入树*后启用排序。*或者，您也可以先将项目插入列表，然后再将项目插入树中。

**访问功能：**

| bool | **isSortingEnabled**() const         |
| ---- | ------------------------------------ |
| void | **setSortingEnabled**(bool *enable*) |

**也可以看看**[sortByColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortByColumn)()。

### uniformRowHeights : bool

该属性保存树视图中的所有项目是否具有相同的高度

仅当保证视图中的所有项目具有相同高度时，才应将此属性设置为 true。这使得视图能够进行一些优化。

高度是从视图中的第一个项目获取的。当该项目的数据发生变化时，它就会更新。

**注意：**如果编辑器大小提示大于单元格大小提示，则将使用编辑器的大小提示。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **uniformRowHeights**() const            |
| ---- | ---------------------------------------- |
| void | **setUniformRowHeights**(bool *uniform*) |

### wordWrap : bool

该属性保存项目文本自动换行策略

如果此属性为`true`，则项目文本将在必要的断字处换行；否则它根本没有被包裹。该属性是`false`默认的。

请注意，即使启用换行，单元格也不会扩展以适合所有文本。省略号将根据当前插入[textElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)。

**访问功能：**

| bool | **wordWrap**() const       |
| ---- | -------------------------- |
| void | **setWordWrap**(bool *on*) |

## 成员函数文档

### `[explicit]`QTreeView::QTreeView([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个树视图*parent*来表示模型的数据。使用[setModel](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)() 设置模型。

**也可以看看**[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[virtual]`QTreeView::~QTreeView()

破坏树视图。

### `[override virtual protected]`void QTreeView::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QFrame::changeEvent](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *ev）。

### `[slot]`void QTreeView::collapse(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

折叠由指定的模型项*index*。

**也可以看看**[collapsed](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapsed)()。

### `[slot]`void QTreeView::collapseAll()

折叠所有展开的项目。

**也可以看看**[expandAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandAll)(),[expand](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expand)(),[collapse](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapse)（）， 和[setExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExpanded)()。

### `[signal]`void QTreeView::collapsed(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当由指定的项目时，发出此信号*index*已经崩溃了。

### int QTreeView::columnAt(int *x*) const

返回树视图中标题覆盖的列*x*给定坐标。

### `[protected slot]`void QTreeView::columnCountChanged(int *oldCount*, int *newCount*)

通知树视图树视图中的列数已更改*oldCount*到*newCount*。

### `[protected slot]`void QTreeView::columnMoved()

每当移动列时就会调用此槽。

### `[protected slot]`void QTreeView::columnResized(int *column*, int *oldSize*, int *newSize*)

每当*column*标题中的大小已更改。*oldSize*和*newSize*给出以前的尺寸和新的尺寸（以像素为单位）。

**也可以看看**[setColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidth)()。

### int QTreeView::columnViewportPosition(int *column*) const

返回水平位置*column*在视口中。

### int QTreeView::columnWidth(int *column*) const

返回宽度*column*。

**也可以看看**[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)（） 和[setColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidth)()。

### `[override virtual protected]`void QTreeView::currentChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*current*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*previous*)

重新实现：[QAbstractItemView::currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)（常量 QModelIndex 和当前，常量 QModelIndex 和上一个）。

### `[override virtual]`void QTreeView::dataChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*topLeft*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*bottomRight*, const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<int> &*roles* = QList<int>())

重新实现：[QAbstractItemView::dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)（const QModelIndex &topLeft、const QModelIndex &bottomRight、const QList<int> &roles）。

### `[override virtual protected]`void QTreeView::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[virtual protected]`void QTreeView::drawBranches([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

在树视图中与模型项在同一行上绘制分支*index*， 使用*painter*给予。分支绘制在由 指定的矩形中*rect*。

### `[virtual protected]`void QTreeView::drawRow([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

在树视图中绘制包含模型项的行*index*， 使用*painter*给予。这*option*控制项目的显示方式。

**也可以看看**[setAlternatingRowColors](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alternatingRowColors-prop)()。

### `[protected]`void QTreeView::drawTree([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*region*) const

绘制与给定树相交的部分*region*使用指定的*painter*。

**也可以看看**[paintEvent](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)()。

### `[slot]`void QTreeView::expand(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

扩展由指定的模型项*index*。

**也可以看看**[expanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expanded)()。

### `[slot]`void QTreeView::expandAll()

展开所有可展开的项目。

**注意：**该函数不会尝试[fetch more](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)数据。

**警告：**如果模型包含大量项目，此函数将需要一些时间来执行。

**也可以看看**[collapseAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapseAll)(),[expand](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expand)(),[collapse](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapse)（）， 和[setExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExpanded)()。

### `[slot]`void QTreeView::expandRecursively(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, int *depth* = -1)

在给定的位置展开项目*index*及其所有子项给定的*depth*。这*depth*是相对于给定的*index*。A*depth*-1 的值将展开所有子项，*depth*0 只会扩展给定的*index*。

**注意：**该函数不会尝试[fetch more](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)数据。

**警告：**如果模型包含大量项目，此函数将需要一些时间来执行。

**也可以看看**[expandAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandAll)()。

### `[slot]`void QTreeView::expandToDepth(int *depth*)

将所有可扩展项目扩展到给定的*depth*。

**注意：**该函数不会尝试[fetch more](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fetchMore)数据。

**也可以看看**[expandAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandAll)(),[collapseAll](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapseAll)(),[expand](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expand)(),[collapse](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collapse)（）， 和[setExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExpanded)()。

### `[signal]`void QTreeView::expanded(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当由指定的项目时，发出此信号*index*被扩展。

**也可以看看**[setExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExpanded)()。

### [QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTreeView::header() const

返回树视图的标题。

**也可以看看**[setHeader](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeader)（） 和[QAbstractItemModel::headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)()。

### `[slot]`void QTreeView::hideColumn(int *column*)

隐藏*column*给予。

**注意：**此函数只能在模型初始化后调用，因为视图需要知道列数才能隐藏*column*。

**也可以看看**[showColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showColumn)（） 和[setColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnHidden)()。

### `[override virtual protected]`int QTreeView::horizontalOffset() const

重新实现：[QAbstractItemView::horizontalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)。

返回树视图中项目的水平偏移量。

请注意，树视图使用水平标题部分位置来确定视图中列的位置。

**也可以看看**[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)()。

### [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::indexAbove(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回上面项目的型号索引*index*。

### `[override virtual]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::indexAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

重新实现：[QAbstractItemView::indexAt(const QPoint &point) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)。

### [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::indexBelow(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回下面项目的型号索引*index*。

### `[protected]`int QTreeView::indexRowSizeHint(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回由 指示的行的大小提示*index*。

**也可以看看**[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)（） 和[uniformRowHeights](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformRowHeights-prop)()。

### bool QTreeView::isColumnHidden(int *column*) const

返回`true`如果*column*被隐藏；否则返回`false`.

**也可以看看**[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)（） 和[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)()。

### bool QTreeView::isExpanded(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回`true`模型项是否*index*已扩大；否则返回 false。

**也可以看看**[expand](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expand)(),[expanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expanded)（）， 和[setExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExpanded)()。

### bool QTreeView::isFirstColumnSpanned(int *row*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*) const

返回`true`给定第一列中的项目是否为*row*的*parent*跨越所有列；否则返回`false`.

**也可以看看**[setFirstColumnSpanned](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFirstColumnSpanned)()。

### `[override virtual protected]`bool QTreeView::isIndexHidden(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::isIndexHidden(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)。

### bool QTreeView::isRowHidden(int *row*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*) const

`true`如果该项目在给定的范围内，则返回*row*的*parent*被隐藏；否则返回`false`.

**也可以看看**[setRowHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHidden)（） 和[isColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isColumnHidden)()。

### `[override virtual protected]`void QTreeView::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

### `[override virtual]`void QTreeView::keyboardSearch(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*search*)

重新实现：[QAbstractItemView::keyboardSearch](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardSearch)（常量 QString &search）。

### `[override virtual protected]`void QTreeView::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QTreeView::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QTreeView::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QTreeView::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（QMouseEvent *事件）。

### `[override virtual protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::moveCursor([QAbstractItemView::CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum) *cursorAction*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*)

重新实现：[QAbstractItemView::moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)（QAbstractItemView::CursorAction 光标操作、Qt::KeyboardModifiers 修饰符）。

按照以下描述的方式移动光标*cursorAction*，使用按钮提供的信息*modifiers*。

### `[override virtual protected]`void QTreeView::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[override virtual]`void QTreeView::reset()

重新实现：[QAbstractItemView::reset](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)()。

### `[slot]`void QTreeView::resizeColumnToContents(int *column*)

调整大小*column*给定其内容的大小。

**也可以看看**[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)(),[setColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidth)(),[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[protected]`int QTreeView::rowHeight(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回给定指示的行的高度*index*。

**也可以看看**[indexRowSizeHint](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexRowSizeHint)()。

### `[override virtual protected]`void QTreeView::rowsAboutToBeRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

重新实现：[QAbstractItemView::rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)(const QModelIndex &parent, int start, int end)。

通知视图来自*start*行到*end*包含的行即将从给定中删除*parent*模型项目。

### `[override virtual protected]`void QTreeView::rowsInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

重新实现：[QAbstractItemView::rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)(const QModelIndex &parent, int start, int end)。

通知视图来自*start*行到*end*行（包含）已插入到*parent*模型项目。

### `[protected slot]`void QTreeView::rowsRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

通知视图来自*start*行到*end*包含的行已从给定中删除*parent*模型项目。

### `[override virtual protected]`void QTreeView::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

将树视图的内容滚动 (*dx*,*dy*）。

### `[override virtual]`void QTreeView::scrollTo(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

重新实现：[QAbstractItemView::scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)（const QModelIndex &index，QAbstractItemView::ScrollHint 提示）。

滚动树视图的内容，直到给定的模型项*index*是可见的。这*hint*参数更精确地指定操作后项目应位于的位置。如果模型项的任何父项折叠，它们将展开以确保模型项可见。

### `[override virtual]`void QTreeView::selectAll()

重新实现：[QAbstractItemView::selectAll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()。

### `[override virtual protected]`[QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) QTreeView::selectedIndexes() const

重新实现：[QAbstractItemView::selectedIndexes() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)。

### `[override virtual protected]`void QTreeView::selectionChanged(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selected*, const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deselected*)

重新实现：[QAbstractItemView::selectionChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)（常量 QItemSelection 和已选择，常量 QItemSelection 和取消选择）。

### void QTreeView::setColumnHidden(int *column*, bool *hide*)

如果*hide*是真的*column*被隐藏，否则*column*显示。

**也可以看看**[isColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isColumnHidden)(),[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)（）， 和[setRowHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHidden)()。

### void QTreeView::setColumnWidth(int *column*, int *width*)

设置给定的宽度*column*到*width*指定的。

**也可以看看**[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)（） 和[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)()。

### void QTreeView::setExpanded(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, bool *expanded*)

设置引用的项目*index*折叠或展开，具体取决于*expanded*。

**也可以看看**[expanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expanded)(),[expand](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expand)（）， 和[isExpanded](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExpanded)()。

### void QTreeView::setFirstColumnSpanned(int *row*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, bool *span*)

如果*span*中第一列中的项目为 true*row*与给定的*parent*设置为跨越所有列，否则上的所有项目*row*显示。

**也可以看看**[isFirstColumnSpanned](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFirstColumnSpanned)()。

### void QTreeView::setHeader([QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **header*)

将树视图的标题设置为给定的*header*。

视图拥有给定的所有权*header*并在设置新标头时删除它。

**也可以看看**[QAbstractItemModel::headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)()。

### `[override virtual]`void QTreeView::setModel([QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **model*)

重新实现：[QAbstractItemView::setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)（QAbstractItemModel *模型）。

### `[override virtual]`void QTreeView::setRootIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

重新实现：[QAbstractItemView::setRootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)（常量 QModelIndex &index）。

### void QTreeView::setRowHidden(int *row*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, bool *hide*)

如果*hide*是真的*row*与给定的*parent*被隐藏，否则*row*显示。

**也可以看看**[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)（） 和[setColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnHidden)()。

### `[override virtual protected]`void QTreeView::setSelection(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

重新实现：[QAbstractItemView::setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（const QRect &rect，QItemSelectionModel::SelectionFlags 标志）。

应用选择*command*到矩形内或被矩形接触的项目，*rect*。

**也可以看看**[selectionCommand](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionCommand)()。

### `[override virtual]`void QTreeView::setSelectionModel([QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **selectionModel*)

重新实现：[QAbstractItemView::setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)(QItemSelectionModel *selectionModel)。

### void QTreeView::setTreePosition(int *index*)

这指定树结构应放置在逻辑索引处*index*。如果设置为 -1，则树将始终遵循视觉索引 0。

**也可以看看**[treePosition](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#treePosition)(),[QHeaderView::swapSections](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swapSections)（）， 和[QHeaderView::moveSection](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveSection)()。

### `[slot]`void QTreeView::showColumn(int *column*)

显示给定的*column*在树视图中。

**也可以看看**[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)（） 和[setColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnHidden)()。

### `[override virtual protected]`int QTreeView::sizeHintForColumn(int *column*) const

重新实现：[QAbstractItemView::sizeHintForColumn(int column) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)。

返回尺寸提示*column*的宽度，如果没有模型，则为 -1。

如果需要将给定列的宽度设置为固定值，请调用[QHeaderView::resizeSection](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeSection)() 在视图的标题上。

如果您在子类中重新实现此函数，请注意您返回的值仅在以下情况下使用：[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)（） 叫做。在这种情况下，如果视图的标题或项目委托需要更大的列宽，则将使用该宽度。

**也可以看看**[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop),[header](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#header)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[slot]`void QTreeView::sortByColumn(int *column*, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order*)

按给定值对模型进行排序*column*和*order*。

*column*可能是 -1，在这种情况下，不会显示排序指示符，并且模型将返回到其自然的、未排序的顺序。请注意，并非所有型号都支持此功能，在这种情况下甚至可能会崩溃。

**也可以看看**[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)。

### `[override virtual protected]`void QTreeView::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::timerEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。

### int QTreeView::treePosition() const

返回设置树的逻辑索引。如果返回值为 -1，则树将放置在视觉索引 0 上。

**也可以看看**[setTreePosition](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTreePosition)()。

### `[override virtual protected]`void QTreeView::updateGeometries()

重新实现：[QAbstractItemView::updateGeometries](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)()。

### `[override virtual protected]`int QTreeView::verticalOffset() const

重新实现：[QAbstractItemView::verticalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)。

返回树视图中项目的垂直偏移量。

**也可以看看**[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)()。

### `[override virtual protected]`bool QTreeView::viewportEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::viewportEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)（QEvent *事件）。

### `[override virtual protected]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::viewportSizeHint() const

重新实现：[QAbstractItemView::viewportSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)。

### `[override virtual]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::visualRect(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::visualRect(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)。

返回视口中项目占据的矩形*index*。如果索引不可见或显式隐藏，则返回的矩形无效。

### `[override virtual protected]`[QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTreeView::visualRegionForSelection(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selection*) const

重新实现：[QAbstractItemView::visualRegionForSelection(const QItemSelection &selection) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)。

从给定项目的视口返回矩形*selection*。

从 4.7 开始，返回的区域仅包含与视口相交（或包含在视口中）的矩形。