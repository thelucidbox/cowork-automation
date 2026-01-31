---
name: screenshot-cleaner
description: --- Takes a folder of screenshots and transforms chaos into organized, searchable archive. Uses OCR to read text content, renames...
---

# Screenshot Cleaner

**OCR screenshots, rename by content, organize by topic, and create searchable index.**

---

## What This Does

Takes a folder of screenshots and transforms chaos into organized, searchable archive. Uses OCR to read text content, renames files descriptively, groups by topic, removes duplicates, and creates a searchable index.

| Output | What You Get |
|--------|--------------|
| organized-screenshots/ | Renamed and organized |
| duplicates-removed.md | What was deduplicated |
| index.md | Searchable index |

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
> "Organize my screenshots"

### Option 2: Specific Folder
> "Clean up screenshots in ~/Desktop/Screenshots"

### Option 3: Search Mode
> "Find all screenshots about project X"

---

## What I Need From You

### Required
- **Screenshots**: Folder of screenshot images

### Optional (Enhances Output)
- **Topic categories**: How you want to organize
- **Naming preference**: Date-first, topic-first, etc.
- **Keep duplicates**: Or remove them

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| OCR | Text content from images | Visual-only analysis |
| File dates | Original capture time | Use file modified date |

---

## Output Location

```
output/
├── organized-screenshots/
│   ├── work/
│   ├── personal/
│   └── reference/
├── duplicates-removed.md
└── index.md
```

---

## Examples

### Example 1: Desktop Screenshot Cleanup
**Input**: 200 screenshots named IMG_XXXX.png

**Output**:
- Organized by content: Slack messages, error screens, references
- Renamed: 2024-01-15-slack-project-discussion.png
- 15 duplicates identified
- Searchable index by text content

### Example 2: Research Screenshots
**Input**: Screenshots from research session

**Output**:
- Grouped by source (website)
- Renamed with article title
- Index with extracted text

### Example 3: Work Evidence
**Input**: Screenshots for documentation

**Output**:
- Organized by project
- Chronological within project
- Index searchable by content

---

## What I Won't Do

- **Won't delete without permission**: Move to duplicates folder
- **Won't lose data**: Preserve dates, keep originals available
- **Won't misclassify**: Ask about uncertain items
- **Won't expose sensitive**: Flag and handle carefully
- **Won't over-organize**: Simple structure preferred

---

## Tips for Best Results

1. **Process regularly**: Weekly beats monthly cleanup
2. **Note sensitive content**: Will handle appropriately
3. **Define categories**: "Work, personal, reference"
4. **Keep duplicates folder**: Review before deleting
5. **Update index**: As you add new screenshots

---

## Troubleshooting

### "OCR isn't reading content"
Some images don't have text. Will categorize by visual content or ask.

### "Wrong categories"
Specify your categories and criteria.

### "False positive duplicates"
Similar screenshots marked. Review duplicates list.

### "Missing screenshots"
Check duplicates folder. Nothing is deleted automatically.

---

*Part of Art of Fact Cowork Skill Library*
