# SupeRR Selector Season 2 · Pressure Dashboard

Static competition submission dashboard for Round 1. It presents the selected batter and bowler list, pressure evidence, methodology, and conditional RR 2027 release scenarios.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8765` from this directory and visit `http://127.0.0.1:8765`.

## Deploy on Vercel

Import this repository in Vercel as a static site with no build command and the repository root as the output directory. The site consists of `index.html`, `data.js`, and `report.pdf`.

The dashboard contains selected-candidate summary metrics for the competition submission. It does not contain the raw challenge CSV pack. 2027 availability, auction eligibility, age and uncapped status must be verified against official lists.
