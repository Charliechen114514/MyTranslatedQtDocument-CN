 QDebug Class

QDebug 类提供调试信息的输出流。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QDebug>                                           |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:        | QT += core                                                   |
| Inherits:     | [QIODeviceBase](https://doc-qt-io.translate.goog/qt-6/qiodevicebase.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| Inherited By: | [QQmlInfo](https://doc-qt-io.translate.goog/qt-6/qqmlinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdebug-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QDebug 是[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共类型

| enum | **[VerbosityLevel](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerbosityLevel-enum)** { MinimumVerbosity, DefaultVerbosity, MaximumVerbosity } |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 公共职能

|          | **[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug)**(QIODevice **device*) |
| -------- | ------------------------------------------------------------ |
|          | **[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug-1)**(QString **string*) |
|          | **[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug-2)**(QtMsgType *t*) |
|          | **[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug-3)**(const QDebug &*o*) |
|          | **[~QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDebug)**() |
| bool     | **[autoInsertSpaces](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoInsertSpaces)**() const |
| QDebug & | **[maybeQuote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maybeQuote)**(char *c* = '"') |
| QDebug & | **[maybeSpace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maybeSpace)**() |
| QDebug & | **[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)**() |
| QDebug & | **[nospace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nospace)**() |
| QDebug & | **[quote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quote)**() |
| QDebug & | **[resetFormat](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetFormat)**() |
| void     | **[setAutoInsertSpaces](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAutoInsertSpaces)**(bool *b*) |
| void     | **[setVerbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerbosity)**(int *verbosityLevel*) |
| QDebug & | **[space](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#space)**() |
| void     | **[swap](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QDebug &*other*) |
| QDebug & | **[verbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verbosity)**(int *verbosityLevel*) |
| int      | **[verbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verbosity-1)**() const |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QChar *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-1)**(bool *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-2)**(char *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-3)**(short *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-4)**(unsigned short *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-5)**(char16_t *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-6)**(char32_t *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-7)**(int *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-8)**(unsigned int *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-9)**(long *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-10)**(unsigned long *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-11)**(qint64 *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-12)**(quint64 *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-14)**(float *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-15)**(double *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-16)**(const char **t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-17)**(const char16_t **t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-18)**(const QString &*t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-19)**(QStringView *s*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-20)**(QUtf8StringView *s*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-21)**(QLatin1StringView *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-22)**(const QByteArray &*t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-23)**(QByteArrayView *t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-24)**(const void **t*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-28)**(const std::basic_string<Char, Args...> &*s*) |
| QDebug & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-29)**(std::basic_string_view<Char, Args...> *s*) |
| QDebug & | **[operator=](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QDebug &*other*) |

## 静态公共成员

| QString | **[toString](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toString)**(T &&*object*) |
| ------- | ------------------------------------------------------------ |
|         |                                                              |

## 相关非会员

| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-36)**(QDebug *debug*, const QMultiMap<Key, T> &*map*) |
| ------ | ------------------------------------------------------------ |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-37)**(QDebug *debug*, const std::map<Key, T, Compare, Alloc> &*map*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-38)**(QDebug *debug*, const std::multimap<Key, T, Compare, Alloc> &*map*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-39)**(QDebug *debug*, const QHash<Key, T> &*hash*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-40)**(QDebug *debug*, const QMultiHash<Key, T> &*hash*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-41)**(QDebug *debug*, const QPair<T1, T2> &*pair*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-42)**(QDebug *debug*, const std::pair<T1, T2> &*pair*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-43)**(QDebug *debug*, const QContiguousCache<  T> &*cache*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-44)**(QDebug *debug*, const QFlags<  T> &*flags*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-30)**(QDebug *debug*, const QList<  T> &*list*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-31)**(QDebug *debug*, const QVarLengthArray<T, P> &*array* = P) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-32)**(QDebug *debug*, const std::list<T, Alloc> &*vec*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-33)**(QDebug *debug*, const std::vector<T, Alloc> &*vec*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-34)**(QDebug *debug*, const QSet<  T> &*set*) |
| QDebug | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt-35)**(QDebug *debug*, const QMap<Key, T> &*map*) |

## 详细说明

当开发人员需要将调试或跟踪信息写入设备、文件、字符串或控制台时，就会使用 QDebug。

### 基本使用

在常见情况下，调用[qDebug](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qDebugx)() 函数获取默认的 QDebug 对象以用于写入调试信息。

```
    qDebug() << "Date:" << QDate::currentDate();
    qDebug() << "Types:" << QString("String") << QChar('x') << QRect(0, 10, 50, 40);
    qDebug() << "Custom coordinate type:" << coordinate;
```

这使用接受的构造函数构造了一个 QDebug 对象[QtMsgType](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QtMsgType-enum)的价值[QtDebugMsg](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QtMsgType-enum)。同样，[qWarning](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qWarning)(),[qCritical](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qCritical)（） 和[qFatal](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qFatal)() 函数还返回相应消息类型的 QDebug 对象。

该类还为其他情况提供了几个构造函数，包括一个接受[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或任何其他[QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于将调试信息写入文件和其他设备的子类。构造函数接受一个[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于写入字符串以进行显示或序列化。

### 格式选项

QDebug 格式化输出以便于读取。它会自动在参数之间添加空格，并在周围添加引号[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)论据。

您可以通过以下方式调整这些选项[space](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#space)(),[nospace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nospace)（） 和[quote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quote)(),[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)（） 方法。此外，[QTextStream manipulators](https://doc-qt-io.translate.goog/qt-6/qtextstream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qtextstream-manipulators)可以通过管道传输到 QDebug 流中。

[QDebugStateSaver](https://doc-qt-io.translate.goog/qt-6/qdebugstatesaver.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将格式更改限制在当前范围内。[resetFormat](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetFormat)() 将选项重置为默认值。

### 将自定义类型写入流

许多标准类型都可以写入 QDebug 对象，并且 Qt 提供对大多数 Qt 值类型的支持。要添加对自定义类型的支持，您需要实现一个流运算符，如下例所示：

```
QDebug operator<<(QDebug debug, const Coordinate &c)
{
    QDebugStateSaver saver(debug);
    debug.nospace() << '(' << c.x() << ", " << c.y() << ')';

    return debug;
}
```

这在[Debugging Techniques](https://doc-qt-io.translate.goog/qt-6/debug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[Creating Custom Qt Types](https://doc-qt-io.translate.goog/qt-6/custom-types.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#making-the-type-printable)文件。

## 会员类型文档

### enum QDebug::VerbosityLevel

该枚举描述了详细级别的范围。

| 持续的                     | 价值 |
| -------------------------- | ---- |
| `QDebug::MinimumVerbosity` | `0`  |
| `QDebug::DefaultVerbosity` | `2`  |
| `QDebug::MaximumVerbosity` | `7`  |

**也可以看看**[verbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verbosity-1)（） 和[setVerbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerbosity)()。

## 成员函数文档

### `[since 6.5]`template <typename Char, typename Args> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(const std::basic_string<Char, Args...> &*s*)

### `[since 6.5]`template <typename Char, typename Args> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(std::basic_string_view<Char, Args...> *s*)

写入字符串或字符串视图*s*到流并返回对流的引用。

这些运算符仅参与重载决策，如果`Char`是以下之一

- 字符
- char8_t（仅限 C++20）
- 字符16_t
- char32_t
- wchar_t

该功能是在 Qt 6.5 中引入的。

### `[explicit]`QDebug::QDebug([QIODevice](https://doc-qt-io.translate.goog/qt-6/qiodevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device*)

构造一个写入给定的调试流*device*。

### `[explicit]`QDebug::QDebug([QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **string*)

构造一个写入给定的调试流*string*。

### `[explicit]`QDebug::QDebug([QtMsgType](https://doc-qt-io.translate.goog/qt-6/qtlogging.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QtMsgType-enum) *t*)

构造一个调试流，写入消息类型的处理程序*t*。

### QDebug::QDebug(const [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &*o*)

构造另一个调试流的副本*o*。

### QDebug::~QDebug()

刷新所有待写入的数据并销毁调试流。

### bool QDebug::autoInsertSpaces() const

`true`如果这样则返回[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例将自动在写入之间插入空格。

**也可以看看**[setAutoInsertSpaces](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAutoInsertSpaces)（） 和[QDebugStateSaver](https://doc-qt-io.translate.goog/qt-6/qdebugstatesaver.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::maybeQuote(char *c* = '"')

写一个字符*c*到调试流，具体取决于自动插入引号的当前设置，并返回对流的引用。

默认字符是双引号`"`。

**也可以看看**[quote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quote)（） 和[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)()。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::maybeSpace()

根据自动插入空格的当前设置，将空格字符写入调试流，并返回对流的引用。

**也可以看看**[space](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#space)（） 和[nospace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nospace)()。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::noquote()

禁用自动插入引号字符[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)内容并返回对流的引用。

当禁用引用时，打印这些类型时不带引号字符，也不转义不可打印的字符。

**也可以看看**[quote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quote)（） 和[maybeQuote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maybeQuote)()。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::nospace()

禁用自动插入空格并返回对流的引用。

**也可以看看**[space](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#space)（） 和[maybeSpace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maybeSpace)()。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::quote()

启用周围自动插入引号字符[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)内容并返回对流的引用。

默认情况下启用引用。

**也可以看看**[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)（） 和[maybeQuote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maybeQuote)()。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::resetFormat()

重置流格式化选项，使其恢复到其原始构造状态。

**也可以看看**[space](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#space)（） 和[quote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quote)()。

### void QDebug::setAutoInsertSpaces(bool *b*)

启用在写入之间自动插入空格，如果*b*是真的; 否则自动插入空格将被禁用。

**也可以看看**[autoInsertSpaces](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoInsertSpaces)（） 和[QDebugStateSaver](https://doc-qt-io.translate.goog/qt-6/qdebugstatesaver.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QDebug::setVerbosity(int *verbosityLevel*)

将流的详细程度设置为*verbosityLevel*。

允许的范围是 0 到 7。默认值为 2。

**也可以看看**[verbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verbosity-1)（） 和[VerbosityLevel](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerbosityLevel-enum)。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::space()

将空格字符写入调试流并返回对该流的引用。

流会记住为将来的写入启用了自动插入空格。

**也可以看看**[nospace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nospace)（） 和[maybeSpace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#maybeSpace)()。

### void QDebug::swap([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &*other*)

将此调试流实例交换为*other*。这个功能非常快并且永远不会失败。

### `[static, since 6.0]`template < typename T> [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDebug::toString(T &&*object*)

流*object*变成一个[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对字符串进行操作，然后返回该字符串的实例。

当您需要对象的文本表示形式进行调试但又不能使用`operator<<`. 例如：

```
    QTRY_VERIFY2(list.isEmpty(), qPrintable(QString::fromLatin1(
        "Expected list to be empty, but it has the following items: %1")).arg(QDebug::toString(list)));
```

该字符串使用流式传输[nospace](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nospace)()。

这个函数是在Qt 6.0中引入的。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::verbosity(int *verbosityLevel*)

将流的详细程度设置为*verbosityLevel*并返回对流的引用。

允许的范围是 0 到 7。默认值为 2。

**也可以看看**[verbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verbosity-1)(),[setVerbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerbosity)（）， 和[VerbosityLevel](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerbosityLevel-enum)。

### int QDebug::verbosity() const

返回调试流的详细程度。

流操作员可以检查该值以确定是否需要详细输出并根据级别打印更多信息。值越高表示需要更多信息。

允许的范围是 0 到 7。默认值为 2。

**也可以看看**[setVerbosity](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVerbosity)（） 和[VerbosityLevel](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#VerbosityLevel-enum)。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *t*)

写出人物，*t*，到流并返回对流的引用。通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将控制字符和非 US-ASCII 字符打印为其 C 转义序列或其 Unicode 值 (\u1234)。要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能，但要注意一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的，并且可能无法表示`t`.

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(bool *t*)

写入布尔值，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(char *t*)

写出人物，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(short *t*)

写入有符号短整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(unsigned short *t*)

然后写入无符号短整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(char16_t *t*)

写入 UTF-16 字符，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(char32_t *t*)

写入 UTF-32 字符，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(int *t*)

写入有符号整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(unsigned int *t*)

然后写入无符号整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(long *t*)

写入有符号长整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(unsigned long *t*)

然后写入无符号长整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) *t*)

写入有符号的 64 位整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([quint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#quint64-typedef) *t*)

然后写入无符号 64 位整数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(float *t*)

写入 32 位浮点数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(double *t*)

写入 64 位浮点数，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(const char **t*)

写入以 '\0' 结尾的 UTF-8 字符串，*t*，到流并返回对流的引用。该字符串在输出时不会被引用或转义。注意[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)内部缓冲区为 UTF-16，并且可能需要使用区域设置的编解码器转换为 8 位才能使用某些后端，这可能会导致乱码输出 (mojibake)。建议限制为 US-ASCII 字符串。

### `[since 6.0]`[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(const char16_t **t*)

写入以 u'\0' 结尾的 UTF-16 字符串，*t*，到流并返回对流的引用。该字符串在输出时不会被引用或转义。注意[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)内部缓冲区为 UTF-16，并且可能需要使用区域设置的编解码器转换为 8 位才能使用某些后端，这可能会导致乱码输出 (mojibake)。建议限制为 US-ASCII 字符串。

这个函数是在Qt 6.0中引入的。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*t*)

写入字符串，*t*，到流并返回对流的引用。通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打印引号内的字符串并将不可打印字符转换为其 Unicode 值 (\u1234)。

要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能。请注意，一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的。

输出示例：

```
    QString s;

    s = "a";
    qDebug().noquote() << s;    // prints: a
    qDebug() << s;              // prints: "a"

    s = "\"a\r\n\"";
    qDebug() << s;              // prints: "\"a\r\n\""

    s = "\033";                 // escape character
    qDebug() << s;              // prints: "\u001B"

    s = "\u00AD";               // SOFT HYPHEN
    qDebug() << s;              // prints: "\u00AD"

    s = "\u00E1";               // LATIN SMALL LETTER A WITH ACUTE
    qDebug() << s;              // prints: "á"

    s = "a\u0301";              // "a" followed by COMBINING ACUTE ACCENT
    qDebug() << s;              // prints: "á";

    s = "\u0430\u0301";         // CYRILLIC SMALL LETTER A followed by COMBINING ACUTE ACCENT
    qDebug() << s;              // prints: "а́"
```

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([QStringView](https://doc-qt-io.translate.goog/qt-6/qstringview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *s*)

写入字符串视图，*s*，到流并返回对流的引用。通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打印引号内的字符串并将不可打印字符转换为其 Unicode 值 (\u1234)。

要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能。请注意，一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的。

请参阅[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)过载为例。

### `[since 6.0]`[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([QUtf8StringView](https://doc-qt-io.translate.goog/qt-6/qutf8stringview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *s*)

写入字符串视图，*s*，到流并返回对流的引用。

通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打印引号内的数据并将控制字符或非 US-ASCII 字符转换为其 C 转义序列 (\xAB)。这样，输出始终是 7 位干净的，并且可以根据需要从输出中复制字符串并将其粘贴回 C++ 源中。

要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能。请注意，一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的。

这个函数是在Qt 6.0中引入的。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([QLatin1StringView](https://doc-qt-io.translate.goog/qt-6/qlatin1stringview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *t*)

写入字符串，*t*，到流并返回对流的引用。通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打印引号内的字符串并将不可打印字符转换为其 Unicode 值 (\u1234)。

要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能。请注意，一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的。

请参阅[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)过载为例。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(const [QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*t*)

写入字节数组，*t*，到流并返回对流的引用。通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打印引号内的数组，并将控制字符或非 US-ASCII 字符转换为其 C 转义序列 (\xAB)。这样，输出始终是 7 位干净的，并且可以根据需要从输出中复制字符串并将其粘贴回 C++ 源中。

要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能。请注意，一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的。

输出示例：

```
    QByteArray ba;

    ba = "a";
    qDebug().noquote() << ba;    // prints: a
    qDebug() << ba;              // prints: "a"

    ba = "\"a\r\n\"";
    qDebug() << ba;              // prints: "\"a\r\n\""

    ba = "\033";                 // escape character
    qDebug() << ba;              // prints: "\x1B"

    ba = "\xC3\xA1";
    qDebug() << ba;              // prints: "\xC3\xA1"

    ba = QByteArray("a\0b", 3);
    qDebug() << ba               // prints: "\a\x00""b"
```

注意如何[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)需要以 C 和 C++ 语言连接字符串文字的方式关闭并重新打开字符串，以便字母“b”不会被解释为先前的十六进制转义序列的一部分。

### `[since 6.0]`[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<([QByteArrayView](https://doc-qt-io.translate.goog/qt-6/qbytearrayview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *t*)

写入观察到的字节数组的数据，*t*，到流并返回对流的引用。

通常情况下，[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)打印引号内的数据并将控制字符或非 US-ASCII 字符转换为其 C 转义序列 (\xAB)。这样，输出始终是 7 位干净的，并且可以根据需要从输出中复制字符串并将其粘贴回 C++ 源中。

要打印不可打印的字符而不进行转换，请启用[noquote](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#noquote)() 功能。请注意，一些[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后端可能不是 8 位干净的。

请参阅[QByteArray](https://doc-qt-io.translate.goog/qt-6/qbytearray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)过载为例。

这个函数是在Qt 6.0中引入的。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator<<(const void **t*)

写一个指针，*t*，到流并返回对流的引用。

### [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &QDebug::operator=(const [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) &*other*)

分配*other*调试流到此流并返回对此流的引用。

## 相关非会员

### template <typename Key, typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QMultiMap](https://doc-qt-io.translate.goog/qt-6/qmultimap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<Key, T> &*map*)

写入内容*map*到*debug*。和`Key`都`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename Key, typename T, typename Compare, typename Alloc> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const std::map<Key, T, Compare, Alloc> &*map*)

写入内容*map*到*debug*。和`Key`都`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename Key, typename T, typename Compare, typename Alloc> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const std::multimap<Key, T, Compare, Alloc> &*map*)

写入内容*map*到*debug*。和`Key`都`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename Key, typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QHash](https://doc-qt-io.translate.goog/qt-6/qhash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<Key, T> &*hash*)

写入内容*hash*到*debug*。和`Key`都`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename Key, typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QMultiHash](https://doc-qt-io.translate.goog/qt-6/qmultihash.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<Key, T> &*hash*)

写入内容*hash*到*debug*。和`Key`都`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename T1, typename T2> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const QPair<T1, T2> &*pair*)

写入内容*pair*到*debug*。和`T1`都`T2`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename T1, typename T2> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const std::pair<T1, T2> &*pair*)

写入内容*pair*到*debug*。和`T1`都`T2`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template < typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QContiguousCache](https://doc-qt-io.translate.goog/qt-6/qcontiguouscache.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T> &*cache*)

写入内容*cache*到*debug*。`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template < typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T> &*flags*)

写*flags*到*debug*。

### template < typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T> &*list*)

写入内容*list*到*debug*。`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[since 6.3]`template <typename T, qsizetype P> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QVarLengthArray](https://doc-qt-io.translate.goog/qt-6/qvarlengtharray.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<T, P> &*array* = P)

写入内容*array*到*debug*。`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

该功能是在 Qt 6.3 中引入的。

### template <typename T, typename Alloc> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const std::list<T, Alloc> &*vec*)

写入列表的内容*vec*到*debug*。`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename T, typename Alloc> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const std::vector<T, Alloc> &*vec*)

写入向量的内容*vec*到*debug*。`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template < typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QSet](https://doc-qt-io.translate.goog/qt-6/qset.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<  T> &*set*)

写入内容*set*到*debug*。`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### template <typename Key, typename T> [QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) operator<<([QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDebug) *debug*, const [QMap](https://doc-qt-io.translate.goog/qt-6/qmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<Key, T> &*map*)

写入内容*map*到*debug*。和`Key`都`T`需要支持流式传输[QDebug](https://doc-qt-io.translate.goog/qt-6/qdebug.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。