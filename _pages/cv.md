---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

### [Click here to view the PDF version](files/odesai_resume_apr14_26.pdf)

Education
======
* Ph.D. in Computer Science, Syracuse University, Expected July 2026
* M.S. in Computer Engineering, Stevens Institute of Technology, 2019
* B.E. in Biomedical Engineering, University of Mumbai, 2017


Work Experience
======
* **Research Assistant, S4 Lab, Syracuse University** — August 2020 – Present
  * Researching storage and I/O systems for large-scale ML workloads under [Prof. Bryan Kim](https://sites.google.com/view/bryansjkim/home), supported by NSF grant [CPR for Flash-Based Storage Systems](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2008453).
  * Built **Seneca** (FAST '26): a data preprocessing system for ML training that decouples preparation from training epochs, eliminating I/O bottlenecks and improving end-to-end GPU utilization.
  * Built **Cicero** (EuroMLSys '26): a cost-efficient training and checkpointing framework for large models on preemptible cloud VMs.
  * Developed an open-source remote monitoring tool for SSDs to study performance and reliability under production workloads.
  * Studied key-value stores (LevelDB, RocksDB) at depth, contributing to advances in background I/O scheduling and storage-level indexing.

* **Research Intern, Samsung Semiconductor** — San Jose, CA — May–August 2022
  * Designed and prototyped a task management system for computational storage devices, resulting in US Patent 12,411,630 (granted September 2025).
  * Worked with the Advanced Memory Lab on near-storage compute architectures.

* **Research Intern, Samsung Semiconductor** — San Jose, CA — May–August 2021
  * Designed a two-level indexing architecture for key-value persistent storage devices, resulting in US Patent 11,954,345 (granted April 2024).
  * Prototyped the design on Samsung's key-value SSD platform and evaluated performance against baseline KV-SSD implementations.

* **Software & Data Engineer, Practo Technologies** — June 2019 – September 2020
  * Owned the user behavior and events ingestion pipeline — the backbone of data analytics, ML, and recommendations infrastructure at India's largest telemedicine platform.
  * Deployed and maintained Apache Airflow on Kubernetes; wrote in-house libraries and deployment automation used across the data engineering team.
  * Brought deep visibility into the production Kubernetes cluster using Prometheus and Grafana.
  * Managed a multi-terabyte production database cluster; built data visualization tools for business analysts.

* **Software Engineering Intern, Delos Living** — New York, NY — May–December 2018
  * Designed and built a cloud-native IoT platform for Delos Labs' indoor wellness research program.
  * Developed a data pipeline ingesting from a heterogeneous set of wearables and environmental sensors (~1,000 data points/hour), powering ML models for human stress and sleep research.


Skills
======
* **Research Areas:** Storage Systems, ML Infrastructure & I/O, Key-Value Stores, Distributed Systems, Flash-Based SSDs, Operating Systems
* **Languages:** C, C++, Python, Java
* **Storage & Databases:** LevelDB, RocksDB, NVMe/KV-SSD, Unix File Systems, RAID
* **Infrastructure:** Kubernetes, Docker, Prometheus, Grafana, Nginx
* **Data Engineering:** Apache Airflow, Apache Kafka, Apache Hadoop, Redis
* **Tools:** eBPF/BCC, fio, blktrace, Git


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Service and Leadership
======
* Reviewer, [ACM Transactions on Storage (TOS)](https://dl.acm.org/journal/tos)
* Artifact Evaluation Reviewer, [USENIX NSDI 2026](https://www.usenix.org/conference/nsdi26)
* Artifact Evaluation Reviewer, [USENIX FAST 2025](https://www.usenix.org/conference/fast25)
* Contributor to [Apache Airflow](https://github.com/apache/airflow) — see [pull requests](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3Aswiftomkar+)
* Contributor to [iovisor/bcc](https://github.com/iovisor/bcc) — see [pull requests](https://github.com/iovisor/bcc/pulls?q=is%3Apr+author%3Aswiftomkar+)
