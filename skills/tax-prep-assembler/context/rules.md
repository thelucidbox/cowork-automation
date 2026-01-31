# Tax Prep Assembler — Rules & Guidelines

## Output Format

### checklist.md
```markdown
# Tax Document Checklist - [Year]

## Income Documents
- [x] W-2 from [Employer] - Found
- [x] 1099-INT from [Bank] - Found
- [ ] 1099-NEC from [Client] - Missing

## Deduction Documents
- [x] 1098 Mortgage Interest - Found
- [ ] Property tax statement - Missing
- [x] Charitable receipts - Found

## Other Documents
- [x] Prior year return - Found
- [x] ID verification - Ready

## Status
- Found: X documents
- Missing: X documents
- Ready: XX%
```

### summary.md
```markdown
# Tax Prep Summary - [Year]

## Income (Preliminary)
| Source | Amount | Form |
|--------|--------|------|
| W-2 Wages | $XX,XXX | W-2 |
| Interest | $XXX | 1099-INT |
| **Total** | $XX,XXX | |

## Deductions (Preliminary)
| Category | Amount |
|----------|--------|
| Mortgage Interest | $X,XXX |
| State Taxes | $X,XXX |
| Charitable | $XXX |

## Notes for Preparer
- [Special circumstances]
- [Questions to address]
```

---

## Document Categories

### Income
- W-2 (employment)
- 1099-NEC (freelance)
- 1099-INT (interest)
- 1099-DIV (dividends)
- 1099-B (investments)
- K-1 (partnerships)

### Deductions
- 1098 (mortgage)
- Property taxes
- Medical expenses
- Charitable donations
- Business expenses

### Credits
- 1098-T (education)
- Childcare expenses
- Energy credits

---

*Part of Art of Fact Cowork Skill Library*
