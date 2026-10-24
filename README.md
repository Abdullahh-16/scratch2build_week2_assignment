# Scratch2Build — Assignment #2
## Responsive Personal Dashboard UI (Vanilla CSS)

Build a modern, responsive personal dashboard using **HTML and plain CSS**. This assignment practices CSS layout, the Box Model, Flexbox, CSS Grid, responsive breakpoints, and CSS custom properties.

> **Deadline:** Wednesday at 11:59 PM. Organizers should confirm the exact calendar date and time zone before publishing this repository.

## Requirements

### 1. Page structure
Your dashboard must include:
- Sidebar navigation
- Header bar
- Main analytics grid
- Recent activity feed

### 2. Layout
- Use **CSS Flexbox** to align the header and navigation elements.
- Arrange dashboard cards with a responsive **CSS Grid**, using a pattern such as `repeat(auto-fit, minmax(...))`.
- Include at least one mobile `@media` breakpoint.
- At a 375px viewport width, the page must fit without horizontal scrolling.

### 3. Theme tokens
- Define design/color variables on `:root`, for example `--color-bg` and `--color-text`.
- All CSS color values used by the UI must come from CSS custom properties with `var(--...)`.

### 4. Constraints
- Use HTML and vanilla CSS only.
- Do **not** use Bootstrap, Tailwind, Bulma, or JavaScript UI plugins.
- Check your layout with browser DevTools at desktop and mobile sizes.

## Files
- `index.html` — page structure and sample dashboard content.
- `style.css` — starter CSS. Complete the layout and responsive rules yourself.

## GitHub workflow
Use the branch name required by the assignment: `feature/responsive-dashboard`.

1. Start from the repository's `main` branch.
2. Create the assignment branch:
   ```bash
   git checkout main
   git pull origin main
   git checkout -b feature/responsive-dashboard
   ```
3. Work on `index.html` and `style.css`.
4. Preview the page in a browser and test at 375px width.
5. Stage and commit your changes:
   ```bash
   git add index.html style.css
   git commit -m "Build responsive dashboard UI"
   ```
6. Push the branch:
   ```bash
   git push -u origin feature/responsive-dashboard
   ```
7. On GitHub, open a Pull Request with **base: `main`** and **compare: `feature/responsive-dashboard`**. Add a clear title and summary, then submit it before the confirmed deadline.
8. If a reviewer requests changes, push additional commits to the same branch; they will appear in the open PR.

> If all students share one repository, confirm with the organizers whether each student should work in a fork or use a unique branch name. The required branch name above follows the assignment PDF.

## Pull Request checklist
Before opening your PR, confirm:
- [ ] Sidebar, header, analytics grid, and activity feed are present.
- [ ] Flexbox is used for header/navigation alignment.
- [ ] Analytics cards use responsive CSS Grid with `repeat(auto-fit, minmax(...))`.
- [ ] A mobile media query is included.
- [ ] The layout works at 375px without horizontal scrolling.
- [ ] UI colors use variables defined on `:root`.
- [ ] No prohibited frameworks or UI plugins are used.
- [ ] The PR targets `main` and describes the changes.

## Suggested PR description
**What I built**
- 

**Responsive checks**
- [ ] Desktop
- [ ] Mobile (375px)

**Notes / questions for reviewer**
- 
