# Alistair Mercer
Staff Blockchain Engineer | London, UK (hybrid) | alistair.mercer@example.com | +44 7700 900482 | linkedin.com/in/alistairmercer

## Summary
12 yrs, started in distributed systems / backend infra before blockchain was a thing, moved into crypto ~2015. Staff-level, deep in Rust + Solidity, consensus protocols (BFT/PoS variants), have shipped things that actually run in production handling real value not just testnets. Comfortable owning architecture end to end - protocol design, client implementation, security review, incident response. Hybrid in London, happy to be in office 2-3x/wk, also fine remote-heavy if the team is distributed (most of mine have been).

## Skills
- **Languages:** Rust (primary, 8+ yrs), Solidity (7 yrs), Go, some C++, Python for tooling/scripts
- Distributed consensus - BFT, Tendermint-style, HotStuff, PoS validator design, fork-choice rules, finality gadgets
- EVM internals, gas optimization, bytecode-level debugging
- Node clients - built and maintained full node + light client software
- Cryptography: BLS signatures, threshold sigs, VRF, zk basics (not a ZK specialist but conversant)
- p2p networking (libp2p), gossip protocols
- Security: audits (led + participated), formal verification exposure (Certora, some TLA+)
- CI/CD, k8s, observability for validator infra (uptime is existential here)
- Mentoring / technical leadership, RFC writing, cross-team protocol design reviews

## Experience

### Staff Engineer, Consensus - **Fenwick Chain Labs**, London — 2021–Present
- Led redesign of validator client consensus module (Rust) cutting missed-block rate by ~40% under network partition scenarios
- Owns the finality gadget implementation, on-call rotation for validator infra (99.95% uptime target, met it most quarters)
- Wrote the internal spec for slashing conditions v2 - went through 6 rounds of review with external auditors before merge
- mentoring 3 mid-level engineers, ran onboarding for the protocol team

### Senior / Lead Protocol Engineer — **Nordhaven Distributed Systems**, London (some remote) — 2017-2021
- Solidity + Rust hybrid role. Built settlement layer contracts handling >$400M TVL at peak (2021)
- designed and implemented custom BFT variant for a permissioned sidechain used by 3 enterprise clients
- Incident: caught a reentrancy-adjacent bug in pre-audit review that would've been bad, wrote it up, became part of internal training material
- Interviewed and hired ~15 engineers over this period, built out the protocol team from 4 to 14

### Blockchain / Backend Engineer — **Whitfield & Ashby Systems**, London — 2015-2017
- transitioned from general distributed backend work into blockchain here. Early Solidity (pre-0.5.0!), built out internal Ethereum tooling
- worked on private/consortium chain PoC for a financial services client (never went to prod but was a good learning ground)

### Software Engineer, Backend/Infra — **Carrow Data Systems**, Reading — 2013-2015
- distributed messaging systems, Kafka-adjacent stuff, Java/Scala mostly (pre-Rust era for me)
- this is where I got interested in consensus/CAP theorem type problems, led directly to the blockchain pivot

## Education
**BSc Computer Science** — University of Bristol, 2009-2013
- Dissertation touched on distributed systems fault tolerance, relevant in hindsight

## Other
- occasional conference talks (local meetups, one DevCon-adjacent lightning talk ~2019)
- reviewed a couple of EIPs informally, never authored one myself (should fix that)
