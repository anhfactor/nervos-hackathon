# nervos-gitcoin-hackathon-task-7
Port An Existing Ethereum DApp To Polyjuice  
Gitcoin bounty: https://gitcoin.co/issue/nervosnetwork/grants/8

1. Screenshots or video of your application running on Godwoken.  
* Screenshots.  
![alt text](https://github.com/anhnt4288/nervous-hackathon/blob/master/task-7/treasure-dapp.png)
* Video.   
[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://youtu.be/2JkYddO3qQs)

2. Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.  
https://github.com/anhnt4288/treasure-dapp-polyjuice

3. If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)  
* Transaction hash
```
0xdac11ed9a170a07625a29738b73b51732d64575dc4604e84a0d1b195902caf98
```

* Deployed contract address   
```
0x97E22b040D51Df95B6dA629929CE0d72d7146c9F
```

* ABI
```
[
    {
      "constant": true,
      "inputs": [
        {
          "name": "",
          "type": "bytes32"
        }
      ],
      "name": "treasuresReceived",
      "outputs": [
        {
          "name": "",
          "type": "uint8"
        }
      ],
      "payable": false,
      "stateMutability": "view",
      "type": "function"
    },
    {
      "constant": true,
      "inputs": [
        {
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "treasureList",
      "outputs": [
        {
          "name": "",
          "type": "bytes32"
        }
      ],
      "payable": false,
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "name": "treasureNames",
          "type": "bytes32[]"
        }
      ],
      "payable": false,
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "constant": true,
      "inputs": [
        {
          "name": "treasure",
          "type": "bytes32"
        }
      ],
      "name": "totalTreasuresFor",
      "outputs": [
        {
          "name": "",
          "type": "uint8"
        }
      ],
      "payable": false,
      "stateMutability": "view",
      "type": "function"
    },
    {
      "constant": false,
      "inputs": [
        {
          "name": "treasure",
          "type": "bytes32"
        }
      ],
      "name": "claimForTreasure",
      "outputs": [],
      "payable": false,
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "constant": true,
      "inputs": [
        {
          "name": "treasure",
          "type": "bytes32"
        }
      ],
      "name": "validTreasure",
      "outputs": [
        {
          "name": "",
          "type": "bool"
        }
      ],
      "payable": false,
      "stateMutability": "view",
      "type": "function"
    }
  ]
```
