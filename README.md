# Time Books — Interactive Timeline

A companion artifact for this month's book club reading on clocks, longitude, and the making of modern time. Built to sit alongside five précis as a single visual map of the period.

**Live timeline:** https://smsteven8.github.io/time_books_timeline/

## What it is

An interactive HTML timeline with four parallel tracks:

- **Landes** — *Revolution in Time* (1983). The long evolution of mechanical timekeeping from Su Sung's eleventh-century water clock through the late-twentieth-century quartz crisis.
- **Sobel** — *Longitude* (1995). John Harrison's marine chronometers H1–H4 and the half-century institutional drama around them.
- **Wulf** — *Chasing Venus* (2012). The 1761 and 1769 transits of Venus and the first deliberately global scientific collaboration.
- **Scaffolding** — the broader scientific context of the eighteenth century: Newton, Hadley's octant, Mayer's lunar tables, the founding of Greenwich, the *Nautical Almanac*.

## How to read it

- **Hover** an event for a brief label.
- **Click** an event to pin its full description in the side panel.
- **Filter** by book using the checkboxes — dim out the lanes you want to set aside.
- **Zoom** with the three preset buttons:
  - *Full view* — Su Sung to quartz, the whole sweep.
  - *18th century* — Harrison's working life and the transit expeditions readable side by side.
  - *Transit window* — the densest part of the story, with the 1761–1769 transits visually anchored by a faint gold band.

## Why these four tracks

Sobel and Wulf both depend on Landes' clock revolution as their precondition. Without precision mechanical timekeeping there is no marine chronometer; without the chronometer (or the lunar-distance method it competed with) there is no synchronous timing of a transit ingress from Tahiti and Vardø and Pondicherry. The scaffolding lane shows what else had to be in place — Newton, telescopes, observatories, almanacs — for any of this to work.

The design intention is to make a structural argument visible: the eighteenth century looks crowded for a reason. Several long-running projects converged on a small window of time, and the world that came out of that window was metrically and temporally different from the one that went in.

## Companion précis

The timeline is one of six files in the book club folder. The précis files include the four listed above plus Zerubavel's *Hidden Rhythms* (on schedules and calendars as social construction) and Canales's *The Physicist and the Philosopher* (on Einstein, Bergson, and the twentieth-century split over what time even is).

## Credits and stack

Single-file HTML, vanilla JavaScript, hand-rolled SVG. No dependencies, no build step. Cosmographic palette: charcoal, slate blue, terracotta, antique gold, warm ivory.

Built as a companion to [The Schematism](https://seanstevenson.substack.com).
