# Local-First AI Tooling

I build Electron apps, MCP servers, semantic search, browser automation, and orchestration layers around real agent workflows.

Most of my work sits in the gap between "LLM chat" and "usable system": terminal orchestration, desktop AI shells, Telegram/Reddit/browser parsing, documentation routing, and note systems that can feed all of that back into an agent.

## Building A Local AI Stack

These repositories are not random side projects. They fit together into one local AI workflow:

- [custom-terminal](https://github.com/RevinFedor/custom-terminal) — terminal orchestration for Claude/Codex sessions
- [ai-mac-electron](https://github.com/RevinFedor/ai-mac-electron) — desktop AI chat + voice shell
- [sc-desktop](https://github.com/RevinFedor/sc-desktop) — Telegram / Reddit / browser parsing + MCP data layer
- [gt-editor](https://github.com/RevinFedor/gt-editor) — notes and markdown workspace
- [docs_search_mcp](https://github.com/RevinFedor/docs_search_mcp) — semantic documentation router
- [main-ios-app](https://github.com/RevinFedor/main-ios-app) — mobile control surface for the whole stack

## Selected Repositories

- [custom-terminal](https://github.com/RevinFedor/custom-terminal) — orchestration layer for Claude/Codex tabs with transcript parsing, timeline/history, cross-session access, PTY control, and deterministic mobile sync.
- [ai-mac-electron](https://github.com/RevinFedor/ai-mac-electron) — Mac-side desktop AI app with voice dictation, overlay chat, prompt library, MCP integrations, and iPhone control APIs.
- [sc-desktop](https://github.com/RevinFedor/sc-desktop) — Electron + MCP hub for Telegram, Reddit, browser-only parsing, semantic indexing, and research job orchestration.
- [gt-editor](https://github.com/RevinFedor/gt-editor) — Markdown workspace with conceal mode, semantic search, project windows, fold-aware editing, and AI-aware note workflows.
- [docs_search_mcp](https://github.com/RevinFedor/docs_search_mcp) — semantic router that tells an agent which docs to read before editing code.
- [main-ios-app](https://github.com/RevinFedor/main-ios-app) — native iPhone control surface for the Mac-side AI stack.

## What I Like Building

- local AI workflows that do not depend on fragile hosted abstractions
- MCP servers that expose real data and real tools instead of toy demos
- semantic search over docs, chats, and notes
- desktop apps that coordinate multiple agents instead of wrapping a single prompt box
- browser automation that works against real logged-in sessions and messy production UI

## Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Electron](https://img.shields.io/badge/Electron-191970?style=flat-square&logo=electron&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Local%20Agents-111827?style=flat-square)
![Browser Automation](https://img.shields.io/badge/Browser-Automation-0F172A?style=flat-square)

## Current Focus

- making multi-agent desktop workflows feel deterministic instead of magical
- turning project documentation into something an agent can actually use
- building reusable infrastructure around parsing, indexing, and orchestration

_Last updated: June 2026_
