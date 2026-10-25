# BlockVectra

Multi-chain JSON-RPC and indexed Data API for developers and AI agents.

- Website: https://blockvectra.com?ref=gh-org-profile
- Docs: https://docs.blockvectra.com?ref=gh-org-profile
- Supported chains: https://blockvectra.com/en/chains/?ref=gh-org-profile
- Live status: https://blockvectra.com/en/status/?ref=gh-org-profile
- Docs MCP server (Streamable HTTP): `https://docs.blockvectra.com/mcp`

## Start with a task

- **Connect to Robinhood Chain:** [RPC setup and chain ID](https://docs.blockvectra.com/en/guides/robinhood-chain/?ref=gh-org-profile) or [compare RPC providers](https://docs.blockvectra.com/en/guides/choose-rpc-provider/?ref=gh-org-profile).
- **Backfill event logs:** [split block ranges and resume a saved checkpoint](https://docs.blockvectra.com/en/guides/getlogs-block-range/?ref=gh-org-profile).
- **Use an AI agent:** [install the MCP server](https://github.com/blockvectra/mcp#readme). Documentation and discovery tools work without an API key; RPC follows each chain's public policy, while indexed Data API and account tools require a key.

## Starter repos

- [mcp](https://github.com/blockvectra/mcp): keyless docs and discovery; RPC follows each chain's public policy; indexed Data API and account tools require an API key
- [skills](https://github.com/blockvectra/skills): agent skills for RPC, Data API and programmatic sign-up
- [agent-quickstart](https://github.com/blockvectra/agent-quickstart): programmatic sign-up and first calls for AI agents
- [multichain-viem](https://github.com/blockvectra/multichain-viem): multichain viem template
- [data-api-js](https://github.com/blockvectra/data-api-js): TypeScript client for the Data API
- [hyperevm-backfill](https://github.com/blockvectra/hyperevm-backfill): HyperEVM event and log backfill
- [robinhood-stock-tokens](https://github.com/blockvectra/robinhood-stock-tokens): Robinhood Chain stock token activity dashboard
- [robinhood-testnet-starter](https://github.com/blockvectra/robinhood-testnet-starter): Robinhood Chain Testnet starter (TypeScript + viem)
- [evm-log-backfill-checkpoints](https://github.com/blockvectra/evm-log-backfill-checkpoints): 11 synthetic offline cases covering checkpoints, timestamp-start estimation and writer fencing, with JSONL data and dependency-free Node.js tests
