## 1.3.1 (计划)

* 修复 ``echarts-gl`` 兼容问题。

## 1.3.0 (2017.12.02)

* 图层初始化：可以在任意时间初始化echarts图层，不需要再手动监听地图是否渲染后在初始化，适应更多场景。
* 添加到地图：不需要再初始化时传入地图对象，可以在地图初始化后再 ``appendTo`` 到地图, 并且
  渲染是在添加到地图后且存在echarts图层配置才会渲染，减少内存开销。
* 优化了echarts配置，不需要再强制传入 coordinateSystem 字段。
* 新增了四个参数，详见 ``api``, 可增强用户体验，减少卡顿。

## 1.2.0 (2017.11.22)

* 修复相关bug，优化相关代码。
* 添加api文档，升级npm包版本。
* 添加 EPSG4326 投影示例。

## 1.1.0 (2017.07.26)

* 重构相关方法，webpack打包构建。
* 更新LICENSE，去除ol依赖。
* 添加相关示例。

## 1.0.0 (2017.02.01)

* 实现基础功能