# Screenshot Cleaner — Rules & Guidelines

## Output Formatting Rules

### index.md Format
```markdown
# Screenshot Index

**Total**: [N] screenshots
**Categories**: [N]
**Generated**: [Date]

---

## By Category

### Work ([N] items)
| Thumbnail | Name | Date | Content |
|-----------|------|------|---------|
| [preview] | [name] | [date] | [OCR text excerpt] |

### Personal ([N] items)
...

---

## Search Index

### Keywords
- **project-alpha**: [list of files]
- **error**: [list of files]
- **slack**: [list of files]

---

## Full Text Index

[Searchable text from all screenshots]
```

### duplicates-removed.md Format
```markdown
# Duplicates Found

**Total Duplicates**: [N]
**Space Saved**: [Size]

---

## Duplicate Groups

### Group 1
| File | Size | Date | Action |
|------|------|------|--------|
| [original] | [size] | [date] | Keep |
| [duplicate] | [size] | [date] | Moved to duplicates/ |

**Similarity**: 98%

### Group 2
...

---

## Review Before Deleting

These have been moved to `duplicates/` folder.
Review and delete manually when confident.
```

---

## Naming Rules

### Format
```
YYYY-MM-DD-[source]-[brief-description].png
```

### Examples
- `2024-01-15-slack-team-discussion.png`
- `2024-01-15-error-api-timeout.png`
- `2024-01-15-reference-design-spec.png`

### From OCR Content
- Use first meaningful text
- App name if identifiable
- "screenshot" fallback

---

## Category Rules

### Work
- Slack, Teams messages
- Code editors, terminals
- Work apps, email
- Project documentation

### Personal
- Personal apps
- Non-work content
- Social media

### Reference
- Documentation
- Tutorials
- Inspiration

### Errors
- Error messages
- Stack traces
- Bug screenshots

---

## Quality Checklist

- [ ] All files renamed meaningfully
- [ ] Categories are logical
- [ ] Duplicates identified correctly
- [ ] Index is searchable
- [ ] Dates preserved
- [ ] Originals recoverable

---

*Part of Art of Fact Cowork Skill Library*
