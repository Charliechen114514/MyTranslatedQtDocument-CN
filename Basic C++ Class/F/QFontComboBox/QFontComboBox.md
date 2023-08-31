 

# QFontComboBox Class

QFontComboBox 小部件是一个组合框，可让用户选择字体系列。[更多的...](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QFontComboBox>                                    |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QComboBox](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qfontcombobox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[FontFilter](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontFilter-enum)** { AllFonts, ScalableFonts, NonScalableFonts, MonospacedFonts, ProportionalFonts } |
| ----- | ------------------------------------------------------------ |
| flags | **[FontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontFilter-enum)** |

## 特性

- **[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont-prop)** : QFont
- **[fontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFilters-prop)** : FontFilters
- **[writingSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writingSystem-prop)** : QFontDatabase::WritingSystem

## 公共函数

|                              | **[QFontComboBox](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFontComboBox)**(QWidget **parent* = nullptr) |
| ---------------------------- | ------------------------------------------------------------ |
| virtual                      | **[~QFontComboBox](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QFontComboBox)**() |
| QFont                        | **[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont-prop)**() const |
| std::optional<QFont>         | **[displayFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFont)**(const QString &*fontFamily*) const |
| QFontComboBox::FontFilters   | **[fontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFilters-prop)**() const |
| QString                      | **[sampleTextForFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sampleTextForFont)**(const QString &*fontFamily*) const |
| QString                      | **[sampleTextForSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sampleTextForSystem)**(QFontDatabase::WritingSystem *writingSystem*) const |
| void                         | **[setDisplayFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDisplayFont)**(const QString &*fontFamily*, const QFont &*font*) |
| void                         | **[setFontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFilters-prop)**(QFontComboBox::FontFilters *filters*) |
| void                         | **[setSampleTextForFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSampleTextForFont)**(const QString &*fontFamily*, const QString &*sampleText*) |
| void                         | **[setSampleTextForSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSampleTextForSystem)**(QFontDatabase::WritingSystem *writingSystem*, const QString &*sampleText*) |
| void                         | **[setWritingSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writingSystem-prop)**(QFontDatabase::WritingSystem) |
| QFontDatabase::WritingSystem | **[writingSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writingSystem-prop)**() const |

## 重载的各个函数

| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
|               |                                                              |

## 公共槽

| void | **[setCurrentFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont-prop)**(const QFont &*f*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 信号

| void | **[currentFontChanged](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFontChanged)**(const QFont &*font*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 重载的protected function

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

​		该组合框填充了按字母顺序排列的字体系列名称列表，例如 Arial、Helvetica 和 Times New Roman。尽可能使用实际字体显示姓氏。对于诸如 Symbol 之类的字体，其名称无法在字体本身中表示，字体示例将显示在系列名称旁边。

QFontComboBox 经常在工具栏中使用，与[QComboBox](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于控制字体大小和两个[QToolButton](https://doc-qt-io.translate.goog/qt-6/qtoolbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)s 表示粗体和斜体。

当用户选择新字体时，[currentFontChanged](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFontChanged)除了发出 () 信号之外[currentIndexChanged](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndexChanged)()。

称呼[setWritingSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writingSystem-prop)() 告诉 QFontComboBox 仅显示支持给定书写系统的字体，以及[setFontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFilters-prop)() 过滤掉某些类型的字体，例如不可缩放字体或等宽字体。

![Windows Vista 上 QFontComboBox 的屏幕截图](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\F\QFontComboBox\QFontComboBox\windowsvista-fontcombobox.png)

**可以查阅**[QComboBox](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFontInfo](https://doc-qt-io.translate.goog/qt-6/qfontinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFontMetrics](https://doc-qt-io.translate.goog/qt-6/qfontmetrics.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFontDatabase](https://doc-qt-io.translate.goog/qt-6/qfontdatabase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Character Map Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-charactermap-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### 枚举 QFontComboBox:: FontFilter 标志 QFontComboBox:: FontFilters

此枚举可用于仅在字体组合框中显示某些类型的字体。

| 持续的                             | 价值  | 描述             |
| ---------------------------------- | ----- | ---------------- |
| `QFontComboBox::AllFonts`          | `0`   | 显示所有字体     |
| `QFontComboBox::ScalableFonts`     | `0x1` | 显示可缩放字体   |
| `QFontComboBox::NonScalableFonts`  | `0x2` | 显示不可缩放字体 |
| `QFontComboBox::MonospacedFonts`   | `0x4` | 显示等宽字体     |
| `QFontComboBox::ProportionalFonts` | `0x8` | 显示比例字体     |

FontFilters 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <FontFilter> 的类型定义。它存储 FontFilter 值的 OR 组合。

## 属性

### currentFont : [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存当前选择的字体

**访问功能：**

| QFont | **currentFont**() const              |
| ----- | ------------------------------------ |
| void  | **setCurrentFont**(const QFont &*f*) |

**通知器信号：**

| void | **[currentFontChanged](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFontChanged)**(const QFont &*font*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**可以查阅**[currentIndex](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)和[currentText](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentText-prop)。

### fontFilters : [FontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FontFilter-enum)

该属性保存组合框的过滤器

默认情况下，列出所有字体。

**访问功能：**

| QFontComboBox::FontFilters | **fontFilters**() const                                  |
| -------------------------- | -------------------------------------------------------- |
| void                       | **setFontFilters**(QFontComboBox::FontFilters *filters*) |

**可以查阅**[writingSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writingSystem-prop)。

### writingSystem : [QFontDatabase::WritingSystem](https://doc-qt-io.translate.goog/qt-6/qfontdatabase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WritingSystem-enum)

此属性保存用作组合框过滤器的书写系统

如果*script*是[QFontDatabase::Any](https://doc-qt-io.translate.goog/qt-6/qfontdatabase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WritingSystem-enum)（默认），列出所有字体。

**访问功能：**

| QFontDatabase::WritingSystem | **writingSystem**() const                          |
| ---------------------------- | -------------------------------------------------- |
| void                         | **setWritingSystem**(QFontDatabase::WritingSystem) |

**可以查阅**[fontFilters](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontFilters-prop)。

## 成员函数文档

### `[explicit]`QFontComboBox::QFontComboBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个字体组合框*parent*。

### `[virtual]`QFontComboBox::~QFontComboBox()

销毁组合框。

### `[signal]`void QFontComboBox::currentFontChanged(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

每当当前字体发生变化时，都会发出此信号*font*。

**注意：**属性的通知程序信号[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont-prop)。

**可以查阅**[currentFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentFont-prop)。

### `[since 6.3]`std::optional<[QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QFontComboBox::displayFont(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fontFamily*) const

返回用于显示给定的字体（如果设置）*fontFamily*（当组合打开时）。

该功能是在 Qt 6.3 中引入的。

**可以查阅**[setDisplayFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDisplayFont)()。

### `[override virtual protected]`bool QFontComboBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QComboBox::event](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[since 6.3]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontComboBox::sampleTextForFont(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fontFamily*) const

返回给定字体名称（当组合打开时）之后显示的示例文本*fontFamily*。

该功能是在 Qt 6.3 中引入的。

**可以查阅**[setSampleTextForFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSampleTextForFont)()。

### `[since 6.3]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontComboBox::sampleTextForSystem([QFontDatabase::WritingSystem](https://doc-qt-io.translate.goog/qt-6/qfontdatabase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WritingSystem-enum) *writingSystem*) const

返回给定字体名称（当组合打开时）之后显示的示例文本*writingSystem*。

该功能是在 Qt 6.3 中引入的。

**可以查阅**[setSampleTextForSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSampleTextForSystem)()。

### `[since 6.3]`void QFontComboBox::setDisplayFont(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fontFamily*, const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

设置*font*用于显示给定的*fontFamily*（当组合打开时）。

该功能是在 Qt 6.3 中引入的。

**可以查阅**[displayFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFont)()。

### `[since 6.3]`void QFontComboBox::setSampleTextForFont(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fontFamily*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sampleText*)

设置*sampleText*显示在给定的字体名称之后（当组合打开时）*fontFamily*。

使用此函数给出的示例文本优先于使用[setSampleTextForSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSampleTextForSystem)()。

该功能是在 Qt 6.3 中引入的。

**可以查阅**[sampleTextForFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sampleTextForFont)()。

### `[since 6.3]`void QFontComboBox::setSampleTextForSystem([QFontDatabase::WritingSystem](https://doc-qt-io.translate.goog/qt-6/qfontdatabase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WritingSystem-enum) *writingSystem*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sampleText*)

设置*sampleText*显示在给定的字体名称之后（当组合打开时）*writingSystem*。

给出的示例文本为[setSampleTextForFont](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSampleTextForFont)() 优先。

该功能是在 Qt 6.3 中引入的。

**可以查阅**[sampleTextForSystem](https://doc-qt-io.translate.goog/qt-6/qfontcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sampleTextForSystem)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFontComboBox::sizeHint() const

重新实现：[QComboBox::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。