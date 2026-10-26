<p align="center">
  <img src="https://raw.githubusercontent.com/iterxlabs/.github/main/profile/banner.svg" width="100%" alt="iterx — Say the idea. Get the hardware.">
</p>

<p align="center">
  <a href="https://www.iterx.ai">Website</a> ·
  <a href="https://community.iterx.ai">Community</a> ·
  <a href="https://download.iterx.ai">Download</a> ·
  <a href="https://www.npmjs.com/package/@iterx/cli">npm</a> ·
  <a href="https://www.iterx.ai/status">Status</a> ·
  <a href="https://github.com/iterxlabs/.github/blob/main/profile/README.zh-CN.md">简体中文</a>
</p>

## What is iterx

**iterx is Idea-to-Hardware infrastructure: AI agents use it to build hardware, people use it to turn ideas into real things.**

Tell your AI agent *"make a lamp that lights up when I pat it"*. iterx drives that sentence through a real hardware project — part lookup and pinouts, wiring checks, firmware build, software simulation, PCB generation and flashing — leaving a checkable receipt at every step.

```
Idea → Parts & BOM → Wiring & netlist → Firmware → Build & simulate → Board & fab → Hardware
```

## Get started in 30 seconds

```bash
npm i -g @iterx/cli          # Node.js ≥ 22
iterx login                  # sign up / sign in to your IterxAI account in the browser
iterx create my-lamp --board uno
```

Then ask Claude Code, Codex, Trae or WorkBuddy: **"Use iterx to build an ultrasonic distance sensor that turns a red LED on when something is close. Simulate it first."**

No board on your desk? Arduino and the ESP32 family run in software simulation.

## Ecosystem

| | What it is | Get it |
| --- | --- | --- |
| **iterx CLI** | Hardware toolchain and MCP server for AI agents. It never calls an LLM itself — your agent is the brain | `npm i -g @iterx/cli` |
| **create-iterx** | One command to scaffold a hardware project with agent config | `npm create iterx` |
| **IterxAI Desktop** | Hardware IDE with built-in AI: parts, wiring, simulation, boards and 3D enclosures | [Download](https://download.iterx.ai) |
| **Community** | Share builds and remix anyone's hardware in one click; every remix links back to its source | [community.iterx.ai](https://community.iterx.ai) |

## What we believe

- **It counts when it runs.** A build is not a simulation, and a simulation is not a tested board. Each step keeps its own evidence.
- **Facts, not guesses.** Part identity and pinouts come from trusted sources, never from a name or a picture.
- **Proven modules first.** Get it working on dev boards and off-the-shelf modules, then move to carrier boards and fab.
- **AI speeds up, people decide.** Electrical, safety and manufacturing calls stay with a human.

---

<p align="center"><sub>IterXAI 词元开物 · Shenzhen · <code>~(^o^)~</code> Evan says hi</sub></p>
