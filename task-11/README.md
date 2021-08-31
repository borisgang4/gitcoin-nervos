# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

### 1- A screenshot of the accounts you created

<img src="https://github.com/borisgang4/gitcoin-nervos/blob/master/task-11/accs.png" />

### 2- A link to the Layer 1 address you funded on the Testnet Explorer

- <a href="https://explorer.nervos.org/aggron/address/ckt1qyq8h2q48wh8yvag3pg0ma725zcce0shphuse22htl">Funded Account Address </a>

### 3- A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/borisgang4/gitcoin-nervos/blob/master/task-11/deposit.png" />

### 4- A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/borisgang4/gitcoin-nervos/blob/master/task-11/contract.png" />

### 5- The transaction hash of the "Contract call" from the console output

```bash
0x70f2142f95f8bfdae46f5900e213dba087aae6dd0559997f4398e097cba01145
```

### 6- The contract address that you called

```bash
0x6933a1b12476A7fbfef565c1b8cc92ee5e14a2a8
```
### 7- The ABI for contract you made a call on

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

### 8- Your Tron address

```bash
TEEisG2MNL1awp3Vt6xbMPKvXJAvf4Dmko
```





