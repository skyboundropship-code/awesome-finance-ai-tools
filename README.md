# Awesome Finance & Trading AI Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![MCP Registry](https://img.shields.io/badge/MCP_Registry-com.tradingaihub%2Fdirectory-555)](https://registry.modelcontextprotocol.io/v0/servers?search=tradingaihub) [![Public API](https://img.shields.io/badge/API-public%20%7C%20no%20key-15803d)](https://tradingaihub.com/developers/) [![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/) [![GitHub stars](https://img.shields.io/github/stars/tradingaihub/awesome-finance-ai-tools?style=social)](https://github.com/tradingaihub/awesome-finance-ai-tools)

> A curated, **automatically re-verified** list of MCP servers, agent skills and APIs for finance and trading. Mirror of [TradingAIHub](https://tradingaihub.com) — status checked weekly (last: 2026-11-09).

Legend: ✅ verified · 🟡 aging (6–12 months without commits) · 🔴 stale (12+ months) · 🗄️ archived. 🟡 also marks entries whose link failed or could not be confirmed. ⭐ = GitHub stars. Not investment advice.

## Use it from your AI agent

This list is the markdown mirror of [TradingAIHub](https://tradingaihub.com). The same data is available to agents with no API key:

- Remote MCP server: `https://tradingaihub.com/mcp` (Streamable HTTP; tools `search_tools`, `get_tool`, `list_categories`). Official MCP Registry: `com.tradingaihub/directory`.
- REST API: `https://tradingaihub.com/api/v1/tools` · OpenAPI: `https://tradingaihub.com/api/openapi.json` · docs: https://tradingaihub.com/developers/

Cursor example (`.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "tradingaihub": {
      "url": "https://tradingaihub.com/mcp"
    }
  }
}
```

Data is CC BY 4.0; attribution is "TradingAIHub, https://tradingaihub.com". Not investment advice.

## Contents

- [Market data APIs & MCPs](#market-data-apis--mcps)
- [Trading & broker MCPs](#trading--broker-mcps)
- [Crypto & DeFi](#crypto--defi)
- [Accounting & bookkeeping](#accounting--bookkeeping)
- [Payments & business banking](#payments--business-banking)
- [Personal finance & budgeting](#personal-finance--budgeting)
- [Research & SEC filings](#research--sec-filings)
- [Quant & backtesting](#quant--backtesting)
- [Macro & economics](#macro--economics)

## Market data APIs & MCPs

- 🔴 [Financial Datasets MCP](https://github.com/financial-datasets/mcp-server) *(official)* — Income statements, balance sheets, cash flows and stock prices from Financial Datasets. ⭐ 2,321 · [details](https://tradingaihub.com/tools/financial-datasets-mcp/)
- ✅ [Maverick MCP](https://github.com/wshobson/maverick-mcp) — Stock analysis MCP server with technical analysis, screening and portfolio tools. ⭐ 721 · [details](https://tradingaihub.com/tools/maverick-mcp/)
- ✅ [Massive MCP](https://github.com/massive-com/mcp_massive) *(official)* — Official MCP server for Massive stocks, options, forex and crypto data. ⭐ 401 · [details](https://tradingaihub.com/tools/massive-mcp/)
- ✅ [investor-agent](https://github.com/ferdousbhai/investor-agent) — MCP server providing market data, sentiment and fundamentals for building an investor agent. ⭐ 348 · [details](https://tradingaihub.com/tools/investor-agent/)
- ✅ [Alpha Vantage MCP](https://github.com/alphavantage/alpha_vantage_mcp) *(official)* — Official MCP server exposing Alpha Vantage stocks, forex, crypto and indicators to AI agents. ⭐ 226 · [details](https://tradingaihub.com/tools/alpha-vantage-mcp/)
- ✅ [Financial Modeling Prep MCP (community)](https://github.com/imbenrabi/Financial-Modeling-Prep-MCP-Server) — Community MCP server wrapping 250+ FMP tools for fundamentals and market insights. ⭐ 149 · [details](https://tradingaihub.com/tools/fmp-mcp-community/)
- ✅ [KOSPI/KOSDAQ MCP](https://github.com/dragon1086/kospi-kosdaq-stock-server) — Korean stock market (KOSPI/KOSDAQ) data via MCP. ⭐ 75 · [details](https://tradingaihub.com/tools/kospi-kosdaq-mcp/)
- ✅ [EODHD Claude Skills](https://github.com/EodHistoricalData/eodhd-claude-skills) *(official)* — Official Claude Code plugin/skills for EODHD: market overview, screener, company briefs, earnings monitor. ⭐ 49 · [details](https://tradingaihub.com/tools/eodhd-claude-skills/)
- ✅ [Yahoo Finance MCP](https://github.com/maxscheijen/mcp-yahoo-finance) — Community MCP server for Yahoo Finance quotes and history (unofficial data source). ⭐ 29 · [details](https://tradingaihub.com/tools/yahoo-finance-mcp/)
- ✅ [EODHD MCP Server (official)](https://github.com/EodHistoricalData/EODHD-MCP-Server) *(official)* — EODHD's official MCP server: 70+ read-only tools for prices, fundamentals, news, technicals, options and macro; API key or OAuth. ⭐ 24 · [details](https://tradingaihub.com/tools/eodhd-mcp/)
- ✅ [HK Finance MCP](https://github.com/hkopenai/hk-finance-mcp-server) — Hong Kong finance and stock market data via MCP. ⭐ 13 · [details](https://tradingaihub.com/tools/hk-finance-mcp/)
- 🔴 [Stock Market MCP (Finnhub)](https://github.com/sverze/stock-market-mcp-server) — Community MCP server serving stock market data via the Finnhub API. ⭐ 7 · [details](https://tradingaihub.com/tools/finnhub-mcp-community/)
- ✅ [Alpha Vantage API](https://www.alphavantage.co/) *(official)* — Stocks, forex, crypto, fundamentals and 50+ technical indicators over a simple REST API. · [details](https://tradingaihub.com/tools/alpha-vantage-api/)
- ✅ [Massive (formerly Polygon.io) API](https://massive.com/) *(official)* — Tick-level US stocks, options, indices, forex and crypto over REST, WebSockets and flat files. · [details](https://tradingaihub.com/tools/massive-api/)
- ✅ [Financial Modeling Prep API](https://site.financialmodelingprep.com/) *(official)* — Fundamentals, ratios, prices, transcripts and 13F holdings across 150+ endpoints. · [details](https://tradingaihub.com/tools/fmp-api/)
- ✅ [Finnhub API](https://finnhub.io/) *(official)* — Real-time quotes, fundamentals, estimates, news and alternative data. · [details](https://tradingaihub.com/tools/finnhub-api/)
- ✅ [Twelve Data API](https://twelvedata.com/) *(official)* — Real-time and historical stocks, forex, crypto and ETFs with credit-based REST and WebSocket access. · [details](https://tradingaihub.com/tools/twelve-data-api/)
- ✅ [EODHD APIs](https://eodhd.com/) *(official)* — End-of-day, intraday, fundamentals and news for 70+ exchanges; ships an MCP server. · [details](https://tradingaihub.com/tools/eodhd-api/)
- ✅ [Alpaca Market Data API](https://alpaca.markets/data) *(official)* — US equities and options market data, free IEX tier and paid full-SIP plan. · [details](https://tradingaihub.com/tools/alpaca-market-data-api/)
- ✅ [TradingView MCP (official)](https://www.tradingview.com/mcp/docs) *(official)* — TradingView's own hosted MCP server (public beta): OHLCV, screeners, technicals, fundamentals, news, watchlists and price alerts. · [details](https://tradingaihub.com/tools/tradingview-official-mcp/)
- ✅ [Financial Modeling Prep MCP (official)](https://site.financialmodelingprep.com/developer/docs/mcp-server) *(official)* — FMP's official hosted MCP server: quotes, financial statements, technical indicators, news and filings as 27 dataset tools. · [details](https://tradingaihub.com/tools/fmp-mcp/)
- ✅ [Finnhub MCP (official)](https://finnhub.io/static/finnhub-how-to-connect-mcp-server.html) *(official)* — Finnhub's hosted MCP server: ~70 tools for quotes, financials, estimates, filings, funds, forex, crypto and economic data; OAuth login. · [details](https://tradingaihub.com/tools/finnhub-mcp/)

## Trading & broker MCPs

- ✅ [Alpaca MCP Server](https://github.com/alpacahq/alpaca-mcp-server) *(official)* — Official Alpaca MCP: trade stocks, ETFs, options and crypto; query positions and market data. ⭐ 1,071 · [details](https://tradingaihub.com/tools/alpaca-mcp/)
- 🟡 [MetaTrader 5 MCP](https://github.com/ariadng/metatrader-mcp-server) — Trade via the MetaTrader 5 terminal from AI agents. ⭐ 845 · [details](https://tradingaihub.com/tools/metatrader-mcp/)
- ✅ [Kraken CLI (MCP + skills)](https://github.com/krakenfx/kraken-cli) *(official)* — Official Kraken CLI with a built-in MCP server and 59 agent skills: crypto, xStocks, forex and futures, plus keyless paper trading. ⭐ 804 · [details](https://tradingaihub.com/tools/kraken-cli/)
- ✅ [Alpaca Skills](https://github.com/alpacahq/alpaca-skills) *(official)* — Official Alpaca agent skills for the Trading and Broker APIs: backtests, orders, account onboarding, money movement and events. ⭐ 165 · [details](https://tradingaihub.com/tools/alpaca-skills/)
- ✅ [tasty-agent (tastytrade)](https://github.com/ferdousbhai/tasty-agent) — Community MCP server for tastytrade: portfolio, market data, options Greeks and order execution. ⭐ 89 · [details](https://tradingaihub.com/tools/tasty-agent/)
- ✅ [Longbridge Skills](https://github.com/longbridge/skills) *(official)* — Official Longbridge agent skills: quotes, technicals, derivatives, fundamentals, portfolio and watchlist across HK, US, A-share and SG markets. ⭐ 71 · [details](https://tradingaihub.com/tools/longbridge-skills/)
- ✅ [Schwab MCP (community)](https://github.com/jkoelker/schwab-mcp) — Community MCP server for the Charles Schwab Trader API: accounts, quotes, options chains; read-only by default, trades need Discord/Signal approval. ⭐ 68 · [details](https://tradingaihub.com/tools/schwab-mcp/)
- ✅ [Webull OpenAPI MCP](https://github.com/webull-inc/webull-openapi-mcp) *(official)* — Official Webull OpenAPI MCP: multi-region market data and orders for stocks, options, futures and crypto, with a UAT sandbox. ⭐ 30 · [details](https://tradingaihub.com/tools/webull-openapi-mcp/)
- 🔴 [Paper Invest MCP](https://github.com/paperinvest/mcp-server) — Paper trading MCP: practice strategies without real money. ⭐ 24 · [details](https://tradingaihub.com/tools/paper-mcp/)
- ✅ [Interactive Brokers MCP (hosted)](https://www.interactivebrokers.com/en/trading/ai-integrations.php) *(official)* — IBKR hosted MCP endpoint for portfolio data, monitoring and authorized trade actions. · [details](https://tradingaihub.com/tools/ibkr-mcp/)
- ✅ [Robinhood Trading MCP (official)](https://robinhood.com/us/en/support/articles/onboarding-an-external-agent/) *(official)* — Robinhood's hosted MCP for external agents: read your accounts and trade stocks, options and crypto in a dedicated agent account. · [details](https://tradingaihub.com/tools/robinhood-trading-mcp/)

## Crypto & DeFi

- ✅ [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) — Toolkit connecting AI agents to Solana protocols, with MCP adapter. ⭐ 1,744 · [details](https://tradingaihub.com/tools/solana-agent-kit/)
- ✅ [Coinbase AgentKit](https://github.com/coinbase/agentkit) *(official)* — Coinbase toolkit for wallet operations and onchain actions by AI agents, with MCP support. ⭐ 1,354 · [details](https://tradingaihub.com/tools/coinbase-agentkit/)
- 🗄️ [Base MCP](https://github.com/base/base-mcp-legacy) *(official)* — Onchain tools for the Base network. ⭐ 351 · [details](https://tradingaihub.com/tools/base-mcp/)
- 🟡 [Crypto Indicators MCP](https://github.com/kukapay/crypto-indicators-mcp) — Technical analysis indicators for crypto assets. ⭐ 131 · [details](https://tradingaihub.com/tools/crypto-indicators-mcp/)
- ✅ [Coinbase Agentic Wallet Skills](https://github.com/coinbase/agentic-wallet-skills) *(official)* — Official Coinbase skills for agent wallets: balances, send USDC, swap tokens, onramp funds and pay x402 APIs on Base, Polygon and Solana. ⭐ 128 · [details](https://tradingaihub.com/tools/coinbase-agentic-wallet-skills/)
- ✅ [DexPaprika MCP](https://github.com/coinpaprika/dexpaprika-mcp) *(official)* — DEX analytics across 20+ blockchains from CoinPaprika. ⭐ 118 · [details](https://tradingaihub.com/tools/dexpaprika-mcp/)
- 🔴 [Binance MCP (community)](https://github.com/TermiX-official/binance-mcp) — Portfolio, trading and token conversion on Binance (requires API key). ⭐ 97 · [details](https://tradingaihub.com/tools/binance-mcp/)
- 🔴 [CoinCap MCP](https://github.com/QuantGeekDev/coincap-mcp) — Crypto market data from the CoinCap API. ⭐ 92 · [details](https://tradingaihub.com/tools/coincap-mcp/)
- 🔴 [CCXT MCP](https://github.com/Nayshins/mcp-server-ccxt) — Market data from 20+ crypto exchanges via the CCXT library. ⭐ 82 · [details](https://tradingaihub.com/tools/ccxt-mcp/)
- 🟡 [Bankless Onchain MCP](https://github.com/Bankless/onchain-mcp) *(official)* — Query onchain data and ERC-20 token information. ⭐ 78 · [details](https://tradingaihub.com/tools/bankless-onchain-mcp/)
- 🔴 [Bitcoin & Lightning MCP](https://github.com/AbdelStark/bitcoin-mcp) — Bitcoin and Lightning Network tools for agents. ⭐ 77 · [details](https://tradingaihub.com/tools/bitcoin-mcp/)
- 🔴 [Crypto Liquidations MCP](https://github.com/kukapay/crypto-liquidations-mcp) — Streams real-time liquidation events. ⭐ 8 · [details](https://tradingaihub.com/tools/crypto-liquidations-mcp/)
- ✅ [Bitget Agent MCP](https://github.com/Bitget-AI/agent-mcp) *(official)* — Official Bitget spot and futures trading MCP (89 operations per listing). ⭐ 1 · [details](https://tradingaihub.com/tools/bitget-agent-mcp/)
- 🟡 [DexScreener Trending MCP](https://github.com/kukapay/dexscreener-trending-mcp) — Trending tokens from DexScreener. ⭐ 1 · [details](https://tradingaihub.com/tools/dexscreener-trending-mcp/)
- ✅ [CoinGecko API](https://www.coingecko.com/en/api) *(official)* — Crypto prices, market caps, exchanges and on-chain DEX data. · [details](https://tradingaihub.com/tools/coingecko-api/)
- ✅ [CoinGecko MCP](https://docs.coingecko.com/ai-integration/mcp-server) *(official)* — Official CoinGecko MCP server; public keyless endpoint plus a Pro endpoint. · [details](https://tradingaihub.com/tools/coingecko-mcp/)

## Accounting & bookkeeping

- ✅ [Anthropic Financial Services Plugins](https://github.com/anthropics/financial-services) *(official)* — Anthropic's finance plugins/skills: Excel model auditing, 3-statement models, DCF/LBO, GL reconciliation. ⭐ 41,161 · [details](https://tradingaihub.com/tools/anthropic-financial-services/)
- ✅ [QuickBooks Online MCP](https://github.com/intuit/quickbooks-online-mcp-server) *(official)* — Official Intuit MCP server exposing QuickBooks Online entities and reports. ⭐ 447 · [details](https://tradingaihub.com/tools/quickbooks-mcp/)
- ✅ [Xero MCP Server](https://github.com/XeroAPI/xero-mcp-server) *(official)* — Official Xero MCP: contacts, chart of accounts, invoices and more. ⭐ 390 · [details](https://tradingaihub.com/tools/xero-mcp/)
- ✅ [Norman Finance MCP](https://github.com/norman-finance/norman-mcp-server) *(official)* — Accounting, invoicing and tax filing workflows for Norman Finance users. ⭐ 65 · [details](https://tradingaihub.com/tools/norman-finance-mcp/)
- ✅ [LedgerSkills](https://github.com/Kimonarrow/ledgerskills) — Claude skills for audit, tax, FP&A and accounting: reconciliation, month-end close, journal-entry testing. ⭐ 2 · [details](https://tradingaihub.com/tools/ledgerskills/)
- 🔴 [Invoice Organizer skill](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/invoice-organizer) — Claude skill that extracts, renames and sorts invoices and receipts for tax prep. · [details](https://tradingaihub.com/tools/invoice-organizer-skill/)
- ✅ [NetSuite AI Connector (MCP)](https://docs.oracle.com/en/cloud/saas/netsuite/ns-online-help/article_3200541651.html) *(official)* — Oracle NetSuite's MCP service plus the MCP Standard Tools SuiteApp: records, reports, saved searches and SuiteQL within your role's permissions. · [details](https://tradingaihub.com/tools/netsuite-ai-connector/)
- ✅ [Zoho Books MCP (official)](https://www.zoho.com/us/books/help/mcp/zoho-books-mcp.html) *(official)* — Official Zoho Books MCP via Zoho MCP: invoices, expenses, bank reconciliation, contacts and reports from any MCP client. · [details](https://tradingaihub.com/tools/zoho-books-mcp/)
- ✅ [Avalara AvaTax MCP](https://developer.avalara.com/mcp-servers/) *(official)* — Avalara's official AvaTax MCP server: sales-tax calculation, transactions, nexus, tax codes and address validation via OAuth. · [details](https://tradingaihub.com/tools/avalara-avatax-mcp/)

## Payments & business banking

- ✅ [Stripe Agent Toolkit & MCP](https://github.com/stripe/ai) *(official)* — Stripe's official agent toolkit and hosted MCP for payments, customers and billing. ⭐ 2,051 · [details](https://tradingaihub.com/tools/stripe-ai/)
- ✅ [Razorpay MCP Server](https://github.com/razorpay/razorpay-mcp-server) *(official)* — Official Razorpay MCP server for payments, orders, refunds, payment links, QR codes, settlements and payouts; hosted or local. ⭐ 231 · [details](https://tradingaihub.com/tools/razorpay-mcp/)
- ✅ [PayPal MCP Server](https://github.com/paypal/agent-toolkit) *(official)* — Official PayPal MCP server and agent toolkit: invoices, orders, payments, refunds, subscriptions and disputes; sandbox supported. ⭐ 198 · [details](https://tradingaihub.com/tools/paypal-mcp/)
- ✅ [x402 (x402 Foundation)](https://github.com/x402-foundation/x402) *(official)* — Open protocol for HTTP-native stablecoin payments by agents. ⭐ 6,795 · [details](https://tradingaihub.com/tools/x402/)
- ✅ [Square MCP Server](https://github.com/square/square-mcp-server) *(official)* — Official Square (Block) MCP server (beta) exposing Square APIs: payments, orders, catalog, customers, inventory and more. ⭐ 109 · [details](https://tradingaihub.com/tools/square-mcp/)
- ✅ [Paddle MCP Server](https://github.com/PaddleHQ/paddle-mcp-server) *(official)* — Official Paddle Billing MCP server: products, prices, customers, subscriptions, transactions and reports; sandbox supported. ⭐ 50 · [details](https://tradingaihub.com/tools/paddle-mcp/)
- ✅ [Qonto MCP](https://github.com/qonto/qonto-mcp-server) *(official)* — Official MCP server for Qonto business banking. ⭐ 42 · [details](https://tradingaihub.com/tools/qonto-mcp/)
- 🗄️ [Ramp MCP](https://github.com/ramp-public/ramp_mcp) *(official)* — Official Ramp MCP for spend and expense data. ⭐ 34 · [details](https://tradingaihub.com/tools/ramp-mcp/)
- ✅ [Adyen MCP Server](https://github.com/Adyen/adyen-mcp) *(official)* — Official Adyen MCP server for payment links, checkout sessions, payments, refunds and merchant account management. ⭐ 27 · [details](https://tradingaihub.com/tools/adyen-mcp/)
- 🟡 [Mercury MCP (official)](https://docs.mercury.com/docs/what-is-mercury-mcp) *(official)* — Mercury's hosted MCP server (beta): balances, transactions, cards and recipients; payment and transfer requests need approval in Mercury. · [details](https://tradingaihub.com/tools/mercury-mcp/)

## Personal finance & budgeting

- 🟡 [Firefly III API](https://github.com/firefly-iii/firefly-iii) *(official)* — REST API of Firefly III, the self-hosted open-source personal finance manager: accounts, transactions, budgets and rules. ⭐ 25,179 · [details](https://tradingaihub.com/tools/firefly-iii-api/)
- ✅ [YNAB MCP Server (community)](https://github.com/calebl/ynab-mcp-server) — Community MCP server for YNAB built on the official SDK: budgets, transactions and approvals, with an optional read-only mode. ⭐ 164 · [details](https://tradingaihub.com/tools/ynab-mcp/)
- ✅ [Lunch Money MCP](https://github.com/akutishevsky/lunchmoney-mcp) — MCP server for Lunch Money budgeting data. ⭐ 113 · [details](https://tradingaihub.com/tools/lunchmoney-mcp/)
- ✅ [OptionsAhoy MCP](https://github.com/AlvisoOculus/optionsahoy-mcp) — Equity-compensation tax optimizer for ISO, NSO, RSU and QSBS scenarios. ⭐ 6 · [details](https://tradingaihub.com/tools/optionsahoy-mcp/)
- 🔴 [Monarch Money MCP](https://github.com/carsol/monarch-mcp-server) — Community MCP server for Monarch Money accounts, transactions and budgets. ⭐ 4 · [details](https://tradingaihub.com/tools/monarch-mcp/)
- 🟡 [Actual Budget MCP](https://github.com/Jacob-Tate/actual-budget-mcp) — MCP server for the open-source Actual Budget app. ⭐ 2 · [details](https://tradingaihub.com/tools/actual-budget-mcp/)
- ✅ [YNAB API](https://api.ynab.com/) *(official)* — Official REST API for YNAB budgets, accounts, categories, payees and transactions; personal access token or OAuth. · [details](https://tradingaihub.com/tools/ynab-api/)

## Research & SEC filings

- 🟡 [OpenBB Platform (MCP)](https://github.com/OpenBB-finance/OpenBB) *(official)* — Open-source investment research platform with an MCP server. ⭐ 75,252 · [details](https://tradingaihub.com/tools/openbb/)
- ✅ [Claude Equity Research](https://github.com/quant-sentiment-ai/claude-equity-research) — Claude Code plugin producing equity research reports with fundamental and technical analysis. ⭐ 754 · [details](https://tradingaihub.com/tools/claude-equity-research/)
- ✅ [SEC EDGAR MCP](https://github.com/stefanoamorelli/sec-edgar-mcp) — Open-source MCP for SEC filings, XBRL financial statements and Form 3/4/5 insider data. ⭐ 386 · [details](https://tradingaihub.com/tools/sec-edgar-mcp/)
- 🔴 [Claude Investor](https://github.com/martinxu9/claude-investor) — Investment analysis agent using price data, balance sheets, sentiment and analyst ratings. ⭐ 34 · [details](https://tradingaihub.com/tools/claude-investor/)
- ✅ [Valyu MCP](https://github.com/valyuAI/valyu-mcp) *(official)* — Financial deep-research search platform for agents. ⭐ 19 · [details](https://tradingaihub.com/tools/valyu-mcp/)
- ✅ [FinBrain MCP](https://github.com/ahmetsbilgin/finbrain-mcp) — Alternative data (sentiment, predictions, insider) from FinBrain. ⭐ 9 · [details](https://tradingaihub.com/tools/finbrain-mcp/)
- ✅ [Equibles stock-market MCP](https://github.com/daniel3303/stock-market-mcp-server) — SEC filings, XBRL, 13F, insider and congressional trades. ⭐ 7 · [details](https://tradingaihub.com/tools/equibles/)
- ✅ [AlphaSMO tools](https://github.com/alphasmo/alphasmo-tools) — 13F holdings, Form 4 insider trades and smart-money signals. ⭐ 2 · [details](https://tradingaihub.com/tools/alphasmo/)
- ✅ [Edgrapi skills](https://github.com/paperandbeyond23-gif/edgrapi-skills) — SEC EDGAR insider trades, 8-Ks, 13F/13D-G, XBRL and full-text search. ⭐ 1 · [details](https://tradingaihub.com/tools/edgrapi-skills/)
- ✅ [SEC EDGAR APIs](https://www.sec.gov/search-filings/edgar-application-programming-interfaces) *(official)* — Official SEC JSON APIs for company submissions and XBRL financial data. · [details](https://tradingaihub.com/tools/sec-edgar-api/)

- [DisconfirmAI](https://disconfirmai.com/en) — Investment research platform that looks for evidence that could overturn a thesis before you trust it. Daily reading, filings/data research, change radar, and personal investment frameworks.

## Quant & backtesting

- ✅ [TradingView MCP (community, unofficial)](https://github.com/atilaahmettaner/tradingview-mcp) — Unofficial community MCP (not affiliated with TradingView): screeners, multi-timeframe technical analysis and backtests for crypto, stocks, forex and futures. ⭐ 5,243 · [details](https://tradingaihub.com/tools/tradingview-mcp/)
- ✅ [Claude Trading Skills](https://github.com/tradermonty/claude-trading-skills) — Claude Code skills for trading analysis, e.g. IBD-style relative strength rating. ⭐ 3,702 · [details](https://tradingaihub.com/tools/claude-trading-skills/)
- ✅ [FinLab AI](https://github.com/koreal6803/finlab-ai) — Quant strategy generation and Taiwan stock market analysis with FinLab and Claude. ⭐ 425 · [details](https://tradingaihub.com/tools/finlab-ai/)
- ✅ [Trading Skills for options traders (community)](https://github.com/staskh/trading_skills) — Community Claude skills for options traders: scanners, Greeks, spreads, PMCC screens, correlations and IBKR portfolio reports. ⭐ 406 · [details](https://tradingaihub.com/tools/options-trading-skills/)
- 🗄️ [MCP Trader](https://github.com/wshobson/mcp-trader) — Trading MCP server with technical analysis and backtesting support. ⭐ 273 · [details](https://tradingaihub.com/tools/mcp-trader/)
- ✅ [Superior Trade skills](https://github.com/Superior-Trade/superior-skills) *(official)* — Agent skills for strategy authoring, backtesting and deployment on Superior Trade. ⭐ 232 · [details](https://tradingaihub.com/tools/superior-skills/)
- ✅ [QuantConnect MCP](https://github.com/QuantConnect/mcp-server) *(official)* — Official QuantConnect MCP for algorithmic trading research, backtests and deployment. ⭐ 80 · [details](https://tradingaihub.com/tools/quantconnect-mcp/)
- ✅ [VARRD](https://github.com/varrdinc/varrd) — Trading research: event studies, backtesting, multiple-testing correction and OOS validation. ⭐ 25 · [details](https://tradingaihub.com/tools/varrd/)
- ✅ [Chart Library MCP](https://github.com/grahammccain/chart-library-mcp) — Historical chart-pattern search across a large pattern library. ⭐ 23 · [details](https://tradingaihub.com/tools/chart-library-mcp/)
- 🔴 [Claude Code Trading Terminal](https://github.com/degentic-tools/claude-code-trading-terminal) — Agent-native trading terminal with sub-agents for trades, positions and risk. ⭐ 21 · [details](https://tradingaihub.com/tools/claude-code-trading-terminal/)
- ✅ [Pineify MCP](https://github.com/pineifyapp/pineify-mcp) *(official)* — Trading-code (Pine Script) validation and market intelligence. ⭐ 1 · [details](https://tradingaihub.com/tools/pineify-mcp/)

## Macro & economics

- ✅ [Frankfurter (FX rates API + MCP)](https://github.com/lineofflight/frankfurter) *(official)* — Free open-source exchange-rate API with central-bank reference rates back to 1948, plus an official hosted MCP endpoint. ⭐ 2,078 · [details](https://tradingaihub.com/tools/frankfurter/)
- ✅ [FRED MCP](https://github.com/stefanoamorelli/fred-mcp-server) — MCP server for Federal Reserve Economic Data (FRED) series search and retrieval. ⭐ 131 · [details](https://tradingaihub.com/tools/fred-mcp/)
- ✅ [FRED API (St. Louis Fed)](https://fred.stlouisfed.org/docs/api/fred/) *(official)* — Hundreds of thousands of US and international economic time series from the Federal Reserve Bank of St. Louis. · [details](https://tradingaihub.com/tools/fred-api/)
- ✅ [FXMacroData MCP](https://github.com/fxmacrodata/mcp-server-fxmacrodata) — Macro indicators, FX, economic calendars, COT and commodities. ⭐ 0 · [details](https://tradingaihub.com/tools/fxmacrodata-mcp/)
- ✅ [BLS Public Data API](https://www.bls.gov/developers/) *(official)* — US Bureau of Labor Statistics API: CPI, employment, wages, productivity and other official time series. · [details](https://tradingaihub.com/tools/bls-api/)
- ✅ [BEA API](https://apps.bea.gov/api/signup/) *(official)* — US Bureau of Economic Analysis API: GDP/NIPA, regional, industry, international transactions and investment position data. · [details](https://tradingaihub.com/tools/bea-api/)
- ✅ [World Bank Indicators API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-about-the-indicators-api-documentation) *(official)* — Nearly 16,000 development and economic indicators from 45+ World Bank databases, many going back 50+ years; no key needed. · [details](https://tradingaihub.com/tools/world-bank-api/)
- ✅ [DBnomics API](https://db.nomics.world/) *(official)* — Open aggregator of macroeconomic series from 90+ providers (IMF, OECD, Eurostat, ECB, national statistics) behind one free API. · [details](https://tradingaihub.com/tools/dbnomics-api/)

## Contributing

Submit a tool for free at https://tradingaihub.com/submit/ or open a PR. Entries are re-checked weekly; stale ones are flagged, not silently kept.

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) — list text is CC BY 4.0; attribution: "TradingAIHub, https://tradingaihub.com". Tool names and trademarks belong to their owners.
