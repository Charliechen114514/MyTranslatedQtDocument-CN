#  QDir Class

QDir 类提供对目录结构及其内容的访问。[更多的...](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include < QDir>                                             |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Core) target_link_libraries(mytarget PRIVATE Qt6::Core) |
| qmake:  | QT += core                                                   |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qdir-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QDir 是[输入/输出、网络](https://doc-qt-io.translate.goog/qt-6/io.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

**注意：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| enum  | **[Filter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum)** { Dirs, AllDirs, Files, Drives, NoSymLinks, …, CaseSensitive } |
| ----- | ------------------------------------------------------------ |
| flags | **[Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum)** |
| enum  | **[SortFlag](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)** { Name, Time, Size, Type, Unsorted, …, LocaleAware } |
| flags | **[SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)** |

## 公共职能

|                       | **[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir-1)**(const QString &*path* = QString()) |
| --------------------- | ------------------------------------------------------------ |
|                       | **[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir-2)**(const QString &*path*, const QString &*nameFilter*, QDir::SortFlags *sort* = SortFlags(Name \| IgnoreCase), QDir::Filters *filters* = AllEntries) |
|                       | **[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir-3)**(const std::filesystem::path &*path*) |
|                       | **[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir-4)**(const std::filesystem::path &*path*, const QString &*nameFilter*, QDir::SortFlags *sort* = SortFlags(Name \| IgnoreCase), QDir::Filters *filters* = AllEntries) |
|                       | **[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir)**(const QDir &*dir*) |
|                       | **[~QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QDir)**() |
| QString               | **[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)**(const QString &*fileName*) const |
| QString               | **[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)**() const |
| QString               | **[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)**() const |
| bool                  | **[cd](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cd)**(const QString &*dirName*) |
| bool                  | **[cdUp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cdUp)**() |
| qsizetype             | **[count](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)**() const |
| QString               | **[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)**() const |
| QFileInfoList         | **[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)**(const QStringList &*nameFilters*, QDir::Filters *filters* = NoFilter, QDir::SortFlags *sort* = NoSort) const |
| QFileInfoList         | **[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList-1)**(QDir::Filters *filters* = NoFilter, QDir::SortFlags *sort* = NoSort) const |
| QStringList           | **[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)**(const QStringList &*nameFilters*, QDir::Filters *filters* = NoFilter, QDir::SortFlags *sort* = NoSort) const |
| QStringList           | **[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList-1)**(QDir::Filters *filters* = NoFilter, QDir::SortFlags *sort* = NoSort) const |
| bool                  | **[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)**(const QString &*name*) const |
| bool                  | **[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)**() const |
| QString               | **[filePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)**(const QString &*fileName*) const |
| std::filesystem::path | **[filesystemAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemAbsolutePath)**() const |
| std::filesystem::path | **[filesystemCanonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemCanonicalPath)**() const |
| std::filesystem::path | **[filesystemPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filesystemPath)**() const |
| QDir::Filters         | **[filter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filter)**() const |
| bool                  | **[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)**() const |
| bool                  | **[isEmpty](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEmpty)**(QDir::Filters *filters* = Filters(AllEntries \| NoDotAndDotDot)) const |
| bool                  | **[isReadable](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)**() const |
| bool                  | **[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)**() const |
| bool                  | **[isRoot](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRoot)**() const |
| bool                  | **[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)**() |
| bool                  | **[mkdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mkdir)**(const QString &*dirName*, QFile::Permissions *permissions*) const |
| bool                  | **[mkdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mkdir-1)**(const QString &*dirName*) const |
| bool                  | **[mkpath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mkpath)**(const QString &*dirPath*) const |
| QStringList           | **[nameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nameFilters)**() const |
| QString               | **[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)**() const |
| void                  | **[refresh](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)**() const |
| QString               | **[relativeFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#relativeFilePath)**(const QString &*fileName*) const |
| bool                  | **[remove](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)**(const QString &*fileName*) |
| bool                  | **[removeRecursively](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeRecursively)**() |
| bool                  | **[rename](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename)**(const QString &*oldName*, const QString &*newName*) |
| bool                  | **[rmdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rmdir)**(const QString &*dirName*) const |
| bool                  | **[rmpath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rmpath)**(const QString &*dirPath*) const |
| void                  | **[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)**(QDir::Filters *filters*) |
| void                  | **[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)**(const QStringList &*nameFilters*) |
| void                  | **[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)**(const QString &*path*) |
| void                  | **[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath-1)**(const std::filesystem::path &*path*) |
| void                  | **[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)**(QDir::SortFlags *sort*) |
| QDir::SortFlags       | **[sorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)**() const |
| void                  | **[swap](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QDir &*other*) |
| bool                  | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QDir &*dir*) const |
| QDir &                | **[operator=](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QDir &*dir*) |
| QDir &                | **[operator=](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(QDir &&*other*) |
| bool                  | **[operator==](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QDir &*dir*) const |
| QString               | **[operator[\]](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)**(qsizetype *pos*) const |

## 静态公共成员

| void          | **[addSearchPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSearchPath)**(const QString &*prefix*, const QString &*path*) |
| ------------- | ------------------------------------------------------------ |
| void          | **[addSearchPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSearchPath-1)**(const QString &*prefix*, const std::filesystem::path &*path*) |
| QString       | **[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)**(const QString &*path*) |
| QDir          | **[current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)**() |
| QString       | **[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)**() |
| QFileInfoList | **[drives](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drives)**() |
| QString       | **[fromNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromNativeSeparators)**(const QString &*pathName*) |
| QDir          | **[home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)**() |
| QString       | **[homePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#homePath)**() |
| bool          | **[isAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolutePath)**(const QString &*path*) |
| bool          | **[isRelativePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelativePath)**(const QString &*path*) |
| QChar         | **[listSeparator](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#listSeparator)**() |
| bool          | **[match](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#match)**(const QString &*filter*, const QString &*fileName*) |
| bool          | **[match](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#match-1)**(const QStringList &*filters*, const QString &*fileName*) |
| QDir          | **[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)**() |
| QString       | **[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)**() |
| QStringList   | **[searchPaths](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths)**(const QString &*prefix*) |
| QChar         | **[separator](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#separator)**() |
| bool          | **[setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)**(const QString &*path*) |
| void          | **[setSearchPaths](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSearchPaths)**(const QString &*prefix*, const QStringList &*searchPaths*) |
| QDir          | **[temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)**() |
| QString       | **[tempPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tempPath)**() |
| QString       | **[toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)**(const QString &*pathName*) |

## 详细说明

QDir 用于操作路径名、访问有关路径和文件的信息以及操作底层文件系统。它还可以用于访问 Qt[resource system](https://doc-qt-io.translate.goog/qt-6/resources.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

Qt 使用“/”作为通用目录分隔符，就像“/”在 URL 中用作路径分隔符一样。如果您始终使用“/”作为目录分隔符，Qt 将转换您的路径以符合底层操作系统。

QDir 可以使用相对路径或绝对路径指向文件。绝对路径以目录分隔符开头（Windows 下可以在前面加上驱动器规范）。相对文件名以目录名或文件名开头，并指定相对于当前目录的路径。

绝对路径示例：

```
QDir("/home/user/Documents")
QDir("C:/Users")
```

在 Windows 上，上面的第二个示例将被转换为`C:\Users`用于访问文件时。

相对路径示例：

```
QDir("images/landscape.png")
```

您可以使用[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（） 或者[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)() 函数检查 QDir 是否使用相对或绝对文件路径。称呼[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)() 将相对 QDir 转换为绝对 QDir。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### 导航和目录操作

可以使用以下命令获取目录的路径[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)() 函数，并设置一个新路径[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)（） 功能。通过调用可以找到目录的绝对路径[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

使用以下命令可以找到目录的名称[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)（） 功能。这通常返回绝对路径中指定目录位置的最后一个元素。但是，它也可以返回“.”。如果 QDir 代表当前目录。

```
QDir("Documents/Letters/Applications").dirName() // "Applications"
QDir().dirName()                                 // "."
```

也可以使用以下命令更改目录的路径[cd](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cd)（） 和[cdUp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cdUp)() 函数，这两个函数的操作都类似于熟悉的 shell 命令。什么时候[cd](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cd)() 使用现有目录的名称调用，QDir 对象会更改目录，以便它代表该目录。这[cdUp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cdUp)() 函数更改 QDir 对象的目录，使其引用其父目录；即 cd("..") 相当于[cdUp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cdUp)()。

可以使用以下命令创建目录[mkdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mkdir)()，重命名为[rename](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename)()，并删除[rmdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rmdir)()。

您可以使用以下命令测试具有给定名称的目录是否存在[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()，并且可以使用以下命令测试目录的属性[isReadable](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（）， 和[isRoot](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRoot)()。

这[refresh](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#refresh)() 函数从磁盘重新读取目录的数据。

### 文件和目录内容

目录包含许多条目，代表文件、目录和符号链接。目录中的条目数由以下命令返回[count](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)()。可以使用以下命令获取目录中所有条目名称的字符串列表[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)()。如果您需要有关每个条目的信息，请使用[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)() 获取列表[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象。

目录中的文件和目录的路径可以使用构造[filePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)（） 和[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)()。这[filePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)()函数返回相对于QDir对象路径的指定文件或目录的路径；[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)() 返回指定文件或目录的绝对路径。这些函数都不检查文件或目录是否存在；他们只构建路径。

```
QDir directory("Documents/Letters");
QString path = directory.filePath("contents.txt");
QString absolutePath = directory.absoluteFilePath("contents.txt");
```

可以使用以下命令删除文件[remove](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#remove)（） 功能。目录不能像文件一样被删除；使用[rmdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rmdir)() 来删除它们。

可以减少返回的条目数[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)() 通过将过滤器应用于 QDir 对象。您可以应用名称过滤器来指定文件名需要匹配的带有通配符的模式、选择条目属性并可以区分文件和目录的属性过滤器以及排序顺序。

名称过滤器是传递给的字符串列表[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)()。属性过滤器由 Filters 按位或组合组成，这些在调用时指定[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()。排序顺序是使用指定的[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)() 与按位或组合[SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)。

您可以使用以下命令测试文件名是否与过滤器匹配[match](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#match)（） 功能。

调用时也可以指定过滤器和排序顺序标志[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)() 以覆盖先前定义的行为。

### 当前目录和其他特殊路径

通过许多返回 QDir 对象的静态函数提供对某些常见目录的访问。对于返回字符串的这些也有相应的函数：

|                            目录号                            | [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |       返回值       |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------: |
| [current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)() | [currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)() | 应用程序的工作目录 |
| [home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)() | [homePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#homePath)() |    用户的主目录    |
| [root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)() | [rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)() |       根目录       |
| [temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)() | [tempPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tempPath)() |    系统临时目录    |

这[setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)()静态函数还可以用来设置应用程序的工作目录。

如果您想查找包含应用程序可执行文件的目录，请参阅[QCoreApplication::applicationDirPath](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#applicationDirPath)()。

这[drives](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drives)() 静态函数为每个包含文件系统的设备提供根目录列表。在 Unix 系统上，这会返回一个包含单个根目录“/”的列表；在 Windows 上，该列表通常包含`C:/`，还可能包含其他驱动器号，例如`D:/`，具体取决于用户系统的配置。

### 路径操作和字符串

包含“.”的路径 引用路径中该点的当前目录的元素、引用父目录的“..”元素以及符号链接可以使用以下命令简化为规范形式：[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)（） 功能。

路径也可以通过使用来简化[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)() 删除多余的“/”和“..”元素。

有时需要能够以用户平台的本机表示形式显示路径。静态的[toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)() 函数返回指定路径的副本，其中每个目录分隔符被底层操作系统的适当分隔符替换。

### 例子

检查目录是否存在：

```
QDir dir("example");
if (!dir.exists())
    qWarning("Cannot find the example directory");
```

（我们还可以使用静态便利函数之一[QFileInfo::exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)（） 或者[QFile::exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)().)

遍历目录并读取文件：

```
QDir dir = QDir::root();                 // "/"
if (!dir.cd("tmp")) {                    // "/tmp"
    qWarning("Cannot find the \"/tmp\" directory");
} else {
    QFile file(dir.filePath("ex1.txt")); // "/tmp/ex1.txt"
    if (!file.open(QIODevice::ReadWrite))
        qWarning("Cannot create the file %s", file.name());
}
```

一个列出当前目录中所有文件（不包括符号链接）的程序，按大小排序，最小的在前：

```
#include < QDir>
#include < iostream>

int main(int argc, char *argv[])
{
    QCoreApplication app(argc, argv);
    QDir dir;
    dir.setFilter(QDir::Files | QDir::Hidden | QDir::NoSymLinks);
    dir.setSorting(QDir::Size | QDir::Reversed);

    QFileInfoList list = dir.entryInfoList();
    std::cout < <  "     Bytes Filename" < <  std::endl;
    for (int i = 0; i <  list.size(); ++i) {
        QFileInfo fileInfo = list.at(i);
        std::cout < <  qPrintable(QString("%1 %2").arg(fileInfo.size(), 10)
                                                .arg(fileInfo.fileName()));
        std::cout < <  std::endl;
    }
    return 0;
}
```

### 平台特定问题

在 Android 上，处理时存在一些限制[content URIs](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/guide/topics/providers/content-provider-basics%23ContentURIs):

- 通过提示用户可能需要访问权限[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它实现了[Android's native file picker](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage/shared/documents-files)。
- 旨在遵循[Scoped storage](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage%23scoped-storage)准则，例如使用应用程序特定目录而不是其他公共外部目录。有关详细信息，另请参阅[storage best practices](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/training/data-storage/use-cases)。
- 由于 Qt API 的设计（例如[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)），后面的 API 无法与 Android 完全集成[MediaStore](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/reference/android/provider/MediaStore)蜜蜂。

**也可以看看**[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFile](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QFileDialog](https://doc-qt-io.translate.goog/qt-6/qfiledialog.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QCoreApplication::applicationDirPath](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#applicationDirPath)（）， 和[Fetch More Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-itemviews-fetchmore-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QDir::过滤器 标志 QDir::过滤器

该枚举描述了可用的过滤选项[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 例如对于[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)()。过滤器值是通过使用按位 OR 运算符组合以下列表中的值来指定的：

| 持续的                 | 价值                    | 描述                                                         |
| ---------------------- | ----------------------- | ------------------------------------------------------------ |
| `QDir::Dirs`           | `0x001`                 | 列出与过滤器匹配的目录。                                     |
| `QDir::AllDirs`        | `0x400`                 | 列出所有目录；即不要将过滤器应用于目录名称。                 |
| `QDir::Files`          | `0x002`                 | 列出文件。                                                   |
| `QDir::Drives`         | `0x004`                 | 列出磁盘驱动器（在 Unix 下被忽略）。                         |
| `QDir::NoSymLinks`     | `0x008`                 | 不要列出符号链接（被不支持符号链接的操作系统忽略）。         |
| `QDir::NoDotAndDotDot` | `NoDot | NoDotDot`      | 不要列出特殊条目“.”。和 ”..”。                               |
| `QDir::NoDot`          | `0x2000`                | 不要列出特殊条目“.”。                                        |
| `QDir::NoDotDot`       | `0x4000`                | 不要列出特殊条目“..”。                                       |
| `QDir::AllEntries`     | `Dirs | Files | Drives` | 列出目录、文件、驱动器和符号链接（除非您指定系统，否则不会列出损坏的符号链接）。 |
| `QDir::Readable`       | `0x010`                 | 列出应用程序具有读取访问权限的文件。Readable 值需要与 Dirs 或 Files 结合使用。 |
| `QDir::Writable`       | `0x020`                 | 列出应用程序具有写访问权限的文件。Writable 值需要与 Dirs 或 Files 结合使用。 |
| `QDir::Executable`     | `0x040`                 | 列出应用程序具有执行访问权限的文件。Executable 值需要与 Dirs 或 Files 组合。 |
| `QDir::Modified`       | `0x080`                 | 仅列出已修改的文件（在 Unix 上忽略）。                       |
| `QDir::Hidden`         | `0x100`                 | 列出隐藏文件（在 Unix 上，文件以“.”开头）。                  |
| `QDir::System`         | `0x200`                 | 列出系统文件（在 Unix 上，包括 FIFO、套接字和设备文件；在 Windows 上，`.lnk`包括文件） |
| `QDir::CaseSensitive`  | `0x800`                 | 过滤器应区分大小写。                                         |

使用 Filter 枚举值来过滤文件和目录列表的函数将包含文件和目录的符号链接，除非您设置 NoSymLinks 值。

默认构造的[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会根据文件的权限过滤掉文件，所以[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)() 将返回所有可读、可写、可执行或三者任意组合的文件。这使得默认值易于编写，同时也很有用。

例如，设置`Readable`、`Writable`和`Files`标志允许列出应用程序具有读访问权、写访问权或两者的所有文件。如果此组合中还包含 和 标志，则可以列出应用程序可以读取、写入或执行的所有驱动器、目录、所有文件以及此类文件/目录的符号链接`Dirs`。`Drives`

要检索目录的权限，请使用[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)() 函数获取关联[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象，然后使用[QFileInfo::permissions](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#permissions)() 获取每个文件的权限和所有权。

Filters 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < Filter> 的类型定义。它存储过滤器值的 OR 组合。

### 枚举 QDir:: SortFlag 标志 QDir:: SortFlags

该枚举描述了可用的排序选项[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，例如对于[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)()。排序值通过对以下列表中的值进行“或”运算来指定：

| 持续的              | 价值   | 描述                                 |
| ------------------- | ------ | ------------------------------------ |
| `QDir::Name`        | `0x00` | 按名称分类。                         |
| `QDir::Time`        | `0x01` | 按时间（修改时间）排序。             |
| `QDir::Size`        | `0x02` | 按文件大小排序。                     |
| `QDir::Type`        | `0x80` | 按文件类型（扩展名）排序。           |
| `QDir::Unsorted`    | `0x03` | 不排序。                             |
| `QDir::NoSort`      | `-1`   | 默认情况下不排序。                   |
| `QDir::DirsFirst`   | `0x04` | 首先放置目录，然后放置文件。         |
| `QDir::DirsLast`    | `0x20` | 首先放置文件，然后放置目录。         |
| `QDir::Reversed`    | `0x08` | 反转排序顺序。                       |
| `QDir::IgnoreCase`  | `0x10` | 排序时不区分大小写。                 |
| `QDir::LocaleAware` | `0x40` | 使用当前区域设置对项目进行适当排序。 |

您只能指定前四个之一。

如果您同时指定 DirsFirst 和 Reversed，目录仍放在第一位，但顺序相反；文件将在目录之后列出，同样以相反的顺序。

SortFlags 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < SortFlag> 的类型定义。它存储 SortFlag 值的 OR 组合。

## 成员函数文档

### QDir::QDir(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path* = QString())

构造一个指向给定目录的 QDir*path*。如果路径为空，则使用程序的工作目录（“.”）。

**也可以看看**[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)()。

### QDir::QDir(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*nameFilter*, [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort* = SortFlags(Name | IgnoreCase), [QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = AllEntries)

构造一个带有路径的 QDir*path*，使用名称按名称过滤其条目*nameFilter*并通过属性使用*filters*。它还使用对名称进行排序*sort*。

默认*nameFilter*是一个空字符串，不排除任何内容；默认值*filters*是[AllEntries](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum)，这也不排除任何内容。默认*sort*是[Name](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)|[IgnoreCase](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)，即按名称排序，不区分大小写。

如果*path*是一个空字符串，QDir 使用“.” （当前目录）。如果*nameFilter*是一个空字符串，QDir 使用名称过滤器“*”（所有文件）。

**笔记：***path*不需要存在。

**也可以看看**[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)(),[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)(),[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)(),[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)（）， 和[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()。

### `[since 6.0]`QDir::QDir(const std::filesystem::path &*path*)

构造一个指向给定目录的 QDir*path*。如果路径为空，则使用程序的工作目录（“.”）。

这个函数是在Qt 6.0中引入的。

**也可以看看**[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)()。

### `[since 6.0]`QDir::QDir(const std::filesystem::path &*path*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*nameFilter*, [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort* = SortFlags(Name | IgnoreCase), [QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = AllEntries)

构造一个带有路径的 QDir*path*，使用名称按名称过滤其条目*nameFilter*并通过属性使用*filters*。它还使用对名称进行排序*sort*。

默认*nameFilter*是一个空字符串，不排除任何内容；默认值*filters*是[AllEntries](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum)，这也不排除任何内容。默认*sort*是[Name](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)|[IgnoreCase](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)，即按名称排序，不区分大小写。

如果*path*为空，QDir 使用“.” （当前目录）。如果*nameFilter*是一个空字符串，QDir 使用名称过滤器“*”（所有文件）。

**笔记：***path*不需要存在。

这个函数是在Qt 6.0中引入的。

**也可以看看**[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)(),[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)(),[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)(),[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)（）， 和[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()。

### QDir::QDir(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &*dir*)

构造一个 QDir 对象，它是目录 QDir 对象的副本*dir*。

**也可以看看**[operator=](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)()。

### `[noexcept]`QDir::~QDir()

摧毁了[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象释放其资源。这对文件系统中的底层目录没有影响。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::absoluteFilePath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*) const

返回目录中文件的绝对路径名。不*检查*文件是否确实存在于目录中；但看[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。冗余的多个分隔符或“.” 和“..”目录*fileName*没有被删除（参见[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)())。

**也可以看看**[relativeFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#relativeFilePath)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)（）， 和[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::absolutePath() const

返回绝对路径（以“/”或驱动器规范开头的路径），该路径可能包含符号链接，但绝不包含多余的“.”、“..”或多个分隔符。

**也可以看看**[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)(),[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)(),[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)(),[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)(),[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)（）， 和[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)()。

### `[static]`void QDir::addSearchPath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*prefix*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

添加*path*到搜索路径*prefix*。

**也可以看看**[setSearchPaths](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSearchPaths)()。

### `[static, since 6.0]`void QDir::addSearchPath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*prefix*, const std::filesystem::path &*path*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::canonicalPath() const

返回规范路径，即没有符号链接或冗余“.”的路径。或“..”元素。

在没有符号链接的系统上，此函数将始终返回与[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)() 返回。如果规范路径不存在（通常是由于悬空符号链接），则 canonicalPath() 返回空字符串。

例子：

```
QString bin = "/local/bin";         // where /local/bin is a symlink to /usr/bin
QDir binDir(bin);
QString canonicalBin = binDir.canonicalPath();
// canonicalBin now equals "/usr/bin"

QString ls = "/local/bin/ls";       // where ls is the executable "ls"
QDir lsDir(ls);
QString canonicalLs = lsDir.canonicalPath();
// canonicalLS now equals "/usr/bin/ls".
```

**也可以看看**[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)(),[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)(),[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)(),[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)(),[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)（）， 和[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)()。

### bool QDir::cd(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dirName*)

改变[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的目录到*dirName*。

返回`true`新目录是否存在；否则返回`false`. 请注意，如果新目录不存在，则不会执行逻辑 cd() 操作。

调用 cd("..") 相当于调用[cdUp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cdUp)()。

**也可以看看**[cdUp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cdUp)(),[isReadable](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)（）， 和[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)()。

### bool QDir::cdUp()

通过将目录向上移动一个目录来更改目录[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的当前目录。

返回`true`新目录是否存在；否则返回`false`. 请注意，如果新目录不存在，则不会执行逻辑 cdUp() 操作。

**注意：**在 Android 上，内容 URI 不支持此功能。有关更多信息，请参阅[DocumentFile.getParentFile()](https://translate.google.com/website?sl=auto&tl=zh-CN&hl=zh-CN&client=webapp&u=https://developer.android.com/reference/androidx/documentfile/provider/DocumentFile%23getParentFile())。

**也可以看看**[cd](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cd)(),[isReadable](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)(),[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)（）， 和[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::cleanPath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

退货*path*目录分隔符标准化（即，平台本机分隔符转换为“/”）并删除多余的分隔符，并解析“.”和“..”（尽可能）。

保留符号链接。该函数不返回规范路径，而是返回输入的最简单版本。例如，“./local”变为“local”，“local/../bin”变为“bin”，“/local/usr/../bin”变为“/local/bin”。

**也可以看看**[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)（） 和[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()。

### qsizetype QDir::count() const

返回目录和目录中文件的总数。

相当于[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（）。数数（）。

**注意：**在 6.5 之前的 Qt 版本中，此函数返回`uint`，而不是`qsizetype`。

**也可以看看**[operator[\]](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-5b-5d)（） 和[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)()。

### `[static]`[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) QDir::current()

返回应用程序的当前目录。

该目录使用当前目录的绝对路径构建，确保其[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)() 将与其相同[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

**也可以看看**[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)(),[setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)(),[home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)(),[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)（）， 和[temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::currentPath()

返回应用程序当前目录的绝对路径。当前目录是最后设置的目录[QDir::setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)() 或者，如果从未调用过该目录，则为父进程启动该应用程序的目录。

**也可以看看**[current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)(),[setCurrent](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCurrent)(),[homePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#homePath)(),[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)(),[tempPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tempPath)（）， 和[QCoreApplication::applicationDirPath](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#applicationDirPath)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::dirName() const

返回目录的名称；这与路径*不同*，例如名称为“mail”的目录可能具有路径“/var/spool/mail”。如果目录没有名称（例如，它是根目录），则返回空字符串。

不会进行任何检查来确保具有此名称的目录确实存在；但看[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。

**也可以看看**[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)(),[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)（）， 和[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)()。

### `[static]`[QFileInfoList](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfoList-typedef) QDir::drives()

返回该系统上的根目录的列表。

在 Windows 上，这会返回一个列表[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)包含“C:/”、“D:/”等的对象。这不会返回带有空可弹出介质的驱动器。在其他操作系统上，它返回一个仅包含一个根目录（即“/”）的列表。

**也可以看看**[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)（） 和[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)()。

### [QFileInfoList](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfoList-typedef) QDir::entryInfoList(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*nameFilters*, [QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = NoFilter, [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort* = NoSort) const

返回一个列表[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目录中所有文件和目录的对象，根据先前设置的名称和属性过滤器排序[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)（） 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()，并根据设置的标志进行排序[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()。

可以使用以下命令覆盖名称过滤器、文件属性过滤器和排序规范*nameFilters*,*filters*， 和*sort*论据。

如果目录不可读、不存在或者没有任何内容与规范匹配，则返回空列表。

**也可以看看**[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)(),[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)(),[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)(),[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)(),[isReadable](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)（）， 和[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。

### [QFileInfoList](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QFileInfoList-typedef) QDir::entryInfoList([QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = NoFilter, [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort* = NoSort) const

这是一个过载功能。

返回一个列表[QFileInfo](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目录中所有文件和目录的对象，根据先前设置的名称和属性过滤器排序[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)（） 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()，并根据设置的标志进行排序[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()。

可以使用以下命令覆盖属性过滤器和排序规范*filters*和*sort*论据。

如果目录不可读、不存在或者没有任何内容与规范匹配，则返回空列表。

**也可以看看**[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)(),[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)(),[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)(),[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)(),[isReadable](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)（）， 和[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。

### [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::entryList(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*nameFilters*, [QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = NoFilter, [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort* = NoSort) const

返回目录中所有文件和目录的名称列表，根据先前设置的名称和属性过滤器排序[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)（） 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()，并根据设置的标志进行排序[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()。

可以使用以下命令覆盖名称过滤器、文件属性过滤器和排序规范*nameFilters*,*filters*， 和*sort*论据。

如果目录不可读、不存在或者没有任何内容与规范匹配，则返回空列表。

**也可以看看**[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)(),[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)(),[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)（）， 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()。

### [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::entryList([QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = NoFilter, [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort* = NoSort) const

这是一个过载功能。

返回目录中所有文件和目录的名称列表，根据先前设置的名称和属性过滤器排序[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)（） 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()，并根据设置的标志进行排序[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()。

可以使用以下命令覆盖属性过滤器和排序规范*filters*和*sort*论据。

如果目录不可读、不存在或者没有任何内容与规范匹配，则返回空列表。

**注意：**要列出指向不存在文件的符号链接，[System](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum)必须传递到过滤器。

**也可以看看**[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)(),[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)(),[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)（）， 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()。

### bool QDir::exists(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*name*) const

`true`如果文件调用则返回*name*存在；否则返回 false。

除非*name*包含绝对文件路径，假定文件名相对于目录本身，因此此函数通常用于检查目录中是否存在文件。

**也可以看看**[QFileInfo::exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)（） 和[QFile::exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。

### bool QDir::exists() const

这是一个过载功能。

返回`true`目录是否存在；否则返回`false`. （如果找到同名文件，该函数将返回 false）。

该函数接受参数的重载用于测试目录中是否存在文件和目录。

**也可以看看**[QFileInfo::exists](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists)（） 和[QFile::exists](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::filePath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*) const

返回目录中文件的路径名。不*检查*文件是否确实存在于目录中；但看[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。如果[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)是相对的，返回的路径名也将是相对的。冗余的多个分隔符或“.” 和“..”目录*fileName*没有被删除（参见[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)())。

**也可以看看**[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)(),[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（）， 和[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()。

### `[since 6.0]`std::filesystem::path QDir::filesystemAbsolutePath() const

退货[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)（） 作为`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

### `[since 6.0]`std::filesystem::path QDir::filesystemCanonicalPath() const

退货[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)（） 作为`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()。

### `[since 6.0]`std::filesystem::path QDir::filesystemPath() const

退货[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)（） 作为`std::filesystem::path`。

这个函数是在Qt 6.0中引入的。

**也可以看看**[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)()。

### [QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) QDir::filter() const

返回设置的值[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()

**也可以看看**[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::fromNativeSeparators(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pathName*)

退货*pathName*使用“/”作为文件分隔符。例如，在 Windows 上，fromNativeSeparators(" `c:\\winnt\\system32`") 返回“c:/winnt/system32”。

返回的字符串可能与某些操作系统上的参数相同，例如 Unix。

**也可以看看**[toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)（） 和[separator](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#separator)()。

### `[static]`[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) QDir::home()

返回用户的主目录。

该目录是使用主目录的绝对路径构建的，确保其[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)() 将与其相同[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

看[homePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#homePath)（）了解详情。

**也可以看看**[drives](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drives)(),[current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)(),[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)（）， 和[temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::homePath()

返回用户主目录的绝对路径。

在 Windows 下，此函数将返回当前用户配置文件的目录。通常，这是：

```
C:/Users/Username
```

使用[toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)() 函数将分隔符转换为适合底层操作系统的分隔符。

如果当前用户配置文件的目录不存在或无法检索，将检查以下替代方案（按给定顺序），直到找到现有且可用的路径：

1. 环境变量指定的路径`USERPROFILE`。
2. `HOMEDRIVE`由和环境变量连接形成的路径`HOMEPATH`。
3. 环境变量指定的路径`HOME`。
4. 返回的路径[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)() 函数（使用`SystemDrive`环境变量）
5. 目录`C:/`。

在非 Windows 操作系统下，`HOME`如果环境变量存在，则使用该环境变量，否则使用返回的路径[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)()。

**也可以看看**[home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)(),[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)(),[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)（）， 和[tempPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tempPath)()。

### bool QDir::isAbsolute() const

`true`如果目录路径是绝对路径则返回；否则返回`false`. 看[isAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolutePath)()。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)(),[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)（）， 和[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)()。

### `[static]`bool QDir::isAbsolutePath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

返回`true`如果*path*是绝对的；`false`如果是相对的则返回。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)(),[isRelativePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelativePath)(),[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)(),[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)（）， 和[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### bool QDir::isEmpty([QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters* = Filters(AllEntries | NoDotAndDotDot)) const

返回目录是否为空。

`count() == 0`与使用过滤器等效`QDir::AllEntries | QDir::NoDotAndDotDot`，但速度更快，因为它只检查目录是否包含至少一个条目。

**注意：**除非您设置*filters*要包含的标志`QDir::NoDotAndDotDot`（与默认值一样），没有目录是空的。

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)(),[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（）， 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()。

### bool QDir::isReadable() const

返回`true`目录是否可读*并且*我们可以按名称打开文件；否则返回`false`.

**警告：**此函数的错误值并不能保证目录中的文件不可访问。

**也可以看看**[QFileInfo::isReadable](https://doc-qt-io.translate.goog/qt-6/qfileinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isReadable)()。

### bool QDir::isRelative() const

返回`true`目录路径是否是相对路径；否则返回 false。（在 Unix 下，如果路径不以“/”开头，则路径是相对路径）。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)(),[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)(),[isAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolutePath)（）， 和[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)()。

### `[static]`bool QDir::isRelativePath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

返回`true`如果*path*是相对的；`false`如果是绝对的则返回。

**注意：**以冒号 (:) 开头的路径*始终*被视为绝对路径，因为它们表示[QResource](https://doc-qt-io.translate.goog/qt-6/qresource.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)(),[isAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolutePath)（）， 和[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)()。

### bool QDir::isRoot() const

返回`true`该目录是否为根目录；否则返回`false`.

**注意：**如果目录是根目录的符号链接，则此函数返回`false`. 如果您想测试此用途[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()，例如

```
QDir dir("/tmp/root_link");
dir = dir.canonicalPath();
if (dir.isRoot())
    qWarning("It is a root link");
```

**也可以看看**[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)（） 和[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)()。

### `[static constexpr noexcept]`[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::listSeparator()

返回本机路径列表分隔符：Unix 下的“:”和“;” 在Windows下。

**也可以看看**[separator](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#separator)()。

### bool QDir::makeAbsolute()

将目录路径转换为绝对路径。如果它已经是绝对的，什么也不会发生。`true`如果转换成功则返回；否则返回`false`.

**也可以看看**[isAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolute)(),[isAbsolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAbsolutePath)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（）， 和[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)()。

### `[static]`bool QDir::match(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*filter*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

返回`true`如果*fileName*匹配通配符（glob）模式*filter*; 否则返回`false`. 这*filter*可以包含由空格或分号分隔的多个模式。匹配不区分大小写。

**也可以看看**[QRegularExpression::fromWildcard](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromWildcard)(),[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（）， 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)()。

### `[static]`bool QDir::match(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*filters*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

这是一个过载功能。

返回`true`如果*fileName*匹配列表中的任何通配符（glob）模式*filters*; 否则返回`false`. 匹配不区分大小写。

**也可以看看**[QRegularExpression::fromWildcard](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromWildcard)(),[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（）， 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)()。

### `[since 6.3]`bool QDir::mkdir(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dirName*, [QFile::Permissions](https://doc-qt-io.translate.goog/qt-6/qfiledevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Permission-enum) *permissions*) const

创建一个名为的子目录*dirName*。

`true`成功回报；否则返回`false`.

如果调用该函数时目录已经存在，则返回`false`.

创建的目录的权限设置为*permissions*。

在 POSIX 系统上，权限受 值的影响`umask`。

在 Windows 上，权限是使用 ACL 模拟的。当授予组的权限少于其他组时，这些 ACL 的顺序可能不规范。当打开“属性”对话框的“安全”选项卡时，具有此类权限的文件和目录将生成警告。向该组授予授予其他人的所有权限可以避免此类警告。

该功能是在 Qt 6.3 中引入的。

**也可以看看**[rmdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rmdir)()。

### bool QDir::mkdir(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dirName*) const

这是一个过载功能。

创建一个名为的子目录*dirName*具有默认权限。

在 POSIX 系统上，默认情况下授予`umask`. 在 Windows 上，新目录继承其父目录的权限。

### bool QDir::mkpath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dirPath*) const

创建目录路径*dirPath*。

该函数将创建创建目录所需的所有父目录。

`true`成功则返回；否则返回`false`.

如果调用此函数时路径已经存在，则返回 true。

**也可以看看**[rmpath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rmpath)()。

### [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::nameFilters() const

返回由设置的字符串列表[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)()

**也可以看看**[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)()。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::path() const

返回路径。这可能包含符号链接，但绝不包含多余的“.”、“..”或多个分隔符。

返回的路径可以是绝对路径或相对路径（请参阅[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)())。

**也可以看看**[setPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPath)(),[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)(),[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)(),[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)(),[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)(),[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)(),[toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)（）， 和[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)()。

### void QDir::refresh() const

刷新目录信息。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::relativeFilePath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*) const

返回路径*fileName*相对于目录。

```
QDir dir("/home/bob");
QString s;

s = dir.relativeFilePath("images/file.jpg");     // s is "images/file.jpg"
s = dir.relativeFilePath("/home/mary/file.txt"); // s is "../mary/file.txt"
```

**也可以看看**[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)(),[filePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filePath)（）， 和[canonicalPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#canonicalPath)()。

### bool QDir::remove(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*fileName*)

删除文件，*fileName*。

`true`如果文件删除成功则返回；否则返回`false`.

### bool QDir::removeRecursively()

删除目录，包括其所有内容。

如果成功则返回`true`，否则返回 false。

如果无法删除文件或目录，removeRecursively() 会继续尝试删除尽可能多的文件和子目录，然后返回`false`。

如果目录已被删除，则该方法返回`true`（已达到预期结果）。

**注意：**此函数用于删除小型应用程序内部目录（例如临时目录），但不是用户可见的目录。对于用户可见的操作，建议更准确地向用户报告错误，在出现错误时提供解决方案，在删除过程中显示进度（因为可能需要几分钟）等。

### bool QDir::rename(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*oldName*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*newName*)

重命名文件或目录*oldName*到*newName*，如果成功则返回true；否则返回`false`.

在大多数文件系统上，只有在以下情况下，rename() 才会失败*oldName*不存在，或者具有新名称的文件已存在。但是，还有其他原因导致 rename() 失败。例如，在以下情况下，至少在一个文件系统上 rename() 会失败：*newName*指向一个打开的文件。

如果*oldName*是一个不能立即重命名的文件（不是目录），Qt 将尝试复制*oldName*到*newName*并删除*oldName*。

**也可以看看**[QFile::rename](https://doc-qt-io.translate.goog/qt-6/qfile.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rename)()。

### bool QDir::rmdir(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dirName*) const

删除指定的目录*dirName*。

该目录必须为空，rmdir() 才能成功。

`true`成功则返回；否则返回`false`.

**也可以看看**[mkdir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mkdir)()。

### bool QDir::rmpath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*dirPath*) const

删除目录路径*dirPath*。

该函数将删除所有父目录*dirPath*，前提是它们是空的。这与 mkpath(dirPath) 相反。

`true`成功则返回；否则返回`false`.

**也可以看看**[mkpath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mkpath)()。

### `[static]`[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) QDir::root()

返回根目录。

该目录使用根目录的绝对路径构建，确保其[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)() 将与其相同[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

看[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)（）了解详情。

**也可以看看**[drives](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drives)(),[current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)(),[home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)（）， 和[temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::rootPath()

返回根目录的绝对路径。

对于 Unix 操作系统，返回“/”。对于 Windows 文件系统，通常返回“c:/”。

**也可以看看**[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)(),[drives](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drives)(),[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)(),[homePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#homePath)（）， 和[tempPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tempPath)()。

### `[static]`[QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::searchPaths(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*prefix*)

返回搜索路径*prefix*。

**也可以看看**[setSearchPaths](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSearchPaths)（） 和[addSearchPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSearchPath)()。

### `[static]`[QChar](https://doc-qt-io.translate.goog/qt-6/qchar.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::separator()

返回本机目录分隔符：Unix 下为“/”，Windows 下为“\”。

您不需要使用此函数来构建文件路径。如果您始终使用“/”，Qt 将转换您的路径以符合底层操作系统。如果您想使用操作系统的分隔符向用户显示路径，请使用[toNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toNativeSeparators)()。

**也可以看看**[listSeparator](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#listSeparator)()。

### `[static]`bool QDir::setCurrent(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

将应用程序的当前工作目录设置为*path*。`true`如果目录更改成功则返回；否则返回`false`.

```
QString absolute = "/local/bin";
QString relative = "local/bin";
QFileInfo absFile(absolute);
QFileInfo relFile(relative);

QDir::setCurrent(QDir::rootPath());
// absFile and relFile now point to the same file

QDir::setCurrent("/tmp");
// absFile now points to "/local/bin",
// while relFile points to "/tmp/local/bin"
```

**也可以看看**[current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)(),[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)(),[home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)(),[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)（）， 和[temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)()。

### void QDir::setFilter([QDir::Filters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum) *filters*)

设置使用的过滤器[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)（） 到*filters*。过滤器用于指定应返回的文件类型[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)()。看[QDir::Filter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Filter-enum)。

**也可以看看**[filter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filter)（） 和[setNameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setNameFilters)()。

### void QDir::setNameFilters(const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*nameFilters*)

设置使用的名称过滤器[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)() 指定的过滤器列表*nameFilters*。

`*`每个名称过滤器都是一个能够理解和通配符的通配符（通配符）过滤器`?`。看[QRegularExpression::fromWildcard](https://doc-qt-io.translate.goog/qt-6/qregularexpression.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromWildcard)()。

例如，以下代码在一个上设置了三个名称过滤器[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)确保仅列出具有通常用于 C++ 源文件的扩展名的文件：

```
    QStringList filters;
    filters < <  "*.cpp" < <  "*.cxx" < <  "*.cc";
    dir.setNameFilters(filters);
```

**也可以看看**[nameFilters](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#nameFilters)（） 和[setFilter](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFilter)()。

### void QDir::setPath(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

将目录的路径设置为*path*。该路径已清除多余的“.”、“..”和多个分隔符。不会检查具有此路径的目录是否实际存在；但你可以使用自己检查[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)()。

该路径可以是绝对路径或相对路径。绝对路径以目录分隔符“/”开头（Windows 下可以在前面加上驱动器规范）。相对文件名以目录名或文件名开头，并指定相对于当前目录的路径。绝对路径的示例是字符串“/tmp/quartz”，相对路径可能类似于“src/fatlib”。

**也可以看看**[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)(),[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)(),[exists](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exists-1)(),[cleanPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cleanPath)(),[dirName](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dirName)(),[absoluteFilePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absoluteFilePath)(),[isRelative](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isRelative)（）， 和[makeAbsolute](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#makeAbsolute)()。

### `[since 6.0]`void QDir::setPath(const std::filesystem::path &*path*)

这是一个过载功能。

这个函数是在Qt 6.0中引入的。

### `[static]`void QDir::setSearchPaths(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*prefix*, const [QStringList](https://doc-qt-io.translate.goog/qt-6/qstringlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*searchPaths*)

设置或替换 Qt 的带有前缀的文件名搜索路径*prefix*到*searchPaths*。

要指定文件名的前缀，请在前缀前面加上一个冒号（例如，“images:undo.png”、“xmldocs:books.xml”）。*prefix*只能包含字母或数字（例如，不能包含冒号或斜杠）。

Qt 使用此搜索路径来查找具有已知前缀的文件。从第一个条目开始，按顺序测试搜索路径条目。

```
QDir::setSearchPaths("icons", QStringList(QDir::homePath() + "/images"));
QDir::setSearchPaths("docs", QStringList(":/embeddedDocuments"));
...
QPixmap pixmap("icons:undo.png"); // will look for undo.png in QDir::homePath() + "/images"
QFile file("docs:design.odf"); // will look in the :/embeddedDocuments resource path
```

文件名前缀的长度必须至少为 2 个字符，以避免与 Windows 驱动器盘符冲突。

搜索路径可能包含以下路径[The Qt Resource System](https://doc-qt-io.translate.goog/qt-6/resources.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[searchPaths](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#searchPaths)()。

### void QDir::setSorting([QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) *sort*)

设置使用的排序顺序[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)（） 和[entryInfoList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryInfoList)()。

这*sort*由枚举中的 OR 值指定[QDir::SortFlag](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)。

**也可以看看**[sorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)（） 和[SortFlag](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)。

### [QDir::SortFlags](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum) QDir::sorting() const

返回设置的值[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)()

**也可以看看**[setSorting](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSorting)（） 和[SortFlag](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortFlag-enum)。

### `[noexcept]`void QDir::swap([QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &*other*)

交换这个[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例与*other*。这个功能非常快并且永远不会失败。

### `[static]`[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) QDir::temp()

返回系统的临时目录。

该目录是使用临时目录的绝对规范路径构建的，确保其[path](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#path)() 将与其相同[absolutePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#absolutePath)()。

看[tempPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#tempPath)（）了解详情。

**也可以看看**[drives](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drives)(),[current](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#current)(),[home](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#home)（）， 和[root](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#root)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::tempPath()

返回系统临时目录的绝对规范路径。

`TMPDIR`在 Unix/Linux 系统上，这是环境变量中的路径，或者`/tmp`如果`TMPDIR`未定义的话。`TEMP`在 Windows 上，这通常是或环境变量中的路径`TMP`。此方法返回的路径不以目录分隔符结尾，除非它是（驱动器的）根目录。

**也可以看看**[temp](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#temp)(),[currentPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#currentPath)(),[homePath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#homePath)（）， 和[rootPath](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rootPath)()。

### `[static]`[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::toNativeSeparators(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pathName*)

退货*pathName*将“/”分隔符转换为适合底层操作系统的分隔符。

在 Windows 上，toNativeSeparators("c:/winnt/system32") 返回“c:\winnt\system32”。

返回的字符串可能与某些操作系统上的参数相同，例如 Unix。

**也可以看看**[fromNativeSeparators](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fromNativeSeparators)（） 和[separator](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#separator)()。

### bool QDir::operator!=(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &*dir*) const

`true`如果目录则返回*dir*并且该目录具有不同的路径或不同的排序或过滤设置；否则返回 false。

例子：

```
// The current directory is "/usr/local"
QDir d1("/usr/local/bin");
d1.setFilter(QDir::Executable);
QDir d2("bin");
if (d1 != d2)
    qDebug("They differ");
```

### [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &QDir::operator=(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &*dir*)

复制一份*dir*对象并将其分配给 this[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

### `[noexcept]`[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &QDir::operator=([QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &&*other*)

移动分配*other*对此[QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

### bool QDir::operator==(const [QDir](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QDir) &*dir*) const

`true`如果目录则返回*dir*并且该目录具有相同的路径，并且它们的排序和过滤设置也相同；否则返回`false`.

例子：

```
// The current directory is "/usr/local"
QDir d1("/usr/local/bin");
QDir d2("bin");
if (d1 == d2)
    qDebug("They're the same");
```

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QDir::operator[]\(qsizetype *pos*) const

返回位置处的文件名*pos*在文件名列表中。相当于[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)().at(索引)。*pos*必须是列表中的有效索引位置（即 0 < = pos < [count](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)())。

**注意：**在 6.5 之前的 Qt 版本中，*pos*是`int`，不是`qsizetype`。

**也可以看看**[count](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#count)（） 和[entryList](https://doc-qt-io.translate.goog/qt-6/qdir.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#entryList)()。