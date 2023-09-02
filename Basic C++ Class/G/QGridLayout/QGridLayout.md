# QGridLayout Class

QGridLayout 类在网格中布置小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QGridLayout>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qgridlayout-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)** : int
- **[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)** : int

## 公共职能

|               | **[QGridLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGridLayout)**(QWidget **parent* = nullptr) |
| ------------- | ------------------------------------------------------------ |
| virtual       | **[~QGridLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QGridLayout)**() |
| void          | **[addItem](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)**(QLayoutItem **item*, int *row*, int *column*, int *rowSpan* = 1, int *columnSpan* = 1, Qt::Alignment *alignment* = Qt::Alignment()) |
| void          | **[addLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLayout)**(QLayout **layout*, int *row*, int *column*, Qt::Alignment *alignment* = Qt::Alignment()) |
| void          | **[addLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLayout-1)**(QLayout **layout*, int *row*, int *column*, int *rowSpan*, int *columnSpan*, Qt::Alignment *alignment* = Qt::Alignment()) |
| void          | **[addWidget](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget-1)**(QWidget **widget*, int *row*, int *column*, Qt::Alignment *alignment* = Qt::Alignment()) |
| void          | **[addWidget](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget-2)**(QWidget **widget*, int *fromRow*, int *fromColumn*, int *rowSpan*, int *columnSpan*, Qt::Alignment *alignment* = Qt::Alignment()) |
| QRect         | **[cellRect](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cellRect)**(int *row*, int *column*) const |
| int           | **[columnCount](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnCount)**() const |
| int           | **[columnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnMinimumWidth)**(int *column*) const |
| int           | **[columnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnStretch)**(int *column*) const |
| void          | **[getItemPosition](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getItemPosition)**(int *index*, int **row*, int **column*, int **rowSpan*, int **columnSpan*) const |
| int           | **[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)**() const |
| QLayoutItem * | **[itemAtPosition](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAtPosition)**(int *row*, int *column*) const |
| Qt::Corner    | **[originCorner](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#originCorner)**() const |
| int           | **[rowCount](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)**() const |
| int           | **[rowMinimumHeight](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowMinimumHeight)**(int *row*) const |
| int           | **[rowStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowStretch)**(int *row*) const |
| void          | **[setColumnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnMinimumWidth)**(int *column*, int *minSize*) |
| void          | **[setColumnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnStretch)**(int *column*, int *stretch*) |
| void          | **[setHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)**(int *spacing*) |
| void          | **[setOriginCorner](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOriginCorner)**(Qt::Corner *corner*) |
| void          | **[setRowMinimumHeight](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowMinimumHeight)**(int *row*, int *minSize*) |
| void          | **[setRowStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowStretch)**(int *row*, int *stretch*) |
| void          | **[setVerticalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)**(int *spacing*) |
| int           | **[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)**() const |

## 重载的公共职能

| virtual int              | **[count](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**() const override |
| ------------------------ | ------------------------------------------------------------ |
| virtual Qt::Orientations | **[expandingDirections](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandingDirections)**() const override |
| virtual bool             | **[hasHeightForWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasHeightForWidth)**() const override |
| virtual int              | **[heightForWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#heightForWidth)**(int *w*) const override |
| virtual void             | **[invalidate](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)**() override |
| virtual QLayoutItem *    | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)**(int *index*) const override |
| virtual QSize            | **[maximumSize](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSize)**() const override |
| virtual int              | **[minimumHeightForWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumHeightForWidth)**(int *w*) const override |
| virtual QSize            | **[minimumSize](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize)**() const override |
| virtual void             | **[setGeometry](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGeometry)**(const QRect &*rect*) override |
| virtual void             | **[setSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpacing)**(int *spacing*) override |
| virtual QSize            | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| virtual int              | **[spacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing)**() const override |
| virtual QLayoutItem *    | **[takeAt](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeAt)**(int *index*) override |

## 重载的受保护的功能

| virtual void | **[addItem](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem-1)**(QLayoutItem **item*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

QGridLayout 获取可用的空间（通过其父布局或通过[parentWidget](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentWidget)())，将其分为行和列，并将其管理的每个小部件放入正确的单元格中。

列和行的行为相同；我们将讨论列，但行也有等效的函数。

每列都有一个最小宽度和一个拉伸因子。最小宽度是该组中最大的，使用[setColumnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnMinimumWidth)() 以及该列中每个小部件的最小宽度。拉伸因子设置为[setColumnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnStretch)() 并确定该列将获得多少可用空间超过其必要的最小值。

通常，每个托管小部件或布局都使用以下方式放入其自己的单元格中[addWidget](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget-1)()。小部件也可以使用行和列跨越重载来占据多个单元格[addItem](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（） 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget-1)()。如果这样做，QGridLayout 将猜测如何在列/行上分配大小（基于拉伸因子）。

要从布局中删除小部件，请调用[removeWidget](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeWidget)()。呼唤[QWidget::hide](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)小部件上的 () 还可以有效地将小部件从布局中删除，直到[QWidget::show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)（） 叫做。

下图显示了带有五列三行网格的对话框片段（网格以洋红色覆盖）：

![网格布局](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\G\QGridLayout\QGridLayout\qgridlayout.png)

该对话框片段中的第 0、2 和 4 列由[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， A[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和一个 QListBox。第 1 列和第 3 列是由以下内容组成的占位符[setColumnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnMinimumWidth)()。第 0 行由三个组成[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，第 1 行（共 3 个）[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象和三个 QListBox 对象的第 2 行。我们使用占位符列（1 和 3）来获得列之间的适当空间量。

请注意，列和行的宽度或高度并不相同。如果您希望两列具有相同的宽度，则必须自行将它们的最小宽度和拉伸因子设置为相同。你这样做使用[setColumnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnMinimumWidth)（） 和[setColumnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnStretch)()。

如果 QGridLayout 不是顶级布局（即不管理所有小部件的区域和子级），则必须在创建它时将其添加到其父布局，但在对其执行任何操作之前。添加布局的正常方法是调用[addLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLayout)() 在父布局上。

添加布局后，您可以开始使用以下命令将小部件和其他布局放入网格布局的单元格中[addWidget](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget-1)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLayout)()。

QGridLayout 还包括两个边距宽度：[contents margin](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getContentsMargins)和[spacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing)()。内容边距是沿 QGridLayout 四个边的保留空间的宽度。这[spacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing)() 是相邻框之间自动分配的间距的宽度。

默认内容边距值由[style](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pixelMetric)。Qt 样式指定的默认值对于子窗口小部件是 9，对于窗口是 11。间距默认与顶级布局的边距宽度相同，或者与父布局相同。

**也可以看看**[QBoxLayout](https://doc-qt-io.translate.goog/qt-6/qboxlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QStackedLayout](https://doc-qt-io.translate.goog/qt-6/qstackedlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Layout Management](https://doc-qt-io.translate.goog/qt-6/layout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Basic Layouts Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-layouts-basiclayouts-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### horizontalSpacing : int

该属性保存并排放置的小部件之间的间距

如果未显式设置值，则布局的水平间距将从父布局或父窗口小部件的样式设置继承。

**访问功能：**

| int  | **horizontalSpacing**() const           |
| ---- | --------------------------------------- |
| void | **setHorizontalSpacing**(int *spacing*) |

**也可以看看**[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop),[QStyle::pixelMetric](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pixelMetric)（）， 和[PM_LayoutHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixelMetric-enum)。

### verticalSpacing : int

该属性保存相互叠放的小部件之间的间距

如果未显式设置值，则布局的垂直间距将从父布局或父窗口小部件的样式设置继承。

**访问功能：**

| int  | **verticalSpacing**() const           |
| ---- | ------------------------------------- |
| void | **setVerticalSpacing**(int *spacing*) |

**也可以看看**[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop),[QStyle::pixelMetric](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pixelMetric)（）， 和[PM_LayoutHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixelMetric-enum)。

## 成员函数文档

### `[explicit]`QGridLayout::QGridLayout([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **parent* = nullptr)

使用父窗口小部件构造一个新的 QGridLayout，*parent*。布局最初为一行一列，当插入新项目时将扩展。

该布局直接设置为顶层布局*parent*。一个小部件只能有一个顶级布局。它由以下方式返回[QWidget::layout](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layout)()。

如果*parent*是`nullptr`，那么您必须将此网格布局插入到另一个布局中，或者使用以下命令将其设置为小部件的布局[QWidget::setLayout](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)()。

**也可以看看**[QWidget::setLayout](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)()。

### `[virtual]`QGridLayout::~QGridLayout()

破坏网格布局。如果这是顶级网格，则终止几何管理。

布局的小部件不会被破坏。

### void QGridLayout::addItem([QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) **item*, int *row*, int *column*, int *rowSpan* = 1, int *columnSpan* = 1, [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *alignment* = Qt::Alignment())

添加*item*在位置*row*,*column*, 跨越*rowSpan*行和*columnSpan*列，并根据*alignment*。如果*rowSpan*和/或*columnSpan*为 -1，则该项目将分别延伸到底部和/或右边缘。布局拥有所有权*item*。

**警告：**请勿使用此功能添加子布局或子小部件项目。使用[addLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLayout)（） 或者[addWidget](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget-1)（） 反而。

### `[override virtual protected]`void QGridLayout::addItem([QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) **item*)

重新实现：[QLayout::addItem](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（QLayoutItem *项目）。

### void QGridLayout::addLayout([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*, int *row*, int *column*, [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *alignment* = Qt::Alignment())

放置*layout*在位置 (*row*,*column*）在网格中。左上角位置是 (0, 0)。

对齐方式由以下方式指定*alignment*。默认对齐方式为 0，这意味着小部件填充整个单元格。

非零对齐表示布局不应增长以填充可用空间，而应根据[sizeHint](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)()。

*layout*成为网格布局的子级。

### void QGridLayout::addLayout([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*, int *row*, int *column*, int *rowSpan*, int *columnSpan*, [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *alignment* = Qt::Alignment())

这是一个过载功能。

这个版本增加了布局*layout*到单元格网格，跨越多行/列。单元格将开始于*row*,*column*跨越*rowSpan*行和*columnSpan*列。

如果*rowSpan*和/或*columnSpan*为 -1，则布局将分别延伸到底部和/或右边缘。

### void QGridLayout::addWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*, int *row*, int *column*, [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *alignment* = Qt::Alignment())

添加给定的*widget*到单元格网格*row*,*column*。默认情况下左上角位置为 (0, 0)。

对齐方式由以下方式指定*alignment*。默认对齐方式为 0，这意味着小部件填充整个单元格。

### void QGridLayout::addWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*, int *fromRow*, int *fromColumn*, int *rowSpan*, int *columnSpan*, [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *alignment* = Qt::Alignment())

这是一个过载功能。

该版本添加了给定的*widget*到单元格网格，跨越多行/列。单元格将开始于*fromRow*,*fromColumn*跨越*rowSpan*行和*columnSpan*列。这*widget*将有给定的*alignment*。

如果*rowSpan*和/或*columnSpan*为 -1，则小部件将分别延伸到底部和/或右边缘。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGridLayout::cellRect(int *row*, int *column*) const

返回带有行的单元格的几何形状*row*和列*column*在网格中。如果出现以下情况，则返回无效矩形*row*或者*column*位于网格之外。

**警告：**在当前版本的 Qt 中，此函数不会返回有效结果，直到[setGeometry](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGeometry)() 已被调用，即在[parentWidget](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentWidget)() 可见。

### int QGridLayout::columnCount() const

返回此网格中的列数。

### int QGridLayout::columnMinimumWidth(int *column*) const

返回列的列间距*column*。

**也可以看看**[setColumnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnMinimumWidth)()。

### int QGridLayout::columnStretch(int *column*) const

返回列的拉伸因子*column*。

**也可以看看**[setColumnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnStretch)()。

### `[override virtual]`int QGridLayout::count() const

重新实现：[QLayout::count() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)。

### `[override virtual]`[Qt::Orientations](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) QGridLayout::expandingDirections() const

重新实现：[QLayout::expandingDirections() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandingDirections)。

### void QGridLayout::getItemPosition(int *index*, int **row*, int **column*, int **rowSpan*, int **columnSpan*) const

返回给定项目的位置信息*index*。

传递的变量为*row*和*column*更新项目在布局中的位置，并且*rowSpan*和*columnSpan*变量随项目的垂直和水平跨度更新。

**也可以看看**[itemAtPosition](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAtPosition)（） 和[itemAt](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)()。

### `[override virtual]`bool QGridLayout::hasHeightForWidth() const

重新实现：[QLayoutItem::hasHeightForWidth() const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasHeightForWidth)。

### `[override virtual]`int QGridLayout::heightForWidth(int *w*) const

重新实现：[QLayoutItem::heightForWidth(int) const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#heightForWidth)。

### `[override virtual]`void QGridLayout::invalidate()

重新实现：[QLayout::invalidate](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)()。

### `[override virtual]`[QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) *QGridLayout::itemAt(int *index*) const

重新实现：[QLayout::itemAt(int index) const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)。

### [QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) *QGridLayout::itemAtPosition(int *row*, int *column*) const

返回占据单元格的布局项（*row*,*column*)，或者`nullptr`如果单元格为空。

**也可以看看**[getItemPosition](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getItemPosition)（） 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGridLayout::maximumSize() const

重新实现：[QLayout::maximumSize() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSize)。

### `[override virtual]`int QGridLayout::minimumHeightForWidth(int *w*) const

重新实现：[QLayoutItem::minimumHeightForWidth(int w) const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumHeightForWidth)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGridLayout::minimumSize() const

重新实现：[QLayout::minimumSize() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize)。

### [Qt::Corner](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Corner-enum) QGridLayout::originCorner() const

返回用于网格原点的角点，即位置 (0, 0)。

**也可以看看**[setOriginCorner](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOriginCorner)()。

### int QGridLayout::rowCount() const

返回此网格中的行数。

### int QGridLayout::rowMinimumHeight(int *row*) const

返回行设置的最小宽度*row*。

**也可以看看**[setRowMinimumHeight](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowMinimumHeight)()。

### int QGridLayout::rowStretch(int *row*) const

返回行的拉伸因子*row*。

**也可以看看**[setRowStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowStretch)()。

### void QGridLayout::setColumnMinimumWidth(int *column*, int *minSize*)

设置列的最小宽度*column*到*minSize*像素。

**也可以看看**[columnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnMinimumWidth)（） 和[setRowMinimumHeight](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowMinimumHeight)()。

### void QGridLayout::setColumnStretch(int *column*, int *stretch*)

设置列的拉伸因子*column*到*stretch*。第一列是数字 0。

拉伸因子是相对于该网格中的其他列而言的。拉伸系数较高的列会占用更多的可用空间。

默认拉伸因子为 0。如果拉伸因子为 0 并且此表中的其他列根本无法增长，则该列可能仍会增长。

另一种方法是使用添加间距[addItem](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)() 与[QSpacerItem](https://doc-qt-io.translate.goog/qt-6/qspaceritem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[columnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnStretch)（） 和[setRowStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowStretch)()。

### `[override virtual]`void QGridLayout::setGeometry(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

重新实现：[QLayout::setGeometry](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGeometry)（常量 QRect &r）。

### void QGridLayout::setOriginCorner([Qt::Corner](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Corner-enum) *corner*)

设置网格的原点角点，即位置 (0, 0)，为*corner*。

**也可以看看**[originCorner](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#originCorner)()。

### void QGridLayout::setRowMinimumHeight(int *row*, int *minSize*)

设置行的最小高度*row*到*minSize*像素。

**也可以看看**[rowMinimumHeight](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowMinimumHeight)（） 和[setColumnMinimumWidth](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnMinimumWidth)()。

### void QGridLayout::setRowStretch(int *row*, int *stretch*)

设置行的拉伸因子*row*到*stretch*。第一行是数字 0。

拉伸因子是相对于该网格中的其他行的。拉伸因子较高的行占用更多的可用空间。

默认拉伸因子为 0。如果拉伸因子为 0 并且此表中的其他行根本无法增长，则该行仍可能增长。

**也可以看看**[rowStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowStretch)(),[setRowMinimumHeight](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowMinimumHeight)（）， 和[setColumnStretch](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColumnStretch)()。

### `[override virtual]`void QGridLayout::setSpacing(int *spacing*)

重新实现属性的访问函数：[QLayout::spacing](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)。

该函数将垂直和水平间距设置为*spacing*。

**也可以看看**[spacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing)(),[setVerticalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)（）， 和[setHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGridLayout::sizeHint() const

重新实现：[QLayoutItem::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### `[override virtual]`int QGridLayout::spacing() const

重新实现属性的访问函数：[QLayout::spacing](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)。

如果垂直间距等于水平间距，则该函数返回该值；否则返回-1。

**也可以看看**[setSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpacing)(),[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)（）， 和[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)()。

### `[override virtual]`[QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) *QGridLayout::takeAt(int *index*)

重新实现：[QLayout::takeAt](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeAt)（整数索引）。