# Archive Architect — Rules & Guidelines

## Output Format

### archive-index.md
```markdown
# Archive Index

## Archives Created
| Archive | Contents | Size | Date | Location |
|---------|----------|------|------|----------|
| 2023-projects | 150 files | 2.3GB | 2024-01 | /archives/ |

## Contents Detail

### 2023-projects.tar.gz
- project-alpha/ (45 files)
- project-beta/ (32 files)
- project-gamma/ (73 files)

## Quick Find
| Looking For | Archive | Path |
|-------------|---------|------|
| Alpha contract | 2023-projects | project-alpha/docs/ |
| Beta designs | 2023-projects | project-beta/design/ |
```

### retrieval-guide.md
```markdown
# How to Retrieve Files

## Extract Full Archive
\`\`\`bash
tar -xzf archive-name.tar.gz
\`\`\`

## Extract Single File
\`\`\`bash
tar -xzf archive-name.tar.gz path/to/file
\`\`\`

## Search Without Extracting
\`\`\`bash
tar -tzf archive-name.tar.gz | grep "search-term"
\`\`\`
```

---

## Archive Structure

### Standard Layout
```
archive-name/
├── README.md (what, when, why)
├── INDEX.md (file listing)
├── contents/
│   └── [preserved structure]
└── metadata/
    └── checksums.md
```

---

## Naming Convention

### Archive Names
- `YYYY-category-description.tar.gz`
- `project-name-archive-YYYYMMDD.tar.gz`
- `client-name-YYYY.tar.gz`

---

## Integrity Verification

- Generate checksums on creation
- Store verification data
- Document retrieval tested

---

*Part of Art of Fact Cowork Skill Library*
