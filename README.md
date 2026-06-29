<div align="center">

# Emmanuel King Christopher

### Creator of the **NEKOVA Programming Language**
### Software Developer · Nigeria 🇳🇬

*"Building the next generation of AI-native software development."*

[![NEKOVA](https://img.shields.io/badge/NEKOVA-Language-blueviolet?style=for-the-badge)](https://github.com/kinghenesey/NEKOVA)
[![PyPI](https://img.shields.io/pypi/v/nekova-lang?style=for-the-badge&color=blue)](https://pypi.org/project/nekova-lang)
[![Tests](https://img.shields.io/badge/Tests-1033%20passing-brightgreen?style=for-the-badge)](https://github.com/kinghenesey/NEKOVA)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://github.com/kinghenesey/NEKOVA/blob/main/LICENSE)

</div>

---

## Who I Am

I'm **Emmanuel King Christopher**, a 21-year-old software developer from Nigeria and the creator of **NEKOVA** — an AI-native programming language I started building 8 months into learning to code.

I didn't build NEKOVA to learn. I built it because I watched people drop out of programming because the tools were too hard — and because no existing language treated AI as a first-class citizen. Every language made you import AI as a library. I made it a keyword.

I believe the era of AI deserves a language built for it from the ground up.

---

## 🌌 NEKOVA — AI-Native Programming Language

NEKOVA is the world's first programming language where AI is **syntax**, not a library.

```nekova
# This is valid NEKOVA. No imports. No boilerplate. No setup.
name = ask("What's your name? ")
remember "user" = name

result = think f"Write a short poem for {name}" as text
speak result

every 1 day:
    mood = ask("How are you feeling today? ")
    think f"Give {name} encouragement based on: {mood}" as text
```

### What makes NEKOVA different

| Feature | Python | NEKOVA |
|---|---|---|
| AI calls | `import anthropic` + 10 lines | `think "..." as text` |
| Text to speech | `import pyttsx3` + setup | `speak "Hello"` |
| Scheduling | `import schedule` + boilerplate | `every 5 minutes:` |
| Image generation | `import openai` + 15 lines | `imagine "a sunset"` |
| Data validation | `import pydantic` + class | `shape User: name text` |
| Isolated execution | No native support | `sandbox strict:` |
| Built-in testing | `import pytest` | `test "it works": expect ...` |

### What's shipped

- **Complete pipeline** — Lexer → Parser (AST) → Interpreter, written from scratch
- **AI-native keywords** — `think`, `speak`, `listen`, `imagine`, `shape`, `watch`, `every`
- **Multi-provider AI** — Anthropic, OpenAI, Gemini — auto-detected, no configuration
- **Built-in database** — `connect()`, `db.create()`, `db.query()` — SQLite native
- **Web server** — `route`, `serve`, `fetch` as language keywords
- **Class system** — inheritance, `self`, `init`, decorators, generators, typed tasks
- **Custom error types** — `error NetworkError: message str, code int`
- **Standard library in NEKOVA** — `math.nk`, `string.nk`, `date.nk`, `file.nk`
- **NEKOVA Sandbox** — isolated execution, resource limits, violation tracking, security API
- **Static checker** — W001–W009 warnings with Rust-style caret error display
- **Formatter** — `nekova fmt` auto-formats `.nk` files
- **Package manager** — `nekova install`, `nekova publish`
- **REPL** — `nekova repl` with history, autocomplete
- **VS Code extension** — syntax highlighting, snippets, bracket matching
- **Notebook** — browser-based NEKOVA notebook
- **Web IDE** — in-browser editor and runner
- **Debugger** — step-through debugging
- **Python transpiler** — `nekova compile` outputs standalone Python
- **1,033 tests** — across 19 test phases, all passing

### Install

```bash
pip install nekova-lang
nekova run myapp.nk
```

---

## 🗺️ Roadmap

| Phase | Status | What |
|---|---|---|
| 1–12 | ✅ Done | Core language, AI primitives, web, DB, REPL, tools |
| 13–15 | ✅ Done | Closures, generators, stdlib, builtins, type system |
| 16 | ✅ Done | `speak`, `listen`, `every`, `test`, `imagine`, `shape`, `watch` |
| 17 | ✅ Done | Decorators, typed tasks, custom error types |
| 18 | ✅ Done | Standard library written in NEKOVA |
| 19 | ✅ Done | NEKOVA Sandbox — isolated execution environment |
| 20 | 🔄 Next | **Self-hosting begins** — NEKOVA lexer written in NEKOVA |
| 21 | 📋 Planned | `prompt` blocks, `retry`/`fallback`, enforced types |
| 22 | 📋 Planned | `observe` telemetry, `mock think` in tests, `\|>` pipe operator |
| 23 | 📋 Planned | `when error:` inline fallback, destructuring, docstrings |
| 24 | 📋 Planned | NEKOVA parser written in NEKOVA |
| 25 | 📋 Planned | Agent as declarative value, unified schema system |
| 26 | 📋 Planned | NEKOVA Sandbox commercial API, `nekova teach` CLI |
| 27 | 🎯 Goal | Full self-hosting — NEKOVA interpreter written in NEKOVA |

---

## 💻 Tech Stack

**Languages I work in:**
Python · JavaScript · TypeScript · Java · SQL · NEKOVA (creator)

**Technologies:**
React · Node.js · REST APIs · SQLite · Git · GitHub

---

## 📊 Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=kinghenesey&show_icons=true&theme=tokyonight&hide_border=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kinghenesey&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=kinghenesey&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=kinghenesey&theme=tokyo-night"/>
</p>

---

## 🤝 Connect

I'm interested in:
- Programming language design and compiler engineering
- AI-native developer tooling
- Open source collaboration
- Backend systems and architecture

If you're building something interesting in AI, compilers, or developer tools — reach out.

---

<div align="center">

> *"Great software begins with great tools. Great tools begin with great ideas."*

**Building NEKOVA** — the language the AI era deserves.

⭐ Star [NEKOVA](https://github.com/kinghenesey/NEKOVA) if the idea resonates.

</div>
