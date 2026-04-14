<h1 align="center">Hey, I'm Akibuzzaman Akib 👋</h1>

<p align="center">
  <b>Full-Stack Web Developer · Python · Node.js · Open Source Contributor</b><br/>
  <i>Building things that matter. Contributing to projects that impact millions.</i>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vAlign=middle&width=500&lines=Full-Stack+Web+Developer;Python+%26+Node.js+Engineer;Open+Source+Contributor;6+Projects+%7C+7+Active+PRs;Always+learning%2C+always+building" alt="Typing SVG" />
</p>

---

## 🚀 About Me

- 🔭 Actively contributing to **6 major open source projects** (107K+ ⭐ to 32K+ ⭐)
- 🌱 Building production-grade features: converters, bug fixes, real-time services, security
- 💬 Ask me about **Python**, **Node.js**, **TypeScript**, **REST APIs**, **WebSockets**
- 🐳 Comfortable with **Docker**, **PostgreSQL**, **Redis**, **microservices**
- ⚡ Fun fact: My code runs inside Microsoft, axios, LangChain and more

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

---

## 🏆 Open Source Contributions

### 🔥 [microsoft/markitdown](https://github.com/microsoft/markitdown/pull/1769) — 107K+ ⭐
> Python tool for converting files and office documents to Markdown. Used by LLM pipelines worldwide.

| Contribution | Description |
|---|---|
| `TomlConverter` | Converts pyproject.toml, Cargo.toml etc. to structured Markdown |
| `SitemapConverter` | Converts XML sitemaps (urlset + sitemapindex) to Markdown link lists |
| `EnvConverter` | Converts .env files to redacted Markdown table (values masked by default) |
| `YamlConverter` | Converts .yaml/.yml files to structured Markdown |
| `RequirementsConverter` | Converts requirements.txt / Pipfile to Markdown table |
| `get_document_stats()` | Word/char/heading/code/link/image count utility on any result |
| 🐛 CSV pipe-escape | Fixed broken Markdown tables when cells contain `\|` or newlines |
| 🐛 ipynb cell outputs | Fixed missing stdout/stderr/traceback outputs in Jupyter notebooks |
| 🐛 Audio formats | Added .ogg/.flac/.aac support to AudioConverter |
| 🐛 Wikipedia infoboxes | Strip messy infoboxes/navboxes by default |
| 🐛 RSS links | Extract and include item/entry link URLs in RSS output |
| ✨ HTML metadata | OG tags / meta extraction via `include_html_metadata=True` |
**75 tests written · All passing**

---

### ⚡ [axios/axios](https://github.com/axios/axios/pull/10710) — 109K+ ⭐
> Promise-based HTTP client for Node.js and browser.

| Contribution | Description |
|---|---|
| TypeScript fix | Replaced loose `any` index signature on `AxiosHeaders` with precise union type |
| JSDoc | Added `@param`, `@returns`, `@example` docs to undocumented utility functions |

---

### 🐍 [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) — 219K+ ⭐
> All algorithms implemented in Python.

| PR | Contribution |
|---|---|
| [#14557](https://github.com/TheAlgorithms/Python/pull/14557) | `fibonacci_fast.py` — O(log n) Fibonacci via matrix exponentiation |
| [#14558](https://github.com/TheAlgorithms/Python/pull/14558) | `luhn_algorithm.py` — Luhn credit card number validation |
| [#14559](https://github.com/TheAlgorithms/Python/pull/14559) | Type hints improvements in `linear_search.py` |

---

### 🛒 [medusajs/medusa](https://github.com/medusajs/medusa/pull/15103) — 32K+ ⭐
> Open-source headless commerce platform.

| Contribution | Description |
|---|---|
| 🐛 AwilixResolutionError fix | Pass container to MedusaAppLoader in `runMigrationScripts` so `query` resolves correctly during DB migrations |

---

### 🐍 [cleitonleonel/pyquotex](https://github.com/cleitonleonel/pyquotex/pull/81)
> Python Quotex trading API client.

| Contribution | Description |
|---|---|
| ⚡ Async WebSocket | Replaced `websocket-client` (threaded) with `websockets` (pure async) |
| ⚡ Async HTTP | Replaced `requests` (sync) with `httpx` (async) + connection pooling |
| ⚡ orjson | Used `orjson` everywhere for 2-3x faster JSON parsing |
| 🎨 Rich CLI | Complete CLI rewrite with 8 subcommands, spinners, tables |
| 📦 Lighter deps | Removed 5 packages (~40% smaller install size) |

---

## 📦 Personal Projects

### [telegram-media-dl](https://github.com/AKIB473/telegram-media-dl)
> Production-grade Telegram bot for downloading media from 50+ sites

- **aiogram 3** — Only `BOT_TOKEN` needed, no API_ID/HASH
- aiosqlite database (user history, preferences, download logs)
- YouTube/site search, target chat auto-forward, user settings
- Async download queue, rate limiting, subtitle support
- Docker + GitHub Actions CI + 48 tests

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AKIB473&show_icons=true&theme=tokyonight&hide_border=true" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AKIB473&theme=tokyonight&hide_border=true" width="48%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AKIB473&layout=compact&theme=tokyonight&hide_border=true" width="48%"/>
</p>

---

## 📫 Connect With Me

<p align="left">
  <a href="https://github.com/AKIB473">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AKIB473&label=Profile%20views&color=0e75b6&style=flat" alt="AKIB473"/>
</p>

<p align="center"><i>"The best way to learn is to build something real and share it with the world."</i></p>
