#  QPen Class

QPen 类定义了如何[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)应该绘制线条和形状轮廓。[更多的...](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include < QPen>                                             |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:  | QT += gui                                                    |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qpen-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QPen 是[绘画类](https://doc-qt-io.translate.goog/qt-6/painting.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共职能

|                  | **[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen)**() |
| ---------------- | ------------------------------------------------------------ |
|                  | **[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen-1)**(Qt::PenStyle *style*) |
|                  | **[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen-2)**(const QColor &*color*) |
|                  | **[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen-3)**(const QBrush &*brush*, qreal *width*, Qt::PenStyle *style* = Qt::SolidLine, Qt::PenCapStyle *cap* = Qt::SquareCap, Qt::PenJoinStyle *join* = Qt::BevelJoin) |
|                  | **[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen-4)**(const QPen &*pen*) |
|                  | **[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen-5)**(QPen &&*pen*) |
|                  | **[~QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QPen)**() |
| QBrush           | **[brush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)**() const |
| Qt::PenCapStyle  | **[capStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capStyle)**() const |
| QColor           | **[color](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)**() const |
| qreal            | **[dashOffset](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dashOffset)**() const |
| QList<qreal>     | **[dashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dashPattern)**() const |
| bool             | **[isCosmetic](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isCosmetic)**() const |
| bool             | **[isSolid](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSolid)**() const |
| Qt::PenJoinStyle | **[joinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#joinStyle)**() const |
| qreal            | **[miterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#miterLimit)**() const |
| void             | **[setBrush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)**(const QBrush &*brush*) |
| void             | **[setCapStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCapStyle)**(Qt::PenCapStyle *style*) |
| void             | **[setColor](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)**(const QColor &*color*) |
| void             | **[setCosmetic](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCosmetic)**(bool *cosmetic*) |
| void             | **[setDashOffset](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDashOffset)**(qreal *offset*) |
| void             | **[setDashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDashPattern)**(const QList<qreal> &*pattern*) |
| void             | **[setJoinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setJoinStyle)**(Qt::PenJoinStyle *style*) |
| void             | **[setMiterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMiterLimit)**(qreal *limit*) |
| void             | **[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)**(Qt::PenStyle *style*) |
| void             | **[setWidth](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidth)**(int *width*) |
| void             | **[setWidthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidthF)**(qreal *width*) |
| Qt::PenStyle     | **[style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)**() const |
| void             | **[swap](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QPen &*other*) |
| int              | **[width](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)**() const |
| qreal            | **[widthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widthF)**() const |
| QVariant         | **[operator QVariant](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-QVariant)**() const |
| bool             | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QPen &*pen*) const |
| QPen &           | **[operator=](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QPen &*pen*) |
| QPen &           | **[operator=](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(QPen &&*other*) |
| bool             | **[operator==](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QPen &*pen*) const |

## 相关非会员

| QDataStream & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QDataStream &*stream*, const QPen &*pen*) |
| ------------- | ------------------------------------------------------------ |
| QDataStream & | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*stream*, QPen &*pen*) |

## 详细说明

一支笔有一个[style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)(),[width](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)(),[brush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)(),[capStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capStyle)（） 和[joinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#joinStyle)()。

画笔样式定义线型。画笔用于填充笔生成的笔划。使用[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类来指定填充样式。端盖样式决定了可以使用以下方式绘制的线端端盖[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，而连接样式描述了如何绘制两条线之间的连接。画笔宽度可以用整数（[width](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)()) 和浮点数 ([widthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widthF)（）） 精确。线宽为零表示化妆笔。这意味着画笔宽度始终绘制为一个像素宽，与[transformation](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)设置在画家身上。

可以使用相应的功能轻松修改各种设置[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)(),[setWidth](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidth)(),[setBrush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)(),[setCapStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCapStyle)（） 和[setJoinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setJoinStyle)() 函数（注意，改变画笔属性时必须重置画家的画笔）。

例如：

```
QPainter painter(this);
QPen pen(Qt::green, 3, Qt::DashDotLine, Qt::RoundCap, Qt::RoundJoin);
painter.setPen(pen);
```

这相当于

```
QPainter painter(this);
QPen pen;  // creates a default pen

pen.setStyle(Qt::DashDotLine);
pen.setWidth(3);
pen.setBrush(Qt::green);
pen.setCapStyle(Qt::RoundCap);
pen.setJoinStyle(Qt::RoundJoin);

painter.setPen(pen);
```

默认笔是纯黑色画笔，宽度为 1，方帽样式 ([Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)) 和斜角连接样式 ([Qt::BevelJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)）。

此外，QPen 还提供[color](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)（） 和[setColor](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)() 分别提取和设置笔刷颜色的便捷函数。笔也可以被比较和流式传输。

有关一般绘画的更多信息，请参阅[Paint System](https://doc-qt-io.translate.goog/qt-6/paintsystem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档。

### 钢笔风格

Qt 提供了几种内置样式，代表为[Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)枚举：

| ![img](.\QPen\qpen-solid.png)                                | ![img](.\QPen\qpen-dash.png)                                 | ![img](.\QPen\qpen-dot.png)                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Qt::SolidLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) | [Qt::DashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) | [Qt::DotLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) |
| ![img](.\QPen\qpen-dashdot.png)                              | ![img](.\QPen\qpen-dashdotdot.png)                           | ![img](.\QPen\qpen-custom.png)                               |
| [Qt::DashDotLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) | [Qt::DashDotDotLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) | [Qt::CustomDashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) |

只需使用[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)() 函数将笔样式转换为任一内置样式，除了[Qt::CustomDashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)我们很快就会回到这个风格。将样式设置为[Qt::NoPen](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)告诉画家不要画线条或轮廓。默认的笔样式是[Qt::SolidLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)。

从 Qt 4.1 开始，还可以使用以下命令指定自定义破折号图案[setDashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDashPattern)() 函数隐式将笔的样式转换为[Qt::CustomDashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)。模式参数，a[QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，必须指定为偶数个[qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)其中条目 1、3、5... 是破折号，2、4、6... 是空格。例如，上面显示的自定义模式是使用以下代码创建的：

```
QPen pen;
QList<qreal> dashes;
qreal space = 4;

dashes << 1 << space << 3 << space << 9 << space
           << 27 << space << 9 << space;

pen.setDashPattern(dashes);
```

请注意，虚线图案是以笔宽度为单位指定的，例如，长度为 5、宽度为 10 的虚线的长度为 50 像素。

可以使用以下命令检索当前设置的破折号图案[dashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dashPattern)（） 功能。使用[isSolid](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSolid)() 函数判断笔是否有实心填充。

### 帽型

帽样式定义了如何使用以下方式绘制线条的端点[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。帽样式仅适用于宽线，即宽度为 1 或更大时。这[Qt::PenCapStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)enum 提供以下样式：

| ![img](.\QPen\qpen-square.png)                               | ![img](.\QPen\qpen-flat.png)                                 | ![img](.\QPen\qpen-roundcap.png)                             |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum) | [Qt::FlatCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum) | [Qt::RoundCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum) |

这[Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)样式是覆盖端点并超出端点线宽一半的方形线端。这[Qt::FlatCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)样式是方形线端，不覆盖线的终点。还有[Qt::RoundCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)样式是覆盖端点的圆线末端。

默认为[Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)。

笔宽为 0 或 1 时是否绘制端点取决于笔帽样式。使用[Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)或者[Qt::RoundCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)他们是用[Qt::FlatCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)它们不是被画出来的。

### 加盟方式

连接样式定义了如何使用以下命令绘制两条连接线之间的连接[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。连接样式仅适用于宽线，即宽度为 1 或更大时。这[Qt::PenJoinStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)enum 提供以下样式：

| ![img](.\QPen\qpen-bevel.png)                                | ![img](.\QPen\qpen-miter.png)                                | ![img](.\QPen\qpen-roundjoin.png)                            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Qt::BevelJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum) | [Qt::MiterJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum) | [Qt::RoundJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum) |

这[Qt::BevelJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)样式填充两条线之间的三角形凹口。这[Qt::MiterJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)风格延伸线条以一定角度相交。还有[Qt::RoundJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)样式填充两条线之间的圆弧。

默认为[Qt::BevelJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)。

![img](.\QPen\qpen-miterlimit.png)

当应用[Qt::MiterJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)应用样式后，可以使用[setMiterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMiterLimit)() 函数指定斜接连接可以从连接点延伸多远。这[miterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#miterLimit)() 用于减少线接近平行的线连接之间的伪影。

这[miterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#miterLimit)() 必须以笔宽度为单位指定，例如，宽度 10 的斜接限制为 5，长度为 50 像素。默认斜接限制为 2，即笔宽度（以像素为单位）的两倍。

| ![img](.\QPen\qpen-demo.png) | **[The Path Stroking Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-pathstroke-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)**Path Stroke 示例展示了 Qt 的内置破折号模式，并展示了如何使用自定义模式来扩展可用模式的范围。 |
| ---------------------------- | ------------------------------------------------------------ |
|                              |                                                              |

**也可以看看**[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Path Stroking Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-pathstroke-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Scribble Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-widgets-scribble-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QPen::QPen()

构造一个宽度为 1 的默认黑色实线笔。

### QPen::QPen([Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) *style*)

构造一支宽度为 1 且给定的黑笔*style*。

**也可以看看**[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()。

### QPen::QPen(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

构造一个宽度为 1 且给定的实线笔*color*。

**也可以看看**[setBrush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)（） 和[setColor](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)()。

### QPen::QPen(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *width*, [Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) *style* = Qt::SolidLine, [Qt::PenCapStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum) *cap* = Qt::SquareCap, [Qt::PenJoinStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum) *join* = Qt::BevelJoin)

构造一支具有指定的笔*brush*,*width*， 笔*style*,*cap*风格和*join*风格。

**也可以看看**[setBrush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)(),[setWidth](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidth)(),[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)(),[setCapStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCapStyle)（）， 和[setJoinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setJoinStyle)()。

### `[noexcept]`QPen::QPen(const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*pen*)

构造一支钢笔，它是给定的副本*pen*。

### `[noexcept]`QPen::QPen([QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &&*pen*)

构造一支从给定位置移动的笔*pen*。

移出的笔只能被分配、复制或销毁。任何其他操作（在赋值之前）都会导致未定义的行为。

### `[noexcept]`QPen::~QPen()

毁掉笔。

### [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPen::brush() const

返回用于填充用该笔生成的笔划的画笔。

**也可以看看**[setBrush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)()。

### [Qt::PenCapStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum) QPen::capStyle() const

返回笔的笔帽样式。

**也可以看看**[setCapStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCapStyle)（） 和[Cap Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cap-style)。

### [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPen::color() const

返回此笔画笔的颜色。

**也可以看看**[brush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)（） 和[setColor](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QPen::dashOffset() const

返回笔的破折号偏移量。

**也可以看看**[setDashOffset](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDashOffset)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)> QPen::dashPattern() const

返回此笔的破折号图案。

**也可以看看**[setDashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDashPattern)(),[style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)（）， 和[isSolid](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSolid)()。

### bool QPen::isCosmetic() const

`true`如果笔是装饰性的，则返回；否则返回`false`.

修饰笔用于绘制具有恒定宽度的笔画，无论对笔画应用任何变换。[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它们一起使用。使用化妆笔绘制形状可确保其轮廓在不同比例因子下具有相同的厚度。

默认情况下，零宽度笔是装饰性的。

**也可以看看**[setCosmetic](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCosmetic)（） 和[widthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widthF)()。

### bool QPen::isSolid() const

`true`如果笔具有实心填充则返回，否则返回 false。

**也可以看看**[style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)（） 和[dashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dashPattern)()。

### [Qt::PenJoinStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum) QPen::joinStyle() const

返回笔的连接样式。

**也可以看看**[setJoinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setJoinStyle)（） 和[Join Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#join-style)。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QPen::miterLimit() const

返回笔的斜接限制。仅当连接样式设置为时，斜接限制才相关[Qt::MiterJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)。

**也可以看看**[setMiterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMiterLimit)（） 和[Join Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#join-style)。

### void QPen::setBrush(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

将用于填充用该笔生成的笔划的画笔设置为给定的*brush*。

**也可以看看**[brush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)（） 和[setColor](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)()。

### void QPen::setCapStyle([Qt::PenCapStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum) *style*)

将笔的笔帽样式设置为给定的*style*。默认值为[Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)。

**也可以看看**[capStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#capStyle)（） 和[Cap Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cap-style)。

### void QPen::setColor(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

将此笔画笔的颜色设置为给定的*color*。

**也可以看看**[setBrush](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)（） 和[color](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)()。

### void QPen::setCosmetic(bool *cosmetic*)

将此笔设置为装饰性或非装饰性，具体取决于*cosmetic*。

**也可以看看**[isCosmetic](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isCosmetic)()。

### void QPen::setDashOffset([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *offset*)

将此笔的虚线偏移量（虚线图案的起点）设置为*offset*指定的。偏移量是根据用于指定虚线图案的单位来测量的。

| ![img](.\QPen\qpen-dashpattern.png) | 例如，每个笔划长度为四个单位，后跟两个单位间隙的图案，在绘制为线条时将从笔划开始。但是，如果虚线偏移量设置为 4.0，则绘制的任何线都将从间隙开始。4.0 以内的偏移值将导致首先绘制部分笔划，4.0 和 6.0 之间的偏移值将导致线条从间隙的一部分开始。 |
| ----------------------------------- | ------------------------------------------------------------ |
|                                     |                                                              |

**注意：**这会隐式地将笔的样式转换为[Qt::CustomDashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)。

**也可以看看**[dashOffset](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dashOffset)()。

### void QPen::setDashPattern(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)> &*pattern*)

将此笔的破折号图案设置为给定的*pattern*。这会隐式地将笔的样式转换为[Qt::CustomDashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)。

该模式必须指定为偶数个正条目，其中条目 1、3、5... 是破折号，2、4、6... 是空格。例如：

| ![img](.\QPen\qpen-custom.png) | `QPen pen; QList<qreal> dashes; qreal space = 4; dashes << 1 << space << 3 << space << 9 << space           << 27 << space << 9 << space; pen.setDashPattern(dashes);` |
| ------------------------------ | ------------------------------------------------------------ |
|                                |                                                              |

虚线图案以笔宽度为单位指定；例如，长度为 5、宽度为 10 的破折号的长度为 50 像素。请注意，宽度为零的笔相当于宽度为 1 像素的化妆笔。

每个破折号也受大写样式的影响，因此带有方形大写字母设置的 1 破折号将在每个方向上延伸 0.5 像素，从而导致总宽度为 2。

请注意，默认的帽子样式是[Qt::SquareCap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenCapStyle-enum)，表示方形线端覆盖端点并超出端点线宽的一半。

**也可以看看**[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)(),[dashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dashPattern)(),[setCapStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCapStyle)（）， 和[setCosmetic](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCosmetic)()。

### void QPen::setJoinStyle([Qt::PenJoinStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum) *style*)

将笔的连接样式设置为给定的*style*。默认值为[Qt::BevelJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)。

**也可以看看**[joinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#joinStyle)（） 和[Join Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#join-style)。

### void QPen::setMiterLimit([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *limit*)

将此笔的斜接限制设置为给定的*limit*。

![img](.\QPen\qpen-miterlimit.png)

斜接限制描述了斜接连接可以从连接点延伸多远。这用于减少线接近平行的线连接之间的伪影。

该值仅在笔样式设置为时有效[Qt::MiterJoin](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenJoinStyle-enum)。该值以画笔宽度为单位指定，例如，宽度 10 中的斜接限制为 5，长度为 50 像素。默认斜接限制为 2，即笔宽度（以像素为单位）的两倍。

**也可以看看**[miterLimit](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#miterLimit)(),[setJoinStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setJoinStyle)（）， 和[Join Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#join-style)。

### void QPen::setStyle([Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) *style*)

将画笔样式设置为给定的*style*。

请参阅[Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)可用样式列表的文档。从 Qt 4.1 开始，还可以使用以下命令指定自定义破折号图案[setDashPattern](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDashPattern)() 函数隐式将笔的样式转换为[Qt::CustomDashLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)。

**注意：**此函数将破折号偏移重置为零。

**也可以看看**[style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)（） 和[Pen Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pen-style)。

### void QPen::setWidth(int *width*)

将画笔宽度设置为给定的*width*以整数精度的像素为单位。

线宽为零表示化妆笔。这意味着画笔宽度始终绘制为一个像素宽，与[transformation](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)设置在画家身上。

不支持将画笔宽度设置为负值。

**也可以看看**[setWidthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidthF)（） 和[width](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)()。

### void QPen::setWidthF([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *width*)

将画笔宽度设置为给定的*width*以浮点精度的像素为单位。

线宽为零表示化妆笔。这意味着画笔宽度始终绘制为一个像素宽，与[transformation](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)在画家身上。

不支持将画笔宽度设置为负值。

**也可以看看**[setWidth](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidth)（） 和[widthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widthF)()。

### [Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) QPen::style() const

返回笔样式。

**也可以看看**[setStyle](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)（） 和[Pen Style](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pen-style)。

### `[noexcept]`void QPen::swap([QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*other*)

交换笔*other*用这支笔。这个操作非常快并且永远不会失败。

### int QPen::width() const

返回整数精度的画笔宽度。

**也可以看看**[setWidth](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidth)（） 和[widthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#widthF)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QPen::widthF() const

返回具有浮点精度的画笔宽度。

**也可以看看**[setWidthF](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWidthF)（） 和[width](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)()。

### [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPen::operator QVariant() const

将笔返回为[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### bool QPen::operator!=(const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*pen*) const

`true`如果笔与给定的不同则返回*pen*; 否则为假。如果两支笔的样式、宽度或颜色不同，那么它们就是不同的。

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### `[noexcept]`[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &QPen::operator=(const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*pen*)

分配给定的*pen*到这支笔并返回对此笔的引用。

### `[noexcept]`[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &QPen::operator=([QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &&*other*)

移动分配*other*对此[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

### bool QPen::operator==(const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*pen*) const

`true`如果笔等于给定值则返回*pen*; 否则为假。如果两支笔具有相同的样式、宽度和颜色，则它们是相等的。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

## 相关非会员

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator<<([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*stream*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*pen*)

写出给定的*pen*对给定的*stream*并返回对*stream*。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*stream*, [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPen) &*pen*)

从给定的位置读取笔*stream*进入给定的*pen*并返回对*stream*。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。