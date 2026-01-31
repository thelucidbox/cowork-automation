---
name: receipt-processor
description: --- Processes receipt images and PDFs, extracts key data (vendor, amount, date, items), categorizes expenses, and creates organized records for...
---

# Receipt Processor

**Extract, categorize, and organize receipt data for expense tracking.**

---

## What This Does

Processes receipt images and PDFs, extracts key data (vendor, amount, date, items), categorizes expenses, and creates organized records for bookkeeping, expense reports, or tax preparation.

| Output | What You Get |
|--------|--------------|
| receipts/ | Processed records |
| expense-log.md | Categorized list |
| summary.md | Spending overview |

---


---

## IMPORTANT: Always Ask First

When the user says "ready to work", "get to work", or loads this folder:

1. **Greet and explain** what this skill does
2. **Ask what they need**:
   > "I can help you with [skill purpose]. Would you like to:
   > 1. **Start fresh** - I'll guide you through what I need
   > 2. **Use files in input/** - I'll process what you've added
   > 3. **See an example** - I'll show you what this produces"

3. **Never auto-run** without confirming what the user wants

### Why This Matters
Users loading a skill folder expect guidance, not assumptions. Always confirm before processing.

## Quick Start

### Option 1: Natural Language
> "Process these receipts"

### Option 2: Batch Mode
> "Extract data from all receipts in folder"

### Option 3: Expense Report
> "Create an expense report from this trip's receipts"

---

## What I Need From You

### Required
- **Receipts**: Images, PDFs, or photos

### Optional (Enhances Output)
- **Categories**: Expense types to use
- **Purpose tags**: Business, personal, etc.
- **Project codes**: For allocation

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Receipt image | Vendor, amount, date | Manual entry |
| PDF receipt | Structured data | OCR extraction |
| Email receipt | Full transaction details | — |

---

## Output Location

```
output/
├── receipts/
│   ├── 2024-01-15_vendor_$XX.md
│   └── [date]_[vendor]_[amount].md
├── expense-log.md
└── summary.md
```

---

## Examples

### Example 1: Monthly Processing
**Input**: 45 receipt images

**Output**:
- All receipts extracted
- Categorized by type
- Monthly total: $X,XXX
- Tax-deductible flagged

### Example 2: Business Trip
**Input**: Trip receipts

**Output**:
- Meals: $XXX
- Transport: $XXX
- Lodging: $XXX
- Per diem comparison
- Expense report ready

### Example 3: Tax Prep
**Input**: Year of business receipts

**Output**:
- By category totals
- Deductible expenses flagged
- Missing receipts identified
- Export for accountant

---

## What I Won't Do

- **Won't file taxes**: Preparation only
- **Won't create fake receipts**: Real data only
- **Won't guarantee accuracy**: Verify important items

---

## Tips for Best Results

1. **Clear photos**: Better extraction
2. **Process promptly**: While memory fresh
3. **Add notes**: Context helps categorization

---

*Part of Art of Fact Cowork Skill Library*
