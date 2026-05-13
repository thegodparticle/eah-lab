---
title: "Conference Talk at COTL 2026: Human in the Loop"
date: 2026-05-13
lastmod: 2026-05-13
authors:
  - admin
sitemap:
  priority: 0.6
  changefreq: yearly
tags:
  - Conference
  - Presentation
  - AI in Education
  - Canvas
  - Teaching
categories:
  - News
summary: "Dr. Arslan presented a faculty-directed AI workflow for building Canvas courses at USA's Conference on Teaching and Learning 2026."
links:
  - icon_pack: fas
    icon: display
    name: View Slides (fullscreen)
    url: "/presentations/cotl-2026/"
---

<p style="text-align: center; margin: 1rem 0 2rem 0;">
  <img src="https://www.southalabama.edu/departments/ilc/images/cotl2026horizontalcolor.png" alt="COTL 2026 logo" style="max-width: 420px; width: 100%; height: auto;" />
</p>

It was a pleasure to present at the **University of South Alabama Conference on Teaching and Learning 2026 (COTL 2026)** on May 13, 2026.

## Slides

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px; box-shadow: 0 6px 24px -10px rgba(28, 25, 23, 0.18); border: 1px solid #e7e5e4; margin: 1.5rem 0;">
  <iframe src="/presentations/cotl-2026/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" allowfullscreen title="Human in the Loop: Faculty-Directed AI for Canvas Course Development"></iframe>
</div>

*Use the arrow keys to navigate, press <kbd>F</kbd> for fullscreen, <kbd>S</kbd> for speaker notes, or <kbd>Esc</kbd> for the slide overview.*

My talk, *"Human in the Loop: Faculty-Directed AI for Canvas Course Development,"* walked through a workflow I have been using in my own graduate audiology courses.

## Talk Summary

Most faculty are already using AI for course work through a browser tab and copy-paste. It works, but every transfer is by hand, the format breaks on paste, and the AI never sees the actual course. The talk laid out a more systematic alternative: faculty define standards once in plain markdown, the AI proposes drafts directly against the live Canvas course, and nothing publishes until the faculty member types **yes**.

The workflow rests on three components:

- **Claude Code** as the runtime: an agentic application that reads project files and calls outside tools through a documented protocol.
- **canvas-mcp** as the bridge: an open-source server by Vishal Sachdev (UIUC) that translates between the Model Context Protocol on the AI side and the Canvas REST API on the LMS side.
- **Skills, hooks, and the GATE protocol** as the customization layer: faculty-authored markdown rules, automatic validators that fire on every write, and a four-letter yes/revise/skip/next pause at every phase boundary.

The talk also covered how this loop addresses the five hidden burdens behind every Canvas course (time, the expertise gap, design constraints, the April 2027 accessibility deadline, and maintenance), and demonstrated FERPA-aware behavior through canvas-mcp's source-level anonymization for student data.

## Session Details

**Research Talks Block · Room 212**

- **Time:** Wednesday, May 13, 2026 | 1:25–1:45 PM
- **Conference theme:** *Humans, Humanity, and the Humanities: Shaping Our Teaching and Learning Environments*
- **Location:** Student Center, University of South Alabama

---

*Thanks to the COTL 2026 organizers and the Innovation in Learning Center for an excellent conference, and to Vishal Sachdev for building and maintaining canvas-mcp as faculty-driven open source.*
