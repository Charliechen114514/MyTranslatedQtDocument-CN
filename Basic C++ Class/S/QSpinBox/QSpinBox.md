 QSpinBox Class

QSpinBox 类提供了一个旋转框小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QSpinBox>                                          |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractSpinBox](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qspinbox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

| **[cleanText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanText-prop)** : const QString**[displayIntegerBase](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayIntegerBase-prop)** : int**[maximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)** : int**[minimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)** : int**[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)** : QString | **[singleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)** : int**[stepType](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)** : StepType**[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)** : QString**[value](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)** : int |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                            | **[QSpinBox](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QSpinBox)**(QWidget **parent* = nullptr) |
| -------------------------- | ------------------------------------------------------------ |
| virtual                    | **[~QSpinBox](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QSpinBox)**() |
| QString                    | **[cleanText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanText-prop)**() const |
| int                        | **[displayIntegerBase](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayIntegerBase-prop)**() const |
| int                        | **[maximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)**() const |
| int                        | **[minimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)**() const |
| QString                    | **[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)**() const |
| void                       | **[setDisplayIntegerBase](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayIntegerBase-prop)**(int *base*) |
| void                       | **[setMaximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)**(int *max*) |
| void                       | **[setMinimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)**(int *min*) |
| void                       | **[setPrefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)**(const QString &*prefix*) |
| void                       | **[setRange](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)**(int *minimum*, int *maximum*) |
| void                       | **[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)**(int *val*) |
| void                       | **[setStepType](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStepType)**(QAbstractSpinBox::StepType *stepType*) |
| void                       | **[setSuffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)**(const QString &*suffix*) |
| int                        | **[singleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)**() const |
| QAbstractSpinBox::StepType | **[stepType](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)**() const |
| QString                    | **[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)**() const |
| int                        | **[value](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**() const |

## 公共槽

| void | **[setValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)**(int *val*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 信号

| void | **[textChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)**(const QString &*text*) |
| ---- | ------------------------------------------------------------ |
| void | **[valueChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)**(int *i*) |

## protected函数

| virtual QString | **[textFromValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)**(int *value*) const |
| --------------- | ------------------------------------------------------------ |
| virtual int     | **[valueFromText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)**(const QString &*text*) const |

## 重载的protected函数

| virtual bool              | **[event](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| ------------------------- | ------------------------------------------------------------ |
| virtual void              | **[fixup](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)**(QString &*input*) const override |
| virtual QValidator::State | **[validate](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)**(QString &*text*, int &*pos*) const override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\S\QSpinBox\QSpinBox\windows-spinbox.png)

QSpinBox 设计用于处理整数和离散值集（例如月份名称）；使用[QDoubleSpinBox](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对于浮点值。

QSpinBox 允许用户通过单击向上/向下按钮或按键盘上/向下键来选择一个值，以增加/减少当前显示的值。用户还可以手动输入该值。旋转框支持整数值，但可以扩展以使用不同的字符串[validate](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)(),[textFromValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)（） 和[valueFromText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)()。

每次值改变时 QSpinBox 都会发出[valueChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)（） 和[textChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)() 信号，前者提供一个 int，后者提供一个[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这[textChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textChanged)() 信号同时提供值[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)()。当前值可以通过以下方式获取[value](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)() 并设置为[setValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()。

单击向上/向下按钮或使用键盘加速器的向上和向下箭头将以大小为单位增加或减少当前值[singleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。如果你想改变这种行为，你可以重新实现虚函数[stepBy](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepBy)()。可以使用构造函数之一设置最小值和最大值以及步长，并且可以稍后使用以下命令进行更改[setMinimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)(),[setMaximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)（） 和[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。

大多数旋转框都是定向的，但QSpinBox也可以作为圆形旋转框操作，即如果范围是0-99并且当前值为99，则单击“向上”将给出0，如果[wrapping](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wrapping-prop)() 设置为 true。使用[setWrapping](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wrapping-prop)() 如果你想要循环行为。

显示的值可以在前面和后面添加任意字符串，表示货币或测量单位等。看[setPrefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[setSuffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)()。旋转框中的文本是通过以下方式检索的[text](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()（其中包括任何[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)())，或与[cleanText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanText-prop)()（其中没有[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（）， 不[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)() 并且没有前导或尾随空格）。

除了数值范围之外，通常还需要为用户提供特殊的（通常是默认的）选择。看[setSpecialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 了解如何使用 QSpinBox 执行此操作。

### 子类化 QSpinBox

如果使用[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)(),[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)（）， 和[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 没有提供足够的控制，您继承 QSpinBox 并重新实现[valueFromText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)（） 和[textFromValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)()。例如，以下是自定义旋转框的代码，允许用户输入图标大小（例如“32 x 32”）：

```
int IconSizeSpinBox::valueFromText(const QString &text) const
{
    static const QRegularExpression regExp(tr("(\\d+)(\\s*[xx]\\s*\\d+)?"));
    Q_ASSERT(regExp.isValid());

    const QRegularExpressionMatch match = regExp.match(text);
    if (match.isValid())
        return match.captured(1).toInt();
    return 0;
}

QString IconSizeSpinBox::textFromValue(int value) const
{
    return tr("%1 x %1").arg(value);
}
```

请参阅[Icons](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-icons-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)完整源代码的示例。

**也可以看看**[QDoubleSpinBox](https://doc-qt-io.translate.goog/qt-6/qdoublespinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QSlider](https://doc-qt-io.translate.goog/qt-6/qslider.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Spin Boxes Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-spinboxes-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### `[read-only]`cleanText : const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性保存旋转框的文本，不包括任何前缀、后缀、前导或尾随空格。

**访问功能：**

| QString | **cleanText**() const |
| ------- | --------------------- |
|         |                       |

**也可以看看**[text](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop),[QSpinBox::prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)， 和[QSpinBox::suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)。

### displayIntegerBase : int

该属性保存用于显示旋转框值的基数

默认的 displayIntegerBase 值为 10。

**访问功能：**

| int  | **displayIntegerBase**() const        |
| ---- | ------------------------------------- |
| void | **setDisplayIntegerBase**(int *base*) |

**也可以看看**[textFromValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)（） 和[valueFromText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)()。

### maximum : int

该属性保存旋转框的最大值

设置此属性时，如有必要，会调整最小值，以确保范围保持有效。

默认最大值为 99。

**访问功能：**

| int  | **maximum**() const       |
| ---- | ------------------------- |
| void | **setMaximum**(int *max*) |

**也可以看看**[setRange](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)（） 和[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)。

### minimum : int

该属性保存旋转框的最小值

设置该属性时[maximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)如有必要，进行调整以确保范围保持有效。

默认最小值为 0。

**访问功能：**

| int  | **minimum**() const       |
| ---- | ------------------------- |
| void | **setMinimum**(int *min*) |

**也可以看看**[setRange](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRange)（） 和[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)。

### prefix : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存旋转框的前缀

前缀添加到显示值的开头。典型用途是显示计量单位或货币符号。例如：

```
sb->setPrefix("$");
```

要关闭前缀显示，请将此属性设置为空字符串。默认没有前缀。当以下情况时不显示前缀[value](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)()==[minimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（） 和[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 已设定。

如果未设置前缀，则 prefix() 返回空字符串。

**访问功能：**

| QString | **prefix**() const                     |
| ------- | -------------------------------------- |
| void    | **setPrefix**(const QString &*prefix*) |

**也可以看看**[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)(),[setSuffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)(),[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)（）， 和[setSpecialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)()。

### singleStep : int

该属性保存步长值

当用户使用箭头更改旋转框的值时，该值将按 singleStep 的量递增/递减。默认值为 1。设置小于 0 的 singleStep 值不会执行任何操作。

**访问功能：**

| int  | **singleStep**() const       |
| ---- | ---------------------------- |
| void | **setSingleStep**(int *val*) |

### stepType : [StepType](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StepType-enum)

该属性保存步骤类型。

步长类型可以是单步长或自适应小数步长。

**访问功能：**

| QAbstractSpinBox::StepType | **stepType**() const                                         |
| -------------------------- | ------------------------------------------------------------ |
| void                       | **[setStepType](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStepType)**(QAbstractSpinBox::StepType *stepType*) |

### suffix : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存旋转框的后缀

后缀附加到显示值的末尾。典型用途是显示计量单位或货币符号。例如：

```
sb->setSuffix(" km");
```

要关闭后缀显示，请将此属性设置为空字符串。默认没有后缀。不显示后缀[minimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)（） 如果[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 已设定。

如果未设置后缀，则 suffix() 返回空字符串。

**访问功能：**

| QString | **suffix**() const                     |
| ------- | -------------------------------------- |
| void    | **setSuffix**(const QString &*suffix*) |

**也可以看看**[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)(),[setPrefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)(),[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)（）， 和[setSpecialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)()。

### value : int

该属性保存旋转框的值

setValue() 将发出[valueChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)() 如果新值与旧值不同。value 属性有第二个通知器信号，其中包括旋转框的前缀和后缀。

**访问功能：**

| int  | **value**() const       |
| ---- | ----------------------- |
| void | **setValue**(int *val*) |

**通知器信号：**

| void | **[valueChanged](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueChanged)**(int *i*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 成员函数文档

### `[explicit]`QSpinBox::QSpinBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个旋转框，最小值为 0，最大值为 99，步长值为 1。该值最初设置为 0。它的父级为*parent*。

**也可以看看**[setMinimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)(),[setMaximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)（）， 和[setSingleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)()。

### `[virtual]`QSpinBox::~QSpinBox()

析构函数。

### `[override virtual protected]`bool QSpinBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::event](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`void QSpinBox::fixup([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*input*) const

重新实现：[QAbstractSpinBox::fixup(QString &input) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)。

### void QSpinBox::setRange(int *minimum*, int *maximum*)

方便的功能来设置*minimum*， 和*maximum*单个函数调用的值。

```
setRange(minimum, maximum);
```

相当于：

```
setMinimum(minimum);
setMaximum(maximum);
```

**也可以看看**[minimum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimum-prop)和[maximum](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximum-prop)。

### void QSpinBox::setStepType([QAbstractSpinBox::StepType](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StepType-enum) *stepType*)

将旋转框的步骤类型设置为*stepType*，这是单步或自适应小数步。

自适应十进制步长是指步长会不断调整为低于当前值的十次方[value](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。因此，当值为 1100 时，步进设置为 100，因此步进一次会将其增加到 1200。对于 1200，步进会将其变为 1300。对于负值，从 -1100 步进会变为 -1200。

处理边缘情况时会考虑步进方向，因此从 100 逐步下降会将值变为 99，而不是 90。因此，先上升后下降（反之亦然）总是落在起始值；99 -> 100 -> 99。

设置此项将导致旋转框忽略[singleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)，尽管它被保留以便[singleStep](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#singleStep-prop)如果稍后关闭自适应小数步长，则该功能生效。

**注意：**属性的 Setter 函数[stepType](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)。

**也可以看看**[stepType](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepType-prop)()。

### `[signal]`void QSpinBox::textChanged(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

每当旋转框的文本更改时都会发出此信号。新文本被传入*text*和[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)（） 和[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)()。

### `[virtual protected]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QSpinBox::textFromValue(int *value*) const

每当旋转框需要显示给定的内容时，就会使用此虚拟函数*value*。默认实现返回一个包含以下内容的字符串*value*使用标准方式打印[QWidget::locale](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#locale-prop)().toString()，但删除千位分隔符，除非[setGroupSeparatorShown](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showGroupSeparator-prop)() 已设定。重新实现可能会返回任何内容。（请参阅详细说明中的示例。）

笔记：[QSpinBox](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不调用此函数[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)() 并且两者都不是[prefix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prefix-prop)() 也不[suffix](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix-prop)() 应包含在返回值中。

如果你重新实现这个，你可能还需要重新实现[valueFromText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)（） 和[validate](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)()

**也可以看看**[valueFromText](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#valueFromText)(),[validate](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)（）， 和[QLocale::groupSeparator](https://doc-qt-io.translate.goog/qt-6/qlocale.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupSeparator)()。

### `[override virtual protected]`[QValidator::State](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum) QSpinBox::validate([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, int &*pos*) const

重新实现：[QAbstractSpinBox::validate(QString &input, int &pos) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)。

### `[signal]`void QSpinBox::valueChanged(int *i*)

每当旋转框的值发生更改时，都会发出此信号。传入新值的整数值*i*。

**注意：**属性的通知程序信号[value](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#value-prop)。

### `[virtual protected]`int QSpinBox::valueFromText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*) const

每当需要解释时，旋转框都会使用此虚拟函数*text*由用户输入作为值。

需要以非数字方式显示旋转框值的子类需要重新实现此函数。

笔记：[QSpinBox](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)把手[specialValueText](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#specialValueText-prop)（） 分别地; 这个函数只关心其他值。

**也可以看看**[textFromValue](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromValue)（） 和[validate](https://doc-qt-io.translate.goog/qt-6/qspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)()。