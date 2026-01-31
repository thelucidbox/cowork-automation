---
name: duplicate-detective
description: --- Scans specified locations for duplicate files using multiple detection methods (hash, name, content similarity), presents findings with confidence levels,...
---

# Duplicate Detective

**Find and eliminate duplicate files across your entire system.**

---

## What This Does

Scans specified locations for duplicate files using multiple detection methods (hash, name, content similarity), presents findings with confidence levels, and helps safely remove redundant copies while keeping the best version.

| Output | What You Get |
|--------|--------------|
| duplicate-report.md | Full analysis |
| duplicates/ | Grouped duplicate sets |
| space-savings.md | Recovery potential |

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
> "Find duplicate files in my Documents folder"

### Option 2: System-Wide
> "Scan for duplicates across all my storage"

### Option 3: Specific Type
> "Find duplicate photos in my library"

---

## What I Need From You

### Required
- **Scan locations**: Folders to analyze

### Optional (Enhances Output)
- **File types**: Focus on specific extensions
- **Minimum size**: Ignore small files
- **Keep rules**: Which copy to preserve

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| File hashes | Exact duplicates | Name matching |
| Metadata | Original vs copy | Date comparison |
| Content analysis | Similar files | Hash only |

---

## Output Location

```
output/
├── duplicate-report.md
├── duplicates/
│   ├── set-001/
│   ├── set-002/
│   └── ...
└── space-savings.md
```

---

## Examples

### Example 1: Photo Library Cleanup
**Input**: 50,000 photos across multiple folders

**Output**:
- 3,000 exact duplicates found
- 500 near-duplicates (same photo, different size)
- 15GB space recoverable
- Safe deletion list

### Example 2: Document Deduplication
**Input**: Work documents folder

**Output**:
- Version conflicts identified
- Latest versions marked
- Old drafts flagged
- Organization recommendations

### Example 3: Full System Scan
**Input**: All user folders

**Output**:
- Cross-folder duplicates
- Backup redundancies
- Cloud sync conflicts
- Priority deletion list

---

## What I Won't Do

- **Won't auto-delete**: Always asks first
- **Won't touch system files**: User files only
- **Won't remove all copies**: Keeps at least one

---

## Tips for Best Results

1. **Start with largest files**: Maximum space savings
2. **Review near-duplicates**: May be intentional
3. **Check before deleting**: Verify recommendations

---

*Part of Art of Fact Cowork Skill Library*
