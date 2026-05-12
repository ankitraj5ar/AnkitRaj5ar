<!-- ============================================================
     ANKIT RAJ — GitHub Profile README
     Inspired by: ankitraj5ar.online
     Color Palette: Deep Navy #0A0F1E → Indigo #1A2B6B | Accent #58A6FF
     ============================================================ -->

<!-- ─── HEADER BANNER ─── -->
<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0A0F1E,40:0F1A35,100:1A2B6B&height=230&section=header&text=Ankit%20Raj&fontSize=58&fontColor=C9D8FF&animation=fadeIn&fontAlignY=40&desc=Backend%20Engineer%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20ERP%20Architecture&descAlignY=60&descSize=16&descColor=7B9CFF)

</div>

<!-- ─── TYPING ANIMATION ─── -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3000&pause=1200&color=7B9CFF&center=true&vCenter=true&width=750&lines=Designing+systems+that+survive+production.;Reliability+is+not+a+feature+%E2%80%94+it%E2%80%99s+the+baseline.;Kafka+%C2%B7+RabbitMQ+%C2%B7+PostgreSQL+%C2%B7+Redis;Event-driven+%C2%B7+Multi-tenant+%C2%B7+Built+for+scale.;Backend+is+where+the+real+decisions+live.)](https://github.com/ankitraj5ar)

</div>

<br/>

---

<!-- ─── STATEMENT ─── -->

<div align="center">

*The measure of a system is not how it performs at launch —*<br/>
*but whether it holds under the load you never planned for.*

</div>

---

<br/>

<!-- ─── ABOUT ─── -->

```yaml
# engineer.yml

name    : Ankit Raj
role    : Software Engineer — Backend & Distributed Systems
exp     : 3+ years designing APIs, ERP platforms, event-driven systems

focus:
  - Multi-tenant ERP infrastructure
  - Event-driven architecture with Kafka & RabbitMQ
  - Distributed system design and reliability
  - Workflow orchestration across complex business domains

mindset : Correctness first. Performance where it matters. Simplicity where it's earned.
status  : open to the right opportunity
```

<br/>

---

<!-- ─── ARCHITECTURE DIAGRAM ─── -->

<div align="center">

### How I think about systems

</div>

```mermaid
flowchart TD
    Client(["⚡ Client"]):::node --> GW

    subgraph GW["API Gateway Layer"]
        direction LR
        AG["Rate Limiting\nAuth · Routing"]:::box
    end

    GW --> ERP & AUTH

    subgraph CORE["Service Layer"]
        direction TB
        ERP["🏢 ERP Core\nBusiness Logic"]:::box
        AUTH["🔐 Auth Service\nJWT · RBAC"]:::box
        WF["⚙️ Workflow Engine\nState · Orchestration"]:::box
        ERP --> WF
    end

    WF & ERP --> MQ

    subgraph MQ["Messaging Layer"]
        direction LR
        RMQ["🐇 RabbitMQ\nTask Queues · Dead-letter"]:::msg
        KFK["⚡ Kafka\nEvent Streams · CDC"]:::msg
        RMQ --> KFK
    end

    ERP --> DATA
    WF --> DATA
    KFK --> ANALYTICS

    subgraph DATA["Data Layer"]
        direction LR
        PG[("🐘 PostgreSQL\nSource of Truth")]:::db
        RD[("⚡ Redis\nCache · Sessions")]:::db
    end

    subgraph ANALYTICS["Observability"]
        direction LR
        PM["📊 Prometheus\n+ Grafana"]:::obs
    end

    classDef node fill:#1A2B6B,stroke:#58A6FF,color:#C9D8FF,rx:8
    classDef box  fill:#0F1A35,stroke:#3B5FC0,color:#C9D8FF,rx:4
    classDef msg  fill:#0D2240,stroke:#2563EB,color:#93C5FD,rx:4
    classDef db   fill:#0A1628,stroke:#1E40AF,color:#7B9CFF,rx:4
    classDef obs  fill:#0A1628,stroke:#6366F1,color:#A5B4FC,rx:4
```

<br/>

---

<!-- ─── TECH STACK ─── -->

<div align="center">

### Tech I work with

[![Tech Stack](https://skillicons.dev/icons?i=python,ts,js,nodejs,fastapi,express,postgres,mysql,redis,rabbitmq,kafka,docker,kubernetes,aws,linux,git&theme=dark)](https://ankitraj5ar.online)

</div>

<br/>

---

<!-- ─── GITHUB ANALYTICS ─── -->

<div align="center">

### GitHub Analytics

<img src="https://github-readme-stats.vercel.app/api?username=ankitraj5ar&show_icons=true&hide_border=true&bg_color=0A0F1E&title_color=7B9CFF&icon_color=58A6FF&text_color=94A3B8&include_all_commits=true&count_private=true" height="165"/>
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ankitraj5ar&hide_border=true&background=0A0F1E&ring=58A6FF&fire=7B9CFF&currStreakLabel=94A3B8&sideLabels=94A3B8&dates=64748B&sideNums=C9D8FF&currStreakNum=C9D8FF" height="165"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ankitraj5ar&theme=react-dark&hide_border=true&bg_color=0A0F1E&color=7B9CFF&line=3B5FC0&point=58A6FF&area=true&area_color=1A2B6B" width="94%"/>

</div>

<br/>

---

<!-- ─── CONNECT ─── -->

<div align="center">

[![Portfolio](https://img.shields.io/badge/ankitraj5ar.online-0A0F1E?style=for-the-badge&logo=vercel&logoColor=7B9CFF)](https://ankitraj5ar.online)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0F1E?style=for-the-badge&logo=linkedin&logoColor=7B9CFF)](https://linkedin.com/in/ankitraj5ar)
&nbsp;
[![Email](https://img.shields.io/badge/Email-0A0F1E?style=for-the-badge&logo=gmail&logoColor=7B9CFF)](mailto:ankitraj5ar@gmail.com)

</div>

<br/>

<!-- ─── FOOTER ─── -->
<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:1A2B6B,60:0F1A35,100:0A0F1E&height=100&section=footer)

</div>
