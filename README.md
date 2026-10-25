# Hi, I'm Prajyot Korde 👋

**Information Technology undergraduate @ Ramdeobaba University (2027) | Backend & Data Systems**

I build backend and data systems with a focus on reliability, resilience, and clean design. Based in Nagpur, India.

## 🔭 Currently working on
- Expanding **PulseCheck**: adding cloud storage streaming and workflow orchestration
- Improving **Resilient Cache Engine**: tests, CI, and documentation
- Building **Chaos-Toolkit**: fault-injection tooling for testing microservice resilience
- Practicing DSA and low-level design

## ⚡ Featured projects

**[PulseCheck](https://github.com/PrajyotKorde-18/PulseCheck)**: resilient batch data ingestion & quarantine guardrail
A batch ingestion engine that stops corrupted data from reaching PostgreSQL without failing the pipeline. Features vectorized row-level validation, a queryable JSONB quarantine table with GIN-indexed reason codes, and idempotent upserts (`ON CONFLICT`). Detects batch-level volume drops and stale data against rolling historical medians, with a deterministic replay CLI to re-validate and backfill remediated records. Profiled on 2.96 million real NYC TLC taxi trips across 31 daily batches with a 99.89% clean load rate.
`Python 3.11+` `PostgreSQL` `Pydantic v2` `PyArrow` `Pandas` `Docker`

**[Resilient Cache Engine](https://github.com/PrajyotKorde-18/Resilient-Cache-Engine)**: self-healing multi-level caching library
A Spring Boot Starter with a two-layer cache (Caffeine + Redis) exposed through a custom `@ResilientCache` annotation. It falls back to the local cache when Redis fails, resyncs on recovery, and uses Redis pub/sub for cross-instance invalidation. Load-tested to a 99%+ hit rate, cutting average API latency from 847 ms to 180 ms.
`Java 21` `Spring Boot` `Spring AOP` `Redis` `Caffeine` `Docker`

**[Chaos Toolkit](https://github.com/PrajyotKorde-18/Chaos-Toolkit)**: chaos engineering platform for Spring Boot microservices
Injects latency and exception faults into running services through a Spring AOP agent, finds the point where a service breaks its SLO, and scores resilience with a letter grade. Includes a live dashboard, a five-scenario fault matrix, and rule-based post-mortem reports.
`Java 21` `Spring Boot` `Spring AOP` `Resilience4j` `Chart.js`

**[PromptBridge](https://github.com/PrajyotKorde-18/HackByte4.0)**: AI-powered prompt optimization platform
Built at HackByte 4.0 (IIITDM Jabalpur, Top 120 teams in India) in a team of four. I owned the architecture and PostgreSQL database design.
`FastAPI` `React` `PostgreSQL` `Groq (Llama-3-70B)`

**[NLP-to-SQL Query Converter](https://github.com/PrajyotKorde-18/NLP-to-SQL-Query-Converter)**: converts plain-English questions into SQL
`Python` `SQL`

## 🛠 Tech stack
**Languages:** Java, Python, SQL, C
**Backend & Data:** Spring Boot, REST APIs, Redis, PostgreSQL (JSONB, GIN), MySQL, PyArrow, Pydantic, Pandas
**Tools:** Git, GitHub, Docker, Maven, JUnit, Pytest, Postman
**Core CS:** DSA (350+ problems solved), OOP, DBMS, Linux, Low-Level Design (LLD)

## 🏆 Highlights
- 3rd place, TechSprint Hackathon (GDG On Campus, RBU)
- Top 120 teams, HackByte 4.0 (IIITDM Jabalpur)

## 🤝 Connect with me
- LinkedIn: [prajyot-korde](https://www.linkedin.com/in/prajyot-korde-912621281)
- GitHub: [PrajyotKorde-18](https://github.com/PrajyotKorde-18)
