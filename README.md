<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
    <img src="assets/logo.svg" width="282" height="120" alt="UDA wordmark: a U with three gold lashes like a closed eye, followed by D and A">
  </picture>
</p>

# UDA

**U DA’ Only Card I Need**

Not a card. A wallet that keeps every card low.

UDA is the consumer company. Personal wallet. Personal cards. Household seats only.

UDA Business is a different company. It is not this repo.

```
The wallet holds the member's own credit cards.
The UDA hard card spends from them. Empty wallet, $0 card.
```

v0 runs on the LINE rules engine. It does not issue cards, move bank money, or report to bureaus.

## How it works

1. Sign up at UDA.com, with an identity check
2. Fill the wallet: add cards you already hold, or apply for offers on the bank’s own form
3. Virtual UDA number right away; hard card by mail
4. Spend: each purchase routes to a wallet card under 10%
5. Hard stop: declined if a card or the whole wallet would reach 30%

The member’s card issuers are the only lenders. UDA does not lend.

## What $25/mo buys

$25 per month or $249 per year.

- A wallet for the member’s own credit cards
- UDA hard card and virtual number
- Watcher routes every purchase to keep each card low
- Hard stop before any card reaches 30%
- Household AU on this wallet
- The Book, The Hook, The File
- Shield on the first three hooked cards
- Burnable virtual number
- We never sell your information

## Hard stop

UDA reads each wallet card’s balance and limit at the swipe.

- Route to a card that stays under 10%
- If none can, route to one that stays under 30%
- If the purchase would put any card, or the whole wallet, at 30% or more: decline
- The decline names a dollar and a date: "Pay $180 on Card A by the 14th to free room."

The stop protects utilization. It is not a score promise.

## Earnest money

An earnest money deposit (EMD) is the one exception to the hard stop.

- Locked to one title or escrow office
- Signed plan to be under 30% by the statement date
- Loaded from the member’s own wallet cards only
- Paid by card, or by the sponsor bank’s wire from the held balance
- Refunds return to the same cards
- A forfeit stays on the member’s own cards

Members are told up front: issuers usually treat an EMD load as a cash advance, typically a 3–5% fee plus interest from day one.

## Offers

Offers rank by fit, not by payout.

- UDA takes no referral fees
- The member applies on the bank’s own form
- An approved card goes into the wallet when the member adds it

## Four rooms

| Room | Job |
| --- | --- |
| The Book | Utilization on every wallet card |
| The Hook | Add / remove a card. Shield on or off per card |
| The File | Soft credit report the member agreed to |
| Watcher | Routes the purchase. Congratulates the band. Nudges when you leave it |

Green 1–9%. Amber 10–29%. Red 30%+ is stopped. Next statement date in plain English: "Photograph in 4 days."

## Shield

When you pay with the UDA hard card or virtual number, the store sees a UDA number. Not your card.

That is a shield. It is not invisibility.

- Watch is included
- Shield is included on three cards
- Fourth hooked card is +$3
- The wallet card’s issuer can still see a charge from UDA
- The network still sees a token

## Watcher

Short. Specific. No score promises.

> Nice. Card A is at 6%. That's the photograph we want.

> Declined. The tire shop would put Card B at 34%. Pay $220 before Friday and try again.

Praise is rare. Correction is a number and a date.

## Policy

- We never sell personal information, for any reason, to any company
- We do not sell spend graphs
- We take no referral fees on offers
- LifeLock is a partner we are asking for — not a live embed until paper is signed
- No fee when a score moves
- No rented authorized-user seats
- No pooling of members’ cards. One member’s cards never fund another’s purchase

UDA does not promise a score. Results vary.

## Product rules

- Personal wallet only
- Household AU: spouse, partner, or adult child
- No Operator seats
- No Team tokens
- No EIN
- No company file

## Plans

| | Starter | Build | Firm |
| --- | --- | --- | --- |
| Price | $25/mo | $25/mo | $25/mo |
| Household | 2 | 4 | 4 |
| Hooked cards with shield | 3 | 3 | 3 |

## LINE

The rules live in LINE: `dibs-financial/dibs-line`. Spec: `UDA_LINE.md` there.

This repo holds no rules code. LINE runs this company as `kind: "consumer"` and refuses to bridge it to a business wallet.

## What v0 does not do

- Live card issuing
- Live balance reads at the swipe
- Business accounts
- Shared authorized-user seats
- Score promises
- Bank wires
- Lending
- LifeLock API

Those wait on a sponsor bank, a bank-data partner, and signed partners.

## GitHub

Repo: `dibs-financial/dibs-uda-card`

About:

```
UDA. U DA’ Only Card I Need.
```

Cleaner About if GitHub feels tight:

```
UDA. The only card I need.
```

The slogan is marketing only. Not a score promise. It stays off KYC, the agreement, and bureau copy.

## License

UNLICENSED. Private.
