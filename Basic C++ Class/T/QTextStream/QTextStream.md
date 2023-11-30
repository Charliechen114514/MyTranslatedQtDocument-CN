#  QTextStream Class

QTextStream 类提供了一个方便的接口来读取和写入文本。[更多的...](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QTextStream>                                      |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:    | QT += core                                                   |
| Inherits: | [QIODeviceBase](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qtextstream-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QTextStream 是[输入/输出、网络](https://doc-qt-io.translate.goog/qt-6/io.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[字符串数据类](https://doc-qt-io.translate.goog/qt-6/string-processing.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| enum  | **[FieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldAlignment-enum)** { AlignLeft, AlignRight, AlignCenter, AlignAccountingStyle } |
| ----- | ------------------------------------------------------------ |
| enum  | **[NumberFlag](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)** { ShowBase, ForcePoint, ForceSign, UppercaseBase, UppercaseDigits } |
| flags | **[NumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)** |
| enum  | **[RealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)** { ScientificNotation, FixedNotation, SmartNotation } |
| enum  | **[Status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum)** { Ok, ReadPastEnd, ReadCorruptData, WriteFailed } |

## 公共职能

|                                 | **[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream)**() |
| ------------------------------- | ------------------------------------------------------------ |
|                                 | **[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream-1)**(QIODevice **device*) |
|                                 | **[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream-2)**(FILE **fileHandle*, QIODeviceBase::OpenMode *openMode* = ReadWrite) |
|                                 | **[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream-3)**(QString **string*, QIODeviceBase::OpenMode *openMode* = ReadWrite) |
|                                 | **[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream-4)**(QByteArray **array*, QIODeviceBase::OpenMode *openMode* = ReadWrite) |
|                                 | **[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream-5)**(const QByteArray &*array*, QIODeviceBase::OpenMode *openMode* = ReadOnly) |
| virtual                         | **[~QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QTextStream)**() |
| bool                            | **[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)**() const |
| bool                            | **[autoDetectUnicode](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDetectUnicode)**() const |
| QIODevice *                     | **[device](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)**() const |
| QStringConverter::Encoding      | **[encoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encoding)**() const |
| QTextStream::FieldAlignment     | **[fieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldAlignment)**() const |
| int                             | **[fieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldWidth)**() const |
| void                            | **[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)**() |
| bool                            | **[generateByteOrderMark](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#generateByteOrderMark)**() const |
| int                             | **[integerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#integerBase)**() const |
| QLocale                         | **[locale](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#locale)**() const |
| QTextStream::NumberFlags        | **[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)**() const |
| QChar                           | **[padChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#padChar)**() const |
| qint64                          | **[pos](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)**() const |
| QString                         | **[read](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)**(qint64 *maxlen*) |
| QString                         | **[readAll](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)**() |
| QString                         | **[readLine](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)**(qint64 *maxlen* = 0) |
| bool                            | **[readLineInto](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLineInto)**(QString **line*, qint64 *maxlen* = 0) |
| QTextStream::RealNumberNotation | **[realNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberNotation)**() const |
| int                             | **[realNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberPrecision)**() const |
| void                            | **[reset](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)**() |
| void                            | **[resetStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)**() |
| bool                            | **[seek](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)**(qint64 *pos*) |
| void                            | **[setAutoDetectUnicode](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAutoDetectUnicode)**(bool *enabled*) |
| void                            | **[setDevice](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)**(QIODevice **device*) |
| void                            | **[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)**(QStringConverter::Encoding *encoding*) |
| void                            | **[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)**(QTextStream::FieldAlignment *mode*) |
| void                            | **[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)**(int *width*) |
| void                            | **[setGenerateByteOrderMark](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGenerateByteOrderMark)**(bool *generate*) |
| void                            | **[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)**(int *base*) |
| void                            | **[setLocale](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLocale)**(const QLocale &*locale*) |
| void                            | **[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)**(QTextStream::NumberFlags *flags*) |
| void                            | **[setPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPadChar)**(QChar *ch*) |
| void                            | **[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)**(QTextStream::RealNumberNotation *notation*) |
| void                            | **[setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)**(int *precision*) |
| void                            | **[setStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatus)**(QTextStream::Status *status*) |
| void                            | **[setString](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setString)**(QString **string*, QIODeviceBase::OpenMode *openMode* = ReadWrite) |
| void                            | **[skipWhiteSpace](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#skipWhiteSpace)**() |
| QTextStream::Status             | **[status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)**() const |
| QString *                       | **[string](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#string)**() const |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QChar *c*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-1)**(char *c*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-2)**(char16_t *c*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-3)**(short *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-4)**(unsigned short *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-5)**(int *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-6)**(unsigned int *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-7)**(long *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-8)**(unsigned long *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-9)**(qlonglong *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-10)**(qulonglong *i*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-11)**(float *f*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-12)**(double *f*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-13)**(const QString &*string*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-14)**(QStringView *string*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-15)**(QLatin1StringView *string*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-16)**(const QByteArray &*array*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-17)**(const char **string*) |
| QTextStream &                   | **[operator< < ](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-18)**(const void **ptr*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QChar &*c*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-1)**(char &*c*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-2)**(char16_t &*c*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-3)**(short &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-4)**(unsigned short &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-5)**(int &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-6)**(unsigned int &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-7)**(long &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-8)**(unsigned long &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-9)**(qlonglong &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-10)**(qulonglong &*i*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-11)**(float &*f*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-12)**(double &*f*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-13)**(QString &*str*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-14)**(QByteArray &*array*) |
| QTextStream &                   | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt-15)**(char **c*) |

## 相关非会员

| QTextStreamManipulator | **[qSetFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qSetFieldWidth)**(int *width*) |
| ---------------------- | ------------------------------------------------------------ |
| QTextStreamManipulator | **[qSetPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qSetPadChar)**(QChar *ch*) |
| QTextStreamManipulator | **[qSetRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qSetRealNumberPrecision)**(int *precision*) |

## 详细说明

QTextStream 可以操作[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， A[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或一个[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。使用QTextStream的流式运算符，您可以方便地读写单词、行和数字。为了生成文本，QTextStream 支持字段填充和对齐的格式选项以及数字格式。例子：

```
QFile data("output.txt");
if (data.open(QFile::WriteOnly | QFile::Truncate)) {
    QTextStream out(&data);
    out < <  "Result: " < <  qSetFieldWidth(10) < <  left < <  3.14 < <  2.7;
    // writes "Result: 3.14      2.7       "
}
```

使用 QTextStream 读取控制台输入和写入控制台输出也很常见。QTextStream 能够识别区域设置，并将使用正确的编码自动解码标准输入。例子：

```
QTextStream stream(stdin);
QString line;
while (stream.readLineInto(&line)) {
    ...
}
```

除了使用QTextStream的构造函数之外，您还可以通过调用来设置QTextStream操作的设备或字符串[setDevice](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)（） 或者[setString](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setString)()。您可以通过致电寻求职位[seek](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)（）， 和[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)当没有数据可供读取时，() 将返回 true。如果你打电话[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)()，QTextStream会将其写入缓冲区中的所有数据清空到设备中并调用[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)() 在设备上。

在内部，QTextStream 使用基于 Unicode 的缓冲区，并且[QStringConverter](https://doc-qt-io.translate.goog/qt-6/qstringconverter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)QTextStream 使用它来自动支持不同的编码。默认情况下，读写使用UTF-8，但你也可以通过调用设置编码[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)()。还支持自动 Unicode 检测。启用此功能（默认行为）时，QTextStream 将检测 UTF-8、UTF-16 或 UTF-32 BOM（字节顺序标记），并在读取时切换到适当的 UTF 编码。QTextStream 默认情况下不写入 BOM，但您可以通过调用启用此功能[setGenerateByteOrderMark](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGenerateByteOrderMark)（真的）。当 QTextStream 运行在[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)直接禁用编码。

使用QTextStream读取文本文件时一般有以下三种方式：

- 逐块调用[readLine](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)（） 或者[readAll](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)()。
- 逐词地。QTextStream支持流式传输到[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)s,[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)s 和 char* 缓冲区。单词由空格分隔，并且会自动跳过前导空格。
- 逐个字符，逐个流入[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或字符类型。此方法通常用于解析文件时方便的输入处理，与字符编码和行尾语义无关。要跳过空格，请调用[skipWhiteSpace](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#skipWhiteSpace)()。

由于文本流使用缓冲区，因此您不应使用超类的实现从流中读取数据。例如，如果您有一个[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并直接使用它读取[QFile::readLine](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)() 而不是使用流，文本流的内部位置将与文件的位置不同步。

默认情况下，当从文本流中读取数字时，QTextStream 将自动检测数字的基本表示形式。例如，如果数字以“0x”开头，则假定为十六进制形式。如果以数字 1-9 开头，则假定为十进制形式，依此类推。您可以通过调用设置整数基数，从而禁用自动检测[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)()。例子：

```
QTextStream in("0x50 0x20");
int firstNumber, secondNumber;

in >> firstNumber;             // firstNumber == 80
in >> dec >> secondNumber;     // secondNumber == 0

char ch;
in >> ch;                      // ch == 'x'
```

QTextStream 支持许多用于生成文本的格式化选项。您可以通过调用设置字段宽度和填充字符[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)（） 和[setPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPadChar)()。使用[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)() 设置每个字段内的对齐方式。如需真实数字，请致电[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)（） 和[setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)() 设置符号 ([SmartNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum),[ScientificNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum),[FixedNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)）和生成数字的位数精度。还可以通过以下方式获得一些额外的数字格式选项[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)()。



`< iostream>`与标准 C++ 库一样，QTextStream 也定义了几个全局操纵器函数：

|                            机械手                            |                             描述                             |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [Qt::bin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bin) | 与...一样[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)（2）。 |
| [Qt::oct](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#oct) | 与...一样[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)（8）。 |
| [Qt::dec](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dec) | 与...一样[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)（10）。 |
| [Qt::hex](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hex) | 与...一样[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)（16）。 |
| [Qt::showbase](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showbase) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)()\|[ShowBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::forcesign](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forcesign) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)()\|[ForceSign](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::forcepoint](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#forcepoint) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)()\|[ForcePoint](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::noshowbase](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noshowbase) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)() & ~[ShowBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::noforcesign](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noforcesign) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)() & ~[ForceSign](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::noforcepoint](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noforcepoint) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)() & ~[ForcePoint](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::uppercasebase](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uppercasebase) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)()\|[UppercaseBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::uppercasedigits](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uppercasedigits) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)()\|[UppercaseDigits](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::lowercasebase](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lowercasebase) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)() & ~[UppercaseBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::lowercasedigits](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lowercasedigits) | 与...一样[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)() & ~[UppercaseDigits](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)）。 |
| [Qt::fixed](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fixed) | 与...一样[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)（[FixedNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)）。 |
| [Qt::scientific](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scientific) | 与...一样[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)（[ScientificNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)）。 |
| [Qt::left](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#left) | 与...一样[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)（[AlignLeft](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldAlignment-enum)）。 |
| [Qt::right](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#right) | 与...一样[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)（[AlignRight](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldAlignment-enum)）。 |
| [Qt::center](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#center) | 与...一样[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)（[AlignCenter](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldAlignment-enum)）。 |
| [Qt::endl](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endl) | 与运算符< < ('\n') 和相同[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)()。 |
| [Qt::flush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush) | 与...一样[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)()。 |
| [Qt::reset](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset) | 与...一样[reset](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#reset)()。 |
| [Qt::ws](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ws) | 与...一样[skipWhiteSpace](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#skipWhiteSpace)()。 |
| [Qt::bom](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bom) | 与...一样[setGenerateByteOrderMark](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGenerateByteOrderMark)（真的）。 |

此外，Qt 提供了三个带有参数的全局操纵器：[qSetFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qSetFieldWidth)(),[qSetPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qSetPadChar)（）， 和[qSetRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qSetRealNumberPrecision)()。

**也可以看看**[QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QBuffer](https://doc-qt-io.translate.goog/qt-6/qbuffer.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QTcpSocket](https://doc-qt-io.translate.goog/qt-6/qtcpsocket.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QTextStream::FieldAlignment

此枚举指定当字段比占据它的文本宽时如何对齐字段中的文本。

| 持续的                              | 价值 | 描述                                         |
| ----------------------------------- | ---- | -------------------------------------------- |
| `QTextStream::AlignLeft`            | `0`  | 垫在字段的右侧。                             |
| `QTextStream::AlignRight`           | `1`  | 垫在字段的左侧。                             |
| `QTextStream::AlignCenter`          | `2`  | 垫在场地两侧。                               |
| `QTextStream::AlignAccountingStyle` | `3`  | 与 AlignRight 相同，只不过数字的符号左对齐。 |

**也可以看看**[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)()。

### 枚举 QTextStream:: NumberFlag 标志 QTextStream:: NumberFlags

`float`该枚举指定了可以设置为影响整数、 s 和`double`s的输出的各种标志。

| 持续的                         | 价值   | 描述                                                         |
| ------------------------------ | ------ | ------------------------------------------------------------ |
| `QTextStream::ShowBase`        | `0x1`  | 如果基数为 16（“0x”）、8（“0”）或 2（“0b”），则将基数显示为前缀。 |
| `QTextStream::ForcePoint`      | `0x2`  | 即使没有小数，也始终在数字中添加小数分隔符。                 |
| `QTextStream::ForceSign`       | `0x4`  | 始终将符号放在数字中，即使是正数。                           |
| `QTextStream::UppercaseBase`   | `0x8`  | 使用大写版本的基本前缀（“0X”、“0B”）。                       |
| `QTextStream::UppercaseDigits` | `0x10` | 表示 10 至 35 的数字时请使用大写字母，而不是小写字母。       |

NumberFlags 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < NumberFlag> 的类型定义。它存储 NumberFlag 值的 OR 组合。

**也可以看看**[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)()。

### enum QTextStream::RealNumberNotation

该枚举指定使用哪些符号来表达`float`和`double`作为字符串。

| 持续的                            | 价值 | 描述                                                         |
| --------------------------------- | ---- | ------------------------------------------------------------ |
| `QTextStream::ScientificNotation` | `2`  | 科学计数法（`printf()`的`%e`标志）。                         |
| `QTextStream::FixedNotation`      | `1`  | 定点表示法（`printf()`的`%f`标志）。                         |
| `QTextStream::SmartNotation`      | `0`  | 科学或定点表示法，取决于哪个最有意义（`printf()`的`%g`标志）。 |

**也可以看看**[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)()。

### enum QTextStream::Status

该枚举描述了文本流的当前状态。

| 持续的                         | 价值 | 描述                                 |
| ------------------------------ | ---- | ------------------------------------ |
| `QTextStream::Ok`              | `0`  | 文本流运行正常。                     |
| `QTextStream::ReadPastEnd`     | `1`  | 文本流已读取到底层设备中的数据末尾。 |
| `QTextStream::ReadCorruptData` | `2`  | 文本流读取了损坏的数据。             |
| `QTextStream::WriteFailed`     | `3`  | 文本流无法写入底层设备。             |

**也可以看看**[status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)()。

## 成员函数文档

### QTextStream::QTextStream()

构造一个 QTextStream。在使用它进行读取或写入之前，必须分配一个设备或字符串。

**也可以看看**[setDevice](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)（） 和[setString](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setString)()。

### `[explicit]`QTextStream::QTextStream([QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device*)

构造一个 QTextStream 来操作*device*。

### `[explicit]`QTextStream::QTextStream(FILE **fileHandle*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *openMode* = ReadWrite)

构造一个 QTextStream 来操作*fileHandle*， 使用*openMode*定义打开模式。在内部，一个[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建来处理 FILE 指针。

此构造函数对于直接使用基于常见 FILE 的输入和输出流非常有用：stdin、stdout 和 stderr。例子：

```
QString str;
QTextStream in(stdin);
in >> str;
```

### `[explicit]`QTextStream::QTextStream([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **string*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *openMode* = ReadWrite)

构造一个 QTextStream 来操作*string*， 使用*openMode*定义打开模式。

### `[explicit]`QTextStream::QTextStream([QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **array*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *openMode* = ReadWrite)

构造一个 QTextStream 来操作*array*， 使用*openMode*定义打开模式。在内部，该数组被一个[QBuffer](https://doc-qt-io.translate.goog/qt-6/qbuffer.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[explicit]`QTextStream::QTextStream(const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*array*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *openMode* = ReadOnly)

构造一个 QTextStream 来操作*array*， 使用*openMode*定义打开模式。无论其中的值如何，该数组都以只读方式访问*openMode*。

这个构造函数对于处理常量字符串很方便。例子：

```
int main(int argc, char *argv[])
{
    // read numeric arguments (123, 0x20, 4.5...)
    for (int i = 1; i <  argc; ++i) {
          int number;
          QTextStream in(argv[i]);
          in >> number;
          ...
    }
}
```

### `[virtual noexcept]`QTextStream::~QTextStream()

摧毁了[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

如果流在设备上运行，[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)() 将被隐式调用。否则，设备不受影响。

### bool QTextStream::atEnd() const

`true`如果没有更多数据可供读取则返回[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 否则返回`false`. 这与调用类似，但不一样[QIODevice::atEnd](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)（）， 作为[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)还考虑了其内部 Unicode 缓冲区。

### bool QTextStream::autoDetectUnicode() const

`true`如果启用了自动 Unicode 检测，则返回，否则返回`false`。默认情况下启用自动 Unicode 检测。

**也可以看看**[setAutoDetectUnicode](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAutoDetectUnicode)（） 和[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)()。

### [QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextStream::device() const

返回与关联的当前设备[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，或者`nullptr`如果尚未分配设备。

**也可以看看**[setDevice](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)（） 和[string](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#string)()。

### [QStringConverter::Encoding](https://doc-qt-io.translate.goog/qt-6/qstringconverter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Encoding-enum) QTextStream::encoding() const

返回当前分配给流的编码。

**也可以看看**[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)(),[setAutoDetectUnicode](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAutoDetectUnicode)（）， 和[locale](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#locale)()。

### [QTextStream::FieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldAlignment-enum) QTextStream::fieldAlignment() const

返回当前字段对齐方式。

**也可以看看**[setFieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldAlignment)（） 和[fieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldWidth)()。

### int QTextStream::fieldWidth() const

返回当前字段宽度。

**也可以看看**[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)()。

### void QTextStream::flush()

刷新所有等待写入设备的缓冲数据。

如果[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对字符串进行操作，该函数不执行任何操作。

### bool QTextStream::generateByteOrderMark() const

返回`true`如果[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)设置为使用 UTF 编码时生成 UTF BOM（字节顺序标记）；否则返回`false`. UTF BOM 生成默认设置为 false。

**也可以看看**[setGenerateByteOrderMark](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGenerateByteOrderMark)()。

### int QTextStream::integerBase() const

返回整数的当前基数。0表示读取时检测底数，生成数字时检测10（十进制）。

**也可以看看**[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)(),[QString::number](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#number)（）， 和[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)()。

### [QLocale](https://doc-qt-io.translate.goog/qt-6/qlocale.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextStream::locale() const

返回此流的区域设置。默认区域设置是 C。

**也可以看看**[setLocale](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLocale)()。

### [QTextStream::NumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum) QTextStream::numberFlags() const

返回当前的数字标志。

**也可以看看**[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)(),[integerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#integerBase)（）， 和[realNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberNotation)()。

### [QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextStream::padChar() const

返回当前的填充字符。

**也可以看看**[setPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPadChar)（） 和[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)()。

### [qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) QTextStream::pos() const

返回与流的当前位置相对应的设备位置，如果发生错误（例如，如果没有设备或字符串，或者存在设备错误），则返回 -1。

因为[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被缓冲后，该函数可能必须寻找设备以重建有效的设备位置。此操作可能会很昂贵，因此您可能希望避免在紧密循环中调用此函数。

**也可以看看**[seek](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#seek)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextStream::read([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *maxlen*)

最多读*maxlen*从流中读取字符，并返回读取的数据[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[readAll](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)(),[readLine](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)（）， 和[QIODevice::read](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#read)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextStream::readAll()

读取流的全部内容，并将其作为[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。处理大文件时避免使用此函数，因为它将消耗大量内存。

呼唤[readLine](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)如果您不知道有多少数据可用，则 () 更好。

**也可以看看**[readLine](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QTextStream::readLine([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *maxlen* = 0)

从流中读取一行文本，并将其作为[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。允许的最大线路长度设置为*maxlen*。如果流包含比这长的行，那么这些行将在之后被分割*maxlen*字符并分部分返回。

如果*maxlen*为 0 时，线可以是任意长度。

返回的行没有尾随行尾字符（“\n”或“\r\n”），因此调用[QString::trimmed](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#trimmed)() 可能是不必要的。

如果流已读到文件末尾，readLine() 将返回 null[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。对于字符串或支持它的设备，您可以使用显式测试流的结尾[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)()。

**也可以看看**[readAll](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)（） 和[QIODevice::readLine](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)()。

### bool QTextStream::readLineInto([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **line*, [qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *maxlen* = 0)

从流中读取一行文本到*line*。如果*line*即`nullptr`，读取的行不被存储。

允许的最大线路长度设置为*maxlen*。如果流包含比这长的行，那么这些行将在之后被分割*maxlen*字符并分部分返回。

如果*maxlen*为 0 时，线可以是任意长度。

结果行没有尾随行尾字符（“\n”或“\r\n”），因此调用[QString::trimmed](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#trimmed)() 可能是不必要的。

如果*line*如果有足够的容量来容纳即将读取的数据，则该函数可能不需要分配新的内存。因此，它可以比[readLine](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)()。

返回`false`流是否已读到文件末尾或发生错误；否则返回`true`. 内容在*line*无论如何，在呼叫被丢弃之前。

**也可以看看**[readAll](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readAll)（） 和[QIODevice::readLine](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readLine)()。

### [QTextStream::RealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum) QTextStream::realNumberNotation() const

返回当前的实数表示法。

**也可以看看**[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)(),[realNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberPrecision)(),[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)（）， 和[integerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#integerBase)()。

### int QTextStream::realNumberPrecision() const

返回当前实数精度，或小数位数[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)生成实数时会写入（[FixedNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum),[ScientificNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)），或最大有效位数（[SmartNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)）。

**也可以看看**[setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)(),[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)(),[realNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberNotation)(),[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)（）， 和[integerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#integerBase)()。

### void QTextStream::reset()

重置[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的格式选项，使其恢复到原始构造状态。设备、字符串和任何缓冲的数据保持不变。

### void QTextStream::resetStatus()

重置文本流的状态。

**也可以看看**[QTextStream::Status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)（）， 和[setStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatus)()。

### bool QTextStream::seek([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *pos*)

寻求职位*pos*在设备中。`true`成功回报；否则返回`false`.

### void QTextStream::setAutoDetectUnicode(bool *enabled*)

如果*enabled*是真的，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将尝试通过查看流数据来检测 Unicode 编码，看看是否可以找到 UTF-8、UTF-16 或 UTF-32 字节顺序标记 (BOM)。如果发现这个标记，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将用 UTF 编码替换当前编码。

该功能可以与[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)()。通常将编码设置为 UTF-8，然后启用 UTF-16 检测。

**也可以看看**[autoDetectUnicode](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoDetectUnicode)（） 和[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)()。

### void QTextStream::setDevice([QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device*)

将当前设备设置为*device*。如果设备已被分配，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将会通知[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)() 更换旧设备之前。

**注意：**此函数将语言环境重置为默认语言环境（“C”），并将编码重置为默认编码 UTF-8。

**也可以看看**[device](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)（） 和[setString](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setString)()。

### void QTextStream::setEncoding([QStringConverter::Encoding](https://doc-qt-io.translate.goog/qt-6/qstringconverter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Encoding-enum) *encoding*)

将此流的编码设置为*encoding*。编码用于解码从指定设备读取的任何数据，以及对写入的任何数据进行编码。默认情况下，[QStringConverter::Utf8](https://doc-qt-io.translate.goog/qt-6/qstringconverter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Encoding-enum)使用，并启用自动 unicode 检测。

如果[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对字符串进行操作，该函数不执行任何操作。

**警告：**如果在文本流从打开的顺序套接字读取时调用此函数，则内部缓冲区可能仍包含使用旧编码解码的文本。

**也可以看看**[encoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encoding)(),[setAutoDetectUnicode](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAutoDetectUnicode)（）， 和[setLocale](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLocale)()。

### void QTextStream::setFieldAlignment([QTextStream::FieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FieldAlignment-enum) *mode*)

将字段对齐设置为*mode*。与一起使用时[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)()，此函数允许您生成文本左对齐、右对齐或居中对齐的格式化输出。

**也可以看看**[fieldAlignment](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldAlignment)（） 和[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)()。

### void QTextStream::setFieldWidth(int *width*)

将当前字段宽度设置为*width*。如果*width*为 0（默认值），字段宽度等于生成文本的长度。

**注意：**字段宽度适用于调用此函数后附加到此流的每个元素（例如，它还填充 endl）。此行为与 STL 中的类似类不同，其中字段宽度仅适用于下一个元素。

**也可以看看**[fieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fieldWidth)（） 和[setPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPadChar)()。

### void QTextStream::setGenerateByteOrderMark(bool *generate*)

如果*generate*为 true 并且使用 UTF 编码，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将在任何数据写入设备之前插入 BOM（字节顺序标记）。如果*generate*为 false，则不会插入 BOM。必须在写入任何数据之前调用此函数。否则，它什么也不做。

**也可以看看**[generateByteOrderMark](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#generateByteOrderMark)（） 和[bom](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bom)()。

### void QTextStream::setIntegerBase(int *base*)

将整数的基数设置为*base*，既用于读取又用于生成数字。*base*可以是 2（二进制）、8（八进制）、10（十进制）或 16（十六进制）。如果*base*是 0，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将尝试通过检查流上的数据来检测碱基。生成数字时，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)假设基数为 10，除非已明确设置基数。

**也可以看看**[integerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#integerBase)(),[QString::number](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#number)（）， 和[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)()。

### void QTextStream::setLocale(const [QLocale](https://doc-qt-io.translate.goog/qt-6/qlocale.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*locale*)

将此流的区域设置设置为*locale*。指定的区域设置用于数字及其字符串表示形式之间的转换。

默认区域设置是 C，这是一种特殊情况 - 出于向后兼容性的原因，不使用千位组分隔符。

**也可以看看**[locale](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#locale)()。

### void QTextStream::setNumberFlags([QTextStream::NumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum) *flags*)

将当前数字标志设置为*flags*。*flags*是一组标志[NumberFlag](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#NumberFlag-enum)enum，并描述用于格式化生成的代码的选项（例如，是否始终写入数字的基数或符号）。

**也可以看看**[numberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#numberFlags)(),[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)（）， 和[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)()。

### void QTextStream::setPadChar([QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *ch*)

将填充字符设置为*ch*。默认值为 ASCII 空格字符 (' ')，或[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（0x20）。该字符用于在生成文本时填充字段中的空格。

例子：

```
QString s;
QTextStream out(&s);
out.setFieldWidth(10);
out.setFieldAlignment(QTextStream::AlignCenter);
out.setPadChar('-');
out < <  "Qt" < <  "rocks!";
```

该字符串`s`包含：

```
----Qt------rocks!--
```

**也可以看看**[padChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#padChar)（） 和[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)()。

### void QTextStream::setRealNumberNotation([QTextStream::RealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum) *notation*)

将实数表示法设置为*notation*（[SmartNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum),[FixedNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum),[ScientificNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)）。当读取和生成数字时，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用该值来检测实数的格式。

**也可以看看**[realNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberNotation)(),[setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)(),[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)（）， 和[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)()。

### void QTextStream::setRealNumberPrecision(int *precision*)

将实数的精度设置为*precision*。该值描述小数位数[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)生成实数时应该写（[FixedNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum),[ScientificNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)），或最大有效位数（[SmartNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)）。

精度不能为负值。默认值为 6。

**也可以看看**[realNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#realNumberPrecision)（） 和[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)()。

### void QTextStream::setStatus([QTextStream::Status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum) *status*)

将文本流的状态设置为*status*给予。

对 setStatus() 的后续调用将被忽略，直到[resetStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)（） 叫做。

**也可以看看**[Status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#status)（）， 和[resetStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)()。

### void QTextStream::setString([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **string*, [QIODeviceBase::OpenMode](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OpenModeFlag-enum) *openMode* = ReadWrite)

将当前字符串设置为*string*，使用给定的*openMode*。如果设备已被分配，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将会通知[flush](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flush)() 之前替换它。

**也可以看看**[string](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#string)（） 和[setDevice](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDevice)()。

### void QTextStream::skipWhiteSpace()

从流中读取并丢弃空格，直到检测到非空格字符，或者直到[atEnd](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#atEnd)() 返回 true。当逐个字符读取流时，此函数非常有用。

空白字符是所有符合以下条件的字符[QChar::isSpace](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSpace)() 返回`true`.

**也可以看看**[operator>>](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)()。

### [QTextStream::Status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum) QTextStream::status() const

返回文本流的状态。

**也可以看看**[QTextStream::Status](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Status-enum),[setStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStatus)（）， 和[resetStatus](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetStatus)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QTextStream::string() const

返回分配给的当前字符串[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，或者`nullptr`如果尚未分配字符串。

**也可以看看**[setString](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setString)（） 和[device](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < ([QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *c*)

写出字符*c*到流，然后返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (char *c*)

这是一个过载功能。

转换*c*从 ASCII 到[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，然后将其写入流。

### `[since 6.3.1]`[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (char16_t *c*)

这是一个过载功能。

写入 Unicode 字符*c*到流，然后返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

该功能是在 Qt 6.3.1 中引入的。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (short *i*)

写入整数*i*到流，然后返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。默认情况下，数字以十进制形式存储，但您也可以通过调用设置基数[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)()。

**也可以看看**[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)（） 和[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (unsigned short *i*)

这是一个过载功能。

写入无符号短整型*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (int *i*)

这是一个过载功能。

写入有符号 int*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (unsigned int *i*)

这是一个过载功能。

写入无符号整型*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (long *i*)

这是一个过载功能。

写入有符号长*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (unsigned long *i*)

这是一个过载功能。

写入无符号长整型*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < ([qlonglong](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qlonglong-typedef) *i*)

这是一个过载功能。

写qlonglong*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < ([qulonglong](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qulonglong-typedef) *i*)

这是一个过载功能。

写曲龙龙*i*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (float *f*)

写出实数*f*到流，然后返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。默认情况下，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)存储它使用[SmartNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RealNumberNotation-enum)，精度高达 6 位。您可以更改文本表示[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将通过调用使用实数[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)(),[setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)（） 和[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)()。

**也可以看看**[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)(),[setRealNumberNotation](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberNotation)(),[setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)（）， 和[setNumberFlags](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNumberFlags)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (double *f*)

这是一个过载功能。

写成双数*f*到溪流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*string*)

写入字符串*string*到流，并返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。在将字符串写入流之前，首先使用指定的编码（默认为 UTF-8）对其进行编码。

**也可以看看**[setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)（） 和[setEncoding](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEncoding)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < ([QStringView](https://doc-qt-io.translate.goog/qt-6/qstringview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *string*)

这是一个过载功能。

写*string*到流，并返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < ([QLatin1StringView](https://doc-qt-io.translate.goog/qt-6/qlatin1stringview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *string*)

这是一个过载功能。

写*string*到流，并返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*array*)

这是一个过载功能。

写*array*到溪流。的内容*array*转换为[QString::fromUtf8](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromUtf8)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (const char **string*)

这是一个过载功能。

写入指向的常量字符串*string*到溪流。*string*假定采用 UTF-8 编码。该运算符在处理常量字符串数据时很方便。例子：

```
QTextStream out(stdout);
out < <  "Qt rocks!" < <  Qt::endl;
```

警告：[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)假设*string*指向以“\0”字符结尾的文本字符串。如果没有终止符“\0”，您的应用程序可能会崩溃。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator< < (const void **ptr*)

这是一个过载功能。

写*ptr*作为带基数的十六进制数发送到流。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>([QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*c*)

从流中读取一个字符并将其存储在*c*。返回对的引用[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，因此可以嵌套多个运算符。例子：

```
QTextStream in(file);
QChar ch1, ch2, ch3;
in >> ch1 >> ch2 >> ch3;
```

*不会*跳过空白。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(char &*c*)

这是一个过载功能。

从流中读取一个字符并将其存储在*c*。流中的字符在存储之前会转换为 ISO-8859-1。

**也可以看看**[QChar::toLatin1](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toLatin1)()。

### `[since 6.4]`[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(char16_t &*c*)

这是一个过载功能。

从流中读取一个字符并将其存储在*c*。

该功能是在 Qt 6.4 中引入的。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(short &*i*)

从流中读取一个整数并将其存储在*i*，然后返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。该数字在存储之前会转换为正确的类型。如果在流中没有检测到号码，*i*设置为 0。

默认情况下，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将尝试使用以下规则检测数字的基数：

|     字首     |      根据      |
| :----------: | :------------: |
|  “0b”或“0B”  |  2（二进制）   |
| “0”后接“0-7” |  8（八进制）   |
|  否则为“0”   |  10（十进制）  |
|  “0x”或“0X”  | 16（十六进制） |
|   “1”到“9”   |  10（十进制）  |

通过致电[setIntegerBase](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setIntegerBase)()，可以显式指定整数基数。这将禁用自动检测，并加快速度[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)轻微地。

前导空格将被跳过。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(unsigned short &*i*)

这是一个过载功能。

将整数存储在无符号短整型中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(int &*i*)

这是一个过载功能。

将整数存储在有符号 int 中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(unsigned int &*i*)

这是一个过载功能。

将整数存储在 unsigned int 中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(long &*i*)

这是一个过载功能。

将整数存储在有符号长整型中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(unsigned long &*i*)

这是一个过载功能。

将整数存储在 unsigned long 中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>([qlonglong](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qlonglong-typedef) &*i*)

这是一个过载功能。

将整数存储在 qlonglong 中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>([qulonglong](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qulonglong-typedef) &*i*)

这是一个过载功能。

将整数存储在 qulonglong 中*i*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(float &*f*)

从流中读取一个实数并将其存储在*f*，然后返回对[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。该数字被转换为正确的类型。如果在流中没有检测到实数，*f*设置为 0.0。

作为一个特殊的例外，[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)允许字符串“nan”和“inf”表示 NAN 和 INF 浮点数或双精度数。

前导空格将被跳过。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(double &*f*)

这是一个过载功能。

将实数存储在双精度数中*f*。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*str*)

从流中读取一个单词并将其存储在*str*，然后返回对流的引用。单词之间用空格分隔（即所有字符[QChar::isSpace](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSpace)() 返回`true`)。

前导空格将被跳过。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>([QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*array*)

这是一个过载功能。

将单词转换为 UTF-8，然后将其存储在*array*。

**也可以看看**[QString::toLatin1](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toLatin1)()。

### [QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QTextStream) &QTextStream::operator>>(char **c*)

这是一个过载功能。

将单词转换为 UTF-8 并将其存储在*c*，以 '\0' 字符终止。如果没有可用的单词，则仅存储“\0”字符。

警告：虽然方便，但该操作符很危险，必须小心使用。[QTextStream](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)假设*c*指向有足够空间容纳单词的缓冲区。如果缓冲区太小，您的应用程序可能会崩溃。对于由 QChar 组成的字`n`，缓冲区需要至少为`3*n+1`字符长。

如果可能的话，使用[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)改为运算符。

## 相关非会员

### QTextStreamManipulator qSetFieldWidth(int *width*)

相当于[QTextStream::setFieldWidth](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFieldWidth)（*width*）。

### QTextStreamManipulator qSetPadChar([QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *ch*)

相当于[QTextStream::setPadChar](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPadChar)（*ch*）。

### QTextStreamManipulator qSetRealNumberPrecision(int *precision*)

相当于[QTextStream::setRealNumberPrecision](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRealNumberPrecision)（*precision*）。