---
name: source-collector
description: --- Collects sources from various inputs (URLs, PDFs, notes), extracts key information, generates proper citations, and creates organized research bibliographies...
---

# Source Collector

**Gather, organize, and cite sources for research projects systematically.**

---

## What This Does

Collects sources from various inputs (URLs, PDFs, notes), extracts key information, generates proper citations, and creates organized research bibliographies with annotations and relevance ratings.

| Output | What You Get |
|--------|--------------|
| sources/ | Collected materials |
| bibliography.md | Formatted citations |
| source-notes.md | Annotated summaries |

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
> "Collect and organize my sources on climate change"

### Option 2: From URLs
> "Add these articles to my research sources"

### Option 3: Build Bibliography
> "Create a bibliography from my collected sources"

---

## What I Need From You

### Required
- **Sources**: URLs, files, or references

### Optional (Enhances Output)
- **Citation style**: APA, MLA, Chicago, etc.
- **Research topic**: For relevance assessment
- **Annotation needs**: Summary requirements

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| URLs | Article metadata | Manual entry |
| PDFs | Title, author, date | Filename |
| DOIs | Full citation data | Partial info |

---

## Output Location

```
output/
├── sources/
│   ├── articles/
│   ├── books/
│   └── other/
├── bibliography.md
└── source-notes.md
```

---

## Claude Artifacts (Interactive)

Ask Claude to create interactive artifacts you can use and return to:

| Artifact Type | What It Does | How to Request |
|---------------|--------------|----------------|
| **Source Library** | Browse and search all collected sources | "Create a source library artifact" |
| **Citation Generator** | Quick copy citations in different formats | "Build a citation generator artifact" |
| **Reading Tracker** | Track which sources you've read and noted | "Make a reading tracker artifact" |
| **Source Cards** | Key info from each source at a glance | "Create source card artifacts" |

### Example Artifact Requests

**Source Library Dashboard**
> "Create a React artifact showing all my sources: filterable by type (article/book/other), searchable, with quick access to citations"

**Citation Copier**
> "Build an artifact where I can select a source and copy its citation in APA, MLA, or Chicago format"

**Reading Progress**
> "Create a tracker showing sources with status: Not Read, Reading, Read, Noted—with progress stats"

### Tips
- Add sources as you find them to build your library over time
- Use the citation generator when writing to maintain consistency
- The reading tracker ensures you don't miss important sources

---

## Examples

### Example 1: Research Paper Sources
**Input**: 25 URLs and 10 PDFs

**Output**:
- All sources cataloged
- APA citations generated
- Annotated bibliography
- Relevance rankings

### Example 2: Literature Review
**Input**: Academic sources on topic

**Output**:
- Categorized by theme
- Key findings extracted
- Citation network mapped
- Gaps identified

### Example 3: Quick Citation
**Input**: Single article URL

**Output**:
- Full citation in requested format
- Quick summary
- Key quotes extracted

---

## What I Won't Do

- **Won't fabricate sources**: Real sources only
- **Won't plagiarize**: Proper attribution always
- **Won't access paywalled content**: Public info only

---

## Tips for Best Results

1. **Provide DOIs when available**: Best metadata
2. **Specify citation style early**: Consistent formatting
3. **Add notes as you go**: Better annotations

---

*Part of Art of Fact Cowork Skill Library*
