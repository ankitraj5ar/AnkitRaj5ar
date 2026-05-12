<!--
╔══════════════════════════════════════════════════════════════════════╗
║  ANKIT RAJ — GitHub Profile README                                  ║
║  Customization guide embedded as comments throughout                 ║
║  Assets folder: /assets/  (see ASSETS.md for setup guide)           ║
╚══════════════════════════════════════════════════════════════════════╝

  QUICK CUSTOMIZATION MAP:
  → Banner:         Line ~20  — swap the SVG banner URL
  → Social links:   Line ~60  — update username handles
  → Tech stack:     Line ~120 — add/remove technologies
  → Projects:       Line ~200 — update project names + links
  → Stats widgets:  Line ~290 — replace ?username=ankitraj5ar
  → Current focus:  Line ~170 — update what you're building now
-->

<!-- ═══════════════════════ HERO ═══════════════════════ -->

<div align="center">

<!-- CUSTOMIZATION: Replace this with your own banner hosted on GitHub or a CDN.
     Recommended: Create a 1200×300px dark banner with your name + tagline.
     Tools: Figma, Canva (dark mode), or generate via carbon.now.sh -->

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                   │
│   █████╗ ███╗   ██╗██╗  ██╗██╗████████╗    ██████╗  █████╗      │
│  ██╔══██╗████╗  ██║██║ ██╔╝██║╚══██╔══╝    ██╔══██╗██╔══██╗     │
│  ███████║██╔██╗ ██║█████╔╝ ██║   ██║       ██████╔╝███████║     │
│  ██╔══██║██║╚██╗██║██╔═██╗ ██║   ██║       ██╔══██╗██╔══██║     │
│  ██║  ██║██║ ╚████║██║  ██╗██║   ██║       ██║  ██║██║  ██║     │
│  ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝   ╚═╝       ╚═╝  ╚═╝╚═╝  ╚═╝     │
│                                                                   │
│         Software Engineer · Distributed Systems · Backend        │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

</div>

<br/>

<!-- ═══════════════════════ IDENTITY ═══════════════════════ -->

<table>
<tr>
<td width="55%">

```bash
$ whoami
> Ankit Raj

$ cat /etc/role
> Software Engineer
> Backend & Distributed Systems

$ uptime --since
> Building systems that scale

$ hostname
> ankitraj5ar.online
```

</td>
<td width="45%" align="right">

```yaml
# system.config.yml

focus:
  - scalable backend systems
  - event-driven architecture
  - distributed systems design
  - ERP & multi-tenant platforms

runtime: production
reliability: non-negotiable
complexity: managed, not avoided
```

</td>
</tr>
</table>

<br/>

---

<!-- ═══════════════════════ ENGINEERING PHILOSOPHY ═══════════════════════ -->

## `$ cat philosophy.md`

> I don't write code to ship features. I design systems to sustain them.

Most engineering problems aren't technical — they're architectural decisions made too early or too late. I care about understanding *why* a system behaves the way it does, not just making it work today. That means thinking through failure modes before they happen, choosing the right consistency model for the workload, and building abstractions that don't leak at 3 AM.

Correctness first. Performance where it matters. Simplicity where complexity isn't earned.

<br/>

---

<!-- ═══════════════════════ ARCHITECTURE INTERESTS ═══════════════════════ -->

## `$ ls /interests/architecture/`

<table>
<tr>
<td width="50%">

**Distributed Systems**
```
├── consensus & replication
├── distributed transactions
├── CAP theorem tradeoffs
└── clock synchronization
```

**Messaging & Queuing**
```
├── Apache Kafka
│   ├── partitioning strategies
│   ├── consumer group design
│   └── exactly-once semantics
├── RabbitMQ
│   ├── exchange topologies
│   ├── dead-letter queues
│   └── routing patterns
└── event sourcing
```

</td>
<td width="50%">

**System Design Patterns**
```
├── CQRS
├── Saga pattern
├── outbox pattern
├── circuit breaker
└── bulkhead isolation
```

**Multi-tenant Architecture**
```
├── tenant isolation models
│   ├── schema-per-tenant
│   ├── row-level security
│   └── silo vs pooled
├── ERP domain modeling
└── workflow orchestration
```

</td>
</tr>
</table>

<br/>

---

<!-- ═══════════════════════ TECH STACK ═══════════════════════ -->

## `$ cat stack.json`

<!-- CUSTOMIZATION: Add/remove technologies. Keep it honest — only list what you use regularly. -->

```json
{
  "languages": ["Python", "JavaScript", "TypeScript", "SQL", "Bash"],

  "backend": {
    "frameworks": ["FastAPI", "Node.js", "Express"],
    "patterns": ["RESTful APIs", "event-driven", "CQRS", "microservices"]
  },

  "messaging": {
    "brokers": ["Apache Kafka", "RabbitMQ"],
    "patterns": ["pub/sub", "work queues", "fanout", "dead-letter"]
  },

  "databases": {
    "relational":    ["PostgreSQL", "MySQL"],
    "caching":       ["Redis"],
    "search":        ["Elasticsearch"],
    "design":        ["schema design", "indexing strategy", "query optimization"]
  },

  "infrastructure": {
    "containers":    ["Docker", "Docker Compose"],
    "orchestration": ["Kubernetes (learning)"],
    "cloud":         ["AWS (EC2, S3, RDS, SQS, Lambda)"],
    "monitoring":    ["Prometheus", "Grafana", "structured logging"]
  },

  "practices": [
    "clean architecture",
    "domain-driven design",
    "12-factor app",
    "system reliability engineering",
    "database migration strategies"
  ]
}
```

<br/>

---

<!-- ═══════════════════════ CURRENT FOCUS ═══════════════════════ -->

## `$ tail -f /var/log/current-work.log`

<!-- CUSTOMIZATION: Update this section every few months — it shows you're active and growing -->

```
[2025] Designing multi-tenant ERP platform
      └── tenant isolation via row-level security
      └── workflow orchestration engine
      └── event-driven inter-module communication

[2025] Kafka deep-dive: building reliable event pipelines
      └── exactly-once delivery guarantees
      └── consumer group rebalancing strategies
      └── schema registry + Avro

[2025] Studying: Designing Data-Intensive Applications (Kleppmann)
      └── applying concepts directly to production systems

[NEXT] Service mesh, distributed tracing, OpenTelemetry
```

<br/>

---

<!-- ═══════════════════════ FEATURED PROJECTS ═══════════════════════ -->

## `$ ls -la /projects/`

<!-- CUSTOMIZATION: Replace with your actual projects. Focus on architecture, not just "what it does" -->

<table>
<tr>
<td width="50%" valign="top">

### `erp-core/`
```yaml
type: multi-tenant ERP platform
stack: [Python, FastAPI, PostgreSQL, Redis, RabbitMQ]
architecture:
  - modular monolith → service extraction
  - row-level tenant isolation
  - event-driven inter-module comms
  - workflow state machine engine
scale: multi-org, role-based access
```
<!-- Add link: [→ repo](https://github.com/ankitraj5ar/your-repo) -->

</td>
<td width="50%" valign="top">

### `event-pipeline/`
```yaml
type: Kafka-based event processing system
stack: [Python, Kafka, PostgreSQL, Docker]
architecture:
  - producer / consumer separation
  - dead-letter queue handling
  - idempotent consumers
  - schema versioning
design: exactly-once processing guarantee
```
<!-- Add link: [→ repo](https://github.com/ankitraj5ar/your-repo) -->

</td>
</tr>
<tr>
<td width="50%" valign="top">

### `queue-worker/`
```yaml
type: distributed task orchestrator
stack: [Python, RabbitMQ, Redis, PostgreSQL]
architecture:
  - work queue with priority lanes
  - retry + backoff strategy
  - job deduplication layer
  - observability via structured logs
```
<!-- Add link: [→ repo](https://github.com/ankitraj5ar/your-repo) -->

</td>
<td width="50%" valign="top">

### `api-gateway/`
```yaml
type: backend API infrastructure
stack: [Node.js, Express, Redis, PostgreSQL]
architecture:
  - JWT auth + refresh token rotation
  - rate limiting per tenant
  - request tracing via correlation IDs
  - middleware pipeline design
```
<!-- Add link: [→ repo](https://github.com/ankitraj5ar/your-repo) -->

</td>
</tr>
</table>

<br/>

---

<!-- ═══════════════════════ ARCHITECTURE PRINCIPLES ═══════════════════════ -->

<details>
<summary><code>$ cat /etc/principles.conf</code> &nbsp;—&nbsp; expand</summary>

<br/>

```
[reliability]
design for failure first, performance second
every network call is a failure waiting to happen
timeout everything, retry with backoff, circuit-break at limits

[data]
understand your read/write ratio before choosing a database
denormalize when reads demand it; normalize when consistency requires it
index for your queries, not your schema

[messaging]
at-least-once is the default; idempotency is your responsibility
don't put business logic in message brokers
model your events as facts, not commands

[architecture]
a distributed system is not just a fast monolith
coupling is the enemy of evolution
shared databases between services are shared liabilities

[code]
complexity is a cost; pay it only when the benefit is real
the most maintainable abstraction is often no abstraction
make the wrong thing hard to do
```

</details>

<br/>

---

<!-- ═══════════════════════ GITHUB STATS ═══════════════════════ -->

## `$ git log --stat`

<!-- CUSTOMIZATION: Replace username. Theme options: dark, radical, merko, gruvbox, tokyonight -->

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ankitraj5ar&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&hide=contribs&include_all_commits=true&count_private=true" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ankitraj5ar&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=6" width="38%" />

</div>

<br/>

<!-- ═══════════════════════ CONTRIBUTION GRAPH ═══════════════════════ -->

<div align="center">

<!-- CUSTOMIZATION: Replace with your GitHub username. Color themes: github-compact, dracula -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ankitraj5ar&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&area_color=1f3a6e" width="95%" />

</div>

<br/>

---

<!-- ═══════════════════════ SYSTEM STATUS ═══════════════════════ -->

## `$ systemctl status engineer`

```
● engineer.service — Ankit Raj, Software Engineer
   Loaded: loaded (/etc/systemd/system)
   Active: active (running) since 2020-01-01
   
   Main PID: [ankitraj5ar]
   Status: "Designing distributed systems"
   
   Task breakdown:
     backend_work       [████████████████████] RUNNING
     distributed_study  [█████████████░░░░░░░] 65% — Kafka internals
     open_source        [████░░░░░░░░░░░░░░░░] contributing
     writing            [██░░░░░░░░░░░░░░░░░░] engineering notes

   Memory: focused
   CPU:    architecture-mode
```

<br/>

---

<!-- ═══════════════════════ CONNECT ═══════════════════════ -->

## `$ curl --connect-timeout 5 /contacts`

<!-- CUSTOMIZATION: Replace links with your actual handles -->

<div align="center">

| Channel | Link |
|:-------:|:-----|
| Portfolio | [ankitraj5ar.online](https://ankitraj5ar.online) |
| GitHub | [@ankitraj5ar](https://github.com/ankitraj5ar) |
| LinkedIn | [linkedin.com/in/ankitraj5ar](https://linkedin.com/in/ankitraj5ar) <!-- update handle --> |
| Email | [reach@ankitraj5ar.online](mailto:reach@ankitraj5ar.online) <!-- update address --> |

</div>

<br/>

```
Response time: reasonable
Topics: distributed systems, backend architecture, engineering tradeoffs
Not accepting: unsolicited recruitment for roles requiring 10 years of experience in a 5-year-old framework
```

<br/>

---

<!-- ═══════════════════════ FOOTER ═══════════════════════ -->

<div align="center">

```
Systems don't fail at launch — they fail under load, over time, at the edges.
Build for that.
```

<!-- CUSTOMIZATION: Optional visitor counter — remove if you find it unnecessary -->
<!-- ![visitors](https://komarev.com/ghpvc/?username=ankitraj5ar&color=58a6ff&style=flat&label=profile+views) -->

</div>

<!--
╔══════════════════════════════════════════════════════════════════════╗
║  END OF README — See ASSETS.md for banner + SVG setup guide         ║
╚══════════════════════════════════════════════════════════════════════╝
-->
