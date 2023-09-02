#  QTableWidget Class

QTableWidget 类提供带有默认模型的基于项目的表视图。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QTableWidget>                                     |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtablewidget-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount-prop)** : int
- **[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount-prop)** : int

## 公共职能

|                                   | **[QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTableWidget)**(QWidget **parent* = nullptr) |
| --------------------------------- | ------------------------------------------------------------ |
|                                   | **[QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTableWidget-1)**(int *rows*, int *columns*, QWidget **parent* = nullptr) |
| virtual                           | **[~QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTableWidget)**() |
| QWidget *                         | **[cellWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellWidget)**(int *row*, int *column*) const |
| void                              | **[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)**(QTableWidgetItem **item*) |
| int                               | **[column](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#column)**(const QTableWidgetItem **item*) const |
| int                               | **[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)**() const |
| int                               | **[currentColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColumn)**() const |
| QTableWidgetItem *                | **[currentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItem)**() const |
| int                               | **[currentRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow)**() const |
| void                              | **[editItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editItem)**(QTableWidgetItem **item*) |
| QList<QTableWidgetItem *>         | **[findItems](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findItems)**(const QString &*text*, Qt::MatchFlags *flags*) const |
| QTableWidgetItem *                | **[horizontalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderItem)**(int *column*) const |
| QModelIndex                       | **[indexFromItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexFromItem)**(const QTableWidgetItem **item*) const |
| bool                              | **[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)**(QTableWidgetItem **item*) const |
| QTableWidgetItem *                | **[item](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item)**(int *row*, int *column*) const |
| QTableWidgetItem *                | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)**(const QPoint &*point*) const |
| QTableWidgetItem *                | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt-1)**(int *ax*, int *ay*) const |
| QTableWidgetItem *                | **[itemFromIndex](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemFromIndex)**(const QModelIndex &*index*) const |
| const QTableWidgetItem *          | **[itemPrototype](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemPrototype)**() const |
| QList<QTableWidgetItem *>         | **[items](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)**(const QMimeData **data*) const |
| void                              | **[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)**(QTableWidgetItem **item*) |
| void                              | **[removeCellWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeCellWidget)**(int *row*, int *column*) |
| int                               | **[row](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#row)**(const QTableWidgetItem **item*) const |
| int                               | **[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)**() const |
| QList<QTableWidgetItem *>         | **[selectedItems](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)**() const |
| QList<QTableWidgetSelectionRange> | **[selectedRanges](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedRanges)**() const |
| void                              | **[setCellWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCellWidget)**(int *row*, int *column*, QWidget **widget*) |
| void                              | **[setColumnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnCount)**(int *columns*) |
| void                              | **[setCurrentCell](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCell)**(int *row*, int *column*) |
| void                              | **[setCurrentCell](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCell-1)**(int *row*, int *column*, QItemSelectionModel::SelectionFlags *command*) |
| void                              | **[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)**(QTableWidgetItem **item*) |
| void                              | **[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem-1)**(QTableWidgetItem **item*, QItemSelectionModel::SelectionFlags *command*) |
| void                              | **[setHorizontalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeaderItem)**(int *column*, QTableWidgetItem **item*) |
| void                              | **[setHorizontalHeaderLabels](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeaderLabels)**(const QStringList &*labels*) |
| void                              | **[setItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItem)**(int *row*, int *column*, QTableWidgetItem **item*) |
| void                              | **[setItemPrototype](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemPrototype)**(const QTableWidgetItem **item*) |
| void                              | **[setRangeSelected](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRangeSelected)**(const QTableWidgetSelectionRange &*range*, bool *select*) |
| void                              | **[setRowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowCount)**(int *rows*) |
| void                              | **[setVerticalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeaderItem)**(int *row*, QTableWidgetItem **item*) |
| void                              | **[setVerticalHeaderLabels](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeaderLabels)**(const QStringList &*labels*) |
| void                              | **[sortItems](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortItems)**(int *column*, Qt::SortOrder *order* = Qt::AscendingOrder) |
| QTableWidgetItem *                | **[takeHorizontalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeHorizontalHeaderItem)**(int *column*) |
| QTableWidgetItem *                | **[takeItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeItem)**(int *row*, int *column*) |
| QTableWidgetItem *                | **[takeVerticalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeVerticalHeaderItem)**(int *row*) |
| QTableWidgetItem *                | **[verticalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderItem)**(int *row*) const |
| int                               | **[visualColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualColumn)**(int *logicalColumn*) const |
| QRect                             | **[visualItemRect](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualItemRect)**(const QTableWidgetItem **item*) const |
| int                               | **[visualRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRow)**(int *logicalRow*) const |

## 公共老虎机

| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| ---- | ------------------------------------------------------------ |
| void | **[clearContents](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearContents)**() |
| void | **[insertColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertColumn)**(int *column*) |
| void | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)**(int *row*) |
| void | **[removeColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeColumn)**(int *column*) |
| void | **[removeRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)**(int *row*) |
| void | **[scrollToItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToItem)**(const QTableWidgetItem **item*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) |

## 信号

| void | **[cellActivated](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellActivated)**(int *row*, int *column*) |
| ---- | ------------------------------------------------------------ |
| void | **[cellChanged](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellChanged)**(int *row*, int *column*) |
| void | **[cellClicked](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellClicked)**(int *row*, int *column*) |
| void | **[cellDoubleClicked](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellDoubleClicked)**(int *row*, int *column*) |
| void | **[cellEntered](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellEntered)**(int *row*, int *column*) |
| void | **[cellPressed](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellPressed)**(int *row*, int *column*) |
| void | **[currentCellChanged](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCellChanged)**(int *currentRow*, int *currentColumn*, int *previousRow*, int *previousColumn*) |
| void | **[currentItemChanged](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItemChanged)**(QTableWidgetItem **current*, QTableWidgetItem **previous*) |
| void | **[itemActivated](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemActivated)**(QTableWidgetItem **item*) |
| void | **[itemChanged](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChanged)**(QTableWidgetItem **item*) |
| void | **[itemClicked](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemClicked)**(QTableWidgetItem **item*) |
| void | **[itemDoubleClicked](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDoubleClicked)**(QTableWidgetItem **item*) |
| void | **[itemEntered](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemEntered)**(QTableWidgetItem **item*) |
| void | **[itemPressed](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemPressed)**(QTableWidgetItem **item*) |
| void | **[itemSelectionChanged](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemSelectionChanged)**() |

## 受保护的功能

| virtual bool            | **[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)**(int *row*, int *column*, const QMimeData **data*, Qt::DropAction *action*) |
| ----------------------- | ------------------------------------------------------------ |
| virtual QMimeData *     | **[mimeData](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)**(const QList<QTableWidgetItem *> &*items*) const |
| virtual QStringList     | **[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)**() const |
| virtual Qt::DropActions | **[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)**() const |

## 重新实现受保护的功能

| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |

## 详细说明

![img](https://doc.qt.io/qt-6/images/windows-tableview.png)

表格小部件为应用程序提供标准表格显示工具。QTableWidget 中的项目由以下提供：[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

如果您想要一个使用您自己的数据模型的表，您应该使用[QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)而不是这个类。

可以使用所需的行数和列数构建表格小部件：

```
    tableWidget = new QTableWidget(12, 3, this);
```

或者，可以在没有给定大小的情况下构建表并稍后调整大小：

```
    tableWidget = new QTableWidget(this);
    tableWidget->setRowCount(10);
    tableWidget->setColumnCount(5);
```

项目在表外部创建（没有父小部件）并插入到表中[setItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItem)():

```
    QTableWidgetItem *newItem = new QTableWidgetItem(tr("%1").arg(
        (row+1)*(column+1)));
    tableWidget->setItem(row, column, newItem);
```

如果您想在表格小部件中启用排序，请在填充项目后执行此操作，否则排序可能会干扰插入顺序（请参阅[setItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItem)() 详细信息）。

表格可以具有水平和垂直标题。创建标头的最简单方法是将字符串列表提供给[setHorizontalHeaderLabels](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeaderLabels)（） 和[setVerticalHeaderLabels](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeaderLabels)（） 功能。这些将为表的列和行提供简单的文本标题。可以从通常在表外部构建的现有表项创建更复杂的标题。例如，我们可以构造一个带有图标和对齐文本的表格项，并将其用作特定列的标题：

```
    QTableWidgetItem *cubesHeaderItem = new QTableWidgetItem(tr("Cubes"));
    cubesHeaderItem->setIcon(QIcon(QPixmap(":/Images/cubed.png")));
    cubesHeaderItem->setTextAlignment(Qt::AlignVCenter);
```

表中的行数可以通过以下方式找到[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 和列数[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)()。可以使用以下命令清除该表[clear](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)（） 功能。

**也可以看看**[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Model/View Programming](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 财产文件

### columnCount : int

该属性保存表中的列数

默认情况下，对于构建的没有行数和列数的表，此属性包含值 0。

**访问功能：**

| int  | **[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)**() const |
| ---- | ------------------------------------------------------------ |
| void | **[setColumnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnCount)**(int *columns*) |

### rowCount : int

该属性保存表中的行数

默认情况下，对于构建的没有行数和列数的表，此属性包含值 0。

**访问功能：**

| int  | **[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)**() const |
| ---- | ------------------------------------------------------------ |
| void | **[setRowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowCount)**(int *rows*) |

## 成员函数文档

### `[explicit]`QTableWidget::QTableWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值创建一个新的表视图*parent*。

### QTableWidget::QTableWidget(int *rows*, int *columns*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值创建一个新的表视图*rows*和*columns*，并且给定*parent*。

### `[virtual]`QTableWidget::~QTableWidget()

毁掉这个[QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[signal]`void QTableWidget::cellActivated(int *row*, int *column*)

当指定的单元格时，会发出此信号*row*和*column*已被激活

### `[signal]`void QTableWidget::cellChanged(int *row*, int *column*)

每当由指定的单元格中的项目数据时，就会发出此信号*row*和*column*已经改变。

### `[signal]`void QTableWidget::cellClicked(int *row*, int *column*)

每当单击表中的单元格时就会发出此信号。这*row*和*column*指定的是被单击的单元格。

### `[signal]`void QTableWidget::cellDoubleClicked(int *row*, int *column*)

每当双击表中的单元格时就会发出此信号。这*row*和*column*指定的是双击的单元格。

### `[signal]`void QTableWidget::cellEntered(int *row*, int *column*)

当鼠标光标进入单元格时会发出此信号。该单元格由以下方式指定*row*和*column*。

仅当打开 mouseTracking 或在移动到某个项目时按下鼠标按钮时，才会发出此信号。

### `[signal]`void QTableWidget::cellPressed(int *row*, int *column*)

每当按下表中的单元格时就会发出此信号。这*row*和*column*指定的是被按下的单元格。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QTableWidget::cellWidget(int *row*, int *column*) const

返回给定单元格中显示的小部件*row*和*column*。

**注意：**该表拥有该小部件的所有权。

**也可以看看**[setCellWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCellWidget)()。

### `[slot]`void QTableWidget::clear()

删除视图中的所有项目。这也将删除所有选择和标题。如果您不想删除标头，请使用[QTableWidget::clearContents](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearContents)()。桌子尺寸保持不变。

### `[slot]`void QTableWidget::clearContents()

从视图中删除标题中没有的所有项目。这也将删除所有选择。桌子尺寸保持不变。

### void QTableWidget::closePersistentEditor([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

关闭持久编辑器*item*。

**也可以看看**[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)（） 和[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)()。

### int QTableWidget::column(const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回列*item*。

### int QTableWidget::columnCount() const

返回列数。

**注意：**属性columnCount 的Getter 函数。

**也可以看看**[setColumnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnCount)()。

### `[signal]`void QTableWidget::currentCellChanged(int *currentRow*, int *currentColumn*, int *previousRow*, int *previousColumn*)

每当当前单元格发生变化时就会发出此信号。由指定的单元格*previousRow*和*previousColumn*是之前获得焦点的单元格，该单元格由*currentRow*和*currentColumn*是新的当前单元格。

### int QTableWidget::currentColumn() const

返回当前项目的列。

**也可以看看**[currentRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow)（） 和[setCurrentCell](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCell)()。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::currentItem() const

返回当前项目。

**也可以看看**[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)()。

### `[signal]`void QTableWidget::currentItemChanged([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **current*, [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **previous*)

每当当前项发生更改时，都会发出此信号。这*previous*item 是先前获得焦点的项目，*current*是新的当前项目。

### int QTableWidget::currentRow() const

返回当前项目的行。

**也可以看看**[currentColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColumn)（） 和[setCurrentCell](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCell)()。

### `[override virtual protected]`void QTableWidget::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### `[virtual protected]`bool QTableWidget::dropMimeData(int *row*, int *column*, const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*, [Qt::DropAction](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) *action*)

处理*data*由以给定结尾的拖放操作提供*action*在给定的*row*和*column*。返回`true`模型是否可以处理数据和操作；否则返回`false`.

**也可以看看**[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)()。

### void QTableWidget::editItem([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

开始编辑*item*如果它是可编辑的。

### `[override virtual protected]`bool QTableWidget::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::event](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QTableWidget::findItems(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [Qt::MatchFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MatchFlag-enum) *flags*) const

查找匹配的项目*text*使用给定的*flags*。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::horizontalHeaderItem(int *column*) const

返回列的水平标题项，*column*，如果已设置；否则返回`nullptr`.

**也可以看看**[setHorizontalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHorizontalHeaderItem)()。

### [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableWidget::indexFromItem(const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与给定相关的*item*。

**注意：**在 5.10 之前的 Qt 版本中，此函数采用非`const` *item*。

### `[slot]`void QTableWidget::insertColumn(int *column*)

在表中插入一个空列*column*。

### `[slot]`void QTableWidget::insertRow(int *row*)

在表中插入一个空行*row*。

### bool QTableWidget::isPersistentEditorOpen([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回持久编辑器是否为项目打开*item*。

**也可以看看**[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)（） 和[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)()。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::item(int *row*, int *column*) const

返回给定的项目*row*和*column*如果已设置；否则返回`nullptr`.

**也可以看看**[setItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItem)()。

### `[signal]`void QTableWidget::itemActivated([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

当指定的*item*已被激活

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::itemAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

返回指向给定项目的指针*point*，或者返回`nullptr`如果*point*未被表格小部件中的项目覆盖。

**也可以看看**[item](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item)()。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::itemAt(int *ax*, int *ay*) const

返回相当于以下位置的项目[QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*ax*,*ay*) 在表格小部件的坐标系中，或者`nullptr`如果指定点未被表格小部件中的项目覆盖，则返回。

**也可以看看**[item](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item)()。

### `[signal]`void QTableWidget::itemChanged([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

每当数据*item*已经改变。

### `[signal]`void QTableWidget::itemClicked([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

每当单击表中的项目时就会发出此信号。这*item*指定的是被单击的项目。

### `[signal]`void QTableWidget::itemDoubleClicked([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

每当双击表中的项目时就会发出此信号。这*item*指定的是双击的项目。

### `[signal]`void QTableWidget::itemEntered([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

当鼠标光标进入某个项目时，会发出此信号。这*item*是输入的项目。

仅当打开 mouseTracking 或在移动到某个项目时按下鼠标按钮时，才会发出此信号。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::itemFromIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回一个指向[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与给定相关的*index*。

### `[signal]`void QTableWidget::itemPressed([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

每当按下表中的项目时就会发出此信号。这*item*指定的是被按下的项目。

### const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::itemPrototype() const

返回表使用的项目原型。

**也可以看看**[setItemPrototype](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemPrototype)()。

### `[signal]`void QTableWidget::itemSelectionChanged()

每当选择发生变化时就会发出此信号。

**也可以看看**[selectedItems](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)（） 和[QTableWidgetItem::isSelected](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSelected)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QTableWidget::items(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*) const

返回指向包含在其中的项目的指针列表*data*目的。如果该对象不是由[QTreeWidget](https://doc-qt-io.translate.goog/qt-6/qtreewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在同一过程中，列表为空。

### `[virtual protected]`[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::mimeData(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> &*items*) const

返回一个对象，其中包含指定的序列化描述*items*。用于描述项目的格式是从[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)（） 功能。

如果项目列表为空，`nullptr`则返回而不是序列化的空列表。

### `[virtual protected]`[QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableWidget::mimeTypes() const

返回可用于描述表格小部件项目列表的 MIME 类型列表。

**也可以看看**[mimeData](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)()。

### void QTableWidget::openPersistentEditor([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

打开给定的编辑器*item*。编辑器在编辑后保持打开状态。

**也可以看看**[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)（） 和[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)()。

### void QTableWidget::removeCellWidget(int *row*, int *column*)

删除由 指示的单元格上设置的小部件*row*和*column*。

### `[slot]`void QTableWidget::removeColumn(int *column*)

删除列*column*以及表中的所有项目。

### `[slot]`void QTableWidget::removeRow(int *row*)

删除行*row*以及表中的所有项目。

### int QTableWidget::row(const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回的行*item*。

### int QTableWidget::rowCount() const

返回行数。

**注意：**属性 rowCount 的 Getter 函数。

**也可以看看**[setRowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowCount)()。

### `[slot]`void QTableWidget::scrollToItem(const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

如有必要，滚动视图以确保*item*是可见的。这*hint*参数更精确地指定*item*应在手术后定位。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QTableWidget::selectedItems() const

返回所有选定项目的列表。

此函数返回指向所选单元格内容的指针列表。使用[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)() 函数检索完整的选择，*包括*空单元格。

**也可以看看**[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTableWidgetSelectionRange](https://doc-qt-io.translate.goog/qt-6/qtablewidgetselectionrange.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QTableWidget::selectedRanges() const

返回所有选定范围的列表。

**也可以看看**[QTableWidgetSelectionRange](https://doc-qt-io.translate.goog/qt-6/qtablewidgetselectionrange.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QTableWidget::setCellWidget(int *row*, int *column*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

设置给定的*widget*要显示在给定的单元格中*row*和*column*，将小部件的所有权传递给表。

如果单元格小部件 A 被单元格小部件 B 替换，则单元格小部件 A 将被删除。例如，在下面的代码片段中，[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象将被删除。

```
setCellWidget(row, column, new QLineEdit);
...
setCellWidget(row, column, new QTextEdit);
```

**也可以看看**[cellWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellWidget)()。

### void QTableWidget::setColumnCount(int *columns*)

将此表模型中的列数设置为*columns*。如果这个值小于[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)()，不需要的列中的数据将被丢弃。

**注意：**属性的 Setter 函数[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)。

**也可以看看**[columnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)（） 和[setRowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowCount)()。

### void QTableWidget::setCurrentCell(int *row*, int *column*)

将当前单元格设置为位置 (*row*,*column*）。

取决于当前[selection mode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，也可以选择单元格。

**也可以看看**[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)(),[currentRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow)（）， 和[currentColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColumn)()。

### void QTableWidget::setCurrentCell(int *row*, int *column*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

将当前单元格设置为位置 (*row*,*column*），使用给定的*command*。

**也可以看看**[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)(),[currentRow](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow)（）， 和[currentColumn](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColumn)()。

### void QTableWidget::setCurrentItem([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

将当前项目设置为*item*。

除非选择模式是[NoSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，该项目也被选中。

**也可以看看**[currentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItem)（） 和[setCurrentCell](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCell)()。

### void QTableWidget::setCurrentItem([QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

将当前项目设置为*item*，使用给定的*command*。

**也可以看看**[currentItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItem)（） 和[setCurrentCell](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCell)()。

### void QTableWidget::setHorizontalHeaderItem(int *column*, [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

设置列的水平标题项*column*到*item*。如有必要，可增加列数以适应该项目。上一个标题项（如果有）将被删除。

**也可以看看**[horizontalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderItem)()。

### void QTableWidget::setHorizontalHeaderLabels(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labels*)

使用设置水平标题标签*labels*。

### void QTableWidget::setItem(int *row*, int *column*, [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

设置给定的项目*row*和*column*到*item*。

该表拥有该项目的所有权。

请注意，如果启用排序（请参阅[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)） 和*column*是当前的排序列，*row*将被移动到由下式确定的排序位置*item*。

如果要设置特定行的多个项目（例如，通过在循环中调用 setItem()），您可能需要在执行此操作之前关闭排序，然后再将其重新打开；这将允许您使用相同的*row*同一行中所有项目的参数（即 setItem() 不会移动该行）。

**也可以看看**[item](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item)（） 和[takeItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeItem)()。

### void QTableWidget::setItemPrototype(const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

将表的项目原型设置为指定的*item*。

当需要创建新的表格项时，表格小部件将使用项目原型克隆功能。例如，当用户在空单元格中进行编辑时。当您有一个[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类并想确保[QTableWidget](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建子类的实例。

该表拥有原型的所有权。

**也可以看看**[itemPrototype](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemPrototype)()。

### void QTableWidget::setRangeSelected(const [QTableWidgetSelectionRange](https://doc-qt-io.translate.goog/qt-6/qtablewidgetselectionrange.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*range*, bool *select*)

选择或取消选择*range*根据*select*。

### void QTableWidget::setRowCount(int *rows*)

将此表模型中的行数设置为*rows*。如果这个值小于[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)()，不需要的行中的数据将被丢弃。

**注意：**属性的 Setter 函数[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)。

**也可以看看**[rowCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)（） 和[setColumnCount](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnCount)()。

### void QTableWidget::setVerticalHeaderItem(int *row*, [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

设置行的垂直标题项*row*到*item*。

**也可以看看**[verticalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderItem)()。

### void QTableWidget::setVerticalHeaderLabels(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labels*)

使用设置垂直标题标签*labels*。

### void QTableWidget::sortItems(int *column*, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::AscendingOrder)

根据以下条件对表格小部件中的所有行进行排序*column*和*order*。

### `[virtual protected]`[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) QTableWidget::supportedDropActions() const

返回此视图支持的放置操作。

**也可以看看**[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum)。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::takeHorizontalHeaderItem(int *column*)

删除水平标题项*column*从标题中删除而不删除它。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::takeItem(int *row*, int *column*)

删除位于*row*和*column*从表中删除而不删除它。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::takeVerticalHeaderItem(int *row*)

删除垂直标题项*row*从标题中删除而不删除它。

### [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTableWidget::verticalHeaderItem(int *row*) const

返回行的垂直标题项*row*。

**也可以看看**[setVerticalHeaderItem](https://doc-qt-io.translate.goog/qt-6/qtablewidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalHeaderItem)()。

### int QTableWidget::visualColumn(int *logicalColumn*) const

返回给定的可视列*logicalColumn*。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTableWidget::visualItemRect(const [QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回视口中项目占据的矩形*item*。

### int QTableWidget::visualRow(int *logicalRow*) const

返回给定的可视行*logicalRow*。