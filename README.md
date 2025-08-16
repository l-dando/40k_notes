# 40K Notes

## Starter Obsidian Vault Layout
Below is a recommended folder structure, note templates, and tagging scheme to kickstart your Horus Heresy vault. Feel free to adapt names or hierarchy to suit your workflow

## 1. Vault Folder Structure
```
HorusHeresyVault/
├── 00-Inbox
├── 01-References
│   ├── Bibliography.md
│   └── Lexicon/
├── 02-Books
│   ├── Templates/
│   │   └── Book Template.md
│   └── The First Heretic.md
├── 03-Characters
│   ├── Templates/
│   │   └── Character Template.md
│   └── Lorgar Aurelian.md
├── 04-Timeline
│   ├── Templates/
│   │   └── Timeline Entry Template.md
│   └── Master Timeline.md
├── 05-Themes
│   └── Themes Index.md
├── 06-Maps & Diagrams
│   └── Segmentum Ultima Map.md
├── 07-Reflections
│   └── Quarterly Synthesis.md
└── 08-Dashboard.md
```

## Key Note Templates
### 2.1 Book Template (02-Books/Templates/Book Template.md)
```
---
type: book
title: 
author: 
order: 
date-started: 
date-finished: 
tags: [book, heresy, #in-progress]
---

# {{title}}

## Chapter Summaries
1. 
2. 
...

## Major Events
- **In-Universe Date**:  
  **Event**:  
  **Significance**:  

## Key Characters
- [[Character Name]] — brief role

## Themes & Motifs
- 

## Memorable Quotes
> “...” — why it matters

## Questions & Theories
1. 
2. 
```

### 2.2 Character Template (03-Characters/Templates/Character Template.md)
```
---
type: character
name: 
legion: 
status: [active, fallen, renegade]
tags: [character, primarch]
---

# {{name}}

## Affiliation
- Legion/Faction: 

## Role & Arc
- Introduction:  
- Key Appearances:  
- Fate/Status:  

## Relationships
- [[Other Character]] — nature of bond

## Quotes & Moments
> “...” (source)

## Notes
-

```

### 2.3 Timeline Entry Template (04-Timeline/Templates/Timeline Entry Template.md)
```
---
type: timeline
date: 
event: 
source: [[Book Title]]
impact: 
tags: [timeline]
---

# {{date}} — {{event}}

**Source**:  
**Impact**:  
```

## 3. Dashboard and Tagging
- 08-Dashboard.md: a top-level note linking to your Inbox, Today’s Tasks, Active Book, and Quick Links.
- Core tags:
    - `#book`
    - `#character`
    - `#timeline`
    - `#theme`
    - `#in-progress / #completed`
- Use YAML frontmatter `type:` field to filter with Dataview or search queries

## Next Steps & Plugins
1. Enable Templater or QuickAdd for one-click note creation.
2. Install Dataview to build dynamic lists (e.g., all books tagged #in-progress).
3. Try Kanban plugin for “To Read / In Progress / Finished” boards.
4. Integrate Calendar or Periodic Notes for your quarterly syntheses.

```
With this layout, you’ll have a structured, interconnected vault that grows richer with every Horus Heresy volume.
```
Looking ahead, you might explore advanced Dataview queries to visualize character appearances across books or build a heatmap of chaos influence over the Crusade timeline.



