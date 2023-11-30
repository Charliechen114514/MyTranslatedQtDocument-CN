#  QDataStream Class

QDataStream 类提供二进制数据的序列化[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QDataStream>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:    | QT += core                                                   |
| Inherits: | [QIODeviceBase](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdatastream-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QDataStream 是[输入/输出和网络](https://doc-qt-io.translate.goog/qt-6/io.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| enum | **[ByteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum)** { BigEndian, LittleEndian } |
| ---- | ------------------------------------------------------------ |
| enum | **[FloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum)** { SinglePrecision, DoublePrecision } |
| enum | **[Status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)** { Ok, ReadPastEnd, ReadCorruptData, WriteFailed } |
| enum | **[Version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)** { Qt_1_0, Qt_2_0, Qt_2_1, Qt_3_0, Qt_3_1, …, Qt_6_6 } |

## 公共职能

|                                     | **[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream)**() |
| ----------------------------------- | ------------------------------------------------------------ |
|                                     | **[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream-1)**(QIODevice **d*) |
|                                     | **[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream-2)**(QByteArray **a*, QIODeviceBase::OpenMode *mode*) |
|                                     | **[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream-3)**(const QByteArray &*a*) |
|                                     | **[~QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDataStream)**() |
| void                                | **[abortTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#abortTransaction)**() |
| bool                                | **[atEnd](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)**() const |
| QDataStream::ByteOrder              | **[byteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#byteOrder)**() const |
| bool                                | **[commitTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitTransaction)**() |
| QIODevice *                         | **[device](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)**() const |
| QDataStream::FloatingPointPrecision | **[floatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floatingPointPrecision)**() const |
| QDataStream &                       | **[readBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readBytes)**(char *&*s*, uint &*l*) |
| int                                 | **[readRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readRawData)**(char **s*, int *len*) |
| void                                | **[resetStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)**() |
| void                                | **[rollbackTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rollbackTransaction)**() |
| void                                | **[setByteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setByteOrder)**(QDataStream::ByteOrder *bo*) |
| void                                | **[setDevice](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)**(QIODevice **d*) |
| void                                | **[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)**(QDataStream::FloatingPointPrecision *precision*) |
| void                                | **[setStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatus)**(QDataStream::Status *status*) |
| void                                | **[setVersion](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVersion)**(int *v*) |
| int                                 | **[skipRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#skipRawData)**(int *len*) |
| void                                | **[startTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startTransaction)**() |
| QDataStream::Status                 | **[status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)**() const |
| int                                 | **[version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#version)**() const |
| QDataStream &                       | **[writeBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeBytes)**(const char **s*, uint *len*) |
| int                                 | **[writeRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeRawData)**(const char **s*, int *len*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-1)**(qint8 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-2)**(quint8 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-3)**(qint16 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-4)**(quint16 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-5)**(qint32 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-6)**(quint32 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-7)**(qint64 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-8)**(quint64 *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-9)**(std::nullptr_t *ptr*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-10)**(bool *i*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-11)**(float *f*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-12)**(double *f*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-13)**(const char **s*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-14)**(char16_t *c*) |
| QDataStream &                       | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-15)**(char32_t *c*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-1)**(qint8 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-2)**(quint8 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-3)**(qint16 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-4)**(quint16 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-5)**(qint32 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-6)**(quint32 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-7)**(qint64 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-8)**(quint64 &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-9)**(std::nullptr_t &*ptr*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-10)**(bool &*i*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-11)**(float &*f*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-12)**(double &*f*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-13)**(char *&*s*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-14)**(char16_t &*c*) |
| QDataStream &                       | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-15)**(char32_t &*c*) |

## 相关非会员

| QDataStream & | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-17)**(QDataStream &*out*, const std::pair< T1, T2> &*pair*) |
| ------------- | ------------------------------------------------------------ |
| QDataStream & | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-17)**(QDataStream &*in*, std::pair< T1, T2> &*pair*) |

## 详细说明

数据流是编码信息的二进制流，100% 独立于主机的操作系统、CPU 或字节顺序。例如，由 Windows 下的 PC 写入的数据流可以由运行 Solaris 的 Sun SPARC 读取。

您还可以使用数据流来读/写[raw unencoded binary data](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#raw)。如果您想要“解析”输入流，请参阅[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QDataStream 类实现了 C++ 基本数据类型的序列化，如`char`、`short`、`int`、`char *`等。更复杂数据的序列化是通过将数据分解为原始单元来完成的。

数据流与数据流紧密合作[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。A[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代表一种可以读取数据和写入数据的输入/输出介质。这[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)class 是 I/O 设备的一个示例。

示例（将二进制数据写入流）：

```
QFile file("file.dat");
file.open(QIODevice::WriteOnly);
QDataStream out(&file);   // we will serialize the data into the file
out < <  QString("the answer is");   // serialize a string
out < <  (qint32)42;        // serialize an integer
```

示例（从流中读取二进制数据）：

```
QFile file("file.dat");
file.open(QIODevice::ReadOnly);
QDataStream in(&file);    // read the data serialized from the file
QString str;
qint32 a;
in >> str >> a;           // extract "the answer is" and 42
```

写入流中的每个项目都以预定义的二进制格式写入，该格式根据项目的类型而变化。支持的 Qt 类型包括[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)以及许多其他人。有关支持数据流的所有 Qt 类型的完整列表，请参阅[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

对于整数，最好始终转换为 Qt 整数类型进行写入，并读回相同的 Qt 整数类型。这可以确保您获得所需大小的整数，并使您免受编译器和平台差异的影响。

枚举可以通过 QDataStream 进行序列化，无需手动定义流运算符。枚举类使用声明的大小进行序列化。

举一个例子，一个`char *`字符串被写成一个32位整数，等于该字符串的长度（包括'\0'字节），后面是该字符串的所有字符（包括'\0'字节）。读取`char *`字符串时，会读取 4 个字节来创建 32 位长度值，然后`char *`读取字符串的许多字符（包括“\0”终止符）。

初始 I/O 设备通常在构造函数中设置，但可以使用以下命令进行更改[setDevice](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)()。如果已到达数据末尾（或者没有设置 I/O 设备）[atEnd](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)() 将返回 true。

### 版本控制

QDataStream 的二进制格式自 Qt 1.0 以来一直在发展，并且可能会继续发展以反映 Qt 中所做的更改。当输入或输出复杂类型时，确保流的版本相同非常重要（[version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#version)()) 用于读取和写入。如果您需要向前和向后兼容，您可以在应用程序中硬编码版本号：

```
stream.setVersion(QDataStream::Qt_4_0);
```

如果您正在生成新的二进制数据格式，例如应用程序创建的文档的文件格式，则可以使用 QDataStream 以可移植格式写入数据。通常，您会编写一个简短的标头，其中包含一个魔术字符串和一个版本号，以便为自己将来的扩展提供空间。例如：

```
QFile file("file.xxx");
file.open(QIODevice::WriteOnly);
QDataStream out(&file);

// Write a header with a "magic number" and a version
out < <  (quint32)0xA0B0C0D0;
out < <  (qint32)123;

out.setVersion(QDataStream::Qt_4_0);

// Write the data
out < <  lots_of_interesting_data;
```

然后读入：

```
QFile file("file.xxx");
file.open(QIODevice::ReadOnly);
QDataStream in(&file);

// Read and check the header
quint32 magic;
in >> magic;
if (magic != 0xA0B0C0D0)
    return XXX_BAD_FILE_FORMAT;

// Read the version
qint32 version;
in >> version;
if (version <  100)
    return XXX_BAD_FILE_TOO_OLD;
if (version > 123)
    return XXX_BAD_FILE_TOO_NEW;

if (version < = 110)
    in.setVersion(QDataStream::Qt_3_2);
else
    in.setVersion(QDataStream::Qt_4_0);

// Read the data
in >> lots_of_interesting_data;
if (version >= 120)
    in >> data_new_in_XXX_version_1_2;
in >> other_interesting_data;
```

您可以选择序列化数据时使用的字节顺序。默认设置为大端（MSB 在前）。将其更改为little-endian会破坏可移植性（除非读者也更改为little-endian）。我们建议保留此设置，除非您有特殊要求。



### 读取和写入原始二进制数据

您可能希望直接从数据流读取/写入您自己的原始二进制数据。`char *`可以使用以下方式将数据从流中读取到预分配中：[readRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readRawData)()。类似地，可以使用以下方法将数据写入流中[writeRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeRawData)()。请注意，数据的任何编码/解码都必须由您完成。

一对类似的函数是[readBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readBytes)（） 和[writeBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeBytes)()。它们与*原始*对应物的不同之处如下：[readBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readBytes)() 读取 quint32，该长度被视为要读取的数据的长度，然后将该字节数读入预分配的`char *`；[writeBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeBytes)() 写入包含数据长度的 quint32，后跟数据。请注意，数据的任何编码/解码（长度 quint32 除外）必须由您完成。

### 读写 Qt 集合类

Qt 容器类也可以序列化为 QDataStream。这些包括[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QSet](https://doc-qt-io.translate.goog/qt-6/qset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qhash)， 和[QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。流运算符被声明为类的非成员。



### 读写其他 Qt 类

除了此处记录的重载流运算符之外，您可能想要序列化到 QDataStream 的任何 Qt 类都将具有声明为该类的非成员的适当流运算符：

```
    QDataStream &operator< < (QDataStream &, const QXxx &);
    QDataStream &operator>>(QDataStream &, QXxx &);
```

例如，以下是声明为非成员的流运算符[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级：

```
    QDataStream & operator< <  (QDataStream& stream, const QImage& image);
    QDataStream & operator>> (QDataStream& stream, QImage& image);
```

要查看您最喜欢的 Qt 类是否定义了类似的流运算符，请检查该类文档页面的**相关非成员部分。**

### 使用读事务

当数据流在异步设备上运行时，数据块可以到达任意时间点。QDataStream 类实现了一种事务机制，该机制提供了使用一系列流运算符原子读取数据的能力。例如，您可以通过使用连接到 readRead() 信号的槽中的事务来处理来自套接字的不完整读取：

```
in.startTransaction();
QString str;
qint32 a;
in >> str >> a; // try to read packet atomically

if (!in.commitTransaction())
    return;     // wait for more data
```

如果没有收到完整的数据包，此代码会将流恢复到初始位置，之后您需要等待更多数据到达。

**也可以看看**[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QDataStream::ByteOrder

用于读/写数据的字节顺序。

| 持续的                      | 价值                     | 描述                     |
| --------------------------- | ------------------------ | ------------------------ |
| `QDataStream::BigEndian`    | `QSysInfo::BigEndian`    | 最重要的字节在前（默认） |
| `QDataStream::LittleEndian` | `QSysInfo::LittleEndian` | 最低有效字节在前         |

### enum QDataStream::FloatingPointPrecision

用于读/写数据的浮点数的精度。仅当数据流的版本为[Qt_4_6](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)或更高。

**警告：**写入数据流的对象和读取数据流的对象上的浮点精度必须设置为相同的值。

| 持续的                         | 价值 | 描述                                   |
| ------------------------------ | ---- | -------------------------------------- |
| `QDataStream::SinglePrecision` | `0`  | 数据流中的所有浮点数都具有 32 位精度。 |
| `QDataStream::DoublePrecision` | `1`  | 数据流中的所有浮点数都具有 64 位精度。 |

**也可以看看**[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)（） 和[floatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floatingPointPrecision)()。

### enum QDataStream::Status

该枚举描述了数据流的当前状态。

| 持续的                         | 价值 | 描述                                 |
| ------------------------------ | ---- | ------------------------------------ |
| `QDataStream::Ok`              | `0`  | 数据流运行正常。                     |
| `QDataStream::ReadPastEnd`     | `1`  | 数据流已读取到底层设备中的数据末尾。 |
| `QDataStream::ReadCorruptData` | `2`  | 数据流读取了损坏的数据。             |
| `QDataStream::WriteFailed`     | `3`  | 数据流无法写入底层设备。             |

### enum QDataStream::Version

该枚举提供数据序列化格式版本号的符号同义词。

| 持续的                 | 价值      | 描述                              |
| ---------------------- | --------- | --------------------------------- |
| `QDataStream::Qt_1_0`  | `1`       | 版本 1 (Qt 1.x)                   |
| `QDataStream::Qt_2_0`  | `2`       | 版本 2（Qt 2.0）                  |
| `QDataStream::Qt_2_1`  | `3`       | 版本 3（Qt 2.1、2.2、2.3）        |
| `QDataStream::Qt_3_0`  | `4`       | 版本 4（Qt 3.0）                  |
| `QDataStream::Qt_3_1`  | `5`       | 版本 5（Qt 3.1、3.2）             |
| `QDataStream::Qt_3_3`  | `6`       | 版本 6（Qt 3.3）                  |
| `QDataStream::Qt_4_0`  | `7`       | 版本 7（Qt 4.0、Qt 4.1）          |
| `QDataStream::Qt_4_1`  | `Qt_4_0`  | 版本 7（Qt 4.0、Qt 4.1）          |
| `QDataStream::Qt_4_2`  | `8`       | 版本 8（Qt 4.2）                  |
| `QDataStream::Qt_4_3`  | `9`       | 版本 9（Qt 4.3）                  |
| `QDataStream::Qt_4_4`  | `10`      | 版本 10（Qt 4.4）                 |
| `QDataStream::Qt_4_5`  | `11`      | 版本 11（Qt 4.5）                 |
| `QDataStream::Qt_4_6`  | `12`      | 版本 12（Qt 4.6、Qt 4.7、Qt 4.8） |
| `QDataStream::Qt_4_7`  | `Qt_4_6`  | 与 Qt_4_6 相同。                  |
| `QDataStream::Qt_4_8`  | `Qt_4_7`  | 与 Qt_4_6 相同。                  |
| `QDataStream::Qt_4_9`  | `Qt_4_8`  | 与 Qt_4_6 相同。                  |
| `QDataStream::Qt_5_0`  | `13`      | 版本 13（Qt 5.0）                 |
| `QDataStream::Qt_5_1`  | `14`      | 版本 14（Qt 5.1）                 |
| `QDataStream::Qt_5_2`  | `15`      | 版本 15（Qt 5.2）                 |
| `QDataStream::Qt_5_3`  | `Qt_5_2`  | 与Qt_5_2相同                      |
| `QDataStream::Qt_5_4`  | `16`      | 版本 16（Qt 5.4）                 |
| `QDataStream::Qt_5_5`  | `Qt_5_4`  | 与Qt_5_4相同                      |
| `QDataStream::Qt_5_6`  | `17`      | 版本 17（Qt 5.6）                 |
| `QDataStream::Qt_5_7`  | `Qt_5_6`  | 与Qt_5_6相同                      |
| `QDataStream::Qt_5_8`  | `Qt_5_7`  | 与Qt_5_6相同                      |
| `QDataStream::Qt_5_9`  | `Qt_5_8`  | 与Qt_5_6相同                      |
| `QDataStream::Qt_5_10` | `Qt_5_9`  | 与Qt_5_6相同                      |
| `QDataStream::Qt_5_11` | `Qt_5_10` | 与Qt_5_6相同                      |
| `QDataStream::Qt_5_12` | `18`      | 版本 18（Qt 5.12）                |
| `QDataStream::Qt_5_13` | `19`      | 版本 19（Qt 5.13）                |
| `QDataStream::Qt_5_14` | `Qt_5_13` | 与Qt_5_13相同                     |
| `QDataStream::Qt_5_15` | `Qt_5_14` | 与Qt_5_13相同                     |
| `QDataStream::Qt_6_0`  | `20`      | 版本 20（Qt 6.0）                 |
| `QDataStream::Qt_6_1`  | `Qt_6_0`  | 与Qt_6_0相同                      |
| `QDataStream::Qt_6_2`  | `Qt_6_0`  | 与Qt_6_0相同                      |
| `QDataStream::Qt_6_3`  | `Qt_6_0`  | 与Qt_6_0相同                      |
| `QDataStream::Qt_6_4`  | `Qt_6_0`  | 与Qt_6_0相同                      |
| `QDataStream::Qt_6_5`  | `Qt_6_0`  | 与Qt_6_0相同                      |
| `QDataStream::Qt_6_6`  | `21`      | 与Qt_6_0相同                      |

**也可以看看**[setVersion](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVersion)（） 和[version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#version)()。

## 成员函数文档

### QDataStream::QDataStream()

构造没有 I/O 设备的数据流。

**也可以看看**[setDevice](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)()。

### `[explicit]`QDataStream::QDataStream([QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **d*)

构造使用 I/O 设备的数据流*d*。

**也可以看看**[setDevice](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)（） 和[device](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)()。

### QDataStream::QDataStream([QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **a*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *mode*)

构造一个对字节数组进行操作的数据流，*a*。这*mode*描述如何使用该设备。

或者，您可以使用 QDataStream(const[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)&) 如果您只想从字节数组中读取。

自从[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是一个[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类，内部是[QBuffer](https://doc-qt-io.translate.goog/qt-6/qbuffer.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建来包装字节数组。

### QDataStream::QDataStream(const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*a*)

构造一个对字节数组进行操作的只读数据流*a*。使用 QDataStream([QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*, int) 如果要写入字节数组。

自从[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不是一个[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类，内部是[QBuffer](https://doc-qt-io.translate.goog/qt-6/qbuffer.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建来包装字节数组。

### `[noexcept]`QDataStream::~QDataStream()

破坏数据流。

析构函数不会影响当前的I/O设备，除非它是一个内部I/O设备（例如一个[QBuffer](https://doc-qt-io.translate.goog/qt-6/qbuffer.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）处理一个[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)传入*构造函数*，在这种情况下，内部 I/O 设备将被销毁。

### void QDataStream::abortTransaction()

中止读取事务。

此函数通常用于在高层协议错误或流同步丢失后丢弃事务。

如果在内部事务上调用，则中止将委托给最外面的事务，并且随后启动的内部事务将被迫失败。

对于最外面的事务，丢弃恢复点和流的任何内部重复数据。不会影响流的当前读取位置。

将数据流的状态设置为

| 持续的            | 描述 |
| ----------------- | ---- |
| `ReadCorruptData` | 。   |

**也可以看看**[startTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startTransaction)(),[commitTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitTransaction)（）， 和[rollbackTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rollbackTransaction)()。

### bool QDataStream::atEnd() const

`true`如果 I/O 设备已到达结束位置（流或文件的末尾）或者是否没有设置 I/O 设备，则返回；否则返回`false`.

**也可以看看**[QIODevice::atEnd](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)()。

### [QDataStream::ByteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum) QDataStream::byteOrder() const

返回当前字节顺序设置 – 要么[BigEndian](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum)或者[LittleEndian](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum)。

**也可以看看**[setByteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setByteOrder)()。

### bool QDataStream::commitTransaction()

完成读取事务。`true`如果事务期间没有发生读取错误则返回；否则返回`false`.

如果在内部事务上调用，提交将被推迟到最外层的 commitTransaction()，[rollbackTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rollbackTransaction)（）， 或者[abortTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#abortTransaction)() 调用发生。

否则，如果流状态指示读取超过数据末尾，则该函数将流数据恢复到数据点[startTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startTransaction)（） 称呼。发生这种情况时，您需要等待更多数据到达，然后开始新的事务。如果数据流读取了损坏的数据或任何内部事务被中止，则此函数将中止事务。

**也可以看看**[startTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startTransaction)(),[rollbackTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rollbackTransaction)（）， 和[abortTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#abortTransaction)()。

### [QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QDataStream::device() const

返回当前设置的 I/O 设备，或者`nullptr`如果当前未设置任何设备。

**也可以看看**[setDevice](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)()。

### [QDataStream::FloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum) QDataStream::floatingPointPrecision() const

返回数据流的浮点精度。

**也可以看看**[FloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum)和[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)()。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::readBytes(char *&*s*, [uint](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uint-typedef) &*l*)

读取缓冲区*s*从流中获取并返回对流的引用。

缓冲器*s*是使用 分配的`new []`。与操作员一起摧毁它`delete []`。

这*l*参数设置为缓冲区的长度。如果读取的字符串为空，*l*设置为 0 且*s*被设定为`nullptr`。

序列化格式首先是 quint32 长度说明符，然后*l*字节数据。

**也可以看看**[readRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readRawData)（） 和[writeBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeBytes)()。

### int QDataStream::readRawData(char **s*, int *len*)

最多读*len*从流中的字节到*s*并返回读取的字节数。如果发生错误，该函数返回-1。

缓冲器*s*必须预先分配。数据*未*解码。

**也可以看看**[readBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readBytes)(),[QIODevice::read](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)（）， 和[writeRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeRawData)()。

### void QDataStream::resetStatus()

重置数据流的状态。

**也可以看看**[Status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)（）， 和[setStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatus)()。

### void QDataStream::rollbackTransaction()

恢复读取事务。

此函数通常用于在提交事务之前检测到不完整读取时回滚事务。

如果在内部事务上调用，则恢复将委托给最外面的事务，并且随后启动的内部事务将被迫失败。

对于最外层事务，将流数据恢复到该点[startTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startTransaction)（） 称呼。如果数据流读取了损坏的数据或任何内部事务被中止，则此函数将中止事务。

如果前面的流操作成功，则将数据流的状态设置为

| 持续的        | 描述 |
| ------------- | ---- |
| `ReadPastEnd` | 。   |

**也可以看看**[startTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#startTransaction)(),[commitTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitTransaction)（）， 和[abortTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#abortTransaction)()。

### void QDataStream::setByteOrder([QDataStream::ByteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum) *bo*)

将序列化字节顺序设置为*bo*。

这*bo*参数可以是[QDataStream::BigEndian](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum)或者[QDataStream::LittleEndian](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ByteOrder-enum)。

默认设置是大端字节序。我们建议保留此设置，除非您有特殊要求。

**也可以看看**[byteOrder](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#byteOrder)()。

### void QDataStream::setDevice([QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **d*)

无效QDataStream::setDevice([QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*d)

将 I/O 设备设置为*d*，可以`nullptr`取消当前 I/O 设备的设置。

**也可以看看**[device](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)()。

### void QDataStream::setFloatingPointPrecision([QDataStream::FloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum) *precision*)

将数据流的浮点精度设置为*precision*。如果浮点精度为[DoublePrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum)数据流的版本是[Qt_4_6](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)或更高，所有浮点数将以 64 位精度写入和读取。如果浮点精度为[SinglePrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum)版本是[Qt_4_6](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)或更高，所有浮点数将以 32 位精度写入和读取。

对于之前的版本[Qt_4_6](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)，数据流中浮点数的精度取决于调用的流运算符。

默认为[DoublePrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FloatingPointPrecision-enum)。

请注意，此属性不会影响`qfloat16`实例的序列化或反序列化。

**警告：**在写入数据流的对象和读取数据流的对象上，必须将此属性设置为相同的值。

**也可以看看**[floatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#floatingPointPrecision)()。

### void QDataStream::setStatus([QDataStream::Status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum) *status*)

将数据流的状态设置为*status*给予。

对 setStatus() 的后续调用将被忽略，直到[resetStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)（） 叫做。

**也可以看看**[Status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)（）， 和[resetStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)()。

### void QDataStream::setVersion(int *v*)

将数据序列化格式的版本号设置为*v*，一个值[Version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)枚举。

如果您使用的是当前版本的 Qt，则不必设置版本，但对于您自己的自定义二进制格式，我们建议您这样做*；*看[Versioning](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#versioning)在详细说明中。

为了适应新功能，某些 Qt 类的数据流序列化格式在某些版本的 Qt 中发生了更改。如果要读取由较早版本的 Qt 创建的数据，或写入可由较早版本的 Qt 编译的程序读取的数据，请使用此函数修改 Qt 使用的序列化格式[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

这[Version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)enum 为不同版本的 Qt 提供符号常量。例如：

```
QDataStream out(file);
out.setVersion(QDataStream::Qt_4_0);
```

**也可以看看**[version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#version)（） 和[Version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)。

### int QDataStream::skipRawData(int *len*)

跳过*len*来自设备的字节。返回实际跳过的字节数，如果出错则返回 -1。

这相当于调用[readRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readRawData)() 在长度的缓冲区上*len*并忽略缓冲区。

**也可以看看**[QIODevice::seek](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)()。

### void QDataStream::startTransaction()

在流上启动新的读取事务。

定义读取操作序列中的可恢复点。对于顺序设备，读取的数据将在内部复制，以便在读取不完整的情况下进行恢复。对于随机访问设备，此函数保存流的当前位置。称呼[commitTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitTransaction)(),[rollbackTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rollbackTransaction)（）， 或者[abortTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#abortTransaction)() 完成当前事务。

一旦事务开始，后续调用该函数将使事务递归。内部事务充当最外层事务的代理（即向最外层事务报告读操作的状态，这可以恢复流的位置）。

**注意：**不支持恢复到嵌套 startTransaction() 调用的点。

当事务期间发生错误（包括内部事务失败）时，从数据流读取将被暂停（所有后续读取操作返回空/零值），并且后续内部事务将被迫失败。启动新的最外层事务将从该状态恢复。这种行为使得无需单独对每个读取操作进行错误检查。

**也可以看看**[commitTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commitTransaction)(),[rollbackTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rollbackTransaction)（）， 和[abortTransaction](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#abortTransaction)()。

### [QDataStream::Status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum) QDataStream::status() const

返回数据流的状态。

**也可以看看**[Status](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[setStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatus)（）， 和[resetStatus](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)()。

### int QDataStream::version() const

返回数据序列化格式的版本号。

**也可以看看**[setVersion](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVersion)（） 和[Version](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Version-enum)。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::writeBytes(const char **s*, [uint](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uint-typedef) *len*)

写入长度说明符*len*和缓冲区*s*到流并返回对流的引用。

这*len*被序列化为 quint32，后面是*len*字节来自*s*。请注意，数据*未*编码。

**也可以看看**[writeRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeRawData)（） 和[readBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readBytes)()。

### int QDataStream::writeRawData(const char **s*, int *len*)

写*len*字节来自*s*到溪流。返回实际写入的字节数，如果出错则返回 -1。数据*未*编码。

**也可以看看**[writeBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeBytes)(),[QIODevice::write](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#write)（）， 和[readRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readRawData)()。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([qint8](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint8-typedef) *i*)

写入一个有符号字节，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([quint8](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint8-typedef) *i*)

这是一个过载功能。

写入一个无符号字节，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([qint16](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint16-typedef) *i*)

这是一个过载功能。

写入一个带符号的 16 位整数，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([quint16](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint16-typedef) *i*)

这是一个过载功能。

写入一个无符号 16 位整数，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([qint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint32-typedef) *i*)

这是一个过载功能。

写入一个带符号的 32 位整数，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) *i*)

这是一个过载功能。

写入一个无符号整数，*i*，作为 32 位无符号整数 (quint32) 发送到流。返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *i*)

这是一个过载功能。

写入一个有符号 64 位整数，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < ([quint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint64-typedef) *i*)

这是一个过载功能。

写入一个无符号 64 位整数，*i*，到流并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (std::nullptr_t *ptr*)

这是一个过载功能。

模拟写一个`std::nullptr_t`,*ptr*，到流并返回对流的引用。该函数实际上不会向流中写入任何内容，因为`std::nullptr_t`值存储为 0 字节。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (bool *i*)

写入一个布尔值，*i*，到流。返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (float *f*)

这是一个过载功能。

写入一个浮点数，*f*，到使用标准 IEEE 754 格式的流。返回对流的引用。

**也可以看看**[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)()。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (double *f*)

这是一个过载功能。

写入一个浮点数，*f*，到使用标准 IEEE 754 格式的流。返回对流的引用。

**也可以看看**[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)()。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (const char **s*)

这是一个过载功能。

写入以“\0”结尾的字符串*s*到流并返回对流的引用。

该字符串使用 进行序列化`writeBytes()`。

**也可以看看**[writeBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeBytes)（） 和[writeRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#writeRawData)()。

### `[since 6.0]`[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (char16_t *c*)

这是一个过载功能。

写一个字，*c*，到流。返回对流的引用

这个函数是在Qt 6.0中引入的。

### `[since 6.0]`[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator< < (char32_t *c*)

这是一个过载功能。

写一个字，*c*，到流。返回对流的引用

这个函数是在Qt 6.0中引入的。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([qint8](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint8-typedef) &*i*)

从流中读取有符号字节到*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([quint8](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint8-typedef) &*i*)

这是一个过载功能。

从流中读取一个无符号字节到*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([qint16](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint16-typedef) &*i*)

这是一个过载功能。

从流中读取一个有符号的 16 位整数*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([quint16](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint16-typedef) &*i*)

这是一个过载功能。

从流中读取一个无符号 16 位整数到*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([qint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint32-typedef) &*i*)

这是一个过载功能。

从流中读取一个有符号的 32 位整数*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([quint32](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint32-typedef) &*i*)

这是一个过载功能。

从流中读取一个无符号 32 位整数到*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) &*i*)

这是一个过载功能。

从流中读取一个有符号的 64 位整数*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>([quint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint64-typedef) &*i*)

这是一个过载功能。

从流中读取一个无符号 64 位整数，存入*i*，并返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(std::nullptr_t &*ptr*)

这是一个过载功能。

`std::nullptr_t`模拟从流中读取a*ptr*并返回对流的引用。该函数实际上并不从流中读取任何内容，因为`std::nullptr_t`值存储为 0 字节。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(bool &*i*)

从流中读取一个布尔值到*i*。返回对流的引用。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(float &*f*)

这是一个过载功能。

从流中读取一个浮点数到*f*，使用标准 IEEE 754 格式。返回对流的引用。

**也可以看看**[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)()。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(double &*f*)

这是一个过载功能。

从流中读取一个浮点数到*f*，使用标准 IEEE 754 格式。返回对流的引用。

**也可以看看**[setFloatingPointPrecision](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFloatingPointPrecision)()。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(char *&*s*)

这是一个过载功能。

读取字符串*s*从流中获取并返回对流的引用。

该字符串使用序列化格式进行反序列化，`readBytes()`其中序列化格式`quint32`首先是长度说明符，后跟那么多字节的数据。生成的字符串始终以“\0”结尾。

字符串的空间是使用分配的`new []`- 调用者必须使用 销毁它`delete []`。

**也可以看看**[readBytes](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readBytes)（） 和[readRawData](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readRawData)()。

### `[since 6.0]`[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(char16_t &*c*)

这是一个过载功能。

从流中读取一个 16 位宽的字符*c*并返回对流的引用。

这个函数是在Qt 6.0中引入的。

### `[since 6.0]`[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &QDataStream::operator>>(char32_t &*c*)

这是一个过载功能。

从流中读取 32 位宽字符到*c*并返回对流的引用。

这个函数是在Qt 6.0中引入的。

## 相关非会员

### `[since 6.0]`template < typename T1, typename T2> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &operator< < ([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &*out*, const std::pair< T1, T2> &*pair*)

写对*pair*流式传输*out*。

该功能需要T1和T2类型来实现`operator< < ()`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[since 6.0]`template < typename T1, typename T2> [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDataStream) &*in*, std::pair< T1, T2> &*pair*)

从流中读取一对*in*进入*pair*。

该功能需要T1和T2类型来实现`operator>>()`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。