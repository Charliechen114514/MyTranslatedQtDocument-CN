 

# QScrollArea Class

QScrollArea 类提供了另一个小部件的滚动视图。[更多的...](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QScrollArea>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qscrollarea-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[alignment](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)** : Qt::Alignment
- **[widgetResizable](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widgetResizable-prop)** : bool

## 公共职能

|               | **[QScrollArea](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QScrollArea)**(QWidget **parent* = nullptr) |
| ------------- | ------------------------------------------------------------ |
| virtual       | **[~QScrollArea](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QScrollArea)**() |
| Qt::Alignment | **[alignment](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**() const |
| void          | **[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)**(int *x*, int *y*, int *xmargin* = 50, int *ymargin* = 50) |
| void          | **[ensureWidgetVisible](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureWidgetVisible)**(QWidget **childWidget*, int *xmargin* = 50, int *ymargin* = 50) |
| void          | **[setAlignment](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**(Qt::Alignment) |
| void          | **[setWidget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)**(QWidget **widget*) |
| void          | **[setWidgetResizable](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widgetResizable-prop)**(bool *resizable*) |
| QWidget *     | **[takeWidget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeWidget)**() |
| QWidget *     | **[widget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)**() const |
| bool          | **[widgetResizable](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widgetResizable-prop)**() const |

## 重载的公共职能

| virtual bool  | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 重载的protected function

| virtual bool  | **[event](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------- | ------------------------------------------------------------ |
| virtual bool  | **[eventFilter](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)**(QObject **o*, QEvent **e*) override |
| virtual void  | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent *) override |
| virtual void  | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual QSize | **[viewportSizeHint](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)**() const override |

## 详细说明

滚动区域用于显示框架内子部件的内容。如果小部件超出了框架的大小，视图可以提供滚动条，以便可以查看子小部件的整个区域。子部件必须指定为[setWidget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。例如：

```
QLabel *imageLabel = new QLabel;
QImage image("happyguy.png");
imageLabel->setPixmap(QPixmap::fromImage(image));

scrollArea = new QScrollArea;
scrollArea->setBackgroundRole(QPalette::Dark);
scrollArea->setWidget(imageLabel);
```

上面的代码创建了一个包含图像标签的滚动区域（如下图所示）。缩放图像时，滚动区域可以提供必要的滚动条：

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\S\QScrollArea\QScrollArea\qscrollarea-noscrollbars.png) | ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\S\QScrollArea\QScrollArea\qscrollarea-onescrollbar.png) | ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\S\QScrollArea\QScrollArea\qscrollarea-twoscrollbars.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |                                                              |

滚动条的外观取决于当前设置[scroll bar policies](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollBarPolicy-enum)。您可以使用继承的功能来控制滚动条的外观[QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

例如，您可以设置[QAbstractScrollArea::horizontalScrollBarPolicy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollBarPolicy-prop)和[QAbstractScrollArea::verticalScrollBarPolicy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollBarPolicy-prop)特性。或者如果您希望滚动条在滚动区域的内容发生变化时动态调整，您可以使用[horizontalScrollBar](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollBar)（） 和[verticalScrollBar](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollBar)() 函数（使您能够访问滚动条）并在滚动区域的内容发生更改时设置滚动条的值，使用[QScrollBar::setValue](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)（） 功能。

您可以使用以下方法检索子小部件[widget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)（） 功能。可以使用以下命令调整视图的大小[setWidgetResizable](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widgetResizable-prop)（） 功能。小部件的对齐方式可以通过指定[setAlignment](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)()。

两个便利功能[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)（） 和[ensureWidgetVisible](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureWidgetVisible)() 确保内容的某个区域在视口内可见，必要时可滚动内容。

### 尺寸提示和布局

当使用滚动区域显示自定义小部件的内容时，重要的是要确保滚动区域[size hint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)子部件的值被设置为合适的值。如果有一个标准[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于子部件，可能需要调用[QWidget::setMinimumSize](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize-prop)() 确保小部件的内容在滚动区域内正确显示。

如果滚动区域用于显示包含排列在布局中的子窗口小部件的窗口小部件的内容，则重要的是要认识到布局的大小策略也将确定窗口小部件的大小。这对于了解您是否打算动态更改布局的内容特别有用。在这种情况下，设置布局[size constraint](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeConstraint-prop)属性对布局的最小和/或最大尺寸提供约束（例如，[QLayout::SetMinAndMaxSize](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SizeConstraint-enum)）将导致滚动区域的大小在布局内容发生变化时更新。

有关使用 QScrollArea 类的完整示例，请参阅[Image Viewer](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-imageviewer-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)例子。该示例展示了如何组合[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和 QScrollArea 来显示图像。

**也可以看看**[QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QScrollBar](https://doc-qt-io.translate.goog/qt-6/qscrollbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Image Viewer Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-imageviewer-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### alignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

该属性保存滚动区域小部件的对齐方式

有效的对齐方式是以下标志的组合：

- `Qt::AlignLeft`
- `Qt::AlignHCenter`
- `Qt::AlignRight`
- `Qt::AlignTop`
- `Qt::AlignVCenter`
- `Qt::AlignBottom`

默认情况下，小部件保持在滚动区域的左上角。

**访问功能：**

| Qt::Alignment | **alignment**() const           |
| ------------- | ------------------------------- |
| void          | **setAlignment**(Qt::Alignment) |

### widgetResizable : bool

该属性保存滚动区域是否应该调整视图小部件的大小

如果此属性设置为 false（默认值），则滚动区域将遵循其小部件的大小。无论此属性如何，您都可以使用以下方式以编程方式调整小部件的大小[widget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()->[resize](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)()，滚动区域会自动调整到新的大小。

如果此属性设置为 true，则滚动区域将自动调整小部件的大小，以避免可以避免的滚动条，或利用额外的空间。

**访问功能：**

| bool | **widgetResizable**() const              |
| ---- | ---------------------------------------- |
| void | **setWidgetResizable**(bool *resizable*) |

## 成员函数文档

### `[explicit]`QScrollArea::QScrollArea([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个空的滚动区域*parent*。

**也可以看看**[setWidget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。

### `[virtual]`QScrollArea::~QScrollArea()

销毁滚动区域及其子部件。

**也可以看看**[setWidget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。

### void QScrollArea::ensureVisible(int *x*, int *y*, int *xmargin* = 50, int *ymargin* = 50)

滚动滚动区域的内容，以便点 (*x*,*y*) 在视口区域内可见，其边距以像素为单位指定*xmargin*和*ymargin*。如果无法到达指定点，内容将滚动到最近的有效位置。两个边距的默认值为 50 像素。

### void QScrollArea::ensureWidgetVisible([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **childWidget*, int *xmargin* = 50, int *ymargin* = 50)

滚动滚动区域的内容，以便*childWidget*的[QScrollArea::widget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)() 在视口内可见，其边距以像素为单位指定*xmargin*和*ymargin*。如果无法到达指定点，内容将滚动到最近的有效位置。两个边距的默认值为 50 像素。

### `[override virtual protected]`bool QScrollArea::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::event](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`bool QScrollArea::eventFilter([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **o*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QObject::eventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)（QObject *观看，QEvent *事件）。

### `[override virtual]`bool QScrollArea::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QScrollArea::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QAbstractScrollArea::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[override virtual protected]`void QScrollArea::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

### void QScrollArea::setWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

设置滚动区域*widget*。

这*widget*成为滚动区域的子级，并且当删除滚动区域或设置新的小部件时将被销毁。

小部件的[autoFillBackground](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFillBackground-prop)属性将被设置为`true`.

如果滚动区域在*widget*添加后，您必须[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 明确表示。

请注意，您必须添加以下布局*widget*在调用此函数之前；如果您稍后添加它，*widget*将不可见 - 无论您何时[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 滚动区域。在这种情况下，您也可以不[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)（） 这*widget*之后。

**也可以看看**[widget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QScrollArea::sizeHint() const

重新实现：[QAbstractScrollArea::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QScrollArea::takeWidget()

删除滚动区域的小部件，并将小部件的所有权传递给调用者。

**也可以看看**[widget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### `[override virtual protected]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QScrollArea::viewportSizeHint() const

重新实现：[QAbstractScrollArea::viewportSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportSizeHint)。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QScrollArea::widget() const

返回滚动区域的小部件，或者`nullptr`如果没有则返回。

**也可以看看**[setWidget](https://doc-qt-io.translate.goog/qt-6/qscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。