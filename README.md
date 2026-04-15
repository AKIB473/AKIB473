<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:6366f1&height=200&section=header&text=Akibuzzaman+Akib&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Full-Stack+Developer+%7C+Open+Source+Contributor+%7C+Python+%26+Node.js&descAlignY=56&descSize=16" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=38BDF8&center=true&width=600&lines=Python+%26+Node.js+Developer;Open+Source+Contributor+%E2%80%94+7+Major+Repos;Telegram+Bot+Engineer;Android+CI%2FCD+Pipeline+Builder;Browser+Fingerprinting+Researcher;219K%E2%98%85+repos+contribution+attempted" alt="Typing SVG"/>

<br/><br/>

[![GitHub followers](https://img.shields.io/github/followers/AKIB473?style=social)](https://github.com/AKIB473)
[![Profile views](https://komarev.com/ghpvc/?username=AKIB473&color=0ea5e9&style=flat)](https://github.com/AKIB473)

</div>

---

## 👋 About Me

I'm a **full-stack developer** focused on Python, Node.js, and building things that are useful.

I contribute to large open-source projects to learn from their codebases, improve my skills, and give back. I've submitted pull requests to projects with 32K–219K stars — some were accepted, some were rejected, all taught me something.

```python
about_me = {
    "name":        "Akibuzzaman Akib",
    "role":        "Full-Stack Developer",
    "focus":       ["Python", "Node.js", "TypeScript", "DevOps"],
    "open_source": "7 major repos (32K – 219K ⭐)",
    "building":    ["Telegram bots", "Android CI/CD", "Browser tools"],
    "learning":    "Every rejected PR is a free code review from senior engineers",
    "contact":     "github.com/AKIB473",
}
```

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend & API**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram_3-229ED9?style=flat-square&logo=telegram&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)

---

## 🏆 Open Source Contributions

> Pull requests submitted to production-grade open source projects used by millions.

---

### 🖥️ [microsoft/markitdown](https://github.com/microsoft/markitdown/pull/1769) &nbsp; ![Stars](https://img.shields.io/github/stars/microsoft/markitdown?style=flat-square&color=f59e0b) &nbsp; `Status: Open`

Microsoft's file-to-Markdown converter, used inside LLM pipelines and document processing workflows.

**Contribution:** 6 new file format converters + 7 bug fixes + 1 utility function

| Type | What |
|---|---|
| ✨ New | `TomlConverter` — pyproject.toml, Cargo.toml → structured Markdown |
| ✨ New | `SitemapConverter` — XML sitemaps → link lists |
| ✨ New | `EnvConverter` — .env files → masked table (secrets hidden by default) |
| ✨ New | `YamlConverter` — .yaml/.yml → structured Markdown |
| ✨ New | `RequirementsConverter` — requirements.txt → dependency table |
| ✨ New | `get_document_stats()` — word/char/heading/link count on any conversion result |
| 🐛 Fix | Jupyter notebook cell outputs (stdout, stderr, tracebacks) were silently dropped |
| 🐛 Fix | Excel empty sheets crashed → now outputs graceful `_No data_` |
| 🐛 Fix | Zip converter silently swallowed errors → now shows warning |
| 🐛 Fix | PowerPoint chart separator broke some Markdown renderers |
| 🐛 Fix | Audio converter rejected .ogg/.flac/.aac → added to accepted formats |
| 🐛 Fix | Wikipedia infoboxes cluttered LLM output → strip by default |
| 🐛 Fix | RSS item links were never extracted → now included per entry |

*75 tests added · All passing · CLA signed*

---

### 🛒 [medusajs/medusa](https://github.com/medusajs/medusa/pull/15103) &nbsp; ![Stars](https://img.shields.io/github/stars/medusajs/medusa?style=flat-square&color=f59e0b) &nbsp; `Status: Open`

Open-source headless commerce platform powering 10,000+ online stores.

**Contribution:** Fixed `AwilixResolutionError` crash in database migration scripts

- **Root cause:** `runMigrationScripts()` created a `new MedusaAppLoader()` without the existing DI container → `query` was registered in a *separate* container → migration scripts couldn't resolve it → crash
- **Fix:** Pass `container` to `MedusaAppLoader({ container })` and made the parameter **required** (not optional) to prevent silent regression
- **Reviewer feedback (NicolasGorga, Medusa core team):** Requested a test + non-optional container → implemented both
- **Tests added:** container forwarding assertion, `query` resolution, shutdown hooks, `MedusaModule.clearInstances()` behaviour

---

### 🐍 [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) &nbsp; ![Stars](https://img.shields.io/github/stars/TheAlgorithms/Python?style=flat-square&color=f59e0b)

World's largest algorithms repository — a reference for CS students and developers worldwide.

| PR | Status | Contribution |
|---|---|---|
| [#14559](https://github.com/TheAlgorithms/Python/pull/14559) | ✅ **Approved** | Type hints in `linear_search.py` — properly typed return values and parameters |
| [#14557](https://github.com/TheAlgorithms/Python/pull/14557) | 🔄 Open | `fibonacci_fast.py` — Fibonacci in **O(log n)** via matrix exponentiation with descriptive parameter names |
| [#14558](https://github.com/TheAlgorithms/Python/pull/14558) | 🔄 Open | `luhn_algorithm.py` — Luhn credit card validation with full type hints and doctests |

---

### ⏱️ [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) &nbsp; ![Stars](https://img.shields.io/github/stars/louislam/uptime-kuma?style=flat-square&color=f59e0b)

Self-hosted monitoring tool with 10M+ Docker pulls.

| PR | Status | Contribution |
|---|---|---|
| [#7270](https://github.com/louislam/uptime-kuma/pull/7270) | 🔄 Open | **fix:** pausing a group monitor now propagates the pause to all child monitors — previously children kept running silently |
| [#7271](https://github.com/louislam/uptime-kuma/pull/7271) | 🔄 Open | **fix:** improve domain expiry warning for unsupported TLDs — added actionable guidance to check via registrar or ICANN |

*Note: Original PR #7269 was correctly split into two separate PRs as requested by maintainer `CommanderStorm`.*

---

### 🏹 [arrow-py/arrow](https://github.com/arrow-py/arrow/pull/1270) &nbsp; ![Stars](https://img.shields.io/github/stars/arrow-py/arrow?style=flat-square&color=f59e0b)

Python datetime library used by 100M+ downloads/month on PyPI.

| PR | Status | Contribution |
|---|---|---|
| [#1270](https://github.com/arrow-py/arrow/pull/1270) | 🔄 Open | **fix:** `arrow.get('2025-01-01', 'YYYY-MM-DD', tzinfo=None)` raised `TypeError` — `tzinfo=None` must be treated identically to omitting `tzinfo`. One-line fix + 2 regression tests. |

---

### 📦 [pypa/pip](https://github.com/pypa/pip/pull/13910) &nbsp; ![Stars](https://img.shields.io/github/stars/pypa/pip?style=flat-square&color=f59e0b)

The Python package installer — installed on every Python system worldwide.

| PR | Status | Contribution |
|---|---|---|
| [#13910](https://github.com/pypa/pip/pull/13910) | 🔄 Open | **fix:** `pip list \| head` crashed with an unhandled `BrokenPipeError` traceback instead of printing a clean "Pipe to stdout was broken" message. One-line fix + `NEWS.d` fragment as required by pip guidelines. |

---

### 🤖 [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli/pull/25432)

Google's official command-line tool for Gemini AI.

| PR | Status | Contribution |
|---|---|---|
| [#25432](https://github.com/google-gemini/gemini-cli/pull/25432) | 🔄 Open | **fix:** word-wrap `while` loop in `InputPrompt.tsx` spun forever (100% CPU) when a CJK character or emoji was wider than the terminal column width — `splitIndex` stayed `0` and `cpSlice(word, 0)` returned the full word unchanged each iteration. Fixed by advancing `splitIndex` to 1 when the for-loop produces no progress. 2 regression tests added. |

---

### ❌ Rejected PRs — What I Learned

| Repo | PR | Rejection reason | Lesson |
|---|---|---|---|
| axios/axios (109K ⭐) | [#10710](https://github.com/axios/axios/pull/10710) | `AxiosHeaders` index change was a breaking change | Always check backward compatibility. Read the CHANGELOG before touching core types. |
| langchain-ai/langchain | Multiple | Opened PRs without being assigned to the linked issue | LangChain policy: comment on issue first → get assigned → then open PR |
| uptime-kuma | [#7269](https://github.com/louislam/uptime-kuma/pull/7269) | Two unrelated fixes in one PR + missing PR template | One PR = one change. Read the template. |

> Rejected PRs are not wasted effort. They're **free code reviews from senior engineers at top companies**. Each one made my next PR better.

---

## 🛠️ Personal Projects

---

### [📱 web-to-apk](https://github.com/AKIB473/web-to-apk)
**HTML/CSS/JS → Signed Android APK — Zero Setup**

Put your web app files in `www/`. Push to GitHub. Download your APK in 5 minutes. No Android Studio, no local Android SDK, no signing setup required.

**Technical highlights:**
- Capacitor 6 wraps web apps as native Android
- 5-job GitHub Actions pipeline: lint → web build → Capacitor sync → Gradle sign → artifact upload
- Auto-generates a demo signing keystore when no secrets are configured
- Separate "Setup Keystore" workflow for permanent Google Play signing
- Produces both APK (direct install) and AAB (Play Store)
- Version code auto-incremented from git commit count
- Designed for students and web developers with zero Android experience

`Python` `GitHub Actions` `Android` `Capacitor` `Gradle`

---

### [🔬 uniq-web-id](https://github.com/AKIB473/uniq-web-id)
**Persistent Browser Identity Without Cookies**

A browser fingerprinting library that generates a stable device ID from hardware-bound signals. Survives cookie clearing, incognito mode, cache wipes, and VPN use.

**Technical highlights:**
- 7 independent signals: Canvas · AudioContext · WebGL GPU · Screen · Fonts · Timezone · CPU
- Each signal has its own independent FNV-1a 32-bit hash
- Unstable signals (network IP, battery, GPS) deliberately excluded and documented
- Estimated accuracy: ~97–99% Chrome/Firefox · ~75% Brave (farbling) · ~20% Tor
- Based on: EFF Panopticlick · AmIUnique (NDSS 2016) · Princeton Web Transparency · WWW '25 paper
- Use cases: referral fraud prevention, coupon deduplication, one-vote polls, anonymous analytics

`JavaScript` `Browser APIs` `WebGL` `AudioContext` `Canvas` `FNV32`

---

### [🤖 telegram-media-dl](https://github.com/AKIB473/telegram-media-dl)
**Production Telegram Bot — Download from 50+ Platforms**

Send any YouTube, Instagram, TikTok, Twitter/X, or Facebook link to the bot and receive the video directly in Telegram. No browser, no websites, no ads.

**Technical highlights:**
- aiogram 3 (async) + yt-dlp + ffmpeg pipeline
- Async download queue — multiple parallel downloads, non-blocking
- Per-user SQLite download history and preferences
- Rate limiting with sliding-window algorithm
- Metadata + thumbnail + subtitle embedding via mutagen + ffmpeg
- Cookie support for age-restricted/login-required content
- Docker + docker-compose deployment
- CLI tool (`tmdl`) for server management
- 48 unit and integration tests

`Python` `aiogram 3` `yt-dlp` `ffmpeg` `aiosqlite` `Docker` `pytest`

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AKIB473&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AKIB473&theme=tokyonight&hide_border=true" width="48%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AKIB473&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>
</p>

---

## 📫 Connect

<p align="left">
  <a href="https://github.com/AKIB473"><img src="https://img.shields.io/badge/GitHub-AKIB473-181717?style=for-the-badge&logo=github"/></a>
</p>

---

<div align="center">

*"I sent pull requests to projects that serve millions of developers.*
*Most bounced. Each one taught me something the documentation never could."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:6366f1&height=100&section=footer" width="100%"/>

</div>
