 QPushButton Class

QPushButton 小部件提供了一个命令按钮。[更多的...](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QPushButton>                                      |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QCommandLinkButton](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qpushbutton-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)** : bool
- **[default](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)** : bool
- **[flat](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)** : bool

## 公共函数

|         | **[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPushButton)**(QWidget **parent* = nullptr) |
| ------- | ------------------------------------------------------------ |
|         | **[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPushButton-1)**(const QString &*text*, QWidget **parent* = nullptr) |
|         | **[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPushButton-2)**(const QIcon &*icon*, const QString &*text*, QWidget **parent* = nullptr) |
| virtual | **[~QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QPushButton)**() |
| bool    | **[autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)**() const |
| bool    | **[isDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)**() const |
| bool    | **[isFlat](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)**() const |
| QMenu * | **[menu](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#menu)**() const |
| void    | **[setAutoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)**(bool) |
| void    | **[setDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)**(bool) |
| void    | **[setFlat](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)**(bool) |
| void    | **[setMenu](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMenu)**(QMenu **menu*) |

## 重载的公共方法

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共槽

| void | **[showMenu](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showMenu)**() |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected 函数

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionButton **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重载的protected 函数

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **e*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **e*) override |
| virtual bool | **[hitButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hitButton)**(const QPoint &*pos*) const override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent *) override |

## 详细说明

​		按钮或命令按钮可能是任何图形用户界面中最常用的小部件。按下（单击）按钮可命令计算机执行某些操作或回答问题。典型的按钮有“确定”、“应用”、“取消”、“关闭”、“是”、“否”和“帮助”。

​		命令按钮是矩形的，通常显示描述其操作的文本标签。可以通过在文本中在首选字符前加上 & 符号来指定快捷键。例如：

```
QPushButton *button = new QPushButton("&Download", this);
```

​		在此示例中，快捷键是*Alt+D*。请参阅[QShortcut](https://doc-qt-io.translate.goog/qt-6/qshortcut.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mnemonic)有关详细信息的文档（要显示实际的＆符号，请使用“&&”）。

​		按钮显示文本标签，还可以选择显示小图标。这些可以使用构造函数进行设置，并稍后使用进行更改[setText](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 和[setIcon](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)()。如果按钮被禁用，则文本和图标的外观将根据 GUI 样式进行操作，以使按钮看起来“禁用”。

​		按钮发出信号[clicked](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)() 当通过鼠标、空格键或键盘快捷键激活时。连接到该信号以执行按钮的操作。按钮还提供不太常用的信号，例如[pressed](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pressed)（） 和[released](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#released)()。

​		对话框中的命令按钮默认为自动默认按钮，即，当它们接收到键盘输入焦点时，它们会自动成为默认按钮。默认按钮是当用户在对话框中按 Enter 或 Return 键时激活的按钮。你可以改变这个[setAutoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)()。请注意，自动默认按钮保留了一些额外的空间，这是绘制默认按钮指示器所必需的。如果您不希望按钮周围有这个空间，请致电[setAutoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)（错误的）。

​		按钮小部件是如此重要，在过去的十年中已经发展到可以容纳很多变化。Microsoft 风格指南现在显示了大约十种不同的 Windows 按钮状态，并且文本暗示当考虑到所有功能组合时还有数十种状态。

最重要的模式或状态是：

- 可用或不可用（灰显、禁用）。
- 标准按钮、切换按钮或菜单按钮。
- 打开或关闭（仅用于切换按钮）。
- 默认或正常。通常可以使用 Enter 或 Return 键“单击”对话框中的默认按钮。
- 是否自动重复。
- 按下与否。

作为一般规则，当应用程序或对话框窗口在用户单击应用程序或对话框窗口执行操作（例如“应用”、“取消”、“关闭”和“帮助”）时，以及当小部件应该具有宽的矩形形状*并*带有文本标签。小的、通常为方形的按钮，用于更改窗口的状态而不是执行操作（例如窗口右上角的按钮）[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）不是命令按钮，而是工具按钮。Qt 提供了一个特殊的类（[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）对于这些按钮。

​		如果您需要切换行为（请参阅[setCheckable](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)()) 或像滚动条中的箭头一样按下时自动重复激活信号的按钮（请参阅[setAutoRepeat](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRepeat-prop)())，命令按钮可能不是您想要的。如有疑问，请使用工具按钮。

**注意：**在 macOS 上，当按钮的宽度小于 50 或高度小于 30 时，按钮的角会从圆形更改为方形。使用[setMinimumSize](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize-prop)() 函数可以防止这种行为。

命令按钮的变体是菜单按钮。它们不仅提供一个命令，而且还提供多个命令，因为单击它们时会弹出一个选项菜单。使用方法[setMenu](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMenu)() 将弹出菜单与按钮相关联。

其他类别的按钮是选项按钮（请参阅[QRadioButton](https://doc-qt-io.translate.goog/qt-6/qradiobutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）和复选框（参见[QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。

在 Qt 中，[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)基类提供了大部分模式和其他API，而QPushButton提供了GUI逻辑。看[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)有关 API 的更多信息。

**可以查阅**[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QRadioButton](https://doc-qt-io.translate.goog/qt-6/qradiobutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### autoDefault : bool

该属性保存按钮是否是自动默认按钮

如果此属性设置为 true，则按钮是自动默认按钮。

在某些 GUI 样式中，默认按钮周围有一个额外的框架，最多 3 个像素或更多。Qt 自动在自动默认按钮周围保留该空间，即自动默认按钮可能具有稍大的尺寸提示。

对于具有[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)父母；否则默认为 false。

请参阅[default](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default)属性以了解如何操作的详细信息[default](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default)和自动默认交互。

**访问功能：**

| bool | **autoDefault**() const  |
| ---- | ------------------------ |
| void | **setAutoDefault**(bool) |

### default : bool

该属性保存按钮是否为默认按钮

默认和自动默认按钮决定当用户在对话框中按 Enter 时会发生什么。

当用户按下回车键时，将此属性设置为 true 的按钮（即对话框的*默认按钮）将自动按下，但有一个例外：如果**autoDefault*按钮当前获得焦点，[autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)按钮被按下。当对话框有[autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)按钮但没有默认按钮，按 Enter 键将按[autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)当前具有焦点的按钮，或者如果没有按钮具有焦点，则下一个按钮[autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)焦点链中的按钮。

在对话框中，一次只能有一个按钮作为默认按钮。然后，该按钮会显示一个附加框架（取决于 GUI 样式）。

默认按钮行为仅在对话框中提供。当按钮具有焦点时，始终可以通过按空格键从键盘上单击按钮。

如果在对话框可见时当前默认按钮的默认属性设置为 false，则下次对话框中的按钮接收焦点时将自动分配新的默认值。

该属性的默认值是 false。

**访问功能：**

| bool | **isDefault**() const |
| ---- | --------------------- |
| void | **setDefault**(bool)  |

### flat : bool

该属性保存按钮边框是否凸起

该属性的默认值是 false。如果设置此属性，则大多数样式将不会绘制按钮背景，除非按下按钮。[setAutoFillBackground](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFillBackground-prop)() 可用于确保背景被填充使用[QPalette::Button](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorRole-enum)刷子。

**访问功能：**

| bool | **isFlat**() const |
| ---- | ------------------ |
| void | **setFlat**(bool)  |

## 成员函数文档

### `[explicit]`QPushButton::QPushButton([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个没有文本的按钮*parent*。

### `[explicit]`QPushButton::QPushButton(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

与父级一起构造一个按钮*parent*和文字*text*。

### QPushButton::QPushButton(const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*icon*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个按钮*icon*和一个*text*，和一个*parent*。

请注意，您还可以传递[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象作为图标（感谢 C++ 提供的隐式类型转换）。

### `[virtual]`QPushButton::~QPushButton()

破坏按钮。

### `[override virtual protected]`bool QPushButton::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::event](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### `[override virtual protected]`void QPushButton::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *e）。

### `[override virtual protected]`void QPushButton::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *e）。

### `[override virtual protected]`bool QPushButton::hitButton(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

重新实现：[QAbstractButton::hitButton(const QPoint &pos) const](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hitButton)。

### `[virtual protected]`void QPushButton::initStyleOption([QStyleOptionButton](https://doc-qt-io.translate.goog/qt-6/qstyleoptionbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionButton](https://doc-qt-io.translate.goog/qt-6/qstyleoptionbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**可以查阅**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual protected]`void QPushButton::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPushButton::menu() const

返回按钮关联的弹出菜单，或者`nullptr`如果未设置弹出菜单。

**可以查阅**[setMenu](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMenu)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPushButton::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[override virtual protected]`void QPushButton::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QPushButton::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QAbstractButton::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *e）。

### void QPushButton::setMenu([QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **menu*)

关联弹出菜单*menu*用这个按钮。这会将按钮变成菜单按钮，在某些样式中会在按钮文本的右侧生成一个小三角形。

菜单的所有权*不会*转移给按钮。

![带有弹出菜单的 Fusion 风格按钮的屏幕截图。](https://doc.qt.io/qt-6/images/fusion-pushbutton-menu.png)

带有弹出菜单的按钮，如图所示[Fusion widget style](https://doc-qt-io.translate.goog/qt-6/gallery.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**可以查阅**[menu](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#menu)()。

### `[slot]`void QPushButton::showMenu()

显示（弹出）关联的弹出菜单。如果没有这样的菜单，则该功能不执行任何操作。在用户关闭弹出菜单之前，此函数不会返回。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPushButton::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。