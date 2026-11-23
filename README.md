# Svay Monirath

**Software Engineer** · Phnom Penh, Cambodia  
[Email](mailto:svaymonirathofficial@gmail.com) · [GitHub](https://github.com/SvayMonirath) · [LinkedIn](https://linkedin.com/in/svay-monirath)

I build real-time voice backends, developer tools, and agent workflows that ship reliable software without the chaos.

---

## How I Build With AI

Most AI tools act like eager junior devs: you give them a bad idea, they say *"Looks great!"*, and write 500 lines of broken code.

Here is the everyday workflow I use to catch bad ideas early and let tests do the grading:

```text
 1. GOAL                 2. AGENT CHALLENGE (Planning)           3. BUILD & TEST LOOP (Coding)            4. SHIP
┌──────────────┐        ┌───────────────────────────────┐       ┌──────────────────────────────┐        ┌──────────────┐
│ You describe │  ───►  │ Planner writes the plan       │ ───►  │ Coder writes the code        │  ───►  │ You check    │
│ what you     │        │        ▲              │       │       │        ▲             │       │        │ the changes  │
│ want to      │        │        │ (Fixes plan) ▼       │       │        │ (Fixes bug) ▼       │        │ and deploy   │
│ build        │        │ Critic attacks flaws & traps  │       │ Terminal runs tests          │        │ to prod      │
└──────────────┘        │ (Multiple models check gaps)  │       │ (If tests fail, loops back)  │        └──────────────┘
                        └───────────────────────────────┘       └──────────────────────────────┘
```

1. **The Planning Challenge**: Before writing code, one agent drafts the plan and other models attack it. They hunt for edge cases, security holes, and missing pieces. We don't just stop because two models agree—we keep questioning the design until we're sure it actually works.
2. **The Build & Test Loop**: Once the plan is solid, a coding agent writes the code and runs the test suite in the terminal. If a test fails, the terminal error goes right back to the agent to fix itself. It loops until all tests pass.
3. **Final Review**: I inspect the code changes, make sure the tests are real, and ship it.

---

## What I Built & What I Learned

- **Cosmo (Agent Workspace)**: Isolated sandboxes for AI coding agents.  
  *Lesson:* Always mount test files as read-only, otherwise agents will literally pass failing builds by deleting the test assertions.

- **Veaja (Real-Time Voice AI)**: Low-latency voice platform across 59 languages.  
  *Lesson:* Prompt engineering cannot fix dropped audio packets; real-time voice lives or dies by WebSocket packet buffers and low latency.

- **Wisp (Audio Studio)**: In-browser vocal pitch tracker and offline-first audio editor.  
  *Lesson:* Heavy UI frameworks destroy 60fps audio; lightweight browser-native state machines beat bloated libraries every time.

- **Better Communication (Conversation Simulator)**: Practice simulator for difficult workplace conversations.  
  *Lesson:* People don't learn from polite chatbots; real confidence comes from failing hard, realistic scenarios.

---

## Tech Stack

- **Languages:** TypeScript, Python, C++, Go
- **Backend & Real-Time:** NestJS, FastAPI, Fastify, WebSockets, WebRTC
- **Data & Tools:** PostgreSQL, Redis, Docker, Linux
