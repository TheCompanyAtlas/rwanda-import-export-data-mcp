# Rwanda Import Export Data MCP

**Rwanda Customs Data: Importers, Suppliers & HS Codes.** Rwanda import export data for your AI assistant. Search Rwanda customs shipment records, find importers and foreign suppliers, and break down trade by HS code, partner country and counterparty company, through the Model Context Protocol.

An AI-native alternative to Rwanda trade data from Panjiva, ImportGenius, Volza, Seair, TradeInt and ExportGenius: ask in plain language instead of exporting spreadsheets.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/trade/rwanda
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month
- Defaults to Rwanda: the server tells your AI to filter on `RW` unless you ask about another country

## Rwanda data coverage

- **Years:** 2024–2026
- **Records:** Import declarations: Rwandan importer, foreign supplier, origin country, HS code, goods description, value, quantity, port and date.
- **Country code:** `RW` (use `buyerCountry: "RW"` for imports into Rwanda)
- **Common products:** medicines (HS 3004), cars (HS 8703), phones (HS 8517), cement (HS 2523)

> Coverage is limited.

## Notable traders in the data

Companies that appear most often in recent Rwanda records (by number of declaration lines, not value):

**Importers**

- Crinnod Limited
- Vitae Business Consultants
- Catholic University of Rwanda

## Example prompts

- *"Who are the top importers of medicines (HS 3004) into Rwanda?"*
- *"List Rwandan importers of cars (HS 8703) in 2025"*
- *"Which countries supply phones (HS 8517) to Rwanda?"*
- *"Show recent import shipments of cement (HS 2523) into Rwanda"*

## Tools

### Trade search

| Tool | Description |
|---|---|
| `Trade_search_trades` | Paginated customs shipment search: filter by HS code, buyer, seller, country, port, value and date range |
| `Trade_company_trade_volume_by_year` | Rank importers or exporters by declared value and line counts per year, with HS code and country filters |

### Trade analytics

| Tool | Description |
|---|---|
| `Trade_hs_code_breakdown` | For one company, import and export value by HS chapter, heading or subheading |
| `Trade_year_country_breakdown` | For one company, trade value by year and counterparty country |
| `Trade_partner_breakdown` | For one company, trade value by year and matched counterparty company |

### Company registry

| Tool | Description |
|---|---|
| `Company_search` | Search the global company registry by name or id, with optional country filter |
| `Company_get_by_id` | Full company profile by id |

## Keywords

Rwanda import data, Rwanda export data, Rwanda customs data, Rwanda shipment data, importers in Rwanda, Rwanda buyers and suppliers, HS code search, Rwanda customs data, RRA import data, importers in Rwanda
