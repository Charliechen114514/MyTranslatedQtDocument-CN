#  QAbstractItemDelegate Class

QAbstractItemDelegate 类用于显示和编辑模型中的数据项。[更多的...](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QAbstractItemDelegate>                            |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QItemDelegate](https://doc-qt-io.translate.goog/qt-6/qitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) and [QStyledItemDelegate](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[EndEditHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EndEditHint-enum)** { NoHint, EditNextItem, EditPreviousItem, SubmitModelCache, RevertModelCache } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 公共职能

|                   | **[QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QAbstractItemDelegate)**(QObject **parent* = nullptr) |
| ----------------- | ------------------------------------------------------------ |
| virtual           | **[~QAbstractItemDelegate](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QAbstractItemDelegate)**() |
| virtual QWidget * | **[createEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createEditor)**(QWidget **parent*, const QStyleOptionViewItem &*option*, const QModelIndex &*index*) const |
| virtual void      | **[destroyEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#destroyEditor)**(QWidget **editor*, const QModelIndex &*index*) const |
| virtual bool      | **[editorEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editorEvent)**(QEvent **event*, QAbstractItemModel **model*, const QStyleOptionViewItem &*option*, const QModelIndex &*index*) |
| virtual bool      | **[helpEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpEvent)**(QHelpEvent **event*, QAbstractItemView **view*, const QStyleOptionViewItem &*option*, const QModelIndex &*index*) |
| virtual void      | **[paint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)**(QPainter **painter*, const QStyleOptionViewItem &*option*, const QModelIndex &*index*) const = 0 |
| virtual void      | **[setEditorData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEditorData)**(QWidget **editor*, const QModelIndex &*index*) const |
| virtual void      | **[setModelData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModelData)**(QWidget **editor*, QAbstractItemModel **model*, const QModelIndex &*index*) const |
| virtual QSize     | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**(const QStyleOptionViewItem &*option*, const QModelIndex &*index*) const = 0 |
| virtual void      | **[updateEditorGeometry](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateEditorGeometry)**(QWidget **editor*, const QStyleOptionViewItem &*option*, const QModelIndex &*index*) const |

## 信号

| void | **[closeEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEditor)**(QWidget **editor*, QAbstractItemDelegate::EndEditHint *hint* = NoHint) |
| ---- | ------------------------------------------------------------ |
| void | **[commitData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitData)**(QWidget **editor*) |
| void | **[sizeHintChanged](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHintChanged)**(const QModelIndex &*index*) |

## 详细说明

QAbstractItemDelegate 为模型/视图架构中的委托提供接口和通用功能。委托在视图中显示各个项目，并处理模型数据的编辑。

QAbstractItemDelegate 类是其中之一[Model/View Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#model-view-classes)是 Qt 的一部分[model/view framework](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

要以自定义方式呈现项目，您必须实现[paint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)（） 和[sizeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)()。这[QStyledItemDelegate](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类提供这些函数的默认实现；如果您不需要自定义渲染，请对该类进行子类化。

我们举一个在items中绘制进度条的例子；在我们的例子中是一个包管理程序。

![img](.\QAbstractItemDelegate\widgetdelegate.png)

我们创建一个`WidgetDelegate`类，它继承自[QStyledItemDelegate](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。我们在中进行绘图[paint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)（） 功能：

```
void WidgetDelegate::paint(QPainter *painter, const QStyleOptionViewItem &option,
                           const QModelIndex &index) const
{
    if (index.column() == 1) {
        int progress = index.data().toInt();

        QStyleOptionProgressBar progressBarOption;
        progressBarOption.rect = option.rect;
        progressBarOption.minimum = 0;
        progressBarOption.maximum = 100;
        progressBarOption.progress = progress;
        progressBarOption.text = QString::number(progress) + "%";
        progressBarOption.textVisible = true;

        QApplication::style()->drawControl(QStyle::CE_ProgressBar,
                                           &progressBarOption, painter);
    } else
        QStyledItemDelegate::paint(painter, option, index);
```

请注意，我们使用[QStyleOptionProgressBar](https://doc-qt-io.translate.goog/qt-6/qstyleoptionprogressbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并初始化其成员。然后我们可以使用当前的[QStyle](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)来画它。

要提供自定义编辑，可以使用两种方法。第一种方法是创建一个编辑器小部件并将其直接显示在项目顶部。为此，您必须重新实现[createEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createEditor)() 提供编辑器小部件，[setEditorData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEditorData)() 用模型中的数据填充编辑器，以及[setModelData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModelData)() 以便委托可以使用编辑器中的数据更新模型。

第二种方法是通过重新实现来直接处理用户事件[editorEvent](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editorEvent)()。

**也可以看看**[Model/View Programming](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QStyledItemDelegate](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QStyle](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QAbstractItemDelegate::EndEditHint

该枚举描述了委托可以向模型和视图组件提供的不同提示，以使用户在模型中编辑数据成为一种舒适的体验。

| 持续的                          | 价值 | 描述                 |
| ------------------------------- | ---- | -------------------- |
| `QAbstractItemDelegate::NoHint` | `0`  | 没有建议执行的操作。 |

这些提示让委托影响视图的行为：

| 持续的                                    | 价值 | 描述                                       |
| ----------------------------------------- | ---- | ------------------------------------------ |
| `QAbstractItemDelegate::EditNextItem`     | `1`  | 视图应使用委托来打开视图中下一项的编辑器。 |
| `QAbstractItemDelegate::EditPreviousItem` | `2`  | 视图应使用委托来打开视图中前一项的编辑器。 |

请注意，自定义视图可能会以不同的方式解释下一个和上一个的概念。

当使用缓存数据的模型（例如在本地操作数据以提高性能或节省网络带宽的模型）时，以下提示非常有用。

| 持续的                                    | 价值 | 描述                                                         |
| ----------------------------------------- | ---- | ------------------------------------------------------------ |
| `QAbstractItemDelegate::SubmitModelCache` | `3`  | 如果模型缓存数据，它应该将缓存数据写入底层数据存储。         |
| `QAbstractItemDelegate::RevertModelCache` | `4`  | 如果模型缓存数据，它应该丢弃缓存的数据并将其替换为底层数据存储中的数据。 |

尽管模型和视图应该以适当的方式响应这些提示，但自定义组件可能会忽略其中的任何或全部提示（如果它们不相关）。

## 成员函数文档

### `[explicit]`QAbstractItemDelegate::QAbstractItemDelegate([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

使用给定的值创建一个新的抽象项委托*parent*。

### `[virtual noexcept]`QAbstractItemDelegate::~QAbstractItemDelegate()

销毁抽象项委托。

### `[signal]`void QAbstractItemDelegate::closeEditor([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **editor*, [QAbstractItemDelegate::EndEditHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EndEditHint-enum) *hint* = NoHint)

当用户使用指定的编辑完成项目时发出此信号*editor*。

这*hint*为委托提供了一种在编辑完成后影响模型和视图行为方式的方法。它向这些组件指示接下来应该执行什么操作，以便为用户提供舒适的编辑体验。例如，如果`EditNextItem`指定，视图应使用委托来打开模型中下一项的编辑器。

**也可以看看**[EndEditHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#EndEditHint-enum)。

### `[signal]`void QAbstractItemDelegate::commitData([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **editor*)

当*editor*小部件已完成数据编辑，并希望将其写回到模型中。

### `[virtual]`[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QAbstractItemDelegate::createEditor([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **parent*, const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回用于编辑给定数据项的编辑器*index*。请注意，索引包含有关正在使用的模型的信息。编辑器的父窗口部件由以下方式指定*parent*，以及项目选项*option*。

基本实现返回`nullptr`. 如果您想要自定义编辑，则需要重新实现此功能。

返回的编辑器小部件应该有[Qt::StrongFocus](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusPolicy-enum); 否则，[QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)小部件接收到的 s 将传播到视图。除非编辑器绘制自己的背景（例如，使用[setAutoFillBackground](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFillBackground-prop)())。

**也可以看看**[destroyEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#destroyEditor)(),[setModelData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModelData)（）， 和[setEditorData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEditorData)()。

### `[virtual]`void QAbstractItemDelegate::destroyEditor([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **editor*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

当*editor*不再需要使用给定的值编辑数据项*index*并应予以销毁。默认行为是在编辑器上调用deleteLater。例如，可以通过重新实现此函数来避免此删除。

**也可以看看**[createEditor](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createEditor)()。

### `[virtual]`bool QAbstractItemDelegate::editorEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*, [QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **model*, const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当开始编辑项目时，将调用此函数*event*触发编辑的*model*， 这*index*该项目的，以及*option*用于渲染项目。

即使鼠标事件没有开始编辑项目，也会将其发送到 editorEvent()。例如，如果您希望在某个项目上按下鼠标右键时打开上下文菜单，这会很有用。

基本实现返回`false`（表明它尚未处理该事件）。

### `[virtual]`bool QAbstractItemDelegate::helpEvent([QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*, [QAbstractItemView](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **view*, const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

每当发生帮助事件时，都会调用此函数*event* *view* *option*和*index*对应于事件发生的项目。

返回`true`委托是否可以处理该事件；否则返回`false`. 返回值 true 表示使用索引获取的数据具有所需的作用。

为了[QEvent::ToolTip](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)和[QEvent::WhatsThis](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)成功处理的事件，可能会显示相关的弹出窗口，具体取决于用户的系统配置。

**也可以看看**[QHelpEvent](https://doc-qt-io.translate.goog/qt-6/qhelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[pure virtual]`void QAbstractItemDelegate::paint([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

如果您想提供自定义渲染，则必须重新实现这个纯抽象函数。使用*painter*和风格*option*渲染由 item 指定的 item*index*。

如果您重新实现它，您还必须重新实现[sizeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)()。

### `[virtual]`void QAbstractItemDelegate::setEditorData([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **editor*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

设置给定的内容*editor*给定的项目的数据*index*。请注意，索引包含有关正在使用的模型的信息。

基本实现不执行任何操作。如果您想要自定义编辑，则需要重新实现此功能。

**也可以看看**[setModelData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setModelData)()。

### `[virtual]`void QAbstractItemDelegate::setModelData([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **editor*, [QAbstractItemModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **model*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

设置给定项目的数据*index*在里面*model*给定的内容*editor*。

基本实现不执行任何操作。如果您想要自定义编辑，则需要重新实现此功能。

**也可以看看**[setEditorData](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEditorData)()。

### `[pure virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QAbstractItemDelegate::sizeHint(const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

如果您想提供自定义渲染，则必须重新实现这个纯抽象函数。选项由以下方式指定*option*和模型项*index*。

如果您重新实现它，您还必须重新实现[paint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)()。

### `[signal]`void QAbstractItemDelegate::sizeHintChanged(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*)

当[sizeHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)（） 的*index*改变了。

视图会自动连接到此信号并根据需要重新布局项目。

### `[virtual]`void QAbstractItemDelegate::updateEditorGeometry([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **editor*, const [QStyleOptionViewItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptionviewitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option*, const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

更新几何形状*editor*对于给定的项目*index*，根据指定的矩形*option*。如果项目有内部布局，编辑器将进行相应的布局。请注意，索引包含有关正在使用的模型的信息。

基本实现不执行任何操作。如果您想要自定义编辑，则必须重新实现此功能。