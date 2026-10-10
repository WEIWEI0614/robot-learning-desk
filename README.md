# 机器人学习台 · robot-learning-desk

一个面向**机器人 / 数学 / AI** 的中文学习资料库。21 个面板，纯静态 HTML，全部可离线打开。

内容分三层：**知识层**（补懂）→ **实践层**（做出来）→ **规划层**（排顺序）。

---

## 怎么用

克隆后直接双击 `index.html` 即可，无需构建、无需服务器、无需联网（课件内已内嵌 KaTeX，公式可离线渲染）。

```bash
git clone https://github.com/WEIWEI0614/robot-learning-desk.git
cd robot-learning-desk
open index.html
```

也可以用任意静态服务器托管：

```bash
python3 -m http.server 8000   # 然后访问 http://localhost:8000
```

---

## 目录结构

```
index.html                 主入口
assets/                    样式与内嵌 KaTeX
pages/
  ├─ 知识层
  │   map.html             知识地图：21 篇 · 5 条演进链 + 阅读顺序
  │   rl4.html             RL 基础四篇：TRPO / A3C / DDPG / MPC
  │   robotmath.html       数学缺口：五个记号缺口与文献导航
  │   mathmap.html         数学脉络：三套体系的规模与关系
  │   terms.html           术语手册：37 条术语 + 三条动手路径
  │   papers.html          论文库：21 篇 · 两条线
  │   papermap.html        论文地图：五条演进链 + 阅读顺序
  │   lect.html            讲解版：逐篇讲透
  ├─ 实践层
  │   exercises.html       课后习题：原书习题 + 分步解答
  │   lessons.html         AI 课件：互动课堂
  │   hw.html              造机器人：SO-101 选型 + BOM + 排错
  │   sim.html             仿真训练：算力实测 + 安全边界
  │   p2a.html             论文转 Agent
  │   code.html            代码详解：PPO / server.py 逐行对照
  └─ 规划层
      timeline.html        时间线
      daily.html           逐日执行计划
      drive.html           30 天游戏化学习
      links.html           资源清单
      jev.html             Jev 决策模型
课件/                      互动课件（*.html + *.classroom.json 源数据）
习题/                      按教材分章的课后习题
强化学习讲解.html           强化学习讲解版阅读器（单文件）
robotmath/cn/              机器人数学中文导读
```

---

## 内容说明

- **原创部分**（笔记、讲解、习题解答、课件）以 MIT 协议开源，见 `LICENSE`。
- **第三方论文与教材不随本仓库分发。** 原站曾收录的论文 PDF、教材 PDF 与论文全文中文翻译，因版权原因已全部移除；相关条目的链接全部替换为可核验的公开地址（arXiv、DOI、或作者授权的免费版本）。少数未检索到公开原文的条目已显式标注为「无公开原文」，不做链接猜测。
- 引用具体数值前请回查原文。课件与笔记中的数字均标注了来源（页码 / 章节号 / 表号），凡原文未给出的数字会显式说明，不做推测。

---

## 贡献

欢迎提 issue 指出错误（尤其是数字、公式、文献出处），也欢迎 PR 补充遗漏的公开原文链接。
