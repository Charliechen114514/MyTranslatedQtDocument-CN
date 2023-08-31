#  QDoubleSpinBox Class

QDoubleSpinBox 类提供了一个采用双精度数的旋转框小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QDoubleSpinBox>                                   |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractSpinBox](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

| **[cleanText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanText-prop)** : const QString**[decimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)** : int**[maximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)** : double**[minimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)** : double**[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)** : QString | **[singleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)** : double**[stepType](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)** : StepType**[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)** : QString**[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)** : double |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                            | **[QDoubleSpinBox](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDoubleSpinBox)**(QWidget **parent* = nullptr) |
| -------------------------- | ------------------------------------------------------------ |
| virtual                    | **[~QDoubleSpinBox](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDoubleSpinBox)**() |
| QString                    | **[cleanText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanText-prop)**() const |
| int                        | **[decimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)**() const |
| double                     | **[maximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)**() const |
| double                     | **[minimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)**() const |
| QString                    | **[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)**() const |
| void                       | **[setDecimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)**(int *prec*) |
| void                       | **[setMaximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)**(double *max*) |
| void                       | **[setMinimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)**(double *min*) |
| void                       | **[setPrefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)**(const QString &*prefix*) |
| void                       | **[setRange](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)**(double *minimum*, double *maximum*) |
| void                       | **[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)**(double *val*) |
| void                       | **[setStepType](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStepType)**(QAbstractSpinBox::StepType *stepType*) |
| void                       | **[setSuffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)**(const QString &*suffix*) |
| double                     | **[singleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)**() const |
| QAbstractSpinBox::StepType | **[stepType](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)**() const |
| QString                    | **[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)**() const |
| virtual QString            | **[textFromValue](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)**(double *value*) const |
| double                     | **[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**() const |
| virtual double             | **[valueFromText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)**(const QString &*text*) const |

## 重载的公共函数

| virtual void              | **[fixup](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)**(QString &*input*) const override |
| ------------------------- | ------------------------------------------------------------ |
| virtual QValidator::State | **[validate](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)**(QString &*text*, int &*pos*) const override |

## 公共槽

| void | **[setValue](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**(double *val*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 信号

| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**(const QString &*text*) |
| ---- | ------------------------------------------------------------ |
| void | **[valueChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)**(double *d*) |

## 详细说明

QDoubleSpinBox 允许用户通过单击向上和向下按钮或按键盘上的向上或向下来增加或减少当前显示的值来选择值。用户还可以手动输入该值。旋转框支持双精度值，但可以扩展为使用不同的字符串[validate](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)(),[textFromValue](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)（） 和[valueFromText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)()。

每次值改变时 QDoubleSpinBox 都会发出[valueChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)（） 和[textChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)() 信号，前者提供一个 double，后者提供一个[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这[textChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)() 信号同时提供值[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)()。当前值可以通过以下方式获取[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)() 并设置为[setValue](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()。

注意：QDoubleSpinBox 会对数字进行四舍五入，以便可以以当前精度显示它们。在小数设置为 2 的 QDoubleSpinBox 中，调用[setValue](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)(2.555) 将导致[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)() 返回 2.56。

单击向上和向下按钮或使用键盘加速器的向上和向下箭头将以大小为步长增加或减少当前值[singleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。如果你想改变这种行为，你可以重新实现虚函数[stepBy](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepBy)()。可以使用构造函数之一设置最小值和最大值以及步长，并且可以稍后使用以下命令进行更改[setMinimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)(),[setMaximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)（） 和[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。旋转框的默认精度为 2 位小数，但可以使用以下命令更改此精度：[setDecimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)()。

大多数旋转框都是方向性的，但QDoubleSpinBox也可以作为圆形旋转框操作，即如果范围是0.0-99.9并且当前值为99.9，则单击“向上”将给出0[wrapping](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wrapping-prop)() 设置为 true。使用[setWrapping](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wrapping-prop)() 如果你想要循环行为。

显示的值可以在前面和后面添加任意字符串，表示货币或测量单位等。看[setPrefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[setSuffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)()。旋转框中的文本是通过以下方式检索的[text](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()（其中包括任何[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)())，或与[cleanText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanText-prop)()（其中没有[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（）， 不[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)() 并且没有前导或尾随空格）。

除了数值范围之外，通常还需要为用户提供特殊的（通常是默认的）选择。看[setSpecialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 了解如何使用 QDoubleSpinBox 执行此操作。

**注意：**除了最终的前缀和后缀内容之外，QDoubleSpinBox 的显示值仅限于 18 个字符。此限制用于保持双旋转框即使在值非常大的情况下也可用。

**也可以看看**[QSpinBox](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QSlider](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Spin Boxes Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-spinboxes-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### `[read-only]`cleanText : const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性保存旋转框的文本，不包括任何前缀、后缀、前导或尾随空格。

**访问功能：**

| QString | **cleanText**() const |
| ------- | --------------------- |
|         |                       |

**也可以看看**[text](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop),[QDoubleSpinBox::prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)， 和[QDoubleSpinBox::suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)。

### decimals : int

该属性保存旋转框的精度（以小数为单位）

设置旋转框将使用多少位小数来显示和解释双精度数。

**警告：**最大值*decimals*由于 double 类型的限制，为 DBL_MAX_10_EXP + DBL_DIG（即 323）。

注意：更改此属性可能会导致最大值、最小值和值发生变化。

**访问功能：**

| int  | **decimals**() const        |
| ---- | --------------------------- |
| void | **setDecimals**(int *prec*) |

### maximum : double

该属性保存旋转框的最大值

设置该属性时[minimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)必要时进行调整，以确保范围保持有效。

默认最大值为 99.99。

注意：最大值将四舍五入以匹配小数属性。

**访问功能：**

| double | **maximum**() const          |
| ------ | ---------------------------- |
| void   | **setMaximum**(double *max*) |

**也可以看看**[decimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)和[setRange](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)()。

### minimum : double

该属性保存旋转框的最小值

设置该属性时[maximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)如有必要，进行调整以确保范围保持有效。

默认最小值为 0.0。

注意：最小值将四舍五入以匹配小数属性。

**访问功能：**

| double | **minimum**() const          |
| ------ | ---------------------------- |
| void   | **setMinimum**(double *min*) |

**也可以看看**[decimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop),[setRange](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)（）， 和[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)。

### prefix : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存旋转框的前缀

前缀添加到显示值的开头。典型用途是显示计量单位或货币符号。例如：

```
spinbox->setPrefix("$");
```

要关闭前缀显示，请将此属性设置为空字符串。默认没有前缀。当以下情况时不显示前缀[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()==[minimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（） 和[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 已设定。

如果未设置前缀，则 prefix() 返回空字符串。

**访问功能：**

| QString | **prefix**() const                     |
| ------- | -------------------------------------- |
| void    | **setPrefix**(const QString &*prefix*) |

**也可以看看**[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)(),[setSuffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)(),[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)（）， 和[setSpecialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)()。

### singleStep : double

该属性保存步长值

当用户使用箭头更改旋转框的值时，该值将按 singleStep 的量递增/递减。默认值为 1.0。将 singleStep 值设置为小于 0 不会产生任何作用。

**访问功能：**

| double | **singleStep**() const          |
| ------ | ------------------------------- |
| void   | **setSingleStep**(double *val*) |

### stepType : [StepType](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StepType-enum)

该属性保存步骤类型。

步长类型可以是单步长或自适应小数步长。

**访问功能：**

| QAbstractSpinBox::StepType | **stepType**() const                                         |
| -------------------------- | ------------------------------------------------------------ |
| void                       | **[setStepType](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStepType)**(QAbstractSpinBox::StepType *stepType*) |

### suffix : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存旋转框的后缀

后缀附加到显示值的末尾。典型用途是显示计量单位或货币符号。例如：

```
spinbox->setSuffix(" km");
```

要关闭后缀显示，请将此属性设置为空字符串。默认没有后缀。不显示后缀[minimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（） 如果[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 已设定。

如果未设置后缀，则 suffix() 返回空字符串。

**访问功能：**

| QString | **suffix**() const                     |
| ------- | -------------------------------------- |
| void    | **setSuffix**(const QString &*suffix*) |

**也可以看看**[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)(),[setPrefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)(),[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)（）， 和[setSpecialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)()。

### value : double

该属性保存旋转框的值

setValue() 将发出[valueChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)() 如果新值与旧值不同。value 属性有第二个通知器信号，其中包括旋转框的前缀和后缀。

注意：该值将被四舍五入，以便可以使用当前设置的小数位显示。

**访问功能：**

| double | **value**() const          |
| ------ | -------------------------- |
| void   | **setValue**(double *val*) |

**通知器信号：**

| void | **[valueChanged](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)**(double *d*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[decimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)。

## 成员函数文档

### `[explicit]`QDoubleSpinBox::QDoubleSpinBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个旋转框，最小值为 0.0，最大值为 99.99，步长值为 1.0，精度为 2 位小数。该值最初设置为 0.00。旋转框有给定的*parent*。

**也可以看看**[setMinimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)(),[setMaximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)（）， 和[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。

### `[virtual]`QDoubleSpinBox::~QDoubleSpinBox()

析构函数。

### `[override virtual]`void QDoubleSpinBox::fixup([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*input*) const

重新实现：[QAbstractSpinBox::fixup(QString &input) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)。

### void QDoubleSpinBox::setRange(double *minimum*, double *maximum*)

方便的功能来设置*minimum*和*maximum*单个函数调用的值。

注意：最大值和最小值将四舍五入以匹配小数属性。

```
setRange(minimum, maximum);
```

相当于：

```
setMinimum(minimum);
setMaximum(maximum);
```

**也可以看看**[minimum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)和[maximum](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)。

### void QDoubleSpinBox::setStepType([QAbstractSpinBox::StepType](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StepType-enum) *stepType*)

将旋转框的步骤类型设置为*stepType*，这是单步或自适应小数步。

自适应十进制步长是指步长会不断调整为低于当前值的十次方[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。因此，当值为 1100 时，步进设置为 100，因此步进一次会将其增加到 1200。对于 1200，步进会将其变为 1300。对于负值，从 -1100 步进会变为 -1200。

它也适用于任何小数值，0.041 通过步进一次增加到 0.042。

处理边缘情况时会考虑步进方向，因此从 100 逐步下降会将值变为 99，而不是 90。因此，先上升后下降（反之亦然）总是落在起始值；99 -> 100 -> 99。

设置此项将导致旋转框忽略[singleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)，尽管它被保留以便[singleStep](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)如果稍后关闭自适应小数步长，则该功能生效。

**注意：**属性的 Setter 函数[stepType](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)。

**也可以看看**[stepType](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)()。

### `[signal]`void QDoubleSpinBox::textChanged(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

每当旋转框的文本更改时都会发出此信号。新文本被传入*text*和[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)()。

### `[virtual]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDoubleSpinBox::textFromValue(double *value*) const

每当旋转框需要显示给定的内容时，就会使用此虚拟函数*value*。默认实现返回一个包含以下内容的字符串*value*打印使用[QWidget::locale](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#locale-prop)().toString(*value*, `u'f'`,[decimals](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decimals-prop)()) 并将删除千位分隔符，除非[setGroupSeparatorShown](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGroupSeparator-prop)() 已设定。重新实现可能会返回任何内容。

笔记：[QDoubleSpinBox](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不调用此函数[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 并且两者都不是[prefix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)() 也不[suffix](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)() 应包含在返回值中。

如果你重新实现这个，你可能还需要重新实现[valueFromText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)()。

**也可以看看**[valueFromText](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)（） 和[QLocale::groupSeparator](https://doc-qt-io.translate.goog/qt-6/qlocale.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupSeparator)()。

### `[override virtual]`[QValidator::State](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum) QDoubleSpinBox::validate([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, int &*pos*) const

重新实现：[QAbstractSpinBox::validate(QString &input, int &pos) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)。

### `[signal]`void QDoubleSpinBox::valueChanged(double *d*)

每当旋转框的值发生更改时，都会发出此信号。新值传入*d*。

**注意：**属性的通知程序信号[value](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。

### `[virtual]`double QDoubleSpinBox::valueFromText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*) const

每当需要解释时，旋转框都会使用此虚拟函数*text*由用户输入作为值。

需要以非数字方式显示旋转框值的子类需要重新实现此函数。

笔记：[QDoubleSpinBox](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)把手[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)（） 分别地; 这个函数只关心其他值。

**也可以看看**[textFromValue](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)（） 和[validate](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)()。