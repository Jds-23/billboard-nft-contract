# How to deploy to Rinkeby blockchain👀

- Run `git clone https://github.com/Jds-23/billboard-nft-contract.git`
- Then `cd billboard-nft-contract`
- Run `npm install`
- Create a `secrets.json` in root directory
- Copy and Paste contents of `secrets.example.json` to `secrets.json`
- Put In Your Alchemy Key and Wallets Secret Key
- Run `npx hardhat run scripts/deploy.js --network rinkeby`
- Good to go 😎
