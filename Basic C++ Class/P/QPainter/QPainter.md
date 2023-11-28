#  QPainter Class

QPainter 类在小部件和其他绘画设备上执行低级绘画。

| Header:       | #include <  QPainter>                                        |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Gui) target_link_libraries(mytarget PRIVATE Qt6::Gui) |
| qmake:        | QT += gui                                                    |
| Inherited By: | [QStylePainter](https://doc-qt-io.translate.goog/qt-6/qstylepainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- QPainter 是[绘画类](https://doc-qt-io.translate.goog/qt-6/painting.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp
- [)的一部分。

**笔记：**该类中的所有函数都是[reentrant](https://doc-qt-io.translate.goog/qt-6/threads-reentrancy.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 公共类型

| class | **[PixmapFragment](https://doc-qt-io.translate.goog/qt-6/qpainter-pixmapfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)** |
| ----- | ------------------------------------------------------------ |
| enum  | **[CompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)** { CompositionMode_SourceOver, CompositionMode_DestinationOver, CompositionMode_Clear, CompositionMode_Source, CompositionMode_Destination, …, RasterOp_SourceOrNotDestination } |
| enum  | **[PixmapFragmentHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixmapFragmentHint-enum)** { OpaqueHint } |
| flags | **[PixmapFragmentHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixmapFragmentHint-enum)** |
| enum  | **[RenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)** { Antialiasing, TextAntialiasing, SmoothPixmapTransform, VerticalSubpixelPositioning, LosslessImageRendering, NonCosmeticBrushPatterns } |
| flags | **[RenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)** |

## 公共职能

|                           | **[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPainter)**() |
| ------------------------- | ------------------------------------------------------------ |
|                           | **[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPainter-1)**(QPaintDevice **device*) |
|                           | **[~QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QPainter)**() |
| const QBrush &            | **[background](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)**() const |
| Qt::BGMode                | **[backgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundMode)**() const |
| bool                      | **[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)**(QPaintDevice **device*) |
| void                      | **[beginNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginNativePainting)**() |
| QRectF                    | **[boundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)**(const QRectF &*rectangle*, int *flags*, const QString &*text*) |
| QRect                     | **[boundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect-1)**(const QRect &*rectangle*, int *flags*, const QString &*text*) |
| QRect                     | **[boundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect-2)**(int *x*, int *y*, int *w*, int *h*, int *flags*, const QString &*text*) |
| QRectF                    | **[boundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect-3)**(const QRectF &*rectangle*, const QString &*text*, const QTextOption &*option* = QTextOption()) |
| const QBrush &            | **[brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)**() const |
| QPoint                    | **[brushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brushOrigin)**() const |
| QRectF                    | **[clipBoundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipBoundingRect)**() const |
| QPainterPath              | **[clipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipPath)**() const |
| QRegion                   | **[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)**() const |
| QTransform                | **[combinedTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#combinedTransform)**() const |
| QPainter::CompositionMode | **[compositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#compositionMode)**() const |
| QPaintDevice *            | **[device](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)**() const |
| const QTransform &        | **[deviceTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deviceTransform)**() const |
| void                      | **[drawArc](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawArc)**(const QRectF &*rectangle*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawArc](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawArc-1)**(const QRect &*rectangle*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawArc](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawArc-2)**(int *x*, int *y*, int *width*, int *height*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawChord](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawChord)**(const QRectF &*rectangle*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawChord](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawChord-1)**(int *x*, int *y*, int *width*, int *height*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawChord](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawChord-2)**(const QRect &*rectangle*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawConvexPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawConvexPolygon)**(const QPointF **points*, int *pointCount*) |
| void                      | **[drawConvexPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawConvexPolygon-1)**(const QPolygonF &*polygon*) |
| void                      | **[drawConvexPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawConvexPolygon-2)**(const QPoint **points*, int *pointCount*) |
| void                      | **[drawConvexPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawConvexPolygon-3)**(const QPolygon &*polygon*) |
| void                      | **[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse)**(const QRectF &*rectangle*) |
| void                      | **[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse-1)**(const QRect &*rectangle*) |
| void                      | **[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse-2)**(int *x*, int *y*, int *width*, int *height*) |
| void                      | **[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse-3)**(const QPointF &*center*, qreal *rx*, qreal *ry*) |
| void                      | **[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse-4)**(const QPoint &*center*, int *rx*, int *ry*) |
| void                      | **[drawGlyphRun](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawGlyphRun)**(const QPointF &*position*, const QGlyphRun &*glyphs*) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage)**(const QRectF &*target*, const QImage &*image*, const QRectF &*source*, Qt::ImageConversionFlags *flags* = Qt::AutoColor) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-1)**(const QRect &*target*, const QImage &*image*, const QRect &*source*, Qt::ImageConversionFlags *flags* = Qt::AutoColor) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-2)**(const QPointF &*point*, const QImage &*image*, const QRectF &*source*, Qt::ImageConversionFlags *flags* = Qt::AutoColor) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-3)**(const QPoint &*point*, const QImage &*image*, const QRect &*source*, Qt::ImageConversionFlags *flags* = Qt::AutoColor) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-4)**(const QRectF &*rectangle*, const QImage &*image*) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-5)**(const QRect &*rectangle*, const QImage &*image*) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-6)**(const QPointF &*point*, const QImage &*image*) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-7)**(const QPoint &*point*, const QImage &*image*) |
| void                      | **[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage-8)**(int *x*, int *y*, const QImage &*image*, int *sx* = 0, int *sy* = 0, int *sw* = -1, int *sh* = -1, Qt::ImageConversionFlags *flags* = Qt::AutoColor) |
| void                      | **[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine)**(const QLineF &*line*) |
| void                      | **[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine-1)**(const QLine &*line*) |
| void                      | **[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine-2)**(int *x1*, int *y1*, int *x2*, int *y2*) |
| void                      | **[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine-3)**(const QPoint &*p1*, const QPoint &*p2*) |
| void                      | **[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine-4)**(const QPointF &*p1*, const QPointF &*p2*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines)**(const QLineF **lines*, int *lineCount*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-1)**(const QList< QLineF> &*lines*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-2)**(const QPointF **pointPairs*, int *lineCount*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-3)**(const QList< QPointF> &*pointPairs*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-4)**(const QLine **lines*, int *lineCount*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-5)**(const QList< QLine> &*lines*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-6)**(const QPoint **pointPairs*, int *lineCount*) |
| void                      | **[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines-7)**(const QList< QPoint> &*pointPairs*) |
| void                      | **[drawPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPath)**(const QPainterPath &*path*) |
| void                      | **[drawPicture](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPicture)**(const QPointF &*point*, const QPicture &*picture*) |
| void                      | **[drawPicture](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPicture-1)**(int *x*, int *y*, const QPicture &*picture*) |
| void                      | **[drawPicture](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPicture-2)**(const QPoint &*point*, const QPicture &*picture*) |
| void                      | **[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie)**(const QRectF &*rectangle*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie-1)**(int *x*, int *y*, int *width*, int *height*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie-2)**(const QRect &*rectangle*, int *startAngle*, int *spanAngle*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)**(const QRectF &*target*, const QPixmap &*pixmap*, const QRectF &*source*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-1)**(const QRect &*target*, const QPixmap &*pixmap*, const QRect &*source*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-2)**(int *x*, int *y*, int *w*, int *h*, const QPixmap &*pixmap*, int *sx*, int *sy*, int *sw*, int *sh*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-3)**(int *x*, int *y*, const QPixmap &*pixmap*, int *sx*, int *sy*, int *sw*, int *sh*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-4)**(const QPointF &*point*, const QPixmap &*pixmap*, const QRectF &*source*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-5)**(const QPoint &*point*, const QPixmap &*pixmap*, const QRect &*source*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-6)**(const QPointF &*point*, const QPixmap &*pixmap*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-7)**(const QPoint &*point*, const QPixmap &*pixmap*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-8)**(int *x*, int *y*, const QPixmap &*pixmap*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-9)**(const QRect &*rectangle*, const QPixmap &*pixmap*) |
| void                      | **[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap-10)**(int *x*, int *y*, int *width*, int *height*, const QPixmap &*pixmap*) |
| void                      | **[drawPixmapFragments](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmapFragments)**(const QPainter::PixmapFragment **fragments*, int *fragmentCount*, const QPixmap &*pixmap*, QPainter::PixmapFragmentHints *hints* = PixmapFragmentHints()) |
| void                      | **[drawPoint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoint)**(const QPointF &*position*) |
| void                      | **[drawPoint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoint-1)**(const QPoint &*position*) |
| void                      | **[drawPoint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoint-2)**(int *x*, int *y*) |
| void                      | **[drawPoints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoints)**(const QPointF **points*, int *pointCount*) |
| void                      | **[drawPoints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoints-1)**(const QPolygonF &*points*) |
| void                      | **[drawPoints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoints-2)**(const QPoint **points*, int *pointCount*) |
| void                      | **[drawPoints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoints-3)**(const QPolygon &*points*) |
| void                      | **[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)**(const QPointF **points*, int *pointCount*, Qt::FillRule *fillRule* = Qt::OddEvenFill) |
| void                      | **[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon-1)**(const QPolygonF &*points*, Qt::FillRule *fillRule* = Qt::OddEvenFill) |
| void                      | **[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon-2)**(const QPoint **points*, int *pointCount*, Qt::FillRule *fillRule* = Qt::OddEvenFill) |
| void                      | **[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon-3)**(const QPolygon &*points*, Qt::FillRule *fillRule* = Qt::OddEvenFill) |
| void                      | **[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline)**(const QPointF **points*, int *pointCount*) |
| void                      | **[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline-1)**(const QPolygonF &*points*) |
| void                      | **[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline-2)**(const QPoint **points*, int *pointCount*) |
| void                      | **[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline-3)**(const QPolygon &*points*) |
| void                      | **[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect)**(const QRectF &*rectangle*) |
| void                      | **[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect-1)**(int *x*, int *y*, int *width*, int *height*) |
| void                      | **[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect-2)**(const QRect &*rectangle*) |
| void                      | **[drawRects](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRects)**(const QRectF **rectangles*, int *rectCount*) |
| void                      | **[drawRects](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRects-1)**(const QList< QRectF> &*rectangles*) |
| void                      | **[drawRects](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRects-2)**(const QRect **rectangles*, int *rectCount*) |
| void                      | **[drawRects](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRects-3)**(const QList< QRect> &*rectangles*) |
| void                      | **[drawRoundedRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRoundedRect)**(const QRectF &*rect*, qreal *xRadius*, qreal *yRadius*, Qt::SizeMode *mode* = Qt::AbsoluteSize) |
| void                      | **[drawRoundedRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRoundedRect-1)**(int *x*, int *y*, int *w*, int *h*, qreal *xRadius*, qreal *yRadius*, Qt::SizeMode *mode* = Qt::AbsoluteSize) |
| void                      | **[drawRoundedRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRoundedRect-2)**(const QRect &*rect*, qreal *xRadius*, qreal *yRadius*, Qt::SizeMode *mode* = Qt::AbsoluteSize) |
| void                      | **[drawStaticText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawStaticText)**(const QPointF &*topLeftPosition*, const QStaticText &*staticText*) |
| void                      | **[drawStaticText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawStaticText-1)**(const QPoint &*topLeftPosition*, const QStaticText &*staticText*) |
| void                      | **[drawStaticText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawStaticText-2)**(int *left*, int *top*, const QStaticText &*staticText*) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)**(const QPointF &*position*, const QString &*text*) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText-1)**(const QPoint &*position*, const QString &*text*) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText-2)**(int *x*, int *y*, const QString &*text*) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText-3)**(const QRectF &*rectangle*, int *flags*, const QString &*text*, QRectF **boundingRect* = nullptr) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText-4)**(const QRect &*rectangle*, int *flags*, const QString &*text*, QRect **boundingRect* = nullptr) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText-5)**(int *x*, int *y*, int *width*, int *height*, int *flags*, const QString &*text*, QRect **boundingRect* = nullptr) |
| void                      | **[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText-6)**(const QRectF &*rectangle*, const QString &*text*, const QTextOption &*option* = QTextOption()) |
| void                      | **[drawTiledPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawTiledPixmap)**(const QRectF &*rectangle*, const QPixmap &*pixmap*, const QPointF &*position* = QPointF()) |
| void                      | **[drawTiledPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawTiledPixmap-1)**(int *x*, int *y*, int *width*, int *height*, const QPixmap &*pixmap*, int *sx* = 0, int *sy* = 0) |
| void                      | **[drawTiledPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawTiledPixmap-2)**(const QRect &*rectangle*, const QPixmap &*pixmap*, const QPoint &*position* = QPoint()) |
| bool                      | **[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)**() |
| void                      | **[endNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endNativePainting)**() |
| void                      | **[eraseRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eraseRect)**(const QRectF &*rectangle*) |
| void                      | **[eraseRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eraseRect-1)**(int *x*, int *y*, int *width*, int *height*) |
| void                      | **[eraseRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eraseRect-2)**(const QRect &*rectangle*) |
| void                      | **[fillPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillPath)**(const QPainterPath &*path*, const QBrush &*brush*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect)**(const QRectF &*rectangle*, const QBrush &*brush*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-1)**(int *x*, int *y*, int *width*, int *height*, const QBrush &*brush*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-2)**(const QRect &*rectangle*, const QBrush &*brush*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-3)**(const QRectF &*rectangle*, const QColor &*color*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-4)**(int *x*, int *y*, int *width*, int *height*, const QColor &*color*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-5)**(const QRect &*rectangle*, const QColor &*color*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-6)**(int *x*, int *y*, int *width*, int *height*, Qt::GlobalColor *color*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-7)**(const QRect &*rectangle*, Qt::GlobalColor *color*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-8)**(const QRectF &*rectangle*, Qt::GlobalColor *color*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-9)**(int *x*, int *y*, int *width*, int *height*, Qt::BrushStyle *style*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-10)**(const QRect &*rectangle*, Qt::BrushStyle *style*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-11)**(const QRectF &*rectangle*, Qt::BrushStyle *style*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-12)**(int *x*, int *y*, int *width*, int *height*, QGradient::Preset *preset*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-13)**(const QRect &*rectangle*, QGradient::Preset *preset*) |
| void                      | **[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect-14)**(const QRectF &*rectangle*, QGradient::Preset *preset*) |
| const QFont &             | **[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)**() const |
| QFontInfo                 | **[fontInfo](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontInfo)**() const |
| QFontMetrics              | **[fontMetrics](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontMetrics)**() const |
| bool                      | **[hasClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasClipping)**() const |
| bool                      | **[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)**() const |
| Qt::LayoutDirection       | **[layoutDirection](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection)**() const |
| qreal                     | **[opacity](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opacity)**() const |
| QPaintEngine *            | **[paintEngine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEngine)**() const |
| const QPen &              | **[pen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pen)**() const |
| QPainter::RenderHints     | **[renderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints)**() const |
| void                      | **[resetTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetTransform)**() |
| void                      | **[restore](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restore)**() |
| void                      | **[rotate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)**(qreal *angle*) |
| void                      | **[save](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#save)**() |
| void                      | **[scale](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)**(qreal *sx*, qreal *sy*) |
| void                      | **[setBackground](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)**(const QBrush &*brush*) |
| void                      | **[setBackgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackgroundMode)**(Qt::BGMode *mode*) |
| void                      | **[setBrush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)**(const QBrush &*brush*) |
| void                      | **[setBrush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush-1)**(Qt::BrushStyle *style*) |
| void                      | **[setBrushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrushOrigin)**(const QPointF &*position*) |
| void                      | **[setBrushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrushOrigin-1)**(int *x*, int *y*) |
| void                      | **[setBrushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrushOrigin-2)**(const QPoint &*position*) |
| void                      | **[setClipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipPath)**(const QPainterPath &*path*, Qt::ClipOperation *operation* = Qt::ReplaceClip) |
| void                      | **[setClipRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRect)**(const QRectF &*rectangle*, Qt::ClipOperation *operation* = Qt::ReplaceClip) |
| void                      | **[setClipRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRect-1)**(const QRect &*rectangle*, Qt::ClipOperation *operation* = Qt::ReplaceClip) |
| void                      | **[setClipRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRect-2)**(int *x*, int *y*, int *width*, int *height*, Qt::ClipOperation *operation* = Qt::ReplaceClip) |
| void                      | **[setClipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRegion)**(const QRegion &*region*, Qt::ClipOperation *operation* = Qt::ReplaceClip) |
| void                      | **[setClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipping)**(bool *enable*) |
| void                      | **[setCompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCompositionMode)**(QPainter::CompositionMode *mode*) |
| void                      | **[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)**(const QFont &*font*) |
| void                      | **[setLayoutDirection](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayoutDirection)**(Qt::LayoutDirection *direction*) |
| void                      | **[setOpacity](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)**(qreal *opacity*) |
| void                      | **[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)**(const QPen &*pen*) |
| void                      | **[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen-1)**(const QColor &*color*) |
| void                      | **[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen-2)**(Qt::PenStyle *style*) |
| void                      | **[setRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHint)**(QPainter::RenderHint *hint*, bool *on* = true) |
| void                      | **[setRenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHints)**(QPainter::RenderHints *hints*, bool *on* = true) |
| void                      | **[setTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)**(const QTransform &*transform*, bool *combine* = false) |
| void                      | **[setViewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewTransformEnabled)**(bool *enable*) |
| void                      | **[setViewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)**(const QRect &*rectangle*) |
| void                      | **[setViewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport-1)**(int *x*, int *y*, int *width*, int *height*) |
| void                      | **[setWindow](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindow)**(const QRect &*rectangle*) |
| void                      | **[setWindow](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindow-1)**(int *x*, int *y*, int *width*, int *height*) |
| void                      | **[setWorldMatrixEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldMatrixEnabled)**(bool *enable*) |
| void                      | **[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)**(const QTransform &*matrix*, bool *combine* = false) |
| void                      | **[shear](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)**(qreal *sh*, qreal *sv*) |
| void                      | **[strokePath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#strokePath)**(const QPainterPath &*path*, const QPen &*pen*) |
| bool                      | **[testRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testRenderHint)**(QPainter::RenderHint *hint*) const |
| const QTransform &        | **[transform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)**() const |
| void                      | **[translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)**(const QPointF &*offset*) |
| void                      | **[translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate-1)**(const QPoint &*offset*) |
| void                      | **[translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate-2)**(qreal *dx*, qreal *dy*) |
| bool                      | **[viewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewTransformEnabled)**() const |
| QRect                     | **[viewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)**() const |
| QRect                     | **[window](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)**() const |
| bool                      | **[worldMatrixEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldMatrixEnabled)**() const |
| const QTransform &        | **[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)**() const |

## 详细说明

QPainter 提供高度优化的功能来完成大多数绘图 GUI 程序所需的功能。它可以绘制从简单线条到复杂形状（如饼图和和弦）的所有内容。它还可以绘制对齐的文本和像素图。通常，它绘制“自然”坐标系，但它也可以进行视图和世界变换。QPainter 可以对任何继承了 QPainter 的对象进行操作[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)班级。

QPainter 的常见用途是在小部件的绘制事件中：构造和自定义（例如设置笔或画笔）画家。然后画。记得在绘制后销毁 QPainter 对象。例如：

```
void SimpleExampleWidget::paintEvent(QPaintEvent *)
{
    QPainter painter(this);
    painter.setPen(Qt::blue);
    painter.setFont(QFont("Arial", 30));
    painter.drawText(rect(), Qt::AlignCenter, "Qt");
}
```

QPainter 的核心功能是绘图，但该类还提供了几个函数，允许您自定义 QPainter 的设置及其渲染质量，以及其他启用剪切的函数。此外，您可以通过指定画家的构图模式来控制不同形状合并在一起的方式。

这[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)() 函数指示画家是否处于活动状态。画家被激活[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)() 函数和带有 a 的构造函数[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)争论。这[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)() 函数和析构函数将其停用。

与[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QPaintEngine](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，QPainter 构成了 Qt 绘图系统的基础。QPainter是用于执行绘图操作的类。[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代表可以使用 QPainter 进行绘画的设备。[QPaintEngine](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供画家用来在不同类型的设备上绘图的界面。如果画家是活跃的，[device](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#device)() 返回画家进行绘画的绘画设备，并且[paintEngine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEngine)() 返回画家当前正在操作的绘画引擎。欲了解更多信息，请参阅[Paint System](https://doc-qt-io.translate.goog/qt-6/paintsystem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

有时需要让别人在不寻常的东西上作画[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。QPainter 支持静态函数 setRedirected() 来执行此操作。

**警告：**当paintdevice是一个widget时，QPainter只能在paintEvent()函数内部或由paintEvent()调用的函数中使用。

### 设置

您可以自定义多种设置，使 QPainter 根据您的喜好进行绘制：

- [font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)() 是用于绘制文本的字体。如果画家[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()，您可以使用以下命令检索有关当前设置的字体及其规格的信息[fontInfo](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontInfo)（） 和[fontMetrics](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontMetrics)() 函数分别。
- [brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)() 定义用于填充形状的颜色或图案。
- [pen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pen)() 定义用于绘制线条或边界的颜色或点画。
- [backgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundMode)() 定义是否存在[background](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)() 或不是，即它是[Qt::OpaqueMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)或者[Qt::TransparentMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)。
- [background](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)() 仅适用于[backgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundMode)（） 是[Qt::OpaqueMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)和[pen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pen)() 是点画。在这种情况下，它描述了点画中背景像素的颜色。
- [brushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brushOrigin)() 定义平铺画笔的原点，通常是小部件背景的原点。
- [viewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)(),[window](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)(),[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)() 组成画家的坐标变换系统。欲了解更多信息，请参阅[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)部分和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档。
- [hasClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasClipping)() 告诉画家是否完全剪辑。（绘画设备也会剪辑。）如果画家剪辑，它会剪辑到[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)()。
- [layoutDirection](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection)() 定义了画家绘制文本时使用的布局方向。
- [worldMatrixEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldMatrixEnabled)() 指示是否启用世界变换。
- [viewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewTransformEnabled)() 指示是否启用视图转换。

请注意，其中一些设置反映了某些绘画设备中的设置，例如[QWidget::font](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font-prop)()。这[QPainter::begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)() 函数（或等效的 QPainter 构造函数）从绘图设备复制这些属性。

您可以随时通过调用来保存 QPainter 的状态[save](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#save)() 函数将所有可用设置保存在内部堆栈上。这[restore](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restore)() 函数将它们弹出。

### 绘画

QPainter 提供了绘制大多数图元的函数：[drawPoint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoint)(),[drawPoints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPoints)(),[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine)(),[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect)(),[drawRoundedRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRoundedRect)(),[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse)(),[drawArc](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawArc)(),[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie)(),[drawChord](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawChord)(),[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline)(),[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)(),[drawConvexPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawConvexPolygon)() 和drawCubicBezier()。这两个便利功能，[drawRects](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRects)（） 和[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines)()，在给定数组中绘制给定数量的矩形或直线[QRects](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QLines](https://doc-qt-io.translate.goog/qt-6/qline.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用当前的笔和画笔。

QPainter 类还提供了[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect)() 函数填充给定的[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，给定[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，以及[eraseRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eraseRect)() 函数擦除给定矩形内的区域。

所有这些函数都有整数和浮点版本。

| ![img](.\QPainter\qpainter-basicdrawing.png) | **基本绘图示例**这[Basic Drawing](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-basicdrawing-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该示例展示了如何使用 QPainter 类以各种样式显示基本图形基元。 |
| -------------------------------------------- | ------------------------------------------------------------ |
|                                              |                                                              |

如果您需要绘制复杂的形状，尤其是需要重复绘制，请考虑创建一个[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并使用绘制它[drawPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPath)()。

| **画家路径示例**这[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类提供了绘画操作的容器，使得图形形状能够被构造和重用。这[Painter Paths](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-painterpaths-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)示例展示了如何使用画家路径来构建复杂的渲染形状。 | ![img](.\QPainter\qpainter-painterpaths.png) |
| ------------------------------------------------------------ | -------------------------------------------- |
|                                                              |                                              |

QPainter 还提供[fillPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillPath)() 函数填充给定的[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与给定的[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，以及[strokePath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#strokePath)() 函数绘制给定路径的轮廓（即描边路径）。

另请参阅[Vector Deformation](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-deform-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)示例展示了如何使用高级矢量技术来绘制文本[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 这[Gradients](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-gradients-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该示例显示了 Qt 中可用的不同类型的渐变，以及[Path Stroking](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-pathstroke-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该示例显示了 Qt 的内置破折号模式，并显示了如何使用自定义模式来扩展可用模式的范围。

| [Vector Deformation](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-deform-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) | [Gradients](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-gradients-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) | [Path Stroking](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-pathstroke-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|      ![img](.\QPainter\qpainter-vectordeformation.png)       |          ![img](.\QPainter\qpainter-gradients.png)           |         ![img](.\QPainter\qpainter-pathstroking.png)         |

文本绘制是使用完成的[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)()。当你需要细粒度定位时，[boundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 告诉你给定的位置[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)() 命令将绘制。

### 绘制像素图和图像

有绘制像素图/图像的函数，即[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)(),[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage)（） 和[drawTiledPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawTiledPixmap)()。两个都[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)（） 和[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage)() 产生相同的结果，除了[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)() 在屏幕上显示速度更快，而[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage)() 可能会更快[QPrinter](https://doc-qt-io.translate.goog/qt-6/qprinter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或其他设备。

有一个[drawPicture](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPicture)() 函数绘制整个内容[QPicture](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。这[drawPicture](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPicture)() 函数是唯一一个忽略所有画家设置的函数[QPicture](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)有自己的设置。

#### 绘制高分辨率版本的像素图和图像

像素图的高分辨率版本的*设备像素比值*大于 1（请参阅[QImageReader](https://doc-qt-io.translate.goog/qt-6/qimagereader.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QPixmap::devicePixelRatio](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#devicePixelRatio)())。是否与标的资产的价值相匹配[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，它被直接绘制到设备上，没有应用额外的转换。

例如，绘制一个[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)*64x64 像素大小，设备像素比为 2 到高 DPI 屏幕上，该屏幕的设备像素比也为 2。请注意，像素图在用户空间*中实际上是 32x32 像素。Qt 中根据像素图大小计算布局几何形状的代码路径将使用此大小。这样做的最终效果是像素图显示为高 DPI 像素图而不是大像素图。

### 渲染质量

为了使用 QPainter 获得最佳渲染结果，您应该使用与平台无关的[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为油漆装置；即使用[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将确保结果在任何平台上具有相同的像素表示。

QPainter 类还提供了一种通过其控制渲染质量的方法[RenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)枚举和对浮点精度的支持：用于绘制基元的所有函数都有浮点版本。这些通常与[QPainter::Antialiasing](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)渲染提示。

| ![img](.\QPainter\qpainter-concentriccircles.png) | **同心圆示例**这[Concentric Circles](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-concentriccircles-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该示例显示了在绘制自定义小部件时使用浮点精度和抗锯齿功能可以获得改进的渲染质量。该应用程序的主窗口显示了几个使用精度和抗锯齿的各种组合绘制的小部件。 |
| ------------------------------------------------- | ------------------------------------------------------------ |
|                                                   |                                                              |

这[RenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)enum 指定 QPainter 的标志，任何给定引擎可能会或可能不会遵守这些标志。[QPainter::Antialiasing](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)指示引擎应该在可能的情况下对图元的边缘进行抗锯齿处理，[QPainter::TextAntialiasing](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)指示引擎应在可能的情况下对文本进行抗锯齿处理，并且[QPainter::SmoothPixmapTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)指示引擎应使用平滑的像素图变换算法。

这[renderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints)() 函数返回一个标志，该标志指定为此画家设置的渲染提示。使用[setRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHint)()函数设置或清除当前设置[RenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)。

### 坐标变换

通常，QPainter 在设备自己的坐标系（通常是像素）上运行，但 QPainter 对坐标变换有很好的支持。

|                  不                   | [rotate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)() | [scale](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)() | [translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)() |
| :-----------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![img](.\QPainter\qpainter-clock.png) |           ![img](.\QPainter\qpainter-rotation.png)           |            ![img](.\QPainter\qpainter-scale.png)             |         ![img](.\QPainter\qpainter-translation.png)          |

最常用的变换是缩放、旋转、平移和剪切。使用[scale](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)() 函数按给定的偏移量缩放坐标系，[rotate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)() 函数将其顺时针旋转并且[translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)() 对其进行平移（即向点添加给定的偏移量）。您还可以使用以下命令围绕原点扭转坐标系[shear](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)（） 功能。请参阅[Affine Transformations](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-affine-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)剪切坐标系可视化的示例。

另请参阅[Transformations](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-transformations-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该示例显示了变换如何影响 QPainter 渲染图形基元的方式。特别是它显示了转换顺序如何影响结果。

| **仿射变换示例**这[Affine Transformations](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-affine-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)该示例显示了 Qt 在绘画操作上执行仿射变换的能力。该演示还允许用户试验转换操作并立即查看结果。 | ![img](.\QPainter\qpainter-affinetransformations.png) |
| ------------------------------------------------------------ | ----------------------------------------------------- |
|                                                              |                                                       |

所有的转换操作都在转换上进行[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()。矩阵将平面上的一个点变换为另一个点。有关变换矩阵的更多信息，请参阅[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)文档。

这[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)()函数可以替换或添加到当前设置[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()。这[resetTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetTransform)() 函数重置使用所做的任何转换[translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)(),[scale](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[shear](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)(),[setViewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)（） 和[setWindow](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindow)（） 功能。这[deviceTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deviceTransform)() 返回从逻辑坐标转换为平台相关绘画设备的设备坐标的矩阵。仅当在平台相关句柄上使用平台绘画命令时才需要后一个函数，并且平台本身不进行转换。

当使用 QPainter 绘图时，我们使用逻辑坐标指定点，然后将其转换为绘图设备的物理坐标。逻辑坐标到物理坐标的映射由 QPainter 处理[combinedTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#combinedTransform)() 的组合[viewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)（） 和[window](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)（） 和[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()。这[viewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()表示指定任意矩形的物理坐标，[window](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)() 在逻辑坐标中描述相同的矩形，并且[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()与变换矩阵相同。

也可以看看[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

### 剪裁

QPainter 可以将任何绘图操作剪切到矩形、区域或矢量路径。当前剪辑可使用以下功能获得[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)（） 和[clipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipPath)()。路径或区域是首选（更快）取决于底层[paintEngine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEngine)()。例如，[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘画引擎更喜欢路径，而 X11 绘画引擎更喜欢区域。设置剪辑是在画家的逻辑坐标中完成的。

QPainter 剪裁后，绘画设备也可能会剪裁。例如，大多数小部件会剪掉子小部件使用的像素，并且大多数打印机会剪掉纸张边缘附近的区域。这个额外的裁剪不会通过返回值反映出来[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)（） 或者[hasClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasClipping)()。

### 作曲模式



QPainter 提供了[CompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)定义数字图像合成的 Porter-Duff 规则的枚举；它描述了一种将一幅图像（源）中的像素与另一幅图像（目标）中的像素组合起来的模型。

两种最常见的组合形式是[Source](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)和[SourceOver](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)。[Source](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)用于将不透明对象绘制到绘画设备上。在此模式下，源中的每个像素都会替换目标中相应的像素。在[SourceOver](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)合成模式下，源对象是透明的并绘制在目标之上。

请注意，合成变换是按像素进行的。因此，使用图形图元本身及其边界矩形之间存在差异：边界矩形包含 alpha == 0 的像素（即图元周围的像素）。这些像素将覆盖其他图像的像素，从而有效地清除这些像素，而基元仅覆盖其自己的区域。

| ![img](.\QPainter\qpainter-compositiondemo.png) | **合成模式示例**这[Composition Modes](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-composition-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)示例位于 Qt 的示例目录中，允许您尝试各种组合模式并立即查看结果。 |
| ----------------------------------------------- | ------------------------------------------------------------ |
|                                                 |                                                              |

### 局限性



如果您使用 Qt 基于光栅的绘制引擎的坐标，请务必注意，虽然可以使用大于 +/- 2 15 的坐标，但不保证显示使用此范围之外的坐标执行的任何绘制；绘图可能会被剪裁。这是由于使用`short int`在实现中使用了 。

当处理弯曲形状时，Qt 的描边生成的轮廓只是一个近似值。在大多数情况下，不可能用另一个贝塞尔曲线段来表示一个贝塞尔曲线段的轮廓，因此Qt通过使用几条较小的曲线来近似曲线轮廓。出于性能原因，Qt 用于这些轮廓的曲线数量是有限的，因此当使用大笔宽度或比例时，轮廓误差会增加。要生成误差较小的轮廓，可以使用[QPainterPathStroker](https://doc-qt-io.translate.goog/qt-6/qpainterpathstroker.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类，它具有 setCurveThreshold 成员函数，让用户指定误差容限。另一种解决方法是先将路径转换为多边形，然后绘制多边形。

### 表现

QPainter 是一个丰富的框架，允许开发人员执行各种各样的图形操作，例如渐变、合成模式和矢量图形。QPainter 可以跨各种不同的硬件和软件堆栈来完成此操作。当然，硬件和软件的底层组合对性能有一定的影响，并且确保每个单独的操作与构图模式、画笔、剪切、变换等的所有各种组合快速结合几乎是一项不可能完成的任务，因为排列的数量。作为折衷方案，我们选择了 QPainter API 和后端的一个子集，在给定的硬件和软件组合下，保证其性能与我们能够明智地获得的性能一样好。

我们关注的高性能引擎后端是：

- Raster - 该后端以纯软件实现所有渲染，并且始终用于渲染到 QImages 中。为了获得最佳性能，仅使用格式类型[QImage::Format_ARGB32_Premultiplied](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Format-enum),[QImage::Format_RGB32](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Format-enum)或者[QImage::Format_RGB16](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Format-enum)。任何其他格式，包括[QImage::Format_ARGB32](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Format-enum)，性能明显较差。该引擎默认用于[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。
- OpenGL 2.0 (ES) - 该后端是硬件加速图形的主要后端。它可以运行在支持OpenGL 2.0或OpenGL/ES 2.0规范的台式机和嵌入式设备上。这包括过去几年生产的大多数图形芯片。可以通过使用 QPainter 来启用该引擎[QOpenGLWidget](https://doc-qt-io.translate.goog/qt-6/qopenglwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

这些操作是：

- 简单的变换，即平移和缩放，加上 0、90、180、270 度旋转。
- `drawPixmap()`结合简单变换和非平滑变换模式的不透明度（`QPainter::SmoothPixmapTransform`不作为渲染提示启用）。
- 矩形填充纯色、双色线性渐变和简单变换。
- 具有简单变换和相交剪辑的矩形剪辑。
- 作曲模式`QPainter::CompositionMode_Source`和[QPainter::CompositionMode_SourceOver](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)。
- 圆角矩形填充使用纯色和双色线性渐变填充。
- 3x3 修补像素图，via[qDrawBorderPixmap](https://doc-qt-io.translate.goog/qt-6/qdrawutil-h.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qDrawBorderPixmap-1)。

此列表指示了在性能至关重要的应用程序中可以安全使用哪些功能。对于某些设置，其他操作可能也很快，但在广泛使用它们之前，建议在软件最终运行的系统上进行基准测试和验证。在某些情况下，可以使用昂贵的操作，例如当结果缓存在[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QPaintEngine](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Qt SVG](https://doc-qt-io.translate.goog/qt-6/qtsvg-index.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[Basic Drawing Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-basicdrawing-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Drawing Utility Functions](https://doc-qt-io.translate.goog/qt-6/qdrawutil-h.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### enum QPainter::CompositionMode

定义数字图像合成支持的模式。合成模式用于指定如何将一个图像（源）中的像素与另一图像（目标）中的像素合并。

请注意，按位光栅操作模式（以 RasterOp 前缀表示）仅在 X11 和光栅绘制引擎中原生支持。这意味着在 Mac 上使用这些模式的唯一方法是通过[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。具有 Alpha 分量的笔和画笔*不*支持RasterOp 表示的混合模式。另外，打开[QPainter::Antialiasing](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)渲染提示将有效禁用 RasterOp 模式。

![img](.\QPainter\qpainter-compositionmode1.png)

![img](.\QPainter\qpainter-compositionmode2.png)

最常见的类型是 SourceOver（通常称为 alpha 混合），其中源像素混合在目标像素之上，源像素的 alpha 分量定义像素的半透明度。

多种合成模式需要源图像或目标图像中的 Alpha 通道才能产生效果。为了获得最佳性能，图像格式[Format_ARGB32_Premultiplied](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Format-enum)是优选的。

设置合成模式后，它适用于所有绘画操作符、笔、画笔、渐变和像素图/图像绘制。

| 持续的                                          | 价值 | 描述                                                         |
| ----------------------------------------------- | ---- | ------------------------------------------------------------ |
| `QPainter::CompositionMode_SourceOver`          | `0`  | 这是默认模式。源的 Alpha 用于混合目标顶部的像素。            |
| `QPainter::CompositionMode_DestinationOver`     | `1`  | 目标的 Alpha 用于将其混合到源像素之上。此模式是 CompositionMode_SourceOver 的逆模式。 |
| `QPainter::CompositionMode_Clear`               | `2`  | 目标中的像素被清除（设置为完全透明），与源无关。             |
| `QPainter::CompositionMode_Source`              | `3`  | 输出是源像素。（这意味着基本的复制操作，并且当源像素不透明时与 SourceOver 相同）。 |
| `QPainter::CompositionMode_Destination`         | `4`  | 输出是目标像素。这意味着混合没有效果。此模式是 CompositionMode_Source 的逆模式。 |
| `QPainter::CompositionMode_SourceIn`            | `5`  | 输出是源，其中 alpha 减去目标的 alpha。                      |
| `QPainter::CompositionMode_DestinationIn`       | `6`  | 输出是目标，其中 alpha 减去源的 alpha。此模式是 CompositionMode_SourceIn 的逆模式。 |
| `QPainter::CompositionMode_SourceOut`           | `7`  | 输出是源，其中 alpha 按目标的倒数减少。                      |
| `QPainter::CompositionMode_DestinationOut`      | `8`  | 输出是目标，其中 alpha 按源的倒数减少。此模式是 CompositionMode_SourceOut 的逆模式。 |
| `QPainter::CompositionMode_SourceAtop`          | `9`  | 源像素混合在目标之上，源像素的 alpha 值减去目标像素的 alpha 值。 |
| `QPainter::CompositionMode_DestinationAtop`     | `10` | 目标像素混合在源之上，目标像素的 Alpha 值会减少目标像素的 Alpha 值。此模式与 CompositionMode_SourceAtop 相反。 |
| `QPainter::CompositionMode_Xor`                 | `11` | 源（其 alpha 按目标 alpha 的倒数减少）与目标（其 alpha 按源 alpha 的倒数减少）合并。CompositionMode_Xor 与按位异或不同。 |
| `QPainter::CompositionMode_Plus`                | `12` | 源像素和目标像素的 Alpha 和颜色都相加。                      |
| `QPainter::CompositionMode_Multiply`            | `13` | 输出是源颜色乘以目标颜色。将一种颜色与白色相乘不会改变颜色，而将一种颜色与黑色相乘则产生黑色。 |
| `QPainter::CompositionMode_Screen`              | `14` | 源颜色和目标颜色被反转然后相乘。用白色筛选颜色会产生白色，而用黑色筛选颜色则保持颜色不变。 |
| `QPainter::CompositionMode_Overlay`             | `15` | 根据目标颜色将颜色相乘或屏蔽。目标颜色与源颜色混合以反映目标的亮度或暗度。 |
| `QPainter::CompositionMode_Darken`              | `16` | 选择源颜色和目标颜色中较暗的一个。                           |
| `QPainter::CompositionMode_Lighten`             | `17` | 选择源颜色和目标颜色中较浅的一个。                           |
| `QPainter::CompositionMode_ColorDodge`          | `18` | 目标颜色变亮以反映源颜色。黑色源颜色使目标颜色保持不变。     |
| `QPainter::CompositionMode_ColorBurn`           | `19` | 目标颜色变暗以反映源颜色。白色源颜色使目标颜色保持不变。     |
| `QPainter::CompositionMode_HardLight`           | `20` | 根据源颜色将颜色相乘或屏蔽。光源颜色将使目标颜色变亮，而深色源颜色将使目标颜色变暗。 |
| `QPainter::CompositionMode_SoftLight`           | `21` | 根据源颜色使颜色变暗或变亮。与 CompositionMode_HardLight 类似。 |
| `QPainter::CompositionMode_Difference`          | `22` | 从较浅的颜色中减去较深的颜色。使用白色绘制会反转目标颜色，而使用黑色绘制则使目标颜色保持不变。 |
| `QPainter::CompositionMode_Exclusion`           | `23` | 与 CompositionMode_Difference 类似，但对比度较低。使用白色绘制会反转目标颜色，而使用黑色绘制则使目标颜色保持不变。 |
| `QPainter::RasterOp_SourceOrDestination`        | `24` | 对源像素和目标像素执行按位或运算 (src OR dst)。              |
| `QPainter::RasterOp_SourceAndDestination`       | `25` | 对源像素和目标像素执行按位 AND 运算 (src AND dst)。          |
| `QPainter::RasterOp_SourceXorDestination`       | `26` | 对源像素和目标像素执行按位 XOR 运算 (src XOR dst)。          |
| `QPainter::RasterOp_NotSourceAndNotDestination` | `27` | 对源像素和目标像素执行按位 NOR 运算（(NOT src) AND (NOT dst)）。 |
| `QPainter::RasterOp_NotSourceOrNotDestination`  | `28` | 对源像素和目标像素执行按位 NAND 运算（(NOT src) OR (NOT dst)）。 |
| `QPainter::RasterOp_NotSourceXorDestination`    | `29` | 执行按位运算，其中源像素被反转，然后与目标进行异或（(NOT src) XOR dst）。 |
| `QPainter::RasterOp_NotSource`                  | `30` | 执行按位运算，其中源像素被反转（不是 src）。                 |
| `QPainter::RasterOp_NotSourceAndDestination`    | `31` | 执行按位运算，其中源被反转，然后与目标进行 AND 运算（(NOT src) AND dst）。 |
| `QPainter::RasterOp_SourceAndNotDestination`    | `32` | 执行按位运算，其中源与反转的目标像素进行“与”运算（src AND（NOT dst））。 |
| `QPainter::RasterOp_NotSourceOrDestination`     | `33` | 执行按位运算，其中源被反转，然后与目标进行“或”运算（(NOT src) OR dst）。 |
| `QPainter::RasterOp_ClearDestination`           | `35` | 目标中的像素将被清除（设置为 0），与源无关。                 |
| `QPainter::RasterOp_SetDestination`             | `36` | 目标中的像素独立于源而设置（设置为 1）。                     |
| `QPainter::RasterOp_NotDestination`             | `37` | 执行按位运算，其中目标像素被反转（不是 dst）。               |
| `QPainter::RasterOp_SourceOrNotDestination`     | `34` | 执行按位运算，其中源与反转的目标像素进行“或”运算（src OR（NOT dst））。 |

**也可以看看**[compositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#compositionMode)(),[setCompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCompositionMode)(),[Composition Modes](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#composition-modes)， 和[Image Composition Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-imagecomposition-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### 枚举 QPainter:: PixmapFragmentHint 标志 QPainter:: PixmapFragmentHints

| 持续的                 | 价值   | 描述                                                         |
| ---------------------- | ------ | ------------------------------------------------------------ |
| `QPainter::OpaqueHint` | `0x01` | 指示要绘制的像素图片段是不透明的。不透明片段的绘制速度可能会更快。 |

[PixmapFragmentHints 类型是QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < PixmapFragmentHint>的 typedef 。它存储 PixmapFragmentHint 值的 OR 组合。

**也可以看看**[QPainter::drawPixmapFragments](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmapFragments)（） 和[QPainter::PixmapFragment](https://doc-qt-io.translate.goog/qt-6/qpainter-pixmapfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### 枚举 QPainter:: RenderHint 标志 QPainter:: RenderHints

Renderhints 用于指定标志[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)任何给定的引擎可能会或可能不会遵守。

| 持续的                                  | 价值   | 描述                                                         |
| --------------------------------------- | ------ | ------------------------------------------------------------ |
| `QPainter::Antialiasing`                | `0x01` | 指示引擎应在可能的情况下对基元的边缘进行抗锯齿处理。         |
| `QPainter::TextAntialiasing`            | `0x02` | 指示引擎应在可能的情况下对文本进行抗锯齿处理。要强制禁用文本的抗锯齿功能，请不要使用此提示。相反，设置[QFont::NoAntialias](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#StyleStrategy-enum)关于你的字体风格策略。 |
| `QPainter::SmoothPixmapTransform`       | `0x04` | 指示引擎应该使用平滑的像素图变换算法（例如双线性）而不是最近邻。 |
| `QPainter::VerticalSubpixelPositioning` | `0x08` | 如果字体引擎支持，允许文本垂直和水平放置在像素分数处。目前，当提示首选项为时，Freetype 在所有平台上都支持此功能[QFont::PreferNoHinting](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HintingPreference-enum)，以及 macOS 上。对于大多数用例，这不会提高视觉质量，但可能会增加内存消耗并在一定程度上降低文本渲染性能。因此，除非用例需要，否则不建议启用此功能。其中一种用例可能是将字形与其他视觉基元对齐。该值是在 Qt 6.1 中添加的。 |
| `QPainter::LosslessImageRendering`      | `0x40` | 尽可能使用无损图像渲染。目前，此提示仅在以下情况下使用：[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于通过以下方式输出 PDF 文件[QPrinter](https://doc-qt-io.translate.goog/qt-6/qprinter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)或者[QPdfWriter](https://doc-qt-io.translate.goog/qt-6/qpdfwriter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 在哪里[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage)()/[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)() 调用将使用无损压缩算法而不是有损 JPEG 压缩对图像进行编码。该值是在 Qt 5.13 中添加的。 |
| `QPainter::NonCosmeticBrushPatterns`    | `0x80` | 当使用具有预定义图案样式之一的画笔进行绘画时，也要变换图案以及正在绘画的对象。默认情况下将图案视为装饰，以便图案像素将直接映射到设备像素，独立于任何活动转换。该值是在 Qt 6.4 中添加的。 |

RenderHints 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < RenderHint> 的类型定义。它存储 RenderHint 值的 OR 组合。

**也可以看看**[renderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints)(),[setRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHint)(),[Rendering Quality](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rendering-quality)， 和[Concentric Circles Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-concentriccircles-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员函数文档

### QPainter::QPainter()

构建一个画家。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### `[explicit]`QPainter::QPainter([QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device*)

构造一个开始绘制油漆的画家*device*立即地。

这个构造函数对于短命的画家来说很方便，例如在[QWidget::paintEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)() 并且只能使用一次。构造函数调用[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)() 为你和 QPainter 析构函数自动调用[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

这是一个使用的示例[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)():

```
void MyWidget::paintEvent(QPaintEvent *)
{
    QPainter p;
    p.begin(this);
    p.drawLine(drawingCode);        // drawing code
    p.end();
}
```

使用此构造函数的相同示例：

```
void MyWidget::paintEvent(QPaintEvent *)
{
    QPainter p(this);
    p.drawLine(drawingCode);        // drawing code
}
```

由于当画家的初始化失败时构造函数无法提供反馈，因此您应该使用[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)() 在外部设备（例如打印机）上绘画。

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)()。

### `[noexcept]`QPainter::~QPainter()

毁了画家。

### const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::background() const

返回当前的背景画笔。

**也可以看看**[setBackground](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [Qt::BGMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum) QPainter::backgroundMode() const

返回当前的后台模式。

**也可以看看**[setBackgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackgroundMode)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### bool QPainter::begin([QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **device*)

开始涂漆*device*如果成功则返回`true`；否则返回`false`.

请注意，所有画家设置（[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)(),[setBrush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)() 等）在调用 begin() 时重置为默认值。

可能发生的错误是严重的问题，例如：

```
painter->begin(0); // impossible - paint device cannot be 0

QPixmap image(0, 0);
painter->begin(&image); // impossible - image.isNull() == true;

painter->begin(myWidget);
painter2->begin(myWidget); // impossible - only one painter at a time
```

请注意，大多数时候，您可以使用其中一个构造函数来代替 begin()，并且[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)() 在销毁时自动完成。

**警告：**一个喷漆设备一次只能由一名喷漆师喷漆。

**警告：**在[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)与格式[QImage::Format_Indexed8](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Format-enum)不支持。

**也可以看看**[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)（） 和[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QPainter)()。

### void QPainter::beginNativePainting()

刷新绘画管道并为用户直接向底层图形上下文发出命令做好准备。随后必须调用[endNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endNativePainting)()。

请注意，只有底层绘制引擎更改的状态才会重置为其各自的默认状态。我们重置的状态可能会因版本而异。当前在 OpenGL 2 引擎中重置以下状态：

- 混合已禁用
- 深度、模板和剪刀测试被禁用
- 活动纹理单元重置为 0
- 深度掩模、深度函数和清晰深度重置为其默认值
- 模板掩码、模板操作和模板功能重置为其默认值
- 当前颜色重置为纯白色

例如，如果用户在 beginNativePaint()/ 内更改了 OpenGL 多边形模式[endNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endNativePainting)() 块，它不会被重置为默认状态[endNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endNativePainting)()。下面是一个示例，显示了画家命令和原始 OpenGL 命令的混合：

```
QPainter painter(this);
painter.fillRect(0, 0, 128, 128, Qt::green);
painter.beginNativePainting();

glEnable(GL_SCISSOR_TEST);
glScissor(0, 0, 64, 64);

glClearColor(1, 0, 0, 1);
glClear(GL_COLOR_BUFFER_BIT);

glDisable(GL_SCISSOR_TEST);

painter.endNativePainting();
```

**也可以看看**[endNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#endNativePainting)()。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::boundingRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *flags*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

返回的边界矩形*text*正如在给定的范围内绘制时出现的那样*rectangle*与指定的*flags*使用当前设置的[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)(); 即该函数告诉您在哪里[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)() 函数在给定相同参数时将绘制。

如果*text*不符合给定的范围*rectangle*使用指定的*flags*，该函数返回所需的矩形。

这*flags*参数是以下标志的按位或：

- [Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignHCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignBottom](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignVCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::TextSingleLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextExpandTabs](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextShowMnemonic](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextWordWrap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextIncludeTrailingSpaces](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)

如果设置了多个水平对齐标志或多个垂直对齐标志，则结果对齐是未定义的。

**也可以看看**[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)(),[Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)， 和[Qt::TextFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::boundingRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *flags*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

这是一个过载功能。

返回的边界矩形*text*正如在给定的范围内绘制时出现的那样*rectangle*与指定的*flags*使用当前设置的[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)()。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::boundingRect(int *x*, int *y*, int *w*, int *h*, int *flags*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

这是一个过载功能。

返回给定的边界矩形*text*正如在从点 ( 开始的矩形内绘制时出现的那样*x*,*y*) 与宽度*w*和身高*h*。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::boundingRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, const [QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option* = QTextOption())

这是一个过载功能。

而不是将标志指定为按位或[Qt::AlignmentFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)和[Qt::TextFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)，这个重载函数需要一个*option*争论。这[QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)类提供一般富文本属性的描述。

**也可以看看**[QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::brush() const

返回画家当前的画笔。

**也可以看看**[QPainter::setBrush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::brushOrigin() const

返回当前设置的画笔原点。

**也可以看看**[setBrushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrushOrigin)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::clipBoundingRect() const

如果有剪辑，则返回当前剪辑的边界矩形；否则返回一个空矩形。请注意，剪辑区域以逻辑坐标给出。

不保证边界矩形是紧密的。

**也可以看看**[setClipRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRect)(),[setClipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipPath)（）， 和[setClipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRegion)()。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::clipPath() const

返回逻辑坐标中的当前剪辑路径。

**警告：**[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不显式存储组合剪辑，因为这是由底层处理的[QPaintEngine](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，因此根据需要重新创建路径并将其转换为当前的逻辑坐标系。这可能是一项昂贵的操作。

**也可以看看**[setClipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipPath)(),[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)（）， 和[setClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipping)()。

### [QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::clipRegion() const

返回当前设置的剪辑区域。请注意，剪辑区域以逻辑坐标给出。

**警告：**[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不显式存储组合剪辑，因为这是由底层处理的[QPaintEngine](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，因此根据需要重新创建路径并将其转换为当前的逻辑坐标系。这可能是一项昂贵的操作。

**也可以看看**[setClipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRegion)(),[clipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipPath)（）， 和[setClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipping)()。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::combinedTransform() const

返回结合当前窗口/视口和世界变换的变换矩阵。

**也可以看看**[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)(),[setWindow](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindow)（）， 和[setViewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)()。

### [QPainter::CompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum) QPainter::compositionMode() const

返回当前的合成模式。

**也可以看看**[CompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum)和[setCompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCompositionMode)()。

### [QPaintDevice](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPainter::device() const

返回该画家当前正在其上绘画的绘画设备，或者`nullptr`如果该画家未处于活动状态。

**也可以看看**[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::deviceTransform() const

返回从逻辑坐标转换为平台相关绘画设备的设备坐标的矩阵。

该功能*仅*当在平台相关句柄上使用平台绘画命令时才需要[Qt::HANDLE](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#HANDLE-typedef)），并且平台本身不进行转换。

这[QPaintEngine::PaintEngineFeature](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PaintEngineFeature-enum)可以查询枚举以确定平台是否执行转换。

**也可以看看**[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)（） 和[QPaintEngine::hasFeature](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFeature)()。

### void QPainter::drawArc(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *startAngle*, int *spanAngle*)

绘制由给定定义的圆弧*rectangle*,*startAngle*和*spanAngle*。

这*startAngle*和*spanAngle*必须以 1/16 度数指定，即整圆等于 5760 (16 * 360)。角度的正值表示逆时针方向，而负值表示顺时针方向。0 度位于 3 点钟位置。

| ![img](.\QPainter\qpainter-arc.png) | `QRectF rectangle(10.0, 20.0, 80.0, 60.0); int startAngle = 30 * 16; int spanAngle = 120 * 16; QPainter painter(this); painter.drawArc(rectangle, startAngle, spanAngle);` |
| ----------------------------------- | ------------------------------------------------------------ |
|                                     |                                                              |

**也可以看看**[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie)(),[drawChord](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawChord)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawArc(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *startAngle*, int *spanAngle*)

这是一个过载功能。

绘制由给定定义的圆弧*rectangle*,*startAngle*和*spanAngle*。

### void QPainter::drawArc(int *x*, int *y*, int *width*, int *height*, int *startAngle*, int *spanAngle*)

这是一个过载功能。

绘制由从 ( 开始的矩形定义的圆弧*x*,*y*）与指定的*width*和*height*，以及给定的*startAngle*和*spanAngle*。

### void QPainter::drawChord(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *startAngle*, int *spanAngle*)

绘制给定定义的和弦*rectangle*,*startAngle*和*spanAngle*。和弦充满当前[brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)()。

startAngle 和spanAngle 必须以1/16 度为单位指定，即整圆等于5760 (16 * 360)。角度的正值表示逆时针方向，而负值表示顺时针方向。0 度位于 3 点钟位置。

| ![img](.\QPainter\qpainter-chord.png) | `QRectF rectangle(10.0, 20.0, 80.0, 60.0); int startAngle = 30 * 16; int spanAngle = 120 * 16; QPainter painter(this); painter.drawChord(rect, startAngle, spanAngle);` |
| ------------------------------------- | ------------------------------------------------------------ |
|                                       |                                                              |

**也可以看看**[drawArc](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawArc)(),[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawChord(int *x*, int *y*, int *width*, int *height*, int *startAngle*, int *spanAngle*)

这是一个过载功能。

绘制由从 ( 开始的矩形定义的弦)*x*,*y*）与指定的*width*和*height*，以及给定的*startAngle*和*spanAngle*。

### void QPainter::drawChord(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *startAngle*, int *spanAngle*)

这是一个过载功能。

绘制给定定义的和弦*rectangle*,*startAngle*和*spanAngle*。

### void QPainter::drawConvexPolygon(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*)

绘制由第一个定义的凸多边形*pointCount*数组中的点*points*使用当前笔。

| ![img](.\QPainter\qpainter-polygon.png) | `static const QPointF points[4] = {    QPointF(10.0, 80.0),    QPointF(20.0, 10.0),    QPointF(80.0, 30.0),    QPointF(90.0, 70.0) }; QPainter painter(this); painter.drawConvexPolygon(points, 4);` |
| --------------------------------------- | ------------------------------------------------------------ |
|                                         |                                                              |

第一个点隐式连接到最后一个点，并且多边形用当前的填充[brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)()。如果提供的多边形不是凸多边形，即它至少包含一个大于 180 度的角度，则结果不确定。

在某些平台（例如 X11）上，drawConvexPolygon() 函数可能比[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)（） 功能。

**也可以看看**[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)(),[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawConvexPolygon(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*)

这是一个过载功能。

绘制由下式定义的凸多边形*polygon*使用当前的笔和画笔。

### void QPainter::drawConvexPolygon(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*)

这是一个过载功能。

绘制由第一个定义的凸多边形*pointCount*数组中的点*points*使用当前笔。

### void QPainter::drawConvexPolygon(const [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*)

这是一个过载功能。

绘制由下式定义的凸多边形*polygon*使用当前的笔和画笔。

### void QPainter::drawEllipse(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

绘制由给定定义的椭圆*rectangle*。

填充椭圆的大小为*rectangle*。[size](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)()。描边椭圆的大小为*rectangle*。[size](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#size)() 加上画笔宽度。

| ![img](.\QPainter\qpainter-ellipse.png) | `QRectF rectangle(10.0, 20.0, 80.0, 60.0); QPainter painter(this); painter.drawEllipse(rectangle);` |
| --------------------------------------- | ------------------------------------------------------------ |
|                                         |                                                              |

**也可以看看**[drawPie](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPie)（） 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawEllipse(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

这是一个过载功能。

绘制由给定定义的椭圆*rectangle*。

### void QPainter::drawEllipse(int *x*, int *y*, int *width*, int *height*)

这是一个过载功能。

绘制由开始于 ( 的矩形定义的椭圆*x*,*y*）与给定的*width*和*height*。

### void QPainter::drawEllipse(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*center*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *rx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *ry*)

这是一个过载功能。

绘制椭圆，位置为*center*有半径*rx*和*ry*。

### void QPainter::drawEllipse(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*center*, int *rx*, int *ry*)

这是一个过载功能。

绘制椭圆，位置为*center*有半径*rx*和*ry*。

### void QPainter::drawGlyphRun(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*, const [QGlyphRun](https://doc-qt-io.translate.goog/qt-6/qglyphrun.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*glyphs*)

绘制由 表示的字形*glyphs*在*position*。这*position*给出字形字符串的基线边缘. 将从所选字体中检索字形*glyphs*并在由位置给出的偏移处*glyphs*。

**也可以看看**[QGlyphRun::setRawFont](https://doc-qt-io.translate.goog/qt-6/qglyphrun.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRawFont)(),[QGlyphRun::setPositions](https://doc-qt-io.translate.goog/qt-6/qglyphrun.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPositions)（）， 和[QGlyphRun::setGlyphIndexes](https://doc-qt-io.translate.goog/qt-6/qglyphrun.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGlyphIndexes)()。

### void QPainter::drawImage(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*target*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*, [Qt::ImageConversionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ImageConversionFlag-enum) *flags* = Qt::AutoColor)

绘制矩形部分*source*给定的*image*进入*target*绘制设备中的矩形。

**注意：**如果图像和矩形大小不一致，则图像会缩放以适合矩形。

**注：**参见[Drawing High Resolution Versions of Pixmaps and Images](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawing-high-resolution-versions-of-pixmaps-and-images)关于这是如何影响的[QImage::devicePixelRatio](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#devicePixelRatio)()。

如果需要修改图像以适应较低分辨率的结果（例如从 32 位转换为 8 位），请使用*flags*指定您希望这种情况如何发生。

```
QRectF target(10.0, 20.0, 80.0, 60.0); QRectF source(0.0, 0.0, 70.0, 40.0); QImage image(":/images/myImage.png"); QPainter painter(this); painter.drawImage(target, image, source);
```

**也可以看看**[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)（） 和[QImage::devicePixelRatio](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#devicePixelRatio)()。

### void QPainter::drawImage(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*target*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*, const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*, [Qt::ImageConversionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ImageConversionFlag-enum) *flags* = Qt::AutoColor)

这是一个过载功能。

绘制矩形部分*source*给定的*image*进入*target*绘制设备中的矩形。

**注意：**如果图像和矩形大小不一致，则图像会缩放以适合矩形。

### void QPainter::drawImage(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*, [Qt::ImageConversionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ImageConversionFlag-enum) *flags* = Qt::AutoColor)

这是一个过载功能。

绘制矩形部分*source*给定的*image*其原点为给定的*point*。

### void QPainter::drawImage(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*, const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*, [Qt::ImageConversionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ImageConversionFlag-enum) *flags* = Qt::AutoColor)

这是一个过载功能。

绘制矩形部分*source*给定的*image*其原点为给定的*point*。

### void QPainter::drawImage(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*)

这是一个过载功能。

绘制给定的*image*进入给定的*rectangle*。

**注意：**如果图像和矩形大小不一致，则图像会缩放以适合矩形。

### void QPainter::drawImage(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*)

这是一个过载功能。

绘制给定的*image*进入给定的*rectangle*。

**注意：**如果图像和矩形大小不一致，则图像会缩放以适合矩形。

### void QPainter::drawImage(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*)

这是一个过载功能。

绘制给定的*image*在给定的*point*。

### void QPainter::drawImage(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*)

这是一个过载功能。

绘制给定的*image*在给定的*point*。

### void QPainter::drawImage(int *x*, int *y*, const [QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*image*, int *sx* = 0, int *sy* = 0, int *sw* = -1, int *sh* = -1, [Qt::ImageConversionFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ImageConversionFlag-enum) *flags* = Qt::AutoColor)

这是一个过载功能。

在 (*x*,*y*）通过复制一部分*image*进入油漆装置。

（*x*,*y*) 指定绘图设备中要绘制的左上角点。（*sx*,*sy*) 指定左上角点*image*那是要绘制的。默认值为 (0, 0)。

（*sw*,*sh*) 指定要绘制的图像的大小。默认值 (0, 0)（和负数）表示一直到图像的右下角。

### void QPainter::drawLine(const [QLineF](https://doc-qt-io.translate.goog/qt-6/qlinef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*line*)

绘制一条由以下定义的线*line*。

| ![img](.\QPainter\qpainter-line.png) | `QLineF line(10.0, 80.0, 90.0, 20.0); QPainter painter(this); painter.drawLine(line);` |
| ------------------------------------ | ------------------------------------------------------------ |
|                                      |                                                              |

**也可以看看**[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines)(),[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawLine(const [QLine](https://doc-qt-io.translate.goog/qt-6/qline.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*line*)

这是一个过载功能。

绘制一条由以下定义的线*line*。

### void QPainter::drawLine(int *x1*, int *y1*, int *x2*, int *y2*)

这是一个过载功能。

从 (*x1*,*y1*） 到 （*x2*,*y2*）。

### void QPainter::drawLine(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*p1*, const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*p2*)

这是一个过载功能。

画一条线从*p1*到*p2*。

### void QPainter::drawLine(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*p1*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*p2*)

这是一个过载功能。

画一条线从*p1*到*p2*。

### void QPainter::drawLines(const [QLineF](https://doc-qt-io.translate.goog/qt-6/qlinef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **lines*, int *lineCount*)

画出第一个*lineCount*数组中的行*lines*使用当前笔。

**也可以看看**[drawLine](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLine)（） 和[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline)()。

### void QPainter::drawLines(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QLineF](https://doc-qt-io.translate.goog/qt-6/qlinef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*lines*)

这是一个过载功能。

绘制由列表定义的线集*lines*使用当前的笔和画笔。

### void QPainter::drawLines(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **pointPairs*, int *lineCount*)

这是一个过载功能。

画出第一个*lineCount*数组中的行*pointPairs*使用当前笔。这些线被指定为点对，因此条目数*pointPairs*必须至少*lineCount** 2.

### void QPainter::drawLines(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*pointPairs*)

这是一个过载功能。

为向量中的每对点绘制一条线*pointPairs*使用当前笔。如果数组中有奇数个点，则最后一个点将被忽略。

### void QPainter::drawLines(const [QLine](https://doc-qt-io.translate.goog/qt-6/qline.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **lines*, int *lineCount*)

这是一个过载功能。

画出第一个*lineCount*数组中的行*lines*使用当前笔。

### void QPainter::drawLines(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QLine](https://doc-qt-io.translate.goog/qt-6/qline.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*lines*)

这是一个过载功能。

绘制由列表定义的线集*lines*使用当前的笔和画笔。

### void QPainter::drawLines(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **pointPairs*, int *lineCount*)

这是一个过载功能。

画出第一个*lineCount*数组中的行*pointPairs*使用当前笔。

### void QPainter::drawLines(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*pointPairs*)

这是一个过载功能。

为向量中的每对点绘制一条线*pointPairs*使用当前笔。

### void QPainter::drawPath(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*)

绘制给定的画家*path*使用当前笔进行轮廓绘制，使用当前画笔进行填充。

| ![img](.\QPainter\qpainter-path.png) | `QPainterPath path; path.moveTo(20, 80); path.lineTo(20, 30); path.cubicTo(80, 0, 50, 50, 80, 80); QPainter painter(this); painter.drawPath(path);` |
| ------------------------------------ | ------------------------------------------------------------ |
|                                      |                                                              |

**也可以看看**[the Painter Paths example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-painterpaths-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[the Vector Deformation example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-deform-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawPicture(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QPicture](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*picture*)

重播给定的*picture*在给定的*point*。

这[QPicture](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)class 是一个记录和重放的绘画设备[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)命令。图片以独立于平台的格式将画家命令序列化到 IO 设备。可以在小部件或像素图上绘制的所有内容也可以存储在图片中。

这个函数的作用与[QPicture::play](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#play)() 当调用时*point*=[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)(0, 0)。

**注意：**此函数保留画家的状态。

```
QPicture picture; QPointF point(10.0, 20.0); picture.load("drawing.pic"); QPainter painter(this); painter.drawPicture(0, 0, picture);
```

**也可以看看**[QPicture::play](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#play)()。

### void QPainter::drawPicture(int *x*, int *y*, const [QPicture](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*picture*)

这是一个过载功能。

绘制给定的*picture*在点 (*x*,*y*）。

### void QPainter::drawPicture(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QPicture](https://doc-qt-io.translate.goog/qt-6/qpicture.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*picture*)

这是一个过载功能。

重播给定的*picture*在给定的*point*。

### void QPainter::drawPie(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *startAngle*, int *spanAngle*)

绘制由给定定义的饼图*rectangle*,*startAngle*和*spanAngle*。

馅饼充满了当前[brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)()。

startAngle 和spanAngle 必须以1/16 度为单位指定，即整圆等于5760 (16 * 360)。角度的正值表示逆时针方向，而负值表示顺时针方向。0 度位于 3 点钟位置。

| ![img](.\QPainter\qpainter-pie.png) | `QRectF rectangle(10.0, 20.0, 80.0, 60.0); int startAngle = 30 * 16; int spanAngle = 120 * 16; QPainter painter(this); painter.drawPie(rectangle, startAngle, spanAngle);` |
| ----------------------------------- | ------------------------------------------------------------ |
|                                     |                                                              |

**也可以看看**[drawEllipse](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawEllipse)(),[drawChord](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawChord)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawPie(int *x*, int *y*, int *width*, int *height*, int *startAngle*, int *spanAngle*)

这是一个过载功能。

绘制由开始于 ( 的矩形定义的饼图*x*,*y*）与指定的*width*和*height*，以及给定的*startAngle*和*spanAngle*。

### void QPainter::drawPie(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *startAngle*, int *spanAngle*)

这是一个过载功能。

绘制由给定定义的饼图*rectangle*,*startAngle*和和*spanAngle*。

### void QPainter::drawPixmap(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*target*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*)

绘制矩形部分*source*给定的*pixmap*进入给定的*target*在油漆装置中。

**注意：**如果像素图和矩形大小不一致，则像素图会缩放以适合矩形。

**注：**参见[Drawing High Resolution Versions of Pixmaps and Images](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawing-high-resolution-versions-of-pixmaps-and-images)关于这是如何影响的[QPixmap::devicePixelRatio](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#devicePixelRatio)()。

```
QRectF target(10.0, 20.0, 80.0, 60.0); QRectF source(0.0, 0.0, 70.0, 40.0); QPixmap pixmap(":myPixmap.png"); QPainter painter(this); painter.drawPixmap(target, pixmap, source);
```

如果*pixmap*是一个[QBitmap](https://doc-qt-io.translate.goog/qt-6/qbitmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)它是用笔颜色“设置”的位绘制的。如果[backgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundMode)是[Qt::OpaqueMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)，使用背景画笔的颜色绘制“未设置”位；如果[backgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundMode)是[Qt::TransparentMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)，“未设置”位是透明的。不支持绘制具有渐变或纹理颜色的位图。

**也可以看看**[drawImage](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawImage)（） 和[QPixmap::devicePixelRatio](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#devicePixelRatio)()。

### void QPainter::drawPixmap(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*target*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*)

这是一个过载功能。

绘制矩形部分*source*给定的*pixmap*进入给定的*target*在油漆装置中。

**注意：**如果像素图和矩形大小不一致，则像素图会缩放以适合矩形。

### void QPainter::drawPixmap(int *x*, int *y*, int *w*, int *h*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, int *sx*, int *sy*, int *sw*, int *sh*)

这是一个过载功能。

以原点 (*sx*,*sy*）， 宽度*sw*和身高*sh*，给定的*pixmap*，在点 (*x*,*y*），宽度为*w*和高度*h*。如果 sw 或 sh 等于 0，则使用像素图的宽度/高度并通过偏移量 sx/sy 进行调整；

### void QPainter::drawPixmap(int *x*, int *y*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, int *sx*, int *sy*, int *sw*, int *sh*)

这是一个过载功能。

在 (*x*,*y*）通过复制给定的一部分*pixmap*进入油漆装置。

（*x*,*y*) 指定绘图设备中要绘制的左上角点。（*sx*,*sy*) 指定左上角点*pixmap*那是要绘制的。默认值为 (0, 0)。

（*sw*,*sh*) 指定要绘制的像素图的大小。默认值 (0, 0)（和负数）表示一直到像素图的右下角。

### void QPainter::drawPixmap(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*)

这是一个过载功能。

绘制矩形部分*source*给定的*pixmap*其原点为给定的*point*。

### void QPainter::drawPixmap(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source*)

这是一个过载功能。

绘制矩形部分*source*给定的*pixmap*其原点为给定的*point*。

### void QPainter::drawPixmap(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

这是一个过载功能。

绘制给定的*pixmap*其原点为给定的*point*。

### void QPainter::drawPixmap(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

这是一个过载功能。

绘制给定的*pixmap*其原点为给定的*point*。

### void QPainter::drawPixmap(int *x*, int *y*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

这是一个过载功能。

绘制给定的*pixmap*在位置 (*x*,*y*）。

### void QPainter::drawPixmap(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

这是一个过载功能。

绘制给定的*pixmap*进入给定的*rectangle*。

**注意：**如果像素图和矩形大小不一致，则像素图会缩放以适合矩形。

### void QPainter::drawPixmap(int *x*, int *y*, int *width*, int *height*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

这是一个过载功能。

绘制了*pixmap*进入矩形的位置 (*x*,*y*）与给定的*width*和*height*。

### void QPainter::drawPixmapFragments(const [QPainter::PixmapFragment](https://doc-qt-io.translate.goog/qt-6/qpainter-pixmapfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **fragments*, int *fragmentCount*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, [QPainter::PixmapFragmentHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixmapFragmentHint-enum) *hints* = PixmapFragmentHints())

这个函数是用来画图的*pixmap*，或一个子矩形*pixmap*，在具有不同比例、旋转和不透明度的多个位置。*fragments*是一个数组*fragmentCount*指定用于绘制每个像素图片段的参数的元素。这*hints*参数可用于传入绘图提示。

该函数可能比多次调用更快[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)()，因为后端可以优化状态变化。

**也可以看看**[QPainter::PixmapFragment](https://doc-qt-io.translate.goog/qt-6/qpainter-pixmapfragment.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QPainter::PixmapFragmentHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PixmapFragmentHint-enum)。

### void QPainter::drawPoint(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*)

在给定的位置绘制一个点*position*使用当前笔的颜色。

**也可以看看**[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawPoint(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*)

这是一个过载功能。

在给定的位置绘制一个点*position*使用当前笔的颜色。

### void QPainter::drawPoint(int *x*, int *y*)

这是一个过载功能。

在位置 (*x*,*y*）。

### void QPainter::drawPoints(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*)

画出第一个*pointCount*数组中的点*points*使用当前笔的颜色。

**也可以看看**[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawPoints(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*points*)

这是一个过载功能。

绘制向量中的点*points*。

### void QPainter::drawPoints(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*)

这是一个过载功能。

画出第一个*pointCount*数组中的点*points*使用当前笔的颜色。

### void QPainter::drawPoints(const [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*points*)

这是一个过载功能。

绘制向量中的点*points*。

### void QPainter::drawPolygon(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*, [Qt::FillRule](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum) *fillRule* = Qt::OddEvenFill)

绘制由第一个定义的多边形*pointCount*数组中的点*points*使用当前的笔和画笔。

| ![img](.\QPainter\qpainter-polygon.png) | `static const QPointF points[4] = {    QPointF(10.0, 80.0),    QPointF(20.0, 10.0),    QPointF(80.0, 30.0),    QPointF(90.0, 70.0) }; QPainter painter(this); painter.drawPolygon(points, 4);` |
| --------------------------------------- | ------------------------------------------------------------ |
|                                         |                                                              |

第一个点隐式连接到最后一个点，并且多边形用当前的填充[brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)()。

如果*fillRule*是[Qt::WindingFill](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum)，使用缠绕填充算法填充多边形。如果*fillRule*是[Qt::OddEvenFill](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum)，使用奇偶填充算法填充多边形。看[Qt::FillRule](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum)有关这些填充规则的更详细说明。

**也可以看看**[drawConvexPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawConvexPolygon)(),[drawPolyline](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolyline)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawPolygon(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*points*, [Qt::FillRule](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum) *fillRule* = Qt::OddEvenFill)

这是一个过载功能。

绘制由给定定义的多边形*points*使用填充规则*fillRule*。

### void QPainter::drawPolygon(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*, [Qt::FillRule](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum) *fillRule* = Qt::OddEvenFill)

这是一个过载功能。

绘制由第一个定义的多边形*pointCount*数组中的点*points*。

### void QPainter::drawPolygon(const [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*points*, [Qt::FillRule](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FillRule-enum) *fillRule* = Qt::OddEvenFill)

这是一个过载功能。

绘制由给定定义的多边形*points*使用填充规则*fillRule*。

### void QPainter::drawPolyline(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*)

绘制由第一个定义的折线*pointCount*点在*points*使用当前笔。

请注意，与[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)() 函数最后一个点没有*连接*到第一个点，折线也没有被填充。

```
static const QPointF points[3] = {    QPointF(10.0, 80.0),    QPointF(20.0, 10.0),    QPointF(80.0, 30.0), }; QPainter painter(this); painter.drawPolyline(points, 3);
```

**也可以看看**[drawLines](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawLines)(),[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawPolyline(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*points*)

这是一个过载功能。

绘制由给定定义的折线*points*使用当前笔。

### void QPainter::drawPolyline(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **points*, int *pointCount*)

这是一个过载功能。

绘制由第一个定义的折线*pointCount*点在*points*使用当前笔。

### void QPainter::drawPolyline(const [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*points*)

这是一个过载功能。

绘制由给定定义的折线*points*使用当前笔。

### void QPainter::drawRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

绘制电流*rectangle*用现在的笔和画笔。

填充矩形的大小为*rectangle*。尺寸（）。描边矩形的大小为*rectangle*.size() 加上画笔宽度。

| ![img](.\QPainter\qpainter-rectangle.png) | `QRectF rectangle(10.0, 20.0, 80.0, 60.0); QPainter painter(this); painter.drawRect(rectangle);` |
| ----------------------------------------- | ------------------------------------------------------------ |
|                                           |                                                              |

**也可以看看**[drawRects](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRects)(),[drawPolygon](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPolygon)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawRect(int *x*, int *y*, int *width*, int *height*)

这是一个过载功能。

绘制一个矩形，其左上角位于 (*x*,*y*）并且给定*width*和*height*。

### void QPainter::drawRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

这是一个过载功能。

绘制电流*rectangle*用现在的笔和画笔。

### void QPainter::drawRects(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **rectangles*, int *rectCount*)

画出第一个*rectCount*给定的*rectangles*使用当前的笔和画笔。

**也可以看看**[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect)()。

### void QPainter::drawRects(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*rectangles*)

这是一个过载功能。

绘制给定的*rectangles*使用当前的笔和画笔。

### void QPainter::drawRects(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **rectangles*, int *rectCount*)

这是一个过载功能。

画出第一个*rectCount*给定的*rectangles*使用当前的笔和画笔。

### void QPainter::drawRects(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)< [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*rectangles*)

这是一个过载功能。

绘制给定的*rectangles*使用当前的笔和画笔。

### void QPainter::drawRoundedRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *xRadius*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *yRadius*, [Qt::SizeMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SizeMode-enum) *mode* = Qt::AbsoluteSize)

绘制给定的矩形*rect*有圆角。

这*xRadius*和*yRadius*参数指定定义圆角矩形角的椭圆的半径。什么时候*mode*是[Qt::RelativeSize](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SizeMode-enum),*xRadius*和*yRadius*分别以矩形宽度和高度的一半的百分比指定，并且应在 0.0 到 100.0 范围内。

填充矩形的大小为 rect.size()。描边矩形的大小为 rect.size() 加上画笔宽度。

| ![img](.\QPainter\qpainter-roundrect.png) | `QRectF rectangle(10.0, 20.0, 80.0, 60.0); QPainter painter(this); painter.drawRoundedRect(rectangle, 20.0, 15.0);` |
| ----------------------------------------- | ------------------------------------------------------------ |
|                                           |                                                              |

**也可以看看**[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect)（） 和[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawRoundedRect(int *x*, int *y*, int *w*, int *h*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *xRadius*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *yRadius*, [Qt::SizeMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SizeMode-enum) *mode* = Qt::AbsoluteSize)

这是一个过载功能。

绘制给定的矩形*x*,*y*,*w*,*h*有圆角。

### void QPainter::drawRoundedRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *xRadius*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *yRadius*, [Qt::SizeMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SizeMode-enum) *mode* = Qt::AbsoluteSize)

这是一个过载功能。

绘制给定的矩形*rect*有圆角。

### void QPainter::drawStaticText(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*topLeftPosition*, const [QStaticText](https://doc-qt-io.translate.goog/qt-6/qstatictext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*staticText*)

绘制给定的*staticText*在给定的*topLeftPosition*。

将使用画家上设置的字体和转换来绘制文本。如果画家上设置的字体和/或转换与用于初始化布局的字体和/或转换不同[QStaticText](https://doc-qt-io.translate.goog/qt-6/qstatictext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，那么就必须重新计算布局。使用[QStaticText::prepare](https://doc-qt-io.translate.goog/qt-6/qstatictext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepare)() 进行初始化*staticText*以及稍后绘制的字体和转换。

如果*topLeftPosition*与何时不一样*staticText*被初始化时，或者最后一次绘制时，那么将文本翻译到新位置时会产生轻微的开销。

**注意：**如果画家的变换不是仿射的，那么*staticText*将使用常规调用来绘制[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)()，失去任何性能改进的潜力。

**注意：** y 位置用作字体的顶部。

**也可以看看**[QStaticText](https://doc-qt-io.translate.goog/qt-6/qstatictext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QPainter::drawStaticText(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*topLeftPosition*, const [QStaticText](https://doc-qt-io.translate.goog/qt-6/qstatictext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*staticText*)

这是一个过载功能。

绘制了*staticText*在*topLeftPosition*。

**注意：** y 位置用作字体的顶部。

### void QPainter::drawStaticText(int *left*, int *top*, const [QStaticText](https://doc-qt-io.translate.goog/qt-6/qstatictext.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*staticText*)

这是一个过载功能。

绘制了*staticText*在坐标处*left*和*top*。

**注意：** y 位置用作字体的顶部。

### void QPainter::drawText(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

绘制给定的*text*使用当前定义的文本方向，从给定的位置开始*position*。

此函数不处理换行符 (\n)，因为它无法将文本分成多行，并且无法显示换行符。如果您想使用换行符绘制多行文本，或者您希望文本被换行，请使用采用矩形的 QPainter::drawText() 重载。

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注意：** y 位置用作字体的基线。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)（） 和[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)()。

### void QPainter::drawText(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

这是一个过载功能。

绘制给定的*text*使用当前定义的文本方向，从给定的位置开始*position*。

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注意：** y 位置用作字体的基线。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)（） 和[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)()。

### void QPainter::drawText(int *x*, int *y*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*)

这是一个过载功能。

绘制给定的*text*在位置 (*x*,*y*），使用画家当前定义的文本方向。

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注意：** y 位置用作字体的基线。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)（） 和[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)()。

### void QPainter::drawText(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *flags*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **boundingRect* = nullptr)

这是一个过载功能。

绘制给定的*text*在提供的范围内*rectangle*。这*rectangle*随着对齐*flags*定义锚点*text*。

| ![img](.\QPainter\qpainter-text.png) | `QPainter painter(this); painter.drawText(rect, Qt::AlignCenter, tr("Qt\nProject"));` |
| ------------------------------------ | ------------------------------------------------------------ |
|                                      |                                                              |

这*boundingRect*(如果不为空) 设置为包围整个文本的边界矩形。例如，在下图中，虚线代表*boundingRect*由函数计算得出，虚线表示*rectangle*:

| ![img](.\QPainter\qpainter-text-bounds.png) | `QPainter painter(this); QFont font = painter.font(); font.setPixelSize(48); painter.setFont(font); const QRect rectangle = QRect(0, 0, 100, 50); QRect boundingRect; painter.drawText(rectangle, 0, tr("Hello"), &boundingRect); QPen pen = painter.pen(); pen.setStyle(Qt::DotLine); painter.setPen(pen); painter.drawRect(boundingRect.adjusted(0, 0, -pen.width(), -pen.width())); pen.setStyle(Qt::DashLine); painter.setPen(pen); painter.drawRect(rectangle.adjusted(0, 0, -pen.width(), -pen.width()));` |
| ------------------------------------------- | ------------------------------------------------------------ |
|                                             |                                                              |

这*flags*参数是以下标志的按位或：

- [Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignHCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignJustify](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignBottom](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignVCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::TextDontClip](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextSingleLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextExpandTabs](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextShowMnemonic](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextWordWrap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextIncludeTrailingSpaces](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注：** y 坐标*rectangle*用作字体的顶部。

**也可以看看**[Qt::AlignmentFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum),[Qt::TextFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum),[boundingRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（）， 和[layoutDirection](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection)()。

### void QPainter::drawText(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, int *flags*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **boundingRect* = nullptr)

这是一个过载功能。

绘制给定的*text*在提供的范围内*rectangle*根据指定的*flags*。

这*boundingRect*(如果不为空) 设置为包围整个文本的边界矩形。例如，在下图中，虚线代表*boundingRect*由函数计算得出，虚线表示*rectangle*:

| ![img](.\QPainter\qpainter-text-bounds.png) | `QPainter painter(this); QFont font = painter.font(); font.setPixelSize(48); painter.setFont(font); const QRect rectangle = QRect(0, 0, 100, 50); QRect boundingRect; painter.drawText(rectangle, 0, tr("Hello"), &boundingRect); QPen pen = painter.pen(); pen.setStyle(Qt::DotLine); painter.setPen(pen); painter.drawRect(boundingRect.adjusted(0, 0, -pen.width(), -pen.width())); pen.setStyle(Qt::DashLine); painter.setPen(pen); painter.drawRect(rectangle.adjusted(0, 0, -pen.width(), -pen.width()));` |
| ------------------------------------------- | ------------------------------------------------------------ |
|                                             |                                                              |

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注：** y 坐标*rectangle*用作字体的顶部。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)（） 和[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)()。

### void QPainter::drawText(int *x*, int *y*, int *width*, int *height*, int *flags*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **boundingRect* = nullptr)

这是一个过载功能。

绘制给定的*text*在以原点 (*x*,*y*),*width*和*height*。

这*boundingRect*(如果不为空) 设置为包围整个文本的边界矩形。例如，在下图中，虚线代表*boundingRect*由函数计算得出，虚线表示由下式定义的矩形*x*,*y*,*width*和*height*:

| ![img](.\QPainter\qpainter-text-bounds.png) | `QPainter painter(this); QFont font = painter.font(); font.setPixelSize(48); painter.setFont(font); const QRect rectangle = QRect(0, 0, 100, 50); QRect boundingRect; painter.drawText(rectangle, 0, tr("Hello"), &boundingRect); QPen pen = painter.pen(); pen.setStyle(Qt::DotLine); painter.setPen(pen); painter.drawRect(boundingRect.adjusted(0, 0, -pen.width(), -pen.width())); pen.setStyle(Qt::DashLine); painter.setPen(pen); painter.drawRect(rectangle.adjusted(0, 0, -pen.width(), -pen.width()));` |
| ------------------------------------------- | ------------------------------------------------------------ |
|                                             |                                                              |

这*flags*参数是以下标志的按位或：

- [Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignRight](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignHCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignJustify](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignBottom](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignVCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::AlignCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)
- [Qt::TextSingleLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextExpandTabs](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextShowMnemonic](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)
- [Qt::TextWordWrap](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum)

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注意：** y 位置用作字体的顶部。

**也可以看看**[Qt::AlignmentFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum),[Qt::TextFlag](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#TextFlag-enum),[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)（）， 和[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)()。

### void QPainter::drawText(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, const [QTextOption](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*option* = QTextOption())

这是一个过载功能。

绘制给定的*text*在里面*rectangle*指定使用*option*控制其位置、方向和方位。中给出的选项*option*覆盖那些设置[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对象本身。

默认情况下，[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制抗锯齿文本。

**注：** y 坐标*rectangle*用作字体的顶部。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)（） 和[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)()。

### void QPainter::drawTiledPixmap(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position* = QPointF())

绘制一个平铺的*pixmap*，在给定的范围内*rectangle*其原点为给定的*position*。

调用drawTiledPixmap()类似于调用[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)() 多次来用像素图填充（平铺）一个区域，但根据底层窗口系统，效率可能要高得多。

与普通 dpi 显示器相比，drawTiledPixmap() 将在高 dpi 显示器（devicePixelRatio > 1）上产生相同的视觉平铺图案。设置 devicePixelRatio*pixmap*来控制瓷砖尺寸。例如，将其设置为 2 会将图块宽度和高度减半（在 1x 和 2x 显示器上），并在 2x 显示器上产生高分辨率输出。

这*position*偏移量始终位于画家坐标系中，与显示设备的PixelRatio无关。

**也可以看看**[drawPixmap](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPixmap)()。

### void QPainter::drawTiledPixmap(int *x*, int *y*, int *width*, int *height*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, int *sx* = 0, int *sy* = 0)

这是一个过载功能。

绘制一个平铺的*pixmap*在指定的矩形内。

（*x*,*y*) 指定绘图设备中要绘制的左上角点；与给定的*width*和*height*。（*sx*,*sy*) 指定左上角点*pixmap*那是要绘制的；默认为 (0, 0)。

### void QPainter::drawTiledPixmap(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*, const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position* = QPoint())

这是一个过载功能。

绘制一个平铺的*pixmap*，在给定的范围内*rectangle*其原点为给定的*position*。

### bool QPainter::end()

结束绘画。绘画时使用的所有资源都会被释放。通常不需要调用它，因为它是由析构函数调用的。

`true`如果画家不再活跃则返回；否则返回`false`.

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### void QPainter::endNativePainting()

手动发出本机绘画命令后恢复画家。让画家在调用任何其他画家命令之前恢复它所依赖的任何本机状态。

**也可以看看**[beginNativePainting](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#beginNativePainting)()。

### void QPainter::eraseRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

擦除给定区域内的区域*rectangle*。相当于调用

```
fillRect(rectangle, background());
```

**也可以看看**[fillRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillRect)()。

### void QPainter::eraseRect(int *x*, int *y*, int *width*, int *height*)

这是一个过载功能。

擦除从 ( 开始的矩形内的区域*x*,*y*）与给定的*width*和*height*。

### void QPainter::eraseRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

这是一个过载功能。

擦除给定区域内的区域*rectangle*。

### void QPainter::fillPath(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

填充给定的*path*使用给定的*brush*。轮廓没有画出来。

或者，您可以指定一个[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代替[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 这[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数（采用[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)参数）将自动创建一个实心图案画笔。

**也可以看看**[drawPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawPath)()。

### void QPainter::fillRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

填充给定的*rectangle*与*brush*指定的。

或者，您可以指定一个[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)代替[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 这[QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)构造函数（采用[QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)参数）将自动创建一个实心图案画笔。

**也可以看看**[drawRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawRect)()。

### void QPainter::fillRect(int *x*, int *y*, int *width*, int *height*, const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

这是一个过载功能。

填充从 (*x*,*y*）与给定的*width*和*height*，使用给定的*brush*。

### void QPainter::fillRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

这是一个过载功能。

填充给定的*rectangle*与指定的*brush*。

### void QPainter::fillRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

这是一个过载功能。

填充给定的*rectangle*与*color*指定的。

### void QPainter::fillRect(int *x*, int *y*, int *width*, int *height*, const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

这是一个过载功能。

填充从 (*x*,*y*）与给定的*width*和*height*，使用给定的*color*。

### void QPainter::fillRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

这是一个过载功能。

填充给定的*rectangle*与*color*指定的。

### void QPainter::fillRect(int *x*, int *y*, int *width*, int *height*, [Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum) *color*)

这是一个过载功能。

填充从 (*x*,*y*）与给定的*width*和*height*，使用给定的*color*。

### void QPainter::fillRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum) *color*)

这是一个过载功能。

填充给定的*rectangle*与指定的*color*。

### void QPainter::fillRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [Qt::GlobalColor](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GlobalColor-enum) *color*)

这是一个过载功能。

填充给定的*rectangle*与指定的*color*。

### void QPainter::fillRect(int *x*, int *y*, int *width*, int *height*, [Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style*)

这是一个过载功能。

填充从 (*x*,*y*）与给定的*width*和*height*，使用画笔*style*指定的。

### void QPainter::fillRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style*)

这是一个过载功能。

填充给定的*rectangle*用刷子*style*指定的。

### void QPainter::fillRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style*)

这是一个过载功能。

填充给定的*rectangle*用刷子*style*指定的。

### void QPainter::fillRect(int *x*, int *y*, int *width*, int *height*, [QGradient::Preset](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Preset-enum) *preset*)

这是一个过载功能。

填充从 (*x*,*y*）与给定的*width*和*height*，使用给定的梯度*preset*。

### void QPainter::fillRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [QGradient::Preset](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Preset-enum) *preset*)

这是一个过载功能。

填充给定的*rectangle*具有指定的梯度*preset*。

### void QPainter::fillRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [QGradient::Preset](https://doc-qt-io.translate.goog/qt-6/qgradient.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Preset-enum) *preset*)

这是一个过载功能。

填充给定的*rectangle*具有指定的梯度*preset*。

### const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::font() const

返回当前设置的用于绘制文本的字体。

**也可以看看**[setFont](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)(),[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [QFontInfo](https://doc-qt-io.translate.goog/qt-6/qfontinfo.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::fontInfo() const

如果画家处于活动状态，则返回画家的字体信息。否则，返回值是未定义的。

**也可以看看**[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)(),[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [QFontMetrics](https://doc-qt-io.translate.goog/qt-6/qfontmetrics.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::fontMetrics() const

如果画家处于活动状态，则返回画家的字体规格。否则，返回值是未定义的。

**也可以看看**[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)(),[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### bool QPainter::hasClipping() const

`true`如果已设置裁剪则返回；否则返回`false`.

**也可以看看**[setClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipping)（） 和[Clipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipping)。

### bool QPainter::isActive() const

返回`true`如果[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)() 已被调用并且[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)() 尚未被调用；否则返回`false`.

**也可以看看**[begin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#begin)（） 和[QPaintDevice::paintingActive](https://doc-qt-io.translate.goog/qt-6/qpaintdevice.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintingActive)()。

### [Qt::LayoutDirection](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum) QPainter::layoutDirection() const

返回绘制器在绘制文本时使用的布局方向。

**也可以看看**[QTextOption::textDirection](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#textDirection)(),[setLayoutDirection](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setLayoutDirection)(),[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QPainter::opacity() const

返回画家的不透明度。默认值为 1。

**也可以看看**[setOpacity](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)()。

### [QPaintEngine](https://doc-qt-io.translate.goog/qt-6/qpaintengine.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QPainter::paintEngine() const

如果画家处于活动状态，则返回画家当前正在操作的绘画引擎；否则为 0。

**也可以看看**[isActive](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::pen() const

返回画家当前的笔。

**也可以看看**[setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### [QPainter::RenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum) QPainter::renderHints() const

返回一个标志，指定为此画家设置的渲染提示。

**也可以看看**[setRenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHints)(),[testRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#testRenderHint)（）， 和[Rendering Quality](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rendering-quality)。

### void QPainter::resetTransform()

重置使用所做的任何转换[translate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)(),[scale](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[shear](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)(),[setViewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)（） 和[setWindow](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindow)()。

**也可以看看**[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)。

### void QPainter::restore()

恢复当前画家状态（从堆栈中弹出保存的状态）。

**也可以看看**[save](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#save)()。

### void QPainter::rotate([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *angle*)

顺时针旋转坐标系。给定的*angle*参数以度为单位。

**也可以看看**[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)（） 和[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)。

### void QPainter::save()

保存当前画家状态（将状态推入堆栈）。save() 后面必须跟有相应的[restore](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restore)(); 这[end](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#end)() 函数展开堆栈。

**也可以看看**[restore](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#restore)()。

### void QPainter::scale([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sy*)

将坐标系缩放 (*sx*,*sy*）。

**也可以看看**[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)（） 和[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)。

### void QPainter::setBackground(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

将画家的背景画笔设置为给定的*brush*。

背景画笔是绘制不透明文本、点画线和位图时填充的画笔。背景画笔在透明背景模式（默认）下没有效果。

**也可以看看**[background](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#background)(),[setBackgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackgroundMode)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setBackgroundMode([Qt::BGMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum) *mode*)

将画家的背景模式设置为给定的*mode*

[Qt::TransparentMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)（默认）绘制点画线和文本而不设置背景像素。[Qt::OpaqueMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BGMode-enum)用当前背景颜色填充这些空间。

请注意，为了透明地绘制位图或像素图，您必须使用[QPixmap::setMask](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setMask)()。

**也可以看看**[backgroundMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundMode)(),[setBackground](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBackground)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setBrush(const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush*)

将画家的画笔设置为给定的*brush*。

画家的画笔定义了形状的填充方式。

**也可以看看**[brush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brush)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setBrush([Qt::BrushStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum) *style*)

这是一个过载功能。

将画家的画笔设置为黑色并指定*style*。

### void QPainter::setBrushOrigin(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*)

将画笔原点设置为*position*。

画笔原点指定画家画笔的 (0, 0) 坐标。

请注意，虽然[brushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brushOrigin)() 对于 Qt 3 中的小部件采用父级背景是必要的，但现在情况已不再是这样，因为 Qt 4 画家不会绘制背景，除非您通过设置小部件的[autoFillBackground](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#autoFillBackground-prop)属性为真。

**也可以看看**[brushOrigin](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#brushOrigin)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setBrushOrigin(int *x*, int *y*)

这是一个过载功能。

将画笔的原点设置为点 (*x*,*y*）。

### void QPainter::setBrushOrigin(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*)

这是一个过载功能。

将画笔的原点设置为给定的*position*。

### void QPainter::setClipPath(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, [Qt::ClipOperation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ClipOperation-enum) *operation* = Qt::ReplaceClip)

启用剪切，并将画家的剪切路径设置为给定的*path*，用夹子*operation*。

请注意，剪辑路径是在逻辑（画家）坐标中指定的。

**也可以看看**[clipPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipPath)(),[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)（）， 和[Clipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipping)。

### void QPainter::setClipRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [Qt::ClipOperation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ClipOperation-enum) *operation* = Qt::ReplaceClip)

启用剪辑，并将剪辑区域设置为给定的*rectangle*使用给定的剪辑*operation*。默认操作是替换当前剪辑矩形。

请注意，剪辑矩形是在逻辑（画家）坐标中指定的。

**也可以看看**[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)(),[setClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipping)（）， 和[Clipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipping)。

### void QPainter::setClipRect(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*, [Qt::ClipOperation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ClipOperation-enum) *operation* = Qt::ReplaceClip)

这是一个过载功能。

启用剪辑，并将剪辑区域设置为给定的*rectangle*使用给定的剪辑*operation*。

### void QPainter::setClipRect(int *x*, int *y*, int *width*, int *height*, [Qt::ClipOperation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ClipOperation-enum) *operation* = Qt::ReplaceClip)

启用剪辑，并将剪辑区域设置为从 (*x*,*y*）与给定的*width*和*height*。

### void QPainter::setClipRegion(const [QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*region*, [Qt::ClipOperation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ClipOperation-enum) *operation* = Qt::ReplaceClip)

将剪辑区域设置为给定的*region*使用指定的剪辑*operation*。默认的剪辑操作是替换当前剪辑区域。

请注意，剪辑区域以逻辑坐标给出。

**也可以看看**[clipRegion](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipRegion)(),[setClipRect](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setClipRect)（）， 和[Clipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipping)。

### void QPainter::setClipping(bool *enable*)

启用剪裁，如果*enable*为 true，或者禁用裁剪，如果*enable*是假的。

**也可以看看**[hasClipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasClipping)（） 和[Clipping](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipping)。

### void QPainter::setCompositionMode([QPainter::CompositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CompositionMode-enum) *mode*)

将合成模式设置为给定的*mode*。

**警告：**只有一个[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)操作于[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)完全支持所有合成模式。X11 支持 RasterOp 模式，如中所述[compositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#compositionMode)()。

**也可以看看**[compositionMode](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#compositionMode)()。

### void QPainter::setFont(const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font*)

将画家的字体设置为给定的*font*。

后续使用此字体[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)（） 功能。文字颜色与笔颜色相同。

如果您设置的字体不可用，Qt 会找到近似匹配的字体。[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)() 将返回您使用 setFont() 设置的内容，并且[fontInfo](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fontInfo)() 返回实际使用的字体（可能相同）。

**也可以看看**[font](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)(),[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setLayoutDirection([Qt::LayoutDirection](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum) *direction*)

将绘制器绘制文本时使用的布局方向设置为指定的*direction*。

默认为[Qt::LayoutDirectionAuto](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#LayoutDirection-enum)，这将隐式确定所绘制文本的方向。

**也可以看看**[QTextOption::setTextDirection](https://doc-qt-io.translate.goog/qt-6/qtextoption.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTextDirection)(),[layoutDirection](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#layoutDirection)(),[drawText](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawText)（）， 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setOpacity([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *opacity*)

将画家的不透明度设置为*opacity*。该值应在 0.0 到 1.0 范围内，其中 0.0 表示完全透明，1.0 表示完全不透明。

画家上设置的不透明度将单独应用于所有绘图操作。

**也可以看看**[opacity](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opacity)()。

### void QPainter::setPen(const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen*)

将画家的笔设置为给定的*pen*。

这*pen*定义如何绘制线条和轮廓，还定义文本颜色。

**也可以看看**[pen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pen)（） 和[Settings](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#settings)。

### void QPainter::setPen(const [QColor](https://doc-qt-io.translate.goog/qt-6/qcolor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*color*)

这是一个过载功能。

让画家的笔有风格[Qt::SolidLine](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum)，宽度1和指定的*color*。

### void QPainter::setPen([Qt::PenStyle](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PenStyle-enum) *style*)

这是一个过载功能。

设置画家的笔具有给定的*style*，宽度 1，黑色。

### void QPainter::setRenderHint([QPainter::RenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum) *hint*, bool *on* = true)

设置给定的渲染*hint*在画家身上如果*on*是真的; 否则清除渲染提示。

**也可以看看**[setRenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHints)(),[renderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints)（）， 和[Rendering Quality](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rendering-quality)。

### void QPainter::setRenderHints([QPainter::RenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum) *hints*, bool *on* = true)

设置给定的渲染*hints*在画家身上如果*on*是真的; 否则清除渲染提示。

**也可以看看**[setRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHint)(),[renderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints)（）， 和[Rendering Quality](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rendering-quality)。

### void QPainter::setTransform(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*transform*, bool *combine* = false)

设置世界变换矩阵。如果*combine*为真，指定的*transform*与当前矩阵组合；否则它将替换当前矩阵。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（） 和[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)()。

### void QPainter::setViewTransformEnabled(bool *enable*)

启用视图转换，如果*enable*为 true，或者禁用视图转换，如果*enable*是假的。

**也可以看看**[viewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewTransformEnabled)（） 和[Window-Viewport Conversion](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window-viewport-conversion)。

### void QPainter::setViewport(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

将画家的视口矩形设置为给定的*rectangle*，并启用视图转换。

视口矩形是视图变换的一部分。视口指定设备坐标系。它的姐妹，[window](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)()，指定逻辑坐标系。

默认视口矩形与设备的矩形相同。

**也可以看看**[viewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)(),[viewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewTransformEnabled)（）， 和[Window-Viewport Conversion](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window-viewport-conversion)。

### void QPainter::setViewport(int *x*, int *y*, int *width*, int *height*)

这是一个过载功能。

将画家的视口矩形设置为从 (*x*,*y*）与给定的*width*和*height*。

### void QPainter::setWindow(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rectangle*)

将画家的窗口设置为给定的*rectangle*，并启用视图转换。

窗口矩形是视图转换的一部分。该窗口指定逻辑坐标系。它的姐妹，[viewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()，指定设备坐标系。

默认窗口矩形与设备的矩形相同。

**也可以看看**[window](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)(),[viewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewTransformEnabled)（）， 和[Window-Viewport Conversion](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window-viewport-conversion)。

### void QPainter::setWindow(int *x*, int *y*, int *width*, int *height*)

这是一个过载功能。

将画家的窗口设置为从 (*x*,*y*）和给定的*width*和*height*。

### void QPainter::setWorldMatrixEnabled(bool *enable*)

启用转换，如果*enable*为 true，或者禁用转换，如果*enable*是假的。世界变换矩阵没有改变。

**也可以看看**[worldMatrixEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldMatrixEnabled)(),[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)（）， 和[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)。

### void QPainter::setWorldTransform(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*matrix*, bool *combine* = false)

设置世界变换矩阵。如果*combine*为真，指定的*matrix*与当前矩阵组合；否则它将替换当前矩阵。

**也可以看看**[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)(),[transform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[setTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()。

### void QPainter::shear([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sh*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sv*)

通过 ( 剪切坐标系*sh*,*sv*）。

**也可以看看**[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)（） 和[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)。

### void QPainter::strokePath(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen*)

绘制路径的轮廓（描边）*path*用指定的笔*pen*

**也可以看看**[fillPath](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fillPath)（） 和[Drawing](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawing)。

### bool QPainter::testRenderHint([QPainter::RenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum) *hint*) const

返回`true`如果*hint*已设置；否则返回`false`.

**也可以看看**[renderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints)（） 和[setRenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHint)()。

### const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::transform() const

别名为[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()。返回世界变换矩阵。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)（） 和[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()。

### void QPainter::translate(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*offset*)

按给定平移坐标系*offset*; 即给定的*offset*被添加到积分中。

**也可以看看**[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)（） 和[Coordinate Transformations](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#coordinate-transformations)。

### void QPainter::translate(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*offset*)

这是一个过载功能。

按给定平移坐标系*offset*。

### void QPainter::translate([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dy*)

这是一个过载功能。

通过向量平移坐标系 (*dx*,*dy*）。

### bool QPainter::viewTransformEnabled() const

返回`true`是否启用视图转换；否则返回 false。

**也可以看看**[setViewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewTransformEnabled)（） 和[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)()。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::viewport() const

返回视口矩形。

**也可以看看**[setViewport](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)（） 和[setViewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewTransformEnabled)()。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QPainter::window() const

返回窗口矩形。

**也可以看看**[setWindow](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWindow)（） 和[setViewTransformEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewTransformEnabled)()。

### bool QPainter::worldMatrixEnabled() const

`true`如果启用了世界变换则返回；否则返回 false。

**也可以看看**[setWorldMatrixEnabled](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldMatrixEnabled)(),[worldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#worldTransform)（）， 和[Coordinate System](https://doc-qt-io.translate.goog/qt-6/coordsys.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &QPainter::worldTransform() const

返回世界变换矩阵。

**也可以看看**[setWorldTransform](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setWorldTransform)()。