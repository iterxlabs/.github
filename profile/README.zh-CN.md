<p align="center">
  <img src="https://raw.githubusercontent.com/iterxlabs/.github/main/profile/banner.zh-CN.svg" width="100%" alt="词元开物 iterx — 说出想法，硬件成真">
</p>

<p align="center">
  <a href="https://www.iterx.ai">官网</a> ·
  <a href="https://community.iterx.ai">社区</a> ·
  <a href="https://download.iterx.ai">下载客户端</a> ·
  <a href="https://www.npmjs.com/package/@iterx/cli">npm</a> ·
  <a href="https://www.iterx.ai/status">服务状态</a> ·
  <a href="https://github.com/iterxlabs">English</a>
</p>

## iterx 是什么

**iterx 是 AI 硬件创造的基础设施：agent 用它做硬件，人用它把想法变成实物。**

跟你的 AI 助手说一句"做一个摸头会亮的灯"，iterx 负责把这句话推进成一套真实的硬件工程：查元件和针脚、校验接线、编译固件、软件仿真、生成电路板、烧录上板，每一步都留下可以检查的回执。

```
想法 → 选型与 BOM → 接线与网表 → 固件 → 编译与仿真 → 成板与制造 → 实物
```

## 30 秒上手

```bash
npm i -g @iterx/cli          # 需要 Node.js ≥ 22
iterx login                  # 网页注册 / 登录 IterxAI 账号
iterx create my-lamp --board uno
```

然后在 Claude Code、Codex、Trae 或 WorkBuddy 里说：**"用 iterx 做一个超声波测距、距离近时亮红灯的小装置，先软件仿真。"**

没有开发板也能跑：Arduino 与 ESP32 系列都支持软件仿真。

## 生态

| | 是什么 | 怎么用 |
| --- | --- | --- |
| **iterx CLI** | 给 AI agent 调用的硬件工具链与 MCP server，自身不调用任何大模型，大脑是你的 agent | `npm i -g @iterx/cli` |
| **create-iterx** | 一条命令建好硬件项目和 agent 配置 | `npm create iterx` |
| **IterxAI 桌面端** | 内置 AI 的硬件 IDE：选型、接线、仿真、成板、三维外壳 | [下载](https://download.iterx.ai) |
| **词元开物社区** | 分享作品，一键复刻别人的硬件，复刻关系自动标注"源于" | [community.iterx.ai](https://community.iterx.ai) |

## 我们相信

- **能跑才算数。** 编译通过不等于仿真成功，仿真成功不等于真机验证，每一步分开记录证据。
- **事实不靠猜。** 元件身份与引脚绑定可信来源，不从名称或图片推测。
- **成熟模块优先。** 先用核心板与成品模块跑通，再进入载板与制造。
- **AI 加速，人做决定。** 电气、安全与制造的关键确认始终在人手里。

---

<p align="center"><sub>词元开物 IterXAI · 深圳 · <code>~(^o^)~</code> Evan 向你问好</sub></p>
