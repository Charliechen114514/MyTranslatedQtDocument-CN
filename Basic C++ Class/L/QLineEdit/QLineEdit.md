#  QLineEdit Class

QLineEdit 小部件是一个单行文本编辑器。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QLineEdit>                                        |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlineedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[ActionPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ActionPosition-enum)** { LeadingPosition, TrailingPosition } |
| ---- | ------------------------------------------------------------ |
| enum | **[EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)** { Normal, NoEcho, Password, PasswordEchoOnEdit } |

## 特性

| **[acceptableInput](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptableInput-prop)** : const bool**[alignment](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)** : Qt::Alignment**[clearButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearButtonEnabled-prop)** : bool**[cursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorMoveStyle-prop)** : Qt::CursorMoveStyle**[cursorPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPosition-prop)** : int**[displayText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayText-prop)** : const QString**[dragEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)** : bool**[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)** : EchoMode**[frame](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#frame-prop)** : bool**[hasSelectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelectedText-prop)** : const bool | **[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)** : QString**[maxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)** : int**[modified](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)** : bool**[placeholderText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)** : QString**[readOnly](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)** : bool**[redoAvailable](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable-prop)** : const bool**[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)** : const QString**[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)** : QString**[undoAvailable](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable-prop)** : const bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                     | **[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLineEdit)**(QWidget **parent* = nullptr) |
| ------------------- | ------------------------------------------------------------ |
|                     | **[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLineEdit-1)**(const QString &*contents*, QWidget **parent* = nullptr) |
| virtual             | **[~QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QLineEdit)**() |
| void                | **[addAction](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addAction)**(QAction **action*, QLineEdit::ActionPosition *position*) |
| QAction *           | **[addAction](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addAction-1)**(const QIcon &*icon*, QLineEdit::ActionPosition *position*) |
| Qt::Alignment       | **[alignment](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**() const |
| void                | **[backspace](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backspace)**() |
| QCompleter *        | **[completer](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completer)**() const |
| QMenu *             | **[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)**() |
| void                | **[cursorBackward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorBackward)**(bool *mark*, int *steps* = 1) |
| void                | **[cursorForward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorForward)**(bool *mark*, int *steps* = 1) |
| Qt::CursorMoveStyle | **[cursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorMoveStyle-prop)**() const |
| int                 | **[cursorPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPosition-prop)**() const |
| int                 | **[cursorPositionAt](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionAt)**(const QPoint &*pos*) |
| void                | **[cursorWordBackward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWordBackward)**(bool *mark*) |
| void                | **[cursorWordForward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWordForward)**(bool *mark*) |
| void                | **[del](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#del)**() |
| void                | **[deselect](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deselect)**() |
| QString             | **[displayText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayText-prop)**() const |
| bool                | **[dragEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)**() const |
| QLineEdit::EchoMode | **[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)**() const |
| void                | **[end](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**(bool *mark*) |
| bool                | **[hasAcceptableInput](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptableInput-prop)**() const |
| bool                | **[hasFrame](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#frame-prop)**() const |
| bool                | **[hasSelectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelectedText-prop)**() const |
| void                | **[home](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)**(bool *mark*) |
| QString             | **[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)**() const |
| void                | **[insert](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)**(const QString &*newText*) |
| bool                | **[isClearButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearButtonEnabled-prop)**() const |
| bool                | **[isModified](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)**() const |
| bool                | **[isReadOnly](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)**() const |
| bool                | **[isRedoAvailable](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable-prop)**() const |
| bool                | **[isUndoAvailable](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable-prop)**() const |
| int                 | **[maxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)**() const |
| QString             | **[placeholderText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)**() const |
| QString             | **[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)**() const |
| int                 | **[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)**() const |
| int                 | **[selectionLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionLength)**() const |
| int                 | **[selectionStart](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)**() const |
| void                | **[setAlignment](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**(Qt::Alignment *flag*) |
| void                | **[setClearButtonEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearButtonEnabled-prop)**(bool *enable*) |
| void                | **[setCompleter](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCompleter)**(QCompleter **c*) |
| void                | **[setCursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorMoveStyle-prop)**(Qt::CursorMoveStyle *style*) |
| void                | **[setCursorPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPosition-prop)**(int) |
| void                | **[setDragEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)**(bool *b*) |
| void                | **[setEchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)**(QLineEdit::EchoMode) |
| void                | **[setFrame](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#frame-prop)**(bool) |
| void                | **[setInputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)**(const QString &*inputMask*) |
| void                | **[setMaxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)**(int) |
| void                | **[setModified](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)**(bool) |
| void                | **[setPlaceholderText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)**(const QString &) |
| void                | **[setReadOnly](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)**(bool) |
| void                | **[setSelection](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)**(int *start*, int *length*) |
| void                | **[setTextMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextMargins)**(int *left*, int *top*, int *right*, int *bottom*) |
| void                | **[setTextMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextMargins-1)**(const QMargins &*margins*) |
| void                | **[setValidator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)**(const QValidator **v*) |
| QString             | **[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)**() const |
| QMargins            | **[textMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textMargins)**() const |
| const QValidator *  | **[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)**() const |

## 重载的公共函数

| virtual bool     | **[event](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ---------------- | ------------------------------------------------------------ |
| virtual QVariant | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *property*) const override |
| virtual QSize    | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| virtual QSize    | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| virtual void     | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **e*) override |

## 公共槽

| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| ---- | ------------------------------------------------------------ |
| void | **[copy](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)**() const |
| void | **[cut](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)**() |
| void | **[paste](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)**() |
| void | **[redo](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo)**() |
| void | **[selectAll](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)**() |
| void | **[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)**(const QString &) |
| void | **[undo](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo)**() |

## 信号

| void | **[cursorPositionChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionChanged)**(int *oldPos*, int *newPos*) |
| ---- | ------------------------------------------------------------ |
| void | **[editingFinished](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editingFinished)**() |
| void | **[inputRejected](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputRejected)**() |
| void | **[returnPressed](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#returnPressed)**() |
| void | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**() |
| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**(const QString &*text*) |
| void | **[textEdited](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textEdited)**(const QString &*text*) |

## protected function

| QRect        | **[cursorRect](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorRect)**() const |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionFrame **option*) const |

## 重载的protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **ev*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QContextMenuEvent **event*) override |
| virtual void | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QDragEnterEvent **e*) override |
| virtual void | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **e*) override |
| virtual void | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **e*) override |
| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **e*) override |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **e*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **e*) override |
| virtual void | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **e*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) override |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent *) override |
| virtual void | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent *) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\L\QLineEdit\QLineEdit\windows-lineedit.png)

行编辑允许用户输入和编辑单行纯文本，并具有一系列有用的编辑功能，包括撤消和重做、剪切和粘贴以及拖放（请参阅[setDragEnabled](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnabled-prop)())。

通过改变[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)() 的行编辑，它也可以用作“只写”字段，用于输入密码等。

文本的长度可以限制为[maxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)()。可以使用任意约束文本[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)() 或[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)（）， 或两者。在同一行编辑上在验证器和输入掩码之间切换时，最好清除验证器或输入掩码以防止未定义的行为。

一个相关的类是[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它允许多行、富文本编辑。

您可以使用以下命令更改文本[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 或者[insert](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。文本检索为[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)(); 显示的文本（可能不同，请参见[EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)) 检索为[displayText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayText-prop)()。可以选择文本[setSelection](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（） 或者[selectAll](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()，则选择可[cut](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)(),[copy](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)() 简易爆炸装置和[paste](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)()d．文本可以与[setAlignment](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)()。

当文本改变时[textChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)() 信号被发射；当文本发生变化而不是通过调用时[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 这[textEdited](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textEdited)() 信号被发射；当光标移动时[cursorPositionChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionChanged)() 信号被发射；当按下 Return 或 Enter 键时[returnPressed](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#returnPressed)() 信号被发射。

编辑完成后，由于行编辑失去焦点或按 Return/Enter 键[editingFinished](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editingFinished)() 信号被发射。请注意，如果在没有进行任何更改的情况下失去焦点，[editingFinished](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editingFinished)() 信号不会被发射。

请注意，如果编辑行上设置了验证器，则[returnPressed](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#returnPressed)()/[editingFinished](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editingFinished)() 信号仅在验证器返回时才会发出[QValidator::Acceptable](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)。

默认情况下，QLineEdits 具有平台样式指南指定的框架；你可以通过拨打电话将其关闭[setFrame](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#frame-prop)（错误的）。

默认键绑定如下所述。行编辑还提供了一个上下文菜单（通常通过单击鼠标右键来调用），其中显示了其中一些编辑选项。

|      按键      |                行动                |
| :------------: | :--------------------------------: |
|     左箭头     |      将光标向左移动一个字符。      |
| Shift+向左箭头 |   将文本向左移动并选择一个字符。   |
|     右箭头     |      将光标向右移动一个字符。      |
|  Shift+右箭头  |   将文本向右移动并选择一个字符。   |
|       家       |          将光标移至行首。          |
|      结尾      |          将光标移至行尾。          |
|     退格键     |        删除光标左侧的字符。        |
|  Ctrl+退格键   |        删除光标左侧的单词。        |
|      删除      |        删除光标右侧的字符。        |
|   Ctrl+删除    |        删除光标右侧的单词。        |
|     Ctrl+A     |               全选。               |
|     Ctrl+C     |     将选定的文本复制到剪贴板。     |
|   Ctrl+插入    |     将选定的文本复制到剪贴板。     |
|     Ctrl+K     |            删除到行尾。            |
|     Ctrl+V     |    将剪贴板文本粘贴到行编辑中。    |
|   Shift+插入   |    将剪贴板文本粘贴到行编辑中。    |
|     Ctrl+X     | 删除选定的文本并将其复制到剪贴板。 |
|   Shift+删除   | 删除选定的文本并将其复制到剪贴板。 |
|     Ctrl+Z     |           撤消上次操作。           |
|     Ctrl+Y     |        重做上次撤消的操作。        |

任何其他代表有效字符的按键序列都会导致该字符被插入到行编辑中。

**可以参阅**[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QComboBox](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Line Edits Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-lineedits-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QLineEdit::ActionPosition

此枚举类型描述行编辑应如何显示要添加的操作小部件。

| 持续的                        | 价值 | 描述                                                         |
| ----------------------------- | ---- | ------------------------------------------------------------ |
| `QLineEdit::LeadingPosition`  | `0`  | 当使用布局方向时，小部件将显示在文本的左侧`Qt::LeftToRight`，而使用 时，小部件将显示在文本的右侧`Qt::RightToLeft`。 |
| `QLineEdit::TrailingPosition` | `1`  | 使用布局方向时，小部件将显示在文本的右侧`Qt::LeftToRight`；使用 时，小部件将显示在文本的左侧`Qt::RightToLeft`。 |

**可以参阅**[addAction](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addAction)(),[removeAction](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAction)（）， 和[QWidget::layoutDirection](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection-prop)。

### enum QLineEdit::EchoMode

此枚举类型描述行编辑应如何显示其内容。

| 持续的                          | 价值 | 描述                                                       |
| ------------------------------- | ---- | ---------------------------------------------------------- |
| `QLineEdit::Normal`             | `0`  | 显示输入的字符。这是默认设置。                             |
| `QLineEdit::NoEcho`             | `1`  | 不要显示任何东西。这可能适用于甚至密码长度也应保密的密码。 |
| `QLineEdit::Password`           | `2`  | 显示与平台相关的密码掩码字符而不是实际输入的字符。         |
| `QLineEdit::PasswordEchoOnEdit` | `3`  | 在编辑时显示输入的字符，否则显示与 一样的字符`Password`。  |

**可以参阅**[setEchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)（） 和[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)()。

## 属性文件

### `[read-only]`acceptableInput : const bool

该属性保存输入是否满足[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)和验证器。

默认情况下，该属性为`true`。

**访问功能：**

| bool | **hasAcceptableInput**() const |
| ---- | ------------------------------ |
|      |                                |

**可以参阅**[setInputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)（） 和[setValidator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)()。

### alignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

该属性保存行编辑的对齐方式。

这里允许水平和垂直对齐，[Qt::AlignJustify](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)将映射到[Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

默认情况下，此属性包含以下组合[Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)和[Qt::AlignVCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

**访问功能：**

| Qt::Alignment | **alignment**() const                  |
| ------------- | -------------------------------------- |
| void          | **setAlignment**(Qt::Alignment *flag*) |

**可以参阅**[Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

### clearButtonEnabled : bool

该属性保存行编辑不为空时是否显示清除按钮。

如果启用，行编辑在包含某些文本时会显示尾随*清除按钮，否则行编辑不会显示清除按钮（默认）。*

**访问功能：**

| bool | **isClearButtonEnabled**() const         |
| ---- | ---------------------------------------- |
| void | **setClearButtonEnabled**(bool *enable*) |

**可以参阅**[addAction](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addAction)（） 和[removeAction](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeAction)()。

### cursorMoveStyle : [Qt::CursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorMoveStyle-enum)

该属性保存了该行编辑中光标的移动方式。

当该属性设置为[Qt::VisualMoveStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorMoveStyle-enum)，线条编辑将使用视觉运动风格。无论文本的书写方向如何，按向左箭头键始终会导致光标向左移动。相同的行为适用于右箭头键。

当该财产是[Qt::LogicalMoveStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorMoveStyle-enum)（默认），在 LTR 文本块内，按向左箭头键时增加光标位置，按向右箭头键时减少光标位置。如果文本块从右到左，则应用相反的行为。

**访问功能：**

| Qt::CursorMoveStyle | **cursorMoveStyle**() const                         |
| ------------------- | --------------------------------------------------- |
| void                | **setCursorMoveStyle**(Qt::CursorMoveStyle *style*) |

### cursorPosition : int

该属性保存该行编辑的当前光标位置。

设置光标位置会在适当的时候导致重新绘制。

默认情况下，此属性包含值 0。

**访问功能：**

| int  | **cursorPosition**() const |
| ---- | -------------------------- |
| void | **setCursorPosition**(int) |

### `[read-only]`displayText : const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存显示的文本。

如果[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)是[Normal](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)这返回相同[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)(); 如果[EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)是[Password](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)或者[PasswordEchoOnEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)它返回一串与平台相关的密码掩码字符[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)().length() 的大小，例如“******”；如果[EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)是[NoEcho](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)返回一个空字符串“”。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **displayText**() const |
| ------- | ----------------------- |
|         |                         |

**可以参阅**[setEchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)(),[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（）， 和[EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)。

### dragEnabled : bool

此属性保存如果用户在某些选定的文本上按下并移动鼠标，线条编辑是否开始拖动。

默认情况下禁用拖动。

**访问功能：**

| bool | **dragEnabled**() const      |
| ---- | ---------------------------- |
| void | **setDragEnabled**(bool *b*) |

### echoMode : [EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)

该属性保存行编辑的回显模式。

回显模式确定如何向用户显示（或回显）行编辑中输入的文本。

最常见的设置是[Normal](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)，其中用户输入的文本逐字显示，但是[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)还支持允许抑制或遮盖输入文本的模式：这些模式包括[NoEcho](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum),[Password](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)和[PasswordEchoOnEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)。

小部件的显示以及复制或拖动文本的能力受此设置的影响。

默认情况下，该属性设置为[Normal](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)。

**访问功能：**

| QLineEdit::EchoMode | **echoMode**() const                 |
| ------------------- | ------------------------------------ |
| void                | **setEchoMode**(QLineEdit::EchoMode) |

**可以参阅**[EchoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)和[displayText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayText-prop)()。

### frame : bool

该属性保存线条编辑是否使用框架绘制自身。

如果启用（默认），线条编辑将在框架内绘制自身，否则线条编辑将在没有任何框架的情况下绘制自身。

**访问功能：**

| bool | **hasFrame**() const |
| ---- | -------------------- |
| void | **setFrame**(bool)   |

### `[read-only]`hasSelectedText : const bool

该属性保存是否有任何文本被选中。

`true`如果用户选择了部分或全部文本，则hasSelectedText() 返回；否则返回`false`.

默认情况下，该属性为`false`。

**访问功能：**

| bool | **hasSelectedText**() const |
| ---- | --------------------------- |
|      |                             |

**可以参阅**[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)()。

### inputMask : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存验证输入掩码。

如果未设置掩码，则 inputMask() 返回空字符串。

设置[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的验证掩码。验证器可以代替掩码使用，或者与掩码一起使用；看[setValidator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)()。

解除遮罩并恢复正常[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过传递空字符串（“”）进行操作。

输入掩码是输入模板字符串。它可以包含以下元素：

| 面具人物 | 定义[Category](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Category-enum)在此位置被认为有效的输入字符数 |
| -------- | ------------------------------------------------------------ |
| 元字符   | 各种特殊含义                                                 |
| 分离器   | 所有其他字符都被视为不可变分隔符                             |

下表显示了可在输入掩码中使用的掩码和元字符。

|   掩码    |                       意义                        |
| :-------: | :-----------------------------------------------: |
|    `A`    |         所需字母类别的字符，例如 AZ、az。         |
|    `a`    |          允许但不要求的字母类别的字符。           |
|    `N`    |   所需字母或数字类别的字符，例如 AZ、az、0-9。    |
|    `n`    |       允许但不要求的字母或数字类别的字符。        |
|    `X`    |               需要任何非空白字符。                |
|    `x`    |         允许但不是必需的任何非空白字符。          |
|    `9`    |          所需数字类别的字符，例如 0-9。           |
|    `0`    |          允许但不要求的数字类别的字符。           |
|    `D`    |     Number 类别的字符，且必须大于零，例如 1-9     |
|    `d`    | Number 类别的字符，允许但不要求大于零，例如 1-9。 |
|    `#`    |    数字类别的字符，或允许但不必需的加号/减号。    |
|    `H`    |          需要十六进制字符。AF，AF，0-9。          |
|    `h`    |       允许使用十六进制字符，但不是必需的。        |
|    `B`    |               需要二进制字符。0-1。               |
|    `b`    |           允许但不要求使用二进制字符。            |
|  元字符   |                       意义                        |
|    `>`    |            以下所有字母字符均为大写。             |
|    `<`    |            以下所有字母字符均为小写。             |
|    `!`    |                 关闭大小写转换。                  |
|   `;c`    |       终止输入掩码并将*空白*字符设置为*c*。       |
| `[ ] { }` |                     预订的。                      |
|    `\`    |  用于`\`转义上面列出的特殊字符以将其用作分隔符。  |

创建或清除时，行编辑将填充输入掩码字符串的副本，其中元字符已被删除，并且掩码字符已替换为空白字符（默认情况下为*a*）`space`。

当设置输入掩码时，[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)() 方法返回行编辑内容的修改副本，其中所有*空白*字符已被删除。可以使用以下方式读取未修改的内容[displayText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayText-prop)()。

这[hasAcceptableInput](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptableInput-prop)如果行编辑的当前内容不满足输入掩码的要求，() 方法将返回 false。

例子：

|                掩码                |                       备注                        |
| :--------------------------------: | :-----------------------------------------------: |
|        `000.000.000.000;_`         |                IP地址; 空格是`_`.                 |
|       `HH:HH:HH:HH:HH:HH;_`        |                      MAC地址                      |
|            `0000-00-00`            |              ISO 日期；空白是`space`              |
| `>AAAAA-AAAAA-AAAAA-AAAAA-AAAAA;#` | 许可证号; 空格`#`和所有（字母）字符都转换为大写。 |

要获得范围控制（例如，对于 IP 地址），请将掩码与[validators](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)。

**访问功能：**

| QString | **inputMask**() const                        |
| ------- | -------------------------------------------- |
| void    | **setInputMask**(const QString &*inputMask*) |

**可以参阅**[maxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop),[QChar::isLetter](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isLetter)(),[QChar::isNumber](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isNumber)（）， 和[QChar::digitValue](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitValue)()。

### maxLength : int

该属性保存文本的最大允许长度。

如果文本太长，则会在限制处被截断。

如果发生截断，任何选定的文本都将被取消选择，光标位置将设置为 0，并显示字符串的第一部分。

如果行编辑具有输入掩码，则该掩码定义最大字符串长度。

默认情况下，此属性包含值 32767。

**访问功能：**

| int  | **maxLength**() const |
| ---- | --------------------- |
| void | **setMaxLength**(int) |

**可以参阅**[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)。

### modified : bool

该属性保存行编辑的内容是否已被用户修改。

修改后的标志永远不会被读取[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 它的默认值为 false，并且每当用户更改行编辑的内容时就会更改为 true。

这对于需要提供默认值但一开始不知道默认值应该是什么（可能取决于表单上的其他字段）的事情很有用。在没有最佳默认值的情况下开始行编辑，当默认值已知时，如果 modded() 返回`false`（用户尚未输入任何文本），则插入默认值。

呼唤[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)() 将修改标志重置为 false。

**访问功能：**

| bool | **isModified**() const |
| ---- | ---------------------- |
| void | **setModified**(bool)  |

### placeholderText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存行编辑的占位符文本。

只要行编辑为空，设置此属性就会使行编辑显示灰色的占位符文本。

通常，空行编辑会显示占位符文本，即使它具有焦点也是如此。但是，如果内容水平居中，则当行编辑具有焦点时，占位符文本不会显示在光标下方。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **placeholderText**() const             |
| ------- | --------------------------------------- |
| void    | **setPlaceholderText**(const QString &) |

**可以参阅**[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()。

### readOnly : bool

该属性保存行编辑是否为只读。

在只读模式下，用户仍然可以将文本复制到剪贴板，或拖放文本（如果[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)（） 是[Normal](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum))，但无法编辑。

[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在只读模式下不显示光标。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isReadOnly**() const |
| ---- | ---------------------- |
| void | **setReadOnly**(bool)  |

**可以参阅**[setEnabled](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enabled-prop)()。

### `[read-only]`redoAvailable : const bool

该属性保存重做是否可用。

一旦用户对行编辑中的文本执行了一项或多项撤消操作，重做就变得可用。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isRedoAvailable**() const |
| ---- | --------------------------- |
|      |                             |

### `[read-only]`selectedText : const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存选定的文本。

如果没有选定的文本，则该属性的值为空字符串。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **selectedText**() const |
| ------- | ------------------------ |
|         |                          |

**可以参阅**[hasSelectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelectedText-prop)()。

### text : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存行编辑的文本。

设置此属性将清除选择、清除撤消/重做历史记录、将光标移动到行尾并重置[modified](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)属性为 false。使用 setText() 插入文本时，不会验证文本。

文本被截断为[maxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)（） 长度。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **text**() const             |
| ------- | ---------------------------- |
| void    | **setText**(const QString &) |

**通知器信号：**

| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**(const QString &*text*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**可以参阅**[insert](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)（） 和[clear](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### `[read-only]`undoAvailable : const bool

该属性保存撤消是否可用。

一旦用户修改了行编辑中的文本，撤消操作就可用。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isUndoAvailable**() const |
| ---- | --------------------------- |
|      |                             |

## 成员函数文档

### `[explicit]`QLineEdit::QLineEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个没有文本的行编辑。

最大文本长度设置为 32767 个字符。

这*parent*参数被发送到[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**可以参阅**[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 和[setMaxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)()。

### `[explicit]`QLineEdit::QLineEdit(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*contents*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造包含文本的行编辑*contents*。

光标位置设置为行尾，最大文本长度设置为 32767 个字符。

这*parent*并且参数被发送到[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**可以参阅**[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 和[setMaxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)()。

### `[virtual]`QLineEdit::~QLineEdit()

破坏行编辑。

### void QLineEdit::addAction([QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **action*, [QLineEdit::ActionPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ActionPosition-enum) *position*)

添加了*action*到操作列表*position*。

### [QAction](https://doc-qt-io.translate.goog/qt-6/qaction.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QLineEdit::addAction(const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*icon*, [QLineEdit::ActionPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ActionPosition-enum) *position*)

这是一个过载功能。

使用给定的创建一个新动作*icon*在*position*。

### void QLineEdit::backspace()

如果未选择任何文本，则删除文本光标左侧的字符并将光标向左移动一位。如果选择任何文本，光标将移动到所选文本的开头，并删除所选文本。

**可以参阅**[del](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#del)()。

### `[override virtual protected]`void QLineEdit::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### `[slot]`void QLineEdit::clear()

清除行编辑的内容。

**可以参阅**[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 和[insert](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insert)()。

### [QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QLineEdit::completer() const

返回当前值[QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供完成。

**可以参阅**[setCompleter](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCompleter)()。

### `[override virtual protected]`void QLineEdit::contextMenuEvent([QContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qcontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)（QContextMenuEvent *事件）。

显示使用创建的标准上下文菜单[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)()。

如果你不希望行编辑有上下文菜单，你可以设置它[contextMenuPolicy](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuPolicy-prop)到[Qt::NoContextMenu](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ContextMenuPolicy-enum)。如果您想自定义上下文菜单，请重新实现此函数。如果要扩展标准上下文菜单，请重新实现此函数，调用[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)() 并扩展返回的菜单。

```
void LineEdit::contextMenuEvent(QContextMenuEvent *event)
{
    QMenu *menu = createStandardContextMenu();
    menu->addAction(tr("My Menu Item"));
    //...
    menu->exec(event->globalPos());
    delete menu;
}
```

这*event*参数用于获取事件发生时鼠标光标所在的位置。

**可以参阅**[setContextMenuPolicy](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuPolicy-prop)()。

### `[slot]`void QLineEdit::copy() const

将选定的文本复制到剪贴板（如果有的话）[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)（） 是[Normal](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)。

**可以参阅**[cut](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)（） 和[paste](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)()。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QLineEdit::createStandardContextMenu()

此函数创建标准上下文菜单，当用户用鼠标右键单击行编辑时显示该菜单。它是从默认调用的[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)() 处理程序。弹出菜单的所有权转移给调用者。

### void QLineEdit::cursorBackward(bool *mark*, int *steps* = 1)

将光标向后移动*steps*人物。如果*mark*为 true 时，移动的每个字符都会添加到选择中；如果*mark*为 false 则清除选择。

**可以参阅**[cursorForward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorForward)()。

### void QLineEdit::cursorForward(bool *mark*, int *steps* = 1)

向前移动光标*steps*人物。如果*mark*为 true 时，移动的每个字符都会添加到选择中；如果*mark*为 false 则清除选择。

**可以参阅**[cursorBackward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorBackward)()。

### int QLineEdit::cursorPositionAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*)

返回该点下的光标位置*pos*。

### `[signal]`void QLineEdit::cursorPositionChanged(int *oldPos*, int *newPos*)

每当光标移动时就会发出此信号。先前的位置由下式给出*oldPos*，以及新位置*newPos*。

**可以参阅**[setCursorPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPosition-prop)（） 和[cursorPosition](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPosition-prop)()。

### `[protected]`[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLineEdit::cursorRect() const

返回包含线条编辑光标的矩形。

### void QLineEdit::cursorWordBackward(bool *mark*)

将光标向后移动一个字。如果*mark*确实如此，这个词也被选中了。

**可以参阅**[cursorWordForward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWordForward)()。

### void QLineEdit::cursorWordForward(bool *mark*)

将光标向前移动一个字。如果*mark*确实如此，这个词也被选中了。

**可以参阅**[cursorWordBackward](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWordBackward)()。

### `[slot]`void QLineEdit::cut()

将选定的文本复制到剪贴板并将其删除（如果有的话）[echoMode](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#echoMode-prop)（） 是[Normal](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EchoMode-enum)。

如果当前验证器不允许删除所选文本，则 cut() 将复制而不删除。

**可以参阅**[copy](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)(),[paste](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)（）， 和[setValidator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)()。

### void QLineEdit::del()

如果未选择任何文本，则删除文本光标右侧的字符。如果选择任何文本，光标将移动到所选文本的开头，并删除所选文本。

**可以参阅**[backspace](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backspace)()。

### void QLineEdit::deselect()

取消选择任何选定的文本。

**可以参阅**[setSelection](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（） 和[selectAll](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()。

### `[override virtual protected]`void QLineEdit::dragEnterEvent([QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（QDragEnterEvent *事件）。

### `[override virtual protected]`void QLineEdit::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

### `[override virtual protected]`void QLineEdit::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[override virtual protected]`void QLineEdit::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::dropEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### `[signal]`void QLineEdit::editingFinished()

当按下 Return 或 Enter 键时，或者如果行编辑失去焦点并且自上次发出此信号以来其内容已更改，则会发出此信号。

请注意，如果有一个[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)（） 或者[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)() 在行 edit 上设置并按下 Enter/Return，只有当输入遵循[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)() 和[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)() 返回[QValidator::Acceptable](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)。

### void QLineEdit::end(bool *mark*)

将文本光标移动到行尾，除非它已经在那里。如果*mark*为 true 时，文本将被选择到最后一个位置；否则，如果移动光标，则取消选择任何选定的文本。

**可以参阅**[home](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)()。

### `[override virtual]`bool QLineEdit::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`void QLineEdit::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[override virtual protected]`void QLineEdit::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

### void QLineEdit::home(bool *mark*)

将文本光标移动到行首，除非它已经在那里。如果*mark*为 true 时，文本将被选择到第一个位置；否则，如果移动光标，则取消选择任何选定的文本。

**可以参阅**[end](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### `[virtual protected]`void QLineEdit::initStyleOption([QStyleOptionFrame](https://doc-qt-io.translate.goog/qt-6/qstyleoptionframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QLineEdit](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionFrame](https://doc-qt-io.translate.goog/qt-6/qstyleoptionframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**可以参阅**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual protected]`void QLineEdit::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)（QInputMethodEvent *事件）。

### `[override virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLineEdit::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *property*) const

重新实现：[QWidget::inputMethodQuery(Qt::InputMethodQuery query) const](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)。

### `[signal]`void QLineEdit::inputRejected()

当用户按下不被认为是可接受的输入的键时，会发出此信号。例如，如果按键导致验证器的 validate() 调用返回 Invalid。另一种情况是尝试输入超出行编辑最大长度的更多字符时。

注意：在部分文本被接受但不是全部被接受的情况下，仍然会发出此信号。例如，如果设置了最大长度，并且粘贴时剪贴板文本比最大长度长。

### void QLineEdit::insert(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*newText*)

删除任何选定的文本，插入*newText*，并验证结果。如果有效，则将其设置为行编辑的新内容。

**可以参阅**[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)（） 和[clear](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### `[override virtual protected]`void QLineEdit::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

转换给定的按键*event*进入行编辑操作。

如果按下 Return 或 Enter 键并且当前文本有效（或者可以是[made valid](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)由验证器），信号[returnPressed](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#returnPressed)() 被发射。

类的详细描述中列出了默认的键绑定。

### `[override virtual protected]`void QLineEdit::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（QKeyEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLineEdit::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

返回行编辑的最小大小。

返回的宽度通常足以容纳至少一个字符。

### `[override virtual protected]`void QLineEdit::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QLineEdit::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QLineEdit::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QLineEdit::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QLineEdit::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[slot]`void QLineEdit::paste()

在光标位置插入剪贴板的文本，删除任何选定的文本，前提是不进行行编辑[read-only](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)。

如果最终结果对当前无效[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)， 什么都没发生。

**可以参阅**[copy](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)（） 和[cut](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)()。

### `[slot]`void QLineEdit::redo()

如果重做，则重做最后一次操作[available](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable-prop)。

### `[signal]`void QLineEdit::returnPressed()

当按下 Return 或 Enter 键时会发出此信号。请注意，如果有一个[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)（） 或者[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)() 设置在行编辑上，只有当输入遵循以下命令时才会发出 returnPressed() 信号[inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)() 和[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)() 返回[QValidator::Acceptable](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)。

### `[slot]`void QLineEdit::selectAll()

选择所有文本（即突出显示它）并将光标移动到末尾。当插入默认值时这非常有用，因为如果用户在单击小部件之前键入，则所选文本将被删除。

**可以参阅**[setSelection](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelection)（） 和[deselect](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deselect)()。

### `[signal]`void QLineEdit::selectionChanged()

每当选择发生变化时就会发出此信号。

**可以参阅**[hasSelectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelectedText-prop)（） 和[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)()。

### int QLineEdit::selectionEnd() const

在行编辑中选择后直接返回字符的索引，如果未选择文本，则返回 -1。

**可以参阅**[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)(),[selectionStart](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)（）， 和[selectionLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionLength)()。

### int QLineEdit::selectionLength() const

返回选择的长度。

**可以参阅**[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)(),[selectionStart](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)（）， 和[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)()。

### int QLineEdit::selectionStart() const

返回行编辑中第一个选定字符的索引；如果未选择任何文本，则返回 -1。

**可以参阅**[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)(),[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)（）， 和[selectionLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionLength)()。

### void QLineEdit::setCompleter([QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **c*)

设置此行编辑以提供来自完成者的自动完成，*c*。完成模式设置使用[QCompleter::setCompletionMode](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completionMode-prop)()。

要使用[QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与一个[QValidator](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QLineEdit::inputMask](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMask-prop)，您需要确保提供的模型[QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)包含有效条目。您可以使用[QSortFilterProxyModel](https://doc-qt-io.translate.goog/qt-6/qsortfilterproxymodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)以确保[QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的模型仅包含有效条目。

如果*c*== 0，setCompleter() 删除当前完成器，有效禁用自动完成。

**可以参阅**[completer](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completer)（） 和[QCompleter](https://doc-qt-io.translate.goog/qt-6/qcompleter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QLineEdit::setSelection(int *start*, int *length*)

从位置选择文本*start*并为*length*人物。允许负长度。

**可以参阅**[deselect](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deselect)(),[selectAll](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)（）， 和[selectedText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText-prop)()。

### void QLineEdit::setTextMargins(int *left*, int *top*, int *right*, int *bottom*)

设置框架内文本周围的边距以具有尺寸*left*,*top*,*right*， 和*bottom*。

可以参阅[textMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textMargins)()。

**可以参阅**[textMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textMargins)()。

### void QLineEdit::setTextMargins(const [QMargins](https://doc-qt-io.translate.goog/qt-6/qmargins.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*margins*)

设置*margins*围绕框架内的文本。

可以参阅[textMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textMargins)()。

### void QLineEdit::setValidator(const [QValidator](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **v*)

将行编辑值的验证器设置为*v*。

行编辑的[returnPressed](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#returnPressed)（） 和[editingFinished](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editingFinished)() 信号只有在以下情况下才会被发射：*v*验证行编辑的内容为[Acceptable](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)。用户可以将内容更改为任意[Intermediate](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)编辑期间的值，但将阻止将文本编辑为以下值*v*验证为[Invalid](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum)。

这允许您限制编辑完成后最终输入的文本，同时让用户有足够的自由将文本从一种有效状态编辑为另一种有效状态。

如果*v*== 0，setValidator() 删除当前输入验证器。初始设置是没有输入验证器（即接受任何输入[maxLength](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maxLength-prop)())。

**可以参阅**[validator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validator)(),[hasAcceptableInput](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptableInput-prop)(),[QIntValidator](https://doc-qt-io.translate.goog/qt-6/qintvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDoubleValidator](https://doc-qt-io.translate.goog/qt-6/qdoublevalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QRegularExpressionValidator](https://doc-qt-io.translate.goog/qt-6/qregularexpressionvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLineEdit::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。

返回小部件的建议大小。

返回的宽度（以像素为单位）通常足以容纳大约 15 到 20 个字符。

### `[signal]`void QLineEdit::textChanged(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

每当文本更改时就会发出此信号。这*text*参数是新文本。

不像[textEdited](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textEdited)()，当以编程方式更改文本时也会发出此信号，例如通过调用[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()。

**注意：**属性的通知程序信号[text](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)。

### `[signal]`void QLineEdit::textEdited(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

每当编辑文本时都会发出此信号。这*text*参数是新文本。

不像[textChanged](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)()，当以编程方式更改文本时，例如通过调用[setText](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()。

### [QMargins](https://doc-qt-io.translate.goog/qt-6/qmargins.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLineEdit::textMargins() const

返回小部件的文本边距。

**可以参阅**[setTextMargins](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextMargins)()。

### `[override virtual]`void QLineEdit::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QObject::timerEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。

### `[slot]`void QLineEdit::undo()

如果撤消，则撤消上一次操作[available](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable-prop)。取消选择任何当前选择，并将选择开始更新为当前光标位置。

### const [QValidator](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QLineEdit::validator() const

返回指向当前输入验证器的指针，或者`nullptr`如果尚未设置验证器。

**可以参阅**[setValidator](https://doc-qt-io.translate.goog/qt-6/qlineedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setValidator)()。