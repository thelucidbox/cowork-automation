---
name: literature-mapper
description: --- Analyzes collections of sources, identifies themes and connections, creates citation networks, and generates visual maps of how literature in...
---

# Literature Mapper

**Map relationships between sources and create visual literature landscapes.**

---

## What This Does

Analyzes collections of sources, identifies themes and connections, creates citation networks, and generates visual maps of how literature in a field relates and evolves over time.

| Output | What You Get |
|--------|--------------|
| literature-map.md | Connection overview |
| theme-clusters/ | Grouped by topic |
| citation-network.md | Who cites whom |

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
> "Map the literature on machine learning ethics"

### Option 2: From Sources
> "Create a literature map from my collected sources"

### Option 3: Gap Analysis
> "What's missing from my literature review?"

---

## What I Need From You

### Required
- **Sources or topic**: Literature to map

### Optional (Enhances Output)
- **Time range**: Period to cover
- **Key authors**: Central figures
- **Your focus**: Specific questions

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Citation data | Network connections | Manual links |
| Abstracts | Theme extraction | Title analysis |
| Publication dates | Timeline | — |

---

## Output Location

```
output/
├── literature-map.md
├── theme-clusters/
│   ├── theme-1/
│   ├── theme-2/
│   └── theme-3/
├── citation-network.md
└── timeline.md
```

---

## Claude Artifacts (Interactive)

Ask Claude to create interactive artifacts you can use and return to:

| Artifact Type | What It Does | How to Request |
|---------------|--------------|----------------|
| **Literature Map** | Visual network of papers and their connections | "Create a literature map artifact" |
| **Theme Explorer** | Interactive clusters you can drill into | "Build a theme explorer artifact" |
| **Citation Network** | See who cites whom in your field | "Make a citation network artifact" |
| **Timeline View** | How the field evolved over time | "Create a literature timeline artifact" |

### Example Artifact Requests

**Interactive Literature Map**
> "Create a React artifact showing papers as nodes, with connections between related works—let me click to see details"

**Theme Cluster View**
> "Build an interactive view where themes are expandable clusters—click to see papers in each theme"

**Research Timeline**
> "Create a timeline artifact showing major papers by year, with foundational works highlighted"

### Tips
- Start with seminal papers as anchors for your map
- Use the theme explorer to find gaps in the literature
- The timeline helps identify emerging vs established areas

---

## Examples

### Example 1: Field Overview
**Input**: "Map AI safety research"

**Output**:
- Major themes identified
- Key papers per theme
- Influential authors
- Evolution over time
- Research gaps

### Example 2: Source Analysis
**Input**: 50 collected papers

**Output**:
- Clustering by methodology
- Citation relationships
- Foundational vs recent
- Theme emergence timeline

### Example 3: Research Positioning
**Input**: Your research area

**Output**:
- Where you fit in landscape
- Related work clusters
- Gaps you could fill
- Suggested citations

---

## What I Won't Do

- **Won't read full papers**: Metadata-based
- **Won't access paywalled**: Public info only
- **Won't fabricate connections**: Evidence-based

---

## Tips for Best Results

1. **Start with key papers**: Build network out
2. **Identify seminal works**: Anchors the map
3. **Update periodically**: Fields evolve

---

*Part of Art of Fact Cowork Skill Library*
