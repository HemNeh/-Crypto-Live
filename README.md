# -Crypto-Live
# Crypto Live INR Chart

A simple lightweight crypto chart (BTC/ETH/SOL/XRP) in INR with:

- Live WebSocket updates
- Volume bars
- MA50 / MA200 lines
- Dark mode toggle
- Mobile fullscreen support

## How to Use

1. Upload this HTML to GitHub Pages or open locally with a Live Server.
2. Select the coin and timeframe (1m, 5m, 1h).
3. Dark mode and fullscreen are available.

## Note

- Historical data uses a CORS proxy (`https://corsproxy.io/`) to work on GitHub Pages.
- WebSocket connects to `wss://stream.wazirx.com/ws` for live price updates.
