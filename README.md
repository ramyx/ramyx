<h1 align="center">Ramiro Martinez</h1>

<p align="center">
  <strong>Senior Full Stack Developer</strong><br>
  TypeScript · Node.js · React · Applied AI
</p>

<p align="center">
  <a href="https://www.ramiromartinez.com.ar/">
    <img src="https://img.shields.io/badge/Website-ramiromartinez.com.ar-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
  </a>
  <a href="mailto:ramiro.daniel.ing@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/ramyx?tab=followers">
    <img src="https://img.shields.io/github/followers/ramyx?style=for-the-badge&logo=github&color=181717&labelColor=181717" alt="Followers">
  </a>
</p>

---

### About

I build production systems end to end — from the type-safe backend to the interface, and
increasingly at the boundary where LLMs meet real operating systems and real APIs.

- 🧠 Currently working on **local-first AI agents** with hard security guarantees — the model
  proposes, a deterministic policy engine decides.
- 🔍 I like problems where the interesting part is the **constraint**: guest-token auth, sandbox
  escapes, rate limits, output contracts that must not drift.
- 🧪 I ship with tests against captured fixtures, not against the live world.
- 🌎 Based in Argentina, working with distributed teams.

---

### Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Material UI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Infra & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🗣️ [yanapaq](https://github.com/ramyx/yanapaq)

A **100% local** voice assistant for Ubuntu, built on DeepSeek Harness.

The LLM proposes; a deterministic policy engine decides. No code path reaches the OS without
passing through `policy_engine.evaluate()` — backed by a Landlock ruleset the gateway applies
to itself at startup, plus a dedicated user with ACLs.

`TypeScript` `Python` `Linux` `MCP`

</td>
<td width="50%" valign="top">

#### 🐦 [x-tweet-scraper](https://github.com/ramyx/x-tweet-scraper)

Browserless X (Twitter) scraper for **Apify**.

HTTP-only against X's internal GraphQL with guest-token auth, a strict output contract, and a
server-authoritative free-tier gate. 170 tests, all offline against captured fixtures — and a
test that fails the build if a browser engine ever enters the dependency tree.

`TypeScript` `GraphQL` `Docker` `Apify`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📊 [material-dashboard-reactts](https://github.com/ramyx/material-dashboard-reactts)

⭐ **35 stars** — TypeScript port of Creative Tim's Material Dashboard for React.

A fully typed rewrite that keeps the original design system intact while giving the codebase
real type safety.

`TypeScript` `React` `Material UI`

</td>
<td width="50%" valign="top">

#### 📈 [cripto-b-alert](https://github.com/ramyx/cripto-b-alert)

Telegram bot on top of the Binance API for live market alerts.

`TypeScript` `Node.js` `Telegram` `Binance`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 👁️ [eye-of-the-ping](https://github.com/ramyx/eye-of-the-ping)

Desktop app that watches your local network and notifies you as devices join or leave, tracking
them by IP and MAC.

`Python` `Networking`

</td>
<td width="50%" valign="top">

#### 🧾 [baselabs-challenge](https://github.com/ramyx/baselabs-challenge)

Policy administration slice: prorates a mid-term endorsement to the cent, posts balanced
double-entry ledger effects, and keeps an append-only hash-chained policy history.

Raw SQL, no ORM — `pg` and `zod` are the only runtime dependencies.

`TypeScript` `Next.js` `PostgreSQL`

</td>
</tr>
</table>

---

### At a Glance

<p align="center">
  <img alt="Public repositories" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Framyx&query=%24.public_repos&label=public%20repos&style=for-the-badge&logo=github&color=181717&labelColor=181717">
  <img alt="Followers" src="https://img.shields.io/github/followers/ramyx?style=for-the-badge&logo=github&color=0A66C2&labelColor=181717">
  <img alt="Stars on material-dashboard-reactts" src="https://img.shields.io/github/stars/ramyx/material-dashboard-reactts?style=for-the-badge&logo=github&label=top%20repo%20stars&color=E3B341&labelColor=181717">
</p>

<p align="center">
  <img alt="yanapaq last commit" src="https://img.shields.io/github/last-commit/ramyx/yanapaq?style=flat-square&logo=git&logoColor=white&label=yanapaq">
  <img alt="x-tweet-scraper last commit" src="https://img.shields.io/github/last-commit/ramyx/x-tweet-scraper?style=flat-square&logo=git&logoColor=white&label=x-tweet-scraper">
  <img alt="baselabs-challenge last commit" src="https://img.shields.io/github/last-commit/ramyx/baselabs-challenge?style=flat-square&logo=git&logoColor=white&label=baselabs-challenge">
</p>

<!--
  Stats cards from github-readme-stats are disabled: the public instance
  (github-readme-stats.vercel.app) was returning HTTP 503 and rendered as broken
  images. Uncomment the block below if the service comes back.

  <p align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ramyx&show_icons=true&hide_border=true&theme=github_dark&count_private=true&include_all_commits=true">
      <img height="165" src="https://github-readme-stats.vercel.app/api?username=ramyx&show_icons=true&hide_border=true&theme=default&count_private=true&include_all_commits=true" alt="GitHub stats">
    </picture>
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ramyx&layout=compact&hide_border=true&theme=github_dark&langs_count=8">
      <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramyx&layout=compact&hide_border=true&theme=default&langs_count=8" alt="Top languages">
    </picture>
  </p>
-->

---

<p align="center">
  <em>Open to interesting problems — reach me at
  <a href="mailto:ramiro.daniel.ing@gmail.com">ramiro.daniel.ing@gmail.com</a>
  or <a href="https://www.ramiromartinez.com.ar/">ramiromartinez.com.ar</a>.</em>
</p>
