## Cassian Obi
Staff Blockchain Engineer | San Francisco, CA (on-site)
cassian.obi@example.com | 415-555-0148 | github.com/cobi-chain | linkedin.com/in/cassianobi

### Summary
12 yrs eng, last 8 in blockchain/distributed systems. built and shipped consensus layers, validator clients, gas metering, EVM-adjacent stuff, also solidity contracts handling 9-figure TVL. comfortable owning a protocol from whitepaper -> mainnet. deep rust, deep solidity, byzantine fault tolerance, gossip protocols, state sync -- the whole stack really. staff-level means i unblock teams not just write code, done that too.

### Skills
- **Languages:** Rust (primary, 8yrs), Solidity (7yrs), Go (secondary), some C++ for perf-critical paths
- **Consensus:** Tendermint/CometBFT, HotStuff variants, PBFT, Raft (pre-blockchain era), custom BFT tuning, leader election, slashing conditions
- Distributed systems: gossip protocols, vector clocks, CRDTs, gRPC, libp2p
- EVM internals, gas optimization, bytecode-level debugging
- security: reentrancy, oracle manipulation, MEV mitigation -- audited ~40 contracts informally
- infra: k8s, terraform, prometheus/grafana for validator monitoring
- cryptography: BLS sigs, threshold signatures, merkle/verkle trees, zk basics (not an expert, can read circom)

### Experience

**Staff Blockchain Engineer -- Ferrovax Labs** (San Francisco, CA) | 2021-Present
- led rewrite of consensus client from Go->Rust, cut block finality time 40%, this was a 14mo project across 3 teams
- designed slashing + validator rotation logic for a 200+ validator PoS network, zero downtime incidents since launch
- wrote the solidity staking contracts, formal verification via Certora, no critical findings in 2 external audits
- mentored 6 engineers, ran the internal "consensus reading group"
- on-call rotation lead for mainnet, handled a chain-halt incident (network partition, not our bug, but we shipped the fix)

**Senior Blockchain Engineer -- Obsidian Chain Labs** | 2017-2021
built the p2p networking layer from scratch (libp2p based), also:
- shipped a novel BFT variant paper internally, some of it made it into prod
- solidity: wrote the bridge contracts connecting to ETH mainnet, handled ~$40M in bridged assets
- reduced state sync time for new nodes from 6hrs to 45min via snapshot-based sync
- interviewed 80+ candidates, built out the eng team from 4 to 22

**Blockchain / Backend Engineer -- Kestrel Systems** (SF) | 2014-2017
- not blockchain from day 1 -- joined as backend eng (rust + postgres), pivoted team into crypto in 2015
- built early prototype of a permissioned ledger, PoC only, never shipped but taught me a lot
- rust systems programming, high throughput matching engine (finance-adjacent, fintech company)

### Education
**B.S. Computer Science** -- Caldera Polytechnic Institute, 2013
(thesis was on distributed hash tables, not blockchain, blockchain wasn't really a thing yet lol)

### Misc
speak at conferences occasionally (Devcon-adjacent stuff, regional ones), contribute to a couple rust crates for BLS aggregation
