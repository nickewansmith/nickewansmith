<p align="center">
  <img src="./assets/header.svg" alt="Hi, I'm Nick — senior blockchain & TypeScript engineer" width="100%" />
</p>

<p align="center">
  <a href="https://metatron.sh"><img src="https://img.shields.io/badge/Building-Metatron_Automata-0A0E0D?style=for-the-badge&labelColor=1FD17A" alt="Metatron Automata" /></a>
  <a href="https://embend.com"><img src="https://img.shields.io/badge/Building-Embend-0A0E0D?style=for-the-badge&labelColor=FED100" alt="Embend" /></a>
  <a href="mailto:nickewansmith@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-0A0E0D?style=for-the-badge&labelColor=7E938A" alt="Email" /></a>
</p>

---

### ⚡ Selected work

I helped build **MetaMask Perps** (perpetual futures trading inside MetaMask Mobile, on Hyperliquid) across the stack, from controller and data layer to the screens traders use.

<a href="https://github.com/MetaMask/metamask-mobile/pull/19726">
  <img src="./assets/featured-tpsl.svg" alt="Position-bound TP/SL for MetaMask Mobile Perps — PR #19726" width="100%" />
</a>

> **The problem:** MetaMask Mobile ties TP/SL to a position, but Hyperliquid's order book treats them as separate orders. Once a user added to a position or stacked multiple TP/SL sets, the app couldn't work out which ones applied, so they showed as **“Not set.”**
>
> **The fix (Solution B):** TP/SL orders bound to the position that **resize automatically** with it. Users can manage TP/SL from the position page even when several orders exist, and never have to re-size them by hand.
>
> [`893b916`](https://github.com/MetaMask/metamask-mobile/commit/893b9166ed2f144ab9c70d9354755246d9afdbad) · [PR #19726](https://github.com/MetaMask/metamask-mobile/pull/19726) · Sep 15, 2025

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/MetaMask/metamask-mobile/pull/17688"><img src="./assets/card-history.svg" alt="Perps transaction history — PR #17688" width="100%" /></a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/MetaMask/metamask-mobile/pull/18545"><img src="./assets/card-portfolio.svg" alt="Perps balances in the wallet portfolio — PR #18545" width="100%" /></a>
</td>
</tr>
</table>

<a href="https://github.com/XRPLF/xrpl.js/pull/1186">
  <img src="./assets/card-xrpl.svg" alt="xrpl.js WebSocket cleanup fix — PR #1186" width="100%" />
</a>

<details>
<summary><b>📜 The details</b></summary>
<br />

| Repo | Change | Why it mattered |
|---|---|---|
| `MetaMask/metamask-mobile` | [Position-bound TP/SL (#19726)](https://github.com/MetaMask/metamask-mobile/pull/19726) | Diagnosed a release-risking mismatch between MetaMask's position-based UI and Hyperliquid's separate orders, then proposed and shipped the fix the team adopted |
| `MetaMask/metamask-mobile` | [Perps transaction history (#17688)](https://github.com/MetaMask/metamask-mobile/pull/17688) | End-to-end feature: Fills, Orders and Funding history with provider and controller data fetching, lists, detail screens, fee breakdowns and explorer links |
| `MetaMask/metamask-mobile` | [Perps balance + P&L (#18545)](https://github.com/MetaMask/metamask-mobile/pull/18545) | Wired Perps account value and 24h history into portfolio calculations with persisted Redux state, and added unrealized P&L to the Perps tab |
| `XRPLF/xrpl.js` | [Socket close-handler fix (#1186)](https://github.com/XRPLF/xrpl.js/pull/1186) · [`c17827e`](https://github.com/XRPLF/xrpl.js/commit/c17827e030fec150bff22035cfccf8b38315c820) | Registered the close listener before post-connect work, ending a reconnect error loop in a widely used SDK, with a regression test for failed setup |

</details>

---

### 🛠️ What I'm building

<table>
<tr>
<td width="50%" valign="top">

#### [Metatron Automata](https://metatron.sh)
An AI-driven, multi-tenant trading platform, built as a composition engine for timestamped event streams. Trading is the first vertical.

`cell-based multi-tenancy` `venue adapters` `non-custodial delegated signing` `fill-to-settle state machines`

</td>
<td width="50%" valign="top">

#### [Embend](https://embend.com)
Finance compliance as an always-on monitoring agent that runs inside the customer's own systems, rather than another app to sign up for and connect.

`compliance` `AI agents` `deep integration`

</td>
</tr>
</table>

---

### 🧭 Where I've shipped

<img src="./assets/career.svg" alt="Previously at MetaMask, BitPay, PROOF, Plastiq, Condé Nast" width="100%" />

---

### 🧰 Toolbox

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity" />
  <img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white" alt="Ethereum" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Agent SDK" />
  <img src="./assets/badge-rust.svg" alt="Rust (learning)" height="20" />
</p>

---

### 🤝 Let's talk

- 👯 **Collaborate with me on** trading automation
- 🤔 **Looking for help with** ML
- 💬 **Ask me about** parenting
- 📫 **Reach me at** [nickewansmith@gmail.com](mailto:nickewansmith@gmail.com)
- 😄 **Pronouns:** he/him
- 🇯🇲 **Fun fact:** Jamaican roots

<p align="center">
  <a href="https://ghfind.com/u/nickewansmith?ref=badge"><img src="https://ghfind.com/api/card/mini/nickewansmith" alt="GitHub Roast score card" width="440" /></a>
</p>
