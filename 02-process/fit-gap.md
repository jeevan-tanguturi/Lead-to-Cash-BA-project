# Fit-Gap Analysis

## As-Is Process (today)
1. Sales rep creates lead and opportunity in Salesforce
2. Quote is built manually in a spreadsheet
3. Risk and Compliance approve by email
4. Signed contract is saved in a shared folder
5. Finance re-keys the deal into SAP to raise the invoice
6. Payment is matched manually

## To-Be Process (future)
1. Lead and opportunity in Salesforce
2. Quote built in CPQ with standard pricing
3. Automated Risk and Compliance approval workflow in Salesforce
4. Contract generated and e-signed from Salesforce
5. Closed-won deal sent automatically to SAP via API
6. Invoice raised in SAP, payment status synced back to Salesforce

## Fit-Gap Table

| ID | Requirement | Current System | Fit / Gap | Solution |
|----|-------------|----------------|-----------|----------|
| FG1 | Track leads and opportunities | Salesforce | Fit | Use as is |
| FG2 | Standard quote pricing | Spreadsheets | Gap | Configure CPQ |
| FG3 | Approval audit trail | Email | Gap | Salesforce approval workflow |
| FG4 | E-signature on contracts | None | Gap | Add e-signature tool |
| FG5 | Deal data to ERP without re-keying | Manual entry | Gap | Salesforce to SAP API integration |
| FG6 | Payment visibility for Sales | None | Partial Gap | Sync payment status from SAP |
