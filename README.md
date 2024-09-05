# Sunpump Volume Bot for Tron Chain

An advanced trading bot designed for pumping volume on the Tron network. This tool allows you to automate trading activities, generate volume, and potentially influence token metrics.

**Disclaimer:** This tool is for educational purposes only. Use at your own risk and always comply with local regulations.

## Features

- Generate multiple wallets
- Fund wallets automatically
- Customizable buy/sell modes
- Volume generation
- Configurable trading parameters
- Support for TRC20 tokens
- Integration with BullXTron for advanced filtering

## Installation

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Configure your `config.ini` file (see Configuration section)

## Configuration

Edit the `config.ini` file with your parameters:

```ini
[Wallet]
NumWallets = 25
FundAmount = 200

[Trading]
MinBuy = 50
MaxBuy = 140
Interval = 2.5

[Token]
ContractAddress = YOUR_TOKEN_ADDRESS_HERE

[Telegram]
ChannelLink = YOUR_TELEGRAM_CHANNEL_LINK
```

## Usage

1. Set up your `config.ini` file with your parameters
2. Run the bot:
   ```
   npm run start
   ```

## Commands

- Check wallet balance: `balance`
- Generate wallets: `generate`
- Fund wallets: `fund`
- Start buying: `buy`
- Start selling: `sell`
- Single large buy: `singlebuy`

## Advanced Features

- Integration with BullXTron for filtering (developers holding < 15%, > 22 holders)
- Customizable market cap settings
- Ability to run multiple instances for different strategies

## Support and Full Version

For assistance and access to the full version with advanced features, join our Telegram group:

[https://t.me/+glKuxUMA1Pw3ZTM0](https://t.me/+glKuxUMA1Pw3ZTM0)

## Disclaimer

This tool is powerful and can be used for both legitimate and potentially harmful purposes. Always use responsibly and in compliance with all applicable laws and regulations. The developers are not responsible for any misuse or consequences resulting from the use of this tool.

Remember: The blockchain is an open ledger. Use this knowledge wisely and ethically.

Stay handsome and trade responsibly!
