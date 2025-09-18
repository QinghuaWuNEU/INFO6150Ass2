# Project README

This document explains the HTML elements and CSS selector of the table. 

---

## 1. Table-related CSS Selectors (Guide)
Below are the selectors used in `styles.css` for the table, what they match, and why they are used:

1. `table` (element selector)
   - Matches: all `<table>` elements
   - Purpose: provide base table layout rules (`border-collapse`, `width: 100%`, `margin-top`)

2. `.projects-table th, .projects-table td` (class + descendant element selectors, grouped)
   - Matches: all `<th>` and `<td>` elements inside a table with class `projects-table`
   - Purpose: set common cell styles such as border, padding and text alignment

3. `.projects-table thead th` (class + descendant + element selector)
   - Matches: `<th>` elements inside the `<thead>` of a `.projects-table`
   - Purpose: apply header-specific styles like background and text color

4. `.projects-table tbody tr:nth-child(odd)` (structural pseudo-class)
   - Matches: odd-numbered `<tr>` rows inside the `<tbody>` of `.projects-table`
   - Purpose: create zebra striping for improved readability

5. `.projects-table tbody tr:hover` (interactive pseudo-class)
   - Matches: a `<tr>` row inside the `<tbody>` of `.projects-table` when hovered by the pointer
   - Purpose: provide hover highlight feedback for better interactivity

Note: Used at least two different selector types.

---

## 2. HTML tags
- `<!DOCTYPE html`> — declares the document as HTML5
- `<html>` — root element (with `lang="en"`)
- `<head>` — document metadata container
- `<meta>` — metadata entries (charset, viewport)
- `<title>` — page title
- `<link rel="stylesheet">` — external stylesheet link
- `<body>` — document body

- `<header>` — site header (title/subtitle)
- `<nav>` — navigation container
- `<ul>` / `<li>` — lists used for navigation and contact items

- `<main>` — main content wrapper
- `<section>` — semantic sections (About, Testimonials, Gallery)
- `<article>` — content article (Projects/Articles)

- `<h1>, <h2>, <h3>, <h4>` — headings used for section/article titles
- `<p>` — paragraphs for descriptive text

- `<figure>` / `<figcaption>` — gallery figures and captions
- `<img>` — images used in the gallery (e.g., `gallery1.png`)

- `<table>` / `<caption>` / `<thead>` / `<tbody>` / `<tr>` / `<th>` / `<td>` — project overview table structure

- `<aside>` — sidebar for contact and social links
- `<form>` / `<label>` / `<input>` / `<textarea>` / `<button>` — contact form elements

- `<footer>` — page footer

---