# 用动态曲线判别危机、临界点与转型

## R｜适用任务与材料

输入连续两期可比较的状态量、一条假定或估计的转移关系、扰动事件和反馈渠道。可选房价、家庭资产、夏季海冰量或电动车采用率。先说明系统边界与时间单位。[§8.2 临界点](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-02-tipping-points-instability-lock-in.html) [§8.3 贫困陷阱](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-03-real-world-poverty-trap-application.html)

## I｜作图与推理

1. 横轴 xₜ，纵轴 xₜ₊₁，取相同单位与刻度。画 y=x 与转移曲线 y=F(x)。交点满足 F(x)=x。在每一交点两侧任选值，若 F(x)>x 则下一期向右，若 F(x)<x 则向左。教材的单调 S 形图中两侧箭头指向交点表示稳定，均背离则是临界点。从初始横坐标上到曲线，再水平移至对角线，迭代读数。[§8.2 动态图](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-02-tipping-points-instability-lock-in.html) [§8.5 房价曲线](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-05-model-house-price-bubble.html)
2. 区分一次性状态冲击和转移机制改变。前者把 xₜ 推到另一位置，可能越过原阈值；后者改变同一 xₜ 对应的下一期值，应重画曲线并重新找全部交点。房市中须指出哪一种信贷或预期变化足以使曲线移动。[§8.6 结构性变动](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-06-housing-market-changes-pdc-shifts.html)
3. 按场景写出反馈环及可观察量。
   - 房价上涨扩大抵押能力，新增借款推高住房需求，反过来抬高房价。下跌时查净值、违约、被迫出售、目标财富与消费削减。区分基本面改善与预期转售获利驱动的价格上涨。[§8.4 泡沫判据](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-04-assets-price-bubbles.html) [§8.7 金融加速器](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-07-borrowing-lending-aggregate-consumption.html) [§8.8 美国家庭分布](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-08-inequality-us-housing-application.html)
   - 银行用资产、负债和权益重算损失。短期融资续借困难可迫使有偿付能力的银行抛售；多家抛售共同资产会经价格传染。按病因匹配流动性支持、资本缓冲、限制风险敞口或有序处置，分清何种债权人吸收损失。[§8.9 银行互联](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-09-vulnerabilities-of-banks.html) [§8.10 制度应对](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-10-instability-of-financial-system.html)
   - 海冰减少导致水面吸收更多热量，加剧融化。一次异常高温可冲击当期冰量；持续变暖可使环境动态曲线整体下移并消除高海冰均衡。临界点未知时比较降低最坏后果风险的干预成本。[§8.11 北极海冰](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-11-environmental-collapse-model.html) [§8.12 审慎政策](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-12-prudential-environmental-policies.html)
   - 电动车普及促进充电网络和规模经济，降低相对使用成本。补贴或偏好变化可上移采用动态曲线，使低采用均衡靠近临界点；撤回补贴后需在撤回后的曲线上重新判定归宿。[§8.13 碳锁定](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-13-carbon-trap-green-technologies.html)

## A1｜合成演练

给定电动车份额 x∈[0,1] 的假设转移函数 F(x)=x−(x−0.2)(x−0.5)(x−0.8)。交点为 0.2、0.5、0.8。以 0.4 和 0.6 为初值，下一期分别为 0.392 和 0.608，两者远离 0.5。在 0.2 与 0.8 两侧检查符号可知二者吸引邻近状态。一次采购把份额从 0.4 推至 0.48，取消采购后仍会回落；若推至 0.52 且原函数持续有效，此后会向 0.8 靠近。此函数用于练习，实地阈值需要单独估计。教材案例使用采用动态曲线比较补贴前后均衡。[§8.13 图8.33](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-13-carbon-trap-green-technologies.html)

## A2｜何时调用与迁移

当用户要判断一次冲击能否永久改变状态、为什么资本充足的银行也会遭遇挤兑、为什么同一项绿色政策在不同起点效果不同，先选状态并画反馈，再按所需证据选场景。只给一次价格变化时，列出基本面与预期反馈两种解释及区分二者所需证据。对于银行账面项目先用第6单元对账，再分析系统放大机制。[§8.1 雷曼案例](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-01-lehman-brothers-collapse.html)

## E｜交付与验收

交付带坐标、均衡和箭头的图或等价符号表；报告初始点、下一期、长期归宿与所依赖的条件；提出一条能切断反馈的政策以及对应的观察指标。合成题可让学习者把起点换到临界点另一侧，再比较临时冲击和永久改变 F 的结果。

## B｜反例与边界

一个持续上升的价格序列无法单独识别投机性泡沫。双峰分布也无法单独证明存在贫困陷阱，需查看相似初始条件下的跨期变化或干预证据。正反馈表示偏离被放大，在技术采用中也能推动社会期望的转型。海冰原理图不能给出真实临界年份或越界概率。[§8.3 贫困陷阱证据](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-03-real-world-poverty-trap-application.html) [§8.12 根本不确定性](https://books.core-econ.org/the-economy/macroeconomics/08-financial-environmental-crises-12-prudential-environmental-policies.html)
