# CoralSwap Finance

**Next-generation AMM on Stellar.  Dynamic fees. Flash loans. Soroban-native.**

---

CoralSwap is a decentralized exchange protocol built on [Stellar](https://stellar.org) / [Soroban](https://soroban.stellar.org). It extends the proven Uniswap V2 constant-product model with two protocol-level innovations:

- **Dynamic Fee Engine** -- fees auto-adjust between 0.10 % and 1.00 % based on real-time EMA volatility, protecting LPs during turbulent markets and lowering costs in stable conditions.
- **Flash Loan Engine** -- single-transaction uncollateralized loans baked into the Pair contract with per-token repayment checks, a 5 bps fee floor, and a 256-byte data cap.

## Repositories

| Repo | Purpose |
|------|---------|
| [`coralswap-core`](https://github.com/CoralSwap-Finance/coralswap-core) | Soroban smart contracts (Factory, Pair, LP Token, Router, Flash Receiver Interface) |
| [`coralswap-frontend`](https://github.com/CoralSwap-Finance/coralswap-frontend) | dApp UI for swaps, liquidity, and pool management |
| [`coralswap-sdk`](https://github.com/CoralSwap-Finance/coralswap-sdk) | TypeScript SDK for programmatic protocol interaction |
| [`coralswap-docs`](https://github.com/CoralSwap-Finance/coralswap-docs) | Developer docs, guides, and API reference |

## Architecture Highlights

- Uniswap V2 constant-product AMM (x * y = k)
- EMA-based volatility tracking with asymmetric cooldown and stale-decay
- 14-point security hardening (reentrancy guard, circuit breaker, multi-sig governance, timelocked upgrades, and more)
- 2-of-3 multi-sig governance with timelocked admin actions
- Contracts written in Rust, compiled to Soroban WASM

## Status

**Pre-launch** -- contracts under active development.

## Links

- Website: *coming soon*
- Docs: *coming soon*
- Twitter: *coming soon*

---

Built on Stellar. Powered by Soroban.
