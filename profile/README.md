# Hedera Developers

[![Release](https://img.shields.io/github/v/release/hashgraph/hedera-sdk-js?label=latest)](https://github.com/hashgraph/hedera-sdk-js/releases)
[![CI](https://github.com/hashgraph/developers/actions/workflows/ci.yml/badge.svg)](https://github.com/hashgraph/developers/actions/workflows/ci.yml)
[![Docs](https://img.shields.io/badge/docs-hedera.dev-blue)](https://hedera.com/learn)
[![Discord](https://img.shields.io/discord/915969073218412594?label=discord)](https://hedera.com/discord)

> Build, test, and scale dApps on the carbon-negative Hedera network.

**Quick links** · [Get Started](#getting-started) · [Repo Matrix](#repository-matrix) · [Open Source Contributions](#open-source-contributions)

## Intro

Hedera Developers is the umbrella for tutorials, tools, and production-grade templates that help you move from zero to mainnet on Hedera. Whether you're experimenting with Hashgraph-native services like the Token Service (HTS) or deploying Solidity on the Hedera EVM, this repo is your starting index.

*⚡️ Why Hedera?*

* Predictably low fees for every transaction
* Finality in seconds on a carbon-negative ledger
* Native tokenization, consensus, and smart-contract services

## Getting Started

<details>
<summary><strong>New to Hedera? 👶&nbsp;Run **Hello Hedera** in&nbsp;5&nbsp;minutes</strong></summary>

1. **Fork** this repo
2. `git clone` and `cd quickstart`
3. `npm install && npm run hello-hedera`
4. You just minted your first testnet token! 🎉

→ Dive deeper in the [Full Hello-World Tutorial](./tutorials/hello-world).

</details>

<details>
<summary><strong>Already shipping on Hedera? 🚀&nbsp;Jump to the repo matrix</strong></summary>

Skip the hand-holding and jump straight to language-specific SDKs, example dApps, and production tooling.

</details>

## Repository Matrix

> Cells link directly to source or docs. Use <kbd>⌘/Ctrl+F</kbd> to quickly filter values.

| Domain                 | Repos                                                                      | Tutorials                    | Workshops               | Products | Tools                                                         | Templates            |
| ---------------------- | -------------------------------------------------------------------------- | ---------------------------- | ----------------------- | -------- | ------------------------------------------------------------- | -------------------- |
| **HIPs**               | [HIP repository](https://github.com/hashgraph/hedera-improvement-proposal) | HIP authoring guide          | –                       | –        | –                                                             | –                    |
| **HTS**                | `token-service-demo`                                                       | [HTS 101](./tutorials/hts)   | Token Treasury Workshop | –        | [`hedera-sdk-js`](https://github.com/hashgraph/hedera-sdk-js) | ERC-20 Scaffold      |
| **HCS**                | `consensus-pubsub`                                                         | [HCS Intro](./tutorials/hcs) | Ordering Guarantees Lab | –        | `hcs-cli`                                                     | Topic Monitor        |
| **Oracles**            | `price-oracle`                                                             | Oracle How-To                | –                       | –        | Chainlink Adapter                                             | Oracle Template      |
| **Bridges**            | `hashport-client`                                                          | Bridging Assets              | –                       | Hashport | –                                                             | Cross-Chain Template |
| **Tools / SDKs**       | –                                                                          | SDK Tutorials                | –                       | –        | `hedera-sdk-go`, `hedera-sdk-java`                            | CLI Starter          |
| **AI**                 | `hedera-genai`                                                             | AI & HTS Tutorial            | –                       | –        | Prompt Playground                                             | GenAI Scaffold       |
| **EVM**                | `hedera-hardhat`                                                           | Hardhat on Hedera            | Solidity Gas Workshop   | –        | Hardhat Plugin                                                | Foundry Kit          |
| **Hybrid (HTS × EVM)** | `hts-evm-bridge`                                                           | Hybrid Token Tutorial        | –                       | –        | –                                                             | Hybrid Scaffold      |

*This table is auto-generated from [`/.matrix.yml`](./.matrix.yml) during CI to avoid stale links.*

## Open Source Contributions

Looking to go deeper? Head over to the fully open-sourced **[Hiero repository](https://github.com/hashgraph/hiero)**—the canonical place for Hedera protocol code and RFC-style discussions. PRs welcome! 🛠️

## License

Code in this repository is licensed under the [Apache 2.0](./LICENSE) license unless stated otherwise.

---

If you spot an issue or have an idea, please [open an issue](https://github.com/hashgraph/developers/issues) or start a discussion.
