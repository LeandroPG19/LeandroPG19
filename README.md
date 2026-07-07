<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=FFB300&center=true&vCenter=true&width=560&lines=Systems+Architect+%C2%B7+Industrial+Automation;Deterministic+Infra+%E2%80%94+Rust+%C2%B7+Python+%C2%B7+TS;Zero+Residual+Risk+by+Design)](https://github.com/LeandroPG19)

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Status](https://img.shields.io/badge/●_ONLINE-3FB950?style=flat-square)

</div>

```
┌─ OPERATOR ──────────────────────────────────────────
│ Leandro Pérez G. — Systems Architect @ SIIOSA
│ Industrial Automation · MES · CNC · deterministic infra
│ ● ONLINE — zero residual risk by design
└─────────────────────────────────────────────────────
```

```rust
loop {
    let telemetry = plc.poll();                 // OPC-UA / Modbus TCP
    match controller.evaluate(telemetry) {
        Ok(command) => actuator.dispatch(command),
        Err(fault)  => safe_state.engage(fault), // fail-closed, always
    }
}
```

<div align="center">

<img src="https://skillicons.dev/icons?i=rust,python,typescript,fastapi,nextjs,react,postgres,redis,docker,linux,grafana,prometheus&theme=dark" />

![OPC-UA](https://img.shields.io/badge/OPC--UA-0A5C36?style=flat-square)
![Modbus](https://img.shields.io/badge/Modbus_TCP-1A5276?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![CNC](https://img.shields.io/badge/CNC_·_G--code-37474F?style=flat-square)
![21 CFR](https://img.shields.io/badge/21_CFR_Part_11-263238?style=flat-square)
![ISA-95](https://img.shields.io/badge/ISA--95-455A64?style=flat-square)

</div>

<div align="center">

**Industrial Automation Stack — ISA-95**

```mermaid
flowchart TB
    L4["ERP — Business / Planning"]:::steel
    L3["MES — Manufacturing Execution · Rust · FastAPI · PostgreSQL"]:::amber
    L2["SCADA / HMI — Supervision · Next.js · Grafana"]:::orange
    L1["PLC — Real-Time Control · IEC 61131"]:::blue
    L0["FIELD — Sensors · CNC · Actuators · OPC-UA / Modbus"]:::green
    L4 --> L3 --> L2 --> L1 --> L0
    classDef steel  fill:#0D1117,stroke:#8B949E,color:#C9D1D9;
    classDef amber  fill:#161B22,stroke:#FFB300,stroke-width:3px,color:#FFB300;
    classDef orange fill:#0D1117,stroke:#FF6F00,color:#C9D1D9;
    classDef blue   fill:#0D1117,stroke:#4169E1,color:#C9D1D9;
    classDef green  fill:#0D1117,stroke:#3FB950,color:#C9D1D9;
```

<sub>Commands flow down · telemetry flows up — I architect the MES layer.</sub>

<br /><br />

<img src="https://github-readme-stats.vercel.app/api?username=LeandroPG19&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&hide_title=true&bg_color=0D1117&icon_color=FF6F00&text_color=C9D1D9" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeandroPG19&layout=compact&hide_border=true&hide_title=true&langs_count=6&bg_color=0D1117&text_color=C9D1D9" height="150" />

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LeandroPG19/LeandroPG19/output/snake.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LeandroPG19/LeandroPG19/output/snake-light.svg" />
  <img alt="contribution telemetry sweep" src="https://raw.githubusercontent.com/LeandroPG19/LeandroPG19/output/snake.svg" width="98%" />
</picture>

<sub>▸ contribution sweep — auto-generated every 12 h by GitHub Actions</sub>

<br /><br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/leandropg19)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:leandropatodo@gmail.com)
![Views](https://komarev.com/ghpvc/?username=LeandroPG19&color=FFB300&style=flat-square&label=views)

</div>
