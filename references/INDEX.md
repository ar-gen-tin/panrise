# Panrise Knowledge Base Index

> Auto-generated summary of all reference files. Read this first to decide which files to load.
> Last updated: 2026-04-08

## Quick Lookup

| File | Lines | Core Topics | When to Read |
|------|-------|-------------|-------------|
| `jurisdictions.md` | 120 | 8 jurisdictions (US/SG/EE/AE/UK/HK/CA/AU), star ratings, tax rates, costs, banking | User asks "where to incorporate" |
| `solo-structures.md` | 402 | 8 entity types (WY LLC, DE LLC, SG Pte, EE OÜ, UK Ltd, Dubai FZ, HK Ltd, TW OBU), decision trees, CN/TW special sections | User needs specific entity comparison or nationality-specific structure |
| `forex-controls.md` | 207 | CN ($50K), IN ($250K LRS), TW, KR, JP, BR, HK, SG, US, UAE, EU — limits, workarounds, CRS | User from forex-controlled country (CN/IN/BR/TW/KR) |
| `tax-residency.md` | 123 | 183-day rule, territorial/zero-tax countries, nomad visas (PT/ES/HR/TH/AE/GR), 5 tax traps, 4 profile strategies | User asks about personal tax, digital nomad, "where should I pay tax" |
| `tax-optimization.md` | 119 | 5 strategies (entity type, residency, deferral, deductions, DTA), Flag Theory, what NOT to do | User asks about minimizing tax, deductions, tax planning |
| `payments-banking.md` | 123 | Stripe/PayPal/Wise/Airwallex/Payoneer, banking by jurisdiction, invoice terms, tax implications | User asks about receiving payments, banking, transfers |
| `vat-gst.md` | 154 | EU VAT (OSS), US sales tax, AU/SG/NZ/JP/CA/UK GST, MoR strategy (Paddle/Lemon Squeezy), thresholds | User sells to consumers, asks about VAT/tax collection |
| `cost-comparison.md` | 99 | Year 1 costs for 8 jurisdictions, hidden costs, revenue breakpoints, ROI calculation example | User asks "how much does it cost" or compares jurisdictions |
| `tax-treaties.md` | 75 | 5 DTA routes (US LLC, SG, EE, HK, Dubai), WHT rates, when DTAs don't help | User has company in one country, lives in another |
| `architecture-patterns.md` | 102 | 3 patterns (single entity, home+foreign, nomad+zero-tax), when NOT to incorporate, common mistakes | User asks about multi-entity structures or "do I need a company" |
| `hiring-contractors.md` | 123 | Contractor vs employee test, payment methods, EOR (Deel/Remote), agreements, country gotchas | User asks about hiring, paying people, contractor agreements |
| `data-compliance.md` | 142 | GDPR, CCPA, UK GDPR, PIPL, cookie consent, email compliance, privacy tools, checklist by stage | User serves EU customers, asks about privacy/GDPR |
| `ip-trademark.md` | 144 | Trademark (Madrid Protocol), copyright, China first-to-file, domain strategy, open source licenses | User asks about protecting brand, trademark, IP |

## Cross-Reference Map

```
Nationality detected → Primary files:
  CN → forex-controls → solo-structures (HK section) → tax-residency (CRS)
  IN → forex-controls (FEMA/LRS) → tax-treaties (DTAA) → hiring-contractors
  US → tax-optimization (FEIE/CFC) → solo-structures (LLC) → tax-residency
  EU → data-compliance (GDPR) → vat-gst → jurisdictions
  JP → jurisdictions → tax-residency → payments-banking
  KR → forex-controls → jurisdictions → tax-residency
  BR → forex-controls → jurisdictions → payments-banking

Topic detected → Primary files:
  "incorporate/register" → jurisdictions → solo-structures → cost-comparison
  "payments/banking" → payments-banking → (jurisdiction-specific section in solo-structures)
  "tax/optimize" → tax-optimization → tax-residency → tax-treaties
  "VAT/GST" → vat-gst → (MoR decision in payments-banking)
  "hire/contractor" → hiring-contractors → (country gotchas section)
  "GDPR/privacy" → data-compliance
  "trademark/IP" → ip-trademark
  "cost/budget" → cost-comparison → (revenue breakpoints in architecture-patterns)
```

## Key Numbers (quick reference)

| Fact | Value | Source |
|------|-------|--------|
| Wyoming LLC setup cost | $160 | cost-comparison |
| Wyoming LLC annual cost | $60 | cost-comparison |
| UK Ltd setup cost | £12 | jurisdictions |
| Singapore annual compliance | SGD 3-5K | cost-comparison |
| China individual forex limit | $50,000/year | forex-controls |
| India LRS limit | $250,000/year | forex-controls |
| EU VAT threshold (B2C digital) | €10,000 | vat-gst |
| FEIE exclusion (US citizens) | ~$126,500 | tax-optimization |
| 183-day tax residency threshold | 183 days | tax-residency |
| Stripe transaction fee | 2.9% + $0.30 | payments-banking |
| Deel EOR cost | $599/month/person | hiring-contractors |
| GDPR max fine | €20M or 4% revenue | data-compliance |
