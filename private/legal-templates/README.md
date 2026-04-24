# Legal template sources

Index of where each standard document comes from. **Downloaded templates themselves go in this folder but are gitignored** (see pattern at bottom). Signed instruments move to `private/formation-docs/` (also gitignored).

---

## RSPAs (Luke, Andrew)

**Primary recommendation: Clerky — `clerky.com`.** ~$500 per RSPA issuance. Template-driven, lawyer-drafted, handles the full package: board consent authorizing repurchase + reissuance, new RSPA with vesting terms, 83(b) form + mailing instructions, stock ledger update.

**Alt: Stripe Atlas Plus partner firms.** $500/yr Atlas Plus subscription unlocks discounted rates (30–50% off) at Cooley, Orrick, Gunderson. Post-formation founder add runs $2–5K through partners. Overkill unless retaining counsel anyway.

**Atlas self-serve does NOT cover this.** Atlas's RSPA flow is single-founder-at-formation only.

### Terms to plug into the template

Pulled from `private/luke-role-memo.md` and `private/andrew-role-memo.md`:

- Shares: 500,000 common each
- Purchase price: $0.00001 par × 500,000 = **$5.00 per founder**
- Vesting: 4-year monthly, 1-year cliff (25% at month 12)
- Acceleration: double-trigger (change of control + involuntary termination w/in 12 months)
- Source: company repurchase from Mitchell (1M shares at $10 par), contemporaneous reissuance
- 83(b): each files own within 30 days of grant date

### Parties

- Luke: **Matthew Lucas Lisa** (legal name per ID)
- Andrew: **Andrew Lisa**

---

## 83(b) Election

**Source:** IRS fillable PDF (search "83(b) election form" — the 1-pager) OR included in Clerky/Atlas RSPA package.

Each recipient mails their own via **USPS Certified Mail** within 30 days of grant. Keep the green card + stamped copy. Save to `private/formation-docs/` when stamped copy returns.

---

## FAST Platinum (Adam advisor agreement)

**Source: Founder Institute — `fi.co/fast` (free).** Pick the Platinum variant (1% equity tier, 2-year monthly vest, no cliff).

### Terms to plug in

Pulled from `private/adam-role-memo.md`:

- 1.0% common-stock options from the 12% pool (100,000 shares)
- 2-year monthly vest, no cliff
- Strike: FMV at grant (pre-409A: board good-faith determination at par / de minimis)
- Acceleration: double-trigger
- Termination: either party 30 days' notice; unvested options cease vesting on termination
- Commitment: ~6–8 hrs/mo

### Sequence

1. Mutual NDA signed first (before hardware/IP specifics)
2. FAST Platinum signed second
3. Board consent granting the options
4. Strike documented in board minutes

---

## Mutual NDA

**Source options (pick one):**

1. **Stripe Atlas — included templates library** (if Atlas Plus) — Delaware-governed, mutual, 2-year term
2. **YC — `ycombinator.com/documents`** (free) — "NDA" template, lawyer-vetted, industry standard

Use for: Adam (pre-FAST), vendor/contractor engagements, any 1:1 investor diligence that graduates past the `/pitch` click-wrap.

---

## SAFE (investor agreement)

**Source: YC — `ycombinator.com/documents` (free).** Use the **post-money SAFE** (2018+ standard). Three variants:

- Valuation cap only
- Discount only
- Valuation cap + discount (most common)

### Decision knobs

- **Cap:** TBD based on market comps + Richard Xie response
- **Discount:** typical 15–25%; skip if cap is priced right
- **MFN clause:** optional; protects early investors if later SAFEs get better terms

**Process:** Andrew (CFO) red-lines every SAFE before Mitchell signs. No SAFE goes out without his eyes on it first.

---

## Ignored from git

This folder is for downloaded template files (`.docx`, `.pdf`) and filled-in drafts. **Do not commit any template file content to git.** This README is the only tracked file here.

Pattern to add to `.gitignore` (done):
```
private/legal-templates/*.docx
private/legal-templates/*.pdf
private/legal-templates/*.doc
```
