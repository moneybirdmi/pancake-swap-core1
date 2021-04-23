# Pancake Factory

[![Actions Status](https://github.com/pancakeswap/pancake-swap-core/workflows/CI/badge.svg)](https://github.com/pancakeswap/pancake-swap-core/actions)

In-depth documentation on PancakeSwap is available at [docs.pancakeswap.finance](https://docs.pancakeswap.finance/).

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`


## How it is work
first deploy the Factory and get init hash and go to pancake-swap-preiphery add the init has into pancakeLibaray.sol and then run the pancake-swap-preiphery migration.