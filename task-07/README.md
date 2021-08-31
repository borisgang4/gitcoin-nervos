# Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

The DApp basically works in 3 steps:

- Generate random words
- Save selected words to blockchain 
- Show saved words with their user addresses

### 1- Screenshots or video of your application running on Godwoken


https://user-images.githubusercontent.com/89857663/131572585-5db5ad83-78ec-40d5-9167-0d4d10e1af9c.mp4

<br/>
<hr/>
<br/>
<img src="https://github.com/borisgang4/gitcoin-nervos/blob/master/task-07/ss.png" />

### 2- Link to the GitHub repository

<a href="https://github.com/borisgang4/Words-Dapp-Nervos"> Github Repo </a>

### 3- Transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract

Transaction hash:

```bash
0x7fe4235c3460aba9be6929535aeb712910d9582e3401b34427f2fe00103293fd
```

Contract Address:

```bash
0x6933a1b12476A7fbfef565c1b8cc92ee5e14a2a8
```

ABI

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "address",
          "name": "owner",
          "type": "address"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "word",
          "type": "string"
        }
      ],
      "name": "WordCreated",
      "type": "event"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "idToWord",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "address",
          "name": "owner",
          "type": "address"
        },
        {
          "internalType": "string",
          "name": "word",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "total",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_word",
          "type": "string"
        }
      ],
      "name": "assignWord",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```



