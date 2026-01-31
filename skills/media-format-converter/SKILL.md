---
name: media-format-converter
description: --- Converts video, audio, and image files between formats. Handles batch conversions, preserves quality, and provides options for compression. Never...
---

# Media Format Converter

**Batch convert media files between formats while preserving quality.**

---

## What This Does

Converts video, audio, and image files between formats. Handles batch conversions, preserves quality, and provides options for compression. Never deletes originals without confirmation.

| Output | What You Get |
|--------|--------------|
| converted/ | Files in new format |
| conversion-report.md | What was converted |

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
> "Convert these videos to MP4"

### Option 2: Batch Mode
> "Convert all MOV files in folder to MP4"

### Option 3: Audio Extraction
> "Extract audio from these videos as MP3"

---

## What I Need From You

### Required
- **Source files**: Media to convert
- **Target format**: What format to output

### Optional (Enhances Output)
- **Quality settings**: Bitrate, resolution
- **Batch rules**: All files of type X
- **Keep originals**: Yes/no

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| ffmpeg | Media processing | Required |

---

## Output Location

```
output/
├── converted/
│   └── [converted files]
└── conversion-report.md
```

---

## Examples

### Example 1: Video Format
**Input**: 10 MOV files from iPhone

**Output**:
- Converted to MP4 (H.264)
- Quality preserved
- Much smaller file sizes

### Example 2: Audio Conversion
**Input**: FLAC music files

**Output**:
- Converted to MP3 320kbps
- Or to AAC for Apple
- Metadata preserved

### Example 3: Image Batch
**Input**: 50 PNG screenshots

**Output**:
- Converted to WebP
- 70% smaller
- Quality maintained

---

## What I Won't Do

- **Won't delete originals**: Without explicit permission
- **Won't upscale**: Can't add quality
- **Won't lose data silently**: Warn about lossy conversion
- **Won't convert DRM**: Only your own content
- **Won't exceed source quality**: Output ≤ input quality

---

## Tips for Best Results

1. **Know your target use**: Web vs archive affects settings
2. **Test before batch**: Convert one file first
3. **Consider quality needs**: Archive vs sharing
4. **Check compatibility**: Target platform requirements
5. **Keep originals until confirmed**: Safety first

---

## Troubleshooting

### "Quality is worse"
Try higher quality settings or lossless format.

### "File is larger"
Some conversions increase size. Try different codec.

### "Won't play on device"
Check device compatibility. May need different codec.

### "Missing audio/video"
Check if source had both. Some files are audio/video only.

---

*Part of Art of Fact Cowork Skill Library*
