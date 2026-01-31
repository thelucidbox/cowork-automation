# Desktop Zero — Rules & Guidelines

## Output Format

### desktop-report.md
```markdown
# Desktop Cleanup Report

## Summary
- Files processed: [count]
- Files sorted: [count]
- Files kept: [count]
- Action needed: [count]

## Sorted Files
| File | From | To | Reason |
|------|------|-----|--------|
| report.pdf | Desktop | ~/Documents | Document |
| photo.jpg | Desktop | ~/Pictures | Image |

## Kept on Desktop
- active-project.docx (recent edit)
- todo.txt (pinned)

## Action Needed
- unknown-file.xyz (unknown type)
- large-archive.zip (review contents)
```

---

## Sorting Rules

### By Extension
| Extension | Category | Destination |
|-----------|----------|-------------|
| .pdf, .docx, .xlsx | Documents | ~/Documents |
| .jpg, .png, .gif | Images | ~/Pictures |
| .mp4, .mov | Videos | ~/Movies |
| .zip, .tar | Archives | ~/Downloads/Archives |
| .dmg, .pkg | Installers | ~/Downloads/Installers |

### By Pattern
| Pattern | Category |
|---------|----------|
| Screenshot* | Screenshots |
| IMG_* | Photos |
| Invoice* | Finance |
| *_draft* | Work in progress |

---

## Keep Criteria

### Always Keep
- Modified in last 24 hours
- User-pinned items
- Active project files

### Never Keep
- Files older than 30 days
- Duplicate copies
- Completed downloads

---

*Part of Art of Fact Cowork Skill Library*
