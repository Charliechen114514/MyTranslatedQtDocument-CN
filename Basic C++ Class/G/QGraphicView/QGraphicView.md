# QGraphicsView Class

QGraphicsView 类提供了一个用于显示图形内容的小部件。[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QGraphicsView>                                    |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qgraphicsview-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qgraphicsview-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| flags | **[CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)** |
| ----- | ------------------------------------------------------------ |
| enum  | **[CacheModeFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)** { CacheNone, CacheBackground } |
| enum  | **[DragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragMode-enum)** { NoDrag, ScrollHandDrag, RubberBandDrag } |
| enum  | **[OptimizationFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OptimizationFlag-enum)** { DontSavePainterState, DontAdjustForAntialiasing, IndirectPainting } |
| flags | **[OptimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OptimizationFlag-enum)** |
| enum  | **[ViewportAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportAnchor-enum)** { NoAnchor, AnchorViewCenter, AnchorUnderMouse } |
| enum  | **[ViewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportUpdateMode-enum)** { FullViewportUpdate, MinimalViewportUpdate, SmartViewportUpdate, BoundingRectViewportUpdate, NoViewportUpdate } |

## 特性

| **[alignment](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)** : Qt::Alignment**[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)** : QBrush**[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode-prop)** : CacheMode**[dragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMode-prop)** : DragMode**[foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)** : QBrush**[interactive](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#interactive-prop)** : bool**[optimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#optimizationFlags-prop)** : OptimizationFlags | **[renderHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints-prop)** : QPainter::RenderHints**[resizeAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeAnchor-prop)** : ViewportAnchor**[rubberBandSelectionMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandSelectionMode-prop)** : Qt::ItemSelectionMode**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)** : QRectF**[transformationAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformationAnchor-prop)** : ViewportAnchor**[viewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportUpdateMode-prop)** : ViewportUpdateMode |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共职能

|                                   | **[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsView)**(QWidget **parent* = nullptr) |
| --------------------------------- | ------------------------------------------------------------ |
|                                   | **[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsView-1)**(QGraphicsScene **scene*, QWidget **parent* = nullptr) |
| virtual                           | **[~QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QGraphicsView)**() |
| Qt::Alignment                     | **[alignment](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**() const |
| QBrush                            | **[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)**() const |
| QGraphicsView::CacheMode          | **[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode-prop)**() const |
| void                              | **[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)**(const QPointF &*pos*) |
| void                              | **[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn-1)**(qreal *x*, qreal *y*) |
| void                              | **[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn-2)**(const QGraphicsItem **item*) |
| QGraphicsView::DragMode           | **[dragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMode-prop)**() const |
| void                              | **[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)**(const QRectF &*rect*, int *xmargin* = 50, int *ymargin* = 50) |
| void                              | **[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, int *xmargin* = 50, int *ymargin* = 50) |
| void                              | **[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible-2)**(const QGraphicsItem **item*, int *xmargin* = 50, int *ymargin* = 50) |
| void                              | **[fitInView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fitInView)**(const QRectF &*rect*, Qt::AspectRatioMode *aspectRatioMode* = Qt::IgnoreAspectRatio) |
| void                              | **[fitInView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fitInView-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, Qt::AspectRatioMode *aspectRatioMode* = Qt::IgnoreAspectRatio) |
| void                              | **[fitInView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#fitInView-2)**(const QGraphicsItem **item*, Qt::AspectRatioMode *aspectRatioMode* = Qt::IgnoreAspectRatio) |
| QBrush                            | **[foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)**() const |
| bool                              | **[isInteractive](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#interactive-prop)**() const |
| bool                              | **[isTransformed](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isTransformed)**() const |
| QGraphicsItem *                   | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)**(const QPoint &*pos*) const |
| QGraphicsItem *                   | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt-1)**(int *x*, int *y*) const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)**() const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-1)**(const QPoint &*pos*) const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-2)**(int *x*, int *y*) const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-3)**(const QRect &*rect*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-4)**(int *x*, int *y*, int *w*, int *h*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-5)**(const QPolygon &*polygon*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QList<QGraphicsItem *>            | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-6)**(const QPainterPath &*path*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QPoint                            | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)**(const QPointF &*point*) const |
| QPolygon                          | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-1)**(const QRectF &*rect*) const |
| QPolygon                          | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-2)**(const QPolygonF &*polygon*) const |
| QPainterPath                      | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-3)**(const QPainterPath &*path*) const |
| QPoint                            | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-4)**(qreal *x*, qreal *y*) const |
| QPolygon                          | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-5)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QPointF                           | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)**(const QPoint &*point*) const |
| QPolygonF                         | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-1)**(const QRect &*rect*) const |
| QPolygonF                         | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-2)**(const QPolygon &*polygon*) const |
| QPainterPath                      | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-3)**(const QPainterPath &*path*) const |
| QPointF                           | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-4)**(int *x*, int *y*) const |
| QPolygonF                         | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-5)**(int *x*, int *y*, int *w*, int *h*) const |
| QGraphicsView::OptimizationFlags  | **[optimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#optimizationFlags-prop)**() const |
| void                              | **[render](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)**(QPainter **painter*, const QRectF &*target* = QRectF(), const QRect &*source* = QRect(), Qt::AspectRatioMode *aspectRatioMode* = Qt::KeepAspectRatio) |
| QPainter::RenderHints             | **[renderHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints-prop)**() const |
| void                              | **[resetCachedContent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetCachedContent)**() |
| void                              | **[resetTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetTransform)**() |
| QGraphicsView::ViewportAnchor     | **[resizeAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeAnchor-prop)**() const |
| void                              | **[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)**(qreal *angle*) |
| QRect                             | **[rubberBandRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandRect)**() const |
| Qt::ItemSelectionMode             | **[rubberBandSelectionMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandSelectionMode-prop)**() const |
| void                              | **[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)**(qreal *sx*, qreal *sy*) |
| QGraphicsScene *                  | **[scene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scene)**() const |
| QRectF                            | **[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)**() const |
| void                              | **[setAlignment](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)**(Qt::Alignment *alignment*) |
| void                              | **[setBackgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)**(const QBrush &*brush*) |
| void                              | **[setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode-prop)**(QGraphicsView::CacheMode *mode*) |
| void                              | **[setDragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMode-prop)**(QGraphicsView::DragMode *mode*) |
| void                              | **[setForegroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)**(const QBrush &*brush*) |
| void                              | **[setInteractive](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#interactive-prop)**(bool *allowed*) |
| void                              | **[setOptimizationFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOptimizationFlag)**(QGraphicsView::OptimizationFlag *flag*, bool *enabled* = true) |
| void                              | **[setOptimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#optimizationFlags-prop)**(QGraphicsView::OptimizationFlags *flags*) |
| void                              | **[setRenderHint](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRenderHint)**(QPainter::RenderHint *hint*, bool *enabled* = true) |
| void                              | **[setRenderHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints-prop)**(QPainter::RenderHints *hints*) |
| void                              | **[setResizeAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeAnchor-prop)**(QGraphicsView::ViewportAnchor *anchor*) |
| void                              | **[setRubberBandSelectionMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandSelectionMode-prop)**(Qt::ItemSelectionMode *mode*) |
| void                              | **[setScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScene)**(QGraphicsScene **scene*) |
| void                              | **[setSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)**(const QRectF &*rect*) |
| void                              | **[setSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) |
| void                              | **[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)**(const QTransform &*matrix*, bool *combine* = false) |
| void                              | **[setTransformationAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformationAnchor-prop)**(QGraphicsView::ViewportAnchor *anchor*) |
| void                              | **[setViewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportUpdateMode-prop)**(QGraphicsView::ViewportUpdateMode *mode*) |
| void                              | **[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)**(qreal *sh*, qreal *sv*) |
| QTransform                        | **[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)**() const |
| QGraphicsView::ViewportAnchor     | **[transformationAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformationAnchor-prop)**() const |
| void                              | **[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)**(qreal *dx*, qreal *dy*) |
| QTransform                        | **[viewportTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportTransform)**() const |
| QGraphicsView::ViewportUpdateMode | **[viewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportUpdateMode-prop)**() const |

## 重新实施公共职能

| virtual QVariant | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *query*) const override |
| ---------------- | ------------------------------------------------------------ |
| virtual QSize    | **[sizeHint](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)**() const override |

## 公共槽

| void | **[invalidateScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidateScene)**(const QRectF &*rect* = QRectF(), QGraphicsScene::SceneLayers *layers* = QGraphicsScene::AllLayers) |
| ---- | ------------------------------------------------------------ |
| void | **[updateScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateScene)**(const QList< QRectF > &*rects*) |
| void | **[updateSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateSceneRect)**(const QRectF &*rect*) |

## 信号

| void | **[rubberBandChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandChanged)**(QRect *rubberBandRect*, QPointF *fromScenePoint*, QPointF *toScenePoint*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## protected function

| virtual void | **[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)**(QPainter **painter*, const QRectF &*rect*) |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)**(QPainter **painter*, const QRectF &*rect*) |

## 重载的protected function

| virtual void | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QContextMenuEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QDragEnterEvent **event*) override |
| virtual void | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QDragLeaveEvent **event*) override |
| virtual void | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QDragMoveEvent **event*) override |
| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QDropEvent **event*) override |
| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **event*) override |
| virtual bool | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) override |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **event*) override |
| virtual void | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **event*) override |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) override |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **event*) override |
| virtual void | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QMouseEvent **event*) override |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QMouseEvent **event*) override |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QMouseEvent **event*) override |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QMouseEvent **event*) override |
| virtual void | **[paintEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)**(QPaintEvent **event*) override |
| virtual void | **[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)**(QResizeEvent **event*) override |
| virtual void | **[scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)**(int *dx*, int *dy*) override |
| virtual void | **[showEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)**(QShowEvent **event*) override |
| virtual bool | **[viewportEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)**(QEvent **event*) override |
| virtual void | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QWheelEvent **event*) override |

## 继承的槽函数

| virtual void | **[setupViewport](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setupViewport)**(QWidget **widget*) override |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

QGraphicsView 可视化 a 的内容[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在可滚动视口中。要创建包含几何项目的场景，请参阅[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的文档。QGraphicsView 是[Graphics View Framework](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

要可视化场景，首先构建一个 QGraphicsView 对象，将要可视化的场景的地址传递给 QGraphicsView 的构造函数。或者，您可以致电[setScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScene)() 设置稍后的场景。打电话后[show](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)()，默认情况下视图将滚动到场景中心并显示此时可见的任何项目。例如：

```
QGraphicsScene scene;
scene.addText("Hello, world!");

QGraphicsView view(&scene);
view.show();
```

您可以使用滚动条或通过调用显式滚动到场景上的任何位置[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()。通过传递一个点到[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()，QGraphicsView将滚动其视口以确保该点位于视图的中心。提供了一个重载用于滚动到[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，在这种情况下，QGraphicsView 将确保项目的中心位于视图的中心。如果您想要的只是确保某个区域可见（但不一定居中），您可以调用[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)（） 反而。

QGraphicsView 可用于可视化整个场景，或仅可视化其中的一部分。默认情况下，第一次显示视图时会自动检测可视化区域（通过调用[QGraphicsScene::itemsBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsBoundingRect)())。要自己设置可视化区域矩形，可以调用[setSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)()。这将适当调整滚动条的范围。请注意，虽然场景支持几乎无限的大小，但滚动条的范围永远不会超过整数的范围（INT_MIN、INT_MAX）。

QGraphicsView 通过调用来可视化场景[render](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)()。默认情况下，项目使用常规方法绘制到视口上[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并使用默认渲染提示。更改 QGraphicsView 传递给的默认渲染提示[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制物品时，您可以调用[setRenderHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints-prop)()。

默认情况下，QGraphicsView提供了常规的[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对于视口小部件。您可以通过调用来访问此小部件[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()，或者您可以通过调用来替换它[setViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)()。要使用 OpenGL 进行渲染，只需调用 setViewport(new QOpenGLWidget)。QGraphicsView 拥有视口小部件的所有权。

QGraphicsView支持仿射变换，使用[QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。您可以将矩阵传递给[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()，或者您可以调用便利函数之一[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)（） 或者[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)()。最常见的两种变换是缩放（用于实现缩放）和旋转。QGraphicsView 在变换期间保持视图中心固定。由于场景对齐（[setAlignment](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment-prop)())，平移视图不会产生视觉影响。

您可以使用鼠标和键盘与场景中的项目进行交互。QGraphicsView将鼠标和按键事件翻译成*场景*事件，（继承的事件[QGraphicsSceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicssceneevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),)，并将它们转发到可视化场景。最后，由单个项目处理事件并对事件做出反应。例如，如果您单击一个可选择的项目，该项目通常会让场景知道它已被选择，并且它还会重新绘制自身以显示一个选择矩形。同样，如果您单击并拖动鼠标来移动可移动项目，则该项目将处理鼠标移动并自行移动。默认情况下启用项目交互，您可以通过调用来切换它[setInteractive](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#interactive-prop)()。

您还可以通过创建 QGraphicsView 的子类并重新实现鼠标和按键事件处理程序来提供自己的自定义场景交互。为了简化您以编程方式与视图中的项目交互的方式，QGraphicsView 提供了映射函数[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（） 和[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)() 和项目访问器[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 和[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)()。这些函数允许您在视图坐标和场景坐标之间映射点、矩形、多边形和路径，并使用视图坐标查找场景上的项目。

当使用 QOpenGLWidget 作为视口时，支持立体渲染。这是使用与 QOpenGLWidget::paintGL 相同的模式完成的。要启用它，请启用[QSurfaceFormat::StereoBuffers](https://doc-qt-io.translate.goog/qt-6/qsurfaceformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FormatOption-enum)旗帜。由于该标志的内部处理方式，设置[QSurfaceFormat::StereoBuffers](https://doc-qt-io.translate.goog/qt-6/qsurfaceformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FormatOption-enum)在创建窗口之前全局标记[QSurfaceFormat::setDefaultFormat](https://doc-qt-io.translate.goog/qt-6/qsurfaceformat.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setDefaultFormat)()。如果启用该标志并且有立体渲染的硬件支持，则[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)（） 和[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)() 每帧会触发两次。调用 QOpenGLWidget::currentTargetBuffer() 查询当前正在绘制到哪个缓冲区。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\G\QGraphicView\QGraphicView\graphicsview-view-1693618902354-3.png)

**注意：**使用 OpenGL 视口会限制使用的能力[QGraphicsProxyWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsproxywidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。此类设置并非支持所有小部件和样式的组合。您应该仔细测试您的 UI 并进行必要的调整。

**也可以看看**[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QGraphicsSceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicssceneevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 会员类型文档

### 枚举 QGraphicsView:: CacheModeFlag 标志 QGraphicsView:: CacheMode

该枚举描述了您可以为[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的缓存模式。

| 持续的                           | 价值  | 描述                                                         |
| -------------------------------- | ----- | ------------------------------------------------------------ |
| `QGraphicsView::CacheNone`       | `0x0` | 所有绘画都直接在视口上完成。                                 |
| `QGraphicsView::CacheBackground` | `0x1` | 背景已缓存。这会影响自定义背景和基于[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)财产。当该标志被启用时，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将分配一个具有视口完整大小的像素图。 |

CacheMode 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <CacheModeFlag> 的类型定义。它存储 CacheModeFlag 值的 OR 组合。

**也可以看看**[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode-prop)。

### enum QGraphicsView::DragMode

该枚举描述了在视口上按下并拖动鼠标时视图的默认操作。

| 持续的                          | 价值 | 描述                                                         |
| ------------------------------- | ---- | ------------------------------------------------------------ |
| `QGraphicsView::NoDrag`         | `0`  | 什么都没发生; 鼠标事件被忽略。                               |
| `QGraphicsView::ScrollHandDrag` | `1`  | 光标变为手形，拖动鼠标将滚动滚动条。此模式适用于[interactive](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#interactive-prop)和非交互模式。 |
| `QGraphicsView::RubberBandDrag` | `2`  | 将会出现一条橡皮筋。拖动鼠标将设置橡皮筋几何形状，并选择橡皮筋覆盖的所有项目。对于非交互式视图禁用此模式。 |

**也可以看看**[dragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMode-prop)和[QGraphicsScene::setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()。

### 枚举 QGraphicsView:: OptimizationFlag 标志 QGraphicsView:: OptimizationFlags

该枚举描述了可以启用以提高渲染性能的标志[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。默认情况下，没有设置这些标志。请注意，设置标志通常会产生副作用，并且这种效果可能因绘画设备和平台而异。

| 持续的                                     | 价值  | 描述                                                         |
| ------------------------------------------ | ----- | ------------------------------------------------------------ |
| `QGraphicsView::DontSavePainterState`      | `0x1` | 渲染时，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)保护画家状态（参见[QPainter::save](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#save)()) 渲染背景或前景时以及渲染每个项目时。这允许您让画家处于改变的状态（即，您可以调用[QPainter::setPen](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPen)（） 或者[QPainter::setBrush](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBrush)() 不恢复绘画后的状态)。但是，如果项目始终恢复状态，您应该启用此标志以防止[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)做同样的事情。 |
| `QGraphicsView::DontAdjustForAntialiasing` | `0x2` | 禁用[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)曝光区域的抗锯齿自动调整。在其边界上呈现抗锯齿线的项目[QGraphicsItem::boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 可以最终将部分线条渲染到外部。为了防止渲染伪影，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将所有曝光区域在所有方向上扩展 2 个像素。如果启用此标志，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将不再执行这些调整，从而最大限度地减少需要重绘的区域，从而提高性能。一个常见的副作用是，使用抗锯齿进行绘制的项目在移动时可能会在场景中留下绘画痕迹。 |
| `QGraphicsView::IndirectPainting`          | `0x4` | 从 Qt 4.6 开始，恢复调用 QGraphicsView::drawItems() 和 QGraphicsScene::drawItems() 的旧绘画算法。仅用于与旧代码兼容。 |

OptimizationFlags 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <OptimizationFlag> 的类型定义。它存储 OptimizationFlag 值的 OR 组合。

### enum QGraphicsView::ViewportAnchor

这个枚举描述了可能的锚点[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当用户调整视图大小或变换视图时可以使用。

| 持续的                            | 价值 | 描述                                 |
| --------------------------------- | ---- | ------------------------------------ |
| `QGraphicsView::NoAnchor`         | `0`  | 无锚点，即视图使场景的位置保持不变。 |
| `QGraphicsView::AnchorViewCenter` | `1`  | 视图中心的场景点用作锚点。           |
| `QGraphicsView::AnchorUnderMouse` | `2`  | 鼠标下方的点用作锚点。               |

**也可以看看**[resizeAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeAnchor-prop)和[transformationAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformationAnchor-prop)。

### enum QGraphicsView::ViewportUpdateMode

这个枚举描述了如何[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当场景内容更改或暴露时更新其视口。

| 持续的                                      | 价值 | 描述                                                         |
| ------------------------------------------- | ---- | ------------------------------------------------------------ |
| `QGraphicsView::FullViewportUpdate`         | `0`  | 当场景的任何可见部分发生变化或重新曝光时，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将更新整个视口。这种方法最快的时候[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)花费更多的时间来弄清楚要绘制什么而不是花费绘制的时间（例如，当重复更新很多小项目时）。对于不支持部分更新的视口（例如 QOpenGLWidget）以及需要禁用滚动优化的视口，这是首选更新模式。 |
| `QGraphicsView::MinimalViewportUpdate`      | `1`  | [QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将确定需要重绘的最小视口区域，通过避免重绘未更改的区域来最小化绘制所花费的时间。这是[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的默认模式。虽然这种方法总体上提供了最佳性能，但如果场景中有许多小的可见变化，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)最终可能会花费更多的时间来寻找最小方法，而不是花费在绘图上。 |
| `QGraphicsView::SmartViewportUpdate`        | `2`  | [QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将尝试通过分析需要重绘的区域来找到最佳更新模式。 |
| `QGraphicsView::BoundingRectViewportUpdate` | `4`  | 视口中所有变化的边界矩形都将被重新绘制。这种模式的优点是[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)仅搜索一个区域进行更改，从而最大限度地减少确定需要重绘的区域所花费的时间。缺点是没有改变的区域也需要重新绘制。 |
| `QGraphicsView::NoViewportUpdate`           | `3`  | [QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当场景改变时永远不会更新其视口；用户应该控制所有更新。此模式禁用所有（可能很慢）项目可见性测试[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并且适用于需要固定帧速率或视口以其他方式从外部更新的场景。 |

**也可以看看**[viewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportUpdateMode-prop)。

## 属性文档

### alignment : [Qt::Alignment](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)

当整个场景可见时，此属性保存视图中场景的对齐方式。

如果整个场景在视图中可见（即，没有可见的滚动条），则视图的对齐方式将决定场景在视图中的渲染位置。例如，如果对齐方式是[Qt::AlignCenter](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)，默认情况下，场景将在视图中居中，如果对齐方式是 ([Qt::AlignLeft](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)|[Qt::AlignTop](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AlignmentFlag-enum)），场景将渲染在视图的左上角。

**访问功能：**

| Qt::Alignment | **alignment**() const                       |
| ------------- | ------------------------------------------- |
| void          | **setAlignment**(Qt::Alignment *alignment*) |

### backgroundBrush : [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景的背景画笔。

此属性设置此视图中场景的背景画笔。它用于覆盖场景自己的背景，并定义[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)()。要为此视图提供自定义背景绘图，您可以重新实现[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)（） 反而。

默认情况下，该属性包含一个带有[Qt::NoBrush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)图案。

**访问功能：**

| QBrush | **backgroundBrush**() const                   |
| ------ | --------------------------------------------- |
| void   | **setBackgroundBrush**(const QBrush &*brush*) |

**也可以看看**[QGraphicsScene::backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)和[foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)。

### cacheMode : [CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)

该属性保存视图的哪些部分被缓存

[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以将预渲染的内容缓存在[QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，然后将其绘制到视口上。此类缓存的目的是加快渲染缓慢区域的总渲染时间。例如，纹理、渐变和 Alpha 混合背景的渲染速度可能会非常慢；尤其是在视野发生变化的情况下。这[CacheBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)标志启用视图背景的缓存。例如：

```
QGraphicsView view;
view.setBackgroundBrush(QImage(":/images/backgroundtile.png"));
view.setCacheMode(QGraphicsView::CacheBackground);
```

每次视图转换时，缓存都会失效。然而，滚动时，只需要部分失效。

默认情况下，不缓存任何内容。

**访问功能：**

| QGraphicsView::CacheMode | **cacheMode**() const                             |
| ------------------------ | ------------------------------------------------- |
| void                     | **setCacheMode**(QGraphicsView::CacheMode *mode*) |

**也可以看看**[resetCachedContent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetCachedContent)（） 和[QPixmapCache](https://doc-qt-io.translate.goog/qt-6/qpixmapcache.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### dragMode : [DragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragMode-enum)

该属性保存按下鼠标左键时在场景上拖动鼠标的行为。

此属性定义当用户单击场景背景并拖动鼠标时应发生的情况（例如，使用手形光标滚动视口内容，或使用橡皮筋选择多个项目）。默认值，[NoDrag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragMode-enum)， 什么也没做。

此行为仅影响不受任何项目处理的鼠标单击。您可以通过创建子类来定义自定义行为[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并重新实施[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)()。

**访问功能：**

| QGraphicsView::DragMode | **dragMode**() const                            |
| ----------------------- | ----------------------------------------------- |
| void                    | **setDragMode**(QGraphicsView::DragMode *mode*) |

### foregroundBrush : [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景的前景画笔。

此属性设置此视图中场景的前景画笔。它用于覆盖场景自己的前景，并定义[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)()。要为此视图提供自定义前景绘图，您可以重新实现[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)（） 反而。

默认情况下，该属性包含一个带有[Qt::NoBrush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)图案。

**访问功能：**

| QBrush | **foregroundBrush**() const                   |
| ------ | --------------------------------------------- |
| void   | **setForegroundBrush**(const QBrush &*brush*) |

**也可以看看**[QGraphicsScene::foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)和[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)。

### interactive : bool

该属性保存视图是否允许场景交互。

如果启用，此视图将设置为允许场景交互。否则，该视图将不允许交互，并且任何鼠标或按键事件都将被忽略（即，它将充当只读视图）。

默认情况下，该属性为`true`。

**访问功能：**

| bool | **isInteractive**() const          |
| ---- | ---------------------------------- |
| void | **setInteractive**(bool *allowed*) |

### optimizationFlags : [OptimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OptimizationFlag-enum)

可用于调整的标志[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的表现。

[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用裁剪、额外边界矩形调整和某些其他辅助工具来提高常见情况图形场景的渲染质量和性能。但是，根据目标平台、场景和使用的视口，其中一些操作可能会降低性能。

不同旗帜的效果各不相同；看到[OptimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OptimizationFlag-enum)文档了解详细信息。

默认情况下，不启用任何优化标志。

**访问功能：**

| QGraphicsView::OptimizationFlags | **optimizationFlags**() const                                |
| -------------------------------- | ------------------------------------------------------------ |
| void                             | **setOptimizationFlags**(QGraphicsView::OptimizationFlags *flags*) |

**也可以看看**[setOptimizationFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOptimizationFlag)()。

### renderHints : [QPainter::RenderHints](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)

该属性保存视图的默认渲染提示

这些提示用于初始化[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在绘制每个可见项目之前。[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用渲染提示来切换渲染功能，例如抗锯齿和平滑像素图转换。

[QPainter::TextAntialiasing](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum)默认启用。

例子：

```
QGraphicsScene scene;
scene.addRect(QRectF(-10, -10, 20, 20));

QGraphicsView view(&scene);
view.setRenderHints(QPainter::Antialiasing | QPainter::SmoothPixmapTransform);
view.show();
```

**访问功能：**

| QPainter::RenderHints | **renderHints**() const                           |
| --------------------- | ------------------------------------------------- |
| void                  | **setRenderHints**(QPainter::RenderHints *hints*) |

### resizeAnchor : [ViewportAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportAnchor-enum)

调整视图大小时视图应如何定位场景。

[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此属性来决定当视口小部件的大小发生变化时如何在视口中定位场景。默认行为，[NoAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportAnchor-enum)，在调整大小期间保持场景位置不变；调整大小时，视图的左上角将显示为锚定的。

请注意，当只有场景的一部分可见时（即，有滚动条时），此属性的效果很明显。否则，如果整个场景都适合视图，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用视图[alignment](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)在视图中定位场景。

**访问功能：**

| QGraphicsView::ViewportAnchor | **resizeAnchor**() const                                    |
| ----------------------------- | ----------------------------------------------------------- |
| void                          | **setResizeAnchor**(QGraphicsView::ViewportAnchor *anchor*) |

**也可以看看**[alignment](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)和[transformationAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformationAnchor-prop)。

### rubberBandSelectionMode : [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum)

此属性保存使用橡皮筋选择矩形选择项目的行为。

该属性定义了使用时如何选择项目[RubberBandDrag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#DragMode-enum)拖动模式。

默认值为[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 所有形状与橡皮筋相交或包含在橡皮筋内的项目都会被选中。

**访问功能：**

| Qt::ItemSelectionMode | **rubberBandSelectionMode**() const                          |
| --------------------- | ------------------------------------------------------------ |
| void                  | **setRubberBandSelectionMode**(Qt::ItemSelectionMode *mode*) |

**也可以看看**[dragMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMode-prop),[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（）， 和[rubberBandRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandRect)()。

### sceneRect : [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存该视图可视化的场景区域。

场景矩形定义场景的范围，在视图的情况下，这意味着您可以使用滚动条导航的场景区域。

如果未设置，或者如果为空[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)设置后，该属性的值与[QGraphicsScene::sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)，并且它随着变化[QGraphicsScene::sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)。否则，视图的场景矩形不受场景影响。

请注意，尽管场景支持几乎无限的大小，但滚动条的范围永远不会超过整数的范围（INT_MIN、INT_MAX）。当场景大于滚动条的值时，可以选择使用[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)() 来导航场景。

默认情况下，此属性在原点包含一个宽度和高度为零的矩形。

**访问功能：**

| QRectF | **sceneRect**() const                                        |
| ------ | ------------------------------------------------------------ |
| void   | **setSceneRect**(const QRectF &*rect*)                       |
| void   | **setSceneRect**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) |

**也可以看看**[QGraphicsScene::sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)。

### transformationAnchor : [ViewportAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportAnchor-enum)

视图在变换期间应如何定位场景。

[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此属性来决定当变换矩阵发生变化以及视图的坐标系发生变换时如何在视口中定位场景。默认行为，[AnchorViewCenter](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportAnchor-enum)，确保视图中心的场景点在变换期间保持不变（例如，旋转时，场景将出现围绕视图中心旋转）。

请注意，当只有场景的一部分可见时（即，有滚动条时），此属性的效果很明显。否则，如果整个场景都适合视图，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用视图[alignment](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)在视图中定位场景。

**访问功能：**

| QGraphicsView::ViewportAnchor | **transformationAnchor**() const                             |
| ----------------------------- | ------------------------------------------------------------ |
| void                          | **setTransformationAnchor**(QGraphicsView::ViewportAnchor *anchor*) |

**也可以看看**[alignment](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#alignment)和[resizeAnchor](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeAnchor-prop)。

### viewportUpdateMode : [ViewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportUpdateMode-enum)

视口应如何更新其内容。

[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用此属性来决定如何更新场景中已重新曝光或更改的区域。通常您不需要修改此属性，但在某些情况下这样做可以提高渲染性能。请参阅[ViewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportUpdateMode-enum)具体细节的文档。

默认值为[MinimalViewportUpdate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportUpdateMode-enum)， 在哪里[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当内容更改时，将更新视口中尽可能小的区域。

**访问功能：**

| QGraphicsView::ViewportUpdateMode | **viewportUpdateMode**() const                               |
| --------------------------------- | ------------------------------------------------------------ |
| void                              | **setViewportUpdateMode**(QGraphicsView::ViewportUpdateMode *mode*) |

**也可以看看**[ViewportUpdateMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ViewportUpdateMode-enum)和[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode-prop)。

## 成员函数文档

### QGraphicsView::QGraphicsView([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个 QGraphicsView。*parent*被传递给[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的构造函数。

### QGraphicsView::QGraphicsView([QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **scene*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **parent* = nullptr)

构造一个QGraphicsView并将可视化场景设置为*scene*。*parent*被传递给[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的构造函数。

### `[virtual]`QGraphicsView::~QGraphicsView()

破坏了[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目的。

### void QGraphicsView::centerOn(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*)

滚动视口的内容以确保场景坐标*pos*，位于视图的中心。

因为*pos*是浮点坐标，滚动条在整数坐标上操作，居中只是一个近似值。

**注意：**如果项目靠近或超出边框，它将在视图中可见，但不会居中。

**也可以看看**[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)()。

### void QGraphicsView::centerOn([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*)

这是一个过载功能。

提供此功能是为了方便。相当于调用centerOn([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### void QGraphicsView::centerOn(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

这是一个过载功能。

滚动视口的内容以确保*item*位于视图的中心。

**也可以看看**[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)()。

### `[override virtual protected]`void QGraphicsView::contextMenuEvent([QContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qcontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)（QContextMenuEvent *e）。

### `[override virtual protected]`void QGraphicsView::dragEnterEvent([QDragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qdragenterevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（QDragEnterEvent *事件）。

### `[override virtual protected]`void QGraphicsView::dragLeaveEvent([QDragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qdragleaveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（QDragLeaveEvent *事件）。

### `[override virtual protected]`void QGraphicsView::dragMoveEvent([QDragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qdragmoveevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（QDragMoveEvent *事件）。

### `[virtual protected]`void QGraphicsView::drawBackground([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

使用绘制场景的背景*painter*，在绘制任何项目和前景之前。重新实现此函数以为该视图提供自定义背景。

如果您只想定义背景的颜色、纹理或渐变，您可以调用[setBackgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)（） 反而。

所有绘画都是在*场景*坐标中完成的。*rect*是暴露的矩形。

默认实现填充*rect*使用视图的[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)。如果没有定义这样的画笔（默认），则调用场景的drawBackground()函数。

**也可以看看**[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)（） 和[QGraphicsScene::drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)()。

### `[virtual protected]`void QGraphicsView::drawForeground([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

使用以下方法绘制场景的前景*painter*，在绘制背景和所有项目之后。重新实现此函数以为该视图提供自定义前景。

如果您只想为前景定义颜色、纹理或渐变，您可以调用[setForegroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)（） 反而。

所有绘画都是在*场景*坐标中完成的。*rect*是暴露的矩形。

默认实现填充*rect*使用视图的[foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)。如果没有定义这样的画笔（默认），则调用场景的drawForeground()函数。

**也可以看看**[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)（） 和[QGraphicsScene::drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)()。

### `[override virtual protected]`void QGraphicsView::dropEvent([QDropEvent](https://doc-qt-io.translate.goog/qt-6/qdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::dropEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（QDropEvent *事件）。

### void QGraphicsView::ensureVisible(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, int *xmargin* = 50, int *ymargin* = 50)

滚动视口的内容，以便场景矩形*rect*是可见的，边距以像素为单位指定*xmargin*和*ymargin*。如果无法到达指定的矩形，则内容将滚动到最近的有效位置。两个边距的默认值为 50 像素。

**也可以看看**[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()。

### void QGraphicsView::ensureVisible([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, int *xmargin* = 50, int *ymargin* = 50)

这是一个过载功能。

提供此功能是为了方便。相当于调用ensureVisible([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*xmargin*,*ymargin*）。

### void QGraphicsView::ensureVisible(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, int *xmargin* = 50, int *ymargin* = 50)

这是一个过载功能。

滚动视口的内容，使项目的中心*item*是可见的，边距以像素为单位指定*xmargin*和*ymargin*。如果无法到达指定点，内容将滚动到最近的有效位置。两个边距的默认值为 50 像素。

**也可以看看**[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()。

### `[override virtual protected]`bool QGraphicsView::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::event](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *事件）。

### void QGraphicsView::fitInView(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [Qt::AspectRatioMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AspectRatioMode-enum) *aspectRatioMode* = Qt::IgnoreAspectRatio)

缩放视图矩阵并滚动滚动条以确保场景矩形*rect*适合视口内。*rect*必须在场景矩形内；否则，fitInView()不能保证整个矩形可见。

此函数保持视图的旋转、平移或剪切。视图按比例缩放*aspectRatioMode*。*rect*如果不紧密贴合，将在视图中居中。

从重新实现内部调用 fitInView() 是很常见的[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)()，以确保整个场景或部分场景在视图大小调整时自动缩放以适应视口的新大小。但请注意，从内部调用 fitInView()[resizeEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)如果新转换切换滚动条的自动状态，() 可能会导致不必要的调整大小递归。您可以将滚动条策略切换为始终打开或始终关闭以防止出现这种情况（请参阅[horizontalScrollBarPolicy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollBarPolicy-prop)（） 和[verticalScrollBarPolicy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollBarPolicy-prop)())。

如果*rect*为空，或者如果视口太小，该函数将不执行任何操作。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)（）， 和[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()。

### void QGraphicsView::fitInView([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, [Qt::AspectRatioMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AspectRatioMode-enum) *aspectRatioMode* = Qt::IgnoreAspectRatio)

这是一个过载功能。

这个便利函数相当于调用 fitInView([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*aspectRatioMode*）。

**也可以看看**[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)（） 和[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()。

### void QGraphicsView::fitInView(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [Qt::AspectRatioMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AspectRatioMode-enum) *aspectRatioMode* = Qt::IgnoreAspectRatio)

这是一个过载功能。

确保*item*紧紧贴合在视图内，根据缩放视图*aspectRatioMode*。

**也可以看看**[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)（） 和[centerOn](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#centerOn)()。

### `[override virtual protected]`void QGraphicsView::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（QFocusEvent *事件）。

### `[override virtual protected]`bool QGraphicsView::focusNextPrevChild(bool *next*)

重新实现：[QWidget::focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)（接下来是布尔值）。

### `[override virtual protected]`void QGraphicsView::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)（QFocusEvent *事件）。

### `[override virtual protected]`void QGraphicsView::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)（QInputMethodEvent *事件）。

### `[override virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *query*) const

重新实现：[QWidget::inputMethodQuery(Qt::InputMethodQuery query) const](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)。

### `[slot]`void QGraphicsView::invalidateScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF(), [QGraphicsScene::SceneLayers](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum) *layers* = QGraphicsScene::AllLayers)

无效并安排重绘*layers*里面*rect*。*rect*位于场景坐标中。任何缓存内容*layers*里面*rect*无条件无效并重新绘制。

您可以调用此函数来通知[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)场景背景或前景的变化。它通常用于具有基于图块的背景的场景，以在以下情况下通知更改：[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)已启用后台缓存。

注意[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目前仅支持后台缓存（请参阅[QGraphicsView::CacheBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)）。该函数相当于调用[update](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 如果任何层但是[QGraphicsScene::BackgroundLayer](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum)已通过。

**也可以看看**[QGraphicsScene::invalidate](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)（） 和[update](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)()。

### bool QGraphicsView::isTransformed() const

`true`如果视图已变换（即已分配非同一变换，或调整滚动条），则返回。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[horizontalScrollBar](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#horizontalScrollBar)（）， 和[verticalScrollBar](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#verticalScrollBar)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsView::itemAt(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

返回位置处的项目*pos*，位于视口坐标中。如果此位置有多个项目，则此函数返回最上面的项目。

例子：

```
void CustomView::mousePressEvent(QMouseEvent *event)
{
    if (QGraphicsItem *item = itemAt(event->pos())) {
        qDebug() << "You clicked on item" << item;
    } else {
        qDebug("You didn't click on an item.");
    }
}
```

**也可以看看**[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsView::itemAt(int *x*, int *y*) const

这是一个过载功能。

提供此功能是为了方便。相当于调用 itemAt([QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items() const

返回关联场景中所有项目的列表，按降序堆叠顺序（即返回列表中的第一项是最上面的项目）。

**也可以看看**[QGraphicsScene::items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*) const

返回该位置的所有项目的列表*pos*视图中。这些项目按降序堆叠顺序列出（即，列表中的第一项是最上面的项目，最后一个项目是最下面的项目）。*pos*位于视口坐标中。

该函数最常在子类中的鼠标事件处理程序中调用[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。*pos*位于未变换的视口坐标中，就像 QMouseEvent::pos() 一样。

```
void CustomView::mousePressEvent(QMouseEvent *event)
{
    qDebug() << "There are" << items(event->pos()).size()
             << "items at position" << mapToScene(event->pos());
}
```

**也可以看看**[QGraphicsScene::items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items(int *x*, int *y*) const

提供此功能是为了方便。相当于调用 items([QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

这是一个过载功能。

返回所有项目的列表，具体取决于*mode*，包含于或相交于*rect*。*rect*位于视口坐标中。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与 相交或包含于 的所有项目*rect*被退回。

这些项目按降序堆叠顺序排序（即返回列表中的第一项是最上面的项目）。

**也可以看看**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)(),[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items(int *x*, int *y*, int *w*, int *h*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

这个便利函数相当于调用 items([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*mode*）。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items(const [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

这是一个过载功能。

返回所有项目的列表，具体取决于*mode*，包含于或相交于*polygon*。*polygon*位于视口坐标中。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与 相交或包含于 的所有项目*polygon*被退回。

这些项目按降序堆叠顺序排序（即返回列表中的第一项是最上面的项目）。

**也可以看看**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)(),[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsView::items(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

这是一个过载功能。

返回所有项目的列表，具体取决于*mode*，包含于或相交于*path*。*path*位于视口坐标中。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与 相交或包含于 的所有项目*path*被退回。

**也可以看看**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)(),[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### `[override virtual protected]`void QGraphicsView::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（QKeyEvent *e）。

### `[override virtual protected]`void QGraphicsView::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（QKeyEvent *事件）。

### [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapFromScene(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

返回场景坐标*point*到视口坐标。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

### [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapFromScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

返回场景矩形*rect*到视口坐标多边形。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

### [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapFromScene(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

返回场景坐标多边形*polygon*到视口坐标多边形。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapFromScene(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

返回场景坐标画家路径*path*到视口坐标画家路径。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

### [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapFromScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

提供此功能是为了方便。相当于调用mapFromScene([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapFromScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

提供此功能是为了方便。相当于调用mapFromScene([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapToScene(const [QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

返回视口坐标*point*映射到场景坐标。

注意：将像素覆盖的整个矩形映射到*point*而不是点本身。为此，您可以调用mapToScene([QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*point*,[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)(2, 2)))。

**也可以看看**[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapToScene(const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

返回视口矩形*rect*映射到场景坐标多边形。

**也可以看看**[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapToScene(const [QPolygon](https://doc-qt-io.translate.goog/qt-6/qpolygon.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

返回视口多边形*polygon*映射到场景坐标多边形。

**也可以看看**[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapToScene(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

返回视口画家路径*path*映射到场景坐标画家路径。

**也可以看看**[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapToScene(int *x*, int *y*) const

提供此功能是为了方便。相当于调用mapToScene([QPoint](https://doc-qt-io.translate.goog/qt-6/qpoint.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::mapToScene(int *x*, int *y*, int *w*, int *h*) const

提供此功能是为了方便。相当于调用mapToScene([QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### `[override virtual protected]`void QGraphicsView::mouseDoubleClickEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QGraphicsView::mouseMoveEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QGraphicsView::mousePressEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QGraphicsView::mouseReleaseEvent([QMouseEvent](https://doc-qt-io.translate.goog/qt-6/qmouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(QMouseEvent *e)。

### `[override virtual protected]`void QGraphicsView::paintEvent([QPaintEvent](https://doc-qt-io.translate.goog/qt-6/qpaintevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::paintEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paintEvent)（QPaintEvent *事件）。

### void QGraphicsView::render([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*target* = QRectF(), const [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source* = QRect(), [Qt::AspectRatioMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AspectRatioMode-enum) *aspectRatioMode* = Qt::KeepAspectRatio)

呈现*source*矩形，在视图坐标中，从场景到*target*，位于绘制设备坐标中，使用*painter*。此函数对于将视图内容捕获到绘画设备（例如[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（例如，截取屏幕截图），或打印到 QPrinter。例如：

```
QGraphicsScene scene;
scene.addItem(...
...

QGraphicsView view(&scene);
view.show();
...

QPrinter printer(QPrinter::HighResolution);
printer.setPageSize(QPrinter::A4);
QPainter painter(&printer);

// print, fitting the viewport contents into a full page
view.render(&painter);

// print the upper half of the viewport into the lower.
// half of the page.
QRect viewport = view.viewport()->rect();
view.render(&painter,
            QRectF(0, printer.height() / 2,
                   printer.width(), printer.height() / 2),
            viewport.adjusted(0, 0, 0, -viewport.height() / 2));
```

如果*source*是一个空矩形，这个函数将使用[viewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewport)()->[rect](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rect-prop)() 来确定要绘制的内容。如果*target*是一个空矩形，其完整尺寸*painter*将使用 的绘图设备（例如，对于 QPrinter，页面大小）。

源矩形内容将根据以下内容进行转换*aspectRatioMode*以适合目标矩形。默认情况下，保持宽高比，并且*source*缩放以适应*target*。

**也可以看看**[QGraphicsScene::render](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)()。

### void QGraphicsView::resetCachedContent()

重置所有缓存的内容。调用该函数会清除[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的缓存。如果当前缓存模式是[CacheNone](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)，这个函数什么也不做。

当[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)或者[QGraphicsScene::backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)属性改变；如果你重新实现了，你只需要调用这个函数[QGraphicsScene::drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)（） 或者[QGraphicsView::drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)() 绘制自定义背景，并且需要触发完全重绘。

**也可以看看**[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode-prop)()。

### void QGraphicsView::resetTransform()

将视图变换重置为单位矩阵。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（） 和[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()。

### `[override virtual protected]`void QGraphicsView::resizeEvent([QResizeEvent](https://doc-qt-io.translate.goog/qt-6/qresizeevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::resizeEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resizeEvent)（QResizeEvent *事件）。

### void QGraphicsView::rotate([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *angle*)

旋转当前视图变换*angle*顺时针度数。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)（）， 和[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)()。

### `[signal]`void QGraphicsView::rubberBandChanged([QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *rubberBandRect*, [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *fromScenePoint*, [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *toScenePoint*)

当橡皮筋矩形更改时会发出此信号。视口矩形由以下方式指定*rubberBandRect*。拖动开始位置和拖动结束位置在场景点中提供*fromScenePoint*和*toScenePoint*。

当橡皮筋选择结束时，该信号将以空值发出。

**也可以看看**[rubberBandRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandRect)()。

### [QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::rubberBandRect() const

如果用户当前正在使用橡皮筋进行项目选择，则此函数返回当前橡皮筋区域（在视口坐标中）。当用户不使用橡皮筋时，该函数返回（空）QRectF()。

请注意这一部分[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可以超出视觉视口。例如，它可以包含负值。

**也可以看看**[rubberBandSelectionMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandSelectionMode-prop)和[rubberBandChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rubberBandChanged)()。

### void QGraphicsView::scale([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sy*)

将当前视图变换缩放 (*sx*,*sy*）。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)（）， 和[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)()。

### [QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsView::scene() const

返回指向视图中当前可视化场景的指针。如果当前没有可视化场景，`nullptr`则返回。

**也可以看看**[setScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScene)()。

### `[override virtual protected]`void QGraphicsView::scrollContentsBy(int *dx*, int *dy*)

重新实现：[QAbstractScrollArea::scrollContentsBy](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scrollContentsBy)（int dx，int dy）。

### void QGraphicsView::setOptimizationFlag([QGraphicsView::OptimizationFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#OptimizationFlag-enum) *flag*, bool *enabled* = true)

启用*flag*如果*enabled*是真的; 否则禁用*flag*。

**也可以看看**[optimizationFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#optimizationFlags-prop)。

### void QGraphicsView::setRenderHint([QPainter::RenderHint](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#RenderHint-enum) *hint*, bool *enabled* = true)

如果*enabled*为 true 时，渲染提示*hint*已启用；否则它会被禁用。

**也可以看看**[renderHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#renderHints-prop)。

### void QGraphicsView::setScene([QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **scene*)

将当前场景设置为*scene*。如果*scene*已被查看，此功能不执行任何操作。

当场景设置在视图上时，[QGraphicsScene::changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 信号自动连接到该视图的[updateScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateScene)() 槽，并且视图的滚动条会调整以适应场景的大小。

该视图不拥有所有权*scene*。

**也可以看看**[scene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scene)()。

### void QGraphicsView::setTransform(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*matrix*, bool *combine* = false)

将视图的当前变换矩阵设置为*matrix*。

如果*combine*是真的，那么*matrix*与当前矩阵组合；否则，*matrix* *替换*当前矩阵。*combine*默认为 false。

变换矩阵将场景变换为视图坐标。使用单位矩阵提供的默认变换，视图中的一个像素代表场景中的一个单元（例如，使用视图中的 10x10 像素绘制一个 10x10 矩形项目）。如果应用 2x2 缩放矩阵，则场景将以 1:2 的比例绘制（例如，然后使用视图中的 20x20 像素绘制 10x10 矩形项目）。

例子：

```
QGraphicsScene scene;
scene.addText("GraphicsView rotated clockwise");

QGraphicsView view(&scene);
view.rotate(90); // the text is rendered with a 90 degree clockwise rotation
view.show();
```

为了使用转换后的视图简化与项目的交互，[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供可以在场景坐标和视图坐标之间转换的mapTo...和mapFrom...函数。例如，您可以调用[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)() 将视图坐标映射到浮点场景坐标，或者[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)() 从浮点场景坐标映射到视图坐标。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[resetTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetTransform)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)（）， 和[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)()。

### `[override virtual protected slot]`void QGraphicsView::setupViewport([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QWidget) **widget*)

重新实现：[QAbstractScrollArea::setupViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setupViewport)（QWidget *视口）。

这个槽被称为[QAbstractScrollArea](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)后[setViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)() 已被调用。在子类中重新实现此函数[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)初始化新视口*widget*在使用之前。

**也可以看看**[setViewport](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setViewport)()。

### void QGraphicsView::shear([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sh*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *sv*)

通过 ( 剪切当前视图变换*sh*,*sv*）。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)（）， 和[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)()。

### `[override virtual protected]`void QGraphicsView::showEvent([QShowEvent](https://doc-qt-io.translate.goog/qt-6/qshowevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QWidget::showEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#showEvent)（QShowEvent *事件）。

### `[override virtual]`[QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::sizeHint() const

重新实现：[QAbstractScrollArea::sizeHint() const](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sizeHint)。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::transform() const

返回视图的当前变换矩阵。如果未设置当前变换，则返回单位矩阵。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)（）， 和[translate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#translate)()。

### void QGraphicsView::translate([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dy*)

将当前视图变换平移 (*dx*,*dy*）。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[rotate](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotate)（）， 和[shear](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shear)()。

### `[slot]`void QGraphicsView::updateScene(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*rects*)

安排场景矩形的更新*rects*。

**也可以看看**[QGraphicsScene::changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)()。

### `[slot]`void QGraphicsView::updateSceneRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

通知[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)场景的场景矩形已更改。*rect*是新场景矩形。如果视图已经有明确设置的场景矩形，则此函数不执行任何操作。

**也可以看看**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)和[QGraphicsScene::sceneRectChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRectChanged)()。

### `[override virtual protected]`bool QGraphicsView::viewportEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::viewportEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#viewportEvent)（QEvent *事件）。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsView::viewportTransform() const

返回将场景坐标映射到视口坐标的矩阵。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（） 和[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

### `[override virtual protected]`void QGraphicsView::wheelEvent([QWheelEvent](https://doc-qt-io.translate.goog/qt-6/qwheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QAbstractScrollArea::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qabstractscrollarea.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)(QWheelEvent *e)。