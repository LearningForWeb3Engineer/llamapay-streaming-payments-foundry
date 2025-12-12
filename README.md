<<<<<<< HEAD
# llamapay-streaming-payments-foundry
A minimal streaming payment protocol implemented with Solidity and Foundry, demonstrating ERC20 approvals, time-based accounting, and on-chain salary streams deployed on opBNB testnet.

# LlamaPay Streaming Payments

A minimal **on-chain streaming payment prototype** built with **Solidity** and **Foundry**, demonstrating ERC20 approvals, time-based accounting, and per-second salary streams.

---

## What This Project Does

- Implements a simple **streaming payment** mechanism  
- Payments accrue **per second** instead of one-time transfers  
- Funds are transferred only when `withdraw` is called  
- Supports **negative payer balances** to represent unpaid liabilities  

---

## Tech Stack

- **Solidity**
- **Foundry** (forge / cast)
- **OpenZeppelin ERC20**

---

## Core Contracts

- **MyToken.sol** — ERC20 test token  
- **LlamaPay.sol** — Streaming payment logic  

---

## ***Basic Flow***

1. **Approve** ERC20 tokens to LlamaPay  
2. **Deposit** tokens into the contract  
3. **Create** a per-second payment stream  
4. **Withdraw** accrued salary  

---

## Network

- **opBNB testnet**

---

## Disclaimer

This project is for **learning and demonstration purposes only** and has not been audited.
=======
## Foundry

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
>>>>>>> 4189864 (init streaming payment prototype)
