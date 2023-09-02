#  QTextBrowser Class

QTextBrowser 类提供了具有超文本导航功能的富文本浏览器。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QTextBrowser>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextbrowser-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextBrowser 是[富文本处理 API](https://doc-qt-io.translate.goog/qt-6/richtext-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 特性

| **[modified](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modified-prop)** : const bool**[openExternalLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openExternalLinks-prop)** : bool**[openLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openLinks-prop)** : bool**[readOnly](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)** : const bool | **[searchPaths](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths-prop)** : QStringList**[source](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)** : QUrl**[sourceType](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sourceType-prop)** : const QTextDocument::ResourceType**[undoRedoEnabled](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#undoRedoEnabled-prop)** : const bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                             | **[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextBrowser)**(QWidget **parent* = nullptr) |
| --------------------------- | ------------------------------------------------------------ |
| int                         | **[backwardHistoryCount](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backwardHistoryCount)**() const |
| void                        | **[clearHistory](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearHistory)**() |
| int                         | **[forwardHistoryCount](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forwardHistoryCount)**() const |
| QString                     | **[historyTitle](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#historyTitle)**(int *i*) const |
| QUrl                        | **[historyUrl](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#historyUrl)**(int *i*) const |
| bool                        | **[isBackwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBackwardAvailable)**() const |
| bool                        | **[isForwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isForwardAvailable)**() const |
| bool                        | **[openExternalLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openExternalLinks-prop)**() const |
| bool                        | **[openLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openLinks-prop)**() const |
| QStringList                 | **[searchPaths](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths-prop)**() const |
| void                        | **[setOpenExternalLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openExternalLinks-prop)**(bool *open*) |
| void                        | **[setOpenLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openLinks-prop)**(bool *open*) |
| void                        | **[setSearchPaths](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths-prop)**(const QStringList &*paths*) |
| QUrl                        | **[source](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)**() const |
| QTextDocument::ResourceType | **[sourceType](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sourceType-prop)**() const |

## 重载的函数

| virtual QVariant | **[loadResource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)**(int *type*, const QUrl &*name*) override |
| ---------------- | ------------------------------------------------------------ |
|                  |                                                              |

## 公共槽

| virtual void | **[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)**() |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)**() |
| virtual void | **[home](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)**() |
| virtual void | **[reload](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reload)**() |
| void         | **[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)**(const QUrl &*url*, QTextDocument::ResourceType *type* = QTextDocument::UnknownResource) |

## 信号

| void | **[anchorClicked](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchorClicked)**(const QUrl &*link*) |
| ---- | ------------------------------------------------------------ |
| void | **[backwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backwardAvailable)**(bool *available*) |
| void | **[forwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forwardAvailable)**(bool *available*) |
| void | **[highlighted](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#highlighted)**(const QUrl &*link*) |
| void | **[historyChanged](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#historyChanged)**() |
| void | **[sourceChanged](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sourceChanged)**(const QUrl &*src*) |

## protected function

| virtual void | **[doSetSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#doSetSource)**(const QUrl &*url*, QTextDocument::ResourceType *type* = QTextDocument::UnknownResource) |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重载的protected function

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **ev*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **ev*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **e*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **e*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **e*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **e*) override |

## 详细说明

这个类扩展了[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（在只读模式下），添加一些导航功能，以便用户可以跟踪超文本文档中的链接。

如果您想为用户提供可编辑的富文本编辑器，请使用[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。如果您想要一个没有超文本导航的文本浏览器，请使用[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并使用[QTextEdit::setReadOnly](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readOnly-prop)() 禁用编辑。如果您只需要显示一小段富文本使用[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### 文档来源及内容

的内容[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)设置为[setHtml](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#html-prop)（） 或者[setPlainText](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPlainText)()，但 QTextBrowser 也实现了[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 函数，使得可以使用命名文档作为源文本。在搜索路径列表和当前文档工厂的目录中查找该名称。

如果文档名称以锚点结尾（例如， " `#anchor"`），则文本浏览器会自动滚动到该位置（使用[scrollToAnchor](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToAnchor)())。当用户点击超链接时，浏览器将调用[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 本身以链接的`href`值作为参数。您可以通过连接到来跟踪当前源[sourceChanged](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sourceChanged)（） 信号。

### 导航

QTextBrowser提供[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 和[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)() 插槽可用于实现后退和前进按钮。这[home](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)() 槽将文本设置为显示的第一个文档。这[anchorClicked](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchorClicked)当用户单击锚点时，会发出 () 信号。要覆盖浏览器的默认导航行为，请调用[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 函数在连接到该信号的槽中提供新的文档文本。

如果要加载存储在 Qt 资源系统中的文档，请使用`qrc`URL 中的方案来加载。例如，对于文档资源路径，`:/docs/index.html`请使用`qrc:/docs/index.html`以下 URL 作为 URL：[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)()。

**也可以看看**[QTextEdit](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTextDocument](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### `[read-only]`modified : const bool

该属性保存文本浏览器的内容是否被修改

### openExternalLinks : bool

指定是否[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)应该使用自动打开到外部源的链接[QDesktopServices::openUrl](https://doc-qt-io.translate.goog/qt-6/qdesktopservices.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openUrl)() 而不是发出[anchorClicked](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchorClicked)信号。如果链接的方案既不是 file 也不是 qrc，则链接被视为外部链接。

默认值为 false。

**访问功能：**

| bool | **openExternalLinks**() const         |
| ---- | ------------------------------------- |
| void | **setOpenExternalLinks**(bool *open*) |

### openLinks : bool

该属性指定是否[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)应自动打开用户尝试通过鼠标或键盘激活的链接。

无论该房产的价值如何[anchorClicked](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anchorClicked)信号始终发出。

默认值是true。

**访问功能：**

| bool | **openLinks**() const         |
| ---- | ----------------------------- |
| void | **setOpenLinks**(bool *open*) |

### readOnly : const bool

该属性保存文本浏览器是否是只读的

默认情况下，该属性为`true`。

### searchPaths : [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存文本浏览器用来查找支持内容的搜索路径

[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此列表来查找图像和文档。

默认情况下，此属性包含一个空字符串列表。

**访问功能：**

| QStringList | **searchPaths**() const                        |
| ----------- | ---------------------------------------------- |
| void        | **setSearchPaths**(const QStringList &*paths*) |

### source : [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存显示文档的名称。

如果未显示任何文档或来源未知，则该 URL 无效。

设置该属性时[QTextBrowser](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)尝试在路径中查找具有指定名称的文档[searchPaths](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths-prop)当前源的属性和目录，除非该值是绝对文件路径。它还检查可选锚点并相应地滚动文档

如果文档中的第一个标签是`<qt type=detail>`，则该文档将显示为弹出窗口，而不是浏览器窗口本身中的新文档。否则，文档将在文本浏览器中正常显示，其中文本设置为指定文档的内容[QTextDocument::setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)（） 或者[QTextDocument::setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMarkdown)()，具体取决于文件名是否以任何已知的 Markdown 文件扩展名结尾。

如果您想避免自动类型检测并显式指定类型，请调用[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 而不是设置此属性。

默认情况下，此属性包含一个空 URL。

**访问功能：**

| QUrl | **source**() const                                           |
| ---- | ------------------------------------------------------------ |
| void | **[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)**(const QUrl &*url*, QTextDocument::ResourceType *type* = QTextDocument::UnknownResource) |

### `[read-only]`sourceType : const [QTextDocument::ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)

该属性保存显示文档的类型

这是[QTextDocument::UnknownResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)如果没有显示文档或者源类型未知。否则，它保存检测到的类型，或指定的类型[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)（） 被称为。

**访问功能：**

| QTextDocument::ResourceType | **sourceType**() const |
| --------------------------- | ---------------------- |
|                             |                        |

### undoRedoEnabled : const bool

该属性保存文本浏览器是否支持撤消/重做操作

默认情况下，该属性为`false`。

## 成员函数文档

### `[explicit]`QTextBrowser::QTextBrowser([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的 QTextBrowser 及其父级*parent*。

### `[signal]`void QTextBrowser::anchorClicked(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*link*)

当用户单击锚点时会发出此信号。传入锚点引用的 URL*link*。

请注意，浏览器将自动处理导航到由*link*除非[openLinks](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openLinks-prop)属性设置为 false 或者您调用[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 在一个已连接的槽中。该机制用于覆盖浏览器的默认导航功能。

### `[virtual slot]`void QTextBrowser::backward()

将显示的文档更改为通过导航链接构建的文档列表中的上一个文档。如果没有先前的文档，则不执行任何操作。

**也可以看看**[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)（） 和[backwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backwardAvailable)()。

### `[signal]`void QTextBrowser::backwardAvailable(bool *available*)

当可用时会发出此信号[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 变化。*available*当用户位于[home](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)(); 否则就是真的。

### int QTextBrowser::backwardHistoryCount() const

返回历史记录中向后的位置数。

### void QTextBrowser::clearHistory()

清除访问过的文档的历史记录并禁用向前和向后导航。

**也可以看看**[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 和[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)()。

### `[virtual protected]`void QTextBrowser::doSetSource(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*url*, [QTextDocument::ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum) *type* = QTextDocument::UnknownResource)

尝试在给定的位置加载文档*url*与指定的*type*。

[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)() 调用 doSetSource。在 Qt 5 中，[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)（常量[QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)&url) 是虚拟的。在 Qt 6 中，doSetSource() 是虚拟的，因此可以在子类中重写它。

### `[override virtual protected]`bool QTextBrowser::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QAbstractScrollArea::event](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`bool QTextBrowser::focusNextPrevChild(bool *next*)

重新实现：[QTextEdit::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QTextBrowser::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QTextEdit::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *e）。

### `[virtual slot]`void QTextBrowser::forward()

将显示的文档更改为通过导航链接构建的文档列表中的下一个文档。如果没有下一个文档，则不执行任何操作。

**也可以看看**[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 和[forwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forwardAvailable)()。

### `[signal]`void QTextBrowser::forwardAvailable(bool *available*)

当可用时会发出此信号[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)（） 变化。*available*用户导航后为 true[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)当用户导航或离开时 () 和 false[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)()。

### int QTextBrowser::forwardHistoryCount() const

返回历史记录中前进的位置数。

### `[signal]`void QTextBrowser::highlighted(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*link*)

当用户选择但未激活文档中的锚点时，会发出此信号。传入锚点引用的 URL*link*。

### `[signal]`void QTextBrowser::historyChanged()

当历史记录发生变化时，会发出此信号。

**也可以看看**[historyTitle](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#historyTitle)（） 和[historyUrl](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#historyUrl)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBrowser::historyTitle(int *i*) const

返回[documentTitle](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentTitle-prop)HistoryItem 的 ()。

|  输入   |                             返回                             |
| :-----: | :----------------------------------------------------------: |
| *i*< 0  | [backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 历史 |
| *i*== 0 | 当前，参见[QTextBrowser::source](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)() |
| *i*> 0  | [forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)（） 历史 |

```
backaction.setToolTip(browser.historyTitle(-1));
forwardaction.setToolTip(browser.historyTitle(+1));
```

### [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBrowser::historyUrl(int *i*) const

返回 HistoryItem 的 url。

|  输入   |                             返回                             |
| :-----: | :----------------------------------------------------------: |
| *i*< 0  | [backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 历史 |
| *i*== 0 | 当前，参见[QTextBrowser::source](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)() |
| *i*> 0  | [forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)（） 历史 |

### `[virtual slot]`void QTextBrowser::home()

将显示的文档更改为历史记录中的第一个文档。

### bool QTextBrowser::isBackwardAvailable() const

返回`true`文本浏览器是否可以使用以下命令在文档历史记录中后退[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)()。

**也可以看看**[backwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backwardAvailable)（） 和[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)()。

### bool QTextBrowser::isForwardAvailable() const

返回`true`文本浏览器是否可以使用以下命令在文档历史记录中前进[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)()。

**也可以看看**[forwardAvailable](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forwardAvailable)（） 和[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)()。

### `[override virtual protected]`void QTextBrowser::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QTextEdit::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

事件*ev*用于提供以下键盘快捷键：

|     按键     |                             行动                             |
| :----------: | :----------------------------------------------------------: |
| Alt+向左箭头 | [backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)() |
|  Alt+右箭头  | [forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)() |
|  Alt+向上键  | [home](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)() |

### `[override virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextBrowser::loadResource(int *type*, const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

重新实现：[QTextEdit::loadResource](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#loadResource)（int 类型，const QUrl 和名称）。

加载文档时以及针对文档中的每个图像调用此函数。这*type*表示要加载的资源类型。无效[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果资源无法加载则返回。

默认实现忽略*type*并尝试通过解释来定位资源*name*作为文件名。如果它不是绝对路径，它会尝试在路径中查找该文件[searchPaths](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths-prop)属性并与当前源位于同一目录中。成功后，结果是[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)存储一个[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与文件的内容。

如果重新实现这个函数，可以返回其他的[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类型。下表显示了根据资源类型支持的变体类型：

|                           资源类型                           | [QMetaType::Type](https://doc-qt-io.translate.goog/qt-6/qmetatype.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum) |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [QTextDocument::HtmlResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum) | [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| [QTextDocument::ImageResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum) | [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| [QTextDocument::StyleSheetResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum) | [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| [QTextDocument::MarkdownResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum) | [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

### `[override virtual protected]`void QTextBrowser::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QTextEdit::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QTextBrowser::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QTextEdit::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QTextBrowser::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QTextEdit::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QTextBrowser::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QTextEdit::paintEvent](https://doc-qt-io.translate.goog/qt-6/qtextedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[virtual slot]`void QTextBrowser::reload()

重新加载当前设置的源。

### `[slot]`void QTextBrowser::setSource(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*url*, [QTextDocument::ResourceType](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum) *type* = QTextDocument::UnknownResource)

尝试在给定的位置加载文档*url*与指定的*type*。

如果*type*是[UnknownResource](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ResourceType-enum)（默认），将检测文档类型：即，如果 url 以 ,`.md`或`.mkd`扩展名结尾`.markdown`，则将通过以下方式加载文档[QTextDocument::setMarkdown](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMarkdown)(); 否则它将通过加载[QTextDocument::setHtml](https://doc-qt-io.translate.goog/qt-6/qtextdocument.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHtml)()。可以通过指定绕过此检测*type*明确地。

**注意：**属性的 Setter 函数[source](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)。

**也可以看看**[source](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#source-prop)()。

### `[signal]`void QTextBrowser::sourceChanged(const [QUrl](https://doc-qt-io.translate.goog/qt-6/qurl.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*src*)

当源发生变化时会发出此信号，*src*成为新的来源。

调用时会以编程方式发生源更改[setSource](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSource)(),[forward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forward)(),[backward](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backward)（） 或者[home](https://doc-qt-io.translate.goog/qt-6/qtextbrowser.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)() 或当用户单击链接或按下等效的按键序列时。