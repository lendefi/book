# General

## What is Lendefi Finance?

Lendefi Finance is an undercollateralized Lending Protocol built on the Binance Smart Chain. 

## When was Lendefi Finance launched?

The Lendefi project started in December 2020 and the governance token LDFI was minted on the 20th of January 2021.

The Lendefi Protocol was originally developed on the Ethereum network. However, it has since become uneconomic to perform a certain size of transaction on the Ethereum network. 

## Why Binance Smart Chain "BSC"?

BSC has the most developed and swiftly growing DeFi infrastructure outside the Ethereum network.   
  
In order to deliver a Protocol that can perform transactions of all sizes at an economical cost to users, a move to BSC was necessary.  
  
The move to BSC was initiated with Lendefi's Governance token LDFI. See [ETH to BSC Bridge](https://app.gitbook.com/@lendefi/s/lendefi-finance/~/drafts/-MYdkbmtt5w8M5uQiHl5/how-to-guides/eth-to-bsc-bridge).

## How do undercollateralized loans for leveraged trading work?

**Example:**

The trader deposits $50,000 BUSD as collateral into the Protocol.

The trader loans $50,000 BUSD from the lending pool.

Borrower invests into $100,000 worth of BTCB. In this step, the Protocol initiates a trade on PancakeSwap to change $100,000 \(minus loan fee of X%\) BUSD into BTCB. The BTCB is then escrowed by the Protocol.

**Example Case A**

The price of BTC has now decreased by 40% \($60,000 total collateral\) and a liquidation event is triggered.

The BTCB is swapped on PancakeSwap into $60,000 BUSD. $50,000 is sent to the lending pool and $10,000 \(minus a liquidation fee of X%\) is sent to the trader.

**Example Case B**

The price of BTC has now increased by 50% \($150,000 total collateral\) and the trader closes out the loan.

The BTCB is swapped on PancakeSwap into $150,000 BUSD. $50,000 is sent to the lending pool and $100,000 \(minus loan fee of X%\) is sent to the trader.





