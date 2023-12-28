#  QFileInfo Class

QFileInfo 类提供与系统无关的文件信息。[更多的...](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include < QFileInfo>                                        |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:  | QT += core                                                   |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qfileinfo-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QFileInfo 是[输入/输出、网络](https://doc-qt-io.translate.goog/qt-6/io.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共职能

|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-1)**() |
| --------------------- | ------------------------------------------------------------ |
|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-2)**(const QString &*file*) |
|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-3)**(const QFileDevice &*file*) |
|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-4)**(const QDir &*dir*, const QString &*file*) |
|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-6)**(const std::filesystem::path &*file*) |
|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-7)**(const QDir &*dir*, const std::filesystem::path &*file*) |
|                       | **[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfo-5)**(const QFileInfo &*fileinfo*) |
|                       | **[~QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QFileInfo)**() |
| QDir                  | **[absoluteDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteDir)**() const |
| QString               | **[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)**() const |
| QString               | **[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)**() const |
| QString               | **[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)**() const |
| QDateTime             | **[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)**() const |
| QDateTime             | **[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime-1)**(const QTimeZone &*tz*) const |
| QString               | **[bundleName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bundleName)**() const |
| bool                  | **[caching](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#caching)**() const |
| QString               | **[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)**() const |
| QString               | **[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)**() const |
| QString               | **[completeBaseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeBaseName)**() const |
| QString               | **[completeSuffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeSuffix)**() const |
| QDir                  | **[dir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dir)**() const |
| bool                  | **[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)**() const |
| QString               | **[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)**() const |
| QString               | **[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)**() const |
| QDateTime             | **[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)**(QFile::FileTime *time*) const |
| QDateTime             | **[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime-1)**(QFile::FileTime *time*, const QTimeZone &*tz*) const |
| std::filesystem::path | **[filesystemAbsoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemAbsoluteFilePath)**() const |
| std::filesystem::path | **[filesystemAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemAbsolutePath)**() const |
| std::filesystem::path | **[filesystemCanonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemCanonicalFilePath)**() const |
| std::filesystem::path | **[filesystemCanonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemCanonicalPath)**() const |
| std::filesystem::path | **[filesystemFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemFilePath)**() const |
| std::filesystem::path | **[filesystemJunctionTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemJunctionTarget)**() const |
| std::filesystem::path | **[filesystemPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemPath)**() const |
| std::filesystem::path | **[filesystemReadSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemReadSymLink)**() const |
| std::filesystem::path | **[filesystemSymLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemSymLinkTarget)**() const |
| QString               | **[group](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)**() const |
| uint                  | **[groupId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupId)**() const |
| bool                  | **[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)**() const |
| bool                  | **[isAlias](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAlias)**() const |
| bool                  | **[isBundle](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBundle)**() const |
| bool                  | **[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)**() const |
| bool                  | **[isExecutable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExecutable)**() const |
| bool                  | **[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)**() const |
| bool                  | **[isHidden](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isHidden)**() const |
| bool                  | **[isJunction](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isJunction)**() const |
| bool                  | **[isNativePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isNativePath)**() const |
| bool                  | **[isReadable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)**() const |
| bool                  | **[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)**() const |
| bool                  | **[isRoot](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRoot)**() const |
| bool                  | **[isShortcut](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isShortcut)**() const |
| bool                  | **[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)**() const |
| bool                  | **[isSymbolicLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymbolicLink)**() const |
| bool                  | **[isWritable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWritable)**() const |
| QString               | **[junctionTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#junctionTarget)**() const |
| QDateTime             | **[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)**() const |
| QDateTime             | **[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified-1)**(const QTimeZone &*tz*) const |
| QDateTime             | **[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)**() const |
| QDateTime             | **[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead-1)**(const QTimeZone &*tz*) const |
| bool                  | **[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)**() |
| QDateTime             | **[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)**() const |
| QDateTime             | **[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime-1)**(const QTimeZone &*tz*) const |
| QString               | **[owner](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#owner)**() const |
| uint                  | **[ownerId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ownerId)**() const |
| QString               | **[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)**() const |
| bool                  | **[permission](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permission)**(QFile::Permissions *permissions*) const |
| QFile::Permissions    | **[permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions)**() const |
| QString               | **[readSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readSymLink)**() const |
| void                  | **[refresh](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)**() |
| void                  | **[setCaching](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCaching)**(bool *enable*) |
| void                  | **[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile)**(const QString &*file*) |
| void                  | **[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile-1)**(const QFileDevice &*file*) |
| void                  | **[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile-2)**(const QDir &*dir*, const QString &*file*) |
| void                  | **[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile-3)**(const std::filesystem::path &*file*) |
| qint64                | **[size](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)**() const |
| void                  | **[stat](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stat)**() |
| QString               | **[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)**() const |
| void                  | **[swap](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QFileInfo &*other*) |
| QString               | **[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)**() const |
| bool                  | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QFileInfo &*fileinfo*) const |
| QFileInfo &           | **[operator=](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QFileInfo &*fileinfo*) |
| QFileInfo &           | **[operator=](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(QFileInfo &&*other*) |
| bool                  | **[operator==](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QFileInfo &*fileinfo*) const |

## 静态公共成员

| bool | **[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)**(const QString &*file*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 相关非会员

|      | **[QFileInfoList](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfoList-typedef)** |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 宏

|      | **[QT_IMPLICIT_QFILEINFO_CONSTRUCTION](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QT_IMPLICIT_QFILEINFO_CONSTRUCTION)** |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 详细说明

QFileInfo 提供有关文件的名称和在文件系统中的位置（路径）、其访问权限以及是否是目录或符号链接等信息。还提供文件的大小和上次修改/读取时间。QFileInfo 还可以用于获取有关 Qt 的信息[resource](https://doc-qt-io.translate.goog/qt-6/resources.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QFileInfo 可以指向具有相对或绝对文件路径的文件。绝对文件路径以目录分隔符“/”（或 Windows 上的驱动器规范）开头。相对文件名以目录名或文件名开头，并指定相对于当前工作目录的路径。绝对路径的一个示例是字符串“/tmp/quartz”。相对路径可能类似于“src/fatlib”。您可以使用该功能[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)() 检查 QFileInfo 使用的是相对文件路径还是绝对文件路径。您可以调用该函数[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)() 将 QFileInfo 的相对路径转换为绝对路径。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QFileInfo 所处理的文件在构造函数中或稍后使用[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile)()。使用[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)() 查看文件是否存在并且[size](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)() 来获取其大小。

文件的类型是通过以下方式获得的[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)（） 和[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)()。这[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)() 函数提供符号链接指向的文件的名称。

可以使用以下命令提取文件名的元素[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)（） 和[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)()。这[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)() 的部分可以用以下方式提取[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)(),[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)（） 或者[completeSuffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeSuffix)()。由 Qt 类创建的目录的 QFileInfo 对象将没有尾随文件分隔符。如果您希望在自己的文件信息对象中使用尾随分隔符，只需将 1 附加到给定构造函数的文件名或[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile)()。

日期和时间相关信息由返回[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)(),[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)(),[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)(),[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)（）， 和[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)()。有关访问权限的信息可以通过以下方式获取[isReadable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[isWritable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWritable)（）， 和[isExecutable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExecutable)()。所有权信息可以通过以下方式获取[owner](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#owner)(),[ownerId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ownerId)(),[group](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)（）， 和[groupId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupId)()。您还可以使用以下命令在单个语句中检查权限和所有权[permission](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permission)（） 功能。

### 符号链接和快捷方式

在 Unix（包括 macOS 和 iOS）上，此类中的属性 getter 函数返回目标文件的时间和大小等属性，而不是符号链接，因为 Unix 透明地处理符号链接。使用打开符号链接[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)有效地打开链接的目标。例如：

```
#ifdef Q_OS_UNIX

QFileInfo info1("/home/bob/bin/untabify");
info1.isSymLink();          // returns true
info1.absoluteFilePath();   // returns "/home/bob/bin/untabify"
info1.size();               // returns 56201
info1.symLinkTarget();      // returns "/opt/pretty++/bin/untabify"

QFileInfo info2(info1.symLinkTarget());
info2.isSymLink();          // returns false
info2.absoluteFilePath();   // returns "/opt/pretty++/bin/untabify"
info2.size();               // returns 56201

#endif
```

在 Windows 上，快捷方式（`.lnk`文件）当前被视为符号链接。与 Unix 系统一样，属性 getter 返回目标文件的大小，而不是`.lnk`文件本身。此行为已被弃用，并且可能会在 Qt 的未来版本中删除，之后`.lnk`文件将被视为常规文件。

```
#ifdef Q_OS_WIN

QFileInfo info1("C:\\Users\\Bob\\untabify.lnk");
info1.isSymLink();          // returns true
info1.absoluteFilePath();   // returns "C:/Users/Bob/untabify.lnk"
info1.size();               // returns 63942
info1.symLinkTarget();      // returns "C:/Pretty++/untabify"

QFileInfo info2(info1.symLinkTarget());
info2.isSymLink();          // returns false
info2.absoluteFilePath();   // returns "C:/Pretty++/untabify"
info2.size();               // returns 63942

#endif
```

### NTFS权限

在 NTFS 文件系统上，出于性能原因，默认情况下禁用所有权和权限检查。要启用它，请包含以下行：

```
extern Q_CORE_EXPORT int qt_ntfs_permission_lookup;
```

`qt_ntfs_permission_lookup`然后通过递增和递减1来打开和关闭权限检查。

```
qt_ntfs_permission_lookup++; // turn checking on
qt_ntfs_permission_lookup--; // turn it off again
```

**注意：**由于这是一个非原子全局变量，因此只有`qt_ntfs_permission_lookup`在主线程以外的任何线程启动之前或除主线程之外的每个线程结束之后递增或递减才是安全的。

**注意：**从 Qt 6.6 开始，该变量`qt_ntfs_permission_lookup`已被弃用。请使用以下替代方案。

管理权限检查的安全且简单的方法是使用 RAII 类`QNtfsPermissionCheckGuard`。

```
void complexFunction()
{
    QNtfsPermissionCheckGuard permissionGuard;  // check is enabled

    // do complex things here that need permission check enabled

}   // as the guard goes out of scope the check is disabled
```

如果您需要更细粒度的控制，可以使用以下函数来管理权限：

```
qAreNtfsPermissionChecksEnabled();   // check status
qEnableNtfsPermissionChecks();       // turn checking on
qDisableNtfsPermissionChecks();      // turn it off again
```

### 性能考虑因素

QFileInfo的一些函数会查询文件系统，但出于性能原因，有些函数只对文件名本身进行操作。例如：要返回相对文件名的绝对路径，[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)() 必须查询文件系统。这[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)然而，() 函数可以直接处理文件名，因此速度更快。

为了提高性能，QFileInfo 还缓存有关文件的信息。由于文件可以被其他用户或程序，甚至同一程序的其他部分更改，因此有一个刷新文件信息的函数：[refresh](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)()。如果您想关闭 QFileInfo 的缓存并强制它在每次向其请求信息时访问文件系统，请调用[setCaching](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCaching)（错误的）。如果要确保从文件系统读取所有信息，请使用[stat](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stat)()。

[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)(),[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)(),[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)(),[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)（）， 和[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)()默认返回当地时间*。*由于本机文件系统 API 通常使用 UTC，因此需要进行转换。如果您实际上不需要当地时间，您可以通过请求时间来避免这种情况[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)直接地。

### 平台特定问题

在 Android 上，处理时存在一些限制[content URIs](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/guide/topics/providers/content-provider-basics%23ContentURIs):

- 通过提示用户可能需要访问权限[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它实现了[Android's native file picker](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage/shared/documents-files)。
- 旨在遵循[Scoped storage](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage%23scoped-storage)准则，例如使用应用程序特定目录而不是其他公共外部目录。有关详细信息，另请参阅[storage best practices](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage/use-cases)。
- 由于 Qt API 的设计（例如[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)），后面的 API 无法与 Android 完全集成[MediaStore](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/reference/android/provider/MediaStore)蜜蜂。

**也可以看看**[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QFileInfo::QFileInfo()

构造一个空的 QFileInfo 对象。

请注意，空的 QFileInfo 对象不包含文件引用。

**也可以看看**[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile)()。

### `[explicit]`QFileInfo::QFileInfo(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

构造一个新的 QFileInfo，它提供有关给定文件的信息。这*file*还可以包括绝对或相对路径。

**也可以看看**[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)(),[QDir::setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)（）， 和[QDir::isRelativePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelativePath)()。

### `[explicit]`QFileInfo::QFileInfo(const [QFileDevice](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

构造一个新的 QFileInfo 来提供有关文件的信息*file*。

如果*file*有一个相对路径，QFileInfo也将有一个相对路径。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### `[explicit]`QFileInfo::QFileInfo(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dir*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

构造一个新的 QFileInfo，它提供有关给定的信息*file*相对于目录*dir*。

如果*dir*有一个相对路径，QFileInfo也将有一个相对路径。

如果*file*是绝对路径，则指定的目录*dir*将被忽视。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### `[since 6.0]`QFileInfo::QFileInfo(const std::filesystem::path &*file*)

构造一个新的 QFileInfo，它提供有关给定的信息*file*。

这个函数是在Qt 6.0中引入的。

**也可以看看**[setFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFile)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)(),[QDir::setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)（）， 和[QDir::isRelativePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelativePath)()。

### `[since 6.0]`QFileInfo::QFileInfo(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dir*, const std::filesystem::path &*file*)

构造一个新的 QFileInfo，它提供有关给定的信息*file*相对于目录*dir*。

如果*dir*有一个相对路径，QFileInfo也将有一个相对路径。

如果*file*是绝对路径，则指定的目录*dir*将被忽视。

这个函数是在Qt 6.0中引入的。

### QFileInfo::QFileInfo(const QFileInfo &*fileinfo*)

构造一个新的 QFileInfo，它是给定的副本*fileinfo*。

### `[noexcept]`QFileInfo::~QFileInfo()

摧毁了[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并释放其资源。

### [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::absoluteDir() const

返回文件的绝对路径[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

**也可以看看**[dir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dir)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（）， 和[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::absoluteFilePath() const

返回包含文件名的绝对路径。

绝对路径名由完整路径和文件名组成。在 Unix 上，这始终以根“/”目录开头。在 Windows 上，该路径始终以“D:/”开头，其中 D 是驱动器盘符，但未映射到驱动器盘符的网络共享除外，在这种情况下，路径将以“//sharename/”开头。[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将大写驱动器字母。注意[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不这样做。下面的代码片段展示了这一点。

```
    QFileInfo fi("c:/temp/foo"); => fi.absoluteFilePath() => "C:/temp/foo"
```

该函数的返回值与[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)（）， 除非[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（） 是真的。相比之下[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)()、符号链接或多余的“.” 或“..”元素不一定会被删除。

**警告：**如果[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)() 为空，该函数的行为未定义。

**也可以看看**[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)（）， 和[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::absolutePath() const

返回文件的路径绝对路径。这不包括文件名。

在 Unix 上，绝对路径始终以根目录“/”开头。在 Windows 上，该路径始终以“D:/”开头，其中 D 是驱动器盘符，但未映射到驱动器盘符的网络共享除外，在这种情况下，路径将以“//sharename/”开头。

相比之下[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)() 符号链接或多余的“.” 或“..”元素不一定会被删除。

**警告：**如果[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)() 为空，该函数的行为未定义。

**也可以看看**[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)(),[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)(),[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)(),[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（）， 和[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::baseName() const

返回不带路径的文件的基本名称。

基本名称由文件中直到（但不包括）第*一个*“.”的所有字符组成。特点。

例子：

```
QFileInfo fi("/tmp/archive.tar.gz");
QString base = fi.baseName();  // base = "archive"
```

文件的基本名称在所有平台上均等计算，与文件命名约定无关（例如，Unix 上的“.bashrc”具有空基本名称，后缀为“bashrc”）。

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)(),[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)(),[completeSuffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeSuffix)（）， 和[completeBaseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeBaseName)()。

### [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::birthTime() const

返回文件创建（生成）的日期和时间（当地时间）。

如果文件生成时间不可用，则该函数返回无效值[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该函数重载 QFileInfo::birthTime(const[QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)&tz)，并返回与 相同的结果`birthTime(QTimeZone::LocalTime)`。

**也可以看看**[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)(),[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)(),[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)（）， 和[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)()。

### `[since 6.6]`[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::birthTime(const [QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*tz*) const

返回文件创建（诞生）的日期和时间。

返回的时间位于指定的时区*tz*。例如，您可以使用[QTimeZone::LocalTime](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)或者[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)分别获取本地时区或 UTC 时间。由于本机文件系统 API 通常使用 UTC，因此使用[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)通常更快，因为它不需要任何转换。

如果文件生成时间不可用，则该函数返回无效值[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified-1)（常量 QTimeZone &），[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead-1)（常量 QTimeZone &），[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime-1)（常量 QTimeZone &），以及[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime-1)（QFile::FileTime，const QTimeZone &）。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::bundleName() const

返回包的名称。

在 macOS 和 iOS 上，如果路径为包，则返回正确的本地化名称[isBundle](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBundle)()。在所有其他平台上都是空的[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)被返回。

例子：

```
QFileInfo fi("/Applications/Safari.app");
QString bundle = fi.bundleName();                // name = "Safari"
```

**也可以看看**[isBundle](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBundle)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)（）， 和[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)()。

### bool QFileInfo::caching() const

返回`true`是否启用缓存；否则返回`false`.

**也可以看看**[setCaching](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCaching)（） 和[refresh](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::canonicalFilePath() const

返回包括文件名的规范路径，即没有符号链接或冗余“.”的绝对路径。或“..”元素。

如果文件不存在，则 canonicalFilePath() 返回空字符串。

**也可以看看**[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)（）， 和[dir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dir)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::canonicalPath() const

返回文件的路径规范路径（不包括文件名），即没有符号链接或冗余“.”的绝对路径。或“..”元素。

如果文件不存在，则 canonicalPath() 返回空字符串。

**也可以看看**[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)（） 和[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::completeBaseName() const

返回文件的完整基本名称，不带路径。

完整的基本名称由文件中直到（但不包括）*最后*一个“.”的所有字符组成。特点。

例子：

```
QFileInfo fi("/tmp/archive.tar.gz");
QString base = fi.completeBaseName();  // base = "archive.tar"
```

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)(),[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)(),[completeSuffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeSuffix)（）， 和[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::completeSuffix() const

返回文件的完整后缀（扩展名）。

完整的后缀由文件中第一个“.”之后（但不包括）的所有字符组成。

例子：

```
QFileInfo fi("/tmp/archive.tar.gz");
QString ext = fi.completeSuffix();  // ext = "tar.gz"
```

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)(),[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)(),[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)（）， 和[completeBaseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeBaseName)()。

### [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::dir() const

返回对象父目录的路径[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

注**：**[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)返回的总是对应于对象的父目录，即使[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代表一个目录。

对于以下各项，dir() 返回[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) `"~/examples/191697"`。

```
    QFileInfo fileInfo1("~/examples/191697/.");
    QFileInfo fileInfo2("~/examples/191697/..");
    QFileInfo fileInfo3("~/examples/191697/main.cpp");
```

对于以下各项，dir() 返回[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) `"."`。

```
    QFileInfo fileInfo4(".");
    QFileInfo fileInfo5("..");
    QFileInfo fileInfo6("main.cpp");
```

**也可以看看**[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（）， 和[absoluteDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteDir)()。

### bool QFileInfo::exists() const

返回`true`文件是否存在；否则返回`false`.

**注意：**如果文件是指向不存在文件的符号链接，则返回 false。

### `[static]`bool QFileInfo::exists(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

返回`true`如果*file*存在；否则返回`false`.

**注：**如果*file*是指向不存在文件的符号链接，返回 false。

**注意：**使用此函数比用于`QFileInfo(file).exists()`文件系统访问要快。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::fileName() const

返回文件的名称，不包括路径。

例子：

```
QFileInfo fi("/tmp/archive.tar.gz");
QString name = fi.fileName();                // name = "archive.tar.gz"
```

请注意，如果这[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)给对象一个以斜线结尾的路径，文件名被认为是空的。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)（）， 和[suffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#suffix)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::filePath() const

返回文件名，包括路径（可以是绝对路径或相对路径）。

**也可以看看**[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)(),[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)（）， 和[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::fileTime([QFile::FileTime](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FileTime-enum) *time*) const

返回指定的文件时间*time*。

如果无法确定时间，则返回无效的日期时间。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该函数重载[QFileInfo::fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime-1)(QFile::FileTime, const QTimeZone &)，并返回与 相同的值`fileTime(time, QTimeZone::LocalTime)`。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)(),[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)(),[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)（）， 和[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)()。

### `[since 6.6]`[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::fileTime([QFile::FileTime](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FileTime-enum) *time*, const [QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*tz*) const

返回指定的文件时间*time*。

返回的时间位于指定的时区*tz*。例如，您可以使用[QTimeZone::LocalTime](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)或者[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)分别获取本地时区或 UTC 时间。由于本机文件系统 API 通常使用 UTC，因此使用[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)通常更快，因为它不需要任何转换。

如果无法确定时间，则返回无效的日期时间。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime-1)（常量 QTimeZone &），[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified-1)（常量 QTimeZone &），[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead-1)（常量 QTimeZone &），[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime-1)（常量 QTimeZone &），以及[QDateTime::isValid](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isValid)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemAbsoluteFilePath() const

退货[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemAbsolutePath() const

退货[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemCanonicalFilePath() const

退货[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemCanonicalPath() const

退货[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemFilePath() const

退货[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)()。

### `[since 6.2]`std::filesystem::path QFileInfo::filesystemJunctionTarget() const

退货[junctionTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#junctionTarget)（） 作为一个`std::filesystem::path`。

该功能是在 Qt 6.2 中引入的。

**也可以看看**[junctionTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#junctionTarget)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemPath() const

退货[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[path](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)()。

### `[since 6.6]`std::filesystem::path QFileInfo::filesystemReadSymLink() const

退货[readSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readSymLink)（） 作为一个`std::filesystem::path`。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[readSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#readSymLink)()。

### `[since 6.0]`std::filesystem::path QFileInfo::filesystemSymLinkTarget() const

退货[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)（） 作为一个`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::group() const

返回文件的组。在 Windows 上，在文件没有组的系统上，或者如果发生错误，则会返回空字符串。

该函数在 Unix 下可能会很耗时（以毫秒为单位）。

如果文件是符号链接，则此函数返回目标的所属组（而不是符号链接）。

**也可以看看**[groupId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupId)(),[owner](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#owner)（）， 和[ownerId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ownerId)()。

### [uint](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uint-typedef) QFileInfo::groupId() const

返回文件所属组的 ID。

在 Windows 和文件没有组的系统上，此函数始终返回 (uint) -2。

如果文件是符号链接，则此函数返回拥有目标的组的 ID（而不是符号链接）。

**也可以看看**[group](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)(),[owner](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#owner)（）， 和[ownerId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ownerId)()。

### bool QFileInfo::isAbsolute() const

`true`如果文件路径是绝对路径则返回，否则返回`false`（即路径是相对路径）。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### `[since 6.4]`bool QFileInfo::isAlias() const

`true`如果该对象指向别名则返回；否则返回`false`.

别名仅存在于 macOS 上。它们被视为常规文件，因此打开别名将打开文件本身。为了打开别名引用的文件或目录[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)()。

**注意：**即使别名指向不存在的文件，isAlias() 也会返回 true。

该功能是在 Qt 6.4 中引入的。

**也可以看看**[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)（）， 和[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)()。

### bool QFileInfo::isBundle() const

返回`true`此对象是否指向捆绑包或指向 macOS 和 iOS 上的捆绑包的符号链接；否则返回`false`.

如果文件是符号链接，并且目标是包（不是符号链接），则此函数返回 true。

**也可以看看**[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)（）， 和[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)()。

### bool QFileInfo::isDir() const

返回`true`此对象是否指向目录或指向目录的符号链接。`false`如果对象指向的内容不是目录（例如文件）或不存在，则返回。

如果文件是符号链接，并且目标是目录（不是符号链接），则此函数返回 true。

**也可以看看**[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)（）， 和[isBundle](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBundle)()。

### bool QFileInfo::isExecutable() const

返回`true`文件是否可执行；否则返回`false`.

如果文件是符号链接，并且目标可执行（不是符号链接），则此函数返回 true。

**也可以看看**[isReadable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[isWritable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWritable)（）， 和[permission](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permission)()。

### bool QFileInfo::isFile() const

返回`true`此对象是否指向文件或指向文件的符号链接。`false`如果对象指向非文件（例如目录）或不存在的内容，则返回。

如果文件是符号链接，并且目标是常规文件（不是符号链接），则此函数返回 true。

**也可以看看**[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)（）， 和[isBundle](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBundle)()。

### bool QFileInfo::isHidden() const

`true`如果这是一个“隐藏”文件则返回；否则返回`false`.

**注意：**此函数返回`true`特殊条目“.”。和 Unix 上的“..”，尽管[QDir::entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)如图所示威胁他们。请注意，由于此函数检查文件名，因此在 Unix 上，如果该文件是符号链接，它将检查符号链接的名称，而不是目标的名称。

在 Windows 上，`true`如果目标文件被隐藏（不是符号链接），则该函数返回。

### bool QFileInfo::isJunction() const

返回`true`对象是否指向结点；否则返回`false`.

连接仅存在于 Windows 的 NTFS 文件系统上，并且通常由命令创建`mklink`。它们可以被认为是目录的符号链接，并且只能为本地卷上的绝对路径创建。

### bool QFileInfo::isNativePath() const

返回`true`文件路径是否可以直接用于本机 API。返回`false`该文件是否受 Qt 内的虚拟文件系统支持，例如[the Qt Resource System](https://doc-qt-io.translate.goog/qt-6/resources.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**注意：**本机路径可能仍需要路径分隔符和字符编码的转换，具体取决于本机 API 的平台和输入要求。

**也可以看看**[QDir::toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)(),[QFile::encodeName](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#encodeName)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)（）， 和[canonicalFilePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalFilePath)()。

### bool QFileInfo::isReadable() const

返回`true`用户是否可以读取该文件；否则返回`false`.

如果文件是符号链接，并且目标可读（不是符号链接），则此函数返回 true。

**注意：**如果[NTFS permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ntfs-permissions)检查尚未启用，Windows 上的结果仅反映文件是否存在。

**也可以看看**[isWritable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWritable)(),[isExecutable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExecutable)（）， 和[permission](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permission)()。

### bool QFileInfo::isRelative() const

`true`如果文件路径是相对路径则返回，否则返回`false`（即路径是绝对路径）。（例如，在 Unix 下，如果路径以“/”开头，则路径是绝对路径）。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)()。

### bool QFileInfo::isRoot() const

`true`如果对象指向目录或指向目录的符号链接，并且该目录是根目录，则返回；否则返回`false`.

### bool QFileInfo::isShortcut() const

`true`如果该对象指向快捷方式则返回；否则返回`false`.

快捷方式仅存在于 Windows 上，通常是`.lnk`文件。例如，`*.lnk`在 Windows 上快捷方式（文件）将返回 true，但在 Unix（包括 macOS 和 iOS）上将返回 false。

快捷方式 (.lnk) 文件被视为常规文件。打开这些将打开`.lnk`文件本身。为了打开快捷方式引用的文件，它必须使用[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)() 上的快捷方式。

**注意：**即使快捷方式（损坏的快捷方式）指向不存在的文件，isShortcut() 也会返回 true。

**也可以看看**[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)(),[isSymbolicLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymbolicLink)（）， 和[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)()。

### bool QFileInfo::isSymLink() const

返回`true`此对象是否指向符号链接、快捷方式或别名；否则返回`false`.

`ln -s`符号链接存在于 Unix（包括 macOS 和 iOS）和 Windows 上，通常分别由或命令创建`mklink`。打开符号链接有效地打开[link's target](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)。

此外，对于`*.lnk`Windows 上的快捷方式（文件）和 macOS 上的别名，将返回 true。此行为已被弃用，并且可能会在 Qt 的未来版本中发生变化。打开快捷方式或别名将打开该`.lnk`或别名文件本身。

例子：

```
QFileInfo info(fileName);
if (info.isSymLink())
    fileName = info.symLinkTarget();
```

**注意：**如果符号链接指向不存在的文件，[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)() 返回假。

**也可以看看**[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)（）， 和[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)()。

### bool QFileInfo::isSymbolicLink() const

`true`如果该对象指向符号链接则返回；否则返回`false`.

符号链接存在于 Unix（包括 macOS 和 iOS）和 Windows（NTFS 符号链接）上，通常分别由`ln -s`或`mklink`命令创建。

Unix 透明地处理符号链接。打开符号链接有效地打开[link's target](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)。

相比之下[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)`*.lnk`()， Windows 上的快捷方式（文件）和 macOS 上的别名将返回 false 。使用[QFileInfo::isShortcut](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isShortcut)（） 和[QFileInfo::isAlias](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAlias)（） 反而。

**注意：**如果符号链接指向不存在的文件，[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)() 返回假。

**也可以看看**[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)(),[isShortcut](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isShortcut)（）， 和[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)()。

### bool QFileInfo::isWritable() const

返回`true`用户是否可以写入文件；否则返回`false`.

如果文件是符号链接，并且目标可写（不是符号链接），则此函数返回 true。

**注意：**如果[NTFS permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ntfs-permissions)检查尚未启用，Windows 上的结果将仅反映文件是否被标记为只读。

**也可以看看**[isReadable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[isExecutable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExecutable)（）， 和[permission](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permission)()。

### `[since 6.2]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::junctionTarget() const

将 NTFS 连接解析为其引用的路径。

返回 NTFS 联结点指向的目录的绝对路径，如果对象不是 NTFS 联结点，则返回空字符串。

无法保证 NTFS 连接命名的目录确实存在。

该功能是在 Qt 6.2 中引入的。

**也可以看看**[isJunction](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isJunction)(),[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)(),[isSymbolicLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymbolicLink)（）， 和[isShortcut](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isShortcut)()。

### [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::lastModified() const

返回文件上次修改的日期和时间。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该函数重载[QFileInfo::lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified-1)(const QTimeZone &)，并返回与 相同的值`lastModified(QTimeZone::LocalTime)`。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)(),[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)(),[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)（）， 和[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)()。

### `[since 6.6]`[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::lastModified(const [QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*tz*) const

返回文件上次修改的日期和时间。

返回的时间位于指定的时区*tz*。例如，您可以使用[QTimeZone::LocalTime](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)或者[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)分别获取本地时区或 UTC 时间。由于本机文件系统 API 通常使用 UTC，因此使用[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)通常更快，因为它不需要任何转换。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime-1)（常量 QTimeZone &），[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead-1)（常量 QTimeZone &），[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime-1)（常量 QTimeZone &），以及[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime-1)（QFile::FileTime，const QTimeZone &）。

### [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::lastRead() const

返回上次读取（访问）文件的日期和时间。

在无法获得此信息的平台上，返回的时间与[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)()。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该函数重载[QFileInfo::lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead-1)(const QTimeZone &)，并返回与 相同的值`lastRead(QTimeZone::LocalTime)`。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)(),[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)(),[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime)（）， 和[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)()。

### `[since 6.6]`[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::lastRead(const [QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*tz*) const

返回上次读取（访问）文件的日期和时间。

返回的时间位于指定的时区*tz*。例如，您可以使用[QTimeZone::LocalTime](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)或者[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)分别获取本地时区或 UTC 时间。由于本机文件系统 API 通常使用 UTC，因此使用[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)通常更快，因为它不需要任何转换。

在无法获得此信息的平台上，返回的时间与[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)()。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime-1)（常量 QTimeZone &），[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified-1)（常量 QTimeZone &），[metadataChangeTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#metadataChangeTime-1)（常量 QTimeZone &），以及[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime-1)（QFile::FileTime，const QTimeZone &）。

### bool QFileInfo::makeAbsolute()

如果文件路径尚未采用绝对路径形式，则将其转换为绝对路径。返回`true`表示路径已转换；否则返回`false`表明该路径已经是绝对路径。

**也可以看看**[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)（） 和[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### [QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::metadataChangeTime() const

返回文件元数据上次更改的日期和时间（当地时间）。

元数据更改发生在文件首次创建时，但每当用户写入或设置 inode 信息（例如，更改文件权限）时也会发生。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该函数重载 QFileInfo::metadataChangeTime(const[QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)&tz)，并返回与 相同的结果`metadataChangeTime(QTimeZone::LocalTime)`。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime)(),[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified)(),[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead)（）， 和[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime)()。

### `[since 6.6]`[QDateTime](https://doc-qt-io.translate.goog/qt-6/qdatetime.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::metadataChangeTime(const [QTimeZone](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*tz*) const

返回文件元数据上次更改的日期和时间。元数据更改发生在文件首次创建时，但每当用户写入或设置 inode 信息（例如，更改文件权限）时也会发生。

返回的时间位于指定的时区*tz*。例如，您可以使用[QTimeZone::LocalTime](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)或者[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)分别获取本地时区或 UTC 时间。由于本机文件系统 API 通常使用 UTC，因此使用[QTimeZone::UTC](https://doc-qt-io.translate.goog/qt-6/qtimezone.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Initialization-enum)通常更快，因为它不需要任何转换。

如果文件是符号链接，则返回目标文件的时间（而不是符号链接）。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[birthTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#birthTime-1)（常量 QTimeZone &），[lastModified](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastModified-1)（常量 QTimeZone &），[lastRead](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#lastRead-1)（常量 QTimeZone &），以及[fileTime](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileTime-1)（QFile::FileTime 时间，const QTimeZone &）。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::owner() const

返回文件的所有者。在文件没有所有者的系统上，或者如果发生错误，则会返回空字符串。

该函数在 Unix 下可能会很耗时（以毫秒为单位）。在 Windows 上，它将返回一个空字符串，除非[NTFS permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ntfs-permissions)检查已启用。

如果文件是符号链接，则此函数返回目标的所有者（而不是符号链接）。

**也可以看看**[ownerId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ownerId)(),[group](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)（）， 和[groupId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupId)()。

### [uint](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#uint-typedef) QFileInfo::ownerId() const

返回文件所有者的 ID。

在 Windows 和文件没有所有者的系统上，此函数返回 ((uint) -2)。

如果文件是符号链接，则此函数返回目标所有者的 ID（而不是符号链接）。

**也可以看看**[owner](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#owner)(),[group](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)（）， 和[groupId](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#groupId)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::path() const

返回文件的路径。这不包括文件名。

请注意，如果这[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)给对象一个以斜杠结尾的路径，文件名被认为是空的，这个函数将返回整个路径。

**也可以看看**[filePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[absolutePath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)(),[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)(),[dir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dir)(),[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)（）， 和[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### bool QFileInfo::permission([QFile::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) *permissions*) const

测试文件权限。这*permissions*参数可以是 QFile::Permissions 类型的多个标志，或组合在一起以检查权限组合。

在文件没有权限的系统上，此函数始终返回`true`。

**注意：**如果在 Windows 上，结果可能不准确[NTFS permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ntfs-permissions)检查尚未启用。

例子：

```
QFileInfo fi("/tmp/archive.tar.gz");
if (fi.permission(QFile::WriteUser | QFile::ReadGroup))
    qWarning("I can change the file; my group can read the file");
if (fi.permission(QFile::WriteGroup | QFile::WriteOther))
    qWarning("The group or others can change the file");
```

如果文件是符号链接，则此函数检查目标（而不是符号链接）的权限。

**也可以看看**[isReadable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[isWritable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWritable)（）， 和[isExecutable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isExecutable)()。

### [QFile::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) QFileInfo::permissions() const

返回文件的 QFile::Permissions 的完整 OR 组合。

**注意：**如果在 Windows 上，结果可能不准确[NTFS permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ntfs-permissions)检查尚未启用。

如果文件是符号链接，则此函数返回目标（而不是符号链接）的权限。

### `[since 6.6]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::readSymLink() const

读取符号链接引用的路径。

返回符号链接引用的原始路径，而不解析相对于包含符号链接的目录的相对路径。如果符号链接实际上引用了绝对路径，则返回的字符串将只是绝对路径。如果对象不是符号链接，则返回空字符串。

该功能是在 Qt 6.6 中引入的。

**也可以看看**[symLinkTarget](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#symLinkTarget)(),[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)（）， 和[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)()。

### void QFileInfo::refresh()

刷新有关文件的信息，即下次获取缓存属性时从文件系统读取信息。

### void QFileInfo::setCaching(bool *enable*)

如果*enable*为 true，启用文件信息缓存。如果*enable*是 false 缓存被禁用。

当启用缓存时，[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)第一次需要时从文件系统读取文件信息，但通常不会稍后读取。

默认情况下启用缓存。

**也可以看看**[refresh](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)（） 和[caching](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#caching)()。

### void QFileInfo::setFile(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

设置文件[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供有关以下信息*file*。

这*file*还可以包含绝对或相对文件路径。绝对路径以目录分隔符（例如，Unix 下的“/”）或驱动器规范（Windows 下）开头。相对文件名以目录名或文件名开头，并指定相对于当前目录的路径。

例子：

```
QFileInfo info("/usr/bin/env");

QString path = info.absolutePath(); // path = /usr/bin
QString base = info.baseName(); // base = env

info.setFile("/etc/hosts");

path = info.absolutePath(); // path = /etc
base = info.baseName(); // base = hosts
```

**也可以看看**[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)(),[QDir::setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)（）， 和[QDir::isRelativePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelativePath)()。

### void QFileInfo::setFile(const [QFileDevice](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

这是一个过载功能。

设置文件[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供有关以下信息*file*。

如果*file*包括相对路径，[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)也会有一个相对路径。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### void QFileInfo::setFile(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dir*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*file*)

这是一个过载功能。

设置文件[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供有关以下信息*file*在目录中*dir*。

如果*file*包括相对路径，[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)也会有一个相对路径。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)()。

### `[since 6.0]`void QFileInfo::setFile(const std::filesystem::path &*file*)

设置文件[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供有关以下信息*file*。

这个函数是在Qt 6.0中引入的。

### [qint64](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qint64-typedef) QFileInfo::size() const

返回文件大小（以字节为单位）。如果文件不存在或无法获取，则返回 0。

如果文件是符号链接，则返回目标文件的大小（而不是符号链接）。

**也可以看看**[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)()。

### `[since 6.0]`void QFileInfo::stat()

从文件系统读取所有属性。

当在工作线程中收集有关文件系统的信息，然后以缓存的形式传递到 UI 时，这非常有用[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

这个函数是在Qt 6.0中引入的。

**也可以看看**[setCaching](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCaching)（） 和[refresh](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::suffix() const

返回文件的后缀（扩展名）。

后缀由文件中最后一个“.”之后（但不包括）的所有字符组成。

例子：

```
QFileInfo fi("/tmp/archive.tar.gz");
QString ext = fi.suffix();  // ext = "gz"
```

文件的后缀在所有平台上均等计算，与文件命名约定无关（例如，Unix 上的“.bashrc”具有空基本名称，后缀为“bashrc”）。

**也可以看看**[fileName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fileName)(),[completeSuffix](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeSuffix)(),[baseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#baseName)（）， 和[completeBaseName](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#completeBaseName)()。

### `[noexcept]`void QFileInfo::swap(QFileInfo &*other*)

交换此文件信息*other*。这个功能非常快并且永远不会失败。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QFileInfo::symLinkTarget() const

返回符号链接指向的文件或目录的绝对路径，如果对象不是符号链接，则返回空字符串。

该名称可能不代表现有文件；它只是一个字符串。[QFileInfo::exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)()`true`如果符号链接指向现有文件则返回。

**也可以看看**[exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)(),[isSymLink](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSymLink)(),[isDir](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isDir)（）， 和[isFile](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isFile)()。

### bool QFileInfo::operator!=(const QFileInfo &*fileinfo*) const

`true`如果这样则返回[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象引用与指定的文件不同的文件*fileinfo*; 否则返回`false`.

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### QFileInfo &QFileInfo::operator=(const QFileInfo &*fileinfo*)

复制给定的*fileinfo*并将其分配给此[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[noexcept]`QFileInfo &QFileInfo::operator=(QFileInfo &&*other*)

移动分配*other*对此[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

### bool QFileInfo::operator==(const QFileInfo &*fileinfo*) const

`true`如果这样则返回[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)object 指的是与以下位置相同的文件*fileinfo*; 否则返回`false`.

注意比较两个空的结果[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不包含文件引用（不存在或为空的文件路径）的对象是未定义的。

**警告：**这不会比较指向同一文件的两个不同符号链接。

**警告：**在 Windows 上引用同一文件的长文件名和短文件名将被视为引用不同的文件。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

## 相关非会员

### QFileInfoList

同义词[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)>。

## 宏文档

### `[since 6.0]`QT_IMPLICIT_QFILEINFO_CONSTRUCTION

定义这个宏使得大多数[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数是隐式的而不是显式的。自建设以来[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象是昂贵的，人们应该避免意外创建它们，特别是如果存在更便宜的替代品。例如：

```
QDirIterator it(dir);
while (it.hasNext()) {
    // Implicit conversion from QString (returned by it.next()):
    // may create unnecessary data structures and cause additional
    // accesses to the file system. Unless this macro is defined,
    // this line does not compile.

    QFileInfo fi = it.next();

    ~~~
}
```

相反，请使用正确的 API：

```
QDirIterator it(dir);
while (it.hasNext()) {
    // Extract the QFileInfo from the iterator directly:
    QFileInfo fi = it.nextFileInfo();

    ~~~
}
```

施工自[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，等等总是可以通过使用直接初始化而不是复制初始化来实现：

```
QFileInfo fi1 = some_string; // Does not compile unless this macro is defined
QFileInfo fi2(some_string);  // OK
QFileInfo fi3{some_string};  // Possibly better, avoids the risk of the Most Vexing Parse
auto fi4 = QFileInfo(some_string); // OK
```

提供此宏是出于兼容性原因。不建议在新代码中使用它。

该宏是在 Qt 6.0 中引入的。