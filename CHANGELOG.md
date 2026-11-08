# Changelog

What shipped on Kyte, newest first. Dates are UTC. Contracts and addresses: https://kyte.sh/docs.

## 2026-11-08
- Oak Agent Kit recipes published: `oak recipes add kyte-oak-recipes` gives any Oak agent 23 Kyte recipes (buy, sell, exercise, cancel, expire, stake) on Robinhood Chain. https://www.npmjs.com/package/kyte-oak-recipes
- Listed on the HOL (Hashgraph Online) registry and AI Plugin Registry; HOL Guard catalog entry. https://hol.org/registry/plugins/usekyte%2Fkyte-mcp
- Autopilot public on production: plain-language rules the user signs once; Kyte prepares the transaction when the condition holds.
- DefiLlama adapter submitted (DefiLlama-Adapters PR 22081).
- Repository moved to usekyte-org; install guide in docs/INSTALL.md.

## 2026-11-07
- Kyte MCP server v1.0.0 at https://kyte.sh/api/mcp: 20 tools (14 read, 6 prepare), 6 resources, 3 prompts; stateless Streamable HTTP, no login.
- Plugin manifests for Claude Code, Codex, Cursor and Gemini; MCP page at https://kyte.sh/mcp.
- Token names keep non-Latin scripts; control and bidi characters stripped.

## 2026-11-06
- PonsLister deployed: permissionless listing of graduated Pons launchpad tokens through the timelock, 24-hour options only.
- Launchpad page: graduated Pons tokens with full on-chain records and a "Listing in 10 min" state.

## 2026-11-01
- Markets v3: new OptionNFT with readable on-chain art, new call and put markets and router. Older market sets keep settling their positions.

## 2026-10-28
- Markets v2: AssetRegistry with room for every Robinhood Stock Token; new markets and router.

## 2026-10-25
- Kyte live on Robinhood Chain mainnet: covered calls, cash-secured puts, Option NFTs, $KYTE staking (30% of fees), FeeVault split and BuybackBurner with on-chain proof page.
