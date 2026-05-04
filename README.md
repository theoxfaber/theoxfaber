# Theo Faber

**Software Engineer | Systems & Web3**

I am a software engineer focused on designing and building high-performance, architecturally dense systems. I specialize in systems-level programming with Rust, asynchronous runtimes (Tokio), and deterministic execution environments, primarily within the Web3 and DeFi sectors.

My engineering philosophy centers on rigorous performance optimization, memory safety, and building scalable foundations from the ground up.

---

### 🛠️ Core Technologies
- **Systems & Backend:** Rust, C++, Python
- **Runtimes & Frameworks:** Tokio, Axum, Node.js
- **Web3 Ecosystem:** Solana (Anchor, RPC), Ethereum (EVM, revm, Flashbots)
- **Infrastructure:** Docker, Linux, SQLx, WebSockets

---

### 🏗️ Featured Projects

#### Distributed Systems & DeFi
* **[arbitrage-bot](https://github.com/theoxfaber/arbitrage-bot)**  
  A pure Rust, high-frequency statistical arbitrage simulator. Implements a lock-free `DashMap` orderbook processing sub-millisecond WebSocket feeds (Binance/Bybit) and a native Rust ML heuristic classifier for gap detection.
* **[mev-arbitrage-bot](https://github.com/theoxfaber/mev-arbitrage-bot)**  
  An Ethereum MEV execution engine. Utilizes Bellman-Ford negative-cycle detection for multi-hop DEX arbitrage, integrated tightly with `revm` for local EVM state simulation and Flashbots bundle submission.
* **[SolVault](https://github.com/theoxfaber/SolVault)** *(formerly WebWallet)*  
  A non-custodial, highly secure Solana terminal wallet built natively in Rust. Features BIP39 mnemonic generation, SLIP-0010 ed25519 HD derivation, and AES-256-GCM encrypted local storage using Argon2id key derivation.
* **[solana-defi-sim](https://github.com/theoxfaber/solana-defi-sim)**  
  A Solana DeFi execution engine featuring an Anchor-based PDA gatekeeper protocol and asynchronous Python simulation agents testing cross-program invocations (CPIs).

#### Systems Tooling
* **[replay-proxy](https://github.com/theoxfaber/replay-proxy)**  
  A deterministic HTTP traffic recorder and replay engine written in Rust, leveraging Tokio for low-level TCP/HTTP parsing and deterministic test environment creation.
* **[filemind](https://github.com/theoxfaber/filemind)**  
  A zero-network, local file organizer written in Rust utilizing a deterministic 3-tier classification system.

---

*"Building robust abstractions requires a fundamental mastery of the execution layer."*
