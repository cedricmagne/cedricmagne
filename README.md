<div align="center">

# Cédric Magne

**Founder of [Rness](https://rness.dev) and [Lendwise](https://lendwise.fi).**<br>
Full-stack engineer for 15+ years, in Web3 since 2019, ex-Consensys (MetaMask, Infura).<br>
I ship products end to end, from on-chain data pipelines to the interface people use.

<a href="https://www.linkedin.com/in/cedricmagne/"><img src="https://img.shields.io/badge/LinkedIn-C%C3%A9dric%20Magne-0A66C2?style=for-the-badge&labelColor=1f2328&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn"></a>
<a href="https://x.com/_cedricmagne"><img src="https://img.shields.io/badge/X-%40__cedricmagne-3f3f46?style=for-the-badge&labelColor=000000&logo=x" alt="X"></a>

</div>

## What I'm building

### <a href="https://rness.dev"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/rness-icon-light.svg"><img src="assets/rness-icon-dark.svg" alt="" height="24" align="center"></picture></a> [Rness](https://rness.dev)

**One source of truth for every AI coding agent.**
Rness writes an organization's standards, decisions, specs and plans into
every repository's `AGENTS.md`. Claude Code, Codex, Cursor and GitHub Copilot
already read that file, so each agent follows the same rules in every repository.

- `rness sync --check` fails CI when a repository drifts from the rules
- Claude Code plugin that loads the rules at session start and drafts specs and plans with you
- ADRs, specs and plans tracked on GitHub Projects and served to any MCP client

<a href="https://www.npmjs.com/package/@rness/cli"><img src="https://img.shields.io/npm/v/@rness/cli?style=for-the-badge&logo=npm&label=%40rness%2Fcli&color=4ade80&labelColor=0C0E10" alt="npm"></a>
<a href="https://rness.dev"><img src="https://img.shields.io/badge/Website-rness.dev-4ade80?style=for-the-badge&labelColor=0C0E10&logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMTIwIiBoZWlnaHQ9IjEyMCIgdmlld0JveD0iMCAwIDEyMCAxMjAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHRpdGxlPlJuZXNzIFIsIHdoaXRlPC90aXRsZT48cGF0aCBkPSJNMzguMzMgNzkuM0MzOC4zMyA4MC45NTY5IDM2Ljk4NjkgODIuMyAzNS4zMyA4Mi4zSDIxQzE5LjM0MzEgODIuMyAxOCA4MC45NTY5IDE4IDc5LjNWMjJDMTggMjAuMzQzMSAxOS4zNDMxIDE5IDIxIDE5SDU3LjY1QzYyLjM3IDE5IDY2LjMxIDE5Ljk1MzMgNjkuNDcgMjEuODZDNzIuNjMgMjMuNzYgNzUuMDA2NyAyNi4yNDMzIDc2LjYgMjkuMzFDNzguMTkzMyAzMi4zNzY3IDc4Ljk5IDM1LjY4NjcgNzguOTkgMzkuMjRDNzguOTkgNDMuMjkzMyA3OC4wNCA0Ni44OTY3IDc2LjE0IDUwLjA1Qzc0LjcyMTQgNTIuNDA5MyA3Mi45MjU3IDU0LjQxNzQgNzAuNzUyOCA1Ni4wNzQzQzY5LjQ5MjcgNTcuMDM1MiA2OC45NjU1IDU4Ljc0MjggNjkuNjc4MyA2MC4xNTgxTDc4LjYzOTQgNzcuOTUwNUM3OS42NDQzIDc5Ljk0NTcgNzguMTk0IDgyLjMgNzUuOTYgODIuM0g1OS45NTE3QzU4Ljc3NTMgODIuMyA1Ny43MDc0IDgxLjYxMjQgNTcuMjIwNiA4MC41NDE1TDQ5LjE1OTQgNjIuODA4NUM0OC42NzI2IDYxLjczNzYgNDcuNjA0NyA2MS4wNSA0Ni40MjgzIDYxLjA1SDQxLjMzQzM5LjY3MzEgNjEuMDUgMzguMzMgNjIuMzkzMSAzOC4zMyA2NC4wNVY3OS4zWk00MS4zMyAzMy40NUMzOS42NzMxIDMzLjQ1IDM4LjMzIDM0Ljc5MzEgMzguMzMgMzYuNDVWNDMuOTdDMzguMzMgNDUuNjI2OCAzOS42NzMxIDQ2Ljk3IDQxLjMzIDQ2Ljk3SDUyLjU5QzU0LjE4MzMgNDYuOTcgNTUuNTMzMyA0Ni4zNDMzIDU2LjY0IDQ1LjA5QzU3Ljc0IDQzLjgzIDU4LjI5IDQyLjE1NjcgNTguMjkgNDAuMDdDNTguMjkgMzguNzgzMyA1OC4wNDY3IDM3LjY1IDU3LjU2IDM2LjY3QzU3LjA2NjcgMzUuNjkgNTYuMzkgMzQuOTA2NyA1NS41MyAzNC4zMkM1NC42NzY3IDMzLjc0IDUzLjY5NjcgMzMuNDUgNTIuNTkgMzMuNDVINDEuMzNaIiBmaWxsPSIjZjRmNGY1Ii8%2BPHBhdGggZD0iTTc1LjY5IDcyLjhDNzguOTEgNzkuMjQgNzkuNTkgNzcuOCA4Ni4xOSA3Ny44SDk4LjE5Qzk5LjI1MDkgNzcuOCAxMDAuMjY4IDc4LjIyMTQgMTAxLjAxOCA3OC45NzE2QzEwMS43NjkgNzkuNzIxNyAxMDIuMTkgODAuNzM5MSAxMDIuMTkgODEuOFY5Ny44QzEwMi4xOSA5OC44NjA5IDEwMS43NjkgOTkuODc4MyAxMDEuMDE4IDEwMC42MjhDMTAwLjI2OCAxMDEuMzc5IDk5LjI1MDkgMTAxLjggOTguMTkgMTAxLjhIODIuMTlDODEuMTI5MSAxMDEuOCA4MC4xMTE3IDEwMS4zNzkgNzkuMzYxNiAxMDAuNjI4Qzc4LjYxMTQgOTkuODc4MyA3OC4xOSA5OC44NjA5IDc4LjE5IDk3LjhWODcuM0M3OC4xOSA4MS4zIDcyLjY5IDgxLjggNjYuNjkgODEuOEw3NS42OSA3Mi44WiIgZmlsbD0iI2Y0ZjRmNSIvPjwvc3ZnPgo%3D" alt="Website"></a>
<a href="https://rness.dev/docs"><img src="https://img.shields.io/badge/Docs-Get%20started-4ade80?style=for-the-badge&labelColor=0C0E10&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xMiA3djE0Ii8%2BPHBhdGggZD0iTTMgMThhMSAxIDAgMCAxLTEtMVY0YTEgMSAwIDAgMSAxLTFoNWE0IDQgMCAwIDEgNCA0IDQgNCAwIDAgMSA0LTRoNWExIDEgMCAwIDEgMSAxdjEzYTEgMSAwIDAgMS0xIDFoLTZhMyAzIDAgMCAwLTMgMyAzIDMgMCAwIDAtMy0zeiIvPjwvc3ZnPg%3D%3D" alt="Docs"></a>
<a href="https://github.com/rness-dev/rness"><img src="https://img.shields.io/badge/GitHub-Open%20source-4ade80?style=for-the-badge&labelColor=0C0E10&logo=github" alt="GitHub"></a>

### <a href="https://lendwise.fi"><img src="assets/lendwise-icon.svg" alt="" height="30" align="center"></a> [Lendwise](https://lendwise.fi)

**One standard for DeFi lending rates.**
Lendwise compares 900+ lending markets across Aave, Morpho, Compound and Blend.
Every rate becomes the same net APY, with base, fees and rewards included.
A supply rate on Aave and one on Morpho finally mean the same thing.

- Ingestion pipeline that maps each protocol's on-chain data to one domain model, served over GraphQL
- Allocation optimizer matched to your risk profile and time horizon
- Hosted MCP server that answers "where should I place this capital?" from live yield data

<a href="https://lendwise.fi"><img src="https://img.shields.io/badge/App-lendwise.fi-762B2B?style=for-the-badge&labelColor=1f2328&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8%2BPHBhdGggZD0iTTEyIDJhMTQuNSAxNC41IDAgMCAwIDAgMjAgMTQuNSAxNC41IDAgMCAwIDAtMjAiLz48cGF0aCBkPSJNMiAxMmgyMCIvPjwvc3ZnPg%3D%3D" alt="App"></a>
<a href="https://lendwise.fi/docs"><img src="https://img.shields.io/badge/Docs-Get%20started-762B2B?style=for-the-badge&labelColor=1f2328&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xMiA3djE0Ii8%2BPHBhdGggZD0iTTMgMThhMSAxIDAgMCAxLTEtMVY0YTEgMSAwIDAgMSAxLTFoNWE0IDQgMCAwIDEgNCA0IDQgNCAwIDAgMSA0LTRoNWExIDEgMCAwIDEgMSAxdjEzYTEgMSAwIDAgMS0xIDFoLTZhMyAzIDAgMCAwLTMgMyAzIDMgMCAwIDAtMy0zeiIvPjwvc3ZnPg%3D%3D" alt="Docs"></a>
<a href="https://github.com/lendwise-fi/lendwise"><img src="https://img.shields.io/badge/GitHub-Open%20source-762B2B?style=for-the-badge&labelColor=1f2328&logo=github" alt="GitHub"></a>
<a href="https://github.com/lendwise-fi/lendwise-mcp"><img src="https://img.shields.io/badge/MCP-mcp.lendwise.fi-762B2B?style=for-the-badge&labelColor=1f2328&logo=modelcontextprotocol" alt="MCP server"></a>

## Before founding

**Consensys** (MetaMask, Infura) · Senior Full-Stack Engineer · 2022–2024<br>
Built the onboarding flow of the MetaMask Developer dashboard (**+20% new-user engagement**)
and 10+ features that cut churn by **7%**. Automated **20+ deployments a day** with
GitHub Actions, Vercel and end-to-end tests.

**Every Finance** · Senior Full-Stack Engineer, DeFi · 2021<br>
Brought portfolio computation down **from hours to minutes** and automated
full infrastructure deployment on Google Cloud in 20 minutes.

**JimmyFairly** · CTO · 2017–2020<br>
Led a team of 4 engineers on the e-commerce platform. Built event-driven order
processing on Google Cloud and KPI dashboards for headquarters on BigQuery.

**Freelance lead developer** · E-commerce · 2010–2017<br>
Developed **10+ Magento stores** for brands including Pernod Ricard, Boucheron,
Karl Lagerfeld and Kérastase. Wrote 20+ custom extensions for payment, shipping and stock.

## Stack

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-2b3137?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript">
      <img src="https://img.shields.io/badge/JavaScript-2b3137?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
      <img src="https://img.shields.io/badge/Python-2b3137?style=flat-square&logo=python&logoColor=FFD43B" alt="Python">
      <img src="https://img.shields.io/badge/Solidity-2b3137?style=flat-square&logo=solidity&logoColor=white" alt="Solidity">
      <img src="https://img.shields.io/badge/SQL-2b3137?style=flat-square&logo=postgresql&logoColor=4169E1" alt="SQL">
    </td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-2b3137?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
      <img src="https://img.shields.io/badge/Next.js-2b3137?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/Tailwind%20CSS-2b3137?style=flat-square&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS">
      <img src="https://img.shields.io/badge/shadcn%2Fui-2b3137?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui">
      <img src="https://img.shields.io/badge/TanStack%20Query-2b3137?style=flat-square&logo=reactquery&logoColor=FF4154" alt="TanStack Query">
    </td>
  </tr>
  <tr>
    <td><b>Backend &amp; data</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-2b3137?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js">
      <img src="https://img.shields.io/badge/NestJS-2b3137?style=flat-square&logo=nestjs&logoColor=E0234E" alt="NestJS">
      <img src="https://img.shields.io/badge/GraphQL-2b3137?style=flat-square&logo=graphql&logoColor=E10098" alt="GraphQL">
      <img src="https://img.shields.io/badge/PostgreSQL-2b3137?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/Drizzle-2b3137?style=flat-square&logo=drizzle&logoColor=C5F74F" alt="Drizzle">
      <img src="https://img.shields.io/badge/Redis-2b3137?style=flat-square&logo=redis&logoColor=FF4438" alt="Redis">
      <img src="https://img.shields.io/badge/BigQuery-2b3137?style=flat-square&logo=googlebigquery&logoColor=669DF6" alt="BigQuery">
    </td>
  </tr>
  <tr>
    <td><b>Web3</b></td>
    <td>
      <img src="https://img.shields.io/badge/Ethereum-2b3137?style=flat-square&logo=ethereum&logoColor=white" alt="Ethereum">
      <img src="https://img.shields.io/badge/Stellar-2b3137?style=flat-square&logo=stellar&logoColor=white" alt="Stellar">
      <img src="https://img.shields.io/badge/wagmi-2b3137?style=flat-square&logo=wagmi&logoColor=white" alt="wagmi">
    </td>
  </tr>
  <tr>
    <td><b>AI engineering</b></td>
    <td>
      <img src="https://img.shields.io/badge/Claude%20Code-2b3137?style=flat-square&logo=claude&logoColor=D97757" alt="Claude Code">
      <img src="https://img.shields.io/badge/MCP-2b3137?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP">
      <img src="https://img.shields.io/badge/Cursor-2b3137?style=flat-square&logo=cursor&logoColor=white" alt="Cursor">
      <img src="https://img.shields.io/badge/GitHub%20Copilot-2b3137?style=flat-square&logo=githubcopilot&logoColor=white" alt="GitHub Copilot">
    </td>
  </tr>
  <tr>
    <td><b>Cloud &amp; delivery</b></td>
    <td>
      <img src="https://img.shields.io/badge/Google%20Cloud-2b3137?style=flat-square&logo=googlecloud&logoColor=4285F4" alt="Google Cloud">
      <img src="https://img.shields.io/badge/Vercel-2b3137?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
      <img src="https://img.shields.io/badge/Docker-2b3137?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker">
      <img src="https://img.shields.io/badge/Kubernetes-2b3137?style=flat-square&logo=kubernetes&logoColor=326CE5" alt="Kubernetes">
      <img src="https://img.shields.io/badge/Terraform-2b3137?style=flat-square&logo=terraform&logoColor=844FBA" alt="Terraform">
      <img src="https://img.shields.io/badge/GitHub%20Actions-2b3137?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions">
    </td>
  </tr>
  <tr>
    <td><b>Quality &amp; monitoring</b></td>
    <td>
      <img src="https://img.shields.io/badge/Vitest-2b3137?style=flat-square&logo=vitest&logoColor=FCC72B" alt="Vitest">
      <img src="https://img.shields.io/badge/Sentry-2b3137?style=flat-square&logo=sentry&logoColor=white" alt="Sentry">
      <img src="https://img.shields.io/badge/Datadog-2b3137?style=flat-square&logo=datadog&logoColor=white" alt="Datadog">
      <img src="https://img.shields.io/badge/PostHog-2b3137?style=flat-square&logo=posthog&logoColor=F9BD2B" alt="PostHog">
    </td>
  </tr>
</table>

---

<div align="center">

**Open to Staff and Founding Engineer roles · Paris**

<a href="https://www.linkedin.com/in/cedricmagne/"><img src="https://img.shields.io/badge/Hiring%3F-Message%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&labelColor=1f2328&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D" alt="Message me on LinkedIn"></a>
<a href="https://rness.dev/docs"><img src="https://img.shields.io/badge/Try%20Rness-npm%20create%20rness-4ade80?style=for-the-badge&labelColor=0C0E10&logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMTIwIiBoZWlnaHQ9IjEyMCIgdmlld0JveD0iMCAwIDEyMCAxMjAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHRpdGxlPlJuZXNzIFIsIHdoaXRlPC90aXRsZT48cGF0aCBkPSJNMzguMzMgNzkuM0MzOC4zMyA4MC45NTY5IDM2Ljk4NjkgODIuMyAzNS4zMyA4Mi4zSDIxQzE5LjM0MzEgODIuMyAxOCA4MC45NTY5IDE4IDc5LjNWMjJDMTggMjAuMzQzMSAxOS4zNDMxIDE5IDIxIDE5SDU3LjY1QzYyLjM3IDE5IDY2LjMxIDE5Ljk1MzMgNjkuNDcgMjEuODZDNzIuNjMgMjMuNzYgNzUuMDA2NyAyNi4yNDMzIDc2LjYgMjkuMzFDNzguMTkzMyAzMi4zNzY3IDc4Ljk5IDM1LjY4NjcgNzguOTkgMzkuMjRDNzguOTkgNDMuMjkzMyA3OC4wNCA0Ni44OTY3IDc2LjE0IDUwLjA1Qzc0LjcyMTQgNTIuNDA5MyA3Mi45MjU3IDU0LjQxNzQgNzAuNzUyOCA1Ni4wNzQzQzY5LjQ5MjcgNTcuMDM1MiA2OC45NjU1IDU4Ljc0MjggNjkuNjc4MyA2MC4xNTgxTDc4LjYzOTQgNzcuOTUwNUM3OS42NDQzIDc5Ljk0NTcgNzguMTk0IDgyLjMgNzUuOTYgODIuM0g1OS45NTE3QzU4Ljc3NTMgODIuMyA1Ny43MDc0IDgxLjYxMjQgNTcuMjIwNiA4MC41NDE1TDQ5LjE1OTQgNjIuODA4NUM0OC42NzI2IDYxLjczNzYgNDcuNjA0NyA2MS4wNSA0Ni40MjgzIDYxLjA1SDQxLjMzQzM5LjY3MzEgNjEuMDUgMzguMzMgNjIuMzkzMSAzOC4zMyA2NC4wNVY3OS4zWk00MS4zMyAzMy40NUMzOS42NzMxIDMzLjQ1IDM4LjMzIDM0Ljc5MzEgMzguMzMgMzYuNDVWNDMuOTdDMzguMzMgNDUuNjI2OCAzOS42NzMxIDQ2Ljk3IDQxLjMzIDQ2Ljk3SDUyLjU5QzU0LjE4MzMgNDYuOTcgNTUuNTMzMyA0Ni4zNDMzIDU2LjY0IDQ1LjA5QzU3Ljc0IDQzLjgzIDU4LjI5IDQyLjE1NjcgNTguMjkgNDAuMDdDNTguMjkgMzguNzgzMyA1OC4wNDY3IDM3LjY1IDU3LjU2IDM2LjY3QzU3LjA2NjcgMzUuNjkgNTYuMzkgMzQuOTA2NyA1NS41MyAzNC4zMkM1NC42NzY3IDMzLjc0IDUzLjY5NjcgMzMuNDUgNTIuNTkgMzMuNDVINDEuMzNaIiBmaWxsPSIjZjRmNGY1Ii8%2BPHBhdGggZD0iTTc1LjY5IDcyLjhDNzguOTEgNzkuMjQgNzkuNTkgNzcuOCA4Ni4xOSA3Ny44SDk4LjE5Qzk5LjI1MDkgNzcuOCAxMDAuMjY4IDc4LjIyMTQgMTAxLjAxOCA3OC45NzE2QzEwMS43NjkgNzkuNzIxNyAxMDIuMTkgODAuNzM5MSAxMDIuMTkgODEuOFY5Ny44QzEwMi4xOSA5OC44NjA5IDEwMS43NjkgOTkuODc4MyAxMDEuMDE4IDEwMC42MjhDMTAwLjI2OCAxMDEuMzc5IDk5LjI1MDkgMTAxLjggOTguMTkgMTAxLjhIODIuMTlDODEuMTI5MSAxMDEuOCA4MC4xMTE3IDEwMS4zNzkgNzkuMzYxNiAxMDAuNjI4Qzc4LjYxMTQgOTkuODc4MyA3OC4xOSA5OC44NjA5IDc4LjE5IDk3LjhWODcuM0M3OC4xOSA4MS4zIDcyLjY5IDgxLjggNjYuNjkgODEuOEw3NS42OSA3Mi44WiIgZmlsbD0iI2Y0ZjRmNSIvPjwvc3ZnPgo%3D" alt="Try Rness"></a>

</div>
