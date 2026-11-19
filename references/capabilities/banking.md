# 用资产负债表追踪信用、货币与杠杆

## R · 原书依据

第 6 单元先让 Marco 与 Julia 直接借贷，再加入商业银行、央行和金融市场。债权在一方是资产，在另一方是负债。家庭还可用住房、债券、股票等资产跨期调配资源。[§6.1 退休收入](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-01-how-do-you-live-if-you-dont-work.html) · [§6.2 双边借贷](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-02-bilateral-debt.html) · [§6.3 中介和市场](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-03-debt-and-financial-sector.html) · [§6.4 银行](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-04-introducing-a-bank.html) · [§6.5 货币](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-05-introducing-money.html)

## I · 选择模型

追踪交易用分主体、分时点的账户表；比较企业融资风险用债务、权益、利息和经营收益；比较家庭资产时按现金收入、资本利得、流动性、期限及风险拆开。

## A1 · 合成演练

甲行初始有准备金 60、贷款 40，存款负债 90、权益 10。它发放贷款 20 并记入客户账户后，有准备金 60、贷款 60，存款 110、权益 10。客户向乙行客户付款 15 后，甲行准备金 45、贷款 60，存款 95、权益 10；乙行准备金与存款各增 15。两行合计存款相对放贷前净增 20，准备金总量不变。若此后甲行贷款发生已确认损失 6 且无其他变动，贷款降至 54，权益降至 4，甲行总资产和负债加权益均为 99。

## A2 · 何时调用

用于贷款是否创造存款、跨行转账、QE、净值与流动性、家庭或公司的杠杆压力测试。若问题是政策利率如何传导到通胀，分录完成后转第 5 单元。

## E · 执行与验收

1. 为借款人、存款人、各银行及必要时央行逐行列“期初、变化、期末”，逐行复核资产=负债+权益。为借贷双方对上工具与金额。区分期末存量与期间利息、收入流量。
2. 新贷款同时生成银行资产和存款负债；同银行内付款只更换存款持有人，跨行结算还移动央行准备金。用存款偿还本金时贷款和存款同时缩减。检查贷款需求与风险定价、资本充足程度、准备金与清算融资。[§6.6 央行](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-06-introducing-central-bank.html) · [§6.8 货币创造](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-08-money-creation-in-modern-economy.html)
3. QE 先标出售者。央行向银行购债时银行用债券换准备金，央行资产与准备金负债增加；向非银行购债并通过其往来银行结算时，出售者以存款换债券，银行同时增准备金和存款。合并政府与央行前先保留各自账表。[§6.7 央行与政府](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-07-central-bank-balance-sheet-and-government.html)
4. 企业用 K=D+E、课本杠杆 L=D/K。给定资产回报 rₖ、债务利率 i，税前权益回报=(rₖK−iD)/E。例：K=100、D=75、i=4%，rₖ 从 8% 降到 2%，权益回报从 20% 变为 −4%。将损失回填权益。[§6.10 企业杠杆](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-10-businesses-capital-and-leverage.html)
5. 债券区分票息和收益率，同一固定未来偿付在贴现率提高时价格下降。家庭住房总回报应包括租金或自住租金与价格变动，注明持有成本、按揭及是否按权益计；股票则区分股息与资本利得。输出交易表或收益表、金额、时点、分母及压力情景。[§6.9 金融市场](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-09-introducing-financial-markets.html) · [§6.11 家庭资产](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-11-household-investments.html) · [§6.12 金融部门全景](https://books.core-econ.org/the-economy/macroeconomics/06-financial-sector-12-financial-sector-overview.html)

## B · 反例与判停

银行能创造存款仍可能在付款时缺准备金，或在贷款违约时耗尽权益。两者分别是流动性和偿付能力问题。增加准备金并无固定倍数的必然贷款增长。若“杠杆 3 倍”没有分母，先列出资产/权益、债务/权益和课本债务/资产的可能口径再计算。
