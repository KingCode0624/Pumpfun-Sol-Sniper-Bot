# Solana GRPC Ultra-Fast pump fun migration to raydium sniper bot

This bot automatically buy tokens which was launched on pump fun and migrated to raydium with cheap price and sell after some time. You can customize trading strategy as yo u want.

# Requirements
This bot use the corvus's great grpc and rpc , so you don't need to purchase any expensive grpc or rpc service.

# Instructions
- Using the Solana CLI, generate a public-bundles.json keypair using the following command
`solana-keygen new --outfile ./public-bundles.json`(There is already this file exists)
![image](https://github.com/bigj-SVS/grpc-sniper/assets/173855326/a6624c17-4397-48f4-82ab-9b1940990b89)
- Move this file to your cloned grpc-sniper repo in the top-level parent directory
- Rename `.env.example` to `.env`
- Add your private key in base64 format which can be exported from either Phantom or derived from your JSON keypair for your wallet.

# Commands
- npm i
- npm run start
