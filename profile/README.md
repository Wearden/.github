## Wearden

*Agent-based security hardening platform.* Wearden scans hosts against reviewed benchmarks, reports findings in one place and, only when an operator confirms it, applies typed and reversible hardening changes.

### Repositories

| Repository | Purpose |
| --- | --- |
| [core](https://github.com/Wearden/core) | Go API, PostgreSQL storage, web interface and AI-assisted report analysis |
| [agent-linux](https://github.com/Wearden/agent-linux) | Linux agent for Ubuntu 22.04 and 24.04 |
| [agent-windows](https://github.com/Wearden/agent-windows) | Windows agent for Windows 10, Windows 11 and Server 2022 |
| [proto](https://github.com/Wearden/proto) | JSON Schema and Go wire contracts shared by core and agents |
| [ruleset](https://github.com/Wearden/ruleset) | Benchmark content and native manifests |

*Agents are scan-only by default. Remediation requires local opt-in, a confirmed task from core and a private backup that allows rollback.*
