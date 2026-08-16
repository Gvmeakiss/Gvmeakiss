<div align="center">

# 👋 Hi, I'm James Li

**IT Audit · Data Analytics · ERP Data Matching**

专注于四大IT审计需求的自动化工具构建的机车佬：从 SAP ECC & S4 Hana/ 用友U8 / OMS / DMS / 金蝶 等多源系统提取数据，构建采购、销售三单匹配、业财核对、经营数据分析、JETesting 等对账流程，输出可复核、可追溯的差异分析结果。

<sub>*A motorcycle rider building automation tools for Big-4 IT audit: extracting data from SAP ECC & S/4HANA, Yonyou U8, OMS / DMS, Kingdee and more, and building reconciliation pipelines for purchase & sales three-way matching, business-finance reconciliation, operating-data analysis and JE testing — delivering reviewable, traceable variance analysis.*</sub>

<br>

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Expert-4479A1)
![SAP](https://img.shields.io/badge/SAP-ECC%2FS4HANA-0FAAFF?logo=sap&logoColor=white)
![U8](https://img.shields.io/badge/U8-ERP-6C8EBF)
![Excel](https://img.shields.io/badge/Excel-Openpyxl-217346?logo=microsoftexcel&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-Bash-89E051?logo=gnubash&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

<br>

![Project Repos](https://img.shields.io/badge/Project%20Repos-20-blue?style=flat-square)
![Categories](https://img.shields.io/badge/Project%20Categories-6-9cf?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Three--Way%20Matching%20%7C%20Data%20Reconciliation-orange?style=flat-square)

</div>

---

## 🧑‍💻 关于我 · About

- 四大IT审计背景（DTT*2year、KPMG*2year），现专注审计数据分析与自动化工具建设
  <sub>*Big-4 IT audit background (2 yrs DTT, 2 yrs KPMG), now focused on audit data analytics and automation tooling.*</sub>
- 把审计逻辑沉淀为可复用的数据工具，覆盖采购 / 销售三单匹配、SAP 取数、多源对账
  <sub>*Turning audit logic into reusable data tools — purchase / sales three-way matching, SAP data extraction, multi-source reconciliation.*</sub>

## 📂 项目矩阵 · Projects

> 20 个公开仓库，按能力域分组；**★ 为核心可复用工具**（建议先看），「类型」标注其适用边界（通用底座 / 具体客户项目）。
> <sub>*20 public repos grouped by capability; ★ marks core reusable tools (start here). The 类型 column marks the scope: generic foundation vs. client-specific project.*</sub>

### ⭐ 核心仓库

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| ★ [sap-abap-data-extraction](https://github.com/Gvmeakiss/sap-abap-data-extraction) | SAP ABAP 取数 KAAP 配置与操作手册（FI / MM / SD），分模块取数范围与审计场景映射（三单匹配 / 序时账-余额核对） | 通用 | `ABAP` · `XML` · `PDF` |
| [kpmg-da-skills](https://github.com/Gvmeakiss/kpmg-da-skills) | 7 个可移植 Codex 审计数据分析技能（含 workbench 路由） | 通用 | `Skills` · `Codex` |
| [purchase-three-match-configurable](https://github.com/Gvmeakiss/purchase-three-match-configurable) | 可配置通用数据匹配工具包（SQL 解析 / 缓存 / 匹配键 / 分类驱动） | 通用 | `Python` · `Pandas` |
| [sales-oms-dms-match](https://github.com/Gvmeakiss/sales-oms-dms-match) | Miaoke ToB 销售 OMS / DMS 双源三单匹配（5 类差异） | Miaoke | `Python` |
| [u8-inventory-valuation](https://github.com/Gvmeakiss/u8-inventory-valuation) | U8 存货发出计价审计复核（CAATS / ITA 职责分离双工作簿） | 通用 | `Excel` · `U8` |
| [miaoke-sales-to-c](https://github.com/Gvmeakiss/miaoke-sales-to-c) | Miaoke ToC 四段 pairwise 对账（旺店通 → 惠策 → OMS → SAP） | Miaoke | `Python` · `Pandas` |

### 📥 SAP ABAP 取数工具（FI / MM / SD）

> sap-abap-data-extraction 是执行三单匹配与序时账核对的基础。按 FI / MM / SD 三个模块配置 KAAP 取数脚本，分别支撑财务核算、采购与销售三单匹配。

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [📒 FI — 财务取数](https://github.com/Gvmeakiss/sap-abap-data-extraction/blob/main/FI/README.md) | 抽序时账（BKPF + BSEG）与余额表（FAGLFLEXT / GLT0）、次要索引、科目主数据，支撑序时账-课余表勾稽（含 SAP 标准表参考） | 通用 | `ABAP` · `XML` |
| [📦 MM — 采购取数](https://github.com/Gvmeakiss/sap-abap-data-extraction/blob/main/MM/README.md) | 抽订单 / 采购历史（EKBE 枢纽）/ 收货 / 发票，支撑采购三单匹配（含 SAP 标准表参考） | 通用 | `ABAP` · `XML` |
| [🚚 SD — 销售取数](https://github.com/Gvmeakiss/sap-abap-data-extraction/blob/main/SD/README.md) | 抽订单 / 交货 / 开票 / 凭证流（VBFA），支撑销售三单匹配（含 SAP 标准表参考） | 通用 | `ABAP` · `XML` |

### 🛒 三单匹配 · 采购

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [purchase-three-match-configurable](https://github.com/Gvmeakiss/purchase-three-match-configurable) | ★ 可配置通用数据匹配工具包（SQL 解析 / 缓存 / 匹配键 / 分类驱动） | 通用 | `Python` · `Pandas` |
| [purchase-three-match-toolkit](https://github.com/Gvmeakiss/purchase-three-match-toolkit) | SAP MM 采购三单匹配（四大类十三子类差异分析） | 通用 | `Python` · `Pandas` |
| [purchase-three-match-final](https://github.com/Gvmeakiss/purchase-three-match-final) | 采购三单匹配最终整合版（四大类13子类，SAP ECC/S4，KPMG 格式数据） | 通用 | `Python` |
| [purchase-three-match-newhope](https://github.com/Gvmeakiss/purchase-three-match-newhope) | NewHope 采购三单匹配落地版（含 SAP 取数配套文档） | NewHope | `Python` |
| [purchase-three-match-aqpp](https://github.com/Gvmeakiss/purchase-three-match-aqpp) | AQPP 2026 三单匹配归档索引（订单 / 发运 / 发票，AQPP-01~24） | AQPP | `Python` |
| [miaoke-purchase-2026](https://github.com/Gvmeakiss/miaoke-purchase-2026) | Miaoke 2026H1 采购三单匹配（订单行粒度全外连接 + AQPP 24 组） | Miaoke | `Python` · `Pandas` |

### 💰 三单匹配 · 销售

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [sales-oms-dms-match](https://github.com/Gvmeakiss/sales-oms-dms-match) | ★ Miaoke ToB 销售 OMS / DMS 双源三单匹配（5 类差异） | 通用 | `Python` |
| [sales-three-match-toolkit](https://github.com/Gvmeakiss/sales-three-match-toolkit) | NewHope SAP SD 销售三单匹配（(VKORG,VBELN,POSNR) 键，30GB+ 优化） | 通用 | `Python` · `Pandas` |
| [sap-sd-three-match](https://github.com/Gvmeakiss/sap-sd-three-match) | SAP SD 销售三单匹配（13 场景，按公司批量并行） | 通用 | `Python` · `SAP` |
| [sales-three-match-newhope](https://github.com/Gvmeakiss/sales-three-match-newhope) | NewHope 销售三单匹配实施版（含使用示例与排错） | NewHope | `Python` |
| [sales-three-match-newhope-2026](https://github.com/Gvmeakiss/sales-three-match-newhope-2026) | NewHope 2026 销售三单匹配（AQPP 无交货金额 24 子组） | NewHope | `Python` · `Pandas` |
| [sales-three-match-miaoke-2026](https://github.com/Gvmeakiss/sales-three-match-miaoke-2026) | Miaoke 2026H1 销售三单匹配（OMS / DMS 双渠道 AQPP-01~24） | Miaoke | `Python` · `Pandas` |
| [miaoke-sales-to-b-2025](https://github.com/Gvmeakiss/miaoke-sales-to-b-2025) | Miaoke 2025 全年 ToB 销售三单匹配（FY25 五分类） | Miaoke | `Python` |
| [miaoke-sales-to-b-2026](https://github.com/Gvmeakiss/miaoke-sales-to-b-2026) | Miaoke 2026H1 ToB 销售三单匹配（冲销前置 / PBC 拆分 / 单测） | Miaoke | `Python` |
| [miaoke-sales-to-c](https://github.com/Gvmeakiss/miaoke-sales-to-c) | ★ Miaoke ToC 四段 pairwise 对账（旺店通 → 惠策 → OMS → SAP） | Miaoke | `Python` · `Pandas` |

### 🧾 SAP JETesting 核对

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [sap-fi-2026h1](https://github.com/Gvmeakiss/sap-fi-2026h1) | SAP FI 2026H1 序时账 JE 测试（Journal Entry Testing）：ACDOCA / BKPF / FAGLFLEXT 抽取、过账勾稽与异常凭证筛查 | 通用 | `Python` · `SAP` |
| [CRRC_DT](https://github.com/Gvmeakiss/CRRC_DT) | CRRC 多公司 JE 会计分录测试：序时账合并 + 期初/发生额/期末余额勾稽（基于 ACDOCA / BKPF / BSEG） | 通用 | `Python` · `SAP` |
| [CRRC_XC](https://github.com/Gvmeakiss/CRRC_XC) | CRRC 材料板块多公司 JE 测试：序时账合并 + 余额交叉验证（基于 BKPF / BSEG） | 通用 | `Python` · `SAP` |

### 🧰 工具

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [test-tools](https://github.com/Gvmeakiss/test-tools) | ★ SAP MM 三单匹配诊断与数据质量工具 | 通用 | `Python` |

---

## 🧠 核心方法论 · Methodology

- **三单匹配（Three-Way Matching）**：采购订单 / 收货单 / 发票 三方核对，定位差异并分类
  <sub>*Three-way matching: cross-check purchase order / goods receipt / invoice; locate and classify variances.*</sub>
- **多源数据对账**：OMS / DMS / SAP 系统间数据一致性校验
  <sub>*Multi-source reconciliation: consistency checks across OMS / DMS / SAP.*</sub>
- **可复核输出**：每个结论附带口径说明、源数据逻辑与运行记录，支撑审计留痕
  <sub>*Reviewable output: every result ships with its basis, source-data logic and run records for audit trail.*</sub>

---

## 📚 参考与官方文档 · References

> 项目逻辑（三单匹配 / 序时账-余额核对 / 多源对账）依赖各 ERP 系统的标准数据结构与接口规范，以下为各厂商官方说明文档，作为数据口径与字段映射的权威依据。
> <sub>*The reconciliation logic relies on each ERP's standard data structures and interfaces. Official vendor docs below serve as the authoritative basis for data scoping and field mapping.*</sub>

### 🟦 SAP（ECC / S/4HANA）
- [SAP Help Portal](https://help.sap.com/docs/) — SAP 官方帮助门户，覆盖 ECC / S/4HANA 全模块文档
- [SAP ERP (ECC) 文档](https://help.sap.com/docs/SAP_ERP) — MM / SD / FI 模块标准配置与底表结构
- [SAP S/4HANA 文档](https://help.sap.com/docs/SAP_S4HANA_ON_PREMISE) — S/4HANA 总账（ACDOCA）与凭证架构
- [ABAP 关键字文档 / 数据字典](https://help.sap.com/doc/abapdocu_latest_index_htm/latest/index.htm) — 标准底表（BKPF / BSEG / EKPO / VBAK …）字段与域定义

### 🟥 用友（U8）
- [用友开发者中心](https://developer.yonyou.com/) — U8 / U9 / NC 开放接口与开发文档
- [用友 U8 产品与文档](https://u8.yonyou.com/) — U8 存货 / 供应链 / 财务模块说明

### 🟩 金蝶（Kingdee）
- [金蝶开放平台](https://open.kingdee.com/) — 金蝶云·苍穹 / K/3 开放 API 与集成规范
- [金蝶开发者社区](https://dev.kingdee.com/) — 苍穹 PaaS 平台开发文档与数据模型
- [金蝶官网](https://www.kingdee.com/) — 产品与模块总览

---

<div align="center">

*Disclaimer: Personal projects and personal views. Not affiliated with or endorsed by KPMG.*<br>
*本页内容为个人项目与个人观点，与 KPMG 无关。*

</div>
