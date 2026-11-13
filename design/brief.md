# Design brief

Source: the interview, without Stitch
Mood: curious, fresh, bright. Technical and precise with playful warmth: monospace details, clean lines, and petroglyph-inspired geometric accent motifs.

## Style

- Style: Technical, with a Playful touch: rounded sticker badges.
- Feel: curious, fresh, bright.
- Personal detail: a stylized ancient petroglyph solar/animal symbol as a subtle geometric divider icon between major sections.
- Motion: crisp and functional: state changes, subtle spring on hover. When the visitor prefers reduced motion, nothing moves.

## Colours

| Token | Light | Dark | Used for |
|---|---|---|---|
| background | #f6f7f9 | #0d1117 | page background: cool white, with a faint dot grid |
| surface | #f1f3f6 | #161b22 | cards |
| text | #161b22 | #e6edf3 | headings and body text |
| muted | #57606a | #9198a1 | dates, labels, file names, borders |
| accent | #0f766e | #38bdf8 | links, focus ring: deep teal (light) / bright cyan-teal (dark) |
| on-accent | #ffffff | #0d1117 | text on an accent-coloured button |

## Type

| Role | Font | Size | Weight |
|---|---|---|---|
| headings | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | name 2rem, section 1.125rem, project 1rem | 600 |
| body | "IBM Plex Sans", system-ui, sans-serif | 1rem, line height 1.6 | 400 |
| details | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | dates and labels 0.875rem | 400 |

## Shapes

- Corner radius: 4px for cards, pill shapes for event/status badges.
- Borders: 1px in the muted colour thinned out, around cards.
- Shadows: none.

## Layout

- One column, at most 46rem, centred, with 1.25rem space at the sides on phones; a faint dot grid behind the page.
- 3rem between sections, 1rem between items in a list.
- Projects: cards with a 1px border, two columns from 40rem.

## Components

- Links: accent colour, underlined; keyboard focus shows a 2px accent ring.
- Projects: surface background, 1px border, 1.25rem inner space, the title in the heading font.
- Skills: a monospace list written like an array: [ "C++", "Python", "Linux" ].
- Section headings: in the heading font, with "// " before them as decoration.

## Signature

- Move: Other cards step back on hover and focus
- Guide: guides/css/child-state-based-styling.md
- Where: the cards: while one is pointed at or focused, the others step back.

## Sections

1. `bio`: the name, headline, pitch, availability, and bio.
2. `events`: tech community leadership, workshops, and speaking.
3. `links`: GitHub, LinkedIn, and email.
4. `cv`: experience, education, and skills.
