[![banner](https://svg-banners.vercel.app/api?type=typeWriter&text1=8NobleTruths&text2=AI%20agents%20·%20security%20·%20verification&width=900&height=180)](https://github.com/8NobleTruths)

### Hi, I'm 8NobleTruths 👋

I build **AI agents** and **security tooling** with one throughline: making machine-written code **trustworthy**. My work proves a change is real by *running* it, not by scoring how plausible it looks.

<p align="left">
  <a href="https://github.com/8NobleTruths?tab=repositories&sort=stargazers">
    <img alt="total stars" title="Total stars" src="https://custom-icon-badges.demolab.com/github/stars/8NobleTruths?color=55960c&style=for-the-badge&labelColor=488207&logo=star"/></a>
  <a href="https://github.com/8NobleTruths?tab=followers">
    <img alt="followers" title="Follow" src="https://custom-icon-badges.demolab.com/github/followers/8NobleTruths?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a>
  <a href="https://www.npmjs.com/~8nobletruths">
    <img alt="npm" title="npm" src="https://img.shields.io/badge/npm-@8nobletruths-CB3837?style=for-the-badge&logo=npm&logoColor=white"/></a>
</p>

## 🎯 Focus

- 🤖 **Agentic AI** — tools that let coding agents verify their own work before they claim "done"
- 🛡️ **Security** — execution-grounded bug finding and verification, not vibes-based scoring
- ✅ **Proof by execution** — a change earns trust only by building, running, and passing a test that fails without it

## 🚀 Featured

### 🛡️ Sabba: a security bug-finder that proves every finding

<img src="assets/sabba-terminal.svg" alt="Sabba, a security bug-finder that proves every finding" width="820">

**Sabba** finds security bugs and proves each one by triggering it. A model proposes candidates; an execution oracle runs an exploit and reports nothing unless the bug actually reproduces, so a finding is a re-runnable proof, not a score. It works across **C and C++, Solidity and the EVM, Python, Go, Java, and Node**, all under one rule: a finding is minted only from a verdict that the target really crashed. On an EVM fork the chain measures the attacker's profit, not the model. Currently in private development, opening to the public soon.

### ✅ Magga: prove a code change works by running it

<a href="https://github.com/8NobleTruths/magga">
  <img src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=8NobleTruths&repo=magga&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=bc8cff&icon_color=bc8cff" />
</a>

**[Magga](https://github.com/8NobleTruths/magga)** proves a code change actually works by running it. Its core check: a newly added test must **fail on the base** revision and **pass on the head**, so hollow "AI-slop" changes that pass either way are caught. It builds the change, runs the suite, and returns a verdict with evidence, over three surfaces on one engine: a **CLI**, an **MCP server** (an agent verifies its own work), and a **GitHub Action** (a verdict on every pull request). Untrusted pull requests run in a no-network sandbox. Detects 16 languages, 7 exercised end to end in CI.

`npx -y @8nobletruths/magga verify .`

## 🧰 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-1F1F1F?style=for-the-badge)

## 📊 GitHub Stats

<p align="left">
  <img height="180" alt="stats" src="https://denvercoder1-github-readme-stats.vercel.app/api?username=8NobleTruths&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=bc8cff&icon_color=bc8cff"/>
  <img height="180" alt="top languages" src="https://denvercoder1-github-readme-stats.vercel.app/api/top-langs/?username=8NobleTruths&langs_count=8&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=bc8cff&icon_color=bc8cff"/>
</p>

<!-- profile -->
