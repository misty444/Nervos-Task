## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](./CallContract.png)
## 2. The transaction hash from the console output (in text format).
0x86f9f459e7776ca5f49e4fad82267476c8716b450ddcb89c2ff744badea740cc
## 3. The contract address that you called (in text format).
0x36f75bb0472B29104F63A39FdE30f4AC1D96984A
## 4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]
```
