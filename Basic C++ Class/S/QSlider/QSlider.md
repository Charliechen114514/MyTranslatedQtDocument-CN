 QSlider Class

QSlider 小部件提供垂直或水平滑块。[更多的...](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QSlider>                                           |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractSlider](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qslider-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[TickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TickPosition-enum)** { NoTicks, TicksBothSides, TicksAbove, TicksBelow, TicksLeft, TicksRight } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 特性

- **[tickInterval](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickInterval-prop)** : int
- **[tickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickPosition-prop)** : TickPosition

## 公共职能

|                       | **[QSlider](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QSlider)**(QWidget **parent* = nullptr) |
| --------------------- | ------------------------------------------------------------ |
|                       | **[QSlider](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QSlider-1)**(Qt::Orientation *orientation*, QWidget **parent* = nullptr) |
| virtual               | **[~QSlider](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QSlider)**() |
| void                  | **[setTickInterval](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickInterval-prop)**(int *ti*) |
| void                  | **[setTickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickPosition-prop)**(QSlider::TickPosition *position*) |
| int                   | **[tickInterval](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickInterval-prop)**() const |
| QSlider::TickPosition | **[tickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickPosition-prop)**() const |

## 重载的公共职能

| virtual bool  | **[event](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## protected功能

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionSlider **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重载的protected功能

| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **ev*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **ev*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **ev*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **ev*) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\S\QSlider\QSlider\windows-slider.png)

滑块是用于控制有界值的经典小部件。它允许用户沿着水平或垂直凹槽移动滑块手柄，并将手柄的位置转换为合法范围内的整数值。

QSlider本身的功能很少；大部分功能都在[QAbstractSlider](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。最有用的功能是[setValue](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)() 将滑块直接设置为某个值；[triggerAction](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#triggerAction)() 模拟点击的效果（对快捷键有用）；[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)(),[setPageStep](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageStep-prop)() 设置步骤；和[setMinimum](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（） 和[setMaximum](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)() 定义滚动条的范围。

QSlider 提供了控制刻度线的方法。您可以使用[setTickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickPosition-prop)() 指示您想要刻度线的位置，[setTickInterval](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickInterval-prop)() 表示您想要多少个。可以使用以下命令查询当前设置的刻度位置和间隔[tickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickPosition-prop)（） 和[tickInterval](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickInterval-prop)() 函数分别。

QSlider继承了一套全面的信号：

|                             信号                             |                             描述                             |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [valueChanged](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)() | 当滑块的值发生更改时发出。Tracking() 确定在用户交互期间是否发出该信号。 |
| [sliderPressed](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliderPressed)() |                  当用户开始拖动滑块时发出。                  |
| [sliderMoved](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliderMoved)() |                    当用户拖动滑块时发出。                    |
| [sliderReleased](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sliderReleased)() |                    当用户释放滑块时发出。                    |

QSlider 仅提供整数范围。请注意，虽然 QSlider 可以处理非常大的数字，但用户很难在非常大的范围内准确地使用滑块。

滑块接受 Tab 上的焦点并提供鼠标滚轮和键盘界面。键盘接口如下：

- 向左/向右将水平滑块移动一步。
- 向上/向下将垂直滑块移动一步。
- PageUp 向上移动一页。
- PageDown 向下移动一页。
- Home 移动到开头（最小）。
- End 移动到末尾（最大）。

**也可以看看**[QScrollBar](https://doc-qt-io.translate.goog/qt-6/qscrollbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QSpinBox](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDial](https://doc-qt-io.translate.goog/qt-6/qdial.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Sliders Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-sliders-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QSlider::TickPosition

该枚举指定相对于滑块凹槽和用户移动手柄的刻度线的绘制位置。

| 持续的                    | 价值         | 描述                         |
| ------------------------- | ------------ | ---------------------------- |
| `QSlider::NoTicks`        | `0`          | 不要画任何刻度线。           |
| `QSlider::TicksBothSides` | `3`          | 在凹槽两侧画刻度线。         |
| `QSlider::TicksAbove`     | `1`          | 在（水平）滑块上方绘制刻度线 |
| `QSlider::TicksBelow`     | `2`          | 在（水平）滑块下方绘制刻度线 |
| `QSlider::TicksLeft`      | `TicksAbove` | 在（垂直）滑块左侧绘制刻度线 |
| `QSlider::TicksRight`     | `TicksBelow` | 在（垂直）滑块右侧绘制刻度线 |

## 属性文档

### tickInterval : int

该属性保存刻度线之间的间隔

这是一个值间隔，而不是像素间隔。如果为 0，滑块将在 singleStep 和 pageStep 之间进行选择。

默认值为 0。

**访问功能：**

| int  | **tickInterval**() const      |
| ---- | ----------------------------- |
| void | **setTickInterval**(int *ti*) |

**也可以看看**[tickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickPosition-prop),[singleStep](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)， 和[pageStep](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageStep-prop)。

### tickPosition : [TickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TickPosition-enum)

该属性保存该滑块的刻度线位置

有效值由以下描述[QSlider::TickPosition](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TickPosition-enum)枚举。

默认值为[QSlider::NoTicks](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TickPosition-enum)。

**访问功能：**

| QSlider::TickPosition | **tickPosition**() const                              |
| --------------------- | ----------------------------------------------------- |
| void                  | **setTickPosition**(QSlider::TickPosition *position*) |

**也可以看看**[tickInterval](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tickInterval-prop)。

## 成员函数文档

### `[explicit]`QSlider::QSlider([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个垂直滑块*parent*。

### `[explicit]`QSlider::QSlider([Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个滑块*parent*。这*orientation*参数决定滑块是水平还是垂直；有效值为[Qt::Vertical](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)和[Qt::Horizontal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)。

### `[virtual]`QSlider::~QSlider()

销毁该滑块。

### `[override virtual]`bool QSlider::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSlider::event](https://doc-qt-io.translate.goog/qt-6/qabstractslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### `[virtual protected]`void QSlider::initStyleOption([QStyleOptionSlider](https://doc-qt-io.translate.goog/qt-6/qstyleoptionslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QSlider](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionSlider](https://doc-qt-io.translate.goog/qt-6/qstyleoptionslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**也可以看看**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QSlider::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[override virtual protected]`void QSlider::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QSlider::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QSlider::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QSlider::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QSlider::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。