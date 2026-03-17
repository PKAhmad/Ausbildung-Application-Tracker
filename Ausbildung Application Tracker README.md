# 📋 Application Tracker

A simple single-file web app to track job and Ausbildung applications. No installation needed — just open `index.html` in your browser.

## Features

- Add applications with Company, City, Position and Date
- Status starts as **Sent** automatically — change it to **Interview** or **Rejected** directly in the table
- Counters update live (Total, Sent, Interview, Rejected)
- Import data from `.xlsx`, `.xls` or `.csv`
- Export all data to Excel
- Data saves in the browser — still there next time you open the file

## Import Format

First row = header (skipped). Columns must be in this order:

| Company | City | Position | Status | Date |
|---|---|---|---|---|
| Bosch GmbH | Essen | Systemintegration | Sent | 17.03.2026 |

## Tech

HTML · CSS · JavaScript · [SheetJS](https://sheetjs.com) (Excel import)

## Author

**Kamran Ahmad Darwishzada** — built to track my own Ausbildung applications across different cities in Germany.
