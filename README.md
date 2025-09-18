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

## 2. HTML tags:

- `<!DOCTYPE html>`: declares the document as HTML5
- `<html>`: root element, includes the `lang` attribute for language
- `<head>`: contains metadata such as `meta`, `title`, and linked stylesheets
- `<meta>`: page metadata like charset and viewport settings
- `<title>`: page title
- `<link rel="stylesheet">`: links to the CSS file `styles.css`
- `<body>`: page body
- `<header>`: page header including main title and description
- `<nav>`: navigation bar containing navigation items
- `<ul>` / `<li>`: unordered lists used for navigation and contact lists
- `<main>`: main content area containing primary content and an `<aside>` sidebar
- `<section>`: semantic sections (About, Testimonials, Gallery)
- `<article>`: independent content block (e.g., project description)
- `<h1>, <h2>, <h3>, <h4>`: heading elements for semantic structure
- `<p>`: paragraph text
- `<table>, <caption>, <thead>, <tbody>, <tr>, <th>, <td>`: table structure for project overview
- `<figure>, <figcaption>`: figure and caption for gallery items
- `<img>`: image element for loading local or remote images
- `<svg>`: scalable vector graphic used as a placeholder example in the project
- `<aside>`: sidebar for contact and form elements
- `<form>, <label>, <input>, <textarea>, <button>`: form elements for the contact form
- `<footer>`: page footer

---