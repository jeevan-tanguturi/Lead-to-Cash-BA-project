# Project Governance

## RAID Log

| Type | ID | Description | Owner | Status |
|------|----|-------------|-------|--------|
| Risk | R1 | SAP integration may be delayed by IT capacity | Tech Lead | Open |
| Assumption | A1 | Salesforce licences cover CPQ users | Product Owner | Confirmed |
| Issue | I1 | Deals reaching SAP late (defect D1) | Tech Lead | Closed |
| Dependency | D1 | E-signature tool contract must be signed | Procurement | Open |

## Decision Log

| ID | Decision | Made By | Date |
|----|----------|---------|------|
| DEC1 | Use Salesforce approval workflow instead of email | Steering Group | Week 2 |
| DEC2 | Add second approval for deals over £500k (CR1) | Product Owner | Week 4 |

## RACI

| Activity | Sales | Compliance | Finance | BA | Tech |
|----------|-------|------------|---------|----|------|
| Requirements | C | C | C | R | I |
| Approval rules | I | A | I | R | C |
| SAP integration | I | I | C | C | R |
| UAT sign-off | A | A | A | R | I |

R = Responsible, A = Accountable, C = Consulted, I = Informed
