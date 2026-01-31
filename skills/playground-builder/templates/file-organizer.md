# File Organizer Playground Template

Use this template when building a playground for configuring file organization rules.

## Layout

```
+------------------------+---------------------------+
|  Controls              |  Live Preview             |
|  ────────────────      |  (folder tree mockup)     |
|  Categories            |                           |
|  Naming Convention     |  📁 Organized/            |
|  Archive Policy        |  ├── 📁 Documents/        |
|  Duplicate Handling    |  │   └── 2024-01-report.pdf│
|                        |  ├── 📁 Media/            |
|  Presets               |  └── 📁 Archives/         |
+------------------------+---------------------------+
|  Prompt Output         |  [ Copy Prompt ]          |
+------------------------+---------------------------+
```

## Control specifications

| Control | Type | Options | Default |
|---------|------|---------|---------|
| Categories | Multi-checkbox | Documents, Media, Code, Archives, Projects | All |
| Naming | Dropdown | Date Prefix, Project Tags, Original, Smart | Date Prefix |
| Archive After | Slider | 30-365 days | 90 days |
| Compression | Checkbox | on/off | on |
| Duplicates | Radio | Keep Newest, Prompt, Auto-merge | Keep Newest |
| Preserve Structure | Checkbox | on/off | off |

## Presets

| Preset | Description |
|--------|-------------|
| Downloads Cleanup | All categories, date prefix, 30-day archive |
| Project Organizer | Projects focus, project tags, preserve structure |
| Media Library | Media focus, smart naming, no compression |
| Minimal | Documents only, original names, 180-day archive |

## Prompt output examples

**Standard:**
> Organize my files into Documents, Media, Code, and Archives categories. Use date-prefix naming (YYYY-MM-filename). Archive files older than 90 days with compression. For duplicates, keep the newest version.

**Project Organizer:**
> Organize files by project with project-tag naming. Preserve existing folder structure within each project. Archive completed projects after 180 days.
