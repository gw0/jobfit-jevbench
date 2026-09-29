# Rhiannon Vasquez
London, UK (Hybrid) | rhiannon.vasquez@example.com | github.com/rvasquez-chain | linkedin.com/in/rhiannonvasquez

## Summary
Staff-level Blockchain Engineer, 12 yrs total (7+ focused purely on chain infra/consensus). Deep Rust background originally from systems/networking before pivoting into distributed ledger work around 2016-17. Comfortable across the stack - protocol design, validator client internals, Solidity contract layer, and the gnarly bits in between (mempool propagation, fork-choice, gas metering). Have shipped consensus changes to production networks handling real economic value, not just testnets. Strong opinions on BFT vs Nakamoto consensus tradeoffs, will argue about it happily.

## Skills
- **Languages:** Rust (expert, 9 yrs), Solidity (advanced, 6 yrs), Go (working knowledge), some C++ from early career, TypeScript for tooling/scripts
- **Consensus/Protocol:** Tendermint/CometBFT internals, HotStuff variants, PBFT, Proof-of-Stake validator design, fork-choice rules (LMD-GHOST), slashing conditions, finality gadgets
- **Blockchain-specific:** EVM internals, gas optimization, smart contract security patterns, substrate/Cosmos SDK, libp2p, gossip protocols
- Cryptography (applied, not academic) - BLS signatures, Merkle proofs, threshold signing schemes
- Infra: Kubernetes, Docker, Prometheus/Grafana for validator monitoring, Terraform
- Testing: property-based testing (proptest), fuzzing (cargo-fuzz), formal-ish verification exposure (not a specialist)

## Experience

### Staff Engineer, Consensus Team - Northgale Protocol Labs
*London (hybrid) | Mar 2021 - Present*
- Led redesign of validator fork-choice module in Rust, cut reorg frequency by ~40% under adversarial network partition testing
- Own the BFT consensus core (~35k LOC Rust) - onboarded 4 engineers onto the codebase, wrote most of the internal docs (there weren't any before)
- Drove Solidity-side changes to staking/slashing contracts after an incident where slashing was miscalculated for correlated downtime - post-mortem, fix, redeploy all inside one sprint
- Represent the team in cross-chain interop working groups, some public speaking at conferences (Devconnect 2023, small panel)

### Senior Blockchain Engineer - Wyrecross Systems
*Remote (UK-based) | Jun 2018 - Feb 2021*
- Built mempool gossip layer from scratch in Rust for a new L1, handled ~2k tx/sec sustained in load tests
- Solidity work on bridge contracts, this is also where I learned the hard way about reentrancy (caught in audit, thankfully, not prod)
- Mentored 2 junior engineers, one is now a staff eng elsewhere

### Backend/Infra Engineer - Halloway & Finch Data Systems
*London | Sep 2016 - May 2018*
- Not blockchain-native role but this is where I got pulled into a crypto side project internally that became my full pivot
- Distributed systems fundamentals - Kafka, consensus-adjacent work on leader election for internal data pipeline
- Rust adoption pilot project, one of first at the company

### Software Engineer - Perrin Vale Technologies
*Manchester | Jul 2013 - Aug 2016*
- Early career, C++ and Python, general backend work
- No blockchain exposure here but good grounding in systems programming

## Education
**MEng, Computer Science** - University of Bristol, 2013
- Final year project touched on distributed systems fault tolerance, didn't know at the time it'd be relevant later

**Various:** Certificates from a couple of online cryptography courses (Coursera-type things), not going to pretend these are equivalent to a PhD but they filled gaps
