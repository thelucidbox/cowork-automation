---
name: archive-architect
description: --- Creates structured archives with proper organization, compression, documentation, and retrieval systems. Ensures important files are preserved with context, searchable,...
---

# Archive Architect

**Design and implement intelligent archival systems for long-term file storage.**

---

## What This Does

Creates structured archives with proper organization, compression, documentation, and retrieval systems. Ensures important files are preserved with context, searchable, and recoverable years later.

| Output | What You Get |
|--------|--------------|
| archives/ | Organized archive packages |
| archive-index.md | Searchable catalog |
| retrieval-guide.md | How to find things |

---


---

## IMPORTANT: Always Ask First

When the user says "ready to work", "get to work", or loads this folder:

1. **Greet and explain** what this skill does
2. **Ask what they need**:
   > "I can help you with [skill purpose]. Would you like to:
   > 1. **Start fresh** - I'll guide you through what I need
   > 2. **Use files in input/** - I'll process what you've added
   > 3. **See an example** - I'll show you what this produces"

3. **Never auto-run** without confirming what the user wants

### Why This Matters
Users loading a skill folder expect guidance, not assumptions. Always confirm before processing.

## Quick Start

### Option 1: Natural Language
> "Archive my completed 2023 projects"

### Option 2: Smart Archive
> "Create a searchable archive of all client work"

### Option 3: Preservation Mode
> "Archive these files with full documentation"

---

## What I Need From You

### Required
- **Files to archive**: What to preserve

### Optional (Enhances Output)
- **Archive structure**: How to organize
- **Retention rules**: How long to keep
- **Access needs**: Who might need these

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| File metadata | Context preservation | Basic info |
| Folder structure | Organization hints | Flat archive |
| File relationships | Grouping logic | Individual files |

---

## Output Location

```
output/
├── archives/
│   ├── 2023-projects.tar.gz
│   ├── client-work-archive/
│   └── [archive-name]/
├── archive-index.md
└── retrieval-guide.md
```

---

## Examples

### Example 1: Project Archive
**Input**: Completed project folder

**Output**:
- Compressed archive with structure preserved
- README documenting contents
- Search index for quick retrieval
- Version info and dates recorded

### Example 2: Annual Archive
**Input**: All 2023 work files

**Output**:
- Categorized by project/client
- Compressed per category
- Master index across all archives
- Storage recommendations

### Example 3: Legal Preservation
**Input**: Contract and correspondence files

**Output**:
- Preserved with timestamps
- Checksums for integrity
- Access log capability
- Retention schedule attached

---

## What I Won't Do

- **Won't delete originals**: Archive is copy
- **Won't lose context**: Preserves structure
- **Won't create unsearchable dumps**: Always indexed

---

## Tips for Best Results

1. **Archive by project**: Logical groupings
2. **Include documentation**: Future you will thank you
3. **Test retrieval**: Verify accessibility

---

*Part of Art of Fact Cowork Skill Library*
