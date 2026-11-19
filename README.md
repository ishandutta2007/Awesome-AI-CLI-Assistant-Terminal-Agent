# Awesome-AI-CLI-Assistant-Terminal-Agent

## Top AI CLI Assistant & Terminal Agent Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Autonomous Terminal Agents, AI Command-Line Assistants, Shell Copilot Wrappers, Git Commit Generators & TUI Coding Harnesses*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI CLI Assistant & Terminal Agent**. These tools embed intelligent agents directly inside the command line—translating natural language into shell commands, autonomously executing multi-step terminal workflows, editing codebases via TUIs, diagnosing stack traces, and automating Git operations.



**Examples** include Warp AI, Amazon Q Developer CLI (formerly Fig), GitHub Copilot CLI, Termius AI, ShellGPT, Aicommits, Butterfly CLI, BitCLI, Oh My Zsh, and gptme/gptme (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for local-first terminal agents, autonomous CLI coding harnesses (`OpenCode`, `Codex CLI`, `Gemini CLI`, `Aider`, `Goose`), natural-language shell translators, and AI-powered terminal emulators — ideal for software engineers, DevOps/SREs, and sysadmins building sovereign CLI workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI developer tools and agentic coding ecosystem is estimated at **$7B–$10B** (projected to reach **$26B–$60B+** by the early 2030s at a ~25% CAGR). The market structure is **moderately concentrated at the infrastructure and IDE layer**—dominated by hyperscalers and platform giants (Microsoft/GitHub, Amazon, Anthropic)—while remaining **highly fragmented across specialized terminal agents, autonomous CLI workflows, and open-source tooling** where niche startups and community projects actively compete.



## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Pricing (Starting Paid Tier) | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[GitHub Copilot CLI](https://github.com)** | ~$3.77T Market Cap / ~$346B Revenue (Microsoft) | $10/month (Pro plan) | Free forever plan: 2,000 code completions/month and limited Copilot CLI chat interactions | Official GitHub command-line AI assistant and terminal agent capable of explaining shell commands, suggesting git/gh workflows, and executing repository tasks directly in the terminal. |
| **[Amazon Q Developer CLI](https://amazon.com)** | ~$2.85T Market Cap / ~$777B Revenue (Amazon) | $19/user/month (Pro plan) | Free forever plan: 50 agentic requests/month and 1,000 lines of code transformation/month | Cloud-backed AI command-line assistant providing IDE-style terminal autocomplete, natural-language-to-bash translation, and agentic codebase/AWS troubleshooting. |
| **[Anthropic Claude Code](https://anthropic.com)** | ~$1.5T Valuation / ~$81B ARR Run-rate | $20/month (Claude Pro plan; or pay-per-token API) | No free tier (free CLI download, but requires paid Pro subscription at $20/mo or Anthropic API key to run) | Agentic terminal coding and command-line assistant that understands entire repositories, executes shell commands, runs tests, and manages Git workflows via MCP and `SKILL.md`. |
| **[Atlassian Rovo Dev CLI](https://atlassian.com)** | ~$36B Market Cap / ~$6.5B Revenue (Atlassian) | $17.65/user/month (Cloud Standard tier with Rovo credits) | 30-day free trial on Rovo Dev Standard (2,000 credits/user/month); 14-to-30 day Cloud trial (25–70 Rovo credits/user/month). No perpetual free plan. | Enterprise cloud-connected terminal agent linking local CLI coding and shell automation directly with Jira tickets, Confluence docs, and Bitbucket pull requests. |
| **[Warp (Warp AI & Oz Agents)](https://warp.dev)** | ~$290M+ Valuation / ~$85M Funding | $20/month (Build plan; $18/mo billed annually) | Free forever plan: 0 managed AI agent credits (BYOK allowed for individuals/small teams ≤10), up to 30 cloud-synced conversations, unlimited core terminal | Modern GPU-accelerated terminal and Agentic Development Environment featuring natural-language command generation, multi-agent cloud/local execution, and team Warp Drive notebooks. |
| **[Wave Terminal Cloud Sync](https://waveterm.dev)** | Seed-stage Startup / Open-Core | ~$15–$20/month (Planned Pro Cloud Sync tier) | Free forever plan: 100% free and unlimited local terminal usage (BYOK for LLM providers & local Ollama models; no login required) | Hybrid open-core graphical terminal combining inline file/web previews with cloud-synced workspaces and integrated multi-model AI command blocks. |
| **[Termius AI](https://termius.com)** | ~$4M–$4.5M ARR / $4.1M Seed Funding | $10/month (Pro plan; billed annually) | Free forever plan (Starter): Single local device only, no multi-device cloud sync; 14-day free trial available for Pro | Cross-platform SSH client and cloud-synced DevOps workspace featuring built-in AI command generation, log diagnostics, and shared team snippet vaults. |
| **[Butterfish](https://butterfish.io)** | Open-Source / Pre-revenue | $0 (100% Free / Self-hosted BYOK) | Free forever: 100% free open-source tool with no software usage limits; users provide their own OpenAI/LLM API keys | Commercial-friendly AI shell wrapper that embeds persistent LLM context directly into standard `bash` and `zsh` sessions for seamless command suggestions and error explanations. |





## Open-Source GitHub Projects



- **[gptme (`gptme/gptme`)](https://github.com)**  

  Personal open-source (`MIT`) AI assistant and autonomous terminal agent equipped with shell execution, Python runtime, file editing, web browsing, vision, and persistent workspace memory.



- **[OpenCode (`sst/opencode` / `anomalyco/opencode`)](https://github.com)**  

  Popular open-source (`MIT`) terminal-native AI coding agent featuring a rich TUI, LSP diagnostics integration, multi-provider model support (Anthropic, OpenAI, Google, Ollama), and client/server architecture.



- **[OpenAI Codex CLI (`openai/codex`)](https://github.com)**  

  Official open-source (`Apache-2.0`) lightweight terminal coding agent built in Rust with OS-level sandboxing (`Seatbelt` / `Landlock`), multimodal input, and MCP server support.



- **[Gemini CLI (`google-gemini/gemini-cli`)](https://github.com)**  

  Official open-source (`Apache-2.0`) command-line AI agent from Google bringing Gemini models, built-in Google Search grounding, file/shell tools, and MCP extensions directly to the terminal.



- **[Aider (`Aider-AI/aider`)](https://github.com)**  

  Pioneering open-source (`Apache-2.0`) AI pair-programming CLI tool that maps entire Git repositories, edits multi-file codebases, runs linters/tests, and automatically commits changes.



- **[Goose (`block/goose`)](https://github.com)**  

  Extensible open-source (`Apache-2.0`) local-first AI developer agent from Block supporting autonomous shell execution, code editing, and Model Context Protocol (MCP) toolkits.



- **[ShellGPT (`TheR1D/shell_gpt`)](https://github.com)**  

  Widely adopted open-source (`MIT`) command-line productivity tool powered by LLMs for generating shell commands, code snippets, and interactive REPL sessions directly from the terminal.



- **[Aicommits (`Nutlope/aicommits`)](https://github.com)**  

  Lightweight open-source (`MIT`) CLI utility that inspects staged `git diff` changes and automatically generates Conventional Commits messages via OpenAI or compatible endpoints.



- **[Oh My Zsh (`ohmyzsh/ohmyzsh`)](https://github.com)**  

  Iconic open-source (`MIT`) community-driven Zsh configuration framework offering 300+ plugins, themes, and AI shell-assistant integrations (`zsh-autosuggestions`, `zsh-ai`) for terminal power users.



- **[Cline CLI / Plandex (`plandex-ai/plandex`)](https://github.com)**  

  Open-source (`AGPL-3.0`) terminal-based AI development engine designed for large, multi-file tasks with sandboxed cumulative diffs, versioned plan branches, and automated context loading.



- **[Warp / WezTerm / Alacritty / Ghostty (`ghostty-org/ghostty`)](https://github.com)**  

  Fast, native, GPU-accelerated open-source (`MIT`) terminal emulators serving as modern high-throughput host environments for TUI agents and CLI assistants.



- **[AIChat (`sigoden/aichat`)](https://github.com)**  

  All-in-one open-source (`MIT` / `Apache-2.0`) Rust CLI LLM tool featuring Shell Assistant mode, RAG document querying, custom AI agents, function calling, and 20+ model backends.



- **[Mods (`charmbracelet/mods`)](https://github.com)**  

  Unix-friendly open-source (`MIT`) CLI tool from Charm that brings AI pipelines to standard shell pipes (`stdin`/`stdout`), formatting Markdown, JSON, and code directly in the terminal.



- **[llm (`simonw/llm`)](https://github.com)**  

  Extensible open-source (`Apache-2.0`) CLI utility and Python library by Simon Willison for interacting with remote and local LLMs, logging SQLite prompt histories, and running tool plugins.



- **[kubectl-ai (`GoogleCloudPlatform/kubectl-ai`)](https://github.com)**  

  Open-source (`Apache-2.0`) AI-powered Kubernetes terminal assistant that translates natural-language intent into safe, verifiable `kubectl` commands and cluster diagnostics.



- **[Open Interpreter (`OpenInterpreter/open-interpreter`)](https://github.com)**  

  Open-source (`AGPL-3.0`) natural-language interface for computers enabling LLMs to write and execute Python, JavaScript, and Shell scripts locally in an interactive terminal loop.



- **[RA.Aid (`ai-christianson/RA.Aid`)](https://github.com)**  

  Open-source (`Apache-2.0`) LangGraph-powered CLI coding agent utilizing a three-stage Research, Planning, and Implementation architecture for autonomous terminal software engineering.



- **[crush (`charmbracelet/crush`)](https://github.com)**  

  Sleek open-source (`FSL-1.1-MIT`) terminal coding assistant built by Charm combining a polished Lip Gloss TUI with multi-model support, LSP awareness, and MCP extensibility.



### Additional Strong Open-Source Options



- **[Fabric (`danielmiessler/fabric`)](https://github.com)** and **[sgpt / tgpt (`aandrew-me/tgpt`)](https://github.com)** for composable Unix-pipe prompt patterns and zero-API-key terminal AI queries.

- **[Lazygit (`jesseduffield/lazygit`)](https://github.com)** and **[OpenCommit (`di-sukharev/opencommit`)](https://github.com)** for terminal Git workflows enhanced with AI commit message generation and diff review.

- **[k8sgpt (`k8sgpt-ai/k8sgpt`)](https://github.com)** and **[ops-agent / bpftrace AI tools](https://github.com)** for SRE-focused CLI log analysis, Linux system diagnostics, and Kubernetes triage.

- **[Ollama (`ollama/ollama`)](https://github.com)** and **[llama.cpp (`ggml-org/llama.cpp`)](https://github.com)** for running local open-weight coding models (`Qwen2.5-Coder`, `DeepSeek`, `Llama`) offline behind terminal agents.

- **[Model Context Protocol (MCP) CLI Servers](https://github.com)** for equipping terminal agents with standardized filesystem, Git, Docker, database, and browser tools.



**Frameworks for building custom systems**: Combine **gptme** or **OpenCode / Codex CLI** with **Ollama** (local inference), **Mods / AIChat** (Unix shell piping), **Aicommits** (Git automation), and **Model Context Protocol (MCP)** for sovereign, high-velocity terminal agent workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).
