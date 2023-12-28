# QListWidgetItem Class

QListWidgetItem 类提供了一个与[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)项目视图类。

| Header: | #include < QListWidgetItem>                                  |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:  | QT += widgets                                                |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[ItemType](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemType-enum)** { Type, UserType } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 公共职能

|                           | **[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem)**(QListWidget **parent* = nullptr, int *type* = Type) |
| ------------------------- | ------------------------------------------------------------ |
|                           | **[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem-1)**(const QString &*text*, QListWidget **parent* = nullptr, int *type* = Type) |
|                           | **[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem-2)**(const QIcon &*icon*, const QString &*text*, QListWidget **parent* = nullptr, int *type* = Type) |
|                           | **[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem-3)**(const QListWidgetItem &*other*) |
| virtual                   | **[~QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QListWidgetItem)**() |
| QBrush                    | **[background](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)**() const |
| Qt::CheckState            | **[checkState](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)**() const |
| virtual QListWidgetItem * | **[clone](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clone)**() const |
| virtual QVariant          | **[data](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)**(int *role*) const |
| Qt::ItemFlags             | **[flags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)**() const |
| QFont                     | **[font](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)**() const |
| QBrush                    | **[foreground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foreground)**() const |
| QIcon                     | **[icon](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon)**() const |
| bool                      | **[isHidden](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isHidden)**() const |
| bool                      | **[isSelected](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSelected)**() const |
| QListWidget *             | **[listWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#listWidget)**() const |
| virtual void              | **[read](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)**(QDataStream &*in*) |
| void                      | **[setBackground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)**(const QBrush &*brush*) |
| void                      | **[setCheckState](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckState)**(Qt::CheckState *state*) |
| virtual void              | **[setData](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)**(int *role*, const QVariant &*value*) |
| void                      | **[setFlags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)**(Qt::ItemFlags *flags*) |
| void                      | **[setFont](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)**(const QFont &*font*) |
| void                      | **[setForeground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setForeground)**(const QBrush &*brush*) |
| void                      | **[setHidden](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHidden)**(bool *hide*) |
| void                      | **[setIcon](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIcon)**(const QIcon &*icon*) |
| void                      | **[setSelected](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)**(bool *select*) |
| void                      | **[setSizeHint](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizeHint)**(const QSize &*size*) |
| void                      | **[setStatusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatusTip)**(const QString &*statusTip*) |
| void                      | **[setText](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setText)**(const QString &*text*) |
| void                      | **[setTextAlignment](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextAlignment-2)**(Qt::Alignment *alignment*) |
| void                      | **[setToolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)**(const QString &*toolTip*) |
| void                      | **[setWhatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWhatsThis)**(const QString &*whatsThis*) |
| QSize                     | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const |
| QString                   | **[statusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusTip)**() const |
| QString                   | **[text](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)**() const |
| int                       | **[textAlignment](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textAlignment)**() const |
| QString                   | **[toolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip)**() const |
| int                       | **[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)**() const |
| QString                   | **[whatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#whatsThis)**() const |
| virtual void              | **[write](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#write)**(QDataStream &*out*) const |
| virtual bool              | **[operator< ](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt)**(const QListWidgetItem &*other*) const |
| QListWidgetItem &         | **[operator=](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QListWidgetItem &*other*) |

## 相关非会员

| QDataStream & | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QDataStream &*out*, const QListWidgetItem &*item*) |
| ------------- | ------------------------------------------------------------ |
| QDataStream & | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*in*, QListWidgetItem &*item*) |

## 详细说明

QListWidgetItem 代表一个 QListWidgetItem 中的单个项目[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。每个项目可以容纳几条信息，并会适当地显示它们。

项目视图便利类使用经典的基于项目的界面，而不是纯粹的模型/视图方法。对于更灵活的列表视图小部件，请考虑使用[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)具有标准模型的类。

列表项可以在构建时通过指定列表小部件自动插入到列表中：

```
    new QListWidgetItem(tr("Hazel"), listWidget);
```

或者，也可以在没有父窗口小部件的情况下创建列表项，然后使用[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)()。

列表项通常用于显示[text](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)（） 和[icon](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon)()。这些设置与[setText](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setText)（） 和[setIcon](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIcon)（） 功能。文本的外观可以自定义[setFont](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)(),[setForeground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setForeground)（）， 和[setBackground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)()。可以使用 setTextAlignment() 函数对齐列表项中的文本。工具提示、状态提示和“这是什么？” 可以将帮助添加到列表项中[setToolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)(),[setStatusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatusTip)（）， 和[setWhatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWhatsThis)()。

默认情况下，项目是启用的、可选择的、可检查的，并且可以是拖放操作的源。

每个项目的标志可以通过调用来更改[setFlags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)() 具有适当的值（参见[Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)）。可检查的项目可以通过以下方式进行检查、取消检查和部分检查[setCheckState](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckState)（） 功能。相应的[checkState](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)() 函数指示该项目的当前检查状态。

这[isHidden](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isHidden)() 函数可用于判断该项是否隐藏。要隐藏项目，请使用[setHidden](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHidden)()。

### 子类化

当子类化 QListWidgetItem 以提供自定义项目时，可以为它们定义新类型，使它们能够与标准项目区分开来。对于需要此功能的子类，请确保使用等于或大于的新类型值调用基类构造函数[UserType](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemType-enum)，在*你的*构造函数中。

**也可以看看**[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Model/View Programming](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTreeWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtreewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTableWidgetItem](https://doc-qt-io.translate.goog/qt-6/qtablewidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QListWidgetItem::ItemType

该枚举描述了用于描述列表小部件项的类型。

| 持续的                      | 价值   | 描述                                              |
| --------------------------- | ------ | ------------------------------------------------- |
| `QListWidgetItem::Type`     | `0`    | 列表小部件项目的默认类型。                        |
| `QListWidgetItem::UserType` | `1000` | 自定义类型的最小值。UserType 以下的值由 Qt 保留。 |

您可以在中定义新的用户类型[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类以确保自定义项目得到特殊处理。

**也可以看看**[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)()。

## 成员函数文档

### `[explicit]`QListWidgetItem::QListWidgetItem([QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **parent* = nullptr, int *type* = Type)

构造指定的空列表小部件项*type*与给定的*parent*。如果*parent*未指定，该项目将需要插入到列表小部件中[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)()。

此构造函数将项插入到传递给构造函数的父级模型中。如果模型已排序，则插入的行为不确定，因为模型将调用`'< '`此时尚未构造的项目的运算符方法。为了避免未确定的行为，我们建议不要指定父级并使用[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)（） 反而。

**也可以看看**[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)()。

### `[explicit]`QListWidgetItem::QListWidgetItem(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **parent* = nullptr, int *type* = Type)

构造指定的空列表小部件项*type*与给定的*text*和*parent*。如果未指定父项，则需要使用以下命令将该项目插入到列表小部件中[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)()。

此构造函数将项插入到传递给构造函数的父级模型中。如果模型已排序，则插入的行为不确定，因为模型将调用`'< '`此时尚未构造的项目的运算符方法。为了避免未确定的行为，我们建议不要指定父级并使用[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)（） 反而。

**也可以看看**[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)()。

### `[explicit]`QListWidgetItem::QListWidgetItem(const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*icon*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **parent* = nullptr, int *type* = Type)

构造指定的空列表小部件项*type*与给定的*icon*,*text*和*parent*。如果未指定父项，则需要使用以下命令将该项目插入到列表小部件中[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)()。

此构造函数将项插入到传递给构造函数的父级模型中。如果模型已排序，则插入的行为不确定，因为模型将调用`'< '`此时尚未构造的项目的运算符方法。为了避免未确定的行为，我们建议不要指定父级并使用[QListWidget::insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)（） 反而。

**也可以看看**[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)()。

### QListWidgetItem::QListWidgetItem(const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) &*other*)

构造一个副本*other*。注意[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)（） 和[listWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#listWidget)() 不被复制。

这个函数在重新实现时很有用[clone](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clone)()。

**也可以看看**[data](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（） 和[flags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)()。

### `[virtual noexcept]`QListWidgetItem::~QListWidgetItem()

销毁列表项。

### [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::background() const

返回用于显示列表项背景的画笔。

**也可以看看**[setBackground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)（） 和[foreground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foreground)()。

### [Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum) QListWidgetItem::checkState() const

返回列表项的选中状态（请参阅[Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum)）。

**也可以看看**[setCheckState](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckState)（） 和[flags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)()。

### `[virtual]`[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) *QListWidgetItem::clone() const

创建该项目的精确副本。

### `[virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::data(int *role*) const

返回给定项目的数据*role*。如果您需要额外的角色或某些角色的特殊行为，请重新实现此函数。

**也可以看看**[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)和[setData](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)()。

### [Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum) QListWidgetItem::flags() const

返回该项目的项目标志（请参阅[Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)）。

**也可以看看**[setFlags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)()。

### [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::font() const

返回用于显示此列表项文本的字体。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)()。

### [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::foreground() const

返回用于显示列表项的前景（例如文本）的画笔。

**也可以看看**[setForeground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setForeground)（） 和[background](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)()。

### [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::icon() const

返回列表项的图标。

**也可以看看**[setIcon](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIcon)（） 和[iconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)。

### bool QListWidgetItem::isHidden() const

`true`如果该项目被隐藏则返回；否则返回`false`.

**也可以看看**[setHidden](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHidden)()。

### bool QListWidgetItem::isSelected() const

`true`如果该项目被选中则返回；否则返回`false`.

**也可以看看**[setSelected](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)()。

### [QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidgetItem::listWidget() const

返回包含该项目的列表小部件。

### `[virtual]`void QListWidgetItem::read([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*in*)

从流中读取项目*in*。

**也可以看看**[write](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#write)()。

### void QListWidgetItem::setBackground(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

将列表项的背景画笔设置为给定的*brush*。设置默认构造的画笔将使视图使用样式中的默认颜色。

**也可以看看**[background](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)（） 和[setForeground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setForeground)()。

### void QListWidgetItem::setCheckState([Qt::CheckState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CheckState-enum) *state*)

将列表项的选中状态设置为*state*。

**也可以看看**[checkState](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkState)()。

### `[virtual]`void QListWidgetItem::setData(int *role*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*value*)

设置给定的数据*role*对给定的*value*。如果您需要额外的角色或某些角色的特殊行为，请重新实现此函数。

**注意：**默认实现处理[Qt::EditRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)和[Qt::DisplayRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)指的是相同的数据。

**也可以看看**[Qt::ItemDataRole](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemDataRole-enum)和[data](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。

### void QListWidgetItem::setFlags([Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum) *flags*)

将列表项的项目标志设置为*flags*。

**也可以看看**[flags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)（） 和[Qt::ItemFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemFlag-enum)。

### void QListWidgetItem::setFont(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

设置将项目绘制为给定时使用的字体*font*。

**也可以看看**[font](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)()。

### void QListWidgetItem::setForeground(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

将列表项的前景画笔设置为给定的*brush*。设置默认构造的画笔将使视图使用样式中的默认颜色。

**也可以看看**[foreground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foreground)（） 和[setBackground](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)()。

### void QListWidgetItem::setHidden(bool *hide*)

如果出现以下情况，则隐藏该项目*hide*是真的; 否则显示该项目。

**也可以看看**[isHidden](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isHidden)()。

### void QListWidgetItem::setIcon(const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*icon*)

将列表项的图标设置为给定的*icon*。

**也可以看看**[icon](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon)(),[text](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)（）， 和[iconSize](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconSize-prop)。

### void QListWidgetItem::setSelected(bool *select*)

将项目的选定状态设置为*select*。

**也可以看看**[isSelected](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSelected)()。

### void QListWidgetItem::setSizeHint(const [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*size*)

将列表项的大小提示设置为*size*。如果没有设置尺寸提示或*size*无效，项目委托将根据项目数据计算大小提示。

**也可以看看**[sizeHint](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)()。

### void QListWidgetItem::setStatusTip(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*statusTip*)

将列表项的状态提示设置为由指定的文本*statusTip*。[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)需要启用 mouseTracking 才能使此功能发挥作用。

**也可以看看**[statusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusTip)(),[setToolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)(),[setWhatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWhatsThis)（）， 和[QWidget::setMouseTracking](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseTracking-prop)()。

### void QListWidgetItem::setText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

将列表小部件项目的文本设置为给定的*text*。

**也可以看看**[text](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text)()。

### `[since 6.4]`void QListWidgetItem::setTextAlignment([Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum) *alignment*)

将列表项的文本对齐方式设置为*alignment*。

该功能是在 Qt 6.4 中引入的。

### void QListWidgetItem::setToolTip(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*toolTip*)

将列表项的工具提示设置为由指定的文本*toolTip*。

**也可以看看**[toolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip)(),[setStatusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatusTip)（）， 和[setWhatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWhatsThis)()。

### void QListWidgetItem::setWhatsThis(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*whatsThis*)

设置“这是什么？” 将列表项的帮助指定为*whatsThis*。

**也可以看看**[whatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#whatsThis)(),[setStatusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatusTip)（）， 和[setToolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)()。

### [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::sizeHint() const

返回为列表项设置的大小提示。

**也可以看看**[setSizeHint](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSizeHint)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::statusTip() const

返回列表项的状态提示。

**也可以看看**[setStatusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatusTip)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::text() const

返回列表项的文本。

**也可以看看**[setText](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setText)()。

### int QListWidgetItem::textAlignment() const

返回列表项的文本对齐方式。

**注意：**由于历史原因，该函数返回一个 int。将会更正返回[Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)在 Qt 7 中。

**也可以看看**[Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::toolTip() const

返回列表项的工具提示。

**也可以看看**[setToolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)(),[statusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusTip)（）， 和[whatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#whatsThis)()。

### int QListWidgetItem::type() const

返回传递给的类型[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidgetItem::whatsThis() const

返回列表项的“这是什么？” 帮助文本。

**也可以看看**[setWhatsThis](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWhatsThis)(),[statusTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#statusTip)（）， 和[toolTip](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip)()。

### `[virtual]`void QListWidgetItem::write([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*out*) const

将项目写入流*out*。

**也可以看看**[read](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)()。

### `[virtual]`bool QListWidgetItem::operator< (const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) &*other*) const

`true`如果该项目的文本小于则返回*other*项目的文本；否则返回`false`.

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) &QListWidgetItem::operator=(const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) &*other*)

分配*other*该项目的数据和标志。注意[type](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)（） 和[listWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#listWidget)() 不被复制。

这个函数在重新实现时很有用[clone](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clone)()。

**也可以看看**[data](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)（） 和[flags](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)()。

## 相关非会员

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator< < ([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*out*, const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) &*item*)

写入列表小部件项目*item*流式传输*out*。

该运算符使用[QListWidgetItem::write](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#write)()。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*in*, [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidgetItem) &*item*)

从流中读取列表小部件项目*in*进入*item*。

该运算符使用[QListWidgetItem::read](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)()。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。