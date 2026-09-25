# TickFoundry

Historical tick-level market data for **Polymarket** and **Hyperliquid**: every order-book change and every trade, as parquet or CSV per market per day, plus a REST API. Built for backtesting and market-microstructure research.

**[tickfoundry.com](https://tickfoundry.com)**

## What is in the archive

| Dataset | Coverage |
| --- | --- |
| Polymarket order books: top of book and the 25-level L2 book | since February 2026 |
| Polymarket native capture, including the raw websocket feed with nanosecond receive stamps | since 11 May 2026 |
| Polymarket on-chain trade fills | since February 2025 |
| Hyperliquid books and trades for every perp, spot pair and HIP-3 market, rebuilt block by block from the chain's own order events | since 25 January 2025 |

A "market" in the catalog is a Polymarket series (a repeating question such as "Bitcoin Up or Down, 15 minute") or a standalone event.

## Start here

- [Free sample bundles](https://tickfoundry.com/samples): one real market-day, parquet and CSV, no account needed
- [How to backtest Polymarket](https://tickfoundry.com/how-to-backtest-polymarket): pandas on the free sample, with slippage measured against the real book
- [How to backtest on Hyperliquid](https://tickfoundry.com/how-to-backtest-hyperliquid): walk the 25-level book for real fills
- [Quickstart notebook](https://tickfoundry.com/quickstart.html)
- [Docs and REST API](https://tickfoundry.com/docs): schemas, timestamps, join keys, bundle layout
- [Catalog](https://tickfoundry.com/catalog): every series and event in the archive, with days of coverage
- [Research notes](https://tickfoundry.com/research): microstructure studies built from the archive

## Contact

[info@tickfoundry.com](mailto:info@tickfoundry.com) · [Bluesky @tickfoundry.com](https://bsky.app/profile/tickfoundry.com)
