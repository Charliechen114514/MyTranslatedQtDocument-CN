#  QBrush Class

QBrush 类定义了绘制的形状的填充图案[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header: | #include <QBrush>                                            |
| ------- | ------------------------------------------------------------ |
| CMake:  | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:  | QT += gui                                                    |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qbrush-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- QBrush 是[绘画类](https://doc-qt-io.translate.goog/qt-6/painting.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[隐式共享类](https://doc-qt-io.translate.goog/qt-6/shared.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的一部分。

## 公共职能

|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush)**() |
| ----------------- | ------------------------------------------------------------ |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-1)**(Qt::BrushStyle *style*) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-2)**(const QColor &*color*, Qt::BrushStyle *style* = Qt::SolidPattern) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-3)**(Qt::GlobalColor *color*, Qt::BrushStyle *style* = Qt::SolidPattern) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-4)**(const QColor &*color*, const QPixmap &*pixmap*) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-5)**(Qt::GlobalColor *color*, const QPixmap &*pixmap*) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-6)**(const QPixmap &*pixmap*) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-7)**(const QImage &*image*) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-9)**(const QGradient &*gradient*) |
|                   | **[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush-8)**(const QBrush &*other*) |
|                   | **[~QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QBrush)**() |
| const QColor &    | **[color](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)**() const |
| const QGradient * | **[gradient](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gradient)**() const |
| bool              | **[isOpaque](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isOpaque)**() const |
| void              | **[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)**(const QColor &*color*) |
| void              | **[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor-1)**(Qt::GlobalColor *color*) |
| void              | **[setStyle](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)**(Qt::BrushStyle *style*) |
| void              | **[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)**(const QPixmap &*pixmap*) |
| void              | **[setTextureImage](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextureImage)**(const QImage &*image*) |
| void              | **[setTransform](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)**(const QTransform &*matrix*) |
| Qt::BrushStyle    | **[style](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)**() const |
| void              | **[swap](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#swap)**(QBrush &*other*) |
| QPixmap           | **[texture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#texture)**() const |
| QImage            | **[textureImage](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textureImage)**() const |
| QTransform        | **[transform](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)**() const |
| QVariant          | **[operator QVariant](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-QVariant)**() const |
| bool              | **[operator!=](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)**(const QBrush &*brush*) const |
| QBrush &          | **[operator=](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq)**(const QBrush &*brush*) |
| QBrush &          | **[operator=](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-1)**(QBrush &&*other*) |
| bool              | **[operator==](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)**(const QBrush &*brush*) const |

## 相关非会员

| QDataStream & | **[operator<<](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-lt-lt)**(QDataStream &*stream*, const QBrush &*brush*) |
| ------------- | ------------------------------------------------------------ |
| QDataStream & | **[operator>>](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-gt-gt)**(QDataStream &*stream*, QBrush &*brush*) |

## 详细说明

画笔具有样式、颜色、渐变和纹理。

刷子[style](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)() 使用以下方式定义填充图案[Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)枚举。默认的画笔样式是[Qt::NoBrush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)（取决于您如何构建画笔）。这种风格告诉画家不要填充形状。填充的标准样式是[Qt::SolidPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。可以在使用适当的构造函数创建画笔时设置样式，此外[setStyle](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)() 函数提供了在画笔构建后更改样式的方法。

![画笔样式](.\QBrush\brush-styles.png)

刷子[color](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)() 定义填充图案的颜色。颜色可以是 Qt 的预定义颜色之一，[Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum)，或任何其他自定义[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。可以使用以下命令检索和更改当前设置的颜色[color](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)（） 和[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)() 函数分别。

这[gradient](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gradient)() 定义当前样式为以下任一情况时使用的渐变填充[Qt::LinearGradientPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum),[Qt::RadialGradientPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)或者[Qt::ConicalGradientPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。渐变画笔是通过给定一个[QGradient](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建 QBrush 时作为构造函数参数。Qt 提供了三种不同的渐变：[QLinearGradient](https://doc-qt-io.translate.goog/qt-6/qlineargradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QConicalGradient](https://doc-qt-io.translate.goog/qt-6/qconicalgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QRadialGradient](https://doc-qt-io.translate.goog/qt-6/qradialgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)- 所有这些都继承[QGradient](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

```
    QRadialGradient gradient(50, 50, 50, 50, 50);
    gradient.setColorAt(0, QColor::fromRgbF(0, 1, 0, 1));
    gradient.setColorAt(1, QColor::fromRgbF(0, 0, 0, 0));

    QBrush brush(gradient);
```

这[texture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#texture)() 定义当前样式为时使用的像素图[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。您可以通过在创建画笔时提供像素图或使用[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)()。

请注意，申请[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)() 使得[style](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()==[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)，无论以前的样式设置如何。另外，打电话[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)如果样式是渐变，() 不会产生任何影响。如果样式是同样的情况[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)样式，除非当前纹理是[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

这[isOpaque](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isOpaque)`true`如果画笔完全不透明，() 函数返回，否则返回 false。在以下情况下，画笔被视为不透明：

- 的 alpha 分量[color](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)() 为 255。
- 它是[texture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#texture)() 没有 alpha 通道并且不是[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。
- 中的颜色[gradient](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gradient)() 的 alpha 分量均为 255。

| ![img](.\QBrush\brush-outline.png)概要 | 要指定线条和轮廓的样式和颜色，请使用[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的[pen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)结合[Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)和[Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum):`QPainter painter(this); painter.setBrush(Qt::cyan); painter.setPen(Qt::darkCyan); painter.drawRect(0, 0, 100,100); painter.setBrush(Qt::NoBrush); painter.setPen(Qt::darkGreen); painter.drawRect(40, 40, 100, 100);`请注意，默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制形状时渲染轮廓（使用当前设置的笔）。使用[`painter.setPen(Qt::NoPen)`](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)禁用此行为。 |
| -------------------------------------- | ------------------------------------------------------------ |
|                                        |                                                              |

有关一般绘画的更多信息，请参阅[Paint System](https://doc-qt-io.translate.goog/qt-6/paintsystem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum),[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QBrush::QBrush()

使用样式构造默认的黑色画笔[Qt::NoBrush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)（即此画笔不会填充形状）。

### QBrush::QBrush([Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style*)

用给定的构造一个黑色画笔*style*。

**也可以看看**[setStyle](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()。

### QBrush::QBrush(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*, [Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style* = Qt::SolidPattern)

用给定的构造一个画笔*color*和*style*。

**也可以看看**[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)（） 和[setStyle](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()。

### QBrush::QBrush([Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum) *color*, [Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style* = Qt::SolidPattern)

用给定的构造一个画笔*color*和*style*。

**也可以看看**[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)（） 和[setStyle](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()。

### QBrush::QBrush(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

用给定的构造一个画笔*color*和存储在的自定义模式*pixmap*。

样式设置为[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。颜色仅对 QBitmap 有效。

**也可以看看**[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)（） 和[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)()。

### QBrush::QBrush([Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum) *color*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

用给定的构造一个画笔*color*和存储在的自定义模式*pixmap*。

样式设置为[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。颜色仅对 QBitmap 有效。

**也可以看看**[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)（） 和[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)()。

### QBrush::QBrush(const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

构造一个具有黑色和给定纹理设置的画笔*pixmap*。样式设置为[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。

**也可以看看**[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)()。

### QBrush::QBrush(const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*)

构造一个具有黑色和给定纹理设置的画笔*image*。样式设置为[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。

**也可以看看**[setTextureImage](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextureImage)()。

### QBrush::QBrush(const [QGradient](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*gradient*)

根据给定构造画笔*gradient*。

画笔样式设置为相应的渐变样式（或者[Qt::LinearGradientPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum),[Qt::RadialGradientPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)或者[Qt::ConicalGradientPattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)）。

### QBrush::QBrush(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*other*)

构造一个副本*other*。

### `[noexcept]`QBrush::~QBrush()

破坏画笔。

### const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QBrush::color() const

返回画笔颜色。

**也可以看看**[setColor](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setColor)()。

### const [QGradient](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QBrush::gradient() const

返回描述此画笔的渐变。

### bool QBrush::isOpaque() const

`true`如果画笔完全不透明则返回，否则返回 false。在以下情况下，画笔被视为不透明：

- 的 alpha 分量[color](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)() 为 255。
- 它是[texture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#texture)() 没有 alpha 通道并且不是[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。
- 中的颜色[gradient](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#gradient)() 的 alpha 分量均为 255。
- 它是一个扩展的径向渐变。

### void QBrush::setColor(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

将画笔颜色设置为给定的*color*。

请注意，如果样式是渐变，则调用 setColor() 不会产生任何影响。如果样式是同样的情况[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)样式，除非当前纹理是[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[color](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#color)()。

### void QBrush::setColor([Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum) *color*)

这是一个过载功能。

将画笔颜色设置为给定的*color*。

### void QBrush::setStyle([Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style*)

将画笔样式设置为*style*。

**也可以看看**[style](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()。

### void QBrush::setTexture(const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

将画笔像素图设置为*pixmap*。样式设置为[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。

当前画笔颜色仅对单色像素图有效，即[QPixmap::depth](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#depth)()==1([QBitmaps](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。

**也可以看看**[texture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#texture)()。

### void QBrush::setTextureImage(const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*)

将画笔图像设置为*image*。样式设置为[Qt::TexturePattern](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。

请注意，当前画笔颜色不会*对*单色图像产生任何影响，这与调用[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)() 与[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。如果要更改单色图像画笔的颜色，请将图像转换为[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并`QBitmap::fromImage()`设置结果[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为纹理，或更改图像颜色表中的条目。

**也可以看看**[textureImage](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textureImage)（） 和[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)()。

### void QBrush::setTransform(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*matrix*)

套*matrix*作为当前画笔上的显式变换矩阵。画笔变换矩阵合并为[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)变换矩阵以产生最终结果。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)()。

### [Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) QBrush::style() const

返回画笔样式。

**也可以看看**[setStyle](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()。

### `[noexcept]`void QBrush::swap([QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*other*)

交换画笔*other*用这把刷子。这个操作非常快并且永远不会失败。

### [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QBrush::texture() const

返回自定义画笔图案，如果未设置自定义画笔图案，则返回空像素图。

**也可以看看**[setTexture](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTexture)()。

### [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QBrush::textureImage() const

返回自定义画笔图案，如果未设置自定义画笔图案，则返回空图像。

如果纹理设置为[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它将被转换为[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[setTextureImage](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextureImage)()。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QBrush::transform() const

返回画笔的当前变换矩阵。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()。

### [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QBrush::operator QVariant() const

将画笔返回为[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

### bool QBrush::operator!=(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*brush*) const

`true`如果画笔与给定的不同则返回*brush*; 否则返回`false`.

如果两个画笔具有不同的样式、颜色或变换，或者根据样式具有不同的像素图或渐变，则它们是不同的。

**也可以看看**[operator==](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-eq-eq)()。

### [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &QBrush::operator=(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*brush*)

分配给定的*brush*到此*画笔并返回**对此*画笔的引用。

### `[noexcept]`[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &QBrush::operator=([QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &&*other*)

移动分配*other*对此[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)实例。

### bool QBrush::operator==(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*brush*) const

`true`如果笔刷等于给定值则返回*brush*; 否则返回`false`.

如果两个画笔具有相同的样式、颜色和变换，以及取决于样式的相同的像素图或渐变，则它们是相同的。

**也可以看看**[operator!=](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#operator-not-eq)()。

## 相关非会员

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator<<([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*stream*, const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*brush*)

写出给定的*brush*对给定的*stream*并返回对*stream*。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &operator>>([QDataStream](https://doc-qt-io.translate.goog/qt-6/qdatastream.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*stream*, [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QBrush) &*brush*)

读取给定的*brush*从给定的*stream*并返回对*stream*。

**也可以看看**[Serializing Qt Data Types](https://doc-qt-io.translate.goog/qt-6/datastreamformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。