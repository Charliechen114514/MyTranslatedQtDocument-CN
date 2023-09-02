#  QDockWidget Class

QDockWidget 类提供了一个可以停靠在[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或作为桌面上的顶级窗口浮动。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QDockWidget>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdockwidget-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[DockWidgetFeature](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)** { DockWidgetClosable, DockWidgetMovable, DockWidgetFloatable, DockWidgetVerticalTitleBar, NoDockWidgetFeatures } |
| ----- | ------------------------------------------------------------ |
| flags | **[DockWidgetFeatures](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)** |

## 特性

- **[allowedAreas](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreas-prop)** : Qt::DockWidgetAreas
- **[features](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#features-prop)** : DockWidgetFeatures
- **[floating](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floating-prop)** : bool
- **[windowTitle](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)** : QString

## 公共职能

|                                 | **[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDockWidget)**(const QString &*title*, QWidget **parent* = nullptr, Qt::WindowFlags *flags* = Qt::WindowFlags()) |
| ------------------------------- | ------------------------------------------------------------ |
|                                 | **[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDockWidget-1)**(QWidget **parent* = nullptr, Qt::WindowFlags *flags* = Qt::WindowFlags()) |
| virtual                         | **[~QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDockWidget)**() |
| Qt::DockWidgetAreas             | **[allowedAreas](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreas-prop)**() const |
| QDockWidget::DockWidgetFeatures | **[features](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#features-prop)**() const |
| bool                            | **[isAreaAllowed](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAreaAllowed)**(Qt::DockWidgetArea *area*) const |
| bool                            | **[isFloating](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floating-prop)**() const |
| void                            | **[setAllowedAreas](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreas-prop)**(Qt::DockWidgetAreas *areas*) |
| void                            | **[setFeatures](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#features-prop)**(QDockWidget::DockWidgetFeatures *features*) |
| void                            | **[setFloating](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floating-prop)**(bool *floating*) |
| void                            | **[setTitleBarWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTitleBarWidget)**(QWidget **widget*) |
| void                            | **[setWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)**(QWidget **widget*) |
| QWidget *                       | **[titleBarWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#titleBarWidget)**() const |
| QAction *                       | **[toggleViewAction](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toggleViewAction)**() const |
| QWidget *                       | **[widget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)**() const |

## 信号

| void | **[allowedAreasChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreasChanged)**(Qt::DockWidgetAreas *allowedAreas*) |
| ---- | ------------------------------------------------------------ |
| void | **[dockLocationChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dockLocationChanged)**(Qt::DockWidgetArea *area*) |
| void | **[featuresChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#featuresChanged)**(QDockWidget::DockWidgetFeatures *features*) |
| void | **[topLevelChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#topLevelChanged)**(bool *topLevel*) |
| void | **[visibilityChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visibilityChanged)**(bool *visible*) |

## protected function

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionDockWidget **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重新实现protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[closeEvent](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)**(QCloseEvent **event*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |

## 详细说明

QDockWidget 提供了停靠小部件的概念，也称为工具选项板或实用程序窗口。停靠窗口是放置在*停靠窗口小部件*周围的辅助窗口[central widget](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centralWidget)在一个[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\D\QDockWidget\QDockWidget\mainwindow-docks.png)

最终用户可以将停靠窗口移动到其当前区域内、移动到新区域以及浮动（例如，取消停靠）。QDockWidget API 允许程序员限制停靠小部件移动、浮动和关闭的能力，以及它们可以放置的区域。

### 外貌

QDockWidget 由标题栏和内容区域组成。标题栏显示停靠小部件[window title](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)、一个*浮动*按钮和一个*关闭*按钮。根据 QDockWidget 的状态，*浮动*和*关闭*按钮可能被禁用或根本不显示。

标题栏和按钮的视觉外观取决于[style](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)正在使用。

QDockWidget 充当其子窗口小部件的包装器，设置为[setWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。自定义尺寸提示、最小和最大尺寸以及尺寸策略应在子窗口小部件中实现。QDockWidget 将尊重它们，调整其自身的约束以包括框架和标题。不应在 QDockWidget 本身上设置大小约束，因为它们会根据它是否停靠而变化；停靠的 QDockWidget 没有框架和较小的标题栏。

**注意：**在 macOS 上，如果 QDockWidget 有本机窗口句柄（例如，如果[winId](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#winId)() 在它或子窗口小部件上调用），那么由于限制，在取消停靠时将无法拖动停靠窗口小部件。开始拖动将取消停靠停靠小部件，但需要第二次拖动才能移动停靠小部件本身。

**也可以看看**[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[Dock Widgets Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-mainwindows-dockwidgets-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QDockWidget:: DockWidgetFeature 标志 QDockWidget:: DockWidgetFeatures

| 持续的                                    | 价值   | 描述                                                         |
| ----------------------------------------- | ------ | ------------------------------------------------------------ |
| `QDockWidget::DockWidgetClosable`         | `0x01` | 停靠小部件可以关闭。在某些系统上，停靠小部件在浮动时始终有一个关闭按钮（例如在 MacOS 10.5 上）。 |
| `QDockWidget::DockWidgetMovable`          | `0x02` | 用户可以在扩展坞之间移动扩展坞小部件。                       |
| `QDockWidget::DockWidgetFloatable`        | `0x04` | 停靠小部件可以从主窗口分离，并作为独立窗口浮动。             |
| `QDockWidget::DockWidgetVerticalTitleBar` | `0x08` | 停靠小部件在其左侧显示一个垂直标题栏。这可以用来增加垂直空间的大小[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。 |
| `QDockWidget::NoDockWidgetFeatures`       | `0x00` | 停靠小部件无法关闭、移动或浮动。                             |

DockWidgetFeatures 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <DockWidgetFeature> 的类型定义。它存储 DockWidgetFeature 值的 OR 组合。

## 属性文档

### allowedAreas : [Qt::DockWidgetAreas](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetArea-enum)

可以放置停靠小部件的区域

默认为[Qt::AllDockWidgetAreas](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetArea-enum)。

**访问功能：**

| Qt::DockWidgetAreas | **allowedAreas**() const                         |
| ------------------- | ------------------------------------------------ |
| void                | **setAllowedAreas**(Qt::DockWidgetAreas *areas*) |

**通知器信号：**

| void | **[allowedAreasChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreasChanged)**(Qt::DockWidgetAreas *allowedAreas*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[Qt::DockWidgetArea](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetArea-enum)。

### features : [DockWidgetFeatures](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)

该属性保存停靠小部件是否可移动、可关闭和可浮动

默认情况下，此属性设置为以下组合[DockWidgetClosable](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum),[DockWidgetMovable](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)和[DockWidgetFloatable](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)。

**访问功能：**

| QDockWidget::DockWidgetFeatures | **features**() const                                        |
| ------------------------------- | ----------------------------------------------------------- |
| void                            | **setFeatures**(QDockWidget::DockWidgetFeatures *features*) |

**通知器信号：**

| void | **[featuresChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#featuresChanged)**(QDockWidget::DockWidgetFeatures *features*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[DockWidgetFeature](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)。

### floating : bool

该属性保存停靠小部件是否浮动

浮动停靠小部件作为其父窗口“顶部”的独立窗口呈现给用户[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，而不是停靠在[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

默认情况下，该属性为`true`。

当该属性发生变化时，`topLevelChanged()`就会发出信号。

**访问功能：**

| bool | **isFloating**() const           |
| ---- | -------------------------------- |
| void | **setFloating**(bool *floating*) |

**也可以看看**[isWindow](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWindow)（） 和[topLevelChanged](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#topLevelChanged)()。

### windowTitle : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存停靠小部件标题（标题）

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **[windowTitle](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)**() const |
| ------- | ------------------------------------------------------------ |
| void    | **[setWindowTitle](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)**(const QString &) |

**通知器信号：**

| void | **[windowTitleChanged](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitleChanged)**(const QString &*title*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 成员函数文档

### `[explicit]`QDockWidget::QDockWidget(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *flags* = Qt::WindowFlags())

构造一个带有父级的 QDockWidget*parent*和窗口标志*flags*。停靠小部件将放置在左侧停靠小部件区域中。

窗口标题设置为*title*。当 QDockWidget 停靠和取消停靠时使用此标题。它也用在由提供的上下文菜单中[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[setWindowTitle](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)()。

### `[explicit]`QDockWidget::QDockWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *flags* = Qt::WindowFlags())

构造一个带有父级的 QDockWidget*parent*和窗口标志*flags*。停靠小部件将放置在左侧停靠小部件区域中。

### `[virtual]`QDockWidget::~QDockWidget()

销毁停靠小部件。

### `[signal]`void QDockWidget::allowedAreasChanged([Qt::DockWidgetAreas](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetArea-enum) *allowedAreas*)

当[allowedAreas](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreas-prop)属性变化。这*allowedAreas*参数给出属性的新值。

**注意：**属性的通知程序信号[allowedAreas](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allowedAreas-prop)。

### `[override virtual protected]`void QDockWidget::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### `[override virtual protected]`void QDockWidget::closeEvent([QCloseEvent](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::closeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)（QCloseEvent *事件）。

### `[signal]`void QDockWidget::dockLocationChanged([Qt::DockWidgetArea](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetArea-enum) *area*)

当停靠小部件移动到另一个停靠栏时会发出此信号*area*，或移动到当前停靠区域中的其他位置。当用户以编程方式移动停靠小部件或将其拖动到新位置时，就会发生这种情况。

### `[override virtual protected]`bool QDockWidget::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[signal]`void QDockWidget::featuresChanged([QDockWidget::DockWidgetFeatures](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum) *features*)

当[features](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#features-prop)属性变化。这*features*参数给出属性的新值。

**注意：**属性的通知程序信号[features](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#features-prop)。

### `[virtual protected]`void QDockWidget::initStyleOption([QStyleOptionDockWidget](https://doc-qt-io.translate.goog/qt-6/qstyleoptiondockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionDockWidget](https://doc-qt-io.translate.goog/qt-6/qstyleoptiondockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**也可以看看**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### bool QDockWidget::isAreaAllowed([Qt::DockWidgetArea](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetArea-enum) *area*) const

返回`true`此停靠小部件是否可以放置在给定的位置*area*; 否则返回`false`.

### `[override virtual protected]`void QDockWidget::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### void QDockWidget::setTitleBarWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

设置任意*widget*作为停靠小部件的标题栏。如果*widget*是`nullptr`，之前在停靠小部件上设置的任何自定义标题栏小部件都将被删除，但不会被删除，而是将使用默认标题栏。

如果设置了标题栏小部件，[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)浮动时不会使用原生窗口装饰。

以下是实现自定义标题栏的一些技巧：

- 标题栏小部件未显式处理的鼠标事件必须通过调用来忽略[QMouseEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)()。然后这些事件传播到[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)父级，以通常的方式处理它们，拖动标题栏时移动，双击时停靠和取消停靠等。

- 什么时候

  DockWidgetVerticalTitleBar

  设置为

  QDockWidget

  ，标题栏小部件会相应地重新定位。在

  resizeEvent

  ()，标题栏应检查它应采取的方向：

  ```
  QDockWidget *dockWidget = qobject_cast<QDockWidget*>(parentWidget());
  if (dockWidget->features() & QDockWidget::DockWidgetVerticalTitleBar) {
      // I need to be vertical
  } else {
      // I need to be horizontal
  }
  ```

- 标题栏小部件必须具有有效的[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)（） 和[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)()。这些函数应考虑标题栏的当前方向。

- 无法从停靠小部件中删除标题栏。然而，通过设置默认构造可以达到类似的效果[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为标题栏小部件。

使用[qobject_cast](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qobject_cast)() 如上所示，标题栏小部件具有对其父级的完全访问权限[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。因此，它可以响应用户操作执行对接和隐藏等操作。

**也可以看看**[titleBarWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#titleBarWidget)（） 和[DockWidgetVerticalTitleBar](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DockWidgetFeature-enum)。

### void QDockWidget::setWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

将停靠小部件的小部件设置为*widget*。

如果停靠小部件在以下情况下可见*widget*添加后，您必须[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 明确表示。

请注意，您必须添加*widget*在调用此函数之前；如果没有，则*widget*将不可见。

**也可以看看**[widget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QDockWidget::titleBarWidget() const

返回自定义标题栏小部件集[QDockWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，或者`nullptr`如果未设置自定义标题栏。

**也可以看看**[setTitleBarWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTitleBarWidget)()。

### [QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QDockWidget::toggleViewAction() const

返回可添加到菜单和工具栏的可检查操作，以便用户可以显示或关闭此停靠小部件。

该操作的文本设置为停靠小部件的窗口标题。

**注意：**该操作不能用于以编程方式显示或隐藏停靠小部件。使用[visible](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visible-prop)为此的财产。

**也可以看看**[QAction::text](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)和[QWidget::windowTitle](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)。

### `[signal]`void QDockWidget::topLevelChanged(bool *topLevel*)

当[floating](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floating-prop)属性变化。这*topLevel*如果停靠小部件现在浮动，则参数为 true；否则就是假的。

**也可以看看**[isWindow](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWindow)()。

### `[signal]`void QDockWidget::visibilityChanged(bool *visible*)

当停靠小部件变为*visible*（或不可见）。当小部件隐藏或显示时，以及当它停靠在选项卡式停靠区域并且其选项卡被选中或取消选中时，就会发生这种情况。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QDockWidget::widget() const

返回停靠小部件的小部件。如果尚未设置小部件，则此函数返回零。

**也可以看看**[setWidget](https://doc-qt-io.translate.goog/qt-6/qdockwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。