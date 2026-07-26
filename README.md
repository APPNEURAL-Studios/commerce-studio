# Commerce Studio

Storefronts, catalogs, checkout and orders

Build storefronts, product catalogs, and checkout flows. Manage inventory, orders, shipping rules, coupons, and subscription plans, configure tax rules and payment gateways, and set up upsells, wishlists, and returns for a complete store.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (13):**

| Service | Status |
|---|---|
| `commerce-service` | Core |
| `order-service` | Core |
| `catalog-service` | Core |
| `product-service` | Core |
| `payment-service` | Core |
| `billing-service` | Core |
| `inventory-service` | New (Tier-1) |
| `marketing-service` | Core |
| `customer-service` | Core |
| `tax-service` | New (Tier-1) |
| `review-service` | New (Tier-1) |
| `recommendation-service` | Suggested — not yet built |
| `localization-service` | Suggested — not yet built |
