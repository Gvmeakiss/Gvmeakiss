<div align="center">

# 👋 Hi, I'm James Li

**IT Audit · Data Analytics · ERP Data Matching**

专注于审计与数据领域的自动化工具建设：从 SAP / U8 / OMS / DMS 等多源系统提取数据，构建采购、销售三单匹配与对账流程，输出可复核、可追溯的差异分析结果。

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

![Project Repos](https://img.shields.io/badge/Project%20Repos-19-blue?style=flat-square)
![Categories](https://img.shields.io/badge/Project%20Categories-5-9cf?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Three--Way%20Matching%20%7C%20Data%20Reconciliation-orange?style=flat-square)

</div>

---

## 🧭 关于我

- 资深 IT 审计背景（DTT、KPMG），现专注审计数据分析与自动化工具建设
- 把审计逻辑沉淀为可复用的数据工具，覆盖采购 / 销售三单匹配、SAP 取数、多源对账

## 📂 项目矩阵

> 19 个公开仓库，按能力域分组；**★ 为核心可复用工具**（建议先看），「类型」标注其适用边界（通用底座 / 具体客户项目）。

### ⭐ 核心仓库

| 仓库 | 一句话定位 | 技术 |
|---|---|---|
| [kpmg-da-skills](https://github.com/Gvmeakiss/kpmg-da-skills) | 7 个可移植 Codex 审计数据分析技能（含 workbench 路由） | `Skills` · `Codex` |
| [purchase-three-match-configurable](https://github.com/Gvmeakiss/purchase-three-match-configurable) | 可配置通用数据匹配工具包（SQL 解析 / 缓存 / 匹配键 / 分类驱动） | `Python` · `Pandas` |
| [sales-oms-dms-match](https://github.com/Gvmeakiss/sales-oms-dms-match) | Miaoke ToB 销售 OMS / DMS 双源三单匹配（5 类差异） | `Python` |
| [sap-abap-data-extraction](https://github.com/Gvmeakiss/sap-abap-data-extraction) | SAP ABAP 取数 KAAP 配置与操作手册（FI / MM / SD） | `ABAP` · `XML` · `PDF` |
| [u8-inventory-valuation](https://github.com/Gvmeakiss/u8-inventory-valuation) | U8 存货发出计价审计复核（CAATS / ITA 职责分离双工作簿） | `Excel` · `U8` |
| [miaoke-sales-to-c](https://github.com/Gvmeakiss/miaoke-sales-to-c) | Miaoke ToC 四段 pairwise 对账（旺店通 → 惠策 → OMS → SAP） | `Python` · `Pandas` |

### 🔍 审计数据分析 · 2

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [kpmg-da-skills](https://github.com/Gvmeakiss/kpmg-da-skills) | 7 个可移植 Codex 审计数据分析技能（含 workbench 路由） | 通用 | `Skills` · `Codex` |
| [u8-inventory-valuation](https://github.com/Gvmeakiss/u8-inventory-valuation) | U8 存货发出计价审计复核（CAATS / ITA 职责分离双工作簿） | 通用 | `Excel` · `U8` |

### 🔄 三单匹配 · 采购 · 5

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [purchase-three-match-configurable](https://github.com/Gvmeakiss/purchase-three-match-configurable) | ★ 可配置通用数据匹配工具包（SQL 解析 / 缓存 / 匹配键 / 分类驱动） | 通用 | `Python` · `Pandas` |
| [purchase-three-match-toolkit](https://github.com/Gvmeakiss/purchase-three-match-toolkit) | SAP MM 采购三单匹配（四大类十三子类差异分析） | 通用 | `Python` · `Pandas` |
| [purchase-three-match-newhope](https://github.com/Gvmeakiss/purchase-three-match-newhope) | NewHope 采购三单匹配落地版（含 SAP 取数配套文档） | NewHope | `Python` |
| [purchase-three-match-aqpp](https://github.com/Gvmeakiss/purchase-three-match-aqpp) | AQPP 2026 三单匹配归档索引（订单 / 发运 / 发票，AQPP-01~24） | AQPP | `Python` |
| [miaoke-purchase-2026](https://github.com/Gvmeakiss/miaoke-purchase-2026) | Miaoke 2026H1 采购三单匹配（订单行粒度全外连接 + AQPP 24 组） | Miaoke | `Python` · `Pandas` |

### 🔄 三单匹配 · 销售 · 8

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [sales-oms-dms-match](https://github.com/Gvmeakiss/sales-oms-dms-match) | ★ Miaoke ToB 销售 OMS / DMS 双源三单匹配（5 类差异） | 通用 | `Python` |
| [sales-three-match-toolkit](https://github.com/Gvmeakiss/sales-three-match-toolkit) | NewHope SAP SD 销售三单匹配（(VKORG,VBELN,POSNR) 键，30GB+ 优化） | 通用 | `Python` · `Pandas` |
| [sales-three-match-newhope](https://github.com/Gvmeakiss/sales-three-match-newhope) | NewHope 销售三单匹配实施版（含使用示例与排错） | NewHope | `Python` |
| [sales-three-match-newhope-2026](https://github.com/Gvmeakiss/sales-three-match-newhope-2026) | NewHope 2026 销售三单匹配（AQPP 无交货金额 24 子组） | NewHope | `Python` · `Pandas` |
| [sales-three-match-miaoke-2026](https://github.com/Gvmeakiss/sales-three-match-miaoke-2026) | Miaoke 2026H1 销售三单匹配（OMS / DMS 双渠道 AQPP-01~24） | Miaoke | `Python` · `Pandas` |
| [miaoke-sales-to-b-2025](https://github.com/Gvmeakiss/miaoke-sales-to-b-2025) | Miaoke 2025 全年 ToB 销售三单匹配（FY25 五分类） | Miaoke | `Python` |
| [miaoke-sales-to-b-2026](https://github.com/Gvmeakiss/miaoke-sales-to-b-2026) | Miaoke 2026H1 ToB 销售三单匹配（冲销前置 / PBC 拆分 / 单测） | Miaoke | `Python` |
| [miaoke-sales-to-c](https://github.com/Gvmeakiss/miaoke-sales-to-c) | ★ Miaoke ToC 四段 pairwise 对账（旺店通 → 惠策 → OMS → SAP） | Miaoke | `Python` · `Pandas` |

### 🖥️ SAP 财务与取数 · 3

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [sap-abap-data-extraction](https://github.com/Gvmeakiss/sap-abap-data-extraction) | ★ SAP ABAP 取数 KAAP 配置与操作手册（FI / MM / SD） | 通用 | `ABAP` · `XML` · `PDF` |
| [sap-fi-2026h1](https://github.com/Gvmeakiss/sap-fi-2026h1) | SAP FI 2026H1 序时账 / 余额表 / 勾稽（ACDOCA / BKPF / FAGLFLEXT） | 通用 | `Python` · `SAP` |
| [sap-sd-three-match](https://github.com/Gvmeakiss/sap-sd-three-match) | SAP SD 销售三单匹配（13 场景，按公司批量并行） | 通用 | `Python` · `SAP` |

### 🧰 工具 · 1

| 仓库 | 说明 | 类型 | 技术 |
|---|---|---|---|
| [test-tools](https://github.com/Gvmeakiss/test-tools) | ★ SAP MM 三单匹配诊断与数据质量工具 | 通用 | `Python` |

---

## 🧠 核心方法论

- **三单匹配（Three-Way Matching）**：采购订单 / 收货单 / 发票 三方核对，定位差异并分类
- **多源数据对账**：OMS / DMS / SAP 系统间数据一致性校验
- **可复核输出**：每个结论附带口径说明、源数据逻辑与运行记录，支撑审计留痕

---

<div align="center">

*Disclaimer: Personal projects and personal views. Not affiliated with or endorsed by KPMG.*<br>
*本页内容为个人项目与个人观点，与 KPMG 无关。*

</div>
