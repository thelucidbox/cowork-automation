# Document Time Machine — Rules & Guidelines

## Output Format

### recovery-report.md
```markdown
# Document Recovery Report

## Search Query
- Document: [name/pattern]
- Date range: [range]

## Versions Found
| Version | Date | Location | Size | Changes |
|---------|------|----------|------|---------|
| v3 (current) | 2024-02-01 | Local | 45KB | — |
| v2 | 2024-01-15 | Time Machine | 42KB | +3 paragraphs |
| v1 | 2024-01-01 | Email | 38KB | Original |

## Content Differences
### v1 → v2
[Summary of changes]

### v2 → v3
[Summary of changes]

## Recovered Content
[Specific content from older versions]
```

---

## Search Priority

1. Local file system
2. Time Machine backups
3. Cloud storage versions
4. Email attachments
5. Temporary/autosave files

---

## Version Identification

### Naming Convention
- `v1_YYYY-MM-DD_source`
- Source: local, backup, cloud, email

### Matching Criteria
- Exact filename
- Similar filename variations
- Content fingerprinting

---

## Diff Generation

### Compare Elements
- Text content changes
- Formatting changes
- Metadata changes
- File size differences

---

*Part of Art of Fact Cowork Skill Library*
