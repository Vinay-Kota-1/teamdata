---
layout: default
title: Shared Datasets
---

# Shared Datasets

## Dataset Categories
- ![📊](assets/images/icon.png) [Customer Data](datasets.md#customer-data)
- ![🌍](assets/images/icon.png) [Geo Data](datasets.md#geo-data)
- ![💡](assets/images/icon.png) [Product Data](datasets.md#product-data)

## Customer Data
- **Description:** Customer behavior data for analysis.
- **Owner:** Data Team.
- **Access:** [Request Access](mailto:data-team@example.com).

### Data Dictionary
| Field Name    | Description           | Data Type |
|---------------|-----------------------|-----------|
| `customer_id` | Unique identifier     | Integer   |
| `purchase`    | Purchase amount       | Float     |
| `region`      | Customer region       | String    |

### Sample Queries
```sql
SELECT customer_id, COUNT(*) AS purchases FROM customer_behavior WHERE region = 'North' GROUP BY customer_id;
