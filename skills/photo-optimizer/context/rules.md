# Photo Optimizer — Rules & Guidelines

## Output Formatting Rules

### optimization-report.md Format
```markdown
# Optimization Report

**Images Processed**: [N]
**Total Before**: [Size]
**Total After**: [Size]
**Reduction**: [%]

---

## Summary

| Metric | Value |
|--------|-------|
| Files processed | [N] |
| Total savings | [Size] |
| Average reduction | [%] |

---

## Individual Files

| Original | Optimized | Before | After | Reduction |
|----------|-----------|--------|-------|-----------|
| [name] | [new name] | [size] | [size] | [%] |

---

## Settings Used

| Setting | Value |
|---------|-------|
| Max width | [px] |
| Quality | [%] |
| Format | [format] |
```

---

## Optimization Guidelines

### Quality Levels
| Use Case | Quality | Notes |
|----------|---------|-------|
| High quality | 90-95 | Minimal compression |
| Standard | 80-85 | Good balance |
| Web | 70-80 | Smaller files |
| Thumbnails | 60-70 | Size priority |

### Size Targets
| Use Case | Max Width |
|----------|-----------|
| Hero images | 1920px |
| Blog content | 1200px |
| Thumbnails | 300px |
| Icons | 64-128px |

---

## Format Selection

### WebP
- Best compression
- Wide browser support
- Use as default

### JPEG
- Universal support
- Good for photos
- Fallback option

### PNG
- Transparency support
- Lossless option
- Larger files

---

## Quality Checklist

- [ ] Aspect ratio preserved
- [ ] Quality acceptable
- [ ] File size reduced
- [ ] Originals preserved
- [ ] Format appropriate
- [ ] Report generated

---

*Part of Art of Fact Cowork Skill Library*
