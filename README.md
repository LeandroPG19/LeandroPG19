<div align="center">

<img src="zeref.gif" width="380" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3000&pause=1000&color=FFB300&center=true&vCenter=true&width=760&lines=Leandro+P%C3%A9rez+G.+%E2%80%94+Systems+Architect;Industrial+Automation+%C2%B7+MES+%C2%B7+CNC;Deterministic+Infra+%E2%80%94+Rust+%C2%B7+Python+%C2%B7+TypeScript;Zero+Residual+Risk+by+Design)](https://github.com/LeandroPG19)

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.14-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MES](https://img.shields.io/badge/MES_·_SCADA-37474F?style=flat-square)
![Status](https://img.shields.io/badge/STATUS-●_ONLINE-3FB950?style=flat-square)

</div>

---

```
┌─ OPERATOR ───────────────────────────────────────────
│ NAME     Leandro Pérez G.
│ ROLE     Systems Architect @ SIIOSA
│ DOMAIN   Industrial Automation · MES · CNC manufacturing
│ STACK    Rust (2024) · Python 3.14 · TypeScript · PostgreSQL 18
│ FOCUS    Deterministic control infra · agent memory · telemetry
│ STATUS   ● ONLINE — shipping zero-residual-risk systems
└──────────────────────────────────────────────────────
```

## `//` SYSTEM OVERVIEW

Systems Architect building **industrial automation infrastructure** for CNC manufacturing environments — the layer between the PLC and the plant floor where a bug is not a stack trace, it's physical damage. I design deterministic, fully-auditable control and data systems in **Rust, Python 3.14 and Next.js**.

I also build the **`cuba-*` MCP ecosystem**: persistent agent memory with Hebbian learning and knowledge graphs, multi-step reasoning engines, real-time web intelligence, and sandboxed execution — the same discipline applied to AI infrastructure.

```rust
// The control law everything else inherits from.
loop {
    let telemetry = plc.poll();                 // OPC-UA / Modbus TCP
    match controller.evaluate(telemetry) {
        Ok(command) => actuator.dispatch(command),
        Err(fault)  => safe_state.engage(fault), // fail-closed, always
    }
}
```

```rust
const DOCTRINE: [&str; 3] = [
    "Zero Residual Risk    — 100% simulable, auditable, reversible logic",
    "Defensive by Design   — strict typing, immutability, ACID integrity",
    "Continuous Automation — if it needs a human, it's a bug",
];
```

---

## `//` SUBSYSTEMS

<div align="center">

**Core / Systems**

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend · Data · Telemetry**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Granian](https://img.shields.io/badge/Granian-CE422B?style=flat-square&logo=rust&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_18-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Industrial / Fieldbus**

![OPC-UA](https://img.shields.io/badge/OPC--UA-0A5C36?style=flat-square)
![Modbus](https://img.shields.io/badge/Modbus_TCP-1A5276?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![CNC](https://img.shields.io/badge/CNC_·_G--code-37474F?style=flat-square)
![21 CFR](https://img.shields.io/badge/21_CFR_Part_11-263238?style=flat-square)

**HMI / Frontend**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Infra / Runtime**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1793D1?style=flat-square&logo=linux&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-8A2BE2?style=flat-square&logo=anthropic&logoColor=white)

</div>

---

## `//` cuba-* ECOSYSTEM

```mermaid
flowchart LR
    AGENT(["AI Agent / IDE"]):::agent

    AGENT --> MEM["cuba-memorys<br/>persistent brain · knowledge graph"]:::core
    AGENT --> THINK["cuba-thinking<br/>6-stage reasoning engine"]:::core
    AGENT --> SEARCH["cuba-search<br/>web intelligence · SSRF-safe"]:::core
    AGENT --> EXEC["cuba-exec<br/>sandboxed execution"]:::core

    MEM --> PG[("PostgreSQL<br/>pgvector · HNSW")]:::data
    EXEC --> OS["Linux / POSIX<br/>bounded output · signals"]:::data

    classDef agent fill:#161B22,stroke:#FFB300,stroke-width:2px,color:#FFB300;
    classDef core  fill:#0D1117,stroke:#FF6F00,stroke-width:1px,color:#C9D1D9;
    classDef data  fill:#0D1117,stroke:#3FB950,stroke-width:1px,color:#C9D1D9;
```

---

## `//` ACTIVE MODULES

<div align="center">

<a href="https://github.com/LeandroPG19/cuba-memorys">
  <img src="https://opengraph.githubassets.com/1/LeandroPG19/cuba-memorys" width="49%" />
</a>
<a href="https://github.com/LeandroPG19/cuba-thinking">
  <img src="https://opengraph.githubassets.com/1/LeandroPG19/cuba-thinking" width="49%" />
</a>

<a href="https://github.com/LeandroPG19/cuba-search">
  <img src="https://opengraph.githubassets.com/1/LeandroPG19/cuba-search" width="49%" />
</a>
<a href="https://github.com/LeandroPG19/cuba-exec">
  <img src="https://opengraph.githubassets.com/1/LeandroPG19/cuba-exec" width="49%" />
</a>

</div>

---

## `//` SYSTEM TELEMETRY

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=LeandroPG19&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=0D1117&title_color=FFB300&icon_color=FF6F00&text_color=C9D1D9" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeandroPG19&layout=compact&hide_border=true&langs_count=8&bg_color=0D1117&title_color=FFB300&text_color=C9D1D9" width="40%" />

<br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=LeandroPG19&bg_color=0D1117&color=FFB300&line=FF6F00&point=C9D1D9&area=true&hide_border=true&custom_title=Contribution%20Telemetry" width="98%" />

</div>

---

## `//` UPLINK

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/leandropg19)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:leandropatodo@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=LeandroPG19&color=FFB300&style=flat-square&label=OPERATOR+VIEWS)

</div>
