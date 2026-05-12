# Citadel Tech

![Citadel Tech Logo](./logo.png)

**Next Gen Sovereign Tech Stack**

## About

We build protocols and interfaces on Bitcoin and related L2s to deliver interoperability, availability, and security benefits for users of the global Bitcoin network. Aiming to create the __**Open Source Bitcoin Freedom Stack**__, that the internet needs so desperately right now. 

Built with love by diverse communities of open source developers from the Global South, in pure FOSS licenses.  

Coinswap, being our first foundational protocol, facilitates decentralized atomic swaps without trusted third parties.

## Core Projects

*Core libraries and applications*

| Project | Repository | Description |
|---------|------------|-------------|
| **Coinswap** | [coinswap](https://github.com/citadel-tech/coinswap) | Functioning, minimal-viable binaries and libraries to perform a trustless, p2p [Maxwell-Belcher Coinswap Protocol](https://gist.github.com/chris-belcher/9144bd57a91c194e332fb5ca371d0964) |
| **Coinswap-FFI** | [coinswap-ffi](https://github.com/citadel-tech/coinswap-ffi) | FFI Interface for the Coinswap client library |
| **Taker App** | [taker-app](https://github.com/citadel-tech/taker-app) | An example desktop client built in Nodejs using the coinswap-ffi |
| **Maker Dashboard** | [maker-dashboard](https://github.com/citadel-tech/maker-dasboard) | A GUI dashboard for Maker managements, dockerized to run in home nodes |
| **Coinswap-Docker** | [coinswap-docker](https://github.com/citadel-tech/coinswap/blob/master/docs/docker.md) | Pre-configured Docker setup with `bitcoind(Mutinynet)`, `Tor`, `makerd`, and `maker-cli`, for quick deployment of makers |

*Auxiliary Infrastructures*

| Project | Repository | Description |
|---------|------------|-------------|
| **mill-io** | [mill-io](https://github.com/citadel-tech/mill-io) | A lightweight performant io library in rust, for efficient non-blocking io operations without heavyweight async runtimes |
| **rust-coinselect** | [rust-coinselect](https://github.com/citadel-tech/rust-coinselect) | A coinselection library in rust to perform CS via multiple algorithms and choose the best result based on waste-metrics, inspired from CS algorithms of Bitcoin Core |


## Documentation & Research

*Protocol specifications and experimental implementations*

| Project | Repository | Description |
|---------|------------|-------------|
| **Protocol Specification** | [Coinswap-Protocol-Specification](https://github.com/citadel-tech/Coinswap-Protocol-Specification) | Technical specification for the coinswap protocol |


## Community

Open source is fundamental to our mission and we would love to connect with you.

Join our [Matrix server](https://matrix.to/#/#ciatdel-foss:matrix.org) to discuss development, ask questions, and contribute to advancing Bitcoin sovereignty tools!
