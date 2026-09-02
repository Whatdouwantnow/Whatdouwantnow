## Hi there 👋

# 🚀 Ludi Zhou

<p align="left">
  <a href="mailto:ludizhou@g.ucla.edu"><img src="https://img.shields.io/badge/Email-ludizhou%40g.ucla.edu-blue?style=flat-square&logo=gmail" alt="Email"></a>
  <a href="https://www.linkedin.com/in/ludi-zhou-349613331"><img src="https://img.shields.io/badge/LinkedIn-Ludi%20Zhou-blue?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Location-Los%20Angeles%20(Open%20to%20Relocate)-orange?style=flat-square" alt="Location">
</p>

---

## 📌 Summary
* **UCLA Master of Data Science in Health** student with strong experience building data-driven applications, software systems, and AI-enabled workflows.
* Skilled in **Python, C++, SQL, Go, and Rust**, with deep interest in developer infrastructure, AI platforms, and software engineering.

---

## 🛠 Technical Skills

| Category | Skills |
| :--- | :--- |
| **Programming** | Python, R, SQL, SAS, C++, Rust, Go |
| **Software Engineering** | OOP, Data Structures & Algorithms, Multithreading, System Design, Git/GitHub, Linux |
| **Data & ML** | Machine Learning, Statistical Modeling & Inference, Data Visualization (Plotly, Streamlit) |
| **Languages** | English (IELTS: 7.5 / GRE: 322), Chinese (Native), French (Basic Conversations), Spanish (Entry Level) |

---

## 💼 Internship Experience

### 🚀 Merit Interactive Co., Ltd. · Alpha Laboratory  
**AI Agent Development Intern** | *Hangzhou, China* | *08/2026 - 09/2026*

* Leveraged the company’s proprietary **Tongren Coding Agent** to drive end-to-end development of a community services platform, spanning **requirements decomposition, architecture design, agent-assisted implementation, automated testing, UI validation, debugging, and performance optimization**.
* Translated a comprehensive software requirements specification into structured development tasks and guided the Coding Agent to implement a **WeChat Mini Program, PC management console, and backend services**, covering identity and community verification, skill certification, task workflows, repair-order matching and claiming, points, volunteer activities, QR-based redemption, settlement, and **RBAC**.
* Established an iterative **Agent generation → automated testing → manual UI smoke testing → defect diagnosis → prompt-driven repair** workflow, identifying and resolving issues involving concurrent order claiming, cross-period task accounting, cross-community authorization, phone-number exposure, transactional settlement, duplicate point rewards, and test-data contamination; expanded the regression suite to **64 passing automated tests** plus browser-level UI flows.
* Improved the reliability of Agent-generated code by driving the implementation of **transactional idempotency, access-control boundaries, sensitive-data encryption/masking, audit logging, atomic points-and-inventory redemption, and repair settlement ledgers**, while optimizing **indexes, lazy loading, parallel requests, pagination, and N+1 queries** to reduce major API latency to **~14–43 ms** and login latency from **~1–1.5 s to ~270 ms**.
* Separated production WeChat dependencies from the development environment by introducing **Mock/Real WeChat authentication providers, token restoration, and environment-based configuration**, enabling full end-to-end demonstrations without production AppID/AppSecret credentials while preserving a clean path for future real WeChat integration.

### 🤖 UCLA Technology Development Group
**AI Agent Platform Intern** | *Los Angeles* | *06/2026 - Present*
* Designed and implemented a namespace-scoped access control layer for a production **Go** message bus serving **40+ autonomous AI agents**, enforcing per-identity pub/sub restrictions across isolated `personal`, `ucla`, and `shared` scopes with denial logging.
* Built a bearer-token identity registry equipped with comprehensive audit logging, tracking every cross-scope access attempt and credential lifecycle event.
* Hardened the **Go** client SDK with environment-based endpoint resolution, exponential backoff with jitter, and idempotency guarantees to ensure **zero message loss** during bus restarts.
* Implemented continuous SQLite replication via **Litestream** to object storage, authoring and executing a full destroy-and-restore drill that proved **sub-minute recovery** from total host failure.
* Authored a structural extraction proof demonstrating that the UCLA agent scope could be migrated to an independent bus instance with **zero client code changes** — requiring only an endpoint URL swap.

### 📊 Wenzhou Oujiangkou Big Data Co., Ltd
**Data Operations Manager Intern** | *Wenzhou* | *05/2024 - 08/2024*
* Cleaned and validated multi-source operational datasets to support business analytics initiatives.
* Conducted qualitative user-behavior analysis and synthesized findings into structured operational reports.
* Collaborated with cross-functional teams to improve reporting consistency and insight communication for internal stakeholders.

### 📡 Zhongxing Telecom Equipment (ZTE) Corporation
**Technology Strategy Intern** | *Shenzhen* | *06/2023 - 08/2023*
* Conducted market and competitive analysis on telecom technology solutions to support pre-bid strategy development.
* Synthesized technical and business findings into presentations for internal stakeholders and external partners.
* Assisted with communication of product capabilities and customer-oriented solution positioning during branding events.

---


## 🎓 Education

* **UCLA Fielding School of Public Health** | MS in Data Science in Health | *Expected 06/2027* | **GPA: 4.0/4.0**
* **The Chinese University of Hong Kong, Shenzhen (CUHKSZ)** | BS in Data Science and Big Data Technology | *Dean's List 2024-2025*

---

<p align="center"><i>Last Updated: September 2026</i></p>
