# JoongHyuk Shin
**System-level Software Engineer specializing in Database Engine Kernels & Distributed Coordination**

---

### 🚀 Summary
- System-level software engineer specializing in database engine kernels and distributed coordination.
- Expertise in extending PostgreSQL with C extensions, hooks (planner, object access), Vector/LLM integration, and Oracle-compatible features.
- Experience architecting distributed lifecycle engines with a focus on transactional state consistency and reliability.
- Proficient in C, C++, Python, and Linux; solid foundation in algorithms, probability, and high-performance distributed system design.

---

### 🛠 Skills
| Area | Details |
|------|--------|
| **Languages** | C, C++ (Modern), Python, SQL, Java, Bash |
| **DB Internals** | PostgreSQL/Oracle engine core, query compiler, optimizer (CBO), vector search |
| **PostgreSQL** | C extensions, planner hook, object access hook, RLS, parser/planner integration |
| **Distributed** | Consensus (etcd/Raft), high availability, cluster orchestration (IaC) |
| **Core** | Probability, high-performance algorithms |
| **Tools** | Linux (system-level), Docker, Git, AWS/Azure (SDK/API integration) |

---

### 💼 Work Experience

#### **Tmax Tibero** | Database Engine Developer (Oct 2023 – Present)

**1) OpenSQL Team (Nov 2024 – Present)**
PostgreSQL-based managed RDBMS with Oracle compatibility and vector DB features.

- **Row-Level Security (DBMS_RLS)**  
  Designed and implemented Oracle-compatible RLS as a **PostgreSQL C extension**, using **planner_hook** and **object_access_hook** for planner integration and runtime policy enforcement. Delivered transient-view–style predicate injection and definer-rights policy execution aligned with Oracle VPD semantics.

- **Oracle compatibility**  
  Implemented Oracle-compatible functions/packages and conducted performance benchmarking; achieved measurable improvements including 50%+ gain for the median function through algorithm redesign.

- **Vector DB & RAG**  
  Integrated pgvector, developed vector embedding features, and implemented LLM integration for DB-based RAG solutions.

- **High availability**  
  Designed PostgreSQL HA environments using Patroni and etcd for enterprise workloads.

- **Cluster orchestration & scaling**  
  Architected a Multi-CSP IaC (ARM/CloudFormation) scaling engine using etcd watch for real-time state sync and Command Pattern–based rollback for transactional reliability in distributed node lifecycle.

- **Debug / monitoring**  
  Built internal debug tooling to print PostgreSQL query trees during development.

**2) SuperTibero Team (Oct 2023 – Oct 2024)**
Enterprise RDBMS with distributed storage; focused on SQL compiler modules.

- **SQL compiler**  
  Built parser, query transformer, and cost-based optimizer.

- **Query optimization**  
  Implemented index range scan, predicate pushdown, sort-skip optimization, and execution plan cache.

- **Privilege & authentication**  
  Designed and implemented privilege check and authentication for secure SQL execution.

- **Performance**  
  Delivered query transformation features that improved index scan opportunities and reduced redundant operations.

---

### 🎓 Education
- **B.S. in Physics** – Yonsei University, Seoul
  - Focus: **Statistical Mechanics**, Quantum Mechanics

---

### 🏆 Achievements & Certifications
- **Algorithms**
  - **Top 4.2%** Contributor on [Leetcode](https://leetcode.com/Joshua-Shin/) (Consecutive years: 2023, 2024)
    <br><br> ![LeetCode Badges](https://leetcode-badge-showcase.vercel.app/api?username=Joshua-Shin)`
  - **Top 3.5%** on [Baekjoon](https://solved.ac/profile/sjh910805) - Platinum V
    
     <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=sjh910805">

- **Certifications**
  - Engineer Information Processing (HRDK)
  - SQL Developer (SQLD, Kdata)

---

### 📫 Connect with Me
- [GitHub](https://github.com/Joshua-Shin)
- [LinkedIn](www.linkedin.com/in/joonghyuk-shin-631701201)
- sjh910805@gmail.com

<!--
### Additional
#### Algorithm

- [Leetcode](https://leetcode.com/Joshua-Shin/)
  - Awarded Top 4.2% Contributing Badges in 2023
  - Awarded Top 4.2% Contributing Badges in 2024
  <br><br> ![LeetCode Badges](https://leetcode-badge-showcase.vercel.app/api?username=Joshua-Shin)`
- [Baekjoon - Platinum V](https://solved.ac/profile/sjh910805) : Top 3.57% (2023.06.14)
     
     
     <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=sjh910805">
#### Certification
- Engineer Information Processing (정보처리기사) : Human Resources Development Service of Korea (2023. 6. 9)
- SQL Developer Certification (SQLD) : Korea Data Agency (2023. 4. 16)

<!--
#### English
- TOEIC Score: 800 - 2021.11.05
- OPIc English IH Level - 2023.09.03

<!--
#### 💳 Certification
- 정보처리기사 취득, 자격번호: 23201300235U, 발급기관: 한국산업인력공단 (2023.06.09) 
- SQLD 취득, 자격번호: SQLD-048004155, 발급기관: 한국데이터산업진흥원 (2023.04.14) 점수 80 / 100
- TOEIC 800점, 자격번호: 027116-0414004801, 발급기관: 한국토익위원회 (2021.11.05)
- OPIc IH등급, 자격번호: 2A5747329351, 발급기관: ACTFL (2023.09.03)
-->
-------
