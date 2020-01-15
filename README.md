# first-network-with-raft

```sh
first-network$ ./byfn.sh generate -o etcdraft
first-network$ ./byfn.sh up -o etcdraft -l golang
```

```sh
server$ ./updateKeystore.sh
server$ node enrollAdmin.js 
``` 
