<div align="center">

<img src="assets/hero.svg" alt="Leandro Pérez G. — Systems Architect, Industrial Automation. Isometric plant cell: a white hygienic-design 6-axis robot MIG girth-welding a turbofan engine casing on rotating rollers, a safety light curtain, a welding power source, a robot controller and gas cylinders, a CNC machining center, a PLC cabinet and a Redis and PostgreSQL server rack." width="880" />

<img src="assets/ticker.svg" alt="Simulated plant telemetry ticker" width="880" />

<br />

<img src="https://skillicons.dev/icons?i=rust,python,fastapi,redis,postgres,typescript,nextjs,docker,linux,grafana,prometheus&theme=dark" alt="Rust, Python, FastAPI, Redis, PostgreSQL, TypeScript, Next.js, Docker, Linux, Grafana, Prometheus" />

<br />

![OPC-UA](https://img.shields.io/badge/OPC--UA-0A5C36?style=flat-square)
![Modbus](https://img.shields.io/badge/Modbus_TCP-1A5276?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![ISA-95](https://img.shields.io/badge/ISA--95-455A64?style=flat-square)
![21 CFR](https://img.shields.io/badge/21_CFR_Part_11-263238?style=flat-square)

<br />

<img src="assets/pipeline.svg" alt="Data path: PLC and CNC, Rust ingest, Redis Streams, Python workers, PostgreSQL. A fault drives the system to a safe state." width="880" />

<img src="assets/orbit.svg" alt="Stack in orbit around the MES core" width="880" />

<img src="assets/code.svg" alt="Rust ingest loop and Python stream worker" width="880" />

<img src="assets/dashboard.svg" alt="Simulated plant monitoring dashboard" width="880" />

</div>

## Engineering rules

| Rule | In practice |
|---|---|
| Fail closed | A fault or an invalid reading puts the service in a safe state. It never guesses. |
| Idempotent writes | Every write carries a key, so a retry cannot repeat a physical action. |
| Expand, then contract | Migrations stay compatible with the previous binary. |
| Red test first | Shared records get a deterministic interleaving test, and each guard is sabotaged to prove it fails. |

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [Memorys](https://github.com/LeandroPG19/Memorys) | Persistent memory MCP server for AI agents: knowledge graph, episodic memory, contradiction detection and Bayesian calibration. Open source. | <img src="https://skillicons.dev/icons?i=rust,docker&theme=dark" height="26" alt="rust,docker" /> |
| Industrial MES platform | Manufacturing execution backend for the plant floor: Rust services, PostgreSQL as the source of truth. Private. | <img src="https://skillicons.dev/icons?i=rust,postgres,redis&theme=dark" height="26" alt="rust,postgres,redis" /> |
| CNC tooling | Parametric CNC simulator and CAM tooling for machine shops. Private. | <img src="https://skillicons.dev/icons?i=python,fastapi,nextjs&theme=dark" height="26" alt="python,fastapi,nextjs" /> |

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LeandroPG19/LeandroPG19/output/snake.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LeandroPG19/LeandroPG19/output/snake-light.svg" />
  <img alt="contribution sweep" src="https://raw.githubusercontent.com/LeandroPG19/LeandroPG19/output/snake.svg" width="98%" />
</picture>

<br /><br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/leandropg19)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:leandropatodo@gmail.com)

</div>
