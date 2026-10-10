# 制造系统建模与仿真 · 交互实验室

课程学习过程中制作的交互演示与配套文字材料。所有演示均为静态 HTML，可直接下载并用浏览器打开；不需要安装依赖或运行服务。

## 在线入口

仓库开启 GitHub Pages 后，可访问：<https://ggpggpggggggp.github.io/manufacturing-simulation-lab/>。

在本地使用时，打开仓库根目录的 [`index.html`](index.html) 即可浏览所有成果。基础版蒙特卡洛演示使用 Tailwind CDN 样式，离线打开时需要联网才能完整显示样式；其余演示的页面资源内嵌在 HTML 中。

## 内容目录

| 主题 | 交互演示 | 配套材料 |
| --- | --- | --- |
| 蒙特卡洛方法估算 π | [升级版](<demos/00. 蒙特卡洛 π 估算实验室（升级版）.html>) · [基础版](<demos/蒙特卡洛 π 估算实验室（基础版）.html>) | — |
| 线性同余法 LCG | [交互演示 V3](<demos/06. 线性同余法（LCG：Linear Congruential Generator）V3.html>) | [预览图](assets/lcg-v3-preview.png) |
| 离散型随机变量统计指标 | [教学演示](<demos/离散型随机变量统计指标教学演示.html>) | [讨论题 23 题参考答案](docs/讨论题23题参考答案.md) |
| 单服务台排队系统 | [例 3.3 仿真演示 V3](<demos/例3.3 单服务台排队系统仿真演示 V3.html>) | [实验报告示例](docs/例3.3-教材模式实验报告示例.md) · [预览图](assets/queue-v3-preview.png) |

## 仓库结构

```text
index.html   导航首页
demos/       五个交互演示
docs/        讨论题答案与实验报告示例
assets/      演示预览图
```

这些内容用于课程学习与教学展示。实验报告示例对应文中给出的输入数据和模型约定；修改参数后应以演示重新生成的结果为准。
