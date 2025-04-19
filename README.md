# R2Money-Auto-Bot

An automated bot for interacting with the R2 Money protocol on the Sepolia testnet. This bot allows users to perform swaps between USDC and R2USD tokens, as well as stake R2USD to receive sR2USD tokens.

- Register: [https://r2.money](https://r2.money?code=6G8BH)
- Faucet: https://discord.gg/r2yield
## Features

- Swap USDC to R2USD
- Swap R2USD to USDC
- Stake R2USD to sR2USD
- Check token balances
- Support for multiple wallets
- Proxy support for IP rotation

## Prerequisites

- Node.js v16 or higher
- Ethereum wallet with private key
- Sepolia ETH for gas fees
- Sepolia USDC tokens

## Installation

1. Clone the repository:
```bash
git clone https://github.com/airdropinsiders/R2Money-Auto-Bot.git
cd R2Money-Auto-Bot
```

2. Install dependencies:
```bash
npm install
```

3. Create an `.env` file with your private key(s):
```
PRIVATE_KEY_1=your_private_key_here
PRIVATE_KEY_2=another_private_key_here
# Add more keys as needed
```

4. (Optional) Create a `proxies.txt` file with your proxies (one per line):
```
http://username:password@host:port
http://host:port
```

## Usage

Run the bot with:

```bash
node index.js
```

Follow the interactive menu to:
1. Swap USDC to R2USD
2. Swap R2USD to USDC
3. Stake R2USD to sR2USD
4. Check balances
5. Exit

## Token Addresses (Sepolia)

- USDC: `0xef84994ef411c4981328ffce5fda41cd3803fae4`
- R2USD: `0x20c54c5f742f123abb49a982bfe0af47edb38756`
- sR2USD: `0xbd6b25c4132f09369c354bee0f7be777d7d434fa`

## Security Notes

- This bot requires your private keys. Never share your private keys with anyone.
- Use this bot only on the Sepolia testnet.
- Always review the code before running it with your private keys.

## Disclaimer

This bot is for educational purposes only. Use at your own risk. The creators of this bot are not responsible for any loss of funds.

## License

MIT License

## Join Our Community

- Telegram: [https://t.me/AirdropInsiderID](https://t.me/AirdropInsiders)
