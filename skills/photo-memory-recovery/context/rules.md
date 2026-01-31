# Photo Memory Recovery — Rules & Guidelines

## Output Format

### recovery-report.md
```markdown
# Photo Recovery Report

## Summary
- Photos processed: [count]
- Dates recovered: [count]
- Events identified: [count]
- Duplicates found: [count]

## Timeline
| Year | Photos | Events |
|------|--------|--------|
| 2024 | [n] | [list] |
| 2023 | [n] | [list] |

## Events Identified
| Event | Date Range | Photos |
|-------|-----------|--------|
| [Name] | [dates] | [n] |

## Unrecovered
- [Files without dates]
```

---

## Date Recovery Methods

### Priority Order
1. EXIF DateTimeOriginal
2. EXIF CreateDate
3. Filename pattern (YYYYMMDD, IMG_XXXX)
4. File modification date
5. Folder name hints
6. Adjacent file dates

---

## Filename Patterns

| Pattern | Extraction |
|---------|------------|
| IMG_20240115_123456 | 2024-01-15 |
| 2024-01-15_photo | 2024-01-15 |
| DSC_1234 | Sequence only |
| Screenshot_* | Parse date portion |

---

## Event Detection

### Grouping Rules
- Photos within 4 hours = same session
- Photos within same location = same event
- Gap > 24 hours = new event
- Different location = possible new event

---

*Part of Art of Fact Cowork Skill Library*
