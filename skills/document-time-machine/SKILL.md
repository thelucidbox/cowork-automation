---
name: document-time-machine
description: --- Finds all versions of documents across your system, cloud backups, and email attachments. Reconstructs version history, identifies changes between...
---

# Document Time Machine

**Reconstruct document history and recover previous versions from scattered sources.**

---

## What This Does

Finds all versions of documents across your system, cloud backups, and email attachments. Reconstructs version history, identifies changes between versions, and helps recover lost content from previous iterations.

| Output | What You Get |
|--------|--------------|
| versions/ | All found versions |
| timeline/ | Version history |
| diffs/ | Change comparisons |
| recovery-report.md | Documentation |

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
> "Find all versions of my quarterly report"

### Option 2: Recovery Mode
> "Recover the version of proposal.docx from last month"

### Option 3: History View
> "Show me the evolution of this document"

---

## What I Need From You

### Required
- **Document name or pattern**: What to search for

### Optional (Enhances Output)
- **Date range**: When versions existed
- **Known locations**: Where to search
- **Content hints**: Text that was in lost version

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Local files | Current versions | — |
| Time Machine | Backup versions | — |
| Cloud storage | Synced versions | — |
| Email attachments | Sent versions | — |

---

## Output Location

```
output/
├── versions/
│   ├── v1_2024-01-01/
│   ├── v2_2024-01-15/
│   └── v3_2024-02-01/
├── timeline/
├── diffs/
└── recovery-report.md
```

---

## Examples

### Example 1: Lost Content Recovery
**Input**: "Find the paragraph I deleted from report.docx"

**Output**:
- 5 versions found across 3 months
- Deleted paragraph identified in v2
- Content extracted and highlighted
- Comparison showing what changed

### Example 2: Version Archaeology
**Input**: Critical contract document

**Output**:
- 12 versions spanning 2 years
- Change timeline documented
- Author attributions where available
- Final vs draft comparisons

### Example 3: Collaboration History
**Input**: Shared team document

**Output**:
- All contributor versions
- Email attachment copies
- Cloud sync history
- Consolidated timeline

---

## What I Won't Do

- **Won't modify originals**: Read-only recovery
- **Won't access unauthorized backups**: Permission required
- **Won't fabricate content**: Only found versions

---

## Tips for Best Results

1. **Know approximate dates**: Narrows search
2. **Check all locations**: Email, cloud, local
3. **Keep Time Machine active**: Best recovery source

---

*Part of Art of Fact Cowork Skill Library*
