# 系统设计框架 / System Design Framework

> B 入口（系统/产品设计）调用。
> Used in Entry B (System/Product Design). Internal reference for system requirements analysis.

---

## 核心逻辑 / Core Logic

**错误顺序 / Wrong order**：先问「系统能做什么」/ "What can the system do?"
**正确顺序 / Right order**：先问「我要怎么经营客户」/ "How do I want to operate?" → then define what the system needs to support.

---

## 四维分析 / Four Dimensions

| 维度 / Dimension | 关键问题 / Key Questions |
|-----------------|------------------------|
| 功能需求 / Functional needs | 需要什么功能？有现成的可以复用吗？ |
| 角色边界 / Role boundaries | 谁触发？谁执行？谁追踪？谁复盘？ |
| 人机协作 / Human-system split | 人做什么，系统做什么？现在vs目标？ |
| 扩展能力 / Scalability | 这套能否支撑未来场景复制？ |

---

## 两个视角 / Two Lenses

| 视角 / Lens | 链路 / Flow |
|------------|------------|
| 用户生命周期 / User lifecycle | 获客→激活→留存→复购 / Acquisition→Activation→Retention→Revenue |
| 用户服务流程 / Service journey | 线上进入→线下到店→接受服务→离店跟进 / Online→Store→Service→Follow-up |

### ⚠️ 高频陷阱 / Common Pitfalls

1. **C 端产品不是普通 APP** — 有实体门店 + 销售队伍的产品，核心是帮一线更容易打仗
   Consumer product with physical stores + sales team: the core is empowering frontline, not fancy UI
2. **不「以为」用户需要什么** — 去跑完整的流程、做调研，别猜
   Don't guess user needs — go through the full process yourself
3. **数据埋点前置** — 上线前想清楚哪些节点必须记录、用来做什么决策
   Plan your data tracking before building, not after launch

---

## 小K的问题清单 / K's Question Flow (B Entry)

1. 要支撑什么经营动作？（先说经营逻辑，不是功能）/ What business operation are you supporting? (Logic first, not features)
2. 用户路径是什么？线上和线下各在哪？/ User journey: online vs offline touchpoints?
3. 谁触发？谁执行？谁追踪？/ Who triggers, executes, and tracks each step?
4. 哪些节点必须埋数据？/ Which nodes need data tracking?
5. 有没有跑过真实业务流程？一线反馈是什么？/ Have you shadowed the real process? What did frontline say?

输出：系统需求分析文档草稿 / Output: system requirements draft
