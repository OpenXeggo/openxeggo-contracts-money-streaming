# openxeggo-contracts-money-streaming

## Contribution guidelines
View Contribution guidelines [here](CONTRIBUTING.md)

## Run Locally

### Clone
```bash
$ git clone https://github.com/OpenXeggo/openxeggo-contracts-money-streaming.git
$ cd openxeggo-contracts-money-streaming
```

### Installation
```bash
$ npm install -g truffle@5.4.0 
$ npm install
```

### Usage
```bash
$ touch .secret && echo "YOUR_PRIVATE_KEY" > .secret
$ touch .env && echo "INFURA_API_KEY={YOUR_INFURA_API_KEY}" >> .env
$ echo "MNEMONIC={YOUR_MNEMONIC}" >> .env
```
### Compile & Deploy
```bash
$ truffle compile --all
$ truffle deploy --reset --network ${NETWORK_NAME}
```
