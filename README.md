# [SE122.M21][web_link] - OpenSky - NFT Marketplace

## [Link Deploy Front-end][deploy_link]

## [Link Deploy Back-end][backend_deploy_link]

## [Github Backend][github_frontend]

## [Github Backend][github_backend]

## [Github Smart Contract][github_smart_contract]

[![Version](https://img.shields.io/badge/version-0.0.1-brightgreen)][web_link]
[![Contributors](https://img.shields.io/badge/contributors-2-blue)][web_link]

## Frontend Developer

- Nguyễn Đức Hướng - 19521592 - duchuong007@gmail.com

## Backend Developer

- Ngô Dương Kha - 19520117 - 19520117@gm.uit.edu.vn

[//]: # "LINKS"
[web_link]: https://github.com/huongnguyenduc/nft-auction-documentation
[deploy_link]: https://nft-auction-uit.vercel.app/
[backend_deploy_link]: https://nft-auction-backend.herokuapp.com/api
[github_frontend]: https://github.com/ngoduongkha/nft-auction
[github_backend]: https://github.com/ngoduongkha/nft-auction-backend
[github_smart_contract]: https://github.com/ngoduongkha/nft-auction-contract

## !! BEFORE RUNNING PROJECT ON LOCALHOST

Require NodeJs and npm installed on your computer. You can check how to install those on Internet to match with your operating system.

## How to run Frontend project

### Prepare environment

Install `node_modules`:

```bash
npm install
```

Provide .env file in root directory

```bash
NEXT_PUBLIC_PROJECT_ID=ff81c88502c540f0b690b55ed77a2c71
NEXT_PUBLIC_CONTRACT_ADDRESS=0x6d20Dd6bA2B22123F040ee1996B34FC072410399
NEXT_PUBLIC_VERIFY_SIGNATURE_CONTRACT_ADDRESS=0xE95Fb2e63772d2d42Ac8B9072791B4ad773352DA
NEXT_PUBLIC_BACKEND_API_URL=https://nft-auction-backend.herokuapp.com/api
NEXT_PUBLIC_CLOUDINARY_API_URL="https://api.cloudinary.com/v1_1/huong/image/upload"
NEXTAUTH_SECRET=QQT4ZEEkCi78yq3NWqjTA6v70gxzvu5h
```

### Start project

```bash
npm run dev
```

## How to run Backend project

### Prepare environment

Install `node_modules`:

```bash
npm install
```

Provide .env file in root directory

```bash
PROJECT_ID=ff81c88502c540f0b690b55ed77a2c71
MARKET_CONTRACT_ADDRESS=0x6d20Dd6bA2B22123F040ee1996B34FC072410399
VERIFY_SIGNATURE_CONTRACT_ADDRESS=0xE95Fb2e63772d2d42Ac8B9072791B4ad773352DA
PRIVATE_KEY=<Your Private Key, use to end auction on server>
```

### Start project

```bash
npm run start
```

## How to run Contract project

### Prepare environment

Install `node_modules`:

```bash
npm install
```

### Compile Smart Contract

```bash
npx hardhat compile
```

### Unit-test Smart Contract

```bash
npx hardhat test <PATH TO TEST FILE>
```

### Deploy Smart Contract

```bash
npx hardhat run ./scripts/deploy.js --network rinkeby
```
