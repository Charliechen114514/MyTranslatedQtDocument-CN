#  QGroupBox Class

QGroupBox 小部件提供了一个带有标题的组框框架。[更多的...](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QGroupBox>                                         |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qgroupbox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

| **[alignment](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)** : Qt::Alignment**[checkable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)** : bool**[checked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)** : bool | **[flat](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)** : bool**[title](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#title-prop)** : QString |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|               | **[QGroupBox](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGroupBox)**(QWidget **parent* = nullptr) |
| ------------- | ------------------------------------------------------------ |
|               | **[QGroupBox](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGroupBox-1)**(const QString &*title*, QWidget **parent* = nullptr) |
| virtual       | **[~QGroupBox](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QGroupBox)**() |
| Qt::Alignment | **[alignment](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**() const |
| bool          | **[isCheckable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)**() const |
| bool          | **[isChecked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)**() const |
| bool          | **[isFlat](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)**() const |
| void          | **[setAlignment](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**(int *alignment*) |
| void          | **[setCheckable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)**(bool *checkable*) |
| void          | **[setFlat](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)**(bool *flat*) |
| void          | **[setTitle](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#title-prop)**(const QString &*title*) |
| QString       | **[title](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#title-prop)**() const |

## 重载的公共函数

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
|               |                                                              |

## 公共槽

| void | **[setChecked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)**(bool *checked*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 信号

| void | **[clicked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)**(bool *checked* = false) |
| ---- | ------------------------------------------------------------ |
| void | **[toggled](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toggled)**(bool *on*) |

## protected function

| virtual void | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionGroupBox **option*) const |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 重新实现protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **ev*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[childEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childEvent)**(QChildEvent **c*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **fe*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **event*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **event*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **event*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **e*) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\G\QGroupBox\QGroupBox\windows-groupbox.png)

组框提供框架、顶部标题、键盘快捷键，并在其内部显示各种其他小部件。键盘快捷键将键盘焦点移动到组框的子窗口小部件之一。

QGroupBox 还允许您设置[title](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#title-prop)（通常在构造函数中设置）和标题[alignment](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)。分组框可以[checkable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)。可检查组框中的子窗口小部件是否启用或禁用取决于该组框是否已启用[checked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)。

您可以通过启用以下功能来最大限度地减少组框的空间消耗[flat](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flat-prop)财产。多数情况[styles](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，启用此属性会导致删除框架的左、右和下边缘。

QGroupBox 不会自动布局子部件（通常是[QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)es 或[QRadioButton](https://doc-qt-io.translate.goog/qt-6/qradiobutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)但可以是任何小部件）。下面的例子展示了我们如何设置一个带有布局的QGroupBox：

```
    QGroupBox *groupBox = new QGroupBox(tr("Exclusive Radio Buttons"));

    QRadioButton *radio1 = new QRadioButton(tr("&Radio button 1"));
    QRadioButton *radio2 = new QRadioButton(tr("R&adio button 2"));
    QRadioButton *radio3 = new QRadioButton(tr("Ra&dio button 3"));

    radio1->setChecked(true);

    QVBoxLayout *vbox = new QVBoxLayout;
    vbox->addWidget(radio1);
    vbox->addWidget(radio2);
    vbox->addWidget(radio3);
    vbox->addStretch(1);
    groupBox->setLayout(vbox);
```

**也可以看看**[QButtonGroup](https://doc-qt-io.translate.goog/qt-6/qbuttongroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[Group Box Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-groupbox-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### alignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

该属性保存组框标题的对齐方式。

大多数样式将标题放置在框架的顶部。标题的水平对齐方式可以使用以下列表中的单个值来指定：

- [Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)将标题文本与组框的左侧对齐。
- [Qt::AlignRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)将标题文本与组框的右侧对齐。
- [Qt::AlignHCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)将标题文本与组框的水平中心对齐。

默认对齐方式是[Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

**访问功能：**

| Qt::Alignment | **alignment**() const             |
| ------------- | --------------------------------- |
| void          | **setAlignment**(int *alignment*) |

**也可以看看**[Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

### checkable : bool

该属性保存组框的标题中是否有复选框

如果此属性为`true`，则组框使用复选框代替普通标签来显示其标题。如果选中该复选框，则启用组框的子项；否则，它们将被禁用且无法访问。

默认情况下，组框是不可选中的。

如果为组框启用了此属性，则还将首先检查它以确保其内容已启用。

**访问功能：**

| bool | **isCheckable**() const            |
| ---- | ---------------------------------- |
| void | **setCheckable**(bool *checkable*) |

**也可以看看**[checked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)。

### checked : bool

该属性保存组框是否被选中

如果该组框是可选的，则会显示一个复选框。如果选中该复选框，则启用组框的子项；否则，孩子们将被禁用并且用户无法访问。

默认情况下，还会选中可检查的组框。

**访问功能：**

| bool | **isChecked**() const          |
| ---- | ------------------------------ |
| void | **setChecked**(bool *checked*) |

**通知器信号：**

| void | **[toggled](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toggled)**(bool *on*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[checkable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)。

### flat : bool

该属性保存组框是平涂还是有框架

组框通常由一个周围的框架组成，顶部有一个标题。如果启用此属性，则在大多数样式中仅绘制框架的顶部部分；否则，将绘制整个框架。

默认情况下，该属性被禁用，即，除非明确指定，否则组框不是平面的。

**注意：**在某些样式中，平面和非平面组框具有相似的表示形式，并且可能不像其他样式那样易于区分。

**访问功能：**

| bool | **isFlat**() const       |
| ---- | ------------------------ |
| void | **setFlat**(bool *flat*) |

**也可以看看**[title](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#title-prop)。

### title : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存组框标题文本

如果标题包含与号 ('&') 后跟一个字母，则组框标题文本将具有键盘快捷键。

```
g->setTitle("&User information");
```

在上面的例子中，**Alt+U**将键盘焦点移至组框。请参阅[QShortcut](https://doc-qt-io.translate.goog/qt-6/qshortcut.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mnemonic)有关详细信息的文档（要显示实际的＆符号，请使用“&&”）。

没有默认的标题文本。

**访问功能：**

| QString | **title**() const                    |
| ------- | ------------------------------------ |
| void    | **setTitle**(const QString &*title*) |

**也可以看看**[alignment](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)。

## 成员函数文档

### `[explicit]`QGroupBox::QGroupBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个组框小部件*parent*但没有标题。

### `[explicit]`QGroupBox::QGroupBox(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个组框*title*和*parent*。

### `[virtual]`QGroupBox::~QGroupBox()

销毁组框。

### `[override virtual protected]`void QGroupBox::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### `[override virtual protected]`void QGroupBox::childEvent([QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **c*)

重新实现：[QObject::childEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childEvent)（QChildEvent *事件）。

### `[signal]`void QGroupBox::clicked(bool *checked* = false)

当激活复选框（即，当鼠标光标位于按钮内时按下然后释放）或键入快捷键时，会发出此信号。值得注意的是，如果您调用，*则不会*发出此信号[setChecked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)()。

如果选中该复选框，*checked*是真的; 如果未选中该复选框，则为 false。

**也可以看看**[checkable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop),[toggled](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toggled)（）， 和[checked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)。

### `[override virtual protected]`bool QGroupBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`void QGroupBox::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **fe*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[virtual protected]`void QGroupBox::initStyleOption([QStyleOptionGroupBox](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

初始化*option*与此值[QGroupBox](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当子类需要时，此方法非常有用[QStyleOptionGroupBox](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**也可以看看**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGroupBox::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[override virtual protected]`void QGroupBox::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QGroupBox::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QGroupBox::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QGroupBox::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### `[override virtual protected]`void QGroupBox::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[signal]`void QGroupBox::toggled(bool *on*)

如果组框是可选的，则在切换复选框时会发出此信号。*on*如果选中该复选框，则为 true；否则，它是错误的。

**注意：**属性的通知程序信号[checked](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checked-prop)。

**也可以看看**[checkable](https://doc-qt-io.translate.goog/qt-6/qgroupbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkable-prop)。