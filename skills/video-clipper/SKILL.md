---
name: video-clipper
description: --- Takes a video file and finds specific moments based on your natural language description. Uses transcription and scene analysis...
---

# Video Clipper

**Find and extract video clips based on content description.**

---

## What This Does

Takes a video file and finds specific moments based on your natural language description. Uses transcription and scene analysis to locate clips, then extracts them with quality preserved. Perfect for finding key quotes, highlights, or memorable moments.

| Output | What You Get |
|--------|--------------|
| clips/ | Extracted video clips |
| clip-manifest.md | Index of all clips |
| thumbnails/ | Preview images |

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
> "Find the part where she talks about AI safety"

### Option 2: Time-Based
> "Extract 30-60 second clips from this interview"

### Option 3: Batch Mode
> "Find all quotable moments in this video"

---

## What I Need From You

### Required
- **Video file**: The source video
- **What to find**: Description of content to extract

### Optional (Enhances Output)
- **Clip length**: Target duration
- **Quality**: Resolution preference
- **Format**: Output format

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| ffmpeg | Video processing | Required for extraction |
| Transcription | Spoken content | Scene-only analysis |

---

## Output Location

```
output/
├── clips/
│   ├── clip-001.mp4
│   └── clip-002.mp4
├── clip-manifest.md
└── thumbnails/
    ├── clip-001.jpg
    └── clip-002.jpg
```

---

## Examples

### Example 1: Quote Extraction
**Input**: "Find where the CEO talks about company culture"

**Output**:
- Clip: 2:34-3:12 extracted
- Thumbnail at key moment
- Transcript of clip included

### Example 2: Highlight Reel
**Input**: "Extract the best 5 moments from this talk"

**Output**:
- 5 clips of peak moments
- Each with thumbnail
- Manifest with descriptions

### Example 3: Tutorial Segments
**Input**: "Split this tutorial into chapters"

**Output**:
- Multiple clips by topic
- Named by content
- Index for navigation

---

## What I Won't Do

- **Won't delete originals**: Clips are copies
- **Won't degrade quality**: Match source quality
- **Won't guess at unclear**: Ask for clarification
- **Won't exceed duration**: Respect video length
- **Won't process DRM**: Only your content

---

## Tips for Best Results

1. **Be specific**: "The part about X" beats "the good part"
2. **Note speakers**: "When Sarah speaks" helps targeting
3. **Provide context**: "From the Q&A section"
4. **Set buffer**: "Add 3 seconds before and after"
5. **Good source quality**: Output can't exceed input

---

## Troubleshooting

### "Clip isn't quite right"
Ask for "5 seconds earlier" or "extend by 10 seconds."

### "Can't find the moment"
Provide more context. Try: "Around the 10-minute mark when..."

### "Processing takes too long"
Long videos take time. Try specifying approximate timestamps.

### "Audio/video out of sync"
This usually means source file issue. Check original.

---

*Part of Art of Fact Cowork Skill Library*
