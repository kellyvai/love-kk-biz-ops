# 数据指标体系框架 / Data Metrics Framework

> C 入口（数据指标体系）调用。
> Used in Entry C (Data Metrics). Internal reference for building a 3-layer KPI system.

---

## 三层视角 / Three Lenses

### 视角一 / Lens 1: 项目维度 / Project Level

用 AARRR 漏斗判断大盘健康度 / Use AARRR to assess pipeline health:
获客→激活→留存→推荐→转化 / Acquisition→Activation→Retention→Referral→Revenue

关键问题 / Key question: 现在卡在哪个阶段？/ Which stage is the bottleneck?

### 视角二 / Lens 2: 渠道维度 / Channel Level

同资源投不同渠道表现差异很大 / Same resources, very different results by channel:

| 渠道 / Channel | 特征 / Trait | 启示 / Insight |
|---------------|-------------|---------------|
| 社群 / Community | 活跃但成交低 | 适合品牌曝光 / Brand awareness play |
| App | 注册高留存差 | 优化用户体验 / Improve UX retention |
| 线下 / Offline | 转化好成本高 | 精准投放 / Targeted, quality over volume |

### 视角三 / Lens 3: 推动维度 / Execution Level

| 层级 / Level | 关注 / Focus | 核心指标 / Core Metrics | 决策用途 / Purpose |
|-------------|-------------|----------------------|------------------|
| 总部 / HQ | 高管 | KPI 完成率、ROI | 战略执行 / Strategy tracking |
| 区域 / Region | 区域负责人 | 转化率、触达率 | 目标拆解 / Goal breakdown |
| 门店 / Store | 店长 | 员工行为量 | 队伍管理 / Team mgmt |
| 一线 / Frontline | 员工 | 客户状态、推荐动作 | 具体执行 / Day-to-day action |

---

## 纵向分析 / Vertical Analysis

指标必须能往下追 / Metrics must be drillable:
- **二级**：哪个客层/渠道/产品拉的？/ Which segment/channel/product?
- **三级**：动作和效果对不对得上？/ Does action correlate with outcome?
- **同级细分**：哪个城市更好？/ Which city outperforms?

---

## ⚠️ 关键陷阱：数据解释权 / Key Trap: Data Narrative Ownership

**典型案例 / Classic case**：
App 下载数据说「下载 App 的客户转化率更高」→ 实际上是因为好客户才被引导下载
> "App downloaders convert better" sounds compelling until you realize it's because high-value customers were told to download.

**结论 / Rule**: 不掌握数据解释权，就没有策略主导权。
If you don't own the data narrative, you don't own the strategy.

---

## 小K的问题清单 / K's Question Flow (C Entry)

1. 最核心要监控的 3 个结果指标？/ Top 3 outcome metrics?
2. 每个结果指标对应的过程指标？/ Leading indicators for each?
3. 数据你自己能解释清楚吗？有没有「数据说一回事、业务另一回事」？/ Do you trust your data narrative? Any mismatches?
4. 不同层级分别看什么？/ What does each level need to see?
5. 数据反馈机制是什么？谁看、多久看、看完做什么？/ Feedback loop: who, when, action?

输出：三层指标体系草稿 / Output: 3-layer KPI framework draft
