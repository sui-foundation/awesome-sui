# Awesome Sui [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Directory tracking developer tools and infrastructure projects within Sui ecosystem

## Contents

- [IDEs](#ides)
    - [Web IDEs](#web-ides)
    - [Desktop IDEs](#desktop-ides)
    - [IDE Utilities](#ide-utilities)
- [Client SDKs & Libraries](#client-sdks--libraries)
- [Indexers](#indexers)
- [Explorers](#explorers)
- [Oracles](#oracles)
- **AI**
    - [Example](./AI/example.md)
- **dApp Development**

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
- [Sui Typescript SDK](SDK/sui_typescript_sdk.md) - a Typescript modular library of tools for interacting with the Sui blockchain


## Indexers
- [ZettaBlock](Indexer/zettablock.md) - Generate custom GraphQL or REST APIs from SQL queries and incorporate your private off-chain data.
- [Sentio](Indexer/sentio.md) - Transform raw indexed data (transactions, events,...) into meaningful queryable data by writing custom processor logic.
- [BlockVision (SuiVision)](Indexer/blockvision.md) - Provide Sui indexed data for developers through pre-built APIs, such as, Token, NFT, and DeFi,...
- [BlockBerry (SuiScan)](Indexer/blockberry.md) - The Blockberry Sui API provides endpoints that reveal data about significant entities on the Sui Network.
- [Space And Time (SxT)](Indexer/space_and_time.md) - Verifiable compute layer for AI x blockchain. Decentralized data warehouse with sub-second ZK proof.

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

## New Dev Tooling Submission Guidelines

- Duplicate and fill out the [new tool submission template](./new_tool_submission_template.md) for the tool you are registering
- Change the file name into the name of the tool in [snaking case](https://en.wikipedia.org/wiki/Snake_case), and move it into the folder according to the category of the tool being submitted
- If you would like to include and link to an image, you can add it under the [`img` folder](./img/), and include it in the same pull request.
- Create a pull request with the changes against the `main` branch
