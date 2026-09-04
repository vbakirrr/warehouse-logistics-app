# Architecture Baseline Assumptions and Risks

## Assumptions

1. Salesforce is the primary system of record for warehouse and logistics operational data.
2. Carrier and shipping information can be exchanged through a future integration boundary.
3. Users will access the application through Salesforce Lightning and their assigned permissions.

## Risks

1. External carrier integration requirements may change and affect the integration design.
2. Incorrect inventory data could cause operational discrepancies and fulfillment delays.
3. Future agent capabilities must respect Salesforce security and user access boundaries.
