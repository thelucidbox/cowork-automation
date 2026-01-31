# Media Format Converter — Rules & Guidelines

## Output Formatting Rules

### conversion-report.md Format
```markdown
# Conversion Report

**Files Converted**: [N]
**Total Before**: [Size]
**Total After**: [Size]
**Date**: [Date]

---

## Conversions

| Original | Converted | Before | After | Status |
|----------|-----------|--------|-------|--------|
| [file.mov] | [file.mp4] | [size] | [size] | Success |

---

## Settings Used

| Setting | Value |
|---------|-------|
| Video codec | H.264 |
| Audio codec | AAC |
| Quality | High |

---

## Commands

```bash
[ffmpeg commands used]
```
```

---

## Quality Guidelines

### Video
| Quality | Bitrate | Use Case |
|---------|---------|----------|
| High | 10-20 Mbps | Archive |
| Medium | 5-10 Mbps | Sharing |
| Web | 2-5 Mbps | Streaming |

### Audio
| Quality | Bitrate | Use Case |
|---------|---------|----------|
| High | 320 kbps | Music |
| Medium | 192 kbps | Podcast |
| Low | 128 kbps | Voice |

---

## Quality Checklist

- [ ] Format correct
- [ ] Quality preserved
- [ ] Metadata intact
- [ ] File plays correctly
- [ ] Originals preserved

---

*Part of Art of Fact Cowork Skill Library*
