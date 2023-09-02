#  QGraphicsScene Class

QGraphicsScene 类提供了一个用于管理大量 2D 图形项目的界面。[更多的...](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:   | #include < QGraphicsScene>                                   |
| --------- | ------------------------------------------------------------ |
| CMake:    | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:    | QT += widgets                                                |
| Inherits: | [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[ItemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemIndexMethod-enum)** { BspTreeIndex, NoIndex } |
| ----- | ------------------------------------------------------------ |
| enum  | **[SceneLayer](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum)** { ItemLayer, BackgroundLayer, ForegroundLayer, AllLayers } |
| flags | **[SceneLayers](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum)** |

## 特性

| **[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)** : QBrush**[bspTreeDepth](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bspTreeDepth-prop)** : int**[focusOnTouch](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOnTouch-prop)** : bool**[font](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font-prop)** : QFont**[foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)** : QBrush | **[itemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)** : ItemIndexMethod**[minimumRenderSize](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumRenderSize-prop)** : qreal**[palette](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#palette-prop)** : QPalette**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)** : QRectF**[stickyFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stickyFocus-prop)** : bool |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                                              |                                                              |

## 公共函数

|                                 | **[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsScene)**(QObject **parent* = nullptr) |
| ------------------------------- | ------------------------------------------------------------ |
|                                 | **[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsScene-1)**(const QRectF &*sceneRect*, QObject **parent* = nullptr) |
|                                 | **[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsScene-2)**(qreal *x*, qreal *y*, qreal *width*, qreal *height*, QObject **parent* = nullptr) |
| virtual                         | **[~QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QGraphicsScene)**() |
| QGraphicsItem *                 | **[activePanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activePanel)**() const |
| QGraphicsWidget *               | **[activeWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeWindow)**() const |
| QGraphicsEllipseItem *          | **[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)**(const QRectF &*rect*, const QPen &*pen* = QPen(), const QBrush &*brush* = QBrush()) |
| QGraphicsEllipseItem *          | **[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, const QPen &*pen* = QPen(), const QBrush &*brush* = QBrush()) |
| void                            | **[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)**(QGraphicsItem **item*) |
| QGraphicsLineItem *             | **[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)**(const QLineF &*line*, const QPen &*pen* = QPen()) |
| QGraphicsLineItem *             | **[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine-1)**(qreal *x1*, qreal *y1*, qreal *x2*, qreal *y2*, const QPen &*pen* = QPen()) |
| QGraphicsPathItem *             | **[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)**(const QPainterPath &*path*, const QPen &*pen* = QPen(), const QBrush &*brush* = QBrush()) |
| QGraphicsPixmapItem *           | **[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)**(const QPixmap &*pixmap*) |
| QGraphicsPolygonItem *          | **[addPolygon](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPolygon)**(const QPolygonF &*polygon*, const QPen &*pen* = QPen(), const QBrush &*brush* = QBrush()) |
| QGraphicsRectItem *             | **[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)**(const QRectF &*rect*, const QPen &*pen* = QPen(), const QBrush &*brush* = QBrush()) |
| QGraphicsRectItem *             | **[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, const QPen &*pen* = QPen(), const QBrush &*brush* = QBrush()) |
| QGraphicsSimpleTextItem *       | **[addSimpleText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSimpleText)**(const QString &*text*, const QFont &*font* = QFont()) |
| QGraphicsTextItem *             | **[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)**(const QString &*text*, const QFont &*font* = QFont()) |
| QGraphicsProxyWidget *          | **[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)**(QWidget **widget*, Qt::WindowFlags *wFlags* = Qt::WindowFlags()) |
| QBrush                          | **[backgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)**() const |
| int                             | **[bspTreeDepth](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bspTreeDepth-prop)**() const |
| void                            | **[clearFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)**() |
| QList<QGraphicsItem *>          | **[collidingItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidingItems)**(const QGraphicsItem **item*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QGraphicsItemGroup *            | **[createItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createItemGroup)**(const QList<QGraphicsItem *> &*items*) |
| void                            | **[destroyItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#destroyItemGroup)**(QGraphicsItemGroup **group*) |
| QGraphicsItem *                 | **[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)**() const |
| bool                            | **[focusOnTouch](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOnTouch-prop)**() const |
| QFont                           | **[font](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font-prop)**() const |
| QBrush                          | **[foregroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)**() const |
| bool                            | **[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)**() const |
| qreal                           | **[height](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#height)**() const |
| virtual QVariant                | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *query*) const |
| void                            | **[invalidate](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, QGraphicsScene::SceneLayers *layers* = AllLayers) |
| bool                            | **[isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)**() const |
| QGraphicsItem *                 | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)**(const QPointF &*position*, const QTransform &*deviceTransform*) const |
| QGraphicsItem *                 | **[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt-1)**(qreal *x*, qreal *y*, const QTransform &*deviceTransform*) const |
| QGraphicsScene::ItemIndexMethod | **[itemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)**() const |
| QList<QGraphicsItem *>          | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)**(Qt::SortOrder *order* = Qt::DescendingOrder) const |
| QList<QGraphicsItem *>          | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-1)**(const QPointF &*pos*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape, Qt::SortOrder *order* = Qt::DescendingOrder, const QTransform &*deviceTransform* = QTransform()) const |
| QList<QGraphicsItem *>          | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-2)**(const QRectF &*rect*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape, Qt::SortOrder *order* = Qt::DescendingOrder, const QTransform &*deviceTransform* = QTransform()) const |
| QList<QGraphicsItem *>          | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-3)**(const QPolygonF &*polygon*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape, Qt::SortOrder *order* = Qt::DescendingOrder, const QTransform &*deviceTransform* = QTransform()) const |
| QList<QGraphicsItem *>          | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-4)**(const QPainterPath &*path*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape, Qt::SortOrder *order* = Qt::DescendingOrder, const QTransform &*deviceTransform* = QTransform()) const |
| QList<QGraphicsItem *>          | **[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items-5)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, Qt::ItemSelectionMode *mode*, Qt::SortOrder *order*, const QTransform &*deviceTransform* = QTransform()) const |
| QRectF                          | **[itemsBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsBoundingRect)**() const |
| qreal                           | **[minimumRenderSize](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumRenderSize-prop)**() const |
| QGraphicsItem *                 | **[mouseGrabberItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseGrabberItem)**() const |
| QPalette                        | **[palette](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#palette-prop)**() const |
| void                            | **[removeItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)**(QGraphicsItem **item*) |
| void                            | **[render](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)**(QPainter **painter*, const QRectF &*target* = QRectF(), const QRectF &*source* = QRectF(), Qt::AspectRatioMode *aspectRatioMode* = Qt::KeepAspectRatio) |
| QRectF                          | **[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)**() const |
| QList<QGraphicsItem *>          | **[selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)**() const |
| QPainterPath                    | **[selectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionArea)**() const |
| bool                            | **[sendEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sendEvent)**(QGraphicsItem **item*, QEvent **event*) |
| void                            | **[setActivePanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActivePanel)**(QGraphicsItem **item*) |
| void                            | **[setActiveWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActiveWindow)**(QGraphicsWidget **widget*) |
| void                            | **[setBackgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)**(const QBrush &*brush*) |
| void                            | **[setBspTreeDepth](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bspTreeDepth-prop)**(int *depth*) |
| void                            | **[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)**(Qt::FocusReason *focusReason* = Qt::OtherFocusReason) |
| void                            | **[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)**(QGraphicsItem **item*, Qt::FocusReason *focusReason* = Qt::OtherFocusReason) |
| void                            | **[setFocusOnTouch](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOnTouch-prop)**(bool *enabled*) |
| void                            | **[setFont](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font-prop)**(const QFont &*font*) |
| void                            | **[setForegroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)**(const QBrush &*brush*) |
| void                            | **[setItemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)**(QGraphicsScene::ItemIndexMethod *method*) |
| void                            | **[setMinimumRenderSize](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#minimumRenderSize-prop)**(qreal *minSize*) |
| void                            | **[setPalette](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#palette-prop)**(const QPalette &*palette*) |
| void                            | **[setSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)**(const QRectF &*rect*) |
| void                            | **[setSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) |
| void                            | **[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)**(const QPainterPath &*path*, const QTransform &*deviceTransform*) |
| void                            | **[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea-1)**(const QPainterPath &*path*, Qt::ItemSelectionOperation *selectionOperation* = Qt::ReplaceSelection, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape, const QTransform &*deviceTransform* = QTransform()) |
| void                            | **[setStickyFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stickyFocus-prop)**(bool *enabled*) |
| void                            | **[setStyle](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)**(QStyle **style*) |
| bool                            | **[stickyFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stickyFocus-prop)**() const |
| QStyle *                        | **[style](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)**() const |
| void                            | **[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) |
| QList<QGraphicsView *>          | **[views](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#views)**() const |
| qreal                           | **[width](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)**() const |

## 公共槽

| void | **[advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)**() |
| ---- | ------------------------------------------------------------ |
| void | **[clear](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clear)**() |
| void | **[clearSelection](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)**() |
| void | **[invalidate](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)**(const QRectF &*rect* = QRectF(), QGraphicsScene::SceneLayers *layers* = AllLayers) |
| void | **[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)**(const QRectF &*rect* = QRectF()) |

## 信号

| void | **[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)**(const QList<QRectF> &*region*) |
| ---- | ------------------------------------------------------------ |
| void | **[focusItemChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItemChanged)**(QGraphicsItem **newFocusItem*, QGraphicsItem **oldFocusItem*, Qt::FocusReason *reason*) |
| void | **[sceneRectChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRectChanged)**(const QRectF &*rect*) |
| void | **[selectionChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionChanged)**() |

## protected function

| virtual void | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QGraphicsSceneContextMenuEvent **contextMenuEvent*) |
| ------------ | ------------------------------------------------------------ |
| virtual void | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void | **[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)**(QPainter **painter*, const QRectF &*rect*) |
| virtual void | **[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)**(QPainter **painter*, const QRectF &*rect*) |
| virtual void | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **focusEvent*) |
| virtual void | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **focusEvent*) |
| virtual void | **[helpEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#helpEvent)**(QGraphicsSceneHelpEvent **helpEvent*) |
| virtual void | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **event*) |
| virtual void | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **keyEvent*) |
| virtual void | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **keyEvent*) |
| virtual void | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QGraphicsSceneMouseEvent **mouseEvent*) |
| virtual void | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QGraphicsSceneMouseEvent **mouseEvent*) |
| virtual void | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QGraphicsSceneMouseEvent **mouseEvent*) |
| virtual void | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QGraphicsSceneMouseEvent **mouseEvent*) |
| virtual void | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QGraphicsSceneWheelEvent **wheelEvent*) |

## 重载的protected function

| virtual bool | **[event](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)**(QEvent **event*) override |
| ------------ | ------------------------------------------------------------ |
| virtual bool | **[eventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)**(QObject **watched*, QEvent **event*) override |

## 继承的槽函数

| virtual bool | **[focusNextPrevChild](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusNextPrevChild)**(bool *next*) |
| ------------ | ------------------------------------------------------------ |
|              |                                                              |

## 详细说明

该类充当 QGraphicsItems 的容器。它与一起使用[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于在 2D 表面上可视化图形项目，例如线条、矩形、文本，甚至自定义项目。QGraphicsScene 是[Graphics View Framework](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

QGraphicsScene 还提供了一些功能，可让您有效地确定项目的位置，并确定哪些项目在场景的任意区域内可见。随着[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)小部件，您可以可视化整个场景，也可以放大并仅查看场景的部分内容。

例子：

```
QGraphicsScene scene;
scene.addText("Hello, world!");

QGraphicsView view(&scene);
view.show();
```

**请注意，QGraphicsScene 没有自己的视觉外观；它只管理项目。你需要创建一个[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于可视化场景的小部件。**

要将项目添加到场景中，您首先要构造一个 QGraphicsScene 对象。然后，您有两个选择：要么添加现有的[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过调用对象[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()，或者您可以调用便利函数之一[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addPolygon](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPolygon)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)（）， 或者[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)()，它们都返回一个指向新添加项的指针。使用这些函数添加的项目的尺寸是相对于项目的坐标系的，并且项目位置在场景中初始化为 (0, 0)。

然后您可以使用以下方式可视化场景[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。当场景改变时，（例如，当一个项目移动或变换时）QGraphicsScene 发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)（） 信号。要删除项目，请调用[removeItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)()。

QGraphicsScene 使用索引算法来有效地管理项目的位置。默认情况下，使用BSP（二进制空间分区）树；适用于大多数项目保持静态（即不移动）的大场景的算法。您可以通过调用来选择禁用该索引[setItemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)()。有关可用索引算法的更多信息，请参阅[itemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)财产。

场景的边界矩形通过调用设置[setSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)()。项目可以放置在场景中的任何位置，并且场景的大小默认是无限的。场景矩形仅用于内部簿记，维护场景的项目索引。如果场景矩形未设置，QGraphicsScene 将使用所有项目的边界区域，如[itemsBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsBoundingRect)()，作为场景矩形。然而，[itemsBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemsBoundingRect)() 是一个相对耗时的函数，因为它通过收集场景中每个项目的位置信息来进行操作。因此，在大场景上操作时应始终设置场景矩形。

QGraphicsScene 的最大优势之一是它能够有效地确定项目的位置。即使现场有数百万件物品，[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 函数可以在几毫秒内确定某个项目的位置。有几个重载[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)()：一种在特定位置查找项目的方法，一种在多边形或矩形内部查找或与多边形或矩形相交的项目的方法，等等。返回的项目列表按堆叠顺序排序，最上面的项目是列表中的第一项。为了方便起见，还有一个[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)() 函数返回给定位置的最上面的项目。

QGraphicsScene 维护场景的选择信息。要选择项目，请致电[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()，并清除当前选择，调用[clearSelection](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)()。称呼[selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)() 获取所有选定项目的列表。

### 事件处理和传播

QGraphicsScene 的另一个职责是传播事件[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。要将事件发送到场景，您可以构造一个继承的事件[QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，然后使用以下命令发送：[QCoreApplication::sendEvent](https://doc-qt-io.translate.goog/qt-6/qcoreapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sendEvent)()。[event](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)() 负责将事件分派到各个项目。一些常见事件由便利事件处理程序处理。例如，按键事件由[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)()，鼠标按下事件由[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)()。

关键事件被传递到*焦点项目*。要设置焦点项目，您可以调用[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)()，传递一个接受焦点的item，或者item本身可以调用[QGraphicsItem::setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)()。称呼[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)() 获取当前焦点项目。为了与小部件兼容，场景还维护自己的焦点信息。默认情况下，场景没有焦点，所有关键事件都会被丢弃。如果[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)() 被调用，或者如果场景中的某个项目获得焦点，则场景会自动获得焦点。如果场景有焦点，[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)() 将返回 true，并且关键事件将被转发到焦点项（如果有）。如果场景失去焦点（即有人打电话[clearFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)()) 当某个项目获得焦点时，场景将维护其项目焦点信息，一旦场景重新获得焦点，它将确保最后一个焦点项目重新获得焦点。

对于鼠标悬停效果，QGraphicsScene 调度*悬停事件*。如果某个项目接受悬停事件（请参阅[QGraphicsItem::acceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptHoverEvents)())，它将收到一个[GraphicsSceneHoverEnter](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)当鼠标进入其区域时发生事件。当鼠标继续在项目区域内移动时，QGraphicsScene 将发送它[GraphicsSceneHoverMove](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件。当鼠标离开该项目的区域时，该项目将收到一个[GraphicsSceneHoverLeave](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件。

所有鼠标事件都会传递到当前*鼠标抓取器*项。如果某个项目接受鼠标事件，则该项目将成为场景的鼠标抓取器（请参阅[QGraphicsItem::acceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptedMouseButtons)()) 并且它接收到鼠标按下。它保持鼠标抓取器状态，直到在没有按下其他鼠标按钮时收到鼠标释放。您可以致电[mouseGrabberItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseGrabberItem)() 来判断当前鼠标抓取的是哪个项目。

**可以查阅**[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QGraphicsScene::ItemIndexMethod

该枚举描述了索引算法[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供管理有关场景上的项目的位置信息。

| 持续的                         | 价值 | 描述                                                         |
| ------------------------------ | ---- | ------------------------------------------------------------ |
| `QGraphicsScene::BspTreeIndex` | `0`  | 应用二元空间分区树。全部[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过使用二分搜索，项目定位算法的复杂度接近对数。添加、移动和删除项目是对数的。此方法最适合静态场景（即大多数项目不移动的场景）。 |
| `QGraphicsScene::NoIndex`      | `-1` | 不应用任何索引。项目位置具有线性复杂度，因为场景中的所有项目都会被搜索。然而，添加、移动和删除项目是在恒定时间内完成的。这种方法非常适合动态场景，其中许多项目被连续添加、移动或删除。 |

**可以查阅**[setItemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)（） 和[bspTreeDepth](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bspTreeDepth-prop)。

### 枚举 QGraphicsScene:: SceneLayer 标志 QGraphicsScene:: SceneLayers

该枚举描述了渲染层[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。什么时候[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制场景内容，它按顺序单独渲染每个层。

每层代表一个标志，在调用诸如[invalidate](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)（） 或者[QGraphicsView::invalidateScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidateScene)()。

| 持续的                            | 价值     | 描述                                                         |
| --------------------------------- | -------- | ------------------------------------------------------------ |
| `QGraphicsScene::ItemLayer`       | `0x1`    | 项目层。[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过调用虚函数drawItems()来渲染该层中的所有项目。项目图层绘制在背景图层之后、前景图层之前。 |
| `QGraphicsScene::BackgroundLayer` | `0x2`    | 背景层。[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过调用虚函数来渲染本层场景的背景[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)()。首先绘制背景层。 |
| `QGraphicsScene::ForegroundLayer` | `0x4`    | 前景层。[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过调用虚函数来渲染本层场景的前景[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)()。前景层是所有层中最后绘制的。 |
| `QGraphicsScene::AllLayers`       | `0xffff` | 所有层；该值代表所有三层的组合。                             |

SceneLayers 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) < SceneLayer> 的类型定义。它存储 SceneLayer 值的 OR 组合。

**可以查阅**[invalidate](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidate)（） 和[QGraphicsView::invalidateScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#invalidateScene)()。

## 属性文档

### backgroundBrush : [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景的背景画笔。

设置此属性可将场景的背景更改为不同的颜色、渐变或纹理。默认背景画笔是[Qt::NoBrush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)。背景绘制在项目之前（之后）。

例子：

```
QGraphicsScene scene;
QGraphicsView view(&scene);
view.show();

// a blue background
scene.setBackgroundBrush(Qt::blue);

// a gradient background
QRadialGradient gradient(0, 0, 10);
gradient.setSpread(QGradient::RepeatSpread);
scene.setBackgroundBrush(gradient);
```

[QGraphicsScene::render](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)() 调用[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)() 绘制场景背景。要更详细地控制背景的绘制方式，您可以重新实现[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)() 的子类[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**访问功能：**

| QBrush | **backgroundBrush**() const                   |
| ------ | --------------------------------------------- |
| void   | **setBackgroundBrush**(const QBrush &*brush*) |

### bspTreeDepth : int

该属性拥有的深度[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的BSP索引树

该属性在以下情况下无效：[NoIndex](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemIndexMethod-enum)用来。

该值决定了深度[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的 BSP 树。深度直接影响[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的性能和内存使用情况；后者随着树的深度呈指数增长。具有最佳的树深度，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)即使对于具有数千或数百万个项目的场景，也可以立即确定项目的位置。这也大大提高了渲染性能。

默认情况下，该值为 0，在这种情况下，Qt 将根据场景中项目的大小、位置和数量猜测合理的默认深度。但是，如果这些参数频繁更改，您可能会遇到速度减慢的情况：[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在内部重新调整深度。您可以通过设置此属性来固定树深度，从而避免潜在的速度下降。

树的深度和场景矩形的大小决定了场景划分的粒度。每个场景片段的大小由以下算法确定：

```
QSizeF segmentSize = sceneRect().size() / pow(2, depth - 1);
```

当每个段包含 0 到 10 个项目时，BSP 树具有最佳大小。

**访问功能：**

| int  | **bspTreeDepth**() const         |
| ---- | -------------------------------- |
| void | **setBspTreeDepth**(int *depth*) |

**可以查阅**[itemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemIndexMethod-prop)。

### focusOnTouch : bool

*该属性保存项目在接收触摸开始*事件时是否获得焦点。

通常的行为是仅在单击某个项目时才转移焦点。通常，操作系统将触摸板上的点击解释为相当于鼠标单击，从而生成合成的单击事件作为响应。但是，至少在 macOS 上您可以配置此行为。

默认情况下，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当您触摸触控板或类似设备时也会转移焦点。如果操作系统配置为在点击触控板时不生成合成鼠标点击，则这是令人惊讶的。如果操作系统确实在点击触控板时生成合成鼠标点击，则无需启动触摸手势时进行焦点转移。

当 focusOnTouch 关闭时，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)其行为与 macOS 上的预期一致。

默认值为`true`，确保默认行为与 5.12 之前的 Qt 版本相同。设置为`false`以防止触摸事件触发焦点变化。

**访问功能：**

| bool | **focusOnTouch**() const            |
| ---- | ----------------------------------- |
| void | **setFocusOnTouch**(bool *enabled*) |

### font : [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景的默认字体

该属性提供场景的字体。场景字体默认为，并解析其所有条目，[QApplication::font](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)。

如果场景的字体发生变化，直接通过 setFont() 或在应用程序字体发生变化时间接发生，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)首先给自己发送一个[FontChange](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件，然后发送[FontChange](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)场景中所有顶级小部件项目的事件。这些项目通过将自己的字体解析到场景来做出响应，然后通知其子项，子项再通知其子项，依此类推，直到所有小部件项都更新了其字体。

改变场景字体，（直接或间接通过[QApplication::setFont](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)(),) 自动安排重绘整个场景。

**访问功能：**

| QFont | **font**() const                 |
| ----- | -------------------------------- |
| void  | **setFont**(const QFont &*font*) |

**可以查阅**[QWidget::font](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font-prop),[QApplication::setFont](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFont)(),[palette](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#palette-prop)， 和[style](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()。

### foregroundBrush : [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景的前景画笔。

更改此属性可将场景的前景设置为不同的颜色、渐变或纹理。

前景绘制在项目之后（之上）。默认的前景画笔是[Qt::NoBrush](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#BrushStyle-enum)（即前景未绘制）。

例子：

```
QGraphicsScene scene;
QGraphicsView view(&scene);
view.show();

// a white semi-transparent foreground
scene.setForegroundBrush(QColor(255, 255, 255, 127));

// a grid foreground
scene.setForegroundBrush(QBrush(Qt::lightGray, Qt::CrossPattern));
```

[QGraphicsScene::render](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)() 调用[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)() 绘制场景前景。要更详细地控制前景的绘制方式，您可以重新实现[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)() 函数在[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类。

**访问功能：**

| QBrush | **foregroundBrush**() const                   |
| ------ | --------------------------------------------- |
| void   | **setForegroundBrush**(const QBrush &*brush*) |

### itemIndexMethod : [ItemIndexMethod](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemIndexMethod-enum)

该属性保存项目索引方法。

[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将索引算法应用于场景，以加速项目发现功能，例如[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 和[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)()。索引对于静态场景（即项目不移动的场景）最有效。对于动态场景或具有许多动画项目的场景，索引簿记可能比快速查找速度更重要。

对于常见情况，默认索引方法[BspTreeIndex](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemIndexMethod-enum)工作正常。如果您的场景使用许多动画并且您遇到缓慢的情况，您可以通过调用 来禁用索引`setItemIndexMethod(NoIndex)`。

**访问功能：**

| QGraphicsScene::ItemIndexMethod | **itemIndexMethod**() const                                  |
| ------------------------------- | ------------------------------------------------------------ |
| void                            | **setItemIndexMethod**(QGraphicsScene::ItemIndexMethod *method*) |

**可以查阅**[bspTreeDepth](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#bspTreeDepth-prop)。

### minimumRenderSize : [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef)

此属性保存必须绘制的项目的最小视图转换大小

渲染场景时，转换为目标视图后宽度或高度小于minimumRenderSize() 的任何项目都不会被渲染。如果某个项目未渲染并且它剪辑了其子项目，那么它们也将不会被渲染。设置此值可加快在缩小视图上渲染许多对象的场景的渲染速度。

默认值为 0。如果未设置，或者设置为 0 或负值，则将始终渲染所有项目。

例如，如果场景由多个视图渲染，其中一个视图充当始终显示所有项目的概述，则设置此属性可能特别有用。在具有许多项目的场景中，此类视图将使用高缩放因子，以便可以显示所有项目。由于缩放，较小的项目只会对最终渲染的场景产生微不足道的贡献。为了避免绘制这些项目并减少渲染场景所需的时间，您可以使用非负值调用 setMinimumRenderSize()。

**注意：**由于太小而没有绘制的项目，仍然可以通过以下方法返回[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 和[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)()，并参与碰撞检测和交互。建议您将minimumRenderSize() 设置为小于或等于1 的值，以避免交互式的大型未渲染项目。

**访问功能：**

| qreal | **minimumRenderSize**() const             |
| ----- | ----------------------------------------- |
| void  | **setMinimumRenderSize**(qreal *minSize*) |

**可以查阅**[QStyleOptionGraphicsItem::levelOfDetailFromTransform](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#levelOfDetailFromTransform)()。

### palette : [QPalette](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景的默认调色板

该属性提供场景的调色板。场景调色板默认为，并解析其所有条目，[QApplication::palette](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#palette)。

如果场景的调色板发生变化，无论是直接通过 setPalette() 还是在应用程序调色板发生变化时间接发生，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)首先给自己发送一个[PaletteChange](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件，然后发送[PaletteChange](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)场景中所有顶级小部件项目的事件。这些项目通过将自己的调色板解析为场景来做出响应，然后通知其子项，子项再通知其子项，依此类推，直到所有小部件项都更新了其调色板。

更改场景调色板，（直接或间接通过[QApplication::setPalette](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPalette)(),) 自动安排重绘整个场景。

**访问功能：**

| QPalette | **palette**() const                       |
| -------- | ----------------------------------------- |
| void     | **setPalette**(const QPalette &*palette*) |

**可以查阅**[QWidget::palette](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#palette-prop),[QApplication::setPalette](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPalette)(),[font](https://doc-qt-io.translate.goog/qt-6/stylesheet-reference.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#font)， 和[style](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()。

### sceneRect : [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

该属性保存场景矩形；场景的边界矩形

场景矩形定义了场景的范围。它主要用于[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)确定视图的默认可滚动区域，并通过[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)管理项目索引。

如果未设置，或者设置为 null[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， sceneRect() 将返回自场景创建以来场景中所有项目的最大边界矩形（即，当项目添加到场景或在场景中移动时会增大的矩形，但不会缩小）。

**访问功能：**

| QRectF | **sceneRect**() const                                        |
| ------ | ------------------------------------------------------------ |
| void   | **setSceneRect**(const QRectF &*rect*)                       |
| void   | **setSceneRect**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) |

**可以查阅**[width](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)(),[height](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#height)（）， 和[QGraphicsView::sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)。

### stickyFocus : bool

该属性保存点击场景背景是否会清除焦点

在一个[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将 StickyFocus 设置为 true 时，当用户单击场景背景或不接受焦点的项目时，焦点将保持不变。否则，焦点将被清除。

默认情况下，该属性为`false`。

焦点随着鼠标按下而改变。你可以重新实现[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)() 的子类[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)根据用户单击的位置切换此属性。

**访问功能：**

| bool | **stickyFocus**() const            |
| ---- | ---------------------------------- |
| void | **setStickyFocus**(bool *enabled*) |

**可以查阅**[clearFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)（） 和[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)()。

## 成员函数文档

### QGraphicsScene::QGraphicsScene([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

构造一个 QGraphicsScene 对象。这*parent*参数被传递到[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的构造函数。

### QGraphicsScene::QGraphicsScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*sceneRect*, [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

构造一个 QGraphicsScene 对象，使用*sceneRect*为其场景矩形。这*parent*参数被传递到[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的构造函数。

**可以查阅**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)。

### QGraphicsScene::QGraphicsScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *width*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *height*, [QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **parent* = nullptr)

使用 ( 指定的矩形构造 QGraphicsScene 对象*x*,*y*），以及给定的*width*和*height*为其场景矩形。这*parent*参数被传递到[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的构造函数。

**可以查阅**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)。

### `[virtual]`QGraphicsScene::~QGraphicsScene()

在销毁场景对象之前从场景对象中移除并删除所有项目。该场景对象将从应用程序的全局场景列表中删除，并从所有关联的视图中删除。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::activePanel() const

返回当前活动面板，或者`nullptr`当前没有活动面板。

**可以查阅**[QGraphicsScene::setActivePanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActivePanel)()。

### [QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::activeWindow() const

返回当前活动窗口，或者`nullptr`当前没有活动窗口。

**可以查阅**[QGraphicsScene::setActiveWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActiveWindow)()。

### [QGraphicsEllipseItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsellipseitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addEllipse(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen(), const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush* = QBrush())

创建椭圆项目并将其添加到场景中，并返回项目指针。椭圆的几何形状定义为*rect*，其笔和画笔被初始化为*pen*和*brush*。

请注意，项目的几何形状在项目坐标中提供，并且其位置初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsEllipseItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsellipseitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addEllipse([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen(), const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush* = QBrush())

这个便利函数相当于调用 addEllipse([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*pen*,*brush*）。

### void QGraphicsScene::addItem([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

添加或移动*item*和它所有的孩子都看到了这一幕。该场景拥有*item*。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回 true),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

如果该项目已经在不同的场景中，它将首先从旧场景中删除，然后作为顶层添加到该场景中。

[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将发送 ItemSceneChange 通知到*item*当它被添加到场景中时。如果项目当前不属于场景，则仅发送一个通知。如果它确实已经属于场景（即，它被移动到这个场景），[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当该项目从之前的场景中删除时，将发送添加通知。

如果该项目是面板，场景处于活动状态，并且场景中没有活动面板，则该项目将被激活。

**可以查阅**[removeItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)(),[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QGraphicsLineItem](https://doc-qt-io.translate.goog/qt-6/qgraphicslineitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addLine(const [QLineF](https://doc-qt-io.translate.goog/qt-6/qlinef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*line*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen())

创建行项目并将其添加到场景中，并返回项目指针。线的几何形状定义为*line*，其笔被初始化为*pen*。

请注意，项目的几何形状在项目坐标中提供，并且其位置初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsLineItem](https://doc-qt-io.translate.goog/qt-6/qgraphicslineitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addLine([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x1*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y1*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x2*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y2*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen())

这个便利函数相当于调用 addLine([QLineF](https://doc-qt-io.translate.goog/qt-6/qlinef.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x1*,*y1*,*x2*,*y2*),*pen*）。

### [QGraphicsPathItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspathitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addPath(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen(), const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush* = QBrush())

创建路径项并将其添加到场景中，并返回项指针。路径的几何形状定义为*path*，其笔和画笔被初始化为*pen*和*brush*。

请注意，项目的几何形状在项目坐标中提供，并且其位置初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsPixmapItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspixmapitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addPixmap(const [QPixmap](https://doc-qt-io.translate.goog/qt-6/qpixmap.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pixmap*)

创建像素图项目并将其添加到场景中，并返回项目指针。像素图定义为*pixmap*。

请注意，项目的几何形状在项目坐标中提供，并且其位置初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsPolygonItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspolygonitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addPolygon(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen(), const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush* = QBrush())

创建多边形项目并将其添加到场景中，并返回项目指针。多边形定义为*polygon*，其笔和画笔被初始化为*pen*和*brush*。

请注意，项目的几何形状在项目坐标中提供，并且其位置初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPath)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsRectItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsrectitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addRect(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen(), const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush* = QBrush())

创建一个矩形项目并将其添加到场景中，并返回项目指针。矩形的几何形状定义为*rect*，其笔和画笔被初始化为*pen*和*brush*。

请注意，项目的几何形状在项目坐标中提供，并且其位置初始化为 (0, 0)。例如，如果一个[QRect](https://doc-qt-io.translate.goog/qt-6/qrect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)添加 (50, 50, 100, 100) 后，其左上角将位于相对于项目坐标系中原点的 (50, 50) 处。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsRectItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsrectitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addRect([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, const [QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pen* = QPen(), const [QBrush](https://doc-qt-io.translate.goog/qt-6/qbrush.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*brush* = QBrush())

这个便利函数相当于调用 addRect([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*pen*,*brush*）。

### [QGraphicsSimpleTextItem](https://doc-qt-io.translate.goog/qt-6/qgraphicssimpletextitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addSimpleText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font* = QFont())

创建并添加一个[QGraphicsSimpleTextItem](https://doc-qt-io.translate.goog/qt-6/qgraphicssimpletextitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)到场景，并返回项目指针。文本字符串被初始化为*text*，其字体被初始化为*font*。

该项目的位置被初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsTextItem](https://doc-qt-io.translate.goog/qt-6/qgraphicstextitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addText(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*text*, const [QFont](https://doc-qt-io.translate.goog/qt-6/qfont.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*font* = QFont())

创建文本项并将其添加到场景中，并返回项指针。文本字符串被初始化为*text*，其字体被初始化为*font*。

该项目的位置被初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（）， 和[addWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addWidget)()。

### [QGraphicsProxyWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsproxywidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::addWidget([QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*, [Qt::WindowFlags](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum) *wFlags* = Qt::WindowFlags())

创建一个新的[QGraphicsProxyWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsproxywidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)为了*widget*，将其添加到场景中，并返回指向代理的指针。*wFlags*设置嵌入代理小部件的默认窗口标志。

该项目的位置被初始化为 (0, 0)。

如果该项目可见（即[QGraphicsItem::isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`true`),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会发出[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)() 一旦控制返回到事件循环。

请注意，小部件带有[Qt::WA_PaintOnScreen](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WidgetAttribute-enum)不支持小部件属性集和包装外部应用程序或控制器的小部件。示例有 QOpenGLWidget 和 QAxWidget。

**可以查阅**[addEllipse](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addEllipse)(),[addLine](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addLine)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addPixmap](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addPixmap)(),[addRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addRect)(),[addText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addText)(),[addSimpleText](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addSimpleText)（）， 和[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### `[slot]`void QGraphicsScene::advance()

该槽通过调用将场景*推进一步*[QGraphicsItem::advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)() 代表场景中的所有物品。这是分两个阶段完成的：在第一阶段，所有项目都被通知场景即将改变，而在第二阶段，所有项目都被通知它们可以移动。在第一阶段，[QGraphicsItem::advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)() 被称为传递值 0 作为参数，而在第二阶段传递 1。

请注意，您还可以使用[Animation Framework](https://doc-qt-io.translate.goog/qt-6/animation-overview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于动画。

**可以查阅**[QGraphicsItem::advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)（） 和[QTimeLine](https://doc-qt-io.translate.goog/qt-6/qtimeline.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[signal]`void QGraphicsScene::changed(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)> &*region*)

该信号由[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)当控制到达事件循环时，如果场景内容发生变化。这*region*参数包含场景矩形列表，指示已更改的区域。

**可以查阅**[QGraphicsView::updateScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateScene)()。

### `[slot]`void QGraphicsScene::clear()

从场景中移除并删除所有项目，但保持场景状态不变。

**可以查阅**[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### void QGraphicsScene::clearFocus()

将焦点从场景中清除。如果调用此函数时任何项目具有焦点，它将失去焦点，并在场景重新获得焦点时再次重新获得焦点。

没有焦点的场景会忽略关键事件。

**可以查阅**[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)（）， 和[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)()。

### `[slot]`void QGraphicsScene::clearSelection()

清除当前选择。

**可以查阅**[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)（） 和[selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::collidingItems(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

返回发生碰撞的所有项目的列表*item*。碰撞是通过调用来确定的[QGraphicsItem::collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)(); 碰撞检测由下式确定*mode*。默认情况下，形状相交的所有项目*item*或者包含在里面*item*的形状被返回。

项目按降序堆叠顺序返回（即列表中的第一项是最上面的项目，最后一个项目是最下面的项目）。

**可以查阅**[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)(),[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)(),[QGraphicsItem::collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### `[virtual protected]`void QGraphicsScene::contextMenuEvent([QGraphicsSceneContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenecontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **contextMenuEvent*)

该事件处理程序，用于事件*contextMenuEvent*，可以在子类中重新实现以接收上下文菜单事件。默认实现将事件转发到最上面的可见项，该项在事件的位置接受上下文菜单事件。如果在此位置没有项目接受上下文菜单事件，则该事件将被忽略。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[QGraphicsItem::contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)()。

### [QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::createItemGroup(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> &*items*)

将所有项目分组*items*进入一个新的[QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，并返回指向该组的指针。该团体是由共同祖先创建的*items*作为其父级，位置为 (0, 0)。这些项目全部重新设置为该组的父级，并且它们的位置和变换也映射到该组。如果*items*为空，该函数将返回一个空的顶层[QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)拥有该组项目的所有权；您不需要删除它。要解散（取消分组）群组，请致电[destroyItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#destroyItemGroup)()。

**可以查阅**[destroyItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#destroyItemGroup)（） 和[QGraphicsItemGroup::addToGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addToGroup)()。

### void QGraphicsScene::destroyItemGroup([QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **group*)

重新设置所有项目的父级*group*到*group*的父项，然后删除*group*从场景中删除，最后将其删除。项目的位置和变换从组映射到组的父项。

**可以查阅**[createItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createItemGroup)（） 和[QGraphicsItemGroup::removeFromGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeFromGroup)()。

### `[virtual protected]`void QGraphicsScene::dragEnterEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以在子类中重新实现以接收场景的拖动输入事件。

默认实现接受该事件并准备场景以接受拖动移动事件。

**可以查阅**[QGraphicsItem::dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)(),[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)(),[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（）， 和[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)()。

### `[virtual protected]`void QGraphicsScene::dragLeaveEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以在子类中重新实现以接收场景的拖动离开事件。

**可以查阅**[QGraphicsItem::dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)(),[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)(),[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（）， 和[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)()。

### `[virtual protected]`void QGraphicsScene::dragMoveEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以在子类中重新实现以接收场景的拖动移动事件。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[QGraphicsItem::dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)(),[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)(),[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)（）， 和[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)()。

### `[virtual protected]`void QGraphicsScene::drawBackground([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

使用绘制场景的背景*painter*，在绘制任何项目和前景之前。重新实现此函数以为场景提供自定义背景。

所有绘画都是在*场景*坐标中完成的。这*rect*参数是暴露的矩形。

如果您只想定义背景的颜色、纹理或渐变，您可以调用[setBackgroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#backgroundBrush-prop)（） 反而。

**可以查阅**[drawForeground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawForeground)（） 和[drawItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawItems)()。

### `[virtual protected]`void QGraphicsScene::drawForeground([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

使用以下方法绘制场景的前景*painter*，在绘制背景和所有项目之后。重新实现此函数以为场景提供自定义前景。

所有绘画都是在*场景*坐标中完成的。这*rect*参数是暴露的矩形。

如果您只想为前景定义颜色、纹理或渐变，您可以调用[setForegroundBrush](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#foregroundBrush-prop)（） 反而。

**可以查阅**[drawBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawBackground)（） 和[drawItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#drawItems)()。

### `[virtual protected]`void QGraphicsScene::dropEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以在子类中重新实现以接收场景的放置事件。

**可以查阅**[QGraphicsItem::dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)(),[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)(),[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（）， 和[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)()。

### `[override virtual protected]`bool QGraphicsScene::event([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QObject::event](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#event)（QEvent *e）。

处理事件*event*，并将其分派给相应的事件处理程序。

除了调用便利的事件处理程序之外，此函数还负责在没有鼠标抓取器项目时将鼠标移动事件转换为悬停事件。悬停事件直接传递给项目；他们没有便利的功能。

不像[QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不具备便利功能[enterEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#enterEvent)（） 和[leaveEvent](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#leaveEvent)()。使用此函数来获取这些事件。

返回`true`如果*event*已被识别和处理；否则，返回`false`。

**可以查阅**

[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)(),[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)(),[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)(),[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(),[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)(),[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（）， 和[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)()。

### `[override virtual protected]`bool QGraphicsScene::eventFilter([QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QObject) **watched*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

重新实现：[QObject::eventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#eventFilter)（QObject *观看，QEvent *事件）。

[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)过滤器[QApplication](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的事件来检测调色板和字体更改。

### `[virtual protected]`void QGraphicsScene::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **focusEvent*)

该事件处理程序，用于事件*focusEvent*，可以在子类中重新实现以接收事件焦点。

默认实现将焦点设置在场景上，然后设置在最后一个焦点项目上。

**可以查阅**[QGraphicsItem::focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::focusItem() const

当场景处于活动状态时，此函数返回场景的当前焦点项目，或者`nullptr`当前没有项目具有焦点。当场景处于非活动状态时，此函数返回当场景变为活动状态时将获得输入焦点的项目。

当场景接收到按键事件时，焦点项接收键盘输入。

**可以查阅**[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)(),[QGraphicsItem::hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)（）， 和[isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### `[signal]`void QGraphicsScene::focusItemChanged([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **newFocusItem*, [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **oldFocusItem*, [Qt::FocusReason](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusReason-enum) *reason*)

该信号由[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)每当场景中焦点发生变化时（即，当某个项目获得或失去输入焦点时，或者当焦点从一个项目传递到另一个项目时）。如果您需要跟踪其他项目何时获得输入焦点，您可以连接到此信号。它对于实现虚拟键盘、输入法和光标项特别有用。

*oldFocusItem*是指向先前获得焦点的项目的指针，如果在发出信号之前没有项目获得焦点，则为 0。*newFocusItem*`nullptr`是指向获得输入焦点或失去焦点的项目的指针。*reason*是焦点变化的原因（例如，如果场景在输入字段具有焦点时被停用，*oldFocusItem*将指向输入字段项，*newFocusItem*会是`nullptr`，并且*reason*将会[Qt::ActiveWindowFocusReason](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusReason-enum)。

### `[virtual protected slot]`bool QGraphicsScene::focusNextPrevChild(bool *next*)

查找一个新的小部件以赋予键盘焦点（适用于 Tab 和 Shift+Tab），`true`如果可以找到新的小部件则返回，如果不能找到则返回 false。如果*next*为 true，该函数向前搜索；如果*next*为 false，则向后搜索。

您可以在子类中重新实现此函数[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供对选项卡焦点如何在场景内传递的细粒度控制。默认实现基于选项卡焦点链定义[QGraphicsWidget::setTabOrder](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTabOrder)()。

### `[virtual protected]`void QGraphicsScene::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **focusEvent*)

该事件处理程序，用于事件*focusEvent*，可以在子类中重新实现以接收焦点移出事件。

默认实现会从任何焦点项目中删除焦点，然后从场景中删除焦点。

**可以查阅**[QGraphicsItem::focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)()。

### bool QGraphicsScene::hasFocus() const

返回`true`场景是否有焦点；否则返回`false`. 如果场景有焦点，则会转发来自的关键事件[QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)任何有焦点的项目。

**可以查阅**[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)（） 和[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsScene::height() const

这个便利功能相当于调用`sceneRect().height()`.

**可以查阅**[width](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)()。

### `[virtual protected]`void QGraphicsScene::helpEvent([QGraphicsSceneHelpEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **helpEvent*)

该事件处理程序，用于事件*helpEvent*，可以在子类中重新实现以接收帮助事件。事件的类型[QEvent::ToolTip](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)，它们是在请求工具提示时创建的。

默认实现在鼠标光标位置显示最顶部可见项目（即具有最高 z 值的项目）的工具提示。如果没有项目设置了工具提示，则此函数不执行任何操作。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[QGraphicsItem::toolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip)（） 和[QGraphicsSceneHelpEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehelpevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[virtual protected]`void QGraphicsScene::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以在子类中重新实现以接收场景的输入法事件。

默认实现将事件转发到[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)()。如果当前没有项目具有焦点或当前焦点项目不接受输入法，则此函数不执行任何操作。

**可以查阅**[QGraphicsItem::inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)()。

### `[virtual]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsScene::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *query*) const

输入法使用此方法来查询场景的一组属性，以便能够支持复杂的输入法操作，如对周围文本和重新转换的支持。

这*query*参数指定查询哪个属性。

**可以查阅**[QWidget::inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)()。

### `[slot]`void QGraphicsScene::invalidate(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF(), [QGraphicsScene::SceneLayers](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum) *layers* = AllLayers)

无效并安排重绘*layers*在*rect*在现场。任何缓存的内容*layers*无条件无效并重新绘制。

您可以使用此函数重载来通知[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)场景背景或前景的变化。此功能通常用于具有基于平铺背景的场景，以在以下情况下通知更改：[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)已启用[CacheBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)。

例子：

```
QRectF TileScene::rectForTile(int x, int y) const
{
    // Return the rectangle for the tile at position (x, y).
    return QRectF(x * tileWidth, y * tileHeight, tileWidth, tileHeight);
}

void TileScene::setTile(int x, int y, const QPixmap &pixmap)
{
    // Sets or replaces the tile at position (x, y) with pixmap.
    if (x >= 0 && x < numTilesH && y >= 0 && y < numTilesV) {
        tiles[y][x] = pixmap;
        invalidate(rectForTile(x, y), BackgroundLayer);
    }
}

void TileScene::drawBackground(QPainter *painter, const QRectF &exposed)
{
    // Draws all tiles that intersect the exposed area.
    for (int y = 0; y < numTilesV; ++y) {
        for (int x = 0; x < numTilesH; ++x) {
            QRectF rect = rectForTile(x, y);
            if (exposed.intersects(rect))
                painter->drawPixmap(rect.topLeft(), tiles[y][x]);
        }
    }
}
```

注意[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)目前仅支持后台缓存（请参阅[QGraphicsView::CacheBackground](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheModeFlag-enum)）。该函数相当于调用[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 如果任何层但是[BackgroundLayer](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum)已通过。

**可以查阅**[QGraphicsView::resetCachedContent](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetCachedContent)()。

### void QGraphicsScene::invalidate([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, [QGraphicsScene::SceneLayers](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SceneLayer-enum) *layers* = AllLayers)

这是一个过载功能。

这个便利函数相当于调用 invalidate([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*layers*）；

### bool QGraphicsScene::isActive() const

返回`true`场景是否处于活动状态（例如，至少有一个人查看过该场景）[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)处于活动状态）；否则返回`false`.

**可以查阅**[QGraphicsItem::isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)（） 和[QWidget::isActiveWindow](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActiveWindow-prop)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::itemAt(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*position*, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform*) const

返回指定位置最上面的可见项*position*，或者`nullptr`如果该位置没有项目。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)(),[collidingItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidingItems)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::itemAt([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform*) const

这是一个过载功能。

返回由 ( 指定的位置处最上面的可见项*x*,*y*)，或者`nullptr`如果该位置没有项目。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

这个便利功能相当于调用`itemAt(QPointF(x, y), deviceTransform)`.

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::items([Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::DescendingOrder) const

返回场景中所有项目的有序列表。*order*决定堆叠顺序。

**可以查阅**[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)(),[removeItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeItem)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::items(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::DescendingOrder, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform* = QTransform()) const

返回所有可见项目，具体取决于*mode*，在指定的*pos*在使用排序的列表中*order*。在这种情况下，“visible”定义以下项： isVisible() 返回`true`， effectiveOpacity() 返回大于 0.0 的值（完全透明）并且父项不会对其进行裁剪。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与相交的所有项目*pos*被退回。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

**可以查阅**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::items(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::DescendingOrder, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform* = QTransform()) const

这是一个过载功能。

返回所有可见项目，具体取决于*mode*，要么在指定的内部，要么与指定的相交*rect*，在使用排序的列表中*order*。在这种情况下，“visible”定义以下项： isVisible() 返回`true`， effectiveOpacity() 返回大于 0.0 的值（完全透明）并且父项不会对其进行裁剪。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与 相交或包含于 的所有项目*rect*被退回。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

**可以查阅**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::items(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::DescendingOrder, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform* = QTransform()) const

这是一个过载功能。

返回所有可见项目，具体取决于*mode*，要么在指定的内部，要么与指定的相交*polygon*，在使用排序的列表中*order*。在这种情况下，“visible”定义以下项： isVisible() 返回`true`， effectiveOpacity() 返回大于 0.0 的值（完全透明）并且父项不会对其进行裁剪。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与 相交或包含于 的所有项目*polygon*被退回。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

**可以查阅**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::items(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order* = Qt::DescendingOrder, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform* = QTransform()) const

这是一个过载功能。

返回所有可见项目，具体取决于*mode*，要么在指定的内部，要么与指定的相交*path*，在使用排序的列表中*order*。在这种情况下，“visible”定义以下项： isVisible() 返回`true`， effectiveOpacity() 返回大于 0.0 的值（完全透明）并且父项不会对其进行裁剪。

默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum); 其确切形状与 相交或包含于 的所有项目*path*被退回。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

**可以查阅**[itemAt](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemAt)（） 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::items([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode*, [Qt::SortOrder](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#SortOrder-enum) *order*, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform* = QTransform()) const

这是一个过载功能。

返回所有可见项目，具体取决于*mode*，要么在由 定义的矩形内部，要么与该矩形相交*x*,*y*,*w*和*h*，在使用排序的列表中*order*。在这种情况下，“visible”定义以下项： isVisible() 返回`true`， effectiveOpacity() 返回大于 0.0 的值（完全透明）并且父项不会对其进行裁剪。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsScene::itemsBoundingRect() const

计算并返回场景中所有项目的边界矩形。此函数通过迭代所有项目来工作，因此，对于大型场景来说，它可能会很慢。

**可以查阅**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)()。

### `[virtual protected]`void QGraphicsScene::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **keyEvent*)

该事件处理程序，用于事件*keyEvent*，可以在子类中重新实现以接收按键事件。默认实现将事件转发到当前焦点项目。

**可以查阅**[QGraphicsItem::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（） 和[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)()。

### `[virtual protected]`void QGraphicsScene::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **keyEvent*)

该事件处理程序，用于事件*keyEvent*，可以在子类中重新实现以接收按键释放事件。默认实现将事件转发到当前焦点项目。

**可以查阅**[QGraphicsItem::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)（） 和[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)()。

### `[virtual protected]`void QGraphicsScene::mouseDoubleClickEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **mouseEvent*)

该事件处理程序，用于事件*mouseEvent*，可以在子类中重新实现以接收场景的鼠标双击事件。

如果有人双击场景，场景将首先接收鼠标按下事件，然后是释放事件（即单击），然后是双击事件，最后是释放事件。如果双击事件传递到与接收到第一次按下和释放的项目不同的项目，则它将作为按下事件传递。但是，在这种情况下，三次单击事件不会作为双击事件传递。

默认实现类似于[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)()。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[QGraphicsItem::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[QGraphicsItem::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[QGraphicsItem::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（）， 和[QGraphicsItem::setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::mouseGrabberItem() const

返回当前的鼠标抓取器项目，或者`nullptr`如果当前没有项目抓取鼠标。鼠标抓取器项是接收发送到场景的所有鼠标事件的项。

当一个项目接收并接受鼠标按下事件时，它就成为鼠标抓取器，并且它将保持鼠标抓取器状态，直到发生以下任一事件：

- 如果该项目在没有按下其他按钮时收到鼠标释放事件，它将失去鼠标抓取。
- 如果该项目变得不可见（即，有人调用`item->setVisible(false)`），或者如果它变得禁用（即，有人调用`item->setEnabled(false)`），它将失去鼠标抓取。
- 如果该项目从场景中移除，它就会失去鼠标抓取的能力。

如果该项目失去了鼠标抓取，场景将忽略所有鼠标事件，直到新项目抓住鼠标（即，直到新项目收到鼠标按下事件）。

### `[virtual protected]`void QGraphicsScene::mouseMoveEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **mouseEvent*)

该事件处理程序，用于事件*mouseEvent*，可以在子类中重新实现以接收场景的鼠标移动事件。

默认实现取决于鼠标抓取器状态。如果有鼠标抓取器项目，则事件将发送到鼠标抓取器。如果当前位置有任何接受悬停事件的项目，则将该事件转换为悬停事件并接受；否则它会被忽略。

**可以查阅**[QGraphicsItem::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[QGraphicsItem::mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(),[QGraphicsItem::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（）， 和[QGraphicsItem::setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)()。

### `[virtual protected]`void QGraphicsScene::mousePressEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **mouseEvent*)

该事件处理程序，用于事件*mouseEvent*，可以在子类中重新实现以接收场景的鼠标按下事件。

默认实现取决于场景的状态。如果有鼠标抓取器项目，则事件将发送到鼠标抓取器。否则，它会从事件转发到在场景位置处接受鼠标事件的最顶层可见项目，并且该项目立即成为鼠标抓取器项目。

如果场景中的给定位置没有项目，则选择区域将重置，任何焦点项目都会失去其输入焦点，然后该事件将被忽略。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[QGraphicsItem::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)（） 和[QGraphicsItem::setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)()。

### `[virtual protected]`void QGraphicsScene::mouseReleaseEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **mouseEvent*)

该事件处理程序，用于事件*mouseEvent*，可以在子类中重新实现以接收场景的鼠标释放事件。

默认实现取决于鼠标抓取器状态。如果没有鼠标抓取器，则该事件将被忽略。否则，如果有鼠标抓取器项目，则事件将发送到鼠标抓取器。如果此鼠标释放代表最后按下的鼠标按钮，则鼠标抓取器项目将失去鼠标抓取。

**可以查阅**[QGraphicsItem::mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[QGraphicsItem::mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[QGraphicsItem::mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（）， 和[QGraphicsItem::setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)()。

### void QGraphicsScene::removeItem([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

删除该项目*item*以及现场的所有孩子。的所有权*item*被传递给调用者（即，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会再删除*item*当被摧毁时）。

**可以查阅**[addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### void QGraphicsScene::render([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*target* = QRectF(), const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*source* = QRectF(), [Qt::AspectRatioMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#AspectRatioMode-enum) *aspectRatioMode* = Qt::KeepAspectRatio)

呈现*source*从场景直入*target*， 使用*painter*。此功能对于将场景内容捕获到绘画设备（例如[QImage](https://doc-qt-io.translate.goog/qt-6/qimage.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（例如，截取屏幕截图），或使用 QPrinter 进行打印。例如：

```
QGraphicsScene scene;
scene.addItem(...
...
QPrinter printer(QPrinter::HighResolution);
printer.setPaperSize(QPrinter::A4);

QPainter painter(&printer);
scene.render(&painter);
```

如果*source*是一个空矩形，这个函数将使用[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)() 来确定要渲染的内容。如果*target*是一个空矩形，尺寸为*painter*会使用到绘画装置。

源矩形内容将根据以下内容进行转换*aspectRatioMode*以适合目标矩形。默认情况下，保持宽高比，并且*source*缩放以适应*target*。

**可以查阅**[QGraphicsView::render](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#render)()。

### `[signal]`void QGraphicsScene::sceneRectChanged(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*)

该信号由[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)每当场景矩形发生变化时。这*rect*参数是新的场景矩形。

**可以查阅**[QGraphicsView::updateSceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateSceneRect)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::selectedItems() const

返回所有当前选定项目的列表。退回的物品没有特定的顺序。

**可以查阅**[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsScene::selectionArea() const

返回先前设置的选择区域[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()，或空[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果没有设置选择区域。

**可以查阅**[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()。

### `[signal]`void QGraphicsScene::selectionChanged()

该信号由[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)每当选择发生变化时。您可以致电[selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)() 获取新的所选项目列表。

每当选择或取消选择某个项目、设置、清除或以其他方式更改选择区域、将预选项目添加到场景中或从场景中删除所选项目时，选择都会发生变化。

[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)对于组选择操作仅发出一次该信号。例如，如果您设置了选择区域，则选择或取消选择一个[QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，或者如果您在场景中添加或删除包含多个选定项目的父项目，则在操作完成后仅发出一次 SelectionChanged() （而不是每个项目一次）。

**可以查阅**[setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)(),[selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)（）， 和[QGraphicsItem::setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)()。

### bool QGraphicsScene::sendEvent([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

发送事件*event*到项目*item*通过可能的事件过滤器。

仅当启用该项目时才会发送该事件。

返回`false`事件是否被过滤或项目是否被禁用。否则返回从事件处理程序返回的值。

**可以查阅**[QGraphicsItem::sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（） 和[QGraphicsItem::sceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEventFilter)()。

### void QGraphicsScene::setActivePanel([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*)

激活*item*，它一定是这个场景中的一个项目。您也可以传递 0*item*， 在这种情况下[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将停用任何当前活动的面板。

如果场景当前处于非活动状态，*item*保持不活动状态，直到场景变为活动状态（或者，ir*item*是`nullptr`，不会激活任何项目）。

**可以查阅**[activePanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activePanel)(),[isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)（）， 和[QGraphicsItem::isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### void QGraphicsScene::setActiveWindow([QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget*)

激活*widget*，它一定是这个场景中的一个小部件。您也可以传递 0*widget*， 在这种情况下[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将停用任何当前活动的窗口。

**可以查阅**[activeWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activeWindow)（） 和[QGraphicsWidget::isActiveWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActiveWindow)()。

### void QGraphicsScene::setFocus([Qt::FocusReason](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusReason-enum) *focusReason* = Qt::OtherFocusReason)

通过发送[QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)到现场，路过*focusReason*作为理由。如果场景在某个项目具有焦点时失去焦点后重新获得焦点，则最后一个焦点项目将获得焦点*focusReason*作为理由。

如果场景已经具有焦点，则此函数不执行任何操作。

**可以查阅**[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)(),[clearFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)（）， 和[setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)()。

### void QGraphicsScene::setFocusItem([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **item*, [Qt::FocusReason](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusReason-enum) *focusReason* = Qt::OtherFocusReason)

将场景的焦点项目设置为*item*, 与焦点原因*focusReason*，从任何先前可能具有焦点的项目中移除焦点后。

如果*item*是`nullptr`，或者如果它不接受焦点（即它没有[QGraphicsItem::ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用），或者不可见或未启用，此功能仅从任何先前的焦点项目中删除焦点。

如果 item 不是`nullptr`，并且场景当前没有焦点（即[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)() 返回`false`)，该函数将调用[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)（） 自动地。

**可以查阅**[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)(),[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)（）， 和[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)()。

### void QGraphicsScene::setSelectionArea(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform*)

将选择区域设置为*path*。该区域内的所有项目都会立即被选择，而区域外的所有项目都会被取消选择。您可以通过调用获取所有选定项目的列表[selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)()。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

对于要选择的项目，必须将其标记为*可选*([QGraphicsItem::ItemIsSelectable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)）。

**可以查阅**[clearSelection](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)（） 和[selectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionArea)()。

### void QGraphicsScene::setSelectionArea(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, [Qt::ItemSelectionOperation](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionOperation-enum) *selectionOperation* = Qt::ReplaceSelection, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape, const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*deviceTransform* = QTransform())

这是一个过载功能。

将选择区域设置为*path*使用*mode*确定项目是否包含在选择区域中。

*deviceTransform*是应用于视图的变换，如果场景包含忽略变换的项目，则需要提供。

*selectionOperation*确定如何处理当前选定的项目。

**可以查阅**[clearSelection](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearSelection)（） 和[selectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectionArea)()。

### void QGraphicsScene::setStyle([QStyle](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **style*)

将场景的样式设置或替换为*style*，并重新设置该场景的样式。任何先前指定的样式都将被删除。场景的风格默认为[QApplication::style](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()，并作为所有的默认值[QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)场景中的物品。

更改样式，可以直接调用此函数，也可以间接调用[QApplication::setStyle](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()，将自动更新场景中所有没有明确指定样式的小部件的样式。

如果*style*是`nullptr`,[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将恢复为[QApplication::style](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()。

**可以查阅**[style](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)()。

### [QStyle](https://doc-qt-io.translate.goog/qt-6/qstyle.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsScene::style() const

返回场景的风格，或者与[QApplication::style](https://doc-qt-io.translate.goog/qt-6/qapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#style)() 如果场景尚未明确指定样式。

**可以查阅**[setStyle](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setStyle)()。

### `[slot]`void QGraphicsScene::update(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF())

安排区域重绘*rect*在现场。

**可以查阅**[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)（） 和[changed](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#changed)()。

### void QGraphicsScene::update([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*)

这是一个过载功能。

该函数相当于调用 update([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））；

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsScene::views() const

返回显示该场景的所有视图的列表。

**可以查阅**[QGraphicsView::scene](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scene)()。

### `[virtual protected]`void QGraphicsScene::wheelEvent([QGraphicsSceneWheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenewheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **wheelEvent*)

该事件处理程序，用于事件*wheelEvent*，可以在子类中重新实现以接收场景的鼠标滚轮事件。

默认情况下，事件将传递到光标下最上面的可见项。如果被忽略，事件将传播到下面的项目，并再次传播，直到事件被接受或到达场景。如果没有项目接受该事件，则该事件将被忽略。

注：参见[items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)() 定义该函数认为哪些项目可见。

**可以查阅**[QGraphicsItem::wheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsScene::width() const

这个便利函数相当于调用[sceneRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneRect-prop)（）。宽度（）。

**可以查阅**[height](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#height)()。