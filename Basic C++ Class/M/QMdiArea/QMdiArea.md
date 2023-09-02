#  QMdiArea Class

QMdiArea 小部件提供了一个显示 MDI 窗口的区域。[更多的...](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include  < QMdiArea>                                        |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qmdiarea-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[AreaOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum)** { DontMaximizeSubWindowOnActivation } |
| ----- | ------------------------------------------------------------ |
| flags | **[AreaOptions](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum)** |
| enum  | **[ViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)** { SubWindowView, TabbedView } |
| enum  | **[WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)** { CreationOrder, StackingOrder, ActivationHistoryOrder } |

## 特性

| **[activationOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activationOrder-prop)** : WindowOrder**[background](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background-prop)** : QBrush**[documentMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMode-prop)** : bool**[tabPosition](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabPosition-prop)** : QTabWidget::TabPosition | **[tabShape](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabShape-prop)** : QTabWidget::TabShape**[tabsClosable](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsClosable-prop)** : bool**[tabsMovable](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsMovable-prop)** : bool**[viewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)** : ViewMode |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                         | **[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMdiArea)**(QWidget **parent* = nullptr) |
| ----------------------- | ------------------------------------------------------------ |
| virtual                 | **[~QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QMdiArea)**() |
| QMdiArea::WindowOrder   | **[activationOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activationOrder-prop)**() const |
| QMdiSubWindow *         | **[activeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeSubWindow)**() const |
| QMdiSubWindow *         | **[addSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSubWindow)**(QWidget **widget*, Qt::WindowFlags *windowFlags* = Qt::WindowFlags()) |
| QBrush                  | **[background](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background-prop)**() const |
| QMdiSubWindow *         | **[currentSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSubWindow)**() const |
| bool                    | **[documentMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMode-prop)**() const |
| void                    | **[removeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSubWindow)**(QWidget **widget*) |
| void                    | **[setActivationOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activationOrder-prop)**(QMdiArea::WindowOrder *order*) |
| void                    | **[setBackground](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background-prop)**(const QBrush &*background*) |
| void                    | **[setDocumentMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMode-prop)**(bool *enabled*) |
| void                    | **[setOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)**(QMdiArea::AreaOption *option*, bool *on* = true) |
| void                    | **[setTabPosition](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabPosition-prop)**(QTabWidget::TabPosition *position*) |
| void                    | **[setTabShape](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabShape-prop)**(QTabWidget::TabShape *shape*) |
| void                    | **[setTabsClosable](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsClosable-prop)**(bool *closable*) |
| void                    | **[setTabsMovable](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsMovable-prop)**(bool *movable*) |
| void                    | **[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)**(QMdiArea::ViewMode *mode*) |
| QList<QMdiSubWindow *>  | **[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)**(QMdiArea::WindowOrder *order* = CreationOrder) const |
| QTabWidget::TabPosition | **[tabPosition](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabPosition-prop)**() const |
| QTabWidget::TabShape    | **[tabShape](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabShape-prop)**() const |
| bool                    | **[tabsClosable](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsClosable-prop)**() const |
| bool                    | **[tabsMovable](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsMovable-prop)**() const |
| bool                    | **[testOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)**(QMdiArea::AreaOption *option*) const |
| QMdiArea::ViewMode      | **[viewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)**() const |

## 重新实施公共职能

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共老虎机

| void | **[activateNextSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activateNextSubWindow)**() |
| ---- | ------------------------------------------------------------ |
| void | **[activatePreviousSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activatePreviousSubWindow)**() |
| void | **[cascadeSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cascadeSubWindows)**() |
| void | **[closeActiveSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeActiveSubWindow)**() |
| void | **[closeAllSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeAllSubWindows)**() |
| void | **[setActiveSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActiveSubWindow)**(QMdiSubWindow **window*) |
| void | **[tileSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tileSubWindows)**() |

## 信号

| void | **[subWindowActivated](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowActivated)**(QMdiSubWindow **window*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 重新实现受保护的功能

| virtual void | **[childEvent](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childEvent)**(QChildEvent **childEvent*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| virtual bool | **[eventFilter](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)**(QObject **object*, QEvent **event*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **paintEvent*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **resizeEvent*) override |
| virtual void | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent **showEvent*) override |
| virtual void | **[timerEvent](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)**(QTimerEvent **timerEvent*) override |
| virtual bool | **[viewportEvent](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)**(QEvent **event*) override |

## 受保护的插槽

| virtual void | **[setupViewport](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setupViewport)**(QWidget **viewport*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

QMdiArea 的功能本质上类似于 MDI 窗口的窗口管理器。例如，它绘制自己管理的窗口，并将它们排列成层叠或平铺图案。QMdiArea 通常用作[QMainWindow](https://doc-qt-io.translate.goog/qt-6/qmainwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建MDI应用程序，但也可以放置在任何布局中。以下代码向主窗口添加一个区域：

```
    QMainWindow *mainWindow = new QMainWindow;
    mainWindow->setCentralWidget(mdiArea);
```

与顶级窗口的窗口管理器不同，所有窗口标志（[Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)) 只要当前小部件样式支持这些标志，QMdiArea 就支持。如果样式不支持特定标志（例如，[WindowShadeButtonHint](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)），您仍然可以使用 showShaded() 为窗口着色。

QMdiArea 中的子窗口是[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。它们被添加到 MDI 区域[addSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSubWindow)()。常见的是通过一个[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，它被设置为内部小部件，到此函数，但也可以传递一个[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)直接地。类继承[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并且在编程时可以使用与普通顶级窗口相同的 API。[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)还具有特定于 MDI 窗口的行为。请参阅[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类描述以获取更多详细信息。

当子窗口获得键盘焦点时，或者当[setFocus](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus-1)（） 叫做。用户通过以通常的方式移动焦点来激活窗口。MDI 区域发出[subWindowActivated](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowActivated)() 当活动窗口改变时发出信号，并且[activeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeSubWindow)() 函数返回活动子窗口。

便利功能[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)() 返回所有子窗口的列表。例如，该信息可以用在包含窗口列表的弹出菜单中。

子窗口按当前顺序排序[WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)。这用于[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)() 和对于[activateNextSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activateNextSubWindow)（） 和[activatePreviousSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activatePreviousSubWindow)()。此外，它还用于层叠或平铺窗口[cascadeSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cascadeSubWindows)（） 和[tileSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tileSubWindows)()。

QMdiArea 为子窗口提供了两种内置的布局策略：[cascadeSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cascadeSubWindows)（） 和[tileSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tileSubWindows)()。两者都是插槽，可以轻松连接到菜单条目。

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMdiArea\QMdiArea\mdi-cascade.png) | ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMdiArea\QMdiArea\mdi-tile.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

**注意：** QMdiArea 的默认滚动条属性是[Qt::ScrollBarAlwaysOff](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ScrollBarPolicy-enum)。

**也可以看看**[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QMdiArea:: AreaOption 标志 QMdiArea:: AreaOptions

该枚举描述了自定义行为的选项[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

| 持续的                                        | 价值  | 描述                                                         |
| --------------------------------------------- | ----- | ------------------------------------------------------------ |
| `QMdiArea::DontMaximizeSubWindowOnActivation` | `0x1` | 当活动子窗口最大化时，默认行为是最大化下一个激活的子窗口。如果您不希望出现此行为，请设置此选项。 |

AreaOptions 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <AreaOption> 的类型定义。它存储 AreaOption 值的 OR 组合。

### enum QMdiArea::ViewMode

该枚举描述了该区域的视图模式；即如何显示子窗口。

| 持续的                    | 价值 | 描述                                 |
| ------------------------- | ---- | ------------------------------------ |
| `QMdiArea::SubWindowView` | `0`  | 显示带有窗口框架的子窗口（默认）。   |
| `QMdiArea::TabbedView`    | `1`  | 在选项卡栏中显示带有选项卡的子窗口。 |

**也可以看看**[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### enum QMdiArea::WindowOrder

指定用于对返回的子窗口列表进行排序的条件[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)()。功能[cascadeSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cascadeSubWindows)（） 和[tileSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tileSubWindows)() 排列窗口时遵循此顺序。

| 持续的                             | 价值 | 描述                                                   |
| ---------------------------------- | ---- | ------------------------------------------------------ |
| `QMdiArea::CreationOrder`          | `0`  | 窗口按其创建顺序返回。                                 |
| `QMdiArea::StackingOrder`          | `1`  | 窗口按其堆叠顺序返回，最顶层的窗口位于列表的最后一个。 |
| `QMdiArea::ActivationHistoryOrder` | `2`  | 窗口按照它们被激活的顺序返回。                         |

**也可以看看**[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)()。

## 财产文件

### activationOrder : [WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)

该属性保存子窗口列表的排序标准

该属性指定返回的子窗口列表的排序标准[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)()。默认情况下，这是窗口创建顺序。

**访问功能：**

| QMdiArea::WindowOrder | **activationOrder**() const                           |
| --------------------- | ----------------------------------------------------- |
| void                  | **setActivationOrder**(QMdiArea::WindowOrder *order*) |

**也可以看看**[subWindowList](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowList)()。

### background : [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存工作区的背景画笔

该属性设置工作区区域本身的背景画笔。默认情况下，它是灰色的，但可以是任何画笔（例如，颜色、渐变或像素图）。

**访问功能：**

| QBrush | **background**() const                        |
| ------ | --------------------------------------------- |
| void   | **setBackground**(const QBrush &*background*) |

### documentMode : bool

该属性保存选项卡式视图模式下选项卡栏是否设置为文档模式。

默认情况下禁用文档模式。

**访问功能：**

| bool | **documentMode**() const            |
| ---- | ----------------------------------- |
| void | **setDocumentMode**(bool *enabled*) |

**也可以看看**[QTabBar::documentMode](https://doc-qt-io.translate.goog/qt-6/qtabbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#documentMode-prop)和[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### tabPosition : [QTabWidget::TabPosition](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabPosition-enum)

该属性保存选项卡视图模式下选项卡的位置。

该属性的可能值由[QTabWidget::TabPosition](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabPosition-enum)枚举。

**访问功能：**

| QTabWidget::TabPosition | **tabPosition**() const                                |
| ----------------------- | ------------------------------------------------------ |
| void                    | **setTabPosition**(QTabWidget::TabPosition *position*) |

**也可以看看**[QTabWidget::TabPosition](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabPosition-enum)和[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### tabShape : [QTabWidget::TabShape](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabShape-enum)

此属性保存选项卡视图模式下选项卡的形状。

该属性的可能值为[QTabWidget::Rounded](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabShape-enum)（默认）或[QTabWidget::Triangular](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabShape-enum)。

**访问功能：**

| QTabWidget::TabShape | **tabShape**() const                          |
| -------------------- | --------------------------------------------- |
| void                 | **setTabShape**(QTabWidget::TabShape *shape*) |

**也可以看看**[QTabWidget::TabShape](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TabShape-enum)和[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### tabsClosable : bool

此属性保存选项卡栏是否应在选项卡视图模式下的每个选项卡上放置关闭按钮。

默认情况下，选项卡不可关闭。

**访问功能：**

| bool | **tabsClosable**() const             |
| ---- | ------------------------------------ |
| void | **setTabsClosable**(bool *closable*) |

**也可以看看**[QTabBar::tabsClosable](https://doc-qt-io.translate.goog/qt-6/qtabbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabsClosable-prop)和[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### tabsMovable : bool

该属性保存用户是否可以在选项卡视图模式下在选项卡栏区域内移动选项卡。

默认情况下，选项卡不可移动。

**访问功能：**

| bool | **tabsMovable**() const            |
| ---- | ---------------------------------- |
| void | **setTabsMovable**(bool *movable*) |

**也可以看看**[QTabBar::movable](https://doc-qt-io.translate.goog/qt-6/qtabbar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#movable-prop)和[setViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewMode-prop)()。

### viewMode : [ViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)

该属性保存子窗口在窗口中的显示方式[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

默认情况下，[SubWindowView](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum)用于显示子窗口。

**访问功能：**

| QMdiArea::ViewMode | **viewMode**() const                       |
| ------------------ | ------------------------------------------ |
| void               | **setViewMode**(QMdiArea::ViewMode *mode*) |

**也可以看看**[ViewMode](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewMode-enum),[setTabShape](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabShape-prop)（）， 和[setTabPosition](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tabPosition-prop)()。

## 成员函数文档

### QMdiArea::QMdiArea([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的 mdi 区域。*parent*被传递给[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的构造函数。

### `[virtual]`QMdiArea::~QMdiArea()

破坏MDI区域。

### `[slot]`void QMdiArea::activateNextSubWindow()

将键盘焦点赋予子窗口列表中的另一个窗口。激活的窗口将是当前确定的下一个窗口[activation order](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)。

**也可以看看**[activatePreviousSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activatePreviousSubWindow)（） 和[QMdiArea::WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)。

### `[slot]`void QMdiArea::activatePreviousSubWindow()

将键盘焦点赋予子窗口列表中的另一个窗口。激活的窗口将是当前确定的上一个窗口[activation order](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)。

**也可以看看**[activateNextSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activateNextSubWindow)（） 和[QMdiArea::WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)。

### [QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMdiArea::activeSubWindow() const

返回指向当前活动子窗口的指针。如果当前没有活动窗口，`nullptr`则返回。

就窗口状态而言，子窗口被视为顶级窗口，即，如果 MDI 区域之外的小部件是活动窗口，则不会有任何子窗口处于活动状态。请注意，如果 MDI 区域所在窗口中的小部件获得焦点，则该窗口将被激活。

**也可以看看**[setActiveSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActiveSubWindow)（） 和[Qt::WindowState](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowState-enum)。

### [QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMdiArea::addSubWindow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *windowFlags* = Qt::WindowFlags())

添加*widget*作为 MDI 区域的新子窗口。如果*windowFlags*非零，它们将覆盖小部件上设置的标志。

这*widget*可以是[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或其他[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（在这种情况下，MDI区域将创建一个子窗口并设置*widget*作为内部小部件）。

**注意：**添加子窗口后，其父窗口将是该子窗口的*视口小部件*[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

```
    QMdiArea mdiArea;
    QMdiSubWindow *subWindow1 = new QMdiSubWindow;
    subWindow1->setWidget(internalWidget1);
    subWindow1->setAttribute(Qt::WA_DeleteOnClose);
    mdiArea.addSubWindow(subWindow1);

    QMdiSubWindow *subWindow2 =
        mdiArea.addSubWindow(internalWidget2);
```

当你创建自己的子窗口时，你必须设置[Qt::WA_DeleteOnClose](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)如果您希望在 MDI 区域中关闭窗口时删除窗口，则使用 widget 属性。如果没有，该窗口将被隐藏，MDI 区域将不会激活下一个子窗口。

返回[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)添加到 MDI 区域。

**也可以看看**[removeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSubWindow)()。

### `[slot]`void QMdiArea::cascadeSubWindows()

以级联模式排列所有子窗口。

**也可以看看**[tileSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tileSubWindows)()。

### `[override virtual protected]`void QMdiArea::childEvent([QChildEvent](https://doc-qt-io.translate.goog/qt-6/qchildevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **childEvent*)

重新实现：[QObject::childEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childEvent)（QChildEvent *事件）。

### `[slot]`void QMdiArea::closeActiveSubWindow()

关闭活动子窗口。

**也可以看看**[closeAllSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeAllSubWindows)()。

### `[slot]`void QMdiArea::closeAllSubWindows()

通过发送关闭所有子窗口[QCloseEvent](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)到每个窗口。您可能会收到[subWindowActivated](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#subWindowActivated)() 在子窗口关闭之前发出信号（如果 MDI 区域在另一个子窗口关闭时激活子窗口）。

忽略关闭事件的子窗口将保持打开状态。

**也可以看看**[closeActiveSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeActiveSubWindow)()。

### [QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMdiArea::currentSubWindow() const

返回指向当前子窗口的指针，或者`nullptr`如果当前不存在子窗口。

该函数将返回与[activeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeSubWindow)() 如果[QApplication](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)含有[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)活跃。

**也可以看看**[activeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeSubWindow)（） 和[QApplication::activeWindow](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeWindow)()。

### `[override virtual protected]`bool QMdiArea::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::event](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`bool QMdiArea::eventFilter([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **object*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QObject::eventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)（QObject *观看，QEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMdiArea::minimumSizeHint() const

重新实现：[QAbstractScrollArea::minimumSizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)。

### `[override virtual protected]`void QMdiArea::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **paintEvent*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### void QMdiArea::removeSubWindow([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

删除*widget*来自 MDI 区域。这*widget*必须是[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者是子窗口的内部小部件。笔记*widget*实际上从未被删除[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。如果一个[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被传入，其父级被设置`nullptr`为并被删除；但如果传入内部小部件，则子小部件将设置为`nullptr`并且[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)没有*被*删除。

**也可以看看**[addSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSubWindow)()。

### `[override virtual protected]`void QMdiArea::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **resizeEvent*)

重新实现：[QAbstractScrollArea::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[override virtual protected]`void QMdiArea::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

### `[slot]`void QMdiArea::setActiveSubWindow([QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **window*)

激活子窗口*window*。如果*window*即`nullptr`，任何当前活动窗口都将被停用。

**也可以看看**[activeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeSubWindow)()。

### void QMdiArea::setOption([QMdiArea::AreaOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum) *option*, bool *on* = true)

如果*on*是真的，*option*在 MDI 区域启用；否则它会被禁用。看[AreaOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum)对于每个选项的效果。

**也可以看看**[AreaOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum)和[testOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testOption)()。

### `[override virtual protected slot]`void QMdiArea::setupViewport([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **viewport*)

重新实现：[QAbstractScrollArea::setupViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setupViewport)（QWidget *视口）。

这个槽被称为[QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后[setViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)() 已被调用。在子类中重新实现此函数[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)初始化新的*viewport*在使用之前。

**也可以看看**[setViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)()。

### `[override virtual protected]`void QMdiArea::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **showEvent*)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QMdiArea::sizeHint() const

重新实现：[QAbstractScrollArea::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### `[signal]`void QMdiArea::subWindowActivated([QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **window*)

[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)之后发出此信号*window*已被激活。什么时候*window*是`nullptr`,[QMdiArea](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)刚刚停用了最后一个活动窗口，并且工作区上没有活动窗口。

**也可以看看**[QMdiArea::activeSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeSubWindow)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QMdiSubWindow](https://doc-qt-io.translate.goog/qt-6/qmdisubwindow.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QMdiArea::subWindowList([QMdiArea::WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum) *order* = CreationOrder) const

返回 MDI 区域中所有子窗口的列表。如果*order*是[CreationOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)（默认），窗口按照插入工作区的顺序排序。如果*order*是[StackingOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)，窗口按堆叠顺序列出，最上面的窗口是列表中的最后一项。如果*order*是[ActivationHistoryOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)，窗口根据其最近的激活历史记录列出。

**也可以看看**[WindowOrder](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowOrder-enum)。

### bool QMdiArea::testOption([QMdiArea::AreaOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum) *option*) const

返回`true`如果*option*已启用；否则返回`false`.

**也可以看看**[AreaOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AreaOption-enum)和[setOption](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOption)()。

### `[slot]`void QMdiArea::tileSubWindows()

以平铺模式排列所有子窗口。

**也可以看看**[cascadeSubWindows](https://doc-qt-io.translate.goog/qt-6/qmdiarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cascadeSubWindows)()。

### `[override virtual protected]`void QMdiArea::timerEvent([QTimerEvent](https://doc-qt-io.translate.goog/qt-6/qtimerevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **timerEvent*)

重新实现：[QObject::timerEvent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timerEvent)（QTimerEvent *事件）。

### `[override virtual protected]`bool QMdiArea::viewportEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::viewportEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)（QEvent *事件）。