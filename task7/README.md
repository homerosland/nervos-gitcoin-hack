### NERVOS/SATOSHI PIZZA STORE

# 👉 Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

### 🍕 Screenshots and video


- <a href="https://youtu.be/SaRoeZu7Xwc" target="_blank">PROJECT VIDEO LINK<a/>
  
<img src="https://github.com/homerosland/nervos-gitcoin-hack/blob/master/task7/nervos%20pizza.png"/>

  
### 🍕 Link to the GitHub repository

  
- <a target="_blank" href="https://github.com/homerosland/nervos-task7"> NERVOS/SATOHI PIZZA STORE CODES<a/>

### 🍕 Transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract

- Transaction hash: ```0x3d2a9dd18f3e36fad856a5e98575472796841fbaa3f98c8646f9509c2c1fdce9 ```
- Deployed contract address: ```0xE0dC75b6bef9EC62F81BE5C21C9DD35402C7a113```
  
  ABI:
  
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
