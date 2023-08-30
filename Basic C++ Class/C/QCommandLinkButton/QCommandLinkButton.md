 

# QCommandLinkButton Class

QCommandLinkButton 小部件提供了 Vista 风格的命令链接按钮。[更多的...](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QCommandLinkButton>                                |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[description](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#description-prop)** : QString
- **[flat](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)** : bool

## 公共方法

|         | **[QCommandLinkButton](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QCommandLinkButton)**(QWidget **parent* = nullptr) |
| ------- | ------------------------------------------------------------ |
|         | **[QCommandLinkButton](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QCommandLinkButton-1)**(const QString &*text*, QWidget **parent* = nullptr) |
|         | **[QCommandLinkButton](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QCommandLinkButton-2)**(const QString &*text*, const QString &*description*, QWidget **parent* = nullptr) |
| virtual | **[~QCommandLinkButton](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QCommandLinkButton)**() |
| QString | **[description](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#description-prop)**() const |
| void    | **[setDescription](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#description-prop)**(const QString &*description*) |

## 重载的公共方法

| virtual int   | **[heightForWidth](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#heightForWidth)**(int *width*) const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 重载的protected function

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qcommandlinkbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent *) override |

## 详细说明

命令链接是 Windows Vista 引入的新控件。其预期用途与单选按钮类似，用于在一组互斥的选项之间进行选择。命令链接按钮不应单独使用，而应作为向导和对话框中单选按钮的替代品，并使按“下一步”按钮变得多余。外观通常与平面按钮类似，但除了正常按钮文本之外，它还允许使用描述性文本。默认情况下，它还会带有一个箭头图标，表示按下该控件将打开另一个窗口或页面。

**也可以看看**[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QRadioButton](https://doc-qt-io.translate.goog/qt-6/qradiobutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### description : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性包含一个描述性标签来补充按钮文本

设置此属性将在按钮上设置描述性文本，以补充文本标签。通常会以比主要文本更小的字体显示。

**访问功能：**

| QString | **description**() const                          |
| ------- | ------------------------------------------------ |
| void    | **setDescription**(const QString &*description*) |

### flat : bool

此属性确定按钮是显示为平面面板还是带有边框。

默认情况下，此属性设置为 false。

**访问功能：**

| bool | **[isFlat](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)**() const |
| ---- | ------------------------------------------------------------ |
| void | **[setFlat](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)**(bool) |

**也可以看看**[QPushButton::flat](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)。

## 成员函数文档

### `[explicit]`QCommandLinkButton::QCommandLinkButton([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个没有文本的命令链接*parent*。

### `[explicit]`QCommandLinkButton::QCommandLinkButton(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

与父级构建命令链接*parent*和文字*text*。

### `[explicit]`QCommandLinkButton::QCommandLinkButton(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*description*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个命令链接*text*， A*description*，和一个*parent*。

### `[virtual]`QCommandLinkButton::~QCommandLinkButton()

析构函数。

### `[override virtual protected]`bool QCommandLinkButton::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重载的：[QPushButton::event](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### `[override virtual]`int QCommandLinkButton::heightForWidth(int *width*) const

重载的：[QWidget::heightForWidth(int w) const](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#heightForWidth)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCommandLinkButton::minimumSizeHint() const

重载的：[QPushButton::minimumSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)。

### `[override virtual protected]`void QCommandLinkButton::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重载的：[QPushButton::paintEvent](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCommandLinkButton::sizeHint() const

重载的：[QPushButton::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。