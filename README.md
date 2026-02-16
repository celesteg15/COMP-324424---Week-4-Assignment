# Week 4 — Guided Build (Starter)

This folder is the **starter** for the Week 4 guided build.

## How to run

- Open `index.html` in your browser (no build step).

## What you will build

By editing `styles.css`, you will implement:

1) `.site-nav` as a wrapping flex row (`display: flex`, `flex-wrap`, `gap`)
2) `.layout` as a simple grid container (stacked by default)
3) `.card-grid` as a responsive grid gallery (`auto-fit` + `minmax`)
4) One breakpoint (recommended: `900px`) that makes list + detail side-by-side
5) One subtle motion cue + a `prefers-reduced-motion` fallback

## Compare with the finished demo

- See `04-layout-patterns-solution/`


## Week 4 Answers
1) What flex pattern you used (and where)
- For the Flexbox usage, I chose the Nav /  Toolbar. This makes the primary navigation act as a tool bar row that can even wrap on smaller screens.
- This was implementted in 'styles.css' under '.site-nav'


2) What grid pattern you used (and where)
- the grid pattern I chose was the list + detail layout, this made the main page layout ('.layout') a grid stacked by a default of 1 column that could become two on wider screens (left side list with the detail panel on the right)

3) What responsive behavior you implemented
I implemented the "card columns changing using 'auto-fit/minmax'**:
- screen gets wider, cards automatically flow into more columns
 Screen gets smaller, the grid will collapse down into fewer columns (into at min 1).
