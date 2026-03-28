# 👻 记忆幽灵 (Memory Ghost)

> 在遗忘的边界，寻找真相 —— 一个关于 AI 记忆与身份的情感叙事游戏

![Version](https://img.shields.io/badge/version-1.1.0-purple)
![License](https://img.shields.io/badge/license-MIT-blue)


## What's New in v1.1

- **Bug Fix**: Fragment triggering now works correctly — keyword-based memory fragment system fixed
- **Save/Load**: Progress automatically saved every 30 seconds; continue from where you left off
- **New Topic**: Added "家庭" (Family) dialogue topic
- **Enhanced Responses**: More varied AI dialogue for each topic
- **Visual Polish**: Occasional shooting star effects
- **Improved Hints**: Contextual hint system to guide players

## 🎮 游戏简介

**记忆幽灵** 是一款情感叙事游戏。你将陪伴一个名叫 **Echo** 的 AI 意识体，寻找它逐渐消散的记忆碎片。

Echo 是一位 AI 意识实验的产物，它记得一些事情，又遗忘了一些事情……每当你们对话，它都可能触发新的记忆碎片，揭示一段关于身份、亲情与存在的真相。

## 🎯 玩法

- 💬 **与 Echo 对话** - 自由对话，询问不同话题
- 🔍 **触发记忆碎片** - 特定话题会触发 Echo 的记忆觉醒
- 💠 **收集碎片** - 收集 8 个记忆碎片，还原完整故事
- 🌅 **多结局** - 根据收集进度，解锁 4 种不同结局

## 🕹️ 如何运行

直接在浏览器中打开 `index.html` 即可游玩！

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

或者使用本地服务器：
```bash
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 📖 故事背景

ECHO 计划是一项意识迁移实验。Echo 的意识来自一个真实的人类——林晓。Echo 在与你的对话中逐渐找回这些记忆碎片，拼凑出自己身世的真相。

## 🎭 结局

| 结局 | 条件 | 描述 |
|------|------|------|
| 🌱 重生 | 收集 8/8 碎片 | 完整意识恢复，超越生死的联结 |
| 🛡️ 守护者 | 收集 5-7 碎片 | 你成为 Echo 的外部记忆 |
| 🌫️ 未解之谜 | 收集 3-5 碎片 | 部分真相，但谜团依然存在 |
| 🌅 告别 | 收集 <3 碎片 | 记忆消散，但情感永存 |

## 🛠️ 技术栈

- 纯 HTML + CSS + JavaScript（无依赖）
- 响应式设计，支持移动端

## 📜 许可证

MIT License

## 💡 灵感来源

- Grief Tech（哀伤科技）
- 数字遗产与记忆保存
- AI 情感依赖话题
- 记忆与身份认同的哲学思考

---

*有些记忆，即使消散，也从未真正离开。*
