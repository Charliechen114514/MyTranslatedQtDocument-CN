#  QToolButton Class

QToolButton 类提供了一个快速访问命令或选项的按钮，通常在[QToolBar](https://doc-qt-io.translate.goog/qt-6/qtoolbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QToolButton>                                       |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtoolbutton-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[ToolButtonPopupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonPopupMode-enum)** { DelayedPopup, MenuButtonPopup, InstantPopup } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 特性

- **[arrowType](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#arrowType-prop)** : Qt::ArrowType
- **[autoRaise](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRaise-prop)** : bool
- **[popupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#popupMode-prop)** : ToolButtonPopupMode
- **[toolButtonStyle](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolButtonStyle-prop)** : Qt::ToolButtonStyle

## 公共函数

|                                  | **[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QToolButton)**(QWidget **parent* = nullptr) |
| -------------------------------- | ------------------------------------------------------------ |
| virtual                          | **[~QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QToolButton)**() |
| Qt::ArrowType                    | **[arrowType](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#arrowType-prop)**() const |
| bool                             | **[autoRaise](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRaise-prop)**() const |
| QAction *                        | **[defaultAction](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultAction)**() const |
| QMenu *                          | **[menu](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#menu)**() const |
| QToolButton::ToolButtonPopupMode | **[popupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#popupMode-prop)**() const |
| void                             | **[setArrowType](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#arrowType-prop)**(Qt::ArrowType *type*) |
| void                             | **[setAutoRaise](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRaise-prop)**(bool *enable*) |
| void                             | **[setMenu](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMenu)**(QMenu **menu*) |
| void                             | **[setPopupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#popupMode-prop)**(QToolButton::ToolButtonPopupMode *mode*) |
| Qt::ToolButtonStyle              | **[toolButtonStyle](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolButtonStyle-prop)**() const |

## 重载的公共函数

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共槽

| void | **[setDefaultAction](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultAction)**(QAction **action*) |
| ---- | ------------------------------------------------------------ |
| void | **[setToolButtonStyle](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolButtonStyle-prop)**(Qt::ToolButtonStyle *style*) |
| void | **[showMenu](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showMenu)**() |

## 信号

| void | **[triggered](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#triggered)**(QAction **action*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected function

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionToolButton **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重载的protected function

| virtual void | **[actionEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#actionEvent)**(QActionEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **e*) override |
| virtual void | **[checkStateSet](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkStateSet)**() override |
| virtual void | **[enterEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enterEvent)**(QEnterEvent **e*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| virtual bool | **[hitButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hitButton)**(const QPoint &*pos*) const override |
| virtual void | **[leaveEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#leaveEvent)**(QEvent **e*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual void | **[nextCheckState](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nextCheckState)**() override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **e*) override |

## 详细说明

​		工具按钮是一种特殊按钮，可提供对特定命令或选项的快速访问。与普通命令按钮不同，工具按钮通常不显示文本标签，而是显示图标。

​		工具按钮通常在新建时创建[QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例是用以下命令创建的[QToolBar::addAction](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addAction)() 或现有操作添加到工具栏[QToolBar::addAction](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addAction)()。还可以以与任何其他小部件相同的方式构造工具按钮，并将它们与布局中的其他小部件排列在一起。

​		工具按钮的一种经典用途是选择工具；例如，绘图程序中的“钢笔”工具。这可以通过使用 QToolButton 作为切换按钮来实现（请参阅[setCheckable](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)())。

​		QToolButton支持自动升起。在自动升起模式下，仅当鼠标指向该按钮时，该按钮才会绘制 3D 框架。当在内部使用按钮时，该功能会自动打开[QToolBar](https://doc-qt-io.translate.goog/qt-6/qtoolbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。改变它与[setAutoRaise](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRaise-prop)()。

​		工具按钮的图标设置为[QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这使得为禁用和活动状态指定不同的像素图成为可能。当按钮的功能不可用时，将使用禁用的像素图。当按钮因鼠标指针悬停在其上而自动升起时，将显示活动像素图。

​		按钮的外观和尺寸可通过以下方式调节[setToolButtonStyle](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolButtonStyle-prop)（） 和[setIconSize](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)()。当在内部使用时[QToolBar](https://doc-qt-io.translate.goog/qt-6/qtoolbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在一个[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，按钮自动调整为[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的设置（参见[QMainWindow::setToolButtonStyle](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolButtonStyle-prop)（） 和[QMainWindow::setIconSize](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)())。除了图标之外，工具按钮还可以显示箭头符号，指定为[arrowType](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#arrowType-prop)。

​		工具按钮可以在弹出菜单中提供附加选项。可以使用以下命令设置弹出菜单[setMenu](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMenu)()。使用[setPopupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#popupMode-prop)() 通过菜单集配置可用于工具按钮的不同模式。默认模式是 DelayedPopupMode，有时与 Web 浏览器中的“后退”按钮一起使用。按住按钮一段时间后，会弹出一个菜单，显示可能跳转到的页面列表。超时取决于样式，请参阅[QStyle::SH_ToolButton_PopupDelay](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleHint-enum)。

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\T\QToolButton\QToolButton\assistant-toolbar.png)Qt Assistant 的工具栏，带有工具按钮 |
| ------------------------------------------------------------ |
| Qt Assistant 的工具栏包含与主窗口其他部分中使用的操作相关联的工具按钮。 |

**可以参阅**[QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QToolBar](https://doc-qt-io.translate.goog/qt-6/qtoolbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QToolButton::ToolButtonPopupMode

描述如何为具有菜单集或包含操作列表的工具按钮弹出菜单。

| 持续的                         | 价值 | 描述                                                         |
| ------------------------------ | ---- | ------------------------------------------------------------ |
| `QToolButton::DelayedPopup`    | `0`  | 按住工具按钮一定时间后（超时时间取决于样式，请参阅[QStyle::SH_ToolButton_PopupDelay](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleHint-enum))，显示菜单。一个典型的应用示例是某些网络浏览器工具栏中的“后退”按钮。如果用户单击它，浏览器将简单地浏览回上一页。如果用户按住按钮一段时间，工具按钮会显示一个包含当前历史列表的菜单 |
| `QToolButton::MenuButtonPopup` | `1`  | 在此模式下，工具按钮会显示一个特殊箭头以指示存在菜单。按下按钮的箭头部分时会显示菜单。 |
| `QToolButton::InstantPopup`    | `2`  | 当按下工具按钮时，菜单会立即显示。在此模式下，不会触发按钮本身的操作。 |

## 属性文档

### arrowType : [Qt::ArrowType](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ArrowType-enum)

该属性保存按钮是否显示箭头而不是普通图标

这会显示一个箭头作为图标[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

默认情况下，该属性设置为[Qt::NoArrow](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ArrowType-enum)。

**访问功能：**

| Qt::ArrowType | **arrowType**() const                  |
| ------------- | -------------------------------------- |
| void          | **setArrowType**(Qt::ArrowType *type*) |

### autoRaise : bool

该属性保存是否启用自动提升。

默认为禁用（即 false）。

使用 QMacStyle 时，当前在 macOS 上会忽略此属性。

**访问功能：**

| bool | **autoRaise**() const           |
| ---- | ------------------------------- |
| void | **setAutoRaise**(bool *enable*) |

### popupMode : [ToolButtonPopupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonPopupMode-enum)

描述弹出菜单与工具按钮一起使用的方式

默认情况下，该属性设置为[DelayedPopup](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonPopupMode-enum)。

**访问功能：**

| QToolButton::ToolButtonPopupMode | **popupMode**() const                                     |
| -------------------------------- | --------------------------------------------------------- |
| void                             | **setPopupMode**(QToolButton::ToolButtonPopupMode *mode*) |

### toolButtonStyle : [Qt::ToolButtonStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonStyle-enum)

此属性保存工具按钮是否仅显示图标、仅显示文本或图标旁边/下方的文本。

默认为[Qt::ToolButtonIconOnly](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonStyle-enum)。

要使工具按钮的样式遵循系统设置，请将此属性设置为[Qt::ToolButtonFollowStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonStyle-enum)。在 Unix 上，将使用桌面环境中的用户设置。在其他平台上，[Qt::ToolButtonFollowStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ToolButtonStyle-enum)仅表示图标。

[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)自动将此插槽连接到相关信号[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)位于其中。

**访问功能：**

| Qt::ToolButtonStyle | **toolButtonStyle**() const                         |
| ------------------- | --------------------------------------------------- |
| void                | **setToolButtonStyle**(Qt::ToolButtonStyle *style*) |

## 成员函数文档

### `[explicit]`QToolButton::QToolButton([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

与父级构造一个空工具按钮*parent*。

### `[virtual]`QToolButton::~QToolButton()

销毁对象并释放所有分配的资源。

### `[override virtual protected]`void QToolButton::actionEvent([QActionEvent](https://doc-qt-io.translate.goog/qt-6/qactionevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::actionEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#actionEvent)（QActionEvent *事件）。

### `[override virtual protected]`void QToolButton::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::changeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *e）。

### `[override virtual protected]`void QToolButton::checkStateSet()

重新实现：[QAbstractButton::checkStateSet](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkStateSet)()。

### [QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QToolButton::defaultAction() const

返回默认操作。

**可以参阅**[setDefaultAction](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultAction)()。

### `[override virtual protected]`void QToolButton::enterEvent([QEnterEvent](https://doc-qt-io.translate.goog/qt-6/qenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::enterEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enterEvent)（QEnterEvent *事件）。

### `[override virtual protected]`bool QToolButton::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractButton::event](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### `[override virtual protected]`bool QToolButton::hitButton(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

重新实现：[QAbstractButton::hitButton(const QPoint &pos) const](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hitButton)。

### `[virtual protected]`void QToolButton::initStyleOption([QStyleOptionToolButton](https://doc-qt-io.translate.goog/qt-6/qstyleoptiontoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionToolButton](https://doc-qt-io.translate.goog/qt-6/qstyleoptiontoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**可以参阅**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual protected]`void QToolButton::leaveEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::leaveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#leaveEvent)（QEvent *事件）。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QToolButton::menu() const

返回关联的菜单，或者`nullptr`如果未定义菜单则返回。

**可以参阅**[setMenu](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMenu)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QToolButton::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[override virtual protected]`void QToolButton::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QToolButton::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QToolButton::nextCheckState()

重新实现：[QAbstractButton::nextCheckState](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nextCheckState)()。

### `[override virtual protected]`void QToolButton::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractButton::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *e）。

根据绘制来绘制按钮*event*。

### `[slot]`void QToolButton::setDefaultAction([QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **action*)

将默认操作设置为*action*。

如果工具按钮具有默认操作，则该操作定义按钮的以下属性：

- [checkable](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)
- [checked](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)
- [enabled](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enabled-prop)
- [font](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font-prop)
- [icon](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)
- [popupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#popupMode-prop)（假设该操作有一个菜单）
- [statusTip](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusTip-prop)
- [text](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)
- [toolTip](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip-prop)
- [whatsThis](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#whatsThis-prop)

其他属性，例如[autoRepeat](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoRepeat-prop)，不受动作影响。

**可以参阅**[defaultAction](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultAction)()。

### void QToolButton::setMenu([QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **menu*)

关联给定的*menu*使用此工具按钮。

菜单将根据按钮的显示[popupMode](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#popupMode-prop)。

菜单的所有权不会转移给工具按钮。

**可以参阅**[menu](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#menu)()。

### `[slot]`void QToolButton::showMenu()

显示（弹出）关联的弹出菜单。如果没有这样的菜单，则该功能不执行任何操作。在用户关闭弹出菜单之前，此函数不会返回。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QToolButton::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。

### `[override virtual protected]`void QToolButton::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractButton::timerEvent](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)(QTimerEvent *e)。

### `[signal]`void QToolButton::triggered([QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **action*)

当给定的*action*被触发。

该动作还可以与用户界面的其他部分相关联，例如菜单项和键盘快捷键。以这种方式共享操作有助于使用户界面更加一致，并且通常可以减少实施工作。