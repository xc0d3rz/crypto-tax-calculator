# Crypto Tax Calculator

A tool to calculate the capital gains of cryptocurrency assets for Canadian taxes.
The source data comes from a set of trade logs, which are provided by the exchanges.
The *adjusted cost base* (ACB) is used to calculate the capital gains.

The following exchanges are supported:

- Binance
- Bittrex
- Kraken

## TODO

- Add support for more exchanges.
- Refactor the code from trade parser for individual exchanges into separate modules.
- Add more end-points for finding the value of an asset at a specific time.
- Remove the hard-coded end-point for the BNB asset.
