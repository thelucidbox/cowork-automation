# Semantic File Tagger — Rules & Guidelines

## Output Format

### tag-index.md
```markdown
# File Tag Index

## By Tag
### #finance
- invoice_2024.pdf
- budget_q1.xlsx
- expense_report.pdf

### #project-alpha
- specs.md
- design.fig
- requirements.docx

## By File
| File | Tags |
|------|------|
| invoice_2024.pdf | #finance, #2024, #vendor |
| specs.md | #project-alpha, #technical |
```

---

## Tag Categories

### Automatic Tags
- File type (document, spreadsheet, image)
- Year/date extracted
- Size category

### Content Tags
- Topics mentioned
- Entities (people, companies)
- Actions (invoice, report, proposal)

### Context Tags
- Project associations
- Department relevance
- Status indicators

---

## Tagging Rules

### Tag Format
- Lowercase
- Hyphenated (multi-word)
- No spaces
- Prefix with # in display

### Confidence Levels
- High (>80%): Auto-apply
- Medium (50-80%): Suggest
- Low (<50%): Omit

---

*Part of Art of Fact Cowork Skill Library*
