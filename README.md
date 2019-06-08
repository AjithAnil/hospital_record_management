# Hospital Record Management

Ethereum sample project based on hospital record smart contract

## steps to install
### Ethereum package management

```
$ truffle install hospital-network@0.0.5
```

### Clone
Clone repo:
```
git clone https://github.com/AjithAnil/hospital_record_managementt
```

Create a new ```.env``` file in root directory and add your private key:
```
RINKEBY_PRIVATE_KEY="Paste your private key..."
ROPSTEN_PRIVATE_KEY="Paste your private key..."
```
You can use private key provided by Ganache if you dont have one:
Note:Only for developement.
```
RINKEBY_PRIVATE_KEY="c87509a1c067bbde78beb793e6fa76530b6382a4c0241e5e4a9ec0a0f44dc0d3"
```

next step:
```
npm install
```
To enter Truffle:
```
truffle develop
```
To compile:
```
truffle(develop)> compile
```
To migrate:
```
truffle(develop)> migrate
```
To test:
```
truffle(develop)> test
```
or
```
npm run test
```

### Solidity Coverage
```
$ npm run coverage
```
For solidity-coverage Truffle needs to be installed globally
Coverage report available [here](./coverage).


## Lint
To fix warnings:
```
$ npm run fix . --ext .js
```
For solium linter:
```
$ solium -d contracts
```
