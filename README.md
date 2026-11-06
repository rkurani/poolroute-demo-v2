# PoolRoute Ops demo — v2 (side-by-side copy)

This is a **duplicate** of the public interactive demo at
https://storage.googleapis.com/poolroute-ops-demo/index.html (Sep 15, 2026),
with newer PoolRoute Ops features surfaced so Ravi can compare two versions.

**Do not overwrite** the original `index.html` or `/commercial/` in the bucket.
If uploading, put this folder at `gs://poolroute-ops-demo/v2/`.

## Open locally

```bash
cd poolroute-demo-v2
python3 -m http.server 8765
# then open http://localhost:8765/
```

## Added in v2 (vs original)

- App Store + Google Play badges (store links)
- Create menu dropdown including **Agreement** (Sign / Enroll / Void)
- **Plans** with card/ACH autopay + month-end billing (combine quotes → invoice, scheduled sends)
- **Integrations**: QuickBooks Online, Skimmer import, Pool Brain import, Fiserv payouts
- **Commissions** (tech) with Fiserv payout CTA
- **Messages** (office texting + overdue reminders)
- **Live Ops**
- **Mobile & login** (mobile office, OTP, Spanish) + guided tour entry
- Link to **commercial/** page
- Pricing left at **$49/mo** (unchanged)
- Not added: Instinct×PRO, customer financing

## Files

- `index.html` — interactive demo (self-contained)
- `commercial/` — copy of commercial landing (Nov 4)
- `og.png`, `favicon.ico`, `apple-touch-icon.png`, `PoolRouteOps-one-pager.pdf`


## Sample data (v2 seed)

~43 residential + 6 commercial/HOA customers, 5 techs, 28 stops today, invoices/agreements/plans/commissions/texts/QBO/Skimmer/Fiserv/Live Ops all populated with fictional names.
