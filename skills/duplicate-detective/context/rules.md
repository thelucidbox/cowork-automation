# Duplicate Detective — Rules & Guidelines

## Output Format

### duplicate-report.md
```markdown
# Duplicate Analysis Report

## Summary
- Files scanned: [count]
- Duplicates found: [count]
- Space recoverable: [size]

## Duplicate Sets

### Set 001 (Exact Match)
| File | Location | Size | Date | Keep? |
|------|----------|------|------|-------|
| photo.jpg | ~/Pictures/ | 5MB | 2024-01 | ✓ |
| photo.jpg | ~/Downloads/ | 5MB | 2024-02 | Delete |

### Set 002 (Near Match)
...
```

---

## Detection Rules

### Exact Duplicates
- Same file hash
- 100% confidence
- Safe to remove copies

### Near Duplicates
- Similar content
- Different metadata
- Review recommended

### Name Duplicates
- Same filename
- Different content
- May be different files

---

## Keep Priority

1. Original location (source folder)
2. Oldest date (original)
3. Best quality (largest/highest res)
4. Most organized path

---

## Safe Delete Rules

- Never delete last copy
- Preserve organized copies over messy
- Keep higher quality versions
- Maintain folder structure references

---

*Part of Art of Fact Cowork Skill Library*
