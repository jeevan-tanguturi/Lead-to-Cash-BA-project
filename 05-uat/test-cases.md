# UAT Plan and Test Cases

## Scope
Test the To-Be Lead-to-Cash process end to end, from quote to payment status.

## Testers
Sales Rep, Compliance Officer, Finance Analyst

## Test Cases

| ID | Story | Test Step | Expected Result | Status |
|----|-------|-----------|-----------------|--------|
| TC1 | US1 | Create a quote for a standard product | Standard price loads automatically | Pass |
| TC2 | US1 | Add a 20% discount and submit | Sent for manager approval | Pass |
| TC3 | US2 | Submit a quote that meets risk rules | Routed to Compliance with audit trail | Pass |
| TC4 | US3 | Generate contract and client signs | Opportunity moves to Closed Won | Pass |
| TC5 | US4 | Close a deal as Won | Deal appears in SAP within 15 minutes | Fail |
| TC6 | US5 | Mark invoice as Paid in SAP | Shows as Paid in Salesforce next day | Pass |

## Defect Log

| ID | Test | Issue | Severity | Status |
|----|------|-------|----------|--------|
| D1 | TC5 | Deal took 2 hours to reach SAP | High | Fixed and retested – Pass |

## Sign-off
All test cases passed after D1 was fixed. Signed off by Sales, Compliance and Finance leads.
