# Receipt Scanner Playground Template

Use this template when building a playground for configuring receipt/expense processing.

## Layout

```
+------------------------+---------------------------+
|  Controls              |  Live Preview             |
|  ────────────────      |  (parsed receipt)         |
|  Categories            |                           |
|  Tax Flags             |  ┌─────────────────────┐  |
|  Export Format         |  │ Vendor: Staples     │  |
|  Vendor Rules          |  │ Date: 2024-01-15    │  |
|                        |  │ Amount: $127.43     │  |
|  Presets               |  │ Category: Supplies  │  |
|                        |  │ Tax: ✓ Deductible   │  |
+------------------------+  └─────────────────────┘  |
|  Prompt Output         |  [ Copy Prompt ]          |
+------------------------+---------------------------+
```

## Control specifications

| Control | Type | Options | Default |
|---------|------|---------|---------|
| Categories | Multi-checkbox | Travel, Meals, Supplies, Software, Services | All |
| Auto-categorize | Checkbox | on/off | on |
| Tax Deductible | Checkbox | on/off | on |
| Reimbursable | Checkbox | on/off | off |
| Export Format | Dropdown | CSV, JSON, QuickBooks, Expensify | CSV |
| Include Image | Checkbox | on/off | on |
| Currency | Dropdown | USD, EUR, GBP, Auto-detect | Auto-detect |

## Presets

| Preset | Description |
|--------|-------------|
| Business Expenses | All categories, deductible, CSV export |
| Reimbursement | Travel + Meals, reimbursable flag, Expensify format |
| Tax Prep | All categories, deductible only, QuickBooks export |
| Personal Tracking | All categories, no tax flags, JSON export |

## Prompt output examples

**Business Expenses:**
> Process my receipts for business expense tracking. Auto-categorize into Travel, Meals, Supplies, Software, and Services. Flag all as tax-deductible. Export as CSV with receipt images attached.

**Tax Prep:**
> Process receipts for tax preparation. Focus on tax-deductible expenses across all categories. Export in QuickBooks-compatible format with auto-detected currency conversion.

**Reimbursement:**
> Process receipts for expense reimbursement. Only include Travel and Meals categories. Mark as reimbursable and export in Expensify format.
