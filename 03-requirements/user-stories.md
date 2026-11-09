# User Stories – Epic L2C-1: Automate Lead-to-Cash

## US1 – Standard Quote Pricing
As a Sales Rep, I want to build quotes in CPQ with standard pricing, so that quotes are accurate and fast.

Acceptance Criteria:
- Given a product is selected, when I create a quote, then the standard price loads automatically
- Given a discount above 15%, when I submit the quote, then it needs manager approval

## US2 – Risk and Compliance Approval
As a Compliance Officer, I want quotes routed to me in Salesforce, so that every approval has an audit trail.

Acceptance Criteria:
- Given a quote is submitted, when it meets the risk rules, then it is sent to Compliance automatically
- Given I approve or reject, then my name, date and comments are saved

## US3 – E-Signature
As a Sales Rep, I want to send contracts for e-signature from Salesforce, so that deals close faster.

Acceptance Criteria:
- Given a quote is approved, when I generate the contract, then it is sent for e-signature
- Given the client signs, then the opportunity moves to Closed Won

## US4 – Send Deal to SAP
As a Finance Analyst, I want closed-won deals sent to SAP automatically, so that I don't re-key data.

Acceptance Criteria:
- Given a deal is Closed Won, then customer, amount and products are sent to SAP within 15 minutes
- Given the transfer fails, then an error alert is sent to the support team

## US5 – Payment Status in Salesforce
As a Sales Rep, I want to see invoice and payment status in Salesforce, so that I can follow up with clients.

Acceptance Criteria:
- Given an invoice is paid in SAP, then the status shows as Paid in Salesforce by the next day

## Change Request – CR1 (mid-sprint)
Compliance asked for a second approval for deals over £500k. Impact checked, agreed with the Product Owner, and added as a new story, US6, for the next sprint.
