# Video Transcriber — Rules & Guidelines

## Output Formatting Rules

### transcripts/{name}.md Format
```markdown
# Transcript: [Video Title]

**Source**: [Filename]
**Duration**: [Length]
**Transcribed**: [Date]
**Speakers**: [List]

---

## Summary
[Brief summary of content]

---

## Transcript

**[00:00]** [Speaker 1]: [Text]

**[00:30]** [Speaker 1]: [Continued text]

**[01:00]** [Speaker 2]: [Response text]

...

---

## Keywords
[Main topics/terms mentioned]
```

### subtitles/{name}.srt Format
```
1
00:00:00,000 --> 00:00:05,000
[First subtitle text]

2
00:00:05,500 --> 00:00:10,000
[Second subtitle text]

3
00:00:10,500 --> 00:00:15,000
[Third subtitle text]
```

### transcript-index.md Format
```markdown
# Transcript Index

**Videos**: [N]
**Total Duration**: [Hours]
**Generated**: [Date]

---

## Videos

| Video | Duration | Date | Topics |
|-------|----------|------|--------|
| [Name] | [Length] | [Date] | [Topics] |

---

## Search Index

### By Topic
- **[Topic]**: [Video 1], [Video 2]

### By Speaker
- **[Speaker]**: [Video list]

---

## Full Text Search

[Combined searchable text from all transcripts]
```

---

## Transcription Guidelines

### Timestamp Frequency
- Paragraphs: Every 30-60 seconds
- Subtitles: 3-7 seconds per caption

### Speaker Labeling
- Consistent labels: "Speaker 1" or names
- Change indication: New paragraph per speaker
- Unclear: "[unclear]" or "[inaudible]"

### Formatting
- Numbers: Spell out under 10
- Abbreviations: Spell out first use
- Filler words: Omit or include (preference)

---

## Quality Checklist

- [ ] Audio extracted cleanly
- [ ] Transcript is readable
- [ ] Timestamps accurate
- [ ] Speakers identified
- [ ] Subtitles timed correctly
- [ ] Index updated

---

*Part of Art of Fact Cowork Skill Library*
