Hard Wiki

A cryptographically‑secured ledger of machine‑verifiable knowledge on Base L2.

X @HardWikiOrg

⸻

⚡️ Why Hard Wiki?

Large language models hallucinate; scientific outputs often lack structured, verifiable proofs. Hard Wiki aligns zero‑knowledge proofs, proof‑of‑personhood, and financial staking to create an immutable, challenge‑able, AI‑readable knowledge graph.

(Deep dive in the litepaper https://www.hardwiki.org/litepaper)

⸻

🛠️ MVP Scope

This repository will eventually host ✦ smart contracts, ✦ CLI tooling, ✦ reference dApp, ✦ SDKs, and ✦ DevOps/scripts.

Status: Pre‑alpha — team formation & design discussion in progress.

Planned folders

Path	Contents
/contracts/	Solidity sources (ClaimRegistry, StakeVault, PremisePackRegistry…)
/cli/	Rust / Node CLI for bundling, submitting & challenging claims
/web/	React + TypeScript front‑end
/sdk/	TypeScript & Python client libraries
/docs/	Architecture diagrams, ADRs, specifications
/infra/	Deployment & CI/CD (Foundry, Hardhat, GitHub Actions)


⸻

📚 Architecture Snapshot (v0)
	•	Base L2 (OP‑Stack) — primary execution, SNARK verification
	•	Ethereum L1 — settlement & finality bridge
	•	Arweave / Filecoin / IPFS — artefact storage (CID‑addressed)
	•	World ID — Sybil‑resistant proof‑of‑personhood
	•	ZK Frameworks — Groth16 & Plonk for theorem/computation verification

See /docs/architecture.md (coming soon) for diagrams and deep dives.

⸻

🗺️ Roadmap

Phase	Milestone	Target
0	Base Testnet (CLI + web α)	
1	Token Launch & Mainnet	
2	Replication DAO (Experiments)	
3	Multi‑Chain Mirrors	
4	Commercial Services	

(Roadmap excerpts — see litepaper §13 for full details.)

⸻

🤝 Contributing

We welcome contributors of all backgrounds — cryptography, smart contracts, front‑end, DevOps, and technical writing.
⭐ Star the repo to follow progress.

All interactions follow our community guidelines — be excellent to each other.

⸻

🔒 Security

If you discover a vulnerability, do not open a public issue. Instead, email Hello@hardwiki.org or DM @HardWikiOrg on X to coordinate responsible disclosure.

⸻

📄 License
	•	Protocol contracts & ZK code: Apache‑2.0
	•	CLI & Reference Front‑end: MIT
	•	Enterprise dashboards & services: Proprietary (see litepaper §11)

⸻

Made with ❤️ by the Hard Wiki community — “Anchoring humanity’s most rigorous knowledge in code.”
