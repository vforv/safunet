# SafuNet

A self-custody crypto wallet and app built on **BNB Smart Chain (BSC)**: hold, send and swap BEP-20 tokens, buy crypto by card, check tokens with Guardian before you buy, and vote in the community DAO. Live at https://safunet.com.

This repository holds the public project information and the BNB Smart Chain network and contract configuration used by SafuNet. It contains no private keys or application secrets.

## Technology Stack

- **Blockchain**: BNB Smart Chain (BEP-20), EVM-compatible
- **Smart Contracts**: Solidity (Reflecto RTO token and fee calculator, RUSD stablecoin, Supreme Swap router, The CEO DAO)
- **Frontend**: Angular (server-side rendered) + web3.js
- **Backend**: Node.js / TypeScript API with ethers.js and web3.js, talking to BNB Smart Chain RPC nodes

## Supported Networks

- **BNB Smart Chain Mainnet** (Chain ID: 56): production at https://safunet.com
- **BNB Smart Chain Testnet** (Chain ID: 97): development and testing

Network settings: [`config/bsc-networks.json`](config/bsc-networks.json)

## Contract Addresses (BNB Smart Chain Mainnet, Chain ID 56)

| Contract | Address |
|---|---|
| Reflecto (RTO) token | [`0x5A341DCF49e161CC73591f02e5f8CDE8A29733fb`](https://bscscan.com/address/0x5A341DCF49e161CC73591f02e5f8CDE8A29733fb) |
| RTO fee calculator | [`0xE7F325D73cF851b2FaEC0037ED359e4920deC28d`](https://bscscan.com/address/0xE7F325D73cF851b2FaEC0037ED359e4920deC28d) |
| RTO rewards | [`0xa1c9Fb2D1349250ec7117E632107280f597905C6`](https://bscscan.com/address/0xa1c9Fb2D1349250ec7117E632107280f597905C6) |
| RUSD stablecoin | [`0x4be8c674c51674beb729832682bba5e5b105b6e2`](https://bscscan.com/address/0x4be8c674c51674beb729832682bba5e5b105b6e2) |

Always check a contract address against this list before you trade. SafuNet staff never ask for your private key, seed phrase or PIN.

## Features

- Wallet for BNB and BEP-20 tokens on BNB Smart Chain, with keys encrypted by your PIN and exportable at any time
- Swap any BSC token at the best rate across BSC DEXs
- Buy crypto by card (EU and US for now) delivered to your BSC address
- Guardian: token safety checks before you buy
- The CEO: holders decide on all Reflecto matters through the DAO
- Coming: perpetual futures and Prophet quant strategies inside the wallet

## Links

- App: https://safunet.com
- Reflecto (RTO): https://reflectocoin.com
- RUSD: https://reflectousd.com
- X: https://x.com/safu_net · https://x.com/reflectocoin
- Telegram: https://t.me/reflectocoin

## Security

Found a security problem? Report it privately through the Telegram link above before making it public.

## Brand assets

- Logo 400 x 400: https://safunet.com/assets/brand/safunet-logo-400.png
- Logo 250 x 250: https://safunet.com/assets/brand/safunet-logo-250.png
