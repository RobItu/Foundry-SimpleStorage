#

Learning and getting familiar with using Foundry. Beginning with SimpleStorage, a simple smart contract that stores and displays variables to users.

Deployed contract to Sepolia Testnet using forge scripts and broadcasting.
Saved private key using `cast wallet` for better security.

Contract address: [0x57B6aDCe8344c35a87e1De39ae4Dba437Ef4CE06](https://sepolia.etherscan.io/address/0x57B6aDCe8344c35a87e1De39ae4Dba437Ef4CE06)

## Foundry - SimpleStorage

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
