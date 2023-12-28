#  QColorDialog Class

QColorDialog 类提供了一个用于指定颜色的对话框小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QColorDialog >                                    |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qcolordialog-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QColorDialog 是[标准对话框](https://doc-qt-io.translate.goog/qt-6/standard-dialogs.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| enum  | **[ColorDialogOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum)** { ShowAlphaChannel, NoButtons, DontUseNativeDialog } |
| ----- | ------------------------------------------------------------ |
| flags | **[ColorDialogOptions](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum)** |

## 特性

- **[currentColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColor-prop)** : QColor
- **[options](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options-prop)** : ColorDialogOptions

## 公共方法

|                                  | **[QColorDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QColorDialog)**(QWidget **parent* = nullptr) |
| -------------------------------- | ------------------------------------------------------------ |
|                                  | **[QColorDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QColorDialog-1)**(const QColor &*initial*, QWidget **parent* = nullptr) |
| virtual                          | **[~QColorDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QColorDialog)**() |
| QColor                           | **[currentColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColor-prop)**() const |
| void                             | **[open](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)**(QObject **receiver*, const char **member*) |
| QColorDialog::ColorDialogOptions | **[options](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options-prop)**() const |
| QColor                           | **[selectedColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedColor)**() const |
| void                             | **[setCurrentColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColor-prop)**(const QColor &*color*) |
| void                             | **[setOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)**(QColorDialog::ColorDialogOption *option*, bool *on* = true) |
| void                             | **[setOptions](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options-prop)**(QColorDialog::ColorDialogOptions *options*) |
| bool                             | **[testOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)**(QColorDialog::ColorDialogOption *option*) const |

## 重载的公共方法

| virtual void | **[setVisible](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)**(bool *visible*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 信号

| void | **[colorSelected](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#colorSelected)**(const QColor &*color*) |
| ---- | ------------------------------------------------------------ |
| void | **[currentColorChanged](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColorChanged)**(const QColor &*color*) |

## 静态公共成员

| QColor | **[customColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#customColor)**(int *index*) |
| ------ | ------------------------------------------------------------ |
| int    | **[customCount](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#customCount)**() |
| QColor | **[getColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getColor)**(const QColor &*initial* = Qt::white, QWidget **parent* = nullptr, const QString &*title* = QString(), QColorDialog::ColorDialogOptions *options* = ColorDialogOptions()) |
| void   | **[setCustomColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCustomColor)**(int *index*, QColor *color*) |
| void   | **[setStandardColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStandardColor)**(int *index*, QColor *color*) |
| QColor | **[standardColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardColor)**(int *index*) |

## 重载的保护函数

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[done](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)**(int *result*) override |

## 详细说明

颜色对话框的功能是允许用户选择颜色。例如，您可以在绘图程序中使用它来允许用户设置画笔颜色。

静态函数提供模式颜色对话框。

静态的[getColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getColor)() 函数显示对话框，并允许用户指定颜色。此功能还可用于让用户选择具有透明度的颜色：传递[ShowAlphaChannel](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum)选项作为附加参数。

用户可以存储[customCount](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#customCount)() 不同的定制颜色。自定义颜色由所有颜色对话框共享，并在程序执行期间被记住。使用[setCustomColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCustomColor)() 设置自定义颜色，并使用[customColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#customColor)() 来获取它们。

当按下“选择屏幕颜色”按钮时，光标会变为十字形，并扫描屏幕上的颜色。用户可以通过单击鼠标或 Enter 按钮来选取一个。按 Esc 键可恢复进入此模式之前选择的最后一个颜色。

这[Standard Dialogs](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-standarddialogs-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)示例展示了如何使用 QColorDialog 以及其他内置 Qt 对话框。

![Fusion 小部件样式的颜色对话框。](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QColorDialog\QColorDialog\fusion-colordialog.png)

**也可以看看**[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Standard Dialogs Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-standarddialogs-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QColorDialog:: ColorDialogOption 标志 QColorDialog:: ColorDialogOptions

该枚举指定影响颜色对话框外观的各种选项。

| 持续的                              | 价值         | 描述                                                     |
| ----------------------------------- | ------------ | -------------------------------------------------------- |
| `QColorDialog::ShowAlphaChannel`    | `0x00000001` | 允许用户选择颜色的 Alpha 分量。                          |
| `QColorDialog::NoButtons`           | `0x00000002` | 不显示**OK**和**Cancel**纽扣。（对于“实时对话”很有用。） |
| `QColorDialog::DontUseNativeDialog` | `0x00000004` | 使用 Qt 的标准颜色对话框而不是操作系统本机颜色对话框。   |

ColorDialogOptions 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <ColorDialogOption> 的类型定义。它存储 ColorDialogOption 值的 OR 组合。

**也可以看看**[options](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options),[setOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)(),[testOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)（）， 和[windowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop)()。

## 财产文件

### currentColor : [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存对话框中当前选择的颜色

**访问功能：**

| QColor | **currentColor**() const                   |
| ------ | ------------------------------------------ |
| void   | **setCurrentColor**(const QColor &*color*) |

**通知器信号：**

| void | **[currentColorChanged](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColorChanged)**(const QColor &*color*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

### options : [ColorDialogOptions](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum)

该属性包含影响对话框外观的各种选项

默认情况下，所有选项均被禁用。

应在显示对话框之前设置选项。在对话框可见时设置它们并不能保证立即对对话框产生影响（取决于选项和平台）。

**访问功能：**

| QColorDialog::ColorDialogOptions | **options**() const                                        |
| -------------------------------- | ---------------------------------------------------------- |
| void                             | **setOptions**(QColorDialog::ColorDialogOptions *options*) |

**也可以看看**[setOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)（） 和[testOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)()。

## 成员函数文档

### `[explicit]`QColorDialog::QColorDialog([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的颜色构造一个颜色对话框*parent*。

### `[explicit]`QColorDialog::QColorDialog(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*initial*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的颜色构造一个颜色对话框*parent*并指定*initial*颜色。

### `[virtual]`QColorDialog::~QColorDialog()

破坏颜色对话框。

### `[override virtual protected]`void QColorDialog::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### `[signal]`void QColorDialog::colorSelected(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

该信号在用户单击后立即发出**OK**选择要使用的颜色。所选颜色由以下方式指定*color*。

**也可以看看**[color](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)和[currentColorChanged](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColorChanged)()。

### `[signal]`void QColorDialog::currentColorChanged(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

每当对话框中的当前颜色发生变化时，就会发出此信号。当前颜色由以下方式指定*color*。

**注意：**属性的通知程序信号[currentColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColor-prop)。

**也可以看看**[color](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)和[colorSelected](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#colorSelected)()。

### `[static]`[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColorDialog::customColor(int *index*)

返回给定的自定义颜色*index*作为一个[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。

**也可以看看**[setCustomColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCustomColor)()。

### `[static]`int QColorDialog::customCount()

返回支持的自定义颜色数量[QColorDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。所有颜色对话框共享相同的自定义颜色。

### `[override virtual protected]`void QColorDialog::done(int *result*)

重新实现：[QDialog::done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)（int r）。

关闭对话框并将其结果代码设置为*result*。如果此对话框显示为[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()、done() 导致本地事件循环完成，并且[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)（） 回来*result*。

**也可以看看**[QDialog::done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)()。

### `[static]`[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColorDialog::getColor(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*initial* = Qt::white, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title* = QString(), [QColorDialog::ColorDialogOptions](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum) *options* = ColorDialogOptions())

弹出带有给定窗口的模态颜色对话框*title*（如果未指定，则为“选择颜色”），让用户选择一种颜色并返回该颜色。颜色最初设置为*initial*。该对话框是一个子项*parent*。它返回一个无效值（参见[QColor::isValid](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)如果用户取消对话框，则 ()) 颜色。

这*options*参数允许您自定义对话框。

### void QColorDialog::open([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **receiver*, const char **member*)

打开对话框并连接其[colorSelected](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#colorSelected)() 向由指定的槽发出信号*receiver*和*member*。

当对话框关闭时，信号将从插槽断开。

### [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColorDialog::selectedColor() const

返回用户通过单击选择的颜色**OK**或等效按钮。

**注意：**此颜色并不总是与所持有的颜色相同[currentColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentColor-prop)属性，因为用户可以在最终选择要使用的颜色之前选择不同的颜色。

### `[static]`void QColorDialog::setCustomColor(int *index*, [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *color*)

将自定义颜色设置为*index*到[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *color*价值。

**注意：**此功能不适用于 macOS 平台上的 Native Color Dialog。如果您仍然需要此功能，请使用[QColorDialog::DontUseNativeDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum)选项。

**也可以看看**[customColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#customColor)()。

### void QColorDialog::setOption([QColorDialog::ColorDialogOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum) *option*, bool *on* = true)

设置给定的*option*启用如果*on*是真的; 否则，清除给定的*option*。

**也可以看看**[options](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options)和[testOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)()。

### `[static]`void QColorDialog::setStandardColor(int *index*, [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *color*)

将标准颜色设置为*index*到[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *color*价值。

**注意：**此功能不适用于 macOS 平台上的 Native Color Dialog。如果您仍然需要此功能，请使用[QColorDialog::DontUseNativeDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum)选项。

**也可以看看**[standardColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardColor)()。

### `[override virtual]`void QColorDialog::setVisible(bool *visible*)

重新实现：[QDialog::setVisible](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（布尔值可见）。

更改对话框的可见性。如果*visible*为 true，则显示对话框；否则，它被隐藏。

### `[static]`[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QColorDialog::standardColor(int *index*)

返回给定的标准颜色*index*作为一个[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。

**也可以看看**[setStandardColor](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStandardColor)()。

### bool QColorDialog::testOption([QColorDialog::ColorDialogOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorDialogOption-enum) *option*) const

`true`如果给定则返回*option*已启用；否则，返回 false。

**也可以看看**[options](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#options)和[setOption](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)()。