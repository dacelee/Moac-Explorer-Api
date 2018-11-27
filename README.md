
# Api
## Transaction
### Get transaction by hash
```
http://api.exp.tmaxpool.com:3000/tx?hash=0xfd4281fec3a4eb136ac33539802cb0b90fb0e946b7cff2f1ae8787f75c3e84f4
```
```
{
    "data": {
        "blockHash": "0x1d8deac61334f54cb7cafb7e5fa8f7dec020989858566f0c5dc8a4a648286c12",
        "blockNumber": 32,
        "from": "0x2F0036792DF25362a2DE0Bab82B4798657B4BC36",
        "gas": 200000,
        "gasPrice": "100000000000",
        "hash": "0xcaebd83e99420ae820ca40a64aa5c5d9106e3fda6db2e75ad8049b93896b10f6",
        "input": "0xa9059cbb000000000000000000000000c4c7fc58b37be1b4f2a6230cace76afd47cff7480000000000000000000000000000000000000000000000000000000000000009",
        "nonce": 6,
        "to": "0x2d051595AA51A29C6EDa4eaCAFBe79234508Ca7C",
        "transactionIndex": 0,
        "value": "0",
        "v": "0xfe7",
        "r": "0xbbdf67a417419da64ff28a85f8b2f81fc84aa9887ce44d4c4f9981a82c93cf73",
        "s": "0x39ead23568017abfd4328ac923798726130d6278593791d5c5a71d81d5b2781a",
        "blockTime": 1533445312,
        "gasUsed": 36231,
        "logs": [
            {
                "address": "0x2d051595AA51A29C6EDa4eaCAFBe79234508Ca7C",
                "topics": [
                    "0xddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef",
                    "0x0000000000000000000000002f0036792df25362a2de0bab82b4798657b4bc36",
                    "0x000000000000000000000000c4c7fc58b37be1b4f2a6230cace76afd47cff748"
                ],
                "data": "0x0000000000000000000000000000000000000000000000000000000000000009",
                "blockNumber": 32,
                "transactionHash": "0xcaebd83e99420ae820ca40a64aa5c5d9106e3fda6db2e75ad8049b93896b10f6",
                "transactionIndex": 0,
                "blockHash": "0x1d8deac61334f54cb7cafb7e5fa8f7dec020989858566f0c5dc8a4a648286c12",
                "logIndex": 0,
                "removed": false,
                "id": "log_6065faca"
            }
        ],
        "status": true
    }
}
```
## Block
### Current block number 

```
http://api.exp.tmaxpool.com:3000/latestnumber
```

```
{"data":10203}
```
### Get block by block number
```
http://api.exp.tmaxpool.com:3000/block?number=10566
```

```
{
   "data":{
      "difficulty":"2",
      "extraData":"0xd7830108",
      "gasLimit":10122307,
      "gasUsed":21000,
      "hash":"0xa36c782512de1a7a0d09fb5e4ed898a2848f8eec97ba8a6916f5df5ec78c3034",
      "logsBloom":"0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
      "miner":"0x0000000000000000000000000000000000000000",
      "mixHash":"0x0000000000000000000000000000000000000000000000000000000000000000",
      "nonce":"0x0000000000000000",
      "number":10566,
      "parentHash":"0xe655b937da6b31fb0192ba3352b7c3810bd5c7e0296ebd5dd52968bc6b96b23f",
      "receiptsRoot":"0x056b23fbba480696b65fe5a59b8f2148a1299103c4f57df839233af2cf4ca2d2",
      "sha3Uncles":"0x1dcc4de8dec75d7aab85b567b6ccd41ad312451b948a7413f0a142fd40d49347",
      "size":711,
      "stateRoot":"0xfb8b9ae3b74dca2143751af66fb4f705d981ac1d0596ae9b601c43a10a7f6615",
      "timestamp":1534431406,
      "totalDifficulty":"21133",
      "transactions":[
         "0xd8d7740442770335a677c5f50a80ae43526bb93679edc6ea41ecc4ef5e9bdcbb"
      ],
      "transactionsRoot":"0x43070a28adec023f9141425f575533af656104762e5bc5ce4d0306d188fb035f",
      "uncles":[

      ]
   }
}

