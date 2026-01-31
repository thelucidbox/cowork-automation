# Warranty Tracker — Rules & Guidelines

## Output Format

### warranties.md
```markdown
# Warranty Inventory

## Active Warranties

| Product | Purchase Date | Warranty Ends | Status |
|---------|--------------|---------------|--------|
| MacBook Pro | 2024-01-15 | 2025-01-15 | Active |
| Dyson Vacuum | 2023-06-01 | 2025-06-01 | Active |
| Samsung TV | 2022-11-20 | 2023-11-20 | Expired |

## By Category

### Electronics
| Product | Ends | Days Left |
|---------|------|-----------|
| MacBook | 2025-01-15 | 365 |

### Appliances
| Product | Ends | Days Left |
|---------|------|-----------|
| Dyson | 2025-06-01 | 500 |
```

### expiring-soon.md
```markdown
# Expiring Soon (Next 90 Days)

| Product | Expires | Days Left | Action |
|---------|---------|-----------|--------|
| Router | 2024-02-15 | 32 | Check for issues |
| Headphones | 2024-03-01 | 46 | Working fine |

## Recommended Actions
1. **Router** - Test all features, document any issues
2. **Headphones** - Verify charging, sound quality
```

---

## Tracking Rules

### Required Info
- Product name/model
- Purchase date
- Warranty length
- Purchase location

### Recommended
- Serial number
- Receipt image/PDF
- Extended warranty details
- Registration confirmation

---

## Reminder Schedule

| Time Before Expiry | Action |
|-------------------|--------|
| 90 days | First alert |
| 30 days | Action reminder |
| 7 days | Final warning |
| Day of | Expiration notice |

---

*Part of Art of Fact Cowork Skill Library*
