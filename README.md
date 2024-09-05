# Sunpump Volume Bot for Tron Chain

An advanced trading bot designed for pumping volume on the Tron network. This tool allows you to automate trading activities, generate volume, and potentially influence token metrics.

Full video available here: [https://www.youtube.com/watch?v=w-CvNUvh34Q](https://www.youtube.com/watch?v=w-CvNUvh34Q)

## Features

- Generate multiple wallets
- Fund wallets automatically
- Customizable buy/sell modes
- Volume generation
- Configurable trading parameters
- Support for TRC20 tokens

  ![Screen Shot 2567-09-05 at 2 34 40 PM](https://github.com/user-attachments/assets/e811f408-9d00-4551-84c8-2b95cd38e302)


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

## Usage

1. Set up your `config.ini` file with your parameters
2. Run the bot:
   ```
   npm run start
   ```
![Screen Shot 2567-09-05 at 2 35 03 PM](https://github.com/user-attachments/assets/674344a0-817f-4c97-8f36-1f89493f927a)


## Commands

- Check wallet balance: `balance`
- Generate wallets: `generate`
- Fund wallets: `fund`
- Start buying: `buy`
- Start selling: `sell`
- Single large buy: `singlebuy`
![Screen Shot 2567-09-05 at 2 35 21 PM](https://github.com/user-attachments/assets/f8a1bdf9-f6d1-4876-8570-5dd98462c403)


## Advanced Features

- Customizable single buy and auto settings
- Ability to run multiple instances for different strategies

## Support and Full Version

For assistance and access to the full version with advanced features, join our Telegram group:

[https://t.me/+glKuxUMA1Pw3ZTM0](https://t.me/+glKuxUMA1Pw3ZTM0)

## Disclaimer

This tool is powerful and can be used for both legitimate and potentially harmful purposes. Always use responsibly and in compliance with all applicable laws and regulations. The developers are not responsible for any misuse or consequences resulting from the use of this tool.


If you want a pump.fun bundler, [check this one](https://github.com/antoinersx/pumpfun-bundler)
