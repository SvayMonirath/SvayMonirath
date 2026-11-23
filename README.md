
# Svay Monirath

**Software Engineer** · Phnom Penh, Cambodia
[Email](mailto:svaymonirathofficial@gmail.com) · [GitHub](https://github.com/SvayMonirath) ·
[LinkedIn](https://linkedin.com/in/svay-monirath)

I build real-time voice backends, developer tools, and resilient agent workflows.

---

## How I Build With AI

Most AI coding tools say yes to bad ideas and write fragile code. My workflow stops bad ideas
before they become bugs by pitting models against each other and letting real compilers grade the
output:

```text
Goal ──► [ Plan Review Swarm ] ──► [ Sandboxed Test Loop ] ──► [ Human Review & Ship ]
         Cross-model debate        Terminal auto-fixes         Verify diff & tests
         (Evidence over consensus) (Compiler is truth)         (Tech lead sign-off)
```

- **Cross-examination over consensus**: Before touching code, multiple models debate the
architecture to spot blind spots and security traps. We don't force agreement; we look for the best
path backed by empirical evidence.
- **Sandboxed build & test loop**: Once the plan is solid, a coding agent works in an isolated
sandbox. Terminal tests (`vitest`, `pytest`, `tsc`) run automatically, looping error traces back
until all tests pass.
- **Human in control**: I act as the tech lead—reviewing the clean git diff and test evidence
before anything touches production.

---

## What I Built & What I Learned

- **Cosmo** (Agent Workspace): Isolated Docker sandboxes for autonomous coding agents.
  *Lesson:* Always mount test files as read-only, otherwise agents will literally pass a failing
  build by deleting the test assertions.

- **Veaja** (Voice AI Platform): Sub-second duplex voice receptionist handling phone calls across
59 languages.
  *Lesson:* Prompt engineering cannot fix dropped audio; real-time voice lives or dies by WebSocket
  packet buffers and low latency.

- **Wisp** (Audio Studio): In-browser vocal pitch tracker and offline-first audio editor.
  *Lesson:* Heavy UI frameworks destroy 60fps audio; lightweight browser-native state machines beat
  bloated libraries every time.

- **Better Communication** (Scenario Simulator): Interactive negotiation practice with realistic AI
counter-parties.
  *Lesson:* People don't learn from polite chatbots; real confidence comes from failing hard,
  realistic scenarios.

---

## Tech Stack

**Languages:** TypeScript, Python, C++, Go
**Backend & Real-Time:** NestJS, FastAPI, Fastify, WebSockets, WebRTC
**Data & Infra:** PostgreSQL, Redis, Docker, Temporal, Linux
