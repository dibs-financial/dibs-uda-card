<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
    <img src="assets/logo.svg" width="282" height="120" alt="UDA wordmark: a U with three gold lashes like a closed eye, followed by D and A">
  </picture>
</p>

# UDA

**The only Tool You Need when building credit**

One card. One personal file.

UDA is the consumer company. Personal card. Personal book. Household seats only.

UDA Business is a different company. It is not this repo.

```
Household AUs sit on the founder's personal UDA.
Nobody's personal file moves unless they flip a toggle and agree.
```

v0 is the consumer rules engine and a local HTTP API. It does not issue cards, move bank money, or report to bureaus.

## What $25/mo buys

$25 per month or $249 per year.

- One personal revolving book, three bureaus when the bank is live
- Watcher composes utilization on that book
- Household AU on this card
- The Book, The Hook, The File
- Watch hooked cards
- Shield on the first three hooked cards
- Burnable virtual number
- We do not sell your data

Chime is free if they get the paycheck. Extra is $20–25 for two bureaus. UDA is $25 for the book, the shield, and the watch.

## Four rooms

| Room | Job |
| --- | --- |
| The Book | Utilization on UDA and every hooked card |
| The Hook | Attach / detach. Shield on or off per card |
| The File | Soft credit report the member agreed to |
| Watcher | Congratulates the band. Nudges when you leave it |

Green 1–9%. Amber 10–29%. Red 30%+. Next statement date in plain English: "Photograph in 4 days."

## Shield

When another card is hooked to UDA, the store sees a UDA number. Not their card.

That is a shield. It is not invisibility.

- Watch is included
- Shield is included on three cards
- Fourth hooked card is +$3
- The attached issuer can still see a charge from UDA
- The network still sees a token

## Watcher

Short. Specific. No score promises.

> Nice. UDA is at 6%. That's the photograph we want.

> UDA jumped to 34% after the tire shop. Pay $220 before Friday and the picture goes back to 7%.

Praise is rare. Correction is a number and a date.

## Policy

- We do not sell personal information
- We do not sell spend graphs
- LifeLock is a partner we are asking for — not a live embed until paper is signed
- No fee when a score moves
- No rented authorized-user seats

UDA does not promise a score. Results vary.

## Product rules

- Personal book only
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

## Run

```bash
npm install
npm test
npm start
```

API: `http://localhost:8787`

```bash
curl -s -X POST localhost:8787/entities \
  -H 'content-type: application/json' \
  -d '{"kind":"consumer","legalName":"Alex Rivera","ssnLast4":"0000"}'
```

## What v0 does not do

- Live card issuing
- Business accounts
- Shared authorized-user seats
- Score promises
- Bank wires
- LifeLock API

Those wait on a sponsor bank and signed partners.

## GitHub

Repo: `dibs-financial/dibs-uda-card`

About:

```
UDA. The only tool you need when building credit.
```

## License

UNLICENSED. Private.
