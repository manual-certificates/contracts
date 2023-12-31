# Manual certificates Contracts

This repository contains Manual certificates contracts.


#### Test

To run the tests, execute the following command:

```bash
npm run test
```

Or to see the coverage, run:

```bash
npm run coverage
```

#### Local deployment

To deploy the contracts locally, run the following commands (in the different terminals):

```bash
npm run private-network
npm run deploy-local
```

#### Bindings

The command to generate the bindings is as follows:

```bash
npm run generate-types
```

> See the full list of available commands in the `package.json` file.

### Integrated plugins

- Hardhat official `ethers` + `ethers-v5`
- [`Typechain`](https://www.npmjs.com/package/@typechain/hardhat)
- [`hardhat-migrate`](https://www.npmjs.com/package/@dlsl/hardhat-migrate), [`hardhat-gobind`](https://www.npmjs.com/package/@dlsl/hardhat-gobind)
- [`hardhat-contract-sizer`](https://www.npmjs.com/package/hardhat-contract-sizer)
- [`hardhat-gas-reporter`](https://www.npmjs.com/package/hardhat-gas-reporter)
- [`solidity-coverage`](https://www.npmjs.com/package/solidity-coverage)

### Other niceties

- The template comes with presetup `prettier` and `solhint` that lint the project via `husky` before compilation hook.
- The `.env.example` file is provided to check what is required as ENVs
- Preinstalled `@openzeppelin/contracts` and `@dlsl/dev-modules`
