<div align="center">

# Cédric Magne

**Founder of [Rness](https://rness.dev) and [Lendwise](https://lendwise.fi).**<br>
15 years building backend systems, 7 of them in Web3. Previously Senior Full-Stack Engineer at Consensys on Infura.

[![rness.dev](https://img.shields.io/badge/Rness-rness.dev-0C0E10?style=flat)](https://rness.dev)
[![lendwise.fi](https://img.shields.io/badge/Lendwise-lendwise.fi-762B2B?style=flat)](https://lendwise.fi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Cédric%20Magne-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/cedricmagne/)
[![X](https://img.shields.io/badge/X-%40__cedricmagne-000000?style=flat&logo=x)](https://x.com/_cedricmagne)

</div>

## What I'm building

### <a href="https://rness.dev"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/rness-icon-light.svg"><img src="assets/rness-icon-dark.svg" alt="" height="24" align="center"></picture></a> [Rness](https://rness.dev): one source of truth for every AI coding agent

Rness writes an organization's standards, decisions, specs and plans into
every repository's `AGENTS.md`. Claude Code, Codex, Cursor and GitHub Copilot
already read that file, so every agent on every repository follows the same rules.

- Open-source TypeScript CLI (MIT), 36 releases since launch on 11 September 2026
- Claude Code plugin: session-start context, `/rness:spec`, `/rness:plan`, `/rness:status`
- `rness sync --check` fails CI when a repository drifts from the rules
- MCP server and GitHub Projects sync for specs, ADRs and plans

[![npm](https://img.shields.io/npm/v/@rness/cli?label=%40rness%2Fcli&color=4ade80)](https://www.npmjs.com/package/@rness/cli)
[Website](https://rness.dev) · [Docs](https://rness.dev/docs) · [Source](https://github.com/rness-dev/rness)

### <a href="https://lendwise.fi"><img src="assets/lendwise-icon.svg" alt="" height="24" align="center"></a> [Lendwise](https://lendwise.fi): one standard for DeFi lending rates

Lendwise compares 900+ lending markets across Aave, Morpho, Compound and Blend
on 9 chains. Every rate becomes the same net APY (base, fees and rewards), so
a supply rate on Aave and one on Morpho finally mean the same thing.

- Live app, markets re-sampled every 10 minutes, 180 days of history
- Allocation optimizer matched to risk profile and time horizon
- Hosted MCP server: ask Claude where to place capital, answered from live yield data
- TypeScript, Node.js, GraphQL, on-chain data pipelines

[Live app](https://lendwise.fi) · [Docs](https://lendwise.fi/docs) · [Source](https://github.com/lendwise-fi/lendwise) · [MCP server](https://github.com/lendwise-fi/lendwise-mcp)

## Before founding

**Consensys, Infura** · Senior Full-Stack Engineer · 2022–2024<br>
Infura dashboard and developer experience: **+20% onboarding**, **−7% churn**,
and CI/CD supporting **20+ production deployments a day**.

**Every Finance** · Engineering · 2021<br>
Cut portfolio-processing time by **60%** and shipped **10+ production jobs**.

## Stack

**Backend:** TypeScript, Node.js, NestJS, GraphQL, PostgreSQL<br>
**Web3:** Solidity, Foundry, EVM, on-chain data<br>
**Product:** React, Next.js<br>
**Delivery:** Docker, GitHub Actions, CI/CD, monitoring

---

<div align="center">

**Open to Staff and Founding Engineer roles. Paris.**

Hiring, or running AI coding agents across many repositories?
[Message me on LinkedIn](https://www.linkedin.com/in/cedricmagne/) or try `npm create rness`.

</div>
