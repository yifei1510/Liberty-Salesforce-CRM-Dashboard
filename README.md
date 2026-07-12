Liberty Australia Salesforce CRM dashboard

An independent CRM and reporting project completed during my ongoing internship with Liberty Exports.

**Role:** Global Trade Intelligence Intern  
**Period:** June 2026 to present  
**Tools:** Salesforce CRM, Salesforce Reports and Dashboards, Microsoft Excel, VLOOKUP, XLOOKUP

## Project overview

Liberty Exports' Australian buyer, supplier, freight and logistics research was stored across separate spreadsheets. Inconsistent fields and category labels made it difficult to compare organisations, identify priorities and give management a clear view of potential follow-up opportunities.

I used Salesforce to turn this fragmented research into a structured CRM workflow. After validating and matching the spreadsheet data in Excel, I created 84 Salesforce Leads, built reports for each business group and combined them in one management dashboard. This gave the company a consistent way to review lead volumes, priority levels, product interests, supplier minimum order quantities and logistics service coverage.

<img width="1269" height="1538" alt="Liberty Australia Overview Dashboard" src="https://github.com/user-attachments/assets/d3343ee0-17da-4d9e-9c09-ebe3b3a1495f" />


## Business need

The source information was stored across research spreadsheets and used different fields and category labels. This made it difficult to compare organisations, identify priority records and prepare consistent follow-up.

I built a workflow that answered practical questions:

- How many researched organisations are available for follow-up?
- Which buyers and suppliers should receive attention first?
- What products, minimum order arrangements and service types are represented?
- How can management review the information without working through multiple spreadsheets?

## What I did

### Excel preparation and CRM data hygiene

- Reviewed buyer, supplier, freight and logistics spreadsheets before import.
- Used VLOOKUP and XLOOKUP to match records across worksheets and check field consistency.
- Standardised category labels, priority values and service descriptions.
- Checked required fields and removed records that were not suitable for Salesforce Lead creation.
- Mapped spreadsheet columns to Salesforce fields while retaining useful source notes.

### Salesforce lead management

- Created Salesforce Leads for four research groups: Buyers, Suppliers, Freight and Logistics.
- Kept the groups identifiable so each could be filtered and reported separately.
- Organised related lead groups through Salesforce Campaigns where needed.
- Checked imported records before building reports.

### Reports and dashboard

- Built Salesforce reports for buyer importance and product category distribution.
- Reported supplier priority and minimum order quantity arrangements.
- Analysed freight company importance and modes of service.
- Reported logistics company importance and available service types.
- Combined the reports into the Liberty Australia Overview Dashboard for management review.

## Dashboard results

The dashboard contains **84 Salesforce Leads** across four market research groups.

| Lead group | Records | Reporting focus |
|---|---:|---|
| Buyers | 10 | Buyer importance and product category distribution |
| Suppliers | 14 | Supplier priority and minimum order quantity |
| Freight | 45 | Company importance and mode of service |
| Logistics | 15 | Company importance and logistics service type |
| **Total** | **84** | Consolidated Australia market overview |

Selected findings from the dashboard:

- 9 of the 10 buyer records were classified as high importance.
- Buyer demand was strongest in Indian Grocery Products and Ethnic / South Asian Foods, with four category records each.
- The supplier list contained 8 high-priority, 4 medium-to-high and 2 medium-priority records.
- 11 suppliers provided minimum order quantities by quote, while 3 required negotiation.
- The freight dataset contained 36 high-importance and 9 medium-importance companies.
- The logistics dataset contained 13 high-importance and 2 medium-to-high-importance companies.

## Workflow

```text
Market research spreadsheets
        |
        v
Excel validation and matching
(VLOOKUP and XLOOKUP)
        |
        v
Field standardisation and Salesforce mapping
        |
        v
Salesforce Lead creation and quality checks
        |
        v
Reports by lead group and business attribute
        |
        v
Management dashboard
```

## Relevance to revenue operations

This project gave me practical experience with the type of work used in revenue operations teams:

- maintaining clean and reportable CRM records;
- using Excel lookups to reconcile and validate business data;
- structuring Lead data for consistent segmentation;
- building reports that support prioritisation and follow-up planning;
- turning separate datasets into a dashboard that managers can review quickly;
- documenting a repeatable process from spreadsheet preparation to CRM reporting.

The project focuses on lead data quality and reporting rather than revenue forecasting. It provides a foundation for pipeline tracking, territory analysis and broader GTM reporting.

## Repository contents

```text
.
|-- README.md
`-- images/
    `-- liberty-australia-overview-dashboard.png
```

## Privacy note

This repository presents the workflow, aggregated counts and dashboard output. It does not publish contact details, email addresses, phone numbers or raw CRM exports.
