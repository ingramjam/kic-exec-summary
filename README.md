# KIC Executive Summary Dashboard

This project is a modern, animated landing page for presenting the executive summary and key performance data for Kick It California (KIC).

## Features
- Infographic cards and animated charts (Chart.js)
- Responsive, mobile-friendly layout (Tailwind CSS)
- Easy-to-update data via a single JSON file

## How to Use
1. Update the data in `data.json` with the latest annual figures.
2. Open `ExecSummaryLandingPage.html` in your browser to view the dashboard.

## Data Update Example
Edit `data.json`:
```json
{
  "clientsEnrolled": 8615,
  "quitKits": 22610,
  "adImpressions": 1500000,
  "satisfaction": 87,
  "proxiesSatisfaction": 86,
  "quitAttempt": 80,
  "abstinence": 37,
  "appRecommend": 94,
  "smokerSatisfaction": 93,
  "vaperSatisfaction": 73,
  "websiteUsers": 67878,
  "referrals": 11689,
  "enrolled": 3337,
  "counselingCompleted": 2339,
  "textService": 2719,
  "appInstalls": 1783
}
```

## Tech Stack
- HTML, Tailwind CSS
- Chart.js
- JSON for data

## License
MIT
