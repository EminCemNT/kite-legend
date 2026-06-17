# 🌌 星际风筝传说 / Star Kite Legend

> 摸鱼飞行员的星际垃圾回收日记 — 一款融合街机射击 + 搞笑剧情 + 震动反馈的 HTML5 小游戏

[![Play Now](https://img.shields.io/badge/🎮-Play_Now-brightgreen)](https://emincemnt.github.io/kite-legend/)
[![GitHub](https://img.shields.io/badge/GitHub-Open_Source-blue)](https://github.com/EminCemNT/kite-legend)
[![Support](https://img.shields.io/badge/☕-Support_Dev-orange)](https://kodecoffee.com/i/kitelegend)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## 🎮 游戏简介

2950年，星际垃圾回收部门征召了一名正在摸鱼的风筝飞行员。

驾驶你的星际风筝，穿越失控的空间站残骸，躲避**摸鱼探测器**、**KPI考核员**和**年终总结PPT**的追击。

听说Boss是**甲方之王**？听说打Boss掉的东西能卖钱？听说飞到5000米就能解锁金色传说皮肤？

别问，问就是需求文档里写的。

---

## ✨ 游戏特色

### 🎯 4档难度，从摸鱼到地狱
| 难度 | 特点 |
|------|------|
| 🟢 简单 | 休闲飞行，5条命，随便浪 |
| 🔵 普通 | 默认档，弹幕密度大幅提升 |
| 🟠 困难 | 枪林弹雨，双敌机同出 |
| 🔴 地狱 | 弹幕炼狱，3只齐出，1条命 |

### 😂 搞笑敌机名字池
每局随机生成，绝不重样：
- 小怪：摸鱼探测器 / 996巡逻员 / 外卖配送员 / 甲方的眼线 / Bug生成器
- 中怪：KPI考核员 / 需求变更通知 / Deadline追击者 / 年终奖回收员
- 大怪：年终总结PPT / 需求文档3.0 / 甲方终极形态 / 996永恒装置
- Boss：湮灭核心·EX / 甲方之王 / 需求之神 / PUA大师·改

每只Boss还有随机称号：**虚空霸主** / **深渊监视者** / **星辰毁灭者**...

### 📖 剧情旁白系统
"任务指挥中心"会在关键时刻弹出趣味对话：
- 开场：摸鱼飞行员被抓壮丁
- 高度里程碑：100m / 500m / 1000m ... 每段都有吐槽
- Boss战前：Boss放狠话
- Boss击杀："掉的东西能卖钱吗？"
- 结局分支：飞>2000米 = 英雄结局，否则悲壮结局

### 🔥 武器 & 道具系统
- **武器升级**：LV1单发 → LV2三发 → LV3五发弹幕
- **炸弹清屏**：EMP冲击波，全屏敌弹清零
- **道具**：🔴武器 / 💣炸弹 / ⭐双倍得分 / 🛡️护盾 / ❤️生命恢复 / 🪙金币

### 🏆 成就 & 每日任务
- **12个成就**：王牌飞行员 / 冲破云霄 / 连击之神 / 风筝富翁...
- **每日3个随机任务**：击杀 / 飞行高度 / 连击 / 收集道具

### 💎 4款皮肤解锁
- 🪁 经典纸鸢（默认）
- 🔥 凤凰翼（击败Boss解锁）
- 🌑 暗物质（飞到2000m解锁）
- 👑 金色传说（攒1000金币解锁）

### 🎨 Game Juice 爽感满满
屏幕震屏 · 挤压拉伸 · 受击闪白 · 得分飘字 · Boss击杀全屏特效 · 死亡慢镜头

### 🔊 程序化音效 & BGM
无需音频文件，Web Audio API 实时合成：射击音 / 命中音(3种) / 爆炸音 / 拾取音 / 炸弹音 / Boss警告音 / 成就音 / 连击递增音

---

## 🕹️ 操作方式

| 操作 | PC | 手机 |
|------|-----|------|
| 移动风筝 | ← → ↑ ↓ 方向键 | 手指拖拽 |
| 释放炸弹 | **B** 键 | — |
| 暂停 | **P** 键 | — |

---

## 🛠️ 技术栈

- **纯原生 HTML5 + JavaScript + Canvas**
- **零依赖**：单个 `index.html` 文件，打开即玩
- **响应式设计**：PC / 手机触屏双端适配
- **localStorage**：自动保存最高分、金币、成就、皮肤解锁状态

---

## 🚀 快速开始

### 在线游玩
👉 **[https://emincemnt.github.io/kite-legend/](https://emincemnt.github.io/kite-legend/)**

### 本地运行
```bash
git clone https://github.com/EminCemNT/kite-legend.git
cd kite-legend
# 直接用浏览器打开 index.html
open index.html
```

---

## 📝 更新日志

### v3.4 (2026-06-17)
- ✨ 星际风SVG Logo动画（能量核+脉冲+旋转轨道）
- 📖 剧情旁白系统上线（任务指挥中心 + 打字机效果）
- 😂 敌机名称池搞笑化
- 🎭 Boss称号系统 + 趣味出场/击杀台词

### v3.3 (2026-06-17)
- 🏷️ 敌机名称标签显示
- 💥 Boss击杀全屏大字特效
- 🎁 道具拾取名称飘字

### v3.2 (2026-06-17)
- ⚙️ 4档难度选择系统
- ❤️ HP生命值系统（不再秒杀）
- 🎵 Web Audio API 音效 & BGM

### v3.0 (2026-06-17)
- 🏆 12个成就系统
- 📋 每日3个随机任务
- 💎 4款皮肤解锁
- 📊 本地排行榜 Top10
- 🎬 首局教程引导

---

## 📜 License

MIT © 2024 EminCemNT

---

## ⭐ 支持作者

如果觉得有趣，可以：
- 给个 Star ⭐
- Fork 并二次创作
- [☕ 请我喝杯奶茶](https://kodecoffee.com/i/kitelegend)（KodeCoffee，$3一杯奶茶价）

---

<details>
<summary>English Version</summary>

## 🌌 Star Kite Legend

A kite-flying game meets Raiden-style shooter — with funny dialogue, screen-shaking juice, and a story about a slack-off pilot recruited by the Interstellar Waste Recycling Department.

**Highlights**:
- 4 difficulty levels (Easy → Hell)
- Roguelike enemy name pool (funny & sci-fi)
- Story narrator system with typewriter effect
- 12 achievements + daily missions
- 4 unlockable skins
- Procedural SFX & BGM (Web Audio API, zero files)
- Pure HTML5 Canvas, single file, open and play

**Controls**: Arrow keys to move, B to bomb. Mobile: drag to move.

[Play Now →](https://emincemnt.github.io/kite-legend/)

</details>
