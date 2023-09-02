#  QColumnView Class

QColumnView 类提供了列视图的模型/视图实现。[更多的...](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <  QColumnView>                                     |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qcolumnview-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[resizeGripsVisible](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeGripsVisible-prop)** : bool

## 公共职能

|            | **[QColumnView](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QColumnView)**(QWidget **parent* = nullptr) |
| ---------- | ------------------------------------------------------------ |
| virtual    | **[~QColumnView](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QColumnView)**() |
| QList<int> | **[columnWidths](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidths)**() const |
| QWidget *  | **[previewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previewWidget)**() const |
| bool       | **[resizeGripsVisible](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeGripsVisible-prop)**() const |
| void       | **[setColumnWidths](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidths)**(const QList<int> &*list*) |
| void       | **[setPreviewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPreviewWidget)**(QWidget **widget*) |
| void       | **[setResizeGripsVisible](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeGripsVisible-prop)**(bool *visible*) |

## 重新实施公共职能

| virtual QModelIndex | **[indexAt](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)**(const QPoint &*point*) const override |
| ------------------- | ------------------------------------------------------------ |
| virtual void        | **[scrollTo](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)**(const QModelIndex &*index*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) override |
| virtual void        | **[selectAll](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)**() override |
| virtual void        | **[setModel](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)**(QAbstractItemModel **model*) override |
| virtual void        | **[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)**(const QModelIndex &*index*) override |
| virtual void        | **[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)**(QItemSelectionModel **newSelectionModel*) override |
| virtual QSize       | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| virtual QRect       | **[visualRect](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)**(const QModelIndex &*index*) const override |

## 信号

| void | **[updatePreviewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updatePreviewWidget)**(const QModelIndex &*index*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 受保护的功能

| virtual QAbstractItemView * | **[createColumn](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createColumn)**(const QModelIndex &*index*) |
| --------------------------- | ------------------------------------------------------------ |
| void                        | **[initializeColumn](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initializeColumn)**(QAbstractItemView **column*) const |

## 重新实现受保护的功能

| virtual void        | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(const QModelIndex &*current*, const QModelIndex &*previous*) override |
| ------------------- | ------------------------------------------------------------ |
| virtual int         | **[horizontalOffset](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)**() const override |
| virtual bool        | **[isIndexHidden](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)**(const QModelIndex &*index*) const override |
| virtual QModelIndex | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QAbstractItemView::CursorAction *cursorAction*, Qt::KeyboardModifiers *modifiers*) override |
| virtual void        | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **event*) override |
| virtual void        | **[rowsInserted](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)**(const QModelIndex &*parent*, int *start*, int *end*) override |
| virtual void        | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual void        | **[setSelection](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)**(const QRect &*rect*, QItemSelectionModel::SelectionFlags *command*) override |
| virtual int         | **[verticalOffset](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)**() const override |
| virtual QRegion     | **[visualRegionForSelection](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)**(const QItemSelection &*selection*) const override |

## 详细说明

QColumnView 在多个 QListView 中显示一个模型，每个 QListView 对应树中的每个层次结构。这有时称为级联列表。

QColumnView 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QColumnView 实现了定义的接口[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，允许它显示由派生的模型提供的数据[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QColumnView\QColumnView\qcolumnview.png)

**也可以看看**[Model/View Programming](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### resizeGripsVisible : bool

此属性保存指定列表视图是否获得调整大小夹点的方法

默认情况下，`visible`设置为 true

**访问功能：**

| bool | **resizeGripsVisible**() const            |
| ---- | ----------------------------------------- |
| void | **setResizeGripsVisible**(bool *visible*) |

**也可以看看**[setRootIndex](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)()。

## 成员函数文档

### `[explicit]`QColumnView::QColumnView([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个列视图*parent*来表示模型的数据。使用[setModel](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)() 设置模型。

**也可以看看**[QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[virtual]`QColumnView::~QColumnView()

破坏列视图。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<int> QColumnView::columnWidths() const

返回此视图中所有列的宽度的列表。

**也可以看看**[setColumnWidths](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnWidths)()。

### `[virtual protected]`[QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QAbstractItemView) *QColumnView::createColumn(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

要在选择项目时对最后一列使用自定义小部件，请重载此函数并返回小部件。*index*是将分配给视图的根索引。

返回新视图。[QColumnView](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将自动取得该小部件的所有权。

**也可以看看**[setPreviewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPreviewWidget)()。

### `[override virtual protected]`void QColumnView::currentChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*current*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*previous*)

重新实现：[QAbstractItemView::currentChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)（常量 QModelIndex 和当前，常量 QModelIndex 和上一个）。

### `[override virtual protected]`int QColumnView::horizontalOffset() const

重新实现：[QAbstractItemView::horizontalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalOffset)。

### `[override virtual]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColumnView::indexAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

重新实现：[QAbstractItemView::indexAt(const QPoint &point) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexAt)。

### `[protected]`void QColumnView::initializeColumn([QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QAbstractItemView) **column*) const

复制列视图的行为和选项并将其应用到*column*如那个[iconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)(),[textElideMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textElideMode-prop)（） 和[alternatingRowColors](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alternatingRowColors-prop)()。这在重新实现时很有用[createColumn](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createColumn)()。

**也可以看看**[createColumn](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createColumn)()。

### `[override virtual protected]`bool QColumnView::isIndexHidden(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::isIndexHidden(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isIndexHidden)。

### `[override virtual protected]`[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColumnView::moveCursor([QAbstractItemView::CursorAction](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorAction-enum) *cursorAction*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*)

重新实现：[QAbstractItemView::moveCursor](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)（QAbstractItemView::CursorAction 光标操作、Qt::KeyboardModifiers 修饰符）。

向左移动应转到父索引向右移动应转到子索引或如果没有子索引则向下移动

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QColumnView::previewWidget() const

返回预览小部件，或者`nullptr`如果没有则返回。

**也可以看看**[setPreviewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPreviewWidget)（） 和[updatePreviewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updatePreviewWidget)()。

### `[override virtual protected]`void QColumnView::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractItemView::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[override virtual protected]`void QColumnView::rowsInserted(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*parent*, int *start*, int *end*)

重新实现：[QAbstractItemView::rowsInserted](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowsInserted)(const QModelIndex &parent, int start, int end)。

### `[override virtual protected]`void QColumnView::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

### `[override virtual]`void QColumnView::scrollTo(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

重新实现：[QAbstractItemView::scrollTo](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollTo)（const QModelIndex &index，QAbstractItemView::ScrollHint 提示）。

### `[override virtual]`void QColumnView::selectAll()

重新实现：[QAbstractItemView::selectAll](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()。

### void QColumnView::setColumnWidths(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<int> &*list*)

将列宽设置为中给出的值*list*。创建列时将保留并使用列表中的额外值。

如果列表包含的值太少，则仅其余列的宽度不会被修改。

**也可以看看**[columnWidths](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnWidths)（） 和[createColumn](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createColumn)()。

### `[override virtual]`void QColumnView::setModel([QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **model*)

重新实现：[QAbstractItemView::setModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModel)（QAbstractItemModel *模型）。

### void QColumnView::setPreviewWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

设置预览*widget*。

这*widget*成为列视图的子视图，并且当删除列区域或设置新的小部件时将被销毁。

**也可以看看**[previewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previewWidget)（） 和[updatePreviewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updatePreviewWidget)()。

### `[override virtual]`void QColumnView::setRootIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

重新实现：[QAbstractItemView::setRootIndex](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRootIndex)（常量 QModelIndex &index）。

### `[override virtual protected]`void QColumnView::setSelection(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

重新实现：[QAbstractItemView::setSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（const QRect &rect，QItemSelectionModel::SelectionFlags 标志）。

### `[override virtual]`void QColumnView::setSelectionModel([QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **newSelectionModel*)

重新实现：[QAbstractItemView::setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)(QItemSelectionModel *selectionModel)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColumnView::sizeHint() const

重新实现：[QAbstractScrollArea::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### `[signal]`void QColumnView::updatePreviewWidget(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当预览小部件应该更新以提供有关以下内容的丰富信息时，会发出此信号*index*

**也可以看看**[previewWidget](https://doc-qt-io.translate.goog/qt-6/qcolumnview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previewWidget)()。

### `[override virtual protected]`int QColumnView::verticalOffset() const

重新实现：[QAbstractItemView::verticalOffset() const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalOffset)。

### `[override virtual]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColumnView::visualRect(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

重新实现：[QAbstractItemView::visualRect(const QModelIndex &index) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRect)。

### `[override virtual protected]`[QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColumnView::visualRegionForSelection(const [QItemSelection](https://doc-qt-io.translate.goog/qt-6/qitemselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*selection*) const

重新实现：[QAbstractItemView::visualRegionForSelection(const QItemSelection &selection) const](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualRegionForSelection)。