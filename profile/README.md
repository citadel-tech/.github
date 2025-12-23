# Citadel Tech

![Citadel Tech Logo](./logo.png)

**Next Gen Sovereign Tech Stack**

Citadel maintains a set of libraries and binaries for various Bitcoin protocols, aiming to enhance individual sovereignty in the new digital panopticon.

## About

We focus on building protocols on top of Bitcoin and other sidechains/L2s that provide a bridge between unconnected layers like Bitcoin, Lightning, Ecash, Liquid, etc, without requiring a trusted third party. These protocols and tools allow more sovereign user access on these layers, reduce centralisation risks while also incentivising node-runners to put their stale liquidity at work to earn more sats. 

Coinswap, being our first foundational protocol which facilitates the first `btc<>btc` perr-to-peer decentralised atomic swaps without trusted third parties. The market itself remains censorship-resistant as it's seeded in the Bitcoin blockchain. Anyone with access to a sovereign node can participate in the market. 

While the core protocol only works on the Bitcoin blockchain, a generalised version of the protocol will be used to bridge between multiple layers—increasing liquidity flow across layers, increasing user sovereignty, reducing network centralisation, while also incentivising individual home node-runners.

## Core Projects

*Core libraries and applications*

| Project | Repository | Description |
|---------|------------|-------------|
| **Coinswap** | [coinswap](https://github.com/citadel-tech/coinswap) | Functioning, minimal-viable binaries and libraries to perform a trustless, p2p Maxwell-Belcher Coinswap Protocol |
| **Coinswap-FFI** | [coinswap-ffi](https://github.com/citadel-tech/coinswap-ffi) | FFI Interface for the Coinswap client library |
| **Taker-App** | [taker-app](https://github.com/citadel-tech/taker-app) | An example desktop client built in Nodejs using the coinswap-ffi |
| **Coinswap-Docker** | [coinswap-docker](https://github.com/citadel-tech/coinswap/blob/master/docs/docker.md) | Pre-configured Docker setup with `bitcoind(Mutinynet)`, `Tor`, `makerd`, and `maker-cli`, for quick deployment of makers |

## Documentation & Research

*Protocol specifications and experimental implementations*

| Project | Repository | Description |
|---------|------------|-------------|
| **Protocol Specification** | [Coinswap-Protocol-Specification](https://github.com/citadel-tech/Coinswap-Protocol-Specification) | Technical specification for the coinswap protocol |


## Community

Open source is fundamental to our mission and we would love to connect with you.

Join our [Discord server](https://discord.gg/VSTapAXePb) to discuss development, ask questions, and contribute to advancing Bitcoin sovereignty tools!
