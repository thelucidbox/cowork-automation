---
name: warranty-tracker
description: --- Catalogs your purchases and their warranties, stores proof of purchase, tracks expiration dates, and reminds you before warranties end...
---

# Warranty Tracker

**Track product warranties and get notified before they expire.**

---

## What This Does

Catalogs your purchases and their warranties, stores proof of purchase, tracks expiration dates, and reminds you before warranties end so you can address issues while still covered.

| Output | What You Get |
|--------|--------------|
| warranties.md | Full inventory |
| expiring-soon.md | Upcoming expirations |
| claims/ | Claim documentation |

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
> "Add this new purchase to warranty tracking"

### Option 2: From Receipt
> "Track warranty from this receipt"

### Option 3: Status Check
> "What warranties are expiring soon?"

---

## What I Need From You

### Required
- **Product info**: What was purchased
- **Purchase date**: When bought
- **Warranty period**: How long coverage lasts

### Optional (Enhances Output)
- **Receipt/proof**: Documentation
- **Serial number**: For claims
- **Extended warranty**: Additional coverage

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Receipt | Purchase date, price | Manual entry |
| Product info | Warranty terms | Standard estimate |
| Email confirmations | Order details | — |

---

## Output Location

```
output/
├── warranties.md
├── expiring-soon.md
├── claims/
│   └── [product]-claim.md
└── receipts/
```

---

## Examples

### Example 1: Electronics Inventory
**Input**: New laptop purchase

**Output**:
- Product registered
- 1-year warranty tracked
- AppleCare+ added (if applicable)
- Reminder set: 11 months

### Example 2: Appliance Tracking
**Input**: Home appliances

**Output**:
- All appliances cataloged
- Warranty periods noted
- Extended warranties tracked
- Expiration calendar

### Example 3: Claim Preparation
**Input**: "My blender broke"

**Output**:
- Warranty status checked
- Purchase proof located
- Claim steps outlined
- Contact information provided

---

## What I Won't Do

- **Won't file claims**: Preparation only
- **Won't guarantee coverage**: Check terms
- **Won't contact manufacturers**: You must follow up

---

## Tips for Best Results

1. **Add immediately**: After purchase
2. **Save receipts**: Required for claims
3. **Note serial numbers**: Speeds up claims

---

*Part of Art of Fact Cowork Skill Library*
