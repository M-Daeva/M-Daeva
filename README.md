## M. Daeva — Solana & Rust Smart Contract Developer

I build and harden on-chain lending infrastructure: protocol integrations via raw CPI,
integration test suites against real third-party programs, audit remediation, and
multisig-based contract administration. Anchor by default, Pinocchio when the compute
budget matters.

**Selected production work**
- Integrated Kamino Lending into [XPlace](https://x.place/), a Solana crypto-backed Visa card:
  hand-written CPI, partial account deserialization, klend built from source with a
  full-flow LiteSVM test suite
- Migrated XPlace's lending integration from Drift to Kamino and took the protocol through
  two FYEO audits
- Maintained a vesting contract holding $20M TVL; IDO contracts handling $400K in sales
  and 2,000 participants per launch event
- Designed [GopLend](https://github.com/cryptogopniks/GopLend), an NFT lending protocol
  with oracle staleness guards, share-based receipt tokens and a prioritized liquidation bid market

**Recent**
- [Meteora Coinflip](https://github.com/M-Daeva/Meteora-Coinflip) — Anchor program that turns
  a fair coinflip bet into a Meteora DBC / DAMM v2 swap: raw CPI without crates, balance-delta
  accounting, ORAO VRF, LiteSVM tests against real program dumps

**Open source**
- [Pinocchio](https://github.com/anza-xyz/pinocchio) — Token-2022 extensions interface ([#330](https://github.com/anza-xyz/pinocchio/pull/330), [#333](https://github.com/anza-xyz/pinocchio/pull/333))
- [LiteSVM](https://github.com/LiteSVM/litesvm) test suite adopted in Turbin3 development ([#6](https://github.com/Turbin3/pinocchio-extensions/pull/6))
- [Solana Kite](https://github.com/solanakite/kite-rust) — Rust API improvements ([#2](https://github.com/solanakite/kite-rust/pull/2))
- [Codama](https://github.com/codama-idl/codama-rs) — IDL generator issue reports ([#27](https://github.com/codama-idl/codama-rs/issues/27), [#29](https://github.com/codama-idl/codama-rs/issues/29))

**Stack:** Rust · Anchor · Pinocchio · Token-2022 · LiteSVM · TypeScript · Solana Kit · Codama

Open to Solana smart contract roles — embedmad@gmail.com · [Telegram](https://t.me/m_daeva)
