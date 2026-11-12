### Tim McGlothin

Infrastructure and security engineer (CISSP) building the plumbing AI agents need to do real operations work.

I've spent twenty years designing and securing enterprise infrastructure: security architecture across 200+ facilities, the integration of a 5,000-employee acquisition, and today a move from decades of shell scripts to infrastructure as code. At home I hold my AI agents to the same rules. They get only the access they need, and everything they write lands in git where I can audit it.

More about me and my work: **[about.timmcg.net](https://about.timmcg.net)**

#### What I'm building

| Project | What it is |
|---|---|
| [**ai-knowledge-base**](https://github.com/mcglothi/ai-knowledge-base) | Shared memory for AI agents: a git-backed Markdown knowledge base that nine agents (Claude Code, Codex, Gemini, Cursor, local models) read, write, search over MCP, and use to hand work to each other. Public template of the system I run daily. |
| [**portside**](https://github.com/mcglothi/portside) | A native macOS SSH workbench for people running fleets of Linux servers. Uses your existing OpenSSH config, SFTP over the same connection, guarded MultiExec. Signed, notarized, `brew install mcglothi/tap/portside`. |
| [**senseless**](https://github.com/mcglothi/senseless) | A local-first companion for the Sense energy monitor. I reverse-engineered the app's realtime protocol, documented it, and built a collector with Prometheus metrics and its own web UI. |
| [**opensoak**](https://github.com/mcglothi/opensoak) | A Raspberry Pi hot tub controller with latching safety faults, scheduled soaks, and heating cost analysis. |
| [**laptime**](https://github.com/mcglothi/laptime) | Feel what a tokens-per-second number means. Plays back LLM benchmarks across Apple Silicon, NVIDIA, DGX Spark-class and Strix Halo hardware. [laptime.run](https://laptime.run) |
| [**ai-hub**](https://github.com/mcglothi/ai-hub) | A self-hosted operator console for local LLM routing, memory operations and persistent agent sessions. |

#### How I work

I let evals set defaults. When a fix passes its tests, I revert it and check that the tests fail. Code one model writes gets reviewed by a different model before it ships. All of it runs in my lab every day, with monitoring on the services.

#### Toolbox

Linux · Ansible · Terraform · Python · Swift · Bash · AWS · Proxmox/KVM · Docker · Prometheus/Grafana · Zero Trust networking · local LLM inference · MCP
