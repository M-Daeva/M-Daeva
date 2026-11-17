## M. Daeva — Solana Smart Contract & Full-Stack Developer

I build Solana dApps end to end: Anchor programs with raw CPI integrations into
third-party protocols, the TypeScript SDKs and backend tooling around them, and
React frontends with wallet integration. Most of my production work is lending
infrastructure that holds user funds, so I care about correctness: integration
tests against real program dumps, audit remediation, and multisig-based contract
administration. Anchor by default, Pinocchio when the compute budget matters.

**Selected production work**
- Integrated Kamino Lending into [XPlace](https://x.place/), a Solana crypto-backed Visa card:
  hand-written CPI, partial account deserialization, klend built from source with a
  full-flow LiteSVM test suite
- Migrated XPlace's lending integration from Drift to Kamino; wrote the TypeScript
  contract-interaction layer used by the backend
- 5 external security audits across two protocols: wrote the audited code and led remediation,
  fixing 33 of 44 findings, including 2 Critical and all 4 High / Severe
  - XPlace: two FYEO audits (Drift and Kamino integrations), nothing above Low
  - Eclipse Fi: [BlockApex](https://github.com/BlockApex/Audit-Reports/blob/master/EclipseFi%20-%20Staking%20v2%20Final%20Audit%20Report.pdf), SCV-Security, [Resonance Security](https://github.com/ResonanceCybersecurity/audits/blob/main/CosmWasm%20Smart%20Contract%20Audits/Audit_Report_ECLP-EQN_FINAL_21.pdf)
- Maintained a vesting contract holding $20M TVL; IDO contracts handling $400K in sales
- Designed [GopLend](https://github.com/cryptogopniks/GopLend), an NFT lending protocol
  with oracle staleness guards, share-based receipt tokens and a prioritized liquidation bid market

**Recent: Meteora Coinflip, a full-stack dApp** ([live demo](https://meteora-coinflip-ui-flax.vercel.app/))
- [Program](https://github.com/M-Daeva/Meteora-Coinflip): Anchor program that turns a fair
  coinflip bet into a Meteora DBC / DAMM v2 swap: raw CPI without crates, balance-delta
  accounting, ORAO VRF, LiteSVM tests against real program dumps
- [Web UI](https://github.com/M-Daeva/Meteora-Coinflip-UI): React 19, Vite, Tailwind CSS v4,
  TanStack Query, Wallet Standard; live balances via websocket subscriptions, resumable bets,
  readable decoding of on-chain and wallet errors

**Open source**
- [Pinocchio](https://github.com/anza-xyz/pinocchio): Token-2022 extensions interface ([#330](https://github.com/anza-xyz/pinocchio/pull/330), [#333](https://github.com/anza-xyz/pinocchio/pull/333))
- [LiteSVM](https://github.com/LiteSVM/litesvm) test suite adopted in Turbin3 development ([#6](https://github.com/Turbin3/pinocchio-extensions/pull/6))
- [Solana Kite](https://github.com/solanakite/kite-rust): Rust API improvements ([#2](https://github.com/solanakite/kite-rust/pull/2))
- [Codama](https://github.com/codama-idl/codama-rs): IDL generator issue reports ([#27](https://github.com/codama-idl/codama-rs/issues/27), [#29](https://github.com/codama-idl/codama-rs/issues/29))

**Stack:** Rust · Anchor · Pinocchio · Token-2022 · LiteSVM · TypeScript · Node.js · React · TanStack Query · Solana Kit · Codama

Open to Solana smart contract and full-stack roles: embedmad@gmail.com · [Telegram](https://t.me/m_daeva)
