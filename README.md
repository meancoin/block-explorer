# MEANcoin-Blockchain-Explorer
Block explorer for MEANcoin CryptoNote based cryptocurrency.

#### Installation
1) It takes data from daemon forknoted. It should be accessible from the Internet. Run forknoted with open port as follows:
```bash
./forknoted --enable-cors="*" --enable_blockexplorer=1 --rpc-bind-ip=0.0.0.0 --rpc-bind-port=41311
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Devs:
    MEANcoin Team

Donate: 
    [BTC] TRTLv2RCPuD7AaaVpQkRPF59MMLx5WW3qFxwJz4Doy7dHhNA6UuQjEpLL3rpUQS4RXdQn8fb4P1XC3K62GeJjGgG8DP9LNaTrNL

### Note
A lot of this code is from the great Turtlecoin/Block-Explorer
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
