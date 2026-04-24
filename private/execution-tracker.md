# Modulor — Execution Tracker

Single source of truth for who's on paper vs. who's not. Cross-reference with `company-formation.md` (terms) and `CLAUDE.md` state snapshot (narrative).

**Last updated:** Apr 24, 2026

---

## Cap table execution status

| Holder | Role | Equity | Memo | Legal instrument | Grant date | 83(b) deadline | 83(b) filed | Stamped copy |
|---|---|---|---|---|---|---|---|---|
| Mitchell Lisa | CEO · Director | 88% common (→78% post-issuances) | n/a | ✅ RSPA (Atlas) | Apr 20, 2026 | **May 20, 2026** | ⏳ Atlas queued, postmark May 4 (buffer May 6) | ⏳ Awaiting return from Atlas |
| Andrew Lisa | Co-Founder · CFO | 5% common (RSPA from Mitchell) | ✅ Verbal accept Apr 21 | ❌ Pending — Clerky/Atlas Plus flow | TBD (target this week) | Grant + 30 days | — | — |
| Matthew Lucas Lisa ("Luke") | Co-Founder · CTO | 5% common (RSPA from Mitchell) | ✅ Verbal accept Apr 21 | ❌ Pending — blocked on Colonel signature | TBD (Wed Apr 29 earliest) | Grant + 30 days | — | — |
| Adam H. Evans | Strategic Advisor — DoD + Mil-Tech | 1% common options (FAST Platinum) | ✅ Verbal accept Apr 22 | ❌ Pending — FAST Platinum template + mutual NDA first | TBD (target week of May 4) | n/a (options) | n/a | n/a |

### Mechanism notes

- **Luke + Andrew RSPAs = founder-to-founder transfer.** Company repurchases 1M shares from Mitchell at par ($10), reissues as two 500K RSPAs with vesting. Preserves Mitchell's QSBS on remaining 7.8M (clock from Apr 20, 2026). Luke + Andrew get fresh QSBS clocks from grant date.
- **Atlas does NOT have a founder-addition flow.** Execute via Clerky (~$500/RSPA) or Atlas Plus partner firm (Cooley/Orrick/Gunderson, $2–5K).
- **Adam = options from the 12% pool.** No 83(b). Strike = FMV at grant; pre-409A the board documents a good-faith determination at par or de minimis. Re-up with 409A before first priced round.

### Luke's legal name (for all paper)

**Matthew Lucas Lisa** (per Luke's text, Apr 24 2026). Use on RSPA, 83(b), stock cert, board consents. "Luke" is first-name-as-known for day-to-day.

---

## NDA counterparties

| Party | Purpose | NDA type | Status |
|---|---|---|---|
| Anyone hitting `/pitch` | Deck preview | Click-wrap (one-way) | ✅ Live, Supabase-logged |
| Adam Evans | Advisor — pre-hardware/IP disclosure | Mutual | ❌ Not sent |
| Design/CNC/prototyping vendors (TBD) | Contractor engagements | Mutual | ❌ Template needed |
| Investor diligence 1:1 (Richard Xie + beyond) | Term-sheet-stage diligence | Mutual | ❌ Send when requested |

---

## Investor agreements

| Counterparty | Instrument | Valuation cap | Discount | Status |
|---|---|---|---|---|
| KAS — Richard Xie | YC post-money SAFE (planned) | TBD | TBD | ❌ No terms yet; meeting in May |

---

## Deadlines (T-minus from today Apr 24, 2026)

| Event | Date | T-minus | Reminder cadence |
|---|---|---|---|
| Atlas postmark Mitchell 83(b) | May 4, 2026 | T-10 | Daily watch once T-5 |
| Mitchell 83(b) window hard close | **May 20, 2026** | **T-26** | T-14, T-7, T-1 |
| Luke mil-side Colonel signature (target) | Apr 29, 2026 | T-5 | Daily |
| Andrew RSPA executed (target) | This week | T-0–3 | Daily |
| Luke RSPA executed (target) | Apr 29–30, 2026 | T-5–6 | Daily |
| Luke + Andrew 83(b) windows | Grant + 30 days | Set once grants issue | T-14, T-7, T-1 |
| Adam FAST Platinum + mutual NDA | Week of May 4 | T-10 | Weekly |
| Delaware franchise tax (first filing) | Mar 1, 2027 | T-311 | Monthly starting Oct 2026 |
| VITR-001 non-provisional conversion | Apr 15, 2027 | T-356 | Monthly starting Jan 2027 |

---

## Update discipline

Every time a box flips from ❌ to ✅ — update this table, commit with a one-line message, and update the matching entry in `CLAUDE.md` state snapshot. Don't let drift accumulate.
