#  QKeySequenceEdit Class

QKeySequenceEdit 小部件允许输入[QKeySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QKeySequenceEdit>                                 |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[clearButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearButtonEnabled-prop)** : bool
- **[finishingKeyCombinations](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finishingKeyCombinations-prop)** : QList<QKeyCombination>
- **[keySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keySequence-prop)** : QKeySequence
- **[maximumSequenceLength](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSequenceLength-prop)** : qsizetype

## 公共职能

|                         | **[QKeySequenceEdit](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QKeySequenceEdit)**(QWidget **parent* = nullptr) |
| ----------------------- | ------------------------------------------------------------ |
|                         | **[QKeySequenceEdit](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QKeySequenceEdit-1)**(const QKeySequence &*keySequence*, QWidget **parent* = nullptr) |
| virtual                 | **[~QKeySequenceEdit](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QKeySequenceEdit)**() |
| QList< QKeyCombination> | **[finishingKeyCombinations](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finishingKeyCombinations-prop)**() const |
| bool                    | **[isClearButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearButtonEnabled-prop)**() const |
| QKeySequence            | **[keySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keySequence-prop)**() const |
| qsizetype               | **[maximumSequenceLength](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSequenceLength-prop)**() const |
| void                    | **[setClearButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearButtonEnabled-prop)**(bool *enable*) |
| void                    | **[setFinishingKeyCombinations](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finishingKeyCombinations-prop)**(const QList<QKeyCombination> &*finishingKeyCombinations*) |

## 公共老虎机

| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| ---- | ------------------------------------------------------------ |
| void | **[setKeySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keySequence-prop)**(const QKeySequence &*keySequence*) |
| void | **[setMaximumSequenceLength](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSequenceLength-prop)**(qsizetype *count*) |

## 信号

| void | **[editingFinished](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editingFinished)**() |
| ---- | ------------------------------------------------------------ |
| void | **[keySequenceChanged](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keySequence-prop)**(const QKeySequence &*keySequence*) |

## 重新实现受保护的功能

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **e*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **e*) override |
| virtual void | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **e*) override |

## 详细说明

该小部件允许用户选择[QKeySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，通常用作快捷方式。当小部件获得焦点时开始录制，并在用户释放最后一个键后一秒结束。

**也可以看看**[QKeySequenceEdit::keySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keySequence-prop)。

## 财产文件

### `[since 6.4]`clearButtonEnabled : bool

该属性保存按键序列编辑不为空时是否显示清除按钮。

如果启用，则按键序列编辑在包含某些文本时会显示尾随*清除按钮，否则行编辑不会显示清除按钮（默认）。*

该属性是在 Qt 6.4 中引入的。

**访问功能：**

| bool | **isClearButtonEnabled**() const         |
| ---- | ---------------------------------------- |
| void | **setClearButtonEnabled**(bool *enable*) |

### `[since 6.5]`finishingKeyCombinations : [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QKeyCombination](https://doc-qt-io.translate.goog/qt-6/qkeycombination.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)>

该属性保存完成按键序列编辑的按键组合列表。

列表中的任何组合都将完成按键序列的编辑。所有其他按键组合都可以记录为按键序列的一部分。默认情况下，[Qt::Key_Tab](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Key-enum)和[Qt::Key_Backtab](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Key-enum)将完成按键序列的记录。

该属性是在 Qt 6.5 中引入的。

**访问功能：**

| QList< QKeyCombination> | **finishingKeyCombinations**() const                         |
| ----------------------- | ------------------------------------------------------------ |
| void                    | **setFinishingKeyCombinations**(const QList< QKeyCombination> &*finishingKeyCombinations*) |

### keySequence : [QKeySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性包含当前选择的按键序列。

用户或通过设置器功能可以更改快捷方式。

**注意：**如果[QKeySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)比[maximumSequenceLength](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumSequenceLength-prop)属性，键序列被截断。

**访问功能：**

| QKeySequence | **keySequence**() const                               |
| ------------ | ----------------------------------------------------- |
| void         | **setKeySequence**(const QKeySequence &*keySequence*) |

**通知器信号：**

| void | **keySequenceChanged**(const QKeySequence &*keySequence*) |
| ---- | --------------------------------------------------------- |
|      |                                                           |

### `[since 6.5]`maximumSequenceLength : qsizetype

该属性保存最大序列长度。

用户可以输入的按键序列的最大数量。该值需要介于 1 和 4 之间，默认值为 4。

该属性是在 Qt 6.5 中引入的。

**访问功能：**

| qsizetype | **maximumSequenceLength**() const               |
| --------- | ----------------------------------------------- |
| void      | **setMaximumSequenceLength**(qsizetype *count*) |

## 成员函数文档

### `[explicit]`QKeySequenceEdit::QKeySequenceEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个 QKeySequenceEdit 小部件*parent*。

### `[explicit]`QKeySequenceEdit::QKeySequenceEdit(const [QKeySequence](https://doc-qt-io.translate.goog/qt-6/qkeysequence.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*keySequence*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个 QKeySequenceEdit 小部件*keySequence*和*parent*。

### `[virtual]`QKeySequenceEdit::~QKeySequenceEdit()

摧毁了[QKeySequenceEdit](https://doc-qt-io.translate.goog/qt-6/qkeysequenceedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

### `[slot]`void QKeySequenceEdit::clear()

清除当前的按键序列。

### `[signal]`void QKeySequenceEdit::editingFinished()

当用户完成输入快捷方式时会发出此信号。

**注意：**释放最后一个键并发出此信号之前有一秒的延迟。

### `[override virtual protected]`bool QKeySequenceEdit::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`void QKeySequenceEdit::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

### `[override virtual protected]`void QKeySequenceEdit::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

### `[override virtual protected]`void QKeySequenceEdit::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（QKeyEvent *事件）。

### `[override virtual protected]`void QKeySequenceEdit::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QObject::timerEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。