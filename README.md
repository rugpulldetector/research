## Digital real
http://65.108.198.248:8000/braz_smartcontracts.zip

http://65.108.198.248:8000/hardhat-nodejs.zip

1) Preparing
Extract to `C:\Users\root\AppData\Local\hardhat-nodejs`

2) Compiling
```
npx hardhat compile
```

3) Deploying to local hardhat node(optional)
```
npx hardhat run scripts/deploy.js --network hardhat
```

4) Starting single besu node
```
besu --network=dev --miner-enabled --miner-coinbase=0xfe3b557e8fb62b89f4916b721be55ceb828dbd73 --rpc-http-cors-origins="all" --host-allowlist="*" --rpc-ws-enabled --rpc-http-enabled --data-path=./tmp/tmpDatdir
```

5) Deploying to besu node
```
npx hardhat run scripts/deploy.js --network besuPrivate
```
```
SUMMARY:
DeployedContracts:
┌─────────┬─────────────────────────────┬──────────────────────────────────────────────┐
│ (index) │            name             │                   address                    │
├─────────┼─────────────────────────────┼──────────────────────────────────────────────┤
│    0    │     'AddressDiscovery'      │ '0x5FbDB2315678afecb367f032d93F642f64180aa3' │
│    1    │        'RealDigital'        │ '0xe7f1725E7734CE288F8367e1Bb143E90bb3F0512' │
│    2    │        'SwapOneStep'        │ '0x9fE46736679d2D9a65F0992F2272dE9f3c7fa6e0' │
│    3    │       'SwapTwoSteps'        │ '0xCf7Ed3AccA5a467e9e704C703E8D87F634fB0Fc9' │
│    4    │ 'RealDigitalDefaultAccount' │ '0x5FC8d32690cc91D4c39d9d3abcBD16989F875707' │
│    5    │ 'RealDigitalEnableAccount'  │ '0x0165878A594ca255338adfa4d48449f69242Eb8F' │
│    6    │  'RealTokenizado@12345678'  │ '0x2279B7A0a67DB372996a5FaB50D91eAA73d2eBe6' │
│    7    │  'RealTokenizado@87654321'  │ '0x8A791620dd6260079BF849Dc5567aDC3F2FdC318' │
│    8    │            'STR'            │ '0x610178dA211FEF7D417bC0e6FeD39F05609AD788' │
└─────────┴─────────────────────────────┴──────────────────────────────────────────────┘
Participants:
┌─────────┬──────────┬──────────────────────────────────────────────┬─────────────────────┐
│ (index) │  cjnp8   │                   address                    │       signer        │
├─────────┼──────────┼──────────────────────────────────────────────┼─────────────────────┤
│    0    │ 12345678 │ '0x3C44CdDdB6a900fa2b585dd299e03d12FA4293BC' │ [SignerWithAddress] │
│    1    │ 87654321 │ '0x90F79bf6EB2c4f870365E785982E1f101E93b906' │ [SignerWithAddress] │
└─────────┴──────────┴──────────────────────────────────────────────┴─────────────────────┘
Admin: 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266
Authority: 0x70997970C51812dc3A010C7d01b50e0d17dc79C8
Contract deployer: 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266
```

6) Adding RealDigital(BRL) token address to Metamask

## Alpha Wallet
http://65.108.198.248:8000/AlphaWallet-v3.72.apk
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.001
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.002
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.003
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.004
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.005
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.006
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.007
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.008
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.009
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.010
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.011
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.012
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.013
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.014
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.015
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.016
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.017
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.018
http://65.108.198.248:8000/alpha-wallet-android-3.72.zip.019

http://65.108.198.248:8000/gradle/.gradle.zip.001
http://65.108.198.248:8000/gradle/.gradle.zip.002
http://65.108.198.248:8000/gradle/.gradle.zip.003
http://65.108.198.248:8000/gradle/.gradle.zip.004
http://65.108.198.248:8000/gradle/.gradle.zip.005
http://65.108.198.248:8000/gradle/.gradle.zip.006
http://65.108.198.248:8000/gradle/.gradle.zip.007
http://65.108.198.248:8000/gradle/.gradle.zip.008
http://65.108.198.248:8000/gradle/.gradle.zip.009
http://65.108.198.248:8000/gradle/.gradle.zip.010
http://65.108.198.248:8000/gradle/.gradle.zip.011
http://65.108.198.248:8000/gradle/.gradle.zip.012
http://65.108.198.248:8000/gradle/.gradle.zip.013
http://65.108.198.248:8000/gradle/.gradle.zip.014
http://65.108.198.248:8000/gradle/.gradle.zip.015
http://65.108.198.248:8000/gradle/.gradle.zip.016
http://65.108.198.248:8000/gradle/.gradle.zip.017
http://65.108.198.248:8000/gradle/.gradle.zip.018
http://65.108.198.248:8000/gradle/.gradle.zip.019
http://65.108.198.248:8000/gradle/.gradle.zip.020
http://65.108.198.248:8000/gradle/.gradle.zip.021
http://65.108.198.248:8000/gradle/.gradle.zip.022
http://65.108.198.248:8000/gradle/.gradle.zip.023
http://65.108.198.248:8000/gradle/.gradle.zip.024
http://65.108.198.248:8000/gradle/.gradle.zip.025
http://65.108.198.248:8000/gradle/.gradle.zip.026
http://65.108.198.248:8000/gradle/.gradle.zip.027
http://65.108.198.248:8000/gradle/.gradle.zip.028
http://65.108.198.248:8000/gradle/.gradle.zip.029
http://65.108.198.248:8000/gradle/.gradle.zip.030
http://65.108.198.248:8000/gradle/.gradle.zip.031
http://65.108.198.248:8000/gradle/.gradle.zip.032
http://65.108.198.248:8000/gradle/.gradle.zip.033
http://65.108.198.248:8000/gradle/.gradle.zip.034
http://65.108.198.248:8000/gradle/.gradle.zip.035
http://65.108.198.248:8000/gradle/.gradle.zip.036
http://65.108.198.248:8000/gradle/.gradle.zip.037

```
gradlew bundle
```

## Solidity Tutorial
http://65.108.198.248:8000/docs-soliditylang-org-en-latest.pdf

http://65.108.198.248:8000/full-stack-ethereum.zip

1) Compiling
```
npx hardhat compile
```

2) Deploying to local hardhat node
```
npx hardhat run scripts/deploy.js --network hardhat
```

3) Running web frontend
```
yarn start
```

## Yarn
http://65.108.198.248:8000/global-npm.zip

Copy Location
```
C:\Users\root\AppData\Roaming\npm
```

## Foundry
http://65.108.198.248:8000/foundry.7z

## Other
http://65.108.198.248:8000/2031105.zip

http://65.108.198.248:8000/android.zip

http://65.108.198.248:8000/compose-samples.zip

## Besu
http://65.108.198.248:8000/besu/besu-23.7.2.zip.001
http://65.108.198.248:8000/besu/besu-23.7.2.zip.002
http://65.108.198.248:8000/besu/besu-23.7.2.zip.003
http://65.108.198.248:8000/besu/besu-23.7.2.zip.004
http://65.108.198.248:8000/besu/besu-23.7.2.zip.005
http://65.108.198.248:8000/besu/besu-23.7.2.zip.006


## Metamask
http://65.108.198.248:8000/metamask-extension.zip.001
http://65.108.198.248:8000/metamask-extension.zip.002
http://65.108.198.248:8000/metamask-extension.zip.003
http://65.108.198.248:8000/metamask-extension.zip.004
http://65.108.198.248:8000/metamask-extension.zip.005
http://65.108.198.248:8000/metamask-extension.zip.006
http://65.108.198.248:8000/metamask-extension.zip.007
http://65.108.198.248:8000/metamask-extension.zip.008
http://65.108.198.248:8000/metamask-extension.zip.009
http://65.108.198.248:8000/metamask-extension.zip.010
http://65.108.198.248:8000/metamask-extension.zip.011
http://65.108.198.248:8000/metamask-extension.zip.012
http://65.108.198.248:8000/metamask-extension.zip.013
http://65.108.198.248:8000/metamask-extension.zip.014
http://65.108.198.248:8000/metamask-extension.zip.015


