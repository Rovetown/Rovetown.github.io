Changelog

All notable changes to this project will be documented in this file.

The format is inspired by Keep a Changelog. Dates use local time.

### [1.0.0] - 2025-12-08

Summary
- Initial public release of the Relic Solver UI after iterative improvements. Earlier versions existed but are referenced simply as earlier versions.

Features and updates
- Experimental banner: clearly warns about experimental features at the top of the page.
- Informational "What this tool is for" block with clarified guidance:
  - Estimates the chance to at least reach a chosen outcome based on your resources.
  - Recommends setting non-zero targets for only 1–2 relic types.
  - Notes that setting 3–4 targets yields very low and often unrealistic probabilities.
  - Explicitly documents that the Divine Relic Cap is a shared max across Supernova Multiplier, Rainbow Floor Multi, and Fishing Ticks 5x; Rainbow Floor Chance is not limited by this cap.
- Layout improvements:
  - Introduced a `.narrow` utility to keep key sections from spanning full width.
  - Aligned banner, info block, progress bar, and output left for consistency.
  - Separated Inputs and Desired outcome into color‑coded sections for readability.
- Inputs section:
  - Fields: Total Relic Chests, Total Divine Chests, Divine Relic Cap.
  - Added an input help toggle with plain‑text explanations (mobile- and accessibility‑friendly).
  - Removed all tooltips from inputs.
- Desired outcome section:
  - Renamed from "Targets" to "Desired outcome" and removed “(target)” text from labels.
  - Fields: Rainbow Floor Chance, Supernova Multipliers, Rainbow Floor Multi, Fishing Ticks 5x Chance.
  - Added an outcome help toggle mirroring the input help.
  - Clarifies realistic usage (1–2 non‑zero targets) and the shared cap note.
- Solver run and feedback:
  - Run Solver button with progress bar and status text.
  - Output is hidden until a run completes; then shows probability and average gems until success.
  - Keeps UI responsive during long runs.

Notes on earlier versions
- Earlier versions existed prior to this 1.0.0 release; they are referred to as earlier versions.

---

Project: Rovetown.github.io — Relic Solver UI
