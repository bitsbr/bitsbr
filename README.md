<h1 align="center"> BITSBR Node</h1>

<p align="center">


BITSNODE node is a host connected to the blockchain network with the following functions:


- [REST API](https://api.bitsbr.org)


## 🚀️ Getting started

A quick introduction of the minimal setup you need to get a running node. 

*Prerequisites:*
- configuration file for a needed network from [here](https://github.com/bitsbr/bitsbr/tree/HEAD/node)
- `bitsbr-all*.jar` file from [releases](https://github.com/bitsbr/bitsbr/releases) 

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
