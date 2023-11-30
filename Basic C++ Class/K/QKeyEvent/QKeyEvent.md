#  QKeyEvent Class

QKeyEvent 类描述了按键事件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QKeyEvent>                                        |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:    | QT += gui                                                    |
| Inherits: | [QInputEvent](https://doc-qt-io.translate.goog/qt-6/qinputevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qkeyevent-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QKeyEvent 是[事件类](https://doc-qt-io.translate.goog/qt-6/events.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共职能

|                       | **[QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QKeyEvent-2)**(QEvent::Type *type*, int *key*, Qt::KeyboardModifiers *modifiers*, const QString &*text* = QString(), bool *autorep* = false, quint16 *count* = 1) |
| --------------------- | ------------------------------------------------------------ |
|                       | **[QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QKeyEvent-3)**(QEvent::Type *type*, int *key*, Qt::KeyboardModifiers *modifiers*, quint32 *nativeScanCode*, quint32 *nativeVirtualKey*, quint32 *nativeModifiers*, const QString &*text* = QString(), bool *autorep* = false, quint16 *count* = 1, const QInputDevice **device* = QInputDevice::primaryKeyboard()) |
| int                   | **[count](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**() const |
| bool                  | **[isAutoRepeat](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAutoRepeat)**() const |
| int                   | **[key](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)**() const |
| QKeyCombination       | **[keyCombination](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyCombination)**() const |
| bool                  | **[matches](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#matches)**(QKeySequence::StandardKey *key*) const |
| Qt::KeyboardModifiers | **[modifiers](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modifiers)**() const |
| quint32               | **[nativeModifiers](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nativeModifiers)**() const |
| quint32               | **[nativeScanCode](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nativeScanCode)**() const |
| quint32               | **[nativeVirtualKey](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nativeVirtualKey)**() const |
| QString               | **[text](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)**() const |

## 详细说明

当按下或释放按键时，按键事件将发送到具有键盘输入焦点的小部件。

按键事件包含一个特殊的接受标志，指示接收者是否将处理按键事件。该标志默认设置为[QEvent::KeyPress](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)和[QEvent::KeyRelease](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)，所以不需要调用[accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)() 对关键事件采取行动时。为了[QEvent::ShortcutOverride](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)接收者需要显式接受事件才能触发覆盖。呼唤[ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)按键事件上的 () 会将其传播到父窗口小部件。该事件沿着父窗口小部件链向上传播，直到窗口小部件接受它或事件过滤器使用它。

这[QWidget::setEnabled](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enabled-prop)() 函数可用于启用或禁用小部件的鼠标和键盘事件。

事件处理程序[QWidget::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)(),[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)(),[QGraphicsItem::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（） 和[QGraphicsItem::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)() 接收按键事件。

**也可以看看**[QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QWidget::grabKeyboard](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabKeyboard)()。

## 成员函数文档

### QKeyEvent::QKeyEvent([QEvent::Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) *type*, int *key*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text* = QString(), bool *autorep* = false, [quint16](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint16-typedef) *count* = 1)

构造一个按键事件对象。

这*type*参数必须是[QEvent::KeyPress](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum),[QEvent::KeyRelease](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)， 或者[QEvent::ShortcutOverride](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。

INT*key*是代码[Qt::Key](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Key-enum)事件循环应该监听。如果*key*为 0，该事件不是已知键的结果；例如，它可能是撰写序列或键盘宏的结果。这*modifiers*保存键盘修饰符，以及给定的*text*是密钥生成的 Unicode 文本。如果*autorep*是真的，[isAutoRepeat](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAutoRepeat)() 将为真。*count*是事件中涉及的键的数量。

### QKeyEvent::QKeyEvent([QEvent::Type](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) *type*, int *key*, [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) *modifiers*, [quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) *nativeScanCode*, [quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) *nativeVirtualKey*, [quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) *nativeModifiers*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text* = QString(), bool *autorep* = false, [quint16](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint16-typedef) *count* = 1, const [QInputDevice](https://doc-qt-io.translate.goog/qt-6/qinputdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device* = QInputDevice::primaryKeyboard())

构造一个按键事件对象。

这*type*参数必须是[QEvent::KeyPress](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum),[QEvent::KeyRelease](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)， 或者[QEvent::ShortcutOverride](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。

INT*key*是代码[Qt::Key](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Key-enum)事件循环应该监听。如果*key*为 0，该事件不是已知键的结果；例如，它可能是撰写序列或键盘宏的结果。这*modifiers*保存键盘修饰符，以及给定的*text*是密钥生成的 Unicode 文本。如果*autorep*是真的，[isAutoRepeat](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAutoRepeat)() 将为真。*count*是事件中涉及的键的数量。

除了正常的按键事件数据外，还包含*nativeScanCode*,*nativeVirtualKey*和*nativeModifiers*。快捷方式系统使用这些额外数据来确定要触发哪些快捷方式。

### int QKeyEvent::count() const

返回此事件涉及的键的数量。如果[text](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)() 不为空，这只是字符串的长度。

**也可以看看**[Qt::WA_KeyCompression](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)。

### bool QKeyEvent::isAutoRepeat() const

`true`如果此事件来自自动重复键，则返回；`false`如果来自初始按键则返回。

请注意，如果事件是部分由于自动重复而导致的多键压缩事件，则此函数可能不确定地返回 true 或 false。

### int QKeyEvent::key() const

返回按下或释放的键的代码。

看[Qt::Key](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Key-enum)获取键盘代码列表。这些代码独立于底层窗口系统。请注意，该函数不区分大写字母和非大写字母，请使用[text](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)() 函数（返回密钥生成的 Unicode 文本）用于此目的。

值为 0 或[Qt::Key_unknown](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Key-enum)表示该事件不是已知密钥的结果；例如，它可能是合成序列、键盘宏或按键事件压缩的结果。

**也可以看看**[Qt::WA_KeyCompression](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)。

### `[since 6.0]`[QKeyCombination](https://doc-qt-io.translate.goog/qt-6/qkeycombination.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QKeyEvent::keyCombination() const

返回一个[QKeyCombination](https://doc-qt-io.translate.goog/qt-6/qkeycombination.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象同时包含[key](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)() 和[modifiers](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modifiers)() 由该事件携带。

这个函数是在Qt 6.0中引入的。

### bool QKeyEvent::matches([QKeySequence::StandardKey](https://doc-qt-io.translate.goog/qt-6/qkeysequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardKey-enum) *key*) const

返回`true`按键事件是否符合给定标准*key*; 否则返回`false`.

### [Qt::KeyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#KeyboardModifier-enum) QKeyEvent::modifiers() const

返回事件发生后立即存在的键盘修饰符标志。

**警告：**此功能并不总是可信。用户可以通过按两个来混淆它**Shift**例如，同时按键并释放其中一个。

**也可以看看**[QGuiApplication::keyboardModifiers](https://doc-qt-io.translate.goog/qt-6/qguiapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardModifiers)()。

### [quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) QKeyEvent::nativeModifiers() const

返回按键事件的本机修饰符。如果按键事件不包含此数据，则返回 0。

**注意：**即使按键事件包含扩展信息，本机修饰符也可能为 0。

### [quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) QKeyEvent::nativeScanCode() const

返回按键事件的本机扫描码。如果按键事件不包含此数据，则返回 0。

**注意：**即使按键事件包含扩展信息，本机扫描码也可能为 0。

### [quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) QKeyEvent::nativeVirtualKey() const

返回本机虚拟键或键事件的键符号。如果按键事件不包含此数据，则返回 0。

**注意：**即使按键事件包含扩展信息，本机虚拟按键也可能为 0。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QKeyEvent::text() const

返回此键生成的 Unicode 文本。

文本不限于 Unicode 代码点的可打印范围，并且可能包括控制字符或来自其他 Unicode 类别的字符，包括[QChar::Other_PrivateUse](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Category-enum)。

文本也可能为空，例如当按下 Shift、Control、Alt 和 Meta 等修饰键时（取决于平台）。这[key](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#key)() 函数将始终返回一个有效值。

**也可以看看**[Qt::WA_KeyCompression](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)。