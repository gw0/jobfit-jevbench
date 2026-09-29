# Temitope Chiedozie
Lagos, Nigeria (Remote) | temitope.chiedozie@example.com | github.com/tchiedozie | +234 803 555 0192

## Summary
Blockchain engineer, ~4yrs, Rust + Solidity, obsessed with consensus correctness and gas-tight contracts. Shipped validator clients and L2 tooling for small teams, comfortable going from whitepaper math to production code. Remote-first, distributed teams (EU/US overlap hours), Lagos-based.

## Skills
- **Languages:** Rust (primary, ~4y), Solidity (~3y), Go (basic, tooling only), some Python for scripts/sims
- **Consensus/Protocols:** BFT variants (Tendermint-style), PoS validator design, leader election, fork-choice rules, gossip protocols (libp2p)
- Smart contracts: ERC20/721/1155, upgradeable proxies (UUPS), reentrancy/invariant testing, Foundry + Hardhat
- Infra: Docker, systemd for validator nodes, Prometheus/Grafana for node monitoring, basic k8s
- Other: gas optimization, static analysis (Slither, Mythril), fuzzing (Echidna)

## Experience

### Kaduna Chain Labs — Blockchain Engineer (Remote)
*Mar 2023 – Present*
- built out a Rust validator client module handling block proposal + vote gossip for a PoS testnet, reduced missed-slot rate from ~6% to under 1% after reworking timeout handling
- wrote Solidity staking + slashing contracts, full Foundry test suite incl. invariant tests, caught a reentrancy bug pre-audit that would've drained rewards pool
- ran node ops for ~40 validators across testnet upgrades, wrote runbooks (nobody read them but me)
- collaborated w/ protocol researchers on fork-choice tweaks, implemented a modified GHOST variant in Rust

### Obudu Ledger Systems — Smart Contract / Backend Dev
*Jul 2021 – Feb 2023*
- solidity dev for a DeFi lending protocol, wrote and audited liquidation logic, oracle integration (Chainlink), handled edge cases around price staleness
- migrated legacy Truffle setup to Hardhat, cut CI test time by half
- gas optimization pass across core contracts saved ~18% avg tx cost — mostly storage packing and fewer SLOADs
- also did some backend Rust work (actix-web) for internal indexing service, not my main thing but did it anyway

### Freelance / Various Contracts
*Jan 2021 – Jun 2021*
- short contracts building ERC721 marketplace contracts for two different startups (both since folded, unrelated to my work as far as I know)
- one gig doing security review of a friend's contract before mainnet launch — found an access control bug, they fixed it

## Education
**University of Lagos** — B.Sc. Computer Science, 2020
- final year project: simplified PBFT simulator in Python (before I knew Rust, embarrassing in hindsight)

## Notes
- comfortable reading consensus papers and going straight to implementation, less interested in frontend/UI work
- open to relocating for right role but prefer remote
