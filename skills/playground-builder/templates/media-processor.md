# Media Processor Playground Template

Use this template when building a playground for configuring media processing settings.

## Layout

```
+------------------------+---------------------------+
|  Controls              |  Live Preview             |
|  ────────────────      |  (processing preview)     |
|  Media Type            |                           |
|  ○ Video               |  Input: video.mov (2:34)  |
|  ○ Audio               |  ─────────────────────    |
|  ○ Images              |  Output:                  |
|                        |  • clip_001.mp4 (0:30)    |
|  [Video Settings]      |  • clip_002.mp4 (0:30)    |
|  Clip Length           |  • thumbnail.jpg          |
|  Format                |                           |
|  Quality               |  Est. size: 45MB          |
+------------------------+---------------------------+
|  Prompt Output         |  [ Copy Prompt ]          |
+------------------------+---------------------------+
```

## Control specifications

### Video Controls
| Control | Type | Options | Default |
|---------|------|---------|---------|
| Clip Length | Slider | 15s - 5min | 30s |
| Format | Dropdown | MP4, WebM, MOV, GIF | MP4 |
| Quality | Slider | Low → Max | High |
| Extract Thumbnails | Checkbox | on/off | on |
| Thumbnail Interval | Slider | 1-60s | 10s |

### Audio Controls
| Control | Type | Options | Default |
|---------|------|---------|---------|
| Format | Dropdown | MP3, WAV, FLAC, AAC | MP3 |
| Bitrate | Slider | 128-320 kbps | 256 |
| Noise Reduction | Checkbox | on/off | off |
| Normalize Volume | Checkbox | on/off | on |

### Image Controls
| Control | Type | Options | Default |
|---------|------|---------|---------|
| Resize | Dropdown | Original, 1080p, 720p, Custom | Original |
| Format | Dropdown | JPEG, PNG, WebP | WebP |
| Quality | Slider | 60-100% | 85% |
| Strip Metadata | Checkbox | on/off | off |

## Presets

| Preset | Description |
|--------|-------------|
| Social Clips | 30s clips, MP4, high quality, thumbnails every 10s |
| Podcast Export | MP3 320kbps, normalized, noise reduced |
| Web Optimized | WebP, 720p, 80% quality, metadata stripped |
| Archive Quality | Original format, max quality, preserve metadata |

## Prompt output examples

**Video - Social Clips:**
> Process my video into 30-second clips in MP4 format at high quality. Extract thumbnails every 10 seconds. Optimize for social media sharing.

**Audio - Podcast:**
> Process the audio file for podcast distribution. Export as MP3 at 320kbps with volume normalization and noise reduction applied.
