hero:
  name: 数字孪生场景编辑器
  text: 一套把「3D 场景」当文档来编辑、存储、导出、播放的开源工具链
  tagline: Vue3 + Babylon.js 驱动的可视化场景编辑器，配套零依赖播放包，任意页面一行代码跑起来
  actions:
    - theme: brand
      text: 快速开始
      link: /quickstart
    - theme: alt
      text: 架构总览
      link: /architecture

features:
  - icon: 🎛️
    title: 拖参数拼场景
    details: 像搭积木一样摆元素、配参数、绑交互与实时数据，场景一键存 IndexedDB，随时导出。
  - icon: 📄
    title: 场景即文档
    details: 把「3D 场景」当作文档来编辑、存储、导出、播放，一份 scene.json 贯穿全链路。
  - icon: ▶️
    title: 一行代码播放
    details: 任意页面一行代码跑起来，支持 npm / Vue 组件 / script 标签多种接入方式。
  - icon: 🔗
    title: 实时数据绑定
    details: 点击 / 悬停让模型透明、发光、飞镜头，让场景随实时数据变化。

---

## 文档地图

| 想了解什么 | 看这里 |
| --- | --- |
| 这套东西是什么、两个工程怎么分工 | [架构总览](architecture.md) |
| 5 分钟跑通「编辑 → 导出 → 播放」 | [快速开始](quickstart.md) |
| 编辑器里每个功能怎么用 | [编辑器 · 能力地图](editor/README.md) → [功能详解](editor/features.md) |
| 点击 / 悬停让模型透明、发光、飞镜头 | [节点交互](editor/interactions.md) |
| 让场景随实时数据变化 | [数据绑定手册](binding-manual.md)（最详细的一份） |
| 在别人的项目里加载场景 | [播放包 · 接入选型](player/README.md) → [接入详解](player/integration.md) |
| API 参考 | [播放包 API](player/api.md) |
| scene.json 每个字段 | [场景文档协议](protocol.md) |
| 踩坑了 | [FAQ](faq.md) |
