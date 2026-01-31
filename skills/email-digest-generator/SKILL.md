---
name: email-digest-generator
description: --- Analyzes email threads and conversations, identifies key information and action items, and produces condensed digests that let you catch...
---

# Email Digest Generator

**Create summarized email digests from high-volume inboxes.**

---

## What This Does

Analyzes email threads and conversations, identifies key information and action items, and produces condensed digests that let you catch up on email without reading everything.

| Output | What You Get |
|--------|--------------|
| digest.md | Summarized emails |
| action-items.md | Required responses |
| priority-list.md | What needs attention |

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
> "Create a digest of my unread emails"

### Option 2: Thread Summary
> "Summarize this email thread"

### Option 3: Weekly Catchup
> "What did I miss while on vacation?"

---

## What I Need From You

### Required
- **Emails to process**: Export or access

### Optional (Enhances Output)
- **Priority senders**: Who matters most
- **Topics of interest**: What to highlight
- **Time range**: Period to cover

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Email metadata | Sender, subject, date | Basic info |
| Thread analysis | Conversation flow | Individual emails |
| Content | Key points, actions | Subject lines only |

---

## Output Location

```
output/
├── digest.md
├── action-items.md
├── priority-list.md
└── archives/
    └── [date]-digest.md
```

---

## Examples

### Example 1: Daily Digest
**Input**: 50 unread emails

**Output**:
- 5 high-priority items
- 10 medium-priority summaries
- 35 low-priority mentions
- 8 action items identified

### Example 2: Thread Summary
**Input**: 30-email thread

**Output**:
- Key decisions made
- Outstanding questions
- Action items by person
- Current status

### Example 3: Vacation Catchup
**Input**: 500 emails over 2 weeks

**Output**:
- Critical items (needed immediate response)
- Important updates
- FYI items
- Safe to archive

---

## What I Won't Do

- **Won't send responses**: Summaries only
- **Won't delete emails**: Read-only
- **Won't access without permission**: Authorized only

---

## Tips for Best Results

1. **Define VIP senders**: Always highlight
2. **Set topic priorities**: Filter noise
3. **Process regularly**: Prevents overwhelm

---

*Part of Art of Fact Cowork Skill Library*
