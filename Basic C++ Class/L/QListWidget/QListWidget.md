#  QListWidget Class

QListWidget 类提供了一个基于项目的列表小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QListWidget>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qlistwidget-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[count](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)** : const int
- **[currentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow-prop)** : int
- **[sortingEnabled](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)** : bool

## 公共职能

|                          | **[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QListWidget)**(QWidget **parent* = nullptr) |
| ------------------------ | ------------------------------------------------------------ |
| virtual                  | **[~QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QListWidget)**() |
| void                     | **[addItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)**(const QString &*label*) |
| void                     | **[addItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem-1)**(QListWidgetItem **item*) |
| void                     | **[addItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItems)**(const QStringList &*labels*) |
| void                     | **[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)**(QListWidgetItem **item*) |
| int                      | **[count](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)**() const |
| QListWidgetItem *        | **[currentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItem)**() const |
| int                      | **[currentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow-prop)**() const |
| void                     | **[editItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#editItem)**(QListWidgetItem **item*) |
| QList<QListWidgetItem *> | **[findItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#findItems)**(const QString &*text*, Qt::MatchFlags *flags*) const |
| QModelIndex              | **[indexFromItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexFromItem)**(const QListWidgetItem **item*) const |
| void                     | **[insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)**(int *row*, QListWidgetItem **item*) |
| void                     | **[insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem-1)**(int *row*, const QString &*label*) |
| void                     | **[insertItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItems)**(int *row*, const QStringList &*labels*) |
| bool                     | **[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)**(QListWidgetItem **item*) const |
| bool                     | **[isSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)**() const |
| QListWidgetItem *        | **[item](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item)**(int *row*) const |
| QListWidgetItem *        | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)**(const QPoint &*p*) const |
| QListWidgetItem *        | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt-1)**(int *x*, int *y*) const |
| QListWidgetItem *        | **[itemFromIndex](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemFromIndex)**(const QModelIndex &*index*) const |
| QWidget *                | **[itemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemWidget)**(QListWidgetItem **item*) const |
| QList<QListWidgetItem *> | **[items](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)**(const QMimeData **data*) const |
| void                     | **[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)**(QListWidgetItem **item*) |
| void                     | **[removeItemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItemWidget)**(QListWidgetItem **item*) |
| int                      | **[row](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#row)**(const QListWidgetItem **item*) const |
| QList<QListWidgetItem *> | **[selectedItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)**() const |
| void                     | **[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)**(QListWidgetItem **item*) |
| void                     | **[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem-1)**(QListWidgetItem **item*, QItemSelectionModel::SelectionFlags *command*) |
| void                     | **[setCurrentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow-prop)**(int *row*) |
| void                     | **[setCurrentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentRow-1)**(int *row*, QItemSelectionModel::SelectionFlags *command*) |
| void                     | **[setItemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemWidget)**(QListWidgetItem **item*, QWidget **widget*) |
| void                     | **[setSortingEnabled](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortingEnabled-prop)**(bool *enable*) |
| void                     | **[sortItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sortItems)**(Qt::SortOrder *order* = Qt::AscendingOrder) |
| QListWidgetItem *        | **[takeItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeItem)**(int *row*) |
| QRect                    | **[visualItemRect](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visualItemRect)**(const QListWidgetItem **item*) const |

## 重新实施公共职能

| virtual void | **[setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)**(QItemSelectionModel **selectionModel*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 公共老虎机

| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| ---- | ------------------------------------------------------------ |
| void | **[scrollToItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollToItem)**(const QListWidgetItem **item*, QAbstractItemView::ScrollHint *hint* = EnsureVisible) |

## 信号

| void | **[currentItemChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItemChanged)**(QListWidgetItem **current*, QListWidgetItem **previous*) |
| ---- | ------------------------------------------------------------ |
| void | **[currentRowChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRowChanged)**(int *currentRow*) |
| void | **[currentTextChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentTextChanged)**(const QString &*currentText*) |
| void | **[itemActivated](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemActivated)**(QListWidgetItem **item*) |
| void | **[itemChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChanged)**(QListWidgetItem **item*) |
| void | **[itemClicked](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemClicked)**(QListWidgetItem **item*) |
| void | **[itemDoubleClicked](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDoubleClicked)**(QListWidgetItem **item*) |
| void | **[itemEntered](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemEntered)**(QListWidgetItem **item*) |
| void | **[itemPressed](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemPressed)**(QListWidgetItem **item*) |
| void | **[itemSelectionChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemSelectionChanged)**() |

## 受保护的功能

| virtual bool            | **[dropMimeData](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropMimeData)**(int *index*, const QMimeData **data*, Qt::DropAction *action*) |
| ----------------------- | ------------------------------------------------------------ |
| virtual QMimeData *     | **[mimeData](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)**(const QList<QListWidgetItem *> &*items*) const |
| virtual QStringList     | **[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)**() const |
| virtual Qt::DropActions | **[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)**() const |

## 重新实现受保护的功能

| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\L\QListWidget\QListWidget\windows-listview.png)

QListWidget 是一个方便的类，它提供了一个类似于由[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但具有用于添加和删除项目的经典的基于项目的界面。QListWidget使用内部模型来管理每个[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在列表中。

对于更灵活的列表视图小部件，请使用[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)具有标准模型的类。

列表小部件的构造方式与其他小部件相同：

```
    QListWidget *listWidget = new QListWidget(this);
```

这[selectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)列表小部件的 () 决定可以同时选择列表中的多少个项目，以及是否可以创建复杂的项目选择。这可以通过设置[setSelectionMode](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)（） 功能。

有两种方法可以将项目添加到列表中：可以使用列表小部件作为其父小部件来构造它们，也可以不使用父小部件来构造它们，然后将其添加到列表中。如果在构造项目时列表小部件已经存在，则第一种方法更容易使用：

```
    new QListWidgetItem(tr("Oak"), listWidget);
    new QListWidgetItem(tr("Fir"), listWidget);
    new QListWidgetItem(tr("Pine"), listWidget);
```

如果您需要将新项目插入到列表中的特定位置，那么应该在没有父窗口小部件的情况下构造它。这[insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)然后应该使用 () 函数将其放入列表中。列表小部件将取得该项目的所有权。

```
    QListWidgetItem *newItem = new QListWidgetItem;
    newItem->setText(itemText);
    listWidget->insertItem(row, newItem);
```

对于多个项目，[insertItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItems)可以用()代替。列表中的项目数可以通过以下命令找到[count](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)（） 功能。要从列表中删除项目，请使用[takeItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeItem)()。

列表中的当前项目可以通过以下方式找到[currentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItem)()，并更改为[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)()。用户还可以通过使用键盘导航或单击不同的项目来更改当前项目。当当前项目发生变化时，[currentItemChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItemChanged)() 信号与新的当前项目和先前的当前项目一起发出。

**也可以看看**[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTreeView](https://doc-qt-io.translate.goog/qt-6/qtreeview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Model/View Programming](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Tab Dialog Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-tabdialog-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 财产文件

### `[read-only]`count : const int

此属性保存列表中的项目数，包括任何隐藏的项目。

**访问功能：**

| int  | **count**() const |
| ---- | ----------------- |
|      |                   |

### currentRow : int

该属性保存当前项目的行。

根据当前的选择模式，还可以选择该行。

**访问功能：**

| int  | **currentRow**() const                                       |
| ---- | ------------------------------------------------------------ |
| void | **setCurrentRow**(int *row*)                                 |
| void | **[setCurrentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentRow-1)**(int *row*, QItemSelectionModel::SelectionFlags *command*) |

**通知器信号：**

| void | **[currentRowChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRowChanged)**(int *currentRow*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

### sortingEnabled : bool

该属性保存是否启用排序

如果此属性为`true`，则为列表启用排序；如果该属性为 false，则不启用排序。

默认值为 false。

**访问功能：**

| bool | **isSortingEnabled**() const         |
| ---- | ------------------------------------ |
| void | **setSortingEnabled**(bool *enable*) |

## 成员函数文档

### `[explicit]`QListWidget::QListWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个空的 QListWidget*parent*。

### `[virtual]`QListWidget::~QListWidget()

销毁列表小部件及其所有项目。

### void QListWidget::addItem(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*label*)

插入带有文本的项目*label*在列表小部件的末尾。

### void QListWidget::addItem([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

插入*item*在列表小部件的末尾。

**警告：** A[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)只能添加到[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)一次。添加相同的[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)多次到[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将导致未定义的行为。

**也可以看看**[insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)()。

### void QListWidget::addItems(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labels*)

插入带有文本的项目*labels*在列表小部件的末尾。

**也可以看看**[insertItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItems)()。

### `[slot]`void QListWidget::clear()

删除视图中的所有项目和选择。

**警告：**所有项目将被永久删除。

### void QListWidget::closePersistentEditor([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

关闭给定的持久编辑器*item*。

**也可以看看**[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)（） 和[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)()。

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::currentItem() const

返回当前项目。

**也可以看看**[setCurrentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentItem)()。

### `[signal]`void QListWidget::currentItemChanged([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **current*, [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **previous*)

每当当前项发生更改时，都会发出此信号。

*previous*是先前获得焦点的项目；*current*是新的当前项目。

### `[signal]`void QListWidget::currentRowChanged(int *currentRow*)

每当当前项发生更改时，都会发出此信号。

*currentRow*是当前项目的行。如果没有当前项目，则*currentRow*是-1。

**注意：**属性的通知程序信号[currentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow-prop)。

### `[signal]`void QListWidget::currentTextChanged(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*currentText*)

每当当前项发生更改时，都会发出此信号。

*currentText*是当前项目中的文本数据。如果没有当前项目，则*currentText*是无效的。

### `[override virtual protected]`void QListWidget::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QListView::dropEvent](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### `[virtual protected]`bool QListWidget::dropMimeData(int *index*, const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*, [Qt::DropAction](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) *action*)

手柄*data*由以给定结尾的外部拖放操作提供*action*在给定的*index*。返回`true`如果*data*和*action*可以由模型处理；否则返回`false`.

**也可以看看**[supportedDropActions](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#supportedDropActions)()。

### void QListWidget::editItem([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

开始编辑*item*如果它是可编辑的。

### `[override virtual protected]`bool QListWidget::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QListView::event](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QListWidget::findItems(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [Qt::MatchFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MatchFlag-enum) *flags*) const

查找文本与字符串匹配的项目*text*使用给定的*flags*。

### [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidget::indexFromItem(const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回[QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与给定相关的*item*。

**注意：**在 5.10 之前的 Qt 版本中，此函数采用非`const` *item*。

### void QListWidget::insertItem(int *row*, [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

插入*item*在由给出的列表中的位置*row*。

**也可以看看**[addItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### void QListWidget::insertItem(int *row*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*label*)

插入带有文本的项目*label*在列表小部件中指定的位置*row*。

**也可以看看**[addItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### void QListWidget::insertItems(int *row*, const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*labels*)

从列表中插入项目*labels*进入列表，从给定的位置开始*row*。

**也可以看看**[insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)（） 和[addItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### bool QListWidget::isPersistentEditorOpen([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回持久编辑器是否为项目打开*item*。

**也可以看看**[openPersistentEditor](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#openPersistentEditor)（） 和[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)()。

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::item(int *row*) const

返回占据给定值的项目*row*如果已设置，则在列表中；否则返回`nullptr`.

**也可以看看**[row](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#row)()。

### `[signal]`void QListWidget::itemActivated([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

当*item*被激活。这*item*当用户单击或双击它时激活，具体取决于系统配置。当用户按下激活键时它也会被激活（在 Windows 和 X11 上，这是**Return**键，在 Mac OS X 上是**Command+O**）。

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::itemAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*p*) const

返回指向坐标处的项目的指针*p*。坐标是相对于列表小部件的[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()。

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::itemAt(int *x*, int *y*) const

这是一个过载功能。

返回指向坐标处的项目的指针 (*x*,*y*）。坐标是相对于列表小部件的[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()。

### `[signal]`void QListWidget::itemChanged([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

每当数据*item*已经改变。

### `[signal]`void QListWidget::itemClicked([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

该信号以指定的方式发出*item*当鼠标按钮单击小部件中的项目时。

**也可以看看**[itemPressed](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemPressed)（） 和[itemDoubleClicked](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDoubleClicked)()。

### `[signal]`void QListWidget::itemDoubleClicked([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

该信号以指定的方式发出*item*当鼠标按钮双击小部件中的项目时。

**也可以看看**[itemClicked](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemClicked)（） 和[itemPressed](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemPressed)()。

### `[signal]`void QListWidget::itemEntered([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

当鼠标光标进入某个项目时，会发出此信号。这*item*是输入的项目。仅当打开 mouseTracking 或在移动到某个项目时按下鼠标按钮时，才会发出此信号。

**也可以看看**[QWidget::setMouseTracking](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseTracking-prop)()。

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::itemFromIndex(const [QModelIndex](https://doc-qt-io.translate.goog/qt-6/qmodelindex.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*index*) const

返回一个指向[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与给定相关的*index*。

### `[signal]`void QListWidget::itemPressed([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

该信号以指定的方式发出*item*当在小部件中的某个项目上按下鼠标按钮时。

**也可以看看**[itemClicked](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemClicked)（） 和[itemDoubleClicked](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemDoubleClicked)()。

### `[signal]`void QListWidget::itemSelectionChanged()

每当选择发生变化时就会发出此信号。

**也可以看看**[selectedItems](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)(),[QListWidgetItem::isSelected](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSelected)（）， 和[currentItemChanged](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItemChanged)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QListWidget::itemWidget([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回给定中显示的小部件*item*。

**也可以看看**[setItemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemWidget)（） 和[removeItemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItemWidget)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QListWidget::items(const [QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **data*) const

返回指向包含在其中的项目的指针列表*data*目的。如果该对象不是由[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在同一过程中，列表为空。

### `[virtual protected]`[QMimeData](https://doc-qt-io.translate.goog/qt-6/qmimedata.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::mimeData(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> &*items*) const

返回一个对象，其中包含指定的序列化描述*items*。用于描述项目的格式是从[mimeTypes](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeTypes)（） 功能。

如果项目列表为空，`nullptr`则返回而不是序列化的空列表。

### `[virtual protected]`[QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidget::mimeTypes() const

返回可用于描述列表小部件项目列表的 MIME 类型列表。

**也可以看看**[mimeData](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mimeData)()。

### void QListWidget::openPersistentEditor([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

打开给定的编辑器*item*。编辑器在编辑后保持打开状态。

**也可以看看**[closePersistentEditor](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closePersistentEditor)（） 和[isPersistentEditorOpen](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPersistentEditorOpen)()。

### void QListWidget::removeItemWidget([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

删除给定的小部件集*item*。

要从列表中完全删除项目（行），请删除该项目或使用[takeItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#takeItem)()。

**也可以看看**[itemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemWidget)（） 和[setItemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemWidget)()。

### int QListWidget::row(const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回包含给定值的行*item*。

**也可以看看**[item](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item)()。

### `[slot]`void QListWidget::scrollToItem(const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [QAbstractItemView::ScrollHint](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollHint-enum) *hint* = EnsureVisible)

如有必要，滚动视图以确保*item*是可见的。

*hint*指定在哪里*item*应在手术后定位。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QListWidget::selectedItems() const

返回列表小部件中所有选定项目的列表。

### void QListWidget::setCurrentItem([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

将当前项目设置为*item*。

除非选择模式是[NoSelection](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，该项目也被选中。

**也可以看看**[currentItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentItem)()。

### void QListWidget::setCurrentItem([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

将当前项目设置为*item*，使用给定的*command*。

### void QListWidget::setCurrentRow(int *row*, [QItemSelectionModel::SelectionFlags](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionFlag-enum) *command*)

将当前行设置为给定的*row*，使用给定的*command*,

**注意：**属性的 Setter 函数[currentRow](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentRow-prop)。

### void QListWidget::setItemWidget([QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

设置*widget*要显示在给定的*item*。

此函数只能用于在列表小部件项目的位置显示静态内容。如果您想显示自定义动态内容或实现自定义编辑器小部件，请使用[QListView](https://doc-qt-io.translate.goog/qt-6/qlistview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和子类[QStyledItemDelegate](https://doc-qt-io.translate.goog/qt-6/qstyleditemdelegate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)反而。

**也可以看看**[itemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemWidget)(),[removeItemWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItemWidget)（）， 和[Delegate Classes](https://doc-qt-io.translate.goog/qt-6/model-view-programming.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#delegate-classes)。

### `[override virtual]`void QListWidget::setSelectionModel([QItemSelectionModel](https://doc-qt-io.translate.goog/qt-6/qitemselectionmodel.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **selectionModel*)

重新实现：[QAbstractItemView::setSelectionModel](https://doc-qt-io.translate.goog/qt-6/qabstractitemview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionModel)(QItemSelectionModel *selectionModel)。

### void QListWidget::sortItems([Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::AscendingOrder)

根据指定对列表小部件中的所有项目进行排序*order*。

### `[virtual protected]`[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum) QListWidget::supportedDropActions() const

返回此视图支持的放置操作。

**也可以看看**[Qt::DropActions](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DropAction-enum)。

### [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QListWidget::takeItem(int *row*)

删除并返回给定的项目*row*在列表小部件中；否则返回`nullptr`.

从列表小部件中删除的项目将不会由 Qt 管理，并且需要手动删除。

**也可以看看**[insertItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)（） 和[addItem](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QListWidget::visualItemRect(const [QListWidgetItem](https://doc-qt-io.translate.goog/qt-6/qlistwidgetitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*) const

返回视口中项目占据的矩形*item*。