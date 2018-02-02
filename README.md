This is a simple blockchain application to demonstrate how blockchain works. The code has been borrowed from <a href="http://ecomunsing.com/build-your-own-blockchain"> Ecomunsing </a> but there has been some changes to make it simpler to understand. Also some code has been added to it to make it possible to run it in interactive mode from terminal.


By running the script you will get an understandig of what a blockchain is, and by diving into to code you can see the parts that come together to make a blockchain.

To understand How blockchain works:

Copy the blockchain.py file to your local machine, open terminal and run the following command:

*	python blockchain.py

Keep in mind that:

- you should include the path to your file if terminal is not open in the same location.
- make sure to use the python 3 interpreter. if python 3 is not your default interpreter, use the following command:
	python3 blockchain.py


when the program is already running, you are given some choices:
	a: show chain
	b: make new transactions
	c: show the new transactions
	d: add the new transactions to the blockchain

what do these do:
* a: shows the current chain:
	the resualt will be some blocks linked to each other by hashes. if you run this command the moment you run the blockchain.py file, you will see a chain with only one block: the genesis block. it will be explained later.
  
* b: make new transactions:
	it will generate some random transactions. all the transactions are between two users: alice and bob, that each time one of them (randomly) would be the sender and the other one the receiver. 
  
* c: show the new transations:
	it will show the random transactions created in previous step. these are not yet added to the block chain.
  
* d: add the new transactions to the blockchain:
	this will add the previous transactions to the blockchain. make sure to run part b before you want to add to the blockchain. 
  


The doc will be completed soon.
