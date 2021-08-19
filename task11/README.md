# 👉 Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

### Screenshot of the accounts you created (account list)

<img src="https://github.com/homerosland/nervos-gitcoin-hack/blob/master/task11/img1.jpg">

### Link to the Layer 1 address you funded

https://explorer.nervos.org/aggron/address/ckt1qyqy3lcy5v8zw6qgnph7ve0f98dmzcyw2j9qr8tkan

### Screenshot, CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/homerosland/nervos-gitcoin-hack/blob/master/task11/img2.jpg">

### Screenshot, smart contract calls on Layer 2

<img src="https://github.com/homerosland/nervos-gitcoin-hack/blob/master/task11/img3.jpg">

### The transaction hash from the console output 

Write call transaction hash:
```bash
0x108349031741e7320d3f4400158c24f188e2e07594b93643fb7b410a6d6d4e9b
```

### The contract address that you called

```bash
0xE0dC75b6bef9EC62F81BE5C21C9DD35402C7a113
```

### The ABI for contract you made a call on

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
        "internalType": "uint256",
        "name": "likes",
        "type": "uint256"
      },
      {
        "indexed": false,
        "internalType": "uint256",
        "name": "dislikes",
        "type": "uint256"
      }
    ],
    "name": "PizzaCreated",
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
    "name": "pizzas",
    "outputs": [
      {
        "internalType": "uint256",
        "name": "id",
        "type": "uint256"
      },
      {
        "internalType": "uint256",
        "name": "likes",
        "type": "uint256"
      },
      {
        "internalType": "uint256",
        "name": "dislikes",
        "type": "uint256"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "_id",
        "type": "uint256"
      }
    ],
    "name": "createPizza",
    "outputs": [],
    "stateMutability": "nonpayable",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "_id",
        "type": "uint256"
      }
    ],
    "name": "like",
    "outputs": [],
    "stateMutability": "nonpayable",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "_id",
        "type": "uint256"
      }
    ],
    "name": "dislike",
    "outputs": [],
    "stateMutability": "nonpayable",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "_id",
        "type": "uint256"
      }
    ],
    "name": "getPizza",
    "outputs": [
      {
        "components": [
          {
            "internalType": "uint256",
            "name": "id",
            "type": "uint256"
          },
          {
            "internalType": "uint256",
            "name": "likes",
            "type": "uint256"
          },
          {
            "internalType": "uint256",
            "name": "dislikes",
            "type": "uint256"
          }
        ],
        "internalType": "struct Vote.Pizza",
        "name": "",
        "type": "tuple"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  }
]
```

### Your Tron address

```bash
TM2onUPnuK8wm7eCxKWBgDVEzk2Hr7GmJk
```
