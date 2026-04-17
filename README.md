<div align="center">

<img src="assets/banner-arch.jpg" alt="Panrise Solo — 3-layer architecture" width="720">

# Panrise Solo

**Need compliance advice for your one-person company? Get AI to guide you.**

Use [Claude](https://claude.ai) with this skill to get jurisdiction-specific advice with real numbers — costs, tax rates, timelines, banking options — instead of generic answers. Describe your situation, and Claude becomes your compliance advisor.

- **No legal background needed** — just describe your nationality, business, and revenue
- **Iterate quickly** — ask follow-up questions about payments, tax, forex, or visas
- **Actionable output** — specific costs, setup steps, compliance calendars, and warnings

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Claude](https://img.shields.io/badge/Claude-Skill-orange)
![Languages](https://img.shields.io/badge/languages-7-brightgreen)
![Knowledge](https://img.shields.io/badge/knowledge-5%2C900%2B_lines-yellow)

</div>

## 🚀 Quick Start (3 Steps)

### Step 1: Install the Skill

**Option A: Claude.ai (Pro/Max/Team/Enterprise)**

1. Download [`panrise.zip`](panrise.zip)
2. Go to [claude.ai](https://claude.ai) → **Settings** → **Capabilities** → **Skills**
3. Click **+ Add** and upload the zip file
4. Toggle the skill on

**Option B: Claude Code CLI**

```bash
git clone https://github.com/ar-gen-tin/panrise.git ~/.claude/skills/panrise
```

### Step 2: Describe Your Situation

Just tell Claude who you are and what you need:

```
I'm an Indian software developer doing $60K/year freelancing for US clients.
Should I get a Wyoming LLC?
```

Or in any supported language:

```
我是大陆开发者，做SaaS卖给全球客户，年收入$120K，应该在哪里注册公司？
```

### Step 3: Get Your Compliance Plan

Claude will respond with a structured plan including:
- **Recommended structure** — which entity and where
- **Setup steps** — numbered list with timeline and costs
- **Banking & payments** — recommended stack
- **Tax obligations** — what you'll owe and where
- **Compliance calendar** — annual deadlines
- **Watch out for** — common traps for your profile

Then iterate — ask about payments, forex, VAT, contractors, or anything else.

---

## 📋 Example Consultations

See complete example outputs in the [`examples/`](examples/) directory:

- **[Chinese SaaS founder](examples/chinese-saas-founder.md)** — HK Ltd pathway, forex controls, CRS enforcement
- **[Indian freelancer](examples/indian-freelancer-us-llc.md)** — Wyoming LLC, FEMA/LRS compliance, Form 5472 trap

### Example Prompts for Common Scenarios

**Solo SaaS founder:**
```
I'm a Korean developer with a SaaS product earning $80K/year.
Customers are mostly in the US. Where should I incorporate?
```

**Digital nomad:**
```
I'm a US citizen living in Lisbon, earning $150K from consulting.
How do I avoid CFC traps? What about Portugal's tax regime?
```

**Freelancer going global:**
```
I'm a Japanese freelance designer. My clients are in Europe.
Do I need to register for EU VAT?
```

---

## 🌍 Coverage

**13 knowledge domains** · **5,900+ lines** · **15 reference files**

| Domain | What You Get |
|--------|-------------|
| Jurisdiction Selection | Decision tree for 8+ jurisdictions (US LLC, HK Ltd, SG, Estonia, UK, Dubai) |
| Tax Optimization | Legal strategies, Flag Theory, crypto taxation, transfer pricing |
| Tax Residency | 183-day rule, exit tax, treaty tie-breakers, split tax year |
| Forex Controls | 11 countries (India $250K LRS, Brazil, Taiwan, Korea, Japan) |
| Payments & Banking | Mercury / Wise / ZA Bank / Airwallex + 3-layer redundancy architecture |
| VAT/GST | EU OSS, digital services tax, Merchant of Record strategy |
| Compliance Operations | Form 5472 deep dive, Q1-Q4 calendar, 72-hour emergency protocol |
| Hiring Contractors | Contractor vs employee, EOR (Deel/Remote), IP assignment |
| Data Compliance | GDPR, CCPA, cookie consent, privacy tools |
| IP & Trademark | Madrid Protocol, domain strategy, open source licenses |
| Cost Comparison | Year 1 total cost for 8 jurisdictions with ROI calculation |
| Tax Treaties | DTA routes, WHT rates, US-UK/SG/PT treaty examples |
| Company Structures | Single entity, dual entity, nomad patterns, exit planning |

**Nationality-specific handling for:**

🇭🇰 Hong Kong · 🇮🇳 India · 🇺🇸 US Citizens · 🇯🇵 Japan · 🇸🇬 Singapore · 🇰🇷 Korea · 🇧🇷 Brazil · 🇪🇺 EU/UK

---

## 🏗 Architecture

3-layer progressive loading — Claude reads only what's needed, not everything at once.

```
L0: SKILL.md (~300 lines)        Always loaded. Decision logic + nationality routing.
L1: INDEX.md (~60 lines)         Loaded first. Summary index + key numbers.
L2: references/ (~4,000 lines)   On demand. 2-3 files per consultation, routed by nationality.
```

```
panrise/
├── SKILL.md                     # Decision logic, user profiling, routing
├── panrise.zip                  # One-click install for Claude.ai
├── references/                  # 15 deep-dive knowledge files
│   ├── INDEX.md                 # Quick lookup + cross-reference map
│   ├── solo-structures.md       # 820 lines — entity types, formation services, exit planning
│   ├── payments-banking.md      # 539 lines — banking comparison, redundancy, insurance
│   ├── tax-residency.md         # 465 lines — residency rules, exit tax, treaty tie-breakers
│   ├── forex-controls.md        # 459 lines — 11 countries, CRS response, bank compliance
│   ├── compliance-operations.md # 266 lines — calendars, Form 5472, 72-hour protocol
│   ├── vat-gst.md               # 267 lines — EU/UK/AU/SG/JP VAT + digital services tax
│   ├── tax-optimization.md      # 256 lines — strategies, crypto, transfer pricing
│   ├── tax-treaties.md          # 154 lines — DTA routes, treaty examples
│   └── ...                      # + 6 more reference files
├── i18n/                        # 6 language translations
│   ├── SKILL.zh.md / .ja.md / .ko.md / .fr.md / .de.md / .es.md
├── examples/                    # Sample consultation outputs
├── assets/                      # Banner images
├── .github/                     # CI + issue/PR templates
├── CONTRIBUTING.md
└── LICENSE (MIT)
```

## 🌐 Languages

7 languages — auto-detects and responds in the user's language:

English · 中文 · 日本語 · 한국어 · Français · Deutsch · Español

## 📊 Quality

- **71 scenarios** stress-tested across 10 categories
- **94% pass rate** (67 of 71 scenarios)
- **Web-search verified** against 2025-2026 policy changes (UAE 5% PIT, FEIE $132.9K, India TCS ₹10L)
- **Competitive benchmark**: absorbed [Global Solo](https://www.globalsolo.global/) content (64 blog posts)

## ⚠️ Data Freshness

Tax rates, visa policies, and forex limits change. The knowledge base reflects **2025-2026 rules**. For amounts >$100K or life-changing decisions, verify current rules with a qualified tax advisor.

## 🤝 Contributing

Found outdated info? Know a better jurisdiction strategy? PRs welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

Priority areas:
- Updated tax rates and visa policies
- More nationality-specific guides
- Company exit/closure procedures
- Real-world cost corrections

## 📄 License

MIT — Free to use, modify, and distribute.

---

**Website:** [panrise-website-ivory.vercel.app](https://panrise-website-ivory.vercel.app)

Made by [ar-gen-tin](https://github.com/ar-gen-tin) · [REWIRED](https://github.com/rewired-hq)
