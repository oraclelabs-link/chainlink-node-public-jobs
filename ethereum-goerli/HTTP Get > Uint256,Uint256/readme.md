# HTTP Get > Uint256,Uint256

Perform HTTP Get request, parse JSON response and fill double uint256.

## Available Contract
  
Contract: [0x1a9b3A42Bf4a0523658c9d229F4aF556da68aA07](https://goerli.etherscan.io/address/0x1a9b3A42Bf4a0523658c9d229F4aF556da68aA07)

JobID: 50ce6528f1db4b7d888caa3fac23b783

## Price

0.05 LINK

## Parameters

The job requires the following parameters to be specified:

* `get` - internet-facing URL from where the data is retrieved
* `path1` - path to first value
* `path2` - path to second value
* `multiply` - int256

## Test request

* `get` - https://min-api.cryptocompare.com/data/pricemultifull?fsyms=ETH&tsyms=USD
* `path1` - RAW,ETH,USD,HIGHDAY
* `path2` - RAW,ETH,USD,LOWDAY
* `multiply` - 100