#  QTableView Class

QTableView 类提供表视图的默认模型/视图实现。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QTableView>                                       |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtableview-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

| **[cornerButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cornerButtonEnabled-prop)** : bool**[gridStyle](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridStyle-prop)** : Qt::PenStyle**[showGrid](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGrid-prop)** : bool | **[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)** : bool**[wordWrap](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)** : bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|               | **[QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTableView)**(QWidget **parent* = nullptr) |
| ------------- | ------------------------------------------------------------ |
| virtual       | **[~QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTableView)**() |
| void          | **[clearSpans](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSpans)**() |
| int           | **[columnAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnAt)**(int *x*) const |
| int           | **[columnSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnSpan)**(int *row*, int *column*) const |
| int           | **[columnViewportPosition](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnViewportPosition)**(int *column*) const |
| int           | **[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)**(int *column*) const |
| Qt::PenStyle  | **[gridStyle](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridStyle-prop)**() const |
| QHeaderView * | **[horizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeader)**() const |
| bool          | **[isColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isColumnHidden)**(int *column*) const |
| bool          | **[isCornerButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cornerButtonEnabled-prop)**() const |
| bool          | **[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)**(int *row*) const |
| bool          | **[isSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)**() const |
| int           | **[rowAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowAt)**(int *y*) const |
| int           | **[rowHeight](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowHeight)**(int *row*) const |
| int           | **[rowSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowSpan)**(int *row*, int *column*) const |
| int           | **[rowViewportPosition](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowViewportPosition)**(int *row*) const |
| void          | **[setColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnHidden)**(int *column*, bool *hide*) |
| void          | **[setColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidth)**(int *column*, int *width*) |
| void          | **[setCornerButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cornerButtonEnabled-prop)**(bool *enable*) |
| void          | **[setGridStyle](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridStyle-prop)**(Qt::PenStyle *style*) |
| void          | **[setHorizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeader)**(QHeaderView **header*) |
| void          | **[setRowHeight](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHeight)**(int *row*, int *height*) |
| void          | **[setRowHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHidden)**(int *row*, bool *hide*) |
| void          | **[setSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSortingEnabled)**(bool *enable*) |
| void          | **[setSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpan)**(int *row*, int *column*, int *rowSpanCount*, int *columnSpanCount*) |
| void          | **[setVerticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeader)**(QHeaderView **header*) |
| void          | **[setWordWrap](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)**(bool *on*) |
| bool          | **[showGrid](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGrid-prop)**() const |
| QHeaderView * | **[verticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeader)**() const |
| bool          | **[wordWrap](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)**() const |

## 重新实施公共职能

| virtual QModelIndex | **[indexAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)**(const QPoint &*pos*) const override |
| ------------------- | ------------------------------------------------------------ |
| virtual void        | **[scrollTo](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)**(const QModelIndex &*index*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) override |
| virtual void        | **[setModel](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)**(QAbstractItemModel **model*) override |
| virtual void        | **[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)**(const QModelIndex &*index*) override |
| virtual void        | **[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)**(QItemSelectionModel **selectionModel*) override |
| virtual QRect       | **[visualRect](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)**(const QModelIndex &*index*) const override |

## 公共槽

| void | **[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)**(int *column*) |
| ---- | ------------------------------------------------------------ |
| void | **[hideRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideRow)**(int *row*) |
| void | **[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)**(int *column*) |
| void | **[resizeColumnsToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnsToContents)**() |
| void | **[resizeRowToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowToContents)**(int *row*) |
| void | **[resizeRowsToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowsToContents)**() |
| void | **[selectColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectColumn)**(int *column*) |
| void | **[selectRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectRow)**(int *row*) |
| void | **[setShowGrid](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGrid-prop)**(bool *show*) |
| void | **[showColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showColumn)**(int *column*) |
| void | **[showRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showRow)**(int *row*) |
| void | **[sortByColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortByColumn)**(int *column*, Qt::SortOrder *order*) |

## 重载的protected function

| virtual void            | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(const QModelIndex &*current*, const QModelIndex &*previous*) override |
| ----------------------- | ------------------------------------------------------------ |
| virtual int             | **[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)**() const override |
| virtual void            | **[initViewItemOption](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initViewItemOption)**(QStyleOptionViewItem **option*) const override |
| virtual bool            | **[isIndexHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)**(const QModelIndex &*index*) const override |
| virtual QModelIndex     | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QAbstractItemView::CursorAction *cursorAction*, Qt::KeyboardModifiers *modifiers*) override |
| virtual void            | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void            | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual QModelIndexList | **[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)**() const override |
| virtual void            | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**(const QItemSelection &*selected*, const QItemSelection &*deselected*) override |
| virtual void            | **[setSelection](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)**(const QRect &*rect*, QItemSelectionModel::SelectionFlags *flags*) override |
| virtual int             | **[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)**(int *column*) const override |
| virtual int             | **[sizeHintForRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)**(int *row*) const override |
| virtual void            | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **event*) override |
| virtual void            | **[updateGeometries](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)**() override |
| virtual int             | **[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)**() const override |
| virtual QSize           | **[viewportSizeHint](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)**() const override |
| virtual QRegion         | **[visualRegionForSelection](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)**(const QItemSelection &*selection*) const override |

## 继承的槽

| void | **[columnCountChanged](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCountChanged)**(int *oldCount*, int *newCount*) |
| ---- | ------------------------------------------------------------ |
| void | **[columnMoved](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnMoved)**(int *column*, int *oldIndex*, int *newIndex*) |
| void | **[columnResized](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnResized)**(int *column*, int *oldWidth*, int *newWidth*) |
| void | **[rowCountChanged](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCountChanged)**(int *oldCount*, int *newCount*) |
| void | **[rowMoved](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowMoved)**(int *row*, int *oldIndex*, int *newIndex*) |
| void | **[rowResized](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowResized)**(int *row*, int *oldHeight*, int *newHeight*) |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\T\QTableView\QTableView\windows-tableview.png)

QTableView 实现了一个显示模型中项目的表视图。该类用于提供以前由 QTable 类提供的标准表，但使用 Qt 模型/视图架构提供的更灵活的方法。

QTableView 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QTableView 实现了定义的接口[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，允许它显示由派生的模型提供的数据[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级。

### 导航

您可以通过用鼠标单击单元格或使用箭头键来导航表中的单元格。因为 QTableView 启用[tabKeyNavigation](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabKeyNavigation-prop)默认情况下，您还可以点击 Tab 和 Backtab 在单元格之间移动。

### 视觉外观

该表有一个垂直标题，可以使用以下命令获得[verticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeader)() 函数，以及可通过以下方式获得的水平标题[horizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeader)（） 功能。表中每行的高度可以通过使用找到[rowHeight](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowHeight)(); 类似地，可以使用以下方法找到列的宽度[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)()。由于这两个都是普通的小部件，因此您可以使用它们来隐藏它们中的任何一个[hide](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)（） 功能。每个标头都配置有其[highlightSections](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#highlightSections-prop)和[sectionsClickable](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sectionsClickable)属性设置为`true`.

行和列可以隐藏和显示[hideRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideRow)(),[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)(),[showRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showRow)（）， 和[showColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showColumn)()。可以选择它们[selectRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectRow)（） 和[selectColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectColumn)()。该表将显示一个网格，具体取决于[showGrid](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGrid-prop)财产。

表视图中显示的项目与其他项目视图中的项目一样，都是使用标准进行渲染和编辑的[delegates](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。但是，对于某些任务，有时能够在表中插入小部件会很有用。小部件是为特定索引设置的[setIndexWidget](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIndexWidget)() 函数，稍后用[indexWidget](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexWidget)()。

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\T\QTableView\QTableView\qtableview-resized.png) | 默认情况下，表中的单元格不会扩展以填充可用空间。您可以通过拉伸最后一个标题部分来使单元格填充可用空间。使用访问相关标头[horizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeader)（） 或者[verticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeader)() 并设置标题[stretchLastSection](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stretchLastSection-prop)财产。要根据每列或行的空间需求分配可用空间，请调用视图的[resizeColumnsToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnsToContents)（） 或者[resizeRowsToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowsToContents)（） 功能。 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

### 坐标系

对于某些特殊形式的表格，能够在行索引和列索引以及小部件坐标之间进行转换非常有用。这[rowAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowAt)() 函数提供指定行的视图内的 y 坐标；行索引可用于获取相应的 y 坐标[rowViewportPosition](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowViewportPosition)()。这[columnAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnAt)（） 和[columnViewportPosition](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnViewportPosition)() 函数提供 x 坐标和列索引之间的等效转换操作。

**也可以看看**[QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#view-classes),[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Chart Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-chart-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Pixelator Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-pixelator-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Table Model Example](https://doc-qt-io.translate.goog/qt-6/qtsql-tablemodel-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 财产文件

### cornerButtonEnabled : bool

该属性保存左上角的按钮是否启用

如果此属性为`true`，则启用表视图左上角的按钮。单击此按钮将选择表视图中的所有单元格。

该属性是`true`默认的。

**访问功能：**

| bool | **isCornerButtonEnabled**() const         |
| ---- | ----------------------------------------- |
| void | **setCornerButtonEnabled**(bool *enable*) |

### gridStyle : [Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)

该属性保存用于绘制网格的笔样式。

该属性保存绘制网格时使用的样式（请参见[showGrid](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGrid-prop)）。

**访问功能：**

| Qt::PenStyle | **gridStyle**() const                  |
| ------------ | -------------------------------------- |
| void         | **setGridStyle**(Qt::PenStyle *style*) |

### showGrid : bool

该属性保存是否显示网格

如果该属性是`true`为表格绘制网格；如果属性为`false`，则不绘制网格。默认值是true。

**访问功能：**

| bool | **showGrid**() const         |
| ---- | ---------------------------- |
| void | **setShowGrid**(bool *show*) |

### sortingEnabled : bool

该属性保存是否启用排序

如果此属性为`true`，则为表启用排序。如果此属性为`false`，则不启用排序。默认值为 false。

**注：** . 将属性设置为 true[setSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSortingEnabled)() 立即触发调用[sortByColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortByColumn)() 与当前排序部分和顺序。

**访问功能：**

| bool | **isSortingEnabled**() const                                 |
| ---- | ------------------------------------------------------------ |
| void | **[setSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSortingEnabled)**(bool *enable*) |

**也可以看看**[sortByColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortByColumn)()。

### wordWrap : bool

该属性保存项目文本自动换行策略

如果此属性为`true`，则项目文本将在必要的断字处换行；否则它根本没有被包裹。该属性是`true`默认的。

请注意，即使启用了换行，单元格也不会扩展以适合所有文本。省略号将根据当前插入[textElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)。

**访问功能：**

| bool | **wordWrap**() const       |
| ---- | -------------------------- |
| void | **setWordWrap**(bool *on*) |

## 成员函数文档

### `[explicit]`QTableView::QTableView([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个表视图*parent*来表示数据。

**也可以看看**[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[virtual]`QTableView::~QTableView()

破坏表视图。

### void QTableView::clearSpans()

删除表视图中的所有行和列跨度。

**也可以看看**[setSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpan)()。

### int QTableView::columnAt(int *x*) const

返回给定 x 坐标所在的列，*x*，在内容坐标中位于。

**注意：**如果给定坐标无效（没有列），则该函数返回 -1。

**也可以看看**[rowAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowAt)()。

### `[protected slot]`void QTableView::columnCountChanged(int *oldCount*, int *newCount*)

每当添加或删除列时都会调用此槽。先前的列数由以下方式指定*oldCount*，新的列数由下式指定*newCount*。

### `[protected slot]`void QTableView::columnMoved(int *column*, int *oldIndex*, int *newIndex*)

调用此槽来更改给定的索引*column*在表视图中。旧索引由以下方式指定*oldIndex*，新索引为*newIndex*。

**也可以看看**[rowMoved](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowMoved)()。

### `[protected slot]`void QTableView::columnResized(int *column*, int *oldWidth*, int *newWidth*)

调用此槽来更改给定的宽度*column*。旧宽度指定为*oldWidth*，新宽度为*newWidth*。

**也可以看看**[rowResized](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowResized)()。

### int QTableView::columnSpan(int *row*, int *column*) const

返回 ( 处的表元素的列跨度*row*,*column*）。默认值为 1。

**也可以看看**[setSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpan)（） 和[rowSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowSpan)()。

### int QTableView::columnViewportPosition(int *column*) const

返回给定内容坐标中的 x 坐标*column*。

### int QTableView::columnWidth(int *column*) const

返回给定的宽度*column*。

**也可以看看**[setColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidth)(),[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)（）， 和[rowHeight](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowHeight)()。

### `[override virtual protected]`void QTableView::currentChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*current*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*previous*)

重新实现：[QAbstractItemView::currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)（常量 QModelIndex 和当前，常量 QModelIndex 和上一个）。

### `[slot]`void QTableView::hideColumn(int *column*)

隐藏给定的*column*。

**也可以看看**[showColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showColumn)（） 和[hideRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideRow)()。

### `[slot]`void QTableView::hideRow(int *row*)

隐藏给定的*row*。

**也可以看看**[showRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showRow)（） 和[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)()。

### [QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableView::horizontalHeader() const

返回表视图的水平标题。

**也可以看看**[setHorizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeader)(),[verticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeader)（）， 和[QAbstractItemModel::headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)()。

### `[override virtual protected]`int QTableView::horizontalOffset() const

重新实现：[QAbstractItemView::horizontalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)。

返回表视图中项目的水平偏移量。

请注意，表视图使用水平标题部分位置来确定视图中列的位置。

**也可以看看**[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)()。

### `[override virtual]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableView::indexAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

重新实现：[QAbstractItemView::indexAt(const QPoint &point) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)。

返回位于位置的表项对应的模型项的索引位置*pos*在内容坐标中。

### `[override virtual protected]`void QTableView::initViewItemOption([QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

重新实现：[QAbstractItemView::initViewItemOption(QStyleOptionViewItem *option) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initViewItemOption)。

### bool QTableView::isColumnHidden(int *column*) const

`true`如果给定则返回*column*被隐藏；否则返回`false`.

**也可以看看**[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)()。

### `[override virtual protected]`bool QTableView::isIndexHidden(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::isIndexHidden(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)。

### bool QTableView::isRowHidden(int *row*) const

`true`如果给定则返回*row*被隐藏；否则返回`false`.

**也可以看看**[isColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isColumnHidden)()。

### `[override virtual protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableView::moveCursor([QAbstractItemView::CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum) *cursorAction*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*)

重新实现：[QAbstractItemView::moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)（QAbstractItemView::CursorAction 光标操作、Qt::KeyboardModifiers 修饰符）。

按照给定的方向移动光标*cursorAction*，使用提供的信息*modifiers*。

**也可以看看**[QAbstractItemView::CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum)。

### `[override virtual protected]`void QTableView::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

在收到给定的绘制事件后绘制表格*event*。

### `[slot]`void QTableView::resizeColumnToContents(int *column*)

调整给定的大小*column*基于用于呈现列中每个项目的委托的大小提示。

**注意：**只有可见列的大小才会调整。重新实现[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)() 也可以调整隐藏列的大小。

**也可以看看**[resizeColumnsToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnsToContents)(),[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[slot]`void QTableView::resizeColumnsToContents()

根据用于呈现列中每个项目的委托的大小提示来调整所有列的大小。

**也可以看看**[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)(),[sizeHintForColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[slot]`void QTableView::resizeRowToContents(int *row*)

调整给定的大小*row*基于用于呈现行中每个项目的委托的大小提示。

**也可以看看**[resizeRowsToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowsToContents)(),[sizeHintForRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[slot]`void QTableView::resizeRowsToContents()

根据用于呈现行中每个项目的委托的大小提示来调整所有行的大小。

**也可以看看**[resizeRowToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowToContents)(),[sizeHintForRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### int QTableView::rowAt(int *y*) const

返回给定 y 坐标所在的行，*y*，在内容坐标中位于。

**注意：**如果给定坐标无效（没有行），则该函数返回 -1。

**也可以看看**[columnAt](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnAt)()。

### `[protected slot]`void QTableView::rowCountChanged(int *oldCount*, int *newCount*)

每当添加或删除行时都会调用此槽。先前的行数由以下方式指定*oldCount*，新的行数由下式指定*newCount*。

### int QTableView::rowHeight(int *row*) const

返回给定的高度*row*。

**也可以看看**[setRowHeight](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHeight)(),[resizeRowToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowToContents)（）， 和[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)()。

### `[protected slot]`void QTableView::rowMoved(int *row*, int *oldIndex*, int *newIndex*)

调用此槽来更改给定的索引*row*在表视图中。旧索引由以下方式指定*oldIndex*，新索引为*newIndex*。

**也可以看看**[columnMoved](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnMoved)()。

### `[protected slot]`void QTableView::rowResized(int *row*, int *oldHeight*, int *newHeight*)

调用此槽来更改给定的高度*row*。旧高度由下式指定*oldHeight*，新高度为*newHeight*。

**也可以看看**[columnResized](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnResized)()。

### int QTableView::rowSpan(int *row*, int *column*) const

返回 ( 处的表元素的行跨度*row*,*column*）。默认值为 1。

**也可以看看**[setSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpan)（） 和[columnSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnSpan)()。

### int QTableView::rowViewportPosition(int *row*) const

返回给定内容坐标中的 y 坐标*row*。

### `[override virtual protected]`void QTableView::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

将表视图的内容滚动 (*dx*,*dy*）。

### `[override virtual]`void QTableView::scrollTo(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

重新实现：[QAbstractItemView::scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)（const QModelIndex &index，QAbstractItemView::ScrollHint 提示）。

确保给定的*index*在表视图中可见，必要时可滚动。

### `[slot]`void QTableView::selectColumn(int *column*)

选择给定的*column*如果当前 SelectionMode 和 SelectionBehavior 允许选择列，则在表视图中。

**也可以看看**[selectRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectRow)()。

### `[slot]`void QTableView::selectRow(int *row*)

选择给定的*row*如果当前 SelectionMode 和 SelectionBehavior 允许选择行，则在表视图中。

**也可以看看**[selectColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectColumn)()。

### `[override virtual protected]`[QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) QTableView::selectedIndexes() const

重新实现：[QAbstractItemView::selectedIndexes() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)。

### `[override virtual protected]`void QTableView::selectionChanged(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selected*, const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deselected*)

重新实现：[QAbstractItemView::selectionChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)（常量 QItemSelection 和已选择，常量 QItemSelection 和取消选择）。

### void QTableView::setColumnHidden(int *column*, bool *hide*)

如果*hide*给定的为真*column*将被隐藏；否则将会显示。

**也可以看看**[isColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isColumnHidden)（） 和[setRowHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHidden)()。

### void QTableView::setColumnWidth(int *column*, int *width*)

设置给定的宽度*column*成为*width*。

**也可以看看**[columnWidth](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidth)()。

### void QTableView::setHorizontalHeader([QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **header*)

将用于水平标题的小部件设置为*header*。

**也可以看看**[horizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeader)（） 和[setVerticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeader)()。

### `[override virtual]`void QTableView::setModel([QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **model*)

重新实现：[QAbstractItemView::setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)（QAbstractItemModel *模型）。

### `[override virtual]`void QTableView::setRootIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

重新实现：[QAbstractItemView::setRootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)（常量 QModelIndex &index）。

### void QTableView::setRowHeight(int *row*, int *height*)

设置给定的高度*row*成为*height*。

**也可以看看**[rowHeight](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowHeight)()。

### void QTableView::setRowHidden(int *row*, bool *hide*)

如果*hide*是真的*row*将被隐藏，否则将显示。

**也可以看看**[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)（） 和[setColumnHidden](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnHidden)()。

### `[override virtual protected]`void QTableView::setSelection(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *flags*)

重新实现：[QAbstractItemView::setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（const QRect &rect，QItemSelectionModel::SelectionFlags 标志）。

选择给定范围内的项目*rect*并按照指定的选择*flags*。

### `[override virtual]`void QTableView::setSelectionModel([QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **selectionModel*)

重新实现：[QAbstractItemView::setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)(QItemSelectionModel *selectionModel)。

### void QTableView::setSortingEnabled(bool *enable*)

如果*enable*为 true，启用表排序并立即触发调用[sortByColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortByColumn)() 与当前排序部分和顺序

**注意：**属性的 Setter 函数[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)。

**也可以看看**[isSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)()。

### void QTableView::setSpan(int *row*, int *column*, int *rowSpanCount*, int *columnSpanCount*)

将表格元素的跨度设置为 (*row*,*column*) 到 ( 指定的行数和列数*rowSpanCount*,*columnSpanCount*）。

**也可以看看**[rowSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowSpan)（） 和[columnSpan](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnSpan)()。

### void QTableView::setVerticalHeader([QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **header*)

将用于垂直标题的小部件设置为*header*。

**也可以看看**[verticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeader)（） 和[setHorizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeader)()。

### `[slot]`void QTableView::showColumn(int *column*)

显示给定的*column*。

**也可以看看**[hideColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideColumn)（） 和[showRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showRow)()。

### `[slot]`void QTableView::showRow(int *row*)

显示给定的*row*。

**也可以看看**[hideRow](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideRow)（） 和[showColumn](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showColumn)()。

### `[override virtual protected]`int QTableView::sizeHintForColumn(int *column*) const

重新实现：[QAbstractItemView::sizeHintForColumn(int column) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForColumn)。

返回给定的大小提示*column*的宽度，如果没有模型，则为 -1。

如果需要将给定列的宽度设置为固定值，请调用[QHeaderView::resizeSection](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeSection)() 在表格的水平标题上。

如果您在子类中重新实现此函数，请注意，您返回的值将在以下情况下使用：[resizeColumnToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeColumnToContents)（） 或者[QHeaderView::resizeSections](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeSections-1)（） 叫做。如果水平标题或项目委托需要更大的列宽，则将使用更大的宽度。

**也可以看看**[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop),[horizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeader)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[override virtual protected]`int QTableView::sizeHintForRow(int *row*) const

重新实现：[QAbstractItemView::sizeHintForRow(int row) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintForRow)。

返回给定的大小提示*row*的高度，如果没有模型，则为 -1。

如果需要将给定行的高度设置为固定值，请调用[QHeaderView::resizeSection](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeSection)() 位于表格的垂直标题上。

如果您在子类中重新实现此函数，请注意您返回的值仅在以下情况下使用：[resizeRowToContents](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeRowToContents)（） 叫做。在这种情况下，如果垂直标题或项目委托需要更大的行高，则将使用该宽度。

**也可以看看**[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop),[verticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeader)（）， 和[QHeaderView::resizeContentsPrecision](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeContentsPrecision)()。

### `[slot]`void QTableView::sortByColumn(int *column*, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order*)

按给定值对模型进行排序*column*和*order*。

*column*可能是 -1，在这种情况下，不会显示排序指示符，并且模型将返回到其自然的、未排序的顺序。请注意，并非所有型号都支持此功能，在这种情况下甚至可能会崩溃。

**也可以看看**[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)。

### `[override virtual protected]`void QTableView::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::timerEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。

### `[override virtual protected]`void QTableView::updateGeometries()

重新实现：[QAbstractItemView::updateGeometries](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)()。

### [QHeaderView](https://doc-qt-io.translate.goog/qt-6/qheaderview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableView::verticalHeader() const

返回表视图的垂直标题。

**也可以看看**[setVerticalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeader)(),[horizontalHeader](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeader)（）， 和[QAbstractItemModel::headerData](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerData)()。

### `[override virtual protected]`int QTableView::verticalOffset() const

重新实现：[QAbstractItemView::verticalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)。

返回表视图中项目的垂直偏移量。

请注意，表视图使用垂直标题部分位置来确定视图中行的位置。

**也可以看看**[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)()。

### `[override virtual protected]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableView::viewportSizeHint() const

重新实现：[QAbstractItemView::viewportSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)。

### `[override virtual]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableView::visualRect(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::visualRect(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)。

返回给定的视口上占据的矩形*index*。如果索引隐藏在视图中，它将返回 null[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[override virtual protected]`[QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableView::visualRegionForSelection(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selection*) const

重新实现：[QAbstractItemView::visualRegionForSelection(const QItemSelection &selection) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)。

从给定项目的视口返回矩形*selection*。

从 4.7 开始，返回的区域仅包含与视口相交（或包含在视口中）的矩形。