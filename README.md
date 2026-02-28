# Sriman's Workflow

> A personal task management board with drag & drop, light/dark mode, and 4 workflow sections.

---

## Overview

**Sriman's Workflow** is a lightweight, browser-based task management application built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies, no build tools required. It provides a clean Kanban-style board that helps you organize your work across four structured workflow stages, with a professional and elegant interface that works right out of the box.

---

## Features

- **4 Workflow Sections** — Just Added, In Review, Pending, and Completed, each with a distinct color identity
- **Drag & Drop** — Smoothly drag tasks from any position on a card and drop them into any section; the card's color and label update instantly
- **Light & Dark Mode** — Toggle between themes with a single click; preference is saved across sessions
- **Add Tasks** — Every new task is added directly to the *Just Added* section to keep your workflow structured
- **Edit Tasks** — Use the pencil icon on any card to edit the title, description, or move it to a different section
- **Delete Tasks** — Remove any task instantly using the delete icon on the card
- **Persistent Storage** — All tasks are saved in the browser's local storage, so your data survives page refreshes
- **Smooth Animations** — Card entrance animations, modal spring transitions, hover lift effects, and drag placeholders
- **Responsive Design** — Works seamlessly on desktop and mobile devices
- **Zero Dependencies** — No npm, no libraries, no internet connection required to run

---

## Workflow Sections

| Section | Color | Purpose |
|---|---|---|
| Just Added | 🔵 Blue | All newly created tasks land here |
| In Review | 🟣 Purple | Tasks currently being reviewed or evaluated |
| Pending | 🟡 Yellow | Tasks waiting to be worked on |
| Completed | 🟢 Green | Finished tasks, shown with a strikethrough |

---

## How to Use

**Adding a Task**
1. Click the **+ Add Task** button in the top right
2. Enter a title and an optional description
3. Click **Add Task** — it will appear in the *Just Added* section

**Moving a Task**
- Drag and drop the card to any section using your mouse or touch
- Alternatively, click the ✏️ pencil icon and change the section from the dropdown

**Editing a Task**
- Click the ✏️ pencil icon on any task card
- Update the title, description, or section and click **Save Changes**

**Deleting a Task**
- Click the 🗑️ trash icon on any task card to remove it

**Switching Theme**
- Click the ☀️ / 🌙 button in the top right corner to toggle between light and dark mode

**Keyboard Shortcuts**
- `Ctrl + Enter` — Save task while the modal is open
- `Escape` — Close the modal

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, CSS variables for theming |
| Vanilla JavaScript | Drag & drop logic, state management, local storage |
| Google Fonts | DM Sans (body) + Fraunces (headings) |

---


## Live Demo

Hosted via GitHub Pages:
**[https://sriman1957.github.io/srimans-workflow/](https://sriman1957.github.io/srimans-workflow/)**

---

## Local Setup

No installation needed. Simply:

1. Download or clone this repository
2. Open `index.html` in any modern browser
3. Start organizing your tasks

---

<p align="center">
  Built with ❤️ by <strong>Sriman</strong>
</p>
<p align="center">
  © 2026 Sriman. All Rights Reserved.
</p>
