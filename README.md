# HTML & CSS Introduction Lab (BCS352)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

> **Course:** HTML and CSS Introduction Lab (`BCS352`)  
> **Degree:** Bachelor of Technology in Computer Science & Engineering (B.Tech CSE — 2nd Year)  
> **Institution:** Invertis University, Bareilly  
> **Student Name:** Hasan Mujtaba  

---

## 📖 Overview

This repository contains the complete practical coursework, code implementations, stylesheets, and execution outputs for the **HTML and CSS Introduction Lab (BCS352)**. 

The lab curriculum progresses from version control fundamentals with **Git** to core **HTML5 semantic structuring**, advanced **CSS3 styling**, modern layout techniques (**Flexbox** & **CSS Grid**), and **Mobile-First Responsive Web Design**.

---

## 📑 Table of Contents

- [Curriculum & Assignment Index](#-curriculum--assignment-index)
- [Detailed Assignment Breakdown](#-detailed-assignment-breakdown)
  - [Assignment 1: Starting a Git Repository](#assignment-1-starting-a-git-repository)
  - [Assignment 2: Pushing and Cloning a Repository](#assignment-2-pushing-and-cloning-a-repository)
  - [Assignment 3: Your First HTML Page](#assignment-3-your-first-html-page)
  - [Assignment 4: Divs, Attributes and a Small Fix](#assignment-4-divs-attributes-and-a-small-fix)
  - [Assignment 5: Links and Images](#assignment-5-links-and-images)
  - [Assignment 6: Types of HTML Lists](#assignment-6-types-of-html-lists)
  - [Assignment 7: About Me Page](#assignment-7-about-me-page)
  - [Assignment 8: Sign-Up Forms and Choices](#assignment-8-sign-up-forms-and-choices)
  - [Assignment 9: Tables with Headers and Footers](#assignment-9-tables-with-headers-and-footers)
  - [Assignment 10: CSS Fundamentals](#assignment-10-css-fundamentals)
  - [Assignment 11: Units and CSS Variables](#assignment-11-units-and-css-variables)
  - [Assignment 12: Box Model, Cards and Scrolling](#assignment-12-box-model-cards-and-scrolling)
  - [Assignment 13: Flexbox Layouts](#assignment-13-flexbox-layouts)
  - [Assignment 14: CSS Grid Layouts](#assignment-14-css-grid-layouts)
  - [Assignment 15: Responsive Pages with Media Queries](#assignment-15-responsive-pages-with-media-queries)
- [Project Directory Structure](#-project-directory-structure)
- [How to Run Locally](#-how-to-run-locally)
- [Technologies & Concepts](#-technologies--concepts)

---

## 📋 Curriculum & Assignment Index

| # | Assignment Title | Key Concepts & Topics | Directory |
|---|---|---|---|
| **01** | Starting a Git Repository | `git init`, `git config`, staging, commits, `git log` | [`Assignment1/`](./Assignment1/) |
| **02** | Pushing and Cloning a Repository | Bare repository, remotes (`origin`), `git push`, `git clone` | [`Assignment2/`](./Assignment2/) |
| **03** | Your First HTML Page | Basic structure, `<h1>`-`<h3>`, paragraphs, `<strong>`, `<em>`, `<br>` | [`Assignment3/`](./Assignment3/) |
| **04** | Divs, Attributes and a Small Fix | `<div>` grouping, classes, IDs, `data-*` attributes, syntax debugging | [`Assignment4/`](./Assignment4/) |
| **05** | Links and Images | Anchor tags (`<a>`), relative paths, `<img>`, `alt`, dimension attributes | [`Assignment5/`](./Assignment5/) |
| **06** | Types of HTML Lists | Unordered lists (`<ul>`), nested ordered lists (`<ol>`), description lists (`<dl>`) | [`Assignment6/`](./Assignment6/) |
| **07** | About Me Page | HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`), `mailto:` | [`Assignment7/`](./Assignment7/) |
| **08** | Sign-Up Forms and Choices | `<form>`, `<input>`, `<label>`, radio buttons, `<select>` dropdown, `required` validation | [`Assignment8/`](./Assignment8/) |
| **09** | Tables with Headers and Footers | `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, accessibility `scope` | [`Assignment9/`](./Assignment9/) |
| **10** | CSS Fundamentals | Inline, Internal (`<style>`), External (`<link>`) CSS, element/class/ID selectors | [`Assignment10/`](./Assignment10/) |
| **11** | Units and CSS Variables | Absolute (`px`) & relative (`%`, `rem`) units, CSS custom properties (`:root`, `var()`) | [`Assignment11/`](./Assignment11/) |
| **12** | Box Model, Cards and Scrolling | `content-box` vs `border-box`, `border-radius`, card UI, `overflow: auto` | [`Assignment12/`](./Assignment12/) |
| **13** | Flexbox Layouts | `display: flex`, navigation bars, centering (`justify-content`, `align-items`), `flex-wrap` | [`Assignment13/`](./Assignment13/) |
| **14** | CSS Grid Layouts | `display: grid`, `fr` units, `gap`, auto-fill gallery (`minmax`), `grid-template-areas` | [`Assignment14/`](./Assignment14/) |
| **15** | Responsive Pages with Media Queries | Viewport meta, `@media (min-width: 600px)`, responsive images, fluid typography | [`Assignment15/`](./Assignment15/) |

---

## 🔬 Detailed Assignment Breakdown

### Assignment 1: Starting a Git Repository
* **Aim:** Initialize a Git repository for the lab workspace and track file changes with descriptive commits.
* **Tasks:**
  * **Task 1:** Initialize repository with `git init`, configure local credentials (`user.name`, `user.email`), and verify configuration.
  * **Task 2:** Create [`index.html`](./Assignment1/Task2/index.html) with an `<h1>` heading, inspect status with `git status`, stage and commit as `"Add home page"`.
  * **Task 3:** Add an `<h2>` heading below the first heading, commit with `"Add next meeting heading"`, and inspect history with `git log --oneline`.
* **Output / Verification:** Command terminal logs saved in [`Assignment1/`](./Assignment1/).

---

### Assignment 2: Pushing and Cloning a Repository
* **Aim:** Set up a bare upstream repository, configure remotes, push branch commits, and verify cloning.
* **Tasks:**
  * **Task 1:** Create bare repository `../html-remote` using `git init --bare`, add remote `origin`, and verify via `git remote -v`.
  * **Task 2:** Push local branch to remote repository (`git push origin master` / `main`).
  * **Task 3:** Clone `html-remote` into `html-copy` and verify commit logs (`git log --oneline`).
* **Output / Verification:** Command terminal logs saved in [`Assignment2/`](./Assignment2/).

---

### Assignment 3: Your First HTML Page
* **Aim:** Construct foundational HTML documents with proper DOCTYPE, document metadata, headings, paragraphs, and inline text formatting.
* **Tasks:**
  * **Task 1:** [`first.html`](./Assignment3/Task1/first.html) — Standard document structure with title `"My First Page"` and `<h1>Hello, I am Asha.</h1>`.
  * **Task 2:** [`headings.html`](./Assignment3/Task2/headings.html) — Hierarchical headings (`<h1>`, `<h2>`, `<h3>`) and paragraph text.
  * **Task 3:** [`text-format.html`](./Assignment3/Task3/text-format.html) — Paragraph formatting using `<strong>` (bold), `<em>` (italics), and `<br>` (line breaks).

---

### Assignment 4: Divs, Attributes and a Small Fix
* **Aim:** Structure layout containers using `<div>`, attach custom metadata via `data-*` attributes, and debug syntax/nesting errors in broken markup.
* **Tasks:**
  * **Task 1:** [`layout.html`](./Assignment4/Task1/layout.html) — Layout sections using `<div class="header">`, `<div class="main">`, and `<div class="footer">`.
  * **Task 2:** [`attributes.html`](./Assignment4/Task2/attributes.html) — Div container with `id="profile"` containing a paragraph tagged with custom attribute `data-topic="hobbies"`.
  * **Task 3:** [`attendance-fixed.html`](./Assignment4/Task3/attendance-fixed.html) — Corrected unclosed tags, proper nesting, and standardized HTML structure.

---

### Assignment 5: Links and Images
* **Aim:** Implement bidirectional page navigation using hyperlinks and embed accessible graphics with alternative text and dimensions.
* **Tasks:**
  * **Task 1:** [`home.html`](./Assignment5/Task1/home.html) — Landing page with anchor navigation linking to `portfolio.html`.
  * **Task 2:** [`portfolio.html`](./Assignment5/Task2/portfolio.html) — Portfolio page containing return link to `home.html`.
  * **Task 3:** [`portfolio-image.html`](./Assignment5/Task3/portfolio-image.html) — Embedding profile image (`200x200` dimensions) with descriptive `alt` attribute for accessibility.

---

### Assignment 6: Types of HTML Lists
* **Aim:** Master list structures including bulleted, hierarchical numbered, and definition/description lists.
* **Tasks:**
  * **Task 1:** [`shopping-list.html`](./Assignment6/Task1/shopping-list.html) — Unordered list (`<ul>`) with items (Notebook, Pen, Bag).
  * **Task 2:** [`canteen-menu.html`](./Assignment6/Task2/canteen-menu.html) — Ordered list (`<ol>`) featuring nested sub-lists for menu variations (Cheese, Vegetable).
  * **Task 3:** [`faq.html`](./Assignment6/Task3/faq.html) — Description list (`<dl>`, `<dt>`, `<dd>`) for questions and answers.

---

### Assignment 7: About Me Page
* **Aim:** Build a semantic personal profile webpage utilizing HTML5 landmark tags, smooth in-page fragment navigation, and email links.
* **Tasks:**
  * **Task 1:** [`about-me.html`](./Assignment7/Task1/about-me.html) — Semantic shell using `<header>`, `<nav>`, `<main>`, and `<footer>` with jump anchors (`#about`, `#contact`).
  * **Task 2:** Add `<section id="about">` with `<h2>About me</h2>` and personal background description.
  * **Task 3:** Add `<footer id="contact">` with interactive `mailto:` link for direct communication.

---

### Assignment 8: Sign-Up Forms and Choices
* **Aim:** Develop accessible web forms with varied input controls, explicit label bindings, and client-side validation constraints.
* **Tasks:**
  * **Task 1:** [`signup.html`](./Assignment8/Task1/signup.html) — Post method form with explicitly associated `<label>` elements for full name, email, and password.
  * **Task 2:** [`choices.html`](./Assignment8/Task2/choices.html) — Mutually exclusive radio buttons (`name="gender"`) and `<select>` dropdown menu for course options (BCA, B.Tech).
  * **Task 3:** [`signup-required.html`](./Assignment8/Task3/signup-required.html) — Form featuring HTML5 `required` attribute validation, descriptive `placeholder` hints, and submit button.

---

### Assignment 9: Tables with Headers and Footers
* **Aim:** Tabulate structured data with semantic subdivisions (`<caption>`, `<thead>`, `<tbody>`, `<tfoot>`) and accessible scope bindings.
* **Tasks:**
  * **Task 1:** [`marks.html`](./Assignment9/Task1/marks.html) — Student grade sheet table with caption, headers (Name, Maths, Science), and student records.
  * **Task 2:** [`marks-average.html`](./Assignment9/Task2/marks-average.html) — Table extended with `<tfoot>` calculating subject class averages.
  * **Task 3:** [`marks-accessible.html`](./Assignment9/Task3/marks-accessible.html) — Accessible table enhancing screen-reader navigation with `scope="col"` and `scope="row"` headers.

---

### Assignment 10: CSS Fundamentals
* **Aim:** Explore the three methods of CSS application (inline, internal, external) and target elements via tag, class, and ID selectors.
* **Tasks:**
  * **Task 1:** [`inline-internal.html`](./Assignment10/Task1/inline-internal.html) — Internal `<style>` stylesheet paired with inline `style=""` overrides.
  * **Task 2:** [`style.css`](./Assignment10/Task1/style.css) — External stylesheet applying rules for headings, classes (`.note`), and IDs (`#title`).
  * **Task 3:** [`linked.html`](./Assignment10/Task3/linked.html) — Separation of concerns by linking external `style.css` via `<link rel="stylesheet">`.

---

### Assignment 11: Units and CSS Variables
* **Aim:** Implement scalable sizing with absolute (`px`) and relative (`%`, `rem`) units, and centralize styling tokens via CSS custom properties.
* **Tasks:**
  * **Task 1:** [`units.html`](./Assignment11/Task1/units.html) — Comparison of fixed pixel widths, fluid percentage widths, and root-relative `rem` font scaling.
  * **Task 2:** [`variables.html`](./Assignment11/Task2/variables.html) — CSS Custom Properties declared in `:root` (`--main-color`, `--accent-color`, `--page-padding`) applied via `var()`.
  * **Task 3:** [`tokens.css`](./Assignment11/Task2/tokens.css) — Reusable design token stylesheet defining primary/accent color schemes, typography sizes, and spacing intervals.

---

### Assignment 12: Box Model, Cards and Scrolling
* **Aim:** Analyze the CSS Box Model (`content-box` vs `border-box`), construct modern card components, and manage overflow content.
* **Tasks:**
  * **Task 1:** [`box-model.html`](./Assignment12/Task1/box-model.html) — Side-by-side analysis of box dimension calculations between `content-box` and `border-box`.
  * **Task 2:** [`card.html`](./Assignment12/Task2/card.html) — UI Card component featuring padding, subtle borders, rounded corners (`border-radius: 12px`), and background shading.
  * **Task 3:** [`scroll.html`](./Assignment12/Task3/scroll.html) — Fixed-height container with `overflow: auto` scrollbar management for overflowing content.

---

### Assignment 13: Flexbox Layouts
* **Aim:** Implement one-dimensional layouts using CSS Flexible Box Layout module for navigation bars, centered alignments, and wrapping catalogs.
* **Tasks:**
  * **Task 1:** [`nav-flex.html`](./Assignment13/Task1/nav-flex.html) — Horizontal navigation bar using `display: flex` with styled navigation links.
  * **Task 2:** [`centred-cards.html`](./Assignment13/Task2/centred-cards.html) — Pricing tier cards centered horizontally and vertically using `justify-content: center` and `align-items: center`.
  * **Task 3:** [`wrapping-cards.html`](./Assignment13/Task3/wrapping-cards.html) — Product card catalog implementing `flex-wrap: wrap` for adaptive multi-row wrapping.

---

### Assignment 14: CSS Grid Layouts
* **Aim:** Construct two-dimensional grid layouts using fractional units, auto-fill responsive columns, and named template areas.
* **Tasks:**
  * **Task 1:** [`grid-first.html`](./Assignment14/Task1/grid-first.html) — Equal three-column grid layout utilizing `repeat(3, 1fr)` and `gap: 12px`.
  * **Task 2:** [`gallery.html`](./Assignment14/Task2/gallery.html) — Dynamic responsive photo gallery utilizing `repeat(auto-fill, minmax(150px, 1fr))`.
  * **Task 3:** [`dashboard-areas.html`](./Assignment14/Task3/dashboard-areas.html) — Dashboard layout using `grid-template-areas` coordinating `header`, `sidebar`, `main`, and `footer`.

---

### Assignment 15: Responsive Pages with Media Queries
* **Aim:** Build responsive, mobile-first web pages that adapt fluidly across devices using viewport meta tags, media query breakpoints, and scalable media.
* **Tasks:**
  * **Task 1:** [`mobile-first.html`](./Assignment15/Task1/mobile-first.html) — Mobile-first stacked card layout adapting to side-by-side columns at `@media (min-width: 600px)`.
  * **Task 2:** [`responsive-image.html`](./Assignment15/Task2/responsive-image.html) — Fluid images configured with `max-width: 100%` and `height: auto` to prevent viewport overflow.
  * **Task 3:** [`responsive-text.html`](./Assignment15/Task3/responsive-text.html) — Fluid typography adapting heading scale from `1.5rem` to `2.5rem` at wide breakpoints.

---

## 📂 Project Directory Structure

```text
HTML_Lab/
├── .gitignore
├── README.md
├── Assignment1/
│   ├── Task1/             # Git init and user configuration screenshot
│   ├── Task2/             # index.html (Initial commit)
│   └── Task3/             # index.html (H2 heading commit & log)
├── Assignment2/
│   ├── Task1/             # Bare remote setup screenshot
│   ├── Task2/             # Git push verification
│   └── Task3/             # Git clone verification
├── Assignment3/
│   ├── Task1/             # first.html
│   ├── Task2/             # headings.html
│   └── Task3/             # text-format.html
├── Assignment4/
│   ├── Task1/             # layout.html
│   ├── Task2/             # attributes.html
│   └── Task3/             # attendance-fixed.html
├── Assignment5/
│   ├── Task1/             # home.html
│   ├── Task2/             # portfolio.html
│   └── Task3/             # portfolio-image.html & images/
├── Assignment6/
│   ├── Task1/             # shopping-list.html
│   ├── Task2/             # canteen-menu.html
│   └── Task3/             # faq.html
├── Assignment7/
│   ├── Task1/             # about-me.html (Semantic skeleton)
│   ├── Task2/             # about-me.html (About section)
│   └── Task3/             # about-me.html (Contact footer & email)
├── Assignment8/
│   ├── Task1/             # signup.html
│   ├── Task2/             # choices.html
│   └── Task3/             # signup-required.html
├── Assignment9/
│   ├── Task1/             # marks.html
│   ├── Task2/             # marks-average.html
│   └── Task3/             # marks-accessible.html
├── Assignment10/
│   ├── Task1/             # inline-internal.html & style.css
│   ├── Task2/             # style.css selector verification
│   └── Task3/             # linked.html
├── Assignment11/
│   ├── Task1/             # units.html
│   ├── Task2/             # variables.html & tokens.css
│   └── Task3/             # Design tokens verification
├── Assignment12/
│   ├── Task1/             # box-model.html
│   ├── Task2/             # card.html
│   └── Task3/             # scroll.html
├── Assignment13/
│   ├── Task1/             # nav-flex.html
│   ├── Task2/             # centred-cards.html
│   └── Task3/             # wrapping-cards.html
├── Assignment14/
│   ├── Task1/             # grid-first.html
│   ├── Task2/             # gallery.html
│   └── Task3/             # dashboard-areas.html
└── Assignment15/
    ├── Task1/             # mobile-first.html
    ├── Task2/             # responsive-image.html
    └── Task3/             # responsive-text.html
```

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hasanmujtaba2006/HTML_Lab.git
   cd HTML_Lab
   ```

2. **Open and Preview:**
   - Double click any `.html` file to view it directly in your web browser (Chrome, Edge, Firefox).
   - Alternatively, open the repository in **VS Code** and launch with the **Live Server** extension (`Right-click > Open with Live Server`).

---

## 🛠️ Technologies & Concepts

- **Markup:** HTML5 (Semantic Elements, Forms, Tables, Multimedia)
- **Styling:** CSS3 (Box Model, Flexbox, CSS Grid, Custom Variables, Media Queries)
- **Version Control:** Git & GitHub (Branching, Remote synchronization, Commit discipline)
- **Design Philosophy:** Clean code separation, accessibility (`scope`, `alt`, explicit form labels), mobile-first responsive design.

---

## 👨‍💻 Author

* **Student:** Hasan Mujtaba
* **Email:** [hasanmujtaba.q@gmail.com](mailto:hasanmujtaba.q@gmail.com)
* **GitHub:** [@hasanmujtaba2006](https://github.com/hasanmujtaba2006)
* **University:** Invertis University, Bareilly
* **Department:** Faculty of Computer Science & Engineering (B.Tech CSE)
