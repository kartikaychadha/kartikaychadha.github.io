# Custom CSS Utility Classes for Responsive Layouts

This repository provides a set of custom CSS utility classes to create responsive website layouts without relying on frameworks like Bootstrap. The utility classes here cover common layout and design needs, including responsive grids, spacing, text alignment, flex utilities, and borders.

## Table of Contents
- [Layout and Grid Classes](#layout-and-grid-classes)
  - [Container Classes](#container-classes)
  - [Row and Column Classes](#row-and-column-classes)
  - [Responsive Column Classes](#responsive-column-classes)
- [Spacing Classes](#spacing-classes)
  - [Padding (p-*) and Margin (m-*)](#padding-p--and-margin-m-)
- [Text Alignment Classes](#text-alignment-classes)
- [Flexbox Utility Classes](#flexbox-utility-classes)
- [Responsive Display Utility Classes](#responsive-display-utility-classes)
- [Border and Shape Classes](#border-and-shape-classes)

---

## Layout and Grid Classes

### Container Classes
- **`.container`**: Creates a centered, fixed-width container for central layouts.
- **`.container-fluid`**: Creates a full-width container that spans the viewport width, suitable for edge-to-edge layouts.

### Row and Column Classes
- **`.row`**: Sets up a flexbox container for horizontal arrangement of columns. Adds margin for spacing.
- **`.col-1` to `.col-12`**: Creates columns that take up a portion of the 12-column grid. For example:
  - `.col-6`: 50% width of the row
  - `.col-4`: 33.33% width of the row

### Responsive Column Classes
- **`.col-sm-*`, `.col-md-*`, `.col-lg-*`**: Adjusts column width based on screen size:
  - `.col-sm-*`: Applies to small devices (min-width: 576px)
  - `.col-md-*`: Applies to medium devices (min-width: 768px)
  - `.col-lg-*`: Applies to large devices (min-width: 992px)

## Spacing Classes

### Padding (`p-*`) and Margin (`m-*`)
- **`.p-[0-5]`**: Adds padding inside elements:
  - `.p-0`: No padding
  - `.p-1` to `.p-5`: Small (`4px`) to large (`32px`) padding
- **`.m-[0-5]`**: Adds margin outside elements:
  - `.m-0`: No margin
  - `.m-1` to `.m-5`: Small (`4px`) to large (`32px`) margin

## Text Alignment Classes
- **`.text-left`**: Aligns text to the left within the element.
- **`.text-center`**: Centers text within the element.
- **`.text-right`**: Aligns text to the right within the element.

## Flexbox Utility Classes
- **`.d-flex`**: Sets display to flex, making the element a flex container.
- **`.flex-column`**: Sets flex direction to vertical.
- **`.flex-row`**: Sets flex direction to horizontal.
- **`.align-items-center`**: Centers items vertically in the flex container.
- **`.justify-content-*`**: Controls horizontal alignment of items:
  - `.justify-content-center`: Centers items.
  - `.justify-content-between`: Spaces items with equal gaps.
  - `.justify-content-around`: Adds equal space around items.

## Responsive Display Utility Classes
- **`.d-md-*`**: Controls display properties at specific breakpoints:
  - `.d-md-block`: Shows element as a block at medium size and above.
  - `.d-md-flex`: Shows element as a flex container at medium size and above.
  - `.d-md-none`: Hides the element at medium size and above.

## Border and Shape Classes
- **`.border`**: Adds a 1-pixel solid border (`#ddd`) around the element.
- **`.border-top`, `.border-right`, `.border-bottom`, `.border-left`**: Adds borders to individual sides.
- **`.rounded`**: Adds small rounded corners (`0.25rem`) to elements.
- **`.rounded-circle`**: Creates a circular shape with a 50% border-radius, ideal for avatars or circular buttons.

## Usage
Include the custom CSS file in your project and apply classes to your HTML elements as needed.

```html
<div class="container">
  <div class="row">
    <div class="col-6 col-md-4 p-3 border rounded">
      Content Area
    </div>
    <div class="col-6 col-md-8 text-center m-2">
      Main Content
    </div>
  </div>
</div>
