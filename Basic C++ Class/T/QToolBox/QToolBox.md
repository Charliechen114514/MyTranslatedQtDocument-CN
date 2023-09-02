#  QToolBox Class

QToolBox 类提供了一列选项卡式小部件项。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QToolBox>                                         |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtoolbox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[count](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)** : const int
- **[currentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)** : int

## 公共职能

|           | **[QToolBox](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QToolBox)**(QWidget **parent* = nullptr, Qt::WindowFlags *f* = Qt::WindowFlags()) |
| --------- | ------------------------------------------------------------ |
| virtual   | **[~QToolBox](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QToolBox)**() |
| int       | **[addItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)**(QWidget **widget*, const QIcon &*iconSet*, const QString &*text*) |
| int       | **[addItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem-1)**(QWidget **w*, const QString &*text*) |
| int       | **[count](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)**() const |
| int       | **[currentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)**() const |
| QWidget * | **[currentWidget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)**() const |
| int       | **[indexOf](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)**(const QWidget **widget*) const |
| int       | **[insertItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)**(int *index*, QWidget **widget*, const QIcon &*icon*, const QString &*text*) |
| int       | **[insertItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem-1)**(int *index*, QWidget **widget*, const QString &*text*) |
| bool      | **[isItemEnabled](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isItemEnabled)**(int *index*) const |
| QIcon     | **[itemIcon](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIcon)**(int *index*) const |
| QString   | **[itemText](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemText)**(int *index*) const |
| QString   | **[itemToolTip](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemToolTip)**(int *index*) const |
| void      | **[removeItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)**(int *index*) |
| void      | **[setItemEnabled](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemEnabled)**(int *index*, bool *enabled*) |
| void      | **[setItemIcon](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemIcon)**(int *index*, const QIcon &*icon*) |
| void      | **[setItemText](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemText)**(int *index*, const QString &*text*) |
| void      | **[setItemToolTip](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemToolTip)**(int *index*, const QString &*toolTip*) |
| QWidget * | **[widget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)**(int *index*) const |

## 公共槽

| void | **[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)**(int *index*) |
| ---- | ------------------------------------------------------------ |
| void | **[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)**(QWidget **widget*) |

## 信号

| void | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(int *index*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected function

| virtual void | **[itemInserted](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemInserted)**(int *index*) |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[itemRemoved](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemRemoved)**(int *index*) |

## 重新实现protected function

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **ev*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent **e*) override |

## 详细说明

工具箱是一个小部件，它显示一列选项卡，其中当前项目显示在当前选项卡下方。每个选项卡在选项卡列中都有一个索引位置。选项卡的项目是[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

每个项目都有一个[itemText](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemText)()，可选[itemIcon](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIcon)()，可选[itemToolTip](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemToolTip)() 和一个[widget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。该项目的属性可以通过以下方式更改[setItemText](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemText)(),[setItemIcon](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemIcon)（）， 和[setItemToolTip](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemToolTip)()。每个项目都可以单独启用或禁用[setItemEnabled](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemEnabled)()。

项目添加使用[addItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()，或使用插入到特定位置[insertItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)()。项目总数由下式给出[count](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)()。可以使用delete删除项目，或者使用以下命令从工具箱中删除项目[removeItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)()。组合[removeItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)（） 和[insertItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertItem)() 允许您将项目移动到不同的位置。

当前项目小部件的索引由以下命令返回[currentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)()，并设置为[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)()。可以使用以下方式找到特定项目的索引[indexOf](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()，并且给定索引处的项目由 item() 返回。

这[currentChanged](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)当当前项发生更改时，会发出 () 信号。

**也可以看看**[QTabWidget](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### `[read-only]`count : const int

该属性保存工具箱中包含的项目数。

默认情况下，该属性的值为 0。

**访问功能：**

| int  | **count**() const |
| ---- | ----------------- |
|      |                   |

### currentIndex : int

该属性保存当前项目的索引

默认情况下，对于空工具箱，此属性的值为 -1。

**访问功能：**

| int  | **currentIndex**() const         |
| ---- | -------------------------------- |
| void | **setCurrentIndex**(int *index*) |

**通知器信号：**

| void | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(int *index*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[indexOf](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)（） 和[widget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

## 成员函数文档

### `[explicit]`QToolBox::QToolBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *f* = Qt::WindowFlags())

使用给定的构造一个新的工具箱*parent*和旗帜，*f*。

### `[virtual]`QToolBox::~QToolBox()

破坏工具箱。

### int QToolBox::addItem([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*, const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*iconSet*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

添加了*widget*在工具箱底部的新选项卡中。新选项卡的文本设置为*text*，以及*iconSet*显示在左侧*text*。返回新选项卡的索引。

### int QToolBox::addItem([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **w*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

这是一个过载功能。

添加小部件*w*在工具箱底部的新选项卡中。新选项卡的文本设置为*text*。返回新选项卡的索引。

### `[override virtual protected]`void QToolBox::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QFrame::changeEvent](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *ev）。

### `[signal]`void QToolBox::currentChanged(int *index*)

当前项目更改时会发出此信号。新的当前项目的索引被传入*index*，如果没有当前项目，则为 -1。

**注意：**属性的通知程序信号[currentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QToolBox::currentWidget() const

返回指向当前小部件的指针，或者`nullptr`如果不存在这样的项目。

**也可以看看**[currentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)（） 和[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)()。

### `[override virtual protected]`bool QToolBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QFrame::event](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### int QToolBox::indexOf(const [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*) const

返回索引*widget*，如果该项不存在则为 -1。

### int QToolBox::insertItem(int *index*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*, const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*icon*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

插入*widget*在位置*index*，或者在工具箱的底部，如果*index*超出范围。新项目的文本设置为*text*，以及*icon*显示在左侧*text*。返回新项目的索引。

### int QToolBox::insertItem(int *index*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

这是一个过载功能。

插入*widget*在位置*index*，或者在工具箱的底部，如果*index*超出范围。新项目的文本设置为*text*。返回新项目的索引。

### bool QToolBox::isItemEnabled(int *index*) const

返回`true`项目是否位于位置*index*已启用；否则返回`false`.

### [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QToolBox::itemIcon(int *index*) const

返回该位置的项目的图标*index*，或空图标，如果*index*超出范围。

**也可以看看**[setItemIcon](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemIcon)()。

### `[virtual protected]`void QToolBox::itemInserted(int *index*)

在位置添加或插入新项目后调用此虚拟处理程序*index*。

**也可以看看**[itemRemoved](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemRemoved)()。

### `[virtual protected]`void QToolBox::itemRemoved(int *index*)

从位置移除项目后调用此虚拟处理程序*index*。

**也可以看看**[itemInserted](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemInserted)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QToolBox::itemText(int *index*) const

返回位置处项目的文本*index*，或者一个空字符串，如果*index*超出范围。

**也可以看看**[setItemText](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemText)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QToolBox::itemToolTip(int *index*) const

返回该位置的项目的工具提示*index*，或者一个空字符串，如果*index*超出范围。

**也可以看看**[setItemToolTip](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setItemToolTip)()。

### void QToolBox::removeItem(int *index*)

删除位置上的项目*index*从工具箱中。请注意，该小部件*并未*被删除。

### `[slot]`void QToolBox::setCurrentWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

使*widget*当前小部件。这*widget*必须是此工具箱中的一项。

**也可以看看**[addItem](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)(),[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)（）， 和[currentWidget](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)()。

### void QToolBox::setItemEnabled(int *index*, bool *enabled*)

如果*enabled*为 true 则该位置的项目*index*已启用；否则该位置的项目*index*被禁用。

**也可以看看**[isItemEnabled](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isItemEnabled)()。

### void QToolBox::setItemIcon(int *index*, const [QIcon](https://doc-qt-io.translate.goog/qt-6/qicon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*icon*)

设置该位置的项目的图标*index*到*icon*。

**也可以看看**[itemIcon](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIcon)()。

### void QToolBox::setItemText(int *index*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

设置该位置项目的文本*index*到*text*。

如果提供的文本包含与字符 ('&')，则会自动为其创建助记符。“&”后面的字符将用作快捷键。如果文本没有定义助记符，则任何先前的助记符都将被覆盖或清除。请参阅[QShortcut](https://doc-qt-io.translate.goog/qt-6/qshortcut.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mnemonic)有关详细信息的文档（要显示实际的＆符号，请使用“&&”）。

**也可以看看**[itemText](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemText)()。

### void QToolBox::setItemToolTip(int *index*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*toolTip*)

设置项目的工具提示位置*index*到*toolTip*。

**也可以看看**[itemToolTip](https://doc-qt-io.translate.goog/qt-6/qtoolbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemToolTip)()。

### `[override virtual protected]`void QToolBox::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QToolBox::widget(int *index*) const

返回位置上的小部件*index*，或者`nullptr`如果没有这样的项目。