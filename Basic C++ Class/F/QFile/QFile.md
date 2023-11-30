#  QFile Class

QFile 类提供了读取和写入文件的接口。

| Header:       | #include < QFile>                                            |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:        | QT += core                                                   |
| Inherits:     | [QFileDevice](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QTemporaryFile](https://doc-qt-io.translate.goog/qt-6/qtemporaryfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qfile-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QFile 是[输入/输出和网络](https://doc-qt-io.translate.goog/qt-6/io.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共职能

|                       | **[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFile)**() |
| --------------------- | ------------------------------------------------------------ |
|                       | **[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFile-1)**(const QString &*name*) |
|                       | **[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFile-2)**(const std::filesystem::path &*name*) |
|                       | **[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFile-3)**(QObject **parent*) |
|                       | **[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFile-4)**(const QString &*name*, QObject **parent*) |
|                       | **[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFile-5)**(const std::filesystem::path &*name*, QObject **parent*) |
| virtual               | **[~QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QFile)**() |
| bool                  | **[copy](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy)**(const QString &*newName*) |
| bool                  | **[copy](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy-2)**(const std::filesystem::path &*newName*) |
| bool                  | **[exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)**() const |
| std::filesystem::path | **[filesystemFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemFileName)**() const |
| std::filesystem::path | **[filesystemSymLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemSymLinkTarget)**() const |
| bool                  | **[link](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#link)**(const QString &*linkName*) |
| bool                  | **[link](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#link-2)**(const std::filesystem::path &*newName*) |
| bool                  | **[moveToTrash](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveToTrash)**() |
| bool                  | **[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open-1)**(QIODeviceBase::OpenMode *mode*, QFileDevice::Permissions *permissions*) |
| bool                  | **[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open-2)**(FILE **fh*, QIODeviceBase::OpenMode *mode*, QFileDevice::FileHandleFlags *handleFlags* = DontCloseHandle) |
| bool                  | **[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open-3)**(int *fd*, QIODeviceBase::OpenMode *mode*, QFileDevice::FileHandleFlags *handleFlags* = DontCloseHandle) |
| bool                  | **[remove](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)**() |
| bool                  | **[rename](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename)**(const QString &*newName*) |
| bool                  | **[rename](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename-2)**(const std::filesystem::path &*newName*) |
| void                  | **[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)**(const QString &*name*) |
| void                  | **[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName-1)**(const std::filesystem::path &*name*) |
| QString               | **[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget-1)**() const |

## 重新实施公共职能

| virtual QString                  | **[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)**() const override |
| -------------------------------- | ------------------------------------------------------------ |
| virtual bool                     | **[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)**(QIODeviceBase::OpenMode *mode*) override |
| virtual QFileDevice::Permissions | **[permissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions)**() const override |
| virtual bool                     | **[resize](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)**(qint64 *sz*) override |
| virtual bool                     | **[setPermissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPermissions)**(QFileDevice::Permissions *permissions*) override |
| virtual qint64                   | **[size](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)**() const override |

## 静态公共成员

| bool                     | **[copy](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#copy-1)**(const QString &*fileName*, const QString &*newName*) |
| ------------------------ | ------------------------------------------------------------ |
| QString                  | **[decodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decodeName)**(const QByteArray &*localFileName*) |
| QString                  | **[decodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decodeName-1)**(const char **localFileName*) |
| QByteArray               | **[encodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encodeName)**(const QString &*fileName*) |
| bool                     | **[exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)**(const QString &*fileName*) |
| std::filesystem::path    | **[filesystemSymLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemSymLinkTarget-1)**(const std::filesystem::path &*fileName*) |
| bool                     | **[link](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#link-1)**(const QString &*fileName*, const QString &*linkName*) |
| bool                     | **[moveToTrash](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveToTrash-1)**(const QString &*fileName*, QString **pathInTrash* = nullptr) |
| QFileDevice::Permissions | **[permissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions-1)**(const QString &*fileName*) |
| QFileDevice::Permissions | **[permissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions-2)**(const std::filesystem::path &*filename*) |
| bool                     | **[remove](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove-1)**(const QString &*fileName*) |
| bool                     | **[rename](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename-1)**(const QString &*oldName*, const QString &*newName*) |
| bool                     | **[resize](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize-1)**(const QString &*fileName*, qint64 *sz*) |
| bool                     | **[setPermissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPermissions-1)**(const QString &*fileName*, QFileDevice::Permissions *permissions*) |
| bool                     | **[setPermissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPermissions-2)**(const std::filesystem::path &*filename*, QFileDevice::Permissions *permissionSpec*) |
| QString                  | **[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)**(const QString &*fileName*) |

## 详细说明

QFile 是一个 I/O 设备，用于读写文本和二进制文件[resources](https://doc-qt-io.translate.goog/qt-6/resources.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。QFile 可以单独使用，或者更方便地与[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

文件名通常在构造函数中传递，但可以随时使用设置[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。无论操作系统如何，QFile 都期望文件分隔符为“/”。不支持使用其他分隔符（例如“\”）。

您可以使用检查文件是否存在[exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()，并使用删除文件[remove](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。（更高级的文件系统相关操作由[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp).)

文件打开方式为[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)()，封闭于[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)()，并用[flush](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)()。数据通常使用以下方式读取和写入[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，但您也可以调用[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)- 继承函数[read](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)(),[readLine](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)(),[readAll](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)(),[write](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#write)()。QFile也继承了[getChar](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#getChar)(),[putChar](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#putChar)（）， 和[ungetChar](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungetChar)()，一次只处理一个字符。

文件的大小由返回[size](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。您可以使用以下命令获取当前文件位置[pos](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)()，或使用移动到新的文件位置[seek](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)()。如果您已到达文件末尾，[atEnd](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)() 返回`true`.

### 直接读取文件

以下示例逐行读取文本文件：

```
    QFile file("in.txt");
    if (!file.open(QIODevice::ReadOnly | QIODevice::Text))
        return;

    while (!file.atEnd()) {
        QByteArray line = file.readLine();
        process_line(line);
    }
```

QIODevice::Text 标志传递给[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)() 告诉 Qt 将 Windows 样式的行终止符（“\r\n”）转换为 C++ 样式的终止符（“\n”）。默认情况下，QFile 假定为二进制，即它不对文件中存储的字节执行任何转换。

### 使用流读取文件

下一个示例使用[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)逐行读取文本文件：

```
    QFile file("in.txt");
    if (!file.open(QIODevice::ReadOnly | QIODevice::Text))
        return;

    QTextStream in(&file);
    while (!in.atEnd()) {
        QString line = in.readLine();
        process_line(line);
    }
```

[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)负责将存储在磁盘上的 8 位数据转换为 16 位 Unicode[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。默认情况下，假定文件采用 UTF-8 编码。这可以改变使用[QTextStream::setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)()。

要写入文本，我们可以使用运算符< < ()，它被重载以接受一个[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)左边和各种数据类型（包括[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)） 在右侧：

```
    QFile file("out.txt");
    if (!file.open(QIODevice::WriteOnly | QIODevice::Text))
        return;

    QTextStream out(&file);
    out < <  "The magic number is: " < <  49 < <  "\n";
```

[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类似，您可以使用operator< < ()写入数据并使用operator>>()将其读回。有关详细信息，请参阅类文档。

### 信号

与其他不同[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实现，例如[QTcpSocket](https://doc-qt-io.translate.goog/qt-6/qtcpsocket.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), QFile 不发出[aboutToClose](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#aboutToClose)(),[bytesWritten](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bytesWritten)（）， 或者[readyRead](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readyRead)() 信号。这个实现细节意味着 QFile 不适合读写某些类型的文件，例如 Unix 平台上的设备文件。

### 平台特定问题

[Qt APIs related to I/O](https://doc-qt-io.translate.goog/qt-6/io.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用基于 UTF-16 的 QString 来表示文件路径。然而，标准 C++ API（`< cstdio>`或`< iostream>`）或特定于平台的 API 通常需要 8 位编码路径。您可以使用[encodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encodeName)（） 和[decodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decodeName)() 在两种表示形式之间进行转换。

在 Unix 上，有一些特殊的系统文件（例如在`/proc`）[size](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)() 将始终返回 0，但您仍然可以从此类文件中读取更多数据；数据是直接响应您的调用而生成的[read](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)()。但是，在这种情况下，您不能使用[atEnd](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)() 确定是否还有更多数据要读取（因为[atEnd](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)() 对于声称大小为 0 的文件将返回 true）。相反，您应该致电[readAll](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)()，或致电[read](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)（） 或者[readLine](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)重复()，直到无法读取更多数据为止。下一个示例使用[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)`/proc/modules`逐行阅读：

```
    QFile file("/proc/modules");
    if (!file.open(QIODevice::ReadOnly | QIODevice::Text))
        return;

    QTextStream in(&file);
    QString line = in.readLine();
    while (!line.isNull()) {
        process_line(line);
        line = in.readLine();
    }
```

文件权限在类 Unix 系统和 Windows 上的处理方式不同。在非[writable](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWritable)类 Unix 系统上的目录，无法创建文件。在 Windows 上情况并非总是如此，例如，“我的文档”目录通常不可写，但仍然可以在其中创建文件。

Qt 对文件权限的理解是有限的，这尤其影响[QFile::setPermissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPermissions)（） 功能。在 Windows 上，Qt 将仅设置旧版只读标志，并且仅当未传递任何 Write* 标志时才会设置。Qt 不操作访问控制列表 (ACL)，这使得该功能对于 NTFS 卷几乎没有用处。它可能仍然适用于使用 VFAT 文件系统的 USB 记忆棒。POSIX ACL 也不会被操纵。

在 Android 上，处理时存在一些限制[content URIs](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/guide/topics/providers/content-provider-basics%23ContentURIs):

- 通过提示用户可能需要访问权限[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它实现了[Android's native file picker](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage/shared/documents-files)。
- 旨在遵循[Scoped storage](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage%23scoped-storage)准则，例如使用应用程序特定目录而不是其他公共外部目录。有关详细信息，另请参阅[storage best practices](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage/use-cases)。
- 由于Qt API（例如QFile）的设计，不可能将后面的API 与Android 完全集成。[MediaStore](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/reference/android/provider/MediaStore)蜜蜂。

**也可以看看**[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[The Qt Resource System](https://doc-qt-io.translate.goog/qt-6/resources.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QFile::QFile()

构造一个 QFile 对象。

### QFile::QFile(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

构造一个新的文件对象来表示具有给定值的文件*name*。

**注意：**在 Qt 6.8 及之前的版本中，此构造函数是隐式的，以实现向后兼容性。从 Qt 6.9 开始，这个构造函数是无条件的`explicit`。用户甚至可以通过在包含任何 Qt 标头之前`explicit`定义宏来强制此构造函数在早期版本的 Qt 中使用。`QT_EXPLICIT_QFILE_CONSTRUCTION_FROM_PATH`

### `[since 6.0]`QFile::QFile(const std::filesystem::path &*name*)

构造一个新的文件对象来表示具有给定值的文件*name*。

**注意：**在 Qt 6.8 及之前的版本中，此构造函数是隐式的，以实现向后兼容性。从 Qt 6.9 开始，这个构造函数是无条件的`explicit`。用户甚至可以通过在包含任何 Qt 标头之前`explicit`定义宏来强制此构造函数在早期版本的 Qt 中使用。`QT_EXPLICIT_QFILE_CONSTRUCTION_FROM_PATH`

这个函数是在Qt 6.0中引入的。

### `[explicit]`QFile::QFile([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent*)

使用给定的值构造一个新的文件对象*parent*。

### QFile::QFile(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*, [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent*)

使用给定的值构造一个新的文件对象*parent*来表示具有指定的文件*name*。

### `[since 6.0]`QFile::QFile(const std::filesystem::path &*name*, [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent*)

使用给定的值构造一个新的文件对象*parent*来表示具有指定的文件*name*。

这个函数是在Qt 6.0中引入的。

### `[virtual noexcept]`QFile::~QFile()

销毁文件对象，必要时关闭它。

### bool QFile::copy(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*newName*)

复制名为的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（） 到*newName*。

该文件在复制之前已关闭。

如果复制的文件是符号链接（symlink），则复制它所引用的文件，而不是链接本身。除了复制的权限之外，不会复制其他文件元数据。

`true`成功则返回；否则返回`false`.

请注意，如果文件名为*newName*已经存在，copy() 返回`false`。这意味着[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会覆盖它。

**注意：**在 Android 上，方案 URI 尚不支持此操作`content`。

**也可以看看**[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[static]`bool QFile::copy(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*newName*)

这是一个过载功能。

复制名为的文件*fileName*到*newName*。

该文件在复制之前已关闭。

如果复制的文件是符号链接（symlink），则复制它所引用的文件，而不是链接本身。除了复制的权限之外，不会复制其他文件元数据。

`true`成功则返回；否则返回`false`.

请注意，如果文件名为*newName*已经存在，copy() 返回`false`。这意味着[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会覆盖它。

**注意：**在 Android 上，方案 URI 尚不支持此操作`content`。

**也可以看看**[rename](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename)()。

### `[since 6.0]`bool QFile::copy(const std::filesystem::path &*newName*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFile::decodeName(const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*localFileName*)

这会起到相反的作用[QFile::encodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encodeName)（） 使用*localFileName*。

**也可以看看**[encodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encodeName)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFile::decodeName(const char **localFileName*)

这是一个过载功能。

返回给定的 Unicode 版本*localFileName*。看[encodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encodeName)（）了解详情。

### `[static]`[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFile::encodeName(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

转换*fileName*转换为可在本机 API 中使用的 8 位编码。在 Windows 上，编码是来自活动 Windows (ANSI) 代码页的编码。在其他平台上，对于 macOS，这是分解形式 (NFD) 的 UTF-8。

**也可以看看**[decodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#decodeName)()。

### `[static]`bool QFile::exists(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

返回`true`是否由指定的文件*fileName*存在；否则返回`false`.

**注：**如果*fileName*是指向不存在文件的符号链接，返回 false。

### bool QFile::exists() const

这是一个过载功能。

返回`true`是否由指定的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)() 存在；否则返回`false`.

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（） 和[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[override virtual]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFile::fileName() const

重新实现：[QFileDevice::fileName() const](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)。

返回由设置的名称[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)() 或到[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数。

**也可以看看**[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)（） 和[QFileInfo::fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)()。

### `[since 6.0]`std::filesystem::path QFile::filesystemFileName() const

退货[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（） 作为`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

### `[since 6.3]`std::filesystem::path QFile::filesystemSymLinkTarget() const

退货[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget-1)（） 作为`std::filesystem::path`。

该功能是在 Qt 6.3 中引入的。

### `[static, since 6.3]`std::filesystem::path QFile::filesystemSymLinkTarget(const std::filesystem::path &*fileName*)

退货[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget-1)（）`std::filesystem::path`作为*fileName*。

该功能是在 Qt 6.3 中引入的。

### bool QFile::link(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*linkName*)

创建一个名为的链接*linkName*指向当前指定的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)()。链接是什么取决于底层文件系统（无论是 Windows 上的快捷方式还是 Unix 上的符号链接）。`true`成功则返回；否则返回`false`.

该函数不会覆盖文件系统中已经存在的实体；在这种情况下，`link()`将返回 false 并设置[error](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#error)（） 回来[RenameError](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FileError-enum)。

**注意：**要在 Windows 上创建有效链接，*linkName*必须有`.lnk`文件扩展名。

**也可以看看**[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[static]`bool QFile::link(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*linkName*)

这是一个过载功能。

创建一个名为的链接*linkName*指向该文件*fileName*。链接是什么取决于底层文件系统（无论是 Windows 上的快捷方式还是 Unix 上的符号链接）。`true`成功则返回；否则返回`false`.

**也可以看看**[link](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#link)()。

### `[since 6.0]`bool QFile::link(const std::filesystem::path &*newName*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### bool QFile::moveToTrash()

移动指定的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)() 到垃圾桶。如果成功则返回`true`，并设置[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)() 到可以在垃圾箱中找到该文件的路径；否则返回`false`.

**注意：**在系统 API 不报告垃圾箱中文件位置的系统上，[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)一旦文件被移动，() 将被设置为空字符串。在没有垃圾桶的系统上，此函数始终返回 false。

### `[static]`bool QFile::moveToTrash(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*, [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **pathInTrash* = nullptr)

这是一个过载功能。

移动指定的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)() 到垃圾桶。如果成功则返回`true`，并设置*pathInTrash*（如果提供）到可以在垃圾箱中找到文件的路径；否则返回`false`.

**注意：**在系统 API 不报告垃圾箱中文件路径的系统上，*pathInTrash*一旦文件被移动，将被设置为空字符串。在没有垃圾桶的系统上，此函数始终返回 false。

### `[override virtual]`bool QFile::open([QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *mode*)

重新实现：[QIODevice::open](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)（QIODeviceBase::OpenMode 模式）。

使用 OpenMode 打开文件*mode*，成功则返回true；否则为假。

这*mode*必须是 QIODevice::ReadOnly、QIODevice::WriteOnly 或 QIODevice::ReadWrite。它还可能有其他标志，例如 QIODevice::Text 和 QIODevice::Unbuffered。

**注：**在[WriteOnly](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum)或者[ReadWrite](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum)模式下，如果相关文件尚不存在，该函数将在打开它之前尝试创建一个新文件。该文件将使用 POSIX 系统上的 umask 屏蔽的模式 0666 创建，并具有从 Windows 上的父目录继承的权限。在Android上，它应该具有对该文件名的父级的访问权限，否则，将无法创建这个不存在的文件。

**也可以看看**[QIODevice::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum)和[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[since 6.3]`bool QFile::open([QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *mode*, [QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) *permissions*)

这是一个过载功能。

如果文件不存在并且*mode*意味着创建它，它是使用指定的创建的*permissions*。

在 POSIX 系统上，实际权限受 值的影响`umask`。

在 Windows 上，权限是使用 ACL 模拟的。当授予组的权限少于其他组时，这些 ACL 的顺序可能不规范。当打开“属性”对话框的“安全”选项卡时，具有此类权限的文件和目录将生成警告。向该组授予授予其他人的所有权限可以避免此类警告。

该功能是在 Qt 6.3 中引入的。

**也可以看看**[QIODevice::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum)和[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### bool QFile::open(FILE **fh*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *mode*, [QFileDevice::FileHandleFlags](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FileHandleFlag-enum) *handleFlags* = DontCloseHandle)

这是一个过载功能。

打开现有的文件句柄*fh*在给定的*mode*。*handleFlags*可用于指定附加选项。`true`成功则返回；否则返回`false`.

例子：

```
#include < stdio.h>

void printError(const char* msg)
{
    QFile file;
    file.open(stderr, QIODevice::WriteOnly);
    file.write(msg, qstrlen(msg));        // write to stderr
    file.close();
}
```

当一个[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此函数打开，行为[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)() 由 AutoCloseHandle 标志控制。如果指定了 AutoCloseHandle，并且此函数成功，则调用[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)() 关闭采用的句柄。否则，[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)() 实际上并不关闭文件，而只是刷新它。

**警告：**

1. 如果*fh*不引用常规文件，例如，它是`stdin`、`stdout`、 或`stderr`，您可能无法[seek](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)()。[size](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()`0`在这些情况下返回。看[QIODevice::isSequential](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSequential)（） 了解更多信息。
2. 由于此函数打开文件时未指定文件名，因此您不能使用此函数[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与一个[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**Windows 平台注意事项**

*fh*访问文件和其他随机访问设备时，必须以二进制模式打开（即模式字符串必须包含“b”，如“rb”或“wb”）。如果您将 QIODevice::Text 传递给 Qt，Qt 将翻译行尾字符*mode*。顺序设备（例如 stdin 和 stdout）不受此限制的影响。

您需要启用对控制台应用程序的支持才能在控制台上使用 stdin、stdout 和 stderr 流。为此，请将以下声明添加到应用程序的项目文件中：

```
CONFIG += console
```

**也可以看看**[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)()。

### bool QFile::open(int *fd*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *mode*, [QFileDevice::FileHandleFlags](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FileHandleFlag-enum) *handleFlags* = DontCloseHandle)

这是一个过载功能。

打开现有的文件描述符*fd*在给定的*mode*。*handleFlags*可用于指定附加选项。`true`成功则返回；否则返回`false`.

当一个[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此函数打开，行为[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)() 由 AutoCloseHandle 标志控制。如果指定了 AutoCloseHandle，并且此函数成功，则调用[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)() 关闭采用的句柄。否则，[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)() 实际上并不关闭文件，而只是刷新它。

**警告：**如果*fd*不是常规文件，例如，它是 0 ( `stdin`)、1 ( `stdout`) 或 2 ( `stderr`)，您可能无法[seek](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)()。在那些情况下，[size](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)() 返回`0`. 看[QIODevice::isSequential](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSequential)（） 了解更多信息。

**警告：**由于此函数在未指定文件名的情况下打开文件，因此您不能使用此函数[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与一个[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[close](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#close)()。

### `[override virtual]`[QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) QFile::permissions() const

重新实现：[QFileDevice::permissions() const](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions)。

**也可以看看**[setPermissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPermissions)()。

### `[static]`[QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) QFile::permissions(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

这是一个过载功能。

返回 QFile::Permission 的完整 OR 组合*fileName*。

### `[static, since 6.0]`[QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) QFile::permissions(const std::filesystem::path &*filename*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### bool QFile::remove()

删除指定的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)()。`true`成功则返回；否则返回`false`.

文件在删除之前已关闭。

**也可以看看**[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[static]`bool QFile::remove(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

这是一个过载功能。

删除指定的文件*fileName*给予。

`true`成功则返回；否则返回`false`.

**也可以看看**[remove](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)()。

### bool QFile::rename(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*newName*)

重命名当前指定的文件[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（） 到*newName*。`true`成功则返回；否则返回`false`.

如果文件名为*newName*已经存在，rename() 返回`false`（即，[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会覆盖它）。

文件在重命名之前已关闭。

如果重命名操作失败，Qt 将尝试将此文件的内容复制到*newName*，然后删除该文件，只保留*newName*。如果该复制操作失败或无法删除该文件，则目标文件*newName*被删除以恢复旧状态。

**也可以看看**[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[static]`bool QFile::rename(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*oldName*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*newName*)

这是一个过载功能。

重命名文件*oldName*到*newName*。`true`成功则返回；否则返回`false`.

如果文件名为*newName*已经存在，rename() 返回`false`（即，[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会覆盖它）。

**也可以看看**[rename](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename)()。

### `[since 6.0]`bool QFile::rename(const std::filesystem::path &*newName*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### `[override virtual]`bool QFile::resize([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *sz*)

重新实现：[QFileDevice::resize](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)（qint64 sz）。

### `[static]`bool QFile::resize(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*, [qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *sz*)

这是一个过载功能。

套*fileName*大小（以字节为单位）*sz*。`true`如果调整大小成功则返回；否则为假。如果*sz*大于*fileName*当前是新字节将被设置为 0，如果*sz*较小的文件会被简单地截断。

**警告：**如果文件不存在，此函数可能会失败。

**也可以看看**[resize](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resize)()。

### void QFile::setFileName(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*)

设置*name*文件的。该名称可以没有路径、相对路径或绝对路径。

如果文件已经打开，请勿调用此函数。

如果文件名没有路径或相对路径，则使用的路径将是应用程序*在执行时的当前目录路径[open](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#open)（）*称呼。

例子：

```
QFile file;
QDir::setCurrent("/tmp");
file.setFileName("readme.txt");
QDir::setCurrent("/home");
file.open(QIODevice::ReadOnly);      // opens "/home/readme.txt" under Unix
```

请注意，目录分隔符“/”适用于 Qt 支持的所有操作系统。

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)(),[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[since 6.0]`void QFile::setFileName(const std::filesystem::path &*name*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### `[override virtual]`bool QFile::setPermissions([QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) *permissions*)

重新实现：[QFileDevice::setPermissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPermissions)（QFileDevice::Permissions 权限）。

将文件的权限设置为*permissions*指定的。如果成功则返回`true`，或者`false`如果权限无法修改则返回。

**警告：**此函数不操作 ACL，这可能会限制其有效性。

**也可以看看**[permissions](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions)（） 和[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。

### `[static]`bool QFile::setPermissions(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*, [QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) *permissions*)

这是一个过载功能。

设置权限*fileName*文件到*permissions*。

### `[static, since 6.0]`bool QFile::setPermissions(const std::filesystem::path &*filename*, [QFileDevice::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) *permissionSpec*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### `[override virtual]`[qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) QFile::size() const

重新实现：[QFileDevice::size() const](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFile::symLinkTarget(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

返回由指定的符号链接（或 Windows 上的快捷方式）引用的文件或目录的绝对路径*fileName*，或者返回一个空字符串，如果*fileName*不对应于符号链接。

该名称可能不代表现有文件；它只是一个字符串。[QFile::exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()`true`如果符号链接指向现有文件则返回。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFile::symLinkTarget() const

这是一个过载功能。

返回符号链接（或 Windows 上的快捷方式）指向的文件或目录的绝对路径，如果对象不是符号链接，则返回空字符串。

该名称可能不代表现有文件；它只是一个字符串。[QFile::exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()`true`如果符号链接指向现有文件则返回。

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（） 和[setFileName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFileName)()。