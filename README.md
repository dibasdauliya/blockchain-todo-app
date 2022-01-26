# Commands

```bash
yarn/npm add global truffle # to install truffle globally
yarn/npx truffle version # to show version of truffle, solidity, node
yarn/npx truffle init # to initialize the truffle project

yarn/npx truffle migrate # migrate it in the network and charges gas fee
yarn/npx truffle console # to enter the truffle console
```

## Get Data

```js
// inside truffle console
todoList = await TodoList.deployed() // store status of todoList in it

todoList.address // account

taskCount = todoList.taskCount() // get data from functions of solidity
taskCount.toNumber() // 0
```
