# 🌌 Wiracocha Labs

Wiracocha Labs is an open-source research and incubation organization focused
on decentralized infrastructure. We build tools that return control to
communities — starting from Latin America, thinking globally.

We are currently one person, building in public.

---

## ✨ Vision

AI and digital infrastructure are concentrating in the hands of a few
corporations. Access to the most powerful tools depends on expensive hardware,
constant connectivity, and paying per query.

We believe this is an architectural decision, not an inevitability.

Wiracocha Labs researches and builds the alternative: decentralized networks,
AI models that run on modest hardware, and tools that work without a central
owner. Our 10-year goal is a decentralized AI model that lives in a P2P
network — not in a datacenter, not owned by anyone.

We are not waiting for someone else to build it.

---

## 🛠️ Principles

- **Open source** — everything we build is open and shared (AGPL-3.0).
- **Users first** — we build for people, not metrics.
- **Honesty over hype** — we document what works and what doesn't.
- **Decentralization** — we seek alternatives to the concentration of power.
- **Privacy where needed, transparency where it matters.**
- **Technology is not separate from the human being.**

---

## 🚀 Projects

### [Chasqui](https://github.com/wiracocha-labs/chasqui-app) — `In development`

Decentralized communication platform for remote teams. Combines encrypted
messaging, private smart contracts on Avalanche (eERC20 escrow, ZK proofs),
AI-powered chat summaries, and GitHub/GitLab webhook integrations. A free,
private alternative to Slack built for teams that value decentralization.

Chasqui is Wiracocha Labs' first commercial product. A percentage of its
revenue funds the organization's research.

**Stack:** Vue 3 + TypeScript · Solidity · Rust · Avalanche

---

### [quipu-ipfs](https://github.com/wiracocha-labs/quipu-ipfs) — `In development`

Decentralized P2P network built in Rust. Generic layer of identity, storage,
and transport for decentralized applications. The core does not know what a
"message" or "post" is — it only knows how to sign, store, and route signed
objects between cryptographic identities.

First use case: encrypted P2P messaging. Long-term: a platform for third
parties to build their own decentralized apps on top.

**Stack:** Rust · libp2p · ed25519 · ChaCha20-Poly1305

---

### [Chaka](https://github.com/wiracocha-labs/chaka) — `Researching`

*Chaka* means "bridge" in Quechua.

Research on delta compression between model versions for efficient
synchronization between nodes in a decentralized P2P network with modest,
heterogeneous hardware (old laptops, Raspberry Pi). The specific gap we
are investigating: existing federated learning research evaluates compression
under static membership, homogeneous devices, and fixed bandwidth — not the
real-world case of dynamic topology and modest hardware that Wiracocha Labs
targets.

**Stack:** Rust

---

### [Yachay](https://github.com/wiracocha-labs/yachay) — `Released (v0.1.0)`

*Yachay* means "knowledge" in Quechua.

A local AI model recommender: selects the right open-source model for your
hardware and your actual task. No downloading what you don't need, no paying
for what you don't use. First target users: developers running local AI on
older hardware.

MVP CLI released as v0.1.0 — pre-compiled binaries for macOS, Linux, and
Windows.

---

## 🛤️ Roadmap

No dates — verifiable milestones.

### Phase 0 — Foundations `In progress`
- Base architectures for Chaka and quipu-ipfs established.
- First public repos with documented architecture decisions.
- Chasqui in active development.
- Yachay MVP released (v0.1.0, installers for macOS/Linux/Windows).

**Exit criterion:** `cargo build` passes on all repos; Chasqui MVP functional.

### Phase 1 — First deliverables `Planned`
- Chasqui launched and generating first revenue.
- Two quipu-ipfs nodes communicating on a local network via mDNS.
- First delta compression experiments documented in Chaka.

**Exit criterion:** someone outside the project can install and use each tool
without touching the code.

### Phase 2 — Real network `Planned`
- quipu-ipfs working between nodes on the real internet (Kademlia DHT).
- Encrypted P2P messaging as first user-facing product on quipu-ipfs.
- First Chaka research results published (delta compression benchmarks
  on real models, compared against zstd baseline).

**Exit criterion:** two nodes on different home networks discover each other
and communicate without a central server.

### Phase 3 — Platform `Planned`
- quipu-ipfs documented as an SDK for third-party apps.
- Reference app demonstrating that the core is genuinely app-agnostic.
- Chaka integrated with quipu-ipfs for model distribution between nodes.

**Exit criterion:** a third-party app runs on quipu-ipfs without modifying
the core crates.

### Phase 4 — Decentralized AI `Horizon (~10 years)`
- An AI model that lives in the network, not in a datacenter.
- No corporate owner. Accessible from modest hardware.
- Informed by what the research in Chaka and the infrastructure of
  quipu-ipfs actually make possible — not by today's assumptions.

---

## 📬 Contact

📧 wiracochalabs@protonmail.com
🐙 [github.com/wiracocha-labs](https://github.com/wiracocha-labs)
📸 [instagram.com/wiracocha_labs](https://www.instagram.com/wiracocha_labs/)

---

## 🌱 How to contribute

1. Read the repo of the project you want to contribute to.
2. Open an issue or propose a PR.
3. Share the project with someone who believes this matters.
4. If you want to support financially — funding options coming soon.

---

## ⚡ Tech stack

- **Language:** Rust 🦀 (infrastructure and research)
- **Frontend:** Vue 3 + TypeScript (Chasqui)
- **Blockchain:** Avalanche + Solidity (Chasqui payments/escrow)
- **P2P:** libp2p (quipu-ipfs)
- **Philosophy:** build in public, document honestly, research what others ignore.

---

*Named after Wiracocha — the Andean creator deity. Built from Latin America,
for everyone.*
