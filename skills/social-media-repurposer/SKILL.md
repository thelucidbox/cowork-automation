---
name: social-media-repurposer
description: --- Takes long-form content (articles, presentations, videos) and repurposes it into multiple social media posts optimized for different platforms, with...
---

# Social Media Repurposer

**Transform content into platform-optimized social media posts.**

---

## What This Does

Takes long-form content (articles, presentations, videos) and repurposes it into multiple social media posts optimized for different platforms, with appropriate formatting, hashtags, and scheduling suggestions.

| Output | What You Get |
|--------|--------------|
| posts/ | Platform-specific content |
| content-calendar.md | Posting schedule |
| asset-list.md | Required images/media |

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
> "Turn this blog post into social media content"

### Option 2: Platform Specific
> "Create LinkedIn posts from my presentation"

### Option 3: Campaign Mode
> "Build a week of posts from this article"

---

## What I Need From You

### Required
- **Source content**: What to repurpose

### Optional (Enhances Output)
- **Platforms**: Where to post
- **Tone**: Brand voice
- **Schedule**: Posting frequency

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Content | Key points, quotes | Manual extraction |
| Platform specs | Character limits, formats | Standard defaults |
| Hashtag research | Relevant tags | Generic tags |

---

## Output Location

```
output/
├── posts/
│   ├── twitter/
│   ├── linkedin/
│   ├── instagram/
│   └── threads/
├── content-calendar.md
└── asset-list.md
```

---

## Claude Artifacts (Interactive)

Ask Claude to create interactive artifacts you can use and return to:

| Artifact Type | What It Does | How to Request |
|---------------|--------------|----------------|
| **Content Calendar** | Visual calendar showing what posts when | "Create a content calendar artifact" |
| **Post Preview Grid** | See all platform versions side by side | "Build a post preview artifact" |
| **Platform Optimizer** | Adjust content for each platform's specs | "Make a platform optimizer artifact" |
| **Campaign Tracker** | Track post performance and engagement | "Create a campaign tracker artifact" |

### Example Artifact Requests

**Content Calendar**
> "Create a React calendar artifact showing scheduled posts across platforms—color-coded by platform"

**Multi-Platform Preview**
> "Build an artifact showing the same content as it will appear on Twitter, LinkedIn, and Instagram side by side"

**Campaign Dashboard**
> "Create a tracker showing: posts scheduled, posts published, and placeholder for engagement metrics"

### Tips
- Use the calendar to maintain consistent posting cadence
- The preview grid helps catch platform-specific issues before posting
- Review the campaign tracker weekly to see what's working

---

## Examples

### Example 1: Blog to Social
**Input**: 2000-word blog post

**Output**:
- 5 Twitter/X threads
- 3 LinkedIn posts
- 10 individual tweets
- Instagram carousel concept
- Posting schedule

### Example 2: Presentation Repurpose
**Input**: 20-slide presentation

**Output**:
- Key insight posts
- Quote graphics list
- Slide-by-slide breakdown
- Video clip suggestions

### Example 3: Video Content
**Input**: 30-minute video

**Output**:
- Timestamp-based clips
- Quote extractions
- Teaser posts
- Full promotion campaign

---

## What I Won't Do

- **Won't post automatically**: Creates drafts only
- **Won't create images**: Lists what's needed
- **Won't guarantee virality**: Quality content only

---

## Tips for Best Results

1. **Provide key messages**: What matters most
2. **Specify brand voice**: Consistent tone
3. **Include call-to-action**: What should readers do

---

*Part of Art of Fact Cowork Skill Library*
