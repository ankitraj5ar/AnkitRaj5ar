<div align="center">
  <img src="./assets/banner.svg" width="100%" alt="Ankit Raj — Software Engineer"/>
</div>

<br/>

<!----------------------------------------------------------------------
  SYSTEM OVERVIEW
----------------------------------------------------------------------->

<br/>

Software engineer with **3+ years** designing backend systems at scale.
I work at the intersection of distributed systems, ERP architecture, and event-driven design —
building platforms that are **correct by construction**, **observable by default**, and **operable under pressure**.

Currently engineering a multi-domain ERP platform serving retail, MSME, and agritech verticals.
I care deeply about how complex business workflows translate into reliable, maintainable systems —
and how to keep them consistent and predictable as they grow.

<br/>

<!----------------------------------------------------------------------
  ENGINEERING PHILOSOPHY
----------------------------------------------------------------------->

---

<br/>

### `∿  engineering philosophy`

<br/>

```
  reliability          >    feature velocity
  maintainability      >    clever abstractions
  operational clarity  >    engineering elegance
  explicit contracts   >    implicit conventions
  understand the system first, then trust the framework
```

<br/>

The systems I design are built to be handed off, debugged at 3am, and still make sense
six months after the original engineer is gone.

<br/>

<!----------------------------------------------------------------------
  ARCHITECTURE DOMAINS
----------------------------------------------------------------------->

---

<br/>

### `⬡  architecture domains`

<br/>

<table>
<tr>
<td width="50%" valign="top">

**Distributed Systems**
Consistency models · partition tolerance · failure modes · clock drift · read-your-writes guarantees · split-brain handling

**Queue-Driven Architecture**
Kafka · RabbitMQ · Redis Streams · consumer group design · dead-letter semantics · backpressure · retry topology

**Workflow Orchestration**
Long-running process design · saga patterns · compensating transactions · workflow state persistence · timeout handling

</td>
<td width="50%" valign="top">

**ERP & Business Systems**
Multi-tenant isolation · complex domain modeling · cross-domain consistency · audit trails · role-based access · RBAC at scale

**Event-Driven Design**
Event sourcing · outbox pattern · dual-write safety · schema evolution · fan-out routing · at-least-once delivery

**Infrastructure Thinking**
Service mesh basics · observability hooks · structured logging · health contracts · graceful degradation · rate limiting design

</td>
</tr>
</table>

<br/>

<!----------------------------------------------------------------------
  TECH STACK
----------------------------------------------------------------------->

---

<br/>

### `⚙  stack`

<br/>

```
  language        Node.js · TypeScript · Go · PHP (Yii2)
  messaging       Kafka · RabbitMQ · Redis Streams
  data            PostgreSQL · MySQL · MongoDB · Redis
  api             REST · GraphQL
  infrastructure  Docker · Kubernetes · AWS
  patterns        Event-Driven · CQRS · Saga · Multi-Tenant · Outbox
```

<br/>

<!----------------------------------------------------------------------
  CURRENT RUNTIME
----------------------------------------------------------------------->

---

<br/>

### `◉  current runtime`

<br/>

```
  ╭─ system.runtime ─────────────────────────────────────────────────────╮
  │                                                                       │
  │   node          ankit-raj                                             │
  │   role          senior software engineer @ dayal infosystems          │
  │   uptime        3y+                                                   │
  │   status        ● OPERATIONAL                                         │
  │                                                                       │
  │   building  ──  ERP platform · retail · MSME · agritech verticals    │
  │                 multi-tenant workflow engine · event sourcing layer   │
  │                                                                       │
  │   exploring ──  Kafka internals · log compaction · consumer lag       │
  │                 distributed tracing · schema registry · OTEL          │
  │                 workflow orchestration patterns · temporal.io          │
  │                                                                       │
  │   reading   ──  Designing Data-Intensive Applications — Kleppmann     │
  │                                                                       │
  ╰───────────────────────────────────────────────────────────────────────╯
```

<br/>

<!----------------------------------------------------------------------
  FEATURED SYSTEMS
----------------------------------------------------------------------->

---

<br/>

### `◫  featured systems`

<br/>

<table>
<tr>
<td valign="top">

**`artemis`** &nbsp;·&nbsp; distributed task queue &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`Go` `Redis Streams` `Docker`

Redis Streams-backed job queue with priority scheduling, exponential backoff retries, delayed execution windows, and a dead-letter pipeline. Designed for predictable failure semantics — the system degrades gracefully and surfaces errors clearly rather than silently dropping work.

→ [github.com/ankitraj5ar/artemis](https://github.com/ankitraj5ar)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td valign="top">

**`cascade`** &nbsp;·&nbsp; real-time event pipeline &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`Python` `Kafka` `PostgreSQL` `Kubernetes`

Webhook ingestion and routing system processing ~50k events/day at sub-100ms p99. Fan-out to multiple downstream consumers with at-least-once delivery guarantees, idempotency enforcement, and structured dead-letter handling per consumer.

→ [github.com/ankitraj5ar/cascade](https://github.com/ankitraj5ar)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td valign="top">

**`hatchet api`** &nbsp;·&nbsp; multi-tenant B2B API layer &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`TypeScript` `Node.js` `PostgreSQL` `GraphQL`

GraphQL + REST API with row-level security, full multi-tenant isolation, rate limiting per tenant tier, and a webhook delivery subsystem with configurable retry logic, exponential backoff, and per-endpoint delivery tracking.

→ [github.com/ankitraj5ar/hatchet](https://github.com/ankitraj5ar)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td valign="top">

**`vault cli`** &nbsp;·&nbsp; secrets manager &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`Go` `AES-256` `GPG`

CLI tool for managing secrets across environments. Encrypts values at rest using AES-256, supports team secret sharing via GPG key exchange, and integrates into CI/CD pipelines through stdin/stdout contracts.

→ [github.com/ankitraj5ar/vault-cli](https://github.com/ankitraj5ar)

</td>
</tr>
</table>

<br/>

<!----------------------------------------------------------------------
  GITHUB ACTIVITY
----------------------------------------------------------------------->

---

<br/>

### `⌁  activity`

<br/>

<div align="center">

<img
  height="155"
  src="https://github-readme-stats.vercel.app/api?username=ankitraj5ar&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=f0f0f0&text_color=444444&icon_color=333333&count_private=true&hide_title=true&hide_rank=false&rank_icon=percentile"
  alt="GitHub Stats"
/>
&nbsp;&nbsp;
<img
  height="155"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=ankitraj5ar&layout=compact&hide_border=true&bg_color=0d0d0d&title_color=f0f0f0&text_color=444444&langs_count=6&hide_title=true"
  alt="Top Languages"
/>

</div>

<br/>

<div align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=ankitraj5ar&bg_color=0d0d0d&color=333333&line=1e1e1e&point=444444&hide_border=true&area=true&area_color=1a1a1a"
    width="96%"
    alt="Contribution Graph"
  />
</div>

<br/>

<!----------------------------------------------------------------------
  CONTACT
----------------------------------------------------------------------->

---

<br/>

### `✦  connect`

<br/>

```
  email      ankitraj5ar@gmail.com
  linkedin   linkedin.com/in/ankitraj5ar
  github     github.com/ankitraj5ar
  web        ankitraj5ar.online
```

<br/>

---

<br/>

<div align="center">
  <sub><code>systems that are correct · observable · operable</code></sub>
</div>

<br/>
