---
name: newsletter-assembler
description: --- Gathers content from specified sources, curates based on your criteria, formats into newsletter layouts, and produces ready-to-send email newsletters...
---

# Newsletter Assembler

**Compile curated newsletters from various content sources automatically.**

---

## What This Does

Gathers content from specified sources, curates based on your criteria, formats into newsletter layouts, and produces ready-to-send email newsletters or digests on any schedule.

| Output | What You Get |
|--------|--------------|
| newsletter.md | Formatted content |
| newsletter.html | Email-ready version |
| content-log.md | Source tracking |

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
> "Create this week's newsletter from my saved articles"

### Option 2: Curated
> "Build a newsletter on AI developments from the past week"

### Option 3: Team Update
> "Assemble our monthly team newsletter"

---

## What I Need From You

### Required
- **Content sources**: Where to pull from

### Optional (Enhances Output)
- **Sections**: Newsletter structure
- **Tone**: Voice and style
- **Length**: Target word count

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Saved articles | Curated content | Manual input |
| RSS feeds | Latest posts | — |
| Team updates | News items | Request from team |

---

## Output Location

```
output/
├── newsletter.md
├── newsletter.html
├── content-log.md
└── archives/
    └── [date]-newsletter.md
```

---

## Claude Artifacts (Interactive)

Ask Claude to create interactive artifacts you can use and return to:

| Artifact Type | What It Does | How to Request |
|---------------|--------------|----------------|
| **Newsletter Builder** | Drag-and-drop content sections into layout | "Create a newsletter builder artifact" |
| **Content Queue** | Stage content throughout the week | "Build a content queue artifact" |
| **Preview Card** | See how the newsletter will look | "Make a newsletter preview artifact" |
| **Archive Browser** | Browse past newsletters for reference | "Create a newsletter archive artifact" |

### Example Artifact Requests

**Newsletter Builder**
> "Create a React artifact where I can drag content blocks into sections: Top Story, Quick Hits, Resources, Commentary"

**Content Staging Queue**
> "Build an artifact where I can save links and notes throughout the week, then select what goes in this edition"

**Live Preview**
> "Create a preview artifact showing how the newsletter will render with current content"

### Tips
- Use the content queue to capture interesting items as you find them
- The builder makes assembly quick on newsletter day
- Preview before sending to catch formatting issues

---

## Examples

### Example 1: Industry Newsletter
**Input**: Tech news sources + commentary

**Output**:
- Top stories curated
- Brief summaries
- Your analysis added
- Links organized

### Example 2: Team Newsletter
**Input**: Project updates, wins, announcements

**Output**:
- Section per team/project
- Highlights featured
- Upcoming events
- Recognition section

### Example 3: Personal Digest
**Input**: Bookmarked articles, notes

**Output**:
- Themed sections
- Personal commentary
- Reading recommendations
- Follow-up actions

---

## What I Won't Do

- **Won't plagiarize**: Summaries and links only
- **Won't fabricate news**: Real sources only
- **Won't send without review**: Draft for approval

---

## Tips for Best Results

1. **Save content throughout week**: Better curation
2. **Define clear sections**: Consistent structure
3. **Add your voice**: Makes it personal

---

*Part of Art of Fact Cowork Skill Library*
