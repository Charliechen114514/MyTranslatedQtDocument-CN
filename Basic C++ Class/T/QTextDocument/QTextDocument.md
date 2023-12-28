#  QTextDocument Class

QTextDocument 类保存格式化文本。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QTextDocument>                                     |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:    | QT += gui                                                    |
| Inherits: | [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextdocument-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextDocument 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| enum  | **[FindFlag](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum)** { FindBackward, FindCaseSensitively, FindWholeWords } |
| ----- | ------------------------------------------------------------ |
| flags | **[FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum)** |
| flags | **[MarkdownFeatures](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MarkdownFeature-enum)** |
| enum  | **[MetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MetaInformation-enum)** { DocumentTitle, DocumentUrl, CssMedia } |
|       | **[ResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceProvider-typedef)** |
| enum  | **[ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)** { UnknownResource, HtmlResource, ImageResource, StyleSheetResource, MarkdownResource, UserResource } |
| enum  | **[Stacks](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Stacks-enum)** { UndoStack, RedoStack, UndoAndRedoStacks } |

## 特性

| **[baseUrl](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseUrl-prop)** : QUrl**[blockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCount-prop)** : const int**[defaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultFont-prop)** : QFont**[defaultStyleSheet](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultStyleSheet-prop)** : QString**[defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption-prop)** : QTextOption**[documentMargin](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMargin-prop)** : qreal**[indentWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentWidth-prop)** : qreal**[layoutEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutEnabled-prop)** : bool | **[maximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)** : int**[modified](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)** : bool**[pageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)** : QSizeF**[size](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)** : const QSizeF**[textWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)** : qreal**[undoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)** : bool**[useDesignMetrics](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#useDesignMetrics-prop)** : bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                                 | **[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextDocument)**(QObject **parent* = nullptr) |
| ------------------------------- | ------------------------------------------------------------ |
|                                 | **[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextDocument-1)**(const QString &*text*, QObject **parent* = nullptr) |
| virtual                         | **[~QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTextDocument)**() |
| void                            | **[addResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addResource)**(int *type*, const QUrl &*name*, const QVariant &*resource*) |
| void                            | **[adjustSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#adjustSize)**() |
| QList<QTextFormat>              | **[allFormats](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allFormats)**() const |
| int                             | **[availableRedoSteps](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#availableRedoSteps)**() const |
| int                             | **[availableUndoSteps](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#availableUndoSteps)**() const |
| QUrl                            | **[baseUrl](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseUrl-prop)**() const |
| qreal                           | **[baselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baselineOffset)**() const |
| QTextBlock                      | **[begin](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() const |
| int                             | **[blockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCount-prop)**() const |
| QChar                           | **[characterAt](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#characterAt)**(int *pos*) const |
| int                             | **[characterCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#characterCount)**() const |
| virtual void                    | **[clear](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| void                            | **[clearUndoRedoStacks](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearUndoRedoStacks)**(QTextDocument::Stacks *stacksToClear* = UndoAndRedoStacks) |
| QTextDocument *                 | **[clone](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clone)**(QObject **parent* = nullptr) const |
| Qt::CursorMoveStyle             | **[defaultCursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultCursorMoveStyle)**() const |
| QFont                           | **[defaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultFont)**() const |
| QString                         | **[defaultStyleSheet](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultStyleSheet-prop)**() const |
| QTextOption                     | **[defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption)**() const |
| QAbstractTextDocumentLayout *   | **[documentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentLayout)**() const |
| qreal                           | **[documentMargin](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMargin-prop)**() const |
| void                            | **[drawContents](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawContents)**(QPainter **p*, const QRectF &*rect* = QRectF()) |
| QTextBlock                      | **[end](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() const |
| QTextCursor                     | **[find](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)**(const QString &*subString*, const QTextCursor &*cursor*, QTextDocument::FindFlags *options* = FindFlags()) const |
| QTextCursor                     | **[find](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-1)**(const QString &*subString*, int *position* = 0, QTextDocument::FindFlags *options* = FindFlags()) const |
| QTextCursor                     | **[find](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-2)**(const QRegularExpression &*expr*, int *from* = 0, QTextDocument::FindFlags *options* = FindFlags()) const |
| QTextCursor                     | **[find](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find-3)**(const QRegularExpression &*expr*, const QTextCursor &*cursor*, QTextDocument::FindFlags *options* = FindFlags()) const |
| QTextBlock                      | **[findBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findBlock)**(int *pos*) const |
| QTextBlock                      | **[findBlockByLineNumber](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findBlockByLineNumber)**(int *lineNumber*) const |
| QTextBlock                      | **[findBlockByNumber](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findBlockByNumber)**(int *blockNumber*) const |
| QTextBlock                      | **[firstBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstBlock)**() const |
| qreal                           | **[idealWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#idealWidth)**() const |
| qreal                           | **[indentWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentWidth-prop)**() const |
| bool                            | **[isEmpty](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)**() const |
| bool                            | **[isLayoutEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutEnabled-prop)**() const |
| bool                            | **[isModified](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)**() const |
| bool                            | **[isRedoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRedoAvailable)**() const |
| bool                            | **[isUndoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isUndoAvailable)**() const |
| bool                            | **[isUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)**() const |
| QTextBlock                      | **[lastBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastBlock)**() const |
| int                             | **[lineCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineCount)**() const |
| void                            | **[markContentsDirty](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#markContentsDirty)**(int *position*, int *length*) |
| int                             | **[maximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)**() const |
| QString                         | **[metaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metaInformation)**(QTextDocument::MetaInformation *info*) const |
| QTextObject *                   | **[object](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#object)**(int *objectIndex*) const |
| QTextObject *                   | **[objectForFormat](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#objectForFormat)**(const QTextFormat &*f*) const |
| int                             | **[pageCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageCount)**() const |
| QSizeF                          | **[pageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)**() const |
| void                            | **[print](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#print)**(QPagedPaintDevice **printer*) const |
| void                            | **[redo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo)**(QTextCursor **cursor*) |
| QVariant                        | **[resource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resource)**(int *type*, const QUrl &*name*) const |
| QTextDocument::ResourceProvider | **[resourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resourceProvider)**() const |
| int                             | **[revision](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revision)**() const |
| QTextFrame *                    | **[rootFrame](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootFrame)**() const |
| void                            | **[setBaseUrl](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseUrl-prop)**(const QUrl &*url*) |
| void                            | **[setBaselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBaselineOffset)**(qreal *baseline*) |
| void                            | **[setDefaultCursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultCursorMoveStyle)**(Qt::CursorMoveStyle *style*) |
| void                            | **[setDefaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultFont)**(const QFont &*font*) |
| void                            | **[setDefaultStyleSheet](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultStyleSheet-prop)**(const QString &*sheet*) |
| void                            | **[setDefaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultTextOption)**(const QTextOption &*option*) |
| void                            | **[setDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocumentLayout)**(QAbstractTextDocumentLayout **layout*) |
| void                            | **[setDocumentMargin](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMargin-prop)**(qreal *margin*) |
| void                            | **[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)**(const QString &*html*) |
| void                            | **[setIndentWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIndentWidth)**(qreal *width*) |
| void                            | **[setLayoutEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutEnabled-prop)**(bool *b*) |
| void                            | **[setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMarkdown)**(const QString &*markdown*, QTextDocument::MarkdownFeatures *features* = MarkdownDialectGitHub) |
| void                            | **[setMaximumBlockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumBlockCount-prop)**(int *maximum*) |
| void                            | **[setMetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMetaInformation)**(QTextDocument::MetaInformation *info*, const QString &*string*) |
| void                            | **[setPageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)**(const QSizeF &*size*) |
| void                            | **[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)**(const QString &*text*) |
| void                            | **[setResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setResourceProvider)**(const QTextDocument::ResourceProvider &*provider*) |
| void                            | **[setSubScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSubScriptBaseline)**(qreal *baseline*) |
| void                            | **[setSuperScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSuperScriptBaseline)**(qreal *baseline*) |
| void                            | **[setTextWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)**(qreal *width*) |
| void                            | **[setUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)**(bool *enable*) |
| void                            | **[setUseDesignMetrics](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#useDesignMetrics-prop)**(bool *b*) |
| QSizeF                          | **[size](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)**() const |
| qreal                           | **[subScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subScriptBaseline)**() const |
| qreal                           | **[superScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#superScriptBaseline)**() const |
| qreal                           | **[textWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)**() const |
| QString                         | **[toHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toHtml)**() const |
| QString                         | **[toMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toMarkdown)**(QTextDocument::MarkdownFeatures *features* = MarkdownDialectGitHub) const |
| QString                         | **[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)**() const |
| QString                         | **[toRawText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toRawText)**() const |
| void                            | **[undo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo)**(QTextCursor **cursor*) |
| bool                            | **[useDesignMetrics](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#useDesignMetrics-prop)**() const |

## 公共老虎机

| void | **[redo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo-1)**() |
| ---- | ------------------------------------------------------------ |
| void | **[setModified](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)**(bool *m* = true) |
| void | **[undo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo-1)**() |

## 信号

| void | **[baseUrlChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseUrl-prop)**(const QUrl &*url*) |
| ---- | ------------------------------------------------------------ |
| void | **[blockCountChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCountChanged)**(int *newBlockCount*) |
| void | **[contentsChange](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentsChange)**(int *position*, int *charsRemoved*, int *charsAdded*) |
| void | **[contentsChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentsChanged)**() |
| void | **[cursorPositionChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionChanged)**(const QTextCursor &*cursor*) |
| void | **[documentLayoutChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentLayoutChanged)**() |
| void | **[modificationChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modificationChanged)**(bool *changed*) |
| void | **[redoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable)**(bool *available*) |
| void | **[undoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)**(bool *available*) |
| void | **[undoCommandAdded](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoCommandAdded)**() |

## 静态公共成员

| QTextDocument::ResourceProvider | **[defaultResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultResourceProvider)**() |
| ------------------------------- | ------------------------------------------------------------ |
| void                            | **[setDefaultResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultResourceProvider)**(const QTextDocument::ResourceProvider &*provider*) |

## 受保护的功能

| virtual QTextObject * | **[createObject](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createObject)**(const QTextFormat &*format*) |
| --------------------- | ------------------------------------------------------------ |
| virtual QVariant      | **[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)**(int *type*, const QUrl &*name*) |

## 详细说明

QTextDocument 是结构化富文本文档的容器，提供对样式文本和各种类型文档元素（例如列表、表格、框架和图像）的支持。它们可以被创建用于[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，或单独使用。

每个文档元素由关联的格式对象描述。每个格式对象都被 QTextDocuments 视为唯一的对象，并且可以传递给[objectForFormat](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#objectForFormat)() 来获取它所应用到的文档元素。

可以使用以下命令以编程方式编辑 QTextDocument[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并且可以通过遍历文档结构来检查其内容。整个文档结构存储为根框架下的文档元素层次结构，可通过[rootFrame](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootFrame)（） 功能。或者，如果您只想迭代文档的文本内容，您可以使用[begin](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),[end](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)（）， 和[findBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findBlock)() 来检索您可以检查和迭代的文本块。

文档的布局由以下因素决定[documentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentLayout)(); 你可以创建自己的[QAbstractTextDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类并使用设置它[setDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocumentLayout)() 如果你想使用自己的布局逻辑。文档的标题和其他元信息可以通过调用[metaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metaInformation)（） 功能。对于通过以下方式向用户公开的文档[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，文档标题也可以通过[QTextEdit::documentTitle](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)（） 功能。

这[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)（） 和[toHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toHtml)() 便利函数允许您以纯文本和 HTML 形式检索文档内容。可以使用以下方式搜索文档的文本[find](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#find)（） 功能。

可以使用以下命令控制对文档执行的操作的撤消/重做[setUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)（） 功能。撤消/重做系统可以由编辑器小部件通过[undo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo-1)（） 和[redo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redo-1)() 插槽；该文件还规定[contentsChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentsChanged)(),[undoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)（）， 和[redoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable)() 信号通知连接的编辑器小部件有关撤消/重做系统的状态。以下是 QTextDocument 的撤消/重做操作：

- 插入或删除字符。同一文本块内的一系列插入或删除被视为单个撤消/重做操作。
- 插入或删除文本块。单个操作中的插入或删除序列（例如，通过选择然后删除文本）被视为单个撤消/重做操作。
- 文本字符格式发生变化。
- 文本块格式更改。
- 文本块组格式更改。

**也可以看看**[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Rich Text Processing](https://doc-qt-io.translate.goog/qt-6/richtext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和文本对象示例。

## 会员类型文档

### 枚举 QTextDocument:: FindFlag 标志 QTextDocument:: FindFlags

该枚举描述了可用的选项[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的查找功能。可以将以下列表中的选项组合在一起：

| 持续的                               | 价值      | 描述                                                         |
| ------------------------------------ | --------- | ------------------------------------------------------------ |
| `QTextDocument::FindBackward`        | `0x00001` | 向后搜索而不是向前搜索。                                     |
| `QTextDocument::FindCaseSensitively` | `0x00002` | 默认情况下，查找工作不区分大小写。指定此选项会将行为更改为区分大小写的查找操作。 |
| `QTextDocument::FindWholeWords`      | `0x00004` | 使查找仅匹配完整的单词。                                     |

FindFlags 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <FindFlag> 的类型定义。它存储 FindFlag 值的 OR 组合。

### enum QTextDocument::MetaInformation

该枚举描述了可以添加到文档中的不同类型的元信息。

| 持续的                         | 价值 | 描述                                                         |
| ------------------------------ | ---- | ------------------------------------------------------------ |
| `QTextDocument::DocumentTitle` | `0`  | 文档的标题。                                                 |
| `QTextDocument::DocumentUrl`   | `1`  | 文档的网址。这[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)() 函数在加载相关资源时使用此 url 作为基础。 |
| `QTextDocument::CssMedia`      | `2`  | 该值用于在以下情况下从指定的 CSS 样式表中选择相应的“@media”规则（如果有）[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)（） 叫做。该枚举值已在 Qt 6.3 中引入。 |

**也可以看看**[metaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metaInformation)(),[setMetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMetaInformation)（）， 和[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)()。

### `[alias, since 6.1]`QTextDocument::ResourceProvider

std::function< 的类型别名[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（常量[QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)&)>。

这个 typedef 是在 Qt 6.1 中引入的。

### enum QTextDocument::ResourceType

该枚举描述了可以加载的资源类型[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)() 函数或通过[QTextBrowser::setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)()。

| 持续的                              | 价值  | 描述                                                         |
| ----------------------------------- | ----- | ------------------------------------------------------------ |
| `QTextDocument::UnknownResource`    | `0`   | 未加载资源，或资源类型未知。                                 |
| `QTextDocument::HtmlResource`       | `1`   | 该资源包含 HTML。                                            |
| `QTextDocument::ImageResource`      | `2`   | 该资源包含图像数据。目前支持的数据类型有[QMetaType::QPixmap](https://doc-qt-io.translate.goog/qt-6/qmetatype.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)和[QMetaType::QImage](https://doc-qt-io.translate.goog/qt-6/qmetatype.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)。如果对应的变体是类型[QMetaType::QByteArray](https://doc-qt-io.translate.goog/qt-6/qmetatype.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)然后 Qt 尝试使用加载图像[QImage::loadFromData](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadFromData)。[QMetaType::QIcon](https://doc-qt-io.translate.goog/qt-6/qmetatype.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)目前不支持。图标需要首先转换为支持的类型之一，例如使用[QIcon::pixmap](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pixmap)。 |
| `QTextDocument::StyleSheetResource` | `3`   | 该资源包含 CSS。                                             |
| `QTextDocument::MarkdownResource`   | `4`   | 该资源包含 Markdown。                                        |
| `QTextDocument::UserResource`       | `100` | 用户定义的资源类型的第一个可用值。                           |

**也可以看看**[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)（） 和[QTextBrowser::sourceType](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sourceType-prop)()。

### enum QTextDocument::Stacks

| 持续的                             | 价值                    | 描述             |
| ---------------------------------- | ----------------------- | ---------------- |
| `QTextDocument::UndoStack`         | `0x01`                  | 撤消堆栈。       |
| `QTextDocument::RedoStack`         | `0x02`                  | 重做堆栈。       |
| `QTextDocument::UndoAndRedoStacks` | `UndoStack | RedoStack` | 撤消和重做堆栈。 |

## 财产文件

### baseUrl : [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存用于解析文档中相对资源 URL 的基本 URL。

资源 URL 被解析为与基本 URL 的目标位于同一目录中，这意味着最后一个“/”之后的路径的任何部分都将被忽略。

|              基本网址              |     相对网址     |              已解析的网址               |
| :--------------------------------: | :--------------: | :-------------------------------------: |
|        文件:///路径/到/内容        |  图片/标志.png   |     文件:///path/to/images/logo.png     |
|       文件:///路径/到/内容/        |  图片/标志.png   | 文件:///path/to/content/images/logo.png |
| 文件:///path/to/content/index.html |  图片/标志.png   | 文件:///path/to/content/images/logo.png |
|     文件:///路径/到/内容/图像/     | ../图片/标志.png | 文件:///path/to/content/images/logo.png |

**访问功能：**

| QUrl | **baseUrl**() const               |
| ---- | --------------------------------- |
| void | **setBaseUrl**(const QUrl &*url*) |

**通知器信号：**

| void | **baseUrlChanged**(const QUrl &*url*) |
| ---- | ------------------------------------- |
|      |                                       |

### `[read-only]`blockCount : const int

该属性保存文档中文本块的数量。

在带有表格或框架的文档中，此属性的值未定义。

默认情况下，如果已定义，此属性包含值 1。

**访问功能：**

| int  | **blockCount**() const |
| ---- | ---------------------- |
|      |                        |

**也可以看看**[lineCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineCount)（） 和[characterCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#characterCount)()。

### defaultFont : [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存用于显示文档文本的默认字体

**访问功能：**

| QFont | **[defaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultFont)**() const |
| ----- | ------------------------------------------------------------ |
| void  | **[setDefaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultFont)**(const QFont &*font*) |

### defaultStyleSheet : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

默认样式表适用于插入到文档中的所有新 HTML 格式的文本，例如使用[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)（） 或者[QTextCursor::insertHtml](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertHtml)()。

样式表需要符合 CSS 2.1 语法。

**注意：**更改默认样式表不会对文档的现有内容产生任何影响。

**访问功能：**

| QString | **defaultStyleSheet**() const                    |
| ------- | ------------------------------------------------ |
| void    | **setDefaultStyleSheet**(const QString &*sheet*) |

**也可以看看**[Supported HTML Subset](https://doc-qt-io.translate.goog/qt-6/richtext-html-subset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### defaultTextOption : [QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性保存将在所有内容上设置的默认文本选项[QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档中的。

什么时候[QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建后，在其上设置 defaultTextOption[QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这允许设置文档的全局属性，例如默认自动换行模式。

**访问功能：**

| QTextOption | **[defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption)**() const |
| ----------- | ------------------------------------------------------------ |
| void        | **[setDefaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultTextOption)**(const QTextOption &*option*) |

### documentMargin : [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)

文档周围的边距。默认值为 4。

**访问功能：**

| qreal | **documentMargin**() const            |
| ----- | ------------------------------------- |
| void  | **setDocumentMargin**(qreal *margin*) |

### indentWidth : [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)

返回用于文本列表和文本块缩进的宽度。

的缩进属性[QTextListFormat](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)指定该值的倍数。默认缩进宽度为 40。

**访问功能：**

| qreal | **indentWidth**() const                                      |
| ----- | ------------------------------------------------------------ |
| void  | **[setIndentWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIndentWidth)**(qreal *width*) |

### `[since 6.4]`layoutEnabled : bool

该属性是否持有[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)每次更改后应重新计算布局

如果此属性设置为 true，则对文档的任何更改都会触发布局，这会使一切按预期工作，但需要时间。

暂时禁用布局可以在进行多次更改（不仅仅是文本内容，还有默认字体、默认文本选项......）时节省时间，以便文档在最后只布局一次。例如，当文本宽度或页面大小未知时，这可能很有用。

默认情况下，该属性为`true`。

该属性是在 Qt 6.4 中引入的。

**访问功能：**

| bool | **isLayoutEnabled**() const    |
| ---- | ------------------------------ |
| void | **setLayoutEnabled**(bool *b*) |

**也可以看看**[setTextWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)。

### maximumBlockCount : int

指定文档中块的限制。

指定文档可以具有的最大块数。如果文档中有更多使用此属性指定的块，则会从文档的开头删除。

负值或零值指定文档可以包含无限数量的块。

默认值为 0。

请注意，设置此属性会将限制立即应用于文档内容。

设置此属性还会禁用撤消重做历史记录。

在带有表格或框架的文档中未定义此属性。

**访问功能：**

| int  | **maximumBlockCount**() const           |
| ---- | --------------------------------------- |
| void | **setMaximumBlockCount**(int *maximum*) |

### modified : bool

该属性保存文档是否已被用户修改

默认情况下，该属性为`false`。

**访问功能：**

| bool | **isModified**() const           |
| ---- | -------------------------------- |
| void | **setModified**(bool *m* = true) |

**也可以看看**[modificationChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modificationChanged)()。

### pageSize : [QSizeF](https://doc-qt-io.translate.goog/qt-6/qsizef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存用于布局文档的页面大小

单位由底层绘画设备决定。在屏幕上绘制时，尺寸以逻辑像素为单位测量；在打印机上绘制时，尺寸以磅（1/72 英寸）为单位测量。

默认情况下，对于新创建的空文档，此属性包含未定义的大小。

**访问功能：**

| QSizeF | **pageSize**() const                  |
| ------ | ------------------------------------- |
| void   | **setPageSize**(const QSizeF &*size*) |

**也可以看看**[modificationChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modificationChanged)()。

### `[read-only]`size : const [QSizeF](https://doc-qt-io.translate.goog/qt-6/qsizef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存文档的实际大小。这相当于[documentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentLayout)()->文档大小();

可以通过设置文本宽度或设置整个页面大小来更改文档的大小。

请注意，宽度始终 >=[pageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)（）。宽度（）。

默认情况下，对于新创建的空文档，此属性包含与配置相关的大小。

**访问功能：**

| QSizeF | **size**() const |
| ------ | ---------------- |
|        |                  |

**也可以看看**[setTextWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)(),[setPageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)（）， 和[idealWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#idealWidth)()。

### textWidth : [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)

文本宽度指定文档中文本的首选宽度。如果文本（或一般内容）比指定的宽，则它会分成多行并垂直增长。如果文本无法分成多行以适合指定的文本宽度，则文本会更大并且[size](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)() 和[idealWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#idealWidth)() 属性将反映这一点。

如果文本宽度设置为 -1，则文本不会分成多行，除非通过显式换行符或新段落强制执行。

默认值为-1。

设置文本宽度也会将页面高度设置为-1，导致文档以连续的方式垂直增大或缩小。如果您希望文档布局将文本分成多个页面，那么您必须设置[pageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)财产代替。

**访问功能：**

| qreal | **textWidth**() const           |
| ----- | ------------------------------- |
| void  | **setTextWidth**(qreal *width*) |

**也可以看看**[size](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)(),[idealWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#idealWidth)（）， 和[pageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)()。

### undoRedoEnabled : bool

该属性保存是否对该文档启用撤消/重做

这默认为 true。如果禁用，撤消堆栈将被清除，并且不会向其中添加任何项目。

**访问功能：**

| bool | **isUndoRedoEnabled**() const         |
| ---- | ------------------------------------- |
| void | **setUndoRedoEnabled**(bool *enable*) |

### useDesignMetrics : bool

该属性保存文档是否使用字体的设计指标来提高文本布局的准确性

如果此属性设置为 true，则布局将使用设计指标。否则，绘制设备的指标设置为[QAbstractTextDocumentLayout::setPaintDevice](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPaintDevice)（） 将会被使用。

使用设计指标使布局的宽度不再依赖于提示和像素舍入。这意味着所见即所得的文本布局成为可能，因为与其他情况相比，宽度基于绘图设备指标的线性缩放更加线性。

默认情况下，该属性为`false`。

**访问功能：**

| bool | **useDesignMetrics**() const      |
| ---- | --------------------------------- |
| void | **setUseDesignMetrics**(bool *b*) |

## 成员函数文档

### `[explicit]`QTextDocument::QTextDocument([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

使用给定的值构造一个空的 QTextDocument*parent*。

### `[explicit]`QTextDocument::QTextDocument(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

构造一个包含纯文本（未格式化）的 QTextDocument*text*指定的，并且具有给定的*parent*。

### `[virtual noexcept]`QTextDocument::~QTextDocument()

销毁文档。

### void QTextDocument::addResource(int *type*, const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*resource*)

添加资源*resource*到资源缓存，使用*type*和*name*作为标识符。*type*应该是一个值[QTextDocument::ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)。

例如，您可以添加图像作为资源，以便从文档中引用它：

```
    document->addResource(QTextDocument::ImageResource,
        QUrl("mydata://image.png"), QVariant(image));
```

可以使用以下命令将图像插入到文档中[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)应用程序编程接口：

```
    QTextImageFormat imageFormat;
    imageFormat.setName("mydata://image.png");
    cursor.insertImage(imageFormat);
```

或者，您可以使用 HTML`img`标签插入图像：

```
    editor->append("<img src=\"mydata://image.png\" />");
```

### void QTextDocument::adjustSize()

将文档调整到合理的大小。

**也可以看看**[idealWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#idealWidth)(),[textWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)， 和[size](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextFormat](https://doc-qt-io.translate.goog/qt-6/qtextformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QTextDocument::allFormats() const

返回文档中使用的所有格式的文本格式列表。

### int QTextDocument::availableRedoSteps() const

返回可用重做步骤的数量。

**也可以看看**[isRedoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRedoAvailable)()。

### int QTextDocument::availableUndoSteps() const

返回可用撤消步骤的数量。

**也可以看看**[isUndoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isUndoAvailable)()。

### `[since 6.0]`[qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QTextDocument::baselineOffset() const

返回文档布局中使用的基线偏移量（以 % 为单位）。

这个函数是在Qt 6.0中引入的。

**也可以看看**[setBaselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBaselineOffset)(),[setSubScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSubScriptBaseline)(),[subScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subScriptBaseline)(),[setSuperScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSuperScriptBaseline)（）， 和[superScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#superScriptBaseline)()。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::begin() const

返回文档的第一个文本块。

**也可以看看**[firstBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstBlock)()。

### `[signal]`void QTextDocument::blockCountChanged(int *newBlockCount*)

当文档中的文本块总数发生变化时，会发出此信号。传入的值*newBlockCount*是新的总数。

### [QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::characterAt(int *pos*) const

返回位置处的字符*pos*，或者如果位置超出范围则为空字符。

**也可以看看**[characterCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#characterCount)()。

### int QTextDocument::characterCount() const

返回此文档的字符数。

**注：**作为[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)总是包含至少一个[QChar::ParagraphSeparator](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SpecialCharacter-enum)，此方法将至少返回 1。

**也可以看看**[blockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCount-prop)（） 和[characterAt](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#characterAt)()。

### `[virtual]`void QTextDocument::clear()

清除文档。

### void QTextDocument::clearUndoRedoStacks([QTextDocument::Stacks](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Stacks-enum) *stacksToClear* = UndoAndRedoStacks)

清除由指定的堆栈*stacksToClear*。

此方法清除撤消堆栈、重做堆栈或两者（默认）上的所有命令。如果命令被清除，则会发出适当的信号，[QTextDocument::undoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)（） 或者[QTextDocument::redoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable)()。

**也可以看看**[QTextDocument::undoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)（） 和[QTextDocument::redoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#redoAvailable)()。

### [QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextDocument) *QTextDocument::clone([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr) const

创建一个新的[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)这是该文本文档的副本。*parent*是返回的文本文档的父文档。

### `[signal]`void QTextDocument::contentsChange(int *position*, int *charsRemoved*, int *charsAdded*)

每当文档内容发生更改时都会发出此信号；例如，插入或删除文本时，或者应用格式时。

提供了有关*position*文档中发生更改的字符的数量，删除的字符数（*charsRemoved*），以及添加的字符数（*charsAdded*）。

在文档的布局管理器收到有关更改的通知之前发出该信号。该挂钩允许您为文档实现语法突出显示。

**也可以看看**[QAbstractTextDocumentLayout::documentChanged](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentChanged)（） 和[contentsChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentsChanged)()。

### `[signal]`void QTextDocument::contentsChanged()

每当文档内容发生更改时都会发出此信号；例如，插入或删除文本时，或者应用格式时。

**也可以看看**[contentsChange](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contentsChange)()。

### `[virtual protected]`[QTextObject](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextDocument::createObject(const [QTextFormat](https://doc-qt-io.translate.goog/qt-6/qtextformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

创建并返回一个新的文档对象（a[QTextObject](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)），根据给定的*format*。

QTextObjects 将始终通过此方法创建，因此如果您在文档中使用自定义文本对象，则必须重新实现它。

### `[signal]`void QTextDocument::cursorPositionChanged(const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*)

每当光标位置由于编辑操作而改变时，就会发出该信号。改变的光标被传入*cursor*。如果该文档与[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，当使用箭头键移动光标时需要一个信号，您可以使用[cursorPositionChanged](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursorPositionChanged)() 信号输入[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [Qt::CursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorMoveStyle-enum) QTextDocument::defaultCursorMoveStyle() const

所有使用默认的光标移动样式[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)从文档创建的对象。默认为[Qt::LogicalMoveStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorMoveStyle-enum)。

**也可以看看**[setDefaultCursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultCursorMoveStyle)()。

### [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::defaultFont() const

返回文档布局中使用的默认字体。

**注意：**属性 defaultFont 的 Getter 函数。

**也可以看看**[setDefaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultFont)()。

### `[static, since 6.1]`[QTextDocument::ResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceProvider-typedef) QTextDocument::defaultResourceProvider()

返回默认的资源提供者。

该功能是在 Qt 6.1 中引入的。

**也可以看看**[setDefaultResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultResourceProvider)(),[resourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resourceProvider)（）， 和[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

### [QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::defaultTextOption() const

默认文本选项用于所有[QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档中的对象。这允许设置文档的全局属性，例如默认自动换行模式。

**注意：** defaultTextOption 属性的 Getter 函数。

**也可以看看**[setDefaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultTextOption)()。

### [QAbstractTextDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextDocument::documentLayout() const

返回此文档的文档布局。

**也可以看看**[setDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocumentLayout)()。

### `[signal]`void QTextDocument::documentLayoutChanged()

当设置新的文档布局时，会发出此信号。

**也可以看看**[setDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDocumentLayout)()。

### void QTextDocument::drawContents([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **p*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF())

用painter绘制文档的内容*p*，剪裁到*rect*。如果*rect*是一个空矩形（默认），则文档将被绘制为未剪切的。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::end() const

此函数返回一个块，以在迭代文档时测试文档的结尾。

```
for (QTextBlock it = doc->begin(); it != doc->end(); it = it.next())
    std::cout << it.text().toStdString() << "\n";
```

返回的块无效，代表文档中最后一个块之后的块。您可以使用[lastBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastBlock)() 检索文档的最后一个有效块。

**也可以看看**[lastBlock](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastBlock)()。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::find(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*subString*, const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = FindFlags()) const

查找字符串的下一个出现位置，*subString*，在文档中。搜索从给定的位置开始*cursor*，并继续浏览文档，除非搜索选项中另有指定。这*options*控制执行的搜索类型。

如果满足以下条件，则返回选定匹配项的光标*subString*被找到; 否则返回空游标。

如果给定*cursor*有选择，选择后开始搜索；否则它从光标位置开始。

默认情况下，搜索不区分大小写，并且可以匹配文档中任何位置的文本。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::find(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*subString*, int *position* = 0, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = FindFlags()) const

这是一个过载功能。

查找字符串的下一个出现位置，*subString*，在文档中。搜索从给定的位置开始*position*，并继续浏览文档，除非搜索选项中另有指定。这*options*控制执行的搜索类型。

如果满足以下条件，则返回选定匹配项的光标*subString*被找到; 否则返回空游标。

如果*position*为 0（默认值）则从文档开头开始搜索；否则它从指定位置开始。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::find(const [QRegularExpression](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*expr*, int *from* = 0, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = FindFlags()) const

查找与给定正则表达式匹配的下一个匹配项，*expr*，在文档的同一段落中。

搜索从给定的位置开始*from*位置，并继续浏览文档，除非搜索选项中另有指定。这*options*控制执行的搜索类型。

如果找到匹配项，则返回选中的匹配项的光标；否则返回空游标。

如果*from*位置为0（默认）搜索从文档的开头开始；否则它从指定位置开始。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::find(const [QRegularExpression](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*expr*, const [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*, [QTextDocument::FindFlags](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FindFlag-enum) *options* = FindFlags()) const

查找与给定正则表达式匹配的下一个匹配项，*expr*，在文档的同一段落中。

搜索从给定的位置开始*cursor*，并继续浏览文档，除非搜索选项中另有指定。这*options*控制执行的搜索类型。

如果找到匹配项，则返回选中的匹配项的光标；否则返回空游标。

如果给定*cursor*有选择，选择后开始搜索；否则它从光标位置开始。

默认情况下，搜索不区分大小写，并且可以匹配文档中任何位置的文本。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::findBlock(int *pos*) const

返回包含以下内容的文本块*pos*第 - 个字符。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::findBlockByLineNumber(int *lineNumber*) const

返回包含指定内容的文本块*lineNumber*。

**也可以看看**[QTextBlock::firstLineNumber](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstLineNumber)()。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::findBlockByNumber(int *blockNumber*) const

返回具有指定的文本块*blockNumber*。

**也可以看看**[QTextBlock::blockNumber](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockNumber)()。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::firstBlock() const

返回文档的第一个文本块。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QTextDocument::idealWidth() const

返回文本文档的理想宽度。理想宽度是文档实际使用的宽度，不考虑可选的对齐方式。总是<=[size](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size-prop)（）。宽度（）。

**也可以看看**[adjustSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#adjustSize)（） 和[textWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textWidth-prop)。

### bool QTextDocument::isEmpty() const

`true`如果文档为空则返回；否则返回`false`.

### bool QTextDocument::isRedoAvailable() const

`true`如果重做可用则返回；否则返回`false`.

**也可以看看**[isUndoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isUndoAvailable)（） 和[availableRedoSteps](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#availableRedoSteps)()。

### bool QTextDocument::isUndoAvailable() const

`true`如果撤消可用则返回；否则返回`false`.

**也可以看看**[isRedoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRedoAvailable)（） 和[availableUndoSteps](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#availableUndoSteps)()。

### [QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::lastBlock() const

返回文档的最后一个（有效）文本块。

### int QTextDocument::lineCount() const

返回此文档的行数（如果布局支持）。否则，这与块数相同。

**也可以看看**[blockCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockCount-prop)（） 和[characterCount](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#characterCount)()。

### `[virtual protected invokable]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::loadResource(int *type*, const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

加载指定的数据*type*从给定的资源*name*。

该函数由富文本引擎调用，以请求不直接存储的数据[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但仍然与之相关。例如，图像通过名称属性间接引用[QTextImageFormat](https://doc-qt-io.translate.goog/qt-6/qtextimageformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

当被 Qt 调用时，*type*是的值之一[QTextDocument::ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)。

如果[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)是 a 的子对象[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)具有可调用的 loadResource 方法，例如[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或一个[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)然后默认实现尝试从父级检索数据。

**注意：**该函数可以通过元对象系统和 QML 调用。看[Q_INVOKABLE](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Q_INVOKABLE)。

**也可以看看**[QTextDocument::ResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceProvider-typedef)。

### void QTextDocument::markContentsDirty(int *position*, int *length*)

标记给定指定的内容*position*和*length*为“脏”，通知文档需要重新布局。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::metaInformation([QTextDocument::MetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MetaInformation-enum) *info*) const

返回有关指定类型的文档的元信息*info*。

**也可以看看**[setMetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMetaInformation)()。

### `[signal]`void QTextDocument::modificationChanged(bool *changed*)

每当文档内容发生变化并影响修改状态时，就会发出此信号。如果*changed*属实，文档已被修改；否则就是假的。

例如，调用[setModified](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)(false) 在文档上，然后插入文本会导致发出信号。如果您撤消该操作，导致文档返回到其原始未修改状态，则该信号将再次发出。

### [QTextObject](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextDocument::object(int *objectIndex*) const

返回与给定关联的文本对象*objectIndex*。

### [QTextObject](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextDocument::objectForFormat(const [QTextFormat](https://doc-qt-io.translate.goog/qt-6/qtextformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*f*) const

返回与格式关联的文本对象*f*。

### int QTextDocument::pageCount() const

返回此文档中的页数。

### void QTextDocument::print([QPagedPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpagedpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **printer*) const

将文档打印到给定的位置*printer*。这[QPagedPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpagedpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此功能之前必须先进行设置。

这只是将整个文档打印到打印机的一种便捷方法。

如果文档已按指定高度分页[pageSize](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pageSize-prop)() 属性按原样打印。

如果文档未分页，例如在[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，然后创建文档的临时副本，并根据绘图设备的 paperRect() 的大小将该副本分成多个页面。默认情况下，文档内容周围设置 2 厘米的边距。此外，当前页码打印在每页底部。

**也可以看看**[QTextEdit::print](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#print)()。

### void QTextDocument::redo([QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **cursor*)

如果出现以下情况，则重做对文档的最后一次编辑操作[redo is available](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRedoAvailable)。

所提供的*cursor*位于重做编辑操作的位置的末尾。

### `[slot]`void QTextDocument::redo()

这是一个过载功能。

如果出现以下情况，则重做对文档的最后一次编辑操作[redo is available](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRedoAvailable)。

### `[signal]`void QTextDocument::redoAvailable(bool *available*)

每当重做操作可用时就会发出此信号（*available*为真）或不可用（*available*是假的）。

### [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::resource(int *type*, const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*) const

返回指定的数据*type*从给定的资源*name*。

该函数由富文本引擎调用，以请求不直接存储的数据[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但仍然与之相关。例如，图像通过名称属性间接引用[QTextImageFormat](https://doc-qt-io.translate.goog/qt-6/qtextimageformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

资源在文档内部缓存。如果在缓存中找不到资源，[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)被调用来尝试加载资源。[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)然后应该使用[addResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addResource)将资源添加到缓存中。

如果[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)不加载资源，那么[resourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resourceProvider)最后是[defaultResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultResourceProvider)如果设置的话将被调用。请注意，来自提供程序的结果不会自动添加到缓存中。

**也可以看看**[QTextDocument::ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)和[resourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resourceProvider)()。

### `[since 6.1]`[QTextDocument::ResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceProvider-typedef) QTextDocument::resourceProvider() const

返回此文本文档的资源提供者。

该功能是在 Qt 6.1 中引入的。

**也可以看看**[setResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setResourceProvider)(),[defaultResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultResourceProvider)（）， 和[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

### int QTextDocument::revision() const

返回文档的修订版本（如果启用了撤消功能）。

当编辑未修改的文档时，保证会增加修订版本。

**也可以看看**[QTextBlock::revision](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revision)（） 和[isModified](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)()。

### [QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextDocument::rootFrame() const

返回文档的根框架。

### `[since 6.0]`void QTextDocument::setBaselineOffset([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *baseline*)

将基线设置为要在文档布局中使用的字体高度的百分比*baseline*。默认值为 0。正值将文本向上移动相应的 %；负值会将其向下移动。

这个函数是在Qt 6.0中引入的。

**也可以看看**[baselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baselineOffset)(),[setSubScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSubScriptBaseline)(),[subScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subScriptBaseline)(),[setSuperScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSuperScriptBaseline)（）， 和[superScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#superScriptBaseline)()。

### void QTextDocument::setDefaultCursorMoveStyle([Qt::CursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorMoveStyle-enum) *style*)

将默认光标移动样式设置为给定的*style*。

**也可以看看**[defaultCursorMoveStyle](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultCursorMoveStyle)()。

### void QTextDocument::setDefaultFont(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

设置默认值*font*在文档布局中使用。

**注意：**属性的 Setter 函数[defaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultFont)。

**也可以看看**[defaultFont](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultFont)()。

### `[static, since 6.1]`void QTextDocument::setDefaultResourceProvider(const [QTextDocument::ResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceProvider-typedef) &*provider*)

将默认资源提供者设置为*provider*。

默认提供程序将由所有没有显式提供程序集的 QTextDocument 使用。

该功能是在 Qt 6.1 中引入的。

**也可以看看**[defaultResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultResourceProvider)(),[setResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setResourceProvider)（）， 和[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

### void QTextDocument::setDefaultTextOption(const [QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*)

将默认文本选项设置为*option*。

**注意：**属性的 Setter 函数[defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption)。

**也可以看看**[defaultTextOption](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultTextOption)()。

### void QTextDocument::setDocumentLayout([QAbstractTextDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **layout*)

设置文档使用给定的*layout*。之前的布局被删除。

**也可以看看**[documentLayoutChanged](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentLayoutChanged)()。

### void QTextDocument::setHtml(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*html*)

将文档的全部内容替换为给定的 HTML 格式文本*html*细绳。调用此函数时，撤消/重做历史记录将被重置。

尽可能尊重 HTML 格式；例如，“<b>粗体</b>文本”将生成文本，其中第一个单词的字体粗细使其具有粗体外观：“**粗体**文本”。

要选择默认“screen”规则之外的 CSS 媒体规则，请使用[setMetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMetaInformation)（） 和 '[CssMedia](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MetaInformation-enum)' 作为“信息”参数。

**注意：**调用者有责任确保文本在调用时正确解码。[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建包含 HTML 的内容并将其传递给 setHtml()。

**也可以看看**[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)(),[Supported HTML Subset](https://doc-qt-io.translate.goog/qt-6/richtext-html-subset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[setMetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMetaInformation)()。

### void QTextDocument::setIndentWidth([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *width*)

设置*width*用于文本列表和文本块缩进。

的缩进属性[QTextListFormat](https://doc-qt-io.translate.goog/qt-6/qtextlistformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)指定该值的倍数。默认缩进宽度为 40 。

**注意：**属性的 Setter 函数[indentWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentWidth-prop)。

**也可以看看**[indentWidth](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indentWidth-prop)()。

### void QTextDocument::setMarkdown(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*markdown*, [QTextDocument::MarkdownFeatures](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MarkdownFeature-enum) *features* = MarkdownDialectGitHub)

将文档的全部内容替换为给定的 Markdown 格式的文本*markdown*字符串，与给定的*features*支持的。默认情况下，包含所有受支持的 GitHub 风格的 Markdown 功能；通过`MarkdownDialectCommonMark`更基本的解析。

尽可能尊重 Markdown 格式；例如，“*粗体*文本”将生成第一个单词具有强调外观的字体粗细的文本。

解析包含在*markdown*字符串的处理方式与[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml); 但是，不支持 HTML 块内的 Markdown 格式。

解析器的某些功能可以通过以下方式启用或禁用*features*争论：

| 持续的                      | 描述                                      |
| --------------------------- | ----------------------------------------- |
| `MarkdownNoHTML`            | Markdown 文本中的任何 HTML 标签都将被丢弃 |
| `MarkdownDialectCommonMark` | 解析器仅支持 CommonMark 标准化的功能      |
| `MarkdownDialectGitHub`     | 解析器支持 GitHub 方言                    |

默认为`MarkdownDialectGitHub`.

调用此函数时，撤消/重做历史记录将被重置。

### void QTextDocument::setMetaInformation([QTextDocument::MetaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MetaInformation-enum) *info*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*string*)

设置指定类型的文档元信息*info*对给定的*string*。

**也可以看看**[metaInformation](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metaInformation)()。

### void QTextDocument::setPlainText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

用给定的纯文本替换文档的全部内容*text*。调用此函数时，撤消/重做历史记录将被重置。

**也可以看看**[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)()。

### `[since 6.1]`void QTextDocument::setResourceProvider(const [QTextDocument::ResourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceProvider-typedef) &*provider*)

将文本文档的资源提供者设置为*provider*。

该功能是在 Qt 6.1 中引入的。

**也可以看看**[resourceProvider](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resourceProvider)（） 和[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)()。

### `[since 6.0]`void QTextDocument::setSubScriptBaseline([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *baseline*)

将默认下标的基线设置为要在文档布局中使用的字体高度的百分比*baseline*。默认值为 16.67%（高度的 1/6）。

这个函数是在Qt 6.0中引入的。

**也可以看看**[subScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subScriptBaseline)(),[setSuperScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSuperScriptBaseline)(),[superScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#superScriptBaseline)(),[setBaselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBaselineOffset)（）， 和[baselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baselineOffset)()。

### `[since 6.0]`void QTextDocument::setSuperScriptBaseline([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *baseline*)

将默认上标的基线设置为要在文档布局中使用的字体高度的百分比*baseline*。默认值为 50%（高度的 1/2）。

这个函数是在Qt 6.0中引入的。

**也可以看看**[superScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#superScriptBaseline)(),[setSubScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSubScriptBaseline)(),[subScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subScriptBaseline)(),[setBaselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBaselineOffset)（）， 和[baselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baselineOffset)()。

### `[since 6.0]`[qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QTextDocument::subScriptBaseline() const

返回上标的基线作为文档布局中使用的字体高度的百分比。

这个函数是在Qt 6.0中引入的。

**也可以看看**[setSubScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSubScriptBaseline)(),[setSuperScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSuperScriptBaseline)(),[superScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#superScriptBaseline)(),[setBaselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBaselineOffset)（）， 和[baselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baselineOffset)()。

### `[since 6.0]`[qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QTextDocument::superScriptBaseline() const

返回上标的基线作为文档布局中使用的字体高度的百分比。

这个函数是在Qt 6.0中引入的。

**也可以看看**[setSuperScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSuperScriptBaseline)(),[setSubScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSubScriptBaseline)(),[subScriptBaseline](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subScriptBaseline)(),[setBaselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBaselineOffset)（）， 和[baselineOffset](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baselineOffset)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::toHtml() const

返回包含文档的 HTML 表示形式的字符串。

文档内容指定其编码为UTF-8。如果您稍后将返回的 html 字符串转换为字节数组以便通过网络传输或保存到磁盘时，您应该使用[QString::toUtf8](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toUtf8)() 将字符串转换为[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[Supported HTML Subset](https://doc-qt-io.translate.goog/qt-6/richtext-html-subset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::toMarkdown([QTextDocument::MarkdownFeatures](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MarkdownFeature-enum) *features* = MarkdownDialectGitHub) const

返回一个字符串，其中包含具有给定文档的 Markdown 表示形式*features*，或者如果由于任何原因写入失败则返回空字符串。

**也可以看看**[setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMarkdown)。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::toPlainText() const

返回文档中包含的纯文本。如果您想要格式化信息，请使用[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)反而。

该函数的返回值与[toRawText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toRawText)()，但会用 ASCII 替代字符替换一些 unicode 字符。特别是，不间断空格 (U+00A0) 被替换为常规空格 (U+0020)，段落 (U+2029) 和行 (U+2028) 分隔符均被换行 (U+000A) 替换。如果您需要文档的精确内容，请使用[toRawText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toRawText)（） 反而。

**注意：**嵌入对象（例如图像）由 Unicode 值 U+FFFC（对象替换字符）表示。

**也可以看看**[toHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toHtml)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextDocument::toRawText() const

返回文档中包含的原始文本，不带任何格式信息。如果您想要格式化信息，请使用[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)反而。

**也可以看看**[toPlainText](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toPlainText)()。

### void QTextDocument::undo([QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **cursor*)

如果撤消可用，则撤消对文档的上次编辑操作。所提供的*cursor*位于撤消编辑操作的位置的末尾。

请参阅[Qt Undo Framework](https://doc-qt-io.translate.goog/qt-6/qundo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档了解详细信息。

**也可以看看**[undoAvailable](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoAvailable)（） 和[isUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)()。

### `[slot]`void QTextDocument::undo()

这是一个过载功能。

### `[signal]`void QTextDocument::undoAvailable(bool *available*)

每当撤消操作可用时就会发出此信号（*available*为真）或不可用（*available*是假的）。

请参阅[Qt Undo Framework](https://doc-qt-io.translate.goog/qt-6/qundo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档了解详细信息。

**也可以看看**[undo](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undo-1)（） 和[isUndoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)()。

### `[signal]`void QTextDocument::undoCommandAdded()

每当新的撤消级别添加到时，都会发出此信号[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。