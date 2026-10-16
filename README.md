# 具身智能中文资源库

**在线直接看 → https://weiwei0614.github.io/robot-learning-desk/**

不用 clone、不用配置，点开即用。全部内容离线可用，无 CDN 依赖。

面向中文读者的**具身智能 / 机器人学习**资料库：从机器人学基础与数学准备，到强化学习、VLA、扩散策略、世界模型、仿真与实机——按「补懂 → 做出来 → 排顺序」三层组织。

| 规模 | |
|---|---|
| 面板 | 21 个 |
| 互动课件 | 18 个自包含 HTML |
| 论文 | 21 篇 · 5 条演进链 |
| 术语 | 37 条 |
| 课后习题 | 46 份（附分步解答） |
| 原创内容许可 | MIT |

---

## 为什么值得看

- **不是链接堆砌。** 论文与教材不随仓库分发，取而代之的是逐篇写透的笔记、课件与习题解答；引用数值均标注来源（页码 / 章节号 / 表号），原文没给的就显式说明，不做推测。
- **不是零散笔记。** 21 篇论文被整理成 5 条演进链并给出阅读顺序，知识地图回答"先看什么、为什么"。
- **能动手。** 含 SO-101 造机器人选型与 BOM、仿真训练算力实测与安全边界、PPO 代码逐行对照。
- **完全离线。** 无构建步骤、无第三方 CDN、无框架。KaTeX 已内嵌，断网也能渲染公式。十年后打开还是这样。

---

## 内容地图

### 知识层 · 把不懂的地方补成懂的

| 面板 | 内容 |
|---|---|
| [知识地图](https://weiwei0614.github.io/robot-learning-desk/pages/map.html) | 21 篇 · 5 条演进链 + 阅读顺序 |
| [RL 基础四篇](https://weiwei0614.github.io/robot-learning-desk/pages/rl4.html) | TRPO / A3C / DDPG / MPC 原文 + 课件 |
| [数学缺口](https://weiwei0614.github.io/robot-learning-desk/pages/robotmath.html) | 李群、旋量、互补约束 —— 五个记号缺口 |
| [数学脉络](https://weiwei0614.github.io/robot-learning-desk/pages/mathmap.html) | 三套体系的规模与关系 |
| [术语手册](https://weiwei0614.github.io/robot-learning-desk/pages/terms.html) | 37 条术语 + 三条动手路径 |
| [论文库](https://weiwei0614.github.io/robot-learning-desk/pages/papers.html) | 21 篇 · 两条线 · 附公开原文链接 |
| [论文地图](https://weiwei0614.github.io/robot-learning-desk/pages/papermap.html) | 五条演进链 + 阅读顺序 |
| [讲解版](https://weiwei0614.github.io/robot-learning-desk/pages/lect.html) | TRPO / RT-2 / OpenVLA 等逐篇讲透 |

### 实践层 · 从懂了到做出来

| 面板 | 内容 |
|---|---|
| [课后习题](https://weiwei0614.github.io/robot-learning-desk/pages/exercises.html) | 原书习题 + 分步解答 |
| [AI 课件](https://weiwei0614.github.io/robot-learning-desk/pages/lessons.html) | 互动课堂，离线 HTML |
| [造机器人](https://weiwei0614.github.io/robot-learning-desk/pages/hw.html) | SO-101 选型 + BOM + 排错 |
| [仿真训练](https://weiwei0614.github.io/robot-learning-desk/pages/sim.html) | 算力实测 + 安全边界 |
| [论文转 Agent](https://weiwei0614.github.io/robot-learning-desk/pages/p2a.html) | 从论文到可调用的 agent |
| [代码详解](https://weiwei0614.github.io/robot-learning-desk/pages/code.html) | PPO / server.py 逐行对照 |

### 规划层 · 决定什么时候做什么

| 面板 | 内容 |
|---|---|
| [时间线](https://weiwei0614.github.io/robot-learning-desk/pages/timeline.html) | 机械自动偶戏机 → VLA 双系统 |
| [逐日执行](https://weiwei0614.github.io/robot-learning-desk/pages/daily.html) | 6 周 + 13 周逐日计划 |
| [每日驱动](https://weiwei0614.github.io/robot-learning-desk/pages/drive.html) | 30 天游戏化学习 |
| [资源清单](https://weiwei0614.github.io/robot-learning-desk/pages/links.html) | 官方仓库 + 课程 + 数据集直链 |
| [Jev 决策模型](https://weiwei0614.github.io/robot-learning-desk/pages/jev.html) | 该不该自建 + 什么规模自建 |

### 独立阅读器

- [强化学习讲解版阅读器](https://weiwei0614.github.io/robot-learning-desk/强化学习讲解.html)
- [机器人数学 · 中文导读](https://weiwei0614.github.io/robot-learning-desk/robotmath/cn/08-中文导读与阅读路径.html)

---

## 互动课件

18 个自包含 HTML 课件，双击即开，断网可用。每个课件都附带 `.classroom.json` 源数据。

**前沿簇复盘（9 个）**

| 课件 | 主题 |
|---|---|
| `vla-generalist` | VLA 通用策略 |
| `vla-evolution` | VLA 演进路径 |
| `diffusion-policy` | 扩散策略 |
| `world-model-advanced` | 世界模型进阶 |
| `sim-and-sim2real` | 仿真与 sim2real |
| `rl-foundation` | 强化学习基础 |
| `rl-algorithms-advanced` | 强化学习进阶算法 |
| `control-hardware` | 控制与硬件 |
| `gpu-sim-scaleup` | 算力与仿真扩展 |

**教材精读（7 个）**

| 课件 | 来源 |
|---|---|
| `MR精读-第3-4-6-8-9章` | *Modern Robotics* |
| `corke精读-第2/7/11章` | Corke《Robotics, Vision and Control》 |
| `boyd精读-第1章` | Boyd《凸优化》 |
| `mls94精读-第3/8章` | MLS94 机器人学 |

**专题（2 个）**

- `RL基础四部曲-TRPO-A3C-DDPG-LMPC`
- `演示-TRPO信赖域KL约束交互演示`

---

## 本地使用

在线版够用了。如果你要离线或二次加工：

```bash
git clone https://github.com/WEIWEI0614/robot-learning-desk.git
cd robot-learning-desk
open index.html
```

无需构建、无需服务器、无需联网。也可以用任意静态服务器托管：

```bash
python3 -m http.server 8000   # 然后访问 http://localhost:8000
```

### 目录结构

```
index.html              主入口（三层导航）
assets/                 样式与内嵌 KaTeX
pages/                  21 个面板
课件/                    18 个互动课件（*.html + *.classroom.json 源数据）
习题/                    按教材分章的课后习题
robotmath/cn/           机器人数学中文导读
强化学习讲解.html         强化学习讲解版阅读器（单文件）
```

---

## 内容边界

- **原创部分**（笔记、讲解、习题解答、课件）以 MIT 协议开源，见 `LICENSE`。
- **第三方论文与教材不随本仓库分发。** 原站曾收录的论文 PDF、教材 PDF 与全文翻译，因版权原因已全部移除；相关条目的链接全部替换为可核验的公开地址（arXiv、DOI、作者授权版本）。少数未检索到公开原文的条目已显式标注为「无公开原文」，不做链接猜测。
- 引用具体数值前请回查原文。凡原文未给出的数字会显式说明，不做推测。

## 贡献

欢迎提 issue 指出错误（尤其是数字、公式、文献出处），也欢迎 PR 补充遗漏的公开原文链接。详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 许可证

原创内容采用 **MIT License**（见 [LICENSE](LICENSE)）。

---

<sub>如果这份资料对你有帮助，点个 Star 是最好的支持。</sub>
