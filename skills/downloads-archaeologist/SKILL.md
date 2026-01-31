---
name: downloads-archaeologist
description: --- Analyzes your Downloads folder, identifies file types and purposes, recovers forgotten treasures, removes junk, and organizes everything into a...
---

# Downloads Archaeologist

**Excavate and organize your chaotic Downloads folder into a structured archive.**

---

## What This Does

Analyzes your Downloads folder, identifies file types and purposes, recovers forgotten treasures, removes junk, and organizes everything into a logical structure with full documentation.

| Output | What You Get |
|--------|--------------|
| organized/ | Sorted files by category |
| archive/ | Important files to keep |
| trash-candidates/ | Safe to delete |
| downloads-report.md | Full excavation report |

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
> "Organize my Downloads folder"

### Option 2: Deep Analysis
> "Excavate Downloads and find important files from the last year"

### Option 3: Cleanup Mode
> "Find duplicate and junk files in Downloads"

---

## What I Need From You

### Required
- **Access to Downloads**: Permission to analyze folder

### Optional (Enhances Output)
- **Time range**: Focus on specific period
- **Priority categories**: What matters most
- **Deletion approval**: Auto-remove obvious junk

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| File metadata | Creation dates, sources | File dates only |
| Browser history | Download sources | Filename analysis |
| File content | Purpose identification | Extension-based |

---

## Output Location

```
output/
├── organized/
│   ├── documents/
│   ├── images/
│   ├── installers/
│   └── archives/
├── archive/
├── trash-candidates/
└── downloads-report.md
```

---

## Examples

### Example 1: Full Excavation
**Input**: 2,000 files spanning 3 years

**Output**:
- Categorized by type and purpose
- 50 important files identified
- 1,200 safe-to-delete items
- Recovery of forgotten resources

### Example 2: Quick Cleanup
**Input**: Current Downloads folder

**Output**:
- Duplicates identified
- Temporary files flagged
- Recent important files highlighted
- Space savings calculated

### Example 3: Project Recovery
**Input**: "Find all files related to Project X"

**Output**:
- Related downloads gathered
- Timeline of downloads
- Missing files identified
- Project folder assembled

---

## What I Won't Do

- **Won't delete without approval**: Safety first
- **Won't move system files**: Protected locations
- **Won't access restricted folders**: Permission-based

---

## Tips for Best Results

1. **Start with analysis**: Review before organizing
2. **Set time boundaries**: Focus on recent first
3. **Check trash candidates**: Before bulk delete

---

*Part of Art of Fact Cowork Skill Library*
