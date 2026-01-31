---
name: competitive-intel
description: --- Gathers publicly available information about competitors, analyzes their positioning, products, and strategies, and compiles actionable intelligence reports for business...
---

# Competitive Intel

**Research and compile competitive intelligence reports on companies and markets.**

---

## What This Does

Gathers publicly available information about competitors, analyzes their positioning, products, and strategies, and compiles actionable intelligence reports for business decision-making.

| Output | What You Get |
|--------|--------------|
| competitor-profiles/ | Individual analyses |
| market-overview.md | Landscape summary |
| intel-report.md | Strategic insights |

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
> "Research our top 5 competitors"

### Option 2: Deep Dive
> "Create a detailed profile on [Company Name]"

### Option 3: Market Scan
> "What's happening in the [industry] market?"

---

## What I Need From You

### Required
- **Competitors or market**: Who/what to research

### Optional (Enhances Output)
- **Your positioning**: For comparison
- **Key questions**: Specific intel needs
- **Focus areas**: Pricing, features, strategy

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Public websites | Product info, pricing | Manual research |
| News sources | Recent developments | Historical data |
| Job postings | Growth signals | — |

---

## Output Location

```
output/
├── competitor-profiles/
│   ├── company-a.md
│   ├── company-b.md
│   └── company-c.md
├── market-overview.md
└── intel-report.md
```

---

## Claude Artifacts (Interactive)

Ask Claude to create interactive artifacts you can use and return to:

| Artifact Type | What It Does | How to Request |
|---------------|--------------|----------------|
| **Competitive Landscape Map** | Visual positioning of competitors on key dimensions | "Create a competitive landscape artifact" |
| **Feature Comparison Grid** | Interactive matrix of features across competitors | "Build a feature comparison artifact" |
| **Threat Dashboard** | Track competitor moves and threat levels | "Make a competitive threat tracker" |
| **Pricing Comparison** | Visual pricing tiers and value comparison | "Create a pricing comparison artifact" |

### Example Artifact Requests

**Landscape Map**
> "Create a 2x2 positioning chart with Price (low/high) on X-axis and Features (basic/advanced) on Y-axis—plot our competitors and us"

**Feature Matrix**
> "Build an interactive feature comparison grid where I can mark which competitors have which features and see gaps"

**Threat Tracker**
> "Create a dashboard tracking each competitor with: threat level (1-5), recent moves, and our response status"

### Tips
- Update the landscape map quarterly as competitors shift positioning
- Use the feature matrix to identify differentiation opportunities
- The threat tracker helps prioritize competitive response

---

## Examples

### Example 1: Competitor Deep Dive
**Input**: "Analyze Competitor X"

**Output**:
- Product/service breakdown
- Pricing structure
- Target audience
- Strengths/weaknesses
- Recent moves

### Example 2: Market Landscape
**Input**: "SaaS project management tools"

**Output**:
- Top 10 players profiled
- Feature comparison matrix
- Pricing comparison
- Market positioning map
- Opportunity gaps

### Example 3: Quick Comparison
**Input**: "Compare us vs. Competitor Y"

**Output**:
- Side-by-side analysis
- Differentiators identified
- Competitive advantages
- Threat assessment

---

## What I Won't Do

- **Won't access private data**: Public sources only
- **Won't speculate without basis**: Evidence-based
- **Won't conduct espionage**: Ethical research only

---

## Tips for Best Results

1. **Be specific about focus**: Better targeted intel
2. **Provide your context**: Enables comparison
3. **Update regularly**: Markets change fast

---

*Part of Art of Fact Cowork Skill Library*
