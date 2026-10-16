# The Cost of Caring Without Control

A short, research-informed resource for educators dealing with burnout: what it is, what drives it in teaching, three conditions that make it worse (low control, value conflict, unsupportive institutional response), and what the evidence does and does not support as helping.

Version 0.3, October 2026. Private prototype intended for a small audience.

## Contents

- `index.html` the whole reflection: conditions, what they cost, side-by-side reading, what helps
- `research.html` annotated library of 21 sources with evidence labels
- `methodology.html` editorial commitments, how the reflection lists and thresholds were built, limitations
- `sources.csv` the library as data (id, section, citation, url, type, evidence_label, scope_limitation)
- `assets/styles.css` the only stylesheet

## Editing

Plain HTML and one CSS file. The reflection page has a few dozen lines of inline JavaScript for the checkboxes and tally; nothing is stored or sent. No framework, build step, analytics, or external requests. Citations are `[R#]` links into `research.html`; if you add or renumber a source, update both `research.html` and `sources.csv`.

## Hosting

The site runs from a local folder as is. If it is ever published through GitHub Pages or similar, it becomes publicly reachable once deployed; keep it local while it is meant for a private audience.
