# AuroraCSS

A lightweight, modern custom CSS framework built with Sass.  
It provides consistent styles for HTML elements and utility classes for quick customization.

## Team Members
- Samuel (Team Leader)
- Ibraheem

## Description
This project is a custom CSS framework that allows developers to quickly apply themed components and utilities to their web pages. Built using Sass, it includes customizable variables, partials, and a compiled CSS file for easy use.


# AuroraCSS

> A lightweight, customizable CSS framework built with Sass. Provides a consistent theme for HTML elements and a set of utility classes for common styling.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Customization](#customization)
5. [Available Utilities](#available-utilities)
6. [Components](#components)
7. [Contributing](#contributing)


## Introduction

AuroraCSS is a **Sass-based CSS framework** designed for simplicity and flexibility. It provides:

* Custom theme for standard HTML elements (headings, lists, paragraphs, forms, buttons, tables)
* Utility classes for common styling (colors, font sizes, font weights, margins, paddings, borders)
* Fully customizable via Sass variables

This framework is ideal for **quick prototyping** or **consistent styling across projects**.



## Installation

### 1️⃣ Clone the repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2️⃣ Install Sass (if not already installed)

```bash
npm install -g sass
```

### 3️⃣ Compile Sass

```bash
sass scss/style.scss css/style.css
```

Or watch for changes automatically:

```bash
sass --watch scss/style.scss:css/style.css
```


## Usage

### Include CSS

In your HTML file:

```html
<link rel="stylesheet" href="css/style.css">
```

### Apply classes

### Headings

```html
<h1 class="text-primary">Heading 1</h1>
<h2 class="text-secondary">Heading 2</h2>
```

### Paragraphs

```html
<p class="fw-light">Light text</p>
<p class="fw-normal">Normal text</p>
<p class="fw-bold">Bold text</p>
```

### Utilities

```html
<div class="m-2 p-2 text-success">Box with margin, padding, and color</div>
```

### Buttons

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
```

### Forms

```html
<input type="text" placeholder="Your Name">
<textarea placeholder="Your Message"></textarea>
<select>
  <option>Option 1</option>
</select>
```

### Tables

```html
<table>
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
</table>
```

### Customization

All colors, fonts, spacing, and other styles can be customized via **Sass variables** in `_variables.scss`.

Example:

```scss
$primary-color: #007bff;
$secondary-color: #6c757d;
$success-color: #28a745;

$font-family: 'Poppins', sans-serif;
$font-size-base: 1rem;
$border-radius: 0.25rem;

$space-xs: 0.25rem;
$space-sm: 0.5rem;
$space-md: 1rem;
$space-lg: 1.5rem;
```

> Update these variables and recompile `style.scss` to apply your custom theme.

### Available Utilities

* **Colors**: `text-primary`, `text-secondary`, `text-success`
* **Font Weight**: `fw-light`, `fw-normal`, `fw-bold`
* **Margin & Padding**: `m-1` … `m-5`, `p-1` … `p-5`
* **Borders**: `border`, `border-top`, `border-bottom`
* **Font Size**: `fs-sm`, `fs-md`, `fs-lg`


### Components

* **Buttons**: `.btn`, `.btn-primary`, `.btn-secondary`
* **Forms**: inputs, textareas, selects
* **Tables**: styled headers, cells, alternating row colors


### Contributing

1. Fork the repository
2. Create a new branch for your changes
3. Make your edits and compile Sass
4. Push and create a Pull Request