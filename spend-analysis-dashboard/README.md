# Spend Analysis Dashboard

A category/supplier spend model with leakage detection and consolidation prioritization - the exact method for answering "how do you find savings?"

## How it works
1. Load PO data: Supplier | Category | Annual Spend | Contract Rate | Actual Rate | Variance | On-Time %
2. Pivot views: spend by category, spend by supplier, variance by supplier (the leakage detector), supplier concentration (top-3 share per category)
3. Dashboard tab: KPI cards (total spend, leakage $, supplier count, avg on-time %), spend-by-category chart, top-5 leakage table
4. Prioritize: leakage dollars × ease of fix

## Status
🟡 Building - Google Sheet template landing here Week 2 (Oct 18-24).

## Reference
Structure modeled on open procurement dashboard patterns (PivotTables + slicers, no VBA).
