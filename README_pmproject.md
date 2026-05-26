# Marmara–UNICEF Child Health Tracking Platform
### Demo Prototype — PM Project

A functional demo/prototype web application for the UNICEF–Marmara University digital child health tracking platform project.

---

## Live Demo

**[View Demo →](https://leylashikzaman.github.io/unicef-marmara-demo/)**

---

## About

This demo represents the functional prototype of the UNICEF–Marmara University digital health tracking platform. It demonstrates:

- **Field worker mobile interface** — Used by UNICEF field workers in camps to collect child health data
- **Medical dashboard** — Used by Marmara University healthcare professionals to monitor cases, alerts, and interventions
- **Automated alert system** — Flags high-risk children based on vaccination and nutritional status
- **Offline sync simulation** — Demonstrates data collection in low-connectivity field environments

### Demo Credentials
| Role | Username | Password |
|------|----------|----------|
| Field Worker | `fieldworker01` | any |
| Medical Staff | `medstaff01` | any |
| Admin | `admin01` | any |

---

## Screens Implemented

| # | Screen | Description |
|---|--------|-------------|
| 1 | Login Page | Role-based access (Field Worker / Medical Staff / Admin) |
| 2 | Field Worker Home | Operational dashboard for field workers |
| 3 | Children Registry | Searchable/filterable list of 50 child records |
| 4 | Child Profile | Full health record with visit history and action buttons |
| 5 | Add Child Form | Data entry form with automated alert rules |
| 6 | Alerts Page | High-risk cases with filter and intervention actions |
| 7 | Medical Dashboard | Charts, KPIs, and statistics for medical staff |
| 8 | Sync / Offline | Demonstrates offline data entry and sync flow |

---

## Dataset

The demo uses hardcoded data reflecting the Excel dataset from the project:

- **50 child records** across 5 cities (Elazig, Sanliurfa, Adana, Mersin, Manisa)
- **30 visit records** with dates, vaccination status, and field notes
- Metrics: 28 alerts, 22 complete vaccinations, 9 severe malnutrition cases, 14 pending interventions

---

## Run Locally

No installation required. Just open:

```
index.html
```

in any modern browser (Chrome, Firefox, Safari, Edge).

---

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — No framework dependencies
- **Chart.js** (CDN) — Dashboard charts
- **Google Fonts** (CDN) — Roboto typeface (UNICEF standard)
- All data is embedded in `data/children.js` — no backend needed

---

## File Structure

```
unicef-marmara-demo/
├── index.html          ← Main application (all 8 screens)
├── data/
│   └── children.js     ← 50 children + 30 visit records
└── README.md
```

---

## Demo Scenario (for presentation)

1. Login as **Field Worker**
2. Go to **Children** → find Child C-1001
3. See the **High Risk Alert** banner on the profile
4. Click **Update Vaccination** or **Add Field Visit**
5. Go to **Alerts** page — see all 28 flagged cases
6. Switch to **Medical Dashboard** — view charts and KPIs
7. Go to **Sync / Offline** → click **Simulate Offline** → then **Sync Now**

---

## Project Context

- **Partner Organizations:** UNICEF Turkey & Marmara University
- **Target Users:** Field health workers, Marmara University medical residents, project managers
- **Purpose:** Child health record creation, vaccination tracking, nutrition monitoring, risk alert generation
- **Field Conditions:** Designed for low-connectivity environments with offline-first data entry

---

*PM Project Demo — Marmara University · 2025*
