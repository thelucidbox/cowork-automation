---
name: semantic-file-tagger
description: --- Analyzes file contents, names, and metadata to generate meaningful tags and categories. Creates a searchable index of your files...
---

# Semantic File Tagger

**Automatically tag and categorize files based on their content and context.**

---

## What This Does

Analyzes file contents, names, and metadata to generate meaningful tags and categories. Creates a searchable index of your files based on what they actually contain, not just where they're stored.

| Output | What You Get |
|--------|--------------|
| tag-index.md | Searchable tag database |
| categories/ | Files grouped by topic |
| tag-cloud.md | Visual tag overview |

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
> "Tag all files in my Documents folder"

### Option 2: Specific Category
> "Find and tag all finance-related files"

### Option 3: Project Tagging
> "Tag files related to Project X"

---

## What I Need From You

### Required
- **Folder to analyze**: Location of files

### Optional (Enhances Output)
- **Tag vocabulary**: Preferred tags to use
- **Categories**: Predefined groupings
- **Exclude patterns**: Files to skip

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| File content | Topic extraction | Filename only |
| Filename | Keywords | Extension only |
| Metadata | Context clues | Basic info |

---

## Output Location

```
output/
├── tag-index.md
├── categories/
│   ├── finance/
│   ├── projects/
│   └── reference/
└── tag-cloud.md
```

---

## Examples

### Example 1: Document Library
**Input**: 500 mixed documents

**Output**:
- Tags: finance, contracts, reports, proposals
- Categories: Work, Personal, Legal, Reference
- Cross-references between related files

### Example 2: Project Files
**Input**: Project folder

**Output**:
- Phase tags: planning, development, review
- Type tags: specs, designs, code, docs
- Status tags: draft, final, archived

### Example 3: Research Materials
**Input**: Research collection

**Output**:
- Topic tags: AI, climate, economics
- Source tags: papers, articles, books
- Quality tags: primary, secondary, reference

---

## What I Won't Do

- **Won't move files**: Tags only, no reorganization
- **Won't modify files**: Read-only analysis
- **Won't tag system files**: User files only

---

## Tips for Best Results

1. **Define key categories first**: Better organization
2. **Start with important folders**: High-value tagging
3. **Review and refine tags**: Improve accuracy

---

*Part of Art of Fact Cowork Skill Library*
