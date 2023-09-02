#  QStackedWidget Class

QStackedWidget 类提供了一堆小部件，其中一次只有一个小部件可见。[更多的...](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QStackedWidget>                                    |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QFrame](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qstackedwidget-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 特性

- **[count](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)** : const int
- **[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)** : int

## 公共职能

|           | **[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QStackedWidget)**(QWidget **parent* = nullptr) |
| --------- | ------------------------------------------------------------ |
| virtual   | **[~QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QStackedWidget)**() |
| int       | **[addWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)**(QWidget **widget*) |
| int       | **[count](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)**() const |
| int       | **[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)**() const |
| QWidget * | **[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)**() const |
| int       | **[indexOf](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)**(const QWidget **widget*) const |
| int       | **[insertWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)**(int *index*, QWidget **widget*) |
| void      | **[removeWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeWidget)**(QWidget **widget*) |
| QWidget * | **[widget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)**(int *index*) const |

## 公共槽

| void | **[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)**(int *index*) |
| ---- | ------------------------------------------------------------ |
| void | **[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)**(QWidget **widget*) |

## 信号

| void | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(int *index*) |
| ---- | ------------------------------------------------------------ |
| void | **[widgetRemoved](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widgetRemoved)**(int *index*) |

## 重新实现protected function

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

QStackedWidget 可用于创建类似于以下提供的用户界面[QTabWidget](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它是一个建立在[QStackedLayout](https://doc-qt-io.translate.goog/qt-6/qstackedlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级。

喜欢[QStackedLayout](https://doc-qt-io.translate.goog/qt-6/qstackedlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), QStackedWidget 可以被构造并填充许多子部件（“页面”）：

```
    QWidget *firstPageWidget = new QWidget;
    QWidget *secondPageWidget = new QWidget;
    QWidget *thirdPageWidget = new QWidget;

    QStackedWidget *stackedWidget = new QStackedWidget;
    stackedWidget->addWidget(firstPageWidget);
    stackedWidget->addWidget(secondPageWidget);
    stackedWidget->addWidget(thirdPageWidget);

    QVBoxLayout *layout = new QVBoxLayout;
    layout->addWidget(stackedWidget);
    setLayout(layout);
```

QStackedWidget 没有为用户提供切换页面的内在方法。这通常是通过[QComboBox](https://doc-qt-io.translate.goog/qt-6/qcombobox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或一个[QListWidget](https://doc-qt-io.translate.goog/qt-6/qlistwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它存储 QStackedWidget 页面的标题。例如：

```
    QComboBox *pageComboBox = new QComboBox;
    pageComboBox->addItem(tr("Page 1"));
    pageComboBox->addItem(tr("Page 2"));
    pageComboBox->addItem(tr("Page 3"));
    connect(pageComboBox, &QComboBox::activated,
            stackedWidget, &QStackedWidget::setCurrentIndex);
```

填充堆叠小部件时，小部件将添加到内部列表中。这[indexOf](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)() 函数返回该列表中小部件的索引。可以使用以下命令将小部件添加到列表的末尾[addWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)() 函数，或使用[insertWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（） 功能。这[removeWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeWidget)() 函数从堆叠的小部件中删除一个小部件。可以使用以下命令获取堆叠小部件中包含的小部件的数量[count](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count-prop)（） 功能。

这[widget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)() 函数返回给定索引位置的小部件。屏幕上显示的小部件的索引由下式给出[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)() 并可以使用更改[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)()。以类似的方式，可以使用以下命令检索当前显示的小部件[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)() 函数，并使用[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)（） 功能。

每当堆叠小部件中的当前小部件发生更改或从堆叠小部件中删除小部件时，[currentChanged](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)（） 和[widgetRemoved](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widgetRemoved)分别发出 () 信号。

**也可以看看**[QStackedLayout](https://doc-qt-io.translate.goog/qt-6/qstackedlayout.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTabWidget](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 属性文档

### `[read-only]`count : const int

该属性保存此堆叠小部件包含的小部件的数量

默认情况下，此属性包含值 0。

**访问功能：**

| int  | **count**() const |
| ---- | ----------------- |
|      |                   |

**也可以看看**[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)（） 和[widget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### currentIndex : int

该属性保存可见小部件的索引位置

如果当前没有小部件，则当前索引为 -1。

默认情况下，该属性的值为 -1，因为堆栈最初为空。

**访问功能：**

| int  | **currentIndex**() const         |
| ---- | -------------------------------- |
| void | **setCurrentIndex**(int *index*) |

**通知器信号：**

| void | **[currentChanged](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentChanged)**(int *index*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)（） 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

## 成员函数文档

### `[explicit]`QStackedWidget::QStackedWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的值构造一个 QStackedWidget*parent*。

**也可以看看**[addWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)（） 和[insertWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)()。

### `[virtual]`QStackedWidget::~QStackedWidget()

销毁这个堆叠的小部件，并释放任何分配的资源。

### int QStackedWidget::addWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

追加给定的*widget*到[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并返回索引位置。所有权*widget*被传递到[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

如果[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在调用该函数之前为空，*widget*成为当前小部件。

**也可以看看**[insertWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)(),[removeWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeWidget)（）， 和[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)()。

### `[signal]`void QStackedWidget::currentChanged(int *index*)

每当当前小部件发生更改时都会发出此信号。

该参数保存的是*index*新的当前小部件的，如果没有新的小部件，则为 -1（例如，如果[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。

**注意：**属性的通知程序信号[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)。

**也可以看看**[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)（） 和[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QStackedWidget::currentWidget() const

返回当前窗口小部件，或者`nullptr`如果没有子窗口小部件。

**也可以看看**[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)（） 和[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)()。

### `[override virtual protected]`bool QStackedWidget::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QFrame::event](https://doc-qt-io.translate.goog/qt-6/qframe.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

### int QStackedWidget::indexOf(const [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*) const

返回给定的索引*widget*，如果给定则为 -1*widget*不是 的孩子[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[currentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)（） 和[widget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widget)()。

### int QStackedWidget::insertWidget(int *index*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

插入给定的*widget*在给定的*index*在里面[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。所有权*widget*被传递到[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。如果*index*超出范围，则*widget*被附加（在这种情况下，它是实际索引*widget*返回）。

如果[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在调用此函数之前为空，给定的*widget*成为当前小部件。

在小于或等于当前索引的索引处插入新的小部件将增加当前索引，但保留当前小部件。

**也可以看看**[addWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)(),[removeWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeWidget)（）， 和[setCurrentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentWidget)()。

### void QStackedWidget::removeWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

删除*widget*来自[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。IE，*widget*不会*被*删除，而只是从堆叠布局中删除，导致其被隐藏。

**注意：**的父对象和父小部件*widget*仍将是[QStackedWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。如果应用程序想要重用已删除的*widget*，那么建议重新设置父级。

**也可以看看**[addWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)(),[insertWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#insertWidget)（）， 和[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)()。

### `[slot]`void QStackedWidget::setCurrentWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

将当前小部件设置为指定的*widget*。新的当前小部件必须已包含在此堆叠小部件中。

**也可以看看**[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)（） 和[setCurrentIndex](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentIndex-prop)()。

### [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) *QStackedWidget::widget(int *index*) const

返回给定位置的小部件*index*，或者`nullptr`如果没有这样的小部件。

**也可以看看**[currentWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentWidget)（） 和[indexOf](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#indexOf)()。

### `[signal]`void QStackedWidget::widgetRemoved(int *index*)

每当一个小部件被删除时，就会发出此信号。小部件的*index*作为参数传递。

**也可以看看**[removeWidget](https://doc-qt-io.translate.goog/qt-6/qstackedwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeWidget)()。