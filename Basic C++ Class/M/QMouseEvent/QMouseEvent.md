#  QMouseEvent Class

QMouseEvent 类包含描述鼠标事件的参数。[更多的...](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QMouseEvent>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:    | QT += gui                                                    |
| Inherits: | [QSinglePointEvent](https://doc-qt-io.translate.goog/qt-6/qsinglepointevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qmouseevent-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qmouseevent-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QMouseEvent 是[事件类](https://doc-qt-io.translate.goog/qt-6/events.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共职能

|                     | **[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMouseEvent-3)**(QEvent::Type *type*, const QPointF &*localPos*, const QPointF &*globalPos*, Qt::MouseButton *button*, Qt::MouseButtons *buttons*, Qt::KeyboardModifiers *modifiers*, const QPointingDevice **device* = QPointingDevice::primaryPointingDevice()) |
| ------------------- | ------------------------------------------------------------ |
|                     | **[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMouseEvent-4)**(QEvent::Type *type*, const QPointF &*localPos*, const QPointF &*scenePos*, const QPointF &*globalPos*, Qt::MouseButton *button*, Qt::MouseButtons *buttons*, Qt::KeyboardModifiers *modifiers*, const QPointingDevice **device* = QPointingDevice::primaryPointingDevice()) |
| Qt::MouseEventFlags | **[flags](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)**() const |

## 详细说明

当在小部件内按下或释放鼠标按钮或移动鼠标光标时，会发生鼠标事件。

仅当按下鼠标按钮时才会发生鼠标移动事件，除非已启用鼠标跟踪[QWidget::setMouseTracking](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseTracking-prop)()。

当在小部件内按下鼠标按钮时，Qt 会自动捕获鼠标；小部件将继续接收鼠标事件，直到释放最后一个鼠标按钮。

鼠标事件包含一个特殊的接受标志，指示接收者是否想要该事件。你应该打电话[ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)() 如果您的小部件未处理鼠标事件。鼠标事件沿着父窗口部件链向上传播，直到窗口部件接受它[accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)()，或者事件过滤器消耗它。

**注意：**如果鼠标事件被传播到[widget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)为此[Qt::WA_NoMousePropagation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)设置后，该鼠标事件将不会进一步传播到父窗口小部件链。

键盘修饰键的状态可以通过调用[modifiers](https://doc-qt-io.translate.goog/qt-6/qinputevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modifiers)() 函数，继承自[QInputEvent](https://doc-qt-io.translate.goog/qt-6/qinputevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

这[position](https://doc-qt-io.translate.goog/qt-6/qsinglepointevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 函数给出相对于接收鼠标事件的小部件或项目的光标位置。如果由于鼠标事件而移动小部件，请使用由[globalPosition](https://doc-qt-io.translate.goog/qt-6/qsinglepointevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#globalPosition)() 以避免晃动。

这[QWidget::setEnabled](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enabled-prop)() 函数可用于启用或禁用小部件的鼠标和键盘事件。

重新实施[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)事件处理程序，[QWidget::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[QWidget::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(),[QWidget::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（）， 和[QWidget::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)() 在您自己的小部件中接收鼠标事件。

**也可以看看**[QWidget::setMouseTracking](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseTracking-prop)(),[QWidget::grabMouse](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabMouse)（）， 和[QCursor::pos](https://doc-qt-io.translate.goog/qt-6/qcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)()。

## 成员函数文档

### QMouseEvent::QMouseEvent([QEvent::Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) *type*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*localPos*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*globalPos*, [Qt::MouseButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum) *button*, [Qt::MouseButtons](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum) *buttons*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*, const [QPointingDevice](https://doc-qt-io.translate.goog/qt-6/qpointingdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device* = QPointingDevice::primaryPointingDevice())

构造一个鼠标事件对象，源自*device*。

这*type*参数必须是[QEvent::MouseButtonPress](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum),[QEvent::MouseButtonRelease](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum),[QEvent::MouseButtonDblClick](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)， 或者[QEvent::MouseMove](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。

这*localPos*是鼠标光标相对于接收小部件或项目的位置。光标在屏幕坐标中的位置由下式指定*globalPos*。窗口位置设置为与*localPos*。这*button*导致事件的值给出为[Qt::MouseButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum)枚举。如果事件*type*是[MouseMove](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)，此事件的相应按钮是[Qt::NoButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum)。*buttons*是事件发生时所有按钮的状态，*modifiers*所有键盘修饰符的状态。

### QMouseEvent::QMouseEvent([QEvent::Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) *type*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*localPos*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*scenePos*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*globalPos*, [Qt::MouseButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum) *button*, [Qt::MouseButtons](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum) *buttons*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*, const [QPointingDevice](https://doc-qt-io.translate.goog/qt-6/qpointingdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device* = QPointingDevice::primaryPointingDevice())

构造一个鼠标事件对象。

这*type*参数必须是[QEvent::MouseButtonPress](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum),[QEvent::MouseButtonRelease](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum),[QEvent::MouseButtonDblClick](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)， 或者[QEvent::MouseMove](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。

要点*localPos*,*scenePos*和*globalPos*分别指定鼠标光标相对于接收小部件或项目、窗口以及屏幕或桌面的位置。

这*button*导致事件的值给出为[Qt::MouseButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum)枚举。如果事件*type*是[MouseMove](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)，此事件的相应按钮是[Qt::NoButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum)。*buttons*是事件发生时所有按钮的状态，*modifiers*是所有键盘修饰符的状态。

### [Qt::MouseEventFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseEventFlag-enum) QMouseEvent::flags() const

返回鼠标事件标志。

鼠标事件标志提供有关鼠标事件的附加信息。

**也可以看看**[Qt::MouseEventFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseEventFlag-enum)和[QGraphicsSceneMouseEvent::flags](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)()。