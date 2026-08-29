# Awesome Sui with stars

<a href="https://sui.io/"><img alt="Sui logo" src="media/logo.svg" align="right" width="150" /></a>

> A curated list of *awesome* developer tools and infrastructure projects within the Sui ecosystem.

Sui is the first Blockchain built for internet scale, enabling fast, scalable, and low-latency transactions. It's programmable and composable, powered by the Move language, making it easy to build and integrate dApps. Sui prioritizes developer experience and frictionless user interactions, designed to support next-gen decentralized applications with minimal complexity.

> ⚠️ This warning icon means that the tool may not be functioning correctly at the moment. Please check these tools carefully.

[**Submit your own developer tool here**](CONTRIBUTING.md)

## Contents

* [Move IDEs](#move-ides)
  * [Web IDEs](#web-ides)
  * [Desktop IDEs](#desktop-ides)
  * [IDE Utilities](#ide-utilities)
* [Client SDKs & Libraries](#client-sdks--libraries)
  * [Client SDKs](#client-sdks)
  * [DeFi SDKs](#defi-sdks)
  * [Client Libraries](#client-libraries)
* [dApp Development](#dapp-development)
  * [dApp Toolkits](#dapp-toolkits)
  * [Smart Contract Toolkits](#smart-contract-toolkits)
* [Indexers & Data Services](#indexers--data-services)
* [Explorers](#explorers)
* [Oracles](#oracles)
* [Security](#security)
* [AI](#ai)
* [Infrastructure as Code](#infrastructure-as-code)
* [Faucets](#faucets)

## Move IDEs

### Web IDEs

* BitsLab IDE - Online Move code editor that requires no configuration and supports Move code syntax highlighting. Beginner friendly and supports interacting with Sui.
  * [Homepage](https://www.bitslab.xyz/bitslabide) - [IDE](https://ide.bitslab.xyz/) - [Tutorial](https://www.youtube.com/watch?v=-9-WkqQwtu8) - [Further Information](details/ide_bitslab.md)
* ChainIDE - Move Cloud-Powered Development Platform.
  * [Homepage](https://chainide.com) - [Documentation](https://chainide.gitbook.io/chainide-english-1/ethereum-ide-1/9.-sui-ide) - [IDE](https://chainide.com/s/sui) - [Further Information](details/ide_chainide.md)

### Desktop IDEs

* [Emacs move-mode](https://github.com/amnn/move-mode) ⭐ 19 | 🐛 4 | 🌐 Emacs Lisp | 📅 2025-12-24 - The move-mode package is an Emacs major-mode for editing smart contracts written in the Move programming language.
* [Move.vim](https://github.com/yanganto/move.vim) ⭐ 5 | 🐛 0 | 🌐 Vim Script | 📅 2025-01-09 - Syntax highlighting that supports the Move 2024 edition.
* VSCode Move by Mysten Labs - VSCode Extension supports Move on Sui development with LSP features through Move Analyzer developed by Mysten Labs.
  * [GitHub](https://github.com/MystenLabs/sui/tree/main/external-crates/move/crates/move-analyzer) ⭐ 7,740 | 🐛 824 | 🌐 Rust | 📅 2026-08-29 - [Documentation & Tutorial](https://marketplace.visualstudio.com/items?itemName=mysten.move) - [Further Information](details/ide_vscode_mysten_move_analyzer.md)
* VSCode Sui Move Analyzer by MoveBit - Alternative VSCode extension developed by MoveBit.
  * [Homepage](https://movebit.xyz/analyzer) - [GitHub](https://github.com/movebit/sui-move-analyzer) ⭐ 40 | 🐛 4 | 🌐 Rust | 📅 2026-02-25 - [Documentation & Tutorial](https://marketplace.visualstudio.com/items?itemName=MoveBit.sui-move-analyzer) - [Further Information](details/ide_vscode_movebit_sui_move_analyzer.md)
* IntelliJ Sui Move Language Plugin - IntelliJ-based plugin for Move on Sui development.
  * [Homepage](https://plugins.jetbrains.com/plugin/23301-sui-move-language) - [GitHub](https://github.com/movefuns/intellij-move) ⭐ 69 | 🐛 10 | 🌐 Kotlin | 📅 2025-08-23

### IDE Utilities

* [Prettier Move Plugin](https://github.com/MystenLabs/sui/tree/main/external-crates/move/crates/move-analyzer/prettier-plugin) ⭐ 7,740 | 🐛 824 | 🌐 Rust | 📅 2026-08-29 - A Move language plugin for the Prettier code formatter.
* [Tree Sitter Move](https://github.com/MystenLabs/sui/tree/main/external-crates/move/tooling/tree-sitter) ⭐ 7,740 | 🐛 824 | 🌐 Rust | 📅 2026-08-29 - Tree Sitter for Move. [What is tree sitter](https://tree-sitter.github.io/tree-sitter/).
* [Sui Extension](https://github.com/zktx-io/sui-extension) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-19 - The Sui extension provides seamless support for compiling, deploying, and testing Sui smart contracts directly within VS Code.
  * [Homepage](https://marketplace.visualstudio.com/items?itemName=zktxio.sui-extension) - [Documentation](https://docs.zktx.io/vsce/sui/)
* ⚠️ Sui Simulator - VSCode Extension to streamline Sui development workflow with intuitive UI.
  * [Homepage](https://marketplace.visualstudio.com/items?itemName=weminal-labs.sui-simulator-vscode) - [GitHub](https://github.com/Weminal-labs/sui-simulator-vscode) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2024-06-23 - [Demo](https://www.youtube.com/watch?v=BHRxeF_visM\&pp=ygUMd2VtaW5hbCBsYWIg)

## Client SDKs & Libraries

### Client SDKs

* Sui TypeScript SDK (Mysten Labs) - TypeScript modular library of tools for interacting with the Sui Blockchain.
  * [GitHub](https://github.com/MystenLabs/ts-sdks/tree/main/packages/typescript) ⭐ 97 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-28 - [Documentation](https://sdk.mystenlabs.com/typescript) - [Further Information](details/sdk_sui_typescript.md)
* Sui Kit(Scallop) - Toolkit for interacting with the Sui network in TypeScript.
  * [GitHub](https://github.com/scallop-io/sui-kit) ⭐ 187 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-28 - [Further Information](details/sdk_sui_kit_scallop.md)
* Sui Rust SDK (Mysten Labs) - Rust SDK to interact with Sui Blockchain.
  * [GitHub](https://github.com/MystenLabs/sui/tree/main/crates/sui-sdk) ⭐ 7,740 | 🐛 824 | 🌐 Rust | 📅 2026-08-29 - [Documentation](https://mystenlabs.github.io/sui/sui_sdk/index.html) - [Further Information](details/sdk_sui_rust.md)
* Pysui - Python SDK to interact with Sui Blockchain.
  * [GitHub](https://github.com/FrankC01/pysui?tab=readme-ov-file) ⭐ 212 | 🐛 2 | 🌐 Python | 📅 2026-08-25 - [Documentation](https://pysui.readthedocs.io/en/latest/index.html) - [Pypi](https://pypi.org/project/pysui/) - [Discord](https://discord.gg/uCGYfY4Ph4) - [Further Information](details/sdk_pysui.md)
* Sui Go SDK (SuiVision) - Golang SDK to interact with Sui Blockchain.
  * [GitHub](https://github.com/block-vision/sui-go-sdk) ⭐ 198 | 🐛 15 | 🌐 Go | 📅 2026-08-12 - [API Documentation](https://pkg.go.dev/github.com/block-vision/sui-go-sdk) - [Examples](https://github.com/block-vision/sui-go-sdk?tab=readme-ov-file#examples) ⭐ 198 | 🐛 15 | 🌐 Go | 📅 2026-08-12 - [Further Information](details/sdk_sui_go.md)
* Sui Go SDK (Pattonkan) - Golang SDK to interact with Sui Blockchain. Support PTB and devInspect.
  * [GitHub](https://github.com/pattonkan/sui-go) ⭐ 12 | 🐛 14 | 🌐 Go | 📅 2026-04-11 - [API Documentation](https://pkg.go.dev/github.com/pattonkan/sui-go) - [Examples](https://github.com/pattonkan/sui-go/tree/main/examples) ⭐ 12 | 🐛 14 | 🌐 Go | 📅 2026-04-11 - [Further Information](details/go_sui.md)
* Sui Dart SDK - Dart SDK to interact with Sui Blockchain.
  * [GitHub](https://github.com/mofalabs/sui) ⭐ 37 | 🐛 0 | 🌐 Dart | 📅 2026-08-15 - [API documentation](https://pub.dev/documentation/sui/latest/) - [Further Information](details/sdk_sui_dart.md)
* Sui Kotlin SDK - Kotlin Multiplatform (KMP) SDK for integrating with the Sui Blockchain.
  * [GitHub](https://github.com/mcxross/ksui) ⭐ 18 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-18 - [Documentation](https://suicookbook.com) - [Further Information](details/sdk_ksui.md)
* SuiKit (OpenDive) - Swift SDK natively designed to make developing for the Sui Blockchain easy.
  * [GitHub](https://github.com/opendive/suikit?tab=readme-ov-file) ⭐ 22 | 🐛 19 | 🌐 Swift | 📅 2025-12-11 - [Further Information](details/sdk_suikit.md)
* Sui Unity SDK (OpenDive) - The OpenDive Sui Unity SDK is the first fully-featured Unity SDK with offline transaction building.
  * [GitHub](https://github.com/OpenDive/Sui-Unity-SDK) ⭐ 22 | 🐛 14 | 🌐 C# | 📅 2025-11-12 - [Further Information](details/sdk_sui_unity_opendive.md)
* Dubhe Client (Dubhe Engine) - Supports various platforms including browsers, Node.js, and game engine. It provides a simple interface to interact with your Sui Move contracts.
  * [GitHub](https://github.com/0xobelisk/dubhe/tree/main/packages/sui-client) ⭐ 73 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-05 - [Documentation](https://dubhe-docs.obelisk.build/)

### DeFi SDKs

* [Cetus CLMM SDK](https://github.com/CetusProtocol/cetus-clmm-sui-sdk) ⭐ 69 | 🐛 8 | 🌐 TypeScript | 📅 2025-02-28 - The official Cetus SDK specifically designed for seamless integration with Cetus-CLMM on Sui.
* [Scallop SDK](https://github.com/scallop-io/sui-scallop-sdk) ⭐ 56 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-28 - The TypeScript SDK for interacting with the Scallop lending protocol on the Sui network.
* [NAVI Protocol SDK](https://github.com/naviprotocol/navi-sdk) ⭐ 47 | 🐛 7 | 🌐 TypeScript | 📅 2026-03-04 - The NAVI TypeScript SDK Client provides tools for interacting with the Sui Blockchain networks, designed for handling transactions, accounts, and smart contracts efficiently.
* [7k Aggregator SDK](https://github.com/7k-ag/7k-sdk-ts) ⚠️ Archived - The TypeScript SDK for interacting with 7k Aggregator protocol.
* [Aftermath SDK](https://github.com/AftermathFinance/aftermath-ts-sdk) ⭐ 28 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-28 - The TypeScript SDK for interacting with Aftermath Protocol.
* [Bucket Protocol SDK](https://github.com/Bucket-Protocol/bucket-protocol-sdk) ⭐ 21 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-21 - The TypeScript SDK for interacting with Bucket Protocol.
* [FlowX SDK](https://github.com/FlowX-Finance/sdk) ⭐ 2 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-29 - The official FlowX TypeScript SDK that allows developers to interact with FlowX protocols using the TypeScript programming language.
* [Suilend SDK](https://github.com/suilend/suilend-fe-public/tree/main/sdk) - The TypeScript SDK for interacting with the Suilend program published on npm as [`@suilend/sdk`](https://www.npmjs.com/package/@suilend/sdk).
* [Hop Aggregator SDK](https://docs.hop.ag/hop-sdk) - The TypeScript SDK for interacting with Hop Aggregator.

### Client Libraries

* Sui Wallet Standard (Mysten Labs) - A suite of standard utilities for implementing wallets and libraries based on the [Wallet Standard](https://github.com/wallet-standard/wallet-standard/) ⭐ 362 | 🐛 25 | 🌐 TypeScript | 📅 2026-06-03.
  * [GitHub](https://github.com/MystenLabs/ts-sdks/tree/main/packages/wallet-standard) ⭐ 97 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-28 - [Documentation](https://docs.sui.io/standards/wallet-standard)
* [Sui Client Gen (Kuna Labs)](https://github.com/kunalabs-io/sui-client-gen/tree/master) ⭐ 104 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-26 - A tool for generating TS SDKs for Sui Move smart contracts. Supports code generation both for source code and on-chain packages with no IDLs or ABIs required.
* [TypeMove (Sentio)](https://github.com/sentioxyz/typemove/blob/main/packages/sui/Readme.md) ⭐ 52 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-28 - Generate TypeScript bindings for Sui contracts.
* [BCS Rust](https://github.com/zefchain/bcs) ⭐ 35 | 🐛 5 | 🌐 Rust | 📅 2026-04-25 - BCS with Rust.
* [BCS Swift](https://github.com/OpenDive/SuiKit/tree/main/Sources/SuiKit/Utils/BCS) ⭐ 22 | 🐛 19 | 🌐 Swift | 📅 2025-12-11 - BCS with Swift.
* [BCS Unity](https://github.com/OpenDive/Sui-Unity-SDK/tree/main/Assets/Sui-Unity-SDK/Code/OpenDive.BCS) ⭐ 22 | 🐛 14 | 🌐 C# | 📅 2025-11-12 - BCS with Unity C#.
* [CoinMeta (Polymedia)](https://github.com/juzybits/polymedia-coinmeta) ⭐ 7 | 🐛 5 | 🌐 TypeScript | 📅 2025-02-23 - Library for fetching coin metadata for Sui coins.
* [BCS Dart](https://github.com/mofalabs/bcs) ⭐ 2 | 🐛 0 | 🌐 Dart | 📅 2026-07-13 - BCS with Dart.
* [Dubhe Client BCS Decoding (Dubhe Engine)](https://github.com/0xobelisk/dubhe-docs/blob/main/pages/dubhe/sui/client.mdx#bcs-data-decoding) ⭐ 0 | 🐛 4 | 🌐 MDX | 📅 2025-08-11 - Library for supports automatic parsing of BCS types based on contract metadata information and automatic conversion formatting.
* [BCS TypeScript (Mysten Labs)](https://sdk.mystenlabs.com/bcs) - BCS with TypeScript.
* BCS Kotlin - BCS with Kotlin.
  * [GitHub](https://github.com/mcxross/kotlinx-serialization-bcs) ⭐ 6 | 🐛 0 | 🌐 Kotlin | 📅 2025-10-11 - [Documentation](https://suicookbook.com/bcs.html)

## dApp Development

### dApp Toolkits

* [create-dubhe (Dubhe Engine)](https://github.com/0xobelisk/dubhe/tree/main/packages/create-dubhe) ⭐ 73 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-05 - Create a new Dubhe project on Sui.
  * [Documentation](https://dubhe.obelisk.build/dubhe/sui/quick-start)
* [Sui Gas Pool (Mysten Labs)](https://github.com/MystenLabs/sui-gas-pool) ⭐ 39 | 🐛 2 | 🌐 Rust | 📅 2026-06-02 - Service that powers sponsored transactions on Sui at scale.
* [Sui dApp Scaffold (Bucket Protocol)](https://github.com/Bucket-Protocol/sui-dapp-scaffold-v1) ⭐ 29 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-10 - A frontend scaffold for a decentralized application (dApp) on the Sui Blockchain.
* [Sui Suitcase](https://github.com/juzybits/polymedia-suitcase) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-05 - Sui utilities for TypeScript, Node, and React.
* [useSuiZkLogin](https://github.com/pixelbrawlgames/use-sui-zklogin) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-05 - React hook and functions for seamless zkLogin integration on Sui.
* [Wormhole Kit (zktx.io)](https://github.com/zktx-io/wormhole-kit-monorepo) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-09-29 - React library that enables instant integration of Wormhole into your dapp.
* [@mysten/create-dapp](https://sdk.mystenlabs.com/dapp-kit/create-dapp) - CLI tool that helps you create Sui dApp projects.
* Sui dApp Kit (Mysten Labs) - Set of React components, hooks, and utilities to help you build a dApp for the Sui ecosystem.
  * [GitHub](https://github.com/MystenLabs/ts-sdks/tree/main/packages/dapp-kit) ⭐ 97 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-28 - [Documentation](https://sdk.mystenlabs.com/dapp-kit)
* Sui dApp Starter - Full-stack boilerplate which lets you scaffold a solid foundation for your Sui project and focus on the business logic of your dapp from day one.
  * [GitHub](https://github.com/suiware/sui-dapp-starter?tab=readme-ov-file) ⭐ 67 | 🐛 5 | 🌐 TypeScript | 📅 2026-02-23 - [Documentation](https://sui-dapp-starter.dev/docs/) - [Demo app](https://demo.sui-dapp-starter.dev/)
* Suiet Wallet Kit - React toolkit for aApps to interact with all wallet types in Sui easily.
  * [GitHub](https://github.com/suiet/wallet-kit) ⭐ 207 | 🐛 40 | 🌐 TypeScript | 📅 2026-06-03 - [Documentation](https://kit.suiet.app/docs/QuickStart)
* [Sui MultiSig Toolkit (Mysten Labs)](https://multisig-toolkit.vercel.app/offline-signer) - Toolkit for transaction signing.
* SuiBase - Suibase makes it easy to create "workdirs", each defining a distinct development environment targeting a network.
  * [GitHub](https://github.com/chainmovers/suibase) ⭐ 51 | 🐛 15 | 🌐 Rust | 📅 2026-08-07 - [Documentation](https://suibase.io/)
* [Sui Tools](https://sui-tools.vercel.app/ptb-generator) - Scaffolding TypeScript PTBs for any on-chain function you might want to invoke.
* [Enoki (Mysten Labs)](https://docs.enoki.mystenlabs.com/) - Make zkLogin and Sponsored Transactions more accessible.
* @suiware/kit - Opinionated React components and hooks for Sui dApps.
  * [Homepage](https://kit.suiware.io/) - [Documentation](https://github.com/suiware/kit/tree/main/packages/kit#readme) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-23 - [GitHub](https://github.com/suiware/kit) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-23
* React ZK Login Kit - Ready-to-use Component with Hook (sign-in + sign-transaction)
  * [GitHub](https://github.com/denyskozak/react-sui-zk-login-kit) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-04 - [YouTube Guide](https://www.youtube.com/watch?v=2qnjmKg3ugY)

#### zkLogin

* [Sui zkLogin Demo by @jovicheng](https://github.com/jovicheng/sui-zklogin-demo) ⭐ 44 | 🐛 2 | 🌐 TypeScript | 📅 2024-12-15
* [zkLogin Demo (Polymedia)](https://github.com/juzybits/polymedia-zklogin-demo) ⭐ 38 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-11
* [Sui zkWallet Demo by @ronanyeah](https://github.com/ronanyeah/sui-zk-wallet) ⭐ 3 | 🐛 1 | 🌐 Elm | 📅 2024-05-31
* [zkLogin Demo using use-sui-zklogin by @pixelbrawlgames](https://pixelbrawlgames.github.io/use-sui-zklogin/)
* [zkLogin Demo using react-zk-login-kit by @denyskozak](https://demo.react-sui-zk-login.com)

#### Misc

* [Polymedia Commando (Polymedia)](https://github.com/juzybits/polymedia-commando) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-14 - Sui command line tools to help with Sui airdrops (send coins to many addresses), gather data from different sources (Sui RPCs, Indexer.xyz, Suiscan), and more.
* [YubiSui (MystenLabs)](https://github.com/MystenLabs/yubigen) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-01-16 - Create a Sui Wallet inside a yubikey and sign Sui transactions with it.
* [Minting Server (Mysten Labs)](https://github.com/MystenLabs/minting-server) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2025-02-14 - A scalable system architecture that can process multiple Sui transactions in parallel using a producer-consumer worker scheme.
* [Sui RPC Proxy](https://github.com/SuiSec/sui-rpc-proxy) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-28 - Monitor and analyze the network requests made by the Sui wallet application and Sui dApps.
* RPC Tools (Polymedia) - A webapp that lets users find the fastest RPC for their location.
  * [GitHub](https://github.com/juzybits/polymedia-rpcs) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-02-25 - [Documentation](https://rpcs.polymedia.app/)
* [`sui-dapp-kit-theme-creator`](https://sui-dapp-kit-theme-creator.app/) - Build custom Sui dApp Kit themes.
* [PTB Studio](https://ptb.studio) - Visual Programmable Transaction Block Builder.
  * [Documentation](https://suicookbook.com/ptb-studio.html)
* [Indexer generator](https://www.npmjs.com/package/sui-events-indexer) - Code generating tool that will generate an indexer given a smart contract for all the events present. After that the user should remove unwanted events and fix the database schema and handlers (that write to the DB) according to their needs. The tool is written in TypeScript and uses Prisma as an ORM.

### Smart Contract Toolkits

* [Move on Sui examples (Mysten Labs)](https://github.com/MystenLabs/sui/tree/main/examples/move) ⭐ 7,740 | 🐛 824 | 🌐 Rust | 📅 2026-08-29 - Examples of Move on Sui applications.
* [Dubhe CLI (Dubhe Engine)](https://github.com/0xobelisk/dubhe/tree/main/packages/sui-cli) ⭐ 73 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-05 - For building, and managing Dapps built on Dubhe Engine in Sui.
  * [Documentation](https://dubhe-docs.obelisk.build/dubhe/sui/cli)
* [Cetus CLMM](https://github.com/CetusProtocol/cetus-contracts/tree/main/packages/cetus_clmm) ⭐ 29 | 🐛 1 | 🌐 Move | 📅 2026-07-09 - The Cetus CLMM DEX open-source code.
* [IntegerMate (Cetus)](https://github.com/CetusProtocol/integer-mate) ⭐ 20 | 🐛 0 | 🌐 Move | 📅 2026-01-22 - A Library of move module provides signed integer and some integer math functions.
* [Sui Codec](https://github.com/sui-potatoes/app/tree/main/packages/codec) ⭐ 13 | 🐛 2 | 🌐 Move | 📅 2026-08-26 - Ultimate encoding solution for Sui.
* [SkipList (Cetus)](https://github.com/CetusProtocol/move-stl) ⭐ 13 | 🐛 1 | 🌐 Move | 📅 2025-10-16 - A skip link list implement by Move language in Sui.
* [SuiDouble Metadata](https://github.com/suidouble/suidouble_metadata) ⭐ 11 | 🐛 0 | 🌐 Move | 📅 2024-11-24 - A Sui Move library and a set of tools to store, retrieve, and manage any type of primitive data as chunks in a `vector<u8>`. Store any data in the `vector<u8>` without dependencies and without any `Struct` defined.
* [Sui Token CLI RPC](https://github.com/otter-sec/sui-token-gen-rpc) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2025-04-30 - A Rust-based RPC service for generating and verifying Sui token smart contracts effortlessly.
  * [Sui Token CLI Tool](https://github.com/otter-sec/sui-token-gen) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2025-04-30 - A Rust-based Command-Line Interface (CLI) tool designed to simplify the process of generating and verifying Sui token smart contracts.
* [Sui CLI](https://docs.sui.io/references/cli) - CLI tool to interact with the Sui network, its features, and the Move programming language.
* [Sentio Debugger](https://docs.sentio.xyz/docs/debugger) - Shows the trace of the transaction [Explorer App](https://app.sentio.xyz/explorer) (mainnet only).
* [`std::debug`](https://docs.sui.io/guides/developer/first-app/debug#related-links) - Print arbitrary values to the console to help with debugging process.
* [Sui Tears 💧 (Interest Protocol)](https://docs.interestprotocol.com/overview/sui-tears) - Open source production ready Sui Move library to increase the productivity of new and experienced developers alike.
* [SuiGPT Decompiler](https://suigpt.tools/decompile) - Uses generative AI to convert Move bytecode back to source code.
* [Revela](https://revela.verichains.io/) - Decompile Sui smart contracts to recover Move source code.
* Package Source Code Verification - Verify your package source code on Suiscan, powered by WELLDONE Studio and Blockberry.
  * [Documentation](https://docs.blockberry.one/docs/contract-verification) - [Form Submission](https://suiscan.xyz/mainnet/package-verification)

## Indexers & Data Services

* ZettaBlock - Generate custom GraphQL or REST APIs from SQL queries and incorporate your private off-chain data.
  * [Homepage](https://zettablock.com/) - [Docs](https://docs.zettablock.com) - [Pricing](https://zettablock.com/pricing) - [Further Information](details/indexer_zettablock.md)
* Sentio - Transform raw indexed data (transactions, events, etc.) into meaningful queryable data by writing custom processor logic.
  * [Homepage](https://www.sentio.xyz/indexer/) - [Documentation](https://docs.sentio.xyz/docs/sui) - [Examples](https://github.com/sentioxyz/sentio-processors/tree/main/projects) ⭐ 31 | 🐛 3 | 🌐 TypeScript | 📅 2026-06-30 - [Further Information](details/indexer_sentio.md)
* BlockVision - Provide Sui indexed data for developers through pre-built APIs, such as, Token, NFT, and DeFi, etc.
  * [Homepage](https://blockvision.org/) - [Documentation](https://docs.blockvision.org/reference/welcome-to-blockvision)
* BlockBerry (Suiscan) - The Blockberry Sui API provides endpoints that reveal data about significant entities on the Sui Network. It indexes useful object metadata, including NFTs, domains, collections, coins, etc. Some data is drawn from third-party providers, particularly market data (coin prices, market cap, etc.).
  * [Homepage](https://blockberry.one/) - [Documentation](https://docs.blockberry.one/reference/sui-quickstart)
* Space And Time (SxT) - Verifiable compute layer for AI x Blockchain. Decentralized data warehouse with sub-second ZK proof.
  * [Homepage](https://www.spaceandtime.io/) - [Documentation](https://docs.spaceandtime.io/) - [Further Documentation](details/indexer_space_and_time.md)
* Birdeye Data Services - Access Crypto Market Data APIs on Sui.
  * [Homepage](https://bds.birdeye.so/) - [Blog](https://blog.sui.io/birdeye-data-services-crypto-api-websocket/) - [API Documentation](https://docs.birdeye.so/reference/intro/authentication)
* Indexer.xyz (behind TradePort) - The ultimate toolkit for accessing NFT data and integrating trading functionality into your app on Sui.
  * [Homepage](https://www.indexer.xyz/) - [API Explorer](https://www.indexer.xyz/api-explorer) - [API Docs](https://tradeport.xyz/docs)
* Dubhe Indexer (Dubhe Engine) - Automatic integration with Dubhe Engine, automatic indexing of all events based on Dubhe Engine to build Dapp on Sui, based on dubhe configuration files.
  * [GitHub](https://github.com/0xobelisk/dubhe/tree/main/crates/dubhe-indexer) ⭐ 73 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-05 - [API Documentation](https://dubhe-docs.obelisk.build/dubhe/sui/indexer)
* Surflux <a href="https://surflux.dev"><img alt="Surflux logo" src="media/surflux_logo.svg" width="15" /></a> - Developer infrastructure for Sui. Build production-ready apps with powerful APIs, indexing, and real-time data streams.
  * [Homepage](https://surflux.dev/) - [Documentation](https://docs.surflux.dev/) - [Blog](https://surflux.dev/blog)

## Explorers

* SuiVision - Data analytics covering transactions, wallets, staking, and validators.
  * [Homepage](https://suivision.xyz/) - [Documentation](https://docs.blockvision.org/reference/integrate-suivision-into-your-dapp) - [Further Information](details/explorer_suivision.md)
* Suiscan - Explorer and analytics platform for Sui.
  * [Homepage](https://suiscan.xyz/mainnet/home) - [Documentation](https://docs.blockberry.one/reference/welcome-to-blockberry-api) - [Further Information](details/explorer_suiscan.md)
* OKLink - Provide fundamental explorer and data APIs on Sui.
  * [Homepage](https://www.oklink.com/sui) - [Further Information](details/explorer_oklink.md)
* Polymedia Explorer - A fork of the original Sui Explorer.
  * [Homepage](https://explorer.polymedia.app) - [GitHub](https://github.com/juzybits/polymedia-explorer) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-09 - [Further Information](details/explorer_polymedia.md)
* PTB Explorer - A fork of the Polymedia Explorer.
  * [GitHub](https://github.com/zktx-io/polymedia-explorer-ptb-builder) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-29
* Local Sui Explorer - Sui Explorer for your localnet maintained by [suiware](https://github.com/suiware)
  * [GitHub](https://github.com/suiware/sui-explorer) ⭐ 18 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-17 - [Further Information](details/explorer_local_sui_explorer.md)
* Suimon - Powerful command line tool designed to provide detailed dashboards for monitoring the Sui network.
  * [GitHub](https://github.com/bartosian/suimon) ⭐ 72 | 🐛 1 | 🌐 Go | 📅 2024-10-16 - [Further Information](details/explorer_suimon.md)

## Oracles

* Pyth Network - Oracle protocol that connects the owners of market data to applications on multiple Blockchains including Sui.
  * [Homepage](https://www.pyth.network/) - [Documentation](https://docs.pyth.network/home) - [Sui Tutorial](https://docs.pyth.network/price-feeds/use-real-time-data/sui) - [Further Information](details/oracle_pyth.md)
* Supra Oracles - Oracle protocol to provide reliable data feed.
  * [Homepage](https://supra.com/) - [Sui Tutorial on Poll Oracle](https://docs.supra.com/oracles/data-feeds/pull-oracle#sui) - [Sui Tutorial on Push Oracle](https://docs.supra.com/oracles/data-feeds/push-oracle#sui-move) - [Further Information](details/oracle_supra.md)
* Switchboard - Data feed customization and management.
  * [Documentation](https://docs.switchboard.xyz/docs-by-chain/sui) - [Further Information](details/oracle_switchboard.md)

## Security

* [Guardians](https://github.com/suiet/guardians) ⭐ 19 | 🐛 3 | 🌐 Python | 📅 2026-01-01 - Phishing Website Protection.
* [HoneyPotDetectionOnSui](https://github.com/SuiSec/HoneyPotDetectionOnSui) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-19 - Detect HoneyPot SCAM on Sui.
* [SuiSecBlockList](https://github.com/SuiSec/SuiSecBlockList) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-22 - Block malicious websites and packages, Identify and hide phishing objects.
* [DryRunTransactionBlockResponsePlus](https://github.com/SuiSec/DryRunTransactionBlockResponsePlus) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-28 - Decorator of `DryRunTransactionBlockResponse`, highlight `SenderChange`.
* <a href="https://info.asymptotic.tech/sui-prover"><img alt="Sui Prover logo" src="media/prover_logo.svg" width="15" /></a> [Sui Prover](https://info.asymptotic.tech/sui-prover) - Prover for doing Formal Verification of Move on Sui code.

## AI

* [Talus](https://docs.talus.network/) - Build autonomous digital economy powered by Sui.
  * [GitHub](https://github.com/Talus-Network) - [Quick Start](https://docs.talus.network/getting-started/math-branching-quickstart)
* [Atoma](https://atoma.network/) - Developer-focused infrastructure for private, verifiable, and fully customized AI experiences.
* [Eliza](https://github.com/elizaOS/eliza) ⭐ 19,206 | 🐛 1,378 | 🌐 TypeScript | 📅 2026-08-29 - Autonomous agents for everyone.

## Infrastructure as Code

* [Dubhe Engine (Obelisk Labs)](https://github.com/0xobelisk/dubhe) ⭐ 73 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-05 - Engine for Everyone to Build Intent-Centric Worlds ⚙️ An Open-Source toolchain for Move Applications.
  * [Documentation](https://dubhe.obelisk.build/) - [Further Information](details/engine_dubhe.md)
* Sui Terraform Modules - All-in-one solution for deploying, monitoring, and managing SUI infrastructure with ease.
  * [GitHub](https://github.com/bartosian/sui-terraform-modules) ⭐ 4 | 🐛 0 | 🌐 HCL | 📅 2024-11-13 - [Further Information](details/iac_sui_terraform_modules.md)

## Faucets

* [Suiware Faucet Chrome Extension](https://github.com/suiware/suiware-faucet-extension) ⭐ 3 | 🐛 2 | 🌐 HTML | 📅 2025-02-23 - An experimental Chrome extension for receiving devnet and testnet SUI.
* [Sui Faucet](https://faucet.sui.io/) - Official web faucet for claiming testnet SUI, with wallet integration.
* [n1stake](https://faucet.n1stake.com/) - Community web faucet for claiming testnet SUI, with wallet integration.
* [Blockbolt](https://faucet.blockbolt.io/) - Community web faucet for claiming testnet SUI, with wallet integration.
* SuiwareFaucetBot - Sui Faucet Bot for Telegram.
  * [GitHub](https://github.com/suiware/SuiwareFaucetBot) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-13 - [Telegram Bot](https://t.me/SuiwareFaucetBot)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
