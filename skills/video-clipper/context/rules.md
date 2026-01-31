# Video Clipper — Rules & Guidelines

## Output Formatting Rules

### clip-manifest.md Format
```markdown
# Clip Manifest

**Source**: [Video filename]
**Duration**: [Total length]
**Clips Generated**: [N]
**Generated**: [Date]

---

## Clips

### Clip 1: [Descriptive Title]
- **File**: clips/clip-001.mp4
- **Timestamp**: [Start] - [End] ([Duration])
- **Content**: [Description of what's in clip]
- **Thumbnail**: thumbnails/clip-001.jpg

**Transcript**:
> "[What's said in the clip]"

**ffmpeg command used**:
```
ffmpeg -i source.mp4 -ss [start] -to [end] -c copy clips/clip-001.mp4
```

---

### Clip 2: [Title]
...

---

## Index by Topic

| Topic | Clips |
|-------|-------|
| [Topic] | 1, 3, 5 |
| [Topic] | 2, 4 |
```

---

## Clip Selection Rules

### Good Clip Characteristics
- Clear audio/video
- Complete thought (not mid-sentence)
- Standalone value
- Natural start/end points

### Buffer Rules
- Default: 1 second before, 1 after
- Speech: Wait for sentence end
- Action: Include setup and resolution

### Duration Guidelines
- Social media: 15-60 seconds
- Highlights: 30-90 seconds
- Chapters: 2-5 minutes
- Full segments: As needed

---

## Technical Rules

### Quality Preservation
- Use `-c copy` when possible (no re-encode)
- Match source resolution
- Maintain frame rate
- Preserve audio quality

### Naming Convention
```
clip-001-[short-description].mp4
```

### Thumbnail Generation
```
ffmpeg -i clip.mp4 -ss 00:00:03 -frames:v 1 thumbnail.jpg
```

---

## Search Methods

### Transcript-Based
1. Transcribe audio
2. Search for keywords/phrases
3. Identify timestamp
4. Extract with buffer

### Scene-Based
1. Analyze visual changes
2. Detect key frames
3. Group by scene
4. Extract scenes

### Manual Timestamp
1. User provides approximate time
2. Find precise boundaries
3. Extract with refinement

---

## Quality Checklist

- [ ] Clip starts at natural point
- [ ] Clip ends at natural point
- [ ] Audio is clear
- [ ] No quality degradation
- [ ] Thumbnail is representative
- [ ] Manifest is complete

---

*Part of Art of Fact Cowork Skill Library*
