# Annamalai Kannan | BI & Data Portfolio

**Junior BI Analyst at TRENDS (Tuapeka Gold Print) · New Zealand**

I work with Power BI, Azure Databricks, SQL, DAX and SYSPRO ERP to develop reporting and financial data models. This portfolio documents real-world problems, technical decisions, reconciliation methods and the limits of the resulting solutions.

## Technical skills

| Area | Technologies and focus |
|---|---|
| Business intelligence | Power BI, DAX, semantic modelling, interactive reporting |
| Data platforms | Azure Databricks, SQL, lakehouse reporting data |
| ERP and finance | SYSPRO ERP, financial data modelling, fiscal-period alignment, reconciliation |
| Analytical methods | Historical balance reconstruction, multi-currency reporting, validation |

## Featured case studies

### [AP Supplier Overview](finance/ap-supplier-overview/README.md)

**Reconstructing historical accounts payable balances in Power BI**

Starting from current supplier balances and transaction history, I designed a roll-back method to reconstruct past period-end positions. The case study explains fact-table grain, fiscal-period alignment, movement classification, exchange-rate treatment and reconciliation against SYSPRO.

- **My contribution:** investigation, method design, semantic model, report and validation.
- **Existing foundation:** AP ingestion and curated lakehouse views supplied by the data engineering team.
- **Outcome:** a production report supporting historical balances from 2023 onward.
- **Validation scope:** tested suppliers and company totals across the current and two prior periods; older periods were not independently reconciled against SYSPRO.

[Read the case study](finance/ap-supplier-overview/README.md) · [Download PDF](finance/ap-supplier-overview/AP-Supplier-Overview.pdf?raw=true)

### [AR Customer Overview](finance/ar-customer-overview/README.md)

**Historical accounts receivable balances at the ERP's entry rate**

I reused the AP roll-back method for receivables, then solved two problems specific to AR: a lakehouse defect that merged adjustment lines, which I traced and the data engineering team fixed at source, and receipts held at the wrong exchange rate, which I corrected by rebuilding SYSPRO's entry-rate valuation in the model, including a separate rule for unapplied cash.

- **My contribution:** investigation, diagnosis, method, semantic model, report and validation.
- **Existing foundation:** AR ingestion and curated lakehouse views owned by the data engineering team.
- **Outcome:** a production report used by Finance and the executive team, with balances for any fiscal period and filtering by customer payment terms.
- **Validation scope:** five customers across the current and two prior periods, matched to SYSPRO within line-level rounding in both currencies; older periods were not independently reconciled against SYSPRO.

[Read the case study](finance/ar-customer-overview/README.md) · [Download PDF](finance/ar-customer-overview/AR-Customer-Overview.pdf?raw=true)

## Project portfolio

| Category | Published case studies |
|---|---|
| [Finance](finance/README.md) | [AP Supplier Overview](finance/ap-supplier-overview/README.md) · [AR Customer Overview](finance/ar-customer-overview/README.md) |
| [Sales](sales/README.md) | No case studies published yet |
| [Product](product/README.md) | No case studies published yet |
| [Operations](operations/README.md) | No case studies published yet |

## About these case studies

The AP and AR case studies are published with employer permission. They describe methodology using fictional financial examples and generic model labels. Production code, business records and confidential datasets are excluded.

Claims, validation limits and possible future improvements are identified in each case study. Future ideas are not presented as delivered work.

## Portfolio organisation

Each project has its own folder, a full case study in `README.md`, and an optional downloadable PDF. The [project template](templates/project-template.md) provides a consistent starting point for future additions.
