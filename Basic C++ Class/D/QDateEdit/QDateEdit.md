#  QDateEdit Class

QDateEdit 类提供了一个用于编辑日期的小部件[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)小部件。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include <QDateEdit>                                         |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdateedit-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共职能

|         | **[QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDateEdit)**(QWidget **parent* = nullptr) |
| ------- | ------------------------------------------------------------ |
|         | **[QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDateEdit-1)**(QDate *date*, QWidget **parent* = nullptr) |
| virtual | **[~QDateEdit](https://doc-qt-io.translate.goog/qt-6/qdateedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDateEdit)**() |

## 详细说明

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\D\QDateEdit\QDateEdit\windows-dateedit.png)

QDateEdit 提供的许多属性和功能都是在[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这些是该类的相关属性：

- [date](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#date)保存小部件显示的日期。
- [minimumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumDate-prop)定义用户可以设置的最小（最早）日期。
- [maximumDate](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maximumDate-prop)定义用户可以设置的最大（最新）日期。
- [displayFormat](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#displayFormat-prop)包含一个用于格式化小部件中显示的日期的字符串。

**也可以看看**[QTimeEdit](https://doc-qt-io.translate.goog/qt-6/qtimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QDateTimeEdit](https://doc-qt-io.translate.goog/qt-6/qdatetimeedit.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### `[explicit]`QDateEdit::QDateEdit([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的日期编辑器*parent*。

### `[explicit]`QDateEdit::QDateEdit([QDate](https://doc-qt-io.translate.goog/qt-6/qdate.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *date*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个空的日期编辑器*parent*。日期设置为*date*。

### `[virtual]`QDateEdit::~QDateEdit()

析构函数。