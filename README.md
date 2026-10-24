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

## GitHub Workflow

Each participant must work on their own fork of this repository.

### 1. Fork the Repository

Click the **Fork** button on GitHub to create your own copy of this repository.

### 2. Clone Your Fork

Clone your fork to your computer:

```bash
git clone <YOUR_FORK_URL>
cd scratch2build-responsive-dashboard
```

Replace `<YOUR_FORK_URL>` with the URL of your own fork.

### 3. Create the Required Branch

```bash
git checkout main
git pull origin main
git checkout -b feature/responsive-dashboard
```

### 4. Complete the Assignment

Edit `index.html` and `style.css`.

Test your dashboard in the browser at desktop and mobile sizes. Ensure that the layout works at a viewport width of 375px without horizontal scrolling.

### 5. Commit and Push Your Work

```bash
git add index.html style.css
git commit -m "Build responsive dashboard UI"
git push -u origin feature/responsive-dashboard
```

### 6. Open a Pull Request

On GitHub, open a Pull Request from your fork's `feature/responsive-dashboard` branch into the original repository's `main` branch.

Set the base repository to `FCAI-E-Club-Tech-Committee/scratch2build-responsive-dashboard`.

Use the Pull Request template and complete its checklist before submitting.

### 7. Handle Review Feedback

If a reviewer requests changes, make the necessary updates and push additional commits to the same branch. The commits will appear in your existing Pull Request.

### 8. Deadline

Submit your Pull Request before the official deadline announced by the organizers. Check the exact calendar date and time before submitting.


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
