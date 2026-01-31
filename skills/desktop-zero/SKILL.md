---
name: desktop-zero
description: --- Analyzes your cluttered desktop, categorizes files by type and purpose, moves them to appropriate locations, and establishes systems to...
---

# Desktop Zero

**Achieve and maintain a clean, organized desktop through intelligent file sorting.**

---

## What This Does

Analyzes your cluttered desktop, categorizes files by type and purpose, moves them to appropriate locations, and establishes systems to prevent future buildup. Transforms desktop chaos into organized calm.

| Output | What You Get |
|--------|--------------|
| Sorted files | Moved to proper homes |
| desktop-report.md | What went where |
| rules/ | Prevention guidelines |

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
> "Clean up my desktop"

### Option 2: Analysis First
> "What's cluttering my desktop?"

### Option 3: Maintenance Mode
> "Process today's desktop files"

---

## What I Need From You

### Required
- **Desktop access**: Permission to analyze

### Optional (Enhances Output)
- **Destination rules**: Where files should go
- **Keep list**: Files to leave on desktop
- **Action items**: Files needing attention first

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| File types | Sort categories | Extension-based |
| File names | Purpose detection | Generic sort |
| File dates | Urgency assessment | All equal |

---

## Output Location

```
output/
├── desktop-report.md
├── sorted/
│   ├── documents/ → ~/Documents
│   ├── images/ → ~/Pictures
│   ├── downloads/ → ~/Downloads
│   └── projects/ → ~/Projects
└── action-needed/
```

---

## Examples

### Example 1: Full Cleanup
**Input**: 200 files on desktop

**Output**:
- 180 files sorted to proper locations
- 15 files flagged for review
- 5 files kept (important/active)
- Desktop zero achieved

### Example 2: Weekly Maintenance
**Input**: 30 new files this week

**Output**:
- Auto-sorted by learned rules
- Quick decisions prompted
- Inbox zero maintained

### Example 3: Project Extraction
**Input**: Desktop with scattered project files

**Output**:
- Project files grouped
- Moved to project folders
- Links created if needed
- Project structure suggested

---

## What I Won't Do

- **Won't delete files**: Only sorts/moves
- **Won't move active work**: Preserves workflow
- **Won't hide problems**: Shows what needs attention

---

## Tips for Best Results

1. **Set destination rules**: Consistent sorting
2. **Review action items**: Don't ignore flagged files
3. **Weekly maintenance**: Prevents buildup

---

*Part of Art of Fact Cowork Skill Library*
