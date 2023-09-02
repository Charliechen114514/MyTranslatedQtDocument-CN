#  QQuickWidget Class

QQuickWidget 类提供了用于显示 Qt Quick 用户界面的小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QQuickWidget>                                     |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS QuickWidgets) target_link_libraries(mytarget PRIVATE Qt6::QuickWidgets) |
| qmake:    | QT += quickwidgets                                           |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qquickwidget-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[ResizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)** { SizeViewToRootObject, SizeRootObjectToView } |
| ---- | ------------------------------------------------------------ |
| enum | **[Status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)** { Null, Ready, Loading, Error } |

## 特性

- **[resizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)** : ResizeMode
- **[source](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)** : QUrl
- **[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status-prop)** : const Status

## 公共函数

|                          | **[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QQuickWidget)**(QWidget **parent* = nullptr) |
| ------------------------ | ------------------------------------------------------------ |
|                          | **[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QQuickWidget-1)**(QQmlEngine **engine*, QWidget **parent*) |
|                          | **[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QQuickWidget-2)**(const QUrl &*source*, QWidget **parent* = nullptr) |
| virtual                  | **[~QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QQuickWidget)**() override |
| QQmlEngine *             | **[engine](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#engine)**() const |
| QList<QQmlError>         | **[errors](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#errors)**() const |
| QSurfaceFormat           | **[format](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format)**() const |
| QImage                   | **[grabFramebuffer](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabFramebuffer)**() const |
| QSize                    | **[initialSize](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initialSize)**() const |
| QQuickWindow *           | **[quickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quickWindow)**() const |
| QQuickWidget::ResizeMode | **[resizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)**() const |
| QQmlContext *            | **[rootContext](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootContext)**() const |
| QQuickItem *             | **[rootObject](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootObject)**() const |
| void                     | **[setClearColor](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClearColor)**(const QColor &*color*) |
| void                     | **[setFormat](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFormat)**(const QSurfaceFormat &*format*) |
| void                     | **[setResizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)**(QQuickWidget::ResizeMode) |
| QUrl                     | **[source](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source)**() const |
| QQuickWidget::Status     | **[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status-prop)**() const |

## 公共槽

| void | **[setSource](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)**(const QUrl &*url*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 信号

| void | **[sceneGraphError](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneGraphError)**(QQuickWindow::SceneGraphError *error*, const QString &*message*) |
| ---- | ------------------------------------------------------------ |
| void | **[statusChanged](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusChanged)**(QQuickWidget::Status *status*) |

## 重载的函数

| virtual void | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QDragEnterEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **e*) override |
| virtual void | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **e*) override |
| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **e*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **event*) override |
| virtual bool | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **event*) override |
| virtual void | **[hideEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideEvent)**(QHideEvent *) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **e*) override |
| virtual void | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent *) override |
| virtual void | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QWheelEvent **e*) override |

## 详细说明

这是一个方便的包装[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当给定主源文件的 URL 时，它将自动加载并显示 QML 场景。或者，您可以使用实例化您自己的对象[QQmlComponent](https://doc-qt-io.translate.goog/qt-6/qqmlcomponent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并将它们放置在手动设置的 QQuickWidget 中。

典型用法：

```
QQuickWidget *view = new QQuickWidget;
view->setSource(QUrl::fromLocalFile("myqmlfile.qml"));
view->show();
```

要接收与使用 QQuickWidget 加载和执行 QML 相关的错误，您可以连接到[statusChanged](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusChanged)() 信号和监视器[QQuickWidget::Error](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)。错误可通过[QQuickWidget::errors](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#errors)()。

QQuickWidget 还管理视图和根对象的大小。默认情况下，[resizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)是[SizeViewToRootObject](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)，这将加载组件并将其大小调整为视图的大小。或者，[resizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)可以设置为[SizeRootObjectToView](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)这会将视图大小调整为根对象的大小。

### 性能考虑因素

QQuickWidget 是使用的替代方法[QQuickView](https://doc-qt-io.translate.goog/qt-6/qquickview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QWidget::createWindowContainer](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createWindowContainer)()。对堆叠顺序的限制不适用，这使得 QQuickWidget 成为更灵活的替代方案，其行为更像普通的小部件。

然而，上述优点是以牺牲性能为代价的：

- 不像[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QQuickView](https://doc-qt-io.translate.goog/qt-6/qquickview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，QQuickWidget 涉及至少一个针对屏幕外颜色缓冲区（通常是 2D 纹理）的附加渲染通道，然后绘制纹理四边形。这意味着负载增加，尤其是 GPU 的片段处理。
- 使用 QQuickWidget 禁用[threaded render loop](https://doc-qt-io.translate.goog/qt-6/qtquick-visualcanvas-scenegraph.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#threaded-render-loop)在所有平台上。这意味着线程渲染的一些好处，例如[Animator](https://doc-qt-io.translate.goog/qt-6/qml-qtquick-animator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类和垂直同步驱动的动画将不可用。

**注意：**避免打电话[winId](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#winId)() 在 QQuickWidget 上。此函数会触发本机窗口的创建，从而导致性能下降并可能出现渲染故障。QQuickWidget 的全部目的是在没有单独的本机窗口的情况下渲染快速场景，因此应始终避免使其成为本机小部件。

### 图形API支持

QQuickWidget 可与 Qt Quick 支持的所有 3D 图形 API 以及`software`后端一起使用。然而，其他后端（例如 OpenVG）不兼容，尝试构建 QQuickWidget 将导致问题。

覆盖平台的默认图形 API 的方式与[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QQuickView](https://doc-qt-io.translate.goog/qt-6/qquickview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp): 要么通过调用[QQuickWindow::setGraphicsApi](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGraphicsApi)() 早在构造第一个 QQuickWidget 之前，或者通过设置`QSG_RHI_BACKEND`环境变量。

**注意：**一个顶层窗口只能使用一个图形API进行渲染。例如，尝试使用 Vulkan 和[QOpenGLWidget](https://doc-qt-io.translate.goog/qt-6/qopenglwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在同一顶级窗口的小部件层次结构中，将会出现问题，并且其中一个小部件将不会按预期呈现。

### 场景图和上下文持久性

QQuickWidget荣誉[QQuickWindow::isPersistentSceneGraph](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentSceneGraph)()，意味着应用程序可以通过调用来决定[QQuickWindow::setPersistentSceneGraph](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPersistentSceneGraph)() 在从返回的窗口上[quickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quickWindow)() 函数 - 让场景图节点和其他 Qt Quick 场景相关资源在小部件隐藏时被释放。默认情况下启用持久性，就像[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

当使用 OpenGL 运行时，[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)还提供了禁用持久 OpenGL 上下文的可能性。当前，QQuickWidget 会忽略此设置，并且上下文始终是持久的。因此，隐藏小部件时 OpenGL 上下文不会被破坏。仅当小部件被销毁或小部件重新成为另一个顶级小部件的子层次结构时，上下文才会被销毁。然而，一些应用程序，特别是那些由于在 Qt Quick 场景中执行自定义 OpenGL 渲染而拥有自己的图形资源的应用程序，可能希望禁用后者，因为它们可能不准备在将 QQuickWidget 移动到另一个窗口。此类应用程序可以设置 QCoreApplication::AA_ShareOpenGLContexts 属性。有关资源初始化和清理细节的讨论，请参阅[QOpenGLWidget](https://doc-qt-io.translate.goog/qt-6/qopenglwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档。

**注意：** QQuickWidget 对其内部 OpenGL 上下文提供的细粒度控制比[QOpenGLWidget](https://doc-qt-io.translate.goog/qt-6/qopenglwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并且存在细微的差异，最值得注意的是，无论 QCoreApplication::AA_ShareOpenGLContexts 是否存在，禁用持久场景图都会导致窗口更改时破坏上下文。

### 局限性

将其他小部件放在下面并使 QQuickWidget 透明不会导致预期的结果：下面的小部件将不可见。这是因为实际上 QQuickWidget 是在所有其他常规非 OpenGL 小部件之前绘制的，因此透明类型的解决方案是不可行的。其他类型的布局，例如在 QQuickWidget 之上放置小部件，将按预期运行。

当绝对必要时，可以通过设置来克服此限制[Qt::WA_AlwaysStackOnTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)QQuickWidget 上的属性。但请注意，这会破坏堆叠顺序。例如，在 QQuickWidget 之上不可能有其他小部件，因此它只能在需要半透明 QQuickWidget 且其他小部件在下面可见的情况下使用。

仅当同一窗口内的 QQuickWidget 下面有其他小部件时，此限制才适用。使窗口半透明，其他应用程序和桌面在后台可见，是通过传统方式完成的：设置[Qt::WA_TranslucentBackground](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)在顶层窗口中，请求一个 Alpha 通道，并将 Qt Quick Scenegraph 的透明颜色更改为[Qt::transparent](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum)通过[setClearColor](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClearColor)()。

### Tab 键处理

按下该`[TAB]`键后，QQuickWidget 内的项目将获得焦点。如果该项目可以处理`[TAB]`按键，则焦点将在该项目内相应地改变，否则焦点链中的下一个小部件将获得焦点。

**也可以看看**[Exposing Attributes of C++ Types to QML](https://doc-qt-io.translate.goog/qt-6/qtqml-cppintegration-exposecppattributes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Qt Quick Widgets Example](https://doc-qt-io.translate.goog/qt-6/qtquick-quickwidgets-quickwidget-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QQuickView](https://doc-qt-io.translate.goog/qt-6/qquickview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QQuickWidget::ResizeMode

该枚举指定如何调整视图大小。

| 持续的                               | 价值 | 描述                                       |
| ------------------------------------ | ---- | ------------------------------------------ |
| `QQuickWidget::SizeViewToRootObject` | `0`  | 视图随 QML 中的根项调整大小。              |
| `QQuickWidget::SizeRootObjectToView` | `1`  | 视图会自动将根项目的大小调整为视图的大小。 |

### enum QQuickWidget::Status

指定加载状态[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

| 持续的                  | 价值 | 描述                                                         |
| ----------------------- | ---- | ------------------------------------------------------------ |
| `QQuickWidget::Null`    | `0`  | 这[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)没有源集。 |
| `QQuickWidget::Ready`   | `1`  | 这[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)已加载并创建 QML 组件。 |
| `QQuickWidget::Loading` | `2`  | 这[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)正在加载网络数据。 |
| `QQuickWidget::Error`   | `3`  | 发生一个或多个错误。称呼[errors](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#errors)() 检索错误列表。 |

## 财产文件

### resizeMode : [ResizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)

确定视图是否应调整窗口内容的大小。

如果该属性设置为[SizeViewToRootObject](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)（默认），视图大小调整为 QML 中根项的大小。

如果该属性设置为[SizeRootObjectToView](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)，视图会自动将根项目的大小调整为视图的大小。

不管这个属性如何，视图的 sizeHint 都是根项的初始大小。但请注意，由于 QML 可能会动态加载，因此该大小可能会发生变化。

**访问功能：**

| QQuickWidget::ResizeMode | **resizeMode**() const                      |
| ------------------------ | ------------------------------------------- |
| void                     | **setResizeMode**(QQuickWidget::ResizeMode) |

**也可以看看**[initialSize](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initialSize)()。

### source : [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存 QML 组件源的 URL。

确保提供的 URL 完整且正确，特别是使用[QUrl::fromLocalFile](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromLocalFile)() 从本地文件系统加载文件时。

**注意：**设置源 URL 将导致 QML 组件被实例化，即使 URL 与当前值相比没有变化。

**访问功能：**

| QUrl | **[source](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source)**() const |
| ---- | ------------------------------------------------------------ |
| void | **[setSource](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)**(const QUrl &*url*) |

### `[read-only]`status : const [Status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)

组件的电流[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)。

**访问功能：**

| QQuickWidget::Status | **status**() const |
| -------------------- | ------------------ |
|                      |                    |

**通知器信号：**

| void | **[statusChanged](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusChanged)**(QQuickWidget::Status *status*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 成员函数文档

### `[explicit]`QQuickWidget::QQuickWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个 QQuickWidget*parent*。默认值为*parent*是 0。

### QQuickWidget::QQuickWidget([QQmlEngine](https://doc-qt-io.translate.goog/qt-6/qqmlengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **engine*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*)

使用给定的 QML 构造一个 QQuickWidget*engine*和*parent*。

注意：在这种情况下，QQuickWidget 不拥有给定的*engine*目的; 调用者有责任销毁引擎。如果*engine*在视图之前被删除，[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status-prop)（） 将返回[QQuickWidget::Error](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)。

**也可以看看**[Status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status-prop)（）， 和[errors](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#errors)()。

### `[explicit]`QQuickWidget::QQuickWidget(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的 QML 构造一个 QQuickWidget*source*和*parent*。默认值为*parent*是 0。

### `[override virtual]`QQuickWidget::~QQuickWidget()

摧毁了[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[override virtual protected]`void QQuickWidget::dragEnterEvent([QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（QDragEnterEvent *事件）。

### `[override virtual protected]`void QQuickWidget::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

### `[override virtual protected]`void QQuickWidget::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[override virtual protected]`void QQuickWidget::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dropEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### [QQmlEngine](https://doc-qt-io.translate.goog/qt-6/qqmlengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QQuickWidget::engine() const

返回一个指向[QQmlEngine](https://doc-qt-io.translate.goog/qt-6/qqmlengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于实例化 QML 组件。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QQmlError](https://doc-qt-io.translate.goog/qt-6/qqmlerror.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QQuickWidget::errors() const

返回上次编译或创建操作期间发生的错误列表。当状态不是[Error](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)，返回一个空列表。

**也可以看看**[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status-prop)。

### `[override virtual protected]`bool QQuickWidget::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`void QQuickWidget::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[override virtual protected]`bool QQuickWidget::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QQuickWidget::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

### [QSurfaceFormat](https://doc-qt-io.translate.goog/qt-6/qsurfaceformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QQuickWidget::format() const

返回实际的表面格式。

如果小部件尚未显示，则返回请求的格式。

**也可以看看**[setFormat](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFormat)()。

### [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QQuickWidget::grabFramebuffer() const

渲染一帧并将其读回到图像中。

**注意：**这是一个潜在昂贵的操作。

### `[override virtual protected]`void QQuickWidget::hideEvent([QHideEvent](https://doc-qt-io.translate.goog/qt-6/qhideevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::hideEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hideEvent)（QHideEvent *事件）。

### [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QQuickWidget::initialSize() const

返回根对象的初始大小。

如果[resizeMode](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeMode-prop)是[SizeRootObjectToView](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResizeMode-enum)，根对象的大小将调整为视图的大小。此函数返回根对象在调整大小之前的大小。

### `[override virtual protected]`void QQuickWidget::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

### `[override virtual protected]`void QQuickWidget::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（QKeyEvent *事件）。

### `[override virtual protected]`void QQuickWidget::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QQuickWidget::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QQuickWidget::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QQuickWidget::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QQuickWidget::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### [QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QQuickWidget::quickWindow() const

返回屏幕外[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该小部件使用它来驱动 Qt Quick 渲染。如果您想使用，这很有用[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当前未公开的 API[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，例如连接到[QQuickWindow::beforeRendering](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beforeRendering)() 信号以便在 Qt Quick 自己的渲染下绘制本机 OpenGL 内容。

**警告：**请谨慎使用该函数的返回值。特别是，切勿试图展示[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并在使用其他时要非常小心[QWindow](https://doc-qt-io.translate.goog/qt-6/qwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)-仅限 API。

**警告：**在屏幕外窗口的生命周期内可能会被删除（并重新创建）[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，特别是当小部件移动到另一个小部件时[QQuickWindow](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。如果您需要知道窗户何时被更换，请连接到其[destroyed](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#destroyed)（） 信号。

### [QQmlContext](https://doc-qt-io.translate.goog/qt-6/qqmlcontext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QQuickWidget::rootContext() const

该函数返回上下文层次结构的根。每个 QML 组件都在一个实例中实例化[QQmlContext](https://doc-qt-io.translate.goog/qt-6/qqmlcontext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[QQmlContext](https://doc-qt-io.translate.goog/qt-6/qqmlcontext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)' 对于将数据传递到 QML 组件至关重要。在 QML 中，上下文按层次结构排列，并且该层次结构由[QQmlEngine](https://doc-qt-io.translate.goog/qt-6/qqmlengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QQuickItem](https://doc-qt-io.translate.goog/qt-6/qquickitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QQuickWidget::rootObject() const

返回视图的根[item](https://doc-qt-io.translate.goog/qt-6/qquickitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。可以为空，当[setSource](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 还没有被调用，如果是用broken调用的话[QtQuick](https://doc-qt-io.translate.goog/qt-6/qtquick-module.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代码或同时[QtQuick](https://doc-qt-io.translate.goog/qt-6/qtquick-module.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)内容正在创建中。

### `[signal]`void QQuickWidget::sceneGraphError([QQuickWindow::SceneGraphError](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneGraphError-enum) *error*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*message*)

当一个*error*发生在场景图初始化期间。

如果应用程序希望以自定义方式处理错误（例如 OpenGL 上下文创建失败），则应连接到此信号。当没有插槽连接到信号时，行为会有所不同：快速将打印*message*，或显示消息框，然后终止应用程序。

该信号将从 GUI 线程发出。

**也可以看看**[QQuickWindow::sceneGraphError](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneGraphError)()。

### void QQuickWidget::setClearColor(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

设置清除*color*。默认情况下，这是不透明的颜色。

为了得到半透明的[QQuickWidget](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，调用此函数*color*设置[Qt::transparent](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum)，设置[Qt::WA_TranslucentBackground](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)顶级窗口上的 widget 属性，并通过以下方式请求 alpha 通道[setFormat](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFormat)()。

**也可以看看**[QQuickWindow::setColor](https://doc-qt-io.translate.goog/qt-6/qquickwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color-prop)()。

### void QQuickWidget::setFormat(const [QSurfaceFormat](https://doc-qt-io.translate.goog/qt-6/qsurfaceformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置曲面*format*用于此小部件使用的上下文和屏幕外表面。

当需要请求给定 OpenGL 版本或配置文件的上下文时，调用此函数。深度、模板和 Alpha 缓冲区的大小会自动处理，无需明确请求。

**也可以看看**[QWindow::setFormat](https://doc-qt-io.translate.goog/qt-6/qwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFormat)(),[QWindow::format](https://doc-qt-io.translate.goog/qt-6/qwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format)（）， 和[format](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format)()。

### `[slot]`void QQuickWidget::setSource(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*url*)

将源设置为*url*，加载 QML 组件并实例化它。

确保提供的 URL 完整且正确，特别是使用[QUrl::fromLocalFile](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromLocalFile)() 从本地文件系统加载文件时。

使用相同的 URL 多次调用此方法将导致 QML 组件被重新实例化。

**注意：**属性的 Setter 函数[source](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source)。

**也可以看看**[source](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source)()。

### `[override virtual protected]`void QQuickWidget::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QQuickWidget::source() const

返回源 URL（如果已设置）。

**注意：**属性源的 Getter 函数。

**也可以看看**[setSource](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)()。

### `[signal]`void QQuickWidget::statusChanged([QQuickWidget::Status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum) *status*)

当组件的电流*status*变化。

**注意：**属性的通知程序信号[status](https://doc-qt-io.translate.goog/qt-6/qquickwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status-prop)。

### `[override virtual protected]`void QQuickWidget::wheelEvent([QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)（QWheelEvent *事件）。