#  QTextBlock Class

QTextBlock 类为文本片段提供了一个容器[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include <QTextBlock>                                        |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:  | QT += gui                                                    |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextblock-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextBlock 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[iterator](https://doc-qt-io.translate.goog/qt-6/qtextblock-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
|       | **[Iterator](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Iterator-typedef)** |

## 公共职能

|                                 | **[QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextBlock-2)**(const QTextBlock &*other*) |
| ------------------------------- | ------------------------------------------------------------ |
| QTextBlock::iterator            | **[begin](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() const |
| QTextBlockFormat                | **[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)**() const |
| int                             | **[blockFormatIndex](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormatIndex)**() const |
| int                             | **[blockNumber](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockNumber)**() const |
| QTextCharFormat                 | **[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)**() const |
| int                             | **[charFormatIndex](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormatIndex)**() const |
| void                            | **[clearLayout](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearLayout)**() |
| bool                            | **[contains](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)**(int *position*) const |
| const QTextDocument *           | **[document](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)**() const |
| QTextBlock::iterator            | **[end](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() const |
| int                             | **[firstLineNumber](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstLineNumber)**() const |
| bool                            | **[isValid](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)**() const |
| bool                            | **[isVisible](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)**() const |
| QTextLayout *                   | **[layout](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layout)**() const |
| int                             | **[length](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#length)**() const |
| int                             | **[lineCount](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineCount)**() const |
| QTextBlock                      | **[next](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)**() const |
| int                             | **[position](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)**() const |
| QTextBlock                      | **[previous](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)**() const |
| int                             | **[revision](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revision)**() const |
| void                            | **[setLineCount](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLineCount)**(int *count*) |
| void                            | **[setRevision](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRevision)**(int *rev*) |
| void                            | **[setUserData](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setUserData)**(QTextBlockUserData **data*) |
| void                            | **[setUserState](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setUserState)**(int *state*) |
| void                            | **[setVisible](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)**(bool *visible*) |
| QString                         | **[text](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)**() const |
| Qt::LayoutDirection             | **[textDirection](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection)**() const |
| QList<QTextLayout::FormatRange> | **[textFormats](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormats)**() const |
| QTextList *                     | **[textList](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textList)**() const |
| QTextBlockUserData *            | **[userData](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#userData)**() const |
| int                             | **[userState](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#userState)**() const |
| bool                            | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QTextBlock &*other*) const |
| bool                            | **[operator<](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt)**(const QTextBlock &*other*) const |
| QTextBlock &                    | **[operator=](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QTextBlock &*other*) |
| bool                            | **[operator==](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QTextBlock &*other*) const |

## 详细说明

文本块将文本块或段落封装在[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。QTextBlock 提供对 QTextDocuments 的块/段落结构的只读访问。如果您想实现自己的布局以实现视觉表示，那么它主要有用。[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，或者如果您想迭代文档并以您自己的自定义格式写出内容。

文本块由其父文档创建。如果您需要创建新的文本块，或者在检查文档内容时修改文档的内容，请使用由[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)反而。

每个文本块位于一个特定的位置[position](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#position)（） 在一个[document](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#document)()。块的内容可以通过使用获得[text](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)（） 功能。这[length](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#length)() 函数确定文档中块的大小（包括格式字符）。块的视觉属性由其文本决定[layout](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layout)（）， 它是[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)() 及其[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

这[next](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)（） 和[previous](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)() 函数可以在迭代过程中不通过其他方式修改文档的情况下，对文档中的连续有效块进行迭代。请注意，虽然块是按顺序返回的，但相邻块可能来自文档结构中的不同位置。可以通过调用来确定块的有效性[isValid](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)()。

QTextBlock 提供比较运算符，以便更轻松地使用块：[operator==](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)() 比较两个块是否相等，[operator!=](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)() 比较两个块是否不相等，并且[operator<](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt)() 确定同一文档中的一个块是否在另一个块之前。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\T\QTextBlock\QTextBlock\qtextblock-sequence.png)

**也可以看看**[QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTextFragment](https://doc-qt-io.translate.goog/qt-6/qtextfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### QTextBlock::Iterator

Qt 风格的同义词[QTextBlock::iterator](https://doc-qt-io.translate.goog/qt-6/qtextblock-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QTextBlock::QTextBlock(const QTextBlock &*other*)

复制*other*文本块的属性为此文本块。

### [QTextBlock::iterator](https://doc-qt-io.translate.goog/qt-6/qtextblock-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBlock::begin() const

返回指向文本块开头的文本块迭代器。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBlock::blockFormat() const

返回[QTextBlockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblockformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)描述特定于块的属性。

**也可以看看**[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)()。

### int QTextBlock::blockFormatIndex() const

返回文本块格式的文档内部块格式列表的索引。

**也可以看看**[QTextDocument::allFormats](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allFormats)()。

### int QTextBlock::blockNumber() const

返回此块的编号，如果块无效，则返回 -1。

**也可以看看**[QTextCursor::blockNumber](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockNumber)()。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBlock::charFormat() const

返回[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)描述块的字符格式。将文本插入空块时将使用块的字符格式。

**也可以看看**[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### int QTextBlock::charFormatIndex() const

返回文本块字符格式的文档内部字符格式列表的索引。

**也可以看看**[QTextDocument::allFormats](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#allFormats)()。

### void QTextBlock::clearLayout()

清除[QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于布局和显示块的内容。

**也可以看看**[layout](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layout)()。

### bool QTextBlock::contains(int *position*) const

`true`如果给定则返回*position*位于文本块内；否则返回`false`.

### const [QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextBlock::document() const

返回此文本块所属的文本文档，或者`nullptr`如果该文本块不属于任何文档。

### [QTextBlock::iterator](https://doc-qt-io.translate.goog/qt-6/qtextblock-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBlock::end() const

返回指向文本块末尾的文本块迭代器。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)(),[next](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)（）， 和[previous](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)()。

### int QTextBlock::firstLineNumber() const

返回此块的第一行号，如果块无效，则返回 -1。除非布局支持，否则行号与块号相同。

**也可以看看**[QTextBlock::blockNumber](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockNumber)()。

### bool QTextBlock::isValid() const

返回`true`此文本块是否有效；否则返回`false`.

### bool QTextBlock::isVisible() const

返回`true`块是否可见；否则返回`false`.

**也可以看看**[setVisible](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。

### [QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextBlock::layout() const

返回[QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于布局和显示块的内容。

请注意，返回的[QTextLayout](https://doc-qt-io.translate.goog/qt-6/qtextlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象只能通过 documentChanged 实现进行修改[QAbstractTextDocumentLayout](https://doc-qt-io.translate.goog/qt-6/qabstracttextdocumentlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类。从外部应用的任何更改都会导致未定义的行为。

**也可以看看**[clearLayout](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearLayout)()。

### int QTextBlock::length() const

返回块的长度（以字符为单位）。

**注意：**返回的长度包括所有格式字符，例如换行符。

**也可以看看**[text](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)(),[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)（）， 和[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### int QTextBlock::lineCount() const

返回行数。并非所有文档布局都支持此功能。

**也可以看看**[setLineCount](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLineCount)()。

### QTextBlock QTextBlock::next() const

返回文档中此块之后的文本块，如果这是最后一个文本块，则返回空文本块。

请注意，下一个块可能位于与该块不同的帧或表中。

**也可以看看**[previous](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#previous)(),[begin](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（）， 和[end](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### int QTextBlock::position() const

返回文档中块的第一个字符的索引。

### QTextBlock QTextBlock::previous() const

返回文档中此块之前的文本块，如果这是第一个文本块，则返回空文本块。

请注意，前一个块可能位于与该块不同的帧或表中。

**也可以看看**[next](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#next)(),[begin](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（）， 和[end](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### int QTextBlock::revision() const

返回块修订版。

**也可以看看**[setRevision](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRevision)（） 和[QTextDocument::revision](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revision)()。

### void QTextBlock::setLineCount(int *count*)

将行数设置为*count*。

**也可以看看**[lineCount](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lineCount)()。

### void QTextBlock::setRevision(int *rev*)

将块修订版设置为*rev*。

**也可以看看**[revision](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revision)（） 和[QTextDocument::revision](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#revision)()。

### void QTextBlock::setUserData([QTextBlockUserData](https://doc-qt-io.translate.goog/qt-6/qtextblockuserdata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*)

附上给定的*data*对象到文本块。

[QTextBlockUserData](https://doc-qt-io.translate.goog/qt-6/qtextblockuserdata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可用于存储自定义设置。所有权被传递给底层文本文档，即提供的[QTextBlockUserData](https://doc-qt-io.translate.goog/qt-6/qtextblockuserdata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果相应的文本块被删除，对象也会被删除。用户数据对象不存储在撤消历史记录中，因此在撤消文本块的删除后它将不可用。

例如，如果您在 IDE 中编写编程编辑器，您可能希望让用户在代码中为集成调试器直观地设置断点。在编程编辑器中，一行文本通常对应一个[QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这[QTextBlockUserData](https://doc-qt-io.translate.goog/qt-6/qtextblockuserdata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)接口允许开发人员存储每个数据[QTextBlock](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，例如用户在源代码的哪些行中设置了断点。当然这也可以存储在外部，但是通过将其存储在内部[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，例如，当用户删除关联行时，它将自动删除。这实际上只是将自定义信息存储在[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不使用自定义属性[QTextFormat](https://doc-qt-io.translate.goog/qt-6/qtextformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)这会影响撤消/重做堆栈。

**也可以看看**[userData](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#userData)()。

### void QTextBlock::setUserState(int *state*)

存储指定的*state*文本块中的整数值。这可能很有用，例如在语法突出显示中存储文本解析状态。

**也可以看看**[userState](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#userState)()。

### void QTextBlock::setVisible(bool *visible*)

将块的可见性设置为*visible*。

**也可以看看**[isVisible](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBlock::text() const

以纯文本形式返回块的内容。

**也可以看看**[length](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#length)(),[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)（）， 和[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### [Qt::LayoutDirection](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum) QTextBlock::textDirection() const

返回解析后的文本方向。

如果块没有明确的方向设置，它将解析块内容的方向。返回任一[Qt::LeftToRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum)或者[Qt::RightToLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum)。

**也可以看看**[QTextFormat::layoutDirection](https://doc-qt-io.translate.goog/qt-6/qtextformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection)(),[QString::isRightToLeft](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRightToLeft)（）， 和[Qt::LayoutDirection](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextLayout::FormatRange](https://doc-qt-io.translate.goog/qt-6/qtextlayout-formatrange.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QTextBlock::textFormats() const

以连续范围列表的形式返回块的文本格式选项[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。在范围边界内插入文本时，将使用范围的字符格式。

**也可以看看**[charFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#charFormat)（） 和[blockFormat](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#blockFormat)()。

### [QTextList](https://doc-qt-io.translate.goog/qt-6/qtextlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextBlock::textList() const

如果该块代表一个列表项，则返回该项所属的列表；否则返回`nullptr`.

### [QTextBlockUserData](https://doc-qt-io.translate.goog/qt-6/qtextblockuserdata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextBlock::userData() const

返回一个指向a的指针[QTextBlockUserData](https://doc-qt-io.translate.goog/qt-6/qtextblockuserdata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，如果已设置[setUserData](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setUserData)(), 或`nullptr`.

**也可以看看**[setUserData](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setUserData)()。

### int QTextBlock::userState() const

返回之前设置的整数值[setUserState](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setUserState)() 或 -1。

**也可以看看**[setUserState](https://doc-qt-io.translate.goog/qt-6/qtextblock.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setUserState)()。

### bool QTextBlock::operator!=(const QTextBlock &*other*) const

如果`true`此文本块与*other*文本块。

### bool QTextBlock::operator<(const QTextBlock &*other*) const

`true`如果此文本块出现在*other*文档中的文本块。

### QTextBlock &QTextBlock::operator=(const QTextBlock &*other*)

分配*other*文本块到此文本块。

### bool QTextBlock::operator==(const QTextBlock &*other*) const

返回`true`此文本块是否与*other*文本块。