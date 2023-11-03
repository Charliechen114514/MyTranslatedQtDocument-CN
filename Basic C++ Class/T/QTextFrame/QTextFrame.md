#  QTextFrame Class

QTextFrame 类代表一个框架[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include <QTextFrame>                                        |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:        | QT += gui                                                    |
| Inherits:     | [QTextObject](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QTextTable](https://doc-qt-io.translate.goog/qt-6/qtexttable.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextframe-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextFrame 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
|       | **[Iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Iterator-typedef)** |

## 公共职能

|                      | **[QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextFrame)**(QTextDocument **document*) |
| -------------------- | ------------------------------------------------------------ |
| virtual              | **[~QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTextFrame)**() |
| QTextFrame::iterator | **[begin](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**() const |
| QList<QTextFrame *>  | **[childFrames](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childFrames)**() const |
| QTextFrame::iterator | **[end](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() const |
| QTextCursor          | **[firstCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstCursorPosition)**() const |
| int                  | **[firstPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstPosition)**() const |
| QTextFrameFormat     | **[frameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#frameFormat)**() const |
| QTextCursor          | **[lastCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastCursorPosition)**() const |
| int                  | **[lastPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastPosition)**() const |
| QTextFrame *         | **[parentFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentFrame)**() const |
| void                 | **[setFrameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFrameFormat)**(const QTextFrameFormat &*format*) |

## 详细说明

文本框架提供文档中文本的结构。它们用作其他文档元素的通用容器。框架通常是通过使用创建的[QTextCursor::insertFrame](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertFrame)()。

框架可用于在富文本文档中创建层次结构。每个文档都有一个根框架（[QTextDocument::rootFrame](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootFrame)())，并且根框架下面的每个框架都有一个父框架和一个（可能为空）子框架列表。父框架可以通过以下方式找到[parentFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentFrame)()，以及[childFrames](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childFrames)() 函数提供子框架列表。

每个框架至少包含一个文本块，以使文本光标能够在其中插入新的文档元素。结果，[QTextFrame::iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类用于遍历给定帧内的块和子帧。框架中的第一个和最后一个子元素可以通过以下方式找到[begin](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

帧也有格式（使用指定[QTextFrameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframeformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)) 可以设置为[setFormat](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFormat)() 并阅读[format](https://doc-qt-io.translate.goog/qt-6/qtextobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format)()。

可以获得指向帧内第一个和最后一个有效光标位置的文本光标；使用[firstCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstCursorPosition)（） 和[lastCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastCursorPosition)() 函数用于此目的。文档中框架的范围可以通过以下方式找到[firstPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstPosition)（） 和[lastPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastPosition)()。

您可以使用迭代框架的内容[QTextFrame::iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类：提供对其内部文本块和子框架列表的只读访问。

**也可以看看**[QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### QTextFrame::Iterator

Qt 风格的同义词[QTextFrame::iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### `[explicit]`QTextFrame::QTextFrame([QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **document*)

为文本创建一个新的空框架*document*。

### `[virtual noexcept]`QTextFrame::~QTextFrame()

破坏文本框架。

**警告：**文本框架归文档所有，因此您切勿自行销毁它们。要从文档中删除框架，请使用 删除其内容`QTextCursor`。

### [QTextFrame::iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextFrame::begin() const

返回一个指向框架内第一个文档元素的迭代器。请参阅文档[STL-style-Iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)了解更多信息。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextFrame) *> QTextFrame::childFrames() const

返回框架的子框架的列表（可能为空）。

**也可以看看**[parentFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentFrame)()。

### [QTextFrame::iterator](https://doc-qt-io.translate.goog/qt-6/qtextframe-iterator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextFrame::end() const

返回一个迭代器，该迭代器指向框架内最后一个文档元素之后的位置。请参阅文档[STL-Style Iterators](https://doc-qt-io.translate.goog/qt-6/containers.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stl-style-iterators)了解更多信息。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)()。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextFrame::firstCursorPosition() const

返回框架内的第一个光标位置。

**也可以看看**[lastCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastCursorPosition)(),[firstPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstPosition)（）， 和[lastPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastPosition)()。

### int QTextFrame::firstPosition() const

返回框架内的第一个文档位置。

**也可以看看**[lastPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastPosition)(),[firstCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstCursorPosition)（）， 和[lastCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastCursorPosition)()。

### [QTextFrameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframeformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextFrame::frameFormat() const

返回帧的格式。

**也可以看看**[setFrameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFrameFormat)()。

### [QTextCursor](https://doc-qt-io.translate.goog/qt-6/qtextcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextFrame::lastCursorPosition() const

返回框架内最后一个光标位置。

**也可以看看**[firstCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstCursorPosition)(),[firstPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstPosition)（）， 和[lastPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastPosition)()。

### int QTextFrame::lastPosition() const

返回框架内的最后一个文档位置。

**也可以看看**[firstPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstPosition)(),[firstCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstCursorPosition)（）， 和[lastCursorPosition](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastCursorPosition)()。

### [QTextFrame](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextFrame) *QTextFrame::parentFrame() const

返回框架的父框架。如果该框架是文档的根框架，则返回 0。

**也可以看看**[childFrames](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childFrames)（） 和[QTextDocument::rootFrame](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootFrame)()。

### void QTextFrame::setFrameFormat(const [QTextFrameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframeformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置框架的*format*。

**也可以看看**[frameFormat](https://doc-qt-io.translate.goog/qt-6/qtextframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#frameFormat)()。