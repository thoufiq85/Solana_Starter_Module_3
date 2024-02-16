# Solana_Starter_Module_3
- Simple project where create a candymachine minting NFTs and creating a spl tokens and minting the NFT using the spl-token .

# Instructions
- Create a spl-tokens
- mint Nft using candyMachine UI
- import candy Machine -UI from chain link Quicknode or metaplex 
- change the env file with your candymachine id
- npm install
- npm run start to start on local host : 3000
- click mint button to mint
- Approve the transaction to mint the NFT .
# Commands
## Generate new Keypair on devnet
- `solana-keygen new --outfile ./wallet.json`.
- ` solana config set -u https://api.devnet.solana.com`.
- `solana config set --keypair ./wallet.json`.
- `solana airdrop 3`.
## Spl-token creation
- `spl-token create-token`.
- `spl-token create-account 37HqEQwn4zdiWuZ6FY76Ytuqk8UieBxxK6oPW7TdEE2u`.
- `spl-token mint 37HqEQwn4zdiWuZ6FY76Ytuqk8UieBxxK6oPW7TdEE2u 10005`.
## SugarCLI  to Create a NFT CandyMachine
- `sugar validate`.
- `sugar upload`.
- `sugar deploy`.
- `sugar verify`.
- `sugar mint`.
# Author 
- MODH THOUFIQ
