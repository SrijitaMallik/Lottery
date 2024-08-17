# Lottery
Introduction
This project is a basic implementation of a lottery smart contract using Solidity. The contract allows users to participate in a lottery by paying 1 ether. The manager of the contract can then pick a winner.

Contract:-
The contract is located in the contracts folder and is named Lottery.sol. It has the following functions:
participate: allows users to participate in the lottery by paying 1 ether
getBalance: returns the balance of the contract, only accessible by the manager
random: generates a random number used to pick a winner
pickWinner: picks a winner from the list of participants, only accessible by the manager.

How it Works:-
Users participate in the lottery by calling the participate function and paying 1 ether.
The manager can check the balance of the contract by calling the getBalance function.
When the manager is ready to pick a winner, they call the pickWinner function.
The pickWinner function generates a random number using the random function and uses it to select a winner from the list of participants.
The winner is then transferred the entire balance of the contract.
The list of participants is reset to empty.

Testing:-
To test the contract, you can use a tool like Truffle or Remix. You can also test the contract manually by deploying it to a testnet and interacting with it using a tool like MetaMask.

Deployment:-
To deploy the contract, you can use a tool like Truffle or Remix. You will need to compile the contract and deploy it to a blockchain network.

Security:-
This contract has not been audited and should not be used in production without further testing and review. The contract uses a simple random number generator, which may not be suitable for production use.

Code:-
The contract code is located in the contracts folder and is named Lottery.sol.
