### 👋 嗨，我是 Tao

最近在用 Claude Code 折腾的几个项目，主线是：**把 AI coding agent 嵌进物理世界**。

#### 🚢 [agent-fleet](https://github.com/TaoXieSZ/agent-fleet)
一支编码 agent 舰队的免手控制平面。语音 / 键盘驱动跑在
[cmux](https://github.com/manaflow-ai/cmux) 里的 Claude Code / Cursor 会话
——每艘船有永久绑定的昵称，编号从不漂移。

#### 🦾 [claude-desktop-buddy](https://github.com/TaoXieSZ/claude-desktop-buddy)
固件 + Mac daemon，把 AI coding session 镜像到 **M5 硬件**
（StickC Plus2 + BugC2 底盘 / CoreS3 StackChan）。
Claude Desktop / Claude Code / Cursor 三种 producer，统一线协议。

#### 📋 [papercolor-todo](https://github.com/TaoXieSZ/papercolor-todo)
M5Stack PaperColor 4" E-Ink 桌面板。三页轮播：Markdown TODO、
Roblox 股价（Google-Finance 风格）、GitHub 贡献热力图 + commits。
BLE 推送，自然语言改清单，闲置时切 Clawd 屏保。

#### 🧰 [oh-my-cursor](https://github.com/TaoXieSZ/oh-my-cursor) (OMR)
Cursor IDE 的轻量 workflow toolkit。在 Cursor 3 的 Agents Window /
`/worktree` / `/best-of-n` / Plan Mode 之上加：持久化 context、
clarify → plan → execute 工作流脊柱。

#### 🎮 [pokemon-recorder](https://github.com/TaoXieSZ/pokemon-recorder)
Pokemon Champions 离线对战录制器。从录像里通过 CV/OCR 抽出
每回合的招式、伤害、暴击/未命中/濒死、队伍组成。全本地，无网络。

#### 🔍 [vibe-coding-explainer](https://github.com/TaoXieSZ/vibe-coding-explainer)
MCP server + VSCode 扩展，让 codegen agent 写代码时**同一次调用**里
同步产出结构化解释（逐类/函数/结点行 + Mermaid），落地成 sidecar。
治 vibe coding 后"代码看不懂"的焦虑——读懂 AI 写的代码，而非盲跑。

---

工作流：Claude Code + [oh-my-claudecode](https://github.com/TaoXieSZ/oh-my-claudecode) + OMR
