# SQL Data Analytics — EDA & Reports (Gold layer) 📊

🔖 Quick overview
This repo contains the EDA and reporting artifacts produced from the Gold layer (business-ready tables/views). It's tuned for fast inspection by analysts — final report outputs are already exported as CSVs.

📚 Table of contents
- ▶ Purpose
- ▶ What’s included
- ▶ Quick view (open CSV)
- ▶ Reproduce reports (run SQL)
- ▶ Run locally (optional)
- ▶ Notes, license & contact

✨ Purpose
- Explore and summarise business-ready (Gold) data for analysis and reporting.
- Exported report CSVs (ready-to-open):
  - 📄 `datasets/csv-files/gold.report_customers.csv` — customer report
  - 📄 `datasets/csv-files/gold.report_products.csv` — product report

📦 What’s included
- 🧾 `datasets/csv-files/` — sample CSVs and exported reports
- 🧪 `scripts/` — numbered SQL scripts (see `12_report_customers.sql` and `13_report_products.sql` for report generation)
- 🗂️ `docs/` — roadmap, architecture diagrams and supporting notes

👀 Quick ways to view the reports
- Open the CSVs with Excel, LibreOffice, VS Code or any CSV viewer — no setup required.

⚙️ Reproduce the reports (run SQL)
- If you prefer to re-run the SQL that produced the CSVs, run the scripts:
  - `scripts/12_report_customers.sql` (generates the customers report)
  - `scripts/13_report_products.sql` (generates the products report)

🧰 Run locally (optional)
- Load CSVs into a local DB (SQLite, DuckDB, Postgres) and run the scripts against the Gold tables/views.
- Or use DuckDB for a zero-setup, fast local run (DuckDB can read CSVs directly).

💡 Notes
- This README focuses on analytics/EDA and final report outputs. For ETL, modeling, and pipeline details check `docs/`.

📜 License & contact
- 🛡️ MIT — see `LICENSE`
- 👤 Maintained by Yitbarek Tesfaye — https://linkedin.com/in/yitbarektesfaye

---
If you want, I can: add a one-click PowerShell script to import CSVs into SQLite/DuckDB and run a chosen script, or add small badges and a visual roadmap image at the top — tell me which you'd prefer.