#  QFontDialog Class

QFontDialog 类提供了一个用于选择字体的对话框小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QFontDialog >                                     |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qfontdialog-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QFontDialog 是[标准对话框](https://doc-qt-io.translate.goog/qt-6/standard-dialogs.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| enum  | **[FontDialogOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontDialogOption-enum)** { NoButtons, DontUseNativeDialog, ScalableFonts, NonScalableFonts, MonospacedFonts, ProportionalFonts } |
| ----- | ------------------------------------------------------------ |
| flags | **[FontDialogOptions](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontDialogOption-enum)** |

## 特性

- **[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont-prop)** : QFont
- **[options](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options-prop)** : FontDialogOptions

## 公共方法

|                                | **[QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFontDialog)**(QWidget **parent* = nullptr) |
| ------------------------------ | ------------------------------------------------------------ |
|                                | **[QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFontDialog-1)**(const QFont &*initial*, QWidget **parent* = nullptr) |
| QFont                          | **[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)**() const |
| void                           | **[open](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)**(QObject **receiver*, const char **member*) |
| QFontDialog::FontDialogOptions | **[options](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options-prop)**() const |
| QFont                          | **[selectedFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedFont)**() const |
| void                           | **[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)**(const QFont &*font*) |
| void                           | **[setOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)**(QFontDialog::FontDialogOption *option*, bool *on* = true) |
| void                           | **[setOptions](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options-prop)**(QFontDialog::FontDialogOptions *options*) |
| bool                           | **[testOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)**(QFontDialog::FontDialogOption *option*) const |

## 重载的公共方法

| virtual void | **[setVisible](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)**(bool *visible*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 信号

| void | **[currentFontChanged](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFontChanged)**(const QFont &*font*) |
| ---- | ------------------------------------------------------------ |
| void | **[fontSelected](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontSelected)**(const QFont &*font*) |

## 静态公共成员

| QFont | **[getFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getFont)**(bool **ok*, const QFont &*initial*, QWidget **parent* = nullptr, const QString &*title* = QString(), QFontDialog::FontDialogOptions *options* = FontDialogOptions()) |
| ----- | ------------------------------------------------------------ |
| QFont | **[getFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getFont-1)**(bool **ok*, QWidget **parent* = nullptr) |

## 重新实现受保护的功能

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[done](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)**(int *result*) override |

## 详细说明

字体对话框是通过静态之一创建的[getFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getFont)（） 功能。

例子：

```
bool ok;
QFont font = QFontDialog::getFont(
                &ok, QFont("Helvetica [Cronyx]", 10), this);
if (ok) {
    // the user clicked OK and font is set to the font the user selected
} else {
    // the user canceled the dialog; font is set to the initial
    // value, in this case Helvetica [Cronyx], 10
}
```

该对话框还可用于直接设置小部件的字体：

```
myWidget.setFont(QFontDialog::getFont(0, myWidget.font()));
```

如果用户单击“确定”，他们选择的字体将用于 myWidget，如果单击“取消”，则使用原始字体。

![Fusion 小部件样式的字体对话框。](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\F\QFontDialog\QFontDialog\fusion-fontdialog.png)

**也可以看看**[QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFontInfo](https://doc-qt-io.translate.goog/qt-6/qfontinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFontMetrics](https://doc-qt-io.translate.goog/qt-6/qfontmetrics.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QColorDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Standard Dialogs Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-standarddialogs-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QFontDialog:: FontDialogOption 标志 QFontDialog:: FontDialogOptions

该枚举指定影响字体对话框外观的各种选项。

例如，它允许指定应显示哪种类型的字体。如果未指定，将列出所有可用字体。

请注意，某些平台（例如 Mac）可能不支持字体过滤选项。它们始终受到非本机对话框（在 Windows 或 Linux 上使用）的支持。

| 持续的                             | 价值         | 描述                                                         |
| ---------------------------------- | ------------ | ------------------------------------------------------------ |
| `QFontDialog::NoButtons`           | `0x00000001` | 不显示**OK**和**Cancel**纽扣。（对于“实时对话”很有用。）     |
| `QFontDialog::DontUseNativeDialog` | `0x00000002` | 在 Mac 上使用 Qt 的标准字体对话框，而不是 Apple 的本机字体面板。 |
| `QFontDialog::ScalableFonts`       | `0x00000004` | 显示可缩放字体                                               |
| `QFontDialog::NonScalableFonts`    | `0x00000008` | 显示不可缩放字体                                             |
| `QFontDialog::MonospacedFonts`     | `0x00000010` | 显示等宽字体                                                 |
| `QFontDialog::ProportionalFonts`   | `0x00000020` | 显示比例字体                                                 |

FontDialogOptions 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <FontDialogOption> 的类型定义。它存储 FontDialogOption 值的 OR 组合。

**也可以看看**[options](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options),[setOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)（）， 和[testOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)()。

## 财产文件

### currentFont : [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存对话框的当前字体。

**访问功能：**

| QFont | **[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)**() const |
| ----- | ------------------------------------------------------------ |
| void  | **[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)**(const QFont &*font*) |

**通知器信号：**

| void | **[currentFontChanged](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFontChanged)**(const QFont &*font*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

### options : [FontDialogOptions](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontDialogOption-enum)

该属性包含影响对话框外观的各种选项

默认情况下，所有选项均被禁用。

应在显示对话框之前设置选项。在对话框可见时设置它们并不能保证立即对对话框产生影响（取决于选项和平台）。

**访问功能：**

| QFontDialog::FontDialogOptions | **options**() const                                      |
| ------------------------------ | -------------------------------------------------------- |
| void                           | **setOptions**(QFontDialog::FontDialogOptions *options*) |

**也可以看看**[setOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)（） 和[testOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)()。

## 成员函数文档

### `[explicit]`QFontDialog::QFontDialog([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个标准字体对话框。

使用[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)() 设置初始字体属性。

这*parent*参数被传递给[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[getFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getFont)()。

### `[explicit]`QFontDialog::QFontDialog(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*initial*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个标准字体对话框*parent*并指定*initial*字体。

### `[override virtual protected]`void QFontDialog::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontDialog::currentFont() const

返回当前字体。

**注意：**属性 currentFont 的 Getter 函数。

**也可以看看**[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)（） 和[selectedFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedFont)()。

### `[signal]`void QFontDialog::currentFontChanged(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

当当前字体改变时，会发出此信号。新字体在中指定*font*。

当用户选择字体时会发出该信号。最终，所选字体可能与当前选择的字体不同。

**注意：**属性的通知程序信号[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)。

**也可以看看**[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont),[fontSelected](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontSelected)（）， 和[selectedFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedFont)()。

### `[override virtual protected]`void QFontDialog::done(int *result*)

重新实现：[QDialog::done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)（int r）。

关闭对话框并将其结果代码设置为*result*。如果此对话框显示为[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()、done() 导致本地事件循环完成，并且[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)（） 回来*result*。

**也可以看看**[QDialog::done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)()。

### `[signal]`void QFontDialog::fontSelected(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

选择字体后会发出此信号。所选字体在中指定*font*。

仅当用户选择要使用的最终字体时才会发出该信号。当用户更改字体对话框中的当前字体时，不会发出它。

**也可以看看**[selectedFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedFont)(),[currentFontChanged](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFontChanged)（）， 和[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)。

### `[static]`[QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontDialog::getFont(bool **ok*, const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*initial*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title* = QString(), [QFontDialog::FontDialogOptions](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontDialogOption-enum) *options* = FontDialogOptions())

执行模式字体对话框并返回字体。

如果用户点击**OK**，返回所选字体。如果用户点击**Cancel**， 这*initial*返回字体。

对话框是用给定的构造的*parent*以及中指定的选项*options*。*title*显示为对话框的窗口标题并且*initial*是最初选择的字体。如果*ok*参数不为空，如果用户单击，则其引用的值设置为 true**OK**，如果用户点击则设置为 false**Cancel**。

例子：

```
bool ok;
QFont font = QFontDialog::getFont(&ok, QFont("Times", 12), this);
if (ok) {
    // font is set to the font the user selected
} else {
    // the user canceled the dialog; font is set to the initial
    // value, in this case Times, 12.
}
```

该对话框还可用于直接设置小部件的字体：

```
myWidget.setFont(QFontDialog::getFont(0, myWidget.font()));
```

在此示例中，如果用户单击“确定”，将使用他们选择的字体，如果单击“取消”，则将使用原始字体。

**警告：**请勿删除*parent*在对话框执行期间。如果您想这样做，您应该使用其中之一自己创建对话框[QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

### `[static]`[QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontDialog::getFont(bool **ok*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

这是一个过载功能。

执行模式字体对话框并返回字体。

如果用户点击**OK**，返回所选字体。如果用户点击**Cancel**，返回 Qt 默认字体。

对话框是用给定的构造的*parent*。如果*ok*参数不为空，如果用户单击，则其引用的值设置为 true**OK**，如果用户点击则为 false**Cancel**。

例子：

```
bool ok;
QFont font = QFontDialog::getFont(&ok, this);
if (ok) {
    // font is set to the font the user selected
} else {
    // the user canceled the dialog; font is set to the default
    // application font, QApplication::font()
}
```

**警告：**请勿删除*parent*在对话框执行期间。如果您想这样做，您应该使用其中之一自己创建对话框[QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

### void QFontDialog::open([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **receiver*, const char **member*)

打开对话框并连接其[fontSelected](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontSelected)() 向由指定的槽发出信号*receiver*和*member*。

当对话框关闭时，信号将从插槽断开。

### [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontDialog::selectedFont() const

返回用户通过单击选择的字体**OK**或等效按钮。

**注意：**此字体并不总是与所拥有的字体相同[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)属性，因为用户可以在最终选择要使用的字体之前选择不同的字体。

### void QFontDialog::setCurrentFont(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

设置突出显示的字体[QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对给定的*font*。

**注意：**属性的 Setter 函数[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)。

**也可以看看**[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)（） 和[selectedFont](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedFont)()。

### void QFontDialog::setOption([QFontDialog::FontDialogOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontDialogOption-enum) *option*, bool *on* = true)

设置给定的*option*启用如果*on*是真的; 否则，清除给定的*option*。

**也可以看看**[options](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options)和[testOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)()。

### `[override virtual]`void QFontDialog::setVisible(bool *visible*)

重新实现：[QDialog::setVisible](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（布尔值可见）。

### bool QFontDialog::testOption([QFontDialog::FontDialogOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontDialogOption-enum) *option*) const

`true`如果给定则返回*option*已启用；否则，返回 false。

**也可以看看**[options](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options)和[setOption](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)()。