# ETABS-Analysis-Automation (ETABSauto)

ETABS automation: intelligent modeling, optimization, and design verification of reinforced-concrete buildings.

[![Launch Web App](https://img.shields.io/badge/Execute-Web%20App-0078D4?style=for-the-badge)](https://script.google.com/macros/s/AKfycbwP639tNpJjFcSv-pTBfLZEUVEqnLCp0Dq5cu-XExDmosBLkoetQaqKS4kLYwq9AhTD/exec)
[![Download EXE](https://img.shields.io/badge/Download-Desktop%20App%20(.exe)-555?style=for-the-badge)](https://github.com/mrbkarimi/ETABS-Analysis-Automation/releases/latest)
[![Documentation](https://img.shields.io/badge/Docs-Technical%20Report-059669?style=for-the-badge)](https://mrbkarimi.github.io/ETABS-Analysis-Automation/)

## Run ETABSauto from the browser

ETABSauto has a web interface for automatic modelling, loading, analysis, design and optimisation of reinforced-concrete buildings in ETABS. It also generates a full report.

**How it works**

1. **Web app (browser):** you set up the model and the jobs here, and you view the results here.
2. **Connector (your PC):** a small program on the Windows PC where ETABS is installed. It takes the jobs from the web app and runs them in your local ETABS through the ETABS API. Nothing is computed in the cloud. ETABS stays on your machine, under your own licence.

**Quick start**

1. Open the [web app](https://mrbkarimi.github.io/ETABS-Analysis-Automation/app/) and sign in.
2. Go to the **Download** tab and install the connector on the PC that runs ETABS.
3. Go to the **Setup** tab, copy your *workspace key* and paste it into `connector_config.json` on that PC.
4. Start the connector. The status should change to **Connector online**.
5. Run the workflow: Modeling → Analysis & Design → Optimization Engine → Reinforcement Detailing → PMM Verification → Reports.

> **Security:** the workspace key lets anyone run jobs on your PC's ETABS and see the results. Keep it private. Never commit it, and never post it in issues or screenshots.

## Requirements

- Windows 10/11
- Licensed ETABS (v19–v22; tested with v21.2.0)

## Desktop version

The standalone desktop executable is still available under [Releases](https://github.com/mrbkarimi/ETABS-Analysis-Automation/releases/latest).

## Documentation

The full technical report is at **https://mrbkarimi.github.io/ETABS-Analysis-Automation/**.
