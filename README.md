# CapSim — Salary Cap & Roster Scenario Model


**Author:** John Liakakos
**Contact:** [jliakakos34@icloud.com] | https://www.linkedin.com/in/john-liakakos


## Objective


CapSim is a practical, spreadsheet-first toolkit to model multi-year salary cap scenarios, quantify the impact of signings/trades/buyouts, and produce executive-ready scenario memos for roster decisions.


## What this answers
- What is the cap impact of re-signing or trading Player X over 1–3 years?
- Which scenarios improve short-term competitiveness vs long-term cap flexibility?
- What tradeoffs exist when using LTIR, buyouts, or long-term contracts?


## Key outputs
- `models/CapModel.xlsx` — primary Excel model (template).
- `reports/scenario_memo.pdf` — 2-page memo with 3 recommended scenarios.
- `scripts/` — optional Python scripts to run batch simulations.


## Methods & approach
- Spreadsheet modeling with clear input tabs and scenario toggles.
- Conservative assumptions called out in the memo.
- Sensitivity analysis for key variables (term length, AAV, bonuses).


## Quickstart


Requirements: Excel (or LibreOffice) + optional Python env.


1. Download `models/CapModel.xlsx`.
2. Populate `Inputs` tab with roster & contract data.
3. Use `Scenario` tab to toggle trade/sign options and view outputs on `Summary` charts.
