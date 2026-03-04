# Claude Code Course Site Simplification — Design

Date: 2026-03-04

## Context
The current course site is visually rich (hero, navigation, sidebar widgets, announcements, cards). Sophia requested a **very simple, academic-style** page.

## Goals
- Single-page layout.
- Keep only: **Title**, **Course description**, **Time**, **Syllabus (14 weeks)**, **Resources**, **Contact email**.
- Clean, academic, minimal design with strong readability.
- No navigation, no multi-page structure, no decorative sections.

## Non-goals
- No announcements, sidebars, hero sections, cards, or badges.
- No assignments page or multi-page navigation.
- No JS or dynamic behavior.

## Proposed Approach
- Replace `index.html` with a single-column page containing the required sections in order.
- Replace `style.css` with a minimal stylesheet focused on typography, spacing, and simple section headings.
- Use a max-width container (~760px) and generous whitespace.

## Content Structure (Order)
1. **Title** (H1) + course code/term subline
2. **Course description** (1–2 short paragraphs)
3. **Time / location** (single line)
4. **Syllabus** (14-week list; each line = week number + topic)
5. **Resources** (short bullet list)
6. **Contact** (email; placeholder until Sophia provides)

## Styling Guidelines
- Neutral background (#fff) and dark text.
- One typeface for body; optional serif for headings.
- Simple section dividers (subtle rule or spacing).
- No icons, badges, or colored panels.

## Placeholders
- Email: `email@example.edu` until provided.
- Time/location and course code/term: keep existing values unless updated.
