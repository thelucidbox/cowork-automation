---
name: tax-prep-assembler
description: --- Compiles tax-related documents from various sources, creates checklists of needed items, organizes by category, calculates preliminary totals, and prepares...
---

# Tax Prep Assembler

**Gather and organize all documents needed for tax filing.**

---

## What This Does

Compiles tax-related documents from various sources, creates checklists of needed items, organizes by category, calculates preliminary totals, and prepares a complete package for your accountant or tax software.

| Output | What You Get |
|--------|--------------|
| tax-docs/ | Organized documents |
| checklist.md | What's needed/found |
| summary.md | Preliminary totals |

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
> "Help me prepare for tax filing"

### Option 2: Document Gathering
> "Find all my tax documents for 2024"

### Option 3: Checklist Mode
> "What tax documents am I missing?"

---

## What I Need From You

### Required
- **Tax year**: Year to prepare

### Optional (Enhances Output)
- **Filing status**: Single, married, etc.
- **Income sources**: Employment, self-employment, etc.
- **Deduction types**: What you plan to claim

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Documents folder | Tax forms, receipts | Manual gathering |
| Email | Tax statements | Request from senders |
| Previous year | Baseline checklist | Standard checklist |

---

## Output Location

```
output/
├── tax-docs/
│   ├── income/
│   ├── deductions/
│   ├── credits/
│   └── other/
├── checklist.md
└── summary.md
```

---

## Examples

### Example 1: W-2 Employee
**Input**: "Prepare my 2024 taxes"

**Output**:
- W-2 located
- 1099-INT found
- Deductions gathered
- Missing: 1098 mortgage
- Ready for filing: 80%

### Example 2: Self-Employed
**Input**: Freelance income year

**Output**:
- 1099s compiled
- Business expenses categorized
- Quarterly payments tracked
- Mileage log located
- Home office calculation

### Example 3: Complex Return
**Input**: Multiple income sources

**Output**:
- All income docs organized
- Investment transactions
- Rental property docs
- Charitable contributions
- Professional review suggested

---

## What I Won't Do

- **Won't file taxes**: Organization only
- **Won't give tax advice**: Preparation help only
- **Won't guarantee completeness**: Verify with professional

---

## Tips for Best Results

1. **Start early**: Allow time to gather
2. **Check prior year**: What was needed
3. **Note missing items**: Track what to request

---

*Part of Art of Fact Cowork Skill Library*
