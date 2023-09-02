#  QListView Class

QListView 类在模型上提供列表或图标视图。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QListView>                                        |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QHelpIndexWidget](https://doc-qt-io.translate.goog/qt-6/qhelpindexwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QUndoView](https://doc-qt-io.translate.goog/qt-6/qundoview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlistview-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[Flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)** { LeftToRight, TopToBottom } |
| ---- | ------------------------------------------------------------ |
| enum | **[LayoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutMode-enum)** { SinglePass, Batched } |
| enum | **[Movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)** { Static, Free, Snap } |
| enum | **[ResizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)** { Fixed, Adjust } |
| enum | **[ViewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)** { ListMode, IconMode } |

## 特性

| **[batchSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#batchSize-prop)** : int**[flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flow-prop)** : Flow**[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)** : QSize**[isWrapping](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWrapping-prop)** : bool**[itemAlignment](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAlignment-prop)** : Qt::Alignment**[layoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutMode-prop)** : LayoutMode**[modelColumn](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelColumn-prop)** : int | **[movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop)** : Movement**[resizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)** : ResizeMode**[selectionRectVisible](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionRectVisible-prop)** : bool**[spacing](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)** : int**[uniformItemSizes](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformItemSizes-prop)** : bool**[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)** : ViewMode**[wordWrap](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)** : bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                       | **[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListView)**(QWidget **parent* = nullptr) |
| --------------------- | ------------------------------------------------------------ |
| virtual               | **[~QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QListView)**() |
| int                   | **[batchSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#batchSize-prop)**() const |
| void                  | **[clearPropertyFlags](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearPropertyFlags)**() |
| QListView::Flow       | **[flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flow-prop)**() const |
| QSize                 | **[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)**() const |
| bool                  | **[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)**(int *row*) const |
| bool                  | **[isSelectionRectVisible](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionRectVisible-prop)**() const |
| bool                  | **[isWrapping](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWrapping-prop)**() const |
| Qt::Alignment         | **[itemAlignment](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAlignment-prop)**() const |
| QListView::LayoutMode | **[layoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutMode-prop)**() const |
| int                   | **[modelColumn](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelColumn-prop)**() const |
| QListView::Movement   | **[movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop)**() const |
| QListView::ResizeMode | **[resizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)**() const |
| void                  | **[setBatchSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#batchSize-prop)**(int *batchSize*) |
| void                  | **[setFlow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flow-prop)**(QListView::Flow *flow*) |
| void                  | **[setGridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)**(const QSize &*size*) |
| void                  | **[setItemAlignment](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAlignment-prop)**(Qt::Alignment *alignment*) |
| void                  | **[setLayoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutMode-prop)**(QListView::LayoutMode *mode*) |
| void                  | **[setModelColumn](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modelColumn-prop)**(int *column*) |
| void                  | **[setMovement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop)**(QListView::Movement *movement*) |
| void                  | **[setResizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)**(QListView::ResizeMode *mode*) |
| void                  | **[setRowHidden](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowHidden)**(int *row*, bool *hide*) |
| void                  | **[setSelectionRectVisible](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionRectVisible-prop)**(bool *show*) |
| void                  | **[setSpacing](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)**(int *space*) |
| void                  | **[setUniformItemSizes](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformItemSizes-prop)**(bool *enable*) |
| void                  | **[setViewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)**(QListView::ViewMode *mode*) |
| void                  | **[setWordWrap](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)**(bool *on*) |
| void                  | **[setWrapping](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWrapping-prop)**(bool *enable*) |
| int                   | **[spacing](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)**() const |
| bool                  | **[uniformItemSizes](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformItemSizes-prop)**() const |
| QListView::ViewMode   | **[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)**() const |
| bool                  | **[wordWrap](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrap-prop)**() const |

## 重新实施公共职能

| virtual QModelIndex | **[indexAt](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)**(const QPoint &*p*) const override |
| ------------------- | ------------------------------------------------------------ |
| virtual void        | **[scrollTo](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)**(const QModelIndex &*index*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) override |
| virtual void        | **[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)**(const QModelIndex &*index*) override |
| virtual QRect       | **[visualRect](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)**(const QModelIndex &*index*) const override |

## 信号

| void | **[indexesMoved](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexesMoved)**(const QModelIndexList &*indexes*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected function

| QRect | **[rectForIndex](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rectForIndex)**(const QModelIndex &*index*) const |
| ----- | ------------------------------------------------------------ |
| void  | **[setPositionForIndex](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPositionForIndex)**(const QPoint &*position*, const QModelIndex &*index*) |

## 重新实现protected function

| virtual void            | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(const QModelIndex &*current*, const QModelIndex &*previous*) override |
| ----------------------- | ------------------------------------------------------------ |
| virtual void            | **[dataChanged](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)**(const QModelIndex &*topLeft*, const QModelIndex &*bottomRight*, const QList<int> &*roles* = QList<int>()) override |
| virtual void            | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **e*) override |
| virtual void            | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **e*) override |
| virtual void            | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **event*) override |
| virtual bool            | **[event](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual int             | **[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)**() const override |
| virtual void            | **[initViewItemOption](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initViewItemOption)**(QStyleOptionViewItem **option*) const override |
| virtual bool            | **[isIndexHidden](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)**(const QModelIndex &*index*) const override |
| virtual void            | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void            | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual QModelIndex     | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QAbstractItemView::CursorAction *cursorAction*, Qt::KeyboardModifiers *modifiers*) override |
| virtual void            | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **e*) override |
| virtual void            | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **e*) override |
| virtual void            | **[rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)**(const QModelIndex &*parent*, int *start*, int *end*) override |
| virtual void            | **[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)**(const QModelIndex &*parent*, int *start*, int *end*) override |
| virtual void            | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual QModelIndexList | **[selectedIndexes](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)**() const override |
| virtual void            | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**(const QItemSelection &*selected*, const QItemSelection &*deselected*) override |
| virtual void            | **[setSelection](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)**(const QRect &*rect*, QItemSelectionModel::SelectionFlags *command*) override |
| virtual void            | **[startDrag](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)**(Qt::DropActions *supportedActions*) override |
| virtual void            | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **e*) override |
| virtual void            | **[updateGeometries](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)**() override |
| virtual int             | **[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)**() const override |
| virtual QSize           | **[viewportSizeHint](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)**() const override |
| virtual QRegion         | **[visualRegionForSelection](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)**(const QItemSelection &*selection*) const override |
| virtual void            | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QWheelEvent **e*) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\L\QListView\QListView\windows-listview.png)

QListView 将存储在模型中的项目呈现为简单的非分层列表或图标集合。该类用于提供以前由`QListBox`和`QIconView`类提供的列表和图标视图，但使用了 Qt 模型/视图架构提供的更灵活的方法。

QListView 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

该视图不显示水平或垂直标题；要显示带有水平标题的项目列表，请使用[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)反而。

QListView 实现了定义的接口[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，允许它显示由派生的模型提供的数据[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级。

列表视图中的项目可以使用两种视图模式之一显示：[ListMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)，项目以简单列表的形式显示；在[IconMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)*，列表视图采用图标视图*的形式，其中项目用图标显示，就像文件管理器中的文件一样。默认情况下，列表视图位于[ListMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)。要更改查看模式，请使用[setViewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)() 函数，并确定当前的视图模式，使用[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

这些视图中的项目按照指定的方向布置[flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flow-prop)() 的列表视图。这些项目可以固定在适当的位置，也可以允许移动，具体取决于视图的[movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop)（） 状态。

如果模型中的项目不能完全按照流动方向布局，可以将它们包裹在视图部件的边界处；这取决于[isWrapping](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWrapping-prop)()。当项目由图标视图表示时，此属性非常有用。

这[resizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)（） 和[layoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutMode-prop)() 控制项目的布置方式和时间。项目根据其间距[spacing](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)()，并且可以存在于由以下指定的大小的概念网格内[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)()。这些项目可以呈现为大图标或小图标，具体取决于它们的[iconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)()。

### 提高绩效

可以向视图提供有关其正在处理的数据的提示，以便在显示大量项目时提高其性能。对于旨在显示具有相同大小的项目的视图，可以采取的一种方法是设置[uniformItemSizes](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uniformItemSizes-prop)属性为真。

**也可以看看**[View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#view-classes),[Item Views Puzzle Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-puzzle-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTableView](https://doc-qt-io.translate.goog/qt-6/qtableview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QListView::Flow

| 持续的                   | 价值 | 描述                       |
| ------------------------ | ---- | -------------------------- |
| `QListView::LeftToRight` | `0`  | 项目在视图中从左到右排列。 |
| `QListView::TopToBottom` | `1`  | 项目在视图中从上到下排列。 |

### enum QListView::LayoutMode

| 持续的                  | 价值 | 描述                                                         |
| ----------------------- | ---- | ------------------------------------------------------------ |
| `QListView::SinglePass` | `0`  | 物品一下子就全部摆好了。                                     |
| `QListView::Batched`    | `1`  | 物品按批次排列[batchSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#batchSize-prop)项目。 |

**也可以看看**[batchSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#batchSize-prop)。

### enum QListView::Movement

| 持续的              | 价值 | 描述                                                         |
| ------------------- | ---- | ------------------------------------------------------------ |
| `QListView::Static` | `0`  | 用户无法移动这些项目。                                       |
| `QListView::Free`   | `1`  | 用户可以自由移动这些项目。                                   |
| `QListView::Snap`   | `2`  | 移动时，项目会捕捉到指定的网格；看[setGridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)()。 |

### enum QListView::ResizeMode

| 持续的              | 价值 | 描述                                   |
| ------------------- | ---- | -------------------------------------- |
| `QListView::Fixed`  | `0`  | 仅在第一次显示视图时才会布置这些项目。 |
| `QListView::Adjust` | `1`  | 每次调整视图大小时都会对项目进行布局。 |

### enum QListView::ViewMode

| 持续的                | 价值 | 描述                                                         |
| --------------------- | ---- | ------------------------------------------------------------ |
| `QListView::ListMode` | `0`  | 这些项目使用[TopToBottom](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)流动，体积小，静态运动 |
| `QListView::IconMode` | `1`  | 这些项目使用[LeftToRight](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)流量大、动作自由 |

## 财产文件

### batchSize : int

该属性保存每批中布置的项目数量，如果[layoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutMode-prop)被设定为[Batched](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutMode-enum)

默认值为 100。

**访问功能：**

| int  | **batchSize**() const             |
| ---- | --------------------------------- |
| void | **setBatchSize**(int *batchSize*) |

### flow : [Flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)

此属性保存项目布局应流动的方向。

如果这个属性是[LeftToRight](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)，项目将从左到右排列。如果[isWrapping](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWrapping-prop)属性为 时`true`，布局到达可见区域右侧时将换行。如果这个属性是[TopToBottom](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)，项目将从可见区域的顶部开始布局，到达底部时进行环绕。

当视图可见时设置此属性将导致项目再次布局。

默认情况下，该属性设置为[TopToBottom](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)。

**访问功能：**

| QListView::Flow | **flow**() const                    |
| --------------- | ----------------------------------- |
| void            | **setFlow**(QListView::Flow *flow*) |

**也可以看看**[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### gridSize : [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存布局网格的大小

此属性是布置项目的网格的大小。默认值是空大小，这意味着没有网格并且布局不是在网格中完成的。将此属性设置为非空大小会在网格布局上切换。（当网格布局生效时[spacing](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)属性被忽略。）

当视图可见时设置此属性将导致项目再次布局。

**访问功能：**

| QSize | **gridSize**() const                 |
| ----- | ------------------------------------ |
| void  | **setGridSize**(const QSize &*size*) |

**也可以看看**[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### isWrapping : bool

该属性保存项目布局是否应该换行。

该属性保存当可见区域没有更多空间时布局是否应该换行。布局换行的点取决于[flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flow-prop)财产。

当视图可见时设置此属性将导致项目再次布局。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isWrapping**() const         |
| ---- | ------------------------------ |
| void | **setWrapping**(bool *enable*) |

**也可以看看**[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### itemAlignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

该属性保存单元格中每个项目的对齐方式

仅支持此功能[ListMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)和[TopToBottom](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flow-enum)流并启用包装。默认对齐方式为 0，这意味着某个项目完全填充其单元格。

**访问功能：**

| Qt::Alignment | **itemAlignment**() const                       |
| ------------- | ----------------------------------------------- |
| void          | **setItemAlignment**(Qt::Alignment *alignment*) |

### layoutMode : [LayoutMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutMode-enum)

确定项目的布局是立即发生还是延迟发生。

该属性保存项目的布局模式。当模式为[SinglePass](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutMode-enum)（默认），所有项目都一次性排列好。当模式为[Batched](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutMode-enum)，物品按批次排列[batchSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#batchSize-prop)项目，同时处理事件。这使得在布置其余部分时可以立即查看可见项目并与之交互。

**访问功能：**

| QListView::LayoutMode | **layoutMode**() const                          |
| --------------------- | ----------------------------------------------- |
| void                  | **setLayoutMode**(QListView::LayoutMode *mode*) |

**也可以看看**[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### modelColumn : int

该属性保存模型中可见的列

默认情况下，该属性包含 0，表示将显示模型中的第一列。

**访问功能：**

| int  | **modelColumn**() const          |
| ---- | -------------------------------- |
| void | **setModelColumn**(int *column*) |

### movement : [Movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)

此属性保存项目是否可以自由移动、捕捉到网格或根本无法移动。

此属性确定用户如何移动视图中的项目。[Static](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)意味着用户无法移动该项目。[Free](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)意味着用户可以将项目拖放到视图中的任何位置。[Snap](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)意味着用户可以拖放项目，但只能拖放到由 表示的概念网格中的位置[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)财产。

当视图可见时设置此属性将导致项目再次布局。

默认情况下，该属性设置为[Static](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)。

**访问功能：**

| QListView::Movement | **movement**() const                            |
| ------------------- | ----------------------------------------------- |
| void                | **setMovement**(QListView::Movement *movement*) |

**也可以看看**[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop),[resizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)， 和[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### resizeMode : [ResizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)

该属性保存在调整视图大小时是否重新布局项目。

如果这个属性是[Adjust](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)，当视图大小调整时，项目将重新布局。如果值为[Fixed](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)，当视图大小调整时，项目将不会布局。

默认情况下，该属性设置为[Fixed](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)。

**访问功能：**

| QListView::ResizeMode | **resizeMode**() const                          |
| --------------------- | ----------------------------------------------- |
| void                  | **setResizeMode**(QListView::ResizeMode *mode*) |

**也可以看看**[movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop),[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop)， 和[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### selectionRectVisible : bool

选择矩形是否可见

如果此属性为`true`，则选择矩形可见；否则它将被隐藏。

**注意：**只有当选择模式处于可以选择多个项目的模式时，选择矩形才可见；即，如果选择模式为，则不会绘制选择矩形[QAbstractItemView::SingleSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isSelectionRectVisible**() const       |
| ---- | ---------------------------------------- |
| void | **setSelectionRectVisible**(bool *show*) |

### spacing : int

该属性保存布局中项目周围的空间

此属性是布局中项目周围填充的空白空间的大小。

当视图可见时设置此属性将导致项目再次布局。

默认情况下，此属性包含值 0。

**访问功能：**

| int  | **spacing**() const         |
| ---- | --------------------------- |
| void | **setSpacing**(int *space*) |

**也可以看看**[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

### uniformItemSizes : bool

该属性保存列表视图中的所有项目是否具有相同的大小

仅当保证视图中的所有项目具有相同大小时，才应将此属性设置为 true。这使得视图能够出于性能目的进行一些优化。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **uniformItemSizes**() const           |
| ---- | -------------------------------------- |
| void | **setUniformItemSizes**(bool *enable*) |

### viewMode : [ViewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)

该属性保存了视图模式[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

此属性将更改其他未设置的属性以符合设置的视图模式。[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)- 已经设置的特定属性不会被更改，除非[clearPropertyFlags](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearPropertyFlags)() 已被调用。

设置视图模式将根据所选的移动启用或禁用拖放。为了[ListMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)，默认运动是[Static](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)（禁用拖放）；为了[IconMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)，默认运动是[Free](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Movement-enum)（启用拖放）。

**访问功能：**

| QListView::ViewMode | **viewMode**() const                        |
| ------------------- | ------------------------------------------- |
| void                | **setViewMode**(QListView::ViewMode *mode*) |

**也可以看看**[isWrapping](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWrapping-prop),[spacing](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop),[gridSize](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridSize-prop),[flow](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flow-prop),[movement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop)， 和[resizeMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)。

### wordWrap : bool

该属性保存项目文本自动换行策略

如果此属性为`true`，则项目文本将在必要的断字处换行；否则它根本没有被包裹。该属性是`false`默认的。

请注意，即使启用换行，单元格也不会扩展以为文本腾出空间。它将根据视图的显示，为无法显示的文本打印省略号[textElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)。

**访问功能：**

| bool | **wordWrap**() const       |
| ---- | -------------------------- |
| void | **setWordWrap**(bool *on*) |

## 成员函数文档

### `[explicit]`QListView::QListView([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值创建一个新的 QListView*parent*查看模型。使用[setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)() 设置模型。

### `[virtual]`QListView::~QListView()

破坏了景色。

### void QListView::clearPropertyFlags()

清除[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)-特定属性标志。看[viewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)。

继承自的属性[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不被属性标志覆盖。具体来说，[dragEnabled](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)和[acceptsDrops](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptDrops-prop)计算公式为[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打电话时[setMovement](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movement-prop)（） 或者[setViewMode](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### `[override virtual protected]`void QListView::currentChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*current*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*previous*)

重新实现：[QAbstractItemView::currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)（常量 QModelIndex 和当前，常量 QModelIndex 和上一个）。

### `[override virtual protected]`void QListView::dataChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*topLeft*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*bottomRight*, const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<int> &*roles* = QList<int>())

重新实现：[QAbstractItemView::dataChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dataChanged)（const QModelIndex &topLeft、const QModelIndex &bottomRight、const QList<int> &roles）。

### `[override virtual protected]`void QListView::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

### `[override virtual protected]`void QListView::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[override virtual protected]`void QListView::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### `[override virtual protected]`bool QListView::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::event](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`int QListView::horizontalOffset() const

重新实现：[QAbstractItemView::horizontalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)。

### `[override virtual]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListView::indexAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*p*) const

重新实现：[QAbstractItemView::indexAt(const QPoint &point) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)。

### `[signal]`void QListView::indexesMoved(const [QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) &*indexes*)

当指定的*indexes*已在视图中移动。

### `[override virtual protected]`void QListView::initViewItemOption([QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

重新实现：[QAbstractItemView::initViewItemOption(QStyleOptionViewItem *option) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initViewItemOption)。

### `[override virtual protected]`bool QListView::isIndexHidden(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::isIndexHidden(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)。

### bool QListView::isRowHidden(int *row*) const

返回`true`如果*row*被隐藏；否则返回`false`.

### `[override virtual protected]`void QListView::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QListView::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（QMouseEvent *事件）。

### `[override virtual protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListView::moveCursor([QAbstractItemView::CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum) *cursorAction*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*)

重新实现：[QAbstractItemView::moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)（QAbstractItemView::CursorAction 光标操作、Qt::KeyboardModifiers 修饰符）。

### `[override virtual protected]`void QListView::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[protected]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListView::rectForIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回位置处项目的矩形*index*在模型中。该矩形位于内容坐标中。

**也可以看看**[visualRect](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)()。

### `[override virtual protected]`void QListView::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[override virtual protected]`void QListView::rowsAboutToBeRemoved(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

重新实现：[QAbstractItemView::rowsAboutToBeRemoved](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsAboutToBeRemoved)(const QModelIndex &parent, int start, int end)。

### `[override virtual protected]`void QListView::rowsInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

重新实现：[QAbstractItemView::rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)(const QModelIndex &parent, int start, int end)。

### `[override virtual protected]`void QListView::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

滚动查看内容*dx*和*dy*。

### `[override virtual]`void QListView::scrollTo(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

重新实现：[QAbstractItemView::scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)（const QModelIndex &index，QAbstractItemView::ScrollHint 提示）。

### `[override virtual protected]`[QModelIndexList](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QModelIndexList-typedef) QListView::selectedIndexes() const

重新实现：[QAbstractItemView::selectedIndexes() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedIndexes)。

### `[override virtual protected]`void QListView::selectionChanged(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selected*, const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deselected*)

重新实现：[QAbstractItemView::selectionChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)（常量 QItemSelection 和已选择，常量 QItemSelection 和取消选择）。

### `[protected]`void QListView::setPositionForIndex(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

将项目的内容位置设置为*index*在模型中给定*position*。如果列表视图的移动模式为 Static 或者其视图模式为[ListView](https://doc-qt-io.translate.goog/qt-6/qml-qtquick-listview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，该功能将不起作用。

### `[override virtual]`void QListView::setRootIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

重新实现：[QAbstractItemView::setRootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)（常量 QModelIndex &index）。

### void QListView::setRowHidden(int *row*, bool *hide*)

如果*hide*是真的，给定的*row*将被隐藏；否则*row*将显示。

**也可以看看**[isRowHidden](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowHidden)()。

### `[override virtual protected]`void QListView::setSelection(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

重新实现：[QAbstractItemView::setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（const QRect &rect，QItemSelectionModel::SelectionFlags 标志）。

### `[override virtual protected]`void QListView::startDrag([Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) *supportedActions*)

重新实现：[QAbstractItemView::startDrag](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startDrag)（Qt::DropActions 支持的操作）。

### `[override virtual protected]`void QListView::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractItemView::timerEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。

### `[override virtual protected]`void QListView::updateGeometries()

重新实现：[QAbstractItemView::updateGeometries](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateGeometries)()。

### `[override virtual protected]`int QListView::verticalOffset() const

重新实现：[QAbstractItemView::verticalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)。

### `[override virtual protected]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListView::viewportSizeHint() const

重新实现：[QAbstractItemView::viewportSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)。

### `[override virtual]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListView::visualRect(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::visualRect(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)。

### `[override virtual protected]`[QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListView::visualRegionForSelection(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selection*) const

重新实现：[QAbstractItemView::visualRegionForSelection(const QItemSelection &selection) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)。

从 4.7 开始，返回的区域仅包含与视口相交（或包含在视口中）的矩形。

### `[override virtual protected]`void QListView::wheelEvent([QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)(QWheelEvent *e)。