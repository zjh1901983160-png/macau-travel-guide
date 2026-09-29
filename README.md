# 澳门旅游攻略

学生课程作业演示页面（手机版 / 电脑版），单文件 HTML + 原生 CSS/JS，不需要构建工具。

在线地址：<https://zjh1901983160-png.github.io/macau-travel-guide/>

## 文件

| 文件 | 说明 |
|---|---|
| `index.html` | 入口页，选手机版或电脑版 |
| `desktop.html` | 电脑版：两栏首屏、三列景点、左列表右地图、区域弹窗 |
| `mobile.html` | 手机版：底部标签栏、滑动手势轮播、折叠面板 |
| `macau-images/` | 页面用到的实景照片与地图，`图片来源.md` 里是作者与许可证 |

## 地图

两种模式用的是同一套底图和配色：

- 联网时用 MapLibre + OpenFreeMap 渲染可缩放、可拖动的实景地图，并显示三个区域标记；
- 没有网络或地图库加载失败时，自动退回 `macau-images/13-map-macau.png`（用同一套底图导出的静态截图），电脑版上的三个热点仍然可以点击。

地图数据 © OpenStreetMap 贡献者，瓦片由 OpenFreeMap 提供（ODbL 1.0）。
MapLibre GL JS 通过 unpkg CDN 加载，采用 BSD-3-Clause 许可。

## 照片授权

照片全部来自 Wikimedia Commons，按各自的开放许可证使用（CC BY / CC BY-SA / 公有领域 / CC0）。
逐张的作者、许可证与来源链接见 [`macau-images/图片来源.md`](macau-images/图片来源.md)。
CC BY、CC BY-SA 类照片在转载或再发布时需要保留作者署名与许可证信息。

## 说明

页面里提到的出行信息（票价、班次、签证规则等）只作课程演示用途，实际情况请以官方最新公布为准。
