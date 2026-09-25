# Awesome-Fraud-Detection-Banking

## Top Fraud Detection (Banking) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Real-Time Transaction Fraud, Behavioral Analytics, Account Takeover Prevention & Risk Scoring for Banks & Payments*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Fraud Detection in Banking**. These systems help financial institutions and payment providers detect and prevent payment fraud, account takeover, mule activity, and related financial crime in real time.



**Examples** include Feedzai, Featurespace, FICO Falcon, SAS Fraud Management, DataVisor, Sift, SEON, Fraud.net, BioCatch, and Kount (the category leaders).



**Open-source emphasis**: Production banking fraud platforms are heavily commercial and regulated. Practical open options include transaction-monitoring engines (**Jube**, **Osprey**), graph analytics, and research/ML prototypes. This section lists the strongest available open resources and is realistic about the large commercial and compliance gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Feedzai](https://www.feedzai.com/)**  

  AI-native RiskOps platform unifying fraud detection, AML, and risk operations with real-time scoring and behavioral intelligence for banks and payment processors.



- **[Featurespace](https://www.featurespace.com/)**  

  Adaptive behavioral analytics platform (ARIC) focused on real-time fraud detection with strong false-positive reduction for financial institutions.



- **[FICO Falcon](https://www.fico.com/)**  

  Industry-standard fraud management platform widely used by banks for payment card and transaction fraud detection and decisioning.



- **[SAS Fraud Management](https://www.sas.com/)**  

  Enterprise analytics-driven fraud detection and investigation suite from SAS for banking and financial services.



- **[DataVisor](https://www.datavisor.com/)**  

  AI-powered fraud and risk platform specializing in detecting sophisticated, coordinated fraud rings and account abuse.



- **[Sift](https://sift.com/)**  

  Digital trust and safety platform providing real-time fraud prevention for payments, account takeover, and content abuse.



- **[SEON](https://seon.io/)**  

  Fraud-prevention platform combining device intelligence, digital footprint analysis, and machine learning for fintechs and banks.



- **[Fraud.net](https://www.fraud.net/)**  

  Consortium and AI-based fraud detection platform that leverages shared intelligence across institutions.



- **[BioCatch](https://www.biocatch.com/)**  

  Behavioral biometrics platform focused on detecting account takeover and social-engineering fraud through user interaction patterns.



- **[Kount (Equifax) and related fraud platforms](https://www.example.com/)**  

  Additional enterprise fraud decisioning and identity-risk solutions used in banking and e-commerce payment flows.



## Open-Source GitHub Projects

- **[Jube (AML & Fraud Transaction Monitoring)](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  

  Fully open-source platform for real-time transaction monitoring, hybrid rule + ML detection, case management, and audit trails designed for fraud and AML prevention.



- **[Osprey](https://github.com/opensource-finance/osprey)**  

  Lightweight open-source transaction-monitoring service using CEL rules and typology-style detection—single binary, fast to deploy for rule-based fraud scoring.



- **[Fraud and anomaly detection open ML libraries](https://github.com/)**  

  Community projects and notebooks demonstrating supervised and unsupervised models for transaction fraud scoring and explainability (SHAP, etc.).



- **[Graph and network analytics open tools](https://github.com/)**  

  Neo4j, NetworkX, and related libraries used to model account relationships, device clusters, and collusive fraud rings.



- **[Device and behavioral signal open collectors](https://github.com/)**  

  Open components for capturing device fingerprints, session features, and basic behavioral signals (not a full commercial biometrics suite).



- **[Rule engines and decision open frameworks](https://github.com/)**  

  Open business-rule engines usable for real-time fraud decisioning pipelines.



- **[Case management open workflows](https://github.com/)**  

  Lightweight open systems for queuing, investigating, and documenting fraud alerts.



- **[Feature store and model-serving open stacks](https://github.com/)**  

  Open tools for managing fraud features and serving models in production-like environments.



- **[Explainability and model-governance open tooling](https://github.com/)**  

  SHAP, MLflow, and related projects that support transparent and auditable fraud models.



- **[Documentation and fraud-typology open playbooks](https://github.com/)**  

  Guides and example rule sets aligned with common payment-fraud and ATO scenarios.



### Additional Strong Open-Source Options

- Prototyping real-time monitoring with **Jube** or **Osprey** for rule + ML detection and basic case handling.

- Using open graph databases to explore network structures around high-risk accounts or devices.

- Accepting that production-grade low-latency decisioning, consortium data, behavioral biometrics at scale, model risk management, and examiner-ready audit trails still require commercial platforms (Feedzai, Featurespace, FICO Falcon, SAS, DataVisor, Sift, BioCatch, etc.).

- Focusing open-source efforts on transparency of detection logic, data ownership, and education for fraud-engineering teams.



**Frameworks for building custom systems**: Ingest transactions and customer/device signals → apply open rules and ML scoring (Jube/Osprey or custom) → enrich with graph analytics → route high-risk events to case management → generate investigation narratives. Suitable for research, fintech sandboxes, and internal prototypes. Regulated banks almost always rely on commercial fraud platforms for production risk management.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Fraud detection systems protect customers and institutions from financial loss. Incorrect detection or incomplete controls can create legal, financial, and reputational risk. Open-source tools are **not** a substitute for regulated commercial systems or professional risk programs. This list is not legal, regulatory, or risk-management advice.



---

**Made for fraud, risk, and banking technology teams.**

Let's keep detection smarter, investigations clearer, and core logic as open as practical.
