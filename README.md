# Flex-and-Grid

Practice exercises for CSS **Flexbox** and **Grid**, part of the Orange training track.
Each task is a standalone page (`.html` + matching `.css`) that recreates a target layout mockup.

## Tasks

### Task 1 — Multi-section page layout (Grid)
A full page layout built with CSS Grid: a top `Section 1` bar, a two-column middle area
(a left column with `section 2` / `section 3`, a right column with `Main Content` / `Extra Content`),
a `Related Images` / `Related Posts` row, and a `Footer`.
White page with a thin black border; nested grids handle the columns and rows.

- Files: `Task1.html`, `Task1.css`

### Task 2 — User list cards (Flexbox)
A rounded card listing four users, each row showing a circular profile image next to the
user's name and specialty, separated by dividers.
Each row uses Flexbox (`display: flex; align-items: center`) to align the avatar and text.

- Files: `Task2.html`, `Task2.css`
- Asset: `profilepic.png` (placeholder avatar)

### Task 3 — Header / Aside / Article / Footer (Grid)
A classic page layout in CSS Grid: a teal `Header`, a green `Aside` sidebar beside an orange
`Article` containing three `Image` boxes, and a teal `Footer`.
Light-blue page, rounded corners; the main area is a `1fr 2fr` grid and the images are a
`repeat(3, 1fr)` grid.

- Files: `Task3.html`, `Task3.css`

## Running

No build step or dependencies — just open any task in a browser:

```
open Task1.html   # or Task2.html / Task3.html
```
