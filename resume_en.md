# Qiuzhuang Wang

**Desired Roles:** JAVA Development Engineer | Backend Architecture Engineer | AI & AIOps Engineer
**Contact:** +86 135-2013-1421 | **Email:** 13520131422@163.com

---

## 🎯 Career Objectives
* **Target Positions:** JAVA Development Engineer | Backend Systems Engineer | AI / AIOps Engineer
* **Preferred Location:** Nationwide (Open to both Domestic and Overseas opportunities)
* **Expected Salary:** Negotiable / Open to discussion
* **Employment Type:** Full-time (Experienced Professional)

---

## 🚀 Core Qualifications
* **Domain Expertise in Fintech & Consumer Finance:** 7 years of deep cultivation in core financial accounts and credit loan systems. Proficient in complex business models (accounting, payments, clearing, and settlement) for joint loans, syndicated loans, and diverse self-operated/channel assets. Experienced in managing 100M+ level online data and building system stability under high-concurrency scenarios.
* **Global Perspective & Cross-Cultural Communication:** Benefiting from an overseas educational and living background, possessing an open mindset and a broad vision. Outstanding cross-cultural communication skills with strong empathy. Adept at a "communication-first" methodology in technical leadership; successfully led the integration of 10+ top-tier channel assets, demonstrating top-tier cross-functional collaboration and delivery capabilities.
* **Hardcore System Tuning & Performance Governance:** Proven track record in system stability governance and extreme performance tuning. Led and core-contributed to high-impact campaigns: reduced core DB Slow SQLs from 20K+ to 100+ daily (99% reduction), slashed core API TP99 latency from 3000ms to <200ms (93% reduction), and compressed master-slave replication lag from 3000s to <10s (99% reduction).
* **AI-Driven Full-Stack Development & Innovation:** Highly proficient in leveraging cutting-edge AI-assisted programming and engineering tools (such as Claude code, Gemini, DeepSeek) to achieve rapid product prototyping and high-productivity Lean development.
    * **Independent Full-Stack Milestone:** Independently developed and currently operating a robust API relay platform featuring multi-channel upstream/downstream distribution and dynamic Redis-based billing controls via AI-assisted engineering.
    * Successfully developed and deployed a personal travel blog website and multiple WeChat Mini-Programs using AI. Managed the complete lifecycle from product ideation, architectural design, frontend coding, Cloud Functions script writing, to independent operations, successfully integrating Google AdSense for automated monetization.
    * Beyond rapid prototyping, possesses practical expertise in embedding AI core technologies with distributed architectures to drive production-grade financial account systems.

---

## 💼 Professional Experience

### Mashang Consumer Finance Co., Ltd.
**JAVA Development Engineer | Core Financial R&D Department**  
*Aug 2019 - Present*

Positioned within the Asset Team of the Account & Settlement Group under the Core Credit Line Product Development Department. Responsible for asset party integration, account system architectural iterations, and online stability governance. Supporting the smooth operation of 90M+ registered users and 600M+ RMB daily loan disbursements.

* **Asset Integration & Architectural Iterations**
    * Led integration projects for major asset platforms including Fenqile (Leka) and Sogou Finance; abstracted hundreds of distinct business rules into standardized adapters, onboarding 10+ asset channels and driving an annual loan growth of 20B+ RMB.
    * Spearheaded the microservice migration and architectural transformation of Ctrip's "Jiequhua" service; decoupled a massive monolithic application into 6 independent microservice modules, cutting average API latency by 40% and elevating system availability to 99.99%.
    * Maintained and iteratively upgraded 34 core account microservices; implemented sharding (database/table splitting) based on ShardingSphere, efficiently handling 1M+ daily account transactions with a 100% distributed transaction consistency rate.
* **Stability Governance & Performance Tuning**
    * Utilized JVM tuning utilities (`jstat`, `map`) to diagnose and resolve memory leak anomalies; optimized GC strategies for high-volume entry bookkeeping, compressing batch job execution windows from 4 hours to 1.5 hours (a 60% throughput boost).
    * Constructed a multi-level Redis caching architecture and optimized hot-parameter query logic, increasing core API QPS by 3x and lowering DB read pressure by 70%.
    * Served as the designated Incident Commander for account system anomalies and batch monitoring, establishing an agile MTTR framework that reduced average online incident resolution times to under 15 minutes, maintaining a zero major asset loss record.
* **Process Optimization & Efficiency Enhancement**
    * Led the standardization of financial reconciliation troubleshooting and engineered an automated reconciliation verification toolkit, boosting data discrepancy correction efficiency by 50% and recovering over 10M RMB in un-reconciled variance.

### Meili Financial Group
**Backend Development Engineer | R&D Center**  
*Jul 2018 - Jun 2019*

Core member of the Capital Channels Group within the Financing Platform Technical Center. Managed the development and maintenance of interaction systems between the group and third-party financial institutions, securing capital liquidity for Automotive Finance, Youyong Fenqi, and Micro Cash Loans.

* **Capital Channel Integration & R&D**
    * Successfully integrated 6 commercial banks (including ICBC and Minsheng Bank) and P2P capital partners; independently developed end-to-end APIs for account opening, credit assessment, loan requisition, and repayment, smoothly channeling over 15B RMB while maintaining 99.95% channel availability.
    * Engineered a centralized gateway configuration manager powered by Redis, converting business constants and routing rules into dynamic configurations, reducing unnecessary production deployments by 30+ occurrences annually and minimizing release risks.
    * Chaired the R&D of the capital provider image management system, automating the upload, storage, and parsing of KYC/contract images, which trimmed manual processing overhead by 60% and secured a 99.9% document processing accuracy rate.
* **Architecture Modernization & Continuous Integration**
    * Promoted an SOA architecture refactoring utilizing Dubbo and Zookeeper, splitting a monolithic gateway into 7 decoupled services, enhancing system scalability by 50% and eliminating 30% of interface latency.
    * Established an automated testing infrastructure utilizing Docker and Jenkins, empowering the QA team with continuous integration (CI/CD) pipelines, slashing test environment deployment cycles from 1 day to 2 hours (a 40% efficiency gain).
    * Standardized development workflows (design reviews, code walk-throughs, strict self-test criteria) across a 10-engineer team, dropping code defect rates by 45% and raising on-time project delivery to 95%.

---

## 💻 Project Highlights

### Account System Intelligent Inspection AI Agent Project
*Feb 2018 - Feb 2018*  
**Role:** AI Engineer / Backend Architect  
* **Background:** The core account system of Mashang Consumer Finance faced extreme challenges under high-concurrency traffic and massive data loads. Traditional manual monitoring fell short in detection speed and coverage for Slow SQLs, API bottlenecks, and sub-healthy server instances, risking production stability. An automated, intelligent inspection and early warning system was urgently required.
* **Objectives:** Develop an AI Agent-driven intelligent inspection robot capable of cross-dimensional auto-monitoring, real-time risk identification, and proactive alerting to replace manual inspection, maximizing system uptime and operations efficiency.
* **Challenges:** Overwhelming monitoring vectors making manual coverage impossible; delayed hazard tracking blocking proactive warning; prolonged root-cause analysis during live outages.
* **Key Contribution (Action):**
    * Deeply integrated the self-developed AI Agent inspection robot with the core account system's logging pipelines and DB logs, breaking through engineering barriers to deploy autonomous inspection, intelligent discovery, and proactive alerting.
    * **Cross-Dimensional Automated Inspection:** Monitored vital metrics including Slow SQL anomalies, high-latency APIs, instance health states, DB workloads, master-slave replication lag, and middleware availability on a minute-level trigger interval with zero human intervention.
    * **AI-Driven Risk Discovery:** Leveraged machine learning models trained on historical operational telemetry and anomalous indicators to dynamically forecast hidden performance degradation, instance deviations, and potential microservice health hazards.
    * **Proactive Alerting & RCA:** Designed an instant alerting mechanism via multiple notification channels when anomalies emerge, combined with AI Root Cause Analysis (RCA) algorithms to isolate the root fault vector within seconds and output optimal tuning prescriptions.
* **Results:** Secured 7×24 automated headless monitoring via the AI Agent, eliminating manual inspection overhead by 100%. Advanced hazard discovery windows by 10–15 minutes compared to legacy alerting, driving a 65% reduction in production incident occurrences. Accelerated root-cause analysis by 70%, fully safeguarding the absolute stability of the core financial architecture.

### Mashang Consumer Finance Core Account System Architectural Transformation Campaign
*Feb 2018 - Feb 2018*  
**Role:** Core Java Development Engineer  
* **Background:** This system serves as the foundational bedrock of the company’s fintech ecosystem, managing core ledger records and virtual card accounts for tens of millions of users with over 600M RMB in daily loan volume. It delivers high-concurrency account API services to B-end partners, C-end users, and hundreds of internal downstream systems. Furthermore, it must precisely complete large-scale batch processing (such as general ledger cross-checking and interest accrual) during EOD (End of Day), necessitating rigorous data consistency and extreme performance.
* **Technical Challenges & Strategic Solutions:**
    * *Business Extensibility:* Faced with intricate upstream and downstream connections, decoupled and refactored channel/product onboarding into modular templates and configurations, ensuring rapid grid entry for new assets.
    * *End-to-End Observability:* Addressing a critical lack of centralized monitoring dashboards, built comprehensive observability cockpits tracking both business dimensions (card issuance, loan payout, repayment trends) and infrastructure layers (CPU, I/O, memory, QPS, TPS, tablespace allocation).
    * *Extreme Performance Optimization:* Targeting historical pain points where single tables exceeded 300M rows and batch jobs drove CPU utilization to 100%, launched a top-to-bottom performance optimization campaign.
* **Tuning Execution & Performance Optimization:**
    * **Eradicating Slow SQLs:** Deployed a tactical roadmap combining "Precise Positioning + Deep Index Tuning + Logic Decoupling + Complex Code Refactoring" to perform a comprehensive cleanup and smooth upgrade of the entire database cluster.
    * **Refactoring Latency-Heavy Batch Engines:** Finetuned concurrency controls, implemented asynchronous message decoupling, and executed physical instance partitioning to comprehensively upgrade the distributed batch framework, permanently clearing EOD performance bottlenecks.
    * **API Bottleneck Remediation:** Deployed read-write splitting architectures, asynchronous processing, aggressive rate-limiting for peak shaving, and eliminated nested loop queries to optimize API latency profiles.
    * **Eliminating Master-Slave Replication Lag:** Implemented asynchronous core refactoring, dynamic thread pool adjustments, and database partitioning to thoroughly flatten I/O spikes at the database layer.
* **Results:**
    * **Hardcore Performance Gains:** Reduced core database Slow SQL counts from 23K+ down to 100+ daily (a 99% reduction); slashed core API TP99 response latencies from 3000ms to under 200ms (a 93% decrease); compressed database master-slave replication lag during peak hours from 4000s down to under 10s (a 99.7% reduction); trimmed overall EOD core batch execution windows by 50%.
    * **Engineering Velocity Boost:** Compressed manual R&D cycles for onboarding new channels/products from 15 man-days down to 3 man-days; post-delivery production defect rates dropped by 80%; halved the integration timeline for new business APIs.

### High-Concurrency Distributed Financing Gateway & Core System Upgrade (Meili Financial)
*Jul 2018 - Aug 2019*  
**Role:** Backend Development Engineer  
* **Background:** This platform functions as the core capital flow distribution architecture for Meili Financial (supporting a total R&D team of 286 engineers). Maintained 7 core systems including the external gateway (Mgateway), internal shared capital gateway (Bgis), distributed scheduling module (Mjob), asset backend (Mac), and frontend operations portal (Mface), safely anchoring tens of billions in capital flow.
* **Core Contribution & Execution:**
    * **Standardized Gateway Architectural Design:** Led the development and integration workflows for external and internal shared capital gateways. Abstracted and componentized interfaces to modularize end-to-end fintech flows (account creation, credit limits, blacklist lookups, loan drawdowns, repayment tracking, and prepayments) across major tier-1 banks and P2P capital sources.
    * **Redis-Powered Dynamic Configuration Refactoring:** Identified structural risks stemming from frequent production releases triggered by simple business constant modifications, and constructed a centralized dynamic configuration registry using Redis. Transformed routing rules and channel switches into dynamic properties, drastically reducing volatile production hot-fixes.
    * **High-Concurrency Batch Scheduling:** Upgraded the shared batch cron framework (Mjob) to reliably consume distributed service events and configure scheduled jobs. Scientifically allocated threads and task priorities to eradicate system stuttering under high-concurrency environments.
* **Results:**
    * **Engineering Rigor & Quality Uplift:** Enforced an engineering pipeline (Technical Design Specs -> Cross-Team Architecture Reviews -> Code Walk-throughs -> Automated Testing Sign-off -> Canary Deployments) within a 10-engineer squad, dropping the online defect rate per 1,000 lines of code by 85% year-on-year.
    * **Configuration Returns & Delivery Velocity:** Reduced unnecessary system deployment frequencies by over 70% via the Redis configuration registry, maintaining a 0% production failure rate due to bad parameters. Onboarding cycles for new capital channels were cut from 10–15 days down to 4–5 days (a 60%+ velocity boost), pinning project delay rates from 25% down to under 3%.

### Bailian Mall B2C Platform R&D Project
*Apr 2017 - Jun 2018*  
**Role:** Junior Software Engineer  
* **Background:** A large-scale comprehensive B2C e-commerce platform built on an SOA distributed architecture utilizing Dubbo and ZooKeeper infrastructures, encompassing Member Services, Order Orchestration, Product Search, Content Display, and Back-office Administration modules.
* **Key Contributions & Milestones:**
    * Implemented fine-grained access control policies based on Shiro, and engineered a Single Sign-On (SSO) architecture driven by Redis Clusters and JSONP, securing a 99.9% success rate across multi-site unified authentication paths.
    * Responsible for the R&D of the search module built on SolrCloud, supporting multi-dimensional facet filtering and fuzzy queries, maintaining search response times within 200ms with a 95% search accuracy rating.
    * Utilized Freemarker to implement full static-page generation for product detail pages and configured Nginx for dynamic-static content separation, accelerating page load times from 1.2s down to 300ms.
    * Implemented Redis caching layers to govern hot-data paths including homepage banners and shopping carts, lowering database query pressure by 60% and scaling system QPS capacity by 3x, helping monthly GMV surpass 20M RMB within the first month of launch.

---

## 🛠 Technical Skills

* **Business & Domain Expertise:** Deep knowledge in fintech core business architectures, credit lifecycles, and clearing/settlement financial models. Rich hands-on experience in high-performance, high-concurrency, and high-availability distributed architecture design, alongside expert-level diagnostic skills for resolving production-grade distributed anomalies.
* **Programming Languages:** Robust Java engineering foundation (Deep understanding of JDK 8+ advanced idioms, multi-threading concurrency, and deep source-code level analysis of the Java Collection Framework and `java.util.concurrent` internals).
* **Microservices & Frameworks:** Highly proficient across the enterprise Java ecosystem: Spring, SpringMVC, MyBatis, SpringBoot, and SpringCloud. Proven competence in microservice architecture design and service governance based on Dubbo and Zookeeper.
* **Data Storage & Architecture:** Expert in MySQL database design, query optimization, indexing strategies, complex SQL tuning, and database sharding architectures. Hands-on experience with ShardingSphere distributed database middleware and distributed transaction management. Proficient in Redis caching design, eviction policies, persistence strategies, and handling cache stampede/avalanche/penetration scenarios.
* **Distributed Middleware:** Experienced in implementing asynchronous decoupling and peak shaving architectures using message queues such as Kafka and RabbitMQ, with practical skills in resolving message backlogs and securing eventual consistency. Proficient in Nginx and Tomcat load-balancing configuration and tuning.
* **Cloud Native & Performance Profiling:** Proficient with Linux operating environments and Shell scripting. Familiar with containerization technologies including Docker and K8s (Kubernetes). Experienced in building automated CI/CD deployment pipelines using Jenkins. Skilled in performance load testing and troubleshooting using enterprise monitoring toolkits like Prometheus, SkyWalking, and Arthas.
* **Full-Stack Potential:** Solid foundational grasp of JavaScript and modern web standards, allowing smooth cross-layer collaboration and independent full-stack product development under AI-assisted workflows.

---

## 🎓 Education

* **Shinhan University (South Korea)**  
  Bachelor of Engineering in Software Engineering (Expected / In Progress)
* **Beijing Jiaotong University (China)**  
  Bachelor of Management in Engineering Management (Graduated)
