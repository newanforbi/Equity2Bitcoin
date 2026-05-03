# Equity2Bitcoin

**Turning dormant home equity into Bitcoin — through a compliant, education-only consulting framework.**

[equity2bitcoin.com](https://equity2bitcoin.com) &nbsp;·&nbsp; Founded 2025 &nbsp;·&nbsp; California, USA &nbsp;·&nbsp; Brendan Ngehsi Ngwa Nforbi

---

## The Problem

American homeowners collectively hold **$17.2 trillion in tappable home equity** — an average of $299,000 per household. That capital is sitting idle, losing purchasing power to inflation every year.

At the same time, Bitcoin has matured into a recognized global asset class with ETF approval, institutional adoption, and a proven four-year halving cycle that has outperformed every major asset class in history. Yet fewer than 3% of homeowners have explored converting any portion of their equity into Bitcoin.

The gap isn't desire — it's infrastructure. Banks won't guide homeowners into Bitcoin. Financial advisers are constrained by compliance. Crypto platforms offer no help with equity extraction. **Nobody is building the bridge.**

Equity2Bitcoin builds the bridge.

---

## The Solution

Equity2Bitcoin is a **milestone-based consulting firm** that guides homeowners through a five-phase process: from understanding their HELOC options all the way to independently securing Bitcoin in self-custody.

We are **non-custodial and education-only** — we never touch client funds, arrange loans, or hold Bitcoin. We earn a single 30% success fee, triggered only when a client's home equity loan is verified and funded. All other phases are free.

```
Phase 1 — Equity Profile Review & Education        No fee
Phase 2 — Loan Preparation & Documentation         No fee
Phase 3 — Loan Approval & Funding           ← 30% fee (this phase only)
Phase 4 — Bitcoin Integration & Custody Education  No fee
Phase 5 — Verification & Documentation            No fee
```

**Example:** A homeowner with a $700K home and $400K mortgage extracts $300K via HELOC. Equity2Bitcoin earns a $90,000 consulting fee. The client independently acquires 3–5 BTC in self-custody and retains full ownership of their home.

---

## Business Model

| Year | Clients | Avg. HELOC | Revenue (30%) |
|------|---------|------------|---------------|
| 2026 | 25      | $300,000   | $2.25M        |
| 2027 | 100     | $300,000   | $9M           |
| 2028 | 250     | $350,000   | $26.25M       |

- **Gross margin: ~98%** — overhead is a lean tech stack and part-time contractors
- **Break-even: 1 client** — fixed costs are negligible relative to per-client revenue
- **No regulatory exposure** to the Investment Advisers Act, California DFPI MLO licensing, or Money Transmission laws — the milestone fee is tied to a service event, not investment performance

---

## Market Opportunity

| Metric | Figure | Source |
|--------|--------|--------|
| U.S. tappable home equity | $17.2T | CoreLogic, Q3 2025 |
| Avg. tappable equity per homeowner | $299,000 | Federal Reserve, 2025 |
| Bitcoin adoption among homeowners | <3% | NYDIG / Morning Consult, 2024 |
| New HELOCs opened (12 months to mid-2024) | 1.2M+ | CFPB, 2024 |
| Bitcoin market cap | $2.25T | CoinMetrics, Oct 2025 |

A **0.1% penetration** of total U.S. tappable equity redirected through Equity2Bitcoin's consulting model represents **$17 billion in conversion volume**.

---

## Why Now

Three forces are converging in 2025–2027:

1. **Post-halving bull cycle** — Bitcoin's April 2024 halving historically precedes 12–24 months of strong price appreciation. Homeowners who position now are early.
2. **Record home equity** — Average home values climbed 142% from 2020–2025, giving millions of middle-class Americans more extractable equity than ever.
3. **Regulatory clarity** — The 2025 GENIUS Act and updated CFPB guidance created a defined compliance perimeter for non-custodial educational consultants.

---

## Regulatory Positioning

Equity2Bitcoin is specifically structured to operate outside the regulatory perimeter of financial services law:

| Domain | Law | Safe Harbor Applied |
|--------|-----|---------------------|
| Investment advice | Investment Advisers Act of 1940 | Publisher's exemption — general education, not tailored advice |
| Loan brokerage | CA Fin. Code §50000 (MLO) | Non-broker, non-arranger — clients apply directly with licensed lenders |
| Money transmission | FinCEN / FinCEN MTL | No custody or facilitation of value transfer |
| Consumer protection | 12 CFR 1008 (CFPB) | Full disclosure; fee not contingent on loan closure or investment outcome |
| Tax reporting | IRC §6041 | Standard milestone income; structured invoices |

---

## Website

The `index.html` in this repository is the production landing page for [equity2bitcoin.com](https://equity2bitcoin.com).

**Stack:** Pure HTML, CSS, and vanilla JavaScript — zero dependencies, zero build step. Fast, auditable, and deployable anywhere in seconds.

**Design system:**
- Colors: Navy `#0d1b2a` + Gold `#f5a623` (matches brand logo)
- Typography: Playfair Display (headings) + Inter (body)
- Fully responsive — mobile-first sticky booking bar

**Conversion flow:**
1. Hero → pain-point framing → trust signals
2. Five-phase process explained in client-benefit language
3. Worked financial example (show, don't just tell)
4. FAQ handling objections (volatility, legality, fees)
5. Multi-step booking form (qualifies lead + captures preferred call time)

---

## Deploy

### GitHub Pages

Pages are auto-deployed from `main` via GitHub Actions (`.github/workflows/pages.yml`).

To enable in your repo:
1. Go to **Settings → Pages**
2. Set **Source** to `GitHub Actions`
3. Push to `main` — the workflow handles the rest

For a custom domain, the `CNAME` file is already set to `equity2bitcoin.com`. Point your DNS:
```
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  newanforbi.github.io
```

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/newanforbi/Equity2Bitcoin)

Or manually:
1. Connect repo in [app.netlify.com](https://app.netlify.com)
2. Publish directory: `.` (repo root)
3. Build command: *(leave blank)*
4. Deploy — `netlify.toml` handles headers, caching, and redirects automatically

To set a custom domain in Netlify: **Site Settings → Domain Management → Add custom domain → equity2bitcoin.com**

### Local Development

```bash
git clone https://github.com/newanforbi/Equity2Bitcoin.git
cd Equity2Bitcoin
open index.html          # macOS
# or
python3 -m http.server   # any OS, then visit http://localhost:8000
```

---

## Roadmap

| Phase | Timeline | Focus |
|-------|----------|-------|
| Pilot | 2026 | California launch, 25 clients, refine funnel |
| Regional | 2027 | 10–15 states via certified affiliate consultants, 100 clients |
| National | 2028 | Equity2Bitcoin Academy launch, 250+ clients, $26M+ revenue |
| Exit / Scale | 2029+ | Institutional adoption, acquisition, or licensing model |

---

## Contact

**Brendan Ngehsi Ngwa Nforbi** — Founder & Lead Consultant  
[info@equity2bitcoin.com](mailto:info@equity2bitcoin.com)  
[equity2bitcoin.com](https://equity2bitcoin.com)

---

*For educational purposes only. Equity2Bitcoin Consulting LLC does not provide financial, investment, tax, or legal advice. All content is general education. Clients retain sole discretion over all financial decisions. Bitcoin is highly volatile. Past performance does not guarantee future results.*
