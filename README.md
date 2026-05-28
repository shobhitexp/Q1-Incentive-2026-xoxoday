# Q1 2026 — India Sales Incentive Portal

A secure, role-based HTML dashboard for viewing Q1 2026 sales incentive calculations for the India Sales Team at Xoxoday.

---

## 🚀 Live Access

Open `index.html` in any browser or visit the hosted GitHub Pages URL.  
Every user must log in with their assigned credentials to view data.

---

## 🔐 Access Roles

| Role | Access Level |
|------|-------------|
| **IC** | Own incentive data only |
| **Manager** | Own data + full team view (all ICs under them) |
| **Admin** | Full access to all POCs, all managers, org-wide totals |

> **Special Access:** Zoya Bilgrami can view 5 designated managers and their ICs.

---

## 📊 What Each POC Dashboard Shows

1. **Hero Card** — Final incentive (USD/INR), Hunting/Farming tag, team, manager, eligibility
2. **Calculation Flow** — 8-step visual: N+C+R → +0.5% Bonus → −Refunds → Net → ×Ridder → +Extras → +OND → Final
3. **N / C / R Breakdown** — New (10%), Cross-sell (7.5%), Regular (0.5%)
4. **Deductions & Additions** — Cash refund, Points refund, New account bonus, Cross-sell bonus, Manager incentive, Trader incentive, OND Remaining
5. **Ridder Slab** — Visual slab indicator (Hunting: 10 slabs / Farming: 6 slabs)
6. **Manager Section** — Team pool, target/actuals, ridder %, team POC chips, team traders
7. **Own Accounts (Managers)** — N/C/R per parent company, or "No account allotted"
8. **Parent Company Drill-Down** — Full table with N/C/R incentive per company

---

## 💱 Currency Toggle

USD ↔ INR switch in the top bar. Conversion rate: **$1 = ₹90**  
Toggles all values across the entire dashboard instantly.

---

## 🔑 Key Terminology

| Term | Meaning |
|------|---------|
| **N** | New Business — company billed first time within last 365 days |
| **C** | Cross-sell Business |
| **R** | Regular / Renewal Business |
| **NCR Tagging** | Classifying every line item as N, C, or R |
| **SaaS / Stores / NetRev** | Three revenue components |
| **Ridder** | Target vs Actual achievement multiplier |
| **OND** | Oct-Nov-Dec 2025 remaining/leftover incentive |
| **Trader** | Carved-out accounts not included in Ridder calculation |
| **MIB** | Money in Bank |
| **FP Check** | First Payment check |

---

## 🛡️ Security

- Login required — no data visible without credentials
- Role-based filtering — backend data scoped per user
- Right-click, View Source, DevTools, Ctrl+S all blocked
- Copy disabled for non-Admin users
- Source Excel files are password-encrypted separately

---

## 📁 File Structure

```
Q1-Sales-Incentive/
├── index.html          ← The full portal (single-file, self-contained)
└── README.md           ← This file
```

---

## ⚙️ Deployment

Already hosted via **GitHub Pages**. To redeploy with updated data:

1. Generate a new `index.html` from the updated Excel file
2. Replace `index.html` in this repo
3. Commit & push — GitHub Pages auto-deploys in ~1 minute

---

## 📬 Contact

For access requests, data queries, or issues:

**Shobhit Raj** — Artifact Maker & Data Administrator

---

> ⚠️ This repository contains sensitive compensation data. Keep it **Private** at all times.
