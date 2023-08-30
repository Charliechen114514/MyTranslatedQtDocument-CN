 QDialogButtonBox Class

QDialogButtonBox 类是一个小部件，它以适合当前小部件样式的布局显示按钮。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QDialogButtonBox>                                  |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[ButtonLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)** { WinLayout, MacLayout, KdeLayout, GnomeLayout, AndroidLayout } |
| ----- | ------------------------------------------------------------ |
| enum  | **[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)** { InvalidRole, AcceptRole, RejectRole, DestructiveRole, ActionRole, …, ResetRole } |
| enum  | **[StandardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)** { Ok, Open, Save, Cancel, Close, …, NoButton } |
| flags | **[StandardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)** |

## 特性

- **[centerButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerButtons-prop)** : bool
- **[orientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)** : Qt::Orientation
- **[standardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)** : StandardButtons

## 公共方法

|                                   | **[QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDialogButtonBox)**(QWidget **parent* = nullptr) |
| --------------------------------- | ------------------------------------------------------------ |
|                                   | **[QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDialogButtonBox-1)**(Qt::Orientation *orientation*, QWidget **parent* = nullptr) |
|                                   | **[QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDialogButtonBox-2)**(QDialogButtonBox::StandardButtons *buttons*, QWidget **parent* = nullptr) |
|                                   | **[QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDialogButtonBox-3)**(QDialogButtonBox::StandardButtons *buttons*, Qt::Orientation *orientation*, QWidget **parent* = nullptr) |
| virtual                           | **[~QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDialogButtonBox)**() |
| void                              | **[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)**(QAbstractButton **button*, QDialogButtonBox::ButtonRole *role*) |
| QPushButton *                     | **[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton-1)**(const QString &*text*, QDialogButtonBox::ButtonRole *role*) |
| QPushButton *                     | **[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton-2)**(QDialogButtonBox::StandardButton *button*) |
| QPushButton *                     | **[button](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#button)**(QDialogButtonBox::StandardButton *which*) const |
| QDialogButtonBox::ButtonRole      | **[buttonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonRole)**(QAbstractButton **button*) const |
| QList<QAbstractButton *>          | **[buttons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)**() const |
| bool                              | **[centerButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerButtons-prop)**() const |
| void                              | **[clear](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| Qt::Orientation                   | **[orientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)**() const |
| void                              | **[removeButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)**(QAbstractButton **button*) |
| void                              | **[setCenterButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerButtons-prop)**(bool *center*) |
| void                              | **[setOrientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)**(Qt::Orientation *orientation*) |
| void                              | **[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)**(QDialogButtonBox::StandardButtons *buttons*) |
| QDialogButtonBox::StandardButton  | **[standardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButton)**(QAbstractButton **button*) const |
| QDialogButtonBox::StandardButtons | **[standardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)**() const |

## 信号

| void | **[accepted](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)**() |
| ---- | ------------------------------------------------------------ |
| void | **[clicked](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)**(QAbstractButton **button*) |
| void | **[helpRequested](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpRequested)**() |
| void | **[rejected](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)**() |

## 重载的protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |

## 详细说明

对话框和消息框通常以符合该平台界面指南的布局显示按钮。不同的平台总是有不同的对话框布局。QDialogButtonBox 允许开发人员向其中添加按钮，并将自动使用适合用户桌面环境的布局。

大多数对话框按钮都遵循特定的角色。此类角色包括：

- 接受或拒绝对话框。
- 寻求帮助。
- 对对话框本身执行操作（例如重置字段或应用更改）。

还可以使用其他方法来关闭该对话框，这可能会导致破坏性结果。

大多数对话框都有几乎可以被视为标准的按钮（例如**OK**和**Cancel**纽扣）。有时以标准方式创建这些按钮会很方便。

有几种使用 QDialogButtonBox 的方法。一种方法是自己创建按钮（或按钮文本）并将它们添加到按钮框中，指定它们的角色。

```
    QDialogButtonBox *buttonBox = new QDialogButtonBox(Qt::Vertical);
    buttonBox->addButton(findButton, QDialogButtonBox::ActionRole);
    buttonBox->addButton(moreButton, QDialogButtonBox::ActionRole);
```

或者，QDialogButtonBox 提供了几个可供您使用的标准按钮（例如“确定”、“取消”、“保存”）。它们作为标志存在，因此您可以在构造函数中将它们组合在一起。

```
    buttonBox = new QDialogButtonBox(QDialogButtonBox::Ok
                                     | QDialogButtonBox::Cancel);

    connect(buttonBox, &QDialogButtonBox::accepted, this, &QDialog::accept);
    connect(buttonBox, &QDialogButtonBox::rejected, this, &QDialog::reject);
```

您可以混合搭配普通按钮和标准按钮。

目前，如果按钮框是水平的，按钮的布局方式如下：

| [GnomeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)水平的 | 水平放置的按钮盒[GnomeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [KdeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)水平的 | 水平放置的按钮盒[KdeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |
| [MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)水平的 | 水平放置的按钮盒[MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |
| [WinLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)水平的 | 水平放置的按钮盒[WinLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |

如果按钮框是垂直的，按钮的布局方式如下：

| [GnomeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) | [KdeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) | [MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) | [WinLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [GnomeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)垂直的 | [KdeLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)垂直的 | [MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)垂直的 | [WinLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum)垂直的 |

此外，仅包含带有以下内容的按钮的按钮框[ActionRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)或者[HelpRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)可以被认为是无模式的，并且在 macOS 上有另一种外观：

| 无模式水平[MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) | 无模横版截图[MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 无模式垂直[MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) | 无模立式截图[MacLayout](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonLayout-enum) |

当点击按钮框中的按钮时，[clicked](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)() 信号是在按下实际按钮时发出的。为了方便起见，如果按钮有[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum),[RejectRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)， 或者[HelpRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)， 这[accepted](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)(),[rejected](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)（）， 或者[helpRequested](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpRequested)分别发出 () 信号。

如果您希望将特定按钮设置为默认按钮，则需要调用[QPushButton::setDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)() 自己做吧。但是，如果没有设置默认按钮，并且在使用时跨平台保留哪个按钮是默认按钮[QPushButton::autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)属性，当显示 QDialogButtonBox 时，第一个具有接受角色的按钮将成为默认按钮，

**可以参阅**[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QDialogButtonBox::ButtonLayout

该枚举描述了排列按钮框中包含的按钮时要使用的布局策略。

| 持续的                            | 价值 | 描述                                                         |
| --------------------------------- | ---- | ------------------------------------------------------------ |
| `QDialogButtonBox::WinLayout`     | `0`  | 使用适合 Windows 上的应用程序的策略。                        |
| `QDialogButtonBox::MacLayout`     | `1`  | 使用适合 macOS 上的应用程序的策略。                          |
| `QDialogButtonBox::KdeLayout`     | `2`  | 使用适合 KDE 上的应用程序的策略。                            |
| `QDialogButtonBox::GnomeLayout`   | `3`  | 使用适合 GNOME 上的应用程序的策略。                          |
| `QDialogButtonBox::AndroidLayout` | `4`  | 使用适合 Android 上的应用程序的策略。该枚举值是在 Qt 5.10 中添加的。 |

按钮布局由指定[current style](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)。但在X11平台上，可能会受到桌面环境的影响。

### enum QDialogButtonBox::ButtonRole

该枚举描述了可用于描述按钮框中按钮的角色。这些角色的组合就像用于描述其行为的不同方面的标志。

| 持续的                              | 价值 | 描述                                                     |
| ----------------------------------- | ---- | -------------------------------------------------------- |
| `QDialogButtonBox::InvalidRole`     | `-1` | 该按钮无效。                                             |
| `QDialogButtonBox::AcceptRole`      | `0`  | 单击该按钮会使对话框被接受（例如“确定”）。               |
| `QDialogButtonBox::RejectRole`      | `1`  | 单击该按钮会导致对话框被拒绝（例如取消）。               |
| `QDialogButtonBox::DestructiveRole` | `2`  | 单击该按钮会导致破坏性更改（例如放弃更改）并关闭对话框。 |
| `QDialogButtonBox::ActionRole`      | `3`  | 单击该按钮会导致对话框中的元素发生更改。                 |
| `QDialogButtonBox::HelpRole`        | `4`  | 可以单击该按钮来请求帮助。                               |
| `QDialogButtonBox::YesRole`         | `5`  | 该按钮是类似“是”的按钮。                                 |
| `QDialogButtonBox::NoRole`          | `6`  | 该按钮是类似“否”的按钮。                                 |
| `QDialogButtonBox::ApplyRole`       | `8`  | 该按钮应用当前更改。                                     |
| `QDialogButtonBox::ResetRole`       | `7`  | 该按钮将对话框的字段重置为默认值。                       |

**可以参阅**[StandardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)。

### 枚举 QDialogButtonBox:: StandardButton 标志 QDialogButtonBox:: StandardButtons

这些枚举描述了标准按钮的标志。每个按钮都有一个定义的[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。

| 持续的                              | 价值         | 描述                                                         |
| ----------------------------------- | ------------ | ------------------------------------------------------------ |
| `QDialogButtonBox::Ok`              | `0x00000400` | 定义的“确定”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Open`            | `0x00002000` | 定义的“打开”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Save`            | `0x00000800` | 定义的“保存”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Cancel`          | `0x00400000` | 定义的“取消”按钮[RejectRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Close`           | `0x00200000` | 定义的“关闭”按钮[RejectRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Discard`         | `0x00800000` | “放弃”或“不保存”按钮，具体取决于平台，由[DestructiveRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Apply`           | `0x02000000` | 定义的“应用”按钮[ApplyRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Reset`           | `0x04000000` | 一个“重置”按钮定义为[ResetRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::RestoreDefaults` | `0x08000000` | 定义的“恢复默认值”按钮[ResetRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Help`            | `0x01000000` | 定义的“帮助”按钮[HelpRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::SaveAll`         | `0x00001000` | 定义的“全部保存”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Yes`             | `0x00004000` | “是”按钮定义为[YesRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::YesToAll`        | `0x00008000` | “全部同意”按钮定义为[YesRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::No`              | `0x00010000` | “否”按钮定义为[NoRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::NoToAll`         | `0x00020000` | “全部拒绝”按钮定义为[NoRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Abort`           | `0x00040000` | “中止”按钮定义为[RejectRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Retry`           | `0x00080000` | 定义的“重试”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::Ignore`          | `0x00100000` | 定义的“忽略”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QDialogButtonBox::NoButton`        | `0x00000000` | 无效按钮。                                                   |

StandardButtons 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <StandardButton> 的类型定义。它存储 StandardButton 值的 OR 组合。

**可以参阅**[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)和[standardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)。

## 财产文件

### centerButtons : bool

该属性保存按钮框中的按钮是否居中

默认情况下，该属性为`false`。此行为适用于大多数类型的对话框。一个值得注意的例外是大多数平台（例如 Windows）上的消息框，其中按钮框水平居中。

**访问功能：**

| bool | **centerButtons**() const           |
| ---- | ----------------------------------- |
| void | **setCenterButtons**(bool *center*) |

**可以参阅**[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### orientation : [Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)

该属性保存按钮框的方向

默认情况下，方向是水平的（即按钮并排放置）。可能的方向是[Qt::Horizontal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)和[Qt::Vertical](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)。

**访问功能：**

| Qt::Orientation | **orientation**() const                           |
| --------------- | ------------------------------------------------- |
| void            | **setOrientation**(Qt::Orientation *orientation*) |

### standardButtons : [StandardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)

按钮框中标准按钮的集合

此属性控制按钮框使用哪些标准按钮。

**访问功能：**

| QDialogButtonBox::StandardButtons | **standardButtons**() const                                  |
| --------------------------------- | ------------------------------------------------------------ |
| void                              | **setStandardButtons**(QDialogButtonBox::StandardButtons *buttons*) |

**可以参阅**[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

## 成员函数文档

### QDialogButtonBox::QDialogButtonBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个空的水平按钮框*parent*。

**可以参阅**[orientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### QDialogButtonBox::QDialogButtonBox([Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个空按钮框*orientation*和*parent*。

**可以参阅**[orientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### `[explicit]`QDialogButtonBox::QDialogButtonBox([QDialogButtonBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个水平按钮框*parent*，包含由指定的标准按钮*buttons*。

**可以参阅**[orientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### QDialogButtonBox::QDialogButtonBox([QDialogButtonBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons*, [Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) *orientation*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个按钮框*orientation*和*parent*，包含由指定的标准按钮*buttons*。

**可以参阅**[orientation](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### `[virtual]`QDialogButtonBox::~QDialogButtonBox()

破坏按钮盒。

### `[signal]`void QDialogButtonBox::accepted()

单击按钮框中的按钮时会发出此信号，只要它是用[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)或者[YesRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。

**可以参阅**[rejected](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)(),[clicked](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)（）， 和[helpRequested](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpRequested)()。

### void QDialogButtonBox::addButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*, [QDialogButtonBox::ButtonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum) *role*)

添加给定的*button*到具有指定的按钮框*role*。如果角色无效，则不会添加该按钮。

如果该按钮已添加，则会将其删除并使用新角色再次添加。

**注意：**按钮框拥有按钮的所有权。

**可以参阅**[removeButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)（） 和[clear](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QDialogButtonBox::addButton(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QDialogButtonBox::ButtonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum) *role*)

使用给定的值创建一个按钮*text*，将其添加到指定的按钮框中*role*，并返回相应的按钮。如果*role*无效，不会创建任何按钮，并且返回零。

**可以参阅**[removeButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)（） 和[clear](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QDialogButtonBox::addButton([QDialogButtonBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *button*)

添加一个标准*button*如果这样做有效，则返回按钮框，并返回一个按钮。如果*button*无效，不添加到按钮框中，返回零。

**可以参阅**[removeButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)（） 和[clear](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QDialogButtonBox::button([QDialogButtonBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *which*) const

返回[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对应标准按钮*which*，或者`nullptr`如果该按钮框中不存在标准按钮。

**可以参阅**[standardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButton)(),[standardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)（）， 和[buttons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)()。

### [QDialogButtonBox::ButtonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum) QDialogButtonBox::buttonRole([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*) const

返回指定按钮的角色*button*。该函数返回[InvalidRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)如果*button*已`nullptr`添加或尚未添加到按钮框。

**可以参阅**[buttons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)（） 和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QDialogButtonBox::buttons() const

返回已添加到按钮框中的所有按钮的列表。

**可以参阅**[buttonRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonRole)(),[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（）， 和[removeButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)()。

### `[override virtual protected]`void QDialogButtonBox::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### void QDialogButtonBox::clear()

清除按钮框，删除其中的所有按钮。

**可以参阅**[removeButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)（） 和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### `[signal]`void QDialogButtonBox::clicked([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*)

当单击按钮框中的按钮时会发出此信号。按下的特定按钮由*button*。

**可以参阅**[accepted](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)(),[rejected](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)（）， 和[helpRequested](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpRequested)()。

### `[override virtual protected]`bool QDialogButtonBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[signal]`void QDialogButtonBox::helpRequested()

单击按钮框中的按钮时会发出此信号，只要它是用[HelpRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。

**可以参阅**[accepted](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)(),[rejected](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)（）， 和[clicked](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)()。

### `[signal]`void QDialogButtonBox::rejected()

单击按钮框中的按钮时会发出此信号，只要它是用[RejectRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)或者[NoRole](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。

**可以参阅**[accepted](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)(),[helpRequested](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpRequested)（）， 和[clicked](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)()。

### void QDialogButtonBox::removeButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*)

删除*button*从按钮框中删除它，并将其父项设置为零。

**可以参阅**[clear](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)(),[buttons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)（）， 和[addButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### [QDialogButtonBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) QDialogButtonBox::standardButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*) const

返回与给定对应的标准按钮枚举值*button*， 或者[NoButton](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)如果给定*button*不是标准按钮。

**可以参阅**[button](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#button)(),[buttons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)（）， 和[standardButtons](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)()。