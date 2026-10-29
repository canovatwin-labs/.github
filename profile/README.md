<div align="center">

# CanovaTwin Labs

### Industrial Digital Twin & Hierarchical Multi-Agent AI Research
**Bridging Software Engineering, Reduced-Order Thermodynamics, and Autonomous Agent Intelligence for Mission-Critical Infrastructure**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Python 3.12+](https://img.shields.io/badge/Python-3.12%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115%2B-009688?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com/)
[![LangGraph](https://img.shields.io/badge/Orchestration-LangGraph-orange?style=flat-square)](https://langchain-ai.github.io/langgraph/)
[![Architecture: 7--Layer](https://img.shields.io/badge/Architecture-7--Layer_Modular_OT/IT-success?style=flat-square)](#-architectural-pillars)
[![Security: NIST SP 800--82](https://img.shields.io/badge/Security-NIST_SP_800--82_OT_Compliant-red?style=flat-square)](https://csrc.nist.gov/pubs/sp/800/82/r3/final)

</div>

---

## 🏛️ Executive Summary

**CanovaTwin Labs** is an applied engineering research and open-source R&D laboratory dedicated to mission-critical data center cooling, environmental telemetry intelligence, and autonomous decision support. 

Our flagship initiative, **[CanovaTwin X](https://github.com/canovatwin-labs/canovatwin-x)**, combines:
1. **First-principles thermal digital twins** modeling CRAC (*Computer Room Air Conditioning*), In-Row precision cooling, and dynamic IT heat loads.
2. A **hierarchical multi-agent network (36 specialized agents organized across 6 squads)** orchestrated through deterministic state-machines and directed acyclic graphs (DAGs).
3. **Rigorous evidence verification and ablation tracking**, ensuring every root-cause hypothesis is verified against sensor telemetry, thermal physics simulations, or indexed technical manuals before reaching an operations engineer.

---

## 🔭 Research & Innovation Pillars

```
+-----------------------------------------------------------------------------------+
|                            CANOVATWIN LABS ECOSYSTEM                             |
+-----------------------------------------------------------------------------------+
|  L7 | Presentation & Workbench  : React + TypeScript, Vite, Dynamic Telemetry UI |
|  L6 | Multi-Agent Orchestration : LangGraph, Global Supervisor, 36 Agents (6 Squads) |
|  L5 | Physics Digital Twin      : Reduced-Order Energy Balance & What-If Engine   |
|  L4 | Unified Data Platform     : PostgreSQL, pgvector (RAG), Time-Series Ingestion|
|  L3 | Industrial Gateway        : OPC UA / Modbus Read-Only OT Protocol Adapters   |
|  L2 | Deterministic Control     : HVAC Closed-Loop Algorithms & Virtual PLC Logic |
|  L1 | Physical / Virtual Assets : Precision Cooling Units, Rack Heat Load, Sensors|
+-----------------------------------------------------------------------------------+
```

### 1. Physics-Grounded Digital Twins
Rather than treating deep learning models as ungrounded black boxes, CanovaTwin binds multi-agent reasoning to a continuous physical energy balance:
$$C \frac{dT}{dt} = Q_{\text{IT}} + Q_{\text{ambient}} - Q_{\text{cooling}}$$
Hypotheses generated during anomaly investigations are executed through **what-if simulation runs** to determine if simulated physics match empirical sensor anomalies.

### 2. 36-Agent Hierarchical Collective
Our catalog is structured into six functional squads led by Group Supervisors and a Global Supervisor:
- **Group A — Sensor & Data Intelligence (`A01`–`A06`)**: Signal validation, drift detection, sensor fusion, missing data analysis.
- **Group B — Fault Diagnosis & Root Cause (`B01`–`B06`)**: Anomaly investigation, multi-hypothesis generation, historical case matching, hypothesis critic.
- **Group C — Maintenance & Reliability (`C01`–`C06`)**: Component health, failure risk projection, spare parts estimation, maintenance history synthesis.
- **Group D — Digital Twin & Simulation (`D01`–`D06`)**: What-if scenario design, thermal analysis, energy optimization, model parameter calibration.
- **Group E — PLC & Software Verification (`E01`–`E06`)**: Static control code analysis, change impact assessment, test generator, isolated simulation execution.
- **Group F — Technical Knowledge & Reporting (`F01`–`F06`)**: RAG manual retrieval, mathematical evidence verification, structured engineering reports.

### 3. Strict Evidence Attribution & Guardrails
- **Zero Hallucination Tolerance**: LLM assertions must be backed by verifiable `evidence_ids`.
- **Ablation-Driven Research**: Empirical benchmarking of $E_0$ (Rule-based), $E_1$ (Single LLM), $E_2$ (6 agents), $E_3$ (12 agents), $E_4$ (24 agents), and $E_5$ (36 agents).
- **OT Safety Isolation**: Follows **NIST SP 800-82** and **NIST AI RMF** guidelines; autonomous agents are restricted to read-only decision support without direct control-override authority.

---

## 📂 Primary Repositories

| Repository | Status | Focus Area |
| :--- | :---: | :--- |
| **[`canovatwin-x`](https://github.com/canovatwin-labs/canovatwin-x)** | 🚀 Active | Core platform: Digital Twin, Agent Runtime, Telemetry Engine, and Operator Workbench. |
| **`.github`** | 📌 Maintained | Organization-level documentation, profile standards, and workflow templates. |

---

## 🛠️ Technology Stack & Standards

- **Core & Runtime**: Python 3.12+, Pydantic v2, FastAPI (Async ASGI)
- **Agent Orchestration**: LangGraph, Deterministic State Machines, OpenTelemetry Tracing
- **Data & Vector Storage**: PostgreSQL 16, pgvector, SQLAlchemy 2.0, Alembic
- **Digital Twin & Numerics**: NumPy, SciPy, Scikit-learn, BOPTEST/LBNL FDD Datasets
- **Frontend & Visualization**: React 18, TypeScript, Tailwind CSS, Recharts / Plotly
- **Industrial Networking**: OPC UA (AsyncUA), Modbus TCP (Pymodbus), Virtual PLC Emulators

---

## 🎓 Academic & Industrial Partnership

CanovaTwin Labs bridges academic graduation research with real-world enterprise engineering:
- **Academic Capstone (Ekim 2026 – Ocak 2027)**: Self-contained simulation platform, benchmarked against Lawrence Berkeley National Laboratory (LBNL) datasets and verifiable synthetic thermal chambers.
- **Industrial Co-Op / İME (Şubat 2027+)**: Read-only integration with Canovate Elektronik precision cooling equipment, industrial controller testbeds, and operational telemetry streams.

---

## 📜 Governance & License

All open-source software published under CanovaTwin Labs is licensed under the [MIT License](https://opensource.org/licenses/MIT).

- **Contribution Guidelines**: Please review our [Code of Conduct and Contribution Guidelines](https://github.com/canovatwin-labs/canovatwin-x/blob/main/CONTRIBUTING.md).
- **Security Inquiries**: For vulnerability disclosures or OT safety questions, refer to our [Security Policy](https://github.com/canovatwin-labs/canovatwin-x/blob/main/SECURITY.md).

<div align="center">
<sub>© 2026 CanovaTwin Labs. Built for resilient, explainable, and sustainable infrastructure engineering.</sub>
</div>
