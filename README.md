# Nimble Commands
Collection of commands for testing on nimble devices.

## Ethereum Commands
Running GETH in light client mode with 256MB of allocated cache
```shell
./geth --syncmode light --rpc --rpccorsdomain * --cache 256
```
## Bithereum Commands
Running pruned Bithereum on low memory devices.
```shell
./bethd -rpcuser=bithereum -rpcpassword=bithereum -rpcallowip=0.0.0.0/0 -rpcport=18554 -port=18553 -dbcache=100 -maxmempool=10 -maxconnections=10 -prune=550 -printtoconsole
```
