# excel-liquidity-pool-simulator

## TL;DR:
Excel spreadsheet model simulating a Uniswap AMM liquidity pool. Uses the exact calculations found in the Uniswap Core contracts. Observe changes in pricing, slippage, LP token issuance and redemption, and impermanent loss transaction-by-transaction.

Initial demo version. Yellow cells are for user data entry. This file is no longer locked, all formulas are unprotected and open for all legitimate licensed users to see, subject to the restrictions in the accompanying LICENSE file.

## Background:
This is definitely of narrow appeal, but I’m happy to share this Web3 AMM Liquidity Pool Simulator project I built in Excel back when I was interested in web3 & decentralized finance. In defi, trading is often done through what's called an Automated Market Maker, a smart contract that serves the same basic purpose as market makers in the traditional stock market, with the slight difference that AMMs require funding by the general public to provide liquidity for other people to trade with, so there is the additional complexity of providing an incentive scheme for people to deposit crypto with them. 

So, then, what's smarter? Trading Ethereum tokens, or depositing them in an AMM's liquidity pool? (I do have a sarcastic answer to this, which I'll forego here.) 

The algorithms by which an AMM calculates prices, pool token issuance, and exchange rates can be difficult to easily understand. This Excel worksheet lifts the lid by modeling a Uniswap AMM liquidity pool, using the exact calculations from the original Uniswap Core smart contracts. You can now observe how exchange rates, slippage, LP token issuance, and impermanent losses change, transaction-by-transaction. If you're an Ethereum or ERC token trader, this is very useful to understand.
