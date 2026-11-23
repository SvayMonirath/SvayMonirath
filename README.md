# Svay Monirath

Hey, I'm Monirath. I build backend services, real-time voice infrastructure, and autonomous agent workflows.

Most of my day is spent writing TypeScript, Python, and C++, designing streaming pipelines, and figuring out how to make AI agents actually reliable in production.

---

### How I Build with AI

Anyone can send a prompt to an LLM. In production, models are unpredictable—real software cannot be.

When I build agentic systems, I treat models like untrusted workers inside a strict software harness:
- **Small, isolated scopes**: Agents do one specific job in their own sandbox so they don't break other files.
- **Automated test loops**: Agent output doesn't touch real state until it passes tests and linters. If tests fail, the error trace goes right back to the agent to fix itself.
- **Hard permission gates**: Any risky action (deleting files, terminal commands, database writes) requires explicit confirmation.

---

### What I Work On

- **Agentic Dev Tools**: Building developer environments where scoped agents write, test, and review code with live browser sandboxes (Cosmo, Wisp).
- **Real-Time Voice & Audio**: Duplex audio streaming, voice activity detection, and speech pipelines across multiple languages.
- **Resilient Backends**: Asynchronous APIs (FastAPI, NestJS), durable workflows (Temporal) that survive server restarts, and WebSockets.

---

### Daily Stack

`TypeScript` · `Python` · `C++` · `FastAPI` · `NestJS` · `PostgreSQL` · `Redis` · `Docker` · `WebSockets`

---

### Connect

- Email: [svaymonirathofficial@gmail.com](mailto:svaymonirathofficial@gmail.com)
- GitHub: [@SvayMonirath](https://github.com/SvayMonirath)
