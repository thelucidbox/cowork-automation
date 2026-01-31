---
name: photo-optimizer
description: --- Takes images and optimizes them for web use. Resizes to specified dimensions, compresses intelligently, and outputs web-ready files. Balances...
---

# Photo Optimizer

**Batch process images for web—resize, compress, and optimize while preserving quality.**

---

## What This Does

Takes images and optimizes them for web use. Resizes to specified dimensions, compresses intelligently, and outputs web-ready files. Balances file size and quality, preserves aspect ratios, and optionally keeps originals.

| Output | What You Get |
|--------|--------------|
| optimized/ | Web-ready images |
| optimization-report.md | Before/after comparison |

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
> "Optimize these images for web"

### Option 2: Specific Target
> "Resize images to 1200px wide for blog"

### Option 3: Batch Mode
> "Optimize all images in folder for fast loading"

---

## What I Need From You

### Required
- **Images**: Files to optimize

### Optional (Enhances Output)
- **Target size**: Max width/height
- **Quality level**: Balance of size vs quality
- **Format**: webp, jpg, png
- **Keep originals**: Yes/no

---

## What I'll Pull Automatically

| Integration | What I Get | Fallback |
|-------------|-----------|----------|
| Image processing | Resize and compress | — |

---

## Output Location

```
output/
├── optimized/
│   ├── image-1.webp
│   └── image-2.webp
└── optimization-report.md
```

---

## Examples

### Example 1: Blog Images
**Input**: 10 high-res photos (5MB each)

**Output**:
- Resized to 1200px wide
- Compressed to ~100KB each
- WebP format
- Total: 50MB → 1MB

### Example 2: Social Media
**Input**: Photos for Instagram

**Output**:
- Square crop option
- 1080x1080px
- Optimized for quality

### Example 3: Website Gallery
**Input**: 50 product photos

**Output**:
- Multiple sizes: thumb, medium, large
- WebP with JPG fallback
- Optimization report

---

## What I Won't Do

- **Won't upscale**: Can't add quality that isn't there
- **Won't lose originals**: Keep unless told otherwise
- **Won't over-compress**: Maintain acceptable quality
- **Won't change aspect ratio**: Unless specifically asked
- **Won't strip important metadata**: Preserve what matters

---

## Tips for Best Results

1. **Start with high quality**: Better source = better output
2. **Specify target use**: "For blog" vs "for social" matters
3. **Test quality level**: Preview before batch processing
4. **Consider WebP**: Smaller files, broad support
5. **Keep originals**: Until you're sure output is good

---

## Troubleshooting

### "Images are too blurry"
Reduce compression. Try quality 85 instead of 75.

### "Files still too large"
Try more aggressive settings or smaller dimensions.

### "Wrong aspect ratio"
Specify: "Keep original aspect ratio" or "Crop to square"

### "Lost image quality"
Check if originals are high enough quality. Can't create detail.

---

*Part of Art of Fact Cowork Skill Library*
