<div align="center">

<img src="https://github.com/SudegoraAnkit.png" width="200"/>

# Ankit Rai

**Backend Engineer · Systems Thinker · Building for Scale & Reliability**

<p align="center">
  <em>I design backend systems that survive production — integrations that handle enterprise complexity,<br/>APIs that scale predictably, and architectures that stay maintainable under real-world constraints.</em>
</p>

<p align="center">
  <a href="https://github.com/SudegoraAnkit">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://linkedin.com/in/ankitsudegora">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
</p>

# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=SudegoraAnkit&theme=transparent&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://streak-stats.demolab.com/?user=SudegoraAnkit&theme=transparent&hide_border=false)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=SudegoraAnkit&theme=transparent&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

</div>

---

## 🎯 What I Bring to Engineering

<table>
<tr>
<td width="50%">

### 💡 Engineering Mindset

```mermaid
graph TD
    A[Problem] --> B{What can fail?}
    B --> C[Design for observability]
    C --> D[Prefer boring solutions]
    D --> E[Think in systems]
    E --> F[Ship & iterate]
```

</td>
<td width="50%">

### 🎪 Current Focus

- **Distributed Systems Thinking**  
  Kafka, event-driven patterns, eventual consistency

- **API Design & Integration**  
  REST, gRPC, async messaging, failure recovery

- **AI-Integrated Backends**  
  LLM tool chains, Spring AI, augmented services

- **Production Java/Spring**  
  Enterprise-grade reliability & observability

</td>
</tr>
</table>

**My Engineering Approach:**
```
Start with constraints → Design for observability → Ship boring solutions → Think in systems
```

---

## 💼 Engineering Experience

<div align="center">

### 🏗️ **Enterprise Backend Architecture**

</div>

<table>
<tr>
<td width="60%">

#### **API Integration Architecture**

Built enterprise API integrations connecting internal services with SharePoint, Azure, and third-party telematics platforms.

**Key Engineering Decisions:**
- Designed retry logic with exponential backoff for flaky external APIs
- Built correlation IDs across distributed calls for debugging
- Instrumented integration points before optimizing

**Tech Context:** Spring Boot, REST, MSSQL, MongoDB, Azure

</td>
<td width="40%">

```mermaid
graph LR
    A[Internal Service] -->|Auth Flow| B[API Gateway]
    B --> C[SharePoint]
    B --> D[Azure Services]
    B --> E[Telematics API]
    C -.Retry Logic.-> B
    D -.Rate Limit.-> B
    E -.Circuit Breaker.-> B
```

</td>
</tr>
</table>

---

<table>
<tr>
<td width="40%">

```mermaid
graph TD
    A[SharePoint Docs] -->|Extract| B[Validation Layer]
    B -->|Transform| C[Schema Mapper]
    C -->|Incremental Load| D[MongoDB]
    D -->|Verify| E[Integrity Check]
    E -.Rollback Path.-> A
```

</td>
<td width="60%">

#### **Large-Scale Data Migration System**

Architected SharePoint → MongoDB migration pipeline for enterprise document management.

**System Properties:**
- Incremental migration with rollback capability
- Zero-downtime cutover strategy
- Schema transformation with integrity validation

**Learning Applied:** Studying Kafka to improve future event-driven migration patterns

**Tech Context:** Java, Spring Boot, MongoDB, SharePoint API

</td>
</tr>
</table>

---

<table>
<tr>
<td width="60%">

#### **Eclipse Plugin Tooling & DSL Systems**

Built Eclipse RCP-based validation tooling for domain-specific languages in enterprise environments.

**Architecture Highlights:**
- Plugin-based extensibility model
- Integrated React UI into Eclipse RCP
- DSL validation engine with real-time feedback

**Tech Context:** Java, Eclipse RCP, React integration

</td>
<td width="40%">

```mermaid
graph TD
    A[Eclipse IDE] --> B[Plugin Core]
    B --> C[DSL Parser]
    B --> D[Validation Engine]
    B --> E[React UI Layer]
    C --> F[Error Reporter]
    D --> F
```

</td>
</tr>
</table>

---

## 🔬 Active Learning (Applied to Real Problems)

<div align="center">

### 📚 Learning Integrated with Engineering Work

</div>

```mermaid
gantt
    title Engineering Learning & Revision Timeline
    dateFormat  YYYY-MM

    section Distributed Systems
    Kafka & Event-Driven Patterns     :active, kafka, 2026-05, 90d
    gRPC & High-Throughput Services   :grpc, 2026-08, 60d

    section AI Integration
    Spring AI & LLM Workflows         :ai, 2026-10, 75d

    section Work Requirements
    C++ & Adaptive AUTOSAR            :crit, autosar, 2026-05, 120d

    section Architecture
    Microservices Decomposition       :micro, 2026-06, 90d

    section Revision
    Java 8 & Java 17                  :rev1, 2026-05, 60d
    Spring Security                   :rev2, 2026-07, 45d
    Spring Cloud Function             :rev3, 2026-08, 45d
    Spring Ecosystem Deep Dive        :rev4, 2026-09, 60d
    Azure Cloud Fundamentals          :rev5, 2026-10, 45d
    GCP Fundamentals                  :rev6, 2026-11, 45d
```

<table>
<tr>
<th>Learning Track</th>
<th>Applied Context</th>
<th>Status</th>
</tr>
<tr>
<td>🔄 <b>Kafka & Event-Driven Systems</b></td>
<td>Rethinking migration pipelines and async integration patterns</td>
<td><img src="https://img.shields.io/badge/Status-Hands--on-blue?style=flat-square" /></td>
</tr>
<tr>
<td>⚡ <b>gRPC & Spring WebFlux</b></td>
<td>Evaluating for high-throughput internal service communication</td>
<td><img src="https://img.shields.io/badge/Status-Prototyping-yellow?style=flat-square" /></td>
</tr>
<tr>
<td>🤖 <b>Spring AI & LLM Integration</b></td>
<td>Exploring AI-augmented backend workflows and tool orchestration</td>
<td><img src="https://img.shields.io/badge/Status-Experimenting-green?style=flat-square" /></td>
</tr>
<tr>
<td>🚗 <b>C++ & Adaptive AUTOSAR</b></td>
<td>Current work requirement — embedded systems context</td>
<td><img src="https://img.shields.io/badge/Status-Active_Work-red?style=flat-square" /></td>
</tr>
<tr>
<td>🏢 <b>Microservices Decomposition</b></td>
<td>Applying to legacy modernization and bounded context design</td>
<td><img src="https://img.shields.io/badge/Status-Studying-orange?style=flat-square" /></td>
</tr>
</table>

**Revising Fundamentals:** DSA · Low-Level Design · High-Level Design *(interview prep + deeper systems thinking)*

---

## 🚀 Projects That Show My Thinking

<div align="center">

### 🛠️ **Active Development**

</div>

<table>
<tr>
<td width="50%">

### **[Lumina Task Orchestrator](https://github.com/SudegoraAnkit/lumina-task-orchestrator)**

![stars](https://img.shields.io/github/stars/SudegoraAnkit/lumina-task-orchestrator?style=social) ![lang](https://img.shields.io/github/languages/top/SudegoraAnkit/lumina-task-orchestrator)

Lightweight workflow orchestrator for scheduled and ad-hoc job execution.

**Engineering Focus:**
- Task scheduling & dependency management
- Failure recovery with retry strategies
- Built-in observability and monitoring

**Tech:** Java, Spring Boot, Scheduler API

**Why This Matters:** Exploring orchestration patterns that replace heavyweight workflow engines in simpler use cases.

</td>
<td width="50%">

```mermaid
graph TD
    A[Job Submission] --> B{Scheduled?}
    B -->|Yes| C[Cron Scheduler]
    B -->|No| D[Immediate Executor]
    C --> E[Task Runner]
    D --> E
    E --> F{Success?}
    F -->|No| G[Retry Logic]
    F -->|Yes| H[Metrics]
    G --> E
```

</td>
</tr>
</table>

---

<table>
<tr>
<td width="50%">

```mermaid
graph LR
    A[Learning Path] --> B[Curated Content]
    B --> C[Notes System]
    C --> D[Knowledge Graph]
    D --> E[Structured Output]
```

</td>
<td width="50%">

### **[GyanYatra](https://github.com/SudegoraAnkit/GyanYatra)**

![stars](https://img.shields.io/github/stars/SudegoraAnkit/GyanYatra?style=social) ![lang](https://img.shields.io/github/languages/top/SudegoraAnkit/GyanYatra)

Knowledge-sharing platform for curated learning paths, tutorials, and engineering notes.

**Engineering Focus:**
- Structured learning workflows
- Documentation-as-product thinking
- Knowledge organization patterns

**Tech:** Web stack, persistence layer

**Why This Matters:** A meta-project exploring how to structure and present technical knowledge effectively.

</td>
</tr>
</table>

---

<details>
<summary><b>📂 Past Projects (Click to expand)</b></summary>

<br/>

| Project | Description | Tech |
|---------|-------------|------|
| **[ComplexityAnalyzer](https://github.com/SudegoraAnkit/ComplexityAnalyzer)** | Static analysis tooling for code complexity measurement | Java, static analysis |
| **[QR Code Tools](https://github.com/SudegoraAnkit/QR-Code-Reader-generator-using-java)** | QR encoding/decoding utilities | Java, ZXing |
| **[Tech Challenges](https://github.com/SudegoraAnkit/expleo_group-techchallenge)** | Problem-solving demonstrations | Various |

</details>

---

## 🛠️ Tech Stack

<div align="center">

### **Production Stack**

<p>
<img src="https://skillicons.dev/icons?i=java,spring,mysql,mongodb,docker,git,azure,postman" />
</p>

### **Exploring & Learning**

<p>
<img src="https://skillicons.dev/icons?i=kafka,cpp,react,postgres,kubernetes" />
</p>

</div>

<table>
<tr>
<td width="33%" align="center">

### ⚙️ **Backend Core**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST-02569B?style=for-the-badge)

</td>
<td width="33%" align="center">

### 🌐 **Distributed Systems**

![Kafka](https://img.shields.io/badge/Kafka-000000?style=for-the-badge&logo=apachekafka) *(exploring)*
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white) *(exploring)*
![WebFlux](https://img.shields.io/badge/WebFlux-6DB33F?style=for-the-badge&logo=spring&logoColor=white) *(exploring)*
![Microservices](https://img.shields.io/badge/Microservices-FF9800?style=for-the-badge)

</td>
<td width="33%" align="center">

### 🗄️ **Data & Cloud**

![MSSQL](https://img.shields.io/badge/MS_SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</td>
</tr>
</table>

---

<div align="center">
## 📊 Engineering Strengths & Growth

<table>
<tr>
<td width="50%">

### ✅ **Where I Operate Well**

```
✓ Backend architecture & systems thinking
✓ Debugging complex integration issues
✓ Understanding tradeoffs
  (performance vs complexity,
   consistency vs availability)
✓ API design & enterprise patterns
✓ Technical documentation
```

</td>
<td width="50%">

### 🎯 **Actively Improving**

```
→ Communication clarity & presentation
→ Frontend/UI collaboration skills
→ Reducing analysis paralysis
→ Prioritization & focus
→ Consistent technical writing
```

</td>
</tr>
</table>
</div>

---

## 🧭 Engineering Philosophy

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│  Build systems that:                                        │
│  • Scale predictably                                        │
│  • Fail gracefully and observably                           │
│  • Stay maintainable under changing requirements            │
│  • Survive real production constraints                      │
│  • Can be operated by someone other than you                │
└─────────────────────────────────────────────────────────────┘
```

</div>

I believe in **first-principles thinking**: understanding *why* a solution exists, what constraints shaped it, and what tradeoffs it accepts.

**Guiding Principles:**
- Prefer boring, proven technology over hype — unless the hype solves a real problem I can articulate
- Instrument before optimizing
- Design for the operator, not just the user
- Question assumptions, but ship code

---

## 📚 Continuous Learning & Community

<div align="center">

### 🎤 **Engineering Engagement**

</div>

<table>
<tr>
<td width="50%">

**I regularly attend:**
- 🏗️ Backend engineering meetups
- 🤖 AI/ML integration discussions
- 📐 Distributed systems architecture talks
- 👥 Developer community events

</td>
<td width="50%">

**Topics I track:**
- Distributed systems patterns
- Backend scalability & reliability
- System design tradeoffs
- AI-augmented development
- Engineering productivity

</td>
</tr>
</table>

<div align="center">

[📝 **Event Notes & Learnings Repository**](https://github.com/SudegoraAnkit/events)

</div>

---

## 📈 GitHub Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SudegoraAnkit&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FF6B6B" />

</div>

---

## 🌐 Connect With Me

<div align="center">

<table>
<tr>
<td align="center">
<a href="https://github.com/SudegoraAnkit">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<br/>
<sub><b>View Repositories</b></sub>
</a>
</td>
<td align="center">
<a href="https://linkedin.com/in/ankitsudegora">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
<br/>
<sub><b>Professional Network</b></sub>
</a>
</td>
<td align="center">
<a href="https://github.com/SudegoraAnkit/SudegoraAnkit.github.io">
<img src="https://img.shields.io/badge/Portfolio-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white" />
<br/>
<sub><b>Engineering Portfolio</b></sub>
</a>
</td>
</tr>
</table>

</div>

---

<div align="center">

### 💡 *"Backend engineering is not about frameworks — it's about designing systems that survive scale, failures, and the test of time."*

<br/>

<img src="https://komarev.com/ghpvc/?username=SudegoraAnkit&color=58A6FF&style=for-the-badge" />

</div>
