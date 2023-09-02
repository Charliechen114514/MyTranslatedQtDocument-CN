#  QFormLayout Class

QFormLayout 类管理输入小部件的表单及其关联的标签。[更多的...](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QFormLayout>                                       |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qformlayout-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| struct | **[TakeRowResult](https://doc-qt-io.translate.goog/qt-6/qformlayout-takerowresult.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ------ | ------------------------------------------------------------ |
| enum   | **[FieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldGrowthPolicy-enum)** { FieldsStayAtSizeHint, ExpandingFieldsGrow, AllNonFixedFieldsGrow } |
| enum   | **[ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum)** { LabelRole, FieldRole, SpanningRole } |
| enum   | **[RowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum)** { DontWrapRows, WrapLongRows, WrapAllRows } |

## 特性

| **[fieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldGrowthPolicy-prop)** : FieldGrowthPolicy**[formAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)** : Qt::Alignment**[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)** : int | **[labelAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelAlignment-prop)** : Qt::Alignment**[rowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)** : RowWrapPolicy**[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)** : int |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                                | **[QFormLayout](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFormLayout)**(QWidget **parent* = nullptr) |
| ------------------------------ | ------------------------------------------------------------ |
| virtual                        | **[~QFormLayout](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QFormLayout)**() |
| void                           | **[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)**(QWidget **label*, QWidget **field*) |
| void                           | **[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow-1)**(QWidget **label*, QLayout **field*) |
| void                           | **[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow-2)**(const QString &*labelText*, QWidget **field*) |
| void                           | **[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow-3)**(const QString &*labelText*, QLayout **field*) |
| void                           | **[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow-4)**(QWidget **widget*) |
| void                           | **[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow-5)**(QLayout **layout*) |
| QFormLayout::FieldGrowthPolicy | **[fieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldGrowthPolicy-prop)**() const |
| Qt::Alignment                  | **[formAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)**() const |
| void                           | **[getItemPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getItemPosition)**(int *index*, int **rowPtr*, QFormLayout::ItemRole **rolePtr*) const |
| void                           | **[getLayoutPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getLayoutPosition)**(QLayout **layout*, int **rowPtr*, QFormLayout::ItemRole **rolePtr*) const |
| void                           | **[getWidgetPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getWidgetPosition)**(QWidget **widget*, int **rowPtr*, QFormLayout::ItemRole **rolePtr*) const |
| int                            | **[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)**() const |
| void                           | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)**(int *row*, QWidget **label*, QWidget **field*) |
| void                           | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow-1)**(int *row*, QWidget **label*, QLayout **field*) |
| void                           | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow-2)**(int *row*, const QString &*labelText*, QWidget **field*) |
| void                           | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow-3)**(int *row*, const QString &*labelText*, QLayout **field*) |
| void                           | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow-4)**(int *row*, QWidget **widget*) |
| void                           | **[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow-5)**(int *row*, QLayout **layout*) |
| bool                           | **[isRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowVisible)**(int *row*) const |
| bool                           | **[isRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowVisible-1)**(QWidget **widget*) const |
| bool                           | **[isRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowVisible-2)**(QLayout **layout*) const |
| QLayoutItem *                  | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)**(int *row*, QFormLayout::ItemRole *role*) const |
| Qt::Alignment                  | **[labelAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelAlignment-prop)**() const |
| QWidget *                      | **[labelForField](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelForField)**(QWidget **field*) const |
| QWidget *                      | **[labelForField](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelForField-1)**(QLayout **field*) const |
| void                           | **[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)**(int *row*) |
| void                           | **[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow-1)**(QWidget **widget*) |
| void                           | **[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow-2)**(QLayout **layout*) |
| int                            | **[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)**() const |
| QFormLayout::RowWrapPolicy     | **[rowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)**() const |
| void                           | **[setFieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldGrowthPolicy-prop)**(QFormLayout::FieldGrowthPolicy *policy*) |
| void                           | **[setFormAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)**(Qt::Alignment *alignment*) |
| void                           | **[setHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)**(int *spacing*) |
| void                           | **[setItem](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItem)**(int *row*, QFormLayout::ItemRole *role*, QLayoutItem **item*) |
| void                           | **[setLabelAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelAlignment-prop)**(Qt::Alignment *alignment*) |
| void                           | **[setLayout](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)**(int *row*, QFormLayout::ItemRole *role*, QLayout **layout*) |
| void                           | **[setRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowVisible)**(int *row*, bool *on*) |
| void                           | **[setRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowVisible-1)**(QWidget **widget*, bool *on*) |
| void                           | **[setRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRowVisible-2)**(QLayout **layout*, bool *on*) |
| void                           | **[setRowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)**(QFormLayout::RowWrapPolicy *policy*) |
| void                           | **[setVerticalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)**(int *spacing*) |
| void                           | **[setWidget](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)**(int *row*, QFormLayout::ItemRole *role*, QWidget **widget*) |
| QFormLayout::TakeRowResult     | **[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)**(int *row*) |
| QFormLayout::TakeRowResult     | **[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow-1)**(QWidget **widget*) |
| QFormLayout::TakeRowResult     | **[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow-2)**(QLayout **layout*) |
| int                            | **[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)**() const |

## 重载的公共职能

| virtual void             | **[addItem](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)**(QLayoutItem **item*) override |
| ------------------------ | ------------------------------------------------------------ |
| virtual int              | **[count](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**() const override |
| virtual Qt::Orientations | **[expandingDirections](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandingDirections)**() const override |
| virtual bool             | **[hasHeightForWidth](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasHeightForWidth)**() const override |
| virtual int              | **[heightForWidth](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#heightForWidth)**(int *width*) const override |
| virtual void             | **[invalidate](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)**() override |
| virtual QLayoutItem *    | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt-1)**(int *index*) const override |
| virtual QSize            | **[minimumSize](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize)**() const override |
| virtual void             | **[setGeometry](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGeometry)**(const QRect &*rect*) override |
| virtual void             | **[setSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpacing)**(int *spacing*) override |
| virtual QSize            | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| virtual int              | **[spacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing)**() const override |
| virtual QLayoutItem *    | **[takeAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeAt)**(int *index*) override |

## 详细说明

QFormLayout 是一个方便的布局类，它以两列形式布局其子级。左列由标签组成，右列由“字段”小部件（行编辑器、旋转框等）组成。

传统上，这种两列表单布局是使用[QGridLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。QFormLayout 是一种更高级别的替代方案，具有以下优点：

- 遵守不同平台的外观和风格指南。

  例如，[macOS Aqua](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://developer.apple.com/library/mac/%23documentation/UserExperience/Conceptual/AppleHIGuidelines/Intro/Intro.html)KDE 指南指定标签应右对齐，而 Windows 和 GNOME 应用程序通常使用左对齐。

- 支持长行换行。

  对于小显示屏的设备，QFormLayout 可以设置为[wrap long rows](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum)，甚至到[wrap all rows](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum)。

- 用于创建标签-字段对的便捷 API。

  这[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)() 重载需要[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和一个[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)* 创建一个[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在幕后自动设置其好友。然后我们可以编写这样的代码：

  ```
  QFormLayout *formLayout = new QFormLayout(this);
  formLayout->addRow(tr("&Name:"), nameLineEdit);
  formLayout->addRow(tr("&Email:"), emailLineEdit);
  formLayout->addRow(tr("&Age:"), ageSpinBox);
  ```

  将此与以下代码进行比较，使用以下代码编写[QGridLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp):

  ```
  QGridLayout *gridLayout = new QGridLayout(this);
  
  nameLabel = new QLabel(tr("&Name:"));
  nameLabel->setBuddy(nameLineEdit);
  
  emailLabel = new QLabel(tr("&Name:"));
  emailLabel->setBuddy(emailLineEdit);
  
  ageLabel = new QLabel(tr("&Name:"));
  ageLabel->setBuddy(ageSpinBox);
  
  gridLayout->addWidget(nameLabel, 0, 0);
  gridLayout->addWidget(nameLineEdit, 0, 1);
  gridLayout->addWidget(emailLabel, 1, 0);
  gridLayout->addWidget(emailLineEdit, 1, 1);
  gridLayout->addWidget(ageLabel, 2, 0);
  gridLayout->addWidget(ageSpinBox, 2, 1);
  ```

下表显示了不同样式的默认外观。

| [QCommonStyle](https://doc-qt-io.translate.goog/qt-6/qcommonstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)派生样式（QPlastiqueStyle 除外） |                           QMac风格                           |                          Q塑料风格                           |                         Qt 扩展样式                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\F\QFormLayout\QFormLayout\qformlayout-win.png) | ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\F\QFormLayout\QFormLayout\qformlayout-mac.png) | ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\F\QFormLayout\QFormLayout\qformlayout-kde.png) | ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\F\QFormLayout\QFormLayout\qformlayout-qpe.png) |
| 用于 Windows、GNOME 和早期版本的 KDE 的传统样式。标签左对齐，扩展字段会增长以填充可用空间。（这通常对应于我们使用两列得到的结果[QGridLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp).) | 风格基于[macOS Aqua](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://developer.apple.com/library/mac/%23documentation/UserExperience/Conceptual/AppleHIGuidelines/Intro/Intro.html)指导方针。标签右对齐，字段不会超出其大小提示，并且表单水平居中。 | 推荐款式[KDE applications](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=http://www.kdedevelopers.org/node/2345)。与 MacStyle 类似，不同之处在于表单左对齐并且所有字段都会增长以填充可用空间。 | Qt 扩展样式的默认样式。标签右对齐，扩展字段增长以填充可用空间，并且为长行启用换行。 |

表单样式也可以通过调用单独覆盖[setLabelAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelAlignment-prop)(),[setFormAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)(),[setFieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldGrowthPolicy-prop)（）， 和[setRowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)()。例如，要在所有平台上模拟 QMacStyle 的表单布局外观，但使用左对齐标签，您可以编写：

```
formLayout->setRowWrapPolicy(QFormLayout::DontWrapRows);
formLayout->setFieldGrowthPolicy(QFormLayout::FieldsStayAtSizeHint);
formLayout->setFormAlignment(Qt::AlignHCenter | Qt::AlignTop);
formLayout->setLabelAlignment(Qt::AlignLeft);
```

**也可以看看**[QGridLayout](https://doc-qt-io.translate.goog/qt-6/qgridlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QBoxLayout](https://doc-qt-io.translate.goog/qt-6/qboxlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QStackedLayout](https://doc-qt-io.translate.goog/qt-6/qstackedlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QFormLayout::FieldGrowthPolicy

该枚举指定可用于控制表单字段增长方式的不同策略。

| 持续的                               | 价值 | 描述                                                         |
| ------------------------------------ | ---- | ------------------------------------------------------------ |
| `QFormLayout::FieldsStayAtSizeHint`  | `0`  | 田野的生长永远不会超出它们的范围[effective size hint](https://doc-qt-io.translate.goog/qt-6/qwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。这是 QMacStyle 的默认设置。 |
| `QFormLayout::ExpandingFieldsGrow`   | `1`  | 具有水平线的字段[size policy](https://doc-qt-io.translate.goog/qt-6/qsizepolicy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的[Expanding](https://doc-qt-io.translate.goog/qt-6/qsizepolicy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Policy-enum)或者[MinimumExpanding](https://doc-qt-io.translate.goog/qt-6/qsizepolicy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Policy-enum)将增长以填充可用空间。其他字段的增长不会超出其有效大小提示。这是 Plastique 的默认策略。 |
| `QFormLayout::AllNonFixedFieldsGrow` | `2`  | 所有具有允许其增长的大小策略的字段都将增长以填充可用空间。这是大多数样式的默认策略。 |

**也可以看看**[fieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldGrowthPolicy-prop)。

### enum QFormLayout::ItemRole

该枚举指定可能出现在一行中的小部件（或其他布局项）的类型。

| 持续的                      | 价值 | 描述                       |
| --------------------------- | ---- | -------------------------- |
| `QFormLayout::LabelRole`    | `0`  | 标签小部件。               |
| `QFormLayout::FieldRole`    | `1`  | 一个字段小部件。           |
| `QFormLayout::SpanningRole` | `2`  | 跨越标签和字段列的小部件。 |

**也可以看看**[itemAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)（） 和[getItemPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getItemPosition)()。

### enum QFormLayout::RowWrapPolicy

该枚举指定可用于控制表单行换行方式的不同策略。

| 持续的                      | 价值 | 描述                                                         |
| --------------------------- | ---- | ------------------------------------------------------------ |
| `QFormLayout::DontWrapRows` | `0`  | 字段始终放置在其标签旁边。这是除 Qt Extended 样式之外的所有样式的默认策略。 |
| `QFormLayout::WrapLongRows` | `1`  | 为标签提供了足够的水平空间以适合最宽的标签，其余空间则分配给字段。如果字段对的最小大小比可用空间宽，则该字段将换行到下一行。这是 Qt Extended 样式的默认策略。 |
| `QFormLayout::WrapAllRows`  | `2`  | 字段始终布置在其标签下方。                                   |

**也可以看看**[rowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)。

## 属性文档

### fieldGrowthPolicy : [FieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldGrowthPolicy-enum)

该属性控制表单字段的增长方式

默认值取决于小部件或应用程序样式。对于 QMacStyle，默认值为[FieldsStayAtSizeHint](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldGrowthPolicy-enum); 为了[QCommonStyle](https://doc-qt-io.translate.goog/qt-6/qcommonstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)派生样式（如 Plastique 和 Windows），默认为[ExpandingFieldsGrow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldGrowthPolicy-enum); 对于 Qt 扩展样式，默认为[AllNonFixedFieldsGrow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldGrowthPolicy-enum)。

如果没有任何字段可以增长并且调整了表单的大小，则根据当前的大小分配额外的空间[form alignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)。

**访问功能：**

| QFormLayout::FieldGrowthPolicy | **fieldGrowthPolicy**() const                                |
| ------------------------------ | ------------------------------------------------------------ |
| void                           | **setFieldGrowthPolicy**(QFormLayout::FieldGrowthPolicy *policy*) |

**也可以看看**[formAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)和[rowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)。

### formAlignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

此属性保存表单布局内容在布局几何图形中的对齐方式

默认值取决于小部件或应用程序样式。对于 QMacStyle，默认值为[Qt::AlignHCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)|[Qt::AlignTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum); 对于其他样式，默认为[Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)|[Qt::AlignTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

**访问功能：**

| Qt::Alignment | **formAlignment**() const                       |
| ------------- | ----------------------------------------------- |
| void          | **setFormAlignment**(Qt::Alignment *alignment*) |

**也可以看看**[labelAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#labelAlignment-prop)和[rowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowWrapPolicy-prop)。

### horizontalSpacing : int

该属性保存并排放置的小部件之间的间距

默认情况下，如果未显式设置任何值，则布局的水平间距将从父布局或父窗口小部件的样式设置继承。

**访问功能：**

| int  | **horizontalSpacing**() const           |
| ---- | --------------------------------------- |
| void | **setHorizontalSpacing**(int *spacing*) |

**也可以看看**[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop),[QStyle::pixelMetric](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pixelMetric)（）， 和[PM_LayoutHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixelMetric-enum)。

### labelAlignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

该属性保存标签的水平对齐方式

默认值取决于小部件或应用程序样式。为了[QCommonStyle](https://doc-qt-io.translate.goog/qt-6/qcommonstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)派生样式，除 QPlastiqueStyle 外，默认为[Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum); 对于其他样式，默认为[Qt::AlignRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

**访问功能：**

| Qt::Alignment | **labelAlignment**() const                       |
| ------------- | ------------------------------------------------ |
| void          | **setLabelAlignment**(Qt::Alignment *alignment*) |

**也可以看看**[formAlignment](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#formAlignment-prop)。

### rowWrapPolicy : [RowWrapPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum)

该属性保存表单行的换行方式

默认值取决于小部件或应用程序样式。对于 Qt 扩展样式，默认为[WrapLongRows](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum); 对于其他样式，默认为[DontWrapRows](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum)。

如果您想在其关联字段上方（而不是旁边）显示每个标签，请将此属性设置为[WrapAllRows](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RowWrapPolicy-enum)。

**访问功能：**

| QFormLayout::RowWrapPolicy | **rowWrapPolicy**() const                                 |
| -------------------------- | --------------------------------------------------------- |
| void                       | **setRowWrapPolicy**(QFormLayout::RowWrapPolicy *policy*) |

**也可以看看**[fieldGrowthPolicy](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldGrowthPolicy-prop)。

### verticalSpacing : int

该属性保存垂直布局的小部件之间的间距

默认情况下，如果未显式设置任何值，则布局的垂直间距将从父布局或父窗口小部件的样式设置继承。

**访问功能：**

| int  | **verticalSpacing**() const           |
| ---- | ------------------------------------- |
| void | **setVerticalSpacing**(int *spacing*) |

**也可以看看**[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop),[QStyle::pixelMetric](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pixelMetric)（）， 和[PM_LayoutHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixelMetric-enum)。

## 成员函数文档

### `[explicit]`QFormLayout::QFormLayout([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **parent* = nullptr)

使用给定的构造一个新的表单布局*parent*小部件。

该布局直接设置为顶层布局*parent*。一个小部件只能有一个顶级布局。它由以下方式返回[QWidget::layout](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layout)()。

**也可以看看**[QWidget::setLayout](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)()。

### `[virtual]`QFormLayout::~QFormLayout()

破坏表单布局。

### `[override virtual]`void QFormLayout::addItem([QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) **item*)

重新实现：[QLayout::addItem](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（QLayoutItem *项目）。

### void QFormLayout::addRow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **label*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **field*)

在此表单布局的底部添加一个新行，其中包含给定的*label*和*field*。

**也可以看看**[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)()。

### void QFormLayout::addRow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **label*, [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **field*)

这是一个过载功能。

### void QFormLayout::addRow(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labelText*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **field*)

这是一个过载功能。

这种重载会自动创建一个[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)幕后与*labelText*作为其文本。这*field*被设置为新的[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的[buddy](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBuddy)。

### void QFormLayout::addRow(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labelText*, [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **field*)

这是一个过载功能。

这种重载会自动创建一个[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)幕后与*labelText*作为其文本。

### void QFormLayout::addRow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*)

这是一个过载功能。

添加指定的*widget*在此表单布局的末尾。这*widget*跨越两列。

### void QFormLayout::addRow([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*)

这是一个过载功能。

添加指定的*layout*在此表单布局的末尾。这*layout*跨越两列。

### `[override virtual]`int QFormLayout::count() const

重新实现：[QLayout::count() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)。

### `[override virtual]`[Qt::Orientations](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Orientation-enum) QFormLayout::expandingDirections() const

重新实现：[QLayout::expandingDirections() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#expandingDirections)。

### void QFormLayout::getItemPosition(int *index*, int **rowPtr*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) **rolePtr*) const

检索指定项目的行和角色（列）*index*。如果*index*超出范围，**rowPtr*设置为-1；否则该行存储在 **rowPtr*并且角色存储在 **rolePtr*。

**也可以看看**[itemAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)(),[count](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)(),[getLayoutPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getLayoutPosition)（）， 和[getWidgetPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getWidgetPosition)()。

### void QFormLayout::getLayoutPosition([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*, int **rowPtr*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) **rolePtr*) const

检索指定子项的行和角色（列）*layout*。如果*layout*不在表单布局中，**rowPtr*设置为-1；否则该行存储在 **rowPtr*并且角色存储在 **rolePtr*。

### void QFormLayout::getWidgetPosition([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*, int **rowPtr*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) **rolePtr*) const

检索指定的行和角色（列）*widget*在布局中。如果*widget*不在布局中，**rowPtr*设置为-1；否则该行存储在 **rowPtr*并且角色存储在 **rolePtr*。

**也可以看看**[getItemPosition](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getItemPosition)（） 和[itemAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)()。

### `[override virtual]`bool QFormLayout::hasHeightForWidth() const

重新实现：[QLayoutItem::hasHeightForWidth() const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasHeightForWidth)。

### `[override virtual]`int QFormLayout::heightForWidth(int *width*) const

重新实现：[QLayoutItem::heightForWidth(int) const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#heightForWidth)。

### void QFormLayout::insertRow(int *row*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **label*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **field*)

在位置插入新行*row*在此表单布局中，具有给定的*label*和*field*。如果*row*超出范围，新行将添加到末尾。

**也可以看看**[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)()。

### void QFormLayout::insertRow(int *row*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **label*, [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **field*)

这是一个过载功能。

### void QFormLayout::insertRow(int *row*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labelText*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **field*)

这是一个过载功能。

这种重载会自动创建一个[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)幕后与*labelText*作为其文本。这*field*被设置为新的[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的[buddy](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBuddy)。

### void QFormLayout::insertRow(int *row*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labelText*, [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **field*)

这是一个过载功能。

这种重载会自动创建一个[QLabel](https://doc-qt-io.translate.goog/qt-6/qlabel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)幕后与*labelText*作为其文本。

### void QFormLayout::insertRow(int *row*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*)

这是一个过载功能。

插入指定的*widget*在位置*row*在这个表单布局中。这*widget*跨越两列。如果*row*超出范围，小部件将添加到末尾。

### void QFormLayout::insertRow(int *row*, [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*)

这是一个过载功能。

插入指定的*layout*在位置*row*在这个表单布局中。这*layout*跨越两列。如果*row*超出范围，小部件将添加到末尾。

### `[override virtual]`void QFormLayout::invalidate()

重新实现：[QLayout::invalidate](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)()。

### `[since 6.4]`bool QFormLayout::isRowVisible(int *row*) const

如果行中有某些项目，则返回 true*row*是可见的，否则返回 false。

该功能是在 Qt 6.4 中引入的。

### `[since 6.4]`bool QFormLayout::isRowVisible([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*) const

这是一个过载功能。

如果行中的某些项目对应于，则返回 true*widget*是可见的，否则返回 false。

该功能是在 Qt 6.4 中引入的。

### `[since 6.4]`bool QFormLayout::isRowVisible([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*) const

这是一个过载功能。

如果行中的某些项目对应于，则返回 true*layout*是可见的，否则返回 false。

该功能是在 Qt 6.4 中引入的。

### [QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) *QFormLayout::itemAt(int *row*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) *role*) const

返回给定的布局项*row*与指定的*role*（柱子）。`nullptr`如果不存在该项目则返回。

**也可以看看**[QLayout::itemAt](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)（） 和[setItem](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItem)()。

### `[override virtual]`[QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) *QFormLayout::itemAt(int *index*) const

重新实现：[QLayout::itemAt(int index) const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QFormLayout::labelForField([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **field*) const

返回与给定关联的标签*field*。

**也可以看看**[itemAt](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QFormLayout::labelForField([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **field*) const

这是一个过载功能。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFormLayout::minimumSize() const

重新实现：[QLayout::minimumSize() const](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSize)。

### void QFormLayout::removeRow(int *row*)

删除行*row*从这个表单布局。

*row*必须为非负且小于[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)()。

这次通话之后，[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 减一。占用该行的所有小部件和嵌套布局都将被删除。这包括字段小部件和标签（如果有）。所有后续行都向上移动一行，并且释放的垂直空间在剩余行之间重新分配。

您可以使用此功能来撤消之前的操作[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)（） 或者[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)():

```
QFormLayout *flay = ...;
QPointer<QLineEdit> le = new QLineEdit;
flay->insertRow(2, "User:", le);
// later:
flay->removeRow(2); // le == nullptr at this point
```

如果您想从布局中删除该行而不删除小部件，请使用[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)（） 反而。

**也可以看看**[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)()。

### void QFormLayout::removeRow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*)

这是一个过载功能。

删除对应的行*widget*从这个表单布局。

这次通话之后，[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 减一。占用该行的所有小部件和嵌套布局都将被删除。这包括字段小部件和标签（如果有）。所有后续行都向上移动一行，并且释放的垂直空间在剩余行之间重新分配。

您可以使用此功能来撤消之前的操作[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)（） 或者[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)():

```
QFormLayout *flay = ...;
QPointer<QLineEdit> le = new QLineEdit;
flay->insertRow(2, "User:", le);
// later:
flay->removeRow(le); // le == nullptr at this point
```

如果您想从布局中删除该行而不删除小部件，请使用[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)（） 反而。

**也可以看看**[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)()。

### void QFormLayout::removeRow([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*)

这是一个过载功能。

删除对应的行*layout*从这个表单布局。

这次通话之后，[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 减一。占用该行的所有小部件和嵌套布局都将被删除。这包括字段小部件和标签（如果有）。所有后续行都向上移动一行，并且释放的垂直空间在剩余行之间重新分配。

您可以使用此功能来撤消之前的操作[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)（） 或者[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)():

```
QFormLayout *flay = ...;
QPointer<QVBoxLayout> vbl = new QVBoxLayout;
flay->insertRow(2, "User:", vbl);
// later:
flay->removeRow(layout); // vbl == nullptr at this point
```

如果要从表单布局中删除该行而不删除插入的布局，请使用[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)（） 反而。

**也可以看看**[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)()。

### int QFormLayout::rowCount() const

返回表单中的行数。

**也可以看看**[QLayout::count](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)()。

### `[override virtual]`void QFormLayout::setGeometry(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

重新实现：[QLayout::setGeometry](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGeometry)（常量 QRect &r）。

### void QFormLayout::setItem(int *row*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) *role*, [QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) **item*)

设置给定的项目*row*对于给定的*role*到*item*，如有必要，用空行扩展布局。

如果该单元已被占用，则*item*未插入，并且错误消息会发送到控制台。这*item*跨越两列。

**警告：**请勿使用此功能添加子布局或子小部件项目。使用[setLayout](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)（） 或者[setWidget](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)（） 反而。

**也可以看看**[setLayout](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)()。

### void QFormLayout::setLayout(int *row*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) *role*, [QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*)

设置给定的子布局*row*对于给定的*role*到*layout*，如有必要，用空行扩展表单布局。

如果该单元已被占用，则*layout*未插入，并且错误消息会发送到控制台。

**注意：**对于大多数应用，[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)（） 或者[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)应该使用 () 而不是 setLayout()。

**也可以看看**[setWidget](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidget)()。

### `[since 6.4]`void QFormLayout::setRowVisible(int *row*, bool *on*)

显示行*row*如果*on*为 true，否则隐藏该行。

*row*必须为非负且小于[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)()。

该功能是在 Qt 6.4 中引入的。

**也可以看看**[isRowVisible](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRowVisible)(),[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（）， 和[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)()。

### `[since 6.4]`void QFormLayout::setRowVisible([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*, bool *on*)

这是一个过载功能。

显示对应的行*widget*如果*on*为 true，否则隐藏该行。

该功能是在 Qt 6.4 中引入的。

**也可以看看**[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（） 和[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)()。

### `[since 6.4]`void QFormLayout::setRowVisible([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*, bool *on*)

这是一个过载功能。

显示对应的行*layout*如果*on*为 true，否则隐藏该行。

该功能是在 Qt 6.4 中引入的。

**也可以看看**[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（） 和[takeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeRow)()。

### `[override virtual]`void QFormLayout::setSpacing(int *spacing*)

重新实现属性的访问函数：[QLayout::spacing](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)。

该函数将垂直和水平间距设置为*spacing*。

**也可以看看**[spacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing)(),[setVerticalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)（）， 和[setHorizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)()。

### void QFormLayout::setWidget(int *row*, [QFormLayout::ItemRole](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemRole-enum) *role*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*)

设置给定的小部件*row*对于给定的*role*到*widget*，如有必要，用空行扩展布局。

如果该单元已被占用，则*widget*未插入，并且错误消息会发送到控制台。

**注意：**对于大多数应用，[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)（） 或者[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)应使用 () 代替 setWidget()。

**也可以看看**[setLayout](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayout)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFormLayout::sizeHint() const

重新实现：[QLayoutItem::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### `[override virtual]`int QFormLayout::spacing() const

重新实现属性的访问函数：[QLayout::spacing](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#spacing-prop)。

如果垂直间距等于水平间距，则该函数返回该值；否则返回-1。

**也可以看看**[setSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSpacing)(),[verticalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalSpacing-prop)（）， 和[horizontalSpacing](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalSpacing-prop)()。

### `[override virtual]`[QLayoutItem](https://doc-qt-io.translate.goog/qt-6/qlayoutitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayoutItem) *QFormLayout::takeAt(int *index*)

重新实现：[QLayout::takeAt](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeAt)（整数索引）。

### [QFormLayout::TakeRowResult](https://doc-qt-io.translate.goog/qt-6/qformlayout-takerowresult.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFormLayout::takeRow(int *row*)

删除指定的*row*从这个表单布局。

*row*必须为非负且小于[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)()。

**注意：**此函数不会删除任何内容。

这次通话之后，[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 减一。所有后续行都向上移动一行，并且释放的垂直空间在剩余行之间重新分配。

您可以使用此功能来撤消之前的操作[addRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRow)（） 或者[insertRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertRow)():

```
QFormLayout *flay = ...;
QPointer<QLineEdit> le = new QLineEdit;
flay->insertRow(2, "User:", le);
// later:
QFormLayout::TakeRowResult result = flay->takeRow(2);
```

如果您想从布局中删除该行并删除小部件，请使用[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（） 反而。

返回包含小部件和相应标签布局项的结构

**也可以看看**[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)()。

### [QFormLayout::TakeRowResult](https://doc-qt-io.translate.goog/qt-6/qformlayout-takerowresult.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFormLayout::takeRow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*)

这是一个过载功能。

删除指定的*widget*从这个表单布局。

**注意：**此函数不会删除任何内容。

这次通话之后，[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 减一。所有后续行都向上移动一行，并且释放的垂直空间在剩余行之间重新分配。

```
QFormLayout *flay = ...;
QPointer<QLineEdit> le = new QLineEdit;
flay->insertRow(2, "User:", le);
// later:
QFormLayout::TakeRowResult result = flay->takeRow(widget);
```

如果您想从布局中删除该行并删除小部件，请使用[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（） 反而。

返回包含小部件和相应标签布局项的结构

**也可以看看**[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)()。

### [QFormLayout::TakeRowResult](https://doc-qt-io.translate.goog/qt-6/qformlayout-takerowresult.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFormLayout::takeRow([QLayout](https://doc-qt-io.translate.goog/qt-6/qlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QLayout) **layout*)

这是一个过载功能。

删除指定的*layout*从这个表单布局。

**注意：**此函数不会删除任何内容。

这次通话之后，[rowCount](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rowCount)() 减一。所有后续行都向上移动一行，并且释放的垂直空间在剩余行之间重新分配。

```
QFormLayout *flay = ...;
QPointer<QVBoxLayout> vbl = new QVBoxLayout;
flay->insertRow(2, "User:", vbl);
// later:
QFormLayout::TakeRowResult result = flay->takeRow(widget);
```

如果要从表单布局中删除该行并删除插入的布局，请使用[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)（） 反而。

返回包含小部件和相应标签布局项的结构

**也可以看看**[removeRow](https://doc-qt-io.translate.goog/qt-6/qformlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRow)()。