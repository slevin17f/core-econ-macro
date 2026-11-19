---
name: core-econ-macro
description: |
  按 CORE Econ《The Economy 2.0: Macroeconomics》讲解宏观模型、出题批改或分析给定情景。适用于 WS–PS、需求乘数、通胀与政策、银行记账、汇率制度、危机动态、增长和政治经济学。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.core-econ-macro
  cangjie.capability-count: 10
  cangjie.entrypoint-count: 1
---
# The Economy 2.0: Macroeconomics — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 实时数据查询、资产定价预测、个股交易决策和微观卷专章。
- 跨微观、宏观和投资基础的综合学习计划交由 economics-tutor 编排；其中指定 CORE 宏观教材的练习可回到本入口。

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 用户指定节号时先查 references/overview.md 中的原书小节，再选能力卡。章节题、图号、数据及原书措辞回到对应页面核对。
2. 讲解用一个经济问题引入模型，列主体、变量、坐标与保持不变的条件，再用一个反例检验。练习模式先给题，等作答后指出第一处推理或计量错误，并给一道只改变一个条件的变式。
3. 核算先对齐时期、单位和分母，分别给恒等式、行为假设和结果。实际案例标明资料时期，教学自拟的数字标为合成。
4. 情景分析按冲击、传导、结果和可区分解释的观测量作答。材料不足时给条件分支。多单元课程按问题分段，每段按需加载。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 就业、失业率、实际工资、WS–PS 均衡 | references/capabilities/labour.md | references/capabilities/distribution.md |
| 洛伦兹曲线、基尼系数、工会、分割市场 | references/capabilities/distribution.md | references/capabilities/labour.md |
| GDP 核算、消费平滑、投资、税收与进口泄漏 | references/capabilities/demand.md | references/capabilities/stabilisation.md |
| 物价指数、议价缺口、预期、菲利普斯曲线 | references/capabilities/inflation.md | references/capabilities/stabilisation.md |
| 紧缩、需求冲击、成本冲击、利率传导 | references/capabilities/stabilisation.md | references/capabilities/regimes.md |
| 银行放贷、跨行结算、央行准备金、杠杆 | references/capabilities/banking.md | references/capabilities/dynamics.md |
| FlexIT、Fix、FlexNIT、汇率与利率平价 | references/capabilities/regimes.md | references/capabilities/stabilisation.md |
| 房价泡沫、去杠杆、冰层、碳锁定 | references/capabilities/dynamics.md | references/capabilities/banking.md |
| 增长核算、TFP、增长动态曲线、碳强度 | references/capabilities/growth.md | references/capabilities/dynamics.md |
| 中位选民、寻租、政策可行性、委托代理 | references/capabilities/government.md | references/capabilities/distribution.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 缺少计量口径或制度条件时，先写可确定的部分，说明还需要什么才能作定量判断。
