A "Mockchain" developed with Express.JS.
A Mockchain is a mock blockchain that can be interacted with through a web browser. Blocks can be mined, transactions can be generated, and they'll be printed to the user. To this end, a singular node is pivoted towards the user's view.

Overview:
| File | Description  |
| ------- | --- |
| ./index.js | Imports. |
| ./routes/index.js | Dynamically loads route files included in the ./routes folder. |
| ./src/transaction.js | Contains the class definition for a single transaction. |
| ./src/block.js | Contains the class definition for a single block. |
| ./src/blockchain.js | Contains the class definition for a blockchain. |
| ./routes/newtransaction.js | Creates a new mock transaction and adds it to the system. |
| ./routes/listtransaction.js | Lists all transactions in the system, not currently on blocks. |
| ./routes/mine.js | The server mines a new block, and adds it to its personal chain. |
| ./routes/chain.js | The server prints out the entire blockchain. |
| ./routes/validate.js | The server validates the blockchain. |
| ./routes/brew.js | The server attempts to brew coffee, but fails, because it is a teapot. |

The way to interact with the blockchain is by reloading the page on the following links:

https://localhost:8080/mine 

https://localhost:8080/newtransaction 

https://localhost:8080/listtransactions 

https://localhost:8080/chain 

https://localhost:8080/validate

