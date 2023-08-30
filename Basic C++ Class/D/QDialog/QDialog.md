#  QDialog Class

QDialog 类是对话框窗口的基类。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include <QDialog>                                           |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherits:     | [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QColorDialog](https://doc-qt-io.translate.goog/qt-6/qcolordialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QErrorMessage](https://doc-qt-io.translate.goog/qt-6/qerrormessage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QFontDialog](https://doc-qt-io.translate.goog/qt-6/qfontdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QInputDialog](https://doc-qt-io.translate.goog/qt-6/qinputdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QProgressDialog](https://doc-qt-io.translate.goog/qt-6/qprogressdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QWizard](https://doc-qt-io.translate.goog/qt-6/qwizard.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdialog-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum | **[DialogCode](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)** { Accepted, Rejected } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 特性

- **[modal](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-prop)** : bool
- **[sizeGripEnabled](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeGripEnabled-prop)** : bool

## 公共方法

|         | **[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDialog)**(QWidget **parent* = nullptr, Qt::WindowFlags *f* = Qt::WindowFlags()) |
| ------- | ------------------------------------------------------------ |
| virtual | **[~QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDialog)**() |
| bool    | **[isSizeGripEnabled](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeGripEnabled-prop)**() const |
| int     | **[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)**() const |
| void    | **[setModal](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-prop)**(bool *modal*) |
| void    | **[setResult](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setResult)**(int *i*) |
| void    | **[setSizeGripEnabled](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeGripEnabled-prop)**(bool) |

## 重载的公共方法

| virtual QSize | **[minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint)**() const override |
| ------------- | ------------------------------------------------------------ |
| virtual void  | **[setVisible](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)**(bool *visible*) override |
| virtual QSize | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共槽

| virtual void | **[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)**() |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)**(int *r*) |
| virtual int  | **[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)**() |
| virtual void | **[open](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)**() |
| virtual void | **[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)**() |

## 信号

| void | **[accepted](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)**() |
| ---- | ------------------------------------------------------------ |
| void | **[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)**(int *result*) |
| void | **[rejected](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)**() |

## 重载的protected function

| virtual void | **[closeEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)**(QCloseEvent **e*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QContextMenuEvent **e*) override |
| virtual bool | **[eventFilter](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)**(QObject **o*, QEvent **e*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **e*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent *) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent **event*) override |

## 详细说明

对话窗口是顶级窗口，主要用于短期任务和与用户的简短通信。QDialog 可以是模态的也可以是非模态的。QDialogs 可以提供[return value](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#return)，他们可以有[default buttons](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default)。QDialogs 还可以有一个[QSizeGrip](https://doc-qt-io.translate.goog/qt-6/qsizegrip.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在右下角，使用[setSizeGripEnabled](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeGripEnabled-prop)()。

请注意，QDialog（以及具有 type 的任何其他小部件`Qt::Dialog`）使用父小部件与 Qt 中的其他类略有不同。对话框始终是顶级小部件，但如果它有父级，则其默认位置位于父级顶级小部件顶部的中心（如果它本身不是顶级）。它还将共享父级的任务栏条目。

使用的过载[QWidget::setParent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParent)() 函数更改 QDialog 小部件的所有权。此函数允许您显式设置重新设置父级的小部件的窗口标志；使用重载函数将清除指定小部件窗口系统属性的窗口标志（特别是它将重置[Qt::Dialog](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)旗帜）。

**注意：**对话框的父关系并不*意味着*对话框将始终堆叠在父窗口之上。为了确保对话框始终位于顶部，请将对话框设为模态。这也适用于对话框本身的子窗口。为了确保对话框的子窗口保持在对话框的顶部，也使子窗口成为模态的。

### 模态对话框

模式对话框是阻止对同一应用程序中其他可见窗口**进行**输入的对话框。用于向用户请求文件名或用于设置应用程序首选项的对话框通常是模态的。对话框可以是[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)（默认）或[window modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)。

打开应用程序模式对话框时，用户必须完成与该对话框的交互并关闭它，然后才能访问应用程序中的任何其他窗口。窗口模式对话框仅阻止对与该对话框关联的窗口的访问，从而允许用户继续使用应用程序中的其他窗口。

显示模式对话框最常见的方法是调用它[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)（） 功能。当用户关闭对话框时，[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 将提供有用的[return value](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#return)。要关闭对话框并返回适当的值，您必须连接一个默认按钮，例如**OK**按钮到[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)() 槽和一个**Cancel**按钮到[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)（） 投币口。或者，您可以致电[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)() 插槽带有`Accepted`或`Rejected`。

另一种方法是致电[setModal](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-prop)（正确）或[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop)（）， 然后[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)()。不像[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)(),[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 立即将控制权返回给调用者。呼唤[setModal](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-prop)(true) 对于进度对话框特别有用，其中用户必须能够与对话框交互，例如取消长时间运行的操作。如果你使用[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)（） 和[setModal](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-prop)(true) 一起执行长操作，必须调用[QCoreApplication::processEvents](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#processEvents)() 在处理过程中定期进行，以使用户能够与对话框交互。（看[QProgressDialog](https://doc-qt-io.translate.goog/qt-6/qprogressdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp).)

### 无模式对话框

无**模式**对话框是独立于同一应用程序中的其他窗口运行的对话框。文字处理程序中的查找和替换对话框通常是无模式的，以允许用户与应用程序的主窗口和对话框进行交互。

非模式对话框显示使用[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)()，它立即将控制权返回给调用者。

如果您调用[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 函数隐藏对话框后，对话框将显示在原来的位置。这是因为窗口管理器决定了程序员未明确放置的窗口的位置。要保留用户移动的对话框的位置，请将其位置保存在您的[closeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)() 处理程序，然后将对话框移动到该位置，然后再次显示它。



### 默认按钮

对话框的*默认*按钮是当用户按 Enter（回车）键时按下的按钮。该按钮用于表示用户接受对话框的设置并想要关闭对话框。使用[QPushButton::setDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)(),[QPushButton::isDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#default-prop)（） 和[QPushButton::autoDefault](https://doc-qt-io.translate.goog/qt-6/qpushbutton.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDefault-prop)() 设置和控制对话框的默认按钮。



### 退出键

如果用户在对话框中按 Esc 键，[QDialog::reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)() 将被调用。这将导致窗口关闭：[close event](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不可能是[ignored](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)。

### 可扩展性

可扩展性是指以两种方式显示对话框的能力：显示最常用选项的部分对话框和显示所有选项的完整对话框。通常，可扩展对话框最初会显示为部分对话框，但带有**More**切换按钮。如果用户按下**More**按下按钮，对话框展开。



### 返回值（模态对话框）

模态对话框通常用于需要返回值的情况，例如指示用户是否按下**OK**或者**Cancel**。可以通过调用关闭对话框[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 或者[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)() 插槽，以及[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 将返回`Accepted`或`Rejected`视情况而定。这[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 调用返回对话框的结果。结果也可从[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)() 如果对话框尚未被销毁。

为了修改对话框的关闭行为，您可以重新实现以下功能[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)(),[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)（） 或者[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)()。这[closeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)() 函数仅应重新实现以保留对话框的位置或覆盖标准关闭或拒绝行为。



### 代码示例

模态对话框：

```
void EditorWindow::countWords()
{
    WordCountDialog dialog(this);
    dialog.setWordCount(document().wordCount());
    dialog.exec();
}
```

无模式对话框：

```
void EditorWindow::find()
{
    if (!findDialog) {
        findDialog = new FindDialog(this);
        connect(findDialog, &FindDialog::findNext,
                this, &EditorWindow::findNext);
    }

    findDialog->show();
    findDialog->raise();
    findDialog->activateWindow();
}
```

带有扩展名的对话框：

```
    findButton = new QPushButton(tr("&Find"));
    moreButton = new QPushButton(tr("&More..."));
    moreButton->setCheckable(true);

    extension = new ExtendedControls;
    mainLayout->addWidget(extension);
    extension->hide();

    connect(moreButton, &QAbstractButton::toggled, extension, &QWidget::setVisible);
```

**可以参阅**[QDialogButtonBox](https://doc-qt-io.translate.goog/qt-6/qdialogbuttonbox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QTabWidget](https://doc-qt-io.translate.goog/qt-6/qtabwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QProgressDialog](https://doc-qt-io.translate.goog/qt-6/qprogressdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Standard Dialogs Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-dialogs-standarddialogs-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QDialog::DialogCode

模式对话框返回的值。

| 持续的              | 价值 |
| ------------------- | ---- |
| `QDialog::Accepted` | `1`  |
| `QDialog::Rejected` | `0`  |

## 属性文档

### modal : bool

该属性是否持有[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 应该弹出模态或非模态对话框

默认情况下，该属性是`false`并且[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)() 以无模式方式弹出对话框。将此属性设置为 true 相当于设置[QWidget::windowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop)到[Qt::ApplicationModal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)。

[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)() 忽略该属性的值并始终以模态方式弹出对话框。

**访问功能：**

| bool | **[isModal](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-prop)**() const |
| ---- | ------------------------------------------------------------ |
| void | **setModal**(bool *modal*)                                   |

**可以参阅**[QWidget::windowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop),[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)（）， 和[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()。

### sizeGripEnabled : bool

该属性保存是否启用尺寸夹点

A[QSizeGrip](https://doc-qt-io.translate.goog/qt-6/qsizegrip.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)启用此属性后，将放置在对话框的右下角。默认情况下，尺寸夹点处于禁用状态。

**访问功能：**

| bool | **isSizeGripEnabled**() const |
| ---- | ----------------------------- |
| void | **setSizeGripEnabled**(bool)  |

## 成员函数文档

### `[explicit]`QDialog::QDialog([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *f* = Qt::WindowFlags())

与父级构建对话*parent*。

对话框始终是顶级小部件，但如果它有父级，则其默认位置位于父级顶部的中心。它还将共享父级的任务栏条目。

小部件标志*f*被传递到[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。例如，如果您不想在对话框的标题栏中显示“这是什么”按钮，请传递[Qt::WindowTitleHint](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)|[Qt::WindowSystemMenuHint](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)在*f*。

**可以参阅**[QWidget::setWindowFlags](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowFlags-prop)()。

### `[virtual]`QDialog::~QDialog()

摧毁了[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，删除其所有子项。

### `[virtual slot]`void QDialog::accept()

隐藏模式对话框并将结果代码设置为`Accepted`。

**可以参阅**[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)（） 和[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)()。

### `[signal]`void QDialog::accepted()

当用户或通过调用接受对话框时，会发出此信号[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 或者[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)() 与[QDialog::Accepted](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)争论。

请注意，隐藏对话框时*不会*发出此信号[hide](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)（） 或者[setVisible](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（错误的）。这包括在对话框可见时将其删除。

**可以参阅**[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)（） 和[rejected](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)()。

### `[override virtual protected]`void QDialog::closeEvent([QCloseEvent](https://doc-qt-io.translate.goog/qt-6/qcloseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::closeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#closeEvent)（QCloseEvent *事件）。

### `[override virtual protected]`void QDialog::contextMenuEvent([QContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qcontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)（QContextMenuEvent *事件）。

### `[virtual slot]`void QDialog::done(int *r*)

关闭对话框并将其结果代码设置为*r*。这[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)() 信号将发出*r*; 如果*r*是[QDialog::Accepted](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)或者[QDialog::Rejected](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)， 这[accepted](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)（） 或者[rejected](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)() 信号也将分别发出。

如果此对话框显示为[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)()、done() 也会导致本地事件循环完成，并且[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)（） 回来*r*。

与[QWidget::close](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)()、done() 删除对话框，如果[Qt::WA_DeleteOnClose](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)标志已设置。如果该对话框是应用程序的主窗口部件，则应用程序将终止。如果该对话框是最后关闭的窗口，则[QGuiApplication::lastWindowClosed](https://doc-qt-io.translate.goog/qt-6/qguiapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastWindowClosed)() 信号被发射。

**可以参阅**[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)(),[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)(),[QApplication::activeWindow](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeWindow)（）， 和[QCoreApplication::quit](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quit)()。

### `[override virtual protected]`bool QDialog::eventFilter([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **o*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QObject::eventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)（QObject *观看，QEvent *事件）。

### `[virtual slot]`int QDialog::exec()

将对话框显示为[modal dialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-dialogs)，阻塞直到用户关闭它。该函数返回一个[DialogCode](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)结果。

如果对话框是[application modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)，用户在关闭对话框之前无法与同一应用程序中的任何其他窗口交互。如果对话框是[window modal](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowModality-enum)，当对话框打开时，仅阻止与父窗口的交互。默认情况下，该对话框是应用程序模式的。

**注意：**避免使用该功能；相反，使用`open()`. 与 exec() 不同，[open](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)() 是异步的，并且不会旋转额外的事件循环。这可以防止发生一系列危险的错误（例如，在通过 exec() 打开对话框时删除对话框的父级）。使用时[open](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)() 您可以连接到[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)() 信号[QDialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当对话框关闭时收到通知。

**可以参阅**[open](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)(),[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)(),[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)（）， 和[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop)()。

### `[signal]`void QDialog::finished(int *result*)

当对话框的*result*代码已由用户或通过调用设置[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)(),[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（）， 或者[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)()。

请注意，隐藏对话框时*不会*发出此信号[hide](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)（） 或者[setVisible](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（错误的）。这包括在对话框可见时将其删除。

**可以参阅**[accepted](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)（） 和[rejected](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rejected)()。

### `[override virtual protected]`void QDialog::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **e*)

重新实现：[QWidget::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDialog::minimumSizeHint() const

重新实现属性的访问函数：[QWidget::minimumSizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumSizeHint-prop)。

### `[virtual slot]`void QDialog::open()

将对话框显示为[window modal dialog](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#modal-dialogs)，立即返回。

**可以参阅**[exec](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exec)(),[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)(),[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)（）， 和[setWindowModality](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowModality-prop)()。

### `[virtual slot]`void QDialog::reject()

隐藏模式对话框并将结果代码设置为`Rejected`。

**可以参阅**[accept](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 和[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)()。

### `[signal]`void QDialog::rejected()

当对话框被用户或调用拒绝时，会发出此信号[reject](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reject)（） 或者[done](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#done)() 与[QDialog::Rejected](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)争论。

请注意，隐藏对话框时*不会*发出此信号[hide](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)（） 或者[setVisible](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（错误的）。这包括在对话框可见时将其删除。

**可以参阅**[finished](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#finished)（） 和[accepted](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accepted)()。

### `[override virtual protected]`void QDialog::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *)

重新实现：[QWidget::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### int QDialog::result() const

通常返回模式对话框的结果代码，`Accepted`或`Rejected`.

**注意：**当调用[QMessageBox](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例，返回值是[QMessageBox::StandardButton](https://doc-qt-io.translate.goog/qt-6/qmessagebox.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StandardButton-enum)枚举。

如果对话框是用以下函数构造的，则不要调用此函数[Qt::WA_DeleteOnClose](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)属性。

**可以参阅**[setResult](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setResult)()。

### void QDialog::setResult(int *i*)

将模式对话框的结果代码设置为*i*。

**注意：**我们建议您使用由定义的值之一[QDialog::DialogCode](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DialogCode-enum)。

**可以参阅**[result](https://doc-qt-io.translate.goog/qt-6/qdialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#result)()。

### `[override virtual]`void QDialog::setVisible(bool *visible*)

重新实现属性的访问函数：[QWidget::visible](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#visible-prop)。

### `[override virtual protected]`void QDialog::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDialog::sizeHint() const

重新实现属性的访问函数：[QWidget::sizeHint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint-prop)。