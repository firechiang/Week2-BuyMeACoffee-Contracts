# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

```shell
# 本地部署加测试
$ npx hardhat run scripts/buy-coffee.js
# 部署到Goerli测试网（注意：配置写在hardhat.config.js里面）
$ npx hardhat run scripts/deploy.js --network goerli
```