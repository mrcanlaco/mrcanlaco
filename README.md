<div align="center">

<img src="./assets/hero-banner.svg" alt="Mrcanlaco — Quantitative Systems Architect & Financial ML Engineer" width="100%" />

<br />

[![FreqPilot Studio](https://img.shields.io/badge/LIVE_STUDIO-freqpilot.dev-0ea5e9?style=for-the-badge&logo=prometheus&logoColor=white)](https://freqpilot.dev)
[![PeakPulse AI](https://img.shields.io/badge/ANOMALY_ENGINE-pulse.freqpilot.dev-8b5cf6?style=for-the-badge&logo=databricks&logoColor=white)](https://pulse.freqpilot.dev)
[![Strategy Library](https://img.shields.io/badge/STRATEGY_HUB-strategies.freqpilot.dev-f59e0b?style=for-the-badge&logo=cloudflare&logoColor=white)](https://strategies.freqpilot.dev)
[![FreqPilot Intel](https://img.shields.io/badge/MARKET_INTEL-intel.freqpilot.dev-10b981?style=for-the-badge&logo=cloudflare&logoColor=white)](https://intel.freqpilot.dev)
[![GitHub Followers](https://img.shields.io/github/followers/mrcanlaco?style=for-the-badge&logo=github&label=Follow&color=1e293b)](https://github.com/mrcanlaco)

</div>

---

### ⚡ Executive Overview

I design and engineer **evidence-first quantitative trading infrastructure**, **real-time financial market anomaly detection engines**, and **point-in-time derivatives research platforms**. My work bridges low-latency analytical data pipelines, strict out-of-sample walk-forward validation, and systematic execution governance.

- 🔬 **Quantitative Research & Walk-Forward Validation:** Multi-timeframe orthogonal alpha modeling, strict point-in-time leakage prevention, and 1x paper-trading validation pipelines powered by Official Freqtrade & Rust/Python cores (`freqpilot.dev`).
- 🧠 **Time-Series ML & Anomaly Detection:** High-throughput derivatives microstructure scanning (Funding, Open Interest, Taker Flow), DuckDB analytical pipelines, and calibrated regime/anomaly telemetry (`pulse.freqpilot.dev`).
- 📚 **Verifiable Provenance & Strategy Registry:** Centralized strategy curation, revision auditing, and public-source market provenance tracking (`strategies.freqpilot.dev` & `intel.freqpilot.dev`).

---

### 🚀 Flagship Quantitative Ecosystem (`*.freqpilot.dev`)

| Platform | Live Portal | Architecture & Core Focus | Tech Stack |
| :--- | :---: | :--- | :--- |
| **[freqpilot](https://github.com/mrcanlaco/freqpilot)** | [`freqpilot.dev`](https://freqpilot.dev) | **Quantitative Research, Walk-Forward Validation & Trading Studio**<br/>End-to-end strategy validation lab built on Official Freqtrade 2026.9 with Rust/Python acceleration and Vue UI (1,878+ tests). | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Vue](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[PeakPulse-AI](https://github.com/mrcanlaco/PeakPulse-AI)** | [`pulse.freqpilot.dev`](https://pulse.freqpilot.dev) | **Real-Time Market Anomaly Detection & Time-Series ML Engine**<br/>24/7 derivatives microstructure radar, calibrated frozen ML bundles, and multi-timeframe structural regime telemetry (484+ tests). | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) |
| **Strategy Library** | [`strategies.freqpilot.dev`](https://strategies.freqpilot.dev) | **Consolidated Strategy Registry & Evidence Hub**<br/>Deduplicated quantitative strategy profiles, test revision history, result artifacts, and automated sync on Cloudflare D1 & R2. | ![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![D1 & R2](https://img.shields.io/badge/D1_%26_R2-F38020?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **[freqpilot-intel](https://github.com/mrcanlaco/freqpilot-intel)** | [`intel.freqpilot.dev`](https://intel.freqpilot.dev) | **Evidence-First Research & Market Provenance Workspace**<br/>Public-source intelligence platform with verifiable data provenance, statement comparison, and browser-local research synthesis. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) |

---

### 🏗️ Quantitative Pipeline Architecture

```mermaid
flowchart LR
    subgraph Data["1. Market Intelligence & Telemetry"]
        Intel["🔎 FreqPilot Intel\n(intel.freqpilot.dev)"]
        Pulse["⚡ PeakPulse AI\n(pulse.freqpilot.dev)"]
    end

    subgraph Alpha["2. Curation & Alpha Modeling"]
        StratLib["📚 Strategy Library\n(strategies.freqpilot.dev)"]
        Engine["🧮 Orthogonal Alpha &\nPoint-in-Time Validation"]
    end

    subgraph Exec["3. Walk-Forward & Paper Studio"]
        Studio["📈 FreqPilot Studio\n(freqpilot.dev)"]
    end

    Intel -->|Provenance & Context| StratLib
    Pulse -->|Regime & Anomaly Signals| Engine
    StratLib -->|Audited Strategy Profiles| Engine
    Engine ==>|Out-of-Sample Verified| Studio
```

---

### 🛠️ Technology & Quantitative Stack

<div align="center">

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Core Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Quant, Data & ML** | ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![Freqtrade](https://img.shields.io/badge/Freqtrade-0ea5e9?style=for-the-badge) ![CCXT](https://img.shields.io/badge/CCXT-10b981?style=for-the-badge) |
| **Backend & Cloud Infra** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_D1_%26_R2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Frontend & Telemetry UI** | ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) |

</div>

---

### 📐 Engineering Principles

1. **Evidence Before Execution:** Every quantitative hypothesis is backed by reproducible provenance (`FreqPilot Intel`), strict point-in-time feature construction, and out-of-sample walk-forward audits with zero look-ahead bias.
2. **Orthogonal Signal Design:** Combining uncorrelated multi-timeframe structural factors with calibrated real-time anomaly telemetry (`PeakPulse AI`) rather than curve-fitted indicators.
3. **Fail-Closed Production Discipline:** Hash-verified frozen model bundles, calibrated probability thresholds, and explicit 1x paper-trading validation gates (`FreqPilot Studio`) prior to capital deployment.

---

<div align="center">
  <sub>Engineered with precision by <b><a href="https://github.com/mrcanlaco">mrcanlaco</a></b> • Explore the live suite at <a href="https://freqpilot.dev">freqpilot.dev</a></sub>
</div>
