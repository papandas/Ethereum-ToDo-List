# Ethereum-ToDo-List

Contract Address https://ropsten.etherscan.io/address/0x86c6e43752c6c98d4cd709f011e81202626494f9

to set up truffle project
`truffle init`

To compile
`truffle compile`

To migrate 
`truffle migrate --reset`

To run test
truffle test

To enter truffle console
truffle console

To exit truffle console
.exit

Truffle Console Command
========================

await used to handle async action/function
todoList = await TodoList.deployed()

to view the entire content
todoList

to get the contract address
todoList.address

to get the number of task count
taskCount = await todoList.taskCount()

to view the number
taskCount.toNumber()


STEPS TO FOLLOW:

1. List task in the smart contract
2. List task in the console
3. List task in the client side application
4. List task in the test

To get the list of tasks
tasks = await todoList.tasks(1)
