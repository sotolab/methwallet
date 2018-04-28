# methwallet
methwallet
geth --networkid 1001 --nodiscover --maxpeers 0 --datadir p1 --rpc --rpcaddr "0.0.0.0" --rpcport 8545 --rpccorsdomain "*" ---rpcapi "admin,db,eth,debug,miner,net,shh,txpool,personal,web3" console 2>> geth.log
