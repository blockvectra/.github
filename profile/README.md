# BlockVectra

Multi-chain JSON-RPC and indexed Data API for developers and AI agents.

- Website: https://blockvectra.com?ref=gh-org-profile
- Docs: https://docs.blockvectra.com?ref=gh-org-profile
- Supported chains: https://blockvectra.com/en/chains/?ref=gh-org-profile
- Live status: https://blockvectra.com/en/status/?ref=gh-org-profile
- Documentation-only MCP (Streamable HTTP): `https://docs.blockvectra.com/mcp/docs` — `search_docs` and `read_doc`, no API key.

## Start with a task

- **Read Robinhood mainnet without an account:** [run the pinned keyless quickstart](https://github.com/blockvectra/agent-quickstart/releases/tag/keyless-read-2026.11.02). With Node.js >= 24.12 and Git, check the chain ID and read a block number without installing dependencies, creating a wallet or using an API key.
- **Connect to Robinhood Chain:** [RPC setup and chain ID](https://docs.blockvectra.com/en/guides/robinhood-chain/?ref=gh-org-profile) or [compare RPC providers](https://docs.blockvectra.com/en/guides/choose-rpc-provider/?ref=gh-org-profile).
- **Backfill event logs:** [split block ranges and resume a saved checkpoint](https://docs.blockvectra.com/en/guides/getlogs-block-range/?ref=gh-org-profile).
- **Search documentation with an AI agent:** [connect to the documentation-only MCP endpoint](https://docs.blockvectra.com/en/guides/mcp-server/?ref=github-org-docs-1107). Search and read English or Chinese docs without an account, API key or local server.
- **Use RPC and Data tools:** [configure the full MCP server](https://github.com/blockvectra/mcp#readme). RPC follows each chain's public policy, while indexed Data API and account tools require a key.

## Starter repos

- [mcp](https://github.com/blockvectra/mcp): keyless docs and discovery; RPC follows each chain's public policy; indexed Data API and account tools require an API key
- [skills](https://github.com/blockvectra/skills): agent skills for RPC, Data API and programmatic sign-up
- [agent-quickstart](https://github.com/blockvectra/agent-quickstart): keyless Robinhood mainnet read; separate wallet/account onboarding and keyed Data API example
- [multichain-viem](https://github.com/blockvectra/multichain-viem): multichain viem template
- [data-api-js](https://github.com/blockvectra/data-api-js): TypeScript client for the Data API
- [hyperevm-backfill](https://github.com/blockvectra/hyperevm-backfill): HyperEVM event and log backfill
- [robinhood-stock-tokens](https://github.com/blockvectra/robinhood-stock-tokens): Robinhood Chain stock token activity dashboard
- [robinhood-testnet-starter](https://github.com/blockvectra/robinhood-testnet-starter): Robinhood Chain Testnet starter (TypeScript + viem)
- [evm-log-backfill-checkpoints](https://github.com/blockvectra/evm-log-backfill-checkpoints): 11 synthetic offline cases covering checkpoints, timestamp-start estimation and writer fencing, with JSONL data and dependency-free Node.js tests
