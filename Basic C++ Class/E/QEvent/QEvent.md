#  QEvent Class

QEvent 类是所有事件类的基类。事件对象包含事件参数。[更多的...](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QEvent>                                           |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:        | QT += core                                                   |
| Inherited By: | [QActionEvent](https://doc-qt-io.translate.goog/qt-6/qactionevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QCloseEvent](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QDynamicPropertyChangeEvent](https://doc-qt-io.translate.goog/qt-6/qdynamicpropertychangeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QExposeEvent](https://doc-qt-io.translate.goog/qt-6/qexposeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QFileOpenEvent](https://doc-qt-io.translate.goog/qt-6/qfileopenevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QGestureEvent](https://doc-qt-io.translate.goog/qt-6/qgestureevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QGraphicsSceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicssceneevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QHideEvent](https://doc-qt-io.translate.goog/qt-6/qhideevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QIconDragEvent](https://doc-qt-io.translate.goog/qt-6/qicondragevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QInputEvent](https://doc-qt-io.translate.goog/qt-6/qinputevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QInputMethodQueryEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodqueryevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QMoveEvent](https://doc-qt-io.translate.goog/qt-6/qmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QPlatformSurfaceEvent](https://doc-qt-io.translate.goog/qt-6/qplatformsurfaceevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QScrollEvent](https://doc-qt-io.translate.goog/qt-6/qscrollevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QScrollPrepareEvent](https://doc-qt-io.translate.goog/qt-6/qscrollprepareevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QShortcutEvent](https://doc-qt-io.translate.goog/qt-6/qshortcutevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QStateMachine::SignalEvent](https://doc-qt-io.translate.goog/qt-6/qstatemachine-signalevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QStateMachine::WrappedEvent](https://doc-qt-io.translate.goog/qt-6/qstatemachine-wrappedevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QStatusTipEvent](https://doc-qt-io.translate.goog/qt-6/qstatustipevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QWhatsThisClickedEvent](https://doc-qt-io.translate.goog/qt-6/qwhatsthisclickedevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QWindowStateChangeEvent](https://doc-qt-io.translate.goog/qt-6/qwindowstatechangeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qevent-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QEvent 是[事件类](https://doc-qt-io.translate.goog/qt-6/events.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| enum | **[Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)** { None, ActionAdded, ActionChanged, ActionRemoved, ActivationChange, …, MaxUser } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 特性

- **[accepted](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted-prop)** : bool

## 公共职能

|                  | **[QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QEvent-2)**(QEvent::Type *type*) |
| ---------------- | ------------------------------------------------------------ |
| virtual          | **[~QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QEvent)**() |
| void             | **[accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)**() |
| virtual QEvent * | **[clone](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clone)**() const |
| void             | **[ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)**() |
| bool             | **[isAccepted](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted-prop)**() const |
| bool             | **[isInputEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isInputEvent)**() const |
| bool             | **[isPointerEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPointerEvent)**() const |
| bool             | **[isSinglePointEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSinglePointEvent)**() const |
| virtual void     | **[setAccepted](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted-prop)**(bool *accepted*) |
| bool             | **[spontaneous](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spontaneous)**() const |
| QEvent::Type     | **[type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)**() const |

## 静态公共成员

| int  | **[registerEventType](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#registerEventType)**(int *hint* = -1) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 详细说明

Qt 的主事件循环（[QCoreApplication::exec](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()) 从事件队列中获取本机窗口系统事件，将其转换为 QEvents，并将转换后的事件发送到[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)s。

一般来说，事件来自底层窗口系统（[spontaneous](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spontaneous)() 返回`true`)，但也可以使用手动发送事件[QCoreApplication::sendEvent](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sendEvent)（） 和[QCoreApplication::postEvent](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#postEvent)()([spontaneous](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spontaneous)() 返回`false`)。

[QObjects](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过让他们接收事件[QObject::event](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)() 函数被调用。该函数可以在子类中重新实现，以自定义事件处理并添加额外的事件类型；[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)() 就是一个显着的例子。默认情况下，事件被分派到事件处理程序，例如[QObject::timerEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（） 和[QWidget::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)()。[QObject::installEventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installEventFilter)() 允许一个对象拦截发往另一个对象的事件。

基本的 QEvent 仅包含一个事件类型参数和一个“接受”标志。接受标志设置为[accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)()，并用[ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)()。它是默认设置的，但不要依赖于此，因为子类可能会选择在其构造函数中清除它。

QEvent 的子类包含描述特定事件的附加参数。

**也可以看看**[QObject::event](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)(),[QObject::installEventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installEventFilter)(),[QCoreApplication::sendEvent](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sendEvent)(),[QCoreApplication::postEvent](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#postEvent)（）， 和[QCoreApplication::processEvents](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#processEvents)()。

## 会员类型文档

### enum QEvent::Type

该枚举类型定义了 Qt 中的有效事件类型。事件类型和每种类型的专门类如下：

| 持续的                                          | 价值                  | 描述                                                         |
| ----------------------------------------------- | --------------------- | ------------------------------------------------------------ |
| `QEvent::None`                                  | `0`                   | 不是一个事件。                                               |
| `QEvent::ActionAdded`                           | `114`                 | 添加了一个新动作（[QActionEvent](https://doc-qt-io.translate.goog/qt-6/qactionevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ActionChanged`                         | `113`                 | 动作已更改（[QActionEvent](https://doc-qt-io.translate.goog/qt-6/qactionevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ActionRemoved`                         | `115`                 | 一个动作已被删除（[QActionEvent](https://doc-qt-io.translate.goog/qt-6/qactionevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ActivationChange`                      | `99`                  | 小部件的顶级窗口激活状态已更改。                             |
| `QEvent::ApplicationActivate`                   | `121`                 | 该枚举已被弃用。请改用 ApplicationStateChange。              |
| `QEvent::ApplicationActivated`                  | `ApplicationActivate` | 该枚举已被弃用。请改用 ApplicationStateChange。              |
| `QEvent::ApplicationDeactivate`                 | `122`                 | 该枚举已被弃用。请改用 ApplicationStateChange。              |
| `QEvent::ApplicationFontChange`                 | `36`                  | 默认应用程序字体已更改。                                     |
| `QEvent::ApplicationLayoutDirectionChange`      | `37`                  | 默认应用程序布局方向已更改。                                 |
| `QEvent::ApplicationPaletteChange`              | `38`                  | 默认应用程序调色板已更改。                                   |
| `QEvent::ApplicationStateChange`                | `214`                 | 应用程序的状态已更改。                                       |
| `QEvent::ApplicationWindowIconChange`           | `35`                  | 应用程序的图标已更改。                                       |
| `QEvent::ChildAdded`                            | `68`                  | 一个对象有一个子对象 ([QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ChildPolished`                         | `69`                  | 小部件子对象被抛光（[QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ChildRemoved`                          | `71`                  | 一个对象失去了一个孩子（[QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Clipboard`                             | `40`                  | 剪贴板内容已更改。                                           |
| `QEvent::Close`                                 | `19`                  | 小部件已关闭（[QCloseEvent](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::CloseSoftwareInputPanel`               | `200`                 | 小部件想要关闭软件输入面板 (SIP)。                           |
| `QEvent::ContentsRectChange`                    | `178`                 | 小部件内容矩形的边距发生了变化。                             |
| `QEvent::ContextMenu`                           | `82`                  | 上下文弹出菜单（[QContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qcontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::CursorChange`                          | `183`                 | 小部件的光标已更改。                                         |
| `QEvent::DeferredDelete`                        | `52`                  | 对象在清理后将被删除（QDeferredDeleteEvent）                 |
| `QEvent::DevicePixelRatioChange (since Qt 6.6)` | `222`                 | 该小部件或窗口的底层后备存储的 devicePixelRatio 已更改。     |
| `QEvent::DragEnter`                             | `60`                  | 光标在拖放操作期间进入小部件（[QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::DragLeave`                             | `62`                  | 在拖放操作期间光标离开小部件（[QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::DragMove`                              | `61`                  | 拖放操作正在进行中（[QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Drop`                                  | `63`                  | 拖放操作完成（[QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::DynamicPropertyChange`                 | `170`                 | 动态属性已从对象中添加、更改或删除。                         |
| `QEvent::EnabledChange`                         | `98`                  | 小部件的启用状态已更改。                                     |
| `QEvent::Enter`                                 | `10`                  | 鼠标进入小部件的边界（[QEnterEvent](https://doc-qt-io.translate.goog/qt-6/qenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::EnterEditFocus`                        | `150`                 | 编辑器小部件获得编辑焦点。`QT_KEYPAD_NAVIGATION`必须被定义。 |
| `QEvent::EnterWhatsThisMode`                    | `124`                 | 当应用程序输入“这是什么？”时发送到顶级小部件 模式。          |
| `QEvent::Expose`                                | `206`                 | 当屏幕上的内容无效并需要从后备存储中刷新时发送到窗口。       |
| `QEvent::FileOpen`                              | `116`                 | 文件打开请求（[QFileOpenEvent](https://doc-qt-io.translate.goog/qt-6/qfileopenevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::FocusIn`                               | `8`                   | 小部件或窗口获得键盘焦点（[QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::FocusOut`                              | `9`                   | 小部件或窗口失去键盘焦点（[QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::FocusAboutToChange`                    | `23`                  | 小部件或窗口焦点即将改变（[QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)） |
| `QEvent::FontChange`                            | `97`                  | 小部件的字体已更改。                                         |
| `QEvent::Gesture`                               | `198`                 | 触发了一个手势（[QGestureEvent](https://doc-qt-io.translate.goog/qt-6/qgestureevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GestureOverride`                       | `202`                 | 触发了手势覆盖（[QGestureEvent](https://doc-qt-io.translate.goog/qt-6/qgestureevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GrabKeyboard`                          | `188`                 | 物品获得键盘抓取（[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)仅有的）。 |
| `QEvent::GrabMouse`                             | `186`                 | 物品获得鼠标抓取（[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)仅有的）。 |
| `QEvent::GraphicsSceneContextMenu`              | `159`                 | 图形场景上的上下文弹出菜单（[QGraphicsSceneContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenecontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneDragEnter`                | `164`                 | 光标在拖放操作期间进入图形场景（[QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneDragLeave`                | `166`                 | 在拖放操作期间光标离开图形场景（[QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneDragMove`                 | `165`                 | 正在场景上进行拖放操作（[QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneDrop`                     | `167`                 | 拖放操作在场景上完成（[QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneHelp`                     | `163`                 | 用户请求图形场景的帮助（[QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneHoverEnter`               | `160`                 | 鼠标光标进入图形场景中的悬停项目（[QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneHoverLeave`               | `162`                 | 鼠标光标在图形场景中留下悬停项目（[QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneHoverMove`                | `161`                 | 鼠标光标在图形场景中的悬停项目内移动（[QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneMouseDoubleClick`         | `158`                 | 在图形场景中再次按下（双击）鼠标（[QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneMouseMove`                | `155`                 | 在图形场景中移动鼠标（[QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneMousePress`               | `156`                 | 在图形场景中按下鼠标（[QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneMouseRelease`             | `157`                 | 在图形场景中释放鼠标（[QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneMove`                     | `182`                 | 小部件已移动（[QGraphicsSceneMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneResize`                   | `181`                 | 小部件已调整大小（[QGraphicsSceneResizeEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicssceneresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneWheel`                    | `168`                 | 鼠标滚轮在图形场景中滚动（[QGraphicsSceneWheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenewheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::GraphicsSceneLeave`                    | `220`                 | 光标离开图形场景（[QGraphicsSceneWheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenewheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Hide`                                  | `18`                  | 小部件被隐藏（[QHideEvent](https://doc-qt-io.translate.goog/qt-6/qhideevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::HideToParent`                          | `27`                  | 子部件已被隐藏。                                             |
| `QEvent::HoverEnter`                            | `127`                 | 鼠标光标进入悬停小部件（[QHoverEvent](https://doc-qt-io.translate.goog/qt-6/qhoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::HoverLeave`                            | `128`                 | 鼠标光标离开悬停小部件（[QHoverEvent](https://doc-qt-io.translate.goog/qt-6/qhoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::HoverMove`                             | `129`                 | 鼠标光标在悬停小部件内移动（[QHoverEvent](https://doc-qt-io.translate.goog/qt-6/qhoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::IconDrag`                              | `96`                  | 窗口的主图标已被拖走（[QIconDragEvent](https://doc-qt-io.translate.goog/qt-6/qicondragevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::IconTextChange`                        | `101`                 | 小部件的图标文本已更改。（已弃用）                           |
| `QEvent::InputMethod`                           | `83`                  | 正在使用输入法（[QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::InputMethodQuery`                      | `207`                 | 输入法查询事件（[QInputMethodQueryEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodqueryevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)） |
| `QEvent::KeyboardLayoutChange`                  | `169`                 | 键盘布局已更改。                                             |
| `QEvent::KeyPress`                              | `6`                   | 按键 （[QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::KeyRelease`                            | `7`                   | 按键释放（[QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::LanguageChange`                        | `89`                  | 应用程序翻译已更改。                                         |
| `QEvent::LayoutDirectionChange`                 | `90`                  | 布局的方向发生了变化。                                       |
| `QEvent::LayoutRequest`                         | `76`                  | 小部件布局需要重做。                                         |
| `QEvent::Leave`                                 | `11`                  | 鼠标离开小部件的边界。                                       |
| `QEvent::LeaveEditFocus`                        | `151`                 | 编辑器小部件失去编辑焦点。必须定义 QT_KEYPAD_NAVIGATION。    |
| `QEvent::LeaveWhatsThisMode`                    | `125`                 | 当应用程序离开“这是什么？”时发送到顶级小部件 模式。          |
| `QEvent::LocaleChange`                          | `88`                  | 系统区域设置已更改。                                         |
| `QEvent::NonClientAreaMouseButtonDblClick`      | `176`                 | 鼠标双击发生在客户区之外（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::NonClientAreaMouseButtonPress`         | `174`                 | 鼠标按钮按下发生在客户区之外（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::NonClientAreaMouseButtonRelease`       | `175`                 | 鼠标按钮释放发生在客户区之外（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::NonClientAreaMouseMove`                | `173`                 | 鼠标移动发生在客户区之外（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::MacSizeChange`                         | `177`                 | 用户更改了他的小部件尺寸（仅限 macOS）。                     |
| `QEvent::MetaCall`                              | `43`                  | 异步方法调用通过[QMetaObject::invokeMethod](https://doc-qt-io.translate.goog/qt-6/qmetaobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invokeMethod)()。 |
| `QEvent::ModifiedChange`                        | `102`                 | 小部件修改状态已更改。                                       |
| `QEvent::MouseButtonDblClick`                   | `4`                   | 再次按下鼠标（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::MouseButtonPress`                      | `2`                   | 鼠标按下（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::MouseButtonRelease`                    | `3`                   | 鼠标释放（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::MouseMove`                             | `5`                   | 鼠标移动（[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::MouseTrackingChange`                   | `109`                 | 鼠标跟踪状态已更改。                                         |
| `QEvent::Move`                                  | `13`                  | 小部件的位置已更改（[QMoveEvent](https://doc-qt-io.translate.goog/qt-6/qmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::NativeGesture`                         | `197`                 | 系统检测到手势（[QNativeGestureEvent](https://doc-qt-io.translate.goog/qt-6/qnativegestureevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::OrientationChange`                     | `208`                 | 屏幕方向发生变化（QScreenOrientationChangeEvent）。          |
| `QEvent::Paint`                                 | `12`                  | 需要更新屏幕（[QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::PaletteChange`                         | `39`                  | 小部件的调色板已更改。                                       |
| `QEvent::ParentAboutToChange`                   | `131`                 | 小部件父级即将更改。                                         |
| `QEvent::ParentChange`                          | `21`                  | 小部件父级已更改。                                           |
| `QEvent::PlatformPanel`                         | `212`                 | 已请求特定于平台的面板。                                     |
| `QEvent::PlatformSurface`                       | `217`                 | 本机平台表面已创建或即将被销毁（[QPlatformSurfaceEvent](https://doc-qt-io.translate.goog/qt-6/qplatformsurfaceevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Polish`                                | `75`                  | 小部件已抛光。                                               |
| `QEvent::PolishRequest`                         | `74`                  | 小部件应该被抛光。                                           |
| `QEvent::QueryWhatsThis`                        | `123`                 | 如果小部件有“这是什么？”，则它应该接受该事件。帮助 （[QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Quit`                                  | `20`                  | 应用程序已退出。                                             |
| `QEvent::ReadOnlyChange (since Qt 5.4)`         | `106`                 | 小部件的只读状态已更改。                                     |
| `QEvent::RequestSoftwareInputPanel`             | `199`                 | 小部件想要打开软件输入面板 (SIP)。                           |
| `QEvent::Resize`                                | `14`                  | 小部件的大小已更改（[QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ScrollPrepare`                         | `204`                 | 该对象需要填写其几何信息（[QScrollPrepareEvent](https://doc-qt-io.translate.goog/qt-6/qscrollprepareevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Scroll`                                | `205`                 | 对象需要滚动到提供的位置（[QScrollEvent](https://doc-qt-io.translate.goog/qt-6/qscrollevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::Shortcut`                              | `117`                 | 子项中的按键用于快捷键处理（[QShortcutEvent](https://doc-qt-io.translate.goog/qt-6/qshortcutevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ShortcutOverride`                      | `51`                  | 子级中的按键，用于覆盖快捷键处理（[QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。当快捷方式即将触发时，`ShortcutOverride`发送到活动窗口。这允许客户端（例如小部件）通过接受事件来发出信号，表明它们将自行处理快捷方式。如果接受快捷方式覆盖，则事件将作为正常按键传递到焦点小部件。否则，它会触发快捷操作（如果存在）。 |
| `QEvent::Show`                                  | `17`                  | 小部件显示在屏幕上（[QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ShowToParent`                          | `26`                  | 已显示子部件。                                               |
| `QEvent::SockAct`                               | `50`                  | 套接字激活，用于实现[QSocketNotifier](https://doc-qt-io.translate.goog/qt-6/qsocketnotifier.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。 |
| `QEvent::StateMachineSignal`                    | `192`                 | 发送到状态机的信号（[QStateMachine::SignalEvent](https://doc-qt-io.translate.goog/qt-6/qstatemachine-signalevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::StateMachineWrapped`                   | `193`                 | 该事件是另一个事件的包装，即包含另一个事件（[QStateMachine::WrappedEvent](https://doc-qt-io.translate.goog/qt-6/qstatemachine-wrappedevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::StatusTip`                             | `112`                 | 请求状态提示（[QStatusTipEvent](https://doc-qt-io.translate.goog/qt-6/qstatustipevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::StyleChange`                           | `100`                 | 小部件的样式已更改。                                         |
| `QEvent::TabletMove`                            | `87`                  | Wacom 数位板移动 ([QTabletEvent](https://doc-qt-io.translate.goog/qt-6/qtabletevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::TabletPress`                           | `92`                  | Wacom 压片机 ([QTabletEvent](https://doc-qt-io.translate.goog/qt-6/qtabletevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::TabletRelease`                         | `93`                  | Wacom 平板电脑发布 ([QTabletEvent](https://doc-qt-io.translate.goog/qt-6/qtabletevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::TabletEnterProximity`                  | `171`                 | Wacom 数位板进入接近事件 ([QTabletEvent](https://doc-qt-io.translate.goog/qt-6/qtabletevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）， 发给[QApplication](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。 |
| `QEvent::TabletLeaveProximity`                  | `172`                 | Wacom 数位板离开接近事件（[QTabletEvent](https://doc-qt-io.translate.goog/qt-6/qtabletevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）， 发给[QApplication](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。 |
| `QEvent::TabletTrackingChange (since Qt 5.9)`   | `219`                 | Wacom 数位板跟踪状态已更改。                                 |
| `QEvent::ThreadChange`                          | `22`                  | 该对象被移动到另一个线程。这是前一个线程中发送到该对象的最后一个事件。看[QObject::moveToThread](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveToThread)()。 |
| `QEvent::Timer`                                 | `1`                   | 定期定时器事件（[QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ToolBarChange`                         | `120`                 | macOS 上的工具栏按钮处于切换状态。                           |
| `QEvent::ToolTip`                               | `110`                 | 请求了工具提示（[QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::ToolTipChange`                         | `184`                 | 小部件的工具提示已更改。                                     |
| `QEvent::TouchBegin`                            | `194`                 | 一系列触摸屏或触控板事件的开始（[QTouchEvent](https://doc-qt-io.translate.goog/qt-6/qtouchevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::TouchCancel`                           | `209`                 | 取消触摸事件序列（[QTouchEvent](https://doc-qt-io.translate.goog/qt-6/qtouchevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::TouchEnd`                              | `196`                 | 触摸事件序列结束（[QTouchEvent](https://doc-qt-io.translate.goog/qt-6/qtouchevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::TouchUpdate`                           | `195`                 | 触摸屏事件（[QTouchEvent](https://doc-qt-io.translate.goog/qt-6/qtouchevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::UngrabKeyboard`                        | `189`                 | 项目失去键盘抓取（[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)仅有的）。 |
| `QEvent::UngrabMouse`                           | `187`                 | 物品失去鼠标抓取能力（[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QQuickItem](https://doc-qt-io.translate.goog/qt-6/qquickitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::UpdateLater`                           | `78`                  | 小部件应该排队以便稍后重新绘制。                             |
| `QEvent::UpdateRequest`                         | `77`                  | 该小部件应该重新绘制。                                       |
| `QEvent::WhatsThis`                             | `111`                 | 小部件应该显示“这是什么？” 帮助 （[QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::WhatsThisClicked`                      | `118`                 | 小部件“这是什么？”中的链接 单击帮助。                        |
| `QEvent::Wheel`                                 | `31`                  | 鼠标滚轮滚动（[QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::WinEventAct`                           | `132`                 | 发生了 Windows 特定的激活事件。                              |
| `QEvent::WindowActivate`                        | `24`                  | 窗口被激活。                                                 |
| `QEvent::WindowBlocked`                         | `103`                 | 该窗口被模式对话框挡住。                                     |
| `QEvent::WindowDeactivate`                      | `25`                  | 窗口已停用。                                                 |
| `QEvent::WindowIconChange`                      | `34`                  | 窗口的图标已更改。                                           |
| `QEvent::WindowStateChange`                     | `105`                 | 这[window's state](https://doc-qt-io.translate.goog/qt-6/qwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowState)（最小化、最大化或全屏）已更改（[QWindowStateChangeEvent](https://doc-qt-io.translate.goog/qt-6/qwindowstatechangeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。 |
| `QEvent::WindowTitleChange`                     | `33`                  | 窗口标题已更改。                                             |
| `QEvent::WindowUnblocked`                       | `104`                 | 模式对话框退出后，窗口将解除阻塞。                           |
| `QEvent::WinIdChange`                           | `203`                 | 此本机小部件的窗口系统标识符已更改。                         |
| `QEvent::ZOrderChange`                          | `126`                 | 小部件的 z 顺序已更改。该事件永远不会发送到顶级窗口。        |

用户事件的值应介于`User`和之间`MaxUser`：

| 持续的            | 价值    | 描述              |
| ----------------- | ------- | ----------------- |
| `QEvent::User`    | `1000`  | 用户定义的事件。  |
| `QEvent::MaxUser` | `65535` | 上次用户事件 ID。 |

为了方便起见，您可以使用[registerEventType](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#registerEventType)() 函数为您的应用程序注册和保留自定义事件类型。这样做可以避免意外地重复使用应用程序中其他地方已使用的自定义事件类型。

## 财产文件

### accepted : bool

该属性保存事件对象的接受标志。

设置accept参数表明事件接收者想要该事件。不需要的事件可能会传播到父窗口小部件。默认情况下，isAccepted() 设置为 true，但不要依赖于此，因为子类可能会选择在其构造函数中清除它。

为了方便起见，还可以设置接受标志[accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)()，并用[ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)()。

**注：**接受[QPointerEvent](https://doc-qt-io.translate.goog/qt-6/qpointerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)隐含地[accepts](https://doc-qt-io.translate.goog/qt-6/qeventpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted-prop)一切[points](https://doc-qt-io.translate.goog/qt-6/qpointerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#points)事件所承载的。

**访问功能：**

| bool         | **isAccepted**() const           |
| ------------ | -------------------------------- |
| virtual void | **setAccepted**(bool *accepted*) |

## 成员函数文档

### `[explicit]`QEvent::QEvent([QEvent::Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) *type*)

构造一个类型的事件对象*type*。

### `[virtual noexcept]`QEvent::~QEvent()

破坏事件。如果它是[posted](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#postEvent)，它将从要发布的事件列表中删除。

### void QEvent::accept()

设置事件对象的接受标志，相当于调用[setAccepted](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted-prop)（真的）。

设置accept参数表明事件接收者想要该事件。不需要的事件可能会传播到父窗口小部件。

**也可以看看**[ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)()。

### `[virtual, since 6.0]`QEvent *QEvent::clone() const

创建并返回此事件的相同副本。

这个函数是在Qt 6.0中引入的。

### void QEvent::ignore()

清除事件对象的接受标志参数，相当于调用[setAccepted](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted-prop)（错误的）。

清除accept参数表明事件接收者不想要该事件。不需要的事件可能会传播到父窗口小部件。

**也可以看看**[accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)()。

### `[noexcept, since 6.0]`bool QEvent::isInputEvent() const

`true`如果事件对象是一个则返回[QInputEvent](https://doc-qt-io.translate.goog/qt-6/qinputevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或其子类之一。

这个函数是在Qt 6.0中引入的。

### `[noexcept, since 6.0]`bool QEvent::isPointerEvent() const

`true`如果事件对象是一个则返回[QPointerEvent](https://doc-qt-io.translate.goog/qt-6/qpointerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或其子类之一。

这个函数是在Qt 6.0中引入的。

### `[noexcept, since 6.0]`bool QEvent::isSinglePointEvent() const

`true`如果事件对象是以下对象的子类，则返回[QSinglePointEvent](https://doc-qt-io.translate.goog/qt-6/qsinglepointevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

这个函数是在Qt 6.0中引入的。

### `[static noexcept]`int QEvent::registerEventType(int *hint* = -1)

注册并返回自定义事件类型。这*hint*如果提供的可用，则使用它，否则将返回一个介于[QEvent::User](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)和[QEvent::MaxUser](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)尚未注册。这*hint*如果其值不在之间，则被忽略[QEvent::User](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)和[QEvent::MaxUser](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。

如果所有可用值已被获取或程序正在关闭，则返回 -1。

**注：**该函数是[thread-safe](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### bool QEvent::spontaneous() const

`true`如果事件源自应用程序外部（系统事件），则返回；否则返回`false`.

### [QEvent::Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) QEvent::type() const

返回事件类型。