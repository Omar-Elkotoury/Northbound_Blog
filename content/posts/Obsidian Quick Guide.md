---
title: Obsidian Quick Guide
date: 2026-08-01
draft: false
tags:
  - blog
  - omar
---

## Table of Contents

1. Introduction
2. Installation
3. Interface
4. Markdown Essentials
5. Linking Knowledge
6. Plugins & Workflow
7. Best Practices

# 1. Introduction

![Obsidian Logo|652](https://obsidian.md/images/obsidian-logo-gradient.svg)

Obsidian is a local-first knowledge management application built around Markdown files. Every note is stored as a plain `.md` file, ensuring your knowledge remains portable, future-proof, and independent of any proprietary cloud platform.

> [!NOTE]
> Your notes belong to you. Obsidian never locks your data into a proprietary format.

### Key Features

| Feature | Benefit |
|---|---|
| Local Markdown | Own your data |
| Wikilinks | Connect ideas |
| Backlinks | Discover relationships |
| Graph View | Visualize your knowledge |
| Canvas | Visual brainstorming |
| Plugins | Extend functionality |

# 2. Installation

Download from https://obsidian.md

Supported platforms:
- Windows
- macOS
- Linux
- Android
- iOS

Create a **Vault**, which is simply a folder containing your Markdown notes.

Example:

```text
My Vault/
├── Inbox/
├── Projects/
├── Resources/
├── Archive/
├── Templates/
└── Attachments/
```

# 3. User Interface

![Interface](https://help.obsidian.md/attachments/app-ui.png)

Main components:

- File Explorer
- Search
- Editor
- Backlinks
- Outgoing Links
- Properties
- Graph View
- Command Palette

> [!TIP]
> Learn `Ctrl+P` early. It gives instant access to almost every command.

# 4. Markdown Essentials

```md
# Heading
## Heading

**Bold**
*Italic*

- Bullet
- [ ] Task

> Quote

`inline code`
```

Insert images:

```md
!![Image Description](/images/image.png)
```

Insert links:

```md
[[My Note]]
[[My Note|Custom Name]]
```

# 5. Building a Knowledge Graph

## Wikilinks

Internal links connect notes into a network.

```md
[[Atomic Habits]]
[[Programming]]
[[Machine Learning]]
```

## Backlinks

Backlinks automatically show every note that references the current note.

## Graph View

![Graph](https://help.obsidian.md/attachments/graph-view.png)

Graph View visualizes your vault as an interactive knowledge graph.

## Canvas

![Canvas](https://help.obsidian.md/attachments/canvas.png)

Canvas combines notes, PDFs, images, videos, and links on an infinite workspace.

# 6. Plugins & Productivity

Recommended Core Plugins:

- Daily Notes
- Templates
- Canvas
- Backlinks
- Bookmarks

Recommended Community Plugins:

| Plugin | Purpose |
|---|---|
| Dataview | Query notes |
| Tasks | Advanced task management |
| Templater | Dynamic templates |
| Excalidraw | Diagrams |
| Kanban | Project boards |
| Calendar | Planning |

Example Dataview:

```dataview
TABLE status
FROM "Projects"
```

# 7. Best Practices

> [!TIP]
> Create small notes containing one idea each.

Recommendations:

- Prefer links over folders.
- Use meaningful note titles.
- Review notes regularly.
- Use templates.
- Keep an Inbox folder.
- Store attachments separately.
- Tag sparingly.

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| Ctrl+P | Command Palette |
| Ctrl+O | Quick Switcher |
| Ctrl+Shift+F | Global Search |
| Ctrl+N | New Note |

## Obsidian vs Notion

| Feature | Obsidian | Notion |
|---|---|---|
| Offline | Yes | Limited |
| Local Files | Yes | No |
| Markdown | Native | Partial |
| Plugins | Extensive | Limited |

# Resources

- https://obsidian.md
- https://help.obsidian.md
- https://obsidian.md/plugins
- https://forum.obsidian.md

---

**Conclusion**

Obsidian is more than a note-taking application. It is a personal knowledge management system that helps you connect ideas, build long-term knowledge, and maintain complete ownership of your information through plain Markdown files.
