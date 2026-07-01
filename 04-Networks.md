# Blockchain Networks

## Why Blockchain Networks Matter

Many cryptocurrencies exist on multiple blockchain networks. Selecting the correct network is one of the most important parts of sending or receiving digital assets.

Choosing the wrong network can delay transactions or, in some cases, permanently result in lost funds.

For Crypto Operations teams, understanding blockchain networks is essential for investigating deposit and withdrawal issues.

---

## TRC20

TRC20 is the token standard used on the TRON blockchain.

Characteristics:

* Fast confirmation times
* Very low transaction fees
* Commonly used for USDT transfers

Block Explorer:

* Tronscan

---

## ERC20

ERC20 is the most widely used token standard on the Ethereum blockchain.

Characteristics:

* High security
* Large ecosystem
* Transaction fees can become expensive during network congestion

Block Explorer:

* Etherscan

---

## BEP20

BEP20 is the token standard used on BNB Smart Chain.

Characteristics:

* Low transaction fees
* Faster confirmations than Ethereum
* Compatible with many decentralized applications

Block Explorer:

* BscScan

---

## Polygon

Polygon is a Layer-2 scaling network built for Ethereum.

Characteristics:

* Lower fees
* Faster transaction processing
* Ethereum-compatible

Block Explorer:

* PolygonScan

---

## Solana

Solana is a high-performance blockchain designed for very fast and inexpensive transactions.

Characteristics:

* Extremely fast
* Very low fees
* Different address format from EVM-compatible blockchains

Block Explorer:

* Solscan

---

## Choosing the Correct Network

Before sending cryptocurrency, always verify:

* The receiving platform supports the selected network.
* The wallet address matches the selected blockchain.
* The asset is supported on both sides.

Using the wrong network may require manual recovery or could result in permanent loss of funds.

---

## Memo and Destination Tag

Some blockchains require an additional identifier besides the wallet address.

Examples include:

* XRP Destination Tag
* XLM Memo
* TON Memo (for some services)

If the Memo or Destination Tag is missing, the funds may reach the platform but cannot automatically be assigned to the correct user.

Operations teams often investigate these cases manually.

---

## Transaction Confirmations

A blockchain transaction is not considered final immediately after being broadcast.

Each blockchain requires confirmations before a deposit is credited.

For example:

* Some networks require only one confirmation.
* Others may require several confirmations before funds become available.

The required number depends on the platform's security policy.

---

## Network Congestion

When blockchain activity becomes very high:

* Confirmation times increase.
* Transaction fees may rise.
* Withdrawals can take longer than expected.

Many customer reports during busy periods are caused by normal network congestion rather than platform issues.

---

## Gas Fees

Gas fees are the network costs paid for processing blockchain transactions.

Different blockchains calculate fees differently.

Examples:

* Ethereum uses Gas.
* TRON uses Bandwidth and Energy.
* Solana uses a very small transaction fee model.

Operations teams frequently explain network fees to users who experience delayed or failed transactions.

---

## Common User Mistakes

Some of the most common mistakes include:

* Selecting the wrong blockchain network
* Sending tokens to an unsupported network
* Forgetting the Memo or Destination Tag
* Sending unsupported assets
* Assuming a transaction has failed before enough confirmations are received

---

## Real-world Operations Notes

Many support tickets are created because users send assets to the correct wallet address using the wrong blockchain network.

Another common situation is when users forget to include the required Memo or Destination Tag. In these cases, the transaction is often successful on-chain, but the platform cannot automatically credit the deposit until the Operations team manually reviews it.

Understanding these scenarios allows Operations teams to resolve issues more efficiently while reducing unnecessary escalations.
