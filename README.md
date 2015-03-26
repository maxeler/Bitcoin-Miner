# Bitcoin Miner
<img src="http://appgallery.maxeler.com/v0.1/app/Bitcoin Miner/icon" alt="Bitcoin Miner" height="300" width="300">
### Description
Bitcoin's proof-of-work is implemented by incrementing a nonce in a transaction block until the block header's hash satisfies the current target. The hashing function is SHA256(SHA256(block header)). BitcoinMiner is an MPI program that can run on multiple nodes and multiple cards. Each process, except the root process, fetches work from a Bitcoin server using JSON-RPC, run the hash search, and return the result to the server when a match is found. The root process handles the commands issued to the console, and gather state information from other processes. BitcoinMiner can also be run in test mode, where no Bitcoin server is required. In this mode, BitcoinMiner repeatedly validates the genesis block.


Bitcoin Miner on [AppGallery](http://appgallery.maxeler.com/) 
