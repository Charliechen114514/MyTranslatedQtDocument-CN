#  QTimeEdit Class

QTimeEdit 类提供了一个用于编辑时间的小部件[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QTimeEdit>                                        |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtimeedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共职能

|         | **[QTimeEdit](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTimeEdit)**(QWidget **parent* = nullptr) |
| ------- | ------------------------------------------------------------ |
|         | **[QTimeEdit](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTimeEdit-1)**(QTime *time*, QWidget **parent* = nullptr) |
| virtual | **[~QTimeEdit](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTimeEdit)**() |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\T\QTimeEdit\QTimeEdit\windows-timeedit.png)

QTimeEdit 提供的许多属性和功能都是在[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这些是该类的相关属性：

- [time](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#time)保存小部件显示的时间。
- [minimumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumTime-prop)定义用户可以设置的最小（最早）时间。
- [maximumTime](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumTime-prop)定义用户可以设置的最大（最晚）时间。
- [displayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)包含一个用于格式化小部件中显示的时间的字符串。

**也可以看看**[QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### `[explicit]`QTimeEdit::QTimeEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的时间编辑器*parent*。

### `[explicit]`QTimeEdit::QTimeEdit([QTime](https://doc-qt-io.translate.goog/qt-6/qtime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *time*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的时间编辑器*parent*。时间设置为*time*。

### `[virtual]`QTimeEdit::~QTimeEdit()

析构函数。