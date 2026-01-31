---
name: playground-builder
description: Creates interactive HTML playgrounds for automation workflows. Configure file organization, media processing, and receipt scanning visually, then copy the generated prompt.
---

# Automation Playground Builder

Creates self-contained HTML playgrounds that let users visually configure automation workflows, see a live preview, and copy out a ready-to-use prompt.

## When to use this skill

When the user wants to:
- Set up file organization rules (categories, naming, archive policies)
- Configure media processing settings (clip length, format, quality)
- Define receipt/expense scanning parameters

## How to use this skill

1. **Identify the playground type** from the user's request
2. **Load the matching template** from `templates/`:
   - `templates/file-organizer.md` — Configure file categorization and organization rules
   - `templates/media-processor.md` — Set up video/audio/image processing parameters
   - `templates/receipt-scanner.md` — Define expense categorization and export settings
3. **Follow the template** to build the playground
4. **Open in browser** with `open <filename>.html`

## Core requirements (every playground)

- **Single HTML file.** Inline all CSS and JS. No external dependencies.
- **Live preview.** Updates instantly on every control change.
- **Prompt output.** Natural language instruction, not a value dump.
- **Copy button.** Clipboard copy with "Copied!" feedback.
- **Sensible defaults + presets.** Include 3-5 named presets.
- **Dark theme.** System font for UI, monospace for values.

## Available templates

### File Organizer (`file-organizer.md`)
Configure file organization rules:
- Category definitions (Documents, Media, Code, Archives)
- Naming conventions (date prefix, project tags)
- Archive policy (age threshold, compression)
- Duplicate handling (keep newest, prompt, auto-merge)

### Media Processor (`media-processor.md`)
Set up media processing:
- Video: clip length, format, quality, thumbnail extraction
- Audio: format, bitrate, noise reduction
- Images: resize, format conversion, metadata handling

### Receipt Scanner (`receipt-scanner.md`)
Define expense processing:
- Categories (travel, meals, supplies, software)
- Tax flags (deductible, reimbursable)
- Export format (CSV, JSON, accounting software)
- Vendor recognition rules
