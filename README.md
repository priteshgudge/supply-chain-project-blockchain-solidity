# Supply Chain Project Ethereum Solidity 

### Versions

```
Truffle v5.1.0 (core: 5.1.0)
Solidity v0.5.0 (solc-js)
Node v8.16.2
truffle-hdwallet-provider v1.0.2
web3 v6.4.1
```

## Rinkeby Deployment & Testing references

``` bash
Rinkeby Contract Address: 0x2AF679d0c76489ec90170649F79142Fbd79D00E1
Transaction Hash: 0x6491b8364e347aa467ab468c448790a567ff20456068d03f2ef4b398555f655f
Account: 0xace8a3DA01A28d4A1b50cDD9Cae6188704591981
Contract Owner: 0xace8a3DA01A28d4A1b50cDD9Cae6188704591981
Farmer: 0x7F6EF66C70C7e48Ae253E722AC1c8Dc9B3195808
Distributor: 0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
Retailer: 0x018C2daBef4904ECbd7118350A0c54DbeaE3549A
Consumer: 0xCe5144391B4aB80668965F2Cc4f2CC102380Ef0A
```

### Rinkeby Testing Transactions

``` bash
    Harvested - 0x419230fb75dddf50fc2771c043a10d97baabc706058c9bb059be55c8a714e3a6
    Processed - 0xd562bd5ea4594229194595d4952aae87f9996b0c9b05a89e608cf3c4ce725242
    Packed - 0x9d57b523a3ca0a3e2b4beb61bd7658c210a4996f85c99428756a96448bf7bd72
    ForSale - 0x90bb7a3239d2dbb9ef667e310ac9bdfb964c37d4eaee99ac9a69855d78b40679
    Sold - 0x9a38963205d9aed31ad2b863a9cdca9eeefd105ee9694a200bf99bc9c4946e92
    Shipped - 0x1f1d9b7ef695add4c779a38a1ac7de4d227cebd7ebb54c9ad069668f24b65e80
    Received - 0x4efc14c05678f9de9789a0947ecf9618928c92737be983b3a28f7c0801e15342
    Purchased - 0x8377ffb81732c5d93493e91bc796037f28f91506ab313509652d9a2b25805ac6
```

![Rinkeby Transaction Log](/images/rinkeby_tranactions_client.png)

### Libraries Used

truffle-hdwallet-provider: Used to sign transactions from adderesses derived from mnemonic. In this case it is used to deploy the contract on Rinkeby network via Infura.
