### solominer For YespowerSUGAR
Help keep SugarChain network stable through solo mining. In case anybody needs this.

### Set up your wallet config.json through options tab when finished adding below info close and re-open wallet
server=1
rpcallowip=127.0.0.1
rpcuser=user
rpcpassword=pass


### Run on Linux
./cpuminer -a yespower -o http://127.0.0.1:34229 --no-longpoll -u <rpc-user> -p <rpc-pass> --coinbase-addr=sugar1quzfgdrv0hkvjjlyd04x75uup5gsat3wexe8pef -t 2 --api-bind=127.0.0.1:4049
  
### Windows
cpuminer.exe -a yespower -o http://127.0.0.1:34229 -u <rpc-user> -p <rpc-pass> --coinbase-addr=sugar1quzfgdrv0hkvjjlyd04x75uup5gsat3wexe8pef -t 2 --api-bind=127.0.0.1:4049
