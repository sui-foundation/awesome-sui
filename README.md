# Awesome Sui [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Directory tracking developer tools and infrastructure projects within Sui ecosystem.

[**Submit your own devtool here**](#submission-guidelines)

## Contents
- [IDEs](#ides)
    - [Web IDEs](#web-ides)
    - [Desktop IDEs](#desktop-ides)
    - [IDE Utilities](#ide-utilities)
- [Client SDKs & Libraries](#client-sdks--libraries)
    - [Client SDKs](#client-sdks)
    - [Client Libraries](#client-libraries)
- [dApp Development](#dapp-development)
    - [dApp Toolkits](#dapp-toolkits)
        - [zkLogin](#zklogin)
        - [Misc](#misc)
    - [Smart Contract Toolkits](#smart-contract-toolkits)
- [Indexers & Data Services](#indexers--data-services)
- [Explorers](#explorers)
- [Oracles](#oracles)
- [AI](#ai)
- [Walrus](#walrus)
- [Submission Guidelines](#submission-guidelines)

## IDEs

### Web IDEs
- [BitsLab IDE](IDE/bitslab_ide.md) - online Move code editor that requires no configuration and supports Move code syntax highlighting, it's beginner-friendly and supports interacting with Sui.
- [MoveStudio](IDE/movestudio.md) - Online IDE for Sui smart contract development.
- [ChainIDE](IDE/chainide.md) - Move Cloud-Powered Development Platform.
- ⚠️ [WELLDONE Code](IDE/welldone_code.md) - Remix IDE plugin supports non-EVM smart contract development including Sui.

### Desktop IDEs
- [VSCode Move by Mysten Labs](IDE/vscode_mysten_move_analyzer.md) - VSCode Extension supports Move on Sui development with LSP features through Move Analyzer developed by Mysten Labs.
- ⚠️ [VSCode Sui Move Analyzer by Movebit](IDE/vscode_movebit_sui_move_analyzer.md) - A fork of VSCode Move by Mysten Labs.
- [IntelliJ Sui Move Language Plugin](IDE/intellij_sui_move_language.md) - IntelliJ-based plugin for Move on Sui development.
- [Emacs move-mode](IDE/emacs_movemode.md) - move-mode is an Emacs major-mode for editing smart contracts written in the Move programming language

### IDE Utilities
- [Prettier Move Plugin](IDE/prettier_move_plugin.md) - a Move language plugin for the Prettier code formatter
- [Sui Extension](IDE/vscode_sui_extension.md) - The Sui extension provides seamless support for compiling, deploying, and testing Sui smart contracts directly within VS Code.
- ⚠️ [Sui Simulator](IDE/vscode_sui_simulator.md) - VSCode Extension to streamline Sui development workflow with intuitive UI.
- [Move.vim](IDE/movevim.md) - Syntax highlighting for the Move smart contract programming language.
- [Tree Sitter Move](IDE/tree_sitter_move.md) - Tree Sitter for Move.

## Client SDKs & Libraries

### Client SDKs
- [Sui Typescript SDK (Mysten Labs)](SDK/sui_typescript_sdk.md) - Typescript modular library of tools for interacting with the Sui blockchain.
- [Sui Rust SDK (Mysten Labs)](SDK/sui_rust_sdk.md) - Rust SDK to interact with Sui blockchain.
- [Pysui](SDK/pysui.md) - Python SDK to interact with Sui blockchain.
- [Sui Go SDK (SuiVision)](SDK/sui_go_sdk.md) - Golang SDK to interact with Sui blockchain.
- [Sui Dart SDK](SDK/sui_dart_sdk.md) - Dart SDK to interact with Sui blockchain.
- [Sui Kotlin SDK](SDK/ksui.md) - Kotlin Multiplatform (KMP) SDK for integrating with the Sui blockchain.
- [SuiKit (OpenDive)](SDK/suikit.md) - Swift SDK natively designed to make developing for the Sui Blockchain easy.
- [Sui Unity SDK (OpenDive)](SDK/sui_unity_sdk_opendive.md) - The OpenDive Sui Unity SDK is the first fully-featured Unity SDK with offline transaction building.

### Client Libraries
- [BCS Typescript (Mysten Labs)](https://sdk.mystenlabs.com/bcs) - BCS with Typescript.
- [BCS Rust]((https://github.com/zefchain/bcs)) - BCS with Rust.
- [BCS Dart](https://github.com/mofalabs/bcs) - BCS with Dart.
- [BCS Kotlin](https://github.com/mcxross/kotlinx-serialization-bcs) - BCS with Kotlin
- [BCS Swift](https://github.com/OpenDive/SuiKit/tree/main/Sources/SuiKit/Utils/BCS) - BCS with Swift
- [BCS Unity](https://github.com/OpenDive/Sui-Unity-SDK/tree/main/Assets/Sui-Unity-SDK/Code/OpenDive.BCS) - BCS with Unity C#
- [Sui Client Gen (KunaLabs)](https://github.com/kunalabs-io/sui-client-gen/tree/master) - A tool for generating TS SDKs for Sui Move smart contracts. Supports code generation both for source code and on-chain packages with no IDLs or ABIs required.
- [TypeMove (Sentio)](https://github.com/sentioxyz/typemove/blob/main/packages/sui/Readme.md) - Generate TypeScript bindings for Sui contracts.
- [Sui Wallet Standard (Mysten Labs)](SDK/sui_wallet_standard.md) - A suite of standard utilities for implementing wallets and libraries based on the [Wallet Standard](https://github.com/wallet-standard/wallet-standard/).
- [CoinMeta (Polymedia)](https://github.com/juzybits/polymedia-coinmeta) - Library for fetching coin metadata for Sui coins

## dApp Development

### dApp Toolkits
- [@mysten/create-dapp](https://sdk.mystenlabs.com/dapp-kit/create-dapp) - CLI tool that helps you create Sui dApp projects.
- [Sui dApp Kit (Mysten Labs)](dApp%20Development/sui_dapp_kit.md) - Set of React components, hooks, and utilities to help you build a dApp for the Sui ecosystem.
- [Sui dApp Starter](dApp%20Development/sui_dapp_starter.md) - Full-stack boilerplate which let you scaffold a solid foundation for your Sui project and focus on the business logic of your dapp from day one.
- [Suiet Wallet Kit](dApp%20Development/suiet_wallet_kit.md) - Suiet wallet kit is an awesome react toolkit for DApps to interact with all the wallets in Sui💧 easily 🥳.
- [SmartKit](https://smartkit.vercel.app/) - React library that allows your dapp to connect to the Sui network in a simple way. [Github](https://github.com/heapup-tech/smartkit)
- [Sui Suitcase](https://github.com/juzybits/polymedia-suitcase) - Sui utilities for TypeScript, Node, and React.
- [Sui MultiSig Toolkit (Mysten Labs)](https://multisig-toolkit.vercel.app/offline-signer) - Toolkit for transaction signing.
- [Wormhole Kit(zktx.io)](https://github.com/zktx-io/wormhole-kit-monorepo) - React library that enables instant integration of Wormhole into your dapp.
- [SuiBase](dApp%20Development/suibase.md) - Streamlines development and testing of your Sui network apps.
- ⚠️ [Obelisk Engine (Beta)](https://obelisk.build/engine/docs) - Framework for ambitious Move applications. It compresses the complexity of building Move apps with a tightly integrated software stack. [Github](https://github.com/0xobelisk/obelisk-engine)
- [Sui Tools](https://sui-tools.vercel.app/ptb-generator) - Scaffolding Typescript PTBs for any on-chain function you might want to invoke.
- [Enoki (MystenLabs)](https://docs.enoki.mystenlabs.com/) - Make zkLogin and Sponsored Transactions more accessible.
- [Sui Gas Pool (MystenLabs)](https://github.com/MystenLabs/sui-gas-pool) - Service that powers sponsored transactions on Sui at scale.

#### zkLogin
- [zkLogin Demo (Polymedia)](https://github.com/juzybits/polymedia-zklogin-demo)
- [Sui zkLogin Demo by @jovicheng](https://github.com/jovicheng/sui-zklogin-demo)
- [Sui zkWallet Demo by @ronanyeah](https://github.com/ronanyeah/sui-zk-wallet)

#### Misc
- [`sui-sniffer`](https://www.app.kriya.finance/sui-sniffer/) - Checking security of Sui tokens.
- [RPC Tools (Polymedia)](https://rpcs.polymedia.app/) - A webapp that lets users find the fastest RPC for their location. [Github](https://github.com/juzybits/polymedia-rpcs)
- [Polymedia Commando (Polymedia)](https://github.com/juzybits/polymedia-commando) - Sui command line tools to help with Sui airdrops (send coins to many addresses), gather data from different sources (Sui RPCs, Indexer.xyz, Suiscan), and more.
- [YubiSui (MystenLabs)](https://github.com/MystenLabs/yubigen) - Create a Sui Wallet inside a yubikey and sign Sui transactions with it.
- [`sui-dapp-kit-theme-creator`](https://sui-dapp-kit-theme-creator.app/) - Build custom Sui dApp Kit themes
- [Minting Server (Mysten Labs)](https://github.com/MystenLabs/minting-server) - A scalable system architecture that can process multiple Sui transactions in parallel using a producer-consumer worker scheme
- [SuiInfra](https://suinfra.io/) - Provide users and developers with up-to-date recommendations on the ideal RPCs to use for their needs.
- [SuiSec](https://suisec.vercel.app/) - Series of security tools to protect users from hacker attacks. [Github](https://github.com/SuiSec/SuiSecToolkit)

### Smart Contract Toolkits
- [Sui CLI](https://docs.sui.io/references/cli) - CLI tool to interact with the Sui network, its features, and the Move programming language.
- [Sentio Debugger](https://docs.sentio.xyz/docs/debugger) - Shows the trace of the transaction [Explorer App](https://app.sentio.xyz/explorer)(mainnet only).
- [`std::debug`](https://docs.sui.io/guides/developer/first-app/debug#related-links) - Print arbitrary values to the console to help with debugging process.
- [Sui Tears 💧 (Interest Protocol)](https://docs.interestprotocol.com/overview/sui-tears) - Open source production ready Sui Move library to increase the productivity of new and experienced developers alike.
- [Sui Codec](https://github.com/sui-potatoes/app/tree/main/packages/codec) - Ultimate encoding solution for Sui.
- [SuiDouble Metadata](https://github.com/suidouble/suidouble_metadata) - A Sui Move library and a set of tools to store, retrieve, and manage any type of primitive data as chunks in a `vector<u8>`. Store any data in the `vector<u8>` without dependencies and without any `Struct` defined.
- [Move on Sui examples (Mysten Labs)](https://github.com/MystenLabs/sui/tree/main/examples/move) - Examples of Move on Sui applications.
- [SuiGPT Decompiler](https://suigpt.tools/decompile) - Use latest generative AI to convert Move Bytecode back to Source Code.
- [Revela](https://revela.verichains.io/) - Decompile Sui smart contracts to recover Move source code.
- [Package Source Code Verification (WELLDONE Studio)](https://twitter.com/suiscanofficial/status/1775931534878621737) - Verify your package source code on [SuiScan](https://suiscan.xyz/mainnet/package-verification)

## Indexers & Data Services
- [ZettaBlock](Indexer/zettablock.md) - Generate custom GraphQL or REST APIs from SQL queries and incorporate your private off-chain data.
- [Sentio](Indexer/sentio.md) - Transform raw indexed data (transactions, events,...) into meaningful queryable data by writing custom processor logic.
- [BlockVision (SuiVision)](Indexer/blockvision.md) - Provide Sui indexed data for developers through pre-built APIs, such as, Token, NFT, and DeFi,...
- [BlockBerry (SuiScan)](Indexer/blockberry.md) - The Blockberry Sui API provides endpoints that reveal data about significant entities on the Sui Network.
- [Space And Time (SxT)](Indexer/space_and_time.md) - Verifiable compute layer for AI x blockchain. Decentralized data warehouse with sub-second ZK proof.
- [Birdeye Data Services](https://bds.birdeye.so/) - Access Crypto Market Data APIs on Sui. [Blog](https://blog.sui.io/birdeye-data-services-crypto-api-websocket/) | [API Documentation](https://docs.birdeye.so/reference/intro/authentication)
- [Indexer.xyz (behind TradePort)](https://www.indexer.xyz/) - The ultimate toolkit for accessing NFT data and integrating trading functionality into your app on Sui. [API Explorer](https://www.indexer.xyz/api-explorer) | [API Docs](https://tradeport.xyz/docs).

## Explorers
- [SuiVision](Explorer/suivision.md) - Data analytics covering transactions, wallets, staking, and validators.
- [SuiScan](Explorer/suiscan.md) - Explorer and analytics platform for Sui.
- [OKLink](Explorer/oklink.md) - Provide fundamental explorer and data APIs on Sui.
- [Polymedia Explorer](Explorer/polymedia.md) - A fork of the original Sui Explorer.
- [Local Sui Explorer](Explorer/local_sui_explorer.md) - Sui Explorer for your localnet maintained by [kkomelin](https://github.com/kkomelin)

## Oracles
- [Pyth Network](Oracle/pyth.md) - Oracle protocol that connects the owners of market data to applications on multiple blockchains including Sui.
- [Supra Oracles](Oracle/supra.md) - Oracle protocol to provide reliable data feed.
- [Switchboard](Oracle/switchboard.md) - Data feed customization and management.

## AI
- [RagPool](https://ragpool.digkas.nl/) - RAG based chat with docs.
- [Cookbook](https://docsbot-demo-git-sui-cookbookdev.vercel.app/) - Gemini-based RAG built for docs.

## Walrus
- [Walrus Sites GA](https://github.com/marketplace/actions/walrus-sites-ga) - Reusable GitHub Action for deploying Walrus Sites

## Submission Guidelines

- For submitting new tools:
    - Duplicate and fill out the [new tool submission template](./new_tool_submission_template.md) for the tool you are registering
    - Change the file name into the name of the tool in [snake casing](https://en.wikipedia.org/wiki/Snake_case), and move it into the folder according to the category of the tool being submitted
    - If you would like to include and link to an image, you can add it under the [`img` folder](./img/), and include it in the same pull request.
    - Create a pull request with the changes against the `main` branch
- For editing existing tracked tools:
    - Create a PR directly with the changes needed against the `main` branch
