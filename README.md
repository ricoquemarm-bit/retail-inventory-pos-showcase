# Retail Inventory & POS — Portfolio Showcase

![Exact dashboard shown on Rico Integration](screenshots/portfolio-preview.png)

A portfolio-safe retail operating system demonstrating checkout, stock health, supplier activity, purchase orders, replenishment alerts, staff visibility, and commercial reporting.

## Matching interface details

| Sales and stock controls | Inventory and supplier operations |
| --- | --- |
| ![Retail interface top](screenshots/interface-top.png) | ![Retail interface bottom](screenshots/interface-bottom.png) |

```mermaid
flowchart LR
  A[Store checkout] --> B[Sales service]
  B --> C[Inventory ledger]
  C --> D[Low-stock policy]
  D --> E[Purchase orders]
  E --> F[Suppliers and receiving]
  B --> G[Retail analytics]
  C --> G
```

The public repository contains a sanitized static demo and portfolio screenshots. The complete interactive source remains private. All products, SKUs, suppliers, employees, stock levels, prices, and results are fictional. No payment integration, card data, credential, customer record, or private API is included.

[Rico Integration](https://ricointegration.com/)
