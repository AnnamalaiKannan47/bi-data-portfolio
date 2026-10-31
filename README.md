# Annamalai Kannan | BI & Data Portfolio

**Junior BI Developer at TRENDS · New Zealand**

I work with Power BI, Azure Databricks, SQL, DAX and SYSPRO ERP to develop reporting and financial data models. This portfolio documents real-world problems, technical decisions, reconciliation methods and the limits of the resulting solutions.

## Technical skills

| Area | Technologies and focus |
|---|---|
| Business intelligence | Power BI, DAX, semantic modelling, interactive reporting |
| Data platforms | Azure Databricks, SQL, lakehouse reporting data |
| ERP and finance | SYSPRO ERP, financial data modelling, fiscal-period alignment, reconciliation |
| Analytical methods | Historical balance reconstruction, multi-currency reporting, validation |

## Featured case study

### [AP Supplier Overview](finance/ap-supplier-overview/README.md)

**Reconstructing historical accounts payable balances in Power BI**

Starting from current supplier balances and transaction history, I designed a roll-back method to reconstruct past period-end positions. The case study explains fact-table grain, fiscal-period alignment, movement classification, exchange-rate treatment and reconciliation against SYSPRO.

- **My contribution:** investigation, method design, semantic model, report and validation.
- **Existing foundation:** AP ingestion and curated lakehouse views supplied by the data engineering team.
- **Outcome:** a production report supporting historical balances from 2023 onward.
- **Validation scope:** tested suppliers and company totals across the current and two prior periods; older periods were not independently reconciled against SYSPRO.

[Read the case study](finance/ap-supplier-overview/README.md) · [Download PDF](finance/ap-supplier-overview/AP-Supplier-Overview.pdf?raw=true)

## Project portfolio

| Category | Published case studies |
|---|---|
| [Finance](finance/README.md) | [AP Supplier Overview](finance/ap-supplier-overview/README.md) |
| [Sales](sales/README.md) | No case studies published yet |
| [Product](product/README.md) | No case studies published yet |
| [Operations](operations/README.md) | No case studies published yet |

## About these case studies

The AP case study is published with employer permission. It describes methodology using fictional financial examples and generic model labels. Production code, business records and confidential datasets are excluded.

Claims, validation limits and possible future improvements are identified in the case study. Future ideas are not presented as delivered work.

## Portfolio organisation

Each project has its own folder, a full case study in `README.md`, and an optional downloadable PDF. The [project template](templates/project-template.md) provides a consistent starting point for future additions.
