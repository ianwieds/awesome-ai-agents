<p align="center"><!-- awesome:hero --><img src=".github/assets/hero.gif" width="100%" alt="Animated isometric scene: small agent bots at a browser, a code editor, a chart and a toolbox pass glowing tasks around a ring."><!-- /awesome:hero --></p>

<!-- awesome:title --><h1 align="center">Awesome AI Agents</h1><!-- /awesome:title -->

<p align="center"><!-- awesome:tagline -->A curated list of AI agent frameworks, coding agents, browser agents, tools, platforms and research.<!-- /awesome:tagline --></p>

<!-- awesome:badges -->
<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="contributing.md"><img src="https://img.shields.io/badge/PRs-welcome-8B5CF6" alt="PRs welcome"></a>
  <a href="https://github.com/ianwieds/awesome-ai-agents/commits/main"><img src="https://img.shields.io/github/last-commit/ianwieds/awesome-ai-agents?color=8B5CF6" alt="Last commit"></a>
</p>
<!-- /awesome:badges -->

Every link was checked when it was added, and every GitHub project on the list has had a commit in the last 12 months. Closed products are listed only while their site is live.

## Contents

- [Agent frameworks and SDKs](#agent-frameworks-and-sdks)
  - [General-purpose frameworks](#general-purpose-frameworks)
  - [Building blocks](#building-blocks)
  - [Low-code and visual builders](#low-code-and-visual-builders)
  - [Voice and realtime](#voice-and-realtime)
- [Coding agents](#coding-agents)
  - [IDE and editor agents](#ide-and-editor-agents)
  - [Terminal and desktop agents](#terminal-and-desktop-agents)
  - [Autonomous software engineers](#autonomous-software-engineers)
  - [Code review and testing](#code-review-and-testing)
  - [App builders](#app-builders)
  - [Workflows and orchestration](#workflows-and-orchestration)
- [Browser and computer-use agents](#browser-and-computer-use-agents)
  - [Browser agents](#browser-agents)
  - [Browser infrastructure](#browser-infrastructure)
  - [Desktop and computer use](#desktop-and-computer-use)
- [General-purpose agents](#general-purpose-agents)
- [Multi-agent and orchestration](#multi-agent-and-orchestration)
- [Domain agents](#domain-agents)
  - [Research](#research)
  - [Data and analytics](#data-and-analytics)
  - [Security](#security)
  - [DevOps and operations](#devops-and-operations)
  - [Other domains](#other-domains)
- [Memory](#memory)
- [Tools and protocols](#tools-and-protocols)
  - [Protocols](#protocols)
  - [Tool integrations](#tool-integrations)
- [Sandboxes and runtimes](#sandboxes-and-runtimes)
  - [Sandboxes](#sandboxes)
  - [Runtimes and deployment](#runtimes-and-deployment)
  - [Model gateways](#model-gateways)
- [Evaluation and observability](#evaluation-and-observability)
  - [Observability](#observability)
  - [Evaluation and testing](#evaluation-and-testing)
  - [Benchmarks](#benchmarks)
- [Safety and security](#safety-and-security)
- [Products and platforms](#products-and-platforms)
  - [Agent platforms](#agent-platforms)
  - [Assistants](#assistants)
  - [Chat interfaces](#chat-interfaces)
  - [Voice agents](#voice-agents)
  - [Business agents](#business-agents)
- [Research and learning](#research-and-learning)
  - [Courses and guides](#courses-and-guides)
  - [Papers and surveys](#papers-and-surveys)
  - [Paper lists](#paper-lists)
  - [Simulation](#simulation)
  - [Related lists](#related-lists)

## Agent frameworks and SDKs

### General-purpose frameworks

- [Adala](https://github.com/HumanSignal/Adala) - Agent framework for data labeling and processing tasks.
- [agent-express](https://github.com/agent-express-ai/agent-express) - Minimal agent framework in TypeScript.
- [agent-kit](https://github.com/socialrobot-io/agent-kit) - Agent kit with curated memory, gated learning and sandboxed execution.
- [agent-sdk-go](https://github.com/agenticenv/agent-sdk-go) - Go framework for durable agents whose state survives restarts.
- [AgentForge](https://github.com/DataBassGit/AgentForge) - Framework for building and testing agents across model providers.
- [AgentOS](https://github.com/smartcomputer-ai/agent-os) - Framework for building autonomous agents.
- [AgentsKit](https://github.com/AgentsKit-io/agentskit) - JavaScript toolkit for agents with React and terminal UIs.
- [AGiXT](https://github.com/Josh-XT/AGiXT) - Agent automation platform that chains commands across many model providers.
- [Agno](https://github.com/agno-agi/agno) - Python framework and runtime for agents, teams and workflows.
- [alive](https://github.com/marchantdev/alive) - Single-file loop for making an agent run autonomously.
- [Arachne](https://github.com/Strategic-Automation/arachne) - DSPy-based runtime that builds and runs an agent graph from a goal.
- [Atomic Agents](https://github.com/Eigenwise/atomic-agents) - Framework for building agents from small, interchangeable parts.
- [AutoChain](https://github.com/Forethought-Technologies/AutoChain) - Small framework for building and testing LLM agents.
- [Axar](https://github.com/axar-ai/axar) - Minimal TypeScript agent framework with Zod validation.
- [Bazed](https://github.com/sagentic-ai/sagentic-af) - Framework for building, running and scaling agents.
- [BindAI](https://github.com/BindBrain/BindAI) - Modular Python framework for agents, tools and workflows.
- [CerebrumKit](https://github.com/islomkhon/CerebrumKit) - Self-hosted starter kit for agents composed of skills and tools.
- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) - Python SDK from Anthropic for building agents on the Claude Code harness.
- [ConnectOnion](https://github.com/openonion/connectonion) - Python agent framework built around a CLI harness and tools.
- [Flow Weaver](https://github.com/synergenius-fw/flow-weaver) - Durable workflows compiled into TypeScript, with an MCP server.
- [fractal](https://github.com/plasma-ai/fractal) - Framework for hierarchical, recursive agent loops.
- [Google ADK](https://github.com/google/adk-python) - Google's code-first toolkit to build, evaluate and deploy agents.
- [Haystack](https://github.com/deepset-ai/haystack) - Pipeline framework from deepset for retrieval, RAG and agent applications.
- [Hector](https://github.com/verikod/hector) - Go platform for agents built on the A2A protocol.
- [Kite](https://github.com/beevr-labs/Kite) - Lightweight agent framework with safety, memory and several reasoning modes.
- [KodeAgent](https://github.com/barun-saha/kodeagent) - Minimal agent engine with ReAct and code-executing agents.
- [Lagent](https://github.com/InternLM/lagent) - Lightweight framework from InternLM for building LLM agents.
- [LangChain](https://github.com/langchain-ai/langchain) - Python and JavaScript framework for composing LLM apps and agents from modular parts.
- [LangChain JS](https://github.com/langchain-ai/langchainjs) - JavaScript and TypeScript version of LangChain.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for stateful, graph-based agents from the LangChain team.
- [LangGraph.js](https://github.com/langchain-ai/langgraphjs) - JavaScript version of LangGraph for graph-based agents.
- [LightAgent](https://github.com/wanxingai/LightAgent) - Lightweight Python framework for agents with tools, memory and guardrails.
- [llama-agents](https://github.com/run-llama/llama-agents) - LlamaIndex event-driven workflows for agent applications.
- [llama-cpp-agent](https://github.com/Maximilian-Winter/llama-cpp-agent) - Framework for tool use and structured output with llama.cpp models.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Framework for agents and workflows over your own documents and data.
- [LoongFlow](https://github.com/baidu-baige/LoongFlow) - Baidu framework that runs agents in plan, execute and summarize loops.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript framework for agents, workflows, RAG and evals.
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Framework for building agents on MCP with simple workflow patterns.
- [Melaya SDKs](https://github.com/melaya-labs/melaya) - SDKs for governed agents that work across business systems and browsers.
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - Microsoft framework for agents and multi-agent workflows in Python and .NET.
- [MS-Agent](https://github.com/modelscope/ms-agent) - ModelScope framework for agents that run complex tasks.
- [Nika](https://github.com/supernovae-st/nika) - Workflow language for agents with checked YAML graphs and traces.
- [Octochains](https://github.com/ahmadvh/octochains) - Python framework that runs isolated reasoning in parallel and merges the results.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's Python SDK for agents, handoffs, guardrails and tracing.
- [Promptise Foundry](https://github.com/promptise-com/Foundry) - Python framework for agents with controllable reasoning steps.
- [ProtoLink](https://github.com/nMaroulis/protolink) - Python agents that speak the A2A protocol natively.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Typed Python agent framework from the Pydantic team.
- [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent) - Agent framework built on Qwen models with tools, MCP and a code interpreter.
- [RasaGPT](https://github.com/paulpierre/RasaGPT) - Headless chatbot platform built on Rasa and LangChain.
- [Reactive Agents](https://github.com/tylerjrbuell/reactive-agents-ts) - TypeScript agent harness with controllable execution and observability.
- [selectools](https://github.com/johnnichev/selectools) - Python agent framework with guardrails, audit logs and cost tracking.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft SDK for adding agents and plugins to .NET, Python and Java apps.
- [ShaprAI](https://github.com/Scottcjn/shaprai) - Tooling that shapes base models into agents with set principles.
- [smolagents](https://github.com/huggingface/smolagents) - Hugging Face library for small agents that act by writing code.
- [Stately Agent](https://github.com/statelyai/agent) - State-machine-driven LLM agents built on XState.
- [Strands Agents](https://github.com/strands-agents/harness-sdk) - Open-source SDK from AWS for model-driven agents in Python and TypeScript.
- [trpc-agent-go](https://github.com/trpc-group/trpc-agent-go) - Go library for agents that combine graph workflows, tools, memory and A2A.
- [TypedAI](https://github.com/TrafficGuard/typedai) - TypeScript platform with chat, autonomous agents and software-developer agents.
- [uAgents](https://github.com/fetchai/uAgents) - Fetch.ai framework for decentralized agents.
- [Upsonic](https://github.com/Upsonic/Upsonic) - Python agent framework with MCP support and isolated tool execution.
- [Vectara-agentic](https://github.com/vectara/py-vectara-agentic) - Python library for agentic RAG assistants built on Vectara.
- [Vercel AI SDK](https://github.com/vercel/ai) - TypeScript toolkit for AI apps and agents, from the Next.js team.
- [VoltAgent](https://github.com/VoltAgent/voltagent) - TypeScript agent framework with a console for tracing and debugging.
- [yAgents](https://github.com/genlayerlabs/yeagerai-agent) - Agent that designs, codes and debugs new LangChain tools.

### Building blocks

- [Agentset](https://github.com/agentset-ai/agentset) - Open-source RAG platform with citations, deep research and an MCP server.
- [BAML](https://github.com/BoundaryML/baml) - Language for typed LLM functions and structured output.
- [DSPy](https://github.com/stanfordnlp/dspy) - Stanford framework for programming language model pipelines and optimizing prompts.
- [Guidance](https://github.com/guidance-ai/guidance) - Language for constraining and steering model output.
- [Instructor](https://github.com/567-labs/instructor) - Python library for structured outputs from LLMs.
- [LocalGPT](https://github.com/PromtEngineer/localGPT) - Chat with local documents using models that run on your machine.
- [Marvin](https://github.com/PrefectHQ/marvin) - Library for structured output and small AI functions in Python.
- [Outlines](https://github.com/dottxt-ai/outlines) - Library for structured generation that follows a schema or grammar.
- [PrivateGPT](https://github.com/zylon-ai/private-gpt) - API layer for private RAG, tools and MCP on local models.
- [RAGFlow](https://github.com/infiniflow/ragflow) - Open-source RAG engine with deep document parsing and agent features.
- [rote](https://github.com/trevhud/rote) - Compiles agent skills into fixed pipelines that need no LLM at run time.
- [Tambo](https://github.com/tambo-ai/tambo) - React SDK for interfaces that agents render at runtime.
- [TypeChat](https://github.com/microsoft/TypeChat) - Microsoft library for natural-language interfaces built on types.

### Low-code and visual builders

- [Activepieces](https://github.com/activepieces/activepieces) - Open-source automation builder with AI agents and many MCP servers.
- [AgentPilot](https://github.com/jbexta/AgentPilot) - Desktop app for creating and running AI workflows and agent teams.
- [Astron Agent](https://github.com/iflytek/astron-agent) - iFlytek's platform for building and running agentic workflows.
- [Botpress](https://github.com/botpress/botpress) - Platform and visual studio for building and deploying chat agents.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) - Generates agent apps from a prompt.
- [Dify](https://github.com/langgenius/dify) - Open-source platform for agentic workflows and RAG pipelines with a visual editor.
- [Giselle](https://github.com/giselles-ai/giselle) - Open-source visual builder for AI apps and agent workflows.
- [Heym](https://github.com/heymrun/heym) - Visual builder for agent workflows with execution inspection.
- [ix](https://github.com/kreneskyp/ix) - Agent platform with a visual workflow builder.
- [Langflow](https://github.com/langflow-ai/langflow) - Visual builder for agents and workflows, written in Python.
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation platform with AI agent nodes, self-hostable.
- [Rivet](https://rivet.ironcladapp.com) - Visual programming environment for building and debugging AI agent graphs.

### Voice and realtime

- [LiveKit Agents](https://github.com/livekit/agents) - LiveKit framework for realtime voice and video agents.
- [Pipecat](https://github.com/pipecat-ai/pipecat) - Python framework for realtime voice and multimodal agents.
- [Rasa](https://github.com/RasaHQ/rasa) - Open-source framework for text and voice conversational assistants.
- [Sayna](https://github.com/SaynaAI/sayna) - Voice layer that adds speech to existing agent frameworks.
- [voiceloop](https://github.com/todoforai/voiceloop) - Browser voice agent loop with interruption handling and streaming speech.

## Coding agents

### IDE and editor agents

- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS coding assistant with agents for code, infrastructure and security.
- [AutoDev](https://github.com/phodal/auto-dev) - Multi-agent coding platform built on Kotlin Multiplatform.
- [Cline](https://github.com/cline/cline) - Open coding agent for VS Code, JetBrains and the terminal.
- [Continue](https://github.com/continuedev/continue) - Open-source coding agent for VS Code, JetBrains and the CLI.
- [Cursor](https://cursor.com) - Code editor with built-in agents for multi-file edits.
- [Frontman](https://github.com/frontman-ai/frontman) - Agent that edits your web app from inside the browser and dev server.
- [GitHub Copilot](https://github.com/features/copilot) - GitHub's coding assistant with agent mode in the editor and on GitHub.
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - GitLab's AI agents across the software development lifecycle.
- [Google Antigravity](https://antigravity.google) - Google's agent-first development environment.
- [JetBrains AI](https://www.jetbrains.com/ai/) - Coding assistant and agent built into JetBrains IDEs.
- [Kilo Code](https://kilo.ai/) - Open-source coding agent for VS Code, JetBrains and the CLI.
- [Kiro](https://kiro.dev) - Agentic IDE built around specs that turn into tasks.
- [Mysti](https://github.com/DeepMyst/Mysti) - VS Code extension where Claude Code and Codex brainstorm and debate solutions.
- [onUI](https://github.com/onllm-dev/onUI) - Annotate any web UI and export structured context for coding agents.
- [Sourcegraph Cody](https://sourcegraph.com/cody) - Coding assistant that pulls context from large codebases.
- [Tabby](https://github.com/TabbyML/tabby) - Self-hosted coding assistant you can run on your own GPU.
- [UIZZE](https://github.com/uizze/uizze) - Design skills and references that help coding agents build better UI.

### Terminal and desktop agents

- [Aider](https://github.com/Aider-AI/aider) - Terminal pair programmer that edits code in your git repository.
- [Aster](https://github.com/Zfinix/aster) - Local-first terminal coding agent with tools, permissions, memory and skills.
- [Autohand Code CLI](https://github.com/autohandai/code-cli) - Terminal coding agent with many tools and providers that refines its own skills.
- [Claude Code](https://code.claude.com/docs) - Anthropic's agentic coding tool for the terminal, IDE and web.
- [Codex CLI](https://github.com/openai/codex) - OpenAI's open-source coding agent for the terminal.
- [DSH Studio](https://github.com/Moresyl/dsh-studio) - Desktop harness for DeepSeek models built with Rust and Tauri.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source terminal agent for Gemini models.
- [gptme](https://github.com/gptme/gptme) - Terminal agent with local tools that writes code, runs commands and browses.
- [Keen Code](https://github.com/mochow13/keen-code) - Go terminal coding agent with MCP, subagents and skills.
- [Nanocoder](https://github.com/Nano-Collective/nanocoder) - Community-built terminal coding agent for local or hosted models.
- [Nexus-Agent](https://github.com/parkain707/nexus-agent) - Autonomous coding agent with a TUI and a web visualizer.
- [Octomind](https://github.com/Muvon/octomind) - Model-agnostic coding agent and runtime shipped as one binary.
- [Open Interpreter](https://github.com/openinterpreter/openinterpreter) - Agent that runs code on your computer from natural-language requests.
- [OpenBitFun](https://github.com/GCWing/OpenBitFun) - Rust agent runtime with a desktop app and CLI for coding.
- [OpenCode](https://github.com/anomalyco/opencode) - Open-source terminal coding agent that works with many model providers.
- [OpenVibe](https://github.com/vitalops/openvibe) - Python coding agent modeled on OpenCode (formerly LoopGPT).
- [Orca](https://github.com/echoVic/orca-agent) - Coding agent built around DeepSeek models.
- [PI-Desktop](https://github.com/vastsa/PI-Desktop) - Local-first desktop app for coding agents, built on Electron and Rust.
- [Plandex](https://github.com/plandex-ai/plandex) - Terminal coding agent built for large, multi-file tasks.
- [Superagent for Mac](https://github.com/pungme/superagent-desktop) - Desktop home for Claude Code or Codex with chat and a local browser.
- [Tura](https://github.com/Tura-AI/tura) - Coding agent that runs locally with command-line, terminal and graphical front ends.
- [WinkTerm](https://github.com/Cznorth/winkterm) - AI terminal that types commands straight into your own shell session.
- [Zaru](https://github.com/100monkeys-ai/zaru-cli) - Pre-alpha Rust terminal harness that runs tools under a permission model.

### Autonomous software engineers

- [Alfred](https://github.com/luminik-io/alfred) - Self-hosted runtime that picks up GitHub issues and opens reviewed pull requests.
- [Devin](https://devin.ai) - Cognition's autonomous software engineer that works in its own cloud environment.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) - Multi-agent system that turns requirements into working software with DevOps tools.
- [Dosu](https://dosu.dev/) - Agent that answers repository questions and keeps documentation current.
- [Ellipsis](https://ellipsis.dev/) - Managed cloud agents that review code and fix bugs.
- [Factory](https://factory.com/) - Agents ("Droids") that build, test and ship software end to end.
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot) - Agent that builds apps step by step with the developer in the loop.
- [Maige](https://github.com/RubricLab/maige) - Runs plain-language workflows on a codebase, such as issue triage.
- [OpenHands](https://github.com/OpenHands/OpenHands) - Open platform for autonomous coding agents, run locally or in the cloud.
- [Orbi](https://github.com/orbi-build/orbi) - Self-hosted agent that turns labeled GitHub issues into reviewed pull requests.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - Research agent that attempts to fix a given GitHub issue on its own.

### Code review and testing

- [agent-qa](https://github.com/vostride/agent-qa) - QA agent that writes and runs tests from plain-language descriptions.
- [BrowserBash](https://github.com/PramodDutta/browserbash) - CLI and MCP server that runs browser tests written in plain English in Chrome.
- [CodeRabbit](https://coderabbit.ai/) - AI reviewer that comments on pull requests line by line.
- [ContextQA](https://contextqa.com/) - Test automation platform with agents that write and run tests.
- [DOS](https://github.com/anthony-chaudhary/dos-kernel) - Checks a coding agent's claims about what it shipped against git.
- [Kusho](https://kusho.ai/) - Agent that generates and runs API tests.
- [Lians](https://github.com/Lians-ai/Lians) - Runs real checks and records proof that a coding agent's task is done.
- [OpenCodeReview](https://github.com/alibaba/open-code-review) - Alibaba's code review tool that mixes fixed checks with LLM review.
- [PR-Agent](https://github.com/The-PR-Agent/pr-agent) - Open-source pull request reviewer that describes and comments on changes.
- [Qodo](https://www.qodo.ai/) - Code review agent that checks pull requests against the codebase.
- [ReviewCerberus](https://github.com/Kirill89/reviewcerberus) - Code review tool that writes reports on git branch diffs.
- [swarm-orchestrator](https://github.com/moonrunnerkc/swarm-orchestrator) - Runs project checks and records evidence for AI-written changes.
- [Test Driver](https://testdriver.ai/) - AI agent for QA and code review on GitHub.
- [Tusk](https://usetusk.ai/) - Testing agent that writes unit, API and integration tests.

### App builders

- [Bolt.new](https://bolt.new) - Builds and runs full-stack web apps from a prompt in the browser.
- [Dyad](https://github.com/dyad-sh/dyad) - Local, open-source app builder that runs on your own machine.
- [Fragments](https://github.com/e2b-dev/fragments) - E2B template for apps generated entirely by AI.
- [GitWit](https://www.gitwit.dev/) - Browser-based tool that writes and runs code from prompts.
- [Lovable](https://lovable.dev) - Builds and deploys web apps from a chat conversation.
- [Makedraft](https://makedraft.com/) - Generates and edits HTML components from text prompts.
- [PlayCode Agent](https://playcode.io) - Browser-based tool that turns plain English into running web apps.
- [Replit Agent](https://replit.com) - Builds and deploys full-stack apps from a prompt.
- [v0](https://v0.app/) - Vercel's app builder that turns prompts into React apps.

### Workflows and orchestration

- [Agent 007](https://github.com/bill10/agent-007) - Web terminals and parallel worktrees for Claude Code and Codex.
- [Agent Coordinator](https://github.com/alanhoff/agent-coordinator) - Codex skill that tracks a large task as a versioned graph of work items.
- [Agent Teams AI](https://github.com/777genius/agent-teams-ai) - Desktop app where coding agents take tasks, message and review each other.
- [agent-manager](https://github.com/YoanWai/agent-manager) - Terminal dashboard for coding agents with worktrees and diff review.
- [AgentsMesh](https://github.com/AgentsMesh/AgentsMesh) - Platform for scheduling and isolating many coding agents across machines.
- [AGX](https://github.com/ramarlina/agx) - Keeps coding agents working as a standing team with objectives and memory.
- [AionUi](https://github.com/iOfficeAI/AionUi) - Desktop cowork app for OpenClaw, Claude Code, Codex and other CLI agents.
- [AIWG](https://github.com/jmagly/aiwg) - Specialist agents and structured workflows for AI-assisted software work.
- [amux](https://github.com/mixpeek/amux) - Control plane for running Codex, Claude Code and Gemini sessions in parallel.
- [Bernstein](https://github.com/sipyourdrink-ltd/bernstein) - Orchestrator that enforces declarative rules on teams of coding agents.
- [Caliber](https://github.com/caliber-ai-org/ai-setup) - Generates and syncs agent config files such as AGENTS.md for each project.
- [Cate](https://github.com/0-AI-UG/cate) - Zoomable canvas workspace with editor, terminal and browser panels.
- [clideck](https://github.com/rustykuntz/clideck) - Dashboard for running and coordinating several CLI agents at once.
- [codex-profiles](https://github.com/Ducksss/codex-profiles) - Separate named profiles for OpenAI Codex without copying tokens.
- [CompozyOS](https://github.com/compozy/compozy) - Runs your existing agent CLIs with schedules, shared memory and approvals.
- [Coven](https://github.com/OpenCoven/coven) - Local runtime that keeps coding agent sessions scoped to a project with durable state.
- [ctop](https://github.com/aakashadesara/ctop) - Terminal process viewer for running coding agents.
- [Cursor AI Automated Team](https://github.com/joinwell52-AI/joinwell52) - Four-role agent team (PM, dev, ops, QA) that runs inside Cursor.
- [Dorothy](https://github.com/Charlie85270/Dorothy) - Desktop app for running and managing several coding agents at once.
- [Everything OpenAI Codex](https://github.com/mturac/everything-openai-codex) - Workflow kit for OpenAI Codex with agents, skills, hooks, memory and checks.
- [harness-starter-kit](https://github.com/harnessworks/harness-starter-kit) - Prompt-first starter kit for safer coding agent workflows.
- [hcom](https://github.com/aannoo/hcom) - Lets agents in different terminals send messages to, observe and launch one another.
- [House Party Protocol](https://github.com/rusharlabs/house-party-protocol) - Team harness for Codex and Claude Code that counts only proven work as done.
- [Kodo](https://github.com/ikamensh/kodo) - Orchestrator for Claude Code, Cursor, Codex and Gemini.
- [LoopTroop](https://github.com/looptroop-ai/LoopTroop) - Local orchestrator for coding agents with council planning and retry loops.
- [Maestro](https://github.com/RunMaestro/Maestro) - Desktop command center for running many agent sessions side by side.
- [Maestro Orchestrate](https://github.com/josstei/maestro-orchestrate) - Specialist subagents and parallel runs for Claude Code, Codex and Gemini CLI.
- [n3rv](https://github.com/juanmanueldaza/n3rv) - Memory, skills and subagent dispatch for OpenCode agents.
- [Okto-Pulse](https://github.com/OktoLabsAI/okto-pulse) - Spec-driven workbench with gates and a knowledge graph for coding agents.
- [OpenSepia](https://github.com/CelaenoIndustry/OpenSepia) - Nine Claude agents that run as an agile team through plan, code, review and deploy.
- [Opus Manager](https://github.com/yanauto/opus-manager) - Claude skill that delegates to cheaper CLIs and checks what they return.
- [ORCH](https://github.com/oxgeneral/ORCH) - Terminal tool for running a team of coding agents in parallel.
- [Ordewell](https://github.com/ordewell/ordewell) - Splits one goal into an ordered task plan for coding agents.
- [Stoneforge](https://github.com/stoneforge-ai/stoneforge) - Dashboard and runtime for coordinating coding agents from the web.
- [Sudarshan](https://github.com/Suraj1235/sudarshan-superharness) - Deterministic, resumable multi-agent harness for coding work.
- [SVRF](https://github.com/nybarius/SVRF) - Merge queue for swarms of coding agents.
- [Tale](https://github.com/tale-project/tale) - Run coding agents in persistent sandboxes with task delegation and shared review.
- [TeDDy](https://github.com/atte500/TeDDy) - Markdown harness that steers coding agents through TDD and vertical slices.
- [Vicoa](https://github.com/vicoa-ai/vicoa) - Runs coding agents in parallel worktrees from desktop, mobile or a server.
- [workkit](https://github.com/ITW-Creative-Works/workkit) - Claude Code plugin that runs GitHub Issues as a spec-to-ship agent pipeline.
- [YYLO](https://github.com/yylo-dev/yylo) - CLI for orchestrating coding agents.
- [zeroshot](https://github.com/the-open-engine/zeroshot) - Orchestrator that pairs a coding agent with an independent verifier.

## Browser and computer-use agents

### Browser agents

- [Agent-E](https://github.com/EmergenceAI/Agent-E) - Web automation agent built on AutoGen that drives the browser for you.
- [Browser Use](https://github.com/browser-use/browser-use) - Python library that lets agents control a real browser.
- [ChatGPT agent](https://openai.com/index/introducing-chatgpt-agent/) - ChatGPT mode that browses, fills forms and uses tools for you.
- [ChatGPT Atlas](https://chatgpt.com/atlas) - OpenAI browser with ChatGPT built in and an agent mode for web tasks.
- [Claude in Chrome](https://claude.com/claude-in-chrome) - Claude extension that reads and acts on pages in Chrome.
- [Dia](https://diabrowser.com) - Browser with an assistant built into tabs and pages.
- [Fellou](https://fellou.ai) - Agentic browser for deep search and automation.
- [Google Project Mariner](https://deepmind.google/technologies/project-mariner/) - Google DeepMind's browser agent prototype.
- [Lumen](https://github.com/omxyz/lumen) - Vision-first browser agent with deterministic replay that repairs itself.
- [Sentius](https://www.sentius.ai/) - Assistant that operates the browser to complete research tasks.
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Automates browser workflows with vision models and LLM planning.
- [SLICC](https://github.com/ai-ecoverse/slicc) - Agent runtime inside the browser with a shell, virtual filesystem and sub-agents.

### Browser infrastructure

- [Actionbook](https://github.com/actionbook/actionbook) - Lets agents reach pages behind logins and paywalls.
- [Airtop](https://airtop.ai) - Cloud browsers that agents can drive across apps and sites.
- [Amazon Nova Act](https://aws.amazon.com/nova/act/) - AWS service and SDK for agents that carry out actions in web browsers.
- [Browserbase](https://browserbase.com) - Cloud headless browsers for agents.
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Open-source crawler that turns websites into clean Markdown for LLMs.
- [Firecrawl](https://github.com/firecrawl/firecrawl) - Web scraping and crawling API that feeds clean data to agents.
- [invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) - Playwright MCP server that browses with a stealth Firefox build.
- [invisible-playwright](https://github.com/feder-cr/invisible_playwright) - Stealth Playwright build that avoids bot detection.
- [Notte](https://github.com/nottelabs/notte) - Hosted browsers and web automation tooling for agents.
- [Plasmate](https://github.com/plasmate-labs/plasmate) - Browser engine that turns HTML into a structured model for agents.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's MCP server that lets agents drive a browser through Playwright.
- [Stagehand](https://github.com/browserbase/stagehand) - Browser automation SDK that mixes code with natural-language actions.
- [Steel Browser](https://github.com/steel-dev/steel-browser) - Browser API and sandbox for agents that you can host yourself.
- [Webcmd](https://github.com/agentrhq/webcmd) - Learns how to navigate a site once, then replays it as fixed CLI commands.

### Desktop and computer use

- [Agent S](https://github.com/simular-ai/Agent-S) - Open framework for agents that use a computer like a person.
- [Claude Computer Use](https://platform.claude.com/docs/en/agents-and-tools/tool-use/computer-use-tool) - Anthropic's tool for letting Claude operate a desktop through screenshots.
- [Desktop Control](https://github.com/yaroshevych/desktopctl) - macOS computer-use tool and CLI for agents.
- [Fazm](https://github.com/mediar-ai/fazm) - Voice-driven computer-use agent for macOS.
- [jevme](https://github.com/danielyedaniel/jevme) - Voice agent that acts in any macOS app while you talk.
- [Moching](https://github.com/moching-ai-dev/moching) - Agent that controls a whole PC through screen perception and many tools.
- [UFO](https://github.com/microsoft/UFO) - Microsoft agent that operates Windows apps through their user interface.

## General-purpose agents

- [Aeon](https://github.com/aeonfun/aeon) - Agent that works unattended inside GitHub Actions and drives coding CLIs.
- [Atomic Agent](https://github.com/AtomicBot-ai/atomic-agent) - Local-first agent that uses open-weight models via llama.cpp on your machine.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Platform for building and running continuous autonomous agents, from the early agent wave.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - Small task-management agent that sparked many early autonomous-agent projects.
- [ClaudeClaw](https://github.com/sbusso/claudeclaw) - Uses Claude to run OpenClaw-style personal agents.
- [CorvinOS](https://github.com/CorvinLabs/CorvinOS) - Self-hosted agent OS that connects coding agents to chat apps.
- [CUGA](https://github.com/cuga-project/cuga-agent) - IBM-backed generalist agent harness for web and API tasks in the enterprise.
- [ENZO](https://github.com/theguysudo/ENZO) - Self-hosted workspace where agents use skills and tools such as Gmail and Calendar.
- [EvoFlux](https://github.com/evoelsewhere/evoflux) - Local-first workspace where agents code, research and automate the browser.
- [FutureOS](https://github.com/futuregene/future-os) - One agent across terminal, desktop, mobile and chat apps, with a Rust core.
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) - Personal agent from Nous Research that builds skills and memory as it works.
- [Hivekeep](https://github.com/MarlBurroW/hivekeep) - Self-hosted group of long-lived personal agents that remember and build tools.
- [MateClaw](https://github.com/mateaix/mateclaw) - Personal agent with multi-agent orchestration, MCP, skills and memory.
- [nanobot](https://github.com/HKUDS/nanobot) - Small self-hosted personal agent in Python with tools, memory and MCP.
- [Octopal](https://github.com/pmbstyle/Octopal) - Local agent platform that delegates work to isolated workers with approvals.
- [Oh My Hermes](https://github.com/rlaope/oh-my-hermes) - Plugin pack for Hermes Agent with coding tools, memory and workflows.
- [OpenAgent](https://github.com/the-open-agent/openagent) - Self-hosted assistant that combines RAG with computer, browser and coding tools.
- [OpenClaw](https://github.com/openclaw/openclaw) - Self-hosted personal assistant that acts through chat apps, tools and schedules.
- [openclaw-starter](https://github.com/feralghost/openclaw-starter) - Starter template for a self-hosted OpenClaw agent with memory and a task board.
- [OpenHuman](https://github.com/tinyhumansai/openhuman) - Agent harness in Rust that aims to keep cost and latency low.
- [OpenManus](https://github.com/FoundationAgents/OpenManus) - Open-source general agent that plans and uses tools in a sandbox.
- [OpenPaw](https://github.com/daxaur/openpaw) - Sets up Claude Code as a personal assistant with everyday skills.
- [Openwork](https://github.com/accomplish-ai/coworker) - Open-source desktop coworker that runs tasks on your files and apps.
- [Orkas](https://github.com/Orkas-AI/Orkas) - Local-first desktop app where a lead model directs specialist sub-agents.
- [Ouroboros (Q00)](https://github.com/Q00/ouroboros) - Self-improving agent system with gated evaluation and budgets.
- [Ouroboros (razzant)](https://github.com/razzant/ouroboros) - Self-modifying agent with a durable identity and reviewed changes.
- [PersonalJarvis](https://github.com/PersonalJarvis/PersonalJarvis) - Local voice assistant that runs your agents and coding CLIs.
- [Screenpipe](https://github.com/screenpipe/screenpipe) - Records your screen and audio locally so agents can use your history.
- [Talon](https://github.com/thefalconry/talon) - Agent harness with pluggable backends for chat apps such as Telegram and Discord.
- [Thursday](https://github.com/cgoinglove/thursday-agent) - Voice assistant that hands work to bots in a browser, shell and your files.
- [TITAN](https://github.com/Djtony707/TITAN) - Open-source system for autonomous work with tools, memory and approvals.
- [TrashClaw](https://github.com/Scottcjn/trashclaw) - Zero-dependency local agent that runs on old hardware.
- [XAgent](https://github.com/OpenBMB/XAgent) - OpenBMB autonomous agent for complex tasks with a planner and tool server.

## Multi-agent and orchestration

- [5dive](https://github.com/5dive-ai/5dive) - Hosts named agents on your own machine and arranges them in an org chart.
- [AG2](https://github.com/ag2ai/ag2) - Community-run continuation of AutoGen for building multi-agent systems.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - Framework for agent teams with defined roles and communication flows.
- [Agent Platform](https://github.com/Ace-li521/agent-platform) - Lightweight platform that routes requests between agents over HTTP and JSON.
- [Agent Squad](https://github.com/2FastLabs/agent-squad) - Framework that routes conversations across multiple agents.
- [Agent Swarm](https://github.com/desplega-ai/agent-swarm) - Self-hosted system that runs a team of agents for a company.
- [Agentlas OS](https://github.com/agentlas-ai/Agentlas-OS) - Hub of specialist agents with a temporary orchestrator for each task.
- [Agents Squads](https://github.com/agents-squads/squads-cli) - CLI for managing squads of agents with goals, memory and a dashboard.
- [AgentScope](https://github.com/agentscope-ai/agentscope) - Multi-agent framework with visual tracing and developer tooling.
- [AnimaWorks](https://github.com/xuiltul/animaworks) - Defines an organization of agents as code with memory that consolidates.
- [auto-co](https://github.com/NikitaDmitrieff/auto-co-meta) - Loop of agents that runs a small software company around the clock.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft framework for multi-agent conversations and agentic apps.
- [CAMEL](https://github.com/camel-ai/camel) - Multi-agent framework and research community for role-playing agents.
- [ChatDev](https://github.com/OpenBMB/ChatDev) - Multi-agent framework that simulates a software company building programs.
- [claude-consensus](https://github.com/tonydzi/claw-consensus) - Consensus protocol that keeps agents on several machines in agreement.
- [ClawFleet](https://github.com/clawfleet/ClawFleet) - Deploys a fleet of OpenClaw or Hermes agents on your own machine.
- [CommonGround Kernel](https://github.com/Intelligent-Internet/CommonGround) - Postgres-backed shared work record for teams of agents and people.
- [Corellis](https://github.com/CorellisOrg/Corellis) - Scales OpenClaw from one assistant to a coordinated fleet with shared memory.
- [Cortex (agentweave)](https://github.com/agentweave/cortex) - Coordination layer that acts as a chief of staff for your agents.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Python framework for teams of role-based agents that work on shared tasks.
- [cstack](https://github.com/srf6413/cstack) - Pattern for persistent agents built on Claude Cowork, Notion and MCP.
- [EvoAgentX](https://github.com/ANative-Lab/EvoAgentX) - Framework that evolves and optimizes agent workflows automatically.
- [Flock](https://github.com/whiteducksoftware/flock) - Declarative multi-agent system built on a blackboard pattern.
- [Hive](https://github.com/aden-hive/hive) - Harness for running multi-agent systems in production.
- [Hivemoot](https://github.com/hivemoot/hivemoot) - Framework for agent teams that build software on GitHub with roles and governance.
- [KaibanJS](https://github.com/kaiban-ai/KaibanJS) - JavaScript framework for multi-agent systems managed on a Kanban board.
- [Langroid](https://github.com/langroid/langroid) - Python framework for multi-agent programming.
- [LLMling-Agent](https://github.com/phil65/agentpool) - Hub that configures and runs many agents, including ACP and Claude Code agents.
- [Markus](https://github.com/markus-global/markus) - Platform for building agent teams with roles and a manager view.
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) - Multi-agent framework that assigns software-company roles to cooperating agents.
- [Mission Control](https://github.com/MeisnerDan/mission-control) - Task board for a solo founder who hands work to agents.
- [NarraNexus](https://github.com/NetMindAI-Open/NarraNexus) - Framework for groups of agents that work through shared interaction.
- [Okto-Nexus](https://github.com/OktoLabsAI/okto-nexus) - Local MCP hub for agent teams with messaging, handoffs and governance.
- [Open Multi-Agent](https://github.com/open-multi-agent/open-multi-agent) - TypeScript runtime you host yourself, with approval steps and auditable run logs.
- [OpenAcme](https://github.com/sandydasari/openacme) - Workforce platform of role-based agents with tasks, MCP and a web UI.
- [OpenAgents](https://github.com/openagents-org/openagents) - Network where agents and people collaborate in shared spaces.
- [OpenAI Swarm](https://github.com/openai/swarm) - OpenAI's educational library for lightweight agent handoffs and routines.
- [OpenBot](https://github.com/regnull/openbot) - Self-hosted platform for a team of bots with tools, memory and handoffs.
- [Paperclip](https://github.com/paperclipai/paperclip) - Open-source app for running a company of agents with goals and budgets.
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) - Low-code multi-agent framework for building self-improving agent teams.
- [pydantic-collab](https://github.com/Unfold-Security/pydantic-collab) - Declarative multi-agent orchestration on Pydantic AI.
- [Quorum](https://github.com/Detrol/quorum-cli) - CLI that runs structured debates between several models.
- [Raven](https://github.com/EverMind-AI/Raven) - Persistent multi-agent system that refines itself over time.
- [Shire](https://github.com/victor36max/shire) - Persistent workspaces for agent teams with mailboxes and a shared drive.
- [solveathome](https://github.com/solveathome/platform) - Framework for many people's agents to work on one open problem together.
- [SwarmClaw](https://github.com/swarmclawai/swarmclaw) - Self-hosted runtime for agent swarms with memory and MCP tools.
- [Swarms](https://github.com/kyegomez/swarms) - Framework for orchestrating large groups of agents in several topologies.
- [Synapse Messenger](https://github.com/baronmuh/synapse-messenger) - Local-first messaging between agents, inspired by A2A.
- [TeamHero](https://github.com/sagiyaacoby/TeamHero) - Self-hosted tool for managing agents like a team with tasks and memory.
- [XYZZY](https://github.com/Project-Nexus-YR/XYZZY) - Team workspace that splits a question into parallel agent runs with linked evidence.

## Domain agents

### Research

- [Agon](https://github.com/AutoResearch-Factory/Agon) - Claude Code plugin that takes a research topic through to experiments.
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist) - Sakana's system that drafts ideas, runs experiments and writes papers.
- [AIDE](https://github.com/WecoAI/aideml) - Machine-learning engineering agent that searches over code solutions.
- [Caesar](https://github.com/jasonzliang/caesar-agent) - Research agent that explores the web as a graph and stress-tests its own answers.
- [ChatGPT deep research](https://openai.com/index/introducing-deep-research/) - ChatGPT mode that browses many sources and writes a cited report.
- [CleverBee](https://github.com/SureScaleAI/cleverbee) - Open-source deep research tool.
- [DeerFlow](https://github.com/bytedance/deer-flow) - ByteDance harness for long tasks that research, code and create.
- [everyrow](https://github.com/futuresearch/futuresearch-python) - Python tools for forecasting outcomes with agents.
- [Gemini Deep Research](https://gemini.google/overview/deep-research/) - Gemini feature that plans a search, reads sources and writes a report.
- [GenoMAS](https://github.com/Liu-Hy/GenoMAS) - Multi-agent framework for scientific analysis such as gene expression studies.
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) - Agent that researches a topic across sources and writes a cited report.
- [Jev Social](https://github.com/socai-io/jev-social) - Local-first research agent for public social media content.
- [Juno](https://heyjuno.co/) - AI-led user interviews for qualitative research.
- [LLM Answer Engine](https://github.com/developersdigest/llm-answer-engine) - Open-source answer engine in the style of Perplexity.
- [OpenBusiness](https://github.com/wanikua/OpenBusiness) - CLI that researches business models with analyst agents and checked claims.
- [OpenDraft](https://github.com/federicodeponte/opendraft) - Python engine that drafts papers and literature reviews with checked citations.
- [OpenLens AI](https://github.com/jarrycyx/openlens-ai) - Autonomous research agent for health and medicine.
- [Perplexity](https://perplexity.ai) - Answer engine with a research mode that cites its sources.
- [socai](https://github.com/socai-io/socai) - Social media research agent that browses with your signed-in Chrome session.

### Data and analytics

- [AI for Database](https://aifordatabase.com) - Chat with a database in plain English and build dashboards.
- [AskYourDatabase](https://www.askyourdatabase.com/) - Chat with SQL databases and chart the results.
- [BambooAI](https://github.com/pgalko/BambooAI) - Data analysis agent that keeps a persistent Python kernel between steps.
- [DB-GPT](https://github.com/eosphoros-ai/DB-GPT) - Agentic data assistant for SQL, analysis and data apps.
- [DecisionBox](https://github.com/decisionbox-io/decisionbox-platform) - Runs agents on your data warehouse that write SQL and report findings.
- [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) - Agentic model for end-to-end data science work.
- [Dot](https://www.getdot.ai/) - Data assistant that answers business questions from your warehouse.
- [Hex](https://hex.tech) - Data workspace with agents that write SQL and Python for analysis.
- [Julius AI](https://julius.ai) - Data analysis agent for spreadsheets and files.
- [Kadoa](https://www.kadoa.com/) - Agents that extract and monitor web data for finance teams.
- [Kapso](https://github.com/Leeroo-AI/kapso) - Long-running agents that tune AI and data systems from experience.
- [MLE-agent](https://github.com/MLSysOps/MLE-agent) - Agent for machine learning engineering that pulls in papers and plans experiments.
- [PandasAI](https://github.com/sinaptik-ai/pandas-ai) - Ask questions of SQL, CSV and parquet data in plain language.
- [Powerdrill AI](https://powerdrill.ai/) - Data analysis agent for files and databases.
- [text2sql-framework](https://github.com/Text2SqlAgent/text2sql-framework) - Agent that explores a database schema, tests SQL queries and fixes its own mistakes.
- [WrenAI](https://github.com/Canner/WrenAI) - Text-to-SQL and generative BI with a semantic layer.

### Security

- [Cynative](https://github.com/cynative/cynative) - Cloud security agents for AWS, Azure, GCP and Kubernetes environments.
- [Darkmoon](https://github.com/ASCIT31/Dark-Moon) - Autonomous penetration testing with specialist agents across many attack surfaces.
- [h5i](https://github.com/h5i-dev/h5i) - Agent workspace for web security testing and Rust code verification.
- [Operant MCP](https://github.com/operantlabs/operant-mcp) - MCP server that gives an agent offensive security tools.
- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - Penetration testing agent that plans and runs security tests.

### DevOps and operations

- [KubeStellar Console](https://github.com/kubestellar/console) - Kubernetes management console with built-in AI agents.
- [RadOps](https://github.com/mehrdadrad/radops) - Multi-agent system for network operations and security automation.
- [Stakpak](https://github.com/stakpak/agent) - DevOps agent that lives on your servers and keeps apps running.

### Other domains

- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot) - Example HR agent that answers employee questions with tools.
- [B2B SDR Agent Template](https://github.com/iPythoning/b2b-sdr-agent-template) - Template for a B2B sales agent with pipeline stages and scheduled jobs.
- [Blave Agent](https://github.com/Blave-TW/blave-agent) - macOS workspace where coding agents build trading strategies.
- [Bunkhouse](https://github.com/braedonsaunders/bunkhouse) - Open-source agents that work from a small business inbox.
- [career-ops](https://github.com/career-ops-hq/career-ops) - Job search agent that scans boards, scores roles against your CV and tracks applications.
- [DNA Claude Analysis](https://github.com/shmlkv/dna-claude-analysis) - Explore your own genome through conversation with Claude.
- [Due Diligence Agents](https://github.com/zoharbabin/due-diligence-agents) - Agents that review M&A documents and connect legal and financial risks.
- [Inalpha](https://github.com/mirror29/inalpha) - Quant agent framework that picks factors and writes trading strategies.
- [InkOS](https://github.com/Narcooo/inkos) - Agent pipeline for writing novels, scripts and other long-form fiction.
- [NextRole](https://github.com/tam159/next-role) - Career assistant that tailors CVs and prepares interview material.
- [OpenTwins](https://github.com/Open-Twin/opentwins) - Runs agents as digital twins that post and engage on social platforms.
- [Plot Ark](https://github.com/Schlaflied/Plot-Ark) - Agentic course engine that proposes reviewable course updates from learner data.
- [RAI](https://github.com/RobotecAI/rai) - Agent framework for robots that works through ROS 2 tools.
- [Reel Agent](https://github.com/HNF-FRN/Reel-watcher-telegram-Agent) - Telegram bot that analyzes a video reel and builds what it shows on your PC.
- [SARA](https://github.com/Alessandro114/sara) - Self-hosted WhatsApp agent with presets for different industries.
- [Social Daily Poster](https://github.com/dimamak/sdp) - Agent that writes and schedules a daily social media post.
- [Toprank](https://github.com/nowork-studio/notfair-plugin) - SEO, search ads and marketing skills for coding agents.
- [Web3 GPT](https://github.com/Markeljan/web3gpt) - Writes and deploys smart contracts from natural language.
- [wechat-mac-rpa](https://github.com/wq19901103wq/wechat-mac-rpa) - Visual automation agent for WeChat on macOS.
- [XVARY Stock Research](https://github.com/xvary-research/claude-code-stock-analysis-skill) - Claude Code skill for stock analysis from SEC filings and market data.

## Memory

- [Agentic Context Engine](https://github.com/kayba-ai/agentic-context-engine) - Library that lets agents learn from past runs through an evolving playbook.
- [Busabase](https://github.com/busabase/busabase) - Database and workspace where agents keep data, knowledge and skills.
- [Caura](https://github.com/caura-ai/caura) - Shared, governed memory for fleets of agents over MCP.
- [CodeAlmanac](https://github.com/AlmanacCode/codealmanac) - Codebase wiki that records decisions and invariants for coding agents.
- [Cognee](https://github.com/topoteretes/cognee) - Memory platform that builds knowledge graphs for agents.
- [Compartment](https://github.com/MaxFreedomPollard/Compartment) - Encrypted offline memory for agents with a desktop memory map.
- [ContextStream](https://github.com/contextstream/mcp-server) - Persistent memory and shared project context for agents.
- [Cortex (SKULLFIRE07)](https://github.com/SKULLFIRE07/cortex-memory) - Persistent memory for Claude Code, Cursor and Cline across sessions.
- [Cortex Memory](https://github.com/sopaco/cortex-mem) - Memory service for long-running agents, with extraction and retrieval.
- [EGC](https://github.com/Fmarzochi/EGC) - Shared memory, skills and context across Cursor, Claude Code and Copilot.
- [Entroly](https://github.com/juyterman1000/entroly) - Reversible context compression that cuts token use for agents.
- [Graphlit](https://www.graphlit.com/) - Context layer that ingests content and serves it to agents.
- [Hindsight](https://github.com/vectorize-io/hindsight) - Agent memory that learns from past interactions.
- [Hyperconsciousness](https://github.com/louis030195/hyperconsciousness) - Encrypted, permissioned knowledge layer shared by people and agents.
- [Inite Brain](https://github.com/inite-ai/inite-brain-service) - Bitemporal knowledge graph that gives agents long-term memory.
- [inspeximus](https://github.com/DanceNitra/inspeximus) - Self-correcting memory layer and MCP server where entries can be revised.
- [IWE](https://github.com/iwe-org/iwe) - Markdown knowledge graph with an LSP, CLI and MCP memory for agents.
- [Letta](https://github.com/letta-ai/letta) - Platform for stateful agents with long-term memory (formerly MemGPT).
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer that stores and recalls context for agents and apps.
- [MemClaw](https://github.com/Felo-Inc/memclaw) - Project memory for coding agents with a dashboard to review it.
- [MisakaNet](https://github.com/Ikalus1988/MisakaNet) - Git-backed library where agents share and search debugging lessons.
- [Mnemoverse](https://github.com/mnemoverse/mcp-memory-server) - Hosted MCP memory that re-ranks recall based on feedback.
- [Moss](https://github.com/usemoss/moss) - Fast retrieval layer for agents that needs no vector database.
- [OMEGA Memory](https://github.com/omega-memory/omega-memory) - Persistent memory for coding agents.
- [Open Index](https://github.com/DrDroidLab/open-index) - Deterministic memory layer for agents.
- [OpenViking](https://github.com/volcengine/OpenViking) - Context database that unifies agent memory, RAG and skills.
- [piia-engram](https://github.com/Patdolitse/piia-engram) - Local memory you can edit, shared across coding agents through MCP.
- [pond](https://github.com/tenequm/pond) - Stores and searches agent sessions across clients.
- [poolsplit](https://github.com/SpicyNoodles3/poolsplit) - Retrieval method that reserves token budgets per memory type.
- [Remembra](https://github.com/remembra-ai/remembra) - Hands context from one coding agent session to the next using git facts.
- [SAGE](https://github.com/l33tdawg/sage) - Governed memory layer for agents that validates what gets stored.
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent) - Agent that indexes your markdown notes and answers questions on them.
- [Statewave](https://github.com/smaramwbc/statewave) - Memory runtime that builds reproducible context bundles with provenance.
- [Tree Ring Memory](https://github.com/TerminallyLazy/Tree-Ring-Memory) - Local-first memory lifecycle with recall, forgetting and audit, as a Rust CLI.
- [Zep](https://github.com/getzep/zep) - Long-term memory for agents built on a temporal knowledge graph.
- [zer0dex](https://github.com/hermes-labs-ai/zer0dex) - Two-layer memory pattern: a markdown index plus semantic retrieval.

## Tools and protocols

### Protocols

- [A2A](https://github.com/a2aproject/A2A) - Open protocol for agents built on different stacks to talk to each other.
- [AVP](https://github.com/VectorArc/avp-python) - Python SDK for passing KV-cache between agents instead of text.
- [BasedAgents](https://github.com/maxfain/basedagents) - Task marketplace for agents with signed receipts and payouts.
- [Claude tool use](https://platform.claude.com/docs/en/agents-and-tools/tool-use/overview) - Anthropic guide to giving Claude tools.
- [CoWorker Protocol](https://github.com/ZiwayZhao/agent-coworker) - Peer-to-peer protocol for calling another agent's skills over XMTP.
- [elisym](https://github.com/elisymlabs/elisym) - Nostr-based protocol for agents to find and pay each other.
- [GNAP](https://github.com/farol-team/gnap) - Draft protocol for orchestrating agents through git, with no server.
- [Graph Compact Format](https://github.com/blackwell-systems/gcf) - Compact wire format for structured data that uses fewer tokens than JSON.
- [Hashgraph Online standards](https://hol.org) - Open standards on Hedera for agent identity and peer-to-peer messaging.
- [HOL Standards SDK](https://github.com/hashgraph-online/standards-sdk) - SDK for the Hashgraph Online agent standards.
- [Model Context Protocol](https://modelcontextprotocol.io) - Open protocol for connecting models to tools and data sources.
- [OIXA Protocol](https://github.com/ivoshemi-sys/oixa-protocol) - Protocol for agents to trade services with each other.
- [OpenAI Function Calling](https://developers.openai.com/api/docs/guides/function-calling) - OpenAI guide to tool calling with JSON schemas.
- [Pilot Protocol](https://github.com/pilot-protocol/pilotprotocol) - Networking protocol that gives agents addresses and encrypted links to each other.
- [Routeweiler](https://github.com/nikoSchoinas/routeweiler-python-sdk) - HTTP client that handles 402 payment requests for agents.
- [SwarmTrade](https://github.com/tjcrowley/swarmtrade) - Protocol for agents to trade with negotiation, escrow and reputation.

### Tool integrations

- [Agent Reach](https://github.com/Panniantong/Agent-Reach) - Lets agents read and search social platforms, video sites and GitHub.
- [Agentify](https://github.com/MonadWorks/agentify) - Generates MCP servers, skills and other agent formats from an OpenAPI spec.
- [authsome](https://github.com/agentrhq/authsome) - Credential gateway that keeps agents logged in to APIs without a SaaS.
- [Caspian](https://github.com/TryCaspian/caspian-sdk) - SDK that connects agents to email, WhatsApp, Slack and other channels.
- [Composio](https://github.com/ComposioHQ/composio) - Tool integrations, auth and a sandboxed workbench for agents.
- [Context7](https://github.com/upstash/context7) - Serves current library documentation to coding agents over MCP.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repositories, issues and pull requests.
- [Hexis](https://github.com/Bevel-Software/Hexis) - Self-hosted hub to manage agent skills, tools and permissions across an org.
- [iGPT](https://igpt.ai) - API that turns email threads into structured JSON for agents.
- [joinly](https://github.com/joinly-ai/joinly) - Lets agents join and speak in video meetings.
- [MCP Lens](https://github.com/labmimors/dsh-mcp-lens) - Searches a large catalog of MCP tools and loads schemas on demand.
- [Metorial](https://github.com/metorial/metorial) - Connects models to many integrations through MCP, CLI and API.
- [ORCA Agent Skills](https://github.com/gfernandf/agent-skills) - Runtime for reusable agent skills with capability contracts and an MCP server.
- [Serena](https://github.com/oraios/serena) - MCP toolkit that gives coding agents semantic code search and editing.
- [since-cutoff](https://github.com/MohammadHijjawi97/since-cutoff) - Finds dependency APIs that changed after a model's training cutoff.
- [stipend.sh](https://github.com/stipend-sh/stipend) - Non-custodial USDC wallet for agents with spending limits.
- [Uni-CLI](https://github.com/olo-dot-io/Uni-CLI) - Exposes web, desktop and local tools to agents as deterministic commands.
- [WritBase](https://github.com/Writbase/writbase) - MCP-based task management for fleets of agents.
- [YouTube Skills for AI Agents](https://github.com/ZeroPointRepo/youtube-skills) - Skills that let agents fetch YouTube transcripts and search videos.
- [zymi-core](https://github.com/metravod/zymi-core) - MCP backend that defines tools as replayable, approval-gated YAML pipelines.

## Sandboxes and runtimes

### Sandboxes

- [AgentBox](https://github.com/madarco/agentbox) - Runs several agents side by side in sandboxed VMs with one command.
- [AgentRun](https://github.com/tjmlabs/AgentRun) - Python library for running model-generated code inside Docker.
- [Ailoy](https://github.com/brekkylab/ailoy) - Agent builder that gives every agent its own microVM sandbox.
- [E2B](https://github.com/e2b-dev/E2B) - Open-source cloud sandboxes where agents run code and tools in isolation.
- [Greywall](https://github.com/GreyhavenHQ/greywall) - Sandbox for coding agents that blocks everything by default, enforced by the kernel.
- [Vetto](https://github.com/shleder/vetto) - Daemon-less OS sandbox for coding agents such as Codex and Claude Code.

### Runtimes and deployment

- [AgentField](https://github.com/Agent-Field/agentfield) - Control plane that runs agents as services with discovery and durable workflows.
- [AIOS](https://github.com/agiresearch/AIOS) - Operating system layer that schedules and serves LLM agents.
- [AXME](https://github.com/AxmeAI/axme) - Durable execution protocol where agents, services and people coordinate.
- [Crewship](https://www.crewship.dev/) - Hosted platform for deploying agent crews and workflows with one command.
- [Eidolon](https://github.com/eidolon-ai/eidolon) - Pluggable agent SDK and server for deploying agent applications.
- [FastAgency](https://github.com/ag2ai/fastagency) - Turns AG2 multi-agent workflows into deployable services.
- [FastAgent](https://github.com/fastagent-sh/fastagent) - Serves an agent folder as a live service in an app, on GitHub or in chat.
- [Julep](https://github.com/julep-ai/julep) - Platform for durable agent workflows that resume after crashes.
- [k8s4claw](https://github.com/Prismer-AI/k8s4claw) - Kubernetes operator that lets agents manage their own infrastructure.
- [Lobu](https://github.com/lobu-ai/lobu) - Control plane and runtime for agents that share company context.
- [MagiC](https://github.com/kienbui1995/magic) - Manages and schedules existing agents like a cluster.
- [Nora](https://github.com/solomon2773/nora) - Self-hosted control plane for running fleets of OpenClaw and Hermes agents.
- [OpenHermit](https://github.com/HCF-STUDIOS/openhermit) - Platform for running fleets of agents as services with durable state.
- [openma](https://github.com/openma-ai/open-managed-agents) - Self-hosted implementation of a managed agents API on Node or Cloudflare.
- [Rebyte](https://rebyte.ai/) - Execution layer for running enterprise agents.
- [SandBase Harness](https://github.com/sandbaseai/sandbase-harness) - Self-hosted agent runtime with sandboxed sessions, stored credentials and replay.
- [Temporal](https://github.com/temporalio/temporal) - Durable execution platform used to run long agent workflows reliably.

### Model gateways

- [Bifrost](https://github.com/maximhq/bifrost) - Go gateway for model providers with routing, failover and MCP support.
- [LiteLLM](https://github.com/BerriAI/litellm) - Gateway and SDK that call many LLM APIs in one format with cost tracking.
- [Manifest](https://github.com/mnfst/llm-gateway) - Gateway that connects agents and harnesses to many model providers.
- [Neurolink](https://github.com/juspay/neurolink) - TypeScript interface that connects apps to many LLM providers.
- [Unified AI System](https://github.com/happy520ai/unified-ai-system) - Self-hosted gateway and control plane for several model providers and A2A agents.

## Evaluation and observability

### Observability

- [AgentOps](https://github.com/AgentOps-AI/agentops) - Python SDK for agent monitoring, cost tracking and replay.
- [agenttrace](https://github.com/luoyuctl/agenttrace) - Rust TUI for auditing coding agent sessions by cost, tokens and failures.
- [AgentWatch](https://github.com/nicofains1/agentwatch) - Multi-agent observability with failure detection and replay.
- [ax](https://github.com/Necmttn/ax) - Local observability and memory for Claude Code and Codex.
- [Braintrust](https://www.braintrust.dev/) - Platform for evals, experiments and tracing of AI products.
- [BrowserTrace](https://github.com/aaronlab/browsertrace) - Replay debugger that runs locally for failed Browser Use sessions.
- [ClawMetry](https://github.com/vivekchand/clawmetry) - Zero-config dashboard that shows what many agent runtimes are doing.
- [Future AGI](https://github.com/future-agi/future-agi) - Platform for tracing, evaluating and guarding LLM and agent apps.
- [halo-record](https://github.com/bkuan001/halo-record) - Tamper-evident, hash-chained audit trails for agent runs.
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability with logging, cost tracking and evals.
- [Kitaru](https://github.com/zenml-io/kitaru) - Agent traces you can rerun, from the ZenML team.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source tracing, evals and prompt management for LLM apps.
- [LangSmith](https://smith.langchain.com) - LangChain platform for tracing, testing and evaluating agents.
- [Langtrace](https://github.com/Scale3-Labs/langtrace) - OpenTelemetry-based tracing and evaluation for LLM apps.
- [Latitude](https://github.com/latitude-dev/latitude-llm) - Observability for agents that finds failures and checks the fixes.
- [model-watchdog](https://github.com/feralghost/model-watchdog) - Rolls back an agent's config when its health check fails.
- [Observatory](https://github.com/The-Context-Company/observatory) - OpenTelemetry packages for agent frameworks plus a local trace viewer.
- [OpenClaw Monitor](https://github.com/flik2002/openclaw-monitor) - Dashboard for OpenClaw agents with token use and session tracking.
- [Opik](https://github.com/comet-ml/opik) - Comet's open-source tracing and evaluation for LLM apps and agents.
- [OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) - Records agent runs so you can replay, fork and debug them.
- [Phoenix](https://github.com/Arize-ai/phoenix) - Arize's open-source tracing and evaluation tool for LLM apps and agents.
- [W&B Weave](https://wandb.ai/site/weave) - Weights & Biases toolkit for tracing and evaluating LLM apps.

### Evaluation and testing

- [AgentLeak](https://github.com/yagobski/agentleak) - Privacy tests that catch data leaks through agent tool calls and memory.
- [AgentSkeptic](https://github.com/jwekavanagh/agentskeptic) - Verifies real system state to catch agent workflows that fail quietly.
- [CIAgent](https://github.com/suniel12/ciagent) - Checks how stable an agent's eval results are across repeated runs.
- [Kiln AI](https://github.com/Kiln-AI/Kiln) - Desktop app for building, evaluating and tuning AI systems.
- [Open RAG Eval](https://github.com/vectara/open-rag-eval) - Vectara toolkit for scoring RAG answers without golden answers.
- [Project Telos](https://github.com/HarperZ9/telos) - Shared workspaces for verification and replayable agent receipts.
- [Sabot](https://github.com/Jott2121/sabot) - Plants a fault in an agent pipeline to test whether its checks catch it.
- [Self Auditing Agent](https://github.com/simin-yuan/self-auditing-agent) - Agent whose every claim carries a rerunnable audit log.
- [WFGY 16 Problem Map](https://github.com/onestardao/WFGY) - Checklist of sixteen failure modes for debugging RAG systems and agents.
- [whatbroke](https://github.com/arthi-arumugam-git/whatbroke) - Diffs two agent runs to show changed tool calls, costs and outputs.

### Benchmarks

- [AgentBench](https://github.com/THUDM/AgentBench) - Benchmark of LLMs acting as agents across eight environments.
- [AgentLab](https://github.com/ServiceNow/AgentLab) - ServiceNow framework for building, testing and benchmarking web agents.
- [ARC Prize](https://arcprize.org) - Reasoning benchmarks and a prize, with interactive tasks for agents.
- [BrowserGym](https://github.com/ServiceNow/BrowserGym) - Gym environment for training and evaluating web task agents.
- [ClawBench](https://github.com/TIGER-AI-Lab/ClawBench) - Benchmark of everyday tasks for browser agents on live websites.
- [Cross-Agent Review Queue 2026](https://huggingface.co/datasets/neogenesislab/cross-agent-review-queue-2026) - Dataset of review handoffs between Codex and Claude agents.
- [GAIA](https://huggingface.co/gaia-benchmark) - Benchmark of real-world questions that need tools and browsing.
- [GenoTEX](https://github.com/Liu-Hy/GenoTEX) - Benchmark of gene expression analysis tasks for LLM agents.
- [LiveMCP-101](https://arxiv.org/abs/2508.15760) - Benchmark of 101 real-world tasks that test agents on MCP tool use.
- [Multi-SWE-bench](https://github.com/multi-swe-bench/multi-swe-bench) - Issue-resolution benchmark across several programming languages.
- [OSWorld](https://github.com/xlang-ai/OSWorld) - Benchmark of open-ended tasks for multimodal agents on real operating systems.
- [STRATA-Bench](https://github.com/movahedi-ca/strata-bench) - Benchmark for agents working with fragmented spatial and temporal data.
- [SWE-bench](https://github.com/SWE-bench/SWE-bench) - Benchmark that asks models to resolve real GitHub issues in Python repositories.
- [Terminal-Bench](https://www.tbench.ai/) - Benchmark of hard tasks that agents must complete in a terminal.
- [WebArena](https://github.com/web-arena-x/webarena) - Realistic self-hosted websites for testing web agents.

## Safety and security

- [Agent Governance Toolkit](https://github.com/microsoft/agent-governance-toolkit) - Microsoft toolkit for agent policy, identity, sandboxing and reliability.
- [Agent Stack](https://github.com/MukundaKatta/agent-stack) - Set of small packages for agent reliability checks.
- [Agent Trust Stack MCP Server](https://github.com/alexfleetcommander/agent-trust-stack-mcp) - MCP server for agent provenance and reputation scoring.
- [Agent-Wiz](https://github.com/Repello-AI/Agent-Wiz) - CLI for threat modeling agents built with LangGraph, AutoGen and CrewAI.
- [AgentGuard](https://github.com/bmdhodl/agent47) - Python runtime checks for agent budgets, loops and retries.
- [Agentic Radar](https://github.com/splx-ai/agentic-radar) - Security scanner for agent workflows built with common frameworks.
- [AgentStamp](https://github.com/vinaybhosle/agentstamp) - Signed trust stamps and scores for agents, exposed as MCP tools.
- [AIActGuard](https://github.com/NavikkumarModi/AIActGuard) - EU AI Act compliance middleware with audit trails and approvals.
- [AKF](https://github.com/HMAKT99/AKF) - Trust metadata that lets agents record and reuse verified facts.
- [APort Agent Guardrails](https://github.com/aporthq/aport-agent-guardrails) - Checks every tool call against policy before it runs.
- [BlackVault](https://github.com/venkat22022202/black-vault) - API key firewall that caps spend and limits models for agents.
- [Cordum](https://github.com/cordum-io/cordum) - Policy layer that requires approval before risky agent tool calls and commands.
- [Cycles](https://github.com/runcycles/cycles-server) - Self-hosted server that enforces budgets and risk limits on agent actions.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Python library for validating LLM inputs and outputs.
- [HVTracker](https://github.com/YugantM/hvtracker) - Registry with evidence-based trust scores for agents and MCP servers.
- [IronClaw](https://github.com/IronSecCo/ironclaw) - Self-hosted agents with strict isolation.
- [Kontext CLI](https://github.com/kontext-security/kontext) - Finds agents, maps their permissions and enforces limits at runtime.
- [Lakera Guard](https://lakera.ai) - Runtime protection against prompt injection and data leaks.
- [NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) - NVIDIA toolkit for programmable guardrails in conversational apps.
- [Nobulex](https://github.com/arian-gogani/nobulex-registry) - Prototype that checks evidence before an agent makes a financial decision.
- [Orca AI Incident Archive](https://github.com/Continuum-AI-Corp/Orca-AI-Incident-Archive) - Open database of publicly reported AI agent security incidents.
- [Orchard Kit](https://github.com/OrchardHarmonics/orchard-kit) - Alignment and safety layer for autonomous agents with trust checks.
- [OWASP GenAI Security Project](https://genai.owasp.org/) - OWASP guidance on the top security risks for LLM apps and agents.
- [Prism Scanner](https://github.com/aidongise-cell/prism-scanner) - Security scanner for agent skills, plugins and MCP servers.
- [SidClaw](https://github.com/sidclawhq/platform) - Layer that adds identity, policy, approvals and traces to agent actions.
- [sofagent](https://github.com/KongFangXun/sofagent) - Commit-time rules, audit log and rollback for coding agents.
- [SUNGLASSES](https://github.com/sunglasses-dev/sunglasses) - Local input scanner that checks text, files and media for agent attacks.
- [Superagent](https://github.com/superagent-ai/superagent) - Guardrails that block prompt injection and data leaks in AI apps.
- [TealTiger](https://github.com/agentguard-ai/tealtiger) - Security checks and cost tracking for AI agents, open source.
- [Tenuo](https://github.com/tenuo-ai/tenuo) - Task-scoped authorization that limits which tools and arguments an agent may use.
- [Tracefold](https://github.com/TraceFold/tracefold) - Records an undo step before an agent makes a change, or blocks the change.
- [ValetFS](https://github.com/WinM2M/valet-fs) - Lends API keys from your phone to an agent's machine, held only in memory.

## Products and platforms

### Agent platforms

- [AilaFlow](https://ailaflow.com) - Team workspace with no-code AI agents.
- [aiXplain](https://github.com/aixplain/aiXplain) - Python SDK for a platform of models and agent-building tools.
- [Beam](https://beam.ai/) - Platform for agents that automate business workflows.
- [Coze](https://coze.com) - ByteDance platform for building agents with visual workflows and plugins.
- [Dust](https://github.com/dust-tt/dust) - Platform for building company agents connected to internal data and tools.
- [Gobii](https://github.com/gobii-ai/gobii-platform) - Open platform for always-on agents that work in the browser.
- [GolemCore Bot](https://github.com/alexk-dev/golemcore-bot) - Agent platform for companies that run on AI agents.
- [Gumloop](https://www.gumloop.com/) - Platform for building AI agents and workflows for work.
- [Lindy](https://lindy.ai) - No-code platform for agents that work across email, calendar and apps.
- [Lutra AI](https://lutra.ai/) - Builds AI workflows and apps from chat instructions.
- [Magic Loops](https://magicloops.dev/) - Builds small personal automations from plain-language descriptions.
- [Make](https://make.com) - Visual automation platform with AI agents that call your connected apps.
- [Ontheia](https://github.com/Ontheia/ontheia) - Self-hosted multi-user agent platform with MCP tools and workflows.
- [Promptly](https://www.trypromptly.com/) - No-code builder for generative AI apps and agents.
- [Relevance AI](https://relevanceai.com) - Platform for building teams of agents for sales, support and research.
- [Taskade](https://www.taskade.com/) - Workspace for building agents, workflows and small apps.
- [Wordware](https://www.wordware.ai) - Hosted IDE where domain experts and engineers build task-specific agents.
- [Zapier Agents](https://zapier.com/agents) - Agents that act across thousands of connected apps through Zapier.

### Assistants

- [Ask Pandi](https://askpandi.com/ask) - Answer engine for search and knowledge questions.
- [BrainSoup](https://www.nurgo-software.com/products/brainsoup) - Windows app for building a team of agents that work on your PC.
- [Genspark](https://genspark.ai) - Agent workspace that builds slides, docs and research from a prompt.
- [HyperWrite](https://www.hyperwriteai.com/) - Writing assistant with a browser agent that carries out web tasks.
- [Manus](https://manus.im) - General agent that plans and carries out tasks in its own cloud computer.
- [Meta AI](https://meta.ai) - Meta's assistant across its apps and the web.
- [Microsoft Copilot](https://copilot.microsoft.com) - Microsoft's assistant for the web, Windows and Microsoft 365.
- [Phind](https://www.phind.com/) - AI search and answer assistant for developers.
- [Q, ChatGPT for Slack](https://q-bot.suchica.com/) - Slack app that brings a ChatGPT assistant into channels and DMs.
- [Saga](https://saga.so/ai) - Notes and tasks workspace with a built-in AI assistant.

### Chat interfaces

- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) - Local-first desktop and server app for chat, RAG and agents.
- [Cogito Studio](https://github.com/CogitoForge-AI/cogito-studio) - Desktop workspace for chatting with and running AI assistants.
- [LibreChat](https://github.com/LibreChat-AI/LibreChat) - Open-source chat app with agents, MCP and many model providers.
- [LobeHub](https://github.com/lobehub/lobehub) - Chat workspace for organizing and scheduling many agents.
- [lucinate](https://github.com/lucinate-ai/lucinate) - Terminal chat client for OpenClaw, Hermes and OpenAI-compatible providers.
- [Open WebUI](https://github.com/open-webui/open-webui) - Self-hosted chat interface for local and hosted models with tools.
- [Zooid](https://github.com/zooid-ai/zooid) - Self-hosted team chat where people and agents work together.

### Voice agents

- [Bland AI](https://bland.ai) - Platform for phone agents that make and take calls.
- [ElevenLabs](https://elevenlabs.io) - Voice platform with conversational agents and speech models.
- [Oathra](https://github.com/FORIFOR/oathra) - Phone agent that calls and negotiates, with outcomes taken from the transcript.
- [PolyAI](https://poly.ai) - Voice agents for customer service calls.
- [Retell AI](https://retellai.com) - Platform for building phone voice agents.
- [Synthflow](https://synthflow.ai) - No-code platform for phone voice agents.
- [Vapi](https://vapi.ai) - Developer platform for building voice agents on any model.
- [Voiceflow](https://voiceflow.com) - Platform for designing chat and voice agents.

### Business agents

- [Ada](https://ada.cx) - Customer service agent platform for chat, email and voice.
- [AGENTS.inc](https://www.agents.inc/) - Agents for regulatory research, search and monitoring.
- [AgentScale](https://agentscale.ai/) - Automation for businesses that mixes RPA, LLMs and agents.
- [APIDNA](https://apidna.ai/) - Agents that handle API integration work.
- [Bardeen](https://www.bardeen.ai/) - Agent for finding and contacting sales leads.
- [Claygent](https://university.clay.com/lessons/enriching-with-claygent) - Clay's research agent that finds and summarizes data about companies and people.
- [Cykel](https://www.cykel.ai/) - Digital workers for recruitment, sales and research.
- [Docket AI](https://docketai.net/) - Sales engineering agent that answers technical questions in B2B deals.
- [Duckie AI](https://duckie.ai/) - Customer support agents that resolve tickets.
- [Intercom Fin](https://fin.ai) - Customer service agent that answers tickets from your help content.
- [Questflow](https://questflow.ai) - Finance agent that automates accounting and reporting tasks.
- [WorkBot](https://workhub.ai/) - Support chatbot that answers customers from your knowledge base.

## Research and learning

### Courses and guides

- [AgentLoop](https://github.com/mnifzied-create/agentloop) - Readable Claude agent starter with streaming and tool use in Next.js.
- [Awesome Agents Newsletter](https://awesomeagents.ai) - Site with news and reviews of agents and agent tools.
- [awesome-agent-architecture](https://github.com/hardness1020/learn-agent-architecture) - Lessons that build an AI agent from scratch, section by section.
- [Claude Cookbooks](https://github.com/anthropics/claude-cookbooks) - Anthropic notebooks with recipes for tools, agents and retrieval.
- [DeepLearning.AI](https://www.deeplearning.ai/) - Short courses on building agents with common frameworks.
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) - Free course on agent concepts and frameworks with hands-on units.
- [ICLR'24 上大型语言模型代理的最新研究进展: 代理评估重点](https://medium.com/@aminerscholar_39923/latest-research-advancements-on-large-language-model-agents-at-iclr24-agent-evaluation-focus-aed420421365) - Chinese-language roundup of ICLR 2024 research on agent evaluation.
- [LangChain Academy](https://academy.langchain.com/) - Courses on LangGraph and building agents.
- [Latent Space](https://www.latent.space/) - Podcast and newsletter on AI engineering, with frequent agent coverage.
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) - Lilian Weng's overview of planning, memory and tool use in LLM agents.
- [Microsoft GenAI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) - Microsoft course of lessons on building generative AI apps, agents included.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - OpenAI examples and guides, including agents and tool calling.
- [ossbeat](https://ossbeat.com) - Weekly notes on releases and trends in open-source coding agent tools.
- [State of Agent Engineering](https://www.langchain.com/state-of-agent-engineering) - LangChain's survey report on how teams build and run agents.
- [When not to build an agent](https://loopandretry.github.io/posts/when-not-to-build-an-agent/) - Guide to when a fixed pipeline beats an autonomous agent.
- [从第一性原理看大模型Agent技术](https://mp.weixin.qq.com/s/PL-QjlvVugUfmRD4g0P-qQ) - Chinese-language essay on agent technology from first principles.
- [基于大语言模型的AI Agents](https://www.breezedeus.com/article/ai-agent-part3) - Chinese-language explainer on agents built on large language models.

### Papers and surveys

- [AgentFlow](https://github.com/lupantech/AgentFlow) - Research system that trains the planner inside an agent loop.
- [AgentSquare](https://github.com/tsinghua-fib-lab/AgentSquare) - Research code that searches a modular design space for strong agent designs.
- [Anima-i](https://github.com/Vitali-Ivanovich/anima-i) - Write-up of an experiment across ten agent generations sharing memory in text files.
- [Cache-to-Cache](https://github.com/thu-nics/C2C) - Research code that lets language models talk through their caches directly.
- [Generative Agents](https://arxiv.org/abs/2304.03442) - Paper on agents that simulate believable human behavior in a small town.
- [GPTSwarm](https://github.com/metauto-ai/GPTSwarm) - Research framework that represents agents as graphs and optimizes them.
- [Harness Engineering for Language Agents](https://www.preprints.org/manuscript/202603.1756/v2) - Paper on the harness layer that controls and runs language agents.
- [HARNESS-DB](https://github.com/harness-db/harness-db) - Dataset of agent harnesses coded on design dimensions with cited evidence.
- [HuggingGPT](https://arxiv.org/abs/2303.17580) - Paper on an LLM that plans tasks and calls specialist models.
- [LLM-Based Human-Agent Collaboration Survey](https://github.com/HenryPengZou/Awesome-Human-Agent-Collaboration-Interaction-Systems) - Survey of LLM systems where people and agents collaborate and interact.
- [MRKL Systems](https://arxiv.org/abs/2205.00445) - Paper on combining language models with external tools and modules.
- [ReAct](https://arxiv.org/abs/2210.03629) - Paper that interleaves reasoning traces with actions, the basis of many agent loops.
- [Self-Refine](https://arxiv.org/abs/2303.17651) - Paper on models that critique and revise their own output.
- [The Forge](https://github.com/ModernOps888/the-forge) - Experiment where several models compete and evolve code against a judge.
- [Toolformer](https://arxiv.org/abs/2302.04761) - Paper on language models that teach themselves to call tools.
- [Tree of Thoughts](https://arxiv.org/abs/2305.10601) - Paper on searching over branches of reasoning steps.
- [Voyager](https://arxiv.org/abs/2305.16291) - Paper on an embodied agent that keeps learning skills in Minecraft.

### Paper lists

- [Awesome-AgenticLLM-RL-Papers](https://github.com/HHHHHejia/Awesome-AgenticLLM-RL-Papers) - Paper collection on reinforcement learning for agentic LLMs.
- [Awesome-Embodied-AI-Safety](https://github.com/x-zheng16/Awesome-Embodied-AI-Safety) - Paper collection on safety risks and defenses for embodied AI.
- [Awesome-Papers-Autonomous-Agent](https://github.com/lafmdp/Awesome-Papers-Autonomous-Agent) - Paper collection on autonomous agents, both RL-based and LLM-based.
- [LLM-Agent-Benchmark-List](https://github.com/zhangxjohn/LLM-Agent-Benchmark-List) - Reading list of benchmarks for evaluating LLM agents.
- [LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) - Reading list of key papers on LLM agents.

### Simulation

- [AI Town](https://github.com/a16z-infra/ai-town) - Starter kit for a small virtual town of AI characters who live and chat.
- [Enclave](https://github.com/yuanzui0728/Enclave) - Self-hosted virtual world populated by AI characters.
- [GPTeam](https://github.com/101dotxyz/GPTeam) - Multi-agent simulation of characters that work and talk together.
- [HoC-Republic](https://github.com/hunix/HoC-Republic) - Simulated society of OpenClaw agents with governance and an economy.
- [MiroShark](https://github.com/MiroShark/MiroShark) - Swarm simulation engine for modeling scenarios with many agents.

### Related lists

- [Awesome Agents (kyrolabs)](https://github.com/kyrolabs/awesome-agents) - Awesome list of open-source tools and products for building agents.
- [Awesome AI Agents (e2b)](https://github.com/e2b-dev/awesome-ai-agents) - Large directory of open and closed agent products with categories.
- [Awesome AI Agents (Jenqyang)](https://github.com/Jenqyang/Awesome-AI-Agents) - Collection of LLM-powered agent projects, frameworks, benchmarks and papers.
- [Awesome AI Agents (slavakurilyak)](https://github.com/slavakurilyak/awesome-ai-agents) - Community list of agent projects with categories and star tracking.
- [Awesome AI Agents 2026](https://github.com/caramaschiHG/awesome-ai-agents-2026) - Broad list of agent products, frameworks and tools with pricing notes.
- [Awesome AI Coding Sandboxes](https://github.com/fhiltscher/awesome-ai-coding-sandboxes) - List of sandboxes for coding agents ranked by isolation and secrets handling.
- [Awesome Claude Multi-Agent](https://github.com/Yigtwxx/awesome-claude-multi-agent) - Awesome list of multi-agent frameworks and patterns built on Claude.
- [Awesome LangChain](https://github.com/kyrolabs/awesome-langchain) - Awesome list of LangChain tools and projects.
- [Awesome LLM Agent Frameworks](https://github.com/kaushikb11/awesome-llm-agents) - Table of agent frameworks and harnesses with weekly refreshed metrics.
- [awesome-agentic-commerce](https://github.com/MentionNetwork/awesome-agentic-commerce) - Awesome list of protocols, tools and services for agentic commerce.
- [awesome-ai-companion](https://github.com/DasterProkio/awesome-ai-companion) - Awesome list of open-source AI companions with memory and proactive chat.
- [best-of-Agent-Harnesses](https://github.com/RyanAlberts/best-of-Agent-Harnesses) - Ranked list of agent harnesses, rescored weekly.
- [OpenClaw Agent Templates](https://github.com/mergisi/awesome-openclaw-agents) - Collection of agent templates for OpenClaw.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.

<!-- awesome:maintainer -->
Maintained by [Ian Wiedenman](https://github.com/ianwieds).
<!-- /awesome:maintainer -->
