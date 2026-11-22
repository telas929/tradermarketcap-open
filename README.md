# tradermarketcap-open

Add an HTX (Huobi) exchange reader

## Overview

**Bounty: 2 RESET** (paid when merged, see CONTRIBUTING.md)

**Done when:** HTX spot tickers read from https://api.huobi.pro/market/tickers, keeping USD, USDT and USDC pairs. Readers live in `collector/sources/exchanges.mjs` (add the venue to VENUES and a reader to READERS, like the Bitget and Binance.US readers). Free public endpoint only, no API keys. Return price, base volume, quote volume, 24h change, an API link and a trade link per pair. Throw on an error answer (don't return an empty list

## Installation

```bash
# Clone the repository
git clone https://github.com/tradermarketcap/tradermarketcap-open.git
cd tradermarketcap-open

# Install dependencies (if applicable)
pip install -r requirements.txt  # Python
# or
npm install  # Node.js
```

## Usage

```bash
# Run the project
python main.py  # Python
# or
node index.js  # Node.js
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request

## License

See [LICENSE](LICENSE) for details.
