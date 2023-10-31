 QProgressBar Class

QProgressBar 小部件提供水平或垂直进度条。[更多的...](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QProgressBar>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qprogressbar-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[Direction](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Direction-enum)** { TopToBottom, BottomToTop } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 特性

| **[alignment](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)** : Qt::Alignment**[format](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format-prop)** : QString**[invertedAppearance](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invertedAppearance-prop)** : bool**[maximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)** : int**[minimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)** : int | **[orientation](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)** : Qt::Orientation**[text](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)** : const QString**[textDirection](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection-prop)** : Direction**[textVisible](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textVisible-prop)** : bool**[value](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)** : int |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                         | **[QProgressBar](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QProgressBar)**(QWidget **parent* = nullptr) |
| ----------------------- | ------------------------------------------------------------ |
| virtual                 | **[~QProgressBar](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QProgressBar)**() |
| Qt::Alignment           | **[alignment](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**() const |
| QString                 | **[format](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format-prop)**() const |
| bool                    | **[invertedAppearance](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invertedAppearance-prop)**() const |
| bool                    | **[isTextVisible](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textVisible-prop)**() const |
| int                     | **[maximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)**() const |
| int                     | **[minimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)**() const |
| Qt::Orientation         | **[orientation](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)**() const |
| void                    | **[resetFormat](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format-prop)**() |
| void                    | **[setAlignment](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**(Qt::Alignment *alignment*) |
| void                    | **[setFormat](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#format-prop)**(const QString &*format*) |
| void                    | **[setInvertedAppearance](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invertedAppearance-prop)**(bool *invert*) |
| void                    | **[setTextDirection](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection-prop)**(QProgressBar::Direction *textDirection*) |
| void                    | **[setTextVisible](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textVisible-prop)**(bool *visible*) |
| virtual QString         | **[text](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)**() const |
| QProgressBar::Direction | **[textDirection](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection-prop)**() const |
| int                     | **[value](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**() const |

## 重新实施公共职能

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共老虎机

| void | **[reset](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)**() |
| ---- | ------------------------------------------------------------ |
| void | **[setMaximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)**(int *maximum*) |
| void | **[setMinimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)**(int *minimum*) |
| void | **[setOrientation](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)**(Qt::Orientation) |
| void | **[setRange](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)**(int *minimum*, int *maximum*) |
| void | **[setValue](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**(int *value*) |

## 信号

| void | **[valueChanged](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)**(int *value*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 受保护的功能

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionProgressBar **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重新实现受保护的功能

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent *) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\P\QProcessBar\QProcessBar\windows-progressbar-1698752885833-1.png)

进度条用于向用户指示操作的进度，并向他们保证应用程序仍在运行。

*进度条使用步骤*的概念。您可以通过指定最小和最大可能的步骤值来设置它，当您稍后给它当前的步骤值时，它将显示已完成的步骤的百分比。百分比的计算方法是除以进度 ([value](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()-[minimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（）） 除以[maximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)()-[minimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)()。

您可以使用以下命令指定最小和最大步数[setMinimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（） 和[setMaximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)。当前步数设置为[setValue](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()。进度条可以倒退到开头[reset](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)()。

如果最小值和最大值均设置为 0，则条形图将显示繁忙指示器而不是步数百分比。例如，当使用 QNetworkAccessManager 下载项目时，当它们无法确定正在下载的项目的大小时，这很有用。

**也可以看看**[QProgressDialog](https://doc-qt-io.translate.goog/qt-6/qprogressdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QProgressBar::Direction

指定读取方向[text](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)对于垂直进度条。

| 持续的                      | 价值 | 描述                   |
| --------------------------- | ---- | ---------------------- |
| `QProgressBar::TopToBottom` | `0`  | 文本顺时针旋转 90 度。 |
| `QProgressBar::BottomToTop` | `1`  | 文本逆时针旋转 90 度。 |

请注意，是否绘制文本取决于样式。目前 CleanLooks 和 Plastique 绘制文本。Mac、Windows 和 WindowsVista 风格则不然。

**也可以看看**[textDirection](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection-prop)。

## 财产文件

### alignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

该属性保存进度条的对齐方式

**访问功能：**

| Qt::Alignment | **alignment**() const                       |
| ------------- | ------------------------------------------- |
| void          | **setAlignment**(Qt::Alignment *alignment*) |

### format : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存用于生成当前文本的字符串

%p - 替换为完成的百分比。%v - 被当前值替换。%m - 替换为总步数。

默认值为“%p%”。

**访问功能：**

| QString | **format**() const                     |
| ------- | -------------------------------------- |
| void    | **setFormat**(const QString &*format*) |
| void    | **resetFormat**()                      |

**也可以看看**[text](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()。

### invertedAppearance : bool

该属性保存进度条是否显示反转的进度

如果此属性为`true`，则进度条沿另一个方向增长（例如从右到左）。默认情况下，进度条不倒转。

**访问功能：**

| bool | **invertedAppearance**() const           |
| ---- | ---------------------------------------- |
| void | **setInvertedAppearance**(bool *invert*) |

**也可以看看**[orientation](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)和[layoutDirection](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection-prop)。

### maximum : int

该属性保存进度条的最大值

设置该属性时，[minimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)如有必要，进行调整以确保范围保持有效。如果当前值超出新范围，进度条将重置[reset](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)()。

**访问功能：**

| int  | **maximum**() const           |
| ---- | ----------------------------- |
| void | **setMaximum**(int *maximum*) |

### minimum : int

该属性保存进度条的最小值

设置该属性时，[maximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)如有必要，进行调整以确保范围保持有效。如果当前值超出新范围，进度条将重置[reset](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)()。

**访问功能：**

| int  | **minimum**() const           |
| ---- | ----------------------------- |
| void | **setMinimum**(int *minimum*) |

### orientation : [Qt::Orientation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)

该属性保存进度条的方向

方向必须是[Qt::Horizontal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)（默认）或[Qt::Vertical](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum)。

**访问功能：**

| Qt::Orientation | **orientation**() const             |
| --------------- | ----------------------------------- |
| void            | **setOrientation**(Qt::Orientation) |

**也可以看看**[invertedAppearance](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invertedAppearance-prop)和[textDirection](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection-prop)。

### `[read-only]`text : const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存进度条显示的描述性文本

返回的文本与进度条中心（或某些样式中的左侧）显示的文本相同。

文本中显示的进度可能小于最小值，表明进度条在设置任何进度之前处于“重置”状态。

在默认实现中，文本要么包含指示到目前为止进度的百分比值，要么为空白，因为进度条处于重置状态。

**访问功能：**

| virtual QString | **text**() const |
| --------------- | ---------------- |
|                 |                  |

### textDirection : [Direction](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Direction-enum)

该属性保存了读取方向[text](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)对于垂直进度条

该属性对水平进度条没有影响。默认情况下，读取方向为[QProgressBar::TopToBottom](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Direction-enum)。

**访问功能：**

| QProgressBar::Direction | **textDirection**() const                                    |
| ----------------------- | ------------------------------------------------------------ |
| void                    | **setTextDirection**(QProgressBar::Direction *textDirection*) |

**也可以看看**[orientation](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#orientation-prop)和[textVisible](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textVisible-prop)。

### textVisible : bool

该属性保存是否应显示当前完成的百分比

该属性可能会被样式忽略（例如，QMacStyle 从不绘制文本）。

**访问功能：**

| bool | **isTextVisible**() const          |
| ---- | ---------------------------------- |
| void | **setTextVisible**(bool *visible*) |

**也可以看看**[textDirection](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection-prop)。

### value : int

该属性保存进度条的当前值

尝试将当前值更改为最小-最大范围之外的值不会对当前值产生任何影响。

**访问功能：**

| int  | **value**() const         |
| ---- | ------------------------- |
| void | **setValue**(int *value*) |

**通知器信号：**

| void | **[valueChanged](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)**(int *value*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 成员函数文档

### `[explicit]`QProgressBar::QProgressBar([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个进度条*parent*。

默认情况下，最小步长值设置为 0，最大步长值设置为 100。

**也可以看看**[setRange](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)()。

### `[virtual noexcept]`QProgressBar::~QProgressBar()

析构函数。

### `[override virtual protected]`bool QProgressBar::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[virtual protected]`void QProgressBar::initStyleOption([QStyleOptionProgressBar](https://doc-qt-io.translate.goog/qt-6/qstyleoptionprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QProgressBar](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionProgressBar](https://doc-qt-io.translate.goog/qt-6/qstyleoptionprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**也可以看看**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QProgressBar::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[override virtual protected]`void QProgressBar::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[slot]`void QProgressBar::reset()

重置进度条。进度条“倒回”并且没有显示任何进度。

### `[slot]`void QProgressBar::setRange(int *minimum*, int *maximum*)

将进度条的最小值和最大值设置为*minimum*和*maximum*分别。

如果*maximum*小于*minimum*,*minimum*成为唯一的合法值。

如果当前值超出新范围，进度条将重置[reset](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)()。

这[QProgressBar](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以使用 setRange(0, 0) 将其设置为未确定状态。

**也可以看看**[minimum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)和[maximum](https://doc-qt-io.translate.goog/qt-6/qprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QProgressBar::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。

### `[signal]`void QProgressBar::valueChanged(int *value*)

当进度条中显示的值发生变化时，会发出此信号。*value*是进度条显示的新值。