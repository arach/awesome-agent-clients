# Awesome Agent Clients [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> An exhaustive map of the agent-client ecosystem: the apps, TUIs, dashboards, remotes, orchestrators, and infrastructure that run, watch, and steer AI coding agents like Claude Code, Codex, Gemini CLI, OpenCode, Pi, and more. Curated by [AgentList.io](https://www.agentlist.io).

**967 entries across 23 sections.** Every entry links to its canonical source; GitHub-backed entries carry stars, license, and activity metadata. `📦 archived` means upstream archived the repository; `💤 dormant` means no pushes in over a year. `drives:` lists the agent harnesses a tool wraps when known.

## Contents

- [Desktop Workbenches](#desktop-workbenches) (104)
- [Terminal Multiplexers & Session Managers](#terminal-multiplexers--session-managers) (112)
- [Web Dashboards & Control Planes](#web-dashboards--control-planes) (46)
- [Cloud & Hosted Control Planes](#cloud--hosted-control-planes) (8)
- [Mobile & Remote-Control Clients](#mobile--remote-control-clients) (78)
- [IDE & Editor Integrations](#ide--editor-integrations) (30)
- [Multi-Agent Swarms & Orchestrators](#multi-agent-swarms--orchestrators) (75)
- [Agent Loops & Autonomous Runs](#agent-loops--autonomous-runs) (71)
- [Task Runners & Async Execution](#task-runners--async-execution) (26)
- [Session Viewers & Observability](#session-viewers--observability) (30)
- [Usage, Cost & Quota Monitors](#usage-cost--quota-monitors) (33)
- [Companions, Notifications & Statusline](#companions-notifications--statusline) (16)
- [Model Routers & Account Managers](#model-routers--account-managers) (30)
- [Sandboxes & Isolated Environments](#sandboxes--isolated-environments) (32)
- [Agent Runtimes & Harness Infrastructure](#agent-runtimes--harness-infrastructure) (6)
- [Coordination, Messaging & Protocols](#coordination-messaging--protocols) (28)
- [Memory & Context Layers](#memory--context-layers) (38)
- [Security, Policy & Review Gates](#security-policy--review-gates) (23)
- [Agent Tooling: Browsers, MCP Adapters & Utilities](#agent-tooling-browsers-mcp-adapters--utilities) (31)
- [SDKs & Agent-Building Kits](#sdks--agent-building-kits) (8)
- [Personal Assistant & Coworker Agents](#personal-assistant--coworker-agents) (38)
- [The Agents: CLIs & Harnesses These Clients Drive](#the-agents-clis--harnesses-these-clients-drive) (97)
- [Dormant & Archived (Notable)](#dormant--archived-(notable)) (7)

## Desktop Workbenches

*Native desktop apps and workspaces that run, supervise, and review coding agents — usually many sessions in parallel.*

- [Orca](https://www.onorca.dev/) — Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime *(★ 78.8k, MIT)*
- [Oh My OpenAgent](https://github.com/code-yeongyu/oh-my-openagent) — OmO: Just type "mass ulw" keyword with your prompt. Now you are the master of graph engineering *(★ 69.5k)*
- [AionUi](https://github.com/iOfficeAI/AionUi) — Open-source 24/7 Cowork app for OpenClaw, Hermes, Claude Code, Codex, OpenCode and 20+ more CLI Agent · Customize your assistants · Team them up｜Star if you… *(★ 33.1k, Apache-2.0, drives Claude Code, Codex, Hermes, OpenClaw, OpenCode)*
- [Vibe Kanban](https://www.vibekanban.com/) — Get 10X more out of Claude Code, Codex or any coding agent *(★ 28.2k, Apache-2.0, drives Claude Code, Codex)*
- [openwork](https://github.com/different-ai/openwork) — The open-source alternative to Claude Cowork (powered by opencode) *(★ 23.7k, drives OpenCode)*
- [opcode](https://github.com/winfunc/opcode) — A powerful GUI app and Toolkit for Claude Code - Create custom agents, manage interactive Claude Code sessions, run secure background agents, and more *(★ 22.4k, AGPL-3.0, drives Claude Code)*
- [qm](https://github.com/yc-software/qm) — Multiplayer agent harness for work *(★ 15.3k, MIT)*
- [Aperant](https://aperant.com) — Autonomous multi-session AI coding *(★ 14.6k, AGPL-3.0)*
- [Agent Orchestrator](https://ao-agents.com) — Run and supervise teams of coding agents from planning to merge. Any harness (Claude code, codex, +25 more). Desktop, web, mobile, and cloud agents *(★ 12.4k, Apache-2.0, drives Claude Code, Codex)*
- [CodeLayer / HumanLayer](https://github.com/humanlayer/humanlayer) — The best way to get AI coding agents to solve hard problems in complex codebases *(★ 11.6k, drives Claude Code)*
- [OpenChamber](https://github.com/openchamber/openchamber) — Agentic Development Environment based on OpenCode AI agent *(★ 10.7k, MIT, drives OpenCode)*
- [munder-difflin](https://github.com/chaitanyagiri/munder-difflin) — A local multi-agent harness that works with your existing Claude Code, Codex subscriptions, allows you to run an office of agents *(★ 8k, MIT, drives Claude Code, Codex)*
- [PI-Desktop](https://github.com/vastsa/PI-Desktop) — Local-first AI coding agent desktop: Electron + Rust host core + pi Agent Harness + user-installable plugins *(★ 5.8k, LGPL-3.0, drives Pi)*
- [desktop-cc-gui](https://github.com/zhukunpenglinyutong/desktop-cc-gui) — Multi-engine AI coding desktop client (Tauri). Claude Code, Codex, Gemini, OpenCode, DeepSeek Harness and more in one GUI *(★ 4.4k, drives Claude Code, Codex, DeepSeek, Gemini CLI, OpenCode)*
- [CodexMonitor](https://github.com/Dimillian/CodexMonitor) — An app to monitor the (Codex) situation *(★ 4.3k, MIT, drives Codex)* 💤 dormant
- [Clawith](https://github.com/dataelement/Clawith) — Your First AI Agents Company *(★ 4.2k, Apache-2.0)*
- [bb](https://github.com/get-bb/bb) — The agent IDE that builds itself *(★ 3.9k, MIT)*
- [codeg](https://github.com/xintaofei/codeg) — Collaborative multi-agent AI coding workspace: aggregate sessions from Claude Code, Codex, OpenCode, Pi, Grok Build, etc. Desktop app, self-hosted server,… *(★ 3.7k, Apache-2.0, drives Claude Code, Codex, Grok Build, OpenCode, Pi)*
- [automaker](https://automaker.app/) — Kanban dev studio where you describe features and watch agents implement them; adds Codex, Copilot, Cursor, Gemini, and OpenCode providers *(★ 3.2k, drives Codex, Copilot, Cursor, Gemini CLI, OpenCode)* 💤 dormant
- [collaborator](https://github.com/collabs-inc/collab-public) — Collaborator is a place to create with agents *(★ 2.9k)*
- [compozy](https://github.com/compozy/compozy) — An operating system for AI agents. Plug in the agent CLIs you already use (Claude Code, Codex, Gemini CLI, Cursor) and they become a team: they split the… *(★ 2.8k, MIT, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [CodeNomad](https://github.com/NeuralNomadsAI/CodeNomad) — CodeNomad: The command center that puts AI coding on steroids *(★ 2.6k, MIT, drives OpenCode)*
- [Agency Orchestrator](https://github.com/jnMetaCode/agency-orchestrator) — 🚀 One sentence → your one-person company of AI experts → complete deliverable in minutes. 276 CN + 184 EN + 5 more languages (ko/ru/pt-BR/id/ar) · zero-code… *(★ 2.3k, Apache-2.0, drives Claude Code, Codex, Copilot, Gemini CLI)*
- [Zeron](https://github.com/zeronsh/zeron) — A native control plane for Claude Code, Codex, Cursor, Devin and other coding agents *(★ 2.2k, MIT, drives Claude Code, Codex, Cursor, Grok, Hermes, Pi)*
- [open-cowork](https://github.com/OpenCoworkAI/open-cowork) — Open-source AI agent desktop app for Windows & macOS. One-click install Claude Code, MCP tools, and Skills — with sandbox isolation, multi-model support,… *(★ 2.2k, MIT, drives Claude Code)*
- [Cate](https://github.com/0-AI-UG/cate) — An infinite zoomable canvas for coding. Editor, terminal, and browser panels in a spatial workspace *(★ 2.2k, MIT)*
- [Orkas](https://github.com/Orkas-AI/Orkas) — Orkas is an open-source, local-first AI desktop app: a commander LLM directs specialist sub-agents, and runs your installed coding CLIs — Claude Code,… *(★ 2.1k, MIT, drives Claude Code, Codex, Hermes, OpenClaw, OpenCode)*
- [xum](https://github.com/coder/xum) — A desktop app for isolated, parallel agentic development *(★ 2k, AGPL-3.0)*
- [synara](https://github.com/Emanuele-web04/synara) — The best place to build with your AI sub *(★ 1.9k, MIT)*
- [Nimbalyst](https://github.com/nimbalyst/nimbalyst) — Nimbalyst - The open-source visual workspace for Claude Code, Codex, and OpenCode. Run multiple coding agents in parallel, edit their work visually in… *(★ 1.8k, MIT, drives Claude Code, Codex, OpenCode)*
- [Waku](https://github.com/egoist/waku) — ⚡ A native app for all your coding agents *(★ 1.5k, GPL-3.0, drives Amp, Claude Code, Codex, Cursor, Grok Build, OpenCode…)*
- [Traycer](https://github.com/traycerai/traycer) — Traycer: Nerve Center for Agentic Coding *(★ 1.5k, MIT)*
- [MonoCode](https://github.com/hardbeat920/monocode) — A GUI for your coding agents *(★ 1.5k, MIT, drives Claude Code, Codex, Cursor, Grok Build, Oh My Pi, OpenCode…)*
- [Helmor](https://github.com/dohooo/helmor) — Open-source local workbench for multi-agent software development *(★ 1.3k, Apache-2.0)*
- [jean](https://github.com/coollabsio/jean) — A dev environment for AI agents *(★ 1.3k, Apache-2.0, drives Claude Code, Codex, Cursor, OpenCode)*
- [Parallel Code](https://github.com/johannesjo/parallel-code) — Run Claude Code, Codex, and Gemini side by side — each in      its own git worktree *(★ 1k, MIT, drives Claude Code, Codex, Gemini CLI)*
- [pi-gui](https://github.com/minghinmatthewlam/pi-gui) — Electron GUI app for the pi coding agent runtime *(★ 993, MIT, drives Pi)*
- [AgentVerse-OS](https://github.com/agentverse-os/AgentVerse-OS) — Personal cloud OS for a developer and their AI agents on a single server. One-command install on Ubuntu, then everything in the browser: a windowed desktop,… *(★ 981, Apache-2.0, drives Claude Code, Codex)*
- [Berd](https://github.com/block/berd) — a desktop app for getting work done with any model *(★ 946, Apache-2.0, drives Goose)*
- [agent-sessions](https://github.com/jazzyalex/agent-sessions) — Local-first macOS app to browse, search, analyze, and resume supported AI coding-agent session history across Codex, Claude Code, OpenCode, Cursor Agent,… *(★ 878, MIT, drives Antigravity, Claude Code, Codex, Copilot, Cursor, Hermes…)*
- [Ghostex](https://github.com/maddada/Ghostex) — Rust & GPUI Native Agent CLIs manager for macOS. Ghostty Terminals + Codex App Features/UX = Ghostex! Embedded browser & IDE. Tons of useful features *(★ 843, MIT, drives Claude Code, Codex, OpenCode)*
- [helix](https://github.com/helixml/helix) — ♾️ Private Agent Fleet with Spec Coding. Each agent gets their own GPU-accelerated desktop. Run Claude, Codex, Gemini and open models on a full private AI… *(★ 810, drives Codex, Gemini CLI)*
- [BossConsole](https://bossconsole.ai/) — Open-source, multi-platform harness for AI agents - a native, multi-threaded operator's console (JVM, not Electron) to run Claude Code, Codex, Gemini or… *(★ 808, Apache-2.0, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [Alethe](https://github.com/Kc1t/alethe-agents) — A local-first desktop workspace for running, organizing, and resuming multiple coding agents and shells with   real PTYs, split panes, persistent layouts,… *(★ 735, AGPL-3.0, drives Claude Code, Codex, OpenCode)*
- [LinJun](https://github.com/wangdabaoqq/LinJun) — 🖥️ 跨平台GUI管理AI编码代理（Claude、Gemini、Codex、Copilot、Kiro等） *(★ 664, MIT, drives Codex, Copilot, Gemini CLI)*
- [cc-pane](https://github.com/wuxiran/cc-pane) — Multi-instance split-pane manager for Claude Code — a cross-platform desktop app built with Tauri 2 *(★ 569, GPL-3.0, drives Claude Code)*
- [omg.dev](https://github.com/BennyKok/omg.dev) — omg.dev — Remote control for claude, codex, cursor, opencode, pi, grok, jcocde with mobile client *(★ 541, MIT, drives Claude Code, Codex, Copilot, Cursor, Grok, OpenCode…)*
- [proliferate](https://github.com/proliferate-ai/proliferate) — The open-source AI IDE for Claude Code, Codex, OpenCode, and more. Run agents in parallel, locally or in the cloud, and build reusable workflows *(★ 507, AGPL-3.0, drives Claude Code, Codex, OpenCode)*
- [AgentHub](https://github.com/jamesrochabrun/AgentHub) — Manage all sessions in Claude Code and Codex. Easily create new worktrees, run multiple terminals in parallel, preview edits before accepting them, make… *(★ 489, MIT, drives Claude Code, Codex)*
- [pi-agent-desktop](https://github.com/abcwyc/pi-agent-desktop) — Pi — A cross-platform AI coding agent, bringing the Claude Code experience to your desktop. No environment setup, no terminal commands. Download and start… *(★ 454, MIT, drives Claude Code, Pi)*
- [TOKENICODE](https://github.com/yiliqi78/TOKENICODE) — A Claude Code GUI — Tauri 2 + React 19 + TypeScript + Tailwind CSS 4 *(★ 445, Apache-2.0, drives Claude Code)*
- [FleetCode](https://github.com/built-by-as/FleetCode) — Light-weight control pane to run CLI coding agents(Claude Code, Codex) in parallel *(★ 424, drives Claude Code, Codex)* 💤 dormant
- [percho](https://github.com/Jaxton07/percho) — Percho: Minimalist desktop GUI for the Pi coding agent — the same engine as the Pi CLI, in a clean visual interface. Multi-session chat, visual tool… *(★ 373, MIT, drives Pi)*
- [Vicoa](https://github.com/vicoa-ai/vicoa) — Vicoa is the agentic IDE for running a team of coding agents from desktop, mobile, VPS. Open-source, self-hostable *(★ 353, AGPL-3.0, drives Claude Code, Codex, Copilot, Cursor, Gemini CLI, Hermes…)*
- [Dorothy](https://github.com/Charlie85270/Dorothy) — Dorothy, the wife your AI agents needs *(★ 348, MIT, drives Claude Code, Codex, Gemini CLI)*
- [diri](https://github.com/cristicretu/diri) — A native workspace for coding agents. Run in parallel, review in place *(★ 335, Apache-2.0, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [Kanban Code](https://github.com/langwatch/kanban-code) — Native desktop app + CLI (LangWatch) managing multiple Claude Code sessions via a kanban board *(★ 324, Apache-2.0, drives Claude Code)*
- [Aizen](https://github.com/vivy-company/aizen) — Bring order to your projects, environments, and day-to-day work *(★ 306, GPL-3.0, drives Claude Code, Codex, OpenCode)*
- [monet](https://github.com/zenolab124/monet) — Monet — Multi-engine mission control for coding agents (Claude Code and Codex today). Browse, search, and drive your agent sessions from a native desktop app *(★ 280, MIT, drives Claude Code, Codex)*
- [vibe-tree](https://github.com/sahithvibudhi/vibe-tree) — Run AI coding agents in parallel, one git worktree each. Desktop, web, and CLI *(★ 267, MIT)*
- [akari](https://github.com/chenzhen7/akari) — Akari 是一个面向开发者团队的 AI Agent 并行开发管理平台。它基于 Git worktree 为每个会话创建完全隔离的工作区，让你能够同时启动多个 Agent（Claude Code、Kimi、Aider、Shell 等），通过统一界面查看状态、终端输出、代码 Diff，并在任务完成后统一… *(★ 256, MIT, drives Aider, Claude Code, Kimi)*
- [Claudoscope](https://github.com/cordwainersmith/Claudoscope) — native macOS app that gives you a real-time dashboard for your Claude Code and Cowork sessions, with analytics, conversation history, security hardening,… *(★ 236, MIT, drives Claude Code)*
- [conduit-release](https://github.com/lostintangent/conduit-release) — 🔌 A terminal-centric workspace manager (a "DIY-DE"), that's built for task parallelization with coding agents *(★ 233)* 💤 dormant
- [Sculptor](https://imbue.com/sculptor/) — Build product with grounded, parallel coding agents *(★ 232, MIT)*
- [galactic](https://github.com/idolaman/galactic) — The command center to ship 10x faster with a parallel Claude Code fleet, featuring isolated Git Worktrees and zero-conflict networking *(★ 228, AGPL-3.0, drives Claude Code)* 💤 dormant
- [MulmoTerminal](https://github.com/receptron/mulmoterminal) — Run multiple Claude Code and Codex sessions in parallel — a browser terminal grid that shows which agent needs you. Local, tmux-backed, MIT *(★ 225, MIT, drives Claude Code, Codex)*
- [Constellagent](https://constellagent.vercel.app/) — Desktop app for running multiple AI agents in parallel. Each agent gets its own terminal, editor, and git worktree, all in one window *(★ 215)* 💤 dormant
- [zuse](https://github.com/swarajbachu/zuse) — open source devin (cloud agents) *(★ 208, AGPL-3.0, drives Claude Code, Codex, Cursor, Gemini CLI, Grok, OpenCode)*
- [Tempest](https://github.com/tempestai-dev/tempest) — Agentic Engineering that actually scales. Run Claude Code, Codex, Gemini and any other CLI Agents in parallel with upto 86% fewer tokens and 92% fewer tool… *(★ 180, Apache-2.0, drives Claude Code, Codex, Gemini CLI)*
- [Claude Command Center (CCC)](https://github.com/amirfish1/claude-command-center) — Manage and orchestrate your Claude Code, Codex, Cursor, Antigravity, Kimi, Grok, Devin, Droid sessions on your Machine. Spawn in parallel, ship in parallel.… *(★ 173, drives Antigravity, Claude Code, Codex, Cursor, Droid, Grok…)*
- [Ouijit](https://github.com/ouijit/ouijit) — Git worktree-based task manager with integrated terminals for CLI coding agents *(★ 172, AGPL-3.0, drives Claude Code, Codex, OpenCode, Pi)*
- [Runner](https://github.com/yicheng47/runner) — Where terminal agents work together. Claude Code, Codex, Copilot CLI and pi on the same task, in one mission, each keeping its own TUI in a real terminal *(★ 171, MIT, drives Claude Code, Codex, Copilot, Pi)*
- [figaro](https://github.com/byt3bl33d3r/figaro) — Orchestrate fleets of Claude Code & Claude Computer Use agents across containers, VMs, and physical devices. Live desktop streaming, intelligent task… *(★ 152, MIT, drives Claude Code)* 💤 dormant
- [kanvibe](https://github.com/rookedsysc/kanvibe) — Keyboard-first desktop Kanban workspace for AI coding agents with embedded terminals, git worktrees, and hook-driven task tracking *(★ 143, AGPL-3.0)*
- [lore](https://github.com/hsusul/lore) — Local desktop app that runs Claude Code and Codex in parallel git worktrees and supervises them until you merge *(★ 139, Apache-2.0, drives Claude Code, Codex)*
- [claude-control](https://github.com/sverrirsig/claude-control) — macOS desktop dashboard for monitoring and managing multiple Claude Code sessions *(★ 134, MIT, drives Claude Code)*
- [GraphCode](https://github.com/scgopi/GraphCode) — Graph Engineering, simplified — with GraphCode. #graphcode *(★ 128, drives Claude Code, Codex, Copilot)*
- [Vigla](https://github.com/Kilbex/Vigla) — Open-source mission control for coding agents. Run cross-vendor workers in isolated worktrees, audit every submission, and revert an entire mission *(★ 116, Apache-2.0)*
- [Dray](https://github.com/monorepo-labs/dray) — Native desktop app wrapping Claude Code, Codex, fx, and pi in a chat UI, with one worktree per session plus diff, PR, and issue panels and an embedded browser *(★ 101, Apache-2.0, drives Claude Code, Codex, Pi)*
- [claude-config-manager](https://github.com/dustinlacewell/claude-config-manager) — A native app for managing all Claude Code configuration *(★ 98, MIT, drives Claude Code)* 💤 dormant
- [claude-code-notification](https://github.com/wyattjoh/claude-code-notification) — A lightweight macOS desktop notification hook for Claude Code that displays native notifications with customizable system sounds when events occur during AI… *(★ 95, MIT, drives Claude Code)*
- [comate](https://github.com/ai-dvps/comate) — Comate is a desktop AI workspace that brings Claude Code into a polished, native app experience. Organize multiple projects in folder-backed workspaces,… *(★ 94, Apache-2.0, drives Claude Code)*
- [Garcon](https://github.com/cfal/garcon) — Self-hosted browser workspace to run coding agents in parallel, steer work as it runs, review diffs, and ship *(★ 88)*
- [Tortie](https://github.com/gregce/tortie) — A calm agent multiplexer with familiar IDE features, for macOS *(★ 87, Apache-2.0)*
- [glyphic](https://github.com/caioricciuti/glyphic) — Glyphic gives you a visual interface to configure, manage, and use Claude Code -- the AI coding assistant from Anthropic. Instead of editing JSON files and… *(★ 75, AGPL-3.0, drives Claude Code)*
- [daintree](https://github.com/daintreehq/daintree) — A delegation environment for orchestrating AI coding agents. Manage Claude, Gemini, and Codex sessions across git   worktrees with integrated terminals,… *(★ 74, drives Codex, Gemini CLI)*
- [agent-manager-x](https://github.com/maddada/agent-manager-x) — A macOS desktop app to monitor your Claude Code, Codex, OpenCode AI coding agents in real-time with voice or bell notifications. Easily jump to a… *(★ 72, drives Claude Code, Codex, OpenCode)* 💤 dormant
- [autosteer](https://github.com/notch-ai/autosteer) — Desktop app for multi-workspace Claude Code management *(★ 68, MIT, drives Claude Code)* 💤 dormant
- [ClaudeLens](https://github.com/giulio333/ClaudeLens) — A desktop app to visually explore and manage your local Claude Code data *(★ 64, MIT, drives Claude Code)*
- [Zaivern Code](https://github.com/tacyan/zaivern-code) — Zaivern Code — Rust-native AI cockpit editor *(★ 52, Apache-2.0, drives Claude Code, Codex, Gemini CLI)*
- [clave](https://github.com/antasphere/clave) — A macOS desktop app for managing multiple Claude Code sessions *(★ 51, MIT, drives Claude Code)*
- [AI4Kanban](https://github.com/ai4kanban/ai4kanban) — Your AI project manager: agents plan and build, while you focus on ideas and make the key decisions *(★ 38, Apache-2.0)*
- [vibecraft](https://github.com/rayzhudev/vibecraft) — RTS-style workspace for commanding coding agents *(★ 35, Apache-2.0)*
- [Superagent](https://github.com/pungme/superagent-desktop) — The desktop home for your coding agent — Claude Code or Codex. A persistent chat, a real browser it drives on your own logins, your phone in the loop, and… *(★ 26, MIT, drives Claude Code, Codex)*
- [Fletch](https://github.com/fwdai/fletch) — A new kind of IDE for agentic engineering *(★ 25, AGPL-3.0, drives Claude Code, Codex, Cursor, OpenCode)*
- [muxel](https://github.com/ProjectHax/muxel) — muxel is a GPUI-native multiplexer for coding agents *(★ 22, GPL-3.0, drives mux)*
- [octomux](https://github.com/ShreyPaharia/octomux) — Local dashboard to run parallel Claude Code & Cursor agents — kanban fleet view, one permission inbox, in-app diff review. macOS, MIT *(★ 22, MIT, drives Claude Code, Cursor)*
- [Podium ADE](https://github.com/madeinorbit/podium) — Podium is an ADE with built-in cross-harness subagents and agent communication. It runs on desktop, mobile and VPS *(★ 22, Apache-2.0)*
- [agent-session-manager-desktop](https://github.com/izll/agent-session-manager-desktop) — Desktop GUI for managing multiple AI coding-agent sessions (Claude, Gemini, Aider, Codex, …) — the GUI counterpart of agent-session-manager. Wails + Svelte… *(★ 21, MIT, drives Aider, Claude Code, Codex, Gemini CLI)*
- [alas](https://github.com/mrmans0n/alas) — The workspace for the whole agent loop: Every agent. Every worktree. One window *(★ 18, MIT)*
- [ateam](https://github.com/clawnify/ateam) — Orchestrate a crew of AI coding agents — Claude Code, OpenCode, and Codex — each isolated in its own git worktree. Run them on your Mac or a remote box *(★ 12, drives Claude Code, Codex, OpenCode)*
- [EvoFlux](https://github.com/evoelsewhere/evoflux) — Evoflux is an open-source, local-first workspace where AI agents build software, conduct deep research, automate browser tasks, and collaborate in parallel.… *(★ 10, Apache-2.0)*
- [Conductor](https://www.conductor.build/) — macOS app (Melty Labs) running agents in parallel, each in an isolated workspace with branch, terminal, and diff
- [mux](https://mux.coder.com/) — Coder's desktop/browser app that runs many agents in parallel via Local/Worktree/SSH runtimes, but drives its own agent loop rather than orchestrating…

## Terminal Multiplexers & Session Managers

*TUIs, terminal multiplexers, and session managers for driving CLI agents side by side.*

- [herdr](https://github.com/herdrdev/herdr) — the runtime your coding agents live on *(★ 40.9k, Apache-2.0)*
- [cmux](https://cmux.com/) — Open source Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents. Built for multitasking, organization, and programmability *(★ 27.4k)*
- [Superset](https://superset.sh/) — Superset is an agentic IDE to orchestrate 100+ coding agents in parallel. Run any agent with your own subscription *(★ 14.7k)*
- [emdash](https://emdash.sh/) — Emdash is the Open-Source Agentic Development Environment (🧡 YC W26). Run multiple coding agents in parallel. Use any provider *(★ 5.8k, Apache-2.0)*
- [toad](https://github.com/batrachianai/toad) — A unified interface for AI in your terminal *(★ 3.4k, AGPL-3.0, drives Claude Code, Codex, Copilot)* 💤 dormant
- [Agent of Empires](https://github.com/agent-of-empires/agent-of-empires) — Manage multiple Claude Code, OpenCode agents from either TUI or Web for easy access on mobile. Also supports Mistral Vibe, Codex CLI, Gemini CLI, Pi.dev,… *(★ 3.3k, MIT, drives Claude Code, Codex, Copilot, Droid, Factory Droid, Gemini CLI…)*
- [Antfarm](https://www.antfarm.cool/) — Build your agent team in OpenClaw with one command *(★ 2.5k, MIT, drives OpenClaw)* 💤 dormant
- [nodeterm](https://github.com/eneskirca/nodeterm) — Node-based terminal manager for AI coding agents — tmux-backed terminals and parallel agent sessions as draggable nodes on an infinite pan/zoom canvas.… *(★ 1.9k)*
- [dmux](https://github.com/standardagents/dmux) — A dev agent multiplexer for git worktrees and coding agents *(★ 1.8k, MIT)*
- [ai-devkit](https://github.com/codeaholicguy/ai-devkit) — The control plane for AI coding agents *(★ 1.6k, Apache-2.0, drives Claude Code, Codex, Pi)*
- [multi-agent-shogun](https://github.com/yohey-w/multi-agent-shogun) — Samurai-inspired multi-agent system for Claude Code. Orchestrate parallel AI tasks via tmux with shogun → karo → ashigaru hierarchy *(★ 1.4k, MIT, drives Claude Code)*
- [CLI Agent Orchestrator](https://github.com/awslabs/cli-agent-orchestrator) — Multi-agent orchestration for AI coding CLIs — Claude Code, Kiro, Codex, and more, coordinated in isolated tmux sessions *(★ 1.4k, Apache-2.0, drives Claude Code, Codex)*
- [ccmanager](https://github.com/kbwo/ccmanager) — Coding Agent Session Manager for Claude Code / Gemini CLI / Codex CLI / Cursor Agent / Copilot CLI / Cline CLI / OpenCode / Kimi CLI *(★ 1.2k, MIT, drives Claude Code, Cline, Codex, Copilot, Cursor, Gemini CLI…)*
- [opensessions](https://github.com/Ataraxy-Labs/opensessions) — tmux sidebar for coding agents — Amp, Claude Code, Codex, OpenCode. Per-thread markers, local HTTP API, live session state *(★ 1.2k, drives Amp, Claude Code, Codex, OpenCode)*
- [pi-subagents](https://github.com/tintinweb/pi-subagents) — Claude Code like Sub-Agents & Workflow Orchestration for Pi — parallel execution, live widget, fleet view, custom agent types, mid-run steering, claude… *(★ 1.2k, MIT, drives Claude Code, Pi)*
- [Agent Deck](https://github.com/asheshgoplani/agent-deck) — Terminal session manager for AI coding agents. One TUI for Claude, Gemini, OpenCode, Codex, and more *(★ 956, MIT, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [claude_code_agent_farm](https://github.com/Dicklesworthstone/claude_code_agent_farm) — Orchestration framework for running 20+ Claude Code agents in parallel: automated bug fixing, best-practices sweeps, lock-based coordination, and real-time… *(★ 919, drives Claude Code)*
- [opslane_old](https://github.com/opslane/opslane_old) — Run multiple Claude Code sessions in parallel *(★ 772, MIT, drives Claude Code)* 💤 dormant
- [counselors](https://github.com/aarondfrancis/counselors) — Fan out prompts to multiple AI coding agents in parallel *(★ 659)* 💤 dormant
- [agterm](https://github.com/umputun/agterm) — A genuinely good terminal *(★ 630, MIT)*
- [Prowl](https://github.com/onevcat/Prowl) — native macOS codings agent orchestrator *(★ 621, drives Claude Code, Codex)*
- [pi-interactive-shell](https://github.com/nicobailon/pi-interactive-shell) — Pi coding agent extension that allows Pi to autonomously control interactive CLIs in an observable overlay. Full PTY emulation, no  tmux, token efficient.… *(★ 588, drives Pi)*
- [tmux-ide](https://github.com/wavyrai/tmux-ide) — Turn any project into a tmux-powered terminal IDE with a simple ide.yml *(★ 549, MIT, drives Aider, Claude Code, Codex, Cursor)*
- [async-code](https://github.com/ObservedObserver/async-code) — Use Claude Code / CodeX CLI to perform multiple tasks in parallel with a Codex-style UI. Your personal codex/cursor-background agent. Claude Code UI *(★ 535, Apache-2.0, drives Claude Code, Codex, Cursor)* 💤 dormant
- [pi-intercom](https://github.com/nicobailon/pi-intercom) — Inter-session communication extension for pi coding agent *(★ 524, MIT, drives Pi)*
- [agent-manager](https://github.com/YoanWai/agent-manager) — The fastest workflow for every AI coding agent. Live status, quick prompts, worktrees, and diff review from one tmux TUI *(★ 507, Apache-2.0, drives Claude Code, Codex, Gemini CLI, Grok, Hermes, OpenCode…)*
- [amux](https://github.com/mixpeek/amux) — Open-source control plane for AI coding agents. Run an AI engineering team: parallel Claude Code, Codex, and Gemini workers with a shared board, atomic… *(★ 503, drives Claude Code, Codex, Gemini CLI)*
- [KKTerm](https://github.com/ryantsai/KKTerm) — Super-tool for vibe coders & system admins — terminals, SSH, SFTP, RDP/VNC, dashboards, install helpers, and a built-in AI assistant *(★ 499, drives Vibe)*
- [memory-forge-rs](https://github.com/voidcraft-dev/memory-forge-rs) — Stop resetting satisfying AI chats — edit the memory instead. Local session manager for Claude Code, Codex & OpenCode & Gemini CLI &  Kiro CLI & pi &Cursor… *(★ 487, MIT, drives Claude Code, Codex, Cursor, Gemini CLI, OpenCode, Pi)*
- [ntm](https://github.com/Dicklesworthstone/ntm) — Named Tmux Manager: spawn, tile, and coordinate multiple AI coding agents (Claude, Codex, Gemini) across tmux panes with a TUI command palette *(★ 451, drives Codex, Gemini CLI)*
- [bridle](https://github.com/neiii/bridle) — TUI / CLI config manager for agentic harnesses (Amp, Claude Code, Opencode, Goose, Copilot CLI, Crush, Droid) *(★ 440, MIT, drives Amp, Claude Code, Copilot, Crush, Droid, Goose…)*
- [foreman](https://github.com/VisionForge-OU/foreman) — A Boris-style agentic orchestrator TUI that supervises headless Claude Code agents through a gated software-delivery pipeline — pointed at any repository *(★ 440, drives Claude Code)*
- [termany](https://github.com/thinkany-ai/termany) — Agent-Native Terminal *(★ 440, drives Codex, Cursor, Gemini CLI, Grok Build, Hermes, Kimi…)*
- [opensync](https://github.com/waynesutton/opensync) — Cloud-synced dashboards for OpenCode and Claude Code. Track sessions, search with semantic lookup, export eval datasets *(★ 410, MIT, drives Claude Code, OpenCode)* 💤 dormant
- [Agent Viewer](https://github.com/hallucinogen/agent-viewer) — Kanban board for managing Claude Code agents in tmux *(★ 402, drives Claude Code)* 💤 dormant
- [grasp](https://github.com/cocofhu/grasp) — Grasp helps you manage multiple projects and parallel coding agents in one visual workflow, so humans can understand faster and ship more *(★ 396, MIT)*
- [claude-code-tool-manager](https://github.com/tylergraydev/claude-code-tool-manager) — GUI app to manage MCP servers for Claude Code *(★ 381, drives Claude Code)*
- [claude-code-trace](https://github.com/delexw/claude-code-trace) — Claude Code session log viewer for JSONL files in ~/.claude/projects. Browse conversations, tool calls, tokens, and live tail sessions on desktop, web, and TUI *(★ 372, MIT, drives Claude Code)*
- [Clarc](https://github.com/ttnear/Clarc) — Native macOS client for Claude Code — a GUI desktop app built with SwiftUI *(★ 368, drives Claude Code)*
- [nexpath](https://github.com/hi0001234d/nexpath) — Local-first AI coding workflow for vibe coders, indie hackers, technical founders and product managers — catch missing tests and safety checks across Claude… *(★ 352, Apache-2.0, drives Claude Code, Cursor, Vibe, Windsurf)*
- [codex-orchestrator](https://github.com/kingbootoshi/codex-orchestrator) — Delegate tasks to OpenAI Codex agents via tmux sessions. Designed for Claude Code orchestration *(★ 351, MIT, drives Claude Code, Codex)* 💤 dormant
- [Calyx](https://github.com/yuuichieguchi/Calyx) — A native macOS terminal app built on Ghostty for running and supervising coding agents *(★ 328, MIT)*
- [comanda](https://github.com/kris-hansen/comanda) — The CLI-native orchestrator for AI agent workflows. Run Claude Code, Codex, Gemini CLI & Kimi Code from declarative YAML. Because the terminal is where real… *(★ 324, MIT, drives Claude Code, Codex, Gemini CLI, Kimi)*
- [dev-3.0](https://github.com/h0x91b/dev-3.0) — Mission control for the One Person Studio — run a fleet of AI coding agents in parallel without losing your mind. Kanban + git worktrees + tmux for Claude… *(★ 298, Apache-2.0, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [rover](https://github.com/endorhq/rover) — A manager for AI coding agents that works with Claude Code, Cursor, Gemini, Codex, and Qwen *(★ 272, Apache-2.0, drives Claude Code, Codex, Cursor, Gemini CLI, Qwen)* 💤 dormant
- [recon](https://github.com/gavraz/recon) — tmux-native dashboard for managing Claude Code agents *(★ 263, MIT, drives Claude Code)*
- [cezar](https://github.com/open-mercato/cezar) — Open-source orchestrator for running Claude Code, Codex, OpenCode and other AI coding agents in parallel — locally or 24/7 on your own server *(★ 252, MIT, drives Claude Code, Codex, OpenCode)*
- [claude-code-config-manage-gui](https://github.com/ronghuaxueleng/claude-code-config-manage-gui) — Windows下的claude code配置可视化管理工具 *(★ 250, MIT)* 💤 dormant
- [Caspian](https://github.com/TryCaspian/Caspian) — Caspian is a control room for running multiple AI coding agents in parallel *(★ 215)* 💤 dormant
- [sub-agents](https://github.com/webdevtodayjason/sub-agents) — Claude Code Sub Agent Manager. A simple Manager for adding Claude Code Sub Agents with hooks and custom slash commands *(★ 200, MIT, drives Claude Code)* 📦 archived
- [ccmux](https://github.com/epilande/ccmux) — 🔮 Run all your AI coding agents in tmux: jump to the one that needs you, spawn them into worktrees, and hand work between them *(★ 195, MIT, drives Claude Code, Codex, Cursor)*
- [lazyagent](https://github.com/illegalstudio/lazyagent) — Monitor all your coding agents from one terminal - Claude Code, Cursor, OpenCode, pi and more *(★ 188, MIT, drives Claude Code, Cursor, OpenCode, Pi)*
- [amux](https://github.com/andyrewlee/amux) — TUI for easily running parallel coding agents *(★ 161, MIT)*
- [clorch](https://github.com/androsovm/clorch) — Clorch is a dashboard that shows all your Claude Code sessions in one place *(★ 159, MIT, drives Claude Code)* 💤 dormant
- [gemini-code-flow](https://github.com/Theopsguide/gemini-code-flow) — AI-powered development orchestration for Gemini CLI - adapted from Claude Code Flow by ruvnet *(★ 159, drives Claude Code, Gemini CLI)* 💤 dormant
- [unsnooze](https://unsnooze.combustortech.in/) — Automatically resume Claude Code, Codex CLI, Grok, Qwen Code, Kimi CLI, OpenCode, and Antigravity sessions when 5-hour or weekly usage limits reset—across… *(★ 154, MIT, drives Antigravity, Claude Code, Codex, Grok, Kimi, OpenCode…)*
- [AgentPipe](https://github.com/kevinelliott/agentpipe) — A CLI/TUI app that orchestrates multi-agent conversations by enabling different AI CLI tools (Claude Code, Gemini, Qwen, etc.) to communicate in shared rooms *(★ 149, MIT, drives Claude Code, Gemini CLI, Qwen)*
- [peky](https://github.com/regenrek/peky) — All your AI Agents like Claude Code, Codex CLI in a single TUI to keep things organized *(★ 149, drives Claude Code, Codex)* 💤 dormant
- [OpenKanban](https://github.com/TechDufus/openkanban) — TUI kanban board for orchestrating AI coding agents *(★ 146, AGPL-3.0)*
- [rove](https://github.com/Sma1lboy/rove) — Rove — the agent multiplexer for your terminal. Run coding agents on parallel tasks with isolated worktrees and persistent sessions *(★ 146, MIT)*
- [agenttrace](https://github.com/luoyuctl/agenttrace) — Local-first Rust TUI/CLI for auditing AI coding-agent sessions: cost, tokens, latency, failures, and health｜本地优先 Rust TUI/CLI，审计 AI 编程 Agent… *(★ 136, MIT, drives Claude Code, Codex)*
- [gridbash](https://jasonsuhari.github.io/gridbash/) — Cross-platform terminal grid for running Codex, Claude, Gemini, and other CLI agents side by side *(★ 134, MIT, drives Codex, Gemini CLI)*
- [kodo](https://github.com/ikamensh/kodo) — Orchestrator for AI coding (claude code, cursor, codex, gemini) *(★ 133, MIT, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [clodex](https://github.com/avirtual/clodex) — A visual manager for fleets of Claude Code and Codex agents — real terminals, live context and cost, agents that message each other, across your Mac and any… *(★ 118, Apache-2.0, drives Claude Code, Codex)*
- [wallfacer](https://github.com/pradipta/wallfacer) — A terminal session manager for Claude Code, and more *(★ 117, MIT, drives Claude Code)*
- [claude-session-driver](https://github.com/obra/claude-session-driver) — Launch, control, and monitor other Claude Code sessions as workers via tmux *(★ 109, MIT, drives Claude Code)*
- [dot-agent-deck](https://github.com/vfarcic/dot-agent-deck) — A rich terminal dashboard for monitoring and controlling multiple AI coding agent sessions *(★ 108, MIT)*
- [claude-code-remote](https://github.com/yazinsai/claude-code-remote) — Claude Code Remote - Access Claude Code sessions from any device 📱💻 *(★ 102, drives Claude Code)* 💤 dormant
- [claude-code-session-cleaner](https://github.com/ihoooohi/claude-code-session-cleaner) — A safe, recoverable terminal session manager for Claude Code — browse, diagnose, clean, and restore conversations *(★ 99, MIT, drives Claude Code)*
- [CodexSessionManager](https://github.com/Aiyawoc/CodexSessionManager) — Safety-first GUI and CLI for auditing, backing up, importing, cleaning, and trimming Codex conversations without editing internal storage *(★ 98, MIT, drives Codex)*
- [ccboard](https://github.com/FlorianBruniaux/ccboard) — Monitor Claude Code sessions, costs, config, hooks, agents & MCP servers from a single Rust binary — TUI (9 tabs) + Web interface with live process… *(★ 96, MIT, drives Claude Code)*
- [essentials-claude-code](https://github.com/GantisStorm/essentials-claude-code) — All-in-one workflow plugin—loops, swarms, and teams on Claude Code's Task System. All enforce exit criteria—swarm is   faster with parallel queue execution,… *(★ 91, Unlicense, drives Claude Code)* 💤 dormant
- [claude-code-manager](https://github.com/MarkShawn2020/claude-code-manager) — CCM: Claude Code Management All In One *(★ 90, Apache-2.0, drives Claude Code)* 📦 archived
- [jmux](https://jmux.build/) — A tmux environment built for running coding agents in parallel — with a persistent sidebar that shows every session, what's running, and what needs your… *(★ 86, AGPL-3.0)*
- [sidekick-agent-hub](https://github.com/cesarandreslopez/sidekick-agent-hub) — See what your AI coding agent is doing. Multi-provider assistant & session monitor for VS Code and the terminal — inline completions, code transforms, and a… *(★ 85, MIT, drives Claude Code, Codex, OpenCode)*
- [openclaw-manager-plugin](https://github.com/ClariSortAi/openclaw-manager-plugin) — Claude Code plugin for intelligent OpenClaw installation, configuration, and management *(★ 82, MIT, drives Claude Code, OpenClaw)* 📦 archived
- [thurbox](https://github.com/Thurbeen/thurbox) — TUI for agentic code orchestration *(★ 79, MIT)*
- [workstreams](https://github.com/workstream-labs/workstreams) — IDE for parallel AI coding agents *(★ 79)* 💤 dormant
- [legion](https://github.com/9thLevelSoftware/legion) — Multi-CLI plugin that orchestrates 49 AI agent personalities (start → plan → build → review → ship) across Claude Code, Codex, Cursor, Copilot, Gemini,… *(★ 77, drives Aider, Antigravity, Claude Code, Codex, Copilot, Cursor…)*
- [claude-code-web](https://github.com/sunpix/claude-code-web) — A web-based interface for Claude Code CLI built with Nuxt 4, featuring real-time chat, project management, and comprehensive tool integration with… *(★ 76, MIT, drives Claude Code)* 💤 dormant
- [Martty](https://github.com/openma-ai/Martty) — Unified Harness TUI (ACP client). Self-Improvement TUI plugin of DeepSeek Harness. Everything Here Is Also A Plugin *(★ 76, MIT, drives DeepSeek)*
- [claude-hooks](https://github.com/webdevtodayjason/claude-hooks) — Claude Code Hooks Manager for managing Hooks in Claude Code via CLI *(★ 74, MIT, drives Claude Code)* 💤 dormant
- [vibemux](https://github.com/UgOrange/vibemux) — VibeMux – Orchestrate parallel Claude Code agents in a single TUI *(★ 74, drives Claude Code)* 💤 dormant
- [Claude-Code-Web-GUI](https://github.com/binggg/Claude-Code-Web-GUI) — Browse, view and share your Claude Code sessions - runs entirely in browser 浏览和查看您的 Claude Code 会话历史 - 完全在浏览器中运行，无需服务器 *(★ 73, MIT, drives Claude Code)* 💤 dormant
- [ai-fleet](https://github.com/nachoal/ai-fleet) — AI Agent fleet manager for parallel agentic systems like claude code and codex *(★ 68, MIT, drives Claude Code, Codex)* 💤 dormant
- [agent-orchestrator](https://github.com/willynikes2/agent-orchestrator) — Three AI agents. One brain. Zero downtime. Multi-agent CLI orchestrator with next-man-up failover for Claude, Codex, and Gemini *(★ 66, MIT, drives Codex, Gemini CLI)* 💤 dormant
- [tmuxcc](https://github.com/nyanko3141592/tmuxcc) — TUI dashboard for managing AI coding agents (Claude Code, OpenCode, Codex CLI, Gemini CLI) in tmux *(★ 65, MIT, drives Claude Code, Codex, Gemini CLI, OpenCode)* 💤 dormant
- [ultracodex](https://www.npmjs.com/package/ultracodex) — Run Claude Code workflow scripts, unmodified, on the OpenAI Codex CLI — fable plans, codex executes, fable verifies. Parallel agent fleets, builder–verifier… *(★ 65, Apache-2.0, drives Claude Code, Codex)*
- [mjolnir](https://github.com/BrokkAi/mjolnir) — Manage Codex, Claude Code, Muse Code, Kimi Code, Grok Build, and DeepSeek Harness with durable sessions, isolated environments, quotas, and remote control.… *(★ 64, GPL-3.0, drives Claude Code, Codex, DeepSeek, Grok Build, Kimi)*
- [codex-migrate](https://github.com/ChenglongLi777/codex-migrate) — Cross-platform GUI and CLI for migrating, repairing, backing up, and exporting local Codex sessions *(★ 62, MIT, drives Codex)*
- [YYLO](https://github.com/yylo-dev/yylo) — YYLO (why-lo): AI coding-agent orchestration CLI with equivalent yylo and yy launchers *(★ 61, MIT, drives Codex, Pi)*
- [Agent AFK](https://github.com/griffinwork40/agent-afk) — The coding agent you don’t have to watch. Start a task and walk away. AFK builds the feature, verifies its own work, and texts you when it’s done. You come… *(★ 55, Apache-2.0)*
- [showagent](https://github.com/aytzey/showagent) — Find local coding-agent sessions and copy their user and assistant messages into another agent's native format. TUI, CLI and MCP *(★ 49, MIT)*
- [agent-console](https://github.com/buhuipao/agent-console) — A local terminal control plane for Codex, Claude Code, and pi sessions—discover, monitor, resume, and work beside persistent workspace shells *(★ 31, Apache-2.0, drives Claude Code, Codex, Pi)*
- [Vigil](https://github.com/butterlatte-zhang/vigil) — A native macOS multi-agent terminal orchestrator: manager-driven agent trees for Claude Code, Codex, and OpenCode *(★ 28, GPL-3.0, drives Claude Code, Codex, OpenCode)*
- [agents-cli](https://github.com/phnx-labs/agi-cli) — AGI CLI ~ a meta-harness for building Agent Factories *(★ 24)*
- [repomon](https://github.com/AliHamzaAzam/repomon) — Mission control for a fleet of AI coding agents (Claude Code, Codex, Antigravity, OpenCode, Cursor, Aider) across many repos — desktop app + Rust TUI,… *(★ 21, Apache-2.0, drives Aider, Antigravity, Claude Code, Codex, Cursor, OpenCode)*
- [Claudescope](https://github.com/vladar107/claudescope) — A scope for your Ai coding-agent sessions *(★ 18, MIT)*
- [construct](https://github.com/construct-worlds/construct) — A terminal-native ADE (agentic development environment) *(★ 18, MIT)*
- [pappardelle](https://github.com/chardigio/pappardelle) — A TUI for multi-clauding without losing your marbles *(★ 17, MIT, drives Claude Code)*
- [agent-session-manager](https://github.com/izll/agent-session-manager) — Terminal session manager for AI coding agents (Claude, Gemini, Aider, OpenCode). Built with Go + Bubble Tea *(★ 13, MIT, drives Aider, Amazon Q, Claude Code, Codex, Gemini CLI, OpenCode)*
- [Cyclops](https://github.com/cyclops-team/cyclops) — The terminal workspace for working with coding agents *(★ 12, MIT, drives Antigravity, Claude Code, Codex, Cursor)*
- [pi-boss](https://github.com/skyfallsin/pi-boss) — Spawn and manage sub-agents in visible tmux panes — the orchestrator that makes multi-agent boss mode work for pi coding agent *(★ 11, MIT, drives Pi)* 💤 dormant
- [Polter](https://github.com/Lugia123/polter) — One Claude Code session supervises the agents in your other terminal tabs: which is stuck, which is done, which is still running. A fork of Ghostty *(★ 11, MIT, drives Claude Code)*
- [tmuxlet](https://github.com/truefrontier/tmuxlet) —  *(★ 8, MIT)*
- [mix2](https://github.com/elleryfamilia/mix2) — Two coding agents. Independent takes. One answer *(★ 5, MIT)*
- [Agent CLI Menu](https://github.com/roypadina/agentctl) — Start and resume Claude Code & Codex sessions from one menu — fuzzy-resume past sessions with transcript preview. Terminal TUI + native macOS menu-bar GUI *(★ 2, MIT, drives Claude Code, Codex)*
- [tring](https://github.com/matogen/tring.chat) — A focus-centred terminal deck for agentic work: run up to 16 Claude Code / agent sessions, one in focus, the rest as live thumbnails that turn green when done *(★ 2, MIT, drives Claude Code)*
- [AgentX](https://github.com/ArcheMind/agentx) — Native-first runtime manager for discovering, installing, launching, and resuming AI coding-agent CLIs *(MIT)*
- [Bwee](https://bwee.app) — custom tools and dashboards that live alongside the terminal. Persistent sessions and task management. macOS
- [JAT](https://github.com/joewinke/jat) — Local web IDE dashboard to supervise 20+ agents with live sessions, task management, editor, and automation triggers
- [Relay protocol is open source](https://github.com/bertshim/termlink-relay) — Remote access and session management for Claude Code - from any browser or phone, without SSH, VPN, or open ports. Open-source subset of TermLink (getterm.link) *(Apache-2.0, drives Claude Code)*

## Web Dashboards & Control Planes

*Self-hosted web UIs and control planes for launching and steering agents.*

- [T3 Code](https://t3.codes/) — Harness control surface available as web, mobile, and desktop app. Claude Code, Codex, Cursor, Grok Build, OpenCode *(★ 23.6k, MIT, drives Claude Code, Codex, Cursor, Grok Build, OpenCode)*
- [pi-web](https://github.com/agegr/pi-web) — Web UI for the pi coding agent *(★ 6.9k, MIT, drives Pi)*
- [Mission Control](https://github.com/builderz-labs/mission-control) — Self-hosted control plane for AI agents: dispatch tasks, review runs, track spend, and operate OpenClaw, Claude Code, Codex, and other runtimes *(★ 6.3k, MIT, drives Claude Code, Codex, OpenClaw)*
- [harnessrouter](https://github.com/HarnessRouter/harnessrouter) — HarnessRouter Community Edition: the self-hosted, Apache-2.0 edition of the unified interface for agent harnesses. Run Codex, Claude Code, Hermes, PI, DSH,… *(★ 2.7k, Apache-2.0, drives Claude Code, Codex, Hermes, Pi)*
- [HolyClaude](https://github.com/CoderLuii/HolyClaude) — AI coding workstation: Claude Code + web UI + 8 AI CLIs + headless browser + 50+ tools *(★ 2.6k, MIT, drives Claude Code)*
- [Cline (Kanban)](https://cline.bot/) — Launch a local web app that runs CLI agents in parallel *(★ 1.3k, Apache-2.0, drives Cline)*
- [Alook](https://github.com/alookai/alook) — Rooms for people and agents *(★ 1.2k, Apache-2.0, drives Claude Code, Codex, OpenCode)*
- [cui](https://github.com/wbopan/cui) — A web UI for Claude Code agents *(★ 1.1k, Apache-2.0, drives Claude Code)* 📦 archived
- [Claude Code Agent Monitor](https://hoangsonww.github.io/Claude-Code-Agent-Monitor/) — 🚀 A real-time monitoring dashboard for Claude Code & Codex, built with SQLite3, Node.js, Express, React, Vite, TailwindCSS, & WebSockets. It tracks… *(★ 1k, MIT, drives Claude Code, Codex)*
- [IM.codes](https://github.com/im4codes/imcodes) — The IM for agents. Shared Agent Context & Memory, supervised execution, and cross-agent audit across AI providers *(★ 971, MIT, drives Claude Code, Codex, Gemini CLI)*
- [kandev](https://github.com/kdlbs/kandev) — AI Kanban & Development Environment. Orchestrate multiple agents, review changes, open PRs. Multi-provider, self-hostable, no telemetry *(★ 847, AGPL-3.0)*
- [pi-web](https://github.com/jmfederico/pi-web) — Web UI for Pi Coding Agent that keeps sessions alive in real workspaces *(★ 821, MIT, drives Pi)*
- [Codeman](https://github.com/Ark0N/Codeman) — Self-hosted mission control for AI coding agents: run Claude Code, OpenCode, Pi, Codex, and Antigravity & Gemini CLI 24/7, from any device, watch every… *(★ 769, MIT, drives Antigravity, Claude Code, Codex, Gemini CLI, OpenCode, Pi)*
- [kanna](https://github.com/jakemor/kanna) — A beautiful web-based UI for Claude Code & Codex *(★ 687, drives Claude Code, Codex)*
- [claude-run](https://github.com/nilbuild/claude-run) — A beautiful web UI for browsing Claude Code conversation history *(★ 672, MIT, drives Claude Code)* 💤 dormant
- [kanbots](https://kanbots.dev/) — Local collaboration interface for working on a kanban board where each task is either a Claude Code or Codex agent *(★ 607, MIT, drives Claude Code, Codex)* 💤 dormant
- [zhikuncode](https://github.com/zhikunqingtao/zhikuncode) — Codex/Claude Code/Cursor的开源增强版，专注一句话实现复杂长程任务（教育、编程、办公、生活、娱乐、游戏）。部署在你自己的服务器上，团队用浏览器打开就能编程——包括手机。CLI & Web UI 双入口，Multi-Agent 协作，原生直连千问/DeepSeek… *(★ 503, MIT, drives Claude Code, Codex, Cursor, DeepSeek)*
- [Open Session](https://github.com/tellahq/opensession) — Self-hosted server driving coding sessions in git worktrees on your own box or in isolated sandboxes, with a web UI, Slack/Linear/Plain/GitHub intake, diff… *(★ 386, MIT, drives Codex)*
- [codexmate](https://github.com/SakuraByteCore/codexmate) — One dashboard for all your local AI coding agents. Switch providers, manage sessions, and orchestrate tasks across Codex, Claude Code, Gemini CLI, CodeBuddy… *(★ 350, Apache-2.0, drives Claude Code, CodeBuddy, Codex, Gemini CLI, KiloCode, OpenClaw…)*
- [agentrove](https://github.com/Mng-dev-ai/agentrove) — Self-hosted AI coding workspace to run and orchestrate Claude Code, Codex, Copilot, Cursor, Grok and OpenCode agents — multi-agent workflows, personas, and… *(★ 329, Apache-2.0, drives Claude Code, Codex, Copilot, Cursor, Grok, OpenCode)*
- [TurboLLM](https://github.com/mohitsoni48/TurboLLM) — Run any local LLM engine, auto-tuned to your GPU — polished web UI + OpenAI/Anthropic-compatible API. Point Claude Code at your own machine in one command.… *(★ 277, drives Claude Code)*
- [Ivy-Tendril](https://github.com/Ivy-Interactive/Ivy-Tendril) — AI agents can now write 99% of the code. This changes what it means to be a developer. Our role shifts to knowing "what good looks like". To do that, we… *(★ 198, drives Antigravity, Claude Code, Codex, Copilot, OpenCode)*
- [stoneforge](https://github.com/stoneforge-ai/stoneforge) — A web dashboard and runtime for orchestrating AI coding agents *(★ 190, Apache-2.0)* 💤 dormant
- [ClawFleet](https://github.com/clawfleet/ClawFleet) — Deploy a fleet of AI agents (OpenClaw, Hermes) on your machine in 10 minutes — use your ChatGPT subscription, no cloud bills. Open-source fleet manager with… *(★ 173, MIT, drives Hermes, OpenClaw)* 💤 dormant
- [Claude Code Board](https://cc-board.cablate.com/) — Use Claude Code on Kanban WebUI *(★ 156, MIT, drives Claude Code)* 💤 dormant
- [cdesktop](https://github.com/cdesktop-ai/cdesktop) — Open-source Claude Code Desktop alternative. Use any provider/model. Web UI for Claude Code, Codex, Gemini CLI, OpenCode, Hermes *(★ 143, Apache-2.0, drives Claude Code, Codex, Gemini CLI, Hermes, OpenCode)* 💤 dormant
- [tlbx](https://github.com/tlbx-ai/tlbx) — Self-hosted terminal browser multiplexer for persistent shells and coding agents on Windows, macOS, and Linux *(★ 112, AGPL-3.0)*
- [octoally](https://github.com/ai-genius-automations/octoally) — AI coding session orchestration dashboard — launch, monitor, and manage Claude Code sessions from a web UI *(★ 100, drives Claude Code)*
- [ADHDev](https://github.com/vilmire/adhdev) — 🦦 ADHDev — Agent Dashboard Hub. Monitor & control AI coding agents from a single dashboard. Self-hosted, open-source *(★ 98, AGPL-3.0)*
- [anyplane](https://github.com/OneCuriousLearner/anyplane) — Self-hosted, vendor-neutral control plane for your local coding agents (Claude Code & Codex). Run your agents, on any plane *(★ 98, MIT, drives Claude Code, Codex)*
- [claude-web](https://github.com/heng1234/claude-web) — Web UI for Claude Code CLI - token streaming, tool visualization, checkpoint, multi-session management *(★ 80, Apache-2.0, drives Claude Code)*
- [recensa](https://github.com/S40911120/recensa) — Self-hosted web viewer for Claude Code session transcripts — read, search, replay, and audit every session you have ever run *(★ 73, MIT, drives Claude Code)*
- [TermHive](https://github.com/0x0funky/TermHive) — Human-driven multi-agent dashboard for Claude Code, Codex, Gemini & OpenCode. Web UI, project wiki, shared content,   and MCP-based agent messaging — see… *(★ 71, drives Claude Code, Codex, Gemini CLI, OpenCode)* 💤 dormant
- [claude-team-dashboard](https://github.com/mukul975/claude-team-dashboard) — 📊 Real-time monitoring dashboard for Claude Code agent teams *(★ 70, MIT, drives Claude Code)* 💤 dormant
- [agent-native-agent](https://github.com/tykimos/agent-native-agent) — Self-hosted apps you operate by watching a dashboard and talking to a coding agent that IS the runtime — it proposes, applies, and evolves the app live.… *(★ 67, AGPL-3.0, drives Claude Code)*
- [watchtower](https://github.com/fahd09/watchtower) — Watchtower — monitor, inspect, and debug all API traffic between AI coding agents (Claude Code, Codex CLI) and their APIs, with a real-time web dashboard *(★ 65, MIT, drives Claude Code, Codex)*
- [VibeBridge](https://github.com/Swayyyyy/VibeBridge) — Web UI for remote control of Claude Code and Codex across multiple machines and nodes *(★ 63, GPL-3.0, drives Claude Code, Codex)* 💤 dormant
- [tiger_cowork](https://github.com/Sompote/tiger_cowork) — A self-hosted AI workspace unifying chat, code execution, parallel multi-agent orchestration, and project management. Each agent runs on a distinct provider… *(★ 61, MIT, drives Claude Code, Codex)*
- [intentic](https://github.com/intentic/intentic) — More work. Less AI waste. Same subscriptions *(★ 46, MIT, drives Claude Code, Codex, Gemini CLI, Grok, Kimi)*
- [vibepanel](https://github.com/jiangmuran/vibepanel) — A web console for running many parallel coding-agent sessions. tmux keeps the processes alive; the browser owns organisation, naming, state and ordering *(★ 31)*
- [agent-squid](https://github.com/agent-squid/squid) — Your Local Coding Agents, Unified *(★ 18, MIT)*
- [Podiom](https://github.com/Podiom/Podiom) — Thin orchestration layer for local LLM agents. Durable sessions, profiles, scheduling, and native MCP/tool/skill integration *(★ 15, MIT)*
- [CLITrigger](https://github.com/HyperAITeam/CLITrigger) — A command center for AI coding agents — run Claude, Gemini & Codex in parallel, each in its own git worktree *(★ 14, MIT, drives Codex, Gemini CLI)*
- [Agent Workbench](https://github.com/cvelasquez/agent-workbench) — One local UI for the Claude Code, Codex, OpenCode and Antigravity CLIs: tabs, browsable history, conversations as cards, handoff between CLIs, global… *(★ 2, MIT, drives Antigravity, Claude Code, Codex, OpenCode)*
- [Better Agent](https://github.com/ofekron/better-agent)
- [Catnip](https://github.com/wandb/catnip) — Self-hostable web service (W&B) running Claude Code in containerized worktree sandboxes, with a native iOS app *(drives Claude Code)*

## Cloud & Hosted Control Planes

*Hosted services that run agents in the cloud or provide managed control planes.*

- [OpenHands](https://github.com/OpenHands/OpenHands) — 🙌 OpenHands: AI-Driven Development *(★ 89.2k, MIT, drives Claude Code, Codex)*
- [Oz](https://www.warp.dev/oz) — Warp is an agentic development environment, born out of the terminal *(★ 65.2k, AGPL-3.0)*
- [Scion](https://googlecloudplatform.github.io/scion/) — Experimental host-side CLI + hub (Google Cloud) orchestrating agents in isolated containers with their own worktrees and credentials *(★ 1.7k, Apache-2.0)*
- [Droid](https://github.com/Factory-AI/factory) — Factory - Agent-Native Software Development *(★ 31, drives Factory Droid)*
- [Jules](https://jules.google.com) — Google's async coding agent that runs tasks in cloud VMs and opens PRs on your repos
- [Niteshift](https://niteshift.dev) — Full-stack cloud for coding agents: bring Claude Code, Codex, OpenCode, or Pi, with runtime + verification workflows and dozens of concurrent sessions… *(drives Claude Code, Codex, OpenCode, Pi)*
- [Replit Agent](https://replit.com/agent) — Cloud workspace where Replit's agent builds and deploys full apps from natural language
- [Tembo](https://tembo.io) — Platform to move coding agents to the cloud: orchestrates Claude Code, Codex, Cursor, Amp, or OpenCode across repos in parallel cloud sandboxes, triggered… *(drives Amp, Claude Code, Codex, Cursor, OpenCode)*

## Mobile & Remote-Control Clients

*Phone, tablet, and messenger clients that reach back into local or cloud agent sessions.*

- [Happy](https://github.com/slopus/happy) — Mobile and Web client for Codex and Claude Code, with realtime voice, encryption and fully featured *(★ 23.9k, MIT, drives Claude Code, Codex)*
- [Paseo](https://paseo.sh/) — Orchestrate multiple coding agents from desktop and mobile *(★ 18.6k, drives Claude Code, Codex, Copilot, OpenCode, Pi)*
- [cc-connect](https://github.com/chenhg5/cc-connect) — Bridge local AI coding agents (Claude Code, Cursor, Gemini CLI, Codex) to messaging platforms (Feishu/Lark, DingTalk, Slack, Telegram, Discord, LINE, WeChat… *(★ 15.7k, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [Claude Code UI](https://github.com/siteboon/claudecodeui) — Use Claude Code, OpenCode, Cursor CLI, and Codex on mobile and web with CloudCLI (aka Claude Code UI). CloudCLI is a free open source webui/GUI that helps… *(★ 13.8k, AGPL-3.0, drives Claude Code, Codex, Cursor, OpenCode)*
- [refly](https://github.com/refly-ai/refly) — The first open-source agent skills builder. Define skills by vibe workflow, run on Claude Code, Cursor, Codex & more. Build Clawdbot 🦞· APIs for Lovable ·… *(★ 7.5k, drives Claude Code, Codex, Cursor, Vibe)*
- [CodePilot](https://github.com/op7418/CodePilot) — A multi-model AI agent desktop client — connect any AI provider, extend with MCP & skills, control from your phone. Built with Electron + Next.js *(★ 6.5k, drives Claude Code)*
- [VibeTunnel](https://github.com/amantus-ai/vibetunnel) — Turn any browser into your terminal & command your agents on the go *(★ 4.7k, MIT, drives Claude Code)*
- [Claude Codex Bridge](https://github.com/SeemSeam/claude_codex_bridge) — Visible multi-agent CLI workspace for mixing Codex, Claude, Gemini, Kimi, Qwen, Cursor, Copilot, Pi, OpenCode, and other AI coding agents *(★ 3.5k, drives Codex, Copilot, Cursor, Gemini CLI, Kimi, OpenCode…)*
- [Moltis](https://github.com/moltis-org/moltis) — A secure persistent personal agent server in Rust. One binary, sandboxed execution, multi-provider LLMs, voice, memory, Telegram, WhatsApp, Discord, Teams,… *(★ 2.9k, MIT)*
- [Omnara](https://github.com/omnara-ai/omnara) — The open-source alternative to Claude Managed Agents *(★ 2.9k, Apache-2.0, drives Claude Code, Codex)*
- [claude-code-telegram](https://github.com/overwirehq/claude-code-telegram) — A powerful Telegram bot that provides remote access to Claude Code, enabling developers to interact with their projects from anywhere with full AI… *(★ 2.8k, drives Claude Code)*
- [nexting](https://github.com/Nexting-ai/nexting) — Remote control for Claude Code, Codex, Grok, and Cursor on Mac or PC. View sessions, send tasks, and drive them remotely from your phone, PIN, or Ring.… *(★ 1.9k, MIT, drives Claude Code, Codex, Cursor, Grok, OpenClaw)*
- [happier](https://github.com/happier-dev/happier) — Web, Desktop & Mobile client and orchestrator for Codex, Claude Code, OpenCode, Pi, Cursor, Grok, Antigravity, Kimi, Augment Code, Qwen, fully end-to-end… *(★ 1.7k, MIT, drives Antigravity, Augment, Claude Code, Codex, Cursor, Grok…)*
- [Centaur](https://centaur.run/) — Centaur is frontier, agentic infrastructure that you own. Centaur is like Claude Tag, but open source and on steroids *(★ 1.3k)*
- [Claude-Code-Remote](https://github.com/JessyTsui/Claude-Code-Remote) — Control Claude Code remotely via email、discord、telegram. Start tasks locally, receive notifications when Claude completes them, and send new commands by… *(★ 1.3k, MIT, drives Claude Code)* 💤 dormant
- [ccpocket](https://github.com/K9i-0/ccpocket) — Mobile client for Codex and Claude — control coding agents from your phone via WebSocket bridge *(★ 1.1k, MIT, drives Codex)*
- [takopi](https://github.com/banteg/takopi) — he just wants to help-pi! *(★ 1.1k, MIT, drives Claude Code, Codex, OpenCode, Pi)* 💤 dormant
- [metabot](https://github.com/xvirobotics/metabot) — 构建受监督的、自我进化的 Agent 组织的基础设施 · Infrastructure for supervised, self-improving agent organization. 飞书/Telegram 手机端运行 Claude Code 或 Kimi… *(★ 988, MIT, drives Claude Code, Kimi)*
- [claude-code-by-agents](https://claudecode.run/) — Desktop app and API created in public for multi-agent Claude Code orchestration - coordinate local and remote agents through @mentions *(★ 893, MIT, drives Claude Code)* 💤 dormant
- [OpenSwarm](https://github.com/Intrect-io/OpenSwarm) — OpenSwarm — Autonomous AI dev team orchestrator powered by Claude Code CLI. Discord control, Linear integration, cognitive memory *(★ 856, MIT, drives Claude Code)*
- [deepseek-harness-desktop](https://github.com/ningbainb/deepseek-harness-desktop) — Open-source Windows desktop client and GUI for DeepSeek Harness — zero-setup installer with Codex, plugins, skills, SSH, mobile remote access, and 11 skins *(★ 732, BSD-3-Clause, drives Codex, DeepSeek)*
- [ccteam](https://github.com/firstintent/ccteam) — ccteam turns the coding agents you already run (Claude Code, Codex, Grok, DeepSeek Harness, Kimi, Pi) into one team — any session can spawn, dispatch, and… *(★ 622, MIT, drives Claude Code, Codex, DeepSeek, Grok, Kimi, Pi)*
- [9remote](https://github.com/decolua/9remote) — 📱 Terminal in Your Pocket — Control Claude Code, Codex, Gemini CLI & your Mac/Linux/Windows from any phone or browser. Vibe coding from anywhere.… *(★ 610, drives Claude Code, Codex, Gemini CLI, Vibe, mux)*
- [claudecode-telegram](https://github.com/hanxiao/claudecode-telegram) — Telegram bridge for Claude Code *(★ 609, drives Claude Code)* 💤 dormant
- [happy-cli](https://github.com/slopus/happy-cli) — Happy Coder CLI to connect your local Claude Code to mobile device *(★ 554, drives Claude Code)* 📦 archived
- [Pane](https://github.com/greenfield-inc/Pane) — Terminal-first, open-source AI agent manager for any CLI agent (agent agnostic), any OS (mac, windows, linux). The Open-Source Agentic Development… *(★ 489)*
- [Claude-to-IM](https://github.com/op7418/Claude-to-IM) — Host-agnostic bridge connecting Claude Code SDK to IM platforms (Telegram, Discord, Feishu) *(★ 473, MIT, drives Claude Code)* 💤 dormant
- [ductor](https://github.com/PleasePrompto/ductor) — Control Claude Code, Codex CLI and Gemini CLI from Telegram. Live streaming, persistent memory, cron jobs, webhooks, Docker sandboxing *(★ 458, MIT, drives Claude Code, Codex, Gemini CLI)*
- [Mobile-Harness](https://github.com/techjarves/Mobile-Harness) — Claude Code on Android:  AI-powered mobile coding IDE for Android — chat with a coding agent, run Linux commands, edit files, review diffs, and preview web… *(★ 424, MIT, drives Claude Code)*
- [remote_pi](https://github.com/jacobaraujo7/remote_pi) — Control your Pi coding agent from your phone. Pair with a one-time QR code and chat with your local agent, even when you're away from your computer *(★ 410, MIT, drives Pi)*
- [clauntty](https://github.com/eriklangille/clauntty) — iOS Terminal with native Claude Code support *(★ 399, drives Claude Code)*
- [claude-telegram-relay](https://github.com/godagoo/claude-telegram-relay) — Minimal pattern for running Claude Code as an always-on Telegram bot. Cross-platform daemon setup included *(★ 326, MIT, drives Claude Code)* 💤 dormant
- [golembot](https://github.com/0xranx/golembot) — Any Agent × Any Provider × Anywhere. Connect Cursor, Claude Code, OpenCode, or Codex to Slack, Telegram, Discord, Feishu, DingTalk, WeCom, WeChat — with any… *(★ 322, MIT, drives Claude Code, Codex, Cursor, OpenCode)*
- [claude-code-monitor](https://github.com/onikan27/claude-code-monitor) — Real-time dashboard for monitoring multiple Claude Code sessions. CLI + Mobile Web UI with QR code access, terminal focus   switching (iTerm2, Terminal.app,… *(★ 310, MIT, drives Claude Code)* 💤 dormant
- [termly-cli](https://github.com/termly-dev/termly-cli) — Mobile companion for Claude Code, Gemini CLI & OpenCode. Encrypted, remote *(★ 310, MIT, drives Claude Code, Gemini CLI, OpenCode)*
- [pi-agent-dashboard](https://github.com/BlackBeltTechnology/pi-agent-dashboard) — Real-time web dashboard for pi coding-agent sessions. Multi-session view, live chat mirroring, integrated terminal, diff viewer, pi-flows execution, and… *(★ 303, MIT, drives Pi)*
- [ccbot](https://github.com/six-ddc/ccbot) — Telegram ↔ tmux bridge for Claude Code: 1 topic = 1 window = 1 session *(★ 274, MIT, drives Claude Code)*
- [CcCompanion](https://github.com/CyberSealNull/CcCompanion) — Unofficial MIT-licensed iOS companion for Claude Code: self-hosted relay, local-first chat, search, and session control from your iPhone. Not affiliated… *(★ 264, MIT, drives Claude Code)*
- [repowire](https://github.com/prassanna-ravishankar/repowire) — May the agents talk . Connect Claude Code, Opencode, Codex, Pi across projects, across machines and with your telegram *(★ 264, drives Claude Code, Codex, OpenCode, Pi)*
- [bagidea-office](https://github.com/bagidea/bagidea-office) — A living AI-agent office on your desktop wallpaper — Claude Code agents that walk, work, delegate, learn & hold meetings. Per-agent swappable models… *(★ 235, MIT, drives Claude Code, DeepSeek, Gemini CLI, Kimi, Qwen)*
- [tlive](https://github.com/y49/tlive) — Self-hosted remote approvals + live monitoring for Claude Code / Codex — via Telegram, Feishu, or a web terminal. Any subscription or API key *(★ 213, MIT, drives Claude Code, Codex)*
- [cc-clip](https://github.com/ShunmeiCho/cc-clip) — Paste images into remote Claude Code & Codex CLI over SSH — clipboard bridging for macOS and Windows *(★ 161, MIT, drives Claude Code, Codex)*
- [handmux](https://github.com/handmux/handmux) — A mobile vibe-coding cockpit — built on tmux: drive your live session, Claude Code / Codex — anything a terminal can run — from your phone. 移动 Vibe Coding… *(★ 161, AGPL-3.0, drives Claude Code, Codex, Vibe)*
- [clideck](https://github.com/rustykuntz/clideck) — A dashboard for running and coordinating multiple AI CLI agents at once *(★ 159, MIT, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [claude-code-remote](https://github.com/buckle42/claude-code-remote) — Use Claude Code from your phone — or anywhere — over a secure VPN connection *(★ 154, drives Claude Code)* 💤 dormant
- [claudegram](https://github.com/NachoSEO/claudegram) — Telegram bot that bridges messages to Claude Code *(★ 152, drives Claude Code)* 💤 dormant
- [claude-telegram-bot-bridge](https://github.com/terranc/claude-telegram-bot-bridge) — A lightweight Telegram bot that bridges Claude Code to any local folder, with autostart support for remote mobile development *(★ 132, drives Claude Code)* 💤 dormant
- [aaa-code-release](https://github.com/hwwn/aaa-code-release) — Cross-platform Claude Code desktop client by hwwn. Multi-workspace, remote mobile access, session branching, BYO LLM. macOS / Windows / Linux *(★ 128, drives Claude Code)*
- [claudeclaw](https://github.com/robonuggets/claudeclaw) — A reference blueprint for building persistent, multi-agent Claude Code setups with Telegram and Discord *(★ 125, drives Claude Code)* 💤 dormant
- [sesori_apps_monorepo](https://github.com/sesori-ai/sesori_apps_monorepo) — Sesori iOS/Android app and the Sesori Bridge CLI — drive Claude, Codex, OpenCode, Cursor, Pi, OMP, Hermes coding sessions from your phone *(★ 122, drives Codex, Cursor, Hermes, Oh My Pi, OpenCode, Pi)*
- [claude-telegram-supercharged](https://github.com/k1p1l0/claude-telegram-supercharged) — Run Claude Code 24/7 from Telegram. Drop-in upgrade for the official plugin: voice notes both ways, a self-healing daemon, memory across restarts, and… *(★ 116, Apache-2.0, drives Claude Code)*
- [mobile-observability](https://github.com/nexus-labs-automation/mobile-observability) — Claude Code plugin for mobile app observability: crash reporting, performance monitoring, and instrumentation for iOS, Android, and React Native *(★ 116, MIT, drives Claude Code)*
- [remote-claude-code](https://github.com/theNetworkChuck/remote-claude-code) — Run Claude Code on a VPS and access it from your phone, tablet, or any device. Code from anywhere *(★ 108, drives Claude Code)* 💤 dormant
- [mimi-remote](https://github.com/gaixianggeng/mimi-remote) — Open-source native iPhone/iPad client for OpenAI Codex CLI and Claude Code — review diffs, approve actions, steer sessions, and manage Git remotely *(★ 102, drives Claude Code, Codex)*
- [whatsapp-claude-plugin](https://github.com/Rich627/whatsapp-claude-plugin) — Claude Code WhatsApp channel plugin — run AI directly from WhatsApp, voice transcription, remote tool approval, access control. No API keys, no Docker, just… *(★ 98, Apache-2.0, drives Claude Code)*
- [heyagent](https://github.com/gergomiklos/heyagent) — Telegram bridge for Claude Code and Codex CLI *(★ 95, MIT, drives Claude Code, Codex)* 💤 dormant
- [afk-code](https://github.com/clharman/afk-code) — Interact with local Claude Code sessions From Telegram, Discord, Slack *(★ 90, MIT, drives Claude Code)* 💤 dormant
- [iOS-vibebuddy](https://github.com/semantic-craft/iOS-vibebuddy) — Native Mac, iPhone & Apple Watch companion for Claude Code, Codex, Grok and Cursor. Task inbox, wrist notifications, agent handoffs, quota widgets, optional… *(★ 90, MIT, drives Claude Code, Codex, Cursor, Grok)*
- [tsgram-mcp](https://github.com/areweai/tsgram-mcp) — TSGram - Telegram MCP Server for local Claude Code integration - debug and vibe code on the go! *(★ 89, MIT, drives Claude Code, Vibe)* 💤 dormant
- [harness-bridge](https://github.com/0xSero/harness-bridge) — Point any coding harness (Claude Code, Codex, OpenCode, Pi, OMP, Crush, Copilot, Grok…) at any OpenAI/Anthropic/Responses-compatible inference endpoint.… *(★ 88, MIT, drives Claude Code, Codex, Copilot, Crush, Grok, Oh My Pi…)*
- [bridge4simulator](https://github.com/AppGram/bridge4simulator) — An MCP (Model Context Protocol) server that enables AI assistants to control iOS Simulator. Seamlessly integrates with Claude Desktop, Cursor, Claude Code,… *(★ 80, drives Claude Code, Cursor)* 💤 dormant
- [instar](https://github.com/JKHeadley/instar) — Persistent Claude Code agents with scheduling, sessions, memory, and Telegram *(★ 80, MIT, drives Claude Code)*
- [code-by-wire](https://github.com/luojiahai/code-by-wire) — Pilot coding agents (Claude Code, Codex) and monitor their telemetry from one cockpit *(★ 76, MIT, drives Claude Code, Codex)*
- [247-claude-code-remote](https://github.com/QuivrHQ/247-claude-code-remote) — Access Claude Code from anywhere - Mobile / Desktop secure connection via Tailscale. Provision VMs with Fly.io. Compatible with Gemini / Codex / OpenCode *(★ 75, drives Claude Code, Codex, Gemini CLI, OpenCode)* 💤 dormant
- [claude-remote-approver](https://github.com/yuuichieguchi/claude-remote-approver) — Approve Claude Code permission requests from your phone via ntfy *(★ 74, MIT, drives Claude Code)* 💤 dormant
- [Untether](https://github.com/littlebearapps/untether) — Code from anywhere — Telegram bridge for AI coding agents (Claude Code, Codex, OpenCode, Pi, Gemini CLI, Amp). Stream progress, approve actions, and send… *(★ 70, MIT, drives Amp, Claude Code, Codex, Gemini CLI, OpenCode, Pi)*
- [AgEnD](https://github.com/suzuke/AgEnD) — Multi-agent fleet daemon — run Claude Code, Gemini CLI, Codex, and OpenCode from Telegram with cross-instance collaboration *(★ 66, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [opendray](https://github.com/Opendray/opendray) — Self-hosted gateway for Claude Code, Codex, Antigravity, Grok Build, OpenCode. Run AI coding agents on your own infra with a shared local-first memory… *(★ 66, Apache-2.0, drives Antigravity, Claude Code, Codex, Grok Build, OpenCode)*
- [codelight](https://github.com/henrikekblad/codelight) — Multi-agent remote dashboard for Claude Code, Copilot, and Codex. Approve permissions, answer questions, and monitor token usage in real-time from a… *(★ 65, MIT, drives Claude Code, Codex, Copilot)*
- [ClaudeBot](https://github.com/Jeffrey0117/ClaudeBot) — Not a pipe to Claude. A command center on your phone. — Telegram bot for Claude Code CLI with plugin system, multi-bot, queue, streaming, and hot-reload *(★ 64, drives Claude Code)*
- [claudecode-discord](https://github.com/chadingTV/claudecode-discord) — Control Claude Code from your phone — a multi-machine agent hub via Discord. No API key needed, runs on your Claude Pro/Max subscription. Start new sessions… *(★ 63, MIT, drives Claude Code)* 💤 dormant
- [ClawCode](https://github.com/crisandrews/ClawCode) — Persistent agents for Claude Code as a plugin, not a harness. Memory, personality, messaging across WhatsApp, Telegram, and Discord, plus a service mode for… *(★ 63, MIT, drives Claude Code, OpenClaw)*
- [run-kit](https://github.com/sahil87/run-kit) — A remote, phone-first console for your tmux — agent-agnostic, no database. Spawn and watch coding agents in parallel worktrees, or anything else you run *(★ 60, MIT)*
- [cowork-to-code-bridge](https://github.com/abhinaykrupa/cowork-to-code-bridge) — Let Claude run code on your real machine — safely — from any Claude chat. Bridges Claude Cowork to Claude Code on your Mac/Linux box. One command,… *(★ 14, MIT, drives Claude Code)*
- [cliclaw](https://github.com/choiyounggi/cliclaw) — Control coding agents on your Mac — Claude Code, Codex, Pi, Gemini — from your phone via Telegram. Kick off tasks, stream progress, and approve dangerous… *(★ 8, MIT, drives Claude Code, Codex, Gemini CLI, Pi)*
- [Claudette](https://github.com/Olorin-ai-git/claudette) — Claudette — mobile control plane for your AI coding agent (iOS, Android, Apple TV). Real shell + session UI. Public front door: install links + setup CLI *(★ 3, MIT)*
- [AgentsRoom](https://agentsroom.dev/) — Desktop app (with iOS/Android companions) orchestrating CLI agents across projects as native local processes
- [Duet](https://duet.so) — Runs Claude Code on a persistent, always-on cloud server (sessions survive for days), controllable from your phone, with scheduling and a team channel interface *(drives Claude Code)*

## IDE & Editor Integrations

*Editor plugins and IDE surfaces embedding agents into VS Code, JetBrains, Neovim, Emacs, and friends.*

- [CodeCompanion.nvim](https://codecompanion.olimorris.dev/) — ✨ AI Coding, Vim Style *(★ 6.9k, Apache-2.0)*
- [CC GUI (Claude or Codex)](https://plugins.jetbrains.com/plugin/29342-cc-gui-claude-or-codex-) — Jetbrains Claude Code and Codex GUI Plugin *(★ 6.6k, MIT, drives Claude Code, Codex)*
- [claudecode.nvim](https://github.com/coder/claudecode.nvim) — 🧩 Claude Code Neovim IDE Extension *(★ 3.1k, MIT, drives Claude Code)*
- [Obsidian Agent Client](https://rait-09.github.io/obsidian-agent-client/) — Bring AI agents into Obsidian via Agent Client Protocol (ACP), such as Claude Code, Codex and Gemini CLI *(★ 2.4k, Apache-2.0, drives Claude Code, Codex, Gemini CLI)*
- [claude-code.nvim](https://github.com/greggh/claude-code.nvim) — Seamless integration between Claude Code AI assistant and Neovim *(★ 2.1k, MIT, drives Claude Code, Continue)* 💤 dormant
- [Ante](https://github.com/AntigmaLabs/ante) — Ghost in your shell. Ante is a self-contained agent harness with a highly optimized core. It works like Claude Code or Codex, with none of their… *(★ 2k, Apache-2.0, drives Claude Code, Codex)*
- [agent-shell](https://github.com/xenodium/agent-shell) — A native Emacs buffer to interact with LLM agents powered by ACP *(★ 1.9k, GPL-3.0, drives Auggie, Gemini CLI, Mistral Vibe)*
- [claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) — Claude Code IDE integration for Emacs *(★ 1.7k, GPL-3.0, drives Claude Code)*
- [agent-flow](https://github.com/patoles/agent-flow) — Real-time visualization of Claude Code agent orchestration — see your agents think, branch, and coordinate as they work *(★ 1.7k, Apache-2.0, drives Claude Code)*
- [Maki](https://github.com/tontinton/maki) — An efficient AI coding agent extendable by neovim-like Lua plugins *(★ 1.1k, MIT)*
- [atlassian-mcp-server](https://github.com/atlassian/atlassian-mcp-server) — Official remote MCP server for Atlassian. Securely connect Jira, Confluence, Jira Service Management, Bitbucket, and Compass to Claude, ChatGPT, Cursor, VS… *(★ 1.1k, Apache-2.0, drives Cursor)*
- [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) — Open-source AI research assistant for biomedicine — chat to run RNA-seq, drug discovery, clinical analysis, and more. Built on Claude Code with 140 K-Dense… *(★ 641, drives Claude Code)* 💤 dormant
- [home-assistant-vibecode-agent](https://github.com/Coolver/home-assistant-vibecode-agent) — Home Assistant MCP server agent. Enable Claude Code, Cursor, VS Code or any MCP-enabled IDE to help you vibe-code and manage Home Assistant: create and… *(★ 633, MIT, drives Claude Code, Cursor, Vibe)*
- [Agentic.nvim](https://github.com/carlos-algms/agentic.nvim) — Agentic Chat Interface directly in Neovim with ACP providers from Claude-Code, Gemini, Codex, OpenCode, and Cursor-agent *(★ 629, MIT, drives Codex, Cursor, Gemini CLI, OpenCode)*
- [agentlytics](https://github.com/f/agentlytics) — Comprehensive analytics dashboard for AI coding agents — Cursor, Windsurf, Claude Code, VS Code Copilot, Zed, Antigravity, OpenCode, Command Code *(★ 580, drives Antigravity, Claude Code, Copilot, Cursor, OpenCode, Windsurf)*
- [agentic-qe](https://github.com/proffesor-for-testing/agentic-qe) — Agentic QE Fleet is an open-source AI-powered QA/QE platform designed for use with Coding Agents (works best with Claude Code) featuring specialized agents… *(★ 485, MIT, drives Claude Code)*
- [marm-memory](https://github.com/Lyellr88/marm-memory) — Local-first 3-in-1 AI memory layer & MCP server for Claude Code, Codex, Grok, Gemini, VS Code and Cursor. Fuses session history, codebase indexing & concept… *(★ 405, Apache-2.0, drives Claude Code, Codex, Cursor, Gemini CLI, Grok)*
- [ClaudeR](https://github.com/IMNMV/ClaudeR) — Connect RStudio to Claude Code, Codex, Gemini, and other LLM agents via MCP. Multi-agent orchestration, automated manuscript   auditing, and zero-config… *(★ 344, drives Claude Code, Codex, Gemini CLI)*
- [grok-build-vscode](https://github.com/phuryn/grok-build-vscode) — Grok Build Desktop (Windows, macOS) + GUI for Grok Build CLI (Grok 4.7; extensions for VS Code, Cursor, and more). New: Talks to Codex and Claude Code, too *(★ 210, drives Claude Code, Codex, Cursor, Grok, Grok Build)*
- [swttch](https://github.com/Swttch/swttch) — Claude Code GUI plugin for JetBrains IDEs. (ex - Claude Code with GUI) *(★ 161, AGPL-3.0, drives Claude Code)*
- [ccswarm](https://github.com/nwiizo/ccswarm) — Multi-agent orchestration system using Claude Code with Git worktree isolation and specialized AI agents for collaborative development *(★ 153, MIT, drives Claude Code)*
- [Claude Code Plus](https://plugins.jetbrains.com/plugin/28343-claude-code-plus) — 🖥️ GUI Plugin for Claude Code / Codex CLI / Gemini CLI in JetBrains IDEs - Run AI coding assistants with a beautiful visual interface *(★ 143, MIT, drives Claude Code, Codex, Gemini CLI)* 💤 dormant
- [nyx-local-ai](https://github.com/sthamann/nyx-local-ai) — Local-first AI coding agent for VS Code & Cursor. Ollama, LM Studio & your inference fleet. Cursor-grade agent UX — offline, private, zero token cost *(★ 133, MIT, drives Cursor)*
- [Waveloom](https://github.com/Menfre01/waveloom) — 为 DeepSeek 前缀缓存定制的终端 Code Agent(纯 Go),缓存命中率 95-99%,命中输入定价为未命中的 1/30。A terminal coding agent optimized for DeepSeek prefix caching — 95-99% cache hit,… *(★ 133, Apache-2.0, drives DeepSeek)*
- [argus](https://github.com/yessGlory17/argus) — Claude Code Agent Monitoring & Observability on VSCode *(★ 114, MIT, drives Claude Code)*
- [AssemblyZero](https://github.com/martymcenroe/AssemblyZero) — Parameterized multi-agent orchestration framework for Claude Code and Gemini *(★ 112, drives Claude Code, Gemini CLI)*
- [multi-agent-squad](https://github.com/bijutharakan/multi-agent-squad) — Production-ready multi-agent orchestration framework for Claude Code. Features specialized AI agents, automated Git workflows, and comprehensive development… *(★ 86, MIT, drives Claude Code)* 💤 dormant
- [claude-config](https://github.com/Aurealibe/claude-config) — Comprehensive Claude Code framework: 6 specialized agents, 7 workflow commands, audio notifications - stack agnostic *(★ 67, MIT, drives Claude Code)*
- [Pi Agent IDE](https://github.com/alexshpunt/pi-agent-ide) — Agent-native IDE extension for the Pi coding agent — guarded editing, search, LSP, terminals, debugging and observability *(★ 8, MIT, drives Pi)*
- [Terminai](https://github.com/emosenkis/terminai) — Make your coding AI available in your shell *(★ 6, MIT)*

## Multi-Agent Swarms & Orchestrators

*Tools that coordinate several agents on shared tasks, roles, or plans.*

- [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) — Teams-first Multi-agent orchestration for Claude Code *(★ 39.4k, MIT, drives Claude Code)*
- [buzz](https://github.com/block/buzz) — A hive mind communication platform *(★ 34.8k, Apache-2.0, drives Claude Code, Codex, Goose)*
- [Gas Town](https://github.com/gastownhall/gastown) — Gas Town - multi-agent workspace manager *(★ 18.2k, MIT)*
- [ClawTeam](https://github.com/HKUDS/ClawTeam) — "ClawTeam: Agent Swarm Intelligence" (One Command → Full Automation) *(★ 5.5k, MIT)* 💤 dormant
- [Every Code](https://github.com/just-every/code) — Every Code - push frontier AI to it limits. A fork of the Codex CLI with validation, automation, browser integration, multi-agents, theming, and much more.… *(★ 4k, Apache-2.0, drives Codex, Gemini CLI)*
- [golutra](https://github.com/golutra/golutra) — Multi-agent AI orchestration platform for automation, workflows, and developer tools. Golutra transforms Codex, Claude Code, and OpenClaw into a unified… *(★ 3.8k, drives Claude Code, Codex, OpenClaw)*
- [squad](https://github.com/bradygaster/squad) — Squad: AI agent teams for any project *(★ 3.2k, MIT, drives Copilot)*
- [OpenSwarm](https://github.com/VRSEN/OpenSwarm) — Claude code for everything except coding *(★ 2.9k, MIT, drives Claude Code)*
- [Agent Teams AI](https://agentteams.live/) — You're the boss, agents are your team. They handle tasks on their own, message each other, and review each other's work. You just watch the kanban board and… *(★ 2.2k, AGPL-3.0, drives Codex, Copilot, Cursor, Grok, Kimi, OpenCode)*
- [TAKT](https://github.com/nrslib/takt) — TAKT Agent Koordination Topology - Define how AI agents coordinate, where humans intervene, and what gets recorded — in YAML *(★ 1.4k, MIT)*
- [overstory](https://github.com/jayminwest/overstory) — Multi-agent orchestration for AI coding agents — pluggable runtime adapters for Claude Code, Pi, and more *(★ 1.3k, MIT, drives Claude Code, Pi)* 📦 archived
- [Fusion](https://github.com/Runfusion/Fusion) — Your Software Factory - build faster and better with multi node agents that work 24/7 *(★ 1.2k, MIT, drives Factory Droid)*
- [room](https://github.com/quoroom-ai/room) — Open-source earning-focused swarm intelligence engine. Self-governing AI collectives (queen, workers, quorum voting) running locally via MCP. Works with… *(★ 839, MIT, drives Claude Code, Codex)* 💤 dormant
- [openswarm](https://github.com/openswarm-ai/openswarm) — Your mission control center for a swarm of Ai agents *(★ 821, AGPL-3.0)*
- [claude-code-cli](https://github.com/huangserva/claude-code-cli) — 这是 Claude Code 的 CLI 客户端主体（src/ 目录），即整个终端交互层的源码。具体包含： 1. CLI 入口与命令解析 — main.tsx（4684行）、entrypoints/（CLI 模式、SDK 模式、MCP 模式） 2. 终端 UI 渲染 — components/（144… *(★ 631, drives Claude Code)* 💤 dormant
- [claw-orchestrator](https://github.com/Enderfga/claw-orchestrator) — Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime — persistent sessions, multi-agent councils, an OpenAI-compatible endpoint, an… *(★ 582, MIT, drives Antigravity, Claude Code, Codex, Cursor, OpenCode)*
- [maestro-flow](https://github.com/catlog22/maestro-flow) — Intent-driven workflow orchestration for multi-agent AI development — adaptive lifecycle engine, self-reinforcing knowledge graph, and visual dashboard for… *(★ 558, drives Claude Code, Codex, Gemini CLI)*
- [openrig](https://github.com/mvschwarz/openrig) — Multi-agent harness that runs Claude Code and Codex together as one system *(★ 533, Apache-2.0, drives Claude Code, Codex)*
- [mco](https://github.com/mco-org/mco) — CLI-first orchestration for AI coding agents: run selected agents and models in parallel, compare raw answers, and coordinate review or implementation workflows *(★ 526, MIT)*
- [hcom](https://github.com/aannoo/hcom) — Let AI agents message, watch, and spawn each other across terminals. Claude Code, Codex, Antigravity CLI, Cursor CLI, OpenCode, Kilo, Pi, Kimi *(★ 520, MIT, drives Antigravity, Claude Code, Codex, Cursor, Kilo Code, Kimi…)*
- [Agent Kanban](https://agent-kanban.dev/) — An agent-first task board, Take human out of the loop *(★ 480)*
- [ai-employees](https://github.com/markfulton/ai-employees) — Open source AI Employees. 8 scheduled business roles, 60 routines, on Claude Code and 10 other harnesses. They drive your browser the way you do and improve… *(★ 435, MIT, drives Claude Code)*
- [OpenGoat](https://github.com/marian2js/opengoat) — Build organizations of OpenClaw agents that coordinate work across Codex, Claude Code, Cursor, OpenCode, and more 🐐 🐐 🐐 *(★ 428, MIT, drives Claude Code, Codex, Cursor, OpenClaw, OpenCode)* 💤 dormant
- [metaswarm](https://github.com/dsifry/metaswarm) — A self-improving multi-agent orchestration framework for Claude Code, Gemini CLI, and Codex CLI — 18 agents, 13 skills, 15 commands, TDD enforcement,… *(★ 420, MIT, drives Claude Code, Codex, Gemini CLI)*
- [orchestrator-supaconductor](https://github.com/Ibrahim-3d/orchestrator-supaconductor) — Multi-agent orchestration system for Claude Code with parallel execution, automated quality gates, Board of Directors, and bundled Superpowers skills *(★ 377, AGPL-3.0, drives Claude Code)* 💤 dormant
- [claude-swarm](https://github.com/affaan-m/claude-swarm) — Multi-agent orchestration for Claude Code — decompose tasks, coordinate agents, visualize everything in a rich terminal UI *(★ 375, MIT, drives Claude Code)* 💤 dormant
- [AgentBridge](https://github.com/raysonmeng/agent-bridge) — A local bridge for bidirectional collaboration between Claude Code and Codex. 连接 Claude Code 与 Codex 的本地实时协作桥接工具。 *(★ 361, MIT, drives Claude Code, Codex)*
- [subtask](https://github.com/zippoxer/subtask) — Claude Skill to do your tasks with subagents in Git worktrees *(★ 340, MIT)* 💤 dormant
- [zenith](https://github.com/Intelligent-Internet/zenith) — Zenith: a continuous-improvement harness for long-running agent tasks. Turns Claude Code, Codex, or Hermes into a multi-agent mission orchestrator via MCP/ACP *(★ 313, Apache-2.0, drives Claude Code, Codex, Hermes)*
- [CCteam-creator](https://github.com/jessepwj/CCteam-creator) — Multi-agent team orchestration skill for Claude Code. Set up parallel AI agent teams with file-based planning and role-based collaboration *(★ 307, MIT, drives Claude Code)* 💤 dormant
- [ringer](https://github.com/NateBJones-Projects/ringer) — Ringer — parallel AI-agent swarm orchestrator. Ringside — its native mission-control HUD. Fable-quality output without Fable-level burn *(★ 291)*
- [roach-pi](https://github.com/tmdgusya/roach-pi) — Strict engineering discipline and multi-agent orchestration for the pi coding agent *(★ 276, drives Pi)*
- [devteam](https://github.com/agent-era/devteam) — Run a team of local coding agents in your terminal. Launch multiple Claude Code, Codex or Gemini agents, switch between them, review their changes and add… *(★ 265, MIT, drives Claude Code, Codex, Gemini CLI, Vibe)* 💤 dormant
- [AgentBase](https://github.com/AgentOrchestrator/AgentBase) — Multi-agent orchestrator for tracking and analyzing AI coding assistant conversations (Claude Code, Cursor, Windsurf) *(★ 247, drives Claude Code, Cursor, Windsurf)* 💤 dormant
- [opencode-ensemble](https://github.com/hueyexe/opencode-ensemble) — Agent teams for OpenCode. Run multiple agents in parallel with messaging, shared tasks, and coordinated execution *(★ 226, MIT, drives OpenCode)*
- [claude-orchestration](https://github.com/mbruhler/claude-orchestration) — Multi-agent workflow orchestration plugin for Claude Code *(★ 220, MIT, drives Claude Code)*
- [academic-writing-agents](https://github.com/andrehuang/academic-writing-agents) — Claude Code plugin: multi-agent orchestrator with 10 specialist agents for academic writing review, research, drafting, and polishing *(★ 205, MIT, drives Claude Code)* 💤 dormant
- [claudectl](https://github.com/mercurialsolo/claudectl) — Swarm orchestration for claude code agents with a local brain that steers based on your preferences *(★ 201, MIT, drives Claude Code)*
- [OtoDock](https://github.com/OtoDock/oto-dock) — Your personal AI agent platform — self-hosted, BYO Claude/Codex subscription *(★ 187, drives Codex)*
- [claude-vibe-squad](https://github.com/mtarcure/claude-vibe-squad) — Multi-model AI orchestration where behaviour is Markdown, not code. One coordinator routes scoped task packets to 71 role-based specialists across 5 model… *(★ 162, MIT, drives Codex, Gemini CLI, Grok, Kimi)*
- [NXTG-Forge Orchestrator](https://github.com/nxtg-ai/forge-orchestrator) — Forge Orchestrator: Multi-AI task orchestration. File locking, knowledge capture, drift detection. Rust *(★ 161, drives Claude Code, Codex, Forge, Gemini CLI)*
- [outsourcerer](https://github.com/alexgreensh/outsourcerer) — Make your AI coding tools work as one team. Orchestrate jobs across Claude, Codex, Cursor, Devin, local models, and more. Carry your setup + context, track… *(★ 159, drives Codex, Cursor)*
- [agent-council](https://github.com/team-attention/agent-council) — Multi-agent collaboration plugin for Claude Code - orchestrate multiple AI agents (Codex CLI, Gemini CLI, etc.) for diverse perspectives *(★ 140, MIT, drives Claude Code, Codex, Gemini CLI)* 💤 dormant
- [claude-code-analysis](https://github.com/thtskaran/claude-code-analysis) — We read all 512K lines of Claude Code's accidentally exposed source. 82 docs, 15 diagrams, every subsystem mapped — from the hidden YOLO safety classifier… *(★ 127, drives Claude Code)* 💤 dormant
- [tutti](https://github.com/nutthouse/tutti) — Multi-agent orchestration CLI — your agents, all together *(★ 127, MIT)*
- [Claudecode-Codex-Gemini](https://github.com/KimYx0207/Claudecode-Codex-Gemini) — 智能多CLI编排系统：Claude Code自动协调Codex和Gemini · Multi-CLI orchestration: auto-coordinate Claude Code + Codex + Gemini *(★ 120, MIT, drives Claude Code, Codex, Gemini CLI)*
- [claude-lane-stack](https://github.com/VKirill/claude-lane-stack) — Multi-agent AI coding factory for one person — Claude Code PM + Codex/Qwen/Grok/Kimi/AGY writers, durable conveyor, auto-merge to main *(★ 119, MIT, drives Claude Code, Codex, Factory Droid, Grok, Kimi, Qwen)*
- [frankenterm](https://github.com/Dicklesworthstone/frankenterm) — Terminal hypervisor for AI agent swarms: real-time pane capture, state-machine pattern detection, and a JSON API for coordinating fleets of coding agents… *(★ 118)*
- [claude-swarm](https://github.com/cj-vana/claude-swarm) — MCP server for orchestrating parallel Claude Code worker swarms with protocol-based behavioral governance, persistent state, and real-time monitoring dashboard *(★ 117, MIT, drives Claude Code)* 💤 dormant
- [Agentic Orchestrator (DoorDash)](https://github.com/doordash-oss/agentic-orchestrator) — Turn a goal into a supervised run *(★ 108, Apache-2.0, drives Claude Code, Codex, OpenCode)*
- [ai-orchestrator](https://github.com/Mybono/ai-orchestrator) — Portable multi-agent AI developer setup for Claude Code + Ollama. Role-based local LLM orchestration via Bash — plan, code, review, commit. Zero Dependency.… *(★ 100, drives Claude Code)*
- [100x-orchestrator](https://github.com/aj47/100x-orchestrator) — An orchestration system for managing AI coding agents. The system uses Aider (an AI coding assistant) to handle coding tasks and provides real-time… *(★ 97, drives Aider)* 💤 dormant
- [handoff](https://github.com/dazuiba/handoff) — Delegate tasks to DeepSeek right inside your Claude Code / Codex sessions *(★ 91, drives Claude Code, Codex, DeepSeek)*
- [sub-agents-skills](https://github.com/shinpr/sub-agents-skills) — Cross-LLM sub-agent orchestration as an Agent Skills. Route tasks to Codex, Claude Code, Grok, GLM, Kimi, Cursor, Gemini, OpenCode, or Command Code from any… *(★ 91, MIT, drives Claude Code, Codex, Cursor, Gemini CLI, Grok, Kimi…)*
- [codex-orchestrator](https://github.com/alexzh3/codex-orchestrator) — Claude Code plugin that orchestrates GPT Codex agents for implementation, monitoring, and independent reviews *(★ 88, MIT, drives Claude Code, Codex)*
- [AI-Agents-Orchestrator](https://github.com/hoangsonww/AI-Agents-Orchestrator) — 🪈 Intelligent orchestration system that coordinates multiple AI coding assistants (Claude, Codex, Gemini CLI, Copilot CLI) to collaborate on complex… *(★ 86, MIT, drives Codex, Copilot, Gemini CLI)*
- [swarms](https://github.com/DheerG/swarms) — Achieve extraordinary results with claude code across a variety of tasks *(★ 85, MIT, drives Claude Code)*
- [ultraswarm](https://github.com/fubak/ultraswarm) — Multi-CLI agent swarm orchestrated by Claude Code: external AI CLIs code in isolated worktrees, Claude verifies and merges *(★ 83, MIT, drives Claude Code)*
- [OmoiOS](https://github.com/kivo360/OmoiOS) — Turn feature specs into merged PRs with a self-supervising swarm of coding agents — parallel execution, isolated sandboxes, DAG dependencies. Open-source,… *(★ 78, Apache-2.0, drives Codex, Gemini CLI)*
- [claude-code-heavy](https://github.com/gtrusler/claude-code-heavy) — Multi-agent research orchestration using Claude Code. Inspired by make-it-heavy *(★ 77, drives Claude Code)* 💤 dormant
- [CompanyHelm](https://github.com/CompanyHelm/companyhelm) — Distributed orchestrator with task management and direct agent-to-agent conversations *(★ 76, MIT)*
- [Claw-Kanban](https://github.com/GreenSheep01201/Claw-Kanban) — AI Agent Orchestration Kanban Board — Route tasks to Claude Code, Codex CLI, and Gemini CLI with role-based auto-assignment and real-time monitoring *(★ 73, Apache-2.0, drives Claude Code, Codex, Gemini CLI)* 💤 dormant
- [agency](https://github.com/christag/agency) — One dashboard for all your AI agents — manage teams across Claude Code, Codex, Gemini, Aider, and more. No database required *(★ 70, AGPL-3.0, drives Aider, Claude Code, Codex, Gemini CLI)* 💤 dormant
- [FleetQ](https://github.com/escapeboy/agent-fleet-o) — Open-source AI agent orchestration platform — self-hosted mission control for autonomous multi-agent systems. Visual DAG workflows, 670+ MCP tools,… *(★ 70, AGPL-3.0, drives Codex, Gemini CLI)*
- [claude-workflow-studio](https://github.com/FocuZHe/claude-workflow-studio) — Web-based visual platform to orchestrate multi-agent Claude Code workflows. Create agents, chain them into pipelines, watch them collaborate in real time *(★ 69, MIT, drives Claude Code)*
- [CrewCtl](https://github.com/omergocmen/CrewCtl) — Claude Code, Codex CLI, Gemini CLI ve diğer yapay zekâ destekli coding agent’larını tek merkezden yöneten açık kaynaklı bir multi-agent orchestration… *(★ 69, drives Claude Code, Codex, Gemini CLI)*
- [swcc](https://github.com/ylxmf2005/swcc) — 🇨🇳 SWCC — Democratic Centralism Multi-Agent Orchestration for Claude Code (民主集中制多智能体编排) *(★ 65, MIT, drives Claude Code)* 💤 dormant
- [HolyCode](https://github.com/CoderLuii/HolyCode) — AI coding workstation: OpenCode + Claude subscription support + 30+ tools + headless browser + multi-agent orchestration *(★ 63, MIT, drives OpenCode)*
- [cleancode](https://github.com/chen-985211/cleancode) — Bring Claude Code, Codex, and your favorite CLI agents into one visual workspace. Run agents in parallel and build executable workflows in isolated Git… *(★ 62, MIT, drives Claude Code, Codex)*
- [5dive](https://github.com/5dive-ai/5dive) — Run a company of AI agents on a server you own. Spin up named agents (claude, codex, pi…), put them on an org chart with a shared backlog, let them hand off… *(★ 61, MIT, drives Antigravity, Claude Code, Codex, Grok, OpenCode, Pi)*
- [Agon](https://github.com/AutoResearch-Factory/Agon) — Claude Code plugin for autonomous AI research — multi-agent loops take a bare topic all the way to running experiments, with no human-written experimental code *(★ 50, MIT, drives Claude Code)*
- [shire](https://github.com/victor36max/shire) — Where agents live, and flourish. 🌿 *(★ 40, MIT, drives Claude Code, OpenCode, Pi)* 💤 dormant
- [corellis](https://github.com/CorellisOrg/Corellis) — Scale OpenClaw from one AI assistant to a coordinated fleet — shared knowledge, collective memory, distributed goals *(★ 30, MIT, drives OpenClaw)* 💤 dormant
- [Kolega Code](https://github.com/kolega-ai/kolega-code) — Agentic coding in the terminal: the model writes its own multi-agent workflows (Gigacode). Provider-agnostic, local-first, 15+ model providers, MCP support *(★ 21)*
- [CLAII](https://github.com/agencyswarm/CLAII) — CLAII = CLI AI Agent for coding. CLAII is a terminal-native AI pair-programmer with multi-agent orchestration, MCP toolchains, and context-aware,… *(★ 6)* 💤 dormant

## Agent Loops & Autonomous Runs

*Ralph-style loops, harnesses, and runners that keep agents iterating autonomously.*

- [DeerFlow](https://github.com/bytedance/deer-flow) — An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and… *(★ 83k, MIT)*
- [Prime Agent](https://github.com/PrimeIntellect-ai/prime-agent) — A self-improving RLM agent for coding workflows and long-running autonomous tasks *(★ 21.3k, MIT)*
- [Loop Engineering](https://github.com/cobusgreyling/loop-engineering) — Practical patterns, starters & CLI tools for loop engineering with AI coding agents. Design systems that prompt and orchestrate agents (inspired by Addy… *(★ 11.3k, MIT)*
- [ralph-claude-code](https://github.com/frankbria/ralph-claude-code) — Autonomous AI development loop for Claude Code with intelligent exit detection *(★ 9.6k, MIT, drives Claude Code)*
- [gptme](https://github.com/gptme/gptme) — Your agent in your terminal, equipped with local tools: writes code, uses the terminal, browses the web. Make your own persistent autonomous agent on top! *(★ 4.4k, MIT)*
- [Kiro Crew](https://github.com/kirodotdev/KiroCrew) — A persistent workspace for development work that self-improves and continues beyond one session *(★ 4.2k, Apache-2.0, drives Continue)*
- [cc-sdd](https://github.com/gotalab/cc-sdd) — Turn approved specs into long-running autonomous implementation. A minimal, adaptable SDD harness with Agent Skills for Claude Code, Codex, Cursor, Copilot,… *(★ 3.7k, MIT, drives Antigravity, Claude Code, Codex, Copilot, Cursor, Gemini CLI…)*
- [ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) — An improved implementation of the Ralph Wiggum technique for autonomous AI agent orchestration *(★ 3.2k, MIT)*
- [ralphy](https://github.com/michaelshimeles/ralphy) — My Ralph Wiggum setup, an autonomous bash script that runs Claude Code, Codex, OpenCode, Cursor agent, Qwen & Droid in a loop until your PRD is complete *(★ 3k, drives Claude Code, Codex, Cursor, Droid, OpenCode, Qwen)* 💤 dormant
- [myclaude](https://github.com/stellarlinkco/myclaude) — Multi-agent orchestration workflow (Claude Code  Codex Gemini OpenCode) *(★ 2.8k, AGPL-3.0, drives Claude Code, Codex, Gemini CLI, OpenCode)* 💤 dormant
- [CodeMachine-CLI](https://github.com/moazbuilds/CodeMachine-CLI) — CodeMachine is an open-source tool that orchestrates AI coding agents into repeatable, long-running workflows. ⚡️ *(★ 2.5k, Apache-2.0)* 💤 dormant
- [Codel](https://github.com/semanser/codel) — ✨ Fully autonomous AI Agent that can perform complicated tasks and projects using terminal, browser, and editor *(★ 2.5k, AGPL-3.0)* 💤 dormant
- [ralph-tui](https://github.com/subsy/ralph-tui) — Drives an agent through a task list autonomously, with a TUI for watching the loop *(★ 2.4k, MIT)*
- [RA.Aid](https://github.com/ai-christianson/RA.Aid) — Develop software autonomously *(★ 2.2k, Apache-2.0)* 💤 dormant
- [Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow) — JSON-driven multi-agent  cadence-team development framework with   intelligent CLI orchestration (Gemini/Qwen/Codex),   context-first architecture, and… *(★ 2.1k, MIT, drives Codex, Gemini CLI, Qwen)* 📦 archived
- [babysitter](https://github.com/a5c-ai/babysitter) — Babysitter enforces obedience on agentic workforces and enables them to manage extremely complex tasks and workflows through deterministic,… *(★ 1.8k, MIT, drives Claude Code, Codex, Copilot, Cursor, Gemini CLI, Hermes…)*
- [LongHorizon-Harness](https://github.com/AMAP-ML/LongHorizon-Harness) — The long-horizon computer-use harness. Run AI agents across desktop apps and the CLI for extended periods while preserving task state and making reliable… *(★ 1.6k, MIT, drives Claude Code, Codex, OpenClaw)*
- [loushang](https://github.com/zhnt/loushang) — AI-native agent harness for coding workflows by python: multi-model LLM orchestration, stateful sessions, tool governance,   traceable delivery, and… *(★ 1.6k, Apache-2.0, drives DeepSeek, Kimi, Qwen)*
- [ralphex](https://github.com/umputun/ralphex) — Extended Ralph loop for autonomous AI-driven plan execution *(★ 1.5k, MIT, drives Claude Code, Codex)*
- [continuous-claude](https://github.com/AnandChowdhary/continuous-claude) — 🔂 Ralph loop with PRs: Run Claude Code in a continuous loop, autonomously creating PRs, waiting for checks, and merging *(★ 1.4k, MIT, drives Claude Code)*
- [loom](https://github.com/ghuntley/loom) — if your name is not Geoffrey Huntley then do not use loom *(★ 1.4k)* 💤 dormant
- [oh-my-agent](https://github.com/first-fluke/oh-my-agent) — Mechanical verification for AI coding agents — skills pack or full harness (stop-hook gates, artifact checks, independent judges) *(★ 1.3k, MIT)*
- [Bernstein](https://bernstein.run/) — The open‑source AI Agents Governance & Orchestration framework: write the rules declaratively, Bernstein enforces them and produces the verifiable,… *(★ 1.3k, Apache-2.0)*
- [moai-adk](https://github.com/modu-ai/moai-adk) — Agentic development harness for Claude Code — SPEC-driven plan/run/sync, TRUST 5 quality gates, model+effort routing, and Claude×GLM multi-LLM cost control.… *(★ 1.2k, Apache-2.0, drives Claude Code)*
- [loki-mode](https://github.com/asklokesh/loki-mode) — Multi-agent autonomous SDLC framework. Spec to deployed app. PRD, GitHub issue, OpenAPI/JSON/YAML, or one-line brief. 5 AI providers, 8 quality gates *(★ 1.1k)*
- [fractal](https://github.com/plasma-ai/fractal) — Hierarchical agent loops with recursive self-organization *(★ 777, Apache-2.0)*
- [looper](https://github.com/ksimback/looper) — Design visual, review-gated agent loops for Claude Code before you run them *(★ 710, MIT, drives Claude Code)*
- [metaharness](https://github.com/ruvnet/metaharness) — 🛠️ The meta-harness for AI agents — scaffold your own focused, branded agent harness with its own npx CLI, MCP server, memory, learning loop, and… *(★ 675, MIT, drives Claude Code, Codex, Hermes, OpenClaw, Pi)*
- [h5i](https://github.com/h5i-dev/h5i) — An agent-native red-teaming workspace with a fast browser, direct HTTP traffic control, sandboxed execution, and auditable sessions. Pure Rust *(★ 658, Apache-2.0, drives Claude Code, Codex)*
- [vibe-check](https://github.com/TexasBedouin/vibe-check) — By a 12-year product manager who builds 0-to-1: takes a beginner from a vague idea to a buildable plan, then guides the build (GitHub basics, clean-code… *(★ 607, MIT, drives Antigravity, Claude Code, Codex, Vibe)*
- [pi-hermes-memory](https://github.com/chandra447/pi-hermes-memory) — Hermes-style persistent memory and learning loop for Pi coding agent *(★ 462, MIT, drives Hermes, Pi)*
- [MartinLoop](https://github.com/Keesan12/martin-loop) — Run coding agents without babysitting them. Keep jobs focused, bounded, checked and accountable from start to finish. Finally run your agents swarms… *(★ 355, Apache-2.0)*
- [interactive-mcp](https://github.com/ttommyth/interactive-mcp) — Vibe coding should have human in the loop! interactive-mcp: Local, cross-platform MCP server for interact with your AI Agent *(★ 352, MIT, drives Vibe)* 💤 dormant
- [pi-cursor-sdk](https://github.com/fitchmultz/pi-cursor-sdk) — Run Cursor's agent loop inside the pi coding agent via local Cursor SDK agents, with native model selection, thinking controls, fast/plan modes, image… *(★ 334, MIT, drives Cursor, Pi)*
- [pi-boomerang](https://github.com/nicobailon/pi-boomerang) — Token-efficient autonomous task execution with context collapse for pi coding agent *(★ 306, drives Pi)*
- [claude-code-orchestrator-kit](https://github.com/maslennikov-ig/claude-code-orchestrator-kit) — 🎼 Turn Claude Code into a production powerhouse. 33+ AI agents automate bug fixing, security scanning,   and dependency management. 19 slash commands, 6 MCP… *(★ 253, drives Claude Code)* 💤 dormant
- [Orbi](https://github.com/orbi-build/orbi) — Open-source (AGPL-3.0), self-hosted autonomous coding agent: label a GitHub Issue, get an independently reviewed, merged PR and a tagged release *(★ 194, AGPL-3.0)*
- [ORCH](https://github.com/oxgeneral/ORCH) — One CLI to orchestrate them all. Manage a team of AI agents executing tasks in parallel from your terminal using a command line interface to manage them… *(★ 166, MIT, drives Claude Code, Codex, Cursor)*
- [ordewell](https://github.com/ordewell/ordewell) — Multi-agent task orchestration for coding agents. Turn one goal into an ordered plan of tasks — each with its own runner, model and mode — then execute and… *(★ 160, Apache-2.0, drives Claude Code, Codex, OpenCode)*
- [LoopTroop](https://github.com/looptroop-ai/LoopTroop) — Local AI coding orchestration for repo-scale work: LLM-council planning, Ralph-loop recovery, isolated OpenCode worktrees, and human-gated PR delivery *(★ 154, MIT, drives OpenCode)*
- [OMK](https://github.com/dmae97/omk) — Evidence-gated runner for Codex, Claude Code, OpenCode, and local coding agents. Routes tasks into scoped DAG lanes with replayable artifacts *(★ 144, drives Claude Code, Codex, OpenCode)*
- [babyagi3](https://github.com/yoheinakajima/babyagi3) — A minimal AI agent you configure once, then run through natural language. _(last commit 2026-03)_ *(★ 130, MIT)* 💤 dormant
- [wreckit](https://github.com/mikehostetler/wreckit) — Wreck it Ralph Wiggum - My code is in danger! *(★ 130, MIT)* 💤 dormant
- [albert](https://github.com/Sdraugel/albert) — Autonomous multi-agent harness for Claude Code (A.L.B.E.R.T. orchestrator) plus a zero-dependency live HUD console *(★ 106, drives Claude Code)*
- [future-os](https://github.com/futuregene/future-os) — One AI agent, everywhere you work — terminal, desktop, mobile, and your chat apps. Rust core *(★ 106, MIT)*
- [great_cto](https://github.com/avelikiy/great_cto) — You already have the agent. This is everything around it. great_cto runs Claude Code as a pipeline of 70 specialist agents — an independent model checks… *(★ 95, MIT, drives Claude Code)*
- [The Factory](https://github.com/akashgit/remote-factory) — Domain-agnostic multi-agent software design and evolution harness *(★ 71, MIT)*
- [OpenCastle](https://github.com/monkilabs/opencastle) — Multi agens orchestration setup for Github Copilot, Cursor, Claude Code, OpenCode, Windsurf, Codex and Antigravity *(★ 62, MIT, drives Antigravity, Claude Code, Codex, Copilot, Cursor, OpenCode…)*
- [gptme-agent-template](https://github.com/gptme/gptme-agent-template) — Agent workspace template for gptme. Create persistent autonomous agents that build, learn, research, socialize, and assist you with whatever you need *(★ 52)*
- [pi-reflect](https://github.com/jo-inc/pi-reflect) — Self-improving behavioral files for AI coding agents. Analyzes session transcripts for correction patterns and makes surgical edits to prevent recurrence *(★ 48, MIT)*
- [Crewplane](https://github.com/crewplaneai/crewplane) — Run reviewable, resumable coding-agent workflows across Claude Code, Codex, Gemini, GitHub Copilot CLI, or any CLI. You define the stages in Markdown;… *(★ 40, Apache-2.0, drives Claude Code, Codex, Copilot, Gemini CLI)*
- [Nausicaa](https://github.com/jackispm/nausicaa-harness) — Nausicaa treats an Agent run as a dynamic topology of Lanes rather than one fixed linear loop. The model can decide when to observe, fan out, delegate, or… *(★ 34, MIT)*
- [fab-kit](https://github.com/sahil87/fab-kit) — Structured, spec-driven development workflow for AI coding agents *(★ 33, MIT)*
- [Grinta](https://github.com/josephsenior/Grinta-Coding-Agent) — Local-first autonomous coding agent that plans, executes, validates, and finishes software tasks end-to-end *(★ 31, MIT)*
- [AGX](https://github.com/ramarlina/agx) — agx: Run AI coding agents as a persistent team with objectives, memory, and coordinated work. The same agents built this tool — 167+ merged PRs, 93% clean *(★ 29)* 💤 dormant
- [orc](https://github.com/spencermarx/orc) — A lightweight orchestration framework that piggybacks your local Agentic CLI setup. Intentionally simple. Yet powerful... like an army of Orcs 👹 *(★ 26)*
- [ralph-harness](https://github.com/rxdt/loopgate_harness) — A repo-native coding-agent loop harness for Claude, Codex, Copilot, and other CLI agents. Agents can edit. Gates decide what lands. You set the plan in… *(★ 23, MIT, drives Codex, Copilot)*
- [Galley](https://github.com/shinpr/galley) — You pick the model per task, with review, evidence, and a PR at the end *(★ 19, MIT)*
- [toryo](https://github.com/JesseRWeigel/toryo) — 棟梁 The intelligent agent orchestrator — chains AI coding agents with trust-based delegation, quality ratcheting, and self-improving loops *(★ 12, MIT, drives Aider, Claude Code, Gemini CLI)*
- [baya-cli](https://github.com/dephelion/baya-cli) — Local multi-provider CLI orchestrator: a plain-text task list to LLM-planned JSON DAG to parallel dispatch across local agent CLIs *(★ 5, MIT)*
- [Ralph Workflow](https://github.com/Ralph-Workflow/Ralph-Workflow) — Autopilot for AI Coding Agents, supports OpenCode, Claude Code, pi.dev, Cursor, and many more *(★ 5, AGPL-3.0, drives Claude Code, Cursor, OpenCode, Pi)*
- [Relay](https://github.com/jcast90/relay) — Orchestrate coding agents across repos. Local-first, self-hosted, runs inside your existing Claude / Codex CLI *(★ 5, MIT, drives Codex)*
- [sage](https://github.com/youwangd/SageCLI) — ⚡ Simple Agent Engine — Orchestrate AI coding agents from your terminal. No frameworks, just bash, jq, and tmux *(★ 5, MIT)* 💤 dormant
- [TeDDy](https://github.com/atte500/TeDDy) — xCogito on YouTube *(★ 5, AGPL-3.0)*
- [Vibestrate](https://github.com/guyshonshon/vibestrate) — Open-source supervised flow for AI coding. Run Claude Code, Codex, Gemini, Aider or local models as one crew, approve the risky steps yourself, and keep… *(★ 5, Apache-2.0, drives Aider, Claude Code, Codex, Gemini CLI)*
- [DevPilot](https://github.com/geastham/devpilot) — The cockpit for your coding agents — a parallelisation-aware wave planner, computed critical paths, and runway warnings before a session goes idle. Agents… *(★ 2, MIT)*
- [claude-northstar](https://github.com/Nisarg38/claude-northstar) — Transform CLI agents from task executors into autonomous project partners. Share your vision, not your todo list *(★ 1, MIT)* 💤 dormant
- [isitdone](https://github.com/raimondasl/isitdone) — Don't let your coding agent say "done" until the tests actually pass. Zero-LLM Stop hook, CLI, MCP server and GitHub Action for Claude Code, Codex, Cursor,… *(★ 1, MIT, drives Claude Code, Codex, Copilot, Cursor, Gemini CLI)*
- [postmortemthis](https://github.com/Softeria/postmortemthis) — Every AI coding-agent CLI (Claude Code, Codex, Gemini, Qwen, Vibe) reviews your diff in parallel, read-only, for one ship/no-ship verdict. One tiny script:… *(★ 1, MIT, drives Claude Code, Codex, Gemini CLI, Qwen, Vibe)*
- [the-perfect-orchestrator](https://github.com/daman8271/the-perfect-orchestrator) — One lead Claude Code session commanding N autonomous workers in tmux — with adversarially verified results. No daemons, no servers, just files *(★ 1, MIT, drives Claude Code)*
- [Dex](https://github.com/francescoalemanno/dex) — Human-gated planning, multi-reviewer code review, and dead-end-aware research loops, shipped as cross-platform binaries for 7 CLI backends

## Task Runners & Async Execution

*Issue-to-PR pipelines, CI actions, and dispatch systems that hand work to agents.*

- [paperclip](https://github.com/paperclipai/paperclip) — The open-source app everyone uses to manage agents at work *(★ 86.8k, MIT)*
- [Multica](https://multica.ai/) — Make humans and AI agents work as one team — open-source and self-hostable *(★ 51.4k)*
- [Symphony](https://github.com/openai/symphony) — Symphony turns project work into isolated, autonomous implementation runs, allowing teams to manage work instead of supervising coding agents *(★ 27.4k, Apache-2.0, drives Codex)*
- [open-swe](https://github.com/langchain-ai/open-swe) — An Open-Source Asynchronous Coding Agent *(★ 10.8k, MIT)*
- [claude-code-action](https://github.com/anthropics/claude-code-action) — Anthropic's official GitHub Action, detecting from context whether to answer, review, or implement. Auth via Anthropic API, Bedrock, Vertex, or Foundry *(★ 9k, MIT)*
- [gh-aw](https://github.com/github/gh-aw) — GitHub Agentic Workflows *(★ 5.2k, MIT, drives Codex, Copilot, Gemini CLI)*
- [background-agents](https://github.com/ColeMurray/background-agents) — An open-source background agents coding system *(★ 3.3k, MIT)*
- [run-gemini-cli](https://github.com/google-github-actions/run-gemini-cli) — A GitHub Action invoking the Gemini CLI *(★ 2.1k, Apache-2.0, drives Gemini CLI)*
- [codex-action](https://github.com/openai/codex-action) — OpenAI's official GitHub Action, running Codex CLI headlessly under drop-sudo, unprivileged-user, or fully read-only sandboxes *(★ 1.2k, Apache-2.0, drives Codex)*
- [optio](https://github.com/jonwiggins/optio) — Workflow orchestration for AI agent swarms *(★ 1.1k, MIT)*
- [agent-qa](https://github.com/vostride/agent-qa) — Open-source self-improving QA agent for software teams. A test harness with memory. Write tests in natural language for web and mobile. agent-qa learns from… *(★ 889)*
- [cyrus](https://github.com/cyrusagents/cyrus) — The Claude Code background agent for Linear, Slack, Github, GitLab etc. you deploy anywhere. Supports Codex, Cursor, Gemini, and Opencode harnesses too *(★ 830, Apache-2.0, drives Claude Code, Codex, Cursor, Gemini CLI, OpenCode)*
- [aeon](https://github.com/aeonfun/aeon) — Official Aeon - the open-source autonomous AI agent framework. Runs unattended on your GitHub Actions, self-healing skills, drives Claude Code, Codex, Grok… *(★ 757, MIT, drives Claude Code, Codex, Grok, Kimi, Pi, Vibe)*
- [Machinist](https://github.com/owainlewis/machinist) — Open source software factory infrastructure for advanced AI coding workflows *(★ 462, MIT, drives Codex, Factory Droid)*
- [no_human](https://github.com/no-human-ai/no_human) — From ticket to reviewed pull request. Free and open-source, on your machine *(★ 322, MIT, drives Claude Code, Codex)*
- [remote-swe-agents](https://github.com/aws-samples/remote-swe-agents) — Autonomous SWE agent working in the cloud! *(★ 243, MIT-0)*
- [Contrabass](https://github.com/junhoyeo/contrabass) — 🎸 A project-level orchestrator for AI coding agents — Go & Charm stack implementation of OpenAI's Symphony *(★ 222, Apache-2.0)*
- [sortie](https://github.com/sortie-ai/sortie) — Turn tracker tickets into autonomous agent sessions *(★ 192, Apache-2.0)*
- [pi-dispatch](https://github.com/edgehero/pi-dispatch) — Run the pi coding agent as a service — triggered on demand, on a cron schedule, or by a GitHub or GitLab issue, comment or pull/merge request — in a… *(★ 178, MIT, drives Pi)*
- [lalph](https://github.com/tim-smart/lalph) — Issue-source-driven (GitHub/Linear) orchestrator that runs CLI agents concurrently in git worktrees *(★ 131, MIT)*
- [Taskuary](https://github.com/ldbumble/taskuary) — Automate your job: local-first AI task hub. Email, Teams, Slack & reports -> one timeline -> AI triage -> your coding agents (Claude Code, Codex, Gemini) do… *(★ 124, MIT, drives Claude Code, Codex, Copilot, Cursor, Gemini CLI)*
- [groundcrew](https://github.com/ClipboardHealth/groundcrew) — Dispatch your task backlog to local, interactive AI coding agents. One git worktree per task, sandboxed by default *(★ 66, MIT)*
- [NEEDLE](https://github.com/jedarden/NEEDLE) — Headless agent orchestrator with deterministic state machine — processes a bead queue, dispatches to any LLM CLI, handles every outcome. Rust *(★ 28, MIT, drives Aider, Claude Code, Codex, OpenCode)*
- [TaskHandoff](https://github.com/edgestorage/task-handoff) — TaskHandoff is a unified control plane for running, managing, and collaborating with docker-based Codex workspaces across local and remote machines *(★ 2, Apache-2.0, drives Codex)*
- [Team1-Factory](https://github.com/Team1-dev/Team1-Factory) — Open-source AI software factory: GitHub issues in, merged PRs out *(★ 2, Apache-2.0, drives Factory Droid)*
- [Dahrk](https://github.com/dahrkai/dahrk-node)

## Session Viewers & Observability

*Transcript browsers, history explorers, replayers, and telemetry/observability for agent runs.*

- [OpenCodeReview](https://github.com/alibaba/open-code-review) — Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level… *(★ 41.6k, Apache-2.0)*
- [AgentsView](https://www.agentsview.io/) — Local-first session search, analytics, insights, and token use statistics for coding agents, supporting Claude Code, Codex, and more than 20 other agents *(★ 6k, MIT, drives Claude Code, Codex)*
- [claude-tap](https://github.com/liaohch3/claude-tap) — Intercept and inspect Coding Agent API traffic from Claude Code, Codex CLI, Gemini CLI, Cursor CLI, OpenCode, Kimi/Kimi Code, Pi, and Hermes in a local… *(★ 3.2k, MIT, drives Claude Code, Codex, Cursor, Gemini CLI, Hermes, Kimi…)*
- [openwolf](https://github.com/cytostack/openwolf) — Portable project memory across Claude Code, Codex and OpenCode, plus token accounting measured from harness transcripts. Local file I/O, no API calls, no… *(★ 2.4k, AGPL-3.0, drives Claude Code, Codex, OpenCode)*
- [claude-usage](https://github.com/phuryn/claude-usage) — A local dashboard for tracking your Claude Code token usage, costs, and session history. Pro and Max subscribers get a progress bar. This gives you the full… *(★ 2.2k, MIT, drives Claude Code)*
- [claude-code-history-viewer](https://github.com/jhlee0409/claude-code-history-viewer) — desktop app to browse and analyze your Claude Code conversation history *(★ 2.2k, MIT, drives Claude Code)*
- [superview.sh](https://github.com/Leanmcp/superview.sh) — See your claude code logs in clear details in your dashboard *(★ 2.1k, MIT, drives Claude Code)* 💤 dormant
- [zeroshot](https://github.com/the-open-engine/zeroshot) — Independent executor–verifier orchestration for software changes *(★ 1.9k, MIT, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) — Real-time monitoring for Claude Code agents through simple hook event tracking *(★ 1.5k, drives Claude Code)* 💤 dormant
- [claude-canvas](https://github.com/dvdsgl/claude-canvas) — Give Claude Code an external monitor *(★ 1.5k, MIT, drives Claude Code)* 💤 dormant
- [Agor](https://github.com/preset-io/agor) — Agor - team command center for all things agentic *(★ 1.4k, drives Claude Code, Codex, Copilot, Cursor, Gemini CLI, OpenCode)*
- [sniffly](https://github.com/chiphuyen/sniffly) — Claude Code dashboard with usage stats, error analysis, and sharable feature *(★ 1.3k, MIT, drives Claude Code)* 💤 dormant
- [coding_agent_session_search](https://github.com/Dicklesworthstone/coding_agent_session_search) — Unified TUI and CLI to index and search your local coding agent session history across 11+ providers (Codex, Claude, Gemini, Cursor, Aider, etc.) *(★ 1.1k, drives Aider, Codex, Cursor, Gemini CLI)*
- [cc-viewer](https://github.com/weiesky/cc-viewer) — A request monitoring system for Claude Code that captures and visualizes all API requests and responses in real time. Helps developers monitor their Context… *(★ 1.1k, MIT, drives Claude Code, Vibe)*
- [ccglass](https://github.com/jianshuo/ccglass) — See what your coding agent (Claude Code, Codex, Kimi) sends to the model — local proxy + web dashboard *(★ 813, MIT, drives Claude Code, Codex, Kimi)*
- [token-dashboard](https://github.com/nateherkai/token-dashboard) — See where Claude Code is burning tokens - turn raw JSONL transcripts into local cost analytics, hotspot views, and session-level usage insight *(★ 708, MIT, drives Claude Code)* 💤 dormant
- [claude-code-otel](https://github.com/ColeMurray/claude-code-otel) — A comprehensive observability solution for monitoring Claude Code usage, performance, and costs *(★ 506, MIT, drives Claude Code)* 💤 dormant
- [kibitz](https://github.com/kibitzsh/kibitz) — Real-time decoded feed of AI agent actions — monitor multiple Claude Code & Codex sessions, see exactly what each agent is doing, and coordinate swarms… *(★ 494, MIT, drives Claude Code, Codex)* 💤 dormant
- [pi-workflows](https://github.com/osolmaz/pi-workflows) — Workflow engine, JSON control-flow tool, and live terminal viewer for the pi coding agent *(★ 310, MIT, drives Pi)*
- [OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) — OrcaReplay — Time travel for AI agents. Record, replay, fork, and debug any agent run with any model. Built by the OrcaRouter.ai team *(★ 267, Apache-2.0)*
- [cc-statusline](https://github.com/NYCU-Chung/cc-statusline) — A comprehensive statusline dashboard for Claude Code — session info, quota bars, agent tracker, MCP health, message history, and more *(★ 263, MIT, drives Claude Code)* 💤 dormant
- [moor](https://github.com/varandrew/moor) — Moor is a local MCP control plane for Mac. It gives every coding agent one safe, observable, configurable gateway to your MCP servers *(★ 198, Apache-2.0)*
- [opencode-plugin-otel](https://github.com/DEVtheOPS/opencode-plugin-otel) — An opencode plugin that exports telemetry via OpenTelemetry (OTLP/gRPC), mirroring the same signals as Claude Code's monitoring *(★ 129, MPL-2.0, drives Claude Code, OpenCode)*
- [ctx](https://github.com/dchu917/ctx) — Local context manager for Claude Code and Codex with workstreams, transcript binding, and branching *(★ 128, MIT, drives Claude Code, Codex)* 💤 dormant
- [pi-harness](https://github.com/wangmiaozero/pi-harness) — The operational superset of Pi Coding Agent — everything Pi, plus observability, governance, recovery, evaluation and multi-agent orchestration *(★ 87, AGPL-3.0, drives Pi)*
- [harness](https://github.com/majiayu000/harness) — Run fleets of parallel coding agents with governance — Rust control plane for Claude Code & Codex: orchestration, policy, cross-agent review, observability *(★ 78, MIT, drives Claude Code, Codex)*
- [ClaudeCodeExtension](https://github.com/dliedke/ClaudeCodeExtension) — Visual Studio .NET extension that provides a better interface for Claude Code, Codex, Cursor Agent, Open Code, Devin, PI, Antigravity and Reasonix.… *(★ 73, MIT, drives Antigravity, Claude Code, Codex, Cursor, Pi)*
- [AgentDiff](https://github.com/codeprakhar25/agentdiff) — Git-native AI code provenance: records which AI agent wrote which line, signs each attribution with ed25519, stores it in your git history. Cross-agent… *(★ 46, Apache-2.0, drives Claude Code, Codex, Copilot, Cursor, Gemini CLI, OpenCode…)*
- [agent-trace](https://github.com/ertygiq/agent-trace) — Universal CLI for filtering and printing agent session transcripts *(★ 3, MIT)*
- [clisweave](https://github.com/uhuntu/clisweave) —  *(MIT)*

## Usage, Cost & Quota Monitors

*Token, cost, and rate-limit dashboards, menu-bar meters, and statusline trackers.*

- [CodexBar](https://github.com/steipete/CodexBar) — Show usage stats for OpenAI Codex and Claude Code, without having to login *(★ 21.9k, MIT, drives Claude Code, Codex)*
- [codeburn](https://github.com/getagentseal/codeburn) — Free, local tool to track AI coding token usage and cost across 37 tools and agents (Claude Code, Cursor, Codex, Gemini and more), by model, project, and… *(★ 11.3k, MIT, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) — Real-time Claude Code usage monitor with predictions and warnings *(★ 8.7k, MIT, drives Claude Code)*
- [abtop](https://github.com/graykode/abtop) — Like htop, but for AI coding agents. Monitor Claude    Code & Codex CLI sessions, tokens, context window,    rate limits, and ports in real-time *(★ 3.7k, MIT, drives Codex)*
- [token-monitor](https://github.com/Javis603/token-monitor) — Local-first desktop widget for tracking token usage, costs, and limits across 40+ AI coding tools—including Claude Code, Codex, Cursor, OpenCode, and… *(★ 2.4k, MIT, drives Claude Code, Codex, Cursor, OpenClaw, OpenCode)*
- [ClaudeBar](https://github.com/tddworks/ClaudeBar) — A macOS menu bar application that monitors AI coding assistant usage quotas. Keep track of your Claude, Codex, Antigravity ,and Gemini usage at a glance *(★ 1.5k, drives Antigravity, Codex, Gemini CLI)*
- [agentacct](https://github.com/mikehasa/agentacct) — See what your coding agents did and what it cost. Breaks each task down into work steps — tools used, files changed, tests run, time and tokens spent.… *(★ 755, MIT, drives Claude Code, Codex, OpenCode)*
- [onWatch](https://github.com/onllm-dev/onWatch) — Track AI API quotas across Synthetic, Z.ai, Anthropic (Claude Code), Codex, GitHub Copilot & Antigravity in real time. Lightweight background daemon (<50MB… *(★ 744, GPL-3.0, drives Antigravity, Claude Code, Codex, Copilot)*
- [cc-lens](https://github.com/Arindam200/cc-lens) — Local analytics dashboard for Claude Code. No cloud, no telemetry *(★ 601, MIT, drives Claude Code)*
- [claude-dashboard](https://github.com/uppinote20/claude-dashboard) — Comprehensive status line plugin for Claude Code with context usage, API rate limits, and cost tracking *(★ 574, MIT, drives Claude Code)*
- [Chisle](https://github.com/JayPokale/Chisle) — Cut your AI coding agent's token bill on three axes: terse prose, YAGNI-first code, and tool-output compression. Claude Code, Pi, Cursor, Codex, Gemini + 4… *(★ 563, MIT, drives Claude Code, Codex, Cursor, Gemini CLI, Pi)*
- [Pulse](https://github.com/qunqin24/Pulse) — A floating macOS monitor for how much Claude Code, Codex, Antigravity, OpenCode Go and Kimi Code you have left *(★ 479, Apache-2.0, drives Antigravity, Claude Code, Codex, Kimi, OpenCode)*
- [claude-pulse](https://github.com/NoobyGains/claude-pulse) — Real-time usage monitor for Claude Code — session limits, weekly limits, and plan tier with colour-coded progress bars *(★ 464, drives Claude Code)*
- [tokentelemetry](https://github.com/VasiHemanth/tokentelemetry) — Token telemetry dashboard for AI autonomous and coding agents — tracks tokens, sessions, tool calls & reasoning across Hermes agent, Claude Code,… *(★ 373, MIT, drives Antigravity, Claude Code, Codex, Hermes)*
- [syrtis](https://github.com/Nanako0129/syrtis) — AI token usage & quota monitor for the macOS menu bar — native Swift, Liquid Glass, 3D contribution graph. Tracks Claude Code, Codex, Cursor, OpenCode & 25+… *(★ 372, MIT, drives Claude Code, Codex, Cursor, OpenCode)*
- [claude-code-karma](https://github.com/JayantDevkar/claude-code-karma) — Dashboard for monitoring claude code sessions *(★ 328, Apache-2.0, drives Claude Code)*
- [claude-lens](https://github.com/foyzulkarim/claude-lens) — A local dashboard for visualizing your Claude Code usage — sessions, token costs, cache performance, tool calls, and daily breakdowns *(★ 249, MIT, drives Claude Code)*
- [claude-pulse](https://github.com/nikitadoudikov/claude-pulse) — Local, zero-dependency dashboard for Claude Code: live token usage and context, lost-session recovery, full-text search, and approve tool calls from your phone *(★ 247, MIT, drives Claude Code)*
- [yet-another-statusline](https://github.com/tmck-code/yet-another-statusline) — A statusline for Claude Code inspired by terminal monitor programs *(★ 242, BSD-3-Clause, drives Claude Code)*
- [claude-pace](https://github.com/Astro-Han/claude-pace) — Claude Code statusline and rate limit tracker with pace-aware quota monitoring. Pure Bash + jq, single file *(★ 234, MIT, drives Claude Code)*
- [splitrail](https://github.com/Piebald-AI/splitrail) — Fast, cross-platform, real-time token usage tracker and cost monitor for Claude Code / Codex CLI / Antigravity CLI / Qwen Code / Cline / Zoo Code / Kilo… *(★ 222, MIT, drives Antigravity, Claude Code, Cline, Codex, Copilot, Kilo Code…)*
- [claude-codex-usage-dashboard](https://github.com/frankchiu-dev/claude-codex-usage-dashboard) — A local Windows dashboard for Claude Code and Codex usage limits *(★ 173, MIT, drives Claude Code, Codex)*
- [vibe-island](https://github.com/vibeislandapp/vibe-island) — Vibe Island — macOS notch panel for 25 AI coding agents: Claude Code, Codex, Cursor, Gemini CLI & more. Monitor, approve, and jump back from the notch.… *(★ 151, drives Claude Code, Codex, Cursor, Gemini CLI, Vibe)*
- [lumo](https://github.com/zhnd/lumo) — Local-first dashboard for observing Claude Code usage, cost, sessions, and time *(★ 147, MIT, drives Claude Code)* 💤 dormant
- [Agent-Quest](https://github.com/FulAppiOS/Agent-Quest) — Real-time gamified dashboard for monitoring Claude Code and Codex AI agents in a medieval fantasy setting *(★ 140, MIT, drives Claude Code, Codex)*
- [cctop](https://github.com/stefanprodan/cctop) — Live top-style monitor for Claude Code sessions *(★ 139, Apache-2.0, drives Claude Code)*
- [Claud-ometer](https://github.com/deshraj/Claud-ometer) — A local-first analytics dashboard for Claude Code. Gives you full visibility into your usage, costs, sessions, and projects — no cloud, no telemetry, just… *(★ 132, MIT, drives Claude Code)* 💤 dormant
- [CodexBar-Win](https://github.com/babakarto/CodexBar-Win) — Windows system tray app for Claude Code usage monitoring — session limits, weekly limits, reset times, API costs. Windows port of CodexBar *(★ 105, MIT, drives Claude Code, Codex)*
- [token-meter](https://github.com/splunk/token-meter) — Open-source, local-first AI coding agent usage and cost dashboard for Claude Code, Codex, Cursor, OpenCode, Kiro, and Pi *(★ 103, MIT, drives Claude Code, Codex, Cursor, OpenCode, Pi)*
- [cc-status-bar](https://github.com/usedhonda/cc-status-bar) — macOS menu bar app for real-time Claude Code session monitoring *(★ 90, MIT, drives Claude Code)*
- [par_cc_usage](https://github.com/paulrobello/par_cc_usage) — Claude Code usage monitor *(★ 84, MIT, drives Claude Code)*
- [WhereMyTokens](https://github.com/jeongwookie/WhereMyTokens) — Local-first Windows tray app for monitoring Claude Code and Codex tokens, costs, sessions, and rate limits *(★ 84, MIT, drives Claude Code, Codex)*
- [tu](https://github.com/sahil87/tu) — AI coding assistant cost tracking CLI — track token usage across Claude Code, Codex, OpenCode *(★ 4, MIT, drives Claude Code, Codex, OpenCode)*
- [OpenClaw Monitor](https://github.com/flik2002/openclaw-monitor) — Web dashboard for OpenClaw AI agents that reads local session data to show token usage, session history, and 7-day trends *(drives OpenClaw)*

## Companions, Notifications & Statusline

*Sidecars: notifications, HUDs, tamagotchis, and session-completion signals.*

- [claude-hud](https://github.com/jarrodwatts/claude-hud) — A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress *(★ 28.2k, MIT, drives Claude Code)*
- [peon-ping](https://github.com/PeonPing/peon-ping) — Warcraft III Peon voice notifications (+ more!) for Claude Code, Codex, IDEs, and any AI agent. Stop babysitting your terminal. Employ a Peon today *(★ 5.1k, MIT, drives Claude Code, Codex)*
- [qwen-audio-agent](https://github.com/QwenAudio/qwen-audio-agent) — A realtime voice runtime that keeps Agents talking, working, and present.  Real-time Voice Runtime for AI Agents *(★ 2.8k, Apache-2.0)*
- [vibe-notch](https://github.com/farouqaldori/vibe-notch) — Claude Code notifications without the context switch. A minimal, always-present session manager for macOS *(★ 2.5k, Apache-2.0, drives Claude Code)* 💤 dormant
- [MioIsland](https://github.com/MioMioOS/MioIsland) — macOS Dynamic Island for AI coding agents. Monitor, approve, and jump to Claude Code sessions from the notch *(★ 542, drives Claude Code)*
- [VibeAround](https://github.com/jazzenchen/VibeAround) — Keep your AI coding agents around. Launch Claude Code, Codex CLI, Gemini CLI, Pi Agent, and more from one place — side by side, connected, reachable, and… *(★ 523, MIT, drives Claude Code, Codex, Gemini CLI, Pi)*
- [zhigeng](https://github.com/Littlesheepxy/zhigeng) — 知更 — 本地 AI 的上下文与记忆层。Mac 上用语音输入、情境代回并调度 Codex / Claude Code；iOS 正在成为随身记忆终端和本地 Agent 遥控器。Local-first · BYOK *(★ 490, drives Claude Code, Codex)*
- [claude-code-statusline](https://github.com/rz1989s/claude-code-statusline) — Transform your Claude Code terminal with atomic precision statusline. Features flexible layouts, real-time cost tracking, MCP monitoring, prayer times, and… *(★ 478, MIT, drives Claude Code)*
- [claude-code-tamagotchi](https://github.com/Ido-Levi/claude-code-tamagotchi) — Real-time behavioral enforcement for Claude Code. Monitors AI actions, detects violations, and interrupts misbehavior. Also has a cute pet *(★ 433, MIT, drives Claude Code)* 💤 dormant
- [ai-cli-complete-notify](https://github.com/ZekerTop/ai-cli-complete-notify) — 面向 Claude Code / Codex / OpenCode / Gemini / ZCode  的多通道AI CLI 任务完成提醒，支持耗时阈值、桌面端与命令行、通用 Webhook（飞书/钉钉/企微）、Telegram、邮件、桌面/声音提示，配备自动监听日志，AI摘要等功能 *(★ 419, ISC, drives Claude Code, Codex, Gemini CLI, OpenCode)*
- [code-notify](https://github.com/mylee04/code-notify) — Cross-platform desktop notifications for Claude Code, Codex, and Gemini CLI. Install via Homebrew, npm, or script *(★ 290, MIT, drives Claude Code, Codex, Gemini CLI)*
- [claude-code-warp](https://github.com/warpdotdev/claude-code-warp) — Official Warp terminal integration for Claude Code - native notifications and more *(★ 231, MIT, drives Claude Code)*
- [CCNotify](https://github.com/dazuiba/CCNotify) — CCNotify provides desktop notifications for Claude Code, alerting you when Claude needs your input or completes tasks *(★ 215, MIT, drives Claude Code)* 💤 dormant
- [fox-ai-roundtable](https://github.com/PeterPanSwift/fox-ai-roundtable) — 🦊 Ask once, get three answers — same prompt to Claude / Codex (GPT) / Antigravity (Gemini) via their local CLIs *(★ 75, drives Antigravity, Claude Code, Codex, Gemini CLI)*
- [termagitchi](https://github.com/TevvvB/termagitchi) — A creature for every git worktree, living in your coding agent's status line. Deterministic species, rarity bands, and one view across every live session *(★ 18, MIT)*
- [llm-panel](https://github.com/musharna/llm-panel) — Ask several LLMs independently, read every answer in full — parallel judges, anonymized rebuttal round, cost accounting, and a measured recall benchmark *(★ 1, MIT)*

## Model Routers & Account Managers

*Proxies, account switchers, profile managers, and multi-provider gateways for agent CLIs.*

- [OmniRoute](https://github.com/diegosouzapw/OmniRoute) — Never stop coding. Free MIT AI gateway: one endpoint, 359 providers (150+ free), 1200+ models Kimi, Claude, GPT, Gemini, GLM, DeepSeek, MiniMax. Works with… *(★ 70.4k, MIT, drives Claude Code, Cline, Codex, Copilot, Cursor, DeepSeek…)*
- [free-claude-code](https://github.com/Alishahryar1/free-claude-code) — Use Claude Code, Codex, Pi, and OpenCode (and 6 other harnesses) for free (1.3B+ free tokens) from your terminal, app, IDE, or phone, and now from the… *(★ 56k, drives Claude Code, Codex, OpenClaw, OpenCode, Pi)*
- [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) — Wrap Antigravity, ChatGPT Codex, Claude Code, Grok Build, Muse Code, Davin as an OpenAI/Gemini/Claude/Codex compatible API service, allowing you to enjoy… *(★ 53.3k, MIT, drives Antigravity, Claude Code, Codex, Gemini CLI, Grok, Grok Build)*
- [claude-code-router](https://github.com/musistudio/claude-code-router) — One local control plane for every AI agent: route across models, fuse new capabilities, orchestrate tools, and stay fully in control *(★ 37.4k, MIT)*
- [Antigravity-Manager](https://github.com/lbjlaq/Antigravity-Manager) — Professional Antigravity Account Manager & Switcher. One-click seamless account switching for Antigravity Tools. Built with Tauri v2 + React (Rust).专业的… *(★ 31.8k, drives Antigravity)*
- [9router](https://github.com/decolua/9router) — Unlimited FREE AI coding. Connect Claude Code, Codex, Cursor, Cline, Copilot, Antigravity to FREE Claude/GPT/Gemini via 40+ providers. Auto-fallback, RTK… *(★ 29.9k, MIT, drives Antigravity, Claude Code, Cline, Codex, Copilot, Cursor…)*
- [OpenCodex](https://github.com/lidge-jun/opencodex) — Universal provider proxy for OpenAI Codex & Claude Code — use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama…) with Codex CLI, App, SDK, and Claude Code *(★ 16.3k, MIT, drives Claude Code, Codex, DeepSeek, Gemini CLI, Grok)*
- [codex-lb](https://github.com/Soju06/codex-lb) — Codex/ChatGPT multiple account load balancer & proxy with usage tracking, dashboard, and OpenCode-compatible endpoints *(★ 3.3k, MIT, drives Codex, OpenCode)*
- [claude-swap](https://github.com/realiti4/claude-swap) — Switch between multiple Claude Code accounts, with automatic rate-limit rotation, usage dashboard, and parallel sessions *(★ 2.8k, MIT, drives Claude Code)*
- [meridian](https://github.com/rynfar/meridian) — Use Claude and Antigravity with Pi, OpenCode and other coding clients. Local API bridge, usage dashboard and Mac app. Antigravity preview available in 1.74.0 *(★ 2.1k, drives Antigravity, OpenCode, Pi)*
- [proxypal](https://github.com/heyhuynhgiabuu/proxypal) — A desktop app that lets you use your AI subscriptions (Claude, ChatGPT, Gemini, GitHub Copilot) with any coding tool. Wraps CLIProxyAPI with a clean UI for… *(★ 1.2k, MIT, drives Copilot, Gemini CLI)*
- [ai-tools-mng](https://github.com/cubezhao/ai-tools-mng) — 基于 Tauri 的跨平台桌面应用，用于管理多平台 AI 账号 Augment、Antigravity、Windsurf、Cursor、OpenAI（Codex、API）、Claude Code 与 API 账号，以及订阅、书签管理与邮箱管理。A Tauri-based cross-platform… *(★ 1.2k, MIT, drives Antigravity, Augment, Claude Code, Codex, Cursor, Windsurf)*
- [ccNexus](https://github.com/lich0821/ccNexus) — Intelligent API gateway for Claude Code and Codex CLI - rotate endpoints, monitor usage, and seamlessly integrate OpenAI, Gemini, and other platforms *(★ 971, MIT, drives Claude Code, Codex, Gemini CLI)*
- [antigravity-panel](https://github.com/n2ns/antigravity-panel) — Community toolkit for Google Antigravity IDE. Quota dashboard (Gemini/Claude/GPT), usage trends + runway prediction, cache manager (Brain Tasks & Code),… *(★ 713, Apache-2.0, drives Antigravity, Gemini CLI)*
- [AIUsage](https://github.com/sylearn/AIUsage) — One dashboard to manage all your AI subscriptions — track quotas, costs, accounts, Claude Code proxy, and Codex proxy in one place *(★ 686, Apache-2.0, drives Claude Code, Codex)*
- [Claudexor](https://github.com/razzant/claudexor) — Multi-harness control plane for Claude Code, Codex, Cursor, and OpenCode: quota-aware rotation across multiple Claude/Codex subscriptions, shared thread… *(★ 487, MIT, drives Claude Code, Codex, Cursor, OpenCode)*
- [codex-switch](https://github.com/piperhex/codex-switch) — Codex Switch & Codex GUI & CSwitch & Codex Mobile & Codex Remote & Codex Web *(★ 316, Apache-2.0, drives Codex)*
- [ccxray](https://github.com/lis186/ccxray) — X-ray vision for AI agent sessions — a transparent HTTP proxy and dashboard for Claude Code *(★ 296, drives Claude Code)*
- [cc-router](https://github.com/finch-xu/cc-router) — 本地运行的大模型聚合网关，GUI桌面端app，零代码部署，把Coding Plan、大模型 API 额度聚合成一个虚拟 Plan，一键接入 Claude Code、Claude Desktop App、OpenClaw、OpenCode 等工具。Bundle your scattered Token Plan,… *(★ 253, MIT, drives Claude Code, OpenClaw, OpenCode)*
- [claude-unlimited](https://github.com/DevDock-AI/claude-unlimited) — Rotate Claude and GPT subscriptions and API keys seamlessly inside the Claude Code CLI — switch on usage limits without interrupting your session, all from… *(★ 242, MIT, drives Claude Code)*
- [clauth](https://github.com/uwuclxdy/clauth) — Claude Code multi-account manager, usage monitor (CLI, TUI & MCP cross-account delegation) *(★ 225, MIT, drives Claude Code)*
- [coding_agent_account_manager](https://github.com/Dicklesworthstone/coding_agent_account_manager) — Sub-100ms auth switching for AI coding CLIs (Claude Code, Codex, Gemini): swap subscription accounts instantly when you hit usage limits *(★ 204, drives Claude Code, Codex, Gemini CLI)*
- [qwengate](https://github.com/youssefvdel/qwengate) — Drop-in OpenAI-compatible API gateway for Qwen AI models. Use your Qwen account (chat.qwen.ai) as a free AI API provider in any OpenAI-compatible client —… *(★ 200, MIT, drives Claude Code, Continue, Copilot, Cursor, Qwen)*
- [codex-profiles](https://github.com/Ducksss/codex-profiles) — Named CODEX_HOME profiles and ChatGPT Desktop windows with separate local state, without copying tokens *(★ 169, MIT, drives Codex)*
- [aisw](https://github.com/burakdede/aisw) — AISW · AI Switcher - Switch between multiple Claude Code, Codex CLI, Antigravity and Gemini CLI accounts in one command. Named profile manager for AI coding… *(★ 121, MIT, drives Antigravity, Claude Code, Codex, Gemini CLI)*
- [notion_manager](https://github.com/SleepingBag945/notion_manager) — Local account pool, dashboard & Anthropic-compatible API proxy for Notion AI. Claude Code compatible. Built with Go + React. 本地 Notion AI 多账号池管理与 API… *(★ 113, drives Claude Code)*
- [fable5-opus5.5-orchestrator](https://github.com/Rylaa/fable5-opus5.5-orchestrator) — Keep Claude Fable 5 in the chair all day without draining your usage limit — token-frugal multi-agent orchestration plugin for Claude Code: tier routing… *(★ 77, MIT, drives Claude Code)*
- [mobius](https://github.com/chussum/mobius) — ∞ macOS menu bar app for switching Claude Code / OpenAI Codex / Claude Desktop accounts in one click — auto-fallback when you hit usage limits, auto-return… *(★ 71, MIT, drives Claude Code, Codex)*
- [FireConnect](https://github.com/fw-ai/fireconnect) — Use Fireworks AI models in Claude Code, Codex, Cursor, VS Code, Copilot, and other coding agents *(★ 53, Apache-2.0, drives Claude Code, Codex, Copilot, Cursor)*
- [Kolkrabbi](https://github.com/onembyte/kolkrabbi) — Open-source AI coding agent for the terminal that works with several subscriptions in one session — your Claude Pro/Max, ChatGPT Plus/Pro (Codex) and GitHub… *(★ 1, Apache-2.0, drives Codex, Continue, Copilot)*

## Sandboxes & Isolated Environments

*Containers, worktree runners, VMs, and isolation layers agents execute inside.*

- [NemoClaw](https://github.com/NVIDIA/NemoClaw) — Run agents like Hermes, LangChain Deep Agents, and OpenClaw more securely inside NVIDIA OpenShell with managed inference *(★ 22.5k, Apache-2.0, drives Hermes, OpenClaw)*
- [Omnigent](https://github.com/omnigent-ai/omnigent) — Omnigent is an open-source AI agent framework and meta-harness: orchestrate Claude Code, Codex, Cursor, Pi, and custom agents — swap harnesses without… *(★ 10.3k, Apache-2.0, drives Claude Code, Codex, Cursor, Pi)*
- [Claude Squad](https://smtg-ai.github.io/claude-squad/) — Manage multiple AI terminal agents like Claude Code, Codex, OpenCode, and Amp *(★ 8.5k, AGPL-3.0, drives Amp, Claude Code, Codex, Continue, OpenCode)*
- [sandcastle](https://github.com/mattpocock/sandcastle) — Orchestrate sandboxed coding agents in TypeScript with sandcastle.run() *(★ 8.2k, MIT)*
- [Supacode](https://supacode.sh/) — worktree coding agents command center *(★ 2.4k)*
- [AgentsMesh](https://agentsmesh.ai/) — The AI Agent Workforce Platform. Run a hundred AI coding agents across your own machines — schedule, isolate, and steer them all from one console *(★ 2.4k, drives Aider, Claude Code, Codex, Gemini CLI, OpenCode)*
- [vibekit](https://github.com/superagent-ai/vibekit) — Run Claude Code, Gemini, Codex — or any coding agent — in a clean, isolated sandbox with sensitive data redaction and observability baked in *(★ 1.9k, MIT, drives Claude Code, Codex, Gemini CLI)* 💤 dormant
- [spec-kitty](https://github.com/spec-kitty/spec-kitty) — Spec-Driven Development for serious software developers. Spec Coding with with Claude, Cursor, Gemini, Codex. Kanban dashboard, git worktrees, auto-merge… *(★ 1.6k, MIT, drives Codex, Cursor, Gemini CLI)*
- [sandbox-agent](https://github.com/rivet-dev/sandbox-agent) — Run Coding Agents in Sandboxes. Control Them Over HTTP. Supports Claude Code, Codex, OpenCode, and Amp *(★ 1.6k, Apache-2.0, drives Amp, Claude Code, Codex, OpenCode)*
- [codexia](https://github.com/milisp/codexia) — Lightweight Agent Workstation for Codex CLI + Claude Code — with task scheduler, git worktree & remote control *(★ 920, MIT, drives Claude Code, Codex)*
- [claude-agent-server](https://github.com/dzhng/claude-agent-server) — Run Claude Agent (Claude Code) in a sandbox, control it via websocket *(★ 584, drives Claude Code)* 💤 dormant
- [uzi](https://github.com/devflowinc/uzi) — CLI for running large numbers of coding agents in parallel with git worktrees *(★ 583, MIT)* 💤 dormant
- [AgentBox](https://agent-box.sh/) — Run multiple agents in parallel sandboxed VMs, with a single command, on your PC or in the cloud *(★ 493, MIT)*
- [Coasts](https://github.com/coast-guard/coasts) — Localhost service isolation and orchestration for git worktrees *(★ 430, MIT)* 💤 dormant
- [sandvault](https://github.com/webcoyote/sandvault) — Run AI agents isolated in a macOS user account and sandbox-exec. Configured to run Claude Code, OpenAI Codex, Cursor Agent, Google Gemini *(★ 421, Apache-2.0, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [mngr](https://github.com/imbue-ai/mngr) — CLI for managing coding agents *(★ 413)*
- [wmux](https://github.com/openwong2kim/wmux) — Run Claude Code, Codex & Gemini in parallel on Windows & macOS — git worktree fan-out with atomic hunk adoption, approval gates, reboot-surviving sessions *(★ 398, MIT, drives Claude Code, Codex, Gemini CLI)*
- [agent-worktree](https://github.com/nekocode/agent-worktree) — A Git worktree workflow tool for AI coding agents. Enables parallel development with isolated environments *(★ 279, MIT)*
- [claude-docker](https://github.com/VishalJ99/claude-docker) — Docker container for running Claude Code with full permissions and Twilio notifications *(★ 188, MIT, drives Claude Code)* 💤 dormant
- [VibePod](https://github.com/VibePod/vibepod-cli) — Unified CLI for running AI coding agents in isolated containers. Includes built-in local metrics collection, HTTP traffic tracking, and an analytics… *(★ 169, MIT)*
- [brood-box](https://github.com/stacklok/brood-box) — CLI tool for running coding agents inside hardware-isolated microVMs *(★ 75, Apache-2.0)*
- [dux](https://getdux.app/) — Dux is a terminal UI that lets you run multiple AI coding agents side by side, each in its own git worktree, with full companion terminals, macros, commit… *(★ 67, MIT)*
- [clash](https://github.com/clash-sh/clash) — Avoid merge conflicts across git worktrees for parallel AI coding agents *(★ 64, MIT)*
- [ai-agent-board](https://github.com/DanWahlin/ai-agent-board) — Drag-and-drop Kanban board that delegates coding tasks to AI agents — GitHub Copilot, Claude Code, OpenAI Codex, and OpenCode — with real-time streaming,… *(★ 60, MIT, drives Claude Code, Codex, Copilot, OpenCode)*
- [claudebox](https://github.com/numtide/claudebox) — responsible Claude Code YOLO *(★ 57, drives Claude Code)* 💤 dormant
- [AgentTier](https://github.com/agenttier/agenttier) — Kubernetes-native sandbox platform to run AI agents, coding assistants and harnesses *(★ 55, Apache-2.0)*
- [sigbound](https://github.com/surya-koritala/sigbound) — Run AI coding agents in parallel on one git repo and safely auto-merge their work — only changes that build and pass tests land. On top of plain git; bring… *(★ 45, Apache-2.0)*
- [machine](https://github.com/katspaugh/machine) — One isolated Lima VM per GitHub project — sandboxed Claude Code/Codex, Docker, Node, signed git *(★ 15, MIT, drives Claude Code, Codex)*
- [taskpods](https://github.com/yanairon/taskpods) — Run parallel AI coding agents in isolated Git worktrees with one lightweight, agent-agnostic CLI *(★ 5, MIT)*
- [distro-rig-vps](https://github.com/shafir-info/distro-rig-vps) — AI agent sandbox — root inside disposable, real-boot Linux VMs on self-hosted KVM. The rig grants no host sudo, /dev/kvm or libvirt access. Deny-by-default… *(★ 2, GPL-3.0)*
- [WorkGround2](https://github.com/KiddPhenix/WorkGround2) — Local-first AI engineering workbench — CLI, desktop & IM bots sharing one Go agent kernel (cache-first · MCP · sandboxed · rewindable) *(★ 2, MIT)*
- [wt](https://github.com/sahil87/wt) — Git worktree CLI for parallel-edit workflows — sibling layout and shell-integrated navigation *(★ 2, MIT)*

## Agent Runtimes & Harness Infrastructure

*Self-hosted runtimes and operating layers underneath agents and swarms.*

- [claude-flow](https://github.com/ruvnet/ruflo) — 🌊 The original agent harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features… *(★ 73.3k, MIT, drives Claude Code, Codex, Hermes)*
- [openfang](https://github.com/RightNow-AI/openfang) — Open-source Agent Operating System *(★ 18.2k, Apache-2.0)*
- [AX](https://github.com/google/ax) — Google's open agentic orchestration runtime *(★ 11.9k, Apache-2.0)*
- [Open Multi-Agent](https://github.com/open-multi-agent/open-multi-agent) — Self-hosted TypeScript agent runtime with durable approvals and verifiable run records. Own it, approve it, audit it *(★ 7k, MIT)*
- [Docker Agent](https://github.com/docker/docker-agent) — AI Agent Builder and Runtime by Docker Engineering *(★ 3.4k, Apache-2.0)*
- [Citadel](https://github.com/SethGammon/Citadel) — The operating layer for Claude Code + OpenAI Codex: persistent project memory, intent routing, safety hooks, cost telemetry, and parallel agent fleets *(★ 923, MIT, drives Claude Code, Codex)*

## Coordination, Messaging & Protocols

*Shared state, task boards, agent-to-agent messaging, and protocols like MCP/ACP.*

- [oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex) — OmX - Oh My codeX: Your codex is not alone. Add hooks, agent teams, HUDs, and so much more *(★ 33.4k, MIT, drives Codex)*
- [Beads](https://github.com/gastownhall/beads) — Beads - A memory upgrade for your coding agent *(★ 27.4k, MIT)*
- [Archon](https://github.com/coleam00/Archon) — The first open-source harness builder for AI coding. Make AI coding deterministic and repeatable *(★ 23.6k, MIT, drives Claude Code, Codex)*
- [Agentlas OS](https://github.com/agentlas-ai/Agentlas-OS) — Agent OS: keep specialist agents in a hub, spin up a temporary orchestrator per task. Local-first, works with any model *(★ 1.5k, Apache-2.0)*
- [SandBase Harness](https://github.com/sandbaseai/sandbase-harness) — Local-first, self-hosted AI agent runtime and MCP bridge with sandboxed sessions, memory, credentials, audit/replay, and a local Console *(★ 674, Apache-2.0)*
- [foremerge](https://github.com/naw103/foremerge) — Catch intent conflicts before code conflicts. The open-source coordination protocol for coding agents, built above Git *(★ 511, Apache-2.0, drives Claude Code, Codex, Cursor)*
- [Concord MCP](https://github.com/Get-Concord-AI/concord-mcp) — Live messaging for coding agents *(★ 335, MIT, drives Claude Code, Codex, Cursor, Gemini CLI, Grok Build)*
- [guild](https://github.com/mathomhaus/guild) — Shared context, memory, and task coordination across AI coding agents. Single Go binary, local SQLite, hybrid keyword and semantic search *(★ 302, Apache-2.0)*
- [AIWG](https://github.com/jmagly/aiwg) — Cognitive architecture for AI-augmented software development. Specialized agents, structured workflows, and multi-platform deployment. Claude Code · Codex ·… *(★ 211, MIT, drives Augment, Claude Code, Codex, Copilot, Cursor, Factory Droid…)*
- [ax](https://github.com/Necmttn/ax) — the agent experience layer · observability + memory for AI coding agents (Claude Code + Codex) · local-first, typed, yours *(★ 113, AGPL-3.0, drives Claude Code, Codex)*
- [Harness Starter Kit](https://github.com/harnessworks/harness-starter-kit) — 🐴 Prompt-first harness engineering for safer AI coding agent workflows *(★ 113, MIT)*
- [gnap](https://github.com/farol-team/gnap) — GNAP — Git-Native Agent Protocol. RFC Draft for git-based agent orchestration. Zero servers *(★ 86, MIT)* 💤 dormant
- [AgentPlane](https://github.com/basilisk-labs/agentplane) — 🛩️ Git-native workflow control for coding agents: approved plans, verification, and reviewable evidence for Claude Code, Codex, Cursor, and Aider *(★ 81, MIT, drives Aider, Claude Code, Codex, Cursor)*
- [swarm-protocol](https://github.com/phuryn/swarm-protocol) — Coordination protocol for agent-first teams. No UI. No sprints. No Jira. Just state sync *(★ 54, MIT)* 💤 dormant
- [Okto Nexus](https://github.com/OktoLabsAI/okto-nexus) — Local-first MCP coordination hub for multi-agent teams, with durable messaging, handoffs, governance, and observability *(★ 51)*
- [wit](https://github.com/amaar-mc/wit) — Agent coordination protocol — declare intents, lock symbols, detect conflicts before code is written *(★ 46, MIT)* 💤 dormant
- [Agent Messaging Protocol](https://github.com/agentmessaging/protocol) — Agent Messaging Protocol (AMP) - the open standard for secure AI agent communication *(★ 35, Apache-2.0, drives Amp, Claude Code)*
- [codecast](https://github.com/codecast-sh/codecast) — See, steer, and remember every coding agent session — Claude Code, Codex, Cursor, Gemini. Team memory, live steering from any device, line-level agent… *(★ 33, MIT, drives Claude Code, Codex, Cursor, Gemini CLI)*
- [LionClaw](https://github.com/moshthepitt/lionclaw) — Lionclaw is a local control plane for AI coding agents. It runs AI agents as durable, auditable workers with explicit state, skills, channels, schedules,… *(★ 19, MIT)*
- [grite](https://github.com/neul-labs/grite) — The issue tracker that lives in your repo. Built for AI agents. Works for humans *(★ 18, MIT)*
- [Agentic Engineering Framework](https://github.com/DimitriGeelen/agentic-engineering-framework) — Governance framework for AI coding agents — enforces task traceability, structural gates, session continuity, and audit trails for Claude Code, Cursor, and… *(★ 15, Apache-2.0, drives Claude Code, Copilot, Cursor)*
- [agent-runbook](https://github.com/KnoxOps/agent-runbook) — Contract-based multi-agent skill framework for Claude Code & Codex — compile YAML runbooks into SKILL.md with loop, parallel, and checkpoint support *(★ 13, Apache-2.0, drives Claude Code, Codex)*
- [myc](https://github.com/aistastudio/myc) — AI-agents development memory/tasks/context *(★ 13, MIT)*
- [clu](https://github.com/Arjia-Labs/clu) — Local-first SQLite issue tracker for coordinating AI coding agents — atomic claim, dependency graphs, workflows & checkpoints, audit log. No daemon, no network *(★ 8, MIT)*
- [SpecWave](https://github.com/Cyning12/SpecWave) — SpecWave — multi-host coding CLI + P0 gates/Harness (Cursor/Claude/DSH). Formerly SpecGate / dsh-coding-kit. npx spec-wave *(★ 6, MIT, drives Cursor)*
- [Weaver](https://github.com/sean35mm/weaver) — Shared situational awareness for multiple coding agents working in the same repo *(★ 3, MIT)*
- [Agent Client Protocol (ACP)](https://agentclientprotocol.com) — Zed's protocol for embedding agents in editor/host clients; used by Obsidian Agent Client, CodeCompanion.nvim, Agentic.nvim, Agent of Empires, and Agent Kanban
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io) — connects agents to tools/data; the dominant integration protocol here

## Memory & Context Layers

*Persistent memory, context stores, and session history that outlive a single run.*

- [agentic-stack](https://github.com/codejunkie99/agentic-stack) — One brain, many harnesses. Portable .agent/ folder (memory + skills + protocols) that plugs into Claude Code, Cursor, Windsurf, OpenCode, OpenClaw, Hermes,… *(★ 2.3k, Apache-2.0, drives Claude Code, Cursor, Hermes, OpenClaw, OpenCode, Windsurf)*
- [octogent](https://github.com/hesamsheikh/octogent) — A thin orchestration dashboard over Claude Code for managing context, automation, and developer headspace. You need tentacles. 🦑 *(★ 1.4k, MIT, drives Claude Code)* 💤 dormant
- [OpenContext](https://github.com/0xranx/OpenContext) — A personal context store for AI agents and assistants—reuse your existing coding agent CLI (Codex/Claude/OpenCode) with built‑in Skills/tools and a desktop… *(★ 1.2k, MIT, drives Codex, OpenCode)*
- [gentle-shell](https://github.com/Gentleman-Programming/gentle-shell) — Gentle Shell is a Pi-native coding-agent harness for controlled development with Organic Driven Development, optional SDD/OpenSpec, subagents, TDD evidence,… *(★ 1.1k, MIT, drives Pi)*
- [AI Maestro](https://github.com/23blocks-OS/ai-maestro) — AI Agent Orchestrator with Skills System - Give AI Agents superpowers: memory search, code graph queries, agent-to-agent messaging. Manage Claude, Codex or… *(★ 799, MIT, drives Codex)*
- [GitClaw](https://github.com/open-gitagent/gitagent) — A universal git-native AI agent framework. Your agent lives inside a git repo — identity, rules, memory, tools, and skills are all version-controlled files *(★ 709, MIT)*
- [Vestige](https://github.com/samvallad33/vestige) — Cognitive deterministic memory transaction security kernel for agents, that traces backwards to find the root cause and not the lookalike *(★ 635, AGPL-3.0)*
- [claude-elixir-phoenix](https://github.com/oliver-kriska/claude-elixir-phoenix) — Claude Code plugin for Elixir/Phoenix/LiveView — 26 specialist agents, Iron Laws enforcement, and Tidewave MCP integration. Plan features with parallel… *(★ 555, MIT, drives Claude Code)*
- [deepagent-code](https://github.com/deepagent-ltd/deepagent-code) — DeepAgent Code: AI coding agent with persistent memory and control plane *(★ 435)*
- [memstack](https://github.com/cwinvestments/memstack) — Structured skill framework for Claude Code. 130 skills, persistent memory, TokenStack compression, localhost dashboard with 3-agent runner, real-time… *(★ 423, MIT, drives Claude Code)*
- [slotstream](https://github.com/carloslfu/slotstream) — Run a 105 GB AI model on a Mac that can't hold it. Slotstream streams Qwen3.8-Flash-Next (125B mixture of experts) from your SSD and caches the busiest… *(★ 399, MIT, drives Claude Code, Codex, Qwen)*
- [GUI-Anything](https://github.com/YurunChen/GUI-Anything) — GUI-Anything is a dual-pane Flow Observer for Claude Code. It watches live JSONL sessions, visualizes exploration as timelines and flowcharts, and curates… *(★ 286, drives Claude Code)*
- [Awareness-Local](https://github.com/edwin-hao-ai/Awareness-Local) — Local-first AI agent memory — one command, works offline, no account needed. Give your Claude Code, Cursor, Windsurf, OpenClaw agent persistent memory.… *(★ 199, MIT, drives Claude Code, Cursor, OpenClaw, Windsurf)* 💤 dormant
- [rails-ai-context](https://github.com/crisnahine/rails-ai-context) — 45 MCP tools that give AI coding agents ground truth about your Rails app: schema, models, routes, controllers, views, jobs, conventions. Works with Claude… *(★ 158, MIT, drives Claude Code, Codex, Copilot, Cursor, OpenCode)*
- [cctx](https://github.com/nwiizo/cctx) — Claude Code context manager for switching between multiple settings.json configurations *(★ 148, MIT, drives Claude Code)*
- [contextvc](https://github.com/HaochengLu/contextvc) — Git-native context control plane for AI coding agents *(★ 143, Apache-2.0)*
- [alive](https://github.com/alivecontext/alive) — Personal Context Manager for Claude Code. Your life in walnuts *(★ 129, MIT, drives Claude Code)*
- [claudex](https://github.com/kunwar-shah/claudex) — MCP server with persistent memory + FTS5 search for Claude Code conversation history. Index your ~/.claude/projects/, expose 10 MCP tools, browse via web… *(★ 95, MIT, drives Claude Code)*
- [claude-context-manager](https://github.com/gaoziman/claude-context-manager) — claude-context-manager for claude code *(★ 85, MIT, drives Claude Code)* 💤 dormant
- [pi-mem](https://github.com/jo-inc/pi-mem) — Plain-Markdown persistent memory for AI coding agents. Long-term facts, daily logs, scratchpad, and semantic search — works with pi, Claude Code, and any… *(★ 78, MIT, drives Claude Code, Pi)*
- [pond](https://github.com/tenequm/pond) — Lossless storage and search for AI agent sessions, across every agentic client *(★ 73, Apache-2.0)*
- [ox](https://github.com/sageox/ox) — The hivemind for AI coding agents — persistent team context recorded once and recalled across agents, machines, and teammates *(★ 61, MIT)*
- [neuralyzer](https://github.com/gintasz/neuralyzer) — AI agent harness tool allowing it to wipe its own session context and re-run the first message *(★ 39, MIT)*
- [Data Olympus](https://github.com/knaisoma/data-olympus) — Governance-grade, OKF-compatible knowledge-base format with a single-writer MCP server and CLI. Pre-release *(★ 26, Apache-2.0)*
- [AgentPack](https://github.com/vishal2612200/agentpack) — Local context engine for AI coding agents. Routes tasks to relevant files, tests, rules, and skills, supports prompt caching, and builds compact context… *(★ 25, AGPL-3.0, drives Claude Code, Codex, Cursor)*
- [Mnemoverse](https://github.com/mnemoverse/mcp-memory-server) — Hosted persistent memory for AI agents over MCP. Tell it a recalled memory helped or misled, and it re-ranks what comes back next. Shared rooms for… *(★ 25, MIT, drives Claude Code, Cursor, Gemini CLI, Windsurf)*
- [m1nd](https://github.com/maxkle1nz/m1nd) — m1nd is a local-first context runtime for coding agents: an evidence-bound, continuously verified model of your code, memory, and change *(★ 21, MIT)*
- [Mneme](https://github.com/MnemeHQ/mneme) — Architectural drift prevention for the agentic AI SDLC *(★ 21, MIT)*
- [GoodMemory](https://github.com/hjqcan/GoodMemory) — Local-first, auditable memory layer for AI apps and coding agents — Codex, Claude Code, MCP, HTTP, TypeScript, and Python *(★ 18, MIT, drives Claude Code, Codex)*
- [Tree Ring Memory](https://github.com/TerminallyLazy/Tree-Ring-Memory) — Framework-agnostic, local-first memory lifecycle for AI agents: Rust CLI, SQLite/FTS recall, forgetting, audit, consolidation, DOX/Revolve adapters, and TUI *(★ 18, MIT, drives forge)*
- [aGiTrack](https://github.com/core-aix/agitrack) — Every agent turn becomes a traceable commit carrying the full interaction trace, model, and token cost, plus a live dashboard and a coach that teaches you,… *(★ 17, Apache-2.0, drives Claude Code, Codex, OpenCode)*
- [OB-1](https://github.com/Overbrilliant/ob-1) — Free open-source coding agent for your terminal. No account, no API key, no card. Parallel subagents, self-correction until your checks pass, project memory *(★ 16, Apache-2.0)*
- [Agent Memory System](https://github.com/RavByte-AI/agent-memory-system) — Generate and maintain AI-readable project memory, worklogs, and handoffs for any repository *(★ 14, MIT)* 💤 dormant
- [context-bridge](https://github.com/serdardb/context-bridge) — Switch agents. Not context. Context bridge across Claude Code, Codex, Grok and Antigravity sessions *(★ 4, MIT, drives Antigravity, Claude Code, Codex, Grok)*
- [opencode-agent-memory](https://github.com/Ghilteras/opencode-agent-memory) — Persistent, self-editable memory blocks and an optional append-only journal with local semantic search for the OpenCode coding agent *(★ 3, MIT, drives OpenCode)*
- [Project Tiny Context Harness](https://github.com/Seven128/project-tiny-context-harness) — Minimal project memory and validation harness for AI coding agents *(★ 3, MIT)*
- [BlaBla](https://github.com/Kiborgik/blabla) — Executable project memory for coding agents — behavioral and structural contracts, minimized counterexamples, and explicit completion gates *(★ 2, MIT)*
- [MoCode](https://github.com/wanxunyang/mocode) — Terminal coding agent with durable memory, hash-gated skill trust and a 61-task eval harness. Works with any OpenAI-compatible backend (GLM / DeepSeek /… *(★ 2, MIT, drives DeepSeek, Qwen)*

## Security, Policy & Review Gates

*Guardrails, permission brokers, sandboxes policies, and verification gates.*

- [Free Code](https://github.com/freecodexyz/free-code) — The free build of Claude Code. All telemetry removed, security-prompt guardrails stripped, all experimental features enabled *(★ 8.8k, drives Claude Code)*
- [OpenAgentsControl](https://github.com/darrenhinde/OpenAgentsControl) — AI agent framework for plan-first development workflows with approval-based execution. Multi-language support (TypeScript, Python, Go, Rust) with automatic… *(★ 4.9k, MIT, drives OpenCode)*
- [OneCLI](https://github.com/onecli/onecli) — Open-source sandboxed agent harness for teams. Giving every employee a secured personal agent *(★ 3.5k, Apache-2.0)*
- [numbat](https://github.com/perplexityai/numbat) — Visibility into AI agent activity on endpoints, with on-device detection, optional pre-action blocking, and forensic reconstruction *(★ 1.1k, Apache-2.0)*
- [AgentSight](https://github.com/eunomia-bpf/agentsight) — lightweight system-level observability for AI Agents *(★ 708, MIT)*
- [HOL Guard](https://github.com/hashgraph-online/hol-guard) — Open-source antivirus for AI agents: block risky tools, secret access, prompt injection, malicious packages, MCP servers, plugins, and skills at runtime *(★ 669, Apache-2.0)*
- [cyber-neo](https://github.com/Hainrixz/cyber-neo) — Open-source cybersecurity analysis agent for Claude Code. Scans projects for vulnerabilities across all OWASP 2025 Top 10 and CWE Top 25 categories. 11… *(★ 272, MIT, drives Claude Code)*
- [repo-forensics](https://github.com/alexgreensh/repo-forensics) — Offline security scanner for AI-agent repos, skills, plugins, and MCP servers *(★ 181)*
- [rish-app](https://github.com/ZSeven-W/rish-app) — Your pocket agent. Local-first AI agents on iOS and Android — real workspaces, tool execution with approvals, and your choice of model (DSH · Claude Code ·… *(★ 148, MIT, drives Claude Code, Codex)*
- [c9watch](https://github.com/minchenlee/c9watch) — c9watch (short for claude code watch, like k8s for Kubernetes) is a macOS desktop app that gives you a real-time dashboard of every Claude Code session… *(★ 128, MIT, drives Claude Code)*
- [DvalinCode](https://github.com/arthurpanhku/dvalincode) — Independent security verification for code written by humans and AI agents. Scan, repair, then prove it — Dvalin runs your project's own checks and issues a… *(★ 118, MIT)*
- [flameox](https://github.com/morluto/flameox) — Runtime evidence that helps agents trace, profile, and burn down hotspots in application and native code, GPU kernels, and inference stacks *(★ 114, MIT)*
- [jev-gui-delegate](https://github.com/YUTA-fywoo/jev-gui-delegate) — AI-assisted Windows and Chrome GUI delegation for Codex: task contracts, local execution, Jev semantic decisions, recovery and outcome verification *(★ 110, drives Codex)*
- [ActPlane](https://github.com/eunomia-bpf/ActPlane) — eBPF Information Flow Enforcement for AI Agent safety, security and effectiveness *(★ 103, MIT)*
- [authsome](https://github.com/agentrhq/authsome) — Credential gateway for AI agents. Log in once via Oauth2 or API Key. Every agent stays authenticated — headless, no SaaS, agents never see your credentials *(★ 92, MIT)*
- [RoleCraft](https://github.com/rolecraft-sh/rolecraft) — The security-first skill manager for AI agents — every install runs a security scan. Manage skills & MCP servers across 87 agents. Zero-dependency CLI *(★ 82, MIT)*
- [vnx-orchestration](https://github.com/Vinix24/vnx-orchestration) — Governance-first orchestration for Claude Code, Codex, and Gemini CLI — parallel workers, receipts, quality gates, and full provenance *(★ 61, MIT, drives Claude Code, Codex, Gemini CLI)*
- [TraceFold](https://github.com/TraceFold/tracefold) — AI agents should not make irreversible changes. TraceFold escrows the inverse before an effect lands, or refuses it, and issues receipts anyone can verify… *(★ 18, Apache-2.0)*
- [agy-auto](https://github.com/onkarbadve/agy-auto) — Auto-permission engine for Antigravity CLI (agy): deterministic AST parser + LLM classifier *(★ 9, MIT, drives Antigravity)*
- [shim-cli](https://github.com/GetSHIM/shim-cli) — Local traffic visibility and privacy controls for coding agents. See what Claude Code, Codex and Copilot actually send to the model, and mask secrets and… *(★ 7, Apache-2.0, drives Claude Code, Codex, Copilot)*
- [PatchWarden](https://github.com/jiezeng2004-design/PatchWarden) — Turn your ChatGPT conversations into safe, auditable local execution. PatchWarden lets you discuss ideas and plans with ChatGPT, then hand the approved plan… *(★ 5, MIT)*
- [Hivelore](https://github.com/Doucs91/hivelore) — Policy enforcement layer for AI coding agents — briefing gates, team memory, Git/CI checks *(★ 3, Apache-2.0)*
- [Minicode](https://github.com/startupmini/minicode) — Coding agent CLI yang menunjukkan semua kerjanya — transparent, permission-first, MIT, zero-dep. npm: minicode-ai *(★ 1, MIT)*

## Agent Tooling: Browsers, MCP Adapters & Utilities

*Browsers, SSH bridges, LSP/MCP adapters, context kits, and CLI utilities agents call.*

- [agent-browser](https://github.com/vercel-labs/agent-browser) — Browser automation CLI for AI agents *(★ 43.2k, Apache-2.0)*
- [ego-lite](https://github.com/citrolabs/ego-lite) — The fastest browser for AI agents to run browser automation, built for sharing your logged-in browser state with your AI agents, like Codex or Claude Code,… *(★ 16.5k, MIT, drives Claude Code, Codex)*
- [Camofox Browser](https://github.com/jo-inc/camofox-browser) — Stealth headless browser for AI agents — bypass Cloudflare, bot detection, and anti-scraping. Drop-in Puppeteer/Playwright replacement *(★ 11.2k, MIT)*
- [BrowserSkill](https://github.com/Tencent/BrowserSkill) — Let AI agents use your real, logged-in browser without interrupting your work. CLI + extension for browser automation across any shell-capable AI agent *(★ 7.4k, MIT)*
- [Webcmd](https://github.com/agentrhq/webcmd) — Self-learning agent browser *(★ 2.6k, Apache-2.0)*
- [token-optimizer](https://github.com/alexgreensh/token-optimizer) — Find the ghost tokens. Fix them. Survive compaction. Avoid context quality decay *(★ 2.4k)*
- [Claude Code Tools](https://github.com/pchalasani/claude-code-tools) — Practical productivity tools for Claude Code, Codex-CLI, and similar CLI coding agents *(★ 2k, MIT, drives Claude Code, Codex)*
- [pi-mcp-adapter](https://github.com/nicobailon/pi-mcp-adapter) — Token-efficient MCP adapter for Pi coding agent *(★ 1.5k, MIT, drives Pi)*
- [codex-mcp-server](https://github.com/tuannvm/codex-mcp-server) — MCP server wrapper for OpenAI Codex CLI that enables Claude Code to leverage Codex's AI capabilities directly *(★ 636, drives Claude Code, Codex)* 💤 dormant
- [mcp-ssh-manager](https://github.com/bvisible/mcp-ssh-manager) — MCP SSH Server: 37 tools for remote SSH management · Claude Code & OpenAI Codex · DevOps automation, backups, database operations, health monitoring *(★ 493, MIT, drives Claude Code, Codex)*
- [mcp-linker](https://github.com/milisp/mcp-linker) — mcp store manager, add & syncs MCP server configurations across clients like Claude code, Cursor💡mcphub *(★ 328, AGPL-3.0, drives Claude Code, Cursor)*
- [claude-cmd](https://github.com/kiliczsh/claude-cmd) — Claude Code Commands Manager *(★ 313, MIT, drives Claude Code)*
- [kasetto](https://github.com/pivoshenko/kasetto) — 📼 Declarative AI agent environment manager, written in Rust *(★ 205)*
- [agent-lsp](https://github.com/blackwell-systems/agent-lsp) — MCP server that orchestrates language servers into agent-native workflows. 65 tools, 30 CI-verified languages *(★ 153, MIT)*
- [terminal-mcp](https://github.com/elleryfamilia/terminal-mcp) — A terminal emulator exposed via MCP for AI assistants *(★ 140, MIT)*
- [skill-optimizer](https://github.com/fastxyz/skill-optimizer) — Benchmark, evaluate, and optimize skills to ensure reliable performance across all LLMs *(★ 81, MIT)* 💤 dormant
- [skillreaper](https://github.com/thousandflowers/skillreaper) — Cut context bloat in your AI-agent stack: find and safely prune unused skills, MCP servers and subagents from real transcript evidence *(★ 58, MIT)*
- [AgentLint](https://github.com/0xmariowu/AgentLint) — The linter for your agent harness. Works with Claude Code, Codex, and Cursor *(★ 57, MIT, drives Claude Code, Codex, Cursor)*
- [AgentManager](https://github.com/kevinelliott/agentmanager) — CLI/TUI app to easily detect, manage, install, and update AI Agent CLI tools *(★ 36, MIT)*
- [Loadout](https://github.com/elleryfamilia/loadout) — Equip the right context for the job — named context kits for AI coding agents, auto-equipped per stack, machine, or task *(★ 32, MIT)*
- [ContextZip](https://github.com/jee599/contextzip) — ⚡ Cut Claude Code context 60-90%. Live stdout today, session-history compression coming v0.2 *(★ 26, drives Claude Code)*
- [Unship](https://github.com/mbenhard/unship) — Compare UI, copy, and states in your app with your coding agent *(★ 21, MIT)*
- [Agent Toolkit](https://github.com/ulises-jeremias/agent-toolkit) — 🛠️ Composable AI agent toolkit — skills, agents, loops, and MCP templates for Claude Code, Cursor, OpenCode, Copilot, Windsurf, and Pi *(★ 18, MIT, drives Claude Code, Copilot, Cursor, OpenCode, Pi, Windsurf)*
- [schliff](https://github.com/Zandereins/schliff) — Deterministic quality scorer for AI agent instruction files — 8-dimension scoring with security, multi-format (SKILL.md, CLAUDE.md, .cursorrules,… *(★ 17, MIT, drives Cursor)*
- [skillfold](https://github.com/byronxlg/skillfold) — Declarative skill manager for Claude Code and Codex. Declare skills in YAML, pin exact revisions in a lockfile, install them reproducibly into .claude/skills *(★ 13, MIT, drives Claude Code, Codex)*
- [agent-terminal](https://github.com/jasonkneen/agent-terminal) — Automate terminals for agents *(★ 12)* 💤 dormant
- [gate4agent](https://github.com/ZENG3LD/gate4agent) — Universal Rust wrapper for CLI AI agents (Claude Code, Codex, Gemini). PTY mirror and pipe/NDJSON modes with tokio broadcast fan-out *(★ 9, MIT, drives Claude Code, Codex, Gemini CLI)*
- [OSOP](https://github.com/Archie0125/osop-agent-rules) — Drop-in OSOP session logging for every AI coding agent — Cursor, Codex, Windsurf, Aider, Cline, Roo Code, Devin, Continue.dev, Copilot *(★ 5, drives Aider, Cline, Codex, Continue, Copilot, Cursor…)* 💤 dormant
- [linear-cli](https://github.com/phnx-labs/linear-cli) — Linear for you and your agents. Single-file Python CLI that drives Linear from the shell or a subagent. Zero deps, MIT *(★ 4, MIT)*
- [CodeVetter](https://github.com/Codevetter/codevetter) — Verify AI-generated code with execution evidence — deterministic, local-first verification for coding-agent changes via a macOS app, CLI, and MCP server *(★ 1, MIT)*
- [spec](https://github.com/Archie0125/osop-spec) — OSOP v1 JSON Schema, node types, examples and RFC - Open Standard Operating Process *(★ 1, Apache-2.0)*

## SDKs & Agent-Building Kits

*Libraries and kits for embedding or building your own agents/harnesses.*

- [Smol Developer](https://github.com/smol-ai/developer) — the first library to let you embed a developer agent in your own app! *(★ 12.2k, MIT)* 💤 dormant
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer) — Claude Engineer is an interactive command-line interface (CLI) that leverages the power of Anthropic's Claude-3.5-Sonnet model to assist with software… *(★ 11.2k)* 💤 dormant
- [adhd](https://github.com/UditAkhourii/adhd) — ADHD — a skill for coding agents. Tree-of-thought with pruning, built on the Claude & Codex Agent SDK. Fans out parallel divergent thoughts under different… *(★ 4.3k, MIT, drives Codex)*
- [Dexto](https://github.com/truffle-ai/dexto) — Agent harness and tookit for building AI agents and agentic applications. CLI and SDKs included *(★ 650)*
- [claude-code-openai-wrapper](https://github.com/RichardAtCT/claude-code-openai-wrapper) — OpenAI API-compatible wrapper for Claude Code *(★ 623, drives Claude Code)*
- [llm](https://github.com/graniet/llm) — A powerful Rust library and CLI tool to unify and orchestrate multiple LLM, Agent and voice backends (OpenAI, Claude, Gemini, Ollama, ElevenLabs...) with a… *(★ 365, MIT, drives Gemini CLI)*
- [claude-glm-wrapper](https://github.com/JoeInnsp23/claude-glm-wrapper) — A wrapper for claude code to be able to use the glm models with out having to lose logins or reset apis *(★ 116, MIT, drives Claude Code)* 💤 dormant
- [mcp-unreal](https://github.com/remiphilippe/mcp-unreal) — MCP server that gives AI coding agents (Claude Code, Cursor, etc.) full control over Unreal Engine 5.7 projects — headless builds & tests, Blueprint… *(★ 72, Apache-2.0, drives Claude Code, Cursor)* 💤 dormant

## Personal Assistant & Coworker Agents

*Always-on personal agents (OpenClaw-style) and general-purpose coworker agents.*

- [nanobot](https://github.com/HKUDS/nanobot) — Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with WebUI, tools, memory, MCP, multi-agent workflows, automation, and… *(★ 48.6k, MIT)*
- [QwenPaw](https://github.com/agentscope-ai/QwenPaw) — Your Personal AI Assistant; easy to install, deploy on your own machine or on the cloud; supports multiple chat apps with easily extensible capabilities *(★ 35.3k, Apache-2.0)*
- [zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) — Fast, small, and fully autonomous AI personal assistant infrastructure, any OS, any platform — deploy anywhere, swap anything 🦀 *(★ 32.9k, Apache-2.0)*
- [nanoclaw](https://github.com/nanocoai/nanoclaw) — A lightweight alternative to OpenClaw that runs in containers for security. Connects to WhatsApp, Telegram, Slack, Discord, Gmail and other messaging apps,,… *(★ 30.8k, MIT, drives OpenClaw)*
- [picoclaw](https://github.com/sipeed/picoclaw) — Tiny, Fast, and Deployable anywhere — automate the mundane, unleash your creativity *(★ 30k, MIT)*
- [OpenWorker](https://github.com/andrewyng/openworker) — Open-source desktop AI coworker that delivers finished work — security review with re-scanned fixes, cloud posture audits, triaged inboxes — from specialist… *(★ 18.3k, MIT)*
- [rowboat](https://github.com/rowboatlabs/rowboat) — AI coworker with memory and collaboration *(★ 18k, Apache-2.0)*
- [leon](https://github.com/leon-ai/leon) — 🧠 Leon is your open-source personal assistant *(★ 17.5k, MIT)*
- [ironclaw](https://github.com/nearai/ironclaw) — IronClaw is an Agent OS focused on privacy, security and extensibility *(★ 12.6k, Apache-2.0)*
- [Coworker](https://github.com/accomplish-ai/coworker) — Open source AI coworker that lives on your desktop. Formerly accomplish *(★ 10.9k)*
- [Cloudflare OS](https://github.com/cloudflare/cloudflare-os) — Agent workspace built on Cloudflare Workers for creating documents, building apps, and running agents with your company’s context and systems *(★ 10.1k, Apache-2.0)*
- [nullclaw](https://github.com/nullclaw/nullclaw) — Fastest, smallest, and fully autonomous AI assistant infrastructure written in Zig *(★ 8.1k, MIT)*
- [lobsterai](https://github.com/netease-youdao/LobsterAI) — Open-source, desktop-grade AI agent that gets real work done — data analysis, slides, docs, video & web research. Built on OpenClaw; runs tools on your real… *(★ 6.1k, MIT, drives OpenClaw)*
- [Octop](https://github.com/TencentCloud/Octop) — A smarter, self-hosted AI assistant — multi-user, multi-agent *(★ 5.1k, MIT)*
- [open-claude-cowork](https://github.com/composio-community/open-claude-cowork) — Open Source version of Claude Cowork with 500+ SaaS app integrations *(★ 4.4k, MIT)* 💤 dormant
- [OpenMausBot](https://github.com/milind-soni/OpenMausBot) — Open Source Alternative to Grok Bot with a virtual machine that bots can use *(★ 3.6k, Apache-2.0, drives Codex, Grok)*
- [MetaClaw](https://github.com/aiming-lab/MetaClaw) — 🦞 Just talk to your agent — it learns and EVOLVES 🧬 *(★ 3.5k, MIT)*
- [Rakazo](https://github.com/elie222/rakazo) — Open-source Grok Bot alternative. Choose your own model and sandbox *(★ 3k, Apache-2.0, drives Grok)*
- [denchclaw](https://github.com/DenchHQ/DenchClaw) — Migrate to dench.com if you're reading this. Fully Managed OpenClaw Framework for all knowledge work ever. CRM Automation and Outreach agents. The only… *(★ 1.7k, MIT, drives OpenClaw)*
- [row-bot](https://github.com/siddsachar/row-bot) — Row-Bot - Personal AI Sovereignty. A local-first AI assistant with integrated tools, a personal knowledge graph, voice, vision, shell, browser automation,… *(★ 1.5k, Apache-2.0)*
- [Ouroboros](https://github.com/razzant/ouroboros) — Ouroboros — self-creating AI agent. Born Feb 16, 2026 *(★ 1.4k, MIT)*
- [poco-claw](https://github.com/poco-ai/poco-claw) — A more beautiful and easier-to-use alternative to OpenClaw. It features a nicer Web UI, built-in IM support, a sandboxed runtime and channel-based team… *(★ 1.4k, MIT, drives Claude Code, OpenClaw)*
- [swarmclaw](https://github.com/swarmclawai/swarmclaw) — Open-source self-hosted AI agent runtime and multi-agent framework for autonomous agent swarms. Agent memory, MCP tools, schedules, delegation, and 23+ LLM… *(★ 681, MIT, drives Claude Code, Gemini CLI)*
- [taOS](https://github.com/jaylfc/taOS) — Self-hosted AI agent OS. Your memory, chat, agents, and files stay on hardware you own, offline by default, cloud by choice. Offline AI memory (taOSmd),… *(★ 550, AGPL-3.0, drives Pi)*
- [rho](https://github.com/mikeyobrien/rho) — An AI agent that stays running, remembers across sessions, and checks in on its own. macOS, Linux, Android. Built on Pi *(★ 372, MIT, drives Pi)* 💤 dormant
- [OpenInstinct](https://github.com/Merit-Systems/OpenInstinct) — iMessage personal assistant + password vault *(★ 364, MIT)*
- [iva](https://github.com/smixs/iva-agent) — AI assistant in Telegram that remembers everything and helps you run your life. Self-hosted in one command *(★ 220, MIT)*
- [lorca](https://github.com/egoist/lorca) — Imagine Telegram but single person, with agents, and end-to-end encrypted *(★ 167, GPL-3.0)*
- [ToFu](https://github.com/NiuTrans/ToFu) — Self-hosted AI assistant with tool use, multi-agent orchestration, coding copilot and a lightweight Flask + vanilla JS stack *(★ 149, MIT, drives Copilot)*
- [Overlay](https://github.com/LayerNorm/overlay-web) — The all-in-one platform for humans and agents to get work done *(★ 145, AGPL-3.0)*
- [lemon](https://github.com/z80dev/lemon) — BEAM-native platform for LLM agents: OTP-supervised per-run processes, pluggable engines and channels, contract-tested extension points, and a deterministic… *(★ 130, MIT)*
- [automata](https://github.com/sentientwave/automata) — Agent swarming organization system *(★ 113)* 💤 dormant
- [ghostclaw](https://github.com/b1rdmania/ghostclaw) — an AI that lives on your computer and does stuff for you. Public beta *(★ 93, MIT)* 💤 dormant
- [assistant](https://github.com/kcosr/assistant) — Panel-based personal assistant with a plugin architecture for productivity workflows. AI agents share a workspace of notes, lists and other panels with the… *(★ 90, drives Claude Code, Codex, Pi)*
- [claude-imprint](https://github.com/Qizhan7/claude-imprint) — Self-hosted AI agent system built on Claude Code. Multi-channel chat, persistent memory with semantic search, scheduled tasks, and a single-file dashboard *(★ 90, drives Claude Code)* 💤 dormant
- [agent-network](https://github.com/sleep2agi/agent-network) — 助力搭建你的数字 AI 员工军团 — 多 Agent 一行命令组网协作。Claude Code / Claude Agent SDK / Codex / Grok Build 4 runtime + 8+ 家 LLM（Anthropic / OpenAI / xAI / MiniMax / DeepSeek /… *(★ 74, Apache-2.0, drives Claude Code, Codex, DeepSeek, Grok Build, Kimi)*
- [Hivekeep](https://github.com/MarlBurroW/hivekeep) — Hivekeep is a self-hosted platform of autonomous, persistent personal AI agents. Your AI team. At home *(★ 63, MIT)*
- [lucinate](https://github.com/lucinate-ai/lucinate) — Terminal-native chat client for OpenClaw, Hermes, Ollama and OpenAI-compatible providers. A pure, beautiful terminal chat experience - connect to the… *(★ 11, Apache-2.0, drives Hermes, OpenClaw)*

## The Agents: CLIs & Harnesses These Clients Drive

*The coding agents and agent CLIs themselves — what most tools above wrap.*

- [OpenClaw](https://github.com/openclaw/openclaw) — The AI that really does things. Any OS. Any Platform. The lobster way. 🦞 *(★ 390.6k)*
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) — The agent that grows with you *(★ 249.2k, MIT)*
- [OpenCode](https://github.com/anomalyco/opencode) — The open source coding agent *(★ 210.2k, MIT)*
- [Claude Code](https://github.com/anthropics/claude-code) — Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks,… *(★ 148.2k)*
- [Codex CLI](https://github.com/openai/codex) — Lightweight coding agent that runs in your terminal *(★ 126.6k, Apache-2.0)*
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) — An open-source AI agent that brings the power of Gemini directly into your terminal *(★ 107.2k, Apache-2.0)*
- [Cline CLI](https://github.com/cline/cline) — Autonomous coding agent as an SDK, IDE extension, or CLI assistant *(★ 69.4k, Apache-2.0)*
- [Open Interpreter](https://github.com/openinterpreter/openinterpreter) — A coding agent for open models like Kimi K3 and GLM 5.3 *(★ 68.4k, Apache-2.0, drives Kimi)*
- [crewAI](https://github.com/crewAIInc/crewAI) — Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly,… *(★ 59.1k, MIT)*
- [Goose](https://github.com/aaif-goose/goose) — an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM *(★ 54.7k, Apache-2.0)*
- [Aider](https://github.com/Aider-AI/aider) — aider is AI pair programming in your terminal *(★ 49.2k, Apache-2.0)* 💤 dormant
- [Codewhale](https://github.com/Hmbown/Codewhale) — Open-source coding agent for your terminal, built in Rust and on a journey of continuous community improvement. Issues and PRs welcome *(★ 41k, MIT)*
- [Continue CLI](https://github.com/continuedev/continue) — open-source coding agent *(★ 36k, Apache-2.0)*
- [Reasonix](https://github.com/esengine/DeepSeek-Reasonix) — DeepSeek-native AI coding agent for your terminal. Engineered around prefix-cache stability — leave it running *(★ 35.7k, MIT, drives DeepSeek)*
- [OH-MY-PI](https://github.com/can1357/oh-my-pi) — ⌥ Coding agent with the IDE wired in. Built by Stencil Labs *(★ 33.4k, MIT)*
- [Deep Agents Code](https://github.com/langchain-ai/deepagents) — The batteries-included agent harness *(★ 29.8k, MIT)*
- [Crush](https://github.com/charmbracelet/crush) — Glamourous agentic coding for all 💘 *(★ 28.3k)*
- [Qwen Code](https://github.com/QwenLM/qwen-code) — An open-source AI coding agent that lives in your terminal *(★ 28.1k, Apache-2.0)*
- [Kilo Code CLI](https://github.com/Kilo-Org/kilocode) — Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with the most popular open source coding agent *(★ 27.4k, MIT, drives Kilo Code)*
- [Grok Build](https://github.com/xai-org/grok-build) — SpaceXAI's coding agent harness and TUI. Fullscreen, mouse interactive, extensible *(★ 27.1k, Apache-2.0)*
- [Roo Code CLI](https://github.com/RooCodeInc/Roo-Code) — Roo Code gives you a whole dev team of AI agents in your code editor *(★ 24.3k, Apache-2.0, drives Roo Code)* 📦 archived
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) — SWE-agent takes a GitHub issue and tries to automatically fix it, using your LM of choice. It can also be employed for offensive cybersecurity or… *(★ 20.4k, MIT)*
- [jcode](https://github.com/1jehuang/jcode) — The most RAM efficient harness *(★ 20.1k, MIT)*
- [Plandex](https://github.com/plandex-ai/plandex) — Open source AI coding agent. Designed for large projects and real world tasks *(★ 15.7k, MIT)* 💤 dormant
- [MiMo Code](https://github.com/XiaomiMiMo/MiMo-Code) — MiMo Code: Where Models and Agents Co-Evolve *(★ 13.5k, MIT)*
- [Codebuff](https://github.com/CodebuffAI/freebuff) — The free coding agent *(★ 12.8k, Apache-2.0)*
- [Trae Agent](https://github.com/bytedance/trae-agent) — Trae Agent is an LLM-based agent for general purpose software engineering tasks *(★ 12.1k, MIT, drives Trae)* 💤 dormant
- [Kimi CLI](https://github.com/MoonshotAI/kimi-cli) — [Archived] Legacy Python Kimi CLI, no longer maintained. Please use Kimi Code CLI: https://github.com/MoonshotAI/kimi-code *(★ 11.4k, Apache-2.0, drives Kimi)* 📦 archived
- [GitHub Copilot in the CLI](https://github.com/github/copilot-cli) — GitHub Copilot CLI brings the power of Copilot coding agent directly to your terminal *(★ 11.2k, drives Copilot)*
- [Claurst](https://github.com/Kuberwastaken/claurst) — Agentic Coding for Builders who Ship *(★ 10.3k, GPL-3.0)*
- [Kimi Code](https://github.com/MoonshotAI/kimi-code) — Kimi Code CLI  —  The Starting Point for Next-Gen Agents *(★ 7.7k, MIT, drives Kimi)*
- [ForgeCode](https://github.com/tailcallhq/forgecode) — AI enabled pair programmer for Claude, GPT, O Series, Grok, Deepseek, Gemini and 300+ models *(★ 7.6k, Apache-2.0, drives DeepSeek, Gemini CLI, Grok)*
- [OpenSquilla](https://github.com/TokenRhythm/opensquilla) — OpenSquilla — Token-Efficient AI Agent with same budget, higher intelligence density *(★ 7.1k, Apache-2.0)*
- [Kode CLI](https://github.com/shareAI-lab/Kode-CLI) — Kode CLI — Design for post-human workflows. One unit agent for every human & computer task *(★ 5.2k, Apache-2.0)*
- [Mistral Vibe](https://github.com/mistralai/mistral-vibe) — Minimal CLI coding agent by Mistral *(★ 5k, Apache-2.0)*
- [Command Code](https://github.com/CommandCodeAI/command-code) — Command Code AI — the best coding agent for open models *(★ 4k)*
- [Grok CLI](https://github.com/superagent-ai/grok-cli) — An open-source coding agent for the Grok API *(★ 3.5k, MIT, drives Grok)*
- [Devon](https://github.com/entropy-research/Devon) — Devon: An open-source pair programmer *(★ 3.5k, AGPL-3.0)* 💤 dormant
- [Letta Code](https://github.com/letta-ai/letta-code) — Stateful agents that are like people, with memory, identity, and the ability to learn and adapt *(★ 3.4k, Apache-2.0)*
- [AutoCodeRover](https://github.com/AutoCodeRoverSG/auto-code-rover) — A project structure aware autonomous software engineer aiming for autonomous program improvement. Resolved 37.3% tasks (pass@1) in SWE-bench lite and 46.2%… *(★ 3.1k)* 💤 dormant
- [Tau](https://github.com/huggingface/tau) — A Python port of Pi’s minimalist coding agent *(★ 2.9k, MIT, drives Pi)*
- [Atomic Agent](https://github.com/AtomicBot-ai/atomic-agent) — Atomic Agent is a local-first AI agent. Runs open-weight models on your own machine via llama.cpp *(★ 2.5k, MIT)*
- [Nanocoder](https://github.com/Nano-Collective/nanocoder) — An open coding agent for your terminal, built by a community collective rather than a company. Bring your own model, keep your code on your machine, and owe… *(★ 2.5k)*
- [open-codex](https://github.com/ymichael/open-codex) — Lightweight coding agent that runs in your terminal *(★ 2.4k, Apache-2.0)* 💤 dormant
- [BitFun](https://github.com/GCWing/OpenBitFun) — OpenBitFun combines a high-performance agent runtime written in Rust with a polished desktop application. It pairs the depth of a Code Agent with open,… *(★ 2.3k, MIT)*
- [Agentless](https://github.com/OpenAutoCoder/Agentless) — Agentless🐱:  an agentless approach to automatically solve software development problems *(★ 2.1k, MIT)* 💤 dormant
- [Amazon Q Developer CLI](https://github.com/aws/amazon-q-developer-cli) — ✨ Agentic chat experience in your terminal. Build applications using natural language *(★ 2k, Apache-2.0)*
- [Neovate Code](https://github.com/neovateai/neovate-code) — Neovate Code is a code agent to enhance your development. You can use it to generate code, fix bugs, review code, add tests, and more. You can run it in… *(★ 1.6k, MIT)* 💤 dormant
- [dirac](https://github.com/dirac-run/dirac) — Coding Agent singularly focused efficiency and context curation. Reduces API costs by 50-80% vs other agent AND improves the code quality at the same time.… *(★ 1.5k, Apache-2.0)*
- [VT Code](https://github.com/vinhnx/VTCode) — VT Code is an open-source Rust terminal coding agent *(★ 854, Apache-2.0)*
- [hax](https://github.com/OleksandrChekhovskyi/hax) — A minimalist, terminal-native coding agent written in C *(★ 819, MIT)*
- [Groq Code CLI](https://github.com/build-with-groq/groq-code-cli) — A highly customizable, lightweight, and open-source coding CLI powered by Groq for instant iteration *(★ 741, MIT)* 💤 dormant
- [RSI-Harness](https://github.com/CosmosMind-ai/RSI-Harness) — RSIH — versionable, shareable agent harness: Pi coding agent + Genome config layer *(★ 711, MIT, drives Pi)*
- [Tura](https://github.com/Tura-AI/tura) — Build agent that uses 80% less token and delivers better results *(★ 644, AGPL-3.0)*
- [agentty](https://github.com/1ay1/agentty) — AI pair programming in your terminal — one static binary, sub-ms startup, any model *(★ 611, MIT)*
- [claw-code-agent](https://github.com/HarnessLab/claw-code-agent) — Claw Code No Rust No TypeScript Only Python. Easy to work with. Fast to iterate. 🔥 Zero external dependencies 🔥 *(★ 546)*
- [g3](https://github.com/dhanji/g3) — experiments in goose *(★ 520, drives Goose)*
- [pool](https://github.com/poolsideai/pool) — pool is Poolside’s coding agent that runs in your terminal or integrates with any ACP-compatible editor *(★ 426)*
- [jules](https://github.com/gemini-cli-extensions/jules) — A Gemini CLI extension that allows you to use the Gemini CLI to orchestrate the Jules asynchronous agent to perform coding tasks like bug fixing,… *(★ 414, Apache-2.0, drives Gemini CLI)*
- [Coro Code](https://github.com/Blushyes/coro-code) — Open-source CLI coding agent, a free alternative to Claude Code. Generate, debug, and manage code seamlessly *(★ 369, drives Claude Code)* 💤 dormant
- [zot](https://github.com/patriceckhart/zot) — Yet another coding agent harness, lightweight and written in go *(★ 346, MIT)*
- [Mini-Kode](https://github.com/minmaxflow/mini-kode) — An educational AI coding agent CLI *(★ 307, MIT)* 💤 dormant
- [Auggie](https://github.com/augmentcode/auggie) — An AI agent that brings Augment Code's power to the terminal *(★ 281, drives Augment)*
- [CLI-only package](https://github.com/OpenHands/OpenHands-CLI) — Lightweight OpenHands CLI in a binary executable *(★ 260, MIT)*
- [nori-cli](https://github.com/tilework-tech/nori-cli) — A simple CLI for working with any agent *(★ 184, Apache-2.0)*
- [Octomind](https://github.com/Muvon/octomind) — Open-source AI coding agent and agent runtime: one binary, any model, MCP-native. Runs in terminal, CI, or as a daemon *(★ 144, Apache-2.0)*
- [openHarness](https://github.com/zhijiewong/openharness) — Open source local terminal cli with any LLM *(★ 101, MIT)* 💤 dormant
- [Codex Infinity](https://github.com/lee101/codex-infinity) — infinite coding agent *(★ 97, Apache-2.0)*
- [forge](https://github.com/automagik-dev/forge) — The Vibe Coding++™ platform - orchestrate multiple AI agents, experiment with isolated attempts, ship code you understand. Multi-agent kanban with MCP… *(★ 91, Apache-2.0, drives Vibe)* 💤 dormant
- [3code](https://github.com/capocasa/3code) — The Economical Coding Agent *(★ 87, MIT)*
- [San](https://github.com/genai-io/san) — Open-source terminal agent runtime. Lean context, native speed, open all the way down — in a single Go binary *(★ 80, Apache-2.0)*
- [Crab Code](https://github.com/lingcoder/crab-code) — 🦀 Open-source alternative to Claude Code, built from scratch in Rust. Agentic coding CLI — thinks, plans, and executes with any LLM. Compatible with Claude… *(★ 76, MIT, drives Claude Code)*
- [Keen Code](https://github.com/mochow13/keen-code) — A context-aware terminal-based coding agent written in Go. Supports multiple-providers, MCPs, Subagents, Agent Skills, controllable tool output retention,… *(★ 69, MIT)*
- [Claudex](https://github.com/l3tchupkt/Claudex) — Claudex is an open-source AI coding agent with multi-provider support (OpenAI, NIM, Ollama, and more), featuring a smart routing system, Telegram… *(★ 67, drives Claude Code)* 💤 dormant
- [picocode](https://github.com/jondot/picocode) — a minimal, Rust-based coding agent focused at CI workflows and small codemods, similar to Claude Code *(★ 61, MIT, drives Claude Code)* 💤 dormant
- [Forge](https://github.com/LucasDuys/forge) — Turn a one-line idea into a branch with tested, reviewed, committed code. The brainstorm-to-commit pipeline for Claude Code *(★ 56, MIT, drives Claude Code)*
- [Jazz](https://github.com/lvndry/jazz) — One agent. Every surface. Your rules *(★ 53, MIT)*
- [QQCode](https://github.com/qnguyen3/qqcode) — A lightweight CLI coding agent focused on speed, determinism, and developer control *(★ 53, Apache-2.0)* 💤 dormant
- [Smelt](https://github.com/leonardcser/smelt) — A fast, Lua-scriptable AI coding agent for the terminal *(★ 52, MIT)*
- [Zap](https://github.com/zap-coding-agent/zap-coding-agent) — ZAP is a terminal-first, local AI coding agent built in Rust. It uses AST-powered codebase indexing and lazy-loaded skills to completely eliminate prompt… *(★ 35)*
- [Binharic](https://github.com/CogitatorTech/binharic-cli) — A multi-provider AI coding agent with the persona of a Tech-Priest *(★ 19, MIT)* 💤 dormant
- [memcode](https://github.com/memcode-ai/memcode) — Open Source Coding Agent *(★ 17, MIT)*
- [Darce](https://github.com/AmerSarhan/darce-cli) — AI coding agent for your terminal. Reads, writes, edits code, runs commands. Any model. 14 kB *(★ 10)* 💤 dormant
- [Forge (Norvia Labs)](https://github.com/NorviaLabs/forge) — Go from idea to verified code without leaving the terminal—Forge unifies an AI agent, code editor, and shell in one focused workflow *(★ 7, MIT)*
- [Ferrum](https://github.com/ominiverdi/ferrum) — A small Rust-native Linux coding agent *(★ 4, MIT)*
- [ipsupport-code](https://github.com/ipsupport-llc/ipsupport-code) — A small self-learning coding agent for your own model — any OpenAI-compatible server, local (LLMTray, LM Studio, Ollama, vLLM) or cloud. Single static Go… *(★ 4, MIT)*
- [TheGitAI](https://github.com/thegitai/thegitai-cli) — Agentic AI coding tool for your terminal. Reads and searches your repository, edits files, runs commands, and verifies the change. Source-visible client *(★ 4)*
- [FetchCoder](https://github.com/fetchai/fetchcoder-releases) — Binary releases for FetchCoder - AI Coding Agent for the Terminal *(★ 2)* 💤 dormant
- [Amp](https://sourcegraph.com/amp)
- [Cortex Code CLI](https://www.snowflake.com/en/product/cortex-code/)
- [Cursor CLI](https://cursor.com/cli)
- [Junie CLI](https://junie.jetbrains.com)
- [Mentat CLI](https://mentat.ai/docs/cli)
- [minicode.fun](https://minicode.fun)
- [molt](https://github.com/solvyxtech/molt) — A coding agent that won't say done on a false claim. Verification on disk. Receipts for accepts and refusals. Terminal and desktop. OpenAI compatible or… *(Apache-2.0)*
- [Tabnine CLI](https://docs.tabnine.com/main/getting-started/tabnine-cli)
- [Yaw](https://yaw.sh)

## Dormant & Archived (Notable)

*Archived, renamed, or dormant projects worth knowing historically.*

- [1code](https://1code.dev/) — Orchestration layer for coding agents (Claude Code, Codex) *(★ 5.6k, Apache-2.0, drives Claude Code, Codex)* 📦 archived
- [Crystal](https://github.com/stravu/crystal) — (Crystal is now Nimbalyst) Run multiple Codex and Claude Code AI sessions in parallel git worktrees. Test, compare approaches & manage AI-assisted… *(★ 3.1k, MIT, drives Claude Code, Codex)* 💤 dormant
- [cashclaw](https://github.com/moltlaunch/cashclaw) — An autonomous agent that takes work, does work, gets paid, and gets better at it *(★ 1.2k, MIT)* 💤 dormant
- [clawe](https://github.com/getclawe/clawe) — Multi-agent coordination system: think Trello for OpenClaw agents *(★ 750, AGPL-3.0, drives OpenClaw)* 💤 dormant
- [lettabot](https://github.com/letta-ai/lettabot) — Archived - has been replaced by Letta Code channels/schedules! *(★ 326, Apache-2.0, drives Letta)* 📦 archived
- [Terragon](https://github.com/terragon-labs/terragon-oss) — This is the website formally known as Terragon Labs. It was a remote background agent orchestrator for running Claude Code, Codex, and other coding clis in… *(★ 259, Apache-2.0, drives Claude Code, Codex)* 💤 dormant
- [mercury](https://github.com/Michaelliv/mercury) — 🪽 Mercury — There are many claws, but this one is mine *(★ 144)* 📦 archived

---

## Contributing

Pull requests welcome. Entries must link a canonical source (repository or homepage) and state what it does in one factual sentence. Suggest the section; we'll re-bucket if needed. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright to this list.

*Generated from `data/agent-clients.json` in the agentlist.io repo by `scripts/generate-awesome.py`. Entries are editorial records, not endorsements; stars/licenses are point-in-time snapshots.*
