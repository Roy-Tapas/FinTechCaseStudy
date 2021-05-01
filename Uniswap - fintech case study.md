# FINTECH CASE STUDY - Homework for Module-1 of Fintech Bootcamp

## Overview and Origin

* Name of project: **UNISWAP**

* When was the project launched? 2018

* Who are the founders of the company? Hayden Adams

* How did the idea for the company (or project) come about and how was it funded? 

Uniswap is a protocol for decentralized exchange of crypto tokens. Uniswap was founded by Hayden Adams. Inspired by one of Vitalik Buterin, reddit posts a few years ago, Hayden initially sought to gain some solidity practice. His solidity training experience turned into a proof of concept for an on-chain automated market maker (AMM) protocol. AMM determine price of a crypto based on the ratio of two cryptos within a pool. This contrasts with the order books we typically see on centralized exchanges.
Subsequently Hayden received a grant from Ethereum foundation to continue his work to full-fledged solution which is now Uniswap. 

Uniswap consists of a set of smart contracts deployed on Ethereum network. That means entire process takes place on-chain and there is no centralization, and no fees going to any of the founders.

Uniswap was funded by Ethereum foundation, investments from  venture capital firms including Andreessen Horowitz, Paradigm Venture Capital, Union Square Ventures LLC and ParaFi.

Hayden received ~$11M series-A funding.


## Business Activities:

* What specific financial problem is the company or project trying to solve?

 


Traditional finance is being disrupted by blockchain to Decentralized finance (DeFi) that doesn’t rely on central financial intermediaries (brokerages, exchanges, banks). 
Uniswap is one of the core products in the DeFi ecosystem. Uniswap is a decentralized crypto exchange (DEX). Uniswap’s DEX challenges traditional order-book based method used by most centralized exchanges. Prices for token swaps are decided by a deterministic algorithm, called an automated market maker (AMM) which automatically sets and balances the pricing for a pair depending on the demand for a token and the available liquidity of each of the tokens in a pool.

DEX aims to solve problems of centralized exchange such as mismanagement, risk of hacking and arbitrary fees. However, DEX may mot have enough liquidity to make trading faster and efficient. 
Uniswap solves the liquidity issue by swapping tokens without the use of order books that means without relying on buyers and sellers creating that liquidity. 

Unlike most centralized exchanges, which match buyers and sellers to determine prices and execute trades, Uniswap uses a simple math equation and pools of tokens and ETH to determine the price and execute trades.
Uniswap pricing mechanism is called “Constant Product Market Maker Model”, where product of liquidity of two tokens under trade, always remain same, hence the name “Constant Product..”. 
Beauty of this model is, it can always provide liquidity no matter how large the order size or how small the liquidity pool. The model asymptotically increases the price (premium) of the coin as the desired quantity increases.
The premiums makes large orders (whale orders) prohibitively expensive. Pricing mechanism bid/ask spreads typically found in centralized and regulated exchanges. 

Uniswap is developed for the community to trade tokens without platform fee or any other middlemen. 



Features of Uniswap
Uniswal has 2 major features known as Swap and Pool:
Swap: allows users to swap between Ethereum (ETH) and different ERC-20 tokens.
Pool: allows users to earn by providing liquidity. This is done by depositing tokens into a smart contract and the depositor will receive pool tokens in return.
Advantages of Uniswap
Self-custodial: Traders retain full custody of their funds through crypto wallet such as meta mask. This mitigates the risk of losing funds if the exchange is hacked. 
No Know Your Customer (KYC): Uniswap allows self-custody of funds. That allows them to skip KYC. Users do not need to disclose sensitive personal information. This allows faster use of the platform, reduces the chances of hacking personal information. 
Access to new coins: New coins are listed in Uniswap faster than centralized exchanges because of absence of vetting process with the exchange before the token is listed for trading. 


* Who is the company's intended customer?  Is there any information about the market size of this set of customers?

Small traders are Uniswap’s intended customers. 
Uniswap’s current Market cap $22B (16% of DEX market share)
Daily trading vol $2.3B



What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

Liquidity provision:
Uniswap is the go-to platform to earn fees by providing liquidity. Other DEX may provide higher liquidity fees, but they are often for pools with volatile tokens.

First mover advantage and network effect
Uniswap is the standard for automated market makers and now a household name in DeFi.
Liquidity
Uniswap is known for it’s high liquidity among it’s peers. Uniswap platform is the go-to choice for many crypto launchpads and new tokens. 
Trading volume
Uniswap’s 24-hour trading volume has been in the range of $2B to $3B. This was highest among all DEXs. Recently Pancakeswap recently surpassed Uniswap’s trading volume. But with the improvement in Ethereum block chain, Uniswap is expected to regain it’s glory.
Diversity of tokens:
Uniswap offers many more tokens among all DEXs. This is primarily because of adoption of Ethereum and ERC-20 tokens. There are few tokens that are not available in Uniswap but available in other DEXs.
Ease of use:
Uniswap has a simple, intuitive and easy to use user interface.
Community:
Uniswap has far bigger community than any of the other exchanges. Thanks to it’s network effect and Ethereum’s adoption. Uniswap has been copied by many. But, still very few DEX can compete with Uniswap. 
Uniswap is tried and tested. This platform offers many advatnages over others. However, gas fee on Uniswap is one of the major bottleneck of the platform that is driving it’s users to other platforms such as PancakeSwap. With ETH2.0 transactions will be faster and gas fee will be more competitive. 








* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

Uniswap uses distributed computing that runs on Ethereum blockchain.
Responsive and intuitive frontend interface is built in React Native (type of JavaScript) 

Uniswap interface allows users to trade (swap) tokens, add liquidity, and create new pools. Under the hood, Uniswap pulls an array of information from smart contracts on the Ethereum blockchain to feed into the interface and populate data such as pricing between pairs, user balances, and swap rates.

Uniswap uses Infura to query information and fetch data like token swap rates, token balances, and other information from the Uniswap smart contracts. 

Infura is a method of connecting off-chain apps, such as Uniswap interface to Ethereum block chain.

## Landscape:

* What domain of the financial industry is the company in?

Uniswap is in the field of Crypto trading by providing guaranteed liquidity.

* What have been the major trends and innovations of this domain over the last 5-10 years?

Uniswap v1 was first launched on the Ethereum mainnet on November2, 2018. Uniswap became the first DEX based on Automated Market Maker (AMM) model. This model is based on a mathematical formula (instead of order books) to determine the price of tokens. 

Uniswal v1 was proof of concept that came with huge promise. A better version Uniswal v2 was launched in May 2020. Major improvements are the following:
-	Much better and user-friendly interface
-	ERC20-ERC20 liquidity token pools to solve “ETH bridging” problem. Meaning users can swap one ERC20 token to another ERC20 token without one ERC20 token to ETH first and then to another ERC20 token.
-	Integration with Oracle solution to get on-chain price feeds thus preventing price manipulation.
-	Introduction of flash swaps allowing users to withdraw as much as they wanted of any ERC20 token on Uniswap at no upfront cost as long as any of the following conditions is met:
o	Pay for tokens withdrawn
o	Pay for a percentage of token and return the rest
o	Return all tokens withdrawn  

Uniswap v3 is slated to launch in May is going to introduce an array of new features.
-	concentrated liquidity
-	capital efficiency
-	active liquidity
-	range orders
-	non-fungible liquidity
-	flexible fees and 
-	a license to use v3 code
https://miro.medium.com/max/965/1*gYBZE9EdBew2iBHNYQbQ0w.png


* What are the other major companies in this domain?
iInch: a DEX aggregator offering best crypto price across DEXs
SushiSwap: A decentralized, community-owned, and community-run cryptocurrency exchange built on the Ethereum network
Pancackeswap - Binance Smart Chain-based DEX, similar to SushiSwap but incorporates many other features such as farming, staking.


## Results

* What has been the business impact of this company so far?

Recent DeFi boom has made Uniswap the most sought-after trading platform in the niche sector of digital assets. 
Uniswap has been the main driver for the rising prominence of decentralized exchanges and the catalyst for Decentralized Finance.

Uniswap is a great example of a non-custodial AMM. Users trade against the pooler assets - liquidity available in a smart contract, as opposed to with a counterparty as they would in traditional order book-based exchanges. They are the pioneer in blockchain based DEXs. 

Number of users grew exponentially over the years following the famous “hockey-stick” growth.
https://miro.medium.com/max/1050/1*45S2M9peYH5t_tZ6vmGsnw.png

Daily trading volumes hit USD2.19 billion on October 26th, 2020 - which was a new all time high for the platform exceeding popular centralized exchanges such as Bittrex, FTX, and Bithumb and very close to the trading volume of Coinbase.


https://images.ctfassets.net/sdlntm3tthp6/2qVqWxCemBdLFJ7wBBoFWB/d1db1fcc435bc0fff18b5e71c17aa93f/Best_Decentralized_Crypto_Exchange_1__2_.jpg?w=650

https://images.ctfassets.net/sdlntm3tthp6/mzzYgEZeVOU4bn73F6dIl/2fba2dc8afde180e6503b51322d85808/Best_Decentralized_Crypto_Exchange_4-min.jpg?w=650





## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

Uniswap has lost some ground to it’s competitors such as PancakeSwap because of high gas fee and network congestion resulting slower transaction. Many DEXs are coming up on different layer-1 and layer-2 blockchains with lightning speed and a fraction of Uniswap’s gas fee.
Uniswap is built on Ethereum blockchain. Reason of higher gas fee and latency is rooted on Ethereum, which is going to solve in Ethereum V2 but that will take some time. Meanwhile Uniswap should focus on some intermediate solution to improve latency and reduce gas fee.

This will also solve transaction failure rates. Today users need to pay gas fee even if transaction fails. 

Uniswap competition offers add-on features such as staking and farming. This is taking away Uniswap users to those innovative DEX platforms. Uniswap should focus on how they can add more value to their users to retain user base and stay competitive. 