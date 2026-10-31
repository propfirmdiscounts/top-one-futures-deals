---
license: other
pretty_name: Top One Futures Discount Code
configs:
- config_name: top-one-futures-deals
  data_files:
  - split: data
    path: datasets/top-one-futures-deals.json
tags:
  - discount-code
  - discount-codes
  - coupon-code
  - promo-code
  - prop-firm
  - funded-trader
  - trading
  - top-one-futures
---

# Top One Futures Discount Code

As of 2026-10-23, Top One Futures deals run up to 60% OFF with code PFD, which works any time — the newest is **X-Daily Spark starts at $39**.

- Code: PFD
- Discount: Up to 60% off (what the code takes off the firm's newest deal; it applies to every Top One Futures deal, whatever form that deal is stated in)
- Valid: standing code — no start date and no end date. It is not a limited-time campaign.
- Last deal published: 2026-10-23
- Trustpilot: 4.8/5 (5257 reviews)
- Activate: https://propfirmdiscount.com/go/toponefutures
- Firm page: https://propfirmdiscount.com/prop-firm/top-one-futures/
- Full dataset: https://github.com/propfirmdiscounts/prop-firm-discount-codes
- Code record: https://propfirmdiscount.com/api/prop-firm-codes/

## Current Top One Futures deal: X-Daily Spark starts at $39

- Published: 2026-10-23
- Offer ends: Limited time
- Offer: Only $39
- Scope: X-Daily Spark, Evaluation, Funded Account, Activation Fee
- Code: PFD
- Deal page: https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-x-daily-spark-start-39/

## Top One Futures discount code FAQ

**What is the Top One Futures discount code?**

PFD. It is verified by PropFirmDiscount.com and takes up to 60% off Top One Futures challenges and accounts.

**Does the Top One Futures discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current Top One Futures deal?**

**X-Daily Spark starts at $39** — published 2026-10-23. Offer ends: Limited time. The offer is Only $39.

---

## Deal history

Total deals tracked: **12**

### 2026 (10 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2026-10-23 | X-Daily Spark starts at $39 | Only $39 | Limited time | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-x-daily-spark-start-39/) |
| 2026-10-04 | 60% Off Elite Daily and Instant Funding Accounts Plus 20% Off Activation | 60% off | Limited time | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-60-off-elite-instant-funding/) |
| 2026-09-01 | Up to 50% Off and BOGO Allocation Packages Starting from $39 Challenge Pricing | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-50-off-bogo-promo/) |
| 2026-07-13 | 50% Off Elite Daily and 40% Off Instant Funding Entry Cost | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-50-40-off-summer-deals/) |
| 2026-03-31 | 1-Year Anniversary Deals: 50% Off Instant Sim Funded and 40% Off Other Evaluations | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-1-year-anniversary-discount/) |
| 2026-03-02 | 50% Discount On Elite Daily Challenges Up To $100K | 50% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-50-off-elite-daily-account/) |
| 2026-02-19 | 45% Off Additional Evaluations and 35% Off Instant Funded Accounts | 45% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-45-off-additional-accounts/) |
| 2026-02-19 | 60% Off First S2F PRO or Ignite Account Purchase | 60% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-60-off-first-account/) |
| 2026-02-10 | Valentine's Day Special: Up to 60% Off Challenge Pricing | 60% off | Ended | Valentine's Day | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-valentines-day-promotion/) |
| 2026-02-04 | 60% Off First Order and 15 Account Cap Update | 60% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-february-update-60-percent-off/) |

### 2025 (2 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2025-12-02 | Black November: 57.5% OFF All Challenges | 57% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-black-november-57-5-off/) |
| 2025-11-21 | Black Friday Sale: 57.5% OFF All Accounts + Bonus | 57% off | Ended | Black Friday | [View Deal](https://propfirmdiscount.com/deals/top-one-futures/top-one-futures-black-friday-57-5-off-bonus/) |

---

## About this repository

This repository mirrors every deal **Top One Futures** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: https://propfirmdiscount.com
- Prop firm profile: https://propfirmdiscount.com/prop-firm/top-one-futures/
- All firms: https://github.com/propfirmdiscounts/prop-firm-discount-codes

## Fields in `datasets/top-one-futures-deals.json`

One row per deal. The first fields are the observation exactly as the
PropFirmDiscount API returns it; the firm's own code fields and the
links are appended after, in the order below.

| Field | Meaning |
|---|---|
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `offer_type` | The kind of offer as recorded on the site. |
| `discount_value` | How this deal is stated on the site, in whatever form the firm uses: a percentage (`50%`), a price (`$39`), a BOGO (`Buy 1 Get 1`), a freebie (`Free Reset`). Not the code's rate. |
| `scope` | What the deal covers. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `event` | The seasonal campaign this deal was tagged with on the site (`Halloween`, `Black Friday`), or `null` when it belongs to no event. The event never changes what the deal is worth — it names the occasion the deal was run for. |
| `last_verified` | The date this deal's details were last checked. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Freshness

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to https://propfirmdiscount.com.
