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
