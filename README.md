# **Solana Copy trading Bot**
![copytradingbot](https://github.com/user-attachments/assets/e00dd28f-61b2-4b0e-ad97-646d1e4173f3)


Solana trading bot trading bot (Raydium) which subscribe target wallet's trading activity and copy transactions on Solana Raydium. as target trader.

1. ## Transaction
- Target Wallet: GXAtmWucJEQxuL8PtpP13atoFi78eM6c9Cuw9fK9W4na
- Copy Wallet: HqbQwVM2fhdYJXqFhBE68zX6mLqCWqEqdgrtf2ePmjRz
- Target Transaction: https://solscan.io/tx/2nNc1DsGxGoYWdweZhKQqnngfEjJqDA4zxnHar2S9bsAYP2csbLRgMpUmy68xuG1RaUGV9xb9k7dGdXcjgcmtJUh
- Copied Transaction: https://solscan.io/tx/n2qrk4Xg3gfBBci6CXGKFqcTC8695sgNyzvacPHVaNkiwjWecwvY5WdNKgtgJhoLJfug6QkXQuaZeB5hVazW6ev

2. ## **Features**

- ### Real-time WebSocket Streaming:

  Connects to Solana's blockchain through Helius geyser RPC WebSocket and listens for new transactions, specifically Tx that target wallet is singer
- ### Filter Transactions:

  Filters transactions as soon as possible and fast.
  maybe it takes about 0.3ms totally

- ### Make Copy transaction:

  Using program id and raydium module you can make copy trasaction.
