<h1 align="center">Akibuzzaman Akib</h1>

<p align="center">
  <b>Full-Stack Developer &nbsp;·&nbsp; Python &nbsp;·&nbsp; Node.js &nbsp;·&nbsp; Open Source</b><br/>
  <i>I send PRs to projects with 100K+ stars and get rejected. Then I send better ones.</i>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vAlign=middle&width=550&lines=Open+Source+Contributor;Python+%26+Node.js+Developer;Browser+Fingerprinting+Researcher;Android+CI%2FCD+Builder;Rejected+9+Times+%E2%80%94+Still+Here" alt="Typing SVG" />
</p>

---

## About Me

- 🔥 Contributed to **7 major open source repos** (32K – 219K ⭐)
- 🏗️ Built **web-to-apk** — HTML → signed Android APK with zero setup
- 🔬 Built **uniq-web-id** — persistent browser identity based on academic research
- 📨 Sent PRs to Microsoft, LangChain, axios, medusa, uptime-kuma, TheAlgorithms, pip, arrow
- 💡 Got rejected a few times. Learned why. Fixed it. Sent better ones.
- ⚡ Stack: Python · TypeScript · Node.js · Capacitor · GitHub Actions · PostgreSQL · Redis

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
</p>

---

## 🏆 Open Source Contributions

> Real PRs. Real repos. Some merged, some pending, some rejected — all honest.

---

### 📝 [microsoft/markitdown](https://github.com/microsoft/markitdown/pull/1769) — 107K+ ⭐ · `Open`
**Python tool for converting files to Markdown. Used inside LLM pipelines worldwide.**

Added 6 new converters + fixed 7 bugs + added `get_document_stats()` utility:

| | What |
|---|---|
| ✨ `TomlConverter` | pyproject.toml, Cargo.toml → structured Markdown |
| ✨ `SitemapConverter` | XML sitemaps → Markdown link lists with metadata |
| ✨ `EnvConverter` | .env files → masked Markdown table (secrets safe by default) |
| ✨ `YamlConverter` | .yaml/.yml → structured Markdown |
| ✨ `RequirementsConverter` | requirements.txt / Pipfile → Markdown table |
| ✨ `get_document_stats()` | word/char/heading/code/link count on any result |
| 🐛 ipynb outputs | Fixed missing stdout/stderr/traceback in Jupyter notebooks |
| 🐛 CSV pipe-escape | Fixed broken tables when cells contain `\|` |
| 🐛 Audio formats | Added .ogg / .flac / .aac to AudioConverter |
| 🐛 Wikipedia infoboxes | Strip cluttered infoboxes/navboxes by default |
| 🐛 RSS links | Extract item/entry links into output |
| 🐛 OG metadata | HTML Open Graph + meta tag extraction |

*75 tests added · All passing*

---

### 🛒 [medusajs/medusa](https://github.com/medusajs/medusa/pull/15103) — 32K+ ⭐ · `Open`
**Headless commerce platform used by 10,000+ e-commerce stores.**

Fixed `AwilixResolutionError` crash during database migrations:

- **Root cause:** `runMigrationScripts()` created a new `MedusaAppLoader()` without passing the existing DI container → `query` registered in a *different* container than the one migration scripts resolved from → crash
- **Fix:** Pass `container` to `MedusaAppLoader({ container })` + made it required (not optional) to prevent silent regression
- **Tests added:** Container forwarding, `query` resolution, shutdown hooks, `MedusaModule.clearInstances()`
- Reviewer `NicolasGorga` (Medusa core team) approved the approach ✅

---

### 🐍 [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) — 219K+ ⭐

World's largest algorithms repository.

| PR | Status | What |
|---|---|---|
| [#14559](https://github.com/TheAlgorithms/Python/pull/14559) | ✅ **Approved** | Type hints in `linear_search.py` |
| [#14557](https://github.com/TheAlgorithms/Python/pull/14557) | 🔄 Open | `fibonacci_fast.py` — O(log n) via matrix exponentiation |
| [#14558](https://github.com/TheAlgorithms/Python/pull/14558) | 🔄 Open | `luhn_algorithm.py` — credit card number validation |

---

### ⏱️ [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) — 64K+ ⭐

Two separate PRs (split as requested by maintainer):

| PR | Status | What |
|---|---|---|
| [#7270](https://github.com/louislam/uptime-kuma/pull/7270) | 🔄 Open | **fix:** pause group now propagates to all child monitors |
| [#7271](https://github.com/louislam/uptime-kuma/pull/7271) | 🔄 Open | **fix:** improve domain expiry warning for unsupported TLDs |

---

### 🏹 [arrow-py/arrow](https://github.com/arrow-py/arrow/pull/1270) — 9K+ ⭐

Python datetime library.

| PR | Status | What |
|---|---|---|
| [#1270](https://github.com/arrow-py/arrow/pull/1270) | 🔄 Open | **fix:** `arrow.get(tzinfo=None)` raised `TypeError` — treat explicit `None` same as omitting `tzinfo` |

Fixed one-line bug + 2 regression tests.

---

### 📦 [pypa/pip](https://github.com/pypa/pip/pull/13910) — 9.5K+ ⭐

The Python package installer.

| PR | Status | What |
|---|---|---|
| [#13910](https://github.com/pypa/pip/pull/13910) | 🔄 Open | **fix:** `pip list \| head` crashed with `BrokenPipeError` traceback instead of clean error message |

One-line fix + news fragment as required by pip's contribution guidelines.

---

### 🤖 [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli/pull/25432) — Active

Google's official Gemini CLI tool.

| PR | Status | What |
|---|---|---|
| [#25432](https://github.com/google-gemini/gemini-cli/pull/25432) | 🔄 Open | **fix:** word-wrap while-loop hung forever on CJK characters or any character wider than terminal width — added `splitIndex === 0` guard + 2 regression tests |

---

### ⚡ [axios/axios](https://github.com/axios/axios/pull/10710) — 109K+ ⭐ · `Closed (rejected)`

| PR | Status | What |
|---|---|---|
| [#10710](https://github.com/axios/axios/pull/10710) | ❌ Rejected | `AxiosHeaders` index type improvement + JSDoc for utils |

**Why rejected:** Maintainer said the AxiosHeaders change was breaking. Lesson: always check if a change is backward-compatible before submitting to a high-traffic library.

---

## 🛠️ Personal Projects

---

### [web-to-apk](https://github.com/AKIB473/web-to-apk) — HTML → Android APK

> Put your HTML/CSS/JS in `www/`. Push to GitHub. Download your signed APK in 5 minutes. No Android Studio, no setup.

- Capacitor 6 + GitHub Actions 5-job pipeline
- Auto-generates signing keystore when no secrets set
- Separate "Setup Keystore" workflow for Google Play publishing
- APK + AAB both produced, version auto-incremented from git commits
- README designed for students, beginners, and web developers with zero Android experience

---

### [uniq-web-id](https://github.com/AKIB473/uniq-web-id) — Browser Fingerprinting Library

> Persistent device identity without cookies. Survives incognito, cache clearing, and VPNs.

- 7 independent hardware signals: Canvas · Audio · GPU · Screen · Fonts · Timezone · CPU
- Each signal has its own FNV32 hash — shown separately in the demo
- Unstable signals (Network/Battery/GPS) explicitly excluded and explained
- Based on: EFF Panopticlick · AmIUnique (NDSS 2016) · Princeton Web Transparency · WWW '25
- Estimated accuracy: ~97–99% on Chrome/Firefox, ~75% on Brave (farbling), ~20% on Tor
- Use cases: referral fraud prevention, coupon control, anonymous analytics, one-vote polls

---

### [telegram-media-dl](https://github.com/AKIB473/telegram-media-dl) — Production Telegram Bot

> Download media from 50+ platforms via Telegram. Production-grade. Docker-ready.

- aiogram 3, aiosqlite, async download queue
- 48 tests · GitHub Actions CI · Docker

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AKIB473&show_icons=true&theme=tokyonight&hide_border=true" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AKIB473&theme=tokyonight&hide_border=true" width="48%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AKIB473&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## The Rejected PRs Log

Because honesty matters more than a fake perfect track record.

| Repo | PR | Why rejected | What I learned |
|---|---|---|---|
| axios/axios | [#10710](https://github.com/axios/axios/pull/10710) | AxiosHeaders change was breaking | Check backward compatibility first |
| langchain-ai/langchain | [#36723](https://github.com/langchain-ai/langchain/pull/36723) | Opened PR without being assigned to the issue first | Always comment on issue → get assigned → then open PR |
| louislam/uptime-kuma | [#7269](https://github.com/louislam/uptime-kuma/pull/7269) | Two unrelated fixes in one PR · missing template | One PR = one thing. Always read the PR template |

*Rejected PRs are not failures. They're expensive lessons that make the next PR better.*

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AKIB473&label=Profile+views&color=0e75b6&style=flat"/>
</p>

<p align="center">
  <i>"Sent PRs to projects that get millions of downloads. Most bounced. That's fine.<br/>
  The ones that land make it worth it."</i>
</p>
