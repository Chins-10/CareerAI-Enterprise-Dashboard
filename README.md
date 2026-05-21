# CareerAI — Enterprise Admin Dashboard

**Role:** Product Manager  
**Timeline:** April 2026 – Present  
**Platform:** AI-powered job search platform  
**Live dashboard:** [View on GitHub Pages](https://github.com/Chins-10/CareerAI-Enterprise-Dashboard/settings/pages) 
**Live product:** [CareerAI](https://www.careerai.io/)

---

## Overview

This repository contains the enterprise admin dashboard I designed and built for 
CareerAI's B2B product — enabling university career centers and bootcamp administrators 
to manage student accounts, track job search progress, monitor interview prep performance, 
and view placement outcomes across cohorts in real time.

The dashboard was designed as part of a B2B growth opportunity I identified during 
competitive research — targeting bootcamps and career centers as institutional clients 
with a platform licensing model.

---

## Two scenarios covered

### 🎓 University (e.g. UT Arlington)
- 240 seat license
- Multiple cohorts — Computer Science, Data Science, Business Analytics
- Student onboarding funnel tracking from invite → offer
- Application pipeline across all students
- Interview prep leaderboard by cohort

### 💻 Bootcamp (e.g. Code Academy)
- 80 seat license
- Cohort-based tracking — Full Stack Web Dev, UX/UI Design
- Higher interview rate (44%) due to focused job search
- Faster placement timeline than university cohort

---

## Features

| Feature | Description |
|---|---|
| **KPI cards** | Total students, applications sent, interviews scheduled, offers received |
| **Onboarding funnel** | 7-step flow from invite sent → offer received with completion percentages |
| **Student progress table** | Per-student status, application count, and progress bar |
| **Application pipeline** | Applied → Interviewing → Final round → Offer with live counts |
| **Cohort management** | Progress tracking per cohort with completion rates |
| **Interview prep leaderboard** | Ranked by sessions completed and performance score |
| **Activity feed** | Real-time events — offers received, interviews scheduled, onboarding completions |
| **Org switcher** | Toggle between University and Bootcamp scenarios instantly |

---

## Design decisions

The dashboard was designed with a premium dark UI to feel like a professional 
SaaS admin tool — not a generic report. Key design choices:

- **Dark sidebar** — deep navy with subtle borders, feels native to enterprise tools
- **Colour-coded KPI cards** — each metric has a unique accent colour and icon
- **Coloured top accent bars** — blue, purple, pink, green — each matching the metric meaning
- **7-step onboarding funnel** — shows exactly where students drop off in the sign-up flow
- **Progress bars throughout** — instant visual scan of completion rates
- **Numbered leaderboard** — ranked interview prep performance per student
- **Two-scenario toggle** — university and bootcamp switch instantly with all data updating

---

## B2B product context

This dashboard was scoped as part of a larger B2B opportunity I identified during 
competitive research. The full B2B feature set includes:

- Platform license model — institution pays per seat, not per student
- Bulk student account creation via CSV upload
- Dedicated student onboarding flow branded per institution
- Super admin sign-up and cohort management
- Real-time progress dashboard — this repository
- Frontend deployed on Netlify with continuous deployment pipeline

---

## Repository structure
---

## How to view

**Option 1 — Live interactive version:**  
👉 [View on GitHub Pages](https://chins-10.github.io/CareerAI-Enterprise-Dashboard/))

**Option 2 — Run locally:**
```bash
git clone https://github.com/Chins-10/careerai-enterprise-dashboard
cd careerai-enterprise-dashboard
open index.html
```

---

## Skills demonstrated

| Skill | How it shows |
|---|---|
| Product thinking | Identified B2B opportunity from competitive research |
| User research | Designed for admin user needs — fast scanning, clear hierarchy |
| UX design | Dark premium UI with clear visual hierarchy and hover states |
| Data visualization | Pipeline, progress bars, funnel, leaderboard |
| Frontend build | HTML, CSS, JavaScript — no frameworks, no dependencies |
| Deployment | GitHub Pages with continuous deployment |

---

## Related repositories

| Repository | Description |
|---|---|
| [careerai-competitive-analysis](https://github.com/Chins-10/careerai-competitive-analysis) | Full research documents and raw data |
| [careerai-stakeholder-report](https://github.com/Chins-10/careerai-stakeholder-report) | Pre-sprint stakeholder strategy document |

---
