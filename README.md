# Awesome-Inventory-Optimization-Platform

## Top Inventory Optimization Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Demand Forecasting, Safety Stock, Multi-Echelon Optimization, Replenishment & Service-Level Driven Inventory Planning*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Inventory Optimization**. These tools help companies set optimal stock levels, calculate safety stock, generate replenishment recommendations, and balance service levels against inventory cost across single or multi-echelon supply chains.

**Examples** include Netstock, EazyStock, Slimstock (Slim4), ToolsGroup, Lokad, RELEX Solutions, GAINS Systems, Blue Ridge Global, StockIQ, ThroughPut AI, Smart Software, Blue Yonder Inventory Optimization, and Logility (the category leaders).

**Open-source emphasis**: Full commercial-grade inventory optimization suites are rare in pure open source, but excellent libraries, planning engines, and research implementations exist for classical and advanced inventory models. This section is expanded with every major active project useful for building or augmenting optimization capabilities.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Netstock](https://www.netstock.com/)**  
  Cloud inventory optimization platform popular with mid-market distributors and manufacturers for demand forecasting, multi-location replenishment, and policy-driven stock recommendations.

- **[EazyStock](https://www.eazystock.com/)**  
  Cloud-based inventory optimization and replenishment solution aimed at SMBs seeking automated forecasting and order recommendations.

- **[Slimstock (Slim4)](https://www.slimstock.com/)**  
  Inventory optimization software widely used in distribution and wholesale for demand planning, safety stock, and replenishment across multi-echelon networks.

- **[ToolsGroup](https://www.toolsgroup.com/)**  
  Advanced probabilistic demand forecasting and multi-echelon inventory optimization platform focused on service-level driven planning.

- **[Lokad](https://www.lokad.com/)**  
  Quantitative supply-chain optimization platform known for probabilistic forecasting, financial optimization of inventory decisions, and its Envision domain-specific language.

- **[RELEX Solutions](https://www.relexsolutions.com/)**  
  Unified retail and supply-chain planning platform with strong inventory optimization, forecasting, and replenishment capabilities.

- **[GAINS Systems](https://www.gainsystems.com/)**  
  AI-driven supply-chain and inventory optimization platform for complex, multi-echelon environments.

- **[Blue Ridge Global](https://www.blueridgeglobal.com/)**  
  Supply-chain planning and inventory optimization suite focused on demand forecasting, replenishment, and inventory productivity.

- **[StockIQ](https://www.stockiqtech.com/)**  
  Inventory optimization and demand planning software tailored for distributors.

- **[ThroughPut AI, Smart Software, Blue Yonder, Logility](https://throughput.ai/)**  
  Additional enterprise and specialist platforms offering AI-powered or advanced statistical inventory optimization, often as part of broader supply-chain planning suites.

## Open-Source GitHub Projects

- **[Stockpyl](https://github.com/LarrySnyder/stockpyl)**  
  Python package for inventory optimization implementing classical models (EOQ, newsvendor, Wagner-Whitin) and multi-echelon inventory optimization algorithms under stochastic- and guaranteed-service assumptions.

- **[frePPLe](https://github.com/frePPLe/frepple)**  
  Open-source demand forecasting and advanced planning & scheduling (APS) tool for manufacturing. Includes forecasting, production planning, and inventory-related optimization capabilities (Community Edition under MIT).

- **[Multi-Echelon Inventory Optimization projects](https://github.com/anshul-musing/multi-echelon-inventory-optimization)**  
  Simulation-optimization frameworks using discrete-event simulation (SimPy) and black-box optimizers to set inventory policies across multi-echelon networks while meeting service levels.

- **[Inventory Optimization notebooks & scripts](https://github.com/fedinb/Inventory-Optimization)**  
  Educational and practical implementations of safety stock, cycle stock, fill-rate, and cost/service-level optimization inspired by modern inventory optimization literature.

- **[SupplySeer](https://github.com/supplyseer-ai/supplyseer)**  
  Python library for applied computational supply chain, including Bayesian EOQ, probabilistic models, time-series forecasting, and optimization utilities.

- **[ERPNext / Odoo Inventory & MRP](https://github.com/frappe/erpnext)**  
  Fully open-source ERPs with inventory, procurement, and manufacturing modules that can serve as the system of record and be extended with custom optimization logic.

- **[Forecasting + inventory pipelines](https://github.com/search?q=demand+forecasting+inventory+optimization)**  
  End-to-end open-source examples combining demand forecasting (Prophet, LightGBM, Nixtla, etc.) with inventory policy calculation and simulation.

### Additional Strong Open-Source Options

- **Classical OR libraries**: Implementations of EOQ, newsvendor, base-stock, and (s, S) policies in Python, R, and Julia.
- **Time-series forecasting**: Nixtla, Prophet, statsmodels, and related tools used as the demand input to inventory models.
- **Simulation frameworks**: SimPy and other discrete-event tools for testing inventory policies under uncertainty.
- **Optimization solvers**: Open-source solvers (CBC, HiGHS, SCIP) used inside custom multi-echelon or lot-sizing models.
- **Dashboarding**: Streamlit, Dash, or Superset front-ends for visualizing recommended vs. actual stock levels.
- Academic and practitioner repositories focused on **probabilistic inventory**, **multi-echelon theory**, and **service-level optimization**.

**Frameworks for building custom systems**:  
Use **Stockpyl** or custom Python/R code for core inventory calculations (safety stock, reorder points, EOQ).  
Feed demand forecasts from open-source time-series tools.  
Simulate policies with discrete-event simulation before deployment.  
Store master data and transactions in **ERPNext** or **Odoo**, and push optimized parameters back as reorder rules.  
For production planning intensity, evaluate **frePPLe**.  
This stack can deliver substantial value for many mid-sized organizations, though it requires internal analytics and engineering capability.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Inventory optimization directly affects service levels, working capital, and operational risk. Any models (commercial or open-source) should be validated against real demand patterns, lead-time variability, and business constraints before being used for automated ordering.
- Self-built open-source solutions require ongoing data quality management, model monitoring, and domain expertise in supply-chain analytics.

---

**Made for supply-chain analysts, inventory managers, demand planners, and operations research practitioners.**  
Let's make rigorous, transparent inventory optimization more accessible through open tools and methods.
