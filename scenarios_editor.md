# Scenarios Editor

Scenarios can be used to test and debug contracts. 

A scenario is effectively a local blockchain where blocks can be mined without PoW – otherwise testing would be quite slow ;). 

A scenario consists of a sequence of transactions. Usually, a scenario would start with the contract creation scenarios of the dapp. In addition, further transactions can be added to test and debug the dapp. Scenarios can be modified, i.e. transactions can be removed. Note that a scenario needs to be rebuilt for modifications to become effective. Further testing can be done using local JS calls via the JS API.

In case it’s not open, access the scenario and debugger pane by pressing F7 or Windows > Show right or the debug button in the upper right corner of the main window. 

### Creating and setting up a new scenario

When you launch Mix for the first time, an empty scenario, i.e. not containing any transactions, will be created.
Add an account named “MyAccount” and set it’s initial balance to 1 ether. Click OK. 
Rename the scenario to “Deploy”.

###Modifying initial ether balance of an account

Actually, we want to do a lot of tests 
Edit the Genesis block parameters and set your initial account balance to 1000 ether.
Rebuild the scenario for the change to become effective.

###Rebuilding a scenario

###Creating a transaction
Let’s get some ether sent to Bob. 
Create another account named “Bob” with zero ether balance. 
Create a new transaction in the scenario pane. Click “Add Tx…” and send 300 ether to Bob. 
Add a block.

 
###Altering and reusing scenarios
Create a new scenario or start from a scenario with several transactions that you duplicate first

Rename the scenario

Modify scenario by specifying transactions that shall be removed

Rebuild the scenario
