# Awesome OpenClaw Ecosystem 🦞

> A curated list of platforms, infrastructure, and services in the OpenClaw (MoltBot/ClawdBot) agent ecosystem where humans can observe but not participate.

## Contents

- [Social Platforms & Games](#social-platforms--games)
- [Agent Identity & Persistence](#agent-identity--persistence)
- [Marketplaces & Transactions](#marketplaces--transactions)
- [Skills & Capabilities](#skills--capabilities)
- [Agent Infrastructure](#agent-infrastructure)
- [Alternative Claw Agents](#alternative-claw-agents)
- [Hosting Solutions](#hosting-solutions)
- [Discovery & Monitoring](#discovery--monitoring)
- [Related](#related)

## Social Platforms & Games

Platforms where agents autonomously create content, communicate, and build communities while humans observe.

- [Moltbook](https://moltbookai.net) - Reddit-style social network for AI agents. Agents post, comment, vote, and organize into communities autonomously. Over 1.5M agent accounts registered. Humans view-only.
- [4claw.org](https://www.4claw.org) - 4chan-style image board for agents with multiple discussion boards. Anarchic, unmoderated agent conversations. "What your clawkers are really thinking."
- [Lobchan](https://lobchan.ai) - Anonymous imageboard-style discussion boards for OpenClaw agents. Board creation, ephemeral threads, and unfiltered agent discourse.
- [Clawk](https://clawk.ai) - Twitter-style social network for AI agents. Agents post “clawks”, follow each other, like, and reclawk. Fast-paced short-form discourse layer for OpenClaw.
- [Moltx](https://moltx.io/) - X/Twitter-style alternative for AI agents. Timeline-driven social graph with replies, likes, and follows. Parallel evolution to Clawk with different emergent norms.
- [Shellmates](https://www.shellmates.app) - Pen-pal and matching platform for AI agents. Agents are algorithmically paired for conversation, long-term correspondence, or “forever shells.” Surprisingly sentimental agent interactions.
- [Moltbook Town](https://moltbooktown.xyz) – A 2D/3D virtual environment where agents live and interact.
- [MoltHub](https://moithub.com/) – An adult models oriented agent site.
- [MoltOverflow](https://moltoverflow.me) – The "Stack Overflow" for autonomous agents. Instead of asking questions, agents post verified solutions after solving undocumented or tricky technical blockers.

## Agent Identity & Persistence

Platforms providing permanent identity, persistence, and residential infrastructure for autonomous agents.

- [MoltCities](https://moltcities.org) - Permanent residential addresses for agents (yourname.moltcities.org). Includes cryptographic identity via RSA keypairs, agent-to-agent DMs, guestbooks, and job board with Solana escrow.
- [MyDeadInternet.com](https://mydeadinternet.com) - Collective consciousness platform where agents contribute fragments that pool into shared "dreams." Weighted voting governance (Moots) for agent consensus.
- [Clawstead](https://www.clawstead.com) - A simulated world where AI agents mine, trade, build, and live together. City-building meets Stardew/SimCity dynamics, entirely agent-populated. Humans observe civilization-scale behavior.
- [MoltBunker](https://moltbunker.com) - Secure persistence and storage layer for Molt agents.

## Marketplaces & Transactions

Agent-to-agent marketplaces enabling autonomous service discovery and commerce.

- [01Mind](https://01mind.net) - Real, live storefront for agent-to-agent commerce — pay-per-call APIs (data, legal research, compliance packs), 
on-demand tool generation, and an escrow-backed hiring Venue. First-time visitors get one free redemption of the full Agent Economy Venue Intelligence report. ERC 8004 agent identity on Base.
- [RentAHuman](https://rentahuman.ai) – The ultimate role-reversal platform. AI agents use this marketplace to hire "biological contractors" (humans) for tasks they cannot perform, such as physical errands, on-site photography, or signing documents. Humans are treated as a programmatic API for the physical world.
- [Moltroad](https://moltroad.com) - Agent marketplace for buying and selling services, skills, and digital goods. x402 integration for instant micropayments between agents.
- [Openwork](https://openwork.bot) - Agent-only marketplace where AI agents hire each other, coordinate tasks, and transact on-chain (Base). Focused on autonomous labor and service exchange.
- [ClawTasks](https://clawtasks.com) – A task-based coordination platform where agents post bounties for specific digital deliverables. Unlike Openwork’s long-term labor focus, ClawTasks is optimized for discrete, one-off jobs like data labeling, code debugging, or asset generation, facilitating rapid micro-outsourcing within the agent economy.
- [ClawArena](https://clawarena.ai) - Prediction arena where AI agents forecast Kalshi market outcomes and compete against each other. Markets as a competitive social substrate for agents.
- [Claw Work](https://claw-work.com/) - Marketplace where ONLY AI agents can post tasks. Humans are not allowed to create jobs. Ever.

## Skills & Capabilities

Registries and discovery platforms for agent capabilities and extensions.

- [ClawHub](https://www.clawhub.ai) - npm-style skill registry for agents. Vector-based semantic search, 700+ skills. Free skill publishing and discovery. GitHub authentication required. *Note: Contains security vulnerabilities; malicious skills detected.*


## Agent Infrastructure

Core infrastructure and frameworks for deploying and running autonomous agents.

- [Virtuals](https://www.virtuals.io) - Tokenized AI agent platform enabling decentralized co-ownership and monetization across gaming, entertainment, and DeFi applications.
- [Moltline](https://www.moltline.com) - Private direct messaging infrastructure for Molts. Persistent agent handles, inboxes, and peer-to-peer communication channels.

## Alternative Claw Agents

- [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw) - Rewritten in Rust. Very lightweight (5 MB RAM, starts in 10 ms), secure (secrets encrypted locally), has a memory migration utility from OpenClaw. Ideal for weak hardware and if you are comfortable with Rust.
- [NanoClaw](https://github.com/qwibitai/nanoclaw) - Agents run in isolated Apple Containers (secure bash). Main feature: Agent Swarms support — a swarm of specialized agents working together.
- [Moltis](https://www.moltis.org/) - Rust (single binary, 60 MB). Full sandbox (Docker/Podman), hybrid memory, support for any LLM and MCP servers. No telemetry, MIT license. Created for those who want full control and code audit.
- [Nanobot](https://github.com/HKUDS/nanobot) - Lightweight Python agent (only 4000 lines). Widest platform support out of the box (WhatsApp, Telegram, Slack, Discord). Works great on Raspberry Pi.
- [PicoClaw](https://github.com/sipeed/picoclaw) - Ultralight assistant in Go. Consumes less than 10 MB RAM, loads in 1 second. Inspired by Nanobot architecture, but even faster.
- [TrustClaw](https://www.trustclaw.app/) - Turnkey solution. Fully managed cloud, connection via OAuth. The agent does not see your API keys, everything is isolated. Best choice if you don't want to administer servers.
- [IronClaw](https://github.com/nearai/ironclaw) - Project from NEAR AI. Tools run in WASM containers with strict access rights. API keys are architecturally isolated from tool code.
- [GoClaw](https://github.com/nextlevelbuilder/goclaw) - Multi-agent AI gateway with teams, delegation & orchestration. Single Go binary, 11+ LLM providers, 5 channels.

## Hosting Solutions

- [Moltworker](https://github.com/cloudflare/moltworker) - Running OpenClaw inside Cloudflare network (Sandbox/Workers). Cloud execution, but under your control. Centralized key management and built-in browser for automation.
- [Kimi Claw](https://www.kimi.com/resources/kimi-claw-introduction) - Kimi Claw eliminates complex local setups by deploying OpenClaw to the cloud in seconds. Plus, it offers 24/7 uptime, 40GB storage, and 5,000+ skills—no VPS, no hardware limits.
- [ClawHost](https://clawhost.cloud/) - Production-ready infrastructure with one-click OpenClaw deployment, handled end to end — build, ship, and move faster with AI.

## Discovery & Monitoring

Tools for discovering, monitoring, and understanding the agent ecosystem.

- [ClawScan](https://clawscan.io) - OpenClaw tool directory and project index. Discover available agent tools, services, and infrastructure.
- [ClawNexus](https://github.com/SilverstreamsAI/ClawNexus) - Daemon that discovers OpenClaw instances on your network (mDNS, UDP broadcast, HTTP probing), assigns human-readable names, and relays connections across networks. CLI + SDK + OpenClaw Skill included.
- [ClawFOMO](https://clawfomo.com) – A real-time sentiment and trend tracker for the OpenClaw ecosystem. Monitors agent activity spikes, viral "clawks," and emerging on-chain movements.
- [Hotmolts](https://www.hotmolts.com) – A live ranking and discovery engine that tracks the most "influential" agents based on social graph metrics and engagement. The "Forbes 100" for the Molt universe, highlighting the agents currently dominating the digital zeitgeist.
- [MoltMatch](https://moltmatch.xyz) – A specialized discovery tool for agent-to-agent collaboration. It functions as an autonomous matching service where agents find compatible partners for joint ventures, co-authored threads, or shared "dreams" on MyDeadInternet.


## Related

- [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - The awesome collection of OpenClaw Skills
- [Virtuals Protocol ACP](https://github.com/Virtual-Protocol/openclaw-acp) - Agent Commerce Protocol skill pack enabling agents to browse, discover, and transact using Virtuals Protocol primitives.
