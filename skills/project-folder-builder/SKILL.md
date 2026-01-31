---
name: project-folder-builder
description: --- Generates standardized project folder structures based on project type, complete with README templates, placeholder files, and organizational guidelines. Ensures...
---

# Project Folder Builder

**Create consistent, well-organized project folder structures instantly.**

---

## What This Does

Generates standardized project folder structures based on project type, complete with README templates, placeholder files, and organizational guidelines. Ensures every project starts with proper organization.

| Output | What You Get |
|--------|--------------|
| project-folder/ | Complete structure |
| README.md | Project documentation |
| templates/ | Starter templates |

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
> "Create a new project folder for a web app"

### Option 2: From Template
> "Set up a folder structure for a client project"

### Option 3: Custom Structure
> "Build a project folder with design, dev, and docs sections"

---

## What I Need From You

### Required
- **Project name**: What to call it
- **Project type**: Category/template to use

### Optional (Enhances Output)
- **Custom sections**: Additional folders needed
- **Team structure**: Collaboration needs
- **Timeline phases**: Project stages

---

## What I'll Pull Automatically

| Source | What I Get | Fallback |
|--------|-----------|----------|
| Project type | Template structure | Generic template |
| Team info | Collaboration folders | Single-user setup |
| Industry | Best practices | Standard structure |

---

## Output Location

```
output/
└── [project-name]/
    ├── README.md
    ├── 01-Planning/
    ├── 02-Research/
    ├── 03-Design/
    ├── 04-Development/
    ├── 05-Testing/
    ├── 06-Delivery/
    └── _Archive/
```

---

## Claude Artifacts (Interactive)

Ask Claude to create interactive artifacts you can use and return to:

| Artifact Type | What It Does | How to Request |
|---------------|--------------|----------------|
| **Project Setup Wizard** | Interactive form to configure your folder structure | "Create a project setup wizard artifact" |
| **Template Selector** | Browse and preview folder templates by project type | "Build a template browser artifact" |
| **Structure Visualizer** | Interactive tree view of your project organization | "Make a folder structure visualizer" |
| **Project Index** | Dashboard of all your projects with quick access | "Create a project index artifact" |

### Example Artifact Requests

**Project Setup Wizard**
> "Create a React form where I can enter project name, type, and custom sections—then show me the folder structure that will be created"

**Template Browser**
> "Build an artifact showing different project templates (Software, Client, Research, Creative) with previews of each structure"

**Structure Visualizer**
> "Create an interactive tree diagram of my project folder structure that I can expand/collapse"

### Tips
- Use the setup wizard to standardize how you create new projects
- The template browser helps teams agree on consistent structure
- Keep a project index artifact to quickly navigate between active projects

---

## Examples

### Example 1: Software Project
**Input**: "New mobile app project called FitTrack"

**Output**:
```
FitTrack/
├── README.md
├── docs/
├── design/
├── src/
├── tests/
├── assets/
└── releases/
```

### Example 2: Client Project
**Input**: "Client project for Acme Corp rebrand"

**Output**:
```
Acme-Rebrand/
├── README.md
├── 01-Brief/
├── 02-Research/
├── 03-Concepts/
├── 04-Revisions/
├── 05-Finals/
├── _Client-Feedback/
└── _Admin/
```

### Example 3: Research Project
**Input**: "Research project on market trends"

**Output**:
```
Market-Trends-Research/
├── README.md
├── sources/
├── data/
├── analysis/
├── drafts/
├── outputs/
└── references/
```

---

## What I Won't Do

- **Won't overwrite existing**: Creates new only
- **Won't add unnecessary files**: Clean structure
- **Won't enforce rigid structure**: Customizable

---

## Tips for Best Results

1. **Use descriptive names**: Clear project identity
2. **Choose right template**: Matches workflow
3. **Customize as needed**: Add/remove sections

---

*Part of Art of Fact Cowork Skill Library*
