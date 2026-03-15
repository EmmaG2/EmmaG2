# Emmanuel Granados

**Software Engineer** — React, Next.js, TypeScript, NestJS, Rust.
Building SaaS platforms, REST APIs, and native desktop apps.

📬 [fergranados.dev@outlook.com](mailto:fergranados.dev@outlook.com) · [LinkedIn](https://www.linkedin.com/in/ingfergranados) · [GitHub](https://github.com/EmmaG2) · [Codeforces](https://codeforces.com/profile/EmmaGranados)

---

## Tech Stack

### Frontend
<p align="left">
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="36" height="36" /></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="36" height="36" /></a>
  <a href="https://react.dev/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="36" height="36" /></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="36" height="36" /></a>
  <a href="https://tailwindcss.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="36" height="36" /></a>
  <a href="https://vitejs.dev/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vitejs/vitejs-original.svg" width="36" height="36" /></a>
</p>

### Backend
<p align="left">
  <a href="https://nodejs.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="36" height="36" /></a>
  <a href="https://nestjs.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" width="36" height="36" /></a>
  <a href="https://www.rust-lang.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="36" height="36" /></a>
</p>

### Databases
<p align="left">
  <a href="https://www.postgresql.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="36" height="36" /></a>
  <a href="https://www.mongodb.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="36" height="36" /></a>
  <a href="https://redis.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="36" height="36" /></a>
</p>

### Cloud & DevOps
<p align="left">
  <a href="https://aws.amazon.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="36" height="36" /></a>
  <a href="https://www.docker.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="36" height="36" /></a>
</p>

### Tools
<p align="left">
  <a href="https://git-scm.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="36" height="36" /></a>
  <a href="https://neovim.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neovim/neovim-original.svg" width="36" height="36" /></a>
  <a href="https://tauri.app/" target="_blank"><img src="https://cdn.simpleicons.org/tauri/FFC131" width="36" height="36" /></a>
  <a href="https://jestjs.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" width="36" height="36" /></a>
  <a href="https://stripe.com/" target="_blank"><img src="https://cdn.simpleicons.org/stripe/635BFF" width="36" height="36" /></a>
  <a href="https://socket.io/" target="_blank"><img src="https://cdn.simpleicons.org/socketdotio/010101" width="36" height="36" /></a>
</p>

---

## Featured Projects

### Nivora — SaaS Restaurant Management Platform

A full-stack multi-tenant SaaS for restaurant operations, built as a **Turborepo + pnpm monorepo** with a shared `@nivora/shared` TypeScript package.

**Frontend** — 5 specialized apps:
- 2 **Next.js** apps with SSR: customer-facing portal and public landing page
- 3 **React + Vite** SPAs: admin dashboard, restaurant dashboard, and inventory dashboard

**Backend** — **NestJS 11** REST API with Hexagonal Architecture and 4 DDD bounded contexts: identity, restaurant, reservation, and billing.

**Infrastructure**:
- PostgreSQL 16 with PostGIS on AWS RDS
- Redis atomic locks (`SET NX EX`) for concurrent reservation management
- Stripe payment integration (SetupIntent + PaymentIntent flows)

---

### Chemical Balancer & Compiler — Tauri + Rust + Vanilla JS

A native desktop application that parses and balances chemical equations using a **full compiler pipeline written in Rust**.

**Compiler pipeline** (Rust 2021):
Lexer → Parser (recursive descent) → Semantic Analyzer → Solver (Gaussian elimination with exact rational arithmetic — zero floating-point error)

**Frontend** — Vanilla HTML/CSS/JS inside a Tauri WebView with real-time visualization of all pipeline phases: tokens, AST, symbol table, and error catalog.

**Architecture**: Clean 3-layer design (Domain / Application / Interface), dual-interface (GUI + CLI) sharing one domain library. Rust ↔ JavaScript communication via Tauri IPC.

---

## Currently

- Building and iterating on the Nivora SaaS platform
- Exploring systems programming with Rust
- Competitive programming on Codeforces

---

<p align="center">
  <a href="https://github.com/EmmaG2">
    <img src="https://github-readme-stats.vercel.app/api?username=EmmaG2&show_icons=true&theme=dracula&hide_border=true&count_private=true&title_color=ff79c6&icon_color=ff79c6&text_color=f8f8f2&bg_color=282a36" width="48%" />
  </a>
  <a href="https://github.com/EmmaG2">
    <img src="https://github-readme-streak-stats.herokuapp.com?user=EmmaG2&theme=dracula&hide_border=true&ring=ff79c6&fire=ff79c6&currStreakLabel=ff79c6" width="48%" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/EmmaG2">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EmmaG2&layout=compact&theme=dracula&hide_border=true&title_color=ff79c6&text_color=f8f8f2&bg_color=282a36" width="50%" />
  </a>
</p>

---

## About Me

I started programming at 12 with Python, initially drawn to game development. Over time my interests shifted toward web and systems engineering. Today I work across the full stack — building React and Next.js frontends, NestJS REST APIs, and native desktop apps with Rust and Tauri. I care about clean architecture, performance, and writing code that lasts.

---

© 2025 **Emmanuel Granados**
