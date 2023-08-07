# This project is official tutorial to build a Aptos Dapp

## requirement
* Aptos Wallet: [Petra wallet extension](https://petra.app/)
* Aptos CLI: 
    * Install the [Aptos CLI](https://aptos.dev/tools/aptos-cli/install-cli/)


## Run this project

### setup
* init account
    * aptos init --profile my-first-nft
    * chose devnet
    * create a petra wallet and copy private key to terminal 
* publish mode
    * example: 
    * aptos move publish --profile my-first-nft --package-dir ~/code/aptos-core/aptos-move/move-examples/hello_blockchain/ --named-addresses hello_blockchain=0x5af503b5c379bd69f46184304975e1ef1fa57f422dd193cdad67dc139d532481
    *  --named-addresses  is your wallet addresss

### run
```
npm start 
```

