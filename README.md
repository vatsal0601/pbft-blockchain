# Implementing PBFT in Blockchain

_**The order of command line arguments to give is `node index SECRET P2P_PORT HTTP_PORT PEERS`**_

For installing the dependencies run the `npm install` or `yarn install` command in terminal after cloning the repository.

Now open three terminals and enter the following command in each of them

```
node index NODE0 5000 3000
```

```
node index NODE1 5001 3001 ws://localhost:5000
```

```
node index NODE2 5002 3002 ws://localhost:5001,ws://localhost:5000
```
