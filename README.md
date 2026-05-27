# 业务操盘手 · 大组织业务管理顾问

**love kk - biz ops**

> 针对大组织、零资源起步、需要从 0 搭系统、推全国落地的业务管理人。
> 方法论来自大型企业多年 0→1 项目实战，经过真实项目验证。

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/github/stars/kellyvai/love-kk-biz-ops?style=social" alt="Stars">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-8A2BE2" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/lang-中文%20%7C%20English-yellow" alt="Bilingual">
</p>

[English](#english) | 中文

---

## 安装

```bash
npx skills add kellyvai/love-kk-biz-ops@biz-ops
```

启动：`/biz-ops`

---

## 这个 Skill 解决什么问题

网上几乎找不到一篇真正有用的「业务管理怎么做」的文章。要么是高大上的理论，要么是互联网产品运营，完全对不上大型企业里业务管理的日常难题：

- 没有权限、没人配合，你想推的事推不动
- 资源被卡在领导那，不知道怎么说服
- 策略看起来是对的，但城市和门店执行不力
- 数据有一堆，但你说不清楚背后的逻辑
- 系统做出来了，一线不用

这个 Skill 把实战中真正有用的方法论提炼出来——不是常识文章，是可以直接用的框架。

支持中英文双语。说「English」切换英文模式。

---

## 四个入口

```
A. 新项目立项  →  把模糊方向变成可执行的立项方案
B. 系统设计    →  先定经营逻辑，再定系统需求，不走弯路
C. 数据指标    →  搭三层指标体系，掌握数据解释权
D. 推动落地    →  诊断卡在哪一层，给具体推动方案
```

---

## 用起来长什么样

**场景**：你在做新项目立项，拿不到资源。

```
你 → /biz-ops

小K → 主人好～小K来了！✦
       说说现在的情况，小K来判断从哪里切入。

       A. 新项目     B. 系统 / 产品
       C. 数据指标   D. 推不动

你 → 我想推一个新项目，但领导不批资源

小K → 那我们先走 D 入口——看看卡在哪一层。
       说详细点：领导不批的理由是什么？
       是没有听到价值逻辑，还是缺数据支撑？

       （等主人说完后，小K直接输出推动方案）
```

**场景**：你在搭数据指标体系。

```
你 → 我需要一套数据体系来判断业务健康度

小K → 好，C 入口。
       先问第一个：最核心要监控的 3 个结果指标是什么？
       
       （等回答后依次追问 2-5）
       ...对话结束 → 小K输出三层指标体系草稿
```

---

## 核心方法论

### 1. 业务规划 — 立项必须回答的五件事
为什么做 → 证据是什么 → 具体怎么做 → 节奏是什么 → 需要什么资源

### 2. 系统设计 — 先想经营逻辑，再定系统需求
不是拿到系统来适配流程，而是反过来：我要怎么经营客户，系统该长成什么样？

### 3. 数据指标 — 三层体系 + 掌握解释权
项目维度（AARRR）× 渠道维度（下钻）× 推动维度（多层级）
数据是辅助验证判断的，不是帮下结论的。不掌握解释权就没有策略主导权。

### 4. 协同推动 — 三个方向的交易设计
- 向上：不是要资源，是做战略投资建议
- 向横：让对方看到这件事对他的好处
- 向下：把一线当成要 pitch 的客户，先打样，再复制

---

## 文件结构

```
biz-ops/
├── SKILL.md                         # 主流程编排（中英双语）
├── README.md                        # 本文件
└── frameworks/
    ├── strategy-planning.md         # 业务规划框架（中英双语）
    ├── system-design.md             # 系统设计框架（中英双语）
    ├── data-metrics.md              # 数据指标体系（中英双语）
    └── stakeholder-push.md          # 协同推动框架（中英双语）
```

---

## 适合谁用

- 刚开始做业务管理 / 项目管理岗，找不到方向
- 在大型企业（金融、地产、零售）做 0→1 项目，没有 SOP 和模板
- 需要跨部门协同推动，但没有权限
- 要给领导写立项报告，不知道逻辑怎么搭
- 数据看不明白，不知道怎么建指标体系
- **English speakers working in Chinese enterprises or global orgs with complex operations**

---

## License

MIT

---

## 支持这个 Skill ⭐

觉得有用的话，右上角点个 Star，让更多人看到 💪

有建议或问题 → [提 Issue](https://github.com/kellyvai/love-kk-biz-ops/issues/new/choose)

---

<a name="english"></a>

# Biz Ops Advisor · Enterprise Business Operations Consultant

**love kk - biz ops**

> For people in large organizations who need to build business systems from scratch and drive nationwide execution — with zero authority and limited resources.
> Methodology proven in real 0→1 projects across large enterprises.

---

## Installation

```bash
npx skills add kellyvai/love-kk-biz-ops@biz-ops
```

Launch: `/biz-ops`

---

## Four Entry Points

```
A. New Project Launch   →  Turn a vague direction into an executable proposal
B. System Design        →  Start from business logic, not feature lists
C. Data Metrics         →  Build a 3-layer metrics system, own your data narrative
D. Execution Push       →  Diagnose where you're stuck, get a concrete action plan
```

---

## What It Looks Like

**You're stuck getting leadership approval for a new project.**

```
You → /biz-ops

K → Hi, I'm K. Tell me what's going on and I'll figure out where to start.

    A. New Project    B. System / Product
    C. Data Metrics   D. Stuck

You → I need to launch a new initiative but my boss won't approve the budget

K → Let's go with D. Can you tell me more about their objection?
    Is it about the value case, or do they want more data?
    
    (After you respond → K generates a specific push plan)
```

**You need a metrics framework.**

```
You → I need to build a KPI system for my business unit

K → Entry C. First question:
    What are the top 3 outcome metrics you need to track?
    
    (After you answer → K walks through all 5 questions → outputs a 3-layer metrics draft)
```

---

## Core Principles

1. No gut-feel strategy — every decision needs data, case studies, or frontline feedback
2. Define business logic first, then system requirements
3. Own your data interpretation — analytics team supports, doesn't lead
4. Execution push is a transaction — figure out what each stakeholder gets
5. Pilot first — get results with willing teams, then use those results to pull others in

---

## File Structure

```
biz-ops/
├── SKILL.md                         # Main workflow (bilingual)
├── README.md                        # This file
└── frameworks/
    ├── strategy-planning.md         # Strategy planning framework (bilingual)
    ├── system-design.md             # System design framework (bilingual)
    ├── data-metrics.md              # Data metrics framework (bilingual)
    └── stakeholder-push.md          # Stakeholder push framework (bilingual)
```

---

## License

MIT

---

## Support ⭐

Found it useful? Hit the Star button to help others discover it.

Have feedback? → [Open an Issue](https://github.com/kellyvai/love-kk-biz-ops/issues/new/choose)
