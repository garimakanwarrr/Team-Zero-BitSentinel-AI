# 🛡️ BitSentinel AI &mdash; Guarding Every Bitcoin Transaction

<div align="center">

[![Python Version](https://img.shields.io/badge/python-3.10%20%7C%203.14-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688.svg?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Bitcoin Telemetry](https://img.shields.io/badge/Blockchain-Bitcoin%20Mainnet-f7931a.svg?logo=bitcoin&logoColor=white)](https://bitcoin.org/)
[![AI Ensemble](https://img.shields.io/badge/AI-Multi--Vector%20XAI%20Ensemble-00f0ff.svg)](#-ai--ml-anomaly-detection-engine)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Team](https://img.shields.io/badge/Built%20By-Team%20ZERO-8b5cf6.svg)](#-team-zero-credentials)

**Hackathon Challenge:** AI Powered Monitoring & Analysis of Bitcoin Transaction Traffic  
**Built by:** **Team ZERO** | **Team Leader:** **Garima Kanwar & Members**

[Key Features](#-core-solutions) • [Architecture](#-system-architecture) • [Quick Start](#-quick-start--installation) • [API Reference](#-api-endpoints) • [Team ZERO](#-team-zero-credentials)

</div>

---

## 📌 Executive Summary

**BitSentinel AI** is an autonomous cyber-defense and intelligence platform designed to monitor, detect, analyze, and visually trace anomalous and illicit transaction flows across the Bitcoin blockchain in real time.

Engineered with a high-tech cyberpunk HUD aesthetic, BitSentinel AI equips security analysts, financial compliance officers, and law enforcement units with state-of-the-art heuristic and Machine Learning ensembles to safeguard the Bitcoin network against money laundering, ransomware exfiltration, and obfuscation tumblers.

---

## 🚀 The Three Core Solutions + Enterprise Admin Portal

### 1. 📊 Bitcoin Transaction Monitoring & Analytics Dashboard
* **Live Mempool Stream:** Real-time ingestion and analysis of Bitcoin transactions with microsecond timestamps, dual-currency valuation (BTC & USD), sat/vB fee density, and dynamic confirmation counts.
* **Dynamic HUD KPI Counters:** Live tracking of Bitcoin price, network velocity (TPS), mempool congestion, priority fee rates, and 24h AI Threat Index.
* **Dual-Axis Interactive Charts (Chart.js):**
  * 12-Hour Volume Flow Velocity vs. Flagged Anomaly Count.
  * Risk Classification Distribution (Low, Medium, High, Critical).
* **Interactive Threat Injection Engine:** 1-click test simulation buttons:
  * `+ Inject Peeling Chain`
  * `+ Inject Wasabi Mixer`
  * `+ Inject AML Smurfing (<$10k)`
  * `+ Inject Micro-Dust Probe`

### 2. 🧠 AI-Powered Anomaly Detection & Risk Forensics
* **Multi-Vector ML & Heuristic Ensemble:**
  * **Peeling Chain Signature Detector:** Detects rapid multi-hop UTXO peeling where >90% of value returns as asymmetric change.
  * **CoinJoin / Mixer Fingerprinting:** Unmasks equalized multi-party inputs/outputs typical of Wasabi Wallet and ChipMixer.
  * **Anti-Smurfing Structuring Filter:** Detects transactions strategically placed right under regulatory AML reporting thresholds (\$10,000 USD / ~0.14-0.15 BTC).
  * **Micro-Dust De-Anonymization Detector:** Flags micro-UTXO transfers (<546 satoshis) aimed at breaking wallet anonymity.
  * **Threat Intelligence Blacklist:** Correlation with known threat actors (Conti Ransomware, Hydra Darknet, Lazarus Group).
* **Radial Risk Score Gauge (0–100):** Visual threat indicator with dynamic color transitions (Emerald $\rightarrow$ Amber $\rightarrow$ Crimson).
* **Explainable AI (XAI) Waterfall:** SHAP-inspired feature attribution scores explaining the exact weight of each detected factor.
* **Automated Regulatory Countermeasure Statements:** Recommends concrete actions (Mempool freeze requests, FinCEN SAR filings, or standard clearance).

### 3. 🌐 Bitcoin Transaction Network Visualization & Relationship Analysis
* **Force-Directed Physics Topology Canvas:** High-performance HTML5 Canvas simulation with gravitational clustering, pan, and zoom controls.
* **Animated Satoshi Particle Vectors:** Visual glowing particles traveling along transaction edges, rendering live economic flow between wallets.
* **Role-Based Entity Nodes:**
  * 🔴 **Sanctioned / Darknet Entity** (Conti, Hydra, Lazarus)
  * 🟣 **Wasabi / CoinJoin Mixer Hubs**
  * 🟡 **Peeling Chain UTXO Hops**
  * 🔵 **Institutional Exchange Vaults** (Binance, Coinbase, Kraken)
  * 🟠 **Whale Wallets**
  * 🟢 **Retail Merchants & Users**
* **Interactive Node Dossier Inspector:** Click any wallet node to view balance, total transactions, cluster risk level, and adjacent connection graph.

### 4. 🏢 Enterprise Admin Portal & Organization Datafile Analyzer
* **Multi-Tenant Authentication & RBAC:** User login, registration, and role management stored in SQLite.
* **1-Click Quick Demo Login:** Instantly authenticate as **Garima Kanwar (Team ZERO)** or **Lead Admin**.
* **Datafile Ingestion Center:** Drag-and-drop file upload for custom organization logs in `.csv` or `.json` formats.
* **Automated Batch AI Scanner:** Processes multi-row datasets with Pandas/Python, detects anomalies, calculates average risk score, and generates executive summaries.
* **Preloaded Sample Datasets:** Includes ready-to-test enterprise CSV and JSON transaction logs.
* **Compliance Audit Report Exporter:** Download comprehensive audit reports in JSON format for compliance and regulatory reporting.

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                             FRONTEND LAYER (SPA)                            │
│  - HTML5 Canvas Physics Force Engine (Custom Force-Directed Graph)          │
│  - Animated Satoshi Particle Flow Vectoring                                 │
│  - Chart.js Neon Telemetry (Dual-axis Volume & Anomaly Velocity)            │
│  - Web Audio API Synthesizer (Dynamic cyber alarm & telemetry bleeps)       │
│  - Responsive Cyber-Engineering HUD Glassmorphism (CSS3 Variables)          │
└──────────────────────────────────────┬──────────────────────────────────────┘
                                       │ REST APIs / JSON
┌──────────────────────────────────────▼──────────────────────────────────────┐
│                            BACKEND ENGINE (FastAPI)                         │
│  - main.py: High-throughput asynchronous routing (Python 3.14 + Uvicorn)    │
│  - Session/RBAC Authentication & Organization Tenant Isolation              │
│  - Real-Time Mempool Stream Generator & Telemetry Oracle                    │
└──────────────────────────────────────┬──────────────────────────────────────┘
                                       │
         ┌─────────────────────────────┴─────────────────────────────┐
         ▼                                                           ▼
┌──────────────────────────────────┐        ┌─────────────────────────────────┐
│     AI & ML ANOMALY ENGINE       │        │       PERSISTENCE LAYER         │
│  - Isolation & Statistical Logic │        │  - SQLite3 (sentinel.db)        │
│  - Peeling Chain Asymmetry Ratio │        │  - Users & Organizations Table  │
│  - CoinJoin Entropy Fingerprint  │        │  - Datasets Metadata Table      │
│  - AML Structuring Smurfing Rule │        │  - Analyzed Transactions Table  │
│  - Micro-Dust Attack Heuristic   │        │  - Automated Audit JSON Exporter│
│  - Blacklist Threat Intel Match  │        └─────────────────────────────────┘
│  - SHAP Explainability & Recs    │
└──────────────────────────────────┘
```

---

## ⚡ Quick Start & Installation

### Prerequisites
* Python 3.10 or higher installed on your system.

### 1. Clone the Repository
```bash
git clone https://github.com/GarimaKanwar/Team-Zero-BitSentinel-AI.git
cd Team-Zero-BitSentinel-AI
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
**On Windows:**
Double-click `run.bat` or run:
```bash
python -m uvicorn main:app --host 127.0.0.1 --port 8000 --reload
```

**On Linux / macOS:**
```bash
uvicorn main:app --host 127.0.0.1 --port 8000 --reload
```

### 4. Access the Platform
Open your browser and navigate to:
```
http://127.0.0.1:8000
```

---

## 🔌 API Endpoints Reference

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/` | Web HUD Interface (HTML5 Single Page App) |
| `GET` | `/api/telemetry/stats` | Real-time Bitcoin Price, Mempool Backlog, and Network TPS |
| `GET` | `/api/telemetry/charts` | 12h Volume and Anomaly Velocity Chart time-series |
| `GET` | `/api/telemetry/live-stream` | Batch of live analyzed Bitcoin transactions |
| `GET` | `/api/telemetry/single-stream` | Streams next transaction (supports `?forced_type=`) |
| `POST`| `/api/ai/analyze-transaction` | Submits custom transaction parameters for instant AI scoring |
| `GET` | `/api/ai/preset-scenarios` | Returns high-risk pre-configured attack scenarios |
| `GET` | `/api/network/graph-data` | Complete topological node-link graph with metadata |
| `GET` | `/api/network/trace-address/{addr}` | Isolates and traces a specific address subgraph |
| `POST`| `/api/auth/register` | Registers a new organization and analyst profile |
| `POST`| `/api/auth/login` | Authenticates credentials and returns user session |
| `POST`| `/api/admin/upload-dataset` | Ingests CSV/JSON datafiles and triggers batch AI scanning |
| `POST`| `/api/admin/load-sample` | 1-Click loading of pre-built enterprise sample dataset |
| `GET` | `/api/admin/datasets` | Lists all analyzed organization datasets |
| `GET` | `/api/admin/datasets/{id}/export` | Generates downloadable JSON compliance audit report |

---

## 👥 Team ZERO Credentials

* **Hackathon Title:** AI Powered Monitoring & Analysis of Bitcoin Transaction Traffic
* **Team Name:** **Team ZERO**
* **Team Leader:** **Garima Kanwar & Members**
* **Project Name:** **BitSentinel AI**
* **Tagline:** *Guarding Every Bitcoin Transaction*

---

## 📄 License

This project is licensed under the MIT License &mdash; see the [LICENSE](LICENSE) file for details.
