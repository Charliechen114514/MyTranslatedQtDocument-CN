 QDateTimeEdit Class

QDateTimeEdit 类提供了一个用于编辑日期和时间的小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include <QDateTimeEdit>                                     |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QAbstractSpinBox](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) and [QTimeEdit](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[Section](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)** { NoSection, AmPmSection, MSecSection, SecondSection, MinuteSection, …, YearSection } |
| ----- | ------------------------------------------------------------ |
| flags | **[Sections](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)** |

## 特性

| **[calendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)** : bool**[currentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)** : Section**[currentSectionIndex](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSectionIndex-prop)** : int**[date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date-prop)** : QDate**[dateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTime-prop)** : QDateTime**[displayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)** : QString**[displayedSections](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayedSections-prop)** : const Sections**[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)** : QDate | **[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)** : QDateTime**[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)** : QTime**[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)** : QDate**[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)** : QDateTime**[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)** : QTime**[sectionCount](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sectionCount-prop)** : const int**[time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time-prop)** : QTime**[timeSpec](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timeSpec-prop)** : Qt::TimeSpec |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                         | **[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDateTimeEdit)**(QWidget **parent* = nullptr) |
| ----------------------- | ------------------------------------------------------------ |
|                         | **[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDateTimeEdit-1)**(const QDateTime &*datetime*, QWidget **parent* = nullptr) |
|                         | **[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDateTimeEdit-2)**(QDate *date*, QWidget **parent* = nullptr) |
|                         | **[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDateTimeEdit-3)**(QTime *time*, QWidget **parent* = nullptr) |
| virtual                 | **[~QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDateTimeEdit)**() |
| bool                    | **[calendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)**() const |
| QCalendarWidget *       | **[calendarWidget](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarWidget)**() const |
| void                    | **[clearMaximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)**() |
| void                    | **[clearMaximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)**() |
| void                    | **[clearMaximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)**() |
| void                    | **[clearMinimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)**() |
| void                    | **[clearMinimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)**() |
| void                    | **[clearMinimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)**() |
| QDateTimeEdit::Section  | **[currentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)**() const |
| int                     | **[currentSectionIndex](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSectionIndex-prop)**() const |
| QDate                   | **[date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date)**() const |
| QDateTime               | **[dateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTime-prop)**() const |
| QString                 | **[displayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)**() const |
| QDateTimeEdit::Sections | **[displayedSections](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayedSections-prop)**() const |
| QDate                   | **[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)**() const |
| QDateTime               | **[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)**() const |
| QTime                   | **[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)**() const |
| QDate                   | **[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)**() const |
| QDateTime               | **[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)**() const |
| QTime                   | **[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)**() const |
| QDateTimeEdit::Section  | **[sectionAt](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sectionAt)**(int *index*) const |
| int                     | **[sectionCount](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sectionCount-prop)**() const |
| QString                 | **[sectionText](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sectionText)**(QDateTimeEdit::Section *section*) const |
| void                    | **[setCalendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)**(bool *enable*) |
| void                    | **[setCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCalendarWidget)**(QCalendarWidget **calendarWidget*) |
| void                    | **[setCurrentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)**(QDateTimeEdit::Section *section*) |
| void                    | **[setCurrentSectionIndex](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSectionIndex-prop)**(int *index*) |
| void                    | **[setDateRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)**(QDate *min*, QDate *max*) |
| void                    | **[setDateTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTimeRange)**(const QDateTime &*min*, const QDateTime &*max*) |
| void                    | **[setDisplayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)**(const QString &*format*) |
| void                    | **[setMaximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)**(QDate *max*) |
| void                    | **[setMaximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)**(const QDateTime &*dt*) |
| void                    | **[setMaximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)**(QTime *max*) |
| void                    | **[setMinimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)**(QDate *min*) |
| void                    | **[setMinimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)**(const QDateTime &*dt*) |
| void                    | **[setMinimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)**(QTime *min*) |
| void                    | **[setSelectedSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectedSection)**(QDateTimeEdit::Section *section*) |
| void                    | **[setTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTimeRange)**(QTime *min*, QTime *max*) |
| void                    | **[setTimeSpec](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timeSpec-prop)**(Qt::TimeSpec *spec*) |
| QTime                   | **[time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time)**() const |
| Qt::TimeSpec            | **[timeSpec](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timeSpec-prop)**() const |

## 重载公共函数

| virtual void  | **[clear](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() override |
| ------------- | ------------------------------------------------------------ |
| virtual bool  | **[event](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |
| virtual void  | **[stepBy](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepBy)**(int *steps*) override |

## 公共槽

| void | **[setDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date-prop)**(QDate *date*) |
| ---- | ------------------------------------------------------------ |
| void | **[setDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTime-prop)**(const QDateTime &*dateTime*) |
| void | **[setTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time-prop)**(QTime *time*) |

## 信号

| void | **[dateChanged](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateChanged)**(QDate *date*) |
| ---- | ------------------------------------------------------------ |
| void | **[dateTimeChanged](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTimeChanged)**(const QDateTime &*datetime*) |
| void | **[timeChanged](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timeChanged)**(QTime *time*) |

## protected功能

| virtual QDateTime | **[dateTimeFromText](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTimeFromText)**(const QString &*text*) const |
| ----------------- | ------------------------------------------------------------ |
| virtual QString   | **[textFromDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromDateTime)**(const QDateTime &*dateTime*) const |

## 重载的protected功能

| virtual void                          | **[fixup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)**(QString &*input*) const override |
| ------------------------------------- | ------------------------------------------------------------ |
| virtual void                          | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **event*) override |
| virtual bool                          | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void                          | **[initStyleOption](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)**(QStyleOptionSpinBox **option*) const override |
| virtual void                          | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) override |
| virtual void                          | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **event*) override |
| virtual void                          | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual QAbstractSpinBox::StepEnabled | **[stepEnabled](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepEnabled)**() const override |
| virtual QValidator::State             | **[validate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)**(QString &*text*, int &*pos*) const override |
| virtual void                          | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QWheelEvent **event*) override |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\D\QDateTimeEdit\QDateTimeEdit\windows-datetimeedit.png)

QDateTimeEdit 允许用户通过使用键盘或箭头键来增加和减少日期和时间值来编辑日期。箭头键可用于在 QDateTimeEdit 框中从一个部分移动到另一个部分。日期和时间按照设置的格式显示；看[setDisplayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)()。

```
QDateTimeEdit *dateEdit = new QDateTimeEdit(QDate::currentDate());
dateEdit->setMinimumDate(QDate::currentDate().addDays(-365));
dateEdit->setMaximumDate(QDate::currentDate().addDays(365));
dateEdit->setDisplayFormat("yyyy.MM.dd");
```

在这里，我们创建了一个新的 QDateTimeEdit 对象，并用今天的日期进行初始化，并将有效日期范围限制为今天正负 365 天。我们将顺序设置为月、日、年。

QDateTimeEdit 的有效值范围由属性控制[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop),[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)，以及它们各自的日期和时间组成部分。默认情况下，从 100 CE 开始到 9999 CE 结束的任何日期时间均有效。

### 使用弹出式日历小部件

QDateTimeEdit 可以配置为允许[QCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于选择日期。这是通过设置来启用的[calendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)财产。此外，您可以通过调用提供自定义日历小部件作为日历弹出窗口[setCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCalendarWidget)（） 功能。现有的日历小部件可以通过以下方式检索[calendarWidget](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarWidget)()。

### 键盘追踪

什么时候[keyboard tracking](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboardTracking-prop)启用（默认），编辑字段的每次击键都会触发值更改的信号。

当允许的[range](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTimeRange)如果比其末端跨越的某些时间间隔更窄，则键盘跟踪会阻止用户编辑日期或时间以访问该间隔的后面部分。例如，对于从 29.04.2020 到 02.05.2020 的范围以及初始日期 30.04.2020，用户既不能更改月份（5 月 30 日超出范围）也不能更改日期（4 月 2 日超出范围）。

禁用键盘跟踪时，仅当焦点在编辑修改内容后离开文本字段时，才会发出更改信号。这允许用户通过无效的日期时间进行编辑以达到有效的日期时间。

**也可以看看**[QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTimeEdit](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### 枚举 QDateTimeEdit::部分 标志 QDateTimeEdit::部分

| 持续的                         | 价值     |
| ------------------------------ | -------- |
| `QDateTimeEdit::NoSection`     | `0x0000` |
| `QDateTimeEdit::AmPmSection`   | `0x0001` |
| `QDateTimeEdit::MSecSection`   | `0x0002` |
| `QDateTimeEdit::SecondSection` | `0x0004` |
| `QDateTimeEdit::MinuteSection` | `0x0008` |
| `QDateTimeEdit::HourSection`   | `0x0010` |
| `QDateTimeEdit::DaySection`    | `0x0100` |
| `QDateTimeEdit::MonthSection`  | `0x0200` |
| `QDateTimeEdit::YearSection`   | `0x0400` |

Sections 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <Section> 的类型定义。它存储部分值的 OR 组合。

## 属性文档

### calendarPopup : bool

该属性保存当前日历弹出显示模式。

单击箭头按钮后将显示日历弹出窗口。仅当存在有效的日期显示格式时，此属性才有效。

**访问功能：**

| bool | **calendarPopup**() const           |
| ---- | ----------------------------------- |
| void | **setCalendarPopup**(bool *enable*) |

**也可以看看**[setDisplayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)()。

### currentSection : [Section](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)

该属性保存旋转框的当前部分。

**访问功能：**

| QDateTimeEdit::Section | **currentSection**() const                              |
| ---------------------- | ------------------------------------------------------- |
| void                   | **setCurrentSection**(QDateTimeEdit::Section *section*) |

### currentSectionIndex : int

该属性保存旋转框的当前部分索引。

如果格式为“yyyy/MM/dd”，显示文本为“2001/05/21”，且光标位置为 5，则 currentSectionIndex 返回 1。如果光标位置为 3，则 currentSectionIndex 为 0，依此类推。

**访问功能：**

| int  | **currentSectionIndex**() const         |
| ---- | --------------------------------------- |
| void | **setCurrentSectionIndex**(int *index*) |

**也可以看看**[setCurrentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)（） 和[currentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)()。

### date : [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该物业拥有[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)这是在小部件中设置的。

默认情况下，此属性包含 2000 年 1 月 1 日的日期。

**访问功能：**

| QDate | **[date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date)**() const |
| ----- | ------------------------------------------------------------ |
| void  | **setDate**(QDate *date*)                                    |

**通知器信号：**

| void | **[dateChanged](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateChanged)**(QDate *date*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time)和[dateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTime-prop)。

### dateTime : [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该物业拥有[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)即设置在[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

设置此属性时，新的[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)转换为时间系统[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，因此保持不变。

默认情况下，此属性设置为公元 2000 年年初。只能设置为有效的[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。如果任何操作导致此属性的值无效，则会将其重置为[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产。

如果[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)没有日期字段，设置此属性会将小部件的日期范围设置为此属性的新值的日期开始和结束。

**访问功能：**

| QDateTime | **dateTime**() const                         |
| --------- | -------------------------------------------- |
| void      | **setDateTime**(const QDateTime &*dateTime*) |

**通知器信号：**

| void | **[dateTimeChanged](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTimeChanged)**(const QDateTime &*datetime*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date),[time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time),[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)， 和[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)。

### displayFormat : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性保存用于显示日期时间编辑的时间/日期的格式。

该格式的描述见[QDateTime::toString](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toString)（） 和[QDateTime::fromString](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromString)()

格式字符串示例（假设日期是 1969 年 7 月 2 日）：

|   格式    |     结果     |
| :-------: | :----------: |
|  年月日   | 1969年7月2日 |
| MMMM 年年 | 七月 2 日 69 |
| MMMM 年年 | 7 月 2 日 69 |

请注意，如果您指定两位数年份，它将被解释为初始化日期时间编辑的世纪。默认世纪是 21 世纪（2000-2099）。

如果指定无效格式，则不会设置该格式。

**访问功能：**

| QString | **displayFormat**() const                     |
| ------- | --------------------------------------------- |
| void    | **setDisplayFormat**(const QString &*format*) |

**也可以看看**[QDateTime::toString](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toString)（） 和[displayedSections](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayedSections-prop)()。

### `[read-only]`displayedSections : const [Sections](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)

该属性保存当前显示的日期时间编辑字段。

返回此格式的显示部分的位集。

**访问功能：**

| QDateTimeEdit::Sections | **displayedSections**() const |
| ----------------------- | ----------------------------- |
|                         |                               |

**也可以看看**[setDisplayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)（） 和[displayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)()。

### maximumDate : [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存日期时间编辑的最大日期。

更改此属性会更新日期[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)财产，同时保留[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)财产。设置该属性时，[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)如有必要，进行调整以确保范围保持有效。当这种情况发生时，[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)如果属性大于[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)财产。否则，对此属性的更改将保留[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产。

该属性只能设置为有效的[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)描述当前日期的对象[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)属性使有效[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。setMaximumDate() 接受的最晚日期是 9999 CE 结束。这是该属性的默认值。可以使用以下命令恢复此默认值[clearMaximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)()。

**访问功能：**

| QDate | **maximumDate**() const         |
| ----- | ------------------------------- |
| void  | **setMaximumDate**(QDate *max*) |
| void  | **clearMaximumDate**()          |

**也可以看看**[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop),[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop),[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop),[setDateRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)(),[QDate::isValid](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### maximumDateTime : [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性保存日期时间编辑的最大日期时间。

更改此属性会隐式更新[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)和[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)属性分别为此属性的日期和时间部分。设置该属性时，[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)如有必要，进行调整以确保范围保持有效。否则，更改此属性将保留[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产。

该属性只能设置为有效的[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。setMaximumDateTime() 接受的最新日期时间是 9999 CE 结束。这是该属性的默认值。可以使用clearMaximumDateTime()恢复此默认值。

**访问功能：**

| QDateTime | **maximumDateTime**() const                   |
| --------- | --------------------------------------------- |
| void      | **setMaximumDateTime**(const QDateTime &*dt*) |
| void      | **clearMaximumDateTime**()                    |

**也可以看看**[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop),[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop),[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)(),[setDateTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTimeRange)(),[QDateTime::isValid](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### maximumTime : [QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存日期时间编辑的最长时间。

更改此属性会更新时间[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)财产，同时保留[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。如果这些日期属性一致，则在设置此属性时，[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)如有必要，调整属性以确保范围保持有效。否则，更改此属性将保留[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产。

该属性可以设置为任何有效的[QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。默认情况下，此属性包含时间 23:59:59 和 999 毫秒。可以使用clearMaximumTime()恢复此默认值。

**访问功能：**

| QTime | **maximumTime**() const         |
| ----- | ------------------------------- |
| void  | **setMaximumTime**(QTime *max*) |
| void  | **clearMaximumTime**()          |

**也可以看看**[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop),[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop),[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop),[setTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTimeRange)(),[QTime::isValid](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### minimumDate : [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存日期时间编辑的最小日期。

更改此属性会更新日期[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产，同时保留[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)财产。设置该属性时，[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)如有必要，进行调整以确保范围保持有效。当这种情况发生时，[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)如果属性小于[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)财产。否则，对此属性的更改将保留[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)财产。

该属性只能设置为有效的[QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)描述当前日期的对象[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)属性使有效[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。setMinimumDate() 接受的最早日期是公元 100 年的开始日期。该属性的默认日期是公元 1752 年 9 月 14 日。可以使用以下命令恢复此默认值[clearMinimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)()。

**访问功能：**

| QDate | **minimumDate**() const         |
| ----- | ------------------------------- |
| void  | **setMinimumDate**(QDate *min*) |
| void  | **clearMinimumDate**()          |

**也可以看看**[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop),[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop),[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop),[setDateRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)(),[QDate::isValid](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### minimumDateTime : [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

此属性保存日期时间编辑的最小日期时间。

更改此属性会隐式更新[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)属性分别为此属性的日期和时间部分。设置该属性时，[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)如有必要，进行调整以确保范围保持有效。否则，更改此属性将保留[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)财产。

该属性只能设置为有效的[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。setMinimumDateTime() 接受的最早日期时间是 100 CE 的开始。该属性的默认日期是公元 1752 年 9 月 14 日开始。可以使用clearMinimumDateTime()恢复此默认值。

**访问功能：**

| QDateTime | **minimumDateTime**() const                   |
| --------- | --------------------------------------------- |
| void      | **setMinimumDateTime**(const QDateTime &*dt*) |
| void      | **clearMinimumDateTime**()                    |

**也可以看看**[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop),[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop),[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop),[setDateTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTimeRange)(),[QDateTime::isValid](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### minimumTime : [QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存日期时间编辑的最短时间。

更改此属性会更新时间[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产，同时保留[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。如果这些日期属性一致，则在设置此属性时，[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)如有必要，调整属性以确保范围保持有效。否则，更改此属性将保留[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)财产。

该属性可以设置为任何有效的[QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)价值。默认情况下，此属性包含时间 00:00:00 和 0 毫秒。可以使用clearMinimumTime()恢复此默认值。

**访问功能：**

| QTime | **minimumTime**() const         |
| ----- | ------------------------------- |
| void  | **setMinimumTime**(QTime *min*) |
| void  | **clearMinimumTime**()          |

**也可以看看**[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop),[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop),[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop),[setTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTimeRange)(),[QTime::isValid](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### `[read-only]`sectionCount : const int

该属性保存显示的部分数量。如果格式为“yyyy/yy/yyyy”，则sectionCount返回3

**访问功能：**

| int  | **sectionCount**() const |
| ---- | ------------------------ |
|      |                          |

### time : [QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该物业拥有[QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)这是在小部件中设置的。

默认情况下，此属性包含时间 00:00:00 和 0 毫秒。

**访问功能：**

| QTime | **[time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time)**() const |
| ----- | ------------------------------------------------------------ |
| void  | **setTime**(QTime *time*)                                    |

**通知器信号：**

| void | **[timeChanged](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#timeChanged)**(QTime *time*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

**也可以看看**[date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date)和[dateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTime-prop)。

### timeSpec : [Qt::TimeSpec](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TimeSpec-enum)

此属性保存日期时间编辑使用的当前时间规范。

**访问功能：**

| Qt::TimeSpec | **timeSpec**() const                 |
| ------------ | ------------------------------------ |
| void         | **setTimeSpec**(Qt::TimeSpec *spec*) |

## 成员函数文档

### `[explicit]`QDateTimeEdit::QDateTimeEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的日期时间编辑器*parent*。

### `[explicit]`QDateTimeEdit::QDateTimeEdit(const [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*datetime*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的日期时间编辑器*parent*。该值设置为*datetime*。

### `[explicit]`QDateTimeEdit::QDateTimeEdit([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的日期时间编辑器*parent*。该值设置为*date*。

### `[explicit]`QDateTimeEdit::QDateTimeEdit([QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *time*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的日期时间编辑器*parent*。该值设置为*time*。

### `[virtual]`QDateTimeEdit::~QDateTimeEdit()

析构函数。

### [QCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QDateTimeEdit::calendarWidget() const

返回编辑器的日历小部件，如果[calendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)设置为 true 且 (sections() &[DateSections_Mask](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)) != 0。

如果尚未设置，此函数将创建并返回一个日历小部件。

**也可以看看**[setCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCalendarWidget)()。

### `[override virtual]`void QDateTimeEdit::clear()

重新实现：[QAbstractSpinBox::clear](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)()。

### [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDateTimeEdit::date() const

返回日期时间编辑的日期。

**注意：**属性日期的 Getter 函数。

**也可以看看**[setDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date-prop)()。

### `[signal]`void QDateTimeEdit::dateChanged([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*)

每当日期更改时都会发出此信号。新日期已传入*date*。

**注意：**属性的通知程序信号[date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date)。

**也可以看看**[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### `[signal]`void QDateTimeEdit::dateTimeChanged(const [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*datetime*)

每当日期或时间更改时都会发出此信号。新的日期和时间被传入*datetime*。

**注意：**属性的通知程序信号[dateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTime-prop)。

**也可以看看**[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### `[virtual protected]`[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDateTimeEdit::dateTimeFromText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*) const

返回给定的适当日期时间*text*。

每当日期时间编辑需要将用户输入的文本解释为值时，就会使用此虚拟函数。

**也可以看看**[textFromDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFromDateTime)（） 和[validate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)()。

### `[override virtual]`bool QDateTimeEdit::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::event](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual protected]`void QDateTimeEdit::fixup([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*input*) const

重新实现：[QAbstractSpinBox::fixup(QString &input) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixup)。

### `[override virtual protected]`void QDateTimeEdit::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[override virtual protected]`bool QDateTimeEdit::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QDateTimeEdit::initStyleOption([QStyleOptionSpinBox](https://doc-qt-io.translate.goog/qt-6/qstyleoptionspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*) const

重新实现：[QAbstractSpinBox::initStyleOption(QStyleOptionSpinBox *option) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initStyleOption)。

初始化*option*使用此 QDataTimeEdit 中的值。当子类需要时，此方法非常有用[QStyleOptionSpinBox](https://doc-qt-io.translate.goog/qt-6/qstyleoptionspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但不想自己填写所有信息。

**也可以看看**[QStyleOption::initFrom](https://doc-qt-io.translate.goog/qt-6/qstyleoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#initFrom)()。

### `[override virtual protected]`void QDateTimeEdit::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

### `[override virtual protected]`void QDateTimeEdit::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（QMouseEvent *事件）。

### `[override virtual protected]`void QDateTimeEdit::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### [QDateTimeEdit::Section](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum) QDateTimeEdit::sectionAt(int *index*) const

返回节位于*index*。

如果格式为“yyyy/MM/dd”，则sectionAt(0)返回[YearSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)，sectionAt(1) 返回[MonthSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)，sectionAt(2) 返回[YearSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum),

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDateTimeEdit::sectionText([QDateTimeEdit::Section](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum) *section*) const

返回给定的文本*section*。

**也可以看看**[currentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)()。

### void QDateTimeEdit::setCalendarWidget([QCalendarWidget](https://doc-qt-io.translate.goog/qt-6/qcalendarwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **calendarWidget*)

设置给定的*calendarWidget*作为用于日历弹出窗口的小部件。编辑器不会自动取得日历小部件的所有权。

**笔记：**[calendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)在设置日历小部件之前必须设置为 true。

**也可以看看**[calendarWidget](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarWidget)（） 和[calendarPopup](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#calendarPopup-prop)。

### void QDateTimeEdit::setDateRange([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *min*, [QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *max*)

设置日期时间编辑允许的日期范围。

此便利功能设置[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。

```
setDateRange(min, max);
```

类似于：

```
setMinimumDate(min);
setMaximumDate(max);
```

如果其中之一*min*或者*max*无效，该函数不执行任何操作。该函数保留了[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)财产。如果*max*小于*min*， 新的[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)财产应为新的[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)财产。如果*max*等于*min*和[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)财产少于[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)财产，[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)属性设置为[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)财产。否则，这将保留[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)财产。

如果范围比其末尾所跨越的时间间隔更窄，例如跨越月底的一周，则在禁用键盘跟踪的情况下，用户只能将日期编辑为该范围后半部分的日期。

**也可以看看**[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop),[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop),[setDateTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTimeRange)(),[QDate::isValid](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### void QDateTimeEdit::setDateTimeRange(const [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*min*, const [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*max*)

设置日期时间编辑允许的日期时间范围。

此便利功能设置[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop)和[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop)特性。

```
setDateTimeRange(min, max);
```

类似于：

```
setMinimumDateTime(min);
setMaximumDateTime(max);
```

如果其中之一*min*或者*max*无效，该函数不执行任何操作。如果*max*小于*min*,*min*也用作*max*。

如果范围比其末尾所跨越的时间间隔更窄，例如跨越月底的一周，则在禁用键盘跟踪的情况下，用户只能将日期时间编辑为该范围后面的部分。

**也可以看看**[minimumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDateTime-prop),[maximumDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDateTime-prop),[setDateRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateRange)(),[setTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTimeRange)(),[QDateTime::isValid](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### void QDateTimeEdit::setSelectedSection([QDateTimeEdit::Section](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum) *section*)

选择*section*。如果*section*当前显示的部分中不存在，该函数不执行任何操作。如果*section*是[NoSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Section-enum)，此函数将取消选择编辑器中的所有文本。否则，此功能会将光标和当前部分移动到所选部分。

**也可以看看**[currentSection](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentSection-prop)()。

### void QDateTimeEdit::setTimeRange([QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *min*, [QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *max*)

设置日期时间编辑的允许时间范围。

此便利功能设置[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)和[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)特性。

请注意，这些仅分别限制日期时间编辑的值[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)。当这些日期属性不一致时，时间晚于*max*允许在之前的日期[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)和之前的时间*min*允许在以下日期使用[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)。

```
setTimeRange(min, max);
```

类似于：

```
setMinimumTime(min);
setMaximumTime(max);
```

如果其中之一*min*或者*max*无效，该函数不执行任何操作。该函数保留了[minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)和[maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)特性。如果这些属性一致并且*max*小于*min*,*min*用作*max*。

如果范围比其末尾所跨越的时间间隔更窄，例如从十点到一小时到同一小时过十点的间隔，则如果键盘跟踪是，用户只能将时间编辑为该范围的后半部分。禁用。

**也可以看看**[minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop),[maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop),[setDateTimeRange](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDateTimeRange)(),[QTime::isValid](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)（）， 和[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDateTimeEdit::sizeHint() const

重新实现：[QAbstractSpinBox::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### `[override virtual]`void QDateTimeEdit::stepBy(int *steps*)

重新实现：[QAbstractSpinBox::stepBy](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepBy)（整数步骤）。

### `[override virtual protected]`[QAbstractSpinBox::StepEnabled](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StepEnabledFlag-enum) QDateTimeEdit::stepEnabled() const

重新实现：[QAbstractSpinBox::stepEnabled() const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stepEnabled)。

### `[virtual protected]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDateTimeEdit::textFromDateTime(const [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dateTime*) const

日期时间编辑在需要显示时使用此虚拟函数*dateTime*。

如果你重新实现这个，你可能还需要重新实现[validate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)()。

**也可以看看**[dateTimeFromText](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dateTimeFromText)（） 和[validate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)()。

### [QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDateTimeEdit::time() const

返回日期时间编辑的时间。

**注意：**属性时间的 getter 函数。

**也可以看看**[setTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time-prop)()。

### `[signal]`void QDateTimeEdit::timeChanged([QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *time*)

每当时间改变时就会发出该信号。新的时间已传入*time*。

**注意：**属性的通知程序信号[time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time)。

**也可以看看**[Keyboard Tracking](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyboard-tracking)。

### `[override virtual protected]`[QValidator::State](https://doc-qt-io.translate.goog/qt-6/qvalidator.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#State-enum) QDateTimeEdit::validate([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, int &*pos*) const

重新实现：[QAbstractSpinBox::validate(QString &input, int &pos) const](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#validate)。

### `[override virtual protected]`void QDateTimeEdit::wheelEvent([QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractSpinBox::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qabstractspinbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)（QWheelEvent *事件）。