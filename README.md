# **assignment_18**

Instruction for launching a new chain using windows.

I hope you all are excited about creating your first new blockchain! If you follow the below steps carefully you will successfully create a blockchain.

##**Instructions**

Required software:

1. Geth
2. Puppeth
3. myCrypto

## **Creating the nodes:**

To start the process you will need to create at least two nodes to be able to test a transaction. This process will require you to install Geth. Once installed you will navigate to the Geth folder. To create the two nodes you will need to input the following code in gitbash (when you launch gitbash its advisable to run it as administrator):

'./geth account new node 1'
'./geth account new node 2'

[1^]Note: 
[1^]You may call the nodes by any name you choose. For instance I used env1 and env2 as the names for my nodes.

## **Creating the Genesis**

After the creation of the nodes you will need to create your genesis block. The genesis block forms the basis of the entire blockchain, it is the first block in the chain. To create your genesis you will need to have puppeth installed. To create a genesis you will need to follow the following steps.

1. Launch puppeth and give your genesis a name with the follwoing command in gitbash:

'./puppeth'

2. After launching puppeth you will be asked to give your genesis a name. Choose a name for your genesis and press enter.

3. After you select the genesis name you will be asked a series of questions. 
![Launching your Genesis!]launching_puppeth.png
[1^]Note: The above assumes a new folder was created to create the nodes in (if you choose not to create a seperate folder you just need 
[1^]to replace ../ with ./

First in the puppeth prompt, you will be asked "What would you like to do?". Select option 2 to configure your genesis from scratch.
[1^]Note:
[1^]You may have to type your network name again first if you're launching puppeth fresh.

Second in the puppeth prompt, you will be asked "Which consensus engine to use? (default = clique). Select option 2 proof of authority. 

Thrid in the puppeth prompt, you will be asked "How many seconds should block take? (default=15)". It is recommended to enter the default 15 seconds.

Fourth in the puppeth prompt, you will be asked which accounts are allowed to seal 
4. After configuring your genesis you will manage your genesis and export your genesis configuration into a yournetworkname.json (give your genesis file a name) file by typing 2 again to choose the Export genesis configuaration option. Continue with the default (current) directory by hitting enter.

5. 

![Follow the recommended responses in the image]genesis_config.png
