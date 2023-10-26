<h1 align="center"> BITSBR Node</h1>

<p align="center">


> Waves is an open source [blockchain protocol](https://waves.tech/waves-protocol). <br/> 
You can use it to build your own decentralized applications. Waves provides full blockchain ecosystem including smart contracts language called RIDE.


## ✨ Demo

<p align="center">
    <img src="https://user-images.githubusercontent.com/1945126/78667964-88209480-78e2-11ea-9304-72178a6a5974.gif" alt="Waves Node Run Demo">
</p>

BITSNODE node is a host connected to the blockchain network with the following functions:

- Processing and validation of [transactions](https://docs.waves.tech/en/blockchain/transaction/transaction-validation)
- Generation and storage of [blocks](https://docs.waves.tech/en/blockchain/block/)
- Network communication with [other nodes](https://docs.waves.tech/en/blockchain/blockchain/#node)
- [REST API](https://docs.waves.tech/en/waves-node/node-api/)
- [Extensions](https://docs.waves.tech/en/waves-node/extensions/) management

Learn more about Waves Node in the [documentation](https://docs.waves.tech/en/waves-node/).

## 🚀️ Getting started

A quick introduction of the minimal setup you need to get a running node. 

*Prerequisites:*
- configuration file for a needed network from [here](https://github.com/wavesplatform/Waves/tree/HEAD/node)
- `bitsbr-all*.jar` file from [releases](https://github.com/wavesplatform/Waves/releases) 

Linux systems:
```bash
sudo apt-get update
sudo apt-get install openjdk-8-jre
java -jar node/target/bitsbr-all*.jar path/to/config/bitsbr.conf
```

Mac systems (assuming already installed homebrew):
```bash
brew cask install adoptopenjdk/openjdk/adoptopenjdk8
java -jar node/target/bitsbr-all*.jar path/to/config/bitsbr.conf
```

Windows systems (assuming already installed OpenJDK 8):
```bash
java -jar node/target/bitsbr-all*.jar path/to/config/bitsbr.conf
```
