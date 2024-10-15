# Awesome Sui [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Directory tracking developer tools and infrastructure projects within Sui ecosystem.

> ⚠️ prefix means that the tool isn't working properly at the moment. We encourage builders to have further check.

[**Submit your own devtool here**](#submission-guidelines)

## Contents

- [Contents](#contents)
- [IDEs](#ides)
  - [Web IDEs](#web-ides)
  - [Desktop IDEs](#desktop-ides)
  - [IDE Utilities](#ide-utilities)
- [Client SDKs \& Libraries](#client-sdks--libraries)
  - [Client SDKs](#client-sdks)
  - [DeFi SDKs](#defi-sdks)
  - [Client Libraries](#client-libraries)
- [dApp Development](#dapp-development)
  - [dApp Toolkits](#dapp-toolkits)
    - [zkLogin](#zklogin)
    - [Misc](#misc)
  - [Smart Contract Toolkits](#smart-contract-toolkits)
- [Indexers \& Data Services](#indexers--data-services)
- [Explorers](#explorers)
- [Oracles](#oracles)
- [Security](#security)
- [AI](#ai)
- [Walrus](#walrus)
- [Submission Guidelines](#submission-guidelines)

## IDEs

### Web IDEs

- **BitsLab IDE** - online Move code editor that requires no configuration and supports Move code syntax highlighting, it's beginner-friendly and supports interacting with Sui.
  - [Homepage](https://www.bitslab.xyz/bitslabide) | [IDE](https://ide.bitslab.xyz/) | [Tutorial](https://www.youtube.com/watch?v=-9-WkqQwtu8) | [Further Information](details/ide_bitslab.md)
- **MoveStudio** - Online IDE for Sui smart contract development.
  - [Homepage](https://www.movestudio.dev/) | [Github](https://github.com/dantheman8300/move-studio) | [IDE](https://www.movestudio.dev/build) | [Further Information](details/ide_movestudio.md)
- **ChainIDE** - Move Cloud-Powered Development Platform.
  - [Homepage](https://chainide.com) | [Documentation](https://chainide.gitbook.io/chainide-english-1/ethereum-ide-1/9.-sui-ide) | [IDE](https://chainide.com/s/sui) | [Further Information](details/ide_chainide.md)
- ⚠️ **WELLDONE Code** - Remix IDE plugin supports non-EVM smart contract development including Sui.
  - [Homepage](https://docs.welldonestudio.io/code) | [Documentation & Tutorial](https://docs.welldonestudio.io/code/deploy-and-run/sui) | [Further Information](details/ide_welldone_code.md)


### Desktop IDEs

- **VSCode Move by Mysten Labs** - VSCode Extension supports Move on Sui development with LSP features through Move Analyzer developed by Mysten Labs.
  - [Github](https://github.com/MystenLabs/sui/tree/main/external-crates/move/crates/move-analyzer) | [Documentation & Tutorial](https://marketplace.visualstudio.com/items?itemName=mysten.move) | [Further Information](details/ide_vscode_mysten_move_analyzer.md)
- **VSCode Sui Move Analyzer by Movebit** - Alternative VSCode extension developed by Movebit.
  - [Homepage](https://movebit.xyz/analyzer) | [Github](https://github.com/movebit/sui-move-analyzer) | [Documentation & Tutorial](https://marketplace.visualstudio.com/items?itemName=MoveBit.sui-move-analyzer) | [Further Information](details/ide_vscode_movebit_sui_move_analyzer.md)
- **IntelliJ Sui Move Language Plugin** - IntelliJ-based plugin for Move on Sui development.
  - [Homepage](https://plugins.jetbrains.com/plugin/23301-sui-move-language) | [Github](https://github.com/movefuns/intellij-move)
- [Emacs move-mode](https://github.com/amnn/move-mode) - move-mode is an Emacs major-mode for editing smart contracts written in the Move programming language.
- [Move.vim](https://github.com/tzakian/move.vim) - Syntax highlighting for the Move smart contract programming language.

### IDE Utilities

- [Prettier Move Plugin](https://github.com/MystenLabs/sui/tree/main/external-crates/move/crates/move-analyzer/prettier-plugin) - a Move language plugin for the Prettier code formatter
- **Sui Extension** - The Sui extension provides seamless support for compiling, deploying, and testing Sui smart contracts directly within VS Code.
  - [Homepage](https://marketplace.visualstudio.com/items?itemName=zktxio.sui-extension) | [Documentation](https://docs.zktx.io/vsce/sui/)
- ⚠️ **Sui Simulator** - VSCode Extension to streamline Sui development workflow with intuitive UI.
  - [Homepage](https://marketplace.visualstudio.com/items?itemName=weminal-labs.sui-simulator-vscode) | [Github](https://github.com/Weminal-labs/sui-simulator-vscode) | [Demo](https://www.youtube.com/watch?v=BHRxeF_visM&pp=ygUMd2VtaW5hbCBsYWIg)
- [Tree Sitter Move](https://github.com/tzakian/tree-sitter-move) - Tree Sitter for Move.

## Client SDKs & Libraries

### Client SDKs

- **Sui Typescript SDK (Mysten Labs)** - Typescript modular library of tools for interacting with the Sui blockchain.
  - [Github](https://github.com/MystenLabs/sui/tree/main/sdk/typescript) | [Documentation](https://sdk.mystenlabs.com/typescript) | [Further Information](details/sdk_sui_typescript.md)
- **Sui Rust SDK (Mysten Labs)** - Rust SDK to interact with Sui blockchain.
  - [Github](https://github.com/MystenLabs/sui/tree/main/crates/sui-sdk) | [Documentation](https://mystenlabs.github.io/sui/sui_sdk/index.html) | [Further Information](details/sdk_sui_rust.md)
- **Pysui** - Python SDK to interact with Sui blockchain.
  - [Github](https://github.com/FrankC01/pysui?tab=readme-ov-file)| [Documentation](https://pysui.readthedocs.io/en/latest/index.html) | [Pypi](https://pypi.org/project/pysui/) | [Discord](https://discord.gg/uCGYfY4Ph4) | [Further Information](details/sdk_pysui.md)
- **Sui Go SDK (SuiVision)** - Golang SDK to interact with Sui blockchain.
  - [Github](https://github.com/block-vision/sui-go-sdk) | [API Documentation](https://pkg.go.dev/github.com/block-vision/sui-go-sdk) | [Examples](https://github.com/block-vision/sui-go-sdk?tab=readme-ov-file#examples) | [Further Information](details/sdk_sui_go.md)
- **Sui Dart SDK** - Dart SDK to interact with Sui blockchain.
  - [Github](https://github.com/mofalabs/sui) | [API documentation](https://pub.dev/documentation/sui/latest/) | [Further Information](details/sdk_sui_dart.md)
- **Sui Kotlin SDK** - Kotlin Multiplatform (KMP) SDK for integrating with the Sui blockchain.
  - [Github](https://github.com/mcxross/ksui) | [Further Information](details/sdk_ksui.md)
- **SuiKit (OpenDive)** - Swift SDK natively designed to make developing for the Sui Blockchain easy.
  - [Github](https://github.com/opendive/suikit?tab=readme-ov-file) | [Further Information](details/sdk_suikit.md)
- **Sui Unity SDK (OpenDive)** - The OpenDive Sui Unity SDK is the first fully-featured Unity SDK with offline transaction building.
  - [Github](https://github.com/OpenDive/Sui-Unity-SDK) | [Further Information](details/sdk_sui_unity_opendive.md)

### DeFi SDKs
- [NAVI Protocol SDK](https://github.com/naviprotocol/navi-sdk) - The NAVI Typescript SDK Client provides tools for interacting with the Sui blockchain networks, designed for handling transactions, accounts, and smart contracts efficiently.
- [Bucket Protocol SDK](https://github.com/Bucket-Protocol/bucket-protocol-sdk) - The Typescript SDK for interacting with Bucket Protocol.
- [Suilend SDK](https://github.com/solendprotocol/suilend-public/tree/production/sdk) - The TypeScript SDK for interacting with the Suilend program published on npm as [`@suilend/sdk`](https://www.npmjs.com/package/@suilend/sdk).
- [Scallop SDK](https://github.com/scallop-io/sui-scallop-sdk) - The Typescript SDK for interacting with the Scallop lending protocol on the Sui network.
- [Cetus CLMM SDK](https://github.com/CetusProtocol/cetus-clmm-sui-sdk) - The official software development kit (SDK) specifically designed for seamless integration with Cetus-CLMM on Sui.
- [Aftermath SDK](https://github.com/AftermathFinance/aftermath-ts-sdk) - The Typescript SDK for interacting with Aftermath Protocol.
- [FlowX SDK](https://github.com/FlowX-Finance/sdk) - FlowX Typescript SDK is an official software development kit that allows developers to interact with FlowX protocols using the Typescript programming language.
- [7k Aggregator SDK](https://github.com/7k-ag/7k-sdk-ts) - The Typescript SDK for interacting with 7k Aggregator protocol.
- [Hop Aggregator SDK](https://docs.hop.ag/hop-sdk) - The Typescript SDK for interacting with Hop Aggregator.

### Client Libraries

- [BCS Typescript (Mysten Labs)](https://sdk.mystenlabs.com/bcs) - BCS with Typescript.
- [BCS Rust](https://github.com/zefchain/bcs) - BCS with Rust.
- [BCS Dart](https://github.com/mofalabs/bcs) - BCS with Dart.
- [BCS Kotlin](https://github.com/mcxross/kotlinx-serialization-bcs) - BCS with Kotlin
- [BCS Swift](https://github.com/OpenDive/SuiKit/tree/main/Sources/SuiKit/Utils/BCS) - BCS with Swift
- [BCS Unity](https://github.com/OpenDive/Sui-Unity-SDK/tree/main/Assets/Sui-Unity-SDK/Code/OpenDive.BCS) - BCS with Unity C#
- [Sui Client Gen (KunaLabs)](https://github.com/kunalabs-io/sui-client-gen/tree/master) - A tool for generating TS SDKs for Sui Move smart contracts. Supports code generation both for source code and on-chain packages with no IDLs or ABIs required.
- [TypeMove (Sentio)](https://github.com/sentioxyz/typemove/blob/main/packages/sui/Readme.md) - Generate TypeScript bindings for Sui contracts.
- **Sui Wallet Standard (Mysten Labs)** - A suite of standard utilities for implementing wallets and libraries based on the [Wallet Standard](https://github.com/wallet-standard/wallet-standard/).
  - [Github](https://github.com/MystenLabs/sui/tree/main/sdk/wallet-standard) | [Documentation](https://docs.sui.io/standards/wallet-standard)
- [CoinMeta (Polymedia)](https://github.com/juzybits/polymedia-coinmeta) - Library for fetching coin metadata for Sui coins

## dApp Development

### dApp Toolkits

- [@mysten/create-dapp](https://sdk.mystenlabs.com/dapp-kit/create-dapp) - CLI tool that helps you create Sui dApp projects.
- **Sui dApp Kit (Mysten Labs)** - Set of React components, hooks, and utilities to help you build a dApp for the Sui ecosystem.
  - [Github](https://github.com/MystenLabs/sui/tree/main/sdk/dapp-kit) | [Documentation](https://sdk.mystenlabs.com/dapp-kit)
- **Sui dApp Starter** - Full-stack boilerplate which lets you scaffold a solid foundation for your Sui project and focus on the business logic of your dapp from day one.
  - [Github](https://github.com/kkomelin/sui-dapp-starter?tab=readme-ov-file) | [Documentation](https://sui-dapp-starter.dev/docs/) |  [Demo app](https://demo.sui-dapp-starter.dev/)
- **Suiet Wallet Kit** - Suiet wallet kit is an awesome react toolkit for DApps to interact with all the wallets in Sui💧 easily 🥳.
  - [Github](https://github.com/suiet/wallet-kit) | [Documentation](https://kit.suiet.app/docs/QuickStart)
- **SmartKit** - React library that allows your dapp to connect to the Sui network in a simple way.
  - [Homepage](https://smartkit.vercel.app/) | [Github](https://github.com/heapup-tech/smartkit)
- [Sui Suitcase](https://github.com/juzybits/polymedia-suitcase) - Sui utilities for TypeScript, Node, and React.
- [Sui MultiSig Toolkit (Mysten Labs)](https://multisig-toolkit.vercel.app/offline-signer) - Toolkit for transaction signing.
- [Sui dApp Scaffold (Bucket Protocol)](https://github.com/Bucket-Protocol/sui-dapp-scaffold-v1) - A frontend scaffold for a decentralized application (dApp) on the Sui blockchain.
- [Wormhole Kit(zktx.io)](https://github.com/zktx-io/wormhole-kit-monorepo) - React library that enables instant integration of Wormhole into your dapp.
- **SuiBase** - Suibase makes it easy to create "workdirs", each defining a distinct development environment targeting a network.
  - [Github](https://github.com/chainmovers/suibase) | [Documentation](https://suibase.io/)
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
- [Sui RPC Proxy](https://github.com/SuiSec/sui-rpc-proxy) - Monitor and analyze the network requests made by the Sui wallet application and Sui dApps.

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

- **ZettaBlock** - Generate custom GraphQL or REST APIs from SQL queries and incorporate your private off-chain data.
  - [Homepage](https://zettablock.com/) | [Docs](https://docs.zettablock.com) | [Pricing](https://zettablock.com/pricing) | [Further Information](details/indexer_zettablock.md)
- **Sentio** - Transform raw indexed data (transactions, events,...) into meaningful queryable data by writing custom processor logic.
  - [Homepage](https://www.sentio.xyz/indexer/) | [Documentation](https://docs.sentio.xyz/docs/data-collection) | [Examples](https://github.com/sentioxyz/sentio-processors/tree/main/projects) | [Further Information](details/indexer_sentio.md)
- **BlockVision (SuiVision)** - Provide Sui indexed data for developers through pre-built APIs, such as, Token, NFT, and DeFi,...
  - [Homepage](https://suivision.xyz/) | [Documentation](https://docs.blockvision.org/reference/welcome-to-blockvision)
- **BlockBerry (SuiScan)** - The Blockberry Sui API provides endpoints that reveal data about significant entities on the Sui Network. We index useful object metadata, including NFTs, domains, collections, coins, etc. Some data is drawn from third-party providers, particularly market data (coin prices, market cap, etc.).
  - [Homepage](https://blockberry.one/) | [Documentation](https://docs.blockberry.one/reference/sui-quickstart)
- **Space And Time (SxT)** - Verifiable compute layer for AI x blockchain. Decentralized data warehouse with sub-second ZK proof.
  - [Homepage](https://www.spaceandtime.io/) | [Documentation](https://www.spaceandtime.io/) | [Further Documentation](details/indexer_space_and_time.md)
- **Birdeye Data Services** - Access Crypto Market Data APIs on Sui. 
  - [Homepage](https://bds.birdeye.so/) | [Blog](https://blog.sui.io/birdeye-data-services-crypto-api-websocket/) | [API Documentation](https://docs.birdeye.so/reference/intro/authentication)
- **Indexer.xyz (behind TradePort)** - The ultimate toolkit for accessing NFT data and integrating trading functionality into your app on Sui. 
  - [Homepage](https://www.indexer.xyz/) | [API Explorer](https://www.indexer.xyz/api-explorer) | [API Docs](https://tradeport.xyz/docs)

## Explorers

- **SuiVision** - Data analytics covering transactions, wallets, staking, and validators.
  - [Homepage](https://suivision.xyz/) | [Documentation](https://docs.blockvision.org/reference/integrate-suivision-into-your-dapp) | [Further Information](details/explorer_suivision.md)
- **SuiScan** - Explorer and analytics platform for Sui.
  - [Homepage](https://suiscan.xyz/mainnet/home) | [Documentation](https://docs.blockberry.one/reference/welcome-to-blockberry-api) | [Further Information](details/explorer_suiscan.md)
- **OKLink** - Provide fundamental explorer and data APIs on Sui.
  - [Homepage](https://www.oklink.com/sui) | [Further Information](details/explorer_oklink.md)
- **Polymedia Explorer** - A fork of the original Sui Explorer.
  - [Homepage](https://explorer.polymedia.app) | [Github](https://github.com/juzybits/polymedia-explorer) | [Further Information](details/explorer_polymedia.md)
- **Local Sui Explorer** - Sui Explorer for your localnet maintained by [kkomelin](https://github.com/kkomelin)
  - [Github](https://github.com/kkomelin/sui-explorer) | [Further Information](details/explorer_local_sui_explorer.md)

## Oracles

- **Pyth Network** - Oracle protocol that connects the owners of market data to applications on multiple blockchains including Sui.
  - [Homepage](https://www.pyth.network/) | [Documentation](https://docs.pyth.network/home) | [Sui Tutorial](https://docs.pyth.network/price-feeds/use-real-time-data/sui) | [Further Information](details/oracle_pyth.md)
- **Supra Oracles** - Oracle protocol to provide reliable data feed.
  - [Homepage](https://supra.com/) | [Sui Tutorial](https://docs.supra.com/docs/developer-tutorials/move) | [Further Information](details/oracle_supra.md)
- **Switchboard** - Data feed customization and management.
  - [Documentation](https://docs.switchboard.xyz/docs) | [Further Information](details/oracle_switchboard.md)

## Security

- [SuiSecBlockList](https://github.com/SuiSec/SuiSecBlockList) - Block malicious websites and packages, Identify and hide phishing objects.
- [DryRunTransactionBlockResponsePlus](https://github.com/SuiSec/DryRunTransactionBlockResponsePlus) - Decorator of `DryRunTransactionBlockResponse`, highlight `SenderChange`.
- [Guardians](https://github.com/suiet/guardians) - Phishing Website Protection.

## AI

- [RagPool](https://ragpool.digkas.nl/) - RAG based chat with docs.
- [Cookbook](https://docsbot-demo-git-sui-cookbookdev.vercel.app/) - Gemini-based RAG built for docs.

## Walrus

- **Walrus Sites GA** - Reusable GitHub Action for deploying Walrus Sites
  - [Github](https://github.com/zktx-io/walrus-sites-ga) | [Marketplace](https://github.com/marketplace/actions/walrus-sites-ga) | [Examples](https://github.com/zktx-io/walrus-sites-ga-example) | [Further Information](details/walrus_sites_ga.md)

## Submission Guidelines

- For submitting new tools:
  - We recommend you to prepare and complete the tool's documentation first as we prefer to include all relevant information and official links inline in the index page (README.md).
  - Add your tool relevant information to the index page (README.md).
  - If you would like to include and link to an image, you can add it under the [`img` folder](./img/), and include it in the same pull request
  - Create a pull request with the changes against the `main` branch
- For editing existing tracked tools:
  - Create a pull request directly with the changes needed against the `main` branch

_💡Note_: The `details` folder consists of each tool's information that we have collected to summarize useful features and resources for the audience. However, this act stems from the lack of documentation from that tool. Therefore, we encourage new and existing project owners to complete the documentation and any relevant materials so that we can redirect other users to those information directly in the index file. However, please feel free to make a PR to update incorrect or outdated information in the `details` folder as it still provides valuable insights in the mean time.
