# Podcast Prep — Rules & Guidelines

## Output Formatting Rules

### processing-log.md Format
```markdown
# Processing Log

**Source**: [Input filename]
**Output**: [Output filename]
**Processed**: [Date/time]

---

## Source Analysis

| Property | Value |
|----------|-------|
| Duration | [Length] |
| Sample Rate | [kHz] |
| Channels | [Mono/Stereo] |
| Format | [Format] |
| Peak Level | [dB] |
| RMS Level | [dB] |
| Noise Floor | [dB] |

---

## Processing Applied

### 1. Noise Reduction
- Type: [Algorithm]
- Strength: [Light/Medium/Heavy]
- Before/After noise floor: [dB] → [dB]

### 2. Normalization
- Target: [LUFS]
- Achieved: [LUFS]
- True Peak: [dB]

### 3. Silence Removal
- Threshold: [dB]
- Silences removed: [N]
- Duration change: [Original] → [New]

### 4. Assembly
- Intro added: [Yes/No] ([Duration])
- Outro added: [Yes/No] ([Duration])
- Crossfade: [Seconds]

---

## Output Specs

| Property | Value |
|----------|-------|
| Duration | [Length] |
| Format | [mp3/wav/etc] |
| Bitrate | [kbps] |
| Sample Rate | [kHz] |
| Loudness | [LUFS] |
| True Peak | [dB] |

---

## Commands Used

```bash
[Actual ffmpeg/sox commands]
```
```

---

## Processing Standards

### Loudness Targets
| Platform | Target LUFS | True Peak |
|----------|-------------|-----------|
| Podcast | -16 LUFS | -1.5 dB |
| YouTube | -14 LUFS | -1 dB |
| Spotify | -14 LUFS | -1 dB |
| Broadcast | -24 LUFS | -2 dB |

### Noise Reduction Levels
- **Light**: -6dB reduction, preserve dynamics
- **Medium**: -12dB reduction, standard
- **Heavy**: -18dB+ reduction, aggressive

### Silence Removal
- Threshold: -40 to -50 dB
- Minimum silence: 0.5-1 second
- Maximum silence: Keep for natural speech

---

## Processing Order

1. Noise reduction (before normalization)
2. Compression/limiting if needed
3. EQ (if needed)
4. Normalization
5. Silence adjustment
6. Intro/outro assembly
7. Final export

---

## Quality Checklist

- [ ] No clipping
- [ ] Consistent volume
- [ ] Noise acceptably reduced
- [ ] Natural silences preserved
- [ ] Transitions smooth
- [ ] Format correct
- [ ] Metadata added

---

*Part of Art of Fact Cowork Skill Library*
