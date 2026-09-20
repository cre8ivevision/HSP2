# 05. Business Model & Unit Economics Analysis

Status: In progress
Last updated: 2026-09-21

## Objective

Determine how Hostable.pk could enter the market with limited initial capital, controlled operational complexity, and a path toward greater infrastructure ownership only when demand justifies it.

## Candidate models

### Model A: Reseller hosting

Purchase wholesale hosting capacity and sell branded packages.

Advantages:
- Low initial infrastructure burden
- Fast launch
- Provider handles much of the server layer
- Useful for demand validation

Risks:
- Lower control
- Provider dependency
- Wholesale limits
- Potentially thin margins
- Limited differentiation if only rebranded

### Model B: VPS-based hosting

Lease VPS/server capacity and build the hosting layer on top.

Advantages:
- Greater control
- Ability to standardize the platform
- Support for custom automation
- Potentially better economics at sufficient utilization

Risks:
- More technical responsibility
- Backup, monitoring, security, and incident-response burden
- Capacity planning

### Model C: Managed VPS / managed hosting

Sell a managed outcome rather than raw server capacity.

Advantages:
- Higher potential revenue per account
- Stronger service differentiation
- Fit for non-technical SMEs

Risks:
- Support labor can dominate economics
- Scope creep
- Need for strong operational processes and SLAs

### Model D: Cloud infrastructure

Build around cloud compute, storage, and networking.

Advantages:
- Elastic infrastructure
- Easier horizontal scaling
- Mature infrastructure primitives

Risks:
- Variable bills
- Greater architectural complexity
- Difficult economics for low-value shared hosting if utilization is poor

### Model E: Hybrid / multi-provider

Use more than one upstream infrastructure provider.

Potential value:
- Vendor diversification
- Regional flexibility
- Product-specific infrastructure
- Reduced single-supplier dependency

Risks:
- Higher operational complexity
- More automation required
- More difficult support and observability

## Current working direction

Do not lock one model yet.

A staged approach should be evaluated:

Validate demand → launch a narrow product set → measure utilization/support/churn → improve economics → add infrastructure ownership/control → diversify upstream providers.

The key question is whether customer revenue covers infrastructure, payment costs, support labor, software, backups, security, taxes, overhead, and customer acquisition.

## Unit economics

For each product calculate:

Revenue per customer
- infrastructure allocation
- control-panel/licensing
- payment processing
- backup/storage
- monitoring/security
- domain cost where bundled
- support labor
- refunds/chargebacks
- taxes and statutory costs
- customer acquisition
- general overhead allocation
= contribution margin

Core metrics:

| Metric | Definition |
|---|---|
| ARPU | Average revenue per customer |
| Gross margin | Revenue less direct service costs |
| Contribution margin | Revenue less variable/direct operating costs |
| CAC | Customer acquisition cost |
| Churn | Customer/service loss rate |
| Renewal rate | Customers renewing at term end |
| LTV | Customer lifetime value |
| Payback period | Time to recover CAC |
| Support cost/account | Support labor per customer |
| Infrastructure utilization | Used versus available capacity |

## Current competitor price signals

HosterPK publicly lists shared plans from Rs. 5,460/year and VPS plans from roughly Rs. 3,330/month. creativeON publicly lists shared hosting from Rs. 1,450/month, WordPress hosting from Rs. 860/month, and cloud hosting from Rs. 6,300/month. These are competitor retail prices, not Hostable.pk cost assumptions. citeturn0search2turn0search5

The next research pass must collect actual wholesale/upstream costs from candidate infrastructure vendors.

## Validation scenarios

Model at least:

- 25 customers
- 50 customers
- 100 customers
- 250 customers
- 500 customers
- 1,000 customers

For each scenario calculate monthly recurring revenue, annual recurring revenue, infrastructure cost, software cost, support hours, payment costs, backup/storage cost, CAC, contribution margin, and break-even customer count.

## Open questions

1. What should the first paid product be?
2. Reseller or VPS-based entry?
3. Which upstream providers should be evaluated?
4. Pakistan, international, or multi-region infrastructure?
5. Which control panel?
6. Which billing platform?
7. Which payment gateways?
8. What support is included?
9. What is the first target customer segment?
10. What minimum margin is required before scaling?
