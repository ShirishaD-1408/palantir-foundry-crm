## CRM Datasets

This project uses two CSV datasets provided as part of the CRM use case.

### 1. crm_company_source_data.csv
Primary CRM dataset containing company-level information.

Columns include:
- Company Name
- Website
- Address
- Revenue (in Millions)
- Industry

This dataset was used to populate the core Company ontology.

------------------------------------------------------------------------------------------------------------

### 2. crm_company_source_data_p.csv
Processed/enriched version of the CRM dataset.

Purpose:
- Used for testing, transformations, or derived attributes
- Supports analytics and CRM workflows inside Palantir Foundry

Both datasets were ingested and modeled using Foundry Ontology.
