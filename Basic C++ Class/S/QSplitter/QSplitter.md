#  QSplitter Class

QSplitter 类实现了一个分割器小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QSplitter>                                        |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qsplitter-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[childrenCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childrenCollapsible-prop)** : bool
- **[handleWidth](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handleWidth-prop)** : int
- **[opaqueResize](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueResize-prop)** : bool
- **[orientation](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)** : Qt::Orientation

## 公共职能

|                   | **[QSplitter](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QSplitter)**(QWidget **parent* = nullptr) |
| ----------------- | ------------------------------------------------------------ |
|                   | **[QSplitter](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QSplitter-1)**(Qt::Orientation *orientation*, QWidget **parent* = nullptr) |
| virtual           | **[~QSplitter](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QSplitter)**() |
| void              | **[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)**(QWidget **widget*) |
| bool              | **[childrenCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childrenCollapsible-prop)**() const |
| int               | **[count](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**() const |
| void              | **[getRange](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getRange)**(int *index*, int **min*, int **max*) const |
| QSplitterHandle * | **[handle](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handle)**(int *index*) const |
| int               | **[handleWidth](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handleWidth-prop)**() const |
| int               | **[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)**(QWidget **widget*) const |
| void              | **[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)**(int *index*, QWidget **widget*) |
| bool              | **[isCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isCollapsible)**(int *index*) const |
| bool              | **[opaqueResize](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueResize-prop)**() const |
| Qt::Orientation   | **[orientation](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)**() const |
| void              | **[refresh](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)**() |
| QWidget *         | **[replaceWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replaceWidget)**(int *index*, QWidget **widget*) |
| bool              | **[restoreState](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restoreState)**(const QByteArray &*state*) |
| QByteArray        | **[saveState](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#saveState)**() const |
| void              | **[setChildrenCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childrenCollapsible-prop)**(bool) |
| void              | **[setCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCollapsible)**(int *index*, bool *collapse*) |
| void              | **[setHandleWidth](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handleWidth-prop)**(int) |
| void              | **[setOpaqueResize](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueResize-prop)**(bool *opaque* = true) |
| void              | **[setOrientation](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)**(Qt::Orientation) |
| void              | **[setSizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizes)**(const QList<int> &*list*) |
| void              | **[setStretchFactor](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStretchFactor)**(int *index*, int *stretch*) |
| QList<int>        | **[sizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizes)**() const |
| QWidget *         | **[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)**(int *index*) const |

## 重载的公共职能

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 信号

| void | **[splitterMoved](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#splitterMoved)**(int *pos*, int *index*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected function

| int                       | **[closestLegalPosition](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closestLegalPosition)**(int *pos*, int *index*) |
| ------------------------- | ------------------------------------------------------------ |
| virtual QSplitterHandle * | **[createHandle](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createHandle)**() |
| void                      | **[moveSplitter](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveSplitter)**(int *pos*, int *index*) |
| void                      | **[setRubberBand](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRubberBand)**(int *pos*) |

## 重新实现protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **ev*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[childEvent](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childEvent)**(QChildEvent **c*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent *) override |

## 详细说明

拆分器允许用户通过拖动子部件之间的边界来控制子部件的大小。单个分离器可以控制任意数量的小部件。QSplitter 的典型用途是创建多个小部件并使用添加它们[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（） 或者[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

下面的例子将展示一个[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并排，带有两个分离手柄：

```
    QSplitter *splitter = new QSplitter(parent);
    QListView *listview = new QListView;
    QTreeView *treeview = new QTreeView;
    QTextEdit *textedit = new QTextEdit;
    splitter->addWidget(listview);
    splitter->addWidget(treeview);
    splitter->addWidget(textedit);
```

如果一个小部件已经在 QSplitter 中[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（） 或者[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)() 被调用，它将移动到新的位置。这可用于稍后在拆分器中重新排序小部件。您可以使用[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)(),[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)（）， 和[count](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)() 来访问拆分器内的小部件。

默认的 QSplitter 水平布置其子级（并排）；您可以使用[setOrientation](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)（[Qt::Vertical](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)）将其子项垂直放置。

默认情况下，所有小部件都可以根据用户的意愿设置为大或小，介于[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)（） （或者[minimumSize](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize-prop)（）） 和[maximumSize](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSize-prop)() 的小部件。

默认情况下，QSplitter 会动态调整其子级的大小。如果您希望 QSplitter 仅在调整大小操作结束时调整子级的大小，请调用[setOpaqueResize](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueResize-prop)（错误的）。

小部件之间的初始大小分布是通过将初始大小乘以拉伸因子来确定的。您还可以使用[setSizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizes)() 设置所有小部件的大小。功能[sizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizes)() 返回用户设置的尺寸。或者，您可以从以下位置保存和恢复小部件的大小：[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用[saveState](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#saveState)（） 和[restoreState](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restoreState)（） 分别。

当你[hide](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)() 一个孩子，它的空间将分配给其他孩子。当您[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 再说一遍。

**注意：**添加一个[QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不支持 QSplitter（通过[setLayout](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)() 或使 QSplitter 成为[QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）；使用[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)() 代替（参见上面的示例）。

**也可以看看**[QSplitterHandle](https://doc-qt-io.translate.goog/qt-6/qsplitterhandle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QHBoxLayout](https://doc-qt-io.translate.goog/qt-6/qhboxlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QVBoxLayout](https://doc-qt-io.translate.goog/qt-6/qvboxlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTabWidget](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### childrenCollapsible : bool

该属性保存用户是否可以将子窗口小部件调整为大小 0

默认情况下，子项是可折叠的。可以使用以下命令启用和禁用单个子项的折叠[setCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCollapsible)()。

**访问功能：**

| bool | **childrenCollapsible**() const  |
| ---- | -------------------------------- |
| void | **setChildrenCollapsible**(bool) |

**也可以看看**[setCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCollapsible)()。

### handleWidth : int

该属性保存分割器手柄的宽度

默认情况下，此属性包含一个取决于用户平台和样式首选项的值。

如果将 handleWidth 设置为 1 或 0，则实际抓取区域将增长以重叠其各自小部件的几个像素。

**访问功能：**

| int  | **handleWidth**() const |
| ---- | ----------------------- |
| void | **setHandleWidth**(int) |

### opaqueResize : bool

返回`true`是否在交互式移动拆分器时动态（不透明）调整小部件的大小。否则返回`false`。

默认调整大小行为取决于样式（由 SH_Splitter_OpaqueResize 样式提示确定）。但是，您可以通过调用 setOpaqueResize() 来覆盖它

**访问功能：**

| bool | **opaqueResize**() const                  |
| ---- | ----------------------------------------- |
| void | **setOpaqueResize**(bool *opaque* = true) |

**也可以看看**[QStyle::StyleHint](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleHint-enum)。

### orientation : [Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)

该属性保存分离器的方向

默认情况下，方向是水平的（即，小部件并排布置）。可能的方向是[Qt::Horizontal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)和[Qt::Vertical](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)。

**访问功能：**

| Qt::Orientation | **orientation**() const             |
| --------------- | ----------------------------------- |
| void            | **setOrientation**(Qt::Orientation) |

**也可以看看**[QSplitterHandle::orientation](https://doc-qt-io.translate.goog/qt-6/qsplitterhandle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation)()。

## 成员函数文档

### `[explicit]`QSplitter::QSplitter([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个水平分离器*parent*论点传递给[QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[setOrientation](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)()。

### `[explicit]`QSplitter::QSplitter([Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个分离器*orientation*和*parent*。

**也可以看看**[setOrientation](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)()。

### `[virtual]`QSplitter::~QSplitter()

破坏分离器。所有子项均被删除。

### void QSplitter::addWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

添加给定的*widget*在所有其他项目之后的拆分器布局。

如果*widget*已在分离器中，它将被移动到新位置。

**注意：**拆分器拥有该小部件的所有权。

**也可以看看**[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)(),[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)（）， 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### `[override virtual protected]`void QSplitter::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QFrame::changeEvent](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *ev）。

### `[override virtual protected]`void QSplitter::childEvent([QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **c*)

重新实现：[QObject::childEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childEvent)（QChildEvent *事件）。

告诉分割器所描述的子部件*c*已被插入或移除。

此方法还用于处理使用拆分器作为父级创建小部件但未显式添加的情况[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（） 或者[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。这是为了兼容性，而不是将小部件放入新代码中的拆分器中的推荐方法。请用[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（） 或者[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)() 在新代码中。

**也可以看看**[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)（） 和[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)()。

### `[protected]`int QSplitter::closestLegalPosition(int *pos*, int *index*)

返回最接近的合法位置*pos*小部件的*index*。

对于从右到左的语言，例如阿拉伯语和希伯来语，水平分隔符的布局是相反的。然后从小部件的右边缘开始测量位置。

**也可以看看**[getRange](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getRange)()。

### int QSplitter::count() const

返回分割器布局中包含的小部件的数量。

**也可以看看**[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)（） 和[handle](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handle)()。

### `[virtual protected]`[QSplitterHandle](https://doc-qt-io.translate.goog/qt-6/qsplitterhandle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QSplitter::createHandle()

返回一个新的拆分器句柄作为该拆分器的子小部件。该函数可以在子类中重新实现，以提供对自定义句柄的支持。

**也可以看看**[handle](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handle)（） 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### `[override virtual protected]`bool QSplitter::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QFrame::event](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### void QSplitter::getRange(int *index*, int **min*, int **max*) const

返回分割器的有效范围*index*在 **min*和 **max*如果*min*和*max*不为 0。

### [QSplitterHandle](https://doc-qt-io.translate.goog/qt-6/qsplitterhandle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QSplitter::handle(int *index*) const

返回给定分配器布局中项目左侧（或上方）的句柄*index*，或者`nullptr`如果没有这样的项目。索引 0 处的句柄始终隐藏。

对于从右到左的语言，例如阿拉伯语和希伯来语，水平分隔符的布局是相反的。句柄将位于小部件的右侧*index*。

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)(),[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)(),[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)(),[createHandle](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createHandle)（）， 和[setHandleWidth](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handleWidth-prop)()。

### int QSplitter::indexOf([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*) const

返回指定拆分器布局中的索引*widget*，或 -1 如果*widget*没有找到。这也适用于手柄。

句柄从 0 开始编号。句柄的数量与子控件的数量一样多，但位置 0 处的句柄始终是隐藏的。

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)（） 和[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### void QSplitter::insertWidget(int *index*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

插入*widget*指定到给定分配器的布局中*index*。

如果*widget*已在分离器中，它将被移动到新位置。

如果*index*是无效索引，则小部件将被插入到末尾。

**注意：**拆分器拥有该小部件的所有权。

**也可以看看**[addWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)(),[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)（）， 和[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### bool QSplitter::isCollapsible(int *index*) const

`true`如果小部件位于*index*是可折叠的，否则返回`false`.

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QSplitter::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[protected]`void QSplitter::moveSplitter(int *pos*, int *index*)

将分割器手柄的左边缘或上边缘移动到*index*尽可能靠近位置*pos*，这是距小部件左边缘或上边缘的距离。

对于从右到左的语言，例如阿拉伯语和希伯来语，水平分隔符的布局是相反的。*pos*那么就是距小部件右边缘的距离。

**也可以看看**[splitterMoved](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#splitterMoved)(),[closestLegalPosition](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closestLegalPosition)（）， 和[getRange](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getRange)()。

### void QSplitter::refresh()

更新分离器的状态。您不需要调用此函数。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QSplitter::replaceWidget(int *index*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

替换给定分割器布局中的小部件*index*经过*widget*。

返回刚刚被替换的小部件，如果*index*是有效的并且*widget*还不是 splitter 的子级。否则，返回 null 并且不进行替换或添加。

新插入的小部件的几何形状将与其替换的小部件相同。它的可见和折叠状态也是继承的。

**注：**分离器拥有所有权*widget*并将替换的小部件的父级设置为 null。

**注：**因为*widget*得到[reparented](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParent)进入分离器，其[geometry](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#geometry-prop)可能不会立即设置，但只能在之后设置*widget*将收到适当的事件。

**也可以看看**[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（） 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### `[override virtual protected]`void QSplitter::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### bool QSplitter::restoreState(const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*state*)

将分离器的布局恢复为*state*指定的。`true`如果状态恢复则返回；否则返回`false`.

通常这与[QSettings](https://doc-qt-io.translate.goog/qt-6/qsettings.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)恢复过去会话的大小。这是一个例子：

恢复分离器的状态：

```
    QSettings settings;
    splitter->restoreState(settings.value("splitterSizes").toByteArray());
```

无法恢复拆分器的布局可能是由于所提供的字节数组中的数据无效或过时造成的。

**也可以看看**[saveState](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#saveState)()。

### [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QSplitter::saveState() const

保存分割器布局的状态。

通常这与[QSettings](https://doc-qt-io.translate.goog/qt-6/qsettings.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)记住该大小以供将来的会话使用。版本号作为数据的一部分存储。这是一个例子：

```
    QSettings settings;
    settings.setValue("splitterSizes", splitter->saveState());
```

**也可以看看**[restoreState](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restoreState)()。

### void QSplitter::setCollapsible(int *index*, bool *collapse*)

设置子部件是否位于*index*可以折叠到*collapse*。

默认情况下，子项是可折叠的，这意味着用户可以将它们的大小调整为 0，即使它们的大小非零[minimumSize](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize-prop)（） 或者[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)()。可以通过调用此函数在每个小部件的基础上更改此行为，或者通过设置拆分器中的所有小部件来全局更改此行为[childrenCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childrenCollapsible-prop)财产。

**也可以看看**[isCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isCollapsible)（） 和[childrenCollapsible](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childrenCollapsible-prop)。

### `[protected]`void QSplitter::setRubberBand(int *pos*)

在位置显示橡皮筋*pos*。如果*pos*为负值，橡皮筋被移除。

### void QSplitter::setSizes(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<int> &*list*)

将子窗口部件各自的大小设置为中给出的值*list*。

如果拆分器是水平的，则这些值设置每个小部件的宽度（以像素为单位），从左到右。如果拆分器是垂直的，则从上到下设置每个小部件的高度。

额外的价值*list*被忽略。如果*list*包含的值太少，结果是未定义的，但程序仍然会表现良好。

拆分器小部件的整体大小不受影响。相反，任何额外/缺失的空间都会根据尺寸的相对权重分布在小部件之间。

如果指定大小为 0，则小部件将不可见。保留小部件的大小策略。也就是说，小于相应小部件的最小尺寸提示的值将被提示的值替换。

**也可以看看**[sizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizes)()。

### void QSplitter::setStretchFactor(int *index*, int *stretch*)

更新位置小部件的大小策略*index*拉伸因子为*stretch*。

*stretch*不是有效拉伸因子；有效拉伸因子是通过获取小部件的初始大小并将其乘以来计算的*stretch*。

提供此功能是为了方便。它相当于

```
QWidget *widget = splitter->widget(index);
QSizePolicy policy = widget->sizePolicy();
policy.setHorizontalStretch(stretch);
policy.setVerticalStretch(stretch);
widget->setSizePolicy(policy);
```

**也可以看看**[setSizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizes)（） 和[widget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QSplitter::sizeHint() const

重新实现：[QFrame::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<int> QSplitter::sizes() const

返回此拆分器中所有小部件的大小参数的列表。

如果拆分器的方向是水平的，则列表从左到右包含以像素为单位的小部件宽度；如果方向是垂直的，则列表包含小部件从上到下的高度（以像素为单位）。

将值赋予另一个分离器[setSizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizes)() 函数将生成一个与此布局相同的拆分器。

请注意，不可见部件的大小为 0。

**也可以看看**[setSizes](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizes)()。

### `[signal]`void QSplitter::splitterMoved(int *pos*, int *index*)

当分离器手柄处于特定位置时会发出此信号*index*已移至位置*pos*。

对于从右到左的语言，例如阿拉伯语和希伯来语，水平分隔符的布局是相反的。*pos*那么就是距小部件右边缘的距离。

**也可以看看**[moveSplitter](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveSplitter)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QSplitter::widget(int *index*) const

返回给定位置的小部件*index*在分割器的布局中，或者`nullptr`如果没有这样的小部件。

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)(),[handle](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#handle)(),[indexOf](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)（）， 和[insertWidget](https://doc-qt-io.translate.goog/qt-6/qsplitter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)()。