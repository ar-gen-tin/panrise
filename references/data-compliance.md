# Data Privacy & Compliance for Solo Founders

## Do You Need to Care About Data Privacy?

**YES**, if you:
- Have a website that collects emails, cookies, or analytics
- Sell to customers in the EU (GDPR), California (CCPA), or UK (UK GDPR)
- Store any customer personal data (name, email, payment info, IP address)
- Use analytics tools (Google Analytics, Mixpanel, Amplitude)

**The good news**: For solo founders, compliance is straightforward. You don't need a DPO or a 50-page policy.

## GDPR (EU + EEA) — The Big One

### When GDPR Applies to You
- You sell products/services to people in the EU, OR
- You monitor behavior of people in the EU (analytics, tracking)
- **It doesn't matter where YOUR company is registered** — if you serve EU customers, GDPR applies

### What You Must Do (Minimum Viable Compliance)

1. **Privacy Policy** — Clear, plain-language page explaining:
   - What data you collect and why
   - How you process and store it
   - Who you share it with (Stripe, analytics, email provider)
   - How users can request deletion
   - Your contact info

2. **Cookie Consent Banner** — Before setting non-essential cookies:
   - Must get explicit opt-in (not just "by continuing you agree")
   - Must allow granular choice (analytics yes, marketing no)
   - Must be easy to withdraw consent
   - Tools: Cookiebot (~€9/month), CookieYes (free tier), or self-built

3. **Lawful Basis for Processing** — For each type of data, you need one of:
   - **Contract**: Processing necessary to deliver the service they paid for
   - **Consent**: They explicitly agreed (email marketing, cookies)
   - **Legitimate interest**: Reasonable business purpose (fraud prevention, analytics)

4. **Data Processing Agreements (DPAs)** — Sign DPAs with every service that processes your users' data:
   - Stripe ✅ (auto-signed in their terms)
   - Vercel ✅ (DPA available)
   - Google Analytics — Problematic (see below)
   - Email providers (Resend, SendGrid) — Most have DPAs available
   - Database providers — Check their terms

5. **Right to Deletion** — When a user asks, you must delete their data within 30 days
   - Have a process (even manual) to handle this
   - Includes backups (within reasonable time)

6. **Data Breach Notification** — If breached, notify supervisory authority within 72 hours

### Google Analytics & GDPR
- Several EU countries have ruled Google Analytics violates GDPR (data transferred to US)
- **Safe alternatives**: Plausible (€9/month, EU-hosted), Fathom ($14/month), Umami (self-hosted, free)
- If you must use GA: ensure EU data stays in EU (GA4 has EU-only settings), get proper consent

### Fines
- Up to €20M or 4% of global revenue (whichever is higher)
- **In practice**: Solo founders are unlikely to face maximum fines, but complaints from EU users can trigger investigations
- First offense with good faith effort at compliance → likely a warning or small fine

## CCPA / CPRA (California)

### When It Applies
- You sell to California residents AND meet ONE of:
  - Annual gross revenue >$25M, OR
  - Buy/sell personal data of 100K+ consumers/households, OR
  - Derive 50%+ revenue from selling personal data

### For Solo Founders
- **Most solo founders don't meet these thresholds** and CCPA doesn't apply
- If you grow past $25M revenue or 100K users in California, revisit
- Good practice: include a "Do Not Sell My Information" link anyway

## UK GDPR (Post-Brexit)

- Nearly identical to EU GDPR
- Applies if you serve UK customers
- Enforced by ICO (Information Commissioner's Office)
- Same requirements: privacy policy, cookie consent, DPAs, deletion rights
- Fines: up to £17.5M or 4% of global revenue

## PIPL (China)

### When It Applies
- You process personal information of individuals in China
- You target products/services at China market

### Key Points for Solo Founders
- Consent required for almost all data processing
- Cross-border data transfer requires one of: security assessment, standard contractual clauses, or certification
- **Practical impact**: If you serve Chinese customers from outside China, technically you need a local representative
- **Reality**: Enforcement against small foreign businesses is minimal, but tightening

## PDPA (Singapore), APPI (Japan), PIPA (Korea)

- Similar principles to GDPR (consent, purpose limitation, security, deletion rights)
- Generally less strict enforcement than GDPR
- If you incorporate in Singapore: PDPA applies to data processed in Singapore
- Japan's APPI: consent for cross-border transfer; adequacy with EU exists

## Practical Compliance Checklist for Solo Founders

### Day 1 (When You Launch)
- [ ] Privacy policy page on your website
- [ ] Cookie consent banner (if using analytics/marketing cookies)
- [ ] DPAs signed with Stripe, email provider, hosting provider
- [ ] SSL/HTTPS on all pages (non-negotiable)
- [ ] Email opt-in is explicit (not pre-checked boxes)

### When You Hit 1,000 Users
- [ ] Review what data you actually collect — delete what you don't need
- [ ] Set up a process for deletion requests (even a manual email workflow)
- [ ] Ensure backups can be purged within reasonable time
- [ ] Review third-party tools for GDPR compliance

### When You Hit €10K+ EU Revenue
- [ ] Consider switching from Google Analytics to EU-hosted alternative
- [ ] Formalize your cookie consent to be GDPR-compliant (not just a dismissible banner)
- [ ] Document your data processing activities (simple spreadsheet is fine)

## Email Marketing Compliance

| Regulation | Opt-in Required? | Unsubscribe Required? | Penalties |
|-----------|-----------------|----------------------|-----------|
| GDPR (EU) | Yes, explicit | Yes, easy one-click | Up to €20M |
| CAN-SPAM (US) | No (opt-out model) | Yes, within 10 days | Up to $51K per email |
| CASL (Canada) | Yes, express consent | Yes | Up to CAD $10M |
| Spam Act (Australia) | Yes, consent or inferred | Yes | Up to AUD $2.2M per day |

**Safe approach**: Always use double opt-in and one-click unsubscribe. This satisfies all regulations globally.

## Recommended Tools

| Need | Tool | Cost | Notes |
|------|------|------|-------|
| Privacy policy generator | Iubenda | €29/year | Auto-updates for law changes |
| Cookie consent | CookieYes | Free tier | GDPR + CCPA compliant |
| Analytics (GDPR-safe) | Plausible | €9/month | EU-hosted, no cookies needed |
| Email compliance | Built into Resend/Mailchimp | Included | Unsubscribe headers automatic |
| DPA management | Manual | $0 | Download DPA from each vendor |
