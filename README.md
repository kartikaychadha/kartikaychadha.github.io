# Custom CSS Utility Classes for Responsive Layouts

This CSS provides a set of utility classes to help you create responsive, grid-based layouts similar to Bootstrap. This guide explains each class and how to use it for beginners learning HTML and CSS.

---

## Table of Contents

1. [Container Classes](#container-classes)
2. [Grid Classes (Row & Column System)](#grid-classes-row--column-system)
3. [Spacing Classes](#spacing-classes)
4. [Text Alignment Classes](#text-alignment-classes)
5. [Flexbox Classes](#flexbox-classes)
6. [Display Utility Classes](#display-utility-classes)
7. [Border and Shape Classes](#border-and-shape-classes)
8. [Example Usage](#example-usage)

---

## Container Classes

- **`.container`**: Wraps content in a responsive container, centering it with padding on each side. This creates a "safe area" for content across different screen sizes.

## Grid Classes (Row & Column System)

- **`.row`**: Defines a horizontal container for organizing content in a grid structure.
- **`.col-*`**: Sets column width. Numbers range from 1 to 12, determining how much of the row each column occupies.
  - Examples:
    - `.col-12`: Full-width column.
    - `.col-6`: Half-width column.
- **Responsive Columns** (`col-md-*`): Column widths that adapt based on screen size, e.g., `.col-md-8` sets width only on medium and larger screens.

## Spacing Classes

- **Padding (`p-*`)**: Adds inner space around an element.
  - `.p-0`: No padding.
  - `.p-3`: Moderate padding on all sides.
  - `.pt-*`, `.pb-*`, etc.: Padding for specific sides (e.g., `.pt-3` for padding-top).

- **Margin (`m-*`)**: Adds outer space around an element.
  - `.m-0`: No margin.
  - `.m-2`: Small margin on all sides.
  - `.mt-*`, `.mb-*`, etc.: Margin for specific sides (e.g., `.mt-5` for margin-top).

## Text Alignment Classes

- **`.text-left`**: Left-aligns text (default).
- **`.text-center`**: Centers text within its container.
- **`.text-right`**: Right-aligns text.

## Flexbox Classes

Flexbox classes help with alignment and spacing by enabling a flexible layout container.

- **`.d-flex`**: Enables flex layout for the container.
- **`.justify-content-*`**: Controls horizontal alignment of items.
  - `.justify-content-center`: Centers items horizontally.
- **`.align-items-*`**: Controls vertical alignment of items.
  - `.align-items-center`: Centers items vertically.

## Display Utility Classes

- **`.d-none`**: Hides an element.
- **`.d-block`**: Makes an element visible as a block.
- **Responsive Visibility**: E.g., `.d-md-none` hides an element on medium and larger screens.

## Border and Shape Classes

- **`.border`**: Adds a border around an element.
- **`.rounded`**: Rounds corners for a softer look.
- **`.rounded-circle`**: Makes an element circular (ideal for profile images).

---

## Example Usage

Here’s an example HTML layout demonstrating how to use these classes:

```html
<div class="container">
  <div class="row">
    <div class="col-8 p-3 border rounded">
      <h1 class="text-center">Main Content</h1>
      <p>This is the main content area using column classes and padding.</p>
    </div>
    <div class="col-4 p-3 border rounded">
      <h2 class="text-center">Sidebar</h2>
      <p>This is the sidebar, occupying 4 columns of the 12-column layout.</p>
    </div>
  </div>
</div>
