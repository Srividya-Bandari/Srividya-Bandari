# Hi, I'm Srividya Bandari

Software Engineer with 3+ years building scalable, event-driven distributed systems in C#/.NET and Python on Azure. Architected OPENLANE’s vehicle inspection platform (processed $50B+ in inventory in the trailing 16 months), cut its workflow latency 35%, saved $1.2M annually in Carfax costs and cut arbitration time 37% with a multimodal AI platform.

📍 Seattle, WA · 🌐 [srividyabandari.com](https://srividyabandari.com) · 💼 [linkedin.com/in/srividya-bandari](https://www.linkedin.com/in/srividya-bandari/) · ✉️ srividya.bandari.swe@gmail.com

## Experience

**Software Engineer I & II — OPENLANE** · Jul 2023 – Present · Remote (Austin, TX)
<br><sub>C#/.NET Core, Java (Spring Boot), Python (FastAPI), React, Azure, PostgreSQL, Redis</sub>

- Architected OPENLANE’s unified full-stack inspection platform (C#/.NET backend, React frontend) with 5+ cross-functional teams; in last 16 months Service handled inspections of $50B+ in inventory with over 500K inspections a month at 99.9% uptime.
- Cut inspection workflow latency 35% with async Carfax & VIN-decoding consumers on a config-driven C#/.NET engine; built the React flow from VIN photo to report and shipped with zero downtime via LaunchDarkly-flagged parity runs and end-to-end tests.
- Saved $1.2M a year (8% of Carfax spend) by cutting duplicate report requests across acquired marketplaces: designed, built and launched a unified Carfax service with idempotent deduplication, Redis caching and async callbacks to avoid vendor timeouts.
- Cut average arbitration time by 37% by building an agentic, multimodal AI platform (Python FastAPI backend, Salesforce, Azure AI Foundry) that summarizes and caches case emails, PDFs, images and call recordings for automated review.
- Cut VIN-decoding costs ~20% with my design’s caching and check-digit filters, which stop bad VINs before a paid vendor call, in a self-initiated Java Spring Boot to .NET migration to one vendor-agnostic API for all OPENLANE B2B and B2C clients; raised VIN-decode success from 92% to 98% with a hybrid vendor waterfall, communicated in design and code reviews.
- Restored OBD2 Bluetooth scanner reliability to 98% within a week as on-call engineer: root-caused failures in 40% of one firmware cohort to a vendor SDK incompatibility; built firmware upgrade and recovery workflows into the Android mobile app.
- Owned observability for .NET services on Azure: built Honeycomb metrics, dashboards and alerts, wrote the on-call runbooks for incidents, and led canary rollouts (1% → 10% → 50% → 100%) with automatic rollback on Terraform based Azure infrastructure.

**Research Intern — University Realty / ASU** · May 2022 – Aug 2022 · Phoenix, AZ
<br><sub>Python, SQL, PostgreSQL/PostGIS, Apache Airflow, LightGBM, FastAPI</sub>

- Turned 104 weekly snapshots of 1.17M stores across 3,060 brands into 7.9M store events (38K openings detected) with scheduled Apache Airflow DAGs running Python data pipelines on PostgreSQL/PostGIS.
- Raised top-25 hit rate from 12.9% (store-count baseline) to 45.9% on 3,498 held-out openings by shipping a LightGBM ranking model that predicts which brand opens at a site; it scores ~2,259 brands in 125 ms and retrains weekly behind release gates.

**Software Engineer — Infosys** · Nov 2020 – Jul 2021 · Hyderabad, India
<br><sub>Java, Python, RabbitMQ, Redis, GCP, Docker, Jenkins, Gerrit, Artifactory, OpenSearch</sub>

- Saved 1,000+ build hours a month across 150+ repositories by cutting redundant CI builds 35% and container image duplication 50% with SHA-based change detection and Redis-backed Docker image deduplication on Google Cloud Storage.
- Cut full-pipeline restarts 18% and debugging time ~50% on 1,000+ weekly Gerrit CI jobs with Jenkins/Python retry blocks for transient failures and Artifactory links for multi-GB logs; built log and metrics monitoring for 170+ concurrent builds.

## Projects

- **[RAG Document Q&A System](https://github.com/Srividya-Bandari/rag-doc-qa):** Cut irrelevant answers 40% on a 100-question eval set by building a retrieval-augmented generation pipeline (hybrid FAISS vector search, reranking, OpenAI API) answering questions over PDFs with page citations.
- **Multi-Threaded File System Simulator:** Raised throughput 70% over a single-threaded baseline by building a POSIX-compliant, Unix-style file system in C++ with multi-threaded read/write locks, journaling and inode data structures.

## Technical Skills

- **Languages:** C#, Python, Java, Kotlin, Go, TypeScript, JavaScript, SQL, C++
- **Backend & web:** .NET Core, ASP.NET Core, Spring Boot, FastAPI, REST APIs, OAuth, microservices, React
- **Streaming and pipelines:** Apache Pulsar, Kafka, RabbitMQ, Apache Airflow, Apache Spark, Snowflake, event-driven architecture
- **Cloud:** Azure, Azure DevOps, Azure AI Foundry, AWS, GCP, Kubernetes, Docker, Terraform (IaC), Salesforce
- **Databases:** PostgreSQL, PostGIS, Redis, OpenSearch, Azure Blob Storage
- **DevOps and observability:** Jenkins, CI/CD, Git, Gerrit, Artifactory, LaunchDarkly, OpenTelemetry, Honeycomb, Grafana
- **AI and ML:** agentic workflows, LLMs, generative AI, RAG, vector search (FAISS), CNNs, PyTorch, TensorFlow, LightGBM
- **AI-assisted development:** Claude Code, GitHub Copilot, Cursor

## Education

- **Arizona State University** — Master of Science, Computer Engineering · Aug 2021 – May 2023
- **Osmania University [CBIT]** — Bachelor of Engineering, Electrical and Electronics Engineering · Aug 2016 – Jul 2020
