# Receipt Processor — Rules & Guidelines

## Output Format

### Individual Receipt
```markdown
# Receipt: [Vendor]

- **Date**: YYYY-MM-DD
- **Vendor**: [Name]
- **Amount**: $XX.XX
- **Tax**: $X.XX
- **Category**: [Category]
- **Payment**: [Card/Cash]

## Items
| Item | Qty | Price |
|------|-----|-------|
| [item] | 1 | $X.XX |

## Notes
[Any additional context]

## Original
[Link to image/PDF]
```

### expense-log.md
```markdown
# Expense Log

## [Month Year]

| Date | Vendor | Amount | Category | Business |
|------|--------|--------|----------|----------|
| 01-15 | Store A | $45.00 | Supplies | Yes |

## Totals
| Category | Amount |
|----------|--------|
| Supplies | $XXX |
| Food | $XXX |
| **Total** | $X,XXX |
```

---

## Extraction Fields

### Required
- Date
- Vendor name
- Total amount

### Optional
- Tax amount
- Payment method
- Line items
- Address
- Transaction ID

---

## Category Defaults

| Category | Examples |
|----------|----------|
| Food & Dining | Restaurants, groceries |
| Transport | Gas, parking, rideshare |
| Supplies | Office, household |
| Services | Subscriptions, repairs |
| Entertainment | Events, media |
| Travel | Hotels, flights |

---

*Part of Art of Fact Cowork Skill Library*
