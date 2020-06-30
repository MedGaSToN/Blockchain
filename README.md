# Requirements
## Bitcoin
### Install wget 
```shell
sudo apt-get install wget
```
### Install Bitcoin Core
* You can download Bitcoin Core file with the command:
```shell
wget https://bitcoin.org/bin/bitcoin-core-0.20.0/bitcoin-0.20.0-x86_64-linux-gnu.tar.gz
```
* Once the file has downloaded, extract it with the command:
```shell
tar xzf bitcoin-0.20.0-x86_64-linux-gnu.tar.gz
```
* When the command completes, you’ll find a newly-created bitcoin-0.20.0 directory. Change into that directory with the command:
```shell
cd bitcoin-0.20.0
```
* Next, change into the bin directory with the command
```shell
cd bin
```
* We’ll now use the install command to install the necessary components into the /usr/local/bin directory like so:
```shell
sudo install -m 0755 -o root -g root -t /usr/local/bin *
```

## Ethereum
* Node.js and npm -> Terminal CLI installation
```shell
sudo apt update
sudo apt install nodejs npm 
```
* Check the installed version with
```shell
sudo apt install nodejs npm
```
* Install Node.js package manager with
```shell
sudo apt install npm
```
* Check version with
```shell
npm --version
```
* Web3 library -> Terminal CLI installation
```shell
npm install web3
```
* GETH -> Terminal CLI installation
```shell
sudo add-apt-repository -y ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install ethereum
```
* TRUFFLE -> Terminal CLI installation
```shell
npm install truffle -g
```
* SOLIDITY COMPILER -> Terminal CLI installation
```shell
npm install -g solc or sudo snap install solc
```

