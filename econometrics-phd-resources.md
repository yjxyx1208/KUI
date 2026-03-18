# 计量经济学 PhD 资源库

> 全方位覆盖计量经济学 PhD 方向的工具、课程、论文复现和学术资源。持续更新中。

---

## 核心工具（必装）

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [statsmodels](https://github.com/statsmodels/statsmodels) | ~11.3k | Python 统计建模与计量经济学核心库，涵盖回归、时间序列、假设检验 | 计量经济学 Python 生态的地基，OLS/GLS/WLS/分位数回归/VAR 全覆盖 |
| [linearmodels](https://github.com/bashtage/linearmodels) | ~1k | statsmodels 的补充，专注面板数据、工具变量（IV）、GMM | 面板数据和 IV 回归的首选，补上 statsmodels 缺的那块 |
| [pmdarima](https://github.com/alkaline-ml/pmdarima) | ~1.7k | Python 版 R 的 auto.arima，自动化时间序列 ARIMA 建模 | 时间序列自动定阶，省去手动调参的痛苦 |

---

## 因果推断

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [DoWhy](https://github.com/py-why/dowhy) | ~8k | 微软开源的因果推断库，结合因果图模型和 potential outcomes 框架 | 因果推断的瑞士军刀，从因果图到反事实估计一条龙 |
| [CausalML](https://github.com/uber/causalml) | ~5.8k | Uber 开源的 uplift modeling 和因果推断机器学习库 | 做 heterogeneous treatment effects 很顺手，工业界实战验证 |
| [EconML](https://github.com/py-why/EconML) | ~4.5k | 微软 ALICE 项目，ML + 计量经济学做因果效应估计（DML、正交学习等） | Double ML / Orthogonal Forest 等前沿方法的标准实现 |
| [python-causality-handbook](https://github.com/matheusfacure/python-causality-handbook) | ~3.3k | 《Causal Inference for the Brave and True》配套代码 | 因果推断入门神书的代码版，DID/RDD/IV 讲得清清楚楚 |

---

## 时间序列

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [pmdarima](https://github.com/alkaline-ml/pmdarima) | ~1.7k | 自动化 ARIMA 建模 | 见上方核心工具 |
| [statsforecast](https://github.com/Nixtla/statsforecast) | ~4.7k | 闪电般快速的统计预测模型库（ARIMA、ETS、Theta 等） | 速度碾压传统实现，适合大规模时间序列预测 |
| [fecon235](https://github.com/rsvp/fecon235) | ~1.3k | 金融经济学 Jupyter Notebooks，涵盖 FRED 数据、GDP、通胀、资产定价 | 宏观金融方向的宝藏，直接对接 FRED 数据源 |

---

## 面板数据

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [linearmodels](https://github.com/bashtage/linearmodels) | ~1k | 面板数据模型（固定效应、随机效应）、IV、系统方程 | Python 面板数据分析的唯一正经选择 |
| [plm (R)](https://cran.r-project.org/package=plm) | CRAN | R 的面板数据线性模型包 | R 生态下面板数据的标准包，FE/RE/Between/FD 全有 |

---

## 结构估计

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [StructEst_W20](https://github.com/rickecon/StructEst_W20) | ~82 | UChicago MACS 40200 结构估计课程材料（Winter 2020） | 芝大课程材料，MLE/GMM/SMM 的教学代码，质量没得说 |

---

## ML × 经济学

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [EconML](https://github.com/py-why/EconML) | ~4.5k | ML 方法做因果效应估计 | 见上方因果推断部分 |
| [python-causality-handbook](https://github.com/matheusfacure/python-causality-handbook) | ~3.3k | ML + 因果推断教程 | 见上方因果推断部分 |

---

## 论文复现

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [mostly-harmless-replication](https://github.com/vikjam/mostly-harmless-replication) | ~645 | 《Mostly Harmless Econometrics》表格和图形的多语言复现 | 经典教材的代码复现，Stata/R/Python/Julia 四种语言 |
| [replication-code-economics](https://github.com/ledwindra/replication-code-economics) | ~27 | 追踪经济学 Top 10 期刊公开复现代码/补充材料 | 找论文复现代码的索引站，AER/QJE/ECMA 等顶刊都在追踪 |

---

## 学术工具

### LaTeX 模板

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [econometrics-cheatsheet](https://github.com/marcelomijas/econometrics-cheatsheet) | ~159 | 计量经济学速查表，LaTeX 排版 | 考试/写论文时速查公式，排版精美 |

### 文献管理

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | ~37.4k | 社区驱动的文档管理系统，带 OCR 和 ML 分类 | 论文/文档管理神器，自动 OCR + 智能分类 |

### Stata 集成

| 工具 | 说明 |
|------|------|
| [ipystata](https://github.com/TiesdeKok/ipystata) | 在 Jupyter Notebook 中运行 Stata 代码 |
| [pyreadstat](https://github.com/Readstat/pyreadstat) | Python 读写 Stata (.dta)、SAS、SPSS 数据文件 |

---

## 资源合集

| 项目 | Stars | 简介 | 推荐理由 |
|------|-------|------|----------|
| [awesome-economics](https://github.com/antontarasenko/awesome-economics) | ~1.6k | 经济学家的精选链接合集 | 数据源、工具、课程、职业资源一网打尽 |
| [awesome-phd-advice](https://github.com/pliang279/awesome-phd-advice) | ~2k | PhD 申请和在读建议大合集 | 偏 CS/ML 但通用建议很多，心态管理/写作/求职都有 |
| [EconometricsResources](https://github.com/zuster/EconometricsResources) | ~992 | 经济学相关专业资料集（中文友好） | 中文社区整理的计量资源，含 MATLAB 代码和教材笔记 |

---

## 已安装的 Claude Skills 中相关技能

以下技能已在本地 Claude Code 环境中配置，可直接调用：

| 技能 | 用途 |
|------|------|
| statsmodels | 统计建模、回归分析、时间序列 |
| scikit-learn | 机器学习模型、交叉验证、特征工程 |
| shap | 模型可解释性分析 |
| polars | 高性能数据处理（比 pandas 快） |
| matplotlib / seaborn | 数据可视化 |
| numpy / scipy | 数值计算和科学计算基础 |

---

*最后更新：2026-03-18*
