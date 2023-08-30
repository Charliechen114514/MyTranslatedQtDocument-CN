 QCheckBox Class

QCheckBox 小部件提供了一个带有文本标签的复选框。[更多的...](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QCheckBox>                                         |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qcheckbox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[tristate](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tristate-prop)** : bool

## 公共方法

|                | **[QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QCheckBox)**(QWidget **parent* = nullptr) |
| -------------- | ------------------------------------------------------------ |
|                | **[QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QCheckBox-1)**(const QString &*text*, QWidget **parent* = nullptr) |
| virtual        | **[~QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QCheckBox)**() |
| Qt::CheckState | **[checkState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)**() const |
| bool           | **[isTristate](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tristate-prop)**() const |
| void           | **[setCheckState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckState)**(Qt::CheckState *state*) |
| void           | **[setTristate](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tristate-prop)**(bool *y* = true) |

## 重载的公共方法

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 信号

| void | **[stateChanged](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stateChanged)**(int *state*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected function

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionButton **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重载的protected function

| virtual void | **[checkStateSet](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkStateSet)**() override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual bool | **[hitButton](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hitButton)**(const QPoint &*pos*) const override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[nextCheckState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nextCheckState)**() override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent *) override |

## 详细说明

![img](https://doc.qt.io/qt-6/images/windows-checkbox.png)

QCheckBox 是一个选项按钮，可以打开（选中）或关闭（取消选中）。复选框通常用于表示应用程序中可以启用或禁用而不影响其他功能的功能。可以实施不同类型的行为。例如，一个[QButtonGroup](https://doc-qt-io.translate.goog/qt-6/qbuttongroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可用于对检查按钮进行逻辑分组，从而允许独占复选框。然而，[QButtonGroup](https://doc-qt-io.translate.goog/qt-6/qbuttongroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不提供任何视觉表示。

下图进一步说明了独占和非独占复选框之间的差异。

| ![img](https://doc.qt.io/qt-6/images/checkboxes-exclusive.png) | ![img](https://doc.qt.io/qt-6/images/checkboxes-non-exclusive.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

每当选中或清除复选框时，它都会发出信号[stateChanged](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stateChanged)()。如果您想在每次复选框更改状态时触发操作，请连接到此信号。您可以使用[isChecked](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)() 查询复选框是否被选中。

除了通常的选中和未选中状态之外，QCheckBox 还可以选择提供第三种状态来指示“无更改”。每当您需要为用户提供既不选中也不取消选中复选框的选项时，这非常有用。如果您需要第三种状态，请启用它[setTristate](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tristate-prop)()，并使用[checkState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)() 查询当前切换状态。

就像[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，复选框显示文本，还可以选择显示小图标。图标设置为[setIcon](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)()。文本可以在构造函数中设置或使用[setText](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()。可以通过在首选字符前加上 & 符号来指定快捷键。例如：

```
QCheckBox *checkbox = new QCheckBox("C&ase sensitive", this);
```

在此示例中，快捷键是*Alt+A*。请参阅[QShortcut](https://doc-qt-io.translate.goog/qt-6/qshortcut.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mnemonic)文档了解详细信息。要显示实际的 & 符号，请使用“&&”。

重要的继承函数：[text](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)(),[setText](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)(),[text](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()、pixmap()、setPixmap()、accel()、setAccel()、isToggleButton()、[setDown](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#down-prop)(),[isDown](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#down-prop)(), isOn(),[checkState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)(),[autoRepeat](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRepeat-prop)(), isExclusiveToggle(),[group](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)(),[setAutoRepeat](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRepeat-prop)(),[toggle](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toggle)(),[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)(),[released](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#released)(),[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)(),[toggled](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toggled)(),[checkState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)（）， 和[stateChanged](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stateChanged)()。

**也可以看看**[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QRadioButton](https://doc-qt-io.translate.goog/qt-6/qradiobutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 财产文件

### tristate : bool

该属性保存复选框是否为三态复选框

默认为 false，即复选框只有两种状态。

**访问功能：**

| bool | **isTristate**() const           |
| ---- | -------------------------------- |
| void | **setTristate**(bool *y* = true) |

## 成员函数文档

### `[explicit]`QCheckBox::QCheckBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个复选框*parent*，但没有文字。

*parent*被传递到[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

### `[explicit]`QCheckBox::QCheckBox(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个复选框*parent*和*text*。

*parent*被传递到[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

### `[virtual]`QCheckBox::~QCheckBox()

析构函数。

### [Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum) QCheckBox::checkState() const

返回复选框的选中状态。如果不需要三态支持，也可以使用[QAbstractButton::isChecked](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)()，返回一个布尔值。

**也可以看看**[setCheckState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckState)（） 和[Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum)。

### `[override virtual protected]`void QCheckBox::checkStateSet()

重新实现：[QAbstractButton::checkStateSet](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkStateSet)()。

### `[override virtual protected]`bool QCheckBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::event](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### `[override virtual protected]`bool QCheckBox::hitButton(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

重新实现：[QAbstractButton::hitButton(const QPoint &pos) const](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hitButton)。

### `[virtual protected]`void QCheckBox::initStyleOption([QStyleOptionButton](https://doc-qt-io.translate.goog/qt-6/qstyleoptionbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。此方法对于需要的子类很有用[QStyleOptionButton](https://doc-qt-io.translate.goog/qt-6/qstyleoptionbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但又不想自己填写所有信息。

**也可以看看**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCheckBox::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[override virtual protected]`void QCheckBox::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QCheckBox::nextCheckState()

重新实现：[QAbstractButton::nextCheckState](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nextCheckState)()。

### `[override virtual protected]`void QCheckBox::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QAbstractButton::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *e）。

### void QCheckBox::setCheckState([Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum) *state*)

将复选框的选中状态设置为*state*。如果不需要三态支持，也可以使用[QAbstractButton::setChecked](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)()，它接受一个布尔值。

**也可以看看**[checkState](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)（） 和[Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCheckBox::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。

### `[signal]`void QCheckBox::stateChanged(int *state*)

每当复选框的状态改变时，即每当用户选中或取消选中它时，都会发出此信号。

*state*包含复选框的新内容[Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum)。