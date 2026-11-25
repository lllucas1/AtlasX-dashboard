# AtlasX live dashboard

Public page for the AtlasX **paper** bot: live BTC/ETH prices from Coinbase, the 200-day averages the bot trades on, its paper holdings and trades. No keys, no real money.

- `index.html`: the page. It fetches prices in the browser straight from Coinbase's public API.
- `state.json`: the paper bot's saved state, pushed by the private AtlasX repo's workflow after each daily run.
