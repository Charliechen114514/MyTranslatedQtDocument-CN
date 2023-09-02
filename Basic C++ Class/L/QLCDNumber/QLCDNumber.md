#  QLCDNumber Class

QLCDNumber 小部件显示带有类似于 LCD 的数字的数字。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QLCDNumber>                                       |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlcdnumber-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[Mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Mode-enum)** { Hex, Dec, Oct, Bin } |
| ---- | ------------------------------------------------------------ |
| enum | **[SegmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SegmentStyle-enum)** { Outline, Filled, Flat } |

## 特性

| **[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount-prop)** : int**[intValue](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#intValue-prop)** : int**[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)** : Mode | **[segmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#segmentStyle-prop)** : SegmentStyle**[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)** : bool**[value](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)** : double |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                          | **[QLCDNumber](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLCDNumber)**(QWidget **parent* = nullptr) |
| ------------------------ | ------------------------------------------------------------ |
|                          | **[QLCDNumber](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLCDNumber-1)**(uint *numDigits*, QWidget **parent* = nullptr) |
| virtual                  | **[~QLCDNumber](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QLCDNumber)**() |
| bool                     | **[checkOverflow](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkOverflow)**(double *num*) const |
| bool                     | **[checkOverflow](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkOverflow-1)**(int *num*) const |
| int                      | **[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount)**() const |
| int                      | **[intValue](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#intValue-prop)**() const |
| QLCDNumber::Mode         | **[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)**() const |
| QLCDNumber::SegmentStyle | **[segmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#segmentStyle-prop)**() const |
| void                     | **[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)**(int *numDigits*) |
| void                     | **[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)**(QLCDNumber::Mode) |
| void                     | **[setSegmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#segmentStyle-prop)**(QLCDNumber::SegmentStyle) |
| bool                     | **[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)**() const |
| double                   | **[value](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**() const |

## 重载的函数

| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
|               |                                                              |

## 公共槽

| void | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)**(const QString &*s*) |
| ---- | ------------------------------------------------------------ |
| void | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display-1)**(int *num*) |
| void | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display-2)**(double *num*) |
| void | **[setBinMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBinMode)**() |
| void | **[setDecMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDecMode)**() |
| void | **[setHexMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHexMode)**() |
| void | **[setOctMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOctMode)**() |
| void | **[setSmallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)**(bool) |

## 信号

| void | **[overflow](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overflow)**() |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 重载的事件

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent *) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\L\QLCDNumber\QLCDNumber\windows-lcdnumber.png)

它可以显示几乎任何大小的数字。它可以显示十进制、十六进制、八进制或二进制数。使用以下方式可以轻松连接到数据源[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)() 槽，它被重载以采用五种参数类型中的任何一种。

还有用于更换底座的插槽[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)() 和小数点[setSmallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()。

QLCDNumber 发出[overflow](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overflow)() 当要求显示超出其范围的内容时发出信号。范围由下式设定[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)（）， 但[setSmallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()也对其有影响。如果显示设置为十六进制、八进制或二进制，则显示该值的等效整数。

这些数字和其他符号可以显示：0/O、1、2、3、4、5/S、6、7、8、9/g、减号、小数点、A、B、C、D、E、 F、h、H、L、o、P、r、u、U、Y、冒号、度数符号（在字符串中指定为单引号）和空格。QLCDNumber 用空格替换非法字符。

尽管可以使用以下命令检索数值，但无法检索 QLCDNumber 对象的内容[value](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()。如果您确实需要文本，我们建议您连接提供信号的信号[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)() 插槽也到另一个插槽并将值存储在那里。

顺便说一句，QLCDNumber 是 Qt 中最古老的部分，其根源可以追溯到 QLCD 上的 BASIC 程序。[Sinclair Spectrum](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://www.nvg.ntnu.no/sinclair/computers/zxspectrum/zxspectrum.htm)。

**也可以看看**[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Digital Clock Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-digitalclock-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Tetrix Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-tetrix-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QLCDNumber::Mode

此类型决定数字的显示方式。

| 持续的            | 价值 | 描述     |
| ----------------- | ---- | -------- |
| `QLCDNumber::Hex` | `0`  | 十六进制 |
| `QLCDNumber::Dec` | `1`  | 十进制   |
| `QLCDNumber::Oct` | `2`  | 八进制   |
| `QLCDNumber::Bin` | `3`  | 二进制   |

如果显示设置为十六进制、八进制或二进制，则显示该值的等效整数。

### enum QLCDNumber::SegmentStyle

该类型决定了视觉外观[QLCDNumber](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)小部件。

| 持续的                | 价值 | 描述                                 |
| --------------------- | ---- | ------------------------------------ |
| `QLCDNumber::Outline` | `0`  | 给出填充背景颜色的凸起段。           |
| `QLCDNumber::Filled`  | `1`  | 给出填充有 windowText 颜色的凸起段。 |
| `QLCDNumber::Flat`    | `2`  | 给出填充有 windowText 颜色的平面段。 |

## 财产文件

### digitCount : int

该属性保存当前显示的位数

对应于当前的位数。如果[QLCDNumber::smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)为 false，小数点占一位。

默认情况下，该属性的值为 5。

**访问功能：**

| int  | **[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount)**() const |
| ---- | ------------------------------------------------------------ |
| void | **[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)**(int *numDigits*) |

**也可以看看**[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)。

### intValue : int

该属性保存显示的值四舍五入到最接近的整数

该属性对应于 LCDNumber 显示的当前值最接近的整数。这是用于十六进制、八进制和二进制模式的值。

如果显示的值不是数字，则该属性的值为 0。

默认情况下，此属性包含值 0。

**访问功能：**

| int  | **intValue**() const                                         |
| ---- | ------------------------------------------------------------ |
| void | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)**(const QString &*s*) |
| void | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display-1)**(int *num*) |
| void | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display-2)**(double *num*) |

### mode : [Mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Mode-enum)

该属性保存当前显示模式（数字基数）

对应于当前显示模式，为`Bin`、`Oct`、`Dec`（默认）和之一`Hex`。`Dec`模式可以显示浮点值，其他模式显示等效的整数。

**访问功能：**

| QLCDNumber::Mode | **mode**() const              |
| ---------------- | ----------------------------- |
| void             | **setMode**(QLCDNumber::Mode) |

**也可以看看**[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)(),[setHexMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHexMode)(),[setDecMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDecMode)(),[setOctMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOctMode)（）， 和[setBinMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBinMode)()。

### segmentStyle : [SegmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SegmentStyle-enum)

该属性保存 LCDNumber 的样式

|           风格           |            结果            |
| :----------------------: | :------------------------: |
|        `Outline`         | 产生填充背景颜色的凸起部分 |
| `Filled`（这是默认值）。 | 产生填充前景色的凸起部分。 |
|          `Flat`          | 生成填充前景色的平坦片段。 |

`Outline`并将`Filled`另外使用[QPalette::light](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#light)（） 和[QPalette::dark](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dark)() 用于阴影效果。

**访问功能：**

| QLCDNumber::SegmentStyle | **segmentStyle**() const                      |
| ------------------------ | --------------------------------------------- |
| void                     | **setSegmentStyle**(QLCDNumber::SegmentStyle) |

### smallDecimalPoint : bool

该属性保存小数点的样式

如果为 true，则小数点绘制在两个数字位置之间。否则，它占据自己的数字位置，即在数字位置绘制。默认为 false。

当在数字之间绘制小数点时，数字之间的间距会稍微变宽。

**访问功能：**

| bool | **smallDecimalPoint**() const  |
| ---- | ------------------------------ |
| void | **setSmallDecimalPoint**(bool) |

**也可以看看**[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)。

### value : double

该属性保存显示的值

该属性对应于 LCDNumber 显示的当前值。

如果显示的值不是数字，则该属性的值为 0。

默认情况下，此属性包含值 0。

**访问功能：**

| double | **value**() const                                            |
| ------ | ------------------------------------------------------------ |
| void   | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)**(const QString &*s*) |
| void   | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display-1)**(int *num*) |
| void   | **[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display-2)**(double *num*) |

## 成员函数文档

### `[explicit]`QLCDNumber::QLCDNumber([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个 LCD 数字，设置位数为 5，基数为小数，小数点模式为“小”，框架样式为凸起框。这[segmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#segmentStyle-prop)() 设置为`Outline`.

这*parent*参数被传递给[QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)（） 和[setSmallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()。

### `[explicit]`QLCDNumber::QLCDNumber([uint](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uint-typedef) *numDigits*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个 LCD 数字，将位数设置为*numDigits*，基数为小数，小数点模式为“小”，框架样式为凸起框。这[segmentStyle](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#segmentStyle-prop)() 设置为`Filled`.

这*parent*参数被传递给[QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)（） 和[setSmallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()。

### `[virtual]`QLCDNumber::~QLCDNumber()

破坏 LCD 编号。

### bool QLCDNumber::checkOverflow(double *num*) const

返回`true`如果*num*太大，无法完整展示；否则返回`false`.

**也可以看看**[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)(),[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount)（）， 和[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()。

### bool QLCDNumber::checkOverflow(int *num*) const

这是一个过载功能。

返回`true`如果*num*太大，无法完整展示；否则返回`false`.

**也可以看看**[display](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#display)(),[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount)（）， 和[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()。

### int QLCDNumber::digitCount() const

返回当前的位数。

**注意：**属性 DigitCount 的 Getter 函数。

**也可以看看**[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)()。

### `[slot]`void QLCDNumber::display(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*s*)

显示字符串所代表的数字*s*。

该版本的函数忽略[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)（） 和[smallDecimalPoint](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#smallDecimalPoint-prop)()。

这些数字和其他符号可以显示：0/O、1、2、3、4、5/S、6、7、8、9/g、减号、小数点、A、B、C、D、E、 F、h、H、L、o、P、r、u、U、Y、冒号、度数符号（在字符串中指定为单引号）和空格。[QLCDNumber](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用空格替换非法字符。

**注意：**属性的 Setter 函数[intValue](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#intValue-prop)。属性的 Setter 函数[value](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。

### `[slot]`void QLCDNumber::display(int *num*)

这是一个过载功能。

显示号码*num*。

**注意：**属性的 Setter 函数[intValue](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#intValue-prop)。属性的 Setter 函数[value](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。

### `[slot]`void QLCDNumber::display(double *num*)

这是一个过载功能。

显示号码*num*。

**注意：**属性的 Setter 函数[intValue](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#intValue-prop)。属性的 Setter 函数[value](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。

### `[override virtual protected]`bool QLCDNumber::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QFrame::event](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### `[signal]`void QLCDNumber::overflow()

每当[QLCDNumber](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)要求显示太大的数字或太长的字符串。

它永远不会由[setDigitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDigitCount)()。

### `[override virtual protected]`void QLCDNumber::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QFrame::paintEvent](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *）。

### `[slot]`void QLCDNumber::setBinMode()

通话[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)（垃圾桶）。提供方便（例如，用于将按钮连接到它）。

**也可以看看**[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)(),[setHexMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHexMode)(),[setDecMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDecMode)(),[setOctMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOctMode)（）， 和[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)()。

### `[slot]`void QLCDNumber::setDecMode()

通话[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)（十二月）。提供方便（例如，用于将按钮连接到它）。

**也可以看看**[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)(),[setHexMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHexMode)(),[setOctMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOctMode)(),[setBinMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBinMode)（）， 和[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)()。

### void QLCDNumber::setDigitCount(int *numDigits*)

将当前位数设置为*numDigits*。必须在 0..99 范围内。

**注意：**属性的 Setter 函数[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount)。

**也可以看看**[digitCount](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#digitCount)()。

### `[slot]`void QLCDNumber::setHexMode()

通话[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)（十六进制）。提供方便（例如，用于将按钮连接到它）。

**也可以看看**[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)(),[setDecMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDecMode)(),[setOctMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOctMode)(),[setBinMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBinMode)（）， 和[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)()。

### `[slot]`void QLCDNumber::setOctMode()

通话[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)（十月）。提供方便（例如，用于将按钮连接到它）。

**也可以看看**[setMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)(),[setHexMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHexMode)(),[setDecMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDecMode)(),[setBinMode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBinMode)（）， 和[mode](https://doc-qt-io.translate.goog/qt-6/qlcdnumber.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mode-prop)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QLCDNumber::sizeHint() const

重新实现：[QFrame::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。