#  QMessageBox Class

QMessageBox 类提供了一个模式对话框，用于通知用户或向用户询问问题并接收答案。[更多的...](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QMessageBox >                                     |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qmessagebox-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qmessagebox-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QMessageBox 是[标准对话框](https://doc-qt-io.translate.goog/qt-6/standard-dialogs.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| enum  | **[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)** { InvalidRole, AcceptRole, RejectRole, DestructiveRole, ActionRole, …, ResetRole } |
| ----- | ------------------------------------------------------------ |
| enum  | **[Icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)** { NoIcon, Question, Information, Warning, Critical } |
| enum  | **[StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)** { Ok, Open, Save, Cancel, Close, …, ButtonMask } |
| flags | **[StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)** |

## 特性

| **[detailedText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)** : QString**[icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)** : Icon**[iconPixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)** : QPixmap**[informativeText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)** : QString | **[standardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)** : StandardButtons**[text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)** : QString**[textFormat](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)** : Qt::TextFormat**[textInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)** : Qt::TextInteractionFlags |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共方法

|                              | **[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMessageBox)**(QWidget **parent* = nullptr) |
| ---------------------------- | ------------------------------------------------------------ |
|                              | **[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QMessageBox-1)**(QMessageBox::Icon *icon*, const QString &*title*, const QString &*text*, QMessageBox::StandardButtons *buttons* = NoButton, QWidget **parent* = nullptr, Qt::WindowFlags *f* = Qt::Dialog \| Qt::MSWindowsFixedSizeDialogHint) |
| virtual                      | **[~QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QMessageBox)**() |
| void                         | **[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)**(QAbstractButton **button*, QMessageBox::ButtonRole *role*) |
| QPushButton *                | **[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton-1)**(const QString &*text*, QMessageBox::ButtonRole *role*) |
| QPushButton *                | **[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton-2)**(QMessageBox::StandardButton *button*) |
| QAbstractButton *            | **[button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#button)**(QMessageBox::StandardButton *which*) const |
| QMessageBox::ButtonRole      | **[buttonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonRole)**(QAbstractButton **button*) const |
| QList<QAbstractButton *>     | **[buttons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)**() const |
| QCheckBox *                  | **[checkBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkBox)**() const |
| QAbstractButton *            | **[clickedButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clickedButton)**() const |
| QPushButton *                | **[defaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultButton)**() const |
| QString                      | **[detailedText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)**() const |
| QAbstractButton *            | **[escapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#escapeButton)**() const |
| QMessageBox::Icon            | **[icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)**() const |
| QPixmap                      | **[iconPixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)**() const |
| QString                      | **[informativeText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)**() const |
| void                         | **[open](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)**(QObject **receiver*, const char **member*) |
| void                         | **[removeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)**(QAbstractButton **button*) |
| void                         | **[setCheckBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckBox)**(QCheckBox **cb*) |
| void                         | **[setDefaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultButton)**(QPushButton **button*) |
| void                         | **[setDefaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultButton-1)**(QMessageBox::StandardButton *button*) |
| void                         | **[setDetailedText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)**(const QString &*text*) |
| void                         | **[setEscapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEscapeButton)**(QAbstractButton **button*) |
| void                         | **[setEscapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEscapeButton-1)**(QMessageBox::StandardButton *button*) |
| void                         | **[setIcon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)**(QMessageBox::Icon) |
| void                         | **[setIconPixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)**(const QPixmap &*pixmap*) |
| void                         | **[setInformativeText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)**(const QString &*text*) |
| void                         | **[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)**(QMessageBox::StandardButtons *buttons*) |
| void                         | **[setText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)**(const QString &*text*) |
| void                         | **[setTextFormat](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)**(Qt::TextFormat *format*) |
| void                         | **[setTextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)**(Qt::TextInteractionFlags *flags*) |
| void                         | **[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)**(Qt::WindowModality *windowModality*) |
| void                         | **[setWindowTitle](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowTitle)**(const QString &*title*) |
| QMessageBox::StandardButton  | **[standardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButton)**(QAbstractButton **button*) const |
| QMessageBox::StandardButtons | **[standardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)**() const |
| QString                      | **[text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)**() const |
| Qt::TextFormat               | **[textFormat](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)**() const |
| Qt::TextInteractionFlags     | **[textInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textInteractionFlags-prop)**() const |

## 公共槽

| virtual int | **[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)**() override |
| ----------- | ------------------------------------------------------------ |
|             |                                                              |

## 信号

| void | **[buttonClicked](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonClicked)**(QAbstractButton **button*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 静态公共成员

| void                        | **[about](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#about)**(QWidget **parent*, const QString &*title*, const QString &*text*) |
| --------------------------- | ------------------------------------------------------------ |
| void                        | **[aboutQt](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#aboutQt)**(QWidget **parent*, const QString &*title* = QString()) |
| QMessageBox::StandardButton | **[critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#critical)**(QWidget **parent*, const QString &*title*, const QString &*text*, QMessageBox::StandardButtons *buttons* = Ok, QMessageBox::StandardButton *defaultButton* = NoButton) |
| QMessageBox::StandardButton | **[information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#information)**(QWidget **parent*, const QString &*title*, const QString &*text*, QMessageBox::StandardButtons *buttons* = Ok, QMessageBox::StandardButton *defaultButton* = NoButton) |
| QMessageBox::StandardButton | **[question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#question)**(QWidget **parent*, const QString &*title*, const QString &*text*, QMessageBox::StandardButtons *buttons* = StandardButtons(Yes \| No), QMessageBox::StandardButton *defaultButton* = NoButton) |
| QMessageBox::StandardButton | **[warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#warning)**(QWidget **parent*, const QString &*title*, const QString &*text*, QMessageBox::StandardButtons *buttons* = Ok, QMessageBox::StandardButton *defaultButton* = NoButton) |

## 重载的保护函数

| virtual void | **[changeEvent](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)**(QEvent **ev*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[closeEvent](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)**(QCloseEvent **e*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **e*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **event*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent **e*) override |

## 详细说明

消息框显示主要[text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)提醒用户某种情况，[informative text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)进一步解释情况，以及可选的[detailed text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)如果用户请求提供更多数据。

消息框还可以显示[icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)和[standard buttons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)用于接受用户响应。

提供了两个使用 QMessageBox 的 API：基于属性的 API 和静态函数。调用静态函数之一是一种更简单的方法，但它不如使用基于属性的 API 灵活，而且结果的信息量也较少。建议使用基于属性的 API。

### 基于属性的 API

要使用基于属性的 API，请构造 QMessageBox 的实例，设置所需的属性，然后调用[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 显示消息。最简单的配置是只设置[message text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)财产。

```
QMessageBox msgBox;
msgBox.setText("The document has been modified.");
msgBox.exec();
```

用户必须单击**OK**按钮以关闭消息框。GUI 的其余部分将被阻止，直到消息框消失。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\msgbox1.png)

比仅仅提醒用户某个事件更好的方法是询问用户如何处理该事件。

设置[standard buttons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)属性到您想要作为用户响应集的按钮集。这些按钮是通过组合以下值来指定的[StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)使用按位或运算符。按钮的显示顺序取决于平台。例如，在 Windows 上，**Save**显示在左侧**Cancel**，而在 macOS 上，顺序相反。将您的标准按钮之一标记为您的[default button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultButton)。

这[informative text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)属性可用于添加附加上下文以帮助用户选择适当的操作。

```
QMessageBox msgBox;
msgBox.setText("The document has been modified.");
msgBox.setInformativeText("Do you want to save your changes?");
msgBox.setStandardButtons(QMessageBox::Save | QMessageBox::Discard | QMessageBox::Cancel);
msgBox.setDefaultButton(QMessageBox::Save);
int ret = msgBox.exec();
```

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\msgbox2.png)

这[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 槽返回[StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)单击的按钮的值。

```
switch (ret) {
  case QMessageBox::Save:
      // Save was clicked
      break;
  case QMessageBox::Discard:
      // Don't Save was clicked
      break;
  case QMessageBox::Cancel:
      // Cancel was clicked
      break;
  default:
      // should never be reached
      break;
}
```

为了给用户更多的信息来帮助他们选择合适的操作，设置[detailed text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)财产。根据平台的不同[detailed text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)，可能需要用户单击**Show Details...**要显示的按钮。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\msgbox3.png)

单击**Show Details...**按钮显示详细文本。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\msgbox4.png)

#### 富文本和文本格式属性

这[detailed text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)属性始终被解释为纯文本。这[main text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)和[informative text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)属性可以是纯文本或富文本。这些字符串根据设置进行解释[text format](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)财产。默认设置是[auto-text](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFormat-enum)。

请注意，对于某些包含 XML 元字符的纯文本字符串，自动文本[rich text detection test](https://doc-qt-io.translate.goog/qt-6/qt-sub-qtgui.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mightBeRichText)可能会失败，导致您的纯文本字符串被错误地解释为富文本。在这些罕见的情况下，使用[Qt::convertFromPlainText](https://doc-qt-io.translate.goog/qt-6/qt-sub-qtgui.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#convertFromPlainText)() 将纯文本字符串转换为视觉上等效的富文本字符串，或设置[text format](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)属性明确地与[setTextFormat](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)()。

#### 严重级别以及图标和像素图属性

QMessageBox 支持四种预定义的消息严重性级别或消息类型，它们实际上仅在各自显示的预定义图标上有所不同。通过设置指定四种预定义消息类型之一[icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)财产归其中之一[predefined icons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)。以下规则为指导原则：

| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\qmessagebox-quest.png) | [Question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum) | 用于在正常操作期间提出问题。 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------- |
| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\qmessagebox-info.png) | [Information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum) | 用于报告有关正常操作的信息。 |
| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\qmessagebox-warn.png) | [Warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum) | 用于报告非严重错误。         |
| ![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\M\QMessageBox\QMessageBox\qmessagebox-crit.png) | [Critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum) | 用于报告严重错误。           |

[Predefined icons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)不是由 QMessageBox 定义的，而是由样式提供的。默认值为[No Icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)。对于所有情况，消息框在其他方面都是相同的。使用标准图标时，请使用表中推荐的图标，或使用适合您平台的样式指南推荐的图标。如果没有一个标准图标适合您的消息框，您可以通过设置来使用自定义图标[icon pixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)属性而不是设置[icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)财产。

总之，要设置图标，请*使用* [setIcon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)() 代表标准图标之一，*或* [setIconPixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)() 用于自定义图标。

### 静态函数 API

使用静态函数 API 构建消息框虽然方便，但不如使用基于属性的 API 灵活，因为静态函数签名缺少用于设置消息框的参数。[informative text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)和[detailed text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)特性。解决此问题的一种方法是使用参数`title`作为消息框主要文本，并将`text`参数作为消息框信息文本。因为这有一个明显的缺点，即消息框的可读性较差，所以平台指南不推荐它。Microsoft *Windows 用户界面指南*建议使用[application name](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#applicationName-prop)作为[window's title](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowTitle)，这意味着如果除了主文本之外还有信息性文本，则必须将其连接到参数`text`。

请注意，静态函数签名已更改其按钮参数，这些参数现在用于设置[standard buttons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)和[default button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultButton)。

静态函数可用于创建[information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#information)(),[question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#question)(),[warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#warning)（）， 和[critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#critical)() 消息框。

```
int ret = QMessageBox::warning(this, tr("My Application"),
                               tr("The document has been modified.\n"
                                  "Do you want to save your changes?"),
                               QMessageBox::Save | QMessageBox::Discard
                               | QMessageBox::Cancel,
                               QMessageBox::Save);
```

这[Standard Dialogs](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-standarddialogs-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)示例展示了如何使用 QMessageBox 和其他内置 Qt 对话框。

### 高级用法

如果[standard buttons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)对于您的消息框来说不够灵活，您可以使用[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)() 重载需要一个文本和一个[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)添加自定义按钮。这[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)QMessageBox 使用它来确定屏幕上按钮的顺序（根据平台的不同而有所不同）。您可以测试以下值[clickedButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clickedButton)() 调用后[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()。例如，

```
QMessageBox msgBox;
QPushButton *connectButton = msgBox.addButton(tr("Connect"), QMessageBox::ActionRole);
QPushButton *abortButton = msgBox.addButton(QMessageBox::Abort);

msgBox.exec();

if (msgBox.clickedButton() == connectButton) {
    // connect
} else if (msgBox.clickedButton() == abortButton) {
    // abort
}
```

### 默认键和退出键

默认按钮（即，当**Enter**被按下）可以使用指定[setDefaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultButton)()。如果未指定默认按钮，QMessageBox 会尝试根据[button roles](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)消息框中使用的按钮。

退出按钮（该按钮在以下情况下激活）**Esc**被按下）可以使用指定[setEscapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEscapeButton)()。如果未指定转义按钮，QMessageBox 会尝试使用以下规则查找转义按钮：

1. 如果只有一个按钮，则该按钮是在以下情况下激活的按钮：**Esc**被按下。
2. 如果有一个[Cancel](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)按钮，它是激活时的按钮**Esc**被按下。
3. 如果恰好有一个按钮具有其中之一[the Reject role](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)或者[the No role](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)，它是激活时的按钮**Esc**被按下。

当使用这些规则无法确定退出按钮时，请按**Esc**没有影响。

**也可以看看**[QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Standard Dialogs Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-standarddialogs-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和 Qt Widgets - 应用程序示例。

## 会员类型文档

### enum QMessageBox::ButtonRole

该枚举描述了可用于描述按钮框中按钮的角色。这些角色的组合就像用于描述其行为的不同方面的标志。

| 持续的                         | 价值 | 描述                                                     |
| ------------------------------ | ---- | -------------------------------------------------------- |
| `QMessageBox::InvalidRole`     | `-1` | 该按钮无效。                                             |
| `QMessageBox::AcceptRole`      | `0`  | 单击该按钮会使对话框被接受（例如“确定”）。               |
| `QMessageBox::RejectRole`      | `1`  | 单击该按钮会导致对话框被拒绝（例如取消）。               |
| `QMessageBox::DestructiveRole` | `2`  | 单击该按钮会导致破坏性更改（例如放弃更改）并关闭对话框。 |
| `QMessageBox::ActionRole`      | `3`  | 单击该按钮会导致对话框中的元素发生更改。                 |
| `QMessageBox::HelpRole`        | `4`  | 可以单击该按钮来请求帮助。                               |
| `QMessageBox::YesRole`         | `5`  | 该按钮是类似“是”的按钮。                                 |
| `QMessageBox::NoRole`          | `6`  | 该按钮是类似“否”的按钮。                                 |
| `QMessageBox::ApplyRole`       | `8`  | 该按钮应用当前更改。                                     |
| `QMessageBox::ResetRole`       | `7`  | 该按钮将对话框的字段重置为默认值。                       |

**也可以看看**[StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)。

### enum QMessageBox::Icon

该枚举具有以下值：

| 持续的                     | 价值 | 描述                                     |
| -------------------------- | ---- | ---------------------------------------- |
| `QMessageBox::NoIcon`      | `0`  | 消息框没有任何图标。                     |
| `QMessageBox::Question`    | `4`  | 指示该消息正在询问问题的图标。           |
| `QMessageBox::Information` | `1`  | 一个图标，表明该消息没有什么异常。       |
| `QMessageBox::Warning`     | `2`  | 一个图标，表明该消息是警告，但可以处理。 |
| `QMessageBox::Critical`    | `3`  | 指示该消息代表严重问题的图标。           |

### 枚举 QMessageBox:: StandardButton 标志 QMessageBox:: StandardButtons

这些枚举描述了标准按钮的标志。每个按钮都有一个定义的[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。

| 持续的                         | 价值         | 描述                                                         |
| ------------------------------ | ------------ | ------------------------------------------------------------ |
| `QMessageBox::Ok`              | `0x00000400` | 定义的“确定”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Open`            | `0x00002000` | 定义的“打开”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Save`            | `0x00000800` | 定义的“保存”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Cancel`          | `0x00400000` | 定义的“取消”按钮[RejectRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Close`           | `0x00200000` | 定义的“关闭”按钮[RejectRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Discard`         | `0x00800000` | “放弃”或“不保存”按钮，具体取决于平台，由[DestructiveRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Apply`           | `0x02000000` | 定义的“应用”按钮[ApplyRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Reset`           | `0x04000000` | 一个“重置”按钮定义为[ResetRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::RestoreDefaults` | `0x08000000` | 定义的“恢复默认值”按钮[ResetRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Help`            | `0x01000000` | 定义的“帮助”按钮[HelpRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::SaveAll`         | `0x00001000` | 定义的“全部保存”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Yes`             | `0x00004000` | “是”按钮定义为[YesRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::YesToAll`        | `0x00008000` | “全部同意”按钮定义为[YesRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::No`              | `0x00010000` | “否”按钮定义为[NoRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::NoToAll`         | `0x00020000` | “全部拒绝”按钮定义为[NoRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Abort`           | `0x00040000` | “中止”按钮定义为[RejectRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Retry`           | `0x00080000` | 定义的“重试”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::Ignore`          | `0x00100000` | 定义的“忽略”按钮[AcceptRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)。 |
| `QMessageBox::NoButton`        | `0x00000000` | 无效按钮。                                                   |

以下值已过时：

| 持续的                    | 价值         | 描述                                                         |
| ------------------------- | ------------ | ------------------------------------------------------------ |
| `QMessageBox::YesAll`     | `YesToAll`   | 请改用 YesToAll。                                            |
| `QMessageBox::NoAll`      | `NoToAll`    | 请改用 NoToAll。                                             |
| `QMessageBox::Default`    | `0x00000100` | 使用`defaultButton`以下参数[information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#information)(),[warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#warning)() 等代替，或调用[setDefaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultButton)()。 |
| `QMessageBox::Escape`     | `0x00000200` | 称呼[setEscapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEscapeButton)（） 反而。 |
| `QMessageBox::FlagMask`   | `0x00000300` |                                                              |
| `QMessageBox::ButtonMask` | `~FlagMask`  |                                                              |

StandardButtons 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <StandardButton> 的类型定义。它存储 StandardButton 值的 OR 组合。

**也可以看看**[ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)和[standardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)。

## 财产文件

### detailedText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存要在详细信息区域中显示的文本。

该文本将被解释为纯文本。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **detailedText**() const                   |
| ------- | ------------------------------------------ |
| void    | **setDetailedText**(const QString &*text*) |

**也可以看看**[QMessageBox::text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)和[QMessageBox::informativeText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)。

### icon : [Icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)

该属性保存消息框的图标

消息框的图标可以用以下值之一指定：

- [QMessageBox::NoIcon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)
- [QMessageBox::Question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)
- [QMessageBox::Information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)
- [QMessageBox::Warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)
- [QMessageBox::Critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)

默认为[QMessageBox::NoIcon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum)。

用于显示实际图标的像素图取决于当前[GUI style](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)。您还可以通过设置图标来设置自定义像素图[icon pixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)财产。

**访问功能：**

| QMessageBox::Icon | **icon**() const               |
| ----------------- | ------------------------------ |
| void              | **setIcon**(QMessageBox::Icon) |

**也可以看看**[iconPixmap](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#iconPixmap-prop)。

### iconPixmap : [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存当前图标

消息框当前使用的图标。请注意，通常很难绘制一张看起来适合所有 GUI 风格的像素图；您可能想为每个平台提供不同的像素图。

默认情况下，该属性是未定义的。

**访问功能：**

| QPixmap | **iconPixmap**() const                     |
| ------- | ------------------------------------------ |
| void    | **setIconPixmap**(const QPixmap &*pixmap*) |

**也可以看看**[icon](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon)。

### informativeText : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性包含信息文本，为消息提供更完整的描述

信息性文本可用于扩展[text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)() 向用户提供更多信息，例如描述情况的后果，或建议替代解决方案。

默认情况下，该属性包含一个空字符串。

**访问功能：**

| QString | **informativeText**() const                   |
| ------- | --------------------------------------------- |
| void    | **setInformativeText**(const QString &*text*) |

**也可以看看**[QMessageBox::text](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)和[QMessageBox::detailedText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)。

### standardButtons : [StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)

消息框中标准按钮的集合

该属性控制消息框使用哪些标准按钮。

默认情况下，此属性不包含标准按钮。

**访问功能：**

| QMessageBox::StandardButtons | **standardButtons**() const                                  |
| ---------------------------- | ------------------------------------------------------------ |
| void                         | **setStandardButtons**(QMessageBox::StandardButtons *buttons*) |

**也可以看看**[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### text : [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存要显示的消息框文本。

文本应该是描述情况的简短句子或短语，最好是中立的陈述或号召性用语问题。

文本将被解释为纯文本或富文本，具体取决于文本格式设置（[QMessageBox::textFormat](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop)）。默认设置是[Qt::AutoText](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFormat-enum)，即消息框将尝试自动检测文本的格式。

该属性的默认值为空字符串。

**访问功能：**

| QString | **text**() const                   |
| ------- | ---------------------------------- |
| void    | **setText**(const QString &*text*) |

**也可以看看**[textFormat](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textFormat-prop),[QMessageBox::informativeText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#informativeText-prop)， 和[QMessageBox::detailedText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#detailedText-prop)。

### textFormat : [Qt::TextFormat](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFormat-enum)

该属性保存消息框显示的文本格式

消息框当前使用的文本格式。请参阅[Qt::TextFormat](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFormat-enum)枚举以解释可能的选项。

默认格式是[Qt::AutoText](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFormat-enum)。

**访问功能：**

| Qt::TextFormat | **textFormat**() const                     |
| -------------- | ------------------------------------------ |
| void           | **setTextFormat**(Qt::TextFormat *format*) |

**也可以看看**[setText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)()。

### textInteractionFlags : [Qt::TextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextInteractionFlag-enum)

指定消息框的标签应如何与用户输入交互。

默认值取决于样式。

**访问功能：**

| Qt::TextInteractionFlags | **textInteractionFlags**() const                             |
| ------------------------ | ------------------------------------------------------------ |
| void                     | **setTextInteractionFlags**(Qt::TextInteractionFlags *flags*) |

**也可以看看**[QStyle::SH_MessageBox_TextInteractionFlags](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleHint-enum)。

## 成员函数文档

### `[explicit]`QMessageBox::QMessageBox([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)没有文本和按钮的消息框。*parent*被传递到[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

窗口模式可以通过重写[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)() 调用之前[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)()。

**注意：**使用[open](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)（） 或者[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 显示的消息框影响窗口模态。请参阅每个功能的详细文档以获取更多信息。

在 macOS 上，如果您希望消息框显示为[Qt::Sheet](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)其*parent*，设置消息框的[window modality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)到[Qt::WindowModal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)或使用[open](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)()。否则，消息框将是一个标准对话框。

**也可以看看**[setWindowTitle](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowTitle)(),[setText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)(),[setIcon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)(),[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)（）， 和[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)()。

### QMessageBox::QMessageBox([QMessageBox::Icon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Icon-enum) *icon*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QMessageBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons* = NoButton, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *f* = Qt::Dialog | Qt::MSWindowsFixedSizeDialogHint)

构造一个[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)带有给定信息的消息框*icon*,*title*,*text*，和标准*buttons*。可以随时使用添加标准或自定义按钮[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。这*parent*和*f*参数被传递给[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

窗口模式可以通过重写[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)() 调用之前[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)()。

**注意：**使用[open](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)（） 或者[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 显示的消息框影响窗口模态。请参阅每个功能的详细文档以获取更多信息。

在 macOS 上，如果*parent*不是`nullptr`，并且您希望消息框显示为[Qt::Sheet](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)该父级的，设置消息框的[window modality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)到[Qt::WindowModal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)（默认）。否则，消息框将是一个标准对话框。

**也可以看看**[setWindowTitle](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowTitle)(),[setText](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#text-prop)(),[setIcon](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#icon-prop)(),[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)（）， 和[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindowModality)()。

### `[virtual]`QMessageBox::~QMessageBox()

销毁消息框。

### `[static]`void QMessageBox::about([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

显示一个带有标题的简单“关于”框*title*和文字*text*。关于框的父级是*parent*。

about() 在四个位置寻找合适的图标：

1. 它更喜欢[parent->icon](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowIcon-prop)() 如果存在的话。
2. 如果没有，它会尝试包含的顶级小部件*parent*。
3. 如果失败，它会尝试[active window.](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeWindow)
4. 作为最后的手段，它使用信息图标。

关于框有一个标记为“确定”的按钮。在 macOS 上，“关于”框以无模式窗口的形式弹出；在其他平台上，目前是应用程序模式。

**也可以看看**[QWidget::windowIcon](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowIcon-prop)（） 和[QApplication::activeWindow](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeWindow)()。

### `[static]`void QMessageBox::aboutQt([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title* = QString())

显示一个关于 Qt 的简单消息框，其中包含给定的内容*title*并以*parent*（如果*parent*不是`nullptr`）。该消息包括应用程序正在使用的 Qt 版本号。

这对于包含在**Help**应用程序的菜单，如图所示[Menus](https://doc-qt-io.translate.goog/qt-6/qtwidgets-mainwindows-menus-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)例子。

[QApplication](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为插槽提供此功能。

在 macOS 上，“关于”框以无模式窗口的形式弹出；在其他平台上，目前是应用程序模式。

**也可以看看**[QApplication::aboutQt](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#aboutQt)()。

### void QMessageBox::addButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*, [QMessageBox::ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum) *role*)

添加给定的*button*到消息框指定*role*。

**也可以看看**[removeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)(),[button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#button)（）， 和[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)()。

### [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::addButton(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QMessageBox::ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum) *role*)

这是一个过载功能。

使用给定的值创建一个按钮*text*，将其添加到指定的消息框中*role*，并返回它。

### [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::addButton([QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *button*)

这是一个过载功能。

添加一个标准*button*如果这样做有效，则发送到消息框，并返回按钮。

**也可以看看**[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)()。

### [QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::button([QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *which*) const

返回对应于标准按钮的指针*which*，或者`nullptr`如果此消息框中不存在标准按钮。

**也可以看看**[standardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)和[standardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButton)()。

### `[signal]`void QMessageBox::buttonClicked([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*)

每当单击内部按钮时就会发出此信号[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。被点击的按钮返回了*button*。

### [QMessageBox::ButtonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum) QMessageBox::buttonRole([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*) const

返回指定按钮的角色*button*。该函数返回[InvalidRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)如果*button*已`nullptr`添加或尚未添加到消息框。

**也可以看看**[buttons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttons)（） 和[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QMessageBox::buttons() const

返回已添加到消息框的所有按钮的列表。

**也可以看看**[buttonRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonRole)(),[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（）， 和[removeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeButton)()。

### `[override virtual protected]`void QMessageBox::changeEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **ev*)

重新实现：[QWidget::changeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changeEvent)（QEvent *事件）。

### [QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::checkBox() const

返回对话框中显示的复选框。这是`nullptr`如果未设置复选框的情况。

**也可以看看**[setCheckBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCheckBox)()。

### [QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::clickedButton() const

返回用户单击的按钮，或者`nullptr`如果用户单击**Esc**钥匙和没有[escape button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEscapeButton)已设置。

如果[exec](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 尚未被调用，返回 nullptr。

例子：

```
QMessageBox messageBox(this);
QAbstractButton *disconnectButton =
      messageBox.addButton(tr("Disconnect"), QMessageBox::ActionRole);
...
messageBox.exec();
if (messageBox.clickedButton() == disconnectButton) {
    ...
}
```

**也可以看看**[standardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButton)（） 和[button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#button)()。

### `[override virtual protected]`void QMessageBox::closeEvent([QCloseEvent](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QDialog::closeEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)(QCloseEvent *e)。

### `[static]`[QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) QMessageBox::critical([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QMessageBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons* = Ok, [QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *defaultButton* = NoButton)

使用给定的信息打开关键消息框*title*和*text*在指定的前面*parent*小部件。

标准*buttons*被添加到消息框中。*defaultButton*指定时使用的按钮**Enter**被按下。*defaultButton*必须引用在中给出的按钮*buttons*。如果*defaultButton*是[QMessageBox::NoButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum),[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)自动选择合适的默认值。

返回被单击的标准按钮的标识。如果**Esc**相反，被按下[escape button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-and-escape-keys)被返回。

消息框是一个[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)对话框。

**警告：**请勿删除*parent*在对话框执行期间。如果您想这样做，您应该使用其中之一自己创建对话框[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#question)(),[warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#warning)（）， 和[information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#information)()。

### [QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::defaultButton() const

返回应该是消息框的按钮[default button](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)。如果未设置默认按钮，则返回 nullptr。

**也可以看看**[setDefaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultButton)(),[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（）， 和[QPushButton::setDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)()。

### [QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QMessageBox::escapeButton() const

返回按下 escape 时激活的按钮。

默认情况下，[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)尝试自动检测退出按钮，如下所示：

1. 如果只有一个按钮，则将其设为退出按钮。
2. 如果有一个[Cancel](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)按钮，它被做成了退出按钮。
3. 仅在 macOS 上，如果只有一个具有该角色的按钮[QMessageBox::RejectRole](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ButtonRole-enum)，它被做成了退出按钮。

当无法自动检测到退出按钮时，按**Esc**没有影响。

**也可以看看**[setEscapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEscapeButton)（） 和[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)()。

### `[override virtual protected]`bool QMessageBox::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::event](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### `[override virtual slot]`int QMessageBox::exec()

重新实现：[QDialog::exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()。

将消息框显示为[modal dialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-dialogs)，阻塞直到用户关闭它。

当使用[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对于标准按钮，此函数返回一个[StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)指示单击的标准按钮的值。使用时[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对于自定义按钮，此函数返回一个不透明的值；使用[clickedButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clickedButton)() 来确定单击了哪个按钮。

注**：**[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)() 函数也返回[StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)值而不是[QDialog::DialogCode](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)。

在通过单击按钮或使用窗口系统提供的机制关闭对话框之前，用户无法与同一应用程序中的任何其他窗口进行交互。

**也可以看看**[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)（） 和[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)()。

### `[static]`[QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) QMessageBox::information([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QMessageBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons* = Ok, [QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *defaultButton* = NoButton)

打开带有给定信息的信息消息框*title*和*text*在指定的前面*parent*小部件。

标准*buttons*被添加到消息框中。*defaultButton*指定时使用的按钮**Enter**被按下。*defaultButton*必须引用在中给出的按钮*buttons*。如果*defaultButton*是[QMessageBox::NoButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum),[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)自动选择合适的默认值。

返回被单击的标准按钮的标识。如果**Esc**相反，被按下[escape button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-and-escape-keys)被返回。

消息框是一个[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)对话框。

**警告：**请勿删除*parent*在对话框执行期间。如果您想这样做，您应该使用其中之一自己创建对话框[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#question)(),[warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#warning)（）， 和[critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#critical)()。

### `[override virtual protected]`void QMessageBox::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QDialog::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

### void QMessageBox::open([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **receiver*, const char **member*)

打开对话框并连接其[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)（） 或者[buttonClicked](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonClicked)() 向由指定的槽发出信号*receiver*和*member*。如果槽位在*member*有一个指向连接的第一个参数的指针[buttonClicked](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#buttonClicked)()，否则连接为[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)()。

当对话框关闭时，信号将从插槽断开。

### `[static]`[QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) QMessageBox::question([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QMessageBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons* = StandardButtons(Yes | No), [QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *defaultButton* = NoButton)

打开一个问题消息框，其中包含给定的内容*title*和*text*在指定的前面*parent*小部件。

标准*buttons*被添加到消息框中。*defaultButton*指定时使用的按钮**Enter**被按下。*defaultButton*必须引用在中给出的按钮*buttons*。如果*defaultButton*是[QMessageBox::NoButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum),[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)自动选择合适的默认值。

返回被单击的标准按钮的标识。如果**Esc**相反，被按下[escape button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-and-escape-keys)被返回。

消息框是一个[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)对话框。

**警告：**请勿删除*parent*在对话框执行期间。如果您想这样做，您应该使用其中之一自己创建对话框[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#information)(),[warning](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#warning)（）， 和[critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#critical)()。

### void QMessageBox::removeButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*)

删除*button*从按钮框中删除它。

**也可以看看**[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（） 和[setStandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)()。

### `[override virtual protected]`void QMessageBox::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QDialog::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *）。

### void QMessageBox::setCheckBox([QCheckBox](https://doc-qt-io.translate.goog/qt-6/qcheckbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **cb*)

设置复选框*cb*在消息对话框上。消息框拥有复选框的所有权。论据*cb*可以是`nullptr`从消息框中删除现有的复选框。

**也可以看看**[checkBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#checkBox)()。

### void QMessageBox::setDefaultButton([QPushButton](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*)

设置消息框的[default button](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)到*button*。

**也可以看看**[defaultButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#defaultButton)(),[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（）， 和[QPushButton::setDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)()。

### void QMessageBox::setDefaultButton([QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *button*)

设置消息框的[default button](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)到*button*。

**也可以看看**[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（） 和[QPushButton::setDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)()。

### void QMessageBox::setEscapeButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*)

设置当按下按钮时激活的按钮**Escape**键被按下*button*。

**也可以看看**[escapeButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#escapeButton)(),[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（）， 和[clickedButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clickedButton)()。

### void QMessageBox::setEscapeButton([QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *button*)

设置当按下按钮时激活的按钮**Escape**键被按下*button*。

**也可以看看**[addButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addButton)（） 和[clickedButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clickedButton)()。

### void QMessageBox::setWindowModality([Qt::WindowModality](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum) *windowModality*)

这个函数有阴影[QWidget::setWindowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop)()。

将消息框的模式设置为*windowModality*。

在 macOS 上，如果模式设置为[Qt::WindowModal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)并且消息框有一个父级，那么消息框将是[Qt::Sheet](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)，否则消息框将是一个标准对话框。

### void QMessageBox::setWindowTitle(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*)

这个函数有阴影[QWidget::setWindowTitle](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowTitle-prop)()。

将消息框的标题设置为*title*。在 macOS 上，窗口标题将被忽略（根据 macOS 指南的要求）。

### `[override virtual protected]`void QMessageBox::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QDialog::showEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### [QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) QMessageBox::standardButton([QAbstractButton](https://doc-qt-io.translate.goog/qt-6/qabstractbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **button*) const

返回与给定对应的标准按钮枚举值*button*， 或者[NoButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)如果给定*button*不是标准按钮。

**也可以看看**[button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#button)（） 和[standardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#standardButtons-prop)()。

### `[static]`[QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) QMessageBox::warning([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*title*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QMessageBox::StandardButtons](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *buttons* = Ok, [QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum) *defaultButton* = NoButton)

打开一个警告消息框，其中包含给定的内容*title*和*text*在指定的前面*parent*小部件。

标准*buttons*被添加到消息框中。*defaultButton*指定时使用的按钮**Enter**被按下。*defaultButton*必须引用在中给出的按钮*buttons*。如果*defaultButton*是[QMessageBox::NoButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum),[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)自动选择合适的默认值。

返回被单击的标准按钮的标识。如果**Esc**相反，被按下[escape button](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-and-escape-keys)被返回。

消息框是一个[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)对话框。

**警告：**请勿删除*parent*在对话框执行期间。如果您想这样做，您应该使用其中之一自己创建对话框[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[question](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#question)(),[information](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#information)（）， 和[critical](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#critical)()。