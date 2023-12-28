#  QTextCursor 

QTextCursor 类提供了一个 API 来访问和修改 QTextDocuments。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include < QTextCursor>                                      |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:  | QT += gui                                                    |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextcursor-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextCursor 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| enum | **[MoveMode](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum)** { MoveAnchor, KeepAnchor } |
| ---- | ------------------------------------------------------------ |
| enum | **[MoveOperation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveOperation-enum)** { NoMove, Start, StartOfLine, StartOfBlock, StartOfWord, …, PreviousRow } |
| enum | **[SelectionType](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionType-enum)** { Document, BlockUnderCursor, LineUnderCursor, WordUnderCursor } |

## 公共职能

|                       | **[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor)**() |
| --------------------- | ------------------------------------------------------------ |
|                       | **[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor-1)**(QTextDocument **document*) |
|                       | **[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor-2)**(QTextFrame **frame*) |
|                       | **[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor-3)**(const QTextBlock &*block*) |
|                       | **[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor-4)**(const QTextCursor &*cursor*) |
|                       | **[~QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTextCursor)**() |
| int                   | **[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)**() const |
| bool                  | **[atBlockEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockEnd)**() const |
| bool                  | **[atBlockStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockStart)**() const |
| bool                  | **[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)**() const |
| bool                  | **[atStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atStart)**() const |
| void                  | **[beginEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginEditBlock)**() |
| QTextBlock            | **[block](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#block)**() const |
| QTextCharFormat       | **[blockCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCharFormat)**() const |
| QTextBlockFormat      | **[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)**() const |
| int                   | **[blockNumber](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockNumber)**() const |
| QTextCharFormat       | **[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)**() const |
| void                  | **[clearSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)**() |
| int                   | **[columnNumber](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#columnNumber)**() const |
| QTextList *           | **[createList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createList)**(const QTextListFormat &*format*) |
| QTextList *           | **[createList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createList-1)**(QTextListFormat::Style *style*) |
| QTextFrame *          | **[currentFrame](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFrame)**() const |
| QTextList *           | **[currentList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentList)**() const |
| QTextTable *          | **[currentTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentTable)**() const |
| void                  | **[deleteChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deleteChar)**() |
| void                  | **[deletePreviousChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deletePreviousChar)**() |
| QTextDocument *       | **[document](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)**() const |
| void                  | **[endEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endEditBlock)**() |
| bool                  | **[hasComplexSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasComplexSelection)**() const |
| bool                  | **[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)**() const |
| void                  | **[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock)**() |
| void                  | **[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock-1)**(const QTextBlockFormat &*format*) |
| void                  | **[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock-2)**(const QTextBlockFormat &*format*, const QTextCharFormat &*charFormat*) |
| void                  | **[insertFragment](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFragment)**(const QTextDocumentFragment &*fragment*) |
| QTextFrame *          | **[insertFrame](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFrame)**(const QTextFrameFormat &*format*) |
| void                  | **[insertHtml](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertHtml)**(const QString &*html*) |
| void                  | **[insertImage](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertImage)**(const QTextImageFormat &*format*) |
| void                  | **[insertImage](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertImage-1)**(const QTextImageFormat &*format*, QTextFrameFormat::Position *alignment*) |
| void                  | **[insertImage](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertImage-2)**(const QString &*name*) |
| void                  | **[insertImage](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertImage-3)**(const QImage &*image*, const QString &*name* = QString()) |
| QTextList *           | **[insertList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertList)**(const QTextListFormat &*format*) |
| QTextList *           | **[insertList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertList-1)**(QTextListFormat::Style *style*) |
| void                  | **[insertMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertMarkdown)**(const QString &*markdown*, QTextDocument::MarkdownFeatures *features* = QTextDocument::MarkdownDialectGitHub) |
| QTextTable *          | **[insertTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertTable)**(int *rows*, int *columns*, const QTextTableFormat &*format*) |
| QTextTable *          | **[insertTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertTable-1)**(int *rows*, int *columns*) |
| void                  | **[insertText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertText)**(const QString &*text*) |
| void                  | **[insertText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertText-1)**(const QString &*text*, const QTextCharFormat &*format*) |
| bool                  | **[isCopyOf](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isCopyOf)**(const QTextCursor &*other*) const |
| bool                  | **[isNull](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isNull)**() const |
| void                  | **[joinPreviousEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#joinPreviousEditBlock)**() |
| bool                  | **[keepPositionOnInsert](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keepPositionOnInsert)**() const |
| void                  | **[mergeBlockCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeBlockCharFormat)**(const QTextCharFormat &*modifier*) |
| void                  | **[mergeBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeBlockFormat)**(const QTextBlockFormat &*modifier*) |
| void                  | **[mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)**(const QTextCharFormat &*modifier*) |
| bool                  | **[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)**(QTextCursor::MoveOperation *operation*, QTextCursor::MoveMode *mode* = MoveAnchor, int *n* = 1) |
| int                   | **[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)**() const |
| int                   | **[positionInBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#positionInBlock)**() const |
| void                  | **[removeSelectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSelectedText)**() |
| void                  | **[select](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#select)**(QTextCursor::SelectionType *selection*) |
| void                  | **[selectedTableCells](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedTableCells)**(int **firstRow*, int **numRows*, int **firstColumn*, int **numColumns*) const |
| QString               | **[selectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText)**() const |
| QTextDocumentFragment | **[selection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selection)**() const |
| int                   | **[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)**() const |
| int                   | **[selectionStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)**() const |
| void                  | **[setBlockCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockCharFormat)**(const QTextCharFormat &*format*) |
| void                  | **[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)**(const QTextBlockFormat &*format*) |
| void                  | **[setCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCharFormat)**(const QTextCharFormat &*format*) |
| void                  | **[setKeepPositionOnInsert](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setKeepPositionOnInsert)**(bool *b*) |
| void                  | **[setPosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPosition)**(int *pos*, QTextCursor::MoveMode *m* = MoveAnchor) |
| void                  | **[setVerticalMovementX](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalMovementX)**(int *x*) |
| void                  | **[setVisualNavigation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisualNavigation)**(bool *b*) |
| void                  | **[swap](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QTextCursor &*other*) |
| int                   | **[verticalMovementX](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalMovementX)**() const |
| bool                  | **[visualNavigation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualNavigation)**() const |
| bool                  | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QTextCursor &*other*) const |
| bool                  | **[operator<](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt)**(const QTextCursor &*other*) const |
| bool                  | **[operator<=](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-eq)**(const QTextCursor &*other*) const |
| QTextCursor &         | **[operator=](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(const QTextCursor &*cursor*) |
| bool                  | **[operator==](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QTextCursor &*other*) const |
| bool                  | **[operator>](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt)**(const QTextCursor &*other*) const |
| bool                  | **[operator>=](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-eq)**(const QTextCursor &*other*) const |

## 详细说明

文本光标是用于通过模拟文本编辑器中光标行为的编程接口来访问和修改文本文档的内容和底层结构的对象。QTextCursor 包含有关光标在文本中的位置的信息[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)以及它所做的任何选择。

QTextCursor 模仿文本光标在文本编辑器中的行为方式，提供通过用户界面执行标准操作的编程方法。文档可以被视为单个字符串。光标当前[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() then 总是位于字符串中的两个连续字符*之间*，或者位于字符串中的第一个字符*之前*或最后一个字符*之后。*除了文本之外，文档还可以包含表格、列表、图像和其他对象，但从开发人员的角度来看，文档可以被视为一个长字符串。该字符串的某些部分可以被认为位于特定的块（例如段落）内，或在表格的单元格内，或在列表的项目内，或在其他结构元素内。当我们提到“当前字符”时，我们指的是光标*之前的字符*[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)文档中的 ()。同样，“当前块”就是包含光标的块[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

QTextCursor 还有一个[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)（） 位置。之间的文字[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)() 和[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 为选择。如果[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)()==[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 没有选择。

可以使用以下命令以编程方式更改光标位置[setPosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPosition)（） 和[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)(); 后者也可用于选择文本。有关选择，请参见[selectionStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)(),[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)(),[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)(),[clearSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)（）， 和[removeSelectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSelectedText)()。

如果[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 位于块的开头，[atBlockStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockStart)() 返回`true`；如果它位于块的末尾，[atBlockEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockEnd)() 返回 true。当前字符的格式由以下命令返回[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)()，当前块的格式由[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

可以使用以下命令将格式应用于当前文本文档[setCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCharFormat)(),[mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)(),[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)（） 和[mergeBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeBlockFormat)（） 功能。“set”函数将替换光标当前的字符或块格式，而“merge”函数将给定的格式属性添加到光标的当前格式中。如果光标有选择，则给定格式将应用于当前选择。请注意，当仅选择块的一部分时，块格式将应用于整个块。当前字符位置的文本可以使用以下命令转换为列表[createList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createList)()。

删除可以通过使用来实现[deleteChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deleteChar)(),[deletePreviousChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deletePreviousChar)（）， 和[removeSelectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSelectedText)()。

可以使用以下命令将文本字符串插入到文档中[insertText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertText)() 函数，块（代表新段落）可以插入[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock)()。

现有的文本片段可以插入[insertFragment](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFragment)() 但是，如果您想插入各种格式的文本片段，通常仍然更容易使用[insertText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertText)() 并提供字符格式。

还可以使用光标将各种类型的高级结构插入到文档中：

- 列表是用项目符号或符号装饰的块元素的有序序列。它们以指定的格式插入[insertList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertList)()。
- 表格插入[insertTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertTable)() 函数，并且可以给出可选的格式。它们包含可以使用光标遍历的单元格数组。
- 内嵌图像插入[insertImage](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertImage)()。要使用的图像可以以图像格式或名称指定。
- 通过调用插入帧[insertFrame](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFrame)() 具有指定的格式。

可以使用以下方法对操作进行分组（即，将其视为撤消/重做的单个操作）[beginEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginEditBlock)（） 和[endEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endEditBlock)()。

光标移动仅限于有效的光标位置。在拉丁文字中，它位于文本中任意两个连续字符之间、第一个字符之前或最后一个字符之后。在一些其他书写系统中，光标移动仅限于“簇”（例如梵文中的音节，或基本字母加变音符号）。功能如[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)（） 和[deleteChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deleteChar)() 限制光标移动到这些有效位置。

**也可以看看**[Rich Text Processing](https://doc-qt-io.translate.goog/qt-6/richtext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QTextCursor::MoveMode

| 持续的                    | 价值 | 描述                               |
| ------------------------- | ---- | ---------------------------------- |
| `QTextCursor::MoveAnchor` | `0`  | 将锚点移动到与光标本身相同的位置。 |
| `QTextCursor::KeepAnchor` | `1`  | 将锚保持在原来的位置。             |

如果[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)() 保留在原处，并且[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 被移动，中间的文本将被选中。

### enum QTextCursor::MoveOperation

| 持续的                           | 价值 | 描述                                                         |
| -------------------------------- | ---- | ------------------------------------------------------------ |
| `QTextCursor::NoMove`            | `0`  | 将光标保持在原来的位置                                       |
| `QTextCursor::Start`             | `1`  | 移至文档的开头。                                             |
| `QTextCursor::StartOfLine`       | `3`  | 移至当前行的开头。                                           |
| `QTextCursor::StartOfBlock`      | `4`  | 移至当前块的开头。                                           |
| `QTextCursor::StartOfWord`       | `5`  | 移至当前单词的开头。                                         |
| `QTextCursor::PreviousBlock`     | `6`  | 移至上一个块的开头。                                         |
| `QTextCursor::PreviousCharacter` | `7`  | 移至上一个字符。                                             |
| `QTextCursor::PreviousWord`      | `8`  | 移至上一个单词的开头。                                       |
| `QTextCursor::Up`                | `2`  | 上移一行。                                                   |
| `QTextCursor::Left`              | `9`  | 向左移动一个字符。                                           |
| `QTextCursor::WordLeft`          | `10` | 左移一个字。                                                 |
| `QTextCursor::End`               | `11` | 移至文档末尾。                                               |
| `QTextCursor::EndOfLine`         | `13` | 移动到当前行的末尾。                                         |
| `QTextCursor::EndOfWord`         | `14` | 移至当前单词的末尾。                                         |
| `QTextCursor::EndOfBlock`        | `15` | 移至当前块的末尾。                                           |
| `QTextCursor::NextBlock`         | `16` | 移至下一个块的开头。                                         |
| `QTextCursor::NextCharacter`     | `17` | 移至下一个字符。                                             |
| `QTextCursor::NextWord`          | `18` | 移至下一个单词。                                             |
| `QTextCursor::Down`              | `12` | 向下移动一行。                                               |
| `QTextCursor::Right`             | `19` | 右移一个字符。                                               |
| `QTextCursor::WordRight`         | `20` | 右移一个字。                                                 |
| `QTextCursor::NextCell`          | `21` | 移至当前表格内下一个表格单元格的开头。如果当前单元格是该行的最后一个单元格，则光标将移动到下一行的第一个单元格。 |
| `QTextCursor::PreviousCell`      | `22` | 移至当前表格内上一个表格单元格的开头。如果当前单元格是该行的第一个单元格，则光标将移动到上一行的最后一个单元格。 |
| `QTextCursor::NextRow`           | `23` | 移至当前表中下一行的第一个新单元格。                         |
| `QTextCursor::PreviousRow`       | `24` | 移至当前表格中上一行的最后一个单元格。                       |

**也可以看看**[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)()。

### enum QTextCursor::SelectionType

该枚举描述了可以应用的选择类型[select](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#select)（） 功能。

| 持续的                          | 价值 | 描述                                                         |
| ------------------------------- | ---- | ------------------------------------------------------------ |
| `QTextCursor::Document`         | `3`  | 选择整个文档。                                               |
| `QTextCursor::BlockUnderCursor` | `2`  | 选择光标下的文本块。                                         |
| `QTextCursor::LineUnderCursor`  | `1`  | 选择光标下的文本行。                                         |
| `QTextCursor::WordUnderCursor`  | `0`  | 选择光标下的单词。如果光标未位于可选择字符的字符串内，则不会选择任何文本。 |

## 成员函数文档

### QTextCursor::QTextCursor()

构造一个空游标。

### `[explicit]`QTextCursor::QTextCursor([QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **document*)

构造一个指向开头的光标*document*。

### `[explicit]`QTextCursor::QTextCursor([QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **frame*)

构造一个指向开头的光标*frame*。

### `[explicit]`QTextCursor::QTextCursor(const [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*block*)

构造一个指向开头的光标*block*。

### QTextCursor::QTextCursor(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*cursor*)

构造一个新游标，它是*cursor*。

### `[noexcept]`QTextCursor::~QTextCursor()

摧毁了[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### int QTextCursor::anchor() const

返回锚点位置；这与[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 除非有选择，在这种情况下[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 标记选择的一端，anchor() 标记另一端。就像光标位置一样，锚点位置位于字符之间。

**也可以看看**[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)(),[setPosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPosition)(),[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)(),[selectionStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)（）， 和[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)()。

### bool QTextCursor::atBlockEnd() const

`true`如果光标位于块的末尾则返回；否则返回`false`.

**也可以看看**[atBlockStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockStart)（） 和[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)()。

### bool QTextCursor::atBlockStart() const

`true`如果光标位于块的开头则返回；否则返回`false`.

**也可以看看**[atBlockEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockEnd)（） 和[atStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atStart)()。

### bool QTextCursor::atEnd() const

`true`如果光标位于文档末尾则返回；否则返回`false`.

**也可以看看**[atStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atStart)（） 和[atBlockEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockEnd)()。

### bool QTextCursor::atStart() const

`true`如果光标位于文档的开头则返回；否则返回`false`.

**也可以看看**[atBlockStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atBlockStart)（） 和[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)()。

### void QTextCursor::beginEditBlock()

指示文档上的一组编辑操作的开始，从撤消/重做的角度来看，该操作应显示为单个操作。

例如：

```
QTextCursor cursor(textDocument);
cursor.beginEditBlock();
cursor.insertText("Hello");
cursor.insertText("World");
cursor.endEditBlock();

textDocument->undo();
```

对 undo() 的调用将导致两次插入都被撤消，从而导致“World”和“Hello”都被删除。

可以嵌套调用 beginEditBlock 和[endEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endEditBlock)。最上面的一对将确定撤消/重做操作的范围。

**也可以看看**[endEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endEditBlock)()。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextCursor::block() const

返回包含光标的块。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextCursor::blockCharFormat() const

返回光标所在块的块字符格式。

块字符格式是在空块的开头插入文本时使用的格式。

**也可以看看**[setBlockCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockCharFormat)()。

### [QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextCursor::blockFormat() const

返回光标所在块的块格式。

**也可以看看**[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)（） 和[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)()。

### int QTextCursor::blockNumber() const

返回光标所在块的编号，如果光标无效则返回 0。

请注意，此功能仅在没有复杂对象（例如表格或框架）的文档中才有意义。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextCursor::charFormat() const

返回光标前字符的格式[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。如果光标位于非空文本块的开头，则返回紧随光标之后的字符的格式。

**也可以看看**[setCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCharFormat)(),[insertText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertText)（）， 和[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### void QTextCursor::clearSelection()

通过将锚点设置到光标位置来清除当前选择。

请注意，它不会**删除**所选内容的文本。

**也可以看看**[removeSelectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSelectedText)（） 和[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)()。

### int QTextCursor::columnNumber() const

返回光标在其包含行中的位置。

请注意，这是相对于换行的列号，而不是相对于块（即段落）的列号。

您可能想打电话[positionInBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#positionInBlock)（） 反而。

**也可以看看**[positionInBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#positionInBlock)()。

### [QTextList](https://doc-qt-io.translate.goog/qt-6/qtextlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::createList(const [QTextListFormat](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

创建并返回具有给定值的新列表*format*，并使当前段落的光标位于第一个列表项中。

**也可以看看**[insertList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertList)（） 和[currentList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentList)()。

### [QTextList](https://doc-qt-io.translate.goog/qt-6/qtextlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::createList([QTextListFormat::Style](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Style-enum) *style*)

这是一个过载功能。

创建并返回具有给定值的新列表*style*，使光标的当前段落成为第一个列表项。

要使用的样式由[QTextListFormat::Style](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Style-enum)枚举。

**也可以看看**[insertList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertList)（） 和[currentList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentList)()。

### [QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::currentFrame() const

返回指向当前帧的指针。`nullptr`如果光标无效则返回。

**也可以看看**[insertFrame](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFrame)()。

### [QTextList](https://doc-qt-io.translate.goog/qt-6/qtextlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::currentList() const

如果光标位于则返回当前列表[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 位于属于列表一部分的块内；否则返回`nullptr`.

**也可以看看**[insertList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertList)（） 和[createList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createList)()。

### [QTextTable](https://doc-qt-io.translate.goog/qt-6/qtexttable.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::currentTable() const

如果光标位于当前表，则返回指向当前表的指针[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 位于属于表一部分的块内；否则返回`nullptr`.

**也可以看看**[insertTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertTable)()。

### void QTextCursor::deleteChar()

如果没有选中的文本，则删除当前光标位置的*字符；*否则删除选定的文本。

**也可以看看**[deletePreviousChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deletePreviousChar)(),[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)（）， 和[clearSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)()。

### void QTextCursor::deletePreviousChar()

如果没有选中的文本，则删除当前光标位置*之前的字符；*否则删除选定的文本。

**也可以看看**[deleteChar](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deleteChar)(),[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)（）， 和[clearSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)()。

### [QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::document() const

返回与该光标关联的文档。

### void QTextCursor::endEditBlock()

指示文档上的一组编辑操作的结束，从撤消/重做的角度来看，该操作应显示为单个操作。

**也可以看看**[beginEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginEditBlock)()。

### bool QTextCursor::hasComplexSelection() const

`true`如果光标包含的选择不仅仅是一个范围，则返回[selectionStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)（） 到[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)(); 否则返回`false`.

复杂选择是指跨越表格中至少两个单元格的选择；它们的范围由下式指定[selectedTableCells](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedTableCells)()。

### bool QTextCursor::hasSelection() const

`true`如果光标包含选择则返回；否则返回`false`.

### void QTextCursor::insertBlock()

在光标处插入一个新的空块[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 与当前[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)（） 和[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)()。

**也可以看看**[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)()。

### void QTextCursor::insertBlock(const [QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

这是一个过载功能。

在光标处插入一个新的空块[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 带块格式*format*和当前的[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)() 作为块字符格式。

**也可以看看**[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)()。

### void QTextCursor::insertBlock(const [QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*, const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*charFormat*)

这是一个过载功能。

在光标处插入一个新的空块[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 带块格式*format*和*charFormat*作为块字符格式。

**也可以看看**[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)()。

### void QTextCursor::insertFragment(const [QTextDocumentFragment](https://doc-qt-io.translate.goog/qt-6/qtextdocumentfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fragment*)

插入文本*fragment*目前[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

### [QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::insertFrame(const [QTextFrameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframeformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

插入一个具有给定的框架*format*在当前光标处[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()，移动光标[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 在框架内，并返回框架。

如果光标保留了一个选择，则整个选择将移动到框架内。

**也可以看看**[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)()。

### void QTextCursor::insertHtml(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*html*)

插入文本*html*目前[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。文本被解释为 HTML。

**注意：**当将此功能与样式表一起使用时，样式表将仅应用于文档中的当前块。为了在整个文档中应用样式表，请使用[QTextDocument::setDefaultStyleSheet](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultStyleSheet-prop)（） 反而。

### void QTextCursor::insertImage(const [QTextImageFormat](https://doc-qt-io.translate.goog/qt-6/qtextimageformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

插入由以下定义的图像*format*目前[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

### void QTextCursor::insertImage(const [QTextImageFormat](https://doc-qt-io.translate.goog/qt-6/qtextimageformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*, [QTextFrameFormat::Position](https://doc-qt-io.translate.goog/qt-6/qtextframeformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Position-enum) *alignment*)

这是一个过载功能。

插入由给定定义的图像*format*在光标当前位置指定*alignment*。

**也可以看看**[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

### void QTextCursor::insertImage(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

这是一个过载功能。

使用给定插入图像的便捷方法*name*目前[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

```
QImage img;
textDocument->addResource(QTextDocument::ImageResource, QUrl("myimage"), img);
cursor.insertImage("myimage");
```

### void QTextCursor::insertImage(const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name* = QString())

这是一个过载功能。

用于插入给定的便捷功能*image*带有可选的*name*目前[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

### [QTextList](https://doc-qt-io.translate.goog/qt-6/qtextlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::insertList(const [QTextListFormat](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

在当前位置插入一个新块，并使其成为具有给定值的新创建列表的第一个列表项*format*。返回创建的列表。

**也可以看看**[currentList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentList)(),[createList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createList)（）， 和[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock)()。

### [QTextList](https://doc-qt-io.translate.goog/qt-6/qtextlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::insertList([QTextListFormat::Style](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Style-enum) *style*)

这是一个过载功能。

在当前位置插入一个新块，并使其成为具有给定值的新创建列表的第一个列表项*style*。返回创建的列表。

**也可以看看**[currentList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentList)(),[createList](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createList)（）， 和[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock)()。

### `[since 6.4]`void QTextCursor::insertMarkdown(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*markdown*, [QTextDocument::MarkdownFeatures](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MarkdownFeature-enum) *features* = QTextDocument::MarkdownDialectGitHub)

插入*markdown*当前文本[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()，带有指定的 Markdown*features*。默认是 GitHub 方言。

该功能是在 Qt 6.4 中引入的。

### [QTextTable](https://doc-qt-io.translate.goog/qt-6/qtexttable.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::insertTable(int *rows*, int *columns*, const [QTextTableFormat](https://doc-qt-io.translate.goog/qt-6/qtexttableformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

创建一个具有给定数量的新表*rows*和*columns*在指定的*format*，将其插入到当前光标处[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 在文档中，并返回表对象。光标移动到第一个单元格的开头。

表中必须至少有一行和一列。

**也可以看看**[currentTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentTable)()。

### [QTextTable](https://doc-qt-io.translate.goog/qt-6/qtexttable.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextCursor::insertTable(int *rows*, int *columns*)

这是一个过载功能。

创建一个具有给定数量的新表*rows*和*columns*，将其插入到当前光标处[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 在文档中，并返回表对象。光标移动到第一个单元格的开头。

表中必须至少有一行和一列。

**也可以看看**[currentTable](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentTable)()。

### void QTextCursor::insertText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

刀片*text*在当前位置，使用当前字符格式。

如果有选择，则该选择将被删除并替换为*text*， 例如：

```
cursor.clearSelection();
cursor.movePosition(QTextCursor::NextWord, QTextCursor::KeepAnchor);
cursor.insertText("Hello World");
```

这将清除任何现有的选择，选择光标处的单词（即来自[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 转发），并将所选内容替换为短语“Hello World”。

插入文本中的任何 ASCII 换行符 (\n) 都会转换为 unicode 块分隔符，对应于[insertBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertBlock)() 调用。

**也可以看看**[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)（） 和[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)()。

### void QTextCursor::insertText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

这是一个过载功能。

刀片*text*在给定的当前位置*format*。

### bool QTextCursor::isCopyOf(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

如果此光标`true`和*other*是彼此的副本，即其中一个是作为另一个的副本创建的，并且从那以后都没有移动过。这比平等严格得多。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)（） 和[operator==](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### bool QTextCursor::isNull() const

`true`如果光标为空则返回；否则返回`false`. 空游标由默认构造函数创建。

### void QTextCursor::joinPreviousEditBlock()

喜欢[beginEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginEditBlock)() 表示编辑操作块的开始，该操作块应显示为撤消/重做的单个操作。然而不像[beginEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginEditBlock)() 它不会启动一个新块，而是反转之前的调用[endEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endEditBlock)() ，因此使以下操作成为先前创建的编辑块的一部分。

例如：

```
QTextCursor cursor(textDocument);
cursor.beginEditBlock();
cursor.insertText("Hello");
cursor.insertText("World");
cursor.endEditBlock();

// ...

cursor.joinPreviousEditBlock();
cursor.insertText("Hey");
cursor.endEditBlock();

textDocument->undo();
```

对 undo() 的调用将导致所有三个插入被撤消。

**也可以看看**[beginEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginEditBlock)（） 和[endEditBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endEditBlock)()。

### bool QTextCursor::keepPositionOnInsert() const

返回在光标位置插入文本时光标是否应保持其当前位置。

默认为 false；

**也可以看看**[setKeepPositionOnInsert](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setKeepPositionOnInsert)()。

### void QTextCursor::mergeBlockCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*modifier*)

使用指定的块格式修改当前块（或选择中包含的所有块）的块字符格式*modifier*。

**也可以看看**[setBlockCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockCharFormat)()。

### void QTextCursor::mergeBlockFormat(const [QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*modifier*)

使用指定的块格式修改当前块（或选择中包含的所有块）的块格式*modifier*。

**也可以看看**[setBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBlockFormat)（） 和[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### void QTextCursor::mergeCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*modifier*)

将光标当前的字符格式与 format 描述的属性合并*modifier*。如果光标有选择，此功能将应用在中设置的所有属性*modifier*属于选择范围的所有字符格式。

**也可以看看**[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)（） 和[setCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCharFormat)()。

### bool QTextCursor::movePosition([QTextCursor::MoveOperation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveOperation-enum) *operation*, [QTextCursor::MoveMode](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum) *mode* = MoveAnchor, int *n* = 1)

通过执行给定的操作来移动光标*operation* *n*次，使用指定的*mode*`true`，如果所有操作均成功完成则返回；否则返回`false`.

例如，如果重复使用此函数来查找下一个单词的末尾，则当到达文档末尾时，它最终会失败。

默认情况下，移动操作执行一次（*n*= 1).

如果*mode*是`KeepAnchor`，光标选择它移动到的文本。这与用户按住 Shift 键并使用光标键移动光标时获得的效果相同。

**也可以看看**[setVisualNavigation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisualNavigation)()。

### int QTextCursor::position() const

返回光标在文档中的绝对位置。光标位于字符之间。

**注：**这里的“字符”指的是字符串[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，即 16 位 Unicode 字符，并且该位置被视为该字符串的索引。这不一定对应于书写系统中的单个字素，因为单个字素可以由多个 Unicode 字符表示，例如在代理对、语言连字或变音符号的情况下。

**也可以看看**[setPosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPosition)(),[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)(),[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)（）， 和[positionInBlock](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#positionInBlock)()。

### int QTextCursor::positionInBlock() const

返回光标在块内的相对位置。光标位于字符之间。

这相当于`position() - block().position()`.

**注：**这里的“字符”指的是字符串[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，即 16 位 Unicode 字符，并且该位置被视为该字符串的索引。这不一定对应于书写系统中的单个字素，因为单个字素可以由多个 Unicode 字符表示，例如在代理对、语言连字或变音符号的情况下。

**也可以看看**[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)()。

### void QTextCursor::removeSelectedText()

如果有选择，则删除其内容；否则什么也不做。

**也可以看看**[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)()。

### void QTextCursor::select([QTextCursor::SelectionType](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionType-enum) *selection*)

根据给定选择文档中的文本*selection*。

### void QTextCursor::selectedTableCells(int **firstRow*, int **numRows*, int **firstColumn*, int **numColumns*) const

如果选择跨越表格单元格，*firstRow*填充选择中第一行的编号，*firstColumn*与选择中第一列的编号，以及*numRows*和*numColumns*以及选择中的行数和列数。如果选择不跨越任何表格单元格，则结果是无害的，但未定义。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextCursor::selectedText() const

返回当前选择的文本（可能为空）。这仅返回文本，没有富文本格式信息。如果您想要文档片段（即格式化的富文本），请使用[selection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selection)（） 反而。

**注意：**如果从编辑器获得的选择跨越换行符，则文本将包含 Unicode U+2029 段落分隔符而不是换行符`\n`。使用[QString::replace](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#replace)() 用换行符替换这些字符。

### [QTextDocumentFragment](https://doc-qt-io.translate.goog/qt-6/qtextdocumentfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextCursor::selection() const

返回当前选择（可能为空）及其所有格式信息。如果您只想要选定的文本（即纯文本），请使用[selectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText)（） 反而。

**注：**不同于[QTextDocumentFragment::toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocumentfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)(),[selectedText](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedText)() 可能包含特殊的 unicode 字符，例如[QChar::ParagraphSeparator](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SpecialCharacter-enum)。

**也可以看看**[QTextDocumentFragment::toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocumentfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)()。

### int QTextCursor::selectionEnd() const

返回选择的结尾或[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 如果光标没有选择。

**也可以看看**[selectionStart](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionStart)(),[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)（）， 和[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)()。

### int QTextCursor::selectionStart() const

返回选择的开始或[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)() 如果光标没有选择。

**也可以看看**[selectionEnd](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionEnd)(),[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)（）， 和[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)()。

### void QTextCursor::setBlockCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

将当前块（或选择中包含的所有块）的块字符格式设置为*format*。

**也可以看看**[blockCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCharFormat)()。

### void QTextCursor::setBlockFormat(const [QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

将当前块（或选择中包含的所有块）的块格式设置为*format*。

**也可以看看**[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)（） 和[mergeBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeBlockFormat)()。

### void QTextCursor::setCharFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

将光标的当前字符格式设置为给定的*format*。如果光标有选择，则给定*format*应用于当前选择。

**也可以看看**[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)(),[hasSelection](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasSelection)（）， 和[mergeCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mergeCharFormat)()。

### void QTextCursor::setKeepPositionOnInsert(bool *b*)

定义在光标当前位置插入文本时光标是否应保持其当前位置。

如果*b*为 true 时，当在光标所在位置插入文本时，光标将保持其当前位置。如果*b*为 false 时，光标将随着插入的文本一起移动。

默认为 false。

请注意，当在光标当前位置之前插入文本时，光标始终会移动；而当在光标当前位置之后插入文本时，光标始终保持其位置。

**也可以看看**[keepPositionOnInsert](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keepPositionOnInsert)()。

### void QTextCursor::setPosition(int *pos*, [QTextCursor::MoveMode](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MoveMode-enum) *m* = MoveAnchor)

将光标移动到文档中指定的绝对位置*pos*使用`MoveMode`指定的*m*。光标位于字符之间。

**注：**这里的“字符”指的是字符串[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，即 16 位 Unicode 字符，以及*pos*被视为该字符串的索引。这不一定对应于书写系统中的单个字素，因为单个字素可以由多个 Unicode 字符表示，例如在代理对、语言连字或变音符号的情况下。如需更通用的文档导航方法，请使用[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)()，它将尊重文本中的实际字素边界。

**也可以看看**[position](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)(),[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)（）， 和[anchor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchor)()。

### void QTextCursor::setVerticalMovementX(int *x*)

将垂直光标移动的视觉 x 位置设置为*x*。

当光标水平移动时，垂直移动x位置自动清除，当光标垂直移动时，垂直移动x位置保持不变。该机制允许光标在具有比例字体的视觉直线上上下移动，并在短线上轻轻地“跳跃”。

值 -1 表示没有预定义的 x 位置。下次光标向上或向下移动时，它将自动设置。

**也可以看看**[verticalMovementX](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalMovementX)()。

### void QTextCursor::setVisualNavigation(bool *b*)

将视觉导航设置为*b*。

视觉导航意味着跳过隐藏的文本段落。默认为 false。

**也可以看看**[visualNavigation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualNavigation)（） 和[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)()。

### `[noexcept]`void QTextCursor::swap([QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*)

将此文本光标实例与*other*。这个功能非常快并且永远不会失败。

### int QTextCursor::verticalMovementX() const

返回垂直光标移动的视觉 x 位置。

值 -1 表示没有预定义的 x 位置。下次光标向上或向下移动时，它将自动设置。

**也可以看看**[setVerticalMovementX](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerticalMovementX)()。

### bool QTextCursor::visualNavigation() const

`true`如果光标进行视觉导航则返回；否则返回`false`.

视觉导航意味着跳过隐藏的文本段落。默认为 false。

**也可以看看**[setVisualNavigation](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisualNavigation)（） 和[movePosition](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movePosition)()。

### bool QTextCursor::operator!=(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

返回`true`如果*other*光标在文档中与此光标位于不同的位置；否则返回`false`.

### bool QTextCursor::operator<(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

返回`true`如果*other*光标在文档中的位置比该光标靠后；否则返回`false`.

### bool QTextCursor::operator<=(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

返回`true`如果*other*光标位于文档中与该光标稍后或相同的位置；否则返回 false。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &QTextCursor::operator=(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*cursor*)

复制一份*cursor*并将其分配给此[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。注意[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)是一个[implicitly shared](https://doc-qt-io.translate.goog/qt-6/implicit-sharing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#implicitly-shared-classes)班级。

### bool QTextCursor::operator==(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

返回`true`如果*other*光标在文档中与此光标处于同一位置；否则返回`false`.

### bool QTextCursor::operator>(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

返回`true`如果*other*光标在文档中的位置比该光标更早；否则返回`false`.

### bool QTextCursor::operator>=(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextCursor) &*other*) const

返回`true`如果*other*光标位于文档中较早的位置或与该光标相同的位置；否则返回 false。

