# TeethakingBuilds

> Building open-source Web3 infrastructure — access control, grants, and bounties on Stellar and Base.

---

## What we build

We ship protocol-level tooling for the decentralized web. Our focus is on making on-chain coordination — authorization, grants, milestones, and payments — accessible, transparent, and trustless.

### Keygate — capability-based access control for Soroban

| Repo | What it does | Stack |
|------|--------------|-------|
| [keygate-contracts](https://github.com/TeethakingBuilds/keygate-contracts) | Capability registry, policy rules, latching circuit breaker, and m-of-n multisig relay | Rust · Soroban |
| [keygate-server](https://github.com/TeethakingBuilds/keygate-server) | Read-only decision server that mirrors on-chain capabilities from Soroban events and answers authorization queries, failing closed | TypeScript |
| [keygate-client](https://github.com/TeethakingBuilds/keygate-client) | SDK to build contract calls, sign authorizations, and verify a server decision before trusting it | TypeScript |

### Grants and bounties

| Repo | What it does | Stack | Chain |
|------|--------------|-------|-------|
| [GrantStream](https://github.com/TeethakingBuilds/GrantStream) | On-chain grant milestone disbursement. Funders lock funds and release them as grantees hit verifiable milestones | Solidity · React · Rust | Base |
| [BountyHex](https://github.com/TeethakingBuilds/BountyHex) | Trustless, automated open-source bounty protocol | Soroban · JavaScript | Stellar |

---

## Tech stack

```
Rust · Soroban SDK · axum · clap
TypeScript · Node.js · React · Vite
Solidity · Hardhat · ethers.js · wagmi
IPFS · Pinata
Stellar · Base
```

---

## Open source

Repos are open for contributions (Apache-2.0 for Keygate, MIT for the rest). We actively participate in:

- **Drips Wave** — open source funding program
- **Stellar ecosystem** — Soroban contract contributions
- **ETH hackathons** — Base, ETHGlobal, and ecosystem sprints

Want to contribute? Pick up any open issue tagged `good first issue` or `help wanted`.

---

## Get in touch

- GitHub: [@teethaking](https://github.com/teethaking)
- Built on Stellar 🌟 · Base 🔵

---

Every line of code ships toward a more trustless, open internet.
