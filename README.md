# Ethereum-ToDo-List

to set up truffle project
truffle init

To compile
truffle compile

To migrate
truffle migrate

To open truffle console
truffle console

Truffle Console Command
========================

await used to handle async action/function
todoList = await TodoList.deployed()

to view the entire list
todoList

to get the contract address
truffle.address

to get the number of task count
taskCount = await todoList.taskCount()