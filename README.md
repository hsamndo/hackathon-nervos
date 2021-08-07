# hackathon-nervos

## Gitcoin: 0) Setup A Local CKB Node And CKB Indexer For The Testnet

| Task| asset |
| ------------- | ------------- |
| CKB node and indexer fully sync on testnet | [Image](./assets/00-full-sync-node-indexer.png) |


## Gitcoin: 1) Create A Godwoken Account On The EVM Layer 2 Testnet

| Task| asset |
| ------------- | ------------- |
| ckb-cli account list command | [Image](./assets/01-ckb-cli-account-list.png) |
| CKB Address Funded by Nervos Faucet | [Nervos Explorer](https://explorer.nervos.org/aggron/address/ckt1qyqr7j4ca8j6n07uwf0smk3ukytxxrt3ep8sezkvzc) |
| CKB Layer 1 CKB to Layer 2 Godwoken Account | [Image](./assets/01-ckb-transfer-l1-to-l2-godwoken.png) |

## Gitcoin: 2) Deploy A Simple Ethereum Smart Contract On Polyjuice

| Task| asset |
| ------------- | ------------- |
| Output Smart Contract Deployed | [Image](./assets/02-smart-contract-deployed.png) |
| Transaction Hash | [Hash](./assets/02-transaction-hash-smart-contract.txt) |
| Smart Contract Address | [Address](./assets/02-smart-contract-address.txt) |

## Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

| Task| asset |
| ------------- | ------------- |
| Output Smart Contract Call | [Image](./assets/03-smart-contract-call.png) |
| Write Transaction Hash | [Hash](./assets/03-write-transaction-hash.txt) |
| Smart Contract Address | [Address](./assets/03-smart-contract-address.txt) |
| ABI | [ABI](./assets/03-abi.json) |

## Gitcoin: 4) Issue An SUDT Token On Layer 1 And Deposit It To Layer 2

| Task| asset |
| ------------- | ------------- |
| CKB Address Funded by Nervos Faucet | [Nervos Explorer](https://explorer.nervos.org/aggron/address/ckt1qyqr7j4ca8j6n07uwf0smk3ukytxxrt3ep8sezkvzc) |
| sudt-cli create sudt token | [Image](./assets/04-sudt-minted.png) |
| Transaction ID sudt | [Nervos Explorer](https://explorer.nervos.org/aggron/transaction/0xa20eadb680b16b04ff1e9479dab6d5515f598a0050278210d457ff15ddd08e5b) |
| Deposit to Layer 2 | [Image](./assets/04-sudt-sent-godwoken.png) |
| SUDT ID | [SUDT ID](./assets/04-sudt-id.txt) |

## Gitcoin: 5) Deploy The ERC20 Proxy Contract For The Deposited SUDT

| Task| asset |
| ------------- | ------------- |
| Output Deployed Proxy Contract | [Image](./assets/05-smart-contract-proxy-deployed.png) |
| Proxy Contract Address | [Address](./assets/05-address-ERC20-proxy-contract.txt) |
| Checking SUDT Balance | [Image](./assets/05-balance-checked.png) |
| Ethereum Address Checked | [Address](./assets/05-ethereum-address.txt) |

## Gitcoin: 6) Use Force Bridge To Deposit Tokens From Ethereum To Polyjuice

| Task| asset |
| ------------- | ------------- |
| Deposit Receiver Address Generated | [Image](./assets/06-deposit-receiver-address.png) |
| Deposit Receiver Address | [Address](./assets/06-deposit-receiver-address.txt) |
| Ethereum Address | [Address](./assets/06-ethereum-address-to-generate-receiver.txt) |
| Etherscan Transaction | [Etherscan](https://rinkeby.etherscan.io/tx/0xb1fd26dcd87722f455394d7710f7ee2f933154141a8fedacd89e58cc7d61ca78) |
| Success Transaction on Nervos Explorer | [Explorer](https://explorer.nervos.org/aggron/transaction/0x1c327e8dec48f03346101c4395a95ed0287d157dff2be69b9e064229b0b3e34f) |

## Gitcoin: 9) Initiate Withdrawal Process From The Layer 2 Back To Layer 1

| Task| asset |
| ------------- | ------------- |
| Output Initiate The Withdrawal | [Image](./assets/09-output-initiate-withdrawal-process.png) |
| Ethereum Address | [Address](./assets/09-ethereum-address-used.txt) |
| CKB Address L1 | [Address](./assets/09-nervos-l1-address.txt) |
