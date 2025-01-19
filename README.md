# Sight AI Testnet BOT

## Table Of Contents
- [Sight AI Testnet BOT](#sight-ai-testnet-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Sight Ai Incentive Testnet](#sight-ai-incentive-testnet)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS
- Eth Holesky Get it from 
  - https://holesky-faucet.pk910.de/
  - https://bwarelabs.com/faucets/ethereum-holesky
  - https://cloud.google.com/application/web3/faucet/ethereum/holesky

## Sight Ai Incentive Testnet
#New Testnet : Sight Ai
Incentivized

🏷 Reward : Confirmed
Network : Holesky
🪂 Register: https://sightai.io/dashboard?referral-code=QYED78
➖ Get ETH Holesky faucet
➖ Connect New Wallet / Wallet Testnet
➖ Participate in Prediction Market Event
➖ Daily Check-in
➖ Done

As you play, you'll be earning Sight Al testnet points. These points can be exchanged for mainnet tokens at launch.

📘Detail:
https://sightai.gitbook.io/docs/sight-oracle-incentive-plan-season-1

📘Source:
https://x.com/theSightAI/status/1839696985147973783

## BOT FEATURE

- Multi Account 
- Support PK
- Auto Daily Check IN
- Auto Bet on Prediction Market
- Auto Claim (IF BET WIN) -> MAYBE SOON


## Setup & Configure BOT

### Linux
1. clone project repo
   ```
   git clone https://github.com/Widiskel/sight-ai-bot.git 
   cd sight-ai-bot
   ```
2. run
   ```
   npm install
   npm run setup
   ```
3. configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. to start the app run
   ```
   npm run start
   ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/Widiskel/sight-ai-bot.git
   ```
   and cd to project dir
   ```
   cd sight-ai-bot
   ```
3. Run 
   ```
   npm install
   npm run setup
   ```
5. Navigate to `sight-ai-bot` directory. 
6. Navigate to `accounts` and configure `accounts.js`.
7. Back to `sight-ai-bot` directory. 
8. To start the app open your `Command Prompt` or `Power Shell` again and run
    ```
    npm run start
    ```

## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
2. start the bot

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks. To get original unencrypted code just join my channel, original code (index.js and src folder) are Obfuscated during build

## SUPPORT

want to support me for creating another bot ?
**star** my repo or buy me a coffee on

EVM : `0x1f0ea6e0b3590e1ab6c12ea0a24d3d0d9bf7707d`

SOLANA : `3tE3Hs7P2wuRyVxyMD7JSf8JTAmEekdNsQWqAnayE1CN`
