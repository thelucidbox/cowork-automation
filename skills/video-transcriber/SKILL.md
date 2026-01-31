---
name: video-transcriber
description: --- Takes video files, extracts audio, and generates accurate transcripts. Outputs multiple formats including searchable markdown, SRT subtitles, and optionally...
---

# Video Transcriber

**Extract audio from videos and generate transcripts with optional subtitles.**

---

## What This Does

Takes video files, extracts audio, and generates accurate transcripts. Outputs multiple formats including searchable markdown, SRT subtitles, and optionally detects speakers. Creates a searchable index across all transcribed content.

| Output | What You Get |
|--------|--------------|
| transcripts/{name}.md | Markdown transcript |
| subtitles/{name}.srt | SRT subtitle file |
| transcript-index.md | Searchable index |

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
> "Transcribe this video"

### Option 2: Batch Mode
> "Transcribe all videos in folder"

### Option 3: Subtitles Only
> "Generate subtitles for this video"

---

## What I Need From You

### Required
- **Video files**: Files to transcribe

### Optional (Enhances Output)
- **Speaker names**: For speaker identification
- **Context**: Topic for accuracy
- **Language**: If not English
- **Format preferences**: Output format

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| ffmpeg | Audio extraction | Required |
| Transcription | Speech-to-text | — |

---

## Output Location

```
output/
├── transcripts/
│   └── video-name.md
├── subtitles/
│   └── video-name.srt
└── transcript-index.md
```

---

## Examples

### Example 1: Meeting Recording
**Input**: 1-hour meeting video

**Output**:
- Full transcript with timestamps
- Speaker labels (if distinguishable)
- SRT for video player
- Searchable text

### Example 2: Video Series
**Input**: 10 tutorial videos

**Output**:
- Individual transcripts
- Subtitle files
- Combined index
- Search across all videos

### Example 3: Podcast Video
**Input**: Video podcast episode

**Output**:
- Clean transcript
- Timestamps at paragraphs
- Export for show notes

---

## What I Won't Do

- **Won't guarantee 100% accuracy**: Review for critical use
- **Won't transcribe copyrighted**: Only your content
- **Won't add to video**: Subtitles are separate files
- **Won't translate**: Transcribe in source language
- **Won't identify unlabeled speakers**: Makes best guess

---

## Tips for Best Results

1. **Good audio = good transcript**: Clear recordings help
2. **Provide speaker names**: "Host is Sarah, guest is Mike"
3. **Note technical terms**: Jargon improves accuracy
4. **Review output**: Especially for names, numbers
5. **Batch similar content**: Consistency improves

---

## Troubleshooting

### "Transcript has errors"
Review and edit. Some terms need manual correction.

### "Speakers not identified"
Provide names: "Two speakers: host and guest"

### "Wrong language"
Specify: "This is in Spanish"

### "Missing sections"
Check if audio is clear in those sections.

---

*Part of Art of Fact Cowork Skill Library*
