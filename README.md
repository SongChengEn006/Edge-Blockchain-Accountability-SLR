# Automated Literature Screening Tool for Blockchain-IoT Accountability

## 📌 Project Overview
This repository contains the Python-based automated screening engine used for the Systematic Literature Review (SLR) in the research paper: **"[Blockchain-based smart device security management system]"**. 

The tool is designed to handle large-scale bibliographic data (N=11,100) by implementing a rigorous, algorithm-driven selection process to minimize human bias and ensure study reproducibility.

arget Keywords (Regex) |
| :--- | :--- | :--- |
| **Accountability** | 4.0 | accountability, traceability, provenance, audit, forensics... |
| **Management & UI**| 3.0 | management system, dashboard, gui, visualization, interface... |
| **Technology Stack**| 3.0 | (blockchain/smart contract) AND (iot/edge/fog/sensor)... |


Multi-stage Deduplication: Combines DOI-based exact matching and a custom fuzzy title-cleansing algorithm to eliminate redundant records.
Weighted Scoring Engine: Implements a three-dimensional scoring logic to evaluate papers based on domain-specific relevance.
Automated PRISMA Support: Generates precise statistical counts required for the PRISMA 2020 Flow Diagram.
**Threshold**: Only papers with a total score of **≥ 8.0** are included in the core candidate pool for full-text review.



## 🛠️ Requirements & Installation
- **Language**: Python 3.10+
- **Library**: Pandas >= 2.0.0

To set up the environment:
```bash
pip install pandas
