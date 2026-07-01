# Crypto Deposits

## What is a Deposit?

A deposit is the process of transferring cryptocurrency from an external wallet or exchange to a user's account on a crypto platform.

Once the blockchain transaction meets the platform's confirmation requirements, the funds are credited to the user's account.

---

## Standard Deposit Flow

A typical deposit follows these steps:

1. The user copies a deposit address from the platform.
2. The user sends cryptocurrency from another wallet or exchange.
3. The blockchain confirms the transaction.
4. The platform detects the transaction.
5. Required confirmations are reached.
6. The user's balance is updated.

---

## Deposit Address

Each supported asset and blockchain network has its own deposit address.

Before sending funds, users should verify:

* Correct cryptocurrency
* Correct blockchain network
* Correct wallet address
* Memo or Destination Tag (if required)

---

## Deposit Confirmations

Most platforms do not credit deposits immediately.

Instead, they wait until the blockchain confirms the transaction a certain number of times.

Reasons include:

* Preventing double-spending
* Improving security
* Reducing blockchain risks

---

## Pending Deposits

A deposit may remain pending for several reasons:

* Insufficient confirmations
* Blockchain congestion
* Wallet maintenance
* Temporary platform delays

Pending deposits do not always indicate a problem.

---

## Missing Deposits

If a user reports that a deposit has not arrived, Operations teams typically investigate:

* Transaction Hash (TXID)
* Blockchain network
* Deposit address
* Confirmation count
* Memo or Destination Tag
* Asset support
* Internal wallet status

---

## Unsupported Assets

Sometimes users send assets that the platform does not support.

Examples include:

* Unsupported tokens
* Unsupported blockchain networks

Recovering these funds may require manual intervention and is not always possible.

---

## Wallet Maintenance

Platforms occasionally perform wallet maintenance.

During maintenance:

* Deposits may be delayed.
* Withdrawals may be temporarily disabled.
* Funds remain safe but processing can take longer.

---

## Best Practices

Users should always:

* Double-check wallet addresses.
* Verify the selected blockchain network.
* Send a small test transaction when transferring large amounts.
* Save the TXID after sending funds.

---

## Real-world Operations Notes

One of the most common support requests is "My deposit has not arrived."

In many cases, the transaction is still waiting for the required number of confirmations or the user selected an unsupported blockchain network.

Operations teams first verify the TXID, then check confirmations, wallet status, and whether all deposit requirements were met before escalating the issue.
