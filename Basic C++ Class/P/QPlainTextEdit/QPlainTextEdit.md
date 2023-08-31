#  QPlainTextEdit Class

QPlainTextEdit 类提供了一个用于编辑和显示纯文本的小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QPlainTextEdit>                                   |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qplaintextedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QPlainTextEdit 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| enum | **[LineWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)** { NoWrap, WidgetWidth } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 特性

| **[backgroundVisible](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundVisible-prop)** : bool**[blockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCount-prop)** : const int**[centerOnScroll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOnScroll-prop)** : bool**[cursorWidth](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWidth-prop)** : int**[documentTitle](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)** : QString**[lineWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)** : LineWrapMode**[maximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)** : int**[overwriteMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overwriteMode-prop)** : bool | **[placeholderText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)** : QString**[plainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)** : QString**[readOnly](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)** : bool**[tabChangesFocus](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabChangesFocus-prop)** : bool**[tabStopDistance](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabStopDistance-prop)** : qreal**[textInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)** : Qt::TextInteractionFlags**[undoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)** : bool**[wordWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)** : QTextOption::WrapMode |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                                  | **[QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPlainTextEdit)**(QWidget **parent* = nullptr) |
| -------------------------------- | ------------------------------------------------------------ |
|                                  | **[QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPlainTextEdit-1)**(const QString &*text*, QWidget **parent* = nullptr) |
| virtual                          | **[~QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QPlainTextEdit)**() |
| QString                          | **[anchorAt](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchorAt)**(const QPoint &*pos*) const |
| bool                             | **[backgroundVisible](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundVisible-prop)**() const |
| int                              | **[blockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCount-prop)**() const |
| bool                             | **[canPaste](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canPaste)**() const |
| bool                             | **[centerOnScroll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOnScroll-prop)**() const |
| QMenu *                          | **[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)**() |
| QMenu *                          | **[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu-1)**(const QPoint &*position*) |
| QTextCharFormat                  | **[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)**() const |
| QTextCursor                      | **[cursorForPosition](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorForPosition)**(const QPoint &*pos*) const |
| QRect                            | **[cursorRect](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorRect)**(const QTextCursor &*cursor*) const |
| QRect                            | **[cursorRect](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorRect-1)**() const |
| int                              | **[cursorWidth](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWidth-prop)**() const |
| QTextDocument *                  | **[document](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)**() const |
| QString                          | **[documentTitle](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)**() const |
| void                             | **[ensureCursorVisible](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureCursorVisible)**() |
| QList<QTextEdit::ExtraSelection> | **[extraSelections](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#extraSelections)**() const |
| bool                             | **[find](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)**(const QString &*exp*, QTextDocument::FindFlags *options* = QTextDocument::FindFlags()) |
| bool                             | **[find](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-1)**(const QRegularExpression &*exp*, QTextDocument::FindFlags *options* = QTextDocument::FindFlags()) |
| bool                             | **[isReadOnly](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)**() const |
| bool                             | **[isUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)**() const |
| QPlainTextEdit::LineWrapMode     | **[lineWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)**() const |
| virtual QVariant                 | **[loadResource](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)**(int *type*, const QUrl &*name*) |
| int                              | **[maximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)**() const |
| void                             | **[mergeCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCurrentCharFormat)**(const QTextCharFormat &*modifier*) |
| void                             | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QTextCursor::MoveOperation *operation*, QTextCursor::MoveMode *mode* = QTextCursor::MoveAnchor) |
| bool                             | **[overwriteMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overwriteMode-prop)**() const |
| QString                          | **[placeholderText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)**() const |
| void                             | **[print](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#print)**(QPagedPaintDevice **printer*) const |
| void                             | **[setBackgroundVisible](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundVisible-prop)**(bool *visible*) |
| void                             | **[setCenterOnScroll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOnScroll-prop)**(bool *enabled*) |
| void                             | **[setCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCharFormat)**(const QTextCharFormat &*format*) |
| void                             | **[setCursorWidth](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWidth-prop)**(int *width*) |
| void                             | **[setDocument](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocument)**(QTextDocument **document*) |
| void                             | **[setDocumentTitle](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)**(const QString &*title*) |
| void                             | **[setExtraSelections](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExtraSelections)**(const QList<QTextEdit::ExtraSelection> &*selections*) |
| void                             | **[setLineWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)**(QPlainTextEdit::LineWrapMode *mode*) |
| void                             | **[setMaximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)**(int *maximum*) |
| void                             | **[setOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overwriteMode-prop)**(bool *overwrite*) |
| void                             | **[setPlaceholderText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)**(const QString &*placeholderText*) |
| void                             | **[setReadOnly](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)**(bool *ro*) |
| void                             | **[setTabChangesFocus](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabChangesFocus-prop)**(bool *b*) |
| void                             | **[setTabStopDistance](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabStopDistance-prop)**(qreal *distance*) |
| void                             | **[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)**(const QTextCursor &*cursor*) |
| void                             | **[setTextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)**(Qt::TextInteractionFlags *flags*) |
| void                             | **[setUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)**(bool *enable*) |
| void                             | **[setWordWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)**(QTextOption::WrapMode *policy*) |
| bool                             | **[tabChangesFocus](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabChangesFocus-prop)**() const |
| qreal                            | **[tabStopDistance](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabStopDistance-prop)**() const |
| QTextCursor                      | **[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)**() const |
| Qt::TextInteractionFlags         | **[textInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)**() const |
| QString                          | **[toPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)**() const |
| QTextOption::WrapMode            | **[wordWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)**() const |

## 重载的公共函数

| virtual QVariant | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *property*) const override |
| ---------------- | ------------------------------------------------------------ |
|                  |                                                              |

## 公共槽

| void | **[appendHtml](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendHtml)**(const QString &*html*) |
| ---- | ------------------------------------------------------------ |
| void | **[appendPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendPlainText)**(const QString &*text*) |
| void | **[centerCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerCursor)**() |
| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| void | **[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)**() |
| void | **[cut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)**() |
| void | **[insertPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertPlainText)**(const QString &*text*) |
| void | **[paste](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)**() |
| void | **[redo](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo)**() |
| void | **[selectAll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)**() |
| void | **[setPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)**(const QString &*text*) |
| void | **[undo](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo)**() |
| void | **[zoomIn](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomIn)**(int *range* = 1) |
| void | **[zoomOut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomOut)**(int *range* = 1) |

## 信号

| void | **[blockCountChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCountChanged)**(int *newBlockCount*) |
| ---- | ------------------------------------------------------------ |
| void | **[copyAvailable](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copyAvailable)**(bool *yes*) |
| void | **[cursorPositionChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionChanged)**() |
| void | **[modificationChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modificationChanged)**(bool *changed*) |
| void | **[redoAvailable](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable)**(bool *available*) |
| void | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**() |
| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**() |
| void | **[undoAvailable](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)**(bool *available*) |
| void | **[updateRequest](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateRequest)**(const QRect &*rect*, int *dy*) |

## protected function

| QRectF                                    | **[blockBoundingGeometry](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockBoundingGeometry)**(const QTextBlock &*block*) const |
| ----------------------------------------- | ------------------------------------------------------------ |
| QRectF                                    | **[blockBoundingRect](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockBoundingRect)**(const QTextBlock &*block*) const |
| virtual bool                              | **[canInsertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canInsertFromMimeData)**(const QMimeData **source*) const |
| QPointF                                   | **[contentOffset](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentOffset)**() const |
| virtual QMimeData *                       | **[createMimeDataFromSelection](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createMimeDataFromSelection)**() const |
| QTextBlock                                | **[firstVisibleBlock](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstVisibleBlock)**() const |
| QAbstractTextDocumentLayout::PaintContext | **[getPaintContext](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getPaintContext)**() const |
| virtual void                              | **[insertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFromMimeData)**(const QMimeData **source*) |

## 重载的protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QContextMenuEvent **event*) override |
| virtual void | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QDragEnterEvent **e*) override |
| virtual void | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **e*) override |
| virtual void | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **e*) override |
| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **e*) override |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **e*) override |
| virtual bool | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **e*) override |
| virtual void | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **e*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **e*) override |
| virtual void | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **e*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **e*) override |
| virtual void | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent *) override |
| virtual void | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QWheelEvent **e*) override |

## 详细说明

### 简介和概念

QPlainTextEdit 是支持纯文本的高级查看器/编辑器。它经过优化，可以处理大型文档并快速响应用户输入。

QPlainText 使用与[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但针对纯文本处理进行了优化。

QPlainTextEdit 适用于段落和字符。段落是一个格式化的字符串，它被自动换行以适应小部件的宽度。默认情况下，阅读纯文本时，一个换行符表示一个段落。文档由零个或多个段落组成。段落之间用硬换行符分隔。段落中的每个字符都有自己的属性，例如字体和颜色。

QPlainTextEdit 上鼠标光标的形状是[Qt::IBeamCursor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorShape-enum)默认情况下。可以通过以下方式更改[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)() 的光标属性。

### 使用 QPlainTextEdit 作为显示小部件

文本设置或替换使用[setPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)() 删除现有文本并将其替换为传递给的文本[setPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)()。

可以使用插入文本[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类或使用便利函数[insertPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertPlainText)(),[appendPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendPlainText)（） 或者[paste](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)()。

默认情况下，文本编辑会在空格处换行以适合文本编辑小部件。这[setLineWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)() 函数用于指定您想要的换行类型，[WidgetWidth](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)或者[NoWrap](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)如果你不想要任何包装。如果您对小部件的宽度使用自动换行[WidgetWidth](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)，您可以指定是否在空格或任何地方中断[setWordWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)()。

这[find](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)() 函数可用于查找并选择文本中的给定字符串。

如果您想限制 QPlainTextEdit 中的段落总数，因为它在日志查看器中很有用，那么您可以使用[maximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)财产。的组合[setMaximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)（） 和[appendPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendPlainText)() 将 QPlainTextEdit 变成一个高效的日志文本查看器。可以通过以下方式减少滚动[centerOnScroll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOnScroll-prop)() 属性，使日志查看器更快。文本可以以有限的方式格式化，可以使用语法荧光笔（见下文），也可以通过附加 html 格式的文本[appendHtml](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendHtml)()。虽然 QPlainTextEdit 不支持使用表格和浮动的复杂富文本呈现，但它确实支持日志查看器中可能需要的有限的基于段落的格式。

#### 只读键绑定

当 QPlainTextEdit 以只读方式使用时，键绑定仅限于导航，并且只能使用鼠标选择文本：

|                             按键                             |               行动               |
| :----------------------------------------------------------: | :------------------------------: |
| [Qt::UpArrow](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ArrowType-enum) |         向上移动一根线。         |
| [Qt::DownArrow](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ArrowType-enum) |          向下移动一行。          |
| [Qt::LeftArrow](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ArrowType-enum) |        向左移动一个字符。        |
| [Qt::RightArrow](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ArrowType-enum) |        向右移动一个字符。        |
|                           向上翻页                           |      向上移动一页（视口）。      |
|                           向下翻页                           |      向下移动一页（视口）。      |
|                              家                              |        移动到文本的开头。        |
|                             结尾                             |          移至文本末尾。          |
|                           Alt+滚轮                           | 水平滚动页面（滚轮是鼠标滚轮）。 |
|                          Ctrl+滚轮                           |            缩放文本。            |
|                            Ctrl+A                            |          选择所有文本。          |

### 使用 QPlainTextEdit 作为编辑器

有关使用 QPlainTextEdit 作为显示小部件的所有信息也适用于此处。

文本的选择由[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，提供创建选择、检索文本内容或删除选择的功能。您可以使用以下命令检索与用户可见光标对应的对象[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)（） 方法。如果你想在 QPlainTextEdit 中设置一个选择，只需在[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，然后使用该光标使光标成为可见光标[setCursor](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursor-prop)()。可以使用以下命令将选择复制到剪贴板[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)()，或使用以下命令剪切到剪贴板[cut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)()。可以使用选择整个文本[selectAll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()。

QPlainTextEdit 持有[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以使用以下方法检索对象[document](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)（） 方法。您还可以使用设置自己的文档对象[setDocument](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocument)()。[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)发出一个[textChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)如果文本发生更改，() 会发出信号，并且它还提供 isModified() 函数，如果文本自加载以来或自上次使用 false 作为参数调用 setModified 以来已被修改，则该函数将返回 true。此外，它还提供了撤消和重做的方法。

#### 语法高亮

就像[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), QPlainTextEdit 与[QSyntaxHighlighter](https://doc-qt-io.translate.goog/qt-6/qsyntaxhighlighter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

#### 编辑按键绑定

实现编辑的按键绑定列表：

|     按键      |                行动                |
| :-----------: | :--------------------------------: |
|    退格键     |        删除光标左侧的字符。        |
|     删除      |        删除光标右侧的字符。        |
|    Ctrl+C     |     将选定的文本复制到剪贴板。     |
|   Ctrl+插入   |     将选定的文本复制到剪贴板。     |
|    Ctrl+K     |            删除到行尾。            |
|    Ctrl+V     |   将剪贴板文本粘贴到文本编辑中。   |
|  Shift+插入   |   将剪贴板文本粘贴到文本编辑中。   |
|    Ctrl+X     | 删除选定的文本并将其复制到剪贴板。 |
|  Shift+删除   | 删除选定的文本并将其复制到剪贴板。 |
|    Ctrl+Z     |           撤消上次操作。           |
|    Ctrl+Y     |           重做上次操作。           |
|    左箭头     |      将光标向左移动一个字符。      |
| Ctrl+向左箭头 |      将光标向左移动一个单词。      |
|    右箭头     |      将光标向右移动一个字符。      |
|  Ctrl+右箭头  |       将光标向右移动一个字。       |
|   向上箭头    |        将光标向上移动一行。        |
|  Ctrl+向上键  |       将光标向上移动一个字。       |
|   向下箭头    |        将光标向下移动一行。        |
|  Ctrl+向下键  |       将光标向下移动一个字。       |
|   向上翻页    |        将光标向上移动一页。        |
|   向下翻页    |        将光标向下移动一页。        |
|      家       |          将光标移至行首。          |
|   Ctrl+Home   |      将光标移动到文本的开头。      |
|     结尾      |          将光标移至行尾。          |
|   Ctrl+结束   |        将光标移至文本末尾。        |
|   Alt+滚轮    |  水平滚动页面（滚轮是鼠标滚轮）。  |
|   Ctrl+滚轮   |             缩放文本。             |

要选择（标记）文本，请按住 Shift 键，同时按任一移动键击，例如，*Shift+右箭头*将选择右侧的字符，*Shift+Ctrl+右箭头*将选择右侧的单词，等等。

### 与 QTextEdit 的差异

QPlainTextEdit 是一个瘦类，使用了背后的大部分技术来实现[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。其性能优势超过[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)主要源于使用一种不同且简化的文本布局，称为[QPlainTextDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qplaintextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在文本文档上（参见[QTextDocument::setDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocumentLayout)())。纯文本文档布局不支持表格或嵌入框架，并*用逐行分别逐段滚动的方法代替像素精确的高度计算*。这使得处理更大的文档成为可能，并且仍然可以实时调整编辑器的大小并启用换行。它还可以提供快速日志查看器（请参阅[setMaximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)())。

**也可以看看**[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), Qt Widgets - 应用程序示例,[Syntax Highlighter Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-richtext-syntaxhighlighter-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Rich Text Processing](https://doc-qt-io.translate.goog/qt-6/richtext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QPlainTextEdit::LineWrapMode

| 持续的                        | 价值 |
| ----------------------------- | ---- |
| `QPlainTextEdit::NoWrap`      | `0`  |
| `QPlainTextEdit::WidgetWidth` | `1`  |

## 属性文档

### backgroundVisible : bool

该属性保存调色板背景在文档区域外是否可见

如果设置为 true，纯文本编辑将在文本文档未覆盖的视口区域上绘制调色板背景。否则，如果设置为 false，则不会。该功能使用户能够在视觉上区分使用调色板基色绘制的文档区域和未被任何文档覆盖的空白区域。

默认为 false。

**访问功能：**

| bool | **backgroundVisible**() const            |
| ---- | ---------------------------------------- |
| void | **setBackgroundVisible**(bool *visible*) |

### `[read-only]`blockCount : const int

该属性保存文档中文本块的数量。

默认情况下，在空文档中，此属性包含值 1。

**访问功能：**

| int  | **blockCount**() const |
| ---- | ---------------------- |
|      |                        |

### centerOnScroll : bool

该属性保存光标是否应位于屏幕中央

如果设置为 true，纯文本编辑会垂直滚动文档以使光标在视口中心可见。这还允许文本编辑滚动到文档末尾下方。否则，如果设置为 false，纯文本编辑会滚动尽可能小的量，以确保光标可见。相同的算法适用于通过附加的任何新行[appendPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendPlainText)()。

默认为 false。

**访问功能：**

| bool | **centerOnScroll**() const            |
| ---- | ------------------------------------- |
| void | **setCenterOnScroll**(bool *enabled*) |

**也可以看看**[centerCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerCursor)（） 和[ensureCursorVisible](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureCursorVisible)()。

### cursorWidth : int

该属性指定光标的宽度（以像素为单位）。默认值为 1。

**访问功能：**

| int  | **cursorWidth**() const         |
| ---- | ------------------------------- |
| void | **setCursorWidth**(int *width*) |

### documentTitle : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存从文本解析的文档的标题。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **documentTitle**() const                    |
| ------- | -------------------------------------------- |
| void    | **setDocumentTitle**(const QString &*title*) |

### lineWrapMode : [LineWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)

该属性保存换行模式

默认模式是[WidgetWidth](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)这会导致单词在文本编辑的右边缘换行。换行发生在空白处，保持整个单词完整。如果您希望在单词中进行换行，请使用[setWordWrapMode](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)()。

**访问功能：**

| QPlainTextEdit::LineWrapMode | **lineWrapMode**() const                                 |
| ---------------------------- | -------------------------------------------------------- |
| void                         | **setLineWrapMode**(QPlainTextEdit::LineWrapMode *mode*) |

### maximumBlockCount : int

此属性保留文档中块的限制。

指定文档可以具有的最大块数。如果文档中有更多使用此属性指定的块，则会从文档的开头删除。

负值或零值指定文档可以包含无限数量的块。

默认值为 0。

请注意，设置此属性会将限制立即应用于文档内容。设置此属性还会禁用撤消重做历史记录。

**访问功能：**

| int  | **maximumBlockCount**() const           |
| ---- | --------------------------------------- |
| void | **setMaximumBlockCount**(int *maximum*) |

### overwriteMode : bool

该属性保存用户输入的文本是否会覆盖现有文本

与许多文本编辑器一样，纯文本编辑器小部件可以配置为插入或用用户输入的新文本覆盖现有文本。

如果此属性为`true`，则现有文本将被新文本逐字符覆盖；否则，文本将插入到光标位置，替换现有文本。

默认情况下，此属性为`false`（新文本不会覆盖现有文本）。

**访问功能：**

| bool | **overwriteMode**() const              |
| ---- | -------------------------------------- |
| void | **setOverwriteMode**(bool *overwrite*) |

### placeholderText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存编辑器占位符文本

设置此属性使编辑器显示灰色的占位符文本，只要[document](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)（） 是空的。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **placeholderText**() const                              |
| ------- | -------------------------------------------------------- |
| void    | **setPlaceholderText**(const QString &*placeholderText*) |

**也可以看看**[document](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)()。

### plainText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性获取和设置纯文本编辑器的内容。设置此属性后，以前的内容将被删除，撤消/重做历史记录将被重置。[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 也会被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

默认情况下，对于没有内容的编辑器，此属性包含空字符串。

**访问功能：**

| QString | **[toPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)**() const |
| ------- | ------------------------------------------------------------ |
| void    | **[setPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)**(const QString &*text*) |

**通知器信号：**

| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**() |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

### readOnly : bool

该属性保存文本编辑是否只读

在只读文本编辑中，用户只能浏览文本并选择文本；无法修改文本。

该属性的默认值是 false。

**访问功能：**

| bool | **isReadOnly**() const     |
| ---- | -------------------------- |
| void | **setReadOnly**(bool *ro*) |

### tabChangesFocus : bool

该属性是否持有**Tab**改变焦点或被接受为输入

在某些情况下，文本编辑不应允许用户输入制表符或使用**Tab**键，因为这会破坏焦点链。默认为 false。

**访问功能：**

| bool | **tabChangesFocus**() const      |
| ---- | -------------------------------- |
| void | **setTabChangesFocus**(bool *b*) |

### tabStopDistance : [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)

该属性保存制表位距离（以像素为单位）

默认情况下，此属性包含 80 像素的值。

不要设置小于[horizontalAdvance](https://doc-qt-io.translate.goog/qt-6/qfontmetrics.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalAdvance)（） 的[QChar::VisualTabCharacter](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SpecialCharacter-enum)字符，否则制表符将绘制不完整。

**访问功能：**

| qreal | **tabStopDistance**() const              |
| ----- | ---------------------------------------- |
| void  | **setTabStopDistance**(qreal *distance*) |

**也可以看看**[QTextOption::ShowTabsAndSpaces](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flag-enum)和[QTextDocument::defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption)。

### textInteractionFlags : [Qt::TextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextInteractionFlag-enum)

指定标签在显示文本时应如何与用户输入交互。

如果标志包含任一[Qt::LinksAccessibleByKeyboard](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextInteractionFlag-enum)或者[Qt::TextSelectableByKeyboard](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextInteractionFlag-enum)那么焦点策略也自动设置为[Qt::ClickFocus](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusPolicy-enum)。

默认值取决于是否[QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)是只读或可编辑的。

**访问功能：**

| Qt::TextInteractionFlags | **textInteractionFlags**() const                             |
| ------------------------ | ------------------------------------------------------------ |
| void                     | **setTextInteractionFlags**(Qt::TextInteractionFlags *flags*) |

### undoRedoEnabled : bool

该属性保存是否启用撤消和重做

仅当此属性为 true 并且存在可以撤消（或重做）的操作时，用户才能撤消或重做操作。

默认情况下，该属性为`true`。

**访问功能：**

| bool | **isUndoRedoEnabled**() const         |
| ---- | ------------------------------------- |
| void | **setUndoRedoEnabled**(bool *enable*) |

### wordWrapMode : [QTextOption::WrapMode](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WrapMode-enum)

该属性保存模式[QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将在按单词换行文本时使用

默认情况下，该属性设置为[QTextOption::WrapAtWordBoundaryOrAnywhere](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WrapMode-enum)。

**访问功能：**

| QTextOption::WrapMode | **wordWrapMode**() const                            |
| --------------------- | --------------------------------------------------- |
| void                  | **setWordWrapMode**(QTextOption::WrapMode *policy*) |

**也可以看看**[QTextOption::WrapMode](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WrapMode-enum)。

## 成员函数文档

### `[explicit]`QPlainTextEdit::QPlainTextEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个带有父级的空 QPlainTextEdit*parent*。

### `[explicit]`QPlainTextEdit::QPlainTextEdit(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个带有父级的 QPlainTextEdit*parent*。文本编辑将显示纯文本*text*。

### `[virtual]`QPlainTextEdit::~QPlainTextEdit()

析构函数。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::anchorAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

返回位置处锚点的引用*pos*，如果该点不存在锚点，则为空字符串。

### `[slot]`void QPlainTextEdit::appendHtml(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*html*)

附加一个新段落*html*到文本编辑的末尾。

[appendPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendPlainText)()

### `[slot]`void QPlainTextEdit::appendPlainText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

附加一个新段落*text*到文本编辑的末尾。

**也可以看看**[appendHtml](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#appendHtml)()。

### `[protected]`[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::blockBoundingGeometry(const [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*block*) const

返回文本的边框*block*在内容坐标中。平移矩形[contentOffset](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentOffset)() 获取视口上的视觉坐标。

**也可以看看**[firstVisibleBlock](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstVisibleBlock)（） 和[blockBoundingRect](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockBoundingRect)()。

### `[protected]`[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::blockBoundingRect(const [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*block*) const

返回文本的边框*block*在块自己的坐标中。

**也可以看看**[blockBoundingGeometry](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockBoundingGeometry)()。

### `[signal]`void QPlainTextEdit::blockCountChanged(int *newBlockCount*)

每当块计数发生变化时就会发出此信号。新的块计数被传入*newBlockCount*。

### `[virtual protected]`bool QPlainTextEdit::canInsertFromMimeData(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **source*) const

`true`如果 MIME 数据对象的内容由该函数指定，则此函数返回*source*，可以解码并插入到文档中。例如，当在拖动操作期间鼠标进入此小部件并且需要确定是否可以接受拖动时，会调用它。

### bool QPlainTextEdit::canPaste() const

返回文本是否可以从剪贴板粘贴到文本编辑中。

### `[slot]`void QPlainTextEdit::centerCursor()

滚动文档以使光标垂直居中。

**也可以看看**[ensureCursorVisible](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureCursorVisible)（） 和[centerOnScroll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOnScroll-prop)。

### `[override virtual protected]`void QPlainTextEdit::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QFrame::changeEvent](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *ev）。

### `[slot]`void QPlainTextEdit::clear()

删除文本编辑中的所有文本。

笔记：

- 撤消/重做历史记录也会被清除。
- [currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

**也可以看看**[cut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)（） 和[setPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)()。

### `[protected]`[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::contentOffset() const

返回视口坐标中内容的原点。

纯文本编辑内容的来源始终是第一个可见文本块的左上角。当文本水平滚动时，或者当第一个可见块部分滚动离开屏幕时，即可见文本不是从第一个可见块的第一行开始时，内容偏移量与 (0,0) 不同，或者当第一个可见块是第一个块并且编辑器显示边距时。

**也可以看看**[firstVisibleBlock](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstVisibleBlock)(),[horizontalScrollBar](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollBar)（）， 和[verticalScrollBar](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollBar)()。

### `[override virtual protected]`void QPlainTextEdit::contextMenuEvent([QContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qcontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)（QContextMenuEvent *e）。

显示使用创建的标准上下文菜单[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)()。

如果你不希望文本编辑有上下文菜单，你可以设置它[contextMenuPolicy](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuPolicy-prop)到[Qt::NoContextMenu](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ContextMenuPolicy-enum)。如果您想自定义上下文菜单，请重新实现此函数。如果要扩展标准上下文菜单，请重新实现此函数，调用[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)() 并扩展返回的菜单。

有关事件的信息在*event*目的。

```
void MyQPlainTextEdit::contextMenuEvent(QContextMenuEvent *event)
{
    QMenu *menu = createStandardContextMenu();
    menu->addAction(tr("My Menu Item"));
    //...
    menu->exec(event->globalPos());
    delete menu;
}
```

### `[slot]`void QPlainTextEdit::copy()

将任何选定的文本复制到剪贴板。

**也可以看看**[copyAvailable](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copyAvailable)()。

### `[signal]`void QPlainTextEdit::copyAvailable(bool *yes*)

当在文本编辑中选择或取消选择文本时，会发出此信号。

当选择文本时，将发出此信号*yes*设置为 true。如果没有选择任何文本或者如果取消选择所选文本，则发出此信号*yes*设置为假。

如果*yes*那么是真的[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)() 可用于将所选内容复制到剪贴板。如果*yes*那么是假的[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)（） 什么也没做。

**也可以看看**[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)()。

### `[virtual protected]`[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPlainTextEdit::createMimeDataFromSelection() const

此函数返回一个新的 MIME 数据对象来表示文本编辑当前选择的内容。当需要将选择封装到新的中时调用它[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的; 例如，当开始拖放操作时，或者当数据复制到剪贴板时。

如果您重新实现此函数，请注意返回的所有权[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象被传递给调用者。可以使用以下命令检索选择[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)（） 功能。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPlainTextEdit::createStandardContextMenu()

此函数创建标准上下文菜单，当用户用鼠标右键单击文本编辑时显示该菜单。它是从默认调用的[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)() 处理程序。弹出菜单的所有权转移给调用者。

我们建议您使用 createStandardContextMenu([QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)) 版本，它将启用对用户单击位置敏感的操作。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPlainTextEdit::createStandardContextMenu(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*)

此函数创建标准上下文菜单，当用户用鼠标右键单击文本编辑时显示该菜单。它是从默认调用的[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)() 处理程序，它需要*position*在鼠标单击所在的文档坐标中。这可以启用对用户单击位置敏感的操作。弹出菜单的所有权转移给调用者。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::currentCharFormat() const

返回插入新文本时使用的字符格式。

**也可以看看**[setCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCharFormat)()。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::cursorForPosition(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

返回一个[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在位置*pos*（在视口坐标中）。

### `[signal]`void QPlainTextEdit::cursorPositionChanged()

每当光标位置改变时，就会发出该信号。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::cursorRect(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*) const

返回一个矩形（在视口坐标中），其中包括*cursor*。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::cursorRect() const

返回一个矩形（在视口坐标中），其中包含文本编辑的光标。

### `[slot]`void QPlainTextEdit::cut()

将选定的文本复制到剪贴板并将其从文本编辑中删除。

如果没有选定的文本，则不会发生任何事情。

**也可以看看**[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)（） 和[paste](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)()。

### [QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPlainTextEdit::document() const

返回指向基础文档的指针。

**也可以看看**[setDocument](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocument)()。

### `[override virtual protected]`void QPlainTextEdit::dragEnterEvent([QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（QDragEnterEvent *事件）。

### `[override virtual protected]`void QPlainTextEdit::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

### `[override virtual protected]`void QPlainTextEdit::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[override virtual protected]`void QPlainTextEdit::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### void QPlainTextEdit::ensureCursorVisible()

如有必要，通过滚动文本编辑确保光标可见。

**也可以看看**[centerCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerCursor)（） 和[centerOnScroll](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOnScroll-prop)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextEdit::ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QPlainTextEdit::extraSelections() const

返回先前设置的额外选择。

**也可以看看**[setExtraSelections](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExtraSelections)()。

### bool QPlainTextEdit::find(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*exp*, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = QTextDocument::FindFlags())

查找字符串的下一个出现位置，*exp*，使用给定的*options*。返回`true`如果*exp*找到并更改光标以选择匹配项；否则返回`false`.

### bool QPlainTextEdit::find(const [QRegularExpression](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*exp*, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = QTextDocument::FindFlags())

这是一个过载功能。

查找与正则表达式匹配的下一个匹配项，*exp*，使用给定的*options*。这[QTextDocument::FindCaseSensitively](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum)对于此重载，选项被忽略，使用[QRegularExpression::CaseInsensitiveOption](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PatternOption-enum)反而。

如果找到匹配项则返回`true`并更改光标以选择匹配项；否则返回`false`.

### `[protected]`[QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::firstVisibleBlock() const

返回第一个可见块。

**也可以看看**[blockBoundingRect](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockBoundingRect)()。

### `[override virtual protected]`void QPlainTextEdit::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[override virtual protected]`bool QPlainTextEdit::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QPlainTextEdit::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

### `[protected]`[QAbstractTextDocumentLayout::PaintContext](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout-paintcontext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::getPaintContext() const

返回绘制上下文[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()，仅在重新实现时有用[paintEvent](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)()。

### `[override virtual protected]`void QPlainTextEdit::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)（QInputMethodEvent *事件）。

### `[override virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *property*) const

重新实现：[QWidget::inputMethodQuery(Qt::InputMethodQuery query) const](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)。

### `[virtual protected]`void QPlainTextEdit::insertFromMimeData(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **source*)

该函数插入 MIME 数据对象的内容，由*source*，进入当前光标位置的文本编辑。每当由于剪贴板粘贴操作而插入文本时，或者当文本编辑接受来自拖放操作的数据时，都会调用它。

### `[slot]`void QPlainTextEdit::insertPlainText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

方便插入的插槽*text*在当前光标位置。

它相当于

```
edit->textCursor().insertText(text);
```

### `[override virtual protected]`void QPlainTextEdit::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

### `[override virtual protected]`void QPlainTextEdit::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（QKeyEvent *事件）。

### `[virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::loadResource(int *type*, const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

加载给定指定的资源*type*和*name*。

这个函数是一个扩展[QTextDocument::loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

**也可以看看**[QTextDocument::loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

### void QPlainTextEdit::mergeCurrentCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*modifier*)

合并指定的属性*modifier*通过调用转换为当前字符格式[QTextCursor::mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)在编辑器的光标上。如果编辑器有一个选择，则属性*modifier*直接应用于选择。

**也可以看看**[QTextCursor::mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)()。

### `[signal]`void QPlainTextEdit::modificationChanged(bool *changed*)

每当文档内容发生变化并影响修改状态时，就会发出此信号。如果*changed*属实，文档已被修改；否则就是假的。

例如，在文档上调用 setModified(false) 然后插入文本会导致发出信号。如果您撤消该操作，导致文档返回到其原始未修改状态，则该信号将再次发出。

### `[override virtual protected]`void QPlainTextEdit::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QPlainTextEdit::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QPlainTextEdit::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QPlainTextEdit::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(QMouseEvent *e)。

### void QPlainTextEdit::moveCursor([QTextCursor::MoveOperation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveOperation-enum) *operation*, [QTextCursor::MoveMode](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum) *mode* = QTextCursor::MoveAnchor)

通过执行给定的操作来移动光标*operation*。

如果*mode*是[QTextCursor::KeepAnchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum)，光标选择它移动到的文本。这与用户按住 Shift 键并使用光标键移动光标时获得的效果相同。

**也可以看看**[QTextCursor::movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)()。

### `[override virtual protected]`void QPlainTextEdit::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[slot]`void QPlainTextEdit::paste()

将剪贴板中的文本粘贴到当前光标位置的文本编辑中。

如果剪贴板中没有文本，则不会发生任何事情。

改变这个函数的行为，即修改什么[QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以粘贴以及如何粘贴，重新实现虚拟[canInsertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canInsertFromMimeData)（） 和[insertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFromMimeData)（） 功能。

**也可以看看**[cut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)（） 和[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)()。

### void QPlainTextEdit::print([QPagedPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpagedpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **printer*) const

将文本编辑的文档打印到给定的便捷功能*printer*。这相当于直接在文档上调用 print 方法，只不过该函数还支持 QPrinter::Selection 作为打印范围。

**也可以看看**[QTextDocument::print](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#print)()。

### `[slot]`void QPlainTextEdit::redo()

重做上次操作。

如果没有要重做的操作，即撤消/重做历史记录中没有重做步骤，则不会发生任何情况。

**也可以看看**[undo](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo)()。

### `[signal]`void QPlainTextEdit::redoAvailable(bool *available*)

每当重做操作可用时就会发出此信号（*available*为真）或不可用（*available*是假的）。

### `[override virtual protected]`void QPlainTextEdit::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[override virtual protected]`void QPlainTextEdit::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

### `[slot]`void QPlainTextEdit::selectAll()

选择所有文本。

**也可以看看**[copy](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)(),[cut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)（）， 和[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)()。

### `[signal]`void QPlainTextEdit::selectionChanged()

每当选择发生变化时就会发出此信号。

**也可以看看**[copyAvailable](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copyAvailable)()。

### void QPlainTextEdit::setCurrentCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置插入新文本时使用的字符格式*format*通过致电[QTextCursor::setCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCharFormat)() 位于编辑器的光标上。如果编辑器有一个选择，则字符格式将直接应用于该选择。

**也可以看看**[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)()。

### void QPlainTextEdit::setDocument([QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **document*)

使*document*文本编辑器的新文档。

家长[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)所提供文档的所有者仍然是该对象的所有者。如果当前文档是文本编辑器的子文档，则将其删除。

该文档必须具有继承的文档布局[QPlainTextDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qplaintextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（看[QTextDocument::setDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocumentLayout)())。

**也可以看看**[document](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)()。

### void QPlainTextEdit::setExtraSelections(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextEdit::ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*selections*)

此功能允许使用给定颜色临时标记文档中的某些区域，指定为*selections*。例如，这在编程编辑器中很有用，可以用给定的背景颜色标记整行文本以指示断点的存在。

**也可以看看**[QTextEdit::ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[extraSelections](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#extraSelections)()。

### `[slot]`void QPlainTextEdit::setPlainText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

将文本编辑的文本更改为字符串*text*。任何先前的文本都将被删除。

*text*被解释为纯文本。

笔记：

- 撤消/重做历史记录也会被清除。
- [currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

**注意：**属性的 Setter 函数[plainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)。

**也可以看看**[toPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)()。

### void QPlainTextEdit::setTextCursor(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*)

设置可见*cursor*。

**也可以看看**[textCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)()。

### `[override virtual protected]`void QPlainTextEdit::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### `[signal]`void QPlainTextEdit::textChanged()

每当文档内容发生更改时都会发出此信号；例如，插入或删除文本时，或者应用格式时。

**注意：**属性的通知程序信号[plainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::textCursor() const

返回一个副本[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代表当前可见的光标。请注意，返回游标的更改不会影响[QPlainTextEdit](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的光标；使用[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)() 更新可见光标。

**也可以看看**[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPlainTextEdit::toPlainText() const

以纯文本形式返回文本编辑的文本。

**注意：**属性的 getter 函数[plainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)。

**也可以看看**[QPlainTextEdit::setPlainText](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)()。

### `[slot]`void QPlainTextEdit::undo()

撤消上次操作。

如果没有要撤消的操作，即撤消/重做历史记录中没有撤消步骤，则不会发生任何情况。

**也可以看看**[redo](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo)()。

### `[signal]`void QPlainTextEdit::undoAvailable(bool *available*)

每当撤消操作可用时就会发出此信号（*available*为真）或不可用（*available*是假的）。

### `[signal]`void QPlainTextEdit::updateRequest(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, int *dy*)

当文本文档需要更新指定的内容时，会发出此信号*rect*。如果文本滚动，*rect*将覆盖整个视口区域。如果文本垂直滚动，*dy*携带视口滚动的像素数量。

该信号的目的是支持纯文本编辑子类中的额外小部件，例如显示行号、断点或其他额外信息。

### `[override virtual protected]`void QPlainTextEdit::wheelEvent([QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)(QWheelEvent *e)。

### `[slot]`void QPlainTextEdit::zoomIn(int *range* = 1)

通过设置基本字体大小来放大文本*range*点变大并重新计算所有字体大小以成为新大小。这不会改变任何图像的大小。

**也可以看看**[zoomOut](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomOut)()。

### `[slot]`void QPlainTextEdit::zoomOut(int *range* = 1)

通过设置基本字体大小来缩小文本*range*点变小并重新计算所有字体大小以成为新大小。这不会改变任何图像的大小。

**也可以看看**[zoomIn](https://doc-qt-io.translate.goog/qt-6/qplaintextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomIn)()。