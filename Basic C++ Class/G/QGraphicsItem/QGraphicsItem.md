 QGraphicsItem Class

QGraphicsItem 类是所有图形项目的基类[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。[更多的...](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#details)

| Header:       | #include < QGraphicsItem>                                    |
| ------------- | ------------------------------------------------------------ |
| CMake:        | find_package(Qt6 REQUIRED COMPONENTS Widgets) target_link_libraries(mytarget PRIVATE Qt6::Widgets) |
| qmake:        | QT += widgets                                                |
| Inherited By: | [QAbstractGraphicsShapeItem](https://doc-qt-io.translate.goog/qt-6/qabstractgraphicsshapeitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QGraphicsLineItem](https://doc-qt-io.translate.goog/qt-6/qgraphicslineitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), [QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp), and [QGraphicsPixmapItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspixmapitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) |

- [所有成员的列表，包括继承的成员](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem-members.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)
- [已弃用的成员](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem-obsolete.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

## 公共类型

| enum  | **[CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)** { NoCache, ItemCoordinateCache, DeviceCoordinateCache } |
| ----- | ------------------------------------------------------------ |
| enum  | **[GraphicsItemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum)** { ItemEnabledChange, ItemEnabledHasChanged, ItemPositionChange, ItemPositionHasChanged, ItemTransformChange, …, ItemScenePositionHasChanged } |
| enum  | **[GraphicsItemFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)** { ItemIsMovable, ItemIsSelectable, ItemIsFocusable, ItemClipsToShape, ItemClipsChildrenToShape, …, ItemContainsChildrenInShape } |
| flags | **[GraphicsItemFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)** |
| enum  | **[PanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PanelModality-enum)** { NonModal, PanelModal, SceneModal } |
| enum  | **[anonymous](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anonymous-enum)** { Type, UserType } |

## 公共职能

|                                  | **[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem)**(QGraphicsItem **parent* = nullptr) |
| -------------------------------- | ------------------------------------------------------------ |
| virtual                          | **[~QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dtor.QGraphicsItem)**() |
| bool                             | **[acceptDrops](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptDrops)**() const |
| bool                             | **[acceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptHoverEvents)**() const |
| bool                             | **[acceptTouchEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptTouchEvents)**() const |
| Qt::MouseButtons                 | **[acceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptedMouseButtons)**() const |
| virtual void                     | **[advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)**(int *phase*) |
| virtual QRectF                   | **[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)**() const = 0 |
| QRegion                          | **[boundingRegion](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegion)**(const QTransform &*itemToDeviceTransform*) const |
| qreal                            | **[boundingRegionGranularity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegionGranularity)**() const |
| QGraphicsItem::CacheMode         | **[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode)**() const |
| QList<QGraphicsItem *>           | **[childItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childItems)**() const |
| QRectF                           | **[childrenBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childrenBoundingRect)**() const |
| void                             | **[clearFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)**() |
| QPainterPath                     | **[clipPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipPath)**() const |
| virtual bool                     | **[collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)**(const QGraphicsItem **other*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| virtual bool                     | **[collidesWithPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithPath)**(const QPainterPath &*path*, Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QList<QGraphicsItem *>           | **[collidingItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidingItems)**(Qt::ItemSelectionMode *mode* = Qt::IntersectsItemShape) const |
| QGraphicsItem *                  | **[commonAncestorItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#commonAncestorItem)**(const QGraphicsItem **other*) const |
| virtual bool                     | **[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)**(const QPointF &*point*) const |
| QCursor                          | **[cursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursor)**() const |
| QVariant                         | **[data](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)**(int *key*) const |
| QTransform                       | **[deviceTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deviceTransform)**(const QTransform &*viewportTransform*) const |
| qreal                            | **[effectiveOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#effectiveOpacity)**() const |
| void                             | **[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)**(const QRectF &*rect* = QRectF(), int *xmargin* = 50, int *ymargin* = 50) |
| void                             | **[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*, int *xmargin* = 50, int *ymargin* = 50) |
| bool                             | **[filtersChildEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filtersChildEvents)**() const |
| QGraphicsItem::GraphicsItemFlags | **[flags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)**() const |
| QGraphicsItem *                  | **[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)**() const |
| QGraphicsItem *                  | **[focusProxy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusProxy)**() const |
| void                             | **[grabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabKeyboard)**() |
| void                             | **[grabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabMouse)**() |
| QGraphicsEffect *                | **[graphicsEffect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#graphicsEffect)**() const |
| QGraphicsItemGroup *             | **[group](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)**() const |
| bool                             | **[hasCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasCursor)**() const |
| bool                             | **[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)**() const |
| void                             | **[hide](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)**() |
| Qt::InputMethodHints             | **[inputMethodHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodHints)**() const |
| void                             | **[installSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installSceneEventFilter)**(QGraphicsItem **filterItem*) |
| bool                             | **[isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)**() const |
| bool                             | **[isAncestorOf](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAncestorOf)**(const QGraphicsItem **child*) const |
| bool                             | **[isBlockedByModalPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isBlockedByModalPanel)**(QGraphicsItem ***blockingPanel* = nullptr) const |
| bool                             | **[isClipped](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isClipped)**() const |
| bool                             | **[isEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEnabled)**() const |
| bool                             | **[isObscured](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscured)**(const QRectF &*rect* = QRectF()) const |
| bool                             | **[isObscured](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscured-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| virtual bool                     | **[isObscuredBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscuredBy)**(const QGraphicsItem **item*) const |
| bool                             | **[isPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPanel)**() const |
| bool                             | **[isSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSelected)**() const |
| bool                             | **[isUnderMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isUnderMouse)**() const |
| bool                             | **[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)**() const |
| bool                             | **[isVisibleTo](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisibleTo)**(const QGraphicsItem **parent*) const |
| bool                             | **[isWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWidget)**() const |
| bool                             | **[isWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWindow)**() const |
| QTransform                       | **[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)**(const QGraphicsItem **other*, bool **ok* = nullptr) const |
| QPointF                          | **[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)**(const QGraphicsItem **item*, const QPointF &*point*) const |
| QPolygonF                        | **[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem-1)**(const QGraphicsItem **item*, const QRectF &*rect*) const |
| QPolygonF                        | **[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem-2)**(const QGraphicsItem **item*, const QPolygonF &*polygon*) const |
| QPainterPath                     | **[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem-3)**(const QGraphicsItem **item*, const QPainterPath &*path*) const |
| QPointF                          | **[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem-4)**(const QGraphicsItem **item*, qreal *x*, qreal *y*) const |
| QPolygonF                        | **[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem-5)**(const QGraphicsItem **item*, qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QPointF                          | **[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)**(const QPointF &*point*) const |
| QPolygonF                        | **[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent-1)**(const QRectF &*rect*) const |
| QPolygonF                        | **[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent-2)**(const QPolygonF &*polygon*) const |
| QPainterPath                     | **[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent-3)**(const QPainterPath &*path*) const |
| QPointF                          | **[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent-4)**(qreal *x*, qreal *y*) const |
| QPolygonF                        | **[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent-5)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QPointF                          | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)**(const QPointF &*point*) const |
| QPolygonF                        | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-1)**(const QRectF &*rect*) const |
| QPolygonF                        | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-2)**(const QPolygonF &*polygon*) const |
| QPainterPath                     | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-3)**(const QPainterPath &*path*) const |
| QPointF                          | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-4)**(qreal *x*, qreal *y*) const |
| QPolygonF                        | **[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene-5)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QRectF                           | **[mapRectFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromItem)**(const QGraphicsItem **item*, const QRectF &*rect*) const |
| QRectF                           | **[mapRectFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromItem-1)**(const QGraphicsItem **item*, qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QRectF                           | **[mapRectFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromParent)**(const QRectF &*rect*) const |
| QRectF                           | **[mapRectFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromParent-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QRectF                           | **[mapRectFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromScene)**(const QRectF &*rect*) const |
| QRectF                           | **[mapRectFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromScene-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QRectF                           | **[mapRectToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToItem)**(const QGraphicsItem **item*, const QRectF &*rect*) const |
| QRectF                           | **[mapRectToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToItem-1)**(const QGraphicsItem **item*, qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QRectF                           | **[mapRectToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToParent)**(const QRectF &*rect*) const |
| QRectF                           | **[mapRectToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToParent-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QRectF                           | **[mapRectToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToScene)**(const QRectF &*rect*) const |
| QRectF                           | **[mapRectToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToScene-1)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QPointF                          | **[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)**(const QGraphicsItem **item*, const QPointF &*point*) const |
| QPolygonF                        | **[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem-1)**(const QGraphicsItem **item*, const QRectF &*rect*) const |
| QPolygonF                        | **[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem-2)**(const QGraphicsItem **item*, const QPolygonF &*polygon*) const |
| QPainterPath                     | **[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem-3)**(const QGraphicsItem **item*, const QPainterPath &*path*) const |
| QPointF                          | **[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem-4)**(const QGraphicsItem **item*, qreal *x*, qreal *y*) const |
| QPolygonF                        | **[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem-5)**(const QGraphicsItem **item*, qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QPointF                          | **[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)**(const QPointF &*point*) const |
| QPolygonF                        | **[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent-1)**(const QRectF &*rect*) const |
| QPolygonF                        | **[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent-2)**(const QPolygonF &*polygon*) const |
| QPainterPath                     | **[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent-3)**(const QPainterPath &*path*) const |
| QPointF                          | **[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent-4)**(qreal *x*, qreal *y*) const |
| QPolygonF                        | **[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent-5)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| QPointF                          | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)**(const QPointF &*point*) const |
| QPolygonF                        | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-1)**(const QRectF &*rect*) const |
| QPolygonF                        | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-2)**(const QPolygonF &*polygon*) const |
| QPainterPath                     | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-3)**(const QPainterPath &*path*) const |
| QPointF                          | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-4)**(qreal *x*, qreal *y*) const |
| QPolygonF                        | **[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene-5)**(qreal *x*, qreal *y*, qreal *w*, qreal *h*) const |
| void                             | **[moveBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveBy)**(qreal *dx*, qreal *dy*) |
| qreal                            | **[opacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opacity)**() const |
| virtual QPainterPath             | **[opaqueArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueArea)**() const |
| virtual void                     | **[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)**(QPainter **painter*, const QStyleOptionGraphicsItem **option*, QWidget **widget* = nullptr) = 0 |
| QGraphicsItem *                  | **[panel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panel)**() const |
| QGraphicsItem::PanelModality     | **[panelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panelModality)**() const |
| QGraphicsItem *                  | **[parentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentItem)**() const |
| QGraphicsObject *                | **[parentObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentObject)**() const |
| QGraphicsWidget *                | **[parentWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentWidget)**() const |
| QPointF                          | **[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)**() const |
| void                             | **[removeSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSceneEventFilter)**(QGraphicsItem **filterItem*) |
| void                             | **[resetTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetTransform)**() |
| qreal                            | **[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)**() const |
| qreal                            | **[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)**() const |
| QGraphicsScene *                 | **[scene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scene)**() const |
| QRectF                           | **[sceneBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneBoundingRect)**() const |
| QPointF                          | **[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)**() const |
| QTransform                       | **[sceneTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneTransform)**() const |
| void                             | **[scroll](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scroll)**(qreal *dx*, qreal *dy*, const QRectF &*rect* = QRectF()) |
| void                             | **[setAcceptDrops](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptDrops)**(bool *on*) |
| void                             | **[setAcceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptHoverEvents)**(bool *enabled*) |
| void                             | **[setAcceptTouchEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptTouchEvents)**(bool *enabled*) |
| void                             | **[setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)**(Qt::MouseButtons *buttons*) |
| void                             | **[setActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActive)**(bool *active*) |
| void                             | **[setBoundingRegionGranularity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBoundingRegionGranularity)**(qreal *granularity*) |
| void                             | **[setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)**(QGraphicsItem::CacheMode *mode*, const QSize &*logicalCacheSize* = QSize()) |
| void                             | **[setCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCursor)**(const QCursor &*cursor*) |
| void                             | **[setData](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)**(int *key*, const QVariant &*value*) |
| void                             | **[setEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEnabled)**(bool *enabled*) |
| void                             | **[setFiltersChildEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFiltersChildEvents)**(bool *enabled*) |
| void                             | **[setFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlag)**(QGraphicsItem::GraphicsItemFlag *flag*, bool *enabled* = true) |
| void                             | **[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)**(QGraphicsItem::GraphicsItemFlags *flags*) |
| void                             | **[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)**(Qt::FocusReason *focusReason* = Qt::OtherFocusReason) |
| void                             | **[setFocusProxy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusProxy)**(QGraphicsItem **item*) |
| void                             | **[setGraphicsEffect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGraphicsEffect)**(QGraphicsEffect **effect*) |
| void                             | **[setGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGroup)**(QGraphicsItemGroup **group*) |
| void                             | **[setInputMethodHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setInputMethodHints)**(Qt::InputMethodHints *hints*) |
| void                             | **[setOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)**(qreal *opacity*) |
| void                             | **[setPanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPanelModality)**(QGraphicsItem::PanelModality *panelModality*) |
| void                             | **[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)**(QGraphicsItem **newParent*) |
| void                             | **[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)**(const QPointF &*pos*) |
| void                             | **[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos-1)**(qreal *x*, qreal *y*) |
| void                             | **[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)**(qreal *angle*) |
| void                             | **[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)**(qreal *factor*) |
| void                             | **[setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)**(bool *selected*) |
| void                             | **[setToolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)**(const QString &*toolTip*) |
| void                             | **[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)**(const QTransform &*matrix*, bool *combine* = false) |
| void                             | **[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)**(const QPointF &*origin*) |
| void                             | **[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint-1)**(qreal *x*, qreal *y*) |
| void                             | **[setTransformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformations)**(const QList<QGraphicsTransform *> &*transformations*) |
| void                             | **[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)**(bool *visible*) |
| void                             | **[setX](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setX)**(qreal *x*) |
| void                             | **[setY](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setY)**(qreal *y*) |
| void                             | **[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)**(qreal *z*) |
| virtual QPainterPath             | **[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)**() const |
| void                             | **[show](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)**() |
| void                             | **[stackBefore](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stackBefore)**(const QGraphicsItem **sibling*) |
| QGraphicsObject *                | **[toGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toGraphicsObject)**() |
| const QGraphicsObject *          | **[toGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toGraphicsObject-1)**() const |
| QString                          | **[toolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip)**() const |
| QGraphicsItem *                  | **[topLevelItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#topLevelItem)**() const |
| QGraphicsWidget *                | **[topLevelWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#topLevelWidget)**() const |
| QTransform                       | **[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)**() const |
| QPointF                          | **[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)**() const |
| QList<QGraphicsTransform *>      | **[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)**() const |
| virtual int                      | **[type](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)**() const |
| void                             | **[ungrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabKeyboard)**() |
| void                             | **[ungrabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabMouse)**() |
| void                             | **[unsetCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unsetCursor)**() |
| void                             | **[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)**(const QRectF &*rect* = QRectF()) |
| void                             | **[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update-1)**(qreal *x*, qreal *y*, qreal *width*, qreal *height*) |
| QGraphicsWidget *                | **[window](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#window)**() const |
| qreal                            | **[x](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#x)**() const |
| qreal                            | **[y](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#y)**() const |
| qreal                            | **[zValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zValue)**() const |

## 受保护的功能

| virtual void     | **[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)**(QGraphicsSceneContextMenuEvent **event*) |
| ---------------- | ------------------------------------------------------------ |
| virtual void     | **[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void     | **[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void     | **[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void     | **[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)**(QGraphicsSceneDragDropEvent **event*) |
| virtual void     | **[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)**(QFocusEvent **event*) |
| virtual void     | **[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)**(QFocusEvent **event*) |
| virtual void     | **[hoverEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverEnterEvent)**(QGraphicsSceneHoverEvent **event*) |
| virtual void     | **[hoverLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverLeaveEvent)**(QGraphicsSceneHoverEvent **event*) |
| virtual void     | **[hoverMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverMoveEvent)**(QGraphicsSceneHoverEvent **event*) |
| virtual void     | **[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)**(QInputMethodEvent **event*) |
| virtual QVariant | **[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)**(Qt::InputMethodQuery *query*) const |
| virtual QVariant | **[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)**(QGraphicsItem::GraphicsItemChange *change*, const QVariant &*value*) |
| virtual void     | **[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)**(QKeyEvent **event*) |
| virtual void     | **[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)**(QKeyEvent **event*) |
| virtual void     | **[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)**(QGraphicsSceneMouseEvent **event*) |
| virtual void     | **[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)**(QGraphicsSceneMouseEvent **event*) |
| virtual void     | **[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)**(QGraphicsSceneMouseEvent **event*) |
| virtual void     | **[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)**(QGraphicsSceneMouseEvent **event*) |
| void             | **[prepareGeometryChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepareGeometryChange)**() |
| virtual bool     | **[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)**(QEvent **event*) |
| virtual bool     | **[sceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEventFilter)**(QGraphicsItem **watched*, QEvent **event*) |
| void             | **[updateMicroFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#updateMicroFocus)**() |
| virtual void     | **[wheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#wheelEvent)**(QGraphicsSceneWheelEvent **event*) |

## 相关非成员

| T    | **[qgraphicsitem_cast](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qgraphicsitem_cast)**(QGraphicsItem **item*) |
| ---- | ------------------------------------------------------------ |
|      |                                                              |

## 详细说明

它为编写您自己的自定义项目提供了一个轻量级的基础。这包括定义项目的几何形状、碰撞检测、其绘制实现以及通过其事件处理程序进行项目交互。QGraphicsItem 是[Graphics View Framework](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\G\QGraphicsItem\QGraphicsItem\graphicsview-items.png)

为了方便起见，Qt 为最常见的形状提供了一组标准图形项。这些都是：

- [QGraphicsEllipseItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsellipseitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供一个椭圆项目
- [QGraphicsLineItem](https://doc-qt-io.translate.goog/qt-6/qgraphicslineitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供行项目
- [QGraphicsPathItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspathitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供任意路径项
- [QGraphicsPixmapItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspixmapitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供一个像素图项
- [QGraphicsPolygonItem](https://doc-qt-io.translate.goog/qt-6/qgraphicspolygonitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供一个多边形项目
- [QGraphicsRectItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsrectitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供一个矩形项目
- [QGraphicsSimpleTextItem](https://doc-qt-io.translate.goog/qt-6/qgraphicssimpletextitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供简单的文本标签项
- [QGraphicsTextItem](https://doc-qt-io.translate.goog/qt-6/qgraphicstextitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供高级文本浏览器项目

项目的所有几何信息都基于其局部坐标系。物品的位置，[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)() 是唯一不在本地坐标中操作的函数，因为它返回父坐标中的位置。[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)详细描述了坐标系。

您可以通过调用来设置项目是否可见（即绘制和接受事件）[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。隐藏一个项目也会隐藏它的子项。同样，您可以通过调用来启用或禁用项目[setEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEnabled)()。如果禁用某个项目，则其所有子项目也将被禁用。默认情况下，项目既可见又启用。要切换是否选择某个项目，请首先通过设置启用选择[ItemIsSelectable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标记，然后调用[setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)()。通常，作为用户交互的结果，选择是由场景切换的。

要编写自己的图形项，首先创建 QGraphicsItem 的子类，然后首先实现它的两个纯虚公共函数：[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()，返回该项目绘制的面积的估计值，以及[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)()，它实现了实际的绘画。例如：

```
class SimpleItem : public QGraphicsItem
{
public:
    QRectF boundingRect() const override
    {
        qreal penWidth = 1;
        return QRectF(-10 - penWidth / 2, -10 - penWidth / 2,
                      20 + penWidth, 20 + penWidth);
    }

    void paint(QPainter *painter, const QStyleOptionGraphicsItem *option,
               QWidget *widget) override
    {
        painter->drawRoundedRect(-10, -10, 20, 20, 5, 5);
    }
};
```

这[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 函数有许多不同的用途。[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)其项目索引基于[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（）， 和[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用它来剔除不可见的项目，并确定绘制重叠项目时需要重新组合的区域。另外，QGraphicsItem的碰撞检测机制使用[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 提供有效的截止。细粒度碰撞算法[collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)() 是基于调用[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)()，它返回项目形状的准确轮廓作为[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)期望所有项目[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（） 和[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)() 保持不变，除非另行通知。如果你想以任何方式改变一个项目的几何形状，你必须首先调用[prepareGeometryChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepareGeometryChange)（） 允许[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)更新其簿记。

碰撞检测可以通过两种方式完成：

1. 重新实现[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)() 返回项目的准确形状，并依赖于默认实现[collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)() 进行形状-形状相交。如果形状很复杂，这可能会相当昂贵。
2. 重新实现[collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)() 提供您自己的自定义项目和形状碰撞算法。

这[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)可以调用()函数来判断该项是否*包含*点。该功能也可以由项目重新实现。默认行为[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)() 是基于调用[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)()。

项目可以包含其他项目，也可以被其他项目包含。所有项目都可以有一个父项目和一个子项目列表。除非该项目没有父项，否则其位置位于*父*坐标（即父项的本地坐标）中。父项将它们的位置和变换传播给所有子项。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\G\QGraphicsItem\QGraphicsItem\graphicsview-parentchild.png)

### 转换

QGraphicsItem 除了其基本位置之外还支持投影变换，[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)()。有多种方法可以更改项目的变换。对于简单的转换，您可以调用任一便利函数[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)（） 或者[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)()，或者您可以将任何变换矩阵传递给[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()。对于高级转换控制，您还可以选择通过调用设置多个组合转换[setTransformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformations)()。

项目变换从父项到子项累积，因此如果父项和子项都旋转 90 度，则子项的总变换将为 180 度。同样，如果该项目的父项缩放为其原始大小的 2 倍，则其子项也将变为原来大小的两倍。项目的变换不会影响其自身的局部几何形状；所有几何函数（例如，[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)(),[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 和所有映射函数）仍然在本地坐标中运行。为了方便起见，QGraphicsItem提供了函数[sceneTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneTransform)()，返回该项目的总变换矩阵（包括其位置以及所有父级的位置和变换），以及[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)()，返回其在场景坐标中的位置。要重置项目的矩阵，请调用[resetTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#resetTransform)()。

某些转换操作会根据其应用顺序产生不同的结果。例如，如果缩放变换，然后旋转它，则可能会得到与先旋转变换不同的结果。然而，您在 QGraphicsItem 上设置变换属性的顺序不会影响最终的变换；QGraphicsItem 始终以固定的、定义的顺序应用属性：

- 应用该项目的基础变换（[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)())
- 项目的变换列表按顺序应用（[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)())
- 该项目相对于其变换原点旋转（[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)())
- 该项目相对于其变换原点进行缩放（[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)())

### 绘画

这[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)() 函数被调用[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)绘制项目的内容。该项目没有自己的背景或默认填充；项目后面的任何内容都会穿过此函数中未明确绘制的所有区域。您可以致电[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 安排重绘，可选择传递需要重绘的矩形。根据该项目在视图中是否可见，该项目可能会也可能不会被重新绘制；没有相当于[QWidget::repaint](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#repaint)() 在 QGraphicsItem 中。

项目由视图绘制，从父项目开始，然后按升序堆叠顺序绘制子项目。您可以通过调用设置项目的堆叠顺序[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)()，并通过调用进行测试[zValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zValue)()，其中 z 值较低的项目在 z 值较高的项目之前绘制。堆叠顺序适用于同级项目；父母总是被吸引在孩子面前。

### 排序

所有项目都按照定义的、稳定的顺序绘制，并且相同的顺序决定当您单击场景时哪些项目将首先接收鼠标输入。通常您不必担心排序，因为项目遵循“自然顺序”，遵循场景的逻辑结构。

项目的子项堆叠在父项的顶部，并且同级项目按插入顺序堆叠（即，按照它们添加到场景或添加到同一父项的顺序相同）。如果您先添加项目 A，然后添加 B，则 B 将位于 A 之上。如果您随后添加 C，则项目的堆叠顺序将为 A、B、C。

![img](C:\Users\陈冠豪\Desktop\QtDoc\My Qt Doc\Basic C++ Class\G\QGraphicsItem\QGraphicsItem\graphicsview-zorder.png)

此示例显示了机器人所有肢体的堆叠顺序[Drag and Drop Robot](https://doc-qt-io.translate.goog/qt-6/qtwidgets-graphicsview-dragdroprobot-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)例子。躯干是根项（所有其他项都是躯干的子项或后代），因此首先绘制它。接下来，绘制头部，因为它是躯干子项列表中的第一项。然后画出左上臂。由于下臂是上臂的子臂，因此先绘制下臂，然后绘制上臂的下一个兄弟，即右上臂，依此类推。

对于高级用户，有多种方法可以更改项目的排序方式：

- 您可以致电[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)() 在某个项目上显式地将其堆叠在其他同级项目的顶部或下方。项目的默认 Z 值为 0。具有相同 Z 值的项目按插入顺序堆叠。
- 您可以致电[stackBefore](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stackBefore)() 对子列表重新排序。这将直接修改插入顺序。
- 您可以设置[ItemStacksBehindParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志将子项堆叠在其父项后面。

两个同级项的堆叠顺序也适用于每个项的子项和后代项。因此，如果一项位于另一项之上，则其所有子项也将位于另一项的所有子项之上。

### 活动

QGraphicsItem 接收事件[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通过虚函数[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。该函数将最常见的事件分发给一组方便的事件处理程序：

- [contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)() 处理上下文菜单事件
- [focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)（） 和[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)() 处理焦点进入和焦点离开事件
- [hoverEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverEnterEvent)(),[hoverMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverMoveEvent)（）， 和[hoverLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverLeaveEvent)() 处理悬停进入、移动和离开事件
- [inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)() 处理输入事件，以支持辅助功能
- [keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（） 和[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)() 处理按键按下和释放事件
- [mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（）， 和[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)() 处理鼠标按下、移动、释放、单击和双击事件

您可以通过安装事件过滤器来过滤任何其他项目的事件。此功能独立于 Qt 的常规事件过滤器（请参阅[QObject::installEventFilter](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installEventFilter)())，仅适用于[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。通过调用将您的项目安装为另一个项目的事件过滤器后[installSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installSceneEventFilter)()，过滤后的事件将被虚函数接收[sceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEventFilter)()。您可以通过调用删除项目事件过滤器[removeSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSceneEventFilter)()。

### 自定义数据

有时，向项目注册自定义数据很有用，无论是自定义项目还是标准项目。您可以致电[setData](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)() 在任何项目上使用键值对存储数据（键是整数，值是[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。要从项目获取自定义数据，请调用[data](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。Qt 本身完全未涉及此功能；它是为了方便用户而提供的。

**也可以看看**[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp),[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[Graphics View Framework](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

## 成员类型文档

### enum QGraphicsItem::CacheMode

这个枚举描述了[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的缓存模式。缓存用于通过分配和渲染到离屏像素缓冲区来加速渲染，当项目需要重绘时可以重用该缓冲区。对于某些绘画设备，缓存直接存储在图形内存中，这使得渲染速度非常快。

| 持续的                                 | 价值 | 描述                                                         |
| -------------------------------------- | ---- | ------------------------------------------------------------ |
| `QGraphicsItem::NoCache`               | `0`  | 默认；所有项目缓存均被禁用。[QGraphicsItem::paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)每次需要重绘项目时都会调用 ()。 |
| `QGraphicsItem::ItemCoordinateCache`   | `1`  | 为项目的逻辑（本地）坐标系启用缓存。[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)创建一个离屏像素缓冲区，其大小/分辨率可配置，您可以将其传递给[QGraphicsItem::setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)()。渲染质量通常会降低，具体取决于缓存的分辨率和项目转换。第一次重绘该项目时，它将自身渲染到缓存中，然后在每次后续公开时重用该缓存。当项目被转换时，缓存也会被重用。要调整缓存的分辨率，可以调用[setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)（） 再次。 |
| `QGraphicsItem::DeviceCoordinateCache` | `2`  | 缓存在绘画设备级别、设备坐标中启用。此模式适用于可以移动但不能旋转、缩放或剪切的项目。如果项目被直接或间接转换，缓存将自动重新生成。与 ItemCooperativeCacheMode 不同，DeviceCooperativeCache 始终以最高质量呈现。 |

**也可以看看**[QGraphicsItem::setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)()。

### enum QGraphicsItem::GraphicsItemChange

该枚举描述了由以下方式通知的状态更改[QGraphicsItem::itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。通知随着状态变化而发送，在某些情况下，可以进行调整（有关详细信息，请参阅每个更改的文档）。

注意：调用函数时要小心[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)本身在里面[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()，因为某些函数调用可能会导致不必要的递归。例如，您不能调用[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在 ItemPositionChange 通知上，作为[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)()函数会再次调用[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)（项目位置更改）。相反，您可以返回新的、调整后的位置[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。

| 持续的                                              | 价值 | 描述                                                         |
| --------------------------------------------------- | ---- | ------------------------------------------------------------ |
| `QGraphicsItem::ItemEnabledChange`                  | `3`  | 该项目的启用状态发生更改。如果该项目当前已启用，它将变为禁用，反之亦然。value 参数是新的启用状态（即 true 或 false）。不要调用[setEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEnabled)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。相反，您可以从返回新状态[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemEnabledHasChanged`              | `13` | 该项目的启用状态已更改。value 参数是新的启用状态（即 true 或 false）。不要调用[setEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEnabled)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemPositionChange`                 | `0`  | 项目的位置发生变化。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且当项目的本地位置相对于其父项发生变化时（即，由于调用[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)（） 或者[moveBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveBy)())。value 参数是新位置（即[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。您可以致电[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)() 获取原始位置。不要调用[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)（） 或者[moveBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#moveBy)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以返回新的、调整后的位置[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。接到此通知后，[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果位置发生变化，立即发送 ItemPositionHasChanged 通知。 |
| `QGraphicsItem::ItemPositionHasChanged`             | `9`  | 该项目的位置已更改。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且在项目相对于其父项的本地位置发生更改后。value 参数是新位置（与[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)（））， 和[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)忽略此通知的返回值（即只读通知）。 |
| `QGraphicsItem::ItemTransformChange`                | `8`  | 该项目的变换矩阵发生变化。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且当项目的局部变换矩阵发生变化时（即，由于调用[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()。value 参数是新矩阵（即[QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）；要获取旧矩阵，请调用[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)()。不要调用[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)() 或设置任何转换属性[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新矩阵[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。如果您更改转换属性，则不会发送此通知。 |
| `QGraphicsItem::ItemTransformHasChanged`            | `10` | 该项目的变换矩阵已更改，因为[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)被调用，或者变换属性之一被改变。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且在项目的局部变换矩阵更改后。value 参数是新矩阵（与[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（））， 和[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)忽略此通知的返回值（即只读通知）。 |
| `QGraphicsItem::ItemRotationChange`                 | `28` | 项目的旋转属性发生变化。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且当项目的旋转属性发生变化时（即，由于调用[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)())。value 参数是新的旋转（即双精度）；要获得旧的轮换，请致电[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)()。不要调用[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新的旋转[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemRotationHasChanged`             | `29` | 该项目的旋转属性已更改。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且在项目的旋转属性更改后。value 参数是新的旋转（即双精度），并且[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)忽略此通知的返回值（即只读通知）。不要调用[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。 |
| `QGraphicsItem::ItemScaleChange`                    | `30` | 项目的比例属性发生变化。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且当项目的缩放属性发生更改时（即，由于调用[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)())。value 参数是新的比例（即双精度）；要获取旧秤，请致电[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)()。不要调用[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新的比例[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemScaleHasChanged`                | `31` | 该项目的比例属性已更改。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且在项目的缩放属性更改后。value 参数是新的比例（即双精度），并且[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)忽略此通知的返回值（即只读通知）。不要调用[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。 |
| `QGraphicsItem::ItemTransformOriginPointChange`     | `32` | 项目的变换原点属性发生变化。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且当项目的变换原点属性发生更改时（即，由于调用[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)())。value 参数是新的原点（即[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）；要获取旧的原点，请致电[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)()。不要调用[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新的变换原点[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemTransformOriginPointHasChanged` | `33` | 该项目的变换原点属性已更改。如果出现以下情况，则会发送此通知[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志已启用，并且在项目的变换原点属性更改后。value 参数是新的原点（即[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）， 和[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)忽略此通知的返回值（即只读通知）。不要调用[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。 |
| `QGraphicsItem::ItemSelectedChange`                 | `4`  | 项目的选定状态发生变化。如果该项目当前已被选中，它将变为未选中状态，反之亦然。value 参数是新选择的状态（即 true 或 false）。不要调用[setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新的选定状态[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemSelectedHasChanged`             | `14` | 项目的选定状态已更改。value 参数是新选择的状态（即 true 或 false）。不要调用[setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemVisibleChange`                  | `2`  | 项目的可见状态发生变化。如果该项目当前可见，它将变得不可见，反之亦然。value 参数是新的可见状态（即 true 或 false）。不要调用[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新的可见状态[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemVisibleHasChanged`              | `12` | 该项目的可见状态已更改。value 参数是新的可见状态（即 true 或 false）。不要调用[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemParentChange`                   | `5`  | 该项目的父级发生变化。value 参数是新的父项（即[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)指针）。不要调用[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 在本通知送达时；相反，您可以从返回新的父级[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemParentHasChanged`               | `15` | 该项目的父项已更改。value 参数是新的父级（即，指向[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。不要调用[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemChildAddedChange`               | `6`  | 一个子项已添加到此项目中。value 参数是新的子项（即[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)指针）。请勿将此物品传递给任何物品的[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)() 在发送此通知时起作用。返回值未使用；您无法调整此通知中的任何内容。请注意，发送此通知时，新的子级可能尚未完全构造；在子进程上调用纯虚函数可能会导致崩溃。 |
| `QGraphicsItem::ItemChildRemovedChange`             | `7`  | 一个孩子已从此项目中移除。value 参数是要删除的子项（即[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)指针）。返回值未使用；您无法调整此通知中的任何内容。 |
| `QGraphicsItem::ItemSceneChange`                    | `11` | 该项目被移动到新场景。当将项目添加到其初始场景以及将其删除时，也会发送此通知。这几项[scene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scene)() 是旧场景，或者`nullptr`如果该项目尚未添加到场景中。value 参数是新场景（即[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)指针），或者`nullptr`如果该项目已从场景中删除。不要通过将此项目传递给来覆盖此更改[QGraphicsScene::addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)() 在本通知送达时；相反，您可以从返回新场景[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。请谨慎使用此功能；反对场景改变很快就会导致不必要的递归。 |
| `QGraphicsItem::ItemSceneHasChanged`                | `16` | 该项目的场景已更改。这几项[scene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scene)() 是新场景。当项目被添加到其初始场景以及被删除时，也会发送此通知。 value 参数是新场景（即，指向[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。不要在中调用 setScene()[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemCursorChange`                   | `17` | 项目的光标发生变化。value 参数是新的光标（即[QCursor](https://doc-qt-io.translate.goog/qt-6/qcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。不要调用[setCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCursor)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。相反，您可以从返回一个新游标[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemCursorHasChanged`               | `18` | 该项目的光标已更改。value 参数是新的光标（即[QCursor](https://doc-qt-io.translate.goog/qt-6/qcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。不要调用[setCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCursor)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemToolTipChange`                  | `19` | 该项目的工具提示发生变化。value 参数是新的工具提示（即[QToolTip](https://doc-qt-io.translate.goog/qt-6/qtooltip.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。不要调用[setToolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。相反，您可以从返回一个新的工具提示[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemToolTipHasChanged`              | `20` | 该项目的工具提示已更改。value 参数是新的工具提示（即[QToolTip](https://doc-qt-io.translate.goog/qt-6/qtooltip.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）。不要调用[setToolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemFlagsChange`                    | `21` | 该项目的标志发生变化。value 参数是新标志（即 quint32）。不要调用[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。相反，您可以从返回新标志[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemFlagsHaveChanged`               | `22` | 该项目的标志已更改。value 参数是新标志（即 quint32）。不要调用[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemZValueChange`                   | `23` | 项目的 Z 值发生变化。value 参数是新的 Z 值（即双精度值）。不要调用[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。相反，您可以从返回一个新的 Z 值[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemZValueHasChanged`               | `24` | 该项目的 Z 值已更改。value 参数是新的 Z 值（即双精度值）。不要调用[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemOpacityChange`                  | `25` | 项目的不透明度发生变化。value 参数是新的不透明度（即双精度）。不要调用[setOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)（） 在[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 发出此通知。相反，您可以从返回新的不透明度[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)()。 |
| `QGraphicsItem::ItemOpacityHasChanged`              | `26` | 该项目的不透明度已更改。value 参数是新的不透明度（即双精度）。不要调用[setOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)() 发出此通知。返回值被忽略。 |
| `QGraphicsItem::ItemScenePositionHasChanged`        | `27` | 该项目的场景位置已更改。如果出现以下情况，则会发送此通知[ItemSendsScenePositionChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)启用标志，并且在项目的场景位置发生变化之后（即，项目本身的位置或变换或者任何祖先的位置或变换发生变化）。value 参数是新的场景位置（与[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)（））， 和[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)忽略此通知的返回值（即只读通知）。 |

### 枚举 QGraphicsItem:: GraphicsItemFlag 标志 QGraphicsItem:: GraphicsItemFlags

此枚举描述了您可以在项目上设置的不同标志，以切换项目行为中的不同功能。

默认情况下，所有标志均被禁用。

| 持续的                                    | 价值   | 描述                                                         |
| ----------------------------------------- | ------ | ------------------------------------------------------------ |
| `QGraphicsItem::ItemIsMovable`            | `0x1`  | 该项目支持使用鼠标进行交互式移动。通过单击该项目然后拖动，该项目将与鼠标光标一起移动。如果该项目有子项，则所有子项也会被移动。如果该项目是所选内容的一部分，则所有选定的项目也会移动。通过基本实现提供此功能是为了方便[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的鼠标事件处理程序。 |
| `QGraphicsItem::ItemIsSelectable`         | `0x2`  | 该项目支持选择。启用此功能将启用[setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)() 切换项目的选择。它还会让该项目被自动选择作为调用的结果[QGraphicsScene::setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()，通过单击某个项目，或使用橡皮筋选择[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。 |
| `QGraphicsItem::ItemIsFocusable`          | `0x4`  | 该项目支持键盘输入焦点（即，它是一个输入项目）。启用此标志将允许该项目接受焦点，这再次允许将关键事件传递给[QGraphicsItem::keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)（） 和[QGraphicsItem::keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)()。 |
| `QGraphicsItem::ItemClipsToShape`         | `0x8`  | 该项目会剪辑成自己的形状。该项目无法在其形状之外绘制或接收鼠标、平板电脑、拖放或悬停事件。默认情况下它是禁用的。此行为由 QGraphicsView::drawItems() 或 QGraphicsScene::drawItems() 强制执行。该标志是在 Qt 4.3 中引入的。 |
| `QGraphicsItem::ItemClipsChildrenToShape` | `0x10` | 该项目将其所有后代的绘画剪裁为其自己的形状。作为该项目的直接或间接子项的项目不能在该项目的形状之外绘制。默认情况下，该标志被禁用；孩子们可以在任何地方画画。此行为由 QGraphicsView::drawItems() 或 QGraphicsScene::drawItems() 强制执行。该标志是在 Qt 4.3 中引入的。 |

**注意：**此标志类似于 ItemContainsChildrenInShape，但此外还通过剪切子项来强制包含。

| 持续的                                      | 价值   | 描述                                                         |
| ------------------------------------------- | ------ | ------------------------------------------------------------ |
| `QGraphicsItem::ItemIgnoresTransformations` | `0x20` | 该项目忽略继承的变换（即，其位置仍然锚定到其父项，但父项或视图旋转、缩放或剪切变换被忽略）。此标志对于保持文本标签项水平且未缩放非常有用，因此即使视图发生变换，它们仍然可读。设置后，项目的视图几何体和场景几何体将单独维护。你必须调用[deviceTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deviceTransform)() 来映射坐标并检测视图中的碰撞。默认情况下，该标志被禁用。该标志是在 Qt 4.3 中引入的。 |

**注意：**设置此标志后，您仍然可以缩放项目本身，并且缩放变换将影响项目的子项目。

| 持续的                                                | 价值      | 描述                                                         |
| ----------------------------------------------------- | --------- | ------------------------------------------------------------ |
| `QGraphicsItem::ItemIgnoresParentOpacity`             | `0x40`    | 该项目忽略其父项的不透明度。该项目的有效不透明度与其自身相同；它不与父级的不透明度结合。即使父项是半透明的，此标志也允许您的项目保持其绝对不透明度。该标志是在 Qt 4.5 中引入的。 |
| `QGraphicsItem::ItemDoesntPropagateOpacityToChildren` | `0x80`    | 该项目不会将其不透明度传播给其子项。此标志允许您创建一个不影响其子项的不透明度的半透明项目。该标志是在 Qt 4.5 中引入的。 |
| `QGraphicsItem::ItemStacksBehindParent`               | `0x100`   | 该项目堆叠在其父项后面。默认情况下，子项堆叠在父项的顶部。但是设置这个标志后，子进程就会被堆放在它后面。此标志对于投影效果和遵循父项几何图形而不在其顶部绘制的装饰对象很有用。该标志是在 Qt 4.5 中引入的。 |
| `QGraphicsItem::ItemUsesExtendedStyleOption`          | `0x200`   | 该项目使用任一[exposedRect](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exposedRect-var)在[QStyleOptionGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。默认情况下，[exposedRect](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#exposedRect-var)被初始化为项目的[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()。您可以启用此标志，以便使用更细粒度的值设置样式选项。使用[QStyleOptionGraphicsItem::levelOfDetailFromTransform](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#levelOfDetailFromTransform)() 如果您需要更高的值。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemHasNoContents`                    | `0x400`   | 该项目不会绘制任何东西（即调用[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)() 对项目没有影响）。您应该在不需要绘制的项目上设置此标志，以确保图形视图避免不必要的绘制准备。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemSendsGeometryChanges`             | `0x800`   | 该项目使[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 通知[ItemPositionChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemPositionHasChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemTransformChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemTransformHasChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemRotationChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemRotationHasChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemScaleChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemScaleHasChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum),[ItemTransformOriginPointChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum)， 和[ItemTransformOriginPointHasChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum)。出于性能原因，默认情况下禁用这些通知。您必须启用此标志才能接收位置和变换更改的通知。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemAcceptsInputMethod`               | `0x1000`  | 该项目支持通常用于亚洲语言的输入法。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemNegativeZStacksBehindParent`      | `0x2000`  | 如果该项目的 z 值为负，则该项目会自动堆叠在其父项后面。该标志使能[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)() 切换 ItemStacksBehindParent。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemIsPanel`                          | `0x4000`  | 该项目是一个面板。面板提供激活和包含的焦点处理。一次只能激活一个面板（请参阅[QGraphicsItem::isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)())。当没有面板处于活动状态时，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)激活所有非面板项目。窗口项目（即[QGraphicsItem::isWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWindow)() 返回`true`) 是面板。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemSendsScenePositionChanges`        | `0x10000` | 该项目使[itemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemChange)() 通知[ItemScenePositionHasChanged](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum)。出于性能原因，默认情况下禁用这些通知。您必须启用此标志才能接收场景位置更改的通知。该标志是在 Qt 4.6 中引入的。 |
| `QGraphicsItem::ItemContainsChildrenInShape`          | `0x80000` | 此标志指示该项目的所有直接或间接子项仅在该项目的形状内绘制。与 ItemClipsChildrenToShape 不同，不强制执行此限制。当您手动确保绘图绑定到项目的形状并希望避免与强制剪辑相关的成本时，请设置 ItemContainsChildrenInShape。设置此标志可以更有效地绘制和碰撞检测。默认情况下禁用该标志。 |

**注意：**如果同时设置了此标志和 ItemClipsChildrenToShape，则将强制执行剪辑。这相当于仅设置 ItemClipsChildrenToShape。

该标志是在 Qt 5.4 中引入的。

GraphicsItemFlags 类型是[QFlags](https://doc-qt-io.translate.goog/qt-6/qflags.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) <GraphicsItemFlag> 的类型定义。它存储 GraphicsItemFlag 值的 OR 组合。

### enum QGraphicsItem::PanelModality

该枚举指定模式面板的行为。模态面板是一种阻止其他面板输入的面板。请注意，模式面板的子项不会被阻止。

这些值为：

| 持续的                      | 价值 | 描述                                                         |
| --------------------------- | ---- | ------------------------------------------------------------ |
| `QGraphicsItem::NonModal`   | `0`  | 该面板不是模态的，不会阻止其他面板的输入。这是面板的默认值。 |
| `QGraphicsItem::PanelModal` | `1`  | 该面板是单个项目层次结构的模式，并阻止输入到其父面板、所有祖父母面板以及其父面板和祖父母面板的所有同级面板。 |
| `QGraphicsItem::SceneModal` | `2`  | 该窗口是整个场景的模态窗口，并阻止所有面板的输入。           |

**也可以看看**[QGraphicsItem::setPanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPanelModality)(),[QGraphicsItem::panelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panelModality)（）， 和[QGraphicsItem::ItemIsPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### enum QGraphicsItem::anonymous

虚拟返回的值[type](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)Qt 中标准图形项类中的 () 函数。Qt 中的所有此类标准图形项类都与 Type 的唯一值相关联，例如由[QGraphicsPathItem::type](https://doc-qt-io.translate.goog/qt-6/qgraphicspathitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)() 为 2。

| 持续的                    | 价值    | 描述                                                         |
| ------------------------- | ------- | ------------------------------------------------------------ |
| `QGraphicsItem::Type`     | `1`     | `class QGraphicsPathItem : public QAbstractGraphicsShapeItem { public:  enum { Type = 2 };    int type() const override { return Type; }  ... };` |
| `QGraphicsItem::UserType` | `65536` | 虚拟返回的最低值[type](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)() 自定义子类的函数[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。`class CustomItem : public QGraphicsItem { public:   enum { Type = UserType + 1 };    int type() const override   {       // Enable the use of qgraphicsitem_cast with this item.       return Type;   }   ... };` |

## 成员函数文档

### `[explicit]`QGraphicsItem::QGraphicsItem([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **parent* = nullptr)

使用给定的值构造一个 QGraphicsItem*parent*物品。它不会修改返回的父对象[QObject::parent](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parent)()。

如果*parent*是`nullptr`，您可以通过调用将项目添加到场景中[QGraphicsScene::addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。然后该项目将成为顶级项目。

**也可以看看**[QGraphicsScene::addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)（） 和[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)()。

### `[virtual]`QGraphicsItem::~QGraphicsItem()

摧毁了[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和它所有的孩子。如果该项目当前与场景关联，则该项目将在删除之前从场景中移除。

**注意：**从列表中删除该项目会更有效[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在销毁该物品之前。

### bool QGraphicsItem::acceptDrops() const

返回`true`此项是否可以接受拖放事件；否则，返回`false`。默认情况下，项目不接受拖放事件；项目对于拖放是透明的。

**也可以看看**[setAcceptDrops](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptDrops)()。

### bool QGraphicsItem::acceptHoverEvents() const

`true`如果项目接受悬停事件则返回（[QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）；否则，返回`false`。默认情况下，项目不接受悬停事件。

**也可以看看**[setAcceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptHoverEvents)（） 和[setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)()。

### bool QGraphicsItem::acceptTouchEvents() const

`true`如果项目接受则返回[touch events](https://doc-qt-io.translate.goog/qt-6/qtouchevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 否则，返回`false`。默认情况下，项目不接受触摸事件。

**也可以看看**[setAcceptTouchEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptTouchEvents)()。

### [Qt::MouseButtons](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum) QGraphicsItem::acceptedMouseButtons() const

返回该项目接受鼠标事件的鼠标按钮。默认情况下，接受所有鼠标按钮。

如果某个项目接受鼠标按钮，则当为该鼠标按钮传递鼠标按下事件时，它将成为鼠标抓取器项目。但是，如果该项目不接受该按钮，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会将鼠标事件转发到其下方的第一个项目。

**也可以看看**[setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)（） 和[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)()。

### `[virtual]`void QGraphicsItem::advance(int *phase*)

对于所有项目，此虚函数被调用两次[QGraphicsScene::advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)（） 投币口。在第一阶段，所有项目都被调用*phase*== 0，表示场景中的物品即将前进，然后调用所有物品*phase*== 1. 如果您需要简单的场景控制动画，请重新实现此函数来更新您的项目。

默认实现不执行任何操作。

该函数用于动画。另一种选择是多重继承[QObject](https://doc-qt-io.translate.goog/qt-6/qobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)和[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)并使用[Animation Framework](https://doc-qt-io.translate.goog/qt-6/animation-overview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[QGraphicsScene::advance](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#advance)（） 和[QTimeLine](https://doc-qt-io.translate.goog/qt-6/qtimeline.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[pure virtual]`[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::boundingRect() const

这个纯虚函数将项目的外边界定义为矩形；所有绘画都必须限制在项目的边界矩形内。[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用它来确定该项目是否需要重绘。

尽管项目的形状可以是任意的，但边界矩形始终是矩形，并且不受项目变换的影响。

如果你想改变项目的边界矩形，你必须首先调用[prepareGeometryChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepareGeometryChange)()。这会通知场景即将发生的变化，以便它可以更新其项目几何索引；否则，场景将不知道该项目的新几何形状，并且结果是未定义的（通常，渲染伪像留在视图中）。

重新实现这个函数让[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)确定小部件的哪些部分（如果有）需要重新绘制。

注意：对于绘制轮廓/笔划的形状，在边界矩形中包含笔宽度的一半非常重要。不过，没有必要补偿抗锯齿。

例子：

```
QRectF CircleItem::boundingRect() const
{
    qreal penWidth = 1;
    return QRectF(-radius - penWidth / 2, -radius - penWidth / 2,
                  diameter + penWidth, diameter + penWidth);
}
```

**也可以看看**[boundingRegion](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegion)(),[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)(),[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)(),[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)， 和[prepareGeometryChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepareGeometryChange)()。

### [QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::boundingRegion(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*itemToDeviceTransform*) const

返回此项的边界区域。返回区域的坐标空间取决于*itemToDeviceTransform*。如果您传递身份[QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)作为参数，该函数将返回局部坐标区域。

边界区域描述了项目视觉内容的粗略轮廓。虽然计算成本较高，但也比[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()，它可以帮助避免在更新项目时不必要的重新绘制。这对于薄的项目（例如，线条或简单的多边形）特别有效。您可以通过调用调整边界区域的粒度[setBoundingRegionGranularity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBoundingRegionGranularity)()。默认粒度为0；其中项目的边界区域与其边界矩形相同。

*itemToDeviceTransform*是从项目坐标到设备坐标的转换。如果你想让这个函数返回一个[QRegion](https://doc-qt-io.translate.goog/qt-6/qregion.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在场景坐标中，你可以通过[sceneTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneTransform)() 作为参数。

**也可以看看**[boundingRegionGranularity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegionGranularity)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::boundingRegionGranularity() const

返回项目的边界区域粒度；介于 0 和 1 之间的值。默认值为 0（即最低粒度，其中边界区域对应于项目的边界矩形）。

**也可以看看**[setBoundingRegionGranularity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setBoundingRegionGranularity)()。

### [QGraphicsItem::CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum) QGraphicsItem::cacheMode() const

返回此项的缓存模式。默认模式是[NoCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)（即，缓存被禁用并且所有绘制都是立即的）。

**也可以看看**[setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *> QGraphicsItem::childItems() const

返回该项目的子项的列表。

项目按堆叠顺序排序。这会考虑项目的插入顺序及其 Z 值。

**也可以看看**[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)(),[zValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zValue)（）， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::childrenBoundingRect() const

返回该项目的后代（即，它的子项、它们的子项等）在本地坐标中的边界矩形。该矩形将包含映射到本地坐标后的所有后代。如果该项目没有子项，则此函数返回空[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

这不包括该项目自己的边界矩形；它只返回其后代累积的边界矩形。如果您需要包含该项目的边界矩形，您可以添加[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)使用 QRectF::operator|() 将 () 转换为 kidsBoundingRect()。

这个函数的复杂度是线性的；它通过迭代所有后代来确定返回的边界矩形的大小。

**也可以看看**[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（） 和[sceneBoundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneBoundingRect)()。

### void QGraphicsItem::clearFocus()

从项目中获取键盘输入焦点。

如果它有焦点，[focus out event](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)发送到此项目以告诉它即将失去焦点。

仅设置的项目[ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志或设置适当焦点策略的小部件可以接受键盘焦点。

**也可以看看**[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)(),[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)（）， 和[QGraphicsWidget::focusPolicy](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusPolicy-prop)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::clipPath() const

返回该项目的剪辑路径，或者一个空的[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果这个项目没有被剪裁。剪辑路径限制项目的外观和交互（即限制项目可以在其中绘制和接收事件的区域）。

您可以通过设置来启用剪辑[ItemClipsToShape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)或者[ItemClipsChildrenToShape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)旗帜。该项目的剪辑路径是通过与所有剪辑祖先的形状相交来计算的。如果该项目设置[ItemClipsToShape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)，最终的剪辑与项目自身的形状相交。

**注意：**裁剪会对所有涉及的项目带来性能损失；如果可以的话，您通常应该避免使用裁剪（例如，如果您的项目总是在内部绘制）[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（） 或者[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)() 边界，不需要裁剪）。

**也可以看看**[isClipped](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isClipped)(),[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)（）， 和[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)()。

### `[virtual]`bool QGraphicsItem::collidesWithItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **other*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

`true`如果该项目与以下项目发生碰撞则返回*other*; 否则返回`false`.

这*mode*应用于*other*，然后将生成的形状或边界矩形与该项目的形状进行比较。默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum);*other*如果该项目与该项目的形状相交、包含或包含在该项目的形状中，则与该项目发生碰撞（请参阅[Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum)了解详情）。

默认实现基于形状交集，它调用[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)() 在这两个项目上。由于当形状复杂时，任意形状与形状相交的复杂性会以一个数量级增长，因此此操作可能会非常耗时。您可以选择在子类中重新实现此函数[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供自定义算法。这使您可以利用自己物品形状的自然约束，以提高碰撞检测的性能。例如，两个未变形的完美圆形物体的碰撞可以通过比较它们的位置和半径来非常有效地确定。

请记住，当重新实现此函数并调用[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)（） 或者[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（） 在*other*，在发生任何相交之前，返回的坐标必须映射到该项目的坐标系。

**也可以看看**[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)()。

### `[virtual]`bool QGraphicsItem::collidesWithPath(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*, [Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

`true`如果该项目与以下项目发生碰撞则返回*path*。

碰撞由下式确定*mode*。默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum);*path*如果该项目与该项目的形状相交、包含或包含在该项目的形状中，则与该项目发生碰撞。

请注意，此函数检查项目的形状或边界矩形（取决于*mode*) 包含在*path*，而不是是否*path*包含在项目形状或边界矩形内。

**也可以看看**[collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)(),[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（）， 和[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)()。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *> QGraphicsItem::collidingItems([Qt::ItemSelectionMode](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum) *mode* = Qt::IntersectsItemShape) const

返回与该项目发生碰撞的所有项目的列表。

检测碰撞的方式是通过应用来确定的*mode*与该项目进行比较的项目，即根据该项目的形状检查每个项目的形状或边界矩形。默认值为*mode*是[Qt::IntersectsItemShape](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ItemSelectionMode-enum)。

**也可以看看**[collidesWithItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithItem)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *QGraphicsItem::commonAncestorItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **other*) const

返回该项目最接近的共同祖先项目并且*other*，或者`nullptr`如果*other*是`nullptr`，或者没有共同的祖先。

**也可以看看**[isAncestorOf](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isAncestorOf)()。

### `[virtual]`bool QGraphicsItem::contains(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

`true`如果该项目包含则返回*point*，在局部坐标中；否则，返回 false。它最常被调用于[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)确定光标所在的项目，因此，该函数的实现应该尽可能轻量级。

默认情况下，该函数调用[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)()，但您可以在子类中重新实现它以提供（也许更有效）的实现。

**也可以看看**[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)(),[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（）， 和[collidesWithPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithPath)()。

### `[virtual protected]`void QGraphicsItem::contextMenuEvent([QGraphicsSceneContextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenecontextmenuevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

可以在子类中重新实现此事件处理程序以处理上下文菜单事件。这*event*参数包含有关要处理的事件的详细信息。

如果您忽略该事件（即，通过调用[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)()),*event*将传播到该项目下的任何项目。如果没有项目接受该事件，该事件将被场景忽略并传播到视图。

开一个很常见[QMenu](https://doc-qt-io.translate.goog/qt-6/qmenu.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)响应接收上下文菜单事件。例子：

```
void CustomItem::contextMenuEvent(QGraphicsSceneContextMenuEvent *event)
{
    QMenu menu;
    QAction *removeAction = menu.addAction("Remove");
    QAction *markAction = menu.addAction("Mark");
    QAction *selectedAction = menu.exec(event->screenPos());
    // ...
}
```

默认实现会忽略该事件。

**也可以看看**[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### [QCursor](https://doc-qt-io.translate.goog/qt-6/qcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::cursor() const

返回项目的当前光标形状。当鼠标光标位于该项目上方时，它将呈现此形状。请参阅[list of predefined cursor objects](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorShape-enum)以获得一系列有用的形状。

编辑器项目可能需要使用 I 型光标：

```
item->setCursor(Qt::IBeamCursor);
```

如果未设置光标，则使用下面项目的光标。

**也可以看看**[setCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCursor)(),[hasCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasCursor)(),[unsetCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unsetCursor)(),[QWidget::cursor](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursor-prop)， 和[QGuiApplication::overrideCursor](https://doc-qt-io.translate.goog/qt-6/qguiapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overrideCursor)()。

### [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::data(int *key*) const

返回该项目的键的自定义数据*key*作为一个[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

自定义项目数据对于在任何项目中存储任意属性非常有用。例子：

```
static const int ObjectName = 0;

QGraphicsItem *item = scene.itemAt(100, 50);
if (item->data(ObjectName).toString().isEmpty()) {
    if (qgraphicsitem_cast<ButtonItem *>(item))
        item->setData(ObjectName, "Button");
}
```

Qt 不使用此功能来存储数据；它仅为了方便用户而提供。

**也可以看看**[setData](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setData)()。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::deviceTransform(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*viewportTransform*) const

返回此项的设备转换矩阵，使用*viewportTransform*从场景映射到设备坐标。该矩阵可用于将坐标和几何形状从该项目的本地坐标系映射到视口（或任何设备）的坐标系。要从视口映射坐标，必须首先反转返回的矩阵。

例子：

```
QGraphicsRectItem rect;
rect.setPos(100, 100);

rect.deviceTransform(view->viewportTransform()).map(QPointF(0, 0));
// returns the item's (0, 0) point in view's viewport coordinates

rect.deviceTransform(view->viewportTransform()).inverted().map(QPointF(100, 100));
// returns view's viewport's (100, 100) coordinate in item coordinates
```

此函数与将此项目的场景变换与视图的视口变换相结合相同，但它也理解[ItemIgnoresTransformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)旗帜。设备变换可用于对不可变换的项目进行精确的坐标映射（和碰撞检测）。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)(),[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)， 和[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)()。

### `[virtual protected]`void QGraphicsItem::dragEnterEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的拖动输入事件。当光标进入项目区域时，会生成拖动输入事件。

通过接受事件（即通过调用[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)())，该项目除了接收拖动移动和拖动离开之外，还将接受放置事件。否则，该事件将被忽略并传播到下面的项目。如果该事件被接受，则该项目将在控制返回到事件循环之前接收拖动移动事件。

DragEnterEvent 的常见实现接受或忽略*event*取决于相关的 mime 数据*event*。例子：

```
CustomItem::CustomItem()
{
    setAcceptDrops(true);
    ...
}

void CustomItem::dragEnterEvent(QGraphicsSceneDragDropEvent *event)
{
    event->setAccepted(event->mimeData()->hasFormat("text/plain"));
}
```

默认情况下，项目不接收拖放事件；要启用此功能，请致电`setAcceptDrops(true)`.

默认实现不执行任何操作。

**也可以看看**[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)(),[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（）， 和[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)()。

### `[virtual protected]`void QGraphicsItem::dragLeaveEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的拖动离开事件。当光标离开项目区域时，会生成拖动离开事件。大多数情况下，您不需要重新实现此功能，但它对于重置项目中的状态（例如突出显示）很有用。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

默认情况下，项目不接收拖放事件；要启用此功能，请致电`setAcceptDrops(true)`.

默认实现不执行任何操作。

**也可以看看**[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)(),[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)（）， 和[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)()。

### `[virtual protected]`void QGraphicsItem::dragMoveEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的拖动移动事件。当光标在项目区域内移动时，会生成拖动移动事件。大多数情况下，您不需要重新实现此函数；它用于指示只有该物品的一部分可以接受掉落。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*切换该物品是否接受事件中该位置的掉落。默认情况下，*event*被接受，表明该物品允许在指定位置掉落。

默认情况下，项目不接收拖放事件；要启用此功能，请致电`setAcceptDrops(true)`.

默认实现不执行任何操作。

**也可以看看**[dropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dropEvent)(),[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)（）， 和[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)()。

### `[virtual protected]`void QGraphicsItem::dropEvent([QGraphicsSceneDragDropEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenedragdropevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的放置事件。如果接受了最后一个拖动移动事件，则项目只能接收放置事件。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

默认情况下，项目不接收拖放事件；要启用此功能，请致电`setAcceptDrops(true)`.

默认实现不执行任何操作。

**也可以看看**[dragEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragEnterEvent)(),[dragMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragMoveEvent)（）， 和[dragLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#dragLeaveEvent)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::effectiveOpacity() const

返回此项的*有效*不透明度，介于 0.0（透明）和 1.0（不透明）之间。该值是该项目的局部不透明度及其父级和祖先的不透明度的组合。有效不透明度决定项目的渲染方式。

**也可以看看**[opacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opacity)(),[setOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)(),[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)(),[ItemIgnoresParentOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)， 和[ItemDoesntPropagateOpacityToChildren](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### void QGraphicsItem::ensureVisible(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF(), int *xmargin* = 50, int *ymargin* = 50)

如果该项目是由某个人查看的场景的一部分[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，这个便利函数将尝试滚动视图以确保*rect*在视图的视口内可见。如果*rect*是一个空矩形（默认），[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将默认为项目的边界矩形。*xmargin*和*ymargin*是视图应用于边距的像素数。

如果无法到达指定的矩形，则内容将滚动到最近的有效位置。

如果此项目未被查看[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，这个函数什么也不做。

**也可以看看**[QGraphicsView::ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)()。

### void QGraphicsItem::ensureVisible([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*, int *xmargin* = 50, int *ymargin* = 50)

这个便利函数相当于调用 EnsureVisible([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*),*xmargin*,*ymargin*）。

### bool QGraphicsItem::filtersChildEvents() const

如果此项过滤了子事件，则返回`true`（即，将发送给其任何子项的所有事件改为发送到此项）；否则，返回 false。

默认值为 false；子事件不会被过滤。

**也可以看看**[setFiltersChildEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFiltersChildEvents)()。

### [QGraphicsItem::GraphicsItemFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum) QGraphicsItem::flags() const

返回该项目的标志。这些标志描述了该项目的哪些可配置功能已启用和未启用。例如，如果标志包括[ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)，该项目可以接受输入焦点。

默认情况下，不启用任何标志。

**也可以看看**[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)（） 和[setFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlag)()。

### `[virtual protected]`void QGraphicsItem::focusInEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收此项事件的焦点。默认实现调用[ensureVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ensureVisible)()。

**也可以看看**[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)(),[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（）， 和[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *QGraphicsItem::focusItem() const

如果此项、该项的子项或后代当前具有输入焦点，则此函数将返回指向该项的指针。如果没有后代具有输入焦点，`nullptr`则返回。

**也可以看看**[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)（）， 和[QWidget::focusWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusWidget)()。

### `[virtual protected]`void QGraphicsItem::focusOutEvent([QFocusEvent](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的焦点移出事件。默认实现不执行任何操作。

**也可以看看**[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)(),[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（）， 和[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *QGraphicsItem::focusProxy() const

返回此项的焦点代理，或者`nullptr`如果该项没有焦点代理。

**也可以看看**[setFocusProxy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusProxy)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)（）， 和[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)()。

### void QGraphicsItem::grabKeyboard()

抓取键盘输入。

该项目将接收场景的所有键盘输入，直到发生以下事件之一：

- 该项目变得不可见
- 该项目已从场景中移除
- 该项目已删除
- 该项目调用[ungrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabKeyboard)()
- 另一个项目调用grabKeyboard()；当其他项目调用时，该项目将重新获得键盘抓取[ungrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabKeyboard)()。

当一个项目获得键盘抓取时，它会收到一个[QEvent::GrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件。当它失去键盘抓取时，它会收到一个[QEvent::UngrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件。这些事件可用于检测您的项目何时通过获得输入焦点以外的其他方式获得或失去键盘抓取。

在 Qt 中几乎不需要显式地抓取键盘，因为 Qt 会明智地抓取和释放键盘。特别是，当您的项目获得输入焦点时，Qt 会抓住键盘，并在您的项目失去输入焦点或隐藏项目时释放键盘。

请注意，只有可见的项目才能获取键盘输入。在不可见的项目上调用grabKeyboard()没有任何效果。

键盘事件不受影响。

**也可以看看**[ungrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabKeyboard)(),[grabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabMouse)（）， 和[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)()。

### void QGraphicsItem::grabMouse()

抓取鼠标输入。

该项目将接收场景的所有鼠标事件，直到发生以下任何事件：

- 该项目变得不可见
- 该项目已从场景中移除
- 该项目已删除
- 项目调用[ungrabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabMouse)()
- 另一个项目调用grabMouse()；当其他项目调用时，该项目将重新获得鼠标抓取[ungrabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabMouse)()。

当一个项目获得鼠标抓取时，它会收到一个[QEvent::GrabMouse](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件。当它失去鼠标抓取时，它会收到一个[QEvent::UngrabMouse](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#Type-enum)事件。这些事件可用于通过接收鼠标按钮事件以外的其他方式来检测您的项目何时获得或失去鼠标抓取。

在 Qt 中几乎不需要显式地抓取鼠标，因为 Qt 会明智地抓取和释放鼠标。特别是，当您按下鼠标按钮时，Qt 会抓住鼠标，并保持鼠标被抓住直到您释放最后一个鼠标按钮。还，[Qt::Popup](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#WindowType-enum)小部件在显示时隐式调用grabMouse()，并且[ungrabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabMouse)() 隐藏时。

请注意，只有可见项目才能抓取鼠标输入。对不可见的项目调用grabMouse() 没有任何效果。

键盘事件不受影响。

**也可以看看**[QGraphicsScene::mouseGrabberItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseGrabberItem)(),[ungrabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabMouse)（）， 和[grabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabKeyboard)()。

### [QGraphicsEffect](https://doc-qt-io.translate.goog/qt-6/qgraphicseffect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::graphicsEffect() const

返回指向该项目效果的指针（如果有）；否则`nullptr`。

**也可以看看**[setGraphicsEffect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGraphicsEffect)()。

### [QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::group() const

返回指向该项目的项目组的指针，或者`nullptr`如果该项目不是组的成员。

**也可以看看**[setGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setGroup)(),[QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)， 和[QGraphicsScene::createItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createItemGroup)()。

### bool QGraphicsItem::hasCursor() const

返回`true`此项是否设置了光标；否则，返回 false。

默认情况下，项目没有任何光标设置。[cursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursor)() 将返回一个标准的指向箭头光标。

**也可以看看**[unsetCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unsetCursor)()。

### bool QGraphicsItem::hasFocus() const

返回`true`此项目是否处于活动状态，并且它或它的[focus proxy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusProxy)有键盘输入焦点；否则，返回`false`。

**也可以看看**[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)(),[QGraphicsScene::setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)（）， 和[isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### void QGraphicsItem::hide()

隐藏项目（默认情况下项目可见）。

这个便利功能相当于调用`setVisible(false)`.

**也可以看看**[show](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)（） 和[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。

### `[virtual protected]`void QGraphicsItem::hoverEnterEvent([QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的悬停输入事件。默认实现调用[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)(); 否则它什么也不做。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

**也可以看看**[hoverMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverMoveEvent)(),[hoverLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverLeaveEvent)(),[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（）， 和[setAcceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptHoverEvents)()。

### `[virtual protected]`void QGraphicsItem::hoverLeaveEvent([QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的悬停离开事件。默认实现调用[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)(); 否则它什么也不做。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

**也可以看看**[hoverEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverEnterEvent)(),[hoverMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverMoveEvent)(),[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（）， 和[setAcceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptHoverEvents)()。

### `[virtual protected]`void QGraphicsItem::hoverMoveEvent([QGraphicsSceneHoverEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenehoverevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的悬停移动事件。默认实现不执行任何操作。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

**也可以看看**[hoverEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverEnterEvent)(),[hoverLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverLeaveEvent)(),[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（）， 和[setAcceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptHoverEvents)()。

### `[virtual protected]`void QGraphicsItem::inputMethodEvent([QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收此项的输入法事件。默认实现会忽略该事件。

**也可以看看**[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)（） 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### [Qt::InputMethodHints](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodHint-enum) QGraphicsItem::inputMethodHints() const

返回此项的当前输入法提示。

输入法提示仅与输入项相关。输入法使用提示来指示它应该如何操作。例如，如果设置了 Qt::ImhNumbersOnly 标志，则输入法可能会更改其视觉组件以反映只能输入数字。

效果可能因输入法实现而异。

**也可以看看**[setInputMethodHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setInputMethodHints)（） 和[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)()。

### `[virtual protected]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::inputMethodQuery([Qt::InputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodQuery-enum) *query*) const

此方法仅与输入项相关。输入法使用它来查询项目的一组属性，以便能够支持复杂的输入法操作，例如支持周围文本和重新转换。*query*指定查询哪个属性。

**也可以看看**[inputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodEvent)（） 和[QInputMethodEvent](https://doc-qt-io.translate.goog/qt-6/qinputmethodevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QGraphicsItem::installSceneEventFilter([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **filterItem*)

为该项目安装事件过滤器*filterItem*，导致该项目的所有事件首先通过*filterItem*的[sceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEventFilter)（） 功能。

要过滤另一个项目的事件，请安装此项目作为另一个项目的事件过滤器。例子：

```
QGraphicsScene scene;
QGraphicsEllipseItem *ellipse = scene.addEllipse(QRectF(-10, -10, 20, 20));
QGraphicsLineItem *line = scene.addLine(QLineF(-10, -10, 20, 20));

line->installSceneEventFilter(ellipse);
// line's events are filtered by ellipse's sceneEventFilter() function.

ellipse->installSceneEventFilter(line);
// ellipse's events are filtered by line's sceneEventFilter() function.
```

一个项目只能过滤同一场景中其他项目的事件。此外，项目无法过滤自己的事件；相反，你可以重新实现[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)（） 直接地。

项目必须属于要安装和使用场景事件过滤器的场景。

**也可以看看**[removeSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#removeSceneEventFilter)(),[sceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEventFilter)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### bool QGraphicsItem::isActive() const

返回`true`此项是否处于活动状态；否则返回`false`.

仅当场景处于活动状态时，项目才能处于活动状态。如果某个项目是活动面板或者是活动面板的后代，则该项目是活动的。非活动面板中的项目不处于活动状态。

当场景没有活动面板时，不属于面板的项目会跟随场景激活。

只有活动项目才能获得输入焦点。

**也可以看看**[QGraphicsScene::isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)(),[QGraphicsScene::activePanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#activePanel)(),[panel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panel)（）， 和[isPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPanel)()。

### bool QGraphicsItem::isAncestorOf(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **child*) const

`true`如果该项目是以下项目的祖先，则返回*child*（即，如果该项目是*child*的父母，或其中之一*child*父母的祖先）。

**也可以看看**[parentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentItem)()。

### bool QGraphicsItem::isBlockedByModalPanel([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) ***blockingPanel* = nullptr) const

`true`如果该项目被模式面板阻止则返回，否则返回 false。如果*blockingPanel*是非零，*blockingPanel*将被设置为阻止该项目的模式面板。如果该项目未被阻止，*blockingPanel*不会被该函数设置。

此函数始终返回`false`不在场景中的项目。

**也可以看看**[panelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panelModality)(),[setPanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPanelModality)（）， 和[PanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PanelModality-enum)。

### bool QGraphicsItem::isClipped() const

`true`如果该项目被剪裁则返回。如果某个项目设置了[ItemClipsToShape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志，或者如果它或它的任何祖先已经设置了[ItemClipsChildrenToShape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)旗帜。

剪切会影响项目的外观（即绘画）以及鼠标和悬停事件的传递。

**也可以看看**[clipPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clipPath)(),[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)（）， 和[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)()。

### bool QGraphicsItem::isEnabled() const

返回`true`该项目是否已启用；否则，返回 false。

**也可以看看**[setEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setEnabled)()。

### bool QGraphicsItem::isObscured(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF()) const

这是一个过载功能。

返回`true`如果*rect*被其上方任何碰撞项目的不透明形状完全遮挡（即，具有比该项目更高的 Z 值）。

**也可以看看**[opaqueArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueArea)()。

### bool QGraphicsItem::isObscured([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这是一个过载功能。

这个便利函数相当于调用 isObscured([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### `[virtual]`bool QGraphicsItem::isObscuredBy(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*) const

`true`如果该项目的边界矩形完全被 的不透明形状遮挡，则返回*item*。

基本实施图*item*的[opaqueArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueArea)() 到该项目的坐标系，然后检查该项目是否[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 完全包含在映射的形状内。

您可以重新实现此函数以提供自定义算法来确定该项目是否被遮挡*item*。

**也可以看看**[opaqueArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opaqueArea)（） 和[isObscured](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscured)()。

### bool QGraphicsItem::isPanel() const

`true`如果该项目是面板则返回；否则返回`false`.

**也可以看看**[QGraphicsItem::panel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panel)（） 和[ItemIsPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### bool QGraphicsItem::isSelected() const

`true`如果该项被选中则返回；否则，返回 false。

组中的项目继承组的选定状态。

默认情况下不选择项目。

**也可以看看**[setSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelected)（） 和[QGraphicsScene::setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()。

### bool QGraphicsItem::isUnderMouse() const

`true`如果该项当前位于某个视图中的鼠标光标下方，则返回；否则，返回 false。

**也可以看看**[QGraphicsScene::views](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#views)（） 和[QCursor::pos](https://doc-qt-io.translate.goog/qt-6/qcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)()。

### bool QGraphicsItem::isVisible() const

返回`true`该项目是否可见；否则，返回 false。

请注意，该项目的一般可见性与它是否实际被可视化无关。[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。

### bool QGraphicsItem::isVisibleTo(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **parent*) const

返回`true`该项目是否可见*parent*; 否则，返回 false。*parent*可以是`nullptr`，在这种情况下，该函数将返回该项目是否对场景可见。

一个项目可能对其祖先不可见，即使[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)（） 是真的。即使它的祖先也可能看到[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 为假。如果隐藏任何祖先，则该项目本身将被隐式隐藏，在这种情况下该函数将返回 false。

**也可以看看**[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)（） 和[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。

### bool QGraphicsItem::isWidget() const

返回`true`该项目是否是一个小部件（即[QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）；否则，返回`false`。

### bool QGraphicsItem::isWindow() const

`true`如果该项目是 a，则返回[QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)窗口，否则返回 false。

**也可以看看**[QGraphicsWidget::windowFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#windowFlags-prop)()。

### `[virtual protected]`[QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::itemChange([QGraphicsItem::GraphicsItemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum) *change*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*value*)

这个虚函数被调用[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)通知自定义项目该项目的某些部分的状态发生了变化。通过重新实现此函数，您可以对更改做出反应，并且在某些情况下（取决于*change*），可以进行调整。

*change*是正在改变的项目的参数。*value*是新值；值的类型取决于*change*。

例子：

```
QVariant Component::itemChange(GraphicsItemChange change, const QVariant &value)
{
    if (change == ItemPositionChange && scene()) {
        // value is the new position.
        QPointF newPos = value.toPointF();
        QRectF rect = scene()->sceneRect();
        if (!rect.contains(newPos)) {
            // Keep the item inside the scene rect.
            newPos.setX(qMin(rect.right(), qMax(newPos.x(), rect.left())));
            newPos.setY(qMin(rect.bottom(), qMax(newPos.y(), rect.top())));
            return newPos;
        }
    }
    return QGraphicsItem::itemChange(change, value);
}
```

默认实现不执行任何操作并返回*value*。

注：一定[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不能在此函数的重新实现中调用函数；看到[GraphicsItemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum)文档了解详细信息。

**也可以看看**[GraphicsItemChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemChange-enum)。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::itemTransform(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **other*, bool **ok* = nullptr) const

返回一个[QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将该项目的坐标映射到*other*。如果*ok*不为空，如果没有这样的转换，则指向的布尔值*ok*将被设置为 false；否则它将被设置为 true。

这种转换提供了一种替代方案[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)（） 或者[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)() 函数，通过返回适当的变换，以便您可以自己映射形状和坐标。它还可以帮助您在相同的两个项目之间重复映射时编写更高效的代码。

**注意：**在极少数情况下，两个项目之间没有映射的转换。

**也可以看看**[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[deviceTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#deviceTransform)()。

### `[virtual protected]`void QGraphicsItem::keyPressEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收此项的按键事件。默认实现会忽略该事件。如果您重新实现此处理程序，则该事件将默认被接受。

请注意，只有设置了[ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志，并且具有键盘输入焦点。

**也可以看看**[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)(),[QGraphicsScene::setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### `[virtual protected]`void QGraphicsItem::keyReleaseEvent([QKeyEvent](https://doc-qt-io.translate.goog/qt-6/qkeyevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的按键释放事件。默认实现会忽略该事件。如果您重新实现此处理程序，则该事件将默认被接受。

请注意，只有设置了[ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志，并且具有键盘输入焦点。

**也可以看看**[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)(),[QGraphicsScene::setFocusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocusItem)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

绘制该点的地图*point*，这是在*item*的坐标系，到该项目的坐标系，并返回映射的坐标。

如果*item*是`nullptr`，该函数返回与[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，这是在*item*的坐标系，到该项目的坐标系，并以多边形形式返回映射的矩形。

如果*item*是`nullptr`，该函数返回与[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

映射多边形*polygon*，这是在*item*的坐标系，到该项目的坐标系，并返回映射的多边形。

如果*item*是`nullptr`，该函数返回与[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

映射路径*path*，这是在*item*的坐标系，到该项目的坐标系，并返回映射的路径。

如果*item*是`nullptr`，该函数返回与[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

这是一个过载功能。

这个便利函数相当于调用mapFromItem(*item*,[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapFromItem(item,[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromParent(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

绘制该点的地图*point*，位于此项的父级坐标系中，转换为该项的坐标系，并返回映射的坐标。

**也可以看看**[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromParent(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，位于此项的父级坐标系中，转换为该项的坐标系，并将映射的矩形作为多边形返回。

**也可以看看**[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromParent(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

映射多边形*polygon*，位于此项的父级坐标系中，转换为该项的坐标系，并返回映射的多边形。

**也可以看看**[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromParent(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

映射路径*path*，位于此项的父级坐标系中，到该项的坐标系，并返回映射路径。

**也可以看看**[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromParent([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

这是一个过载功能。

这个便利函数相当于调用mapFromParent([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromParent([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromScene(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

绘制该点的地图*point*，位于该项目的场景坐标系中，转换为该项目的坐标系，并返回映射的坐标。

**也可以看看**[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，它位于该项目的场景坐标系中，到该项目的坐标系，并将映射的矩形作为多边形返回。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromScene(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

映射多边形*polygon*，位于该项目的场景坐标系中，转换为该项目的坐标系，并返回映射的多边形。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromScene(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

映射路径*path*，位于该项目的场景坐标系中，到该项目的坐标系，并返回映射路径。

**也可以看看**[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

这是一个过载功能。

这个便利函数相当于调用mapFromScene([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapFromScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapFromScene([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，这是在*item*的坐标系，到此项的坐标系，并将映射的矩形作为新矩形返回（即，生成的多边形的边界矩形）。

如果*item*是`nullptr`，该函数返回与[mapRectFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectFromScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectFromItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapRectFromItem(item,[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectFromParent(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，它位于该项目的父级坐标系中，到该项目的坐标系，并将映射的矩形作为新矩形返回（即，生成的多边形的边界矩形）。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectFromParent([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapRectFromParent([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectFromScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，它位于场景坐标中，到该项目的坐标系，并将映射的矩形作为新矩形返回（即，生成的多边形的边界矩形）。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectFromScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapRectFromScene([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，位于该项目的坐标系中，*item*的坐标系，并将映射的矩形作为新矩形返回（即生成的多边形的边界矩形）。

如果*item*是`nullptr`，该函数返回与[mapRectToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapRectToScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapRectToItem(item,[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectToParent(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，位于此项的坐标系中，到其父项的坐标系，并将映射的矩形作为新矩形返回（即，生成的多边形的边界矩形）。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectToParent([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapRectToParent([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectToScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，它位于该项目的坐标系中，到场景坐标系，并将映射的矩形作为新矩形返回（即，生成的多边形的边界矩形）。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapRectToScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapRectToScene([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

绘制该点的地图*point*，位于该项目的坐标系中，*item*的坐标系，并返回映射的坐标。

如果*item*是`nullptr`，该函数返回与[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，位于该项目的坐标系中，*item*的坐标系，并将映射的矩形作为多边形返回。

如果*item*是`nullptr`，该函数返回与[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

映射多边形*polygon*，位于该项目的坐标系中，*item*的坐标系，并返回映射的多边形。

如果*item*是`nullptr`，该函数返回与[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

映射路径*path*，位于该项目的坐标系中，*item*的坐标系，并返回映射路径。

如果*item*是`nullptr`，该函数返回与[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)()。

**也可以看看**[itemTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#itemTransform)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapFromItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromItem)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

这是一个过载功能。

这个便利函数相当于调用mapToItem(*item*,[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToItem(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapToItem(item,[QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToParent(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

绘制该点的地图*point*，位于此项的坐标系中，到其父项的坐标系中，并返回映射的坐标。如果该项目没有父项，*point*将被映射到场景的坐标系。

**也可以看看**[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToParent(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，位于此项的坐标系中，到其父项的坐标系，并将映射的矩形作为多边形返回。如果该项目没有父项，*rect*将被映射到场景的坐标系。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToParent(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

映射多边形*polygon*，位于该项目的坐标系中，到其父项的坐标系，并返回映射的多边形。如果该项目没有父项，*polygon*将被映射到场景的坐标系。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToParent(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

映射路径*path*，位于此项的坐标系中，到其父项的坐标系，并返回映射的路径。如果该项目没有父项，*path*将被映射到场景的坐标系。

**也可以看看**[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromParent)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToParent([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

这是一个过载功能。

这个便利函数相当于调用mapToParent([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToParent([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapToParent([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToScene(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*point*) const

绘制该点的地图*point*，它位于该项目的坐标系中，到场景的坐标系中，并返回映射的坐标。

**也可以看看**[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToScene(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect*) const

映射矩形*rect*，位于该项目的坐标系中，转换为场景的坐标系，并将映射的矩形作为多边形返回。

**也可以看看**[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToScene(const [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*polygon*) const

映射多边形*polygon*，位于该项目的坐标系中，转换为场景的坐标系，并返回映射的多边形。

**也可以看看**[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToScene(const [QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*path*) const

映射路径*path*，位于该项目的坐标系中，转换为场景的坐标系，并返回映射的路径。

**也可以看看**[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(),[mapToItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToItem)(),[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*) const

这是一个过载功能。

这个便利函数相当于调用mapToScene([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### [QPolygonF](https://doc-qt-io.translate.goog/qt-6/qpolygonf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::mapToScene([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *w*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *h*) const

这个便利函数相当于调用mapToScene([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*w*,*h*））。

### `[virtual protected]`void QGraphicsItem::mouseDoubleClickEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的鼠标双击事件。

当双击某个项目时，该项目将首先接收鼠标按下事件，然后是释放事件（即单击），然后是双击事件，最后是释放事件。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

默认实现调用[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)()。如果您想在重新实现此函数时保留基本实现，请在重新实现中调用 QGraphicsItem::mouseDoubleClickEvent() 。

请注意，如果项目既不接收双击事件，也不会接收双击事件。[selectable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)也不[movable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)（在这种情况下，单击鼠标将被忽略，并且会停止生成双击）。

**也可以看看**[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### `[virtual protected]`void QGraphicsItem::mouseMoveEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的鼠标移动事件。如果您确实收到此事件，则可以确定此项目也收到了鼠标按下事件，并且此项目是当前的鼠标抓取器。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

默认实现处理基本的项目交互，例如选择和移动。如果您想在重新实现此函数时保留基本实现，请在重新实现中调用 QGraphicsItem::mouseMoveEvent() 。

请注意[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)() 决定是哪个图形项接收鼠标事件。请参阅[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)() 详细说明。

**也可以看看**[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(),[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### `[virtual protected]`void QGraphicsItem::mousePressEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收此项的鼠标按下事件。鼠标按下事件仅传递给接受按下的鼠标按钮的项目。默认情况下，项目接受所有鼠标按钮，但您可以通过调用来更改此设置[setAcceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setAcceptedMouseButtons)()。

鼠标按下事件决定哪个项目应成为鼠标抓取器（请参阅[QGraphicsScene::mouseGrabberItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseGrabberItem)())。如果您不重新实现此函数，则按下事件将传播到该项目下方的任何最上面的项目，并且不会将其他鼠标事件传递到该项目。

如果你重新实现这个函数，*event*将默认被接受（参见[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)())，这个项目就是鼠标抓取器。这允许该项目接收未来的移动、释放和双击事件。如果你调用[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 在*event*，该项目将失去鼠标抓取，并且*event*将传播到下面任何最上面的项目。除非收到新的鼠标按下事件，否则不会向该项目传递更多鼠标事件。

默认实现处理基本的项目交互，例如选择和移动。如果您想在重新实现此函数时保留基本实现，请在重新实现中调用 QGraphicsItem::mousePressEvent() 。

该活动是[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)()d 对于两者都不是的项目[movable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)也不[selectable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

**也可以看看**[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(),[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### `[virtual protected]`void QGraphicsItem::mouseReleaseEvent([QGraphicsSceneMouseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenemouseevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的鼠标释放事件。

呼唤[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)（） 或者[QEvent::accept](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#accept)（） 在*event*没有影响。

默认实现处理基本的项目交互，例如选择和移动。如果您想在重新实现此函数时保留基本实现，请在重新实现中调用 QGraphicsItem::mouseReleaseEvent() 。

请注意[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)() 决定是哪个图形项接收鼠标事件。请参阅[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)() 详细说明。

**也可以看看**[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)(),[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)（）， 和[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### void QGraphicsItem::moveBy([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dy*)

将项目移动*dx*水平点，并且*dy*垂直指向。该函数相当于调用[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)（[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)() +[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*dx*,*dy*））。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::opacity() const

返回此项的局部不透明度，介于 0.0（透明）和 1.0（不透明）之间。该值与父代和祖先值结合到[effectiveOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#effectiveOpacity)()。有效不透明度决定了项目的渲染方式，并且还会影响其在被诸如以下函数查询时的可见性：[QGraphicsView::items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)()。

不透明度属性决定了传递给画家的状态[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)（） 功能。如果该项目已缓存，即[ItemCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)或者[DeviceCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)，有效属性将在渲染时应用于项目的缓存。

默认不透明度为1.0；完全不透明。

**也可以看看**[setOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)(),[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)(),[ItemIgnoresParentOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)， 和[ItemDoesntPropagateOpacityToChildren](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### `[virtual]`[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::opaqueArea() const

该虚函数返回一个表示该项目不透明区域的形状。如果使用不透明画笔或颜色（即不透明）填充某个区域，则该区域是不透明的。

该函数用于[isObscuredBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscuredBy)()，由底层项目调用，以确定它们是否被该项目遮挡。

默认实现返回空值[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，表示该项目是完全透明的，不会遮挡任何其他项目。

**也可以看看**[isObscuredBy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscuredBy)(),[isObscured](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isObscured)（）， 和[shape](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#shape)()。

### `[pure virtual]`void QGraphicsItem::paint([QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **painter*, const [QStyleOptionGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qstyleoptiongraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **option*, [QWidget](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **widget* = nullptr)

该函数通常被调用[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，在局部坐标中绘制项目的内容。

重新实现这个函数[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类提供项目的绘画实现，使用*painter*。这*option*参数提供项目的样式选项，例如其状态、暴露区域及其详细程度提示。这*widget*参数是可选的。如果提供，它指向正在绘制的小部件；否则为 0。对于缓存绘画，*widget*始终为 0。

```
void RoundRectItem::paint(QPainter *painter,
                          const QStyleOptionGraphicsItem *option,
                          QWidget *widget)
{
    painter->drawRoundedRect(-10, -10, 20, 20, 5, 5);
}
```

画家的笔默认为0宽度，其笔被初始化为[QPalette::Text](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorRole-enum)从绘画设备的调色板中选择画笔。画笔初始化为[QPalette::Window](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorRole-enum)。

确保将所有绘画限制在[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 以避免渲染伪影（如[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不会为你剪辑画家）。特别是，当[QPainter](https://doc-qt-io.translate.goog/qt-6/qpainter.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用指定的渲染形状的轮廓[QPen](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，轮廓的一半将绘制在您要渲染的形状的外部，一半绘制在内部（例如，使用 2 个单位的笔宽，您必须在内部绘制 1 个单位的轮廓）[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)())。[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)不支持使用非零宽度的化妆笔。

所有绘画都是在局部坐标中完成的。

**注意：**项目必须始终以完全相同的方式重新绘制自身，除非[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)（） 被称为; 否则可能会出现视觉伪影。换句话说，对 Paint() 的两次后续调用必须始终产生相同的输出，除非[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)他们之间调用了()。

**注意：**启用项目缓存并不能保证图形视图框架只会调用一次paint()，即使没有任何显式调用[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)()。请参阅文档[setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)（） 更多细节。

**也可以看看**[setCacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheMode)(),[QPen::width](https://doc-qt-io.translate.goog/qt-6/qpen.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#width)(),[Item Coordinates](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#item-coordinates)， 和[ItemUsesExtendedStyleOption](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *QGraphicsItem::panel() const

返回该项目的面板，或者`nullptr`如果该项目没有面板。如果该项目是面板，它将返回自身。否则它将返回最接近的祖先，即面板。

**也可以看看**[isPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPanel)（） 和[ItemIsPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### [QGraphicsItem::PanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PanelModality-enum) QGraphicsItem::panelModality() const

返回该项目的模态。

**也可以看看**[setPanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPanelModality)()。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *QGraphicsItem::parentItem() const

返回指向该项目的父项目的指针。如果该项目没有父项，`nullptr`则返回。

**也可以看看**[setParentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setParentItem)（） 和[childItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childItems)()。

### [QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::parentObject() const

返回指向项目父项的指针，转换为[QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。`nullptr`如果父项不是则返回[QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

**也可以看看**[parentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentItem)（） 和[childItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childItems)()。

### [QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::parentWidget() const

返回指向该项目的父窗口小部件的指针。该项目的父窗口小部件是作为窗口小部件的最接近的父项目。

**也可以看看**[parentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentItem)（） 和[childItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childItems)()。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::pos() const

返回项目在父坐标中的位置。如果该项目没有父项，则其位置以场景坐标给出。

项目的位置描述了它在父坐标中的原点（本地坐标 (0, 0)）；该函数的返回值与[mapToParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToParent)(0, 0)。

为了方便您也可以拨调用[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)() 来确定项目在场景坐标中的位置，无论其父项如何。

**也可以看看**[x](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#x)(),[y](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#y)(),[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### `[protected]`void QGraphicsItem::prepareGeometryChange()

为几何形状更改准备项目。在更改要保留的项目的边界矩形之前调用此函数[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的索引是最新的。

将调用prepareGeometryChange()[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 如果有必要的话。

例子：

```
void CircleItem::setRadius(qreal newRadius)
{
    if (radius != newRadius) {
        prepareGeometryChange();
        radius = newRadius;
    }
}
```

**也可以看看**[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()。

### void QGraphicsItem::removeSceneEventFilter([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **filterItem*)

从以下项目中删除该项目的事件过滤器*filterItem*。

**也可以看看**[installSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installSceneEventFilter)()。

### void QGraphicsItem::resetTransform()

将此项目的变换矩阵重置为单位矩阵或将所有变换属性重置为其默认值。这相当于调用`setTransform(QTransform())`.

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)（） 和[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::rotation() const

返回绕 Z 轴的顺时针旋转（以度为单位）。默认值为 0（即，项目不旋转）。

旋转与项目的[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（） 和[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)() 将项目的坐标系映射到父项目。

**也可以看看**[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)(),[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)（）， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::scale() const

返回项目的比例因子。默认比例因子为 1.0（即项目未缩放）。

比例尺与物品的尺寸相结合[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（） 和[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)() 将项目的坐标系映射到父项目。

**也可以看看**[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)(),[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)（）， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### [QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::scene() const

返回该项目的当前场景，或者`nullptr`如果该项目未存储在场景中。

要将项目添加或移动到场景，请调用[QGraphicsScene::addItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)()。

### [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::sceneBoundingRect() const

通过组合返回该项目在场景坐标中的边界矩形[sceneTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneTransform)（） 和[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()。

**也可以看看**[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)（） 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### `[virtual protected]`bool QGraphicsItem::sceneEvent([QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该虚拟函数接收该项目的事件。重新实现此函数以在将事件分派到专门的事件处理程序之前拦截事件[contextMenuEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contextMenuEvent)(),[focusInEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)(),[focusOutEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)(),[hoverEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverEnterEvent)(),[hoverMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverMoveEvent)(),[hoverLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverLeaveEvent)(),[keyPressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyPressEvent)(),[keyReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#keyReleaseEvent)(),[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)(),[mouseReleaseEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseReleaseEvent)(),[mouseMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseMoveEvent)（）， 和[mouseDoubleClickEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseDoubleClickEvent)()。

返回`true`事件是否被识别并处理；否则，（例如，如果事件类型未被识别）则返回 false。

*event*是被拦截的事件。

### `[virtual protected]`bool QGraphicsItem::sceneEventFilter([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **watched*, [QEvent](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

过滤项目的事件*watched*。*event*是过滤后的事件。

在子类中重新实现此函数使得该项目可以用作其他项目的事件过滤器，在这些项目能够响应之前拦截发送到这些项目的所有事件。

重新实现必须返回 true 以防止进一步处理给定事件，确保该事件不会传递到监视项，或者返回 false 以指示事件系统应进一步传播该事件。

**也可以看看**[installSceneEventFilter](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#installSceneEventFilter)()。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::scenePos() const

返回项目在场景坐标中的位置。这相当于调用`mapToScene(0, 0)`.

**也可以看看**[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)(),[sceneTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneTransform)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::sceneTransform() const

返回此项的场景变换矩阵。该矩阵可用于将坐标和几何形状从该项目的局部坐标系映射到场景的坐标系。要映射场景中的坐标，必须首先反转返回的矩阵。

例子：

```
QGraphicsRectItem rect;
rect.setPos(100, 100);

rect.sceneTransform().map(QPointF(0, 0));
// returns QPointF(100, 100);

rect.sceneTransform().inverted().map(QPointF(100, 100));
// returns QPointF(0, 0);
```

不像[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)()，仅返回项目的局部变换，该函数包括项目（和任何父项）的位置以及所有变换属性。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)(),[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)(),[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### void QGraphicsItem::scroll([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dx*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *dy*, const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF())

滚动内容*rect*经过*dx*,*dy*。如果*rect*是一个空矩形（默认），该项目的边界矩形会滚动。

当项目的内容（或项目的一部分）垂直或水平移动时，滚动提供了一种简单重画的快速替代方法。根据当前的变换和绘图设备（即视口）的功能，此操作可能只是使用 memmove() 将像素从一个位置移动到另一个位置。在大多数情况下，这比重新渲染整个区域要快。

滚动后，该项目将为新暴露的区域发布更新。如果不支持滚动（例如，您正在渲染到 OpenGL 视口，这不会从滚动优化中受益），此函数相当于调用 update(*rect*）。

**注意：**仅在以下情况下才支持滚动[QGraphicsItem::ItemCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)已启用；在所有其他情况下，调用此函数相当于调用 update(*rect*）。如果您确定该项目是不透明的并且没有与其他项目重叠，则可以映射该项目*rect*视口坐标并滚动视口。

```
QTransform xform = item->deviceTransform(view->viewportTransform());
QRect deviceRect = xform.mapRect(rect).toAlignedRect();
view->viewport()->scroll(dx, dy, deviceRect);
```

**也可以看看**[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()。

### void QGraphicsItem::setAcceptDrops(bool *on*)

如果*on*为 true 时，此项将接受拖放事件；否则，拖放事件是透明的。默认情况下，项目不接受拖放事件。

**也可以看看**[acceptDrops](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptDrops)()。

### void QGraphicsItem::setAcceptHoverEvents(bool *enabled*)

如果*enabled*为 true 时，该项目将接受悬停事件；否则，它将忽略它们。默认情况下，项目不接受悬停事件。

当当前没有鼠标抓取器项目时，将传递悬停事件。当鼠标光标进入项目、在项目内移动以及光标离开项目时发送它们。悬停事件通常用于在输入项目时突出显示项目，以及在鼠标光标悬停在项目上时跟踪鼠标光标（相当于[QWidget::mouseTracking](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mouseTracking-prop)）。

父项在其子项之前接收悬停输入事件，并在其子项之后接收离开事件。但是，如果光标进入子级，则父级不会收到悬停离开事件；父级保持“悬停”状态，直到光标离开其区域（包括其子级区域）。

如果父项处理子事件，则当光标经过其子项时，它将接收悬停移动、拖动移动和放置事件，但不会代表其接收悬停进入和悬停离开，也不会接收拖动进入和拖动离开事件孩子们。

A[QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)带有窗口装饰的窗口将接受悬停事件，无论其值如何[acceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptHoverEvents)()。

**也可以看看**[acceptHoverEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptHoverEvents)(),[hoverEnterEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverEnterEvent)(),[hoverMoveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverMoveEvent)（）， 和[hoverLeaveEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hoverLeaveEvent)()。

### void QGraphicsItem::setAcceptTouchEvents(bool *enabled*)

如果*enabled*是真的，该商品将接受[touch events](https://doc-qt-io.translate.goog/qt-6/qtouchevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp); 否则，它将忽略它们。默认情况下，项目不接受触摸事件。

**也可以看看**[acceptTouchEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptTouchEvents)()。

### void QGraphicsItem::setAcceptedMouseButtons([Qt::MouseButtons](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum) *buttons*)

设置鼠标*buttons*该项目接受鼠标事件。

默认情况下，接受所有鼠标按钮。如果某个项目接受鼠标按钮，则当为该按钮传递鼠标按下事件时，它将成为鼠标抓取器项目。但是，如果该项目不接受鼠标按钮，[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会将鼠标事件转发到其下方的第一个项目。

要禁用某个项目的鼠标事件（即使其对鼠标事件透明），请调用 setAcceptedMouseButtons([Qt::NoButton](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#MouseButton-enum)）。

**也可以看看**[acceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptedMouseButtons)（） 和[mousePressEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mousePressEvent)()。

### void QGraphicsItem::setActive(bool *active*)

如果*active*为 true，并且场景处于活动状态时，该项目的面板将被激活。否则，面板将被停用。

如果该项目不是活动场景的一部分，*active*将决定当场景变为活动状态或将项目添加到场景时面板会发生什么。如果为 true，则当将项目添加到场景或激活场景时，项目的面板将被激活。否则，该项目将保持非活动状态，与场景的激活状态无关。

**也可以看看**[isPanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isPanel)(),[QGraphicsScene::setActivePanel](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setActivePanel)（）， 和[QGraphicsScene::isActive](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isActive)()。

### void QGraphicsItem::setBoundingRegionGranularity([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *granularity*)

将边界区域粒度设置为*granularity*; 介于 0 和 1 之间的值。默认值为 0（即最低粒度，其中边界区域对应于项目的边界矩形）。

使用的粒度是[boundingRegion](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegion)() 来计算项目的边界区域应该有多细。可实现的最高粒度为 1，其中[boundingRegion](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegion)() 将返回各个设备可能的最精细轮廓（例如，对于[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)视口，这为您提供了像素完美的边界区域）。最低可能的粒度为 0。*granularity*描述设备分辨率与边界区域分辨率之间的比率（例如，值 0.25 将提供每个块对应于 4x4 设备单元/像素的区域）。

**也可以看看**[boundingRegionGranularity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRegionGranularity)()。

### void QGraphicsItem::setCacheMode([QGraphicsItem::CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum) *mode*, const [QSize](https://doc-qt-io.translate.goog/qt-6/qsize.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*logicalCacheSize* = QSize())

将项目的缓存模式设置为*mode*。

可选的*logicalCacheSize*参数仅由以下人员使用[ItemCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)模式，并描述缓存缓冲区的分辨率；如果*logicalCacheSize*是 (100, 100),[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)会将项目放入图形内存中的 100x100 像素中，无论项目本身的逻辑大小如何。默认情况下[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使用大小[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()。对于所有其他缓存模式[ItemCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum),*logicalCacheSize*被忽略。

如果您的项目花费大量时间重新绘制自身，则缓存可以加快渲染速度。在某些情况下，缓存还会减慢渲染速度，特别是当项目重绘时间少于[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)花费从缓存中重绘的时间。

启用缓存后，项目的[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)() 函数通常会绘制到离屏像素图缓存中；对于任何后续的重绘请求，图形视图框架将从缓存中重绘。这种方法特别适用于 QGLWidget，它将所有缓存存储为 OpenGL 纹理。

意识到[QPixmapCache](https://doc-qt-io.translate.goog/qt-6/qpixmapcache.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)可能需要更改缓存限制才能获得最佳性能。

您可以阅读有关不同缓存模式的更多信息[CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)文档。

**注意：**启用缓存并不意味着该项目的[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)() 函数只会在响应显式调用时被调用[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)（） 称呼。例如，在内存压力下，Qt 可能决定删除一些缓存信息；在这种情况下，一个项目的[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)即使没有，() 函数也会被调用[update](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#update)() 调用（也就是说，就像没有启用缓存一样）。

**也可以看看**[cacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cacheMode)(),[CacheMode](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)， 和[QPixmapCache::setCacheLimit](https://doc-qt-io.translate.goog/qt-6/qpixmapcache.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCacheLimit)()。

### void QGraphicsItem::setCursor(const [QCursor](https://doc-qt-io.translate.goog/qt-6/qcursor.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*cursor*)

将项目的当前光标形状设置为*cursor*。当鼠标光标位于该项目上方时，它将呈现此形状。请参阅[list of predefined cursor objects](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CursorShape-enum)以获得一系列有用的形状。

编辑器项目可能需要使用 I 型光标：

```
item->setCursor(Qt::IBeamCursor);
```

如果未设置光标，则使用下面项目的光标。

**也可以看看**[cursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursor)(),[hasCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasCursor)(),[unsetCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#unsetCursor)(),[QWidget::cursor](https://doc-qt-io.translate.goog/qt-6/qwidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#cursor-prop)， 和[QGuiApplication::overrideCursor](https://doc-qt-io.translate.goog/qt-6/qguiapplication.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#overrideCursor)()。

### void QGraphicsItem::setData(int *key*, const [QVariant](https://doc-qt-io.translate.goog/qt-6/qvariant.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*value*)

设置该项目的键的自定义数据*key*到*value*。

自定义项目数据对于存储任何项目的任意属性非常有用。Qt 不使用此功能来存储数据；它仅为了方便用户而提供。

**也可以看看**[data](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#data)()。

### void QGraphicsItem::setEnabled(bool *enabled*)

如果*enabled*为 true，该项目已启用；否则，它被禁用。

禁用的项目是可见的，但它们不会接收任何事件，并且无法获得焦点或被选择。鼠标事件被丢弃；它们不会传播，除非该项目也是不可见的，或者它不接受鼠标事件（请参阅[acceptedMouseButtons](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#acceptedMouseButtons)())。禁用的项目不能成为鼠标抓取器，因此，如果项目在抓取鼠标时变为禁用，则该项目将失去抓取，就像如果在禁用时获得焦点则该项目会失去焦点一样。

传统上，禁用的项目是使用灰色颜色绘制的（请参见[QPalette::Disabled](https://doc-qt-io.translate.goog/qt-6/qpalette.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ColorGroup-enum)）。

如果禁用父项，则其所有子项也将被禁用。如果启用父项，则所有子项都将被启用，除非它们已被显式禁用（即，如果您对子项调用 setEnabled(false) ，则如果其父项被禁用，然后再次启用，则不会重新启用它）。

默认情况下启用项目。

**注意：**如果您安装了事件过滤器，您仍然可以在事件传递到项目之前拦截它们；此机制忽略项目的启用状态。

**也可以看看**[isEnabled](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isEnabled)()。

### void QGraphicsItem::setFiltersChildEvents(bool *enabled*)

如果*enabled*为 true 时，此项设置为过滤其所有子项的所有事件（即，针对其任何子项的所有事件都将发送到此项）；否则，如果*enabled*为 false，该项目将只处理它自己的事件。默认值为 false。

**也可以看看**[filtersChildEvents](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#filtersChildEvents)()。

### void QGraphicsItem::setFlag([QGraphicsItem::GraphicsItemFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum) *flag*, bool *enabled* = true)

如果*enabled*为 true，项目标志*flag*已启用；否则，它被禁用。

**也可以看看**[flags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)（） 和[setFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlags)()。

### void QGraphicsItem::setFlags([QGraphicsItem::GraphicsItemFlags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum) *flags*)

将项目标志设置为*flags*。所有标志位于*flags*已启用；所有标志不在*flags*被禁用。

如果该项目具有焦点并且*flags*不启用[ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)，该项目因调用此函数而失去焦点。同样，如果选择了该项目，并且*flags*未启用[ItemIsSelectable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)，该项目将自动取消选择。

默认情况下，不启用任何标志。（[QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)使[ItemSendsGeometryChanges](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)默认情况下标记以跟踪位置变化。）

**也可以看看**[flags](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#flags)（） 和[setFlag](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFlag)()。

### void QGraphicsItem::setFocus([Qt::FocusReason](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#FocusReason-enum) *focusReason* = Qt::OtherFocusReason)

将键盘输入焦点赋予此项。这*focusReason*参数将被传递到任何[focus event](https://doc-qt-io.translate.goog/qt-6/qfocusevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)由该函数生成；它用于解释导致该项目获得焦点的原因。

仅启用设置的项目[ItemIsFocusable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)标志可以接受键盘焦点。

如果此项不可见、不活动或不与场景关联，则它将不会立即获得输入焦点。但是，如果稍后变得可见，它将被注册为其项目子树的首选焦点项目。

调用此函数的结果是，该项目将收到一个[focus in event](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusInEvent)和*focusReason*。如果另一个项目已经获得焦点，则该项目将首先收到[focus out event](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusOutEvent)表明它失去了输入焦点。

**也可以看看**[clearFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#clearFocus)(),[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)(),[focusItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusItem)（）， 和[focusProxy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusProxy)()。

### void QGraphicsItem::setFocusProxy([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*)

将项目的焦点代理设置为*item*。

如果某个项目具有焦点代理，则当该项目获得输入焦点时，焦点代理将接收输入焦点。该项目本身仍然具有焦点（即[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)() 将返回 true)，但只有焦点代理才会接收键盘输入。

焦点代理本身可以有一个焦点代理，等等。在这种情况下，键盘输入将由最外面的焦点代理处理。

焦点代理*item*必须与该项目属于同一场景。

**也可以看看**[focusProxy](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#focusProxy)(),[setFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setFocus)（）， 和[hasFocus](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasFocus)()。

### void QGraphicsItem::setGraphicsEffect([QGraphicsEffect](https://doc-qt-io.translate.goog/qt-6/qgraphicseffect.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **effect*)

套*effect*作为该物品的效果。如果该项目已经安装了效果，[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)将在安装新效果之前删除现有效果*effect*。您可以通过调用 setGraphicsEffect( ) 来删除现有效果`nullptr`。

如果*effect*是在不同项目上安装的效果，setGraphicsEffect() 将从该项目中删除该效果并将其安装在该项目上。

[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)取得所有权*effect*。

**注意：**此函数会将效果应用于其自身及其所有子函数。

**也可以看看**[graphicsEffect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#graphicsEffect)()。

### void QGraphicsItem::setGroup([QGraphicsItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsitemgroup.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **group*)

将此项目添加到项目组*group*。如果*group*是`nullptr`，此项将从任何当前组中删除，并添加为前一个组的父组的子项。

**也可以看看**[group](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#group)（） 和[QGraphicsScene::createItemGroup](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#createItemGroup)()。

### void QGraphicsItem::setInputMethodHints([Qt::InputMethodHints](https://doc-qt-io.translate.goog/qt-6/qt.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#InputMethodHint-enum) *hints*)

将此项的当前输入法提示设置为*hints*。

**也可以看看**[inputMethodHints](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodHints)（） 和[inputMethodQuery](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#inputMethodQuery)()。

### void QGraphicsItem::setOpacity([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *opacity*)

设置该项目的本地*opacity*，介于 0.0（透明）和 1.0（不透明）之间。该项目的局部不透明度与父级和祖先不透明度合并到[effectiveOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#effectiveOpacity)()。

默认情况下，不透明度从父级传播到子级，因此如果父级的不透明度为 0.5，子级的不透明度也为 0.5，则子级的有效不透明度将为 0.25。

不透明度属性决定了传递给画家的状态[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)（） 功能。如果该项目已缓存，即[ItemCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)或者[DeviceCoordinateCache](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#CacheMode-enum)，有效属性将在渲染时应用于项目的缓存。

有两个项目标志会影响项目的不透明度与父级的组合方式：[ItemIgnoresParentOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)和[ItemDoesntPropagateOpacityToChildren](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

**注意：**将项目的不透明度设置为 0 不会使该项目不可见（根据[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)())，但该项目将被视为不可见项目。请参阅文档[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)（） 了解更多信息。

**也可以看看**[opacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#opacity)(),[effectiveOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#effectiveOpacity)（）， 和[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。

### void QGraphicsItem::setPanelModality([QGraphicsItem::PanelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#PanelModality-enum) *panelModality*)

将此项目的模式设置为*panelModality*。

更改可见项目的形态会立即生效。

**也可以看看**[panelModality](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#panelModality)()。

### void QGraphicsItem::setParentItem([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **newParent*)

将此项目的父项目设置为*newParent*。如果该项目已有父项，则首先将其从前一个父项中删除。如果*newParent*为0时，该项目将成为顶级项目。

请注意，这会隐式将此图形项目添加到父级的场景中。你不应该[add](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#addItem)该项目请您亲自到现场。

在作为祖先的项目上调用此函数时的行为*newParent*未定义。

**也可以看看**[parentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentItem)（） 和[childItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#childItems)()。

### void QGraphicsItem::setPos(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*pos*)

将项目的位置设置为*pos*，位于父坐标中。对于没有父项的项目，*pos*位于场景坐标中。

项目的位置描述了其在父坐标中的原点（局部坐标 (0, 0)）。

**也可以看看**[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)(),[scenePos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scenePos)（）， 和[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)。

### void QGraphicsItem::setPos([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*)

这是一个过载功能。

这个便利函数相当于调用 setPos([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

### void QGraphicsItem::setRotation([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *angle*)

设置顺时针旋转*angle*，以度为单位，绕 Z 轴。默认值为 0（即，项目不旋转）。指定负值将使项目逆时针旋转。通常，旋转角度在 (-360, 360) 范围内，但也可以指定此范围之外的值（例如，370 度的旋转与 10 度的旋转相同）。

该项目围绕其变换原点旋转，默认情况下为 (0, 0)。您可以通过调用选择不同的转换原点[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)()。

旋转与项目的[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（） 和[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)() 将项目的坐标系映射到父项目。

**也可以看看**[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（）， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### void QGraphicsItem::setScale([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *factor*)

设置比例*factor*的项目。默认比例因子为 1.0（即项目未缩放）。比例因子为 0.0 会将项目折叠成一个点。如果提供负比例因子，该项目将被翻转和镜像（即旋转 180 度）。

该项目围绕其变换原点进行缩放，默认情况下为 (0, 0)。您可以通过调用选择不同的转换原点[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)()。

比例尺与物品的尺寸相结合[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)（） 和[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)() 将项目的坐标系映射到父项目。

**也可以看看**[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（）， 和[Transformations Example](https://doc-qt-io.translate.goog/qt-6/qtwidgets-painting-transformations-example.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QGraphicsItem::setSelected(bool *selected*)

如果*selected*为 true 并且此项可选，则该项被选中；否则，不选择。

如果该项目在一个组中，则整个组的选定状态将通过此功能切换。如果选择了组，则也会选择组中的所有项目，如果未选择组，则不会选择组中的任何项目。

只能选择可见的、启用的、可选择的项目。如果*selected*为 true 并且此项不可见、禁用或不可选择时，此函数不执行任何操作。

默认情况下，无法选择项目。要启用选择，请设置[ItemIsSelectable](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)旗帜。

提供此功能是为了方便，允许单独切换项目的选定状态。然而，选择项目的更常见方法是调用[QGraphicsScene::setSelectionArea](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setSelectionArea)()，它将为场景中指定区域内的所有可见、启用和可选项目调用此函数。

**也可以看看**[isSelected](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isSelected)（） 和[QGraphicsScene::selectedItems](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#selectedItems)()。

### void QGraphicsItem::setToolTip(const [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*toolTip*)

将项目的工具提示设置为*toolTip*。如果*toolTip*为空，该项目的工具提示被清除。

**也可以看看**[toolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#toolTip)（） 和[QToolTip](https://doc-qt-io.translate.goog/qt-6/qtooltip.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QGraphicsItem::setTransform(const [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*matrix*, bool *combine* = false)

将项目的当前变换矩阵设置为*matrix*。

如果*combine*是真的，那么*matrix*与当前矩阵组合；否则，*matrix* *替换*当前矩阵。*combine*默认为 false。

为了使用转换后的视图简化与项目的交互，[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)提供mapTo...和mapFrom...函数，可以在项目坐标和场景坐标之间进行转换。例如，您可以调用[mapToScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapToScene)() 将项目坐标映射到场景坐标，或者[mapFromScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#mapFromScene)() 从场景坐标映射到项目坐标。

变换矩阵与项目的组合[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)（） 和[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)() 转换为将项目的坐标系映射到其父项的组合变换。

**也可以看看**[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)(),[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)(),[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)(),[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)(),[The Graphics View Coordinate System](https://doc-qt-io.translate.goog/qt-6/graphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#the-graphics-view-coordinate-system)， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### void QGraphicsItem::setTransformOriginPoint(const [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*origin*)

设置*origin*项目坐标变换的点。

**也可以看看**[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)（） 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### void QGraphicsItem::setTransformOriginPoint([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*)

这是一个过载功能。

设置项目坐标变换的原点。这相当于调用 setTransformOriginPoint([QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*））。

**也可以看看**[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（） 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### void QGraphicsItem::setTransformations(const [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicstransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> &*transformations*)

设置图形列表*transformations*（[QGraphicsTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicstransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)）当前适用于该项目。

如果您只想旋转或缩放项目，您应该调用[setRotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setRotation)（） 或者[setScale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setScale)（） 反而。如果你想对一个项目设置任意变换，你可以调用[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)()。

[QGraphicsTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicstransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于应用和控制项目上的一系列单独转换操作。它在动画中特别有用，其中每个变换操作都需要独立或不同地进行插值。

变换与项目的组合[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)（） 和[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)() 将项目的坐标系映射到父项目。

**也可以看看**[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（）， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### void QGraphicsItem::setVisible(bool *visible*)

如果*visible*为 true，则该项目可见。否则，该项目将变得不可见。隐形物品不会被绘制，也不会接收任何事件。特别是，鼠标事件直接穿过不可见的项目，并传递到可能位于后面的任何项目。不可见项目也是不可选择的，它们无法获取输入焦点，并且不会被[QGraphicsScene](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)的物品定位功能。

如果一个项目在抓取鼠标时变得不可见（即，当它正在接收鼠标事件时），它将自动失去鼠标抓取，并且不会通过使该项目再次可见来重新获得抓取；它必须接受新的鼠标按下才能重新获得鼠标抓取权。

同样，不可见的项目无法获得焦点，因此如果该项目在变得不可见时具有焦点，它将失去焦点，并且仅通过使该项目再次可见而无法重新获得焦点。

如果隐藏父项，则其所有子项也将被隐藏。如果显示父项，则所有子项都会显示，除非它们已被显式隐藏（即，如果您对子项调用 setVisible(false)，即使其父项被隐藏然后再次显示，也不会重新显示） 。

默认情况下，项目是可见的；没有必要对新项目调用 setVisible()。

**注意：**不透明度设置为 0 的项目仍将被视为可见，尽管它将被视为不可见项目：鼠标事件将穿过它，它不会包含在由[QGraphicsView::items](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（）， 等等。但是，该项目将保留焦点。

**也可以看看**[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)(),[show](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#show)(),[hide](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)（）， 和[setOpacity](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setOpacity)()。

### void QGraphicsItem::setX([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*)

设置的是*x*项目位置的坐标。相当于调用[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)（X，[y](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#y)())。

**也可以看看**[x](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#x)（） 和[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)()。

### void QGraphicsItem::setY([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*)

设置的是*y*项目位置的坐标。相当于调用[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)（[x](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#x)()，y)。

**也可以看看**[y](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#y)(),[x](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#x)（）， 和[setPos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setPos)()。

### void QGraphicsItem::setZValue([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *z*)

将项目的 Z 值设置为*z*。Z 值决定同级（相邻）项目的堆叠顺序。高 Z 值的同级项目将始终绘制在另一个具有较低 Z 值的同级项目之上。

如果恢复 Z 值，则项目的插入顺序将决定其堆叠顺序。

Z 值不会以任何方式影响项目的大小。

默认 Z 值为 0。

**也可以看看**[zValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#zValue)(),[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting),[stackBefore](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stackBefore)（）， 和[ItemStacksBehindParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

### `[virtual]`[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::shape() const

返回该项目的形状为[QPainterPath](https://doc-qt-io.translate.goog/qt-6/qpainterpath.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)在当地坐标中。该形状有很多用途，包括碰撞检测、命中测试以及[QGraphicsScene::items](https://doc-qt-io.translate.goog/qt-6/qgraphicsscene.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#items)（） 功能。

默认实现调用[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)() 返回一个简单的矩形形状，但子类可以重新实现此函数以返回非矩形项目的更准确的形状。例如，圆形项目可以选择返回椭圆形以更好地进行碰撞检测。例如：

```
QPainterPath RoundItem::shape() const
{
    QPainterPath path;
    path.addEllipse(boundingRect());
    return path;
}
```

形状的轮廓可能会根据绘图时使用的笔的宽度和风格而变化。如果您想将此轮廓包含在项目的形状中，您可以使用以下命令从笔画创建形状[QPainterPathStroker](https://doc-qt-io.translate.goog/qt-6/qpainterpathstroker.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

该函数由默认实现调用[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)（） 和[collidesWithPath](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#collidesWithPath)()。

**也可以看看**[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)(),[contains](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#contains)(),[prepareGeometryChange](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#prepareGeometryChange)（）， 和[QPainterPathStroker](https://doc-qt-io.translate.goog/qt-6/qpainterpathstroker.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### void QGraphicsItem::show()

显示项目（默认情况下项目可见）。

这个便利功能相当于调用`setVisible(true)`.

**也可以看看**[hide](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hide)（） 和[setVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setVisible)()。

### void QGraphicsItem::stackBefore(const [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **sibling*)

之前堆叠此项目*sibling*，它必须是同级项（即，两个项必须共享相同的父项，或者必须都是顶级项）。这*sibling*必须与该项目具有相同的Z值，否则调用该函数将不起作用。

默认情况下，所有同级项目均按插入顺序堆叠（即，添加的第一个项目在添加的下一个项目之前绘制）。如果两个项目的 Z 值不同，则 Z 值最高的项目将绘制在顶部。当Z值相同时，插入顺序将决定堆叠顺序。

**也可以看看**[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)(),[ItemStacksBehindParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)， 和[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting)。

### [QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::toGraphicsObject()

将图形项目返回到[QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，如果该类实际上是图形对象，否则为 0。

### const [QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::toGraphicsObject() const

将图形项目返回到[QGraphicsObject](https://doc-qt-io.translate.goog/qt-6/qgraphicsobject.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)，如果该类实际上是图形对象，否则为 0。

### [QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::toolTip() const

返回项目的工具提示，或空的[QString](https://doc-qt-io.translate.goog/qt-6/qstring.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)如果没有设置工具提示。

**也可以看看**[setToolTip](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setToolTip)（） 和[QToolTip](https://doc-qt-io.translate.goog/qt-6/qtooltip.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### [QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) *QGraphicsItem::topLevelItem() const

返回该项目的顶级项目。顶级项目是该项目的最顶层祖先项目，其父项是`nullptr`。如果一个项目没有父项，则返回其自己的指针（即，顶级项目是其自己的顶级项目）。

**也可以看看**[parentItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#parentItem)()。

### [QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::topLevelWidget() const

返回指向该项目的顶级小部件的指针（即，该项目的祖先，其父级是`nullptr`，或其父级不是小部件），或者`nullptr`如果该项目没有顶级小部件。如果该项目是其自己的顶级小部件，则此函数返回指向该项目本身的指针。

### [QTransform](https://doc-qt-io.translate.goog/qt-6/qtransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::transform() const

返回此项的变换矩阵。

变换矩阵与项目的组合[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)（） 和[transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)() 转换为项目的组合变换。

默认变换矩阵是单位矩阵。

**也可以看看**[setTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransform)（） 和[sceneTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneTransform)()。

### [QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) QGraphicsItem::transformOriginPoint() const

返回项目坐标变换的原点。

默认为[QPointF](https://doc-qt-io.translate.goog/qt-6/qpointf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)(0,0)。

**也可以看看**[setTransformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformOriginPoint)（） 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### [QList](https://doc-qt-io.translate.goog/qt-6/qlist.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)<[QGraphicsTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicstransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *> QGraphicsItem::transformations() const

返回当前应用于此项的图形变换列表。

[QGraphicsTransform](https://doc-qt-io.translate.goog/qt-6/qgraphicstransform.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)用于应用和控制项目上的一系列单独转换操作。它在动画中特别有用，其中每个变换操作都需要独立或不同地进行插值。

变换与项目的组合[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)（） 和[transform](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transform)() 将项目的坐标系映射到父项目。

**也可以看看**[setTransformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setTransformations)(),[scale](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#scale)(),[rotation](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#rotation)(),[transformOriginPoint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformOriginPoint)（）， 和[Transformations](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#transformations)。

### `[virtual]`int QGraphicsItem::type() const

以 int 形式返回项目的类型。所有标准图形项目类都与唯一值相关联；看[QGraphicsItem::Type](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anonymous-enum)。该类型信息用于[qgraphicsitem_cast](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qgraphicsitem_cast)() 来区分类型。

默认实现（在[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)) 返回[UserType](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anonymous-enum)。

为了能够使用[qgraphicsitem_cast](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qgraphicsitem_cast)() 与自定义项，重新实现此函数并声明一个等于自定义项类型的 Type 枚举值。自定义项目返回的值必须大于或等于[UserType](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anonymous-enum)（65536）。

例如：

```
class CustomItem : public QGraphicsItem
{
public:
   enum { Type = UserType + 1 };

   int type() const override
   {
       // Enable the use of qgraphicsitem_cast with this item.
       return Type;
   }
   ...
};
```

**也可以看看**[UserType](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anonymous-enum)。

### void QGraphicsItem::ungrabKeyboard()

释放键盘抓取。

**也可以看看**[grabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabKeyboard)（） 和[ungrabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabMouse)()。

### void QGraphicsItem::ungrabMouse()

释放鼠标抓取。

**也可以看看**[grabMouse](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#grabMouse)（） 和[ungrabKeyboard](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ungrabKeyboard)()。

### void QGraphicsItem::unsetCursor()

从该项目清除光标。

**也可以看看**[hasCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#hasCursor)（） 和[setCursor](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setCursor)()。

### void QGraphicsItem::update(const [QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) &*rect* = QRectF())

安排重绘所覆盖的区域*rect*在这个项目中。每当您的项目需要重新绘制（例如更改外观或大小）时，您都可以调用此函数。

该函数不会立即绘制；相反，它会安排一个绘制请求，该请求由[QGraphicsView](https://doc-qt-io.translate.goog/qt-6/qgraphicsview.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)控制到达事件循环后。仅当该项目在任何关联视图中可见时才会重新绘制。

作为重新绘制项目的副作用，与该区域重叠的其他项目*rect*也可以重新喷漆。

如果该项目不可见（即[isVisible](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isVisible)() 返回`false`)，该函数不执行任何操作。

**也可以看看**[paint](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#paint)（） 和[boundingRect](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#boundingRect)()。

### void QGraphicsItem::update([qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *x*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *y*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *width*, [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) *height*)

这是一个过载功能。

这个便利函数相当于调用 update([QRectF](https://doc-qt-io.translate.goog/qt-6/qrectf.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)（*x*,*y*,*width*,*height*））。

### `[protected]`void QGraphicsItem::updateMicroFocus()

更新项目的微焦点。

**也可以看看**[QInputMethod](https://doc-qt-io.translate.goog/qt-6/qinputmethod.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)。

### `[virtual protected]`void QGraphicsItem::wheelEvent([QGraphicsSceneWheelEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsscenewheelevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) **event*)

该事件处理程序，用于事件*event*，可以重新实现以接收该项目的滚轮事件。如果你重新实现这个函数，*event*将默认接受。

如果您忽略该事件（即通过调用[QEvent::ignore](https://doc-qt-io.translate.goog/qt-6/qevent.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#ignore)(),) 它将传播到该项目下的任何项目。如果没有项目接受该事件，则该事件将被场景忽略，并传播到视图（例如，视图的垂直滚动条）。

默认实现会忽略该事件。

**也可以看看**[sceneEvent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sceneEvent)()。

### [QGraphicsWidget](https://doc-qt-io.translate.goog/qt-6/qgraphicswidget.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp) *QGraphicsItem::window() const

返回该项目的窗口，或者`nullptr`如果该项目没有窗口。如果该项目是一个窗口，它将返回自身。否则它将返回最接近的祖先，即窗口。

**也可以看看**[QGraphicsWidget::isWindow](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#isWindow)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::x() const

这个便利函数相当于调用[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)（）。X（）。

**也可以看看**[setX](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setX)（） 和[y](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#y)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::y() const

这个便利函数相当于调用[pos](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#pos)().y()。

**也可以看看**[setY](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setY)（） 和[x](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#x)()。

### [qreal](https://doc-qt-io.translate.goog/qt-6/qttypes.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#qreal-typedef) QGraphicsItem::zValue() const

返回项目的 Z 值。Z 值影响同级（相邻）项目的堆叠顺序。

默认 Z 值为 0。

**也可以看看**[setZValue](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#setZValue)(),[Sorting](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#sorting),[stackBefore](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#stackBefore)（）， 和[ItemStacksBehindParent](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#GraphicsItemFlag-enum)。

## 相关非会员

### template < typename T > T qgraphicsitem_cast([QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#QGraphicsItem) **item*)

返回给定的*item*强制转换为 T 类型，如果*item*属于 T 型；否则，`nullptr`返回。

**注意：**要使此功能与自定义项目正常工作，请重新实现[type](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)每个自定义的 () 函数[QGraphicsItem](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp)子类。

**也可以看看**[QGraphicsItem::type](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#type)（） 和[QGraphicsItem::UserType](https://doc-qt-io.translate.goog/qt-6/qgraphicsitem.html?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=zh-CN&_x_tr_pto=wapp#anonymous-enum)。