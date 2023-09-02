#  QCalendarWidget Class

QCalendarWidget 类提供基于每月的日历小部件，允许用户选择日期。[更多的...](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QCalendarWidget>                                   |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[HorizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HorizontalHeaderFormat-enum)** { SingleLetterDayNames, ShortDayNames, LongDayNames, NoHorizontalHeader } |
| ---- | ------------------------------------------------------------ |
| enum | **[SelectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)** { NoSelection, SingleSelection } |
| enum | **[VerticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerticalHeaderFormat-enum)** { ISOWeekNumbers, NoVerticalHeader } |

## 特性

| **[dateEditAcceptDelay](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditAcceptDelay-prop)** : int**[dateEditEnabled](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditEnabled-prop)** : bool**[firstDayOfWeek](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstDayOfWeek-prop)** : Qt::DayOfWeek**[gridVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridVisible-prop)** : bool**[horizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderFormat-prop)** : HorizontalHeaderFormat**[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)** : QDate | **[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)** : QDate**[navigationBarVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#navigationBarVisible-prop)** : bool**[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)** : QDate**[selectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)** : SelectionMode**[verticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderFormat-prop)** : VerticalHeaderFormat |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                                         | **[QCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QCalendarWidget)**(QWidget **parent* = nullptr) |
| --------------------------------------- | ------------------------------------------------------------ |
| virtual                                 | **[~QCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QCalendarWidget)**() |
| int                                     | **[dateEditAcceptDelay](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditAcceptDelay-prop)**() const |
| QMap<QDate, QTextCharFormat>            | **[dateTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTextFormat)**() const |
| QTextCharFormat                         | **[dateTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTextFormat-1)**(QDate *date*) const |
| Qt::DayOfWeek                           | **[firstDayOfWeek](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstDayOfWeek-prop)**() const |
| QTextCharFormat                         | **[headerTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerTextFormat)**() const |
| QCalendarWidget::HorizontalHeaderFormat | **[horizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderFormat-prop)**() const |
| bool                                    | **[isDateEditEnabled](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditEnabled-prop)**() const |
| bool                                    | **[isGridVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridVisible-prop)**() const |
| bool                                    | **[isNavigationBarVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#navigationBarVisible-prop)**() const |
| QDate                                   | **[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)**() const |
| QDate                                   | **[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)**() const |
| int                                     | **[monthShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#monthShown)**() const |
| QDate                                   | **[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)**() const |
| QCalendarWidget::SelectionMode          | **[selectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)**() const |
| void                                    | **[setDateEditAcceptDelay](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditAcceptDelay-prop)**(int *delay*) |
| void                                    | **[setDateEditEnabled](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditEnabled-prop)**(bool *enable*) |
| void                                    | **[setDateTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTextFormat)**(QDate *date*, const QTextCharFormat &*format*) |
| void                                    | **[setFirstDayOfWeek](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstDayOfWeek-prop)**(Qt::DayOfWeek *dayOfWeek*) |
| void                                    | **[setHeaderTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderTextFormat)**(const QTextCharFormat &*format*) |
| void                                    | **[setHorizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderFormat-prop)**(QCalendarWidget::HorizontalHeaderFormat *format*) |
| void                                    | **[setMaximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)**(QDate *date*) |
| void                                    | **[setMinimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)**(QDate *date*) |
| void                                    | **[setSelectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)**(QCalendarWidget::SelectionMode *mode*) |
| void                                    | **[setVerticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderFormat-prop)**(QCalendarWidget::VerticalHeaderFormat *format*) |
| void                                    | **[setWeekdayTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWeekdayTextFormat)**(Qt::DayOfWeek *dayOfWeek*, const QTextCharFormat &*format*) |
| QCalendarWidget::VerticalHeaderFormat   | **[verticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderFormat-prop)**() const |
| QTextCharFormat                         | **[weekdayTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#weekdayTextFormat)**(Qt::DayOfWeek *dayOfWeek*) const |
| int                                     | **[yearShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#yearShown)**() const |

## 重载的公共职能

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共槽

| void | **[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)**(int *year*, int *month*) |
| ---- | ------------------------------------------------------------ |
| void | **[setDateRange](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)**(QDate *min*, QDate *max*) |
| void | **[setGridVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridVisible-prop)**(bool *show*) |
| void | **[setNavigationBarVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#navigationBarVisible-prop)**(bool *visible*) |
| void | **[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)**(QDate *date*) |
| void | **[showNextMonth](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showNextMonth)**() |
| void | **[showNextYear](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showNextYear)**() |
| void | **[showPreviousMonth](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showPreviousMonth)**() |
| void | **[showPreviousYear](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showPreviousYear)**() |
| void | **[showSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showSelectedDate)**() |
| void | **[showToday](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showToday)**() |

## 信号

| void | **[activated](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)**(QDate *date*) |
| ---- | ------------------------------------------------------------ |
| void | **[clicked](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clicked)**(QDate *date*) |
| void | **[currentPageChanged](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPageChanged)**(int *year*, int *month*) |
| void | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**() |

## protected function

| virtual void | **[paintCell](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintCell)**(QPainter **painter*, const QRect &*rect*, QDate *date*) const |
| ------------ | ------------------------------------------------------------ |
| void         | **[updateCell](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateCell)**(QDate *date*) |
| void         | **[updateCells](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateCells)**() |

## 重载的protected function

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[eventFilter](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)**(QObject **watched*, QEvent **event*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **event*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **event*) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QCalendarWidget\QCalendarWidget\fusion-calendarwidget.png)

该小部件使用当前月份和年份进行初始化，但 QCalendarWidget 提供了多个公共插槽来更改显示的年份和月份。

默认情况下，选择今天的日期，用户可以使用鼠标和键盘选择日期。可以使用以下命令检索当前选择的日期[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)（） 功能。可以通过设置将用户选择限制在给定的日期范围内[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。或者，可以使用以下命令一次性设置这两个属性[setDateRange](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)() 便利槽。设置[selectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)财产给[NoSelection](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)完全禁止用户选择。请注意，也可以使用以下命令以编程方式选择日期[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)（） 投币口。

可以使用以下命令检索当前显示的月份和年份[monthShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#monthShown)（） 和[yearShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#yearShown)() 函数分别。

新创建的日历小部件使用缩写的日期名称，周六和周日都标记为红色。日历网格不可见。将显示周数，第一列日是日历区域设置一周的第一天。

通过设置可以将日期的表示法更改为单个字母缩写（“M”代表“星期一”）[horizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderFormat-prop)财产给[QCalendarWidget::SingleLetterDayNames](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HorizontalHeaderFormat-enum)。将相同的属性设置为[QCalendarWidget::LongDayNames](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HorizontalHeaderFormat-enum)使标题显示完整的日期名称。可以通过设置删除周数[verticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderFormat-prop)财产给[QCalendarWidget::NoVerticalHeader](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerticalHeaderFormat-enum)。可以通过设置来打开日历网格[gridVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridVisible-prop)属性为 true 使用[setGridVisible](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gridVisible-prop)（） 功能：

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QCalendarWidget\QCalendarWidget\qcalendarwidget-grid.png) |
| ------------------------------------------------------------ |
| `QCalendarWidget *calendar; calendar->setGridVisible(true);` |

最后，可以使用以下命令更改第一列中的日期[setFirstDayOfWeek](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#firstDayOfWeek-prop)（） 功能。

QCalendarWidget 类还提供了三个信号，[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)(),[activated](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activated)（） 和[currentPageChanged](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPageChanged)() 使得响应用户交互成为可能。

标题、工作日或单日的呈现可以通过设置在很大程度上自定义[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于某些特殊的工作日、特殊的日期或用于呈现标题。

仅属性的一个子集[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)由日历小部件使用。目前，前景、背景和字体属性用于确定小部件中各个单元格的呈现。

**也可以看看**[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QCalendarWidget::HorizontalHeaderFormat

该枚举类型定义了水平标题可以显示的各种格式。

| 持续的                                  | 价值 | 描述                                                 |
| --------------------------------------- | ---- | ---------------------------------------------------- |
| `QCalendarWidget::SingleLetterDayNames` | `1`  | 标题显示日期名称的单字母缩写（例如，M 表示星期一）。 |
| `QCalendarWidget::ShortDayNames`        | `2`  | 标题显示日期名称的简短缩写（例如 Mon 表示星期一）。  |
| `QCalendarWidget::LongDayNames`         | `3`  | 标题显示完整的日期名称（例如星期一）。               |
| `QCalendarWidget::NoHorizontalHeader`   | `0`  | 标题被隐藏。                                         |

**也可以看看**[horizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalHeaderFormat-prop)（） 和[VerticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerticalHeaderFormat-enum)。

### enum QCalendarWidget::SelectionMode

该枚举描述了为用户提供的用于在日历中选择日期的选择类型。

| 持续的                             | 价值 | 描述               |
| ---------------------------------- | ---- | ------------------ |
| `QCalendarWidget::NoSelection`     | `0`  | 无法选择日期。     |
| `QCalendarWidget::SingleSelection` | `1`  | 可以选择单个日期。 |

**也可以看看**[selectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionMode-prop)。

### enum QCalendarWidget::VerticalHeaderFormat

该枚举类型定义了垂直标题可以显示的各种格式。

| 持续的                              | 价值 | 描述                                                         |
| ----------------------------------- | ---- | ------------------------------------------------------------ |
| `QCalendarWidget::ISOWeekNumbers`   | `1`  | 标题显示 ISO 周数，如下所述[QDate::weekNumber](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#weekNumber)()。 |
| `QCalendarWidget::NoVerticalHeader` | `0`  | 标题被隐藏。                                                 |

**也可以看看**[verticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalHeaderFormat-prop)（） 和[HorizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HorizontalHeaderFormat-enum)。

## 属性文档

### dateEditAcceptDelay : int

此属性保存在接受其内容之前显示非活动日期编辑的时间

如果日历小部件的[date edit is enabled](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditEnabled-prop)，此属性指定在最近的用户输入之后日期编辑保持打开状态的时间量（以毫秒为单位）。一旦过了这个时间，日期编辑中指定的日期就会被接受并关闭弹出窗口。

默认情况下，延迟定义为 1500 毫秒（1.5 秒）。

**访问功能：**

| int  | **dateEditAcceptDelay**() const         |
| ---- | --------------------------------------- |
| void | **setDateEditAcceptDelay**(int *delay*) |

### dateEditEnabled : bool

该属性保存是否启用日期编辑弹出窗口

如果启用此属性，则在日历小部件具有焦点时按非修饰键将弹出日期编辑，允许用户以当前区域设置指定的形式指定日期。

默认情况下，此属性处于启用状态。

日期编辑在外观上比[QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但允许用户使用左右光标键在字段之间导航，使用向上和向下光标键递增和递减各个字段，以及直接使用数字键输入值。

**访问功能：**

| bool | **isDateEditEnabled**() const         |
| ---- | ------------------------------------- |
| void | **setDateEditEnabled**(bool *enable*) |

**也可以看看**[QCalendarWidget::dateEditAcceptDelay](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateEditAcceptDelay-prop)。

### firstDayOfWeek : [Qt::DayOfWeek](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DayOfWeek-enum)

该属性保存一个值，用于标识第一列中显示的日期。

默认情况下，第一列中显示的日期是日历区域设置一周的第一天。

**访问功能：**

| Qt::DayOfWeek | **firstDayOfWeek**() const                       |
| ------------- | ------------------------------------------------ |
| void          | **setFirstDayOfWeek**(Qt::DayOfWeek *dayOfWeek*) |

### gridVisible : bool

该属性保存是否显示表格网格。

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QCalendarWidget\QCalendarWidget\qcalendarwidget-grid.png) |
| ------------------------------------------------------------ |
| `QCalendarWidget *calendar; calendar->setGridVisible(true);` |

默认值为 false。

**访问功能：**

| bool | **isGridVisible**() const       |
| ---- | ------------------------------- |
| void | **setGridVisible**(bool *show*) |

### horizontalHeaderFormat : [HorizontalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HorizontalHeaderFormat-enum)

该属性保存水平标题的格式。

默认值为[QCalendarWidget::ShortDayNames](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HorizontalHeaderFormat-enum)。

**访问功能：**

| QCalendarWidget::HorizontalHeaderFormat | **horizontalHeaderFormat**() const                           |
| --------------------------------------- | ------------------------------------------------------------ |
| void                                    | **setHorizontalHeaderFormat**(QCalendarWidget::HorizontalHeaderFormat *format*) |

### maximumDate : [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存当前指定日期范围的最大日期。

用户将无法选择当前设置的最大日期之后的日期。

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QCalendarWidget\QCalendarWidget\qcalendarwidget-maximum.png) |
| ------------------------------------------------------------ |
| `QCalendarWidget *calendar; calendar->setGridVisible(true); calendar->setMaximumDate(QDate(2006, 7, 3));` |

默认情况下，最大日期是最后一天[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类可以处理。

设置最大日期时，[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)如果选择范围无效，则调整属性。如果提供的日期无效[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象时，setMaximumDate() 函数不执行任何操作。

**访问功能：**

| QDate | **maximumDate**() const          |
| ----- | -------------------------------- |
| void  | **setMaximumDate**(QDate *date*) |

**也可以看看**[setDateRange](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)()。

### minimumDate : [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存当前指定日期范围的最小日期。

用户将无法选择当前设置的最短日期之前的日期。

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\C\QCalendarWidget\QCalendarWidget\qcalendarwidget-minimum.png) |
| ------------------------------------------------------------ |
| `QCalendarWidget *calendar; calendar->setGridVisible(true); calendar->setMinimumDate(QDate(2006, 6, 19));` |

默认情况下，最小日期是最早的日期[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类可以处理。

设置最短日期时，[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)和[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)如果选择范围无效，则调整属性。如果提供的日期无效[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象时，setMinimumDate() 函数不执行任何操作。

**访问功能：**

| QDate | **minimumDate**() const          |
| ----- | -------------------------------- |
| void  | **setMinimumDate**(QDate *date*) |

**也可以看看**[setDateRange](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)()。

### navigationBarVisible : bool

该属性保存导航栏是否显示

当此属性为`true`（默认）时，下个月、上个月、月份选择、年份选择控件显示在顶部。

当该属性设置为 false 时，这些控件将被隐藏。

**访问功能：**

| bool | **isNavigationBarVisible**() const          |
| ---- | ------------------------------------------- |
| void | **setNavigationBarVisible**(bool *visible*) |

### selectedDate : [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存当前选择的日期。

所选日期必须在指定的日期范围内[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。默认情况下，所选日期是当前日期。

**访问功能：**

| QDate | **selectedDate**() const          |
| ----- | --------------------------------- |
| void  | **setSelectedDate**(QDate *date*) |

**也可以看看**[setDateRange](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)()。

### selectionMode : [SelectionMode](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)

该属性保存用户可以在日历中进行的选择类型

当该属性设置为[SingleSelection](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，用户可以使用鼠标或键盘在允许的最小和最大日期内选择日期。

当该属性设置为[NoSelection](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，用户将无法选择日期，但仍然可以通过编程方式选择日期。请注意，该属性设置为时选择的日期[NoSelection](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)仍将是日历中选定的日期。

默认值为[SingleSelection](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)。

**访问功能：**

| QCalendarWidget::SelectionMode | **selectionMode**() const                                   |
| ------------------------------ | ----------------------------------------------------------- |
| void                           | **setSelectionMode**(QCalendarWidget::SelectionMode *mode*) |

### verticalHeaderFormat : [VerticalHeaderFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerticalHeaderFormat-enum)

该属性保存垂直标题的格式。

默认值为 QCalendarWidget::ISOWeekNumber。

**访问功能：**

| QCalendarWidget::VerticalHeaderFormat | **verticalHeaderFormat**() const                             |
| ------------------------------------- | ------------------------------------------------------------ |
| void                                  | **setVerticalHeaderFormat**(QCalendarWidget::VerticalHeaderFormat *format*) |

## 成员函数文档

### `[explicit]`QCalendarWidget::QCalendarWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

使用给定的构造一个日历小部件*parent*。

该小部件使用当前月份和年份进行初始化，当前选择的日期是今天。

**也可以看看**[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)()。

### `[virtual]`QCalendarWidget::~QCalendarWidget()

销毁日历小部件。

### `[signal]`void QCalendarWidget::activated([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*)

每当用户按下 Return 或 Enter 键或双击某个按钮时，就会发出此信号*date*在日历小部件中。

### `[signal]`void QCalendarWidget::clicked([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*)

单击鼠标按钮时会发出此信号。鼠标单击的日期由以下方式指定*date*。仅当单击有效日期时才会发出该信号，例如日期不在规定范围内[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)（） 和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)()。如果选择模式是[NoSelection](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SelectionMode-enum)，该信号将不会被发射。

### `[signal]`void QCalendarWidget::currentPageChanged(int *year*, int *month*)

当前显示的月份更改时会发出此信号。新的*year*和*month*作为参数传递。

**也可以看看**[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)()。

### [QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> QCalendarWidget::dateTextFormat() const

返回一个[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)从[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)到[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)显示使用特殊格式改变其呈现的所有日期。

**也可以看看**[setDateTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTextFormat)()。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCalendarWidget::dateTextFormat([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*) const

返回一个[QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)为了*date*。如果没有专门渲染日期，char格式可以为空。

### `[override virtual protected]`bool QCalendarWidget::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`bool QCalendarWidget::eventFilter([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **watched*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QObject::eventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)（QObject *观看，QEvent *事件）。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCalendarWidget::headerTextFormat() const

返回用于呈现标题的文本字符格式。

**也可以看看**[setHeaderTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderTextFormat)()。

### `[override virtual protected]`void QCalendarWidget::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCalendarWidget::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### int QCalendarWidget::monthShown() const

返回当前显示的月份。月份编号为 1 到 12。

**也可以看看**[yearShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#yearShown)（） 和[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)()。

### `[override virtual protected]`void QCalendarWidget::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[virtual protected]`void QCalendarWidget::paintCell([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*) const

绘制给定指定的单元格*date*，使用给定的*painter*和*rect*。

### `[override virtual protected]`void QCalendarWidget::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### `[signal]`void QCalendarWidget::selectionChanged()

当前选择的日期更改时会发出此信号。

当前选择的日期可以由用户使用鼠标或键盘更改，也可以由程序员使用[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)()。

**也可以看看**[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)()。

### `[slot]`void QCalendarWidget::setCurrentPage(int *year*, int *month*)

显示给定的*month*给定的*year*而不更改所选日期。使用[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)() 函数更改所选日期。

可以使用以下命令检索当前显示的月份和年份[monthShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#monthShown)（） 和[yearShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#yearShown)() 函数分别。

**也可以看看**[yearShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#yearShown)(),[monthShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#monthShown)(),[showPreviousMonth](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showPreviousMonth)(),[showNextMonth](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showNextMonth)(),[showPreviousYear](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showPreviousYear)（）， 和[showNextYear](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showNextYear)()。

### `[slot]`void QCalendarWidget::setDateRange([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *min*, [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *max*)

通过设置来定义日期范围[minimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。

日期范围限制了用户的选择，即用户只能选择指定日期范围内的日期。注意

```
QCalendarWidget *calendar;

calendar->setDateRange(min, max);
```

类似于

```
QCalendarWidget *calendar;

calendar->setMinimumDate(min);
calendar->setMaximumDate(max);
```

如果任一*min*或者*max*参数无效[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，这个函数什么也不做。

**也可以看看**[setMinimumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)（） 和[setMaximumDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)()。

### void QCalendarWidget::setDateTextFormat([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*, const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置用于渲染给定的格式*date*到指定的*format*。

如果*date*为空，所有日期格式都被清除。

**也可以看看**[dateTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTextFormat)()。

### void QCalendarWidget::setHeaderTextFormat(const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置用于呈现标题的文本字符格式*format*。如果您还设置了工作日文本格式，则该格式的前景色和背景色将优先于标题的格式。其他格式信息仍然由标头的格式决定。

**也可以看看**[headerTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerTextFormat)()。

### void QCalendarWidget::setWeekdayTextFormat([Qt::DayOfWeek](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DayOfWeek-enum) *dayOfWeek*, const [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*format*)

设置用于呈现一周中的某一天的文本字符格式*dayOfWeek*到*format*。在前景色和背景色的情况下，该格式将优先于标题格式。其他文本格式信息取自标题格式。

**也可以看看**[weekdayTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#weekdayTextFormat)（） 和[setHeaderTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setHeaderTextFormat)()。

### `[slot]`void QCalendarWidget::showNextMonth()

显示相对于当前显示月份的下一个月。请注意，所选日期不会更改。

**也可以看看**[showPreviousMonth](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showPreviousMonth)(),[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)（）， 和[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)()。

### `[slot]`void QCalendarWidget::showNextYear()

显示相对于当前显示年份的下一年中当前显示的*月份*。请注意，所选日期不会更改。

**也可以看看**[showPreviousYear](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showPreviousYear)(),[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)（）， 和[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)()。

### `[slot]`void QCalendarWidget::showPreviousMonth()

显示相对于当前显示月份的上个月。请注意，所选日期不会更改。

**也可以看看**[showNextMonth](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showNextMonth)(),[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)（）， 和[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)()。

### `[slot]`void QCalendarWidget::showPreviousYear()

显示相对于*当前*显示年份的上一年当前显示的月份。请注意，所选日期不会更改。

**也可以看看**[showNextYear](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showNextYear)(),[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)（）， 和[setSelectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)()。

### `[slot]`void QCalendarWidget::showSelectedDate()

显示所选日期的月份。

**也可以看看**[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)（） 和[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)()。

### `[slot]`void QCalendarWidget::showToday()

显示今天日期的月份。

**也可以看看**[selectedDate](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedDate-prop)（） 和[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)()。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCalendarWidget::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。

### `[protected]`void QCalendarWidget::updateCell([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*)

更新给定指定的单元格*date*除非禁用更新或隐藏单元格。

**也可以看看**[updateCells](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateCells)(),[yearShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#yearShown)（）， 和[monthShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#monthShown)()。

### `[protected]`void QCalendarWidget::updateCells()

更新所有可见单元格，除非禁用更新。

**也可以看看**[updateCell](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateCell)()。

### [QTextCharFormat](https://doc-qt-io.translate.goog/qt-6/qtextcharformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QCalendarWidget::weekdayTextFormat([Qt::DayOfWeek](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DayOfWeek-enum) *dayOfWeek*) const

返回用于呈现一周中的某一天的文本字符格式*dayOfWeek*。

**也可以看看**[setWeekdayTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWeekdayTextFormat)（） 和[headerTextFormat](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#headerTextFormat)()。

### int QCalendarWidget::yearShown() const

返回当前显示月份的年份。月份编号为 1 到 12。

**也可以看看**[monthShown](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#monthShown)（） 和[setCurrentPage](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrentPage)()。