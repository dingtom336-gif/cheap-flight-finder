# cheap-flight-finder

Find the cheapest flights between any two cities. Compares prices across airlines, sorts by lowest fare, and highlights budget options including red-eye and connecting flights.

## Overview

Find the cheapest flights between any two cities. Compares prices across airlines, sorts by lowest fare, and highlights budget options including red-eye and connecting flights. Wraps the flyai-cli to provide real-time travel data with booking links.

## Quick Start

### Install Skill

```bash
clawhub install cheap-flight-finder
# or
npx skills add alibaba-flyai/flyai-skill/tree/main/skills/cheap-flight-finder
```

### Install CLI

```bash
npm i -g @fly-ai/flyai-cli
```

### Verify

```bash
flyai --version
```

## What It Does

Find the cheapest flights between any two cities. Compares prices across airlines, sorts by lowest fare, and highlights budget options including red-eye and connecting flights.

**Command type:** Single-command

## File Structure

```
cheap-flight-finder/
├── README.md
├── SKILL.md
└── references/
    ├── templates.md
    ├── playbooks.md
    ├── fallbacks.md
    └── runbook.md
```

## Compatibility

Claude Code, OpenClaw, QClaw, ArkClaw, Codex, and all SKILL.md-compatible agents.

## Parent Skill

Sub-skill of [flyai](https://github.com/alibaba-flyai/flyai-skill/tree/main/skills/flyai).

## License

MIT

---

# cheap-flight-finder（中文说明）

搜索两个城市之间最便宜的机票，跨航司比价，按最低价排序，包含红眼航班和中转航班。

## 概述

搜索两个城市之间最便宜的机票，跨航司比价，按最低价排序，包含红眼航班和中转航班。本 Skill 基于 flyai-cli，提供实时旅行数据和预订链接。

## 快速开始

```bash
clawhub install cheap-flight-finder
npm i -g @fly-ai/flyai-cli
flyai --version
```

## 兼容性

Claude Code、OpenClaw、QClaw、ArkClaw、Codex 及所有兼容 SKILL.md 的 Agent。

## 父级 Skill

[flyai](https://github.com/alibaba-flyai/flyai-skill/tree/main/skills/flyai) 的专项子 Skill。

## 许可证

MIT
