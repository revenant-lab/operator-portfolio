# Revenant — Web3 Builder | Exploit Simulations | dApp Operator

## 💻 Projects

### ⚡ Revenant Flashloan Executor
- **Scope**: Full-stack MEV bot framework for DeFi exploitation, simulations, and profit extraction
- **Core Capabilities**:
  - Aave V3 / Radiant flashloan engine
  - Multi-hop arbitrage across UniswapV2/V3, Curve
  - GPT-automated route generation (`gptRouter`)
  - Simulation of arb + liquidation paths with revert introspection
  - Reusable execution engine (`simulateBundle`, `bundleSender`, `traceReverts`)
- **Innovations**:
  - Fully atomic execution via Flashbots
  - Step-level outcome tracing, gas profiling, and strategy hashing
  - “Dry-run” simulation of profitable paths pre-execution
- **Tech Stack**: Solidity, Hardhat, Node.js, ethers.js v6, GPT-4o turbo logic
- **Repo**: [revenant-flashloan-executor](https://github.com/revenant-lab/revenant-flashloan-executor)
- **Impact**: Foundation for a live, AI-reactive MEV infrastructure

### 🔒 Gnosis Safe Module Scanner
- Detects enabled modules and evaluates exploit paths
- Automated ABI bruteforce
- Repo: [GitHub Link]
- Result: Used to scan >100 safes on-chain for module hijacks

### ⛓️ Token + Staking Stack
- Built token + staking dApp in 24h
- React + Hardhat
- Live demo on [testnet URL]

---

## 🔗 Contacts
- TG: @revenant_ops
- GitHub: github.com/revenant-dev
