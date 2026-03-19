# Eduardo José Moreno

**Software Architect | Blockchain/Web3 · Backend Python · Full Stack | +20 years of experience | LATAM · Spain**  
📍 Buenos Aires, Argentina · 🌎 Available for remote projects in LATAM & Spain  
✉️ eduardomoreno2503@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/eduardo-moreno-15813b19b)

---

## About Me

Software architect with **20+ years of experience** in critical systems — combining high-level technical execution with real business vision.

I don't just write code — I deliver **production systems**. From a DEX on Ethereum with verified contracts on Sepolia and >95% test coverage, to a live Flask web application at [tradicom.com.ar](https://www.tradicom.com.ar), to a real-time BI dashboard currently driving strategic decisions at a wholesale distribution company with 17+ years of operational history.

- 🎓 **B.S. in Computer Systems** — Universidad Católica Argentina (UCA), 1993  
- 📊 **MBA (1st year)** — Universidad Politécnica de Madrid, 2000  
- 🏢 Currently: **IT & Operations Manager** at Microbell S.A., Buenos Aires

---

## Tech Stack

### ⛓️ Blockchain / Web3
`Solidity` `Cairo` `Hardhat` `Ethers.js` `Web3.js` `Ethereum` `Starknet L2` `DeFi Protocols` `Smart Contract Security Auditing` `MetaMask`

### 🐍 Backend Python
`Flask` `FastAPI` `TensorFlow` `Pandas` `openpyxl` `ReportLab` `REST APIs`

### 🌐 Full Stack
`HTML` `CSS` `JavaScript` `Node.js` `SQL`

### 🏢 Enterprise Systems
`ERP Flexxus` `Power BI` `RRHH Management` `Delphi` `Object Pascal` `COBOL`

---

## Featured Projects

### 🔄 [SimpleSwap DApp](https://github.com/edumor/simpleswap-dapp)
Decentralized exchange (DEX) built on Ethereum. Smart contracts verified on Sepolia testnet, >95% test coverage with Hardhat. Full DeFi swap flow with Ethers.js frontend integration.

### 🔒 [ETH Kipu Security Analysis](https://github.com/edumor/eth-kipu-modue5-secutiry-analysis)
Smart contract security audit and vulnerability analysis. Module 5 of the ETH Kipu Ethereum Developers Pack — focused on reentrancy, access control, and common attack vectors in Solidity.

### 🏗️ [Starknet Resolve Hackathon](https://github.com/edumor/starknet-resolve-hackathon)
Hackathon project on Starknet L2 using Cairo. Explores ZK-rollup architecture and L2 scalability patterns for DeFi use cases.

### 🌐 [Tradicom Flask](https://github.com/edumor/tradicom-flask)
Live Flask web application deployed at [tradicom.com.ar](https://www.tradicom.com.ar). Full backend/frontend integration, REST API, production deployment.

### 📊 [Microbell Dashboard](https://github.com/edumor/edumor.github.io)
Real-time BI dashboard (Chart.js) actively used for strategic decision-making at Microbell S.A. Covers sales, costs, replenishment, and P&L — built as a single-file HTML application deployed on GitHub Pages.

### 🏷️ [Microbell Juguetería — Competitive Pricing BI](https://github.com/edumor/Microbell-Jugueteria)
End-to-end Business Intelligence system for competitive pricing analysis on Mercado Libre Argentina — **Toy Line, Top 30 SKUs by stock (41,801 units)**.

**What it solves:** Aligning Microbell's e-commerce publication prices with real market data, ensuring every listing covers the full operational cost of the ML channel while maximizing competitive positioning.

**Data pipeline:**
- Ingests two internal sources: a CSV stock file (latin-1, semicolon-separated) and an XLSX wholesale price list with Excel formulas (`openpyxl data_only=True` to resolve cached values)
- Cross-references by SKU (5-digit code) to produce a unified pricing dataset
- Applies a 9-step pricing chain: Purchase Cost → Operational Floor (+50%) → Wholesale List → Current ML Price (×1.80) → Competitor Scraping → Optimal Competitive Price (`MAX(competitor × 0.85 ; floor × 1.20)`)

**Competitive intelligence:** Web scraping of competitor sites (Google-indexed, since ML uses JS rendering that blocks direct extraction). Confirmed prices from 10 active ML sellers across 8 product categories.

**Outputs — 3 interactive HTML dashboards + PDF report:**
- `dashboard_precios_optimos_jugueteria_microbell.html` — 30-SKU comparison table, 7 KPIs, bar charts, category filters, alerts
- `analisis_competitivo_ml_jugueteria_microbell.html` — Competitor breakdown by category with vendor tier (Platinum/Gold/Standard)
- `dashboard_rentabilidad_jugueteria_microbell.html` — Full methodology chain, profitability actual vs. optimal, gain-per-unit and uplift analysis
- `informe_metodologia_precios_jugueteria_microbell.pdf` — Executive report with methodology, findings and recommendations

**Key findings:** Average current profitability 190% over operational floor → recommended optimal pricing raises it to 232%, representing an additional **+$113M ARS** in projected margin on existing stock (+27.7%).

**Stack:** Python · pandas · openpyxl · HTML/CSS/JS · Chart.js · ReportLab (PDF generation)

### 🏛️ [Subasta (Auction System)](https://github.com/edumor/Subasta)
Online auction platform. Full-stack development with business logic for bid management, user flow, and state control.

### 🐍 [Proyecto Integrador](https://github.com/edumor/proyecto-integrador)
Full-stack Python integrator project. Backend API with database integration and frontend interface.

---

## Certifications

| Credential | Issuer | Year |
|---|---|---|
| Power BI | Buenos Aires / Agencia de Habilidades para el Futuro | 2026 |
| Talento Tech · Power BI | Ministerio de Educación CABA | 2026 |
| Ethereum Developers Pack | ETH Kipu | 2025 |
| Introducción a Smart Contracts | Talento Tech & ETH-KIPU | 2025 |
| Codo a Codo 4.0 · Full Stack Python | Ministerio de Educación CABA | 2024 |
| Python Avanzado | Talento Tech · Ministerio de Educación CABA | 2024 |
| Iniciación a la Programación con Python | Agencia de Habilidades para el Futuro | 2024 |

---

## Professional Background

**20+ years** across enterprise, financial, and telecom sectors:

- **Microbell S.A.** *(2008 – present)* — IT Manager, HR & Operations. ERP implementation (Flexxus), systems development in Delphi, Power BI reporting, payroll management.
- **Got S.A.** *(2003 – 2008)* — Business Development Manager. Built a full in-house management system in ObjectPal/Paradox covering sales, stock, accounts, and reporting.
- **Tecnoconsult S.A.** *(1993 – 2002)* — Administrative & Financial Director. Led a 600-person organization across 32 branches as Official Telecom S.A. Agent.
- **ABAPRA** *(1985 – 1993)* — Systems Developer & HR Administrator. Delphi development for banking data processing and administrative systems.

---

## GitHub Stats

![Eduardo's GitHub Stats](https://github-readme-stats.vercel.app/api?username=edumor&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

---

> *"The future is decentralized — and it runs on production-grade code."*
