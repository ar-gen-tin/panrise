# Cross-Border Payments & Banking for Solo Founders

## Payment Collection (Receiving Money from Customers)

### Stripe
- **Best for**: SaaS, subscriptions, one-time digital sales
- **Coverage**: 46+ countries can accept payments; customers in 195+ countries
- **Fees**: 2.9% + $0.30 per transaction (US), varies by country
- **Payout**: 2 business days (US), 7 days (most international)
- **Stripe Atlas**: Full incorporation + Stripe + Mercury bundle ($500)

### PayPal
- **Best for**: Freelancers, marketplace sellers, casual invoicing
- **Coverage**: 200+ countries
- **Fees**: 3.49% + fixed fee for commercial transactions
- **Payout**: Instant to PayPal balance, 1-3 days to bank
- **Downside**: Account freezes common, high dispute costs

### Gumroad / Lemon Squeezy / Paddle
- **Best for**: Digital products, courses, downloads
- **Key advantage**: Act as "Merchant of Record" — they handle VAT/sales tax for you
- **Fees**: 5-10% but includes tax compliance
- **Ideal when**: You sell to EU consumers and don't want to deal with VAT OSS

## Business Banking (Where Your Money Lives)

### Mercury (US — Best for Non-Residents)
- **Best for**: Non-US founders with US LLC
- **Features**: Full business checking, debit card, wire transfers, integrations
- **Fee**: $0/month
- **Opening**: Remote, no US visit required; accepts Wyoming/Delaware LLC
- **Integrations**: Stripe, QuickBooks, Gusto
- **Min balance**: None
- **Note**: Can now open before EIN is issued

### Wise Business
- **Best for**: Multi-currency operations, international transfers
- **Features**: Hold 40+ currencies, local account details in USD/EUR/GBP/AUD/SGD/etc.
- **Fee**: Small one-time fee per currency account (~$5-30)
- **Transfer fees**: 0.4-1.5% (much cheaper than banks)
- **Opening**: Remote, accepts most entity types globally
- **Ideal when**: You receive payments in multiple currencies

### Revolut Business
- **Best for**: UK/EU-based founders
- **Features**: Multi-currency, crypto, analytics, invoicing
- **Fee**: Free plan available (paid plans from £25/month)
- **Limitation**: Can be restrictive about non-resident accounts

### Airwallex
- **Best for**: High-volume cross-border transactions
- **Features**: 60+ currencies, batch payments, FX at interbank rates
- **Fee**: 0.4-1% on transfers
- **Coverage**: 150+ countries
- **Best when**: You pay contractors or suppliers internationally in bulk

### Payoneer
- **Best for**: Marketplace sellers, freelancers on platforms (Upwork, Fiverr, Amazon)
- **Features**: Receive from marketplaces, multi-currency, request payments
- **Fee**: 2% on currency conversion, 1-3% on payment requests
- **Coverage**: 190+ countries, 70+ currencies

## Cross-Border Transfer (Moving Money Between Accounts)

### Comparison

| Method | Speed | Cost | Best For |
|--------|-------|------|----------|
| Wise | 1-2 days | 0.4-1.5% | Regular transfers |
| Mercury Wire | 1-3 days | $5 domestic, varies international | US bank to US bank |
| Airwallex | 1 day | 0.4-1% | High volume |
| PayPal | Instant to balance | 3-5% total | Small amounts |
| SWIFT (traditional bank) | 3-5 days | $25-50+ per transfer | Legacy/large amounts |
| Crypto (USDC) | Minutes | <$1 gas fee | Crypto-native clients |

## Recommended Setup by Structure

### Wyoming LLC (Non-US Founder)
1. **Mercury** — primary business account (free, remote opening)
2. **Wise Business** — multi-currency receiving and transfers
3. **Stripe** — customer payments
4. **Total cost**: ~$0/month (fees only on transactions)

### Delaware C-Corp (Stripe Atlas)
1. **Stripe Atlas** — handles everything in one flow
2. **Mercury** — opened as part of Atlas pipeline
3. **Stripe** — already connected
4. **Total cost**: $500 one-time (Atlas)

### Singapore Pte. Ltd.
1. **DBS/OCBC** — local Singapore business account (visit may help)
2. **Wise Business** — international transfers
3. **Stripe** — customer payments (Singapore Stripe available)
4. **Total cost**: ~$50-100/month banking fees

### Estonia OÜ
1. **Wise Business** — primary account (best for e-Residency companies)
2. **Stripe** — customer payments (works with Estonian entities)
3. **LHV/Swedbank** — local Estonian bank (optional, harder to open remotely)
4. **Total cost**: ~$0/month

### UK Ltd
1. **Wise Business** — primary (easy to open for UK Ltd)
2. **Revolut Business** — secondary / spending
3. **Stripe** — customer payments
4. **Total cost**: ~$0-25/month

### Dubai Freezone
1. **Emirates NBD / Mashreq** — local UAE bank (required for many transactions)
2. **Wise Business** — international transfers
3. **Stripe** — available in UAE
4. **Total cost**: ~$20-50/month banking fees

## Invoice Payment Terms for Global Clients
- **Net 15-30**: Standard for B2B services
- **Prepay**: Common for SaaS, digital products
- **Milestone**: For project work >$5K
- **Currency**: Invoice in your client's currency, receive in yours via Wise/Stripe

## Tax Implications of Payment Methods
- **All payment methods report to tax authorities** — Stripe sends 1099-K (US), payment providers report under CRS (Common Reporting Standard) internationally
- **Crypto**: Increasingly tracked; most countries treat as taxable income
- **PayPal/Wise balances**: Count as foreign bank accounts (FBAR reporting for US persons if >$10K aggregate)

---

## Account Freeze Emergency Protocol

When Mercury, Wise, Stripe, or PayPal freezes your account, the first 24 hours matter most.

### Immediate Steps
1. **Do not panic-transfer** funds from other accounts — sudden movement across accounts signals more risk to fraud teams
2. Contact support immediately via the highest-priority channel (Stripe: dashboard chat > email; Mercury: email support@mercury.com; Wise: in-app chat; PayPal: phone 1-888-221-1161 > chat)
3. Screenshot every notification, email, and error message — you'll need a paper trail
4. Keep the account active but don't attempt logins from new devices or locations (triggers additional flags)
5. Do not open a second account with the same platform while the first is under review — grounds for permanent ban

### Required Documentation to Unfreeze

| Platform | Typical Docs Required |
|----------|----------------------|
| Stripe | Government ID, proof of business address, recent invoices, website URL, bank statement |
| Mercury | EIN letter, articles of incorporation, operating agreement, utility bill or lease, description of business |
| Wise | Business registration, UBO (ultimate beneficial owner) declaration, proof of address, source of funds statement |
| PayPal | ID, proof of address, bank statement, invoices for recent transactions, tracking/delivery confirmation |

**Source of funds**: Write a brief plain-English explanation of where your revenue comes from. "We sell B2B SaaS subscriptions to US customers; attached are sample invoices" is more useful than a spreadsheet.

### Timeline Expectations

| Platform | Typical Review Time | Worst Case |
|----------|-------------------|------------|
| Stripe | 1–3 business days | 7 days; funds held 90 days if terminated |
| Mercury | 3–7 business days | 14 days |
| Wise | 2–5 business days | 21 days |
| PayPal | 3–10 business days | **180-day hold** on funds if account limited |

PayPal's 180-day hold is well-documented and nearly impossible to shorten — plan accordingly.

### Prevention: Multi-Bank Strategy

Never run your business through a single financial account. Minimum viable setup:

- **Primary**: Mercury (main operations, Stripe payouts)
- **Secondary**: Wise Business (multi-currency, backup receiving)
- **Emergency reserve**: A separate account with 2–3 months of operating expenses, never connected to payment processors

**Backup banks to have pre-approved** (open accounts before you need them):

| Bank | Best For | Notes |
|------|----------|-------|
| Relay | US LLC, fintech-friendly | No crypto restriction, good for backup |
| Brex | VC-backed startups | Requires revenue or funding history |
| Revolut Business | EU/UK-based ops | Multi-currency, fast opening |
| Local bank (Chase, BOA) | US persons | Slower to open, but stable for ACH/wire |

---

## Chargeback Management

### Stripe Dispute Thresholds

| Rate | Consequence |
|------|-------------|
| 0.5% dispute rate | Warning email; monitoring begins |
| 0.65% | Placed in Visa Dispute Monitoring Program (VDMP) |
| 1.0% | Account review; risk of termination |
| 1.5%+ | Visa High-Dispute Program; $50/chargeback fine |

Dispute rate = disputes opened in a calendar month / transactions processed in that same month.

### How to Respond to a Dispute (Stripe)

**Deadline: 7 calendar days** from when Stripe notifies you. Missing the deadline = automatic loss.

Evidence to submit (strongest to weakest):
1. Signed contract or order confirmation
2. Delivery confirmation (tracking number, signed receipt, email with download link + IP)
3. Customer communications showing they received and used the product
4. Refund policy clearly shown at checkout (screenshot)
5. Login/usage logs showing the customer accessed the service post-purchase

Stripe's evidence form has specific fields — fill every section. A detailed narrative ("Customer purchased on Jan 3, accessed dashboard on Jan 4-10 per attached logs...") matters more than raw files.

### Prevention Checklist

- **Statement descriptor**: Match your descriptor to your brand name (customers won't recognize "ACME CORP LLC" and will dispute it)
- **Refund policy**: Display it on checkout page and in confirmation email — link to a dedicated URL
- **Delivery confirmation**: For digital goods, log the IP address and timestamp of first access; send a "your download is ready" email as paper trail
- **Clear communication**: Send receipts, usage summaries, and renewal reminders — most chargebacks are "I forgot I subscribed"
- **Proactive refunds**: If a customer is upset, refund before they dispute — a refund costs $0, a lost dispute costs $15+ plus the transaction amount

### Chargeback Protection Tools

| Tool | Platform | Cost | Notes |
|------|----------|------|-------|
| Stripe Radar + Chargeback Protection | Stripe | 0.4% per transaction | Stripe covers the disputed amount if you lose |
| Kount | Stripe/others | Custom pricing | ML-based fraud scoring |
| Chargebacks911 | Any processor | Custom | Dispute management service, good for volume >20/month |
| PayPal Seller Protection | PayPal | Free (built-in) | Covers eligible transactions automatically |

---

## High-Risk Industry Payment Solutions

Stripe and PayPal both maintain restricted/prohibited business lists. If your business falls into a restricted category, you need a different processor from day one — attempting to use Stripe and getting terminated damages your processing history.

### Restricted Categories (Stripe/PayPal Both Reject or Heavily Scrutinize)

| Category | Stripe | PayPal |
|----------|--------|--------|
| CBD / hemp (no THC) | Case-by-case, restricted | Prohibited |
| Cannabis (THC) | Prohibited | Prohibited |
| Crypto exchange / NFT trading | Restricted | Restricted |
| Adult content | Prohibited | Prohibited |
| Online gambling | Prohibited | Prohibited |
| Firearms / ammo | Prohibited | Restricted |
| Supplements (weight loss, hormones) | Restricted | Case-by-case |
| Telemarketing / MLM | Prohibited | Prohibited |

### Alternative Processors by Category

**Supplements / Nutraceuticals / Health**
- PaymentCloud — specializes in high-risk; approves supplements, coaching, continuity billing
- Durango Merchant Services — established high-risk processor; higher fees (3.5–5%) but stable
- NMI (Network Merchants) — white-label gateway, works with high-risk acquiring banks

**Adult Content**
- Segpay — industry standard for adult platforms
- Paxum — works with creators; also supports crypto withdrawals
- CCBill — largest adult processor, built-in subscription management

**Crypto / NFT / Web3**
- BitPay — accepts BTC, ETH, stablecoins; settles in fiat or crypto
- Coinbase Commerce — no fees on crypto transactions; good for one-time payments
- Stripe Crypto Onramp — limited to fiat→crypto flows only, not general crypto businesses
- MoonPay (B2B) — for embedding crypto purchase into your product

**CBD / Cannabis**
- Square — more lenient than Stripe for CBD (hemp-derived, <0.3% THC); review required
- PaymentCloud — covers CBD merchant accounts
- Paybotic — cannabis-specific; works in US states where legal

### Crypto Company Banking

| Bank | Crypto Policy |
|------|--------------|
| Mercury | Case-by-case review; crypto exchanges often rejected; holding/using crypto as treasury OK |
| Relay | No stated crypto restriction; less scrutiny than Mercury for crypto-adjacent businesses |
| Mercuryo Business | Crypto-native; accepts crypto companies, DeFi, NFT platforms |
| Brex | Accepts crypto startups with VC backing; less friendly to early-stage |
| Silvergate / Signature | Both failed in 2023 — no longer options |
| Customers Bank | Replaced Silvergate for many crypto firms; CBIT network |

### Pre-Approval Tips

1. **Read the full Terms of Service before building** — "payment processing" section, not just the summary
2. **Email risk@processor.com before applying** — ask if your specific business model is eligible; get confirmation in writing
3. **Have a legal opinion letter ready** for anything involving cannabis, crypto, or financial services
4. **Expect higher fees**: High-risk processing typically runs 3–5% + $0.20-0.50 per transaction vs. Stripe's 2.9% + $0.30
5. **Rolling reserve**: Many high-risk processors hold 5–10% of monthly volume for 90–180 days as a reserve; factor this into cash flow

---

## Platform Creator Tax & Payments

### YouTube / AdSense — Withholding Tax

Google withholds US taxes from AdSense payments to non-US creators. Submitting the correct form dramatically reduces this.

| Entity Type | Form to Submit | Withholding Without Form | With Treaty (e.g., Japan, UK) | With Treaty (No Treaty Country) |
|-------------|---------------|-------------------------|-------------------------------|----------------------------------|
| Individual (non-US) | W-8BEN | 30% | 0–15% depending on treaty | 30% |
| LLC (non-US members) | W-8BEN-E | 30% | 0–15% depending on treaty | 30% |
| US person / US LLC | W-9 | Backup withholding only | N/A | N/A |

Key countries and their US tax treaty rates on YouTube income:
- Japan: 0% (Article 12, royalties)
- UK: 0%
- Germany: 0%
- Taiwan: 10%
- Canada: 0–10%
- No treaty (most Southeast Asia, Africa): 30%

**Action**: Submit W-8BEN or W-8BEN-E in AdSense > Payments > Manage settings. Renew every 3 years.

### Patreon

- For **US entities**: Patreon issues a 1099-K if you process >$600/year (post-2023 IRS threshold change); income is taxable as ordinary income
- For **non-US entities**: Patreon pays gross amounts; no US withholding on most creator income (considered services, not royalties); **your home country taxes apply**
- Patreon fees: 8% (Lite), 12% (Pro), 15% (Premium) + Stripe/PayPal processing fees (~2.9% + $0.30)
- Payout: Via Stripe or PayPal; same freeze risks apply

### Substack

- Substack uses **direct Stripe integration** — you are the merchant of record
- Stripe fees: 2.9% + $0.30 per transaction
- Substack's cut: 10% of paid subscription revenue
- Tax: Stripe issues 1099-K for US entities; non-US entities receive gross; standard CRS reporting applies
- For VAT: Substack **does not handle EU VAT** on your behalf — if you have EU subscribers and hit local thresholds, you are responsible (unlike Gumroad/Paddle which act as MoR)

### Gumroad

- Acts as **Merchant of Record** — handles VAT/GST globally
- Gumroad's cut: 10% flat fee (as of 2023 pricing change)
- Payouts: Weekly via PayPal or Stripe bank deposit
- Tax reporting: Issues 1099-K for US persons; non-US creators get gross payments; Gumroad reports under CRS

### Multiple Platform Income: VAT Threshold Aggregation

If you earn across YouTube, Patreon, Substack, and Gumroad, **aggregate your EU digital services revenue** for VAT threshold purposes:

- EU VAT OSS threshold: **€10,000/year** across all EU B2C digital sales
- Once exceeded, you must register for VAT OSS in one EU country and report all EU sales
- Gumroad/Paddle handle this for their platform sales; Stripe/Patreon/AdSense do not
- Practical threshold: If you're earning <€10K from EU consumers total, you're likely under the threshold; above it, get an OSS registration

### CRS / FATCA Reporting — What All Platforms Do

Every major platform reports to tax authorities. There is no "under the radar" option:

| Platform | Reports To | Mechanism |
|----------|-----------|-----------|
| YouTube/AdSense | IRS (1042-S for non-US), local tax auth | FATCA / CRS |
| Patreon | IRS (1099-K), local auth via CRS | FATCA / CRS |
| Stripe | IRS (1099-K), EU tax authorities | FATCA / CRS |
| PayPal | IRS (1099-K), local auth via CRS | FATCA / CRS |
| Gumroad | IRS (1099-K for US), CRS for non-US | FATCA / CRS |

**Bottom line**: Declare all platform income. The question is not whether authorities will know, but whether you've applied for the correct treaties and deductions to minimize the rate.

---

## Hong Kong Bank Account Comparison for Mainland Founders

| Bank | Type | Account Opening | Monthly Fee | SWIFT Inbound | Stripe Compatible | Best For |
|------|------|----------------|-------------|---------------|-------------------|----------|
| ZA Bank | Virtual | Fully online app, requires HKID | HKD 0 | Yes (USD/HKD) | Yes | Starting out, low-cost (HKID required) |
| Mox Bank (天星) | Virtual | Fully online | HKD 0 | No SWIFT inbound | No | Personal spending only |
| Ant Bank (众安) | Virtual | Fully online | HKD 0 | Yes | Yes | Backup account |
| Airwallex HK | Payment account | Online + video KYC | HKD 0 | Yes (60+ currencies) | Yes | High-frequency collections |
| HSBC Business | Traditional | In-person appointment required | HKD 200/month (waivable) | Yes | Yes | Large transactions, trade finance |
| Hang Seng Business | Traditional | In-person required | HKD 100-200/month | Yes | Yes | Alternative to HSBC |

### ZA Bank — Specific Notes for Mainland Founders

**IMPORTANT: ZA Bank Business accounts require ALL directors/shareholders to hold valid HKID and be HK tax residents. Personal accounts also require HKID. Mainland Chinese without HKID cannot open ZA Bank business accounts — use Airwallex HK or Statrys as alternatives.**

| Topic | Detail |
|-------|--------|
| ID accepted (personal) | Requires HKID; 港澳通行证 alone is NOT sufficient for account opening |
| ID accepted (business) | All directors/shareholders must hold valid HKID and be HK tax residents |
| First deposit | Via Wise HKD transfer or FPS from another HK account |
| Limitations | No cheque book, no trade finance, no credit facility |
| KYC renewal | Annual, mostly automated (document upload via app) |

### Airwallex HK vs ZA Bank

| Dimension | Airwallex HK | ZA Bank |
|-----------|-------------|---------|
| Currency support | 60+ currencies | HKD, USD, EUR (limited) |
| Transaction limits | Higher limits | Lower limits |
| Batch payments | Yes | No |
| Stripe settlement | Yes | Yes |
| HKD holding | Yes | Better suited |
| Complexity | More features, steeper setup | Simpler, faster to start |

**Recommendation**: Open BOTH — ZA Bank as primary Stripe settlement account, Airwallex for international collections.

### HSBC Business — Opening Tips for Mainland Founders

| Factor | Detail |
|--------|--------|
| Common rejection reasons | No HK local business presence, vague business description, no proof of revenue |
| Success factors | Bring 6+ months of bank statements, client contracts, company financials, business plan |
| Account opening service | Consider using a service (HKD 3,000–8,000) for higher success rate |
| Alternative path | Open HSBC Personal first (easier approval), then upgrade to Business after 6 months |

---

## Stripe HK Registration — Troubleshooting

### Required Documents

- HK Business Registration (BR) — must be valid
- Certificate of Incorporation (CI)
- Director passport or HKID
- Proof of address (director or company)
- Business website (live and functional)

### Common Rejection Reasons and Fixes

| Rejection Reason | Fix |
|-----------------|-----|
| "Website not live" | Must have a working website with product/service description before applying |
| "Business description unclear" | Write detailed description: what you sell, to whom, how payment works |
| "Restricted business type" | Check Stripe's restricted list; crypto/gambling/adult content blocked |
| "Director not verified" | Ensure passport photo matches, address document must be <3 months old |

### Stripe HK vs Stripe US (Using HK Company)

| Dimension | Stripe HK | Stripe US |
|-----------|-----------|-----------|
| Entity required | HK company (BR + CI) | US entity with EIN |
| Settlement currency | HKD to HK bank | USD to US bank |
| Transaction fee | 3.4% + HKD 2.35 per transaction | 2.9% + USD 0.30 per transaction |
| HK company eligibility | Yes — direct signup | No — HK company cannot directly use Stripe US |
| USD settlement path | Stripe HK → HKD → convert via Wise/Airwallex | N/A (requires US entity) |

### After Rejection

- Wait 30 days before reapplying
- Fix all identified issues before resubmitting
- Reapply with improved documentation and a clearer business description

### Alternatives to Stripe HK

| Option | Fees | Notes |
|--------|------|-------|
| Airwallex payment links | ~2.6% + HKD | Good for one-time or low-volume invoices |
| 2Checkout (Verifone) | 3.5% + $0.35 | Works with HK entities, global coverage |
| PayPal Business | 3.49% + fee | Higher fees but easier approval for most business types |

---

## Mainland Bank Cards in Hong Kong — Limits & Workarounds

### UnionPay ATM Withdrawals in HK

- Maximum per transaction: **HKD 5,000** (hard limit enforced by HK ATMs)
- Daily aggregate limit: equivalent of **RMB 10,000** — but the exact HKD cap varies by issuing bank (some set it lower, e.g., RMB 8,000)
- Each withdrawal counts against your issuing bank's daily ATM limit, not just the UnionPay network limit
- ATM fees: HK ATMs typically charge HKD 15–30 per withdrawal for mainland cards; your issuing bank may also charge a cross-border fee (~1%)

### UnionPay POS Purchases in HK

- HK POS purchases using a mainland UnionPay debit or credit card are **counted toward your annual individual foreign exchange quota (USD 50,000 equivalent)**
- The transaction is converted at the daily reference rate published by the People's Bank of China; a ~1–1.5% FX markup is added by your issuing bank
- This applies to both UnionPay debit cards and credit cards; credit card spending in HK also counts
- Once you approach the USD 50,000 annual quota, the issuing bank will decline the card for FX conversion

### WeChat Pay: Mainland vs HK Wallets

- **Mainland WeChat Pay** and **WeChat Pay HK** are entirely separate wallets with separate balances, separate KYC, and separate currencies (RMB vs HKD)
- Mainland WeChat Pay can pay at selected HK merchants that have enabled the cross-border QR code feature, but a FX conversion fee of approximately **1–3%** applies
- The cross-border payment is routed through the mainland wallet; the amount consumed counts against the **USD 50,000 forex quota**
- Not all HK merchants support mainland WeChat Pay — look for the mainland WeChat Pay logo specifically, not the general WeChat Pay logo

### Alipay: Same Structure

- Mainland Alipay and Alipay HK are separate apps with separate accounts
- Mainland Alipay works at selected HK merchants (particularly in tourist and retail areas) via cross-border scan
- FX conversion fee: ~1–2%; counts against USD 50,000 quota
- Alipay HK requires a HK phone number and HK bank account to set up — it is a different product from mainland Alipay

### Using HK Company Funds for Personal Expenses

| Approach | Tax/Legal Status | Notes |
|----------|-----------------|-------|
| Pay yourself salary from HK company → deposit to HK personal account → use HK debit card | **Proper** — salary is a legitimate company expense; subject to HK Salaries Tax if work performed in HK | Requires proper payroll records and MPF contributions if you are an HK employee |
| Pay yourself a declared director's loan for legitimate advances | **Acceptable with documentation** — must be recorded in company accounts; repayment schedule required | IRD may impute interest if no commercial terms documented |
| Use company debit/credit card for personal purchases | **Improper** — treated as a director's loan or undeclared benefit in kind; must be repaid to the company or recognized as income | Accountants will flag this on the annual accounts; may trigger Profits Tax assessment and IRD scrutiny |

### Practical Setup for CN Founders Living Between Shenzhen and HK

The optimal daily banking stack for a founder commuting across the Shenzhen-HK border:

| Tool | Purpose | Setup Requirement |
|------|---------|-------------------|
| **ZA Bank** (personal HKD account) | Primary HK spending account; works at all HK merchants and ATMs; debit card issued | Open via app with HKID; no in-person visit needed. **Mainland residents without HKID cannot open ZA Bank — use Airwallex HK or Statrys instead** |
| **Salary transfer** from HK company | Fund your ZA Bank personal account with salary from your HK company each month | Set up regular bank transfer from company account to personal ZA Bank |
| **Octopus card (八达通)** | MTR, buses, minibuses, convenience stores, fast food — covers ~95% of daily HK transit and small purchases | Available at any MTR station; top up with HK card or cash |
| **Mainland bank card** (UnionPay) | Mainland expenses only — groceries, restaurants, Didi, utilities in Shenzhen | Keep a separate card for mainland use; avoid using it in HK to preserve your forex quota |
| **Airwallex HK** (company account) | Receive international payments (Stripe, PayPal, wire transfers) into company; batch pay overseas contractors | Set up alongside ZA Bank for business operations |

**Key principle**: keep company funds in the company account (Airwallex/HSBC), pay yourself a regular salary or director's fee into your personal ZA Bank account, and use the ZA Bank debit card for all HK personal spending. This maintains a clean separation between business and personal funds and avoids director loan complications.
