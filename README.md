# MEANcoin-Blockchain-Explorer
Block explorer for MEANcoin CryptoNote based cryptocurrency.

### Installation
1) It takes data from daemon forknoted. It should be accessible from the Internet. Run forknoted with open port as follows:
```bash
./forknoted --enable-cors="*" --enable_blockexplorer=1 --rpc-bind-ip=0.0.0.0 --rpc-bind-port=41311
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Devs:
    MEANcoin Team

Donate: 
    [BTC] 3PUcDwVGmUnpstRFkR6QS2FrtDGhraUdWM
    [BCH] qpvlqt3fr98hera5cqfcja730t5tzn4r4gde3xzjun
    [ETH] 0x8B77EfF25889590dB566628B1CB7a7B89F9168a8
    [LTC] MJqgfKU3rhbdafTYoTKL3eps9waXUigv47

### Note
A lot of this code is from the great Turtlecoin/Block-Explorer
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
