---
layout: default
permalink: /worker/
language: en
---

## Overview

The BitShares Blockchain Foundation takes a lead in managing so called
*worker proposals* on the BitShares DAC. These proposals, once approved
by BTS holders, obtain funding in BTS tokens from the working budget
(a.k.a. reserves) of the BitShares DAC. These BTS tokens are then traded
into a *price-stable* cryptocurrency, such as bitUSD.

## Transparency

We want to serve an open and trust-less ecosystem. As such, we provide
full transparency to the BitShares network.
For the sake of **transparency and accountability**, we have the
accounting for the escrow workers under public domain. You can read more
about this on our dedicated [Accountability Page](/accounting).

## Spending Budgets

The BitShares Blockchain Foundation currently maintains the following
list of proposals through escrow:

{% include workers.html %}

The BitShares Blockchain Foundation currently knows **three** types of
worker proposals:

* **escrow workers**: With this, we organize
  freelancers around the world that want to work for the BitShares DAC
  through our trusted escrow setup which carefully vets the individual
  offers, sets them up on the blockchain and ensures the maximum of code
  quality for the BTS token holders.

* **budget workers**: These workers serve as a budget
  that can be tapped whenever it is needed for purposes defined in the
  individual budget workers. This serves as working budget that is more
  flexible then static escrow workers in the way that it allows to pay
  many different people for their support out of a single purpose-specific
  fund.

* **BSIP workers**: These workers merely serve to seek
  approval for so called BitShares Improvement Proposals (BSIPS) which
  is required in order to introduce new features to the BitShares main
  network through protocol upgrades.

### Escrow Worker Model

The purpose of escrow workers is to ensure proper payment for the work
provided over a period of time and absorb volatility of the BTS token
during that time. The freelancer has a reduced currency-risk during
while the BitShares DAC does not overpay for the provided work,
especially for long-term agreements.

Given that a worker on the blockchain may be voted in for quite some
time, the BitShares Foundation would like to exercise the new model of
running an escrow worker to reduce risks and costs for the BTS token
holders:

* BitShares Blockchain Foundation has an account (`workers.bitshares.foundation`) that is co-owned by `committee-account` and escrow partners.
* The worker will redeem it's funds on a regular basis and buy up bitUSD from the market (with reasonable premiums).
* For this reason and due to volatility of BTS, the actual pay of the worker is higher than the USD value.
* The worker will only pay the agreed amount of money and pay only in bitUSD to the `bitshares.foundation` account.
* Every BTS that is not paid out after the end of the worker **will be returned** to the BTS token holders through the reserve fund.
* In the event a worker is voted out prior to its completion, the pro-rata share of payment will be made to the freelancer and the contract will be closed.

### Budget Worker Model

Budget workers serve as workers that provide capital for specific
purposes where escrow workers do not fit, such as translation work,
bug fixing or bounties. The rules are as follows:

* BitShares Blockchain Foundation has an account (`workers.bitshares.foundation`) that is co-owned by `committee-account` and escrow partners.
* The BBF will redeem these funds on a regular basis and buy up bitUSD from the market (with reasonable premiums).
* For this reason and due to volatility of BTS, the available budget in USD terms might vary over time.
* The budget is controlled by `bitshares.foundation` who serves as an independent entity to supervise payouts.
* The amounts available for individual budgets can be obtained through [transparent account](/accounting)

### BSIP Worker Model

BSIP is the abbreviation for *BitShares Improvement Proposal* and is
describes the procedure of improving the BitShares protocol. Every major
change to the behavior of the BitShares Blockchain requires approval by
BTS holders by means of approval voting. This is implemented by means of
a BSIP worker.

## Beneficiaries

Beneficiaries of either of these models need to authenticate themselves
against the BitShares Blockchain Foundation with their real-world identity.
Invoices need to be sent that are published in this site.

**Payments will be made only after receiving and approving individual
invoices!**
Invoices are to be adressed to

    BitShares Blockchain Foundation
    Suite 10, Huggins House
    P. O. Box 187
    Old Manor Estate
    Gingerland, Nevis

## Legal Setup

Workers listed on this site will be owned by the BitShares Blockchain
Foundation, who will also act as the freelancer's contracting partner,
supervise the progress. Payouts are facilitated in bitUSD through a
multi-signature escrow setup with the independent BitShares Foundation.

[Blockchain Projects BV](http://blockchainprojectsbv.com) is contracted to 
handle the technical details and support quality assurance procedures.
