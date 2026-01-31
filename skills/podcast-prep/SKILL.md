---
name: podcast-prep
description: --- Takes raw audio recordings—interviews, solo episodes, recordings—and processes them into podcast-ready files. Normalizes volume levels, removes silence, reduces background...
---

# Podcast Prep

**Process raw audio into podcast-ready files with normalized volume and noise reduction.**

---

## What This Does

Takes raw audio recordings—interviews, solo episodes, recordings—and processes them into podcast-ready files. Normalizes volume levels, removes silence, reduces background noise, and optionally adds intro/outro. Professional quality output from amateur recordings.

| Output | What You Get |
|--------|--------------|
| podcast-ready.mp3 | Processed audio file |
| transcript.md | Text transcript |
| processing-log.md | What was done |

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
> "Process this recording for podcast"

### Option 2: Batch Mode
> "Prep all audio files in input for podcast"

### Option 3: Specific Processing
> "Normalize volume and remove silence from this audio"

---

## What I Need From You

### Required
- **Audio file**: Raw recording

### Optional (Enhances Output)
- **Intro/outro files**: To add automatically
- **Processing preferences**: What adjustments to make
- **Output format**: mp3, wav, etc.
- **Target loudness**: Specific LUFS target

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| ffmpeg | Audio processing | Required |
| Sox/Audacity | Advanced processing | Basic processing |

---

## Output Location

```
output/
├── podcast-ready.mp3      # Final processed audio
├── transcript.md          # Optional transcript
└── processing-log.md      # What was processed
```

---

## Examples

### Example 1: Interview Recording
**Input**: Raw 45-minute interview, uneven levels

**Output**:
- Volume normalized (-16 LUFS)
- Long silences reduced
- Background hum removed
- Intro/outro added

### Example 2: Solo Episode
**Input**: Voice memo recording with background noise

**Output**:
- Noise reduction applied
- Volume boosted and normalized
- Mouth clicks reduced
- Export-ready

### Example 3: Multi-Track
**Input**: Separate host and guest tracks

**Output**:
- Tracks combined
- Levels balanced
- Crossfades smoothed
- Single file output

---

## What I Won't Do

- **Won't change content**: Audio processing only
- **Won't auto-publish**: Prepare files, you publish
- **Won't fix unfixable**: Some recordings can't be rescued
- **Won't add music without rights**: You provide licensed audio
- **Won't delete originals**: Always preserve source

---

## Tips for Best Results

1. **Best input = best output**: Good recordings process better
2. **Provide specs**: "Match my other episodes at -16 LUFS"
3. **Include intro/outro**: For automatic assembly
4. **Note problem areas**: "There's a loud noise at 23:15"
5. **Check output on multiple devices**: Before publishing

---

## Troubleshooting

### "Volume is too quiet/loud"
Specify target: "-14 LUFS for YouTube" or "-16 LUFS for podcasts"

### "Too much noise reduction"
Ask for lighter processing: "Gentle noise reduction only"

### "Missing parts"
Silence removal may be too aggressive. Adjust thresholds.

### "Processing artifacts"
Some recordings are challenging. Try less aggressive settings.

---

*Part of Art of Fact Cowork Skill Library*
