#  QTextEdit Class

QTextEdit 类提供了一个用于编辑和显示纯文本和富文本的小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include <QTextEdit>                                         |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextEdit 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| struct | **[ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ------ | ------------------------------------------------------------ |
| flags  | **[AutoFormatting](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum)** |
| enum   | **[AutoFormattingFlag](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum)** { AutoNone, AutoBulletList, AutoAll } |
| enum   | **[LineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)** { NoWrap, WidgetWidth, FixedPixelWidth, FixedColumnWidth } |

## 特性

| **[acceptRichText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptRichText-prop)** : bool**[autoFormatting](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFormatting-prop)** : AutoFormatting**[cursorWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWidth-prop)** : int**[document](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)** : QTextDocument***[documentTitle](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)** : QString**[html](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)** : QString**[lineWrapColumnOrWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapColumnOrWidth-prop)** : int**[lineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)** : LineWrapMode**[markdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)** : QString | **[overwriteMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overwriteMode-prop)** : bool**[placeholderText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)** : QString**[plainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)** : QString**[readOnly](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)** : bool**[tabChangesFocus](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabChangesFocus-prop)** : bool**[tabStopDistance](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabStopDistance-prop)** : qreal**[textInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)** : Qt::TextInteractionFlags**[undoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)** : bool**[wordWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)** : QTextOption::WrapMode |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                                  | **[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextEdit)**(QWidget **parent* = nullptr) |
| -------------------------------- | ------------------------------------------------------------ |
|                                  | **[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextEdit-1)**(const QString &*text*, QWidget **parent* = nullptr) |
| virtual                          | **[~QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTextEdit)**() |
| bool                             | **[acceptRichText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptRichText-prop)**() const |
| Qt::Alignment                    | **[alignment](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)**() const |
| QString                          | **[anchorAt](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchorAt)**(const QPoint &*pos*) const |
| QTextEdit::AutoFormatting        | **[autoFormatting](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFormatting-prop)**() const |
| bool                             | **[canPaste](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canPaste)**() const |
| QMenu *                          | **[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)**() |
| QMenu *                          | **[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu-1)**(const QPoint &*position*) |
| QTextCharFormat                  | **[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)**() const |
| QFont                            | **[currentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)**() const |
| QTextCursor                      | **[cursorForPosition](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorForPosition)**(const QPoint &*pos*) const |
| QRect                            | **[cursorRect](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorRect)**(const QTextCursor &*cursor*) const |
| QRect                            | **[cursorRect](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorRect-1)**() const |
| int                              | **[cursorWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWidth-prop)**() const |
| QTextDocument *                  | **[document](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)**() const |
| QString                          | **[documentTitle](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)**() const |
| void                             | **[ensureCursorVisible](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureCursorVisible)**() |
| QList<QTextEdit::ExtraSelection> | **[extraSelections](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#extraSelections)**() const |
| bool                             | **[find](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)**(const QString &*exp*, QTextDocument::FindFlags *options* = QTextDocument::FindFlags()) |
| bool                             | **[find](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-1)**(const QRegularExpression &*exp*, QTextDocument::FindFlags *options* = QTextDocument::FindFlags()) |
| QString                          | **[fontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFamily)**() const |
| bool                             | **[fontItalic](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontItalic)**() const |
| qreal                            | **[fontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontPointSize)**() const |
| bool                             | **[fontUnderline](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontUnderline)**() const |
| int                              | **[fontWeight](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontWeight)**() const |
| bool                             | **[isReadOnly](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)**() const |
| bool                             | **[isUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)**() const |
| int                              | **[lineWrapColumnOrWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapColumnOrWidth-prop)**() const |
| QTextEdit::LineWrapMode          | **[lineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)**() const |
| virtual QVariant                 | **[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)**(int *type*, const QUrl &*name*) |
| void                             | **[mergeCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCurrentCharFormat)**(const QTextCharFormat &*modifier*) |
| void                             | **[moveCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveCursor)**(QTextCursor::MoveOperation *operation*, QTextCursor::MoveMode *mode* = QTextCursor::MoveAnchor) |
| bool                             | **[overwriteMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overwriteMode-prop)**() const |
| QString                          | **[placeholderText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)**() const |
| void                             | **[print](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#print)**(QPagedPaintDevice **printer*) const |
| void                             | **[setAcceptRichText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptRichText-prop)**(bool *accept*) |
| void                             | **[setAutoFormatting](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFormatting-prop)**(QTextEdit::AutoFormatting *features*) |
| void                             | **[setCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCharFormat)**(const QTextCharFormat &*format*) |
| void                             | **[setCursorWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorWidth-prop)**(int *width*) |
| void                             | **[setDocument](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)**(QTextDocument **document*) |
| void                             | **[setDocumentTitle](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)**(const QString &*title*) |
| void                             | **[setExtraSelections](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExtraSelections)**(const QList<QTextEdit::ExtraSelection> &*selections*) |
| void                             | **[setLineWrapColumnOrWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapColumnOrWidth-prop)**(int *w*) |
| void                             | **[setLineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)**(QTextEdit::LineWrapMode *mode*) |
| void                             | **[setOverwriteMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overwriteMode-prop)**(bool *overwrite*) |
| void                             | **[setPlaceholderText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#placeholderText-prop)**(const QString &*placeholderText*) |
| void                             | **[setReadOnly](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)**(bool *ro*) |
| void                             | **[setTabChangesFocus](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabChangesFocus-prop)**(bool *b*) |
| void                             | **[setTabStopDistance](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabStopDistance-prop)**(qreal *distance*) |
| void                             | **[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)**(const QTextCursor &*cursor*) |
| void                             | **[setTextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)**(Qt::TextInteractionFlags *flags*) |
| void                             | **[setUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)**(bool *enable*) |
| void                             | **[setWordWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)**(QTextOption::WrapMode *policy*) |
| bool                             | **[tabChangesFocus](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabChangesFocus-prop)**() const |
| qreal                            | **[tabStopDistance](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabStopDistance-prop)**() const |
| QColor                           | **[textBackgroundColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textBackgroundColor)**() const |
| QColor                           | **[textColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textColor)**() const |
| QTextCursor                      | **[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)**() const |
| Qt::TextInteractionFlags         | **[textInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)**() const |
| QString                          | **[toHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)**() const |
| QString                          | **[toMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)**(QTextDocument::MarkdownFeatures *features* = QTextDocument::MarkdownDialectGitHub) const |
| QString                          | **[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)**() const |
| QTextOption::WrapMode            | **[wordWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)**() const |

## 重载的公共函数

| virtual QVariant | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *property*) const override |
| ---------------- | ------------------------------------------------------------ |
|                  |                                                              |

## 公共槽

| void | **[append](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)**(const QString &*text*) |
| ---- | ------------------------------------------------------------ |
| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| void | **[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)**() |
| void | **[cut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)**() |
| void | **[insertHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertHtml)**(const QString &*text*) |
| void | **[insertPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertPlainText)**(const QString &*text*) |
| void | **[paste](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)**() |
| void | **[redo](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo)**() |
| void | **[scrollToAnchor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToAnchor)**(const QString &*name*) |
| void | **[selectAll](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)**() |
| void | **[setAlignment](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAlignment)**(Qt::Alignment *a*) |
| void | **[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)**(const QFont &*f*) |
| void | **[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)**(const QString &*fontFamily*) |
| void | **[setFontItalic](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontItalic)**(bool *italic*) |
| void | **[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)**(qreal *s*) |
| void | **[setFontUnderline](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontUnderline)**(bool *underline*) |
| void | **[setFontWeight](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontWeight)**(int *weight*) |
| void | **[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)**(const QString &*text*) |
| void | **[setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)**(const QString &*markdown*) |
| void | **[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)**(const QString &*text*) |
| void | **[setText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setText)**(const QString &*text*) |
| void | **[setTextBackgroundColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextBackgroundColor)**(const QColor &*c*) |
| void | **[setTextColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextColor)**(const QColor &*c*) |
| void | **[undo](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo)**() |
| void | **[zoomIn](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomIn)**(int *range* = 1) |
| void | **[zoomOut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomOut)**(int *range* = 1) |

## 信号

| void | **[copyAvailable](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copyAvailable)**(bool *yes*) |
| ---- | ------------------------------------------------------------ |
| void | **[currentCharFormatChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormatChanged)**(const QTextCharFormat &*f*) |
| void | **[cursorPositionChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionChanged)**() |
| void | **[redoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable)**(bool *available*) |
| void | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**() |
| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**() |
| void | **[undoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)**(bool *available*) |

## protected function

| virtual bool        | **[canInsertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canInsertFromMimeData)**(const QMimeData **source*) const |
| ------------------- | ------------------------------------------------------------ |
| virtual QMimeData * | **[createMimeDataFromSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createMimeDataFromSelection)**() const |
| virtual void        | **[insertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFromMimeData)**(const QMimeData **source*) |

## 重载的protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QContextMenuEvent **event*) override |
| virtual void | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QDragEnterEvent **e*) override |
| virtual void | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **e*) override |
| virtual void | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **e*) override |
| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **e*) override |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **e*) override |
| virtual bool | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **e*) override |
| virtual void | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **e*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **e*) override |
| virtual void | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **e*) override |
| virtual void | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent *) override |
| virtual void | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QWheelEvent **e*) override |

## 详细说明

### 简介和概念

QTextEdit 是一种高级的所见即所得查看器/编辑器，支持使用 HTML 样式标签或 Markdown 格式的富文本格式。它经过优化，可以处理大型文档并快速响应用户输入。

QTextEdit 适用于段落和字符。段落是一个格式化的字符串，它被自动换行以适应小部件的宽度。默认情况下，阅读纯文本时，一个换行符表示一个段落。文档由零个或多个段落组成。段落中的单词按照段落的对齐方式对齐。段落之间用硬换行符分隔。段落中的每个字符都有自己的属性，例如字体和颜色。

QTextEdit可以显示图像、列表和表格。如果文本太大而无法在文本编辑的视口中查看，则会出现滚动条。文本编辑可以加载纯文本和富文本文件。富文本可以使用 HTML 4 标记的子集来描述；参考[Supported HTML Subset](https://doc-qt-io.translate.goog/qt-6/richtext-html-subset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)页面了解更多信息。

如果您只需要显示一小段富文本使用[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

Qt 中的富文本支持旨在提供一种快速、可移植且高效的方式来向应用程序添加合理的在线帮助设施，并为富文本编辑器提供基础。如果您发现 HTML 支持不足以满足您的需求，您可以考虑使用 Qt WebKit，它提供了功能齐全的 Web 浏览器小部件。

QTextEdit 上鼠标光标的形状是[Qt::IBeamCursor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorShape-enum)默认情况下。可以通过以下方式更改[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)() 的光标属性。

### 使用 QTextEdit 作为显示小部件

QTextEdit 可以显示大型 HTML 子集，包括表格和图像。

可以使用设置或替换文本[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)() 删除任何现有文本并将其替换为传入的文本[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)（） 称呼。如果你打电话[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)() 使用旧版 HTML，然后调用[toHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)()，返回的文本可能有不同的标记，但会呈现相同的效果。可以使用以下命令删除整个文本[clear](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

文本也可以使用设置或替换[setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)()，并且同样的警告适用：如果您随后调用[toMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)()，返回的文本可能不同，但尽可能保留含义。可以解析带有一些嵌入 HTML 的 Markdown，具有与[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)（） 有; 但[toMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)() 只编写“纯”Markdown，没有任何嵌入的 HTML。

文本本身可以使用插入[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类或使用便利函数[insertHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertHtml)(),[insertPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertPlainText)(),[append](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#append)（） 或者[paste](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)()。[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)还能够将复杂的对象（例如表格或列表）插入到文档中，并且它处理创建选择并对所选文本应用更改。

默认情况下，文本编辑会在空格处换行以适合文本编辑小部件。这[setLineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)() 函数用于指定您想要的换行类型，或者[NoWrap](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)如果你不想要任何包装。称呼[setLineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)() 设置固定像素宽度[FixedPixelWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)，或字符列（例如80列）[FixedColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)与指定的像素或列[setLineWrapColumnOrWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapColumnOrWidth-prop)()。如果您对小部件的宽度使用自动换行[WidgetWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)，您可以指定是否在空格或任何地方中断[setWordWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)()。

这[find](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)() 函数可用于查找并选择文本中的给定字符串。

如果您想限制 QTextEdit 中的段落总数，例如它在日志查看器中通常很有用，那么您可以使用[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的 MaximumBlockCount 属性。

#### 只读键绑定

当 QTextEdit 以只读方式使用时，按键绑定仅限于导航，并且只能使用鼠标选择文本：

|   按键    |               行动               |
| :-------: | :------------------------------: |
|   向上    |         向上移动一根线。         |
|   向下    |          向下移动一行。          |
|   左边    |        向左移动一个字符。        |
|  正确的   |        向右移动一个字符。        |
| 向上翻页  |      向上移动一页（视口）。      |
| 向下翻页  |      向下移动一页（视口）。      |
|    家     |        移动到文本的开头。        |
|   结尾    |          移至文本末尾。          |
| Alt+滚轮  | 水平滚动页面（滚轮是鼠标滚轮）。 |
| Ctrl+滚轮 |            缩放文本。            |
|  Ctrl+A   |          选择所有文本。          |

文本编辑也许能够提供一些元信息。例如，[documentTitle](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)() 函数将从 HTML 标记中返回文本`<title>`。

**注意：**仅当字体大小未设置为固定大小时，缩放 HTML 文档才有效。

### 使用 QTextEdit 作为编辑器

有关使用 QTextEdit 作为显示小部件的所有信息也适用于此处。

当前字符格式的属性设置为[setFontItalic](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontItalic)(),[setFontWeight](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontWeight)(),[setFontUnderline](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontUnderline)(),[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)(),[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)(),[setTextColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextColor)（） 和[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)()。当前段落的对齐方式设置为[setAlignment](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAlignment)()。

文本的选择由[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，提供创建选择、检索文本内容或删除选择的功能。您可以使用以下命令检索与用户可见光标对应的对象[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)（） 方法。如果你想在 QTextEdit 中设置一个选择，只需在[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，然后使用该光标使光标成为可见光标[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)()。可以使用以下命令将选择复制到剪贴板[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)()，或使用以下命令剪切到剪贴板[cut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)()。可以使用选择整个文本[selectAll](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectAll)()。

当光标移动并且底层格式属性发生变化时，[currentCharFormatChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormatChanged)发出 () 信号以反映新光标位置处的新属性。

这[textChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)每当文本发生变化时（由于[setText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setText)() 或通过编辑器本身）。

QTextEdit 拥有一个[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以使用以下方法检索对象[document](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)（） 方法。您还可以使用设置自己的文档对象[setDocument](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)()。

[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供了一个[isModified](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)() 函数，如果文本自加载以来或自上次使用 false 作为参数调用 setModified 以来已被修改，则该函数将返回 true。此外，它还提供了撤消和重做的方法。

#### 拖放

QTextEdit 还支持自定义拖放行为。默认情况下，当用户将这些 MIME 类型的数据拖放到文档中时，QTextEdit 将插入纯文本、HTML 和富文本。重新实现[canInsertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canInsertFromMimeData)（） 和[insertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFromMimeData)() 添加对其他 MIME 类型的支持。

例如，要允许用户将图像拖放到 QTextEdit 上，您可以通过以下方式实现这些功能：

```
bool TextEdit::canInsertFromMimeData( const QMimeData *source ) const
{
    if (source->hasImage())
        return true;
    else
        return QTextEdit::canInsertFromMimeData(source);
}
```

我们通过返回 true 添加对图像 MIME 类型的支持。对于所有其他 MIME 类型，我们使用默认实现。

```
void TextEdit::insertFromMimeData( const QMimeData *source )
{
    if (source->hasImage())
    {
        QImage image = qvariant_cast<QImage>(source->imageData());
        QTextCursor cursor = this->textCursor();
        QTextDocument *document = this->document();
        document->addResource(QTextDocument::ImageResource, QUrl("image"), image);
        cursor.insertImage("image");
    }
}
```

我们将图像从[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)由 MIME 源保存并将其作为资源插入到文档中。

#### 编辑按键绑定

实现编辑的按键绑定列表：

|    按键    |                行动                |
| :--------: | :--------------------------------: |
|   退格键   |        删除光标左侧的字符。        |
|    删除    |        删除光标右侧的字符。        |
|   Ctrl+C   |     将选定的文本复制到剪贴板。     |
| Ctrl+插入  |     将选定的文本复制到剪贴板。     |
|   Ctrl+K   |            删除到行尾。            |
|   Ctrl+V   |   将剪贴板文本粘贴到文本编辑中。   |
| Shift+插入 |   将剪贴板文本粘贴到文本编辑中。   |
|   Ctrl+X   | 删除选定的文本并将其复制到剪贴板。 |
| Shift+删除 | 删除选定的文本并将其复制到剪贴板。 |
|   Ctrl+Z   |           撤消上次操作。           |
|   Ctrl+Y   |           重做上次操作。           |
|    左边    |      将光标向左移动一个字符。      |
| Ctrl+左键  |      将光标向左移动一个单词。      |
|   正确的   |      将光标向右移动一个字符。      |
|  Ctrl+右   |       将光标向右移动一个字。       |
|    向上    |        将光标向上移动一行。        |
|    向下    |        将光标向下移动一行。        |
|  向上翻页  |        将光标向上移动一页。        |
|  向下翻页  |        将光标向下移动一页。        |
|     家     |          将光标移至行首。          |
| Ctrl+Home  |      将光标移动到文本的开头。      |
|    结尾    |          将光标移至行尾。          |
| Ctrl+结束  |        将光标移至文本末尾。        |
|  Alt+滚轮  |  水平滚动页面（滚轮是鼠标滚轮）。  |

要选择（标记）文本，请按住 Shift 键，同时按任一移动键击，例如，*Shift+Right*将选择右侧的字符，*Shift+Ctrl+Right*将选择右侧的单词，等等。

**可以参阅**[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), Qt Widgets - 应用程序示例,[Syntax Highlighter Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-richtext-syntaxhighlighter-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Rich Text Processing](https://doc-qt-io.translate.goog/qt-6/richtext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QTextEdit:: AutoFormattingFlag 标志 QTextEdit:: AutoFormatting

| 持续的                      | 价值         | 描述                                                         |
| --------------------------- | ------------ | ------------------------------------------------------------ |
| `QTextEdit::AutoNone`       | `0`          | 不要执行任何自动格式化。                                     |
| `QTextEdit::AutoBulletList` | `0x00000001` | 自动创建项目符号列表（例如，当用户在最左边的列中输入星号（“*”）或在现有列表项中按 Enter 键时。 |
| `QTextEdit::AutoAll`        | `0xffffffff` | 应用所有自动格式。目前仅支持自动项目符号列表。               |

AutoFormatting 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <AutoFormattingFlag> 的类型定义。它存储 AutoFormattingFlag 值的 OR 组合。

### enum QTextEdit::LineWrapMode

| 持续的                        | 价值 |
| ----------------------------- | ---- |
| `QTextEdit::NoWrap`           | `0`  |
| `QTextEdit::WidgetWidth`      | `1`  |
| `QTextEdit::FixedPixelWidth`  | `2`  |
| `QTextEdit::FixedColumnWidth` | `3`  |

## 属性文档

### acceptRichText : bool

该属性保存文本编辑是否接受用户插入的富文本

当此属性设置为 false 时，文本编辑将仅接受用户的纯文本输入。例如通过剪贴板或拖放。

该属性的默认值为 true。

**访问功能：**

| bool | **acceptRichText**() const           |
| ---- | ------------------------------------ |
| void | **setAcceptRichText**(bool *accept*) |

### autoFormatting : [AutoFormatting](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum)

该属性保存启用的自动格式化功能集

该值可以是中值的任意组合[AutoFormattingFlag](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum)枚举。默认为[AutoNone](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum)。选择[AutoAll](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum)启用所有自动格式化。

目前，唯一提供的自动格式化功能是[AutoBulletList](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AutoFormattingFlag-enum); Qt 的未来版本可能会提供更多功能。

**访问功能：**

| QTextEdit::AutoFormatting | **autoFormatting**() const                                  |
| ------------------------- | ----------------------------------------------------------- |
| void                      | **setAutoFormatting**(QTextEdit::AutoFormatting *features*) |

### cursorWidth : int

该属性指定光标的宽度（以像素为单位）。默认值为 1。

**访问功能：**

| int  | **cursorWidth**() const         |
| ---- | ------------------------------- |
| void | **setCursorWidth**(int *width*) |

### document : [QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*

该属性保存文本编辑器的基础文档。

**注意：**编辑器*不拥有文档的所有权*，除非它是文档的父对象。所提供文档的父对象仍然是该对象的所有者。如果先前分配的文档是编辑器的子文档，那么它将被删除。

**访问功能：**

| QTextDocument * | **document**() const                       |
| --------------- | ------------------------------------------ |
| void            | **setDocument**(QTextDocument **document*) |

### documentTitle : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存从文本解析的文档的标题。

默认情况下，对于新创建的空文档，此属性包含空字符串。

**访问功能：**

| QString | **documentTitle**() const                    |
| ------- | -------------------------------------------- |
| void    | **setDocumentTitle**(const QString &*title*) |

### html : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性为文本编辑的文本提供了 HTML 界面。

toHtml() 将文本编辑的文本返回为 html。

setHtml() 更改文本编辑的文本。任何先前的文本都将被删除，并且撤消/重做历史记录将被清除。输入文本被解释为 html 格式的富文本。[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 也会被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

**注意：**调用者有责任确保文本在调用时正确解码。[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建包含 HTML 的内容并将其传递给 setHtml()。

默认情况下，对于新创建的空文档，此属性包含用于描述没有正文文本的 HTML 4.0 文档的文本。

**访问功能：**

| QString | **toHtml**() const                 |
| ------- | ---------------------------------- |
| void    | **setHtml**(const QString &*text*) |

**通知器信号：**

| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**() |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**可以参阅**[Supported HTML Subset](https://doc-qt-io.translate.goog/qt-6/richtext-html-subset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[plainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)。

### lineWrapColumnOrWidth : int

此属性保存文本将被换行的位置（以像素或列为单位，具体取决于换行模式）

如果换行模式是[FixedPixelWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)，该值是距离文本编辑左边缘应换行的像素数。如果换行模式是[FixedColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)，该值是距文本编辑左边缘的列号（在字符列中），文本应在该位置换行。

默认情况下，此属性包含值 0。

**访问功能：**

| int  | **lineWrapColumnOrWidth**() const     |
| ---- | ------------------------------------- |
| void | **setLineWrapColumnOrWidth**(int *w*) |

**可以参阅**[lineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapMode-prop)。

### lineWrapMode : [LineWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)

该属性保存换行模式

默认模式是[WidgetWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)这会导致单词在文本编辑的右边缘换行。换行发生在空白处，保持整个单词完整。如果您希望在单词中进行换行，请使用[setWordWrapMode](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wordWrapMode-prop)()。如果您设置换行模式[FixedPixelWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)或者[FixedColumnWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LineWrapMode-enum)你也应该打电话[setLineWrapColumnOrWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapColumnOrWidth-prop)() 为您想要的宽度。

**访问功能：**

| QTextEdit::LineWrapMode | **lineWrapMode**() const                            |
| ----------------------- | --------------------------------------------------- |
| void                    | **setLineWrapMode**(QTextEdit::LineWrapMode *mode*) |

**可以参阅**[lineWrapColumnOrWidth](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineWrapColumnOrWidth-prop)。

### markdown : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性为文本编辑的文本提供了 Markdown 接口。

`toMarkdown()`将文本编辑的文本返回为“纯”Markdown，没有任何嵌入的 HTML 格式。一些功能[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)支持（例如使用特定颜色和命名字体）无法用“纯”Markdown 表达，它们将被省略。

`setMarkdown()`更改文本编辑的文本。任何先前的文本都将被删除，并且撤消/重做历史记录将被清除。输入文本被解释为 Markdown 格式的富文本。

解析包含在*markdown*字符串的处理方式与[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop); 但是，不支持 HTML 块内的 Markdown 格式。

解析器的某些功能可以通过以下方式启用或禁用*features*争论：

| 持续的                      | 描述                                      |
| --------------------------- | ----------------------------------------- |
| `MarkdownNoHTML`            | Markdown 文本中的任何 HTML 标签都将被丢弃 |
| `MarkdownDialectCommonMark` | 解析器仅支持 CommonMark 标准化的功能      |
| `MarkdownDialectGitHub`     | 解析器支持 GitHub 方言                    |

默认为`MarkdownDialectGitHub`.

**访问功能：**

| QString | **toMarkdown**(QTextDocument::MarkdownFeatures *features* = QTextDocument::MarkdownDialectGitHub) const |
| ------- | ------------------------------------------------------------ |
| void    | **setMarkdown**(const QString &*markdown*)                   |

**通知器信号：**

| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**() |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**可以参阅**[plainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop),[html](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop),[QTextDocument::toMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toMarkdown)（）， 和[QTextDocument::setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMarkdown)()。

### overwriteMode : bool

该属性保存用户输入的文本是否会覆盖现有文本

与许多文本编辑器一样，文本编辑器小部件可以配置为插入或用用户输入的新文本覆盖现有文本。

如果此属性为`true`，则现有文本将被新文本逐字符覆盖；否则，文本将插入到光标位置，替换现有文本。

默认情况下，此属性为`false`（新文本不会覆盖现有文本）。

**访问功能：**

| bool | **overwriteMode**() const              |
| ---- | -------------------------------------- |
| void | **setOverwriteMode**(bool *overwrite*) |

### placeholderText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存编辑器占位符文本

设置此属性使编辑器显示灰色的占位符文本，只要[document](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)（） 是空的。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **placeholderText**() const                              |
| ------- | -------------------------------------------------------- |
| void    | **setPlaceholderText**(const QString &*placeholderText*) |

**可以参阅**[document](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document-prop)()。

### plainText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性将文本编辑器的内容保存为纯文本。

设置该属性后，以前的内容将被删除，撤消/重做历史记录将被重置。[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 也会被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

如果文本编辑有其他内容类型，则调用时它不会被纯文本替换[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)()。唯一的例外是不间断空格，*nbsp；*，将转换为标准空间。

默认情况下，对于没有内容的编辑器，此属性包含空字符串。

**访问功能：**

| QString | **[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)**() const |
| ------- | ------------------------------------------------------------ |
| void    | **[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)**(const QString &*text*) |

**可以参阅**[html](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)。

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

**可以参阅**[QTextOption::ShowTabsAndSpaces](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Flag-enum)和[QTextDocument::defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption)。

### textInteractionFlags : [Qt::TextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextInteractionFlag-enum)

指定小部件应如何与用户输入交互。

默认值取决于是否[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)是只读还是可编辑，以及是否是[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或不。

**访问功能：**

| Qt::TextInteractionFlags | **textInteractionFlags**() const                             |
| ------------------------ | ------------------------------------------------------------ |
| void                     | **setTextInteractionFlags**(Qt::TextInteractionFlags *flags*) |

### undoRedoEnabled : bool

该属性保存是否启用撤消和重做。

仅当此属性为 true 并且存在可以撤消（或重做）的操作时，用户才能撤消或重做操作。

**访问功能：**

| bool | **isUndoRedoEnabled**() const         |
| ---- | ------------------------------------- |
| void | **setUndoRedoEnabled**(bool *enable*) |

### wordWrapMode : [QTextOption::WrapMode](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WrapMode-enum)

该属性保存模式[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将在按单词换行文本时使用

默认情况下，该属性设置为[QTextOption::WrapAtWordBoundaryOrAnywhere](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WrapMode-enum)。

**访问功能：**

| QTextOption::WrapMode | **wordWrapMode**() const                            |
| --------------------- | --------------------------------------------------- |
| void                  | **setWordWrapMode**(QTextOption::WrapMode *policy*) |

**可以参阅**[QTextOption::WrapMode](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WrapMode-enum)。

## 成员函数文档

### `[explicit]`QTextEdit::QTextEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的 QTextEdit 及其父级*parent*。

### `[explicit]`QTextEdit::QTextEdit(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个带有父级的 QTextEdit*parent*。文本编辑将显示文本*text*。文本被解释为 html。

### `[virtual]`QTextEdit::~QTextEdit()

析构函数。

### [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) QTextEdit::alignment() const

返回当前段落的对齐方式。

**可以参阅**[setAlignment](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAlignment)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::anchorAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

返回位置处锚点的引用*pos*，如果该点不存在锚点，则为空字符串。

### `[slot]`void QTextEdit::append(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

附加一个新段落*text*到文本编辑的末尾。

**注意：**附加的新段落将具有与当前段落相同的字符格式和块格式，具体取决于光标的位置。

**可以参阅**[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)（） 和[QTextCursor::blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### `[virtual protected]`bool QTextEdit::canInsertFromMimeData(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **source*) const

`true`如果 MIME 数据对象的内容由该函数指定，则此函数返回*source*，可以解码并插入到文档中。例如，当在拖动操作期间鼠标进入该小部件并且需要确定是否可以接受拖放操作时调用它。

重新实现此函数以启用对其他 MIME 类型的拖放支持。

### bool QTextEdit::canPaste() const

返回文本是否可以从剪贴板粘贴到文本编辑中。

### `[override virtual protected]`void QTextEdit::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QFrame::changeEvent](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *ev）。

### `[slot]`void QTextEdit::clear()

删除文本编辑中的所有文本。

笔记：

- 撤消/重做历史记录也会被清除。
- [currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

**可以参阅**[cut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)(),[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)（）， 和[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)()。

### `[override virtual protected]`void QTextEdit::contextMenuEvent([QContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qcontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)（QContextMenuEvent *e）。

显示使用创建的标准上下文菜单[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)()。

如果你不希望文本编辑有上下文菜单，你可以设置它[contextMenuPolicy](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuPolicy-prop)到[Qt::NoContextMenu](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ContextMenuPolicy-enum)。如果您想自定义上下文菜单，请重新实现此函数。如果要扩展标准上下文菜单，请重新实现此函数，调用[createStandardContextMenu](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createStandardContextMenu)() 并扩展返回的菜单。

有关事件的信息在*event*目的。

```
void MyTextEdit::contextMenuEvent(QContextMenuEvent *event)
{
    QMenu *menu = createStandardContextMenu();
    menu->addAction(tr("My Menu Item"));
    //...
    menu->exec(event->globalPos());
    delete menu;
}
```

### `[slot]`void QTextEdit::copy()

将任何选定的文本复制到剪贴板。

**可以参阅**[copyAvailable](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copyAvailable)()。

### `[signal]`void QTextEdit::copyAvailable(bool *yes*)

当在文本编辑中选择或取消选择文本时，会发出此信号。

当选择文本时，将发出此信号*yes*设置为 true。如果没有选择任何文本或者如果取消选择所选文本，则发出此信号*yes*设置为假。

如果*yes*那么是真的[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)() 可用于将所选内容复制到剪贴板。如果*yes*那么是假的[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)（） 什么也没做。

**可以参阅**[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)()。

### `[virtual protected]`[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextEdit::createMimeDataFromSelection() const

此函数返回一个新的 MIME 数据对象来表示文本编辑当前选择的内容。当需要将选择封装到新的中时调用它[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的; 例如，当开始拖放操作时，或者当数据复制到剪贴板时。

如果您重新实现此函数，请注意返回的所有权[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象被传递给调用者。可以使用以下命令检索选择[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)（） 功能。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextEdit::createStandardContextMenu()

此函数创建标准上下文菜单，当用户用鼠标右键单击文本编辑时显示该菜单。它是从默认调用的[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)() 处理程序。弹出菜单的所有权转移给调用者。

我们建议您使用 createStandardContextMenu([QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)) 版本，它将启用对用户单击位置敏感的操作。

### [QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextEdit::createStandardContextMenu(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*)

此函数创建标准上下文菜单，当用户用鼠标右键单击文本编辑时显示该菜单。它是从默认调用的[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)() 处理程序，它需要*position*在鼠标单击所在的文档坐标中。这可以启用对用户单击位置敏感的操作。弹出菜单的所有权转移给调用者。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::currentCharFormat() const

返回插入新文本时使用的字符格式。

**可以参阅**[setCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCharFormat)()。

### `[signal]`void QTextEdit::currentCharFormatChanged(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*f*)

如果当前字符格式已更改（例如由于光标位置的更改而引起），则会发出此信号。

新格式是*f*。

**可以参阅**[setCurrentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentCharFormat)()。

### [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::currentFont() const

返回当前格式的字体。

**可以参阅**[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)(),[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)（）， 和[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)()。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::cursorForPosition(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

返回一个[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在位置*pos*（在视口坐标中）。

### `[signal]`void QTextEdit::cursorPositionChanged()

每当光标位置改变时，就会发出该信号。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::cursorRect(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*) const

返回一个矩形（在视口坐标中），其中包括*cursor*。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::cursorRect() const

返回一个矩形（在视口坐标中），其中包含文本编辑的光标。

### `[slot]`void QTextEdit::cut()

将选定的文本复制到剪贴板并将其从文本编辑中删除。

如果没有选定的文本，则不会发生任何事情。

**可以参阅**[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)（） 和[paste](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paste)()。

### `[override virtual protected]`void QTextEdit::dragEnterEvent([QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（QDragEnterEvent *事件）。

### `[override virtual protected]`void QTextEdit::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

### `[override virtual protected]`void QTextEdit::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[override virtual protected]`void QTextEdit::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### void QTextEdit::ensureCursorVisible()

如有必要，通过滚动文本编辑确保光标可见。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextEdit::ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QTextEdit::extraSelections() const

返回先前设置的额外选择。

**可以参阅**[setExtraSelections](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setExtraSelections)()。

### bool QTextEdit::find(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*exp*, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = QTextDocument::FindFlags())

查找字符串的下一个出现位置，*exp*，使用给定的*options*。返回`true`如果*exp*找到并更改光标以选择匹配项；否则返回`false`.

### bool QTextEdit::find(const [QRegularExpression](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*exp*, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = QTextDocument::FindFlags())

这是一个过载功能。

查找与正则表达式匹配的下一个匹配项，*exp*，使用给定的*options*。这[QTextDocument::FindCaseSensitively](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum)对于此重载，选项被忽略，使用[QRegularExpression::CaseInsensitiveOption](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PatternOption-enum)反而。

如果找到匹配项则返回`true`并更改光标以选择匹配项；否则返回`false`.

### `[override virtual protected]`void QTextEdit::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[override virtual protected]`bool QTextEdit::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QTextEdit::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::fontFamily() const

返回当前格式的字体系列。

**可以参阅**[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)(),[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)（）， 和[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)()。

### bool QTextEdit::fontItalic() const

返回`true`当前格式的字体是否为斜体；否则返回 false。

**可以参阅**[setFontItalic](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontItalic)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QTextEdit::fontPointSize() const

返回当前格式字体的磅值。

**可以参阅**[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)(),[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)（）， 和[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)()。

### bool QTextEdit::fontUnderline() const

返回`true`当前格式的字体是否有下划线；否则返回 false。

**可以参阅**[setFontUnderline](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontUnderline)()。

### int QTextEdit::fontWeight() const

返回当前格式的字体粗细。

**可以参阅**[setFontWeight](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontWeight)(),[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)(),[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)（）， 和[QFont::Weight](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Weight-enum)。

### `[override virtual protected]`void QTextEdit::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)（QInputMethodEvent *事件）。

### `[override virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *property*) const

重新实现：[QWidget::inputMethodQuery(Qt::InputMethodQuery query) const](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)。

### `[virtual protected]`void QTextEdit::insertFromMimeData(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **source*)

该函数插入 MIME 数据对象的内容，由*source*，进入当前光标位置的文本编辑。每当由于剪贴板粘贴操作而插入文本时，或者当文本编辑接受来自拖放操作的数据时，都会调用它。

重新实现此函数以启用对其他 MIME 类型的拖放支持。

### `[slot]`void QTextEdit::insertHtml(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

方便插入的插槽*text*假定当前光标位置为 html 格式。

它相当于：

```
edit->textCursor().insertHtml(fragment);
```

**注意：**当将此功能与样式表一起使用时，样式表将仅应用于文档中的当前块。为了在整个文档中应用样式表，请使用[QTextDocument::setDefaultStyleSheet](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultStyleSheet-prop)（） 反而。

### `[slot]`void QTextEdit::insertPlainText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

方便插入的插槽*text*在当前光标位置。

它相当于

```
edit->textCursor().insertText(text);
```

### `[override virtual protected]`void QTextEdit::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

### `[override virtual protected]`void QTextEdit::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（QKeyEvent *事件）。

### `[virtual invokable]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::loadResource(int *type*, const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

加载给定指定的资源*type*和*name*。

这个函数是一个扩展[QTextDocument::loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**可以参阅**[QTextDocument::loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

### void QTextEdit::mergeCurrentCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*modifier*)

合并指定的属性*modifier*通过调用转换为当前字符格式[QTextCursor::mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)在编辑器的光标上。如果编辑器有一个选择，则属性*modifier*直接应用于选择。

**可以参阅**[QTextCursor::mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)()。

### `[override virtual protected]`void QTextEdit::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QTextEdit::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QTextEdit::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QTextEdit::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(QMouseEvent *e)。

### void QTextEdit::moveCursor([QTextCursor::MoveOperation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveOperation-enum) *operation*, [QTextCursor::MoveMode](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum) *mode* = QTextCursor::MoveAnchor)

通过执行给定的操作来移动光标*operation*。

如果*mode*是[QTextCursor::KeepAnchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum)，光标选择它移动到的文本。这与用户按住 Shift 键并使用光标键移动光标时获得的效果相同。

**可以参阅**[QTextCursor::movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)()。

### `[override virtual protected]`void QTextEdit::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

该事件处理程序可以在子类中重新实现以接收传入的绘制事件*event*。通常不需要在子类中重新实现这个函数[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**注意：**如果您创建[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，它必须运行在[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()。

**警告：**不得在此函数的重新实现中修改基础文本文档。

### `[slot]`void QTextEdit::paste()

将剪贴板中的文本粘贴到当前光标位置的文本编辑中。

如果剪贴板中没有文本，则不会发生任何事情。

改变这个函数的行为，即修改什么[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以粘贴以及如何粘贴，重新实现虚拟[canInsertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canInsertFromMimeData)（） 和[insertFromMimeData](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFromMimeData)（） 功能。

**可以参阅**[cut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)（） 和[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)()。

### void QTextEdit::print([QPagedPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpagedpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **printer*) const

将文本编辑的文档打印到给定的便捷功能*printer*。这相当于直接在文档上调用 print 方法，只不过该函数还支持 QPrinter::Selection 作为打印范围。

**可以参阅**[QTextDocument::print](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#print)()。

### `[slot]`void QTextEdit::redo()

重做上次操作。

如果没有要重做的操作，即撤消/重做历史记录中没有重做步骤，则不会发生任何情况。

**可以参阅**[undo](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo)()。

### `[signal]`void QTextEdit::redoAvailable(bool *available*)

每当重做操作可用时就会发出此信号（*available*为真）或不可用（*available*是假的）。

### `[override virtual protected]`void QTextEdit::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[override virtual protected]`void QTextEdit::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

### `[slot]`void QTextEdit::scrollToAnchor(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

滚动文本编辑，以便锚点具有给定的*name*是可见的；如果*name*为空，或已可见，或未找到。

### `[slot]`void QTextEdit::selectAll()

选择所有文本。

**可以参阅**[copy](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)(),[cut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cut)（）， 和[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)()。

### `[signal]`void QTextEdit::selectionChanged()

每当选择发生变化时就会发出此信号。

**可以参阅**[copyAvailable](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copyAvailable)()。

### `[slot]`void QTextEdit::setAlignment([Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *a*)

将当前段落的对齐方式设置为*a*。有效的对齐方式是[Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum),[Qt::AlignRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum),[Qt::AlignJustify](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)和[Qt::AlignCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)（水平居中）。

**可以参阅**[alignment](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)()。

### void QTextEdit::setCurrentCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置插入新文本时使用的字符格式*format*通过致电[QTextCursor::setCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCharFormat)() 位于编辑器的光标上。如果编辑器有一个选择，则字符格式将直接应用于该选择。

**可以参阅**[currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)()。

### `[slot]`void QTextEdit::setCurrentFont(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*f*)

将当前格式的字体设置为*f*。

**可以参阅**[currentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont)(),[setFontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontPointSize)（）， 和[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)()。

### void QTextEdit::setExtraSelections(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextEdit::ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*selections*)

此功能允许使用给定颜色临时标记文档中的某些区域，指定为*selections*。例如，这在编程编辑器中很有用，可以用给定的背景颜色标记整行文本以指示断点的存在。

**可以参阅**[QTextEdit::ExtraSelection](https://doc-qt-io.translate.goog/qt-6/qtextedit-extraselection.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[extraSelections](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#extraSelections)()。

### `[slot]`void QTextEdit::setFontFamily(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fontFamily*)

将当前格式的字体系列设置为*fontFamily*。

**可以参阅**[fontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFamily)（） 和[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)()。

### `[slot]`void QTextEdit::setFontItalic(bool *italic*)

如果*italic*为 true，将当前格式设置为斜体；否则将当前格式设置为非斜体。

**可以参阅**[fontItalic](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontItalic)()。

### `[slot]`void QTextEdit::setFontPointSize([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *s*)

将当前格式的磅值设置为*s*。

请注意，如果*s*为零或负数，则该函数的行为未定义。

**可以参阅**[fontPointSize](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontPointSize)(),[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)（）， 和[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)()。

### `[slot]`void QTextEdit::setFontUnderline(bool *underline*)

如果*underline*为 true，将当前格式设置为下划线；否则将当前格式设置为无下划线。

**可以参阅**[fontUnderline](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontUnderline)()。

### `[slot]`void QTextEdit::setFontWeight(int *weight*)

将当前格式的字体粗细设置为给定的*weight*，其中使用的值在由[QFont::Weight](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Weight-enum)枚举。

**可以参阅**[fontWeight](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontWeight)(),[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentFont)（）， 和[setFontFamily](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFontFamily)()。

### `[slot]`void QTextEdit::setPlainText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

将文本编辑的文本更改为字符串*text*。任何先前的文本都将被删除。

笔记：

- *text*被解释为纯文本。
- 撤消/重做历史记录也会被清除。
- [currentCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentCharFormat)() 被重置，除非[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)() 已位于文档的开头。

**注意：**属性的 Setter 函数[plainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)。

**可以参阅**[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)()。

### `[slot]`void QTextEdit::setText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

设置文本编辑的*text*。文本可以是纯文本或 HTML，文本编辑将尝试猜测正确的格式。

使用[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)（） 或者[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)() 直接避免文本编辑的猜测。

**可以参阅**[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)（） 和[toHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)()。

### `[slot]`void QTextEdit::setTextBackgroundColor(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*c*)

将当前格式的文本背景颜色设置为*c*。

**可以参阅**[textBackgroundColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textBackgroundColor)()。

### `[slot]`void QTextEdit::setTextColor(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*c*)

将当前格式的文本颜色设置为*c*。

**可以参阅**[textColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textColor)()。

### void QTextEdit::setTextCursor(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*)

设置可见*cursor*。

**可以参阅**[textCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textCursor)()。

### `[override virtual protected]`void QTextEdit::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::textBackgroundColor() const

返回当前格式的文本背景颜色。

**可以参阅**[setTextBackgroundColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextBackgroundColor)()。

### `[signal]`void QTextEdit::textChanged()

每当文档内容发生更改时都会发出此信号；例如，插入或删除文本时，或者应用格式时。

**注意：**属性的通知程序信号[html](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)。属性通知器信号[markdown](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markdown-prop)。

### [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::textColor() const

返回当前格式的文本颜色。

**可以参阅**[setTextColor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextColor)()。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::textCursor() const

返回一个副本[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代表当前可见的光标。请注意，返回游标的更改不会影响[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的光标；使用[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)() 更新可见光标。

**可以参阅**[setTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextCursor)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextEdit::toPlainText() const

[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)QTextEdit::toPlainText() const

以纯文本形式返回文本编辑的文本。

**注意：**属性的 getter 函数[plainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#plainText-prop)。

**可以参阅**[QTextEdit::setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)()。

### `[slot]`void QTextEdit::undo()

撤消上次操作。

如果没有要撤消的操作，即撤消/重做历史记录中没有撤消步骤，则不会发生任何情况。

**可以参阅**[redo](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo)()。

### `[signal]`void QTextEdit::undoAvailable(bool *available*)

每当撤消操作可用时就会发出此信号（*available*为真）或不可用（*available*是假的）。

### `[override virtual protected]`void QTextEdit::wheelEvent([QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)(QWheelEvent *e)。

### `[slot]`void QTextEdit::zoomIn(int *range* = 1)

通过设置基本字体大小来放大文本*range*点变大并重新计算所有字体大小以成为新大小。这不会改变任何图像的大小。

**可以参阅**[zoomOut](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomOut)()。

### `[slot]`void QTextEdit::zoomOut(int *range* = 1)

通过设置基本字体大小来缩小文本*range*点变小并重新计算所有字体大小以成为新大小。这不会改变任何图像的大小。

**可以参阅**[zoomIn](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zoomIn)()。