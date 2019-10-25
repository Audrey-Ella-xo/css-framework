# Grid based CSS Framework
It is a basic CSS framework similar to bootstrap to build the grid based responsive page layouts for all devices.

## Description
In this project we build two dimensional layout based grid framework by taking only widths in consideration. Also included basic utility classes for display, flex-box, aligning, and spacing content.

## Getting Started

There are two ways to get started. You can either:

- use the cloudinary CDN to link to our stylesheet
- use the GitHub repository to get the latest development version

### Prerequisites

If you need to make your webpage responsive with this simple framework.

##### Use the HTML5 doctype
```html
<!DOCTYPE html>
```

##### Add the responsive viewport meta tag
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
### Installing

- Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load our CSS.
```html
<link rel="stylesheet" href="https://res.cloudinary.com/rna/raw/upload/v1571948949/grid-framework.css">

<!--Minified Version-->

<link rel="stylesheet" href="https://res.cloudinary.com/rna/raw/upload/v1571948949/grid-framework.min.css">
```

##### Or

- Download this repository and copy the `styles.css` file into your project.

## This framework contains following elements: 
- [Grid](#Grid)
- [Displays](#Displays)
- [Flexbox Utilities](#Flexbox)
- [Positions](#Positions)
- [Padding & Margins ](#Padding-Margins)
- [Buttons](#Buttons)
- [Background Colors](#Background-colors)
- [Text Utilities](#Text-Utilities)

### Grid
Using a single set of .col-sm-* classes, you can create a basic grid system.

#### Example
```html
<!--For small screens  & medium screens -->
<div class="row">
  <div class="col-sm-8 col-md-6">col-sm-8 col-md-6</div>
  <div class="col-sm-4 col-md-6">col-sm-4 col-md-6</div>
</div>
```

To make the grid responsive, we considered five grid breakpoints, one for each responsive breakpoint: all breakpoints (extra small), small, medium, large, and extra large.

```html
$container-breakpoints: (
  xs: 425px
  sm: 575px,
  md: 768px,
  lg: 1024px,
  xl: 1440px
);
```

### Displays
Display utility classes are named using the format `.d-{value}`

Where value is one of:
- none
- inline
- inline-block
- block
- table
- flex
- inline-flex

### Flexbox
Apply display utilities to create a flexbox container and transform direct children elements into flex items. Flex containers and items are able to be modified further with additional flex properties.

Flexbox utility classes are named using the format `.{flex-property-value}`

#### Example
```html
<div class="d-flex justify-content-space-around">I'm a flexbox container!</div>
```

### Positions
Quick positioning classes are available, though they are not responsive.

#### Examples
```html
<div class="position-static">...</div>
<div class="position-relative">...</div>
<div class="position-absolute">...</div>
<div class="position-fixed">...</div>
<div class="position-sticky">...</div>
```

### Padding-Margins
The padding & margin uttility classes are named using the format `{property}{sides}-{size}`

Where property is one of:
```
m - for classes that set margin
p - for classes that set padding
```
Where sides is one of:
```
t - for classes that set margin-top or padding-top
b - for classes that set margin-bottom or padding-bottom
l - for classes that set margin-left or padding-left
r - for classes that set margin-right or padding-right
x - for classes that set both *-left and *-right
y - for classes that set both *-top and *-bottom
```

### Buttons
Some preset button styles are made for serving its own purpose.

#### Examples
```html
<button type="button" class="btn-primary">Primary</button>
<button type="button" class="btn-secondary">Secondary</button>
<button type="button" class="btn-success">Success</button>
<button type="button" class="btn-danger">Danger</button>
<button type="button" class="btn-warning">Warning</button>
<button type="button" class="btn-info">Info</button>
```

### Background-colors
Some preset background classes are made to style the backgrounds easily.

#### Examples
```html
<div class="bg-primary">Primary</div>
<div class="bg-secondary">Secondary</div>
<div class="bg-success">Success</div>
<div class="bg-danger">Danger</div>
<div class="bg-warning">Warning</div>
<div class="bg-info">Info</div>
```
### Text-Utilities
Text utilities to control alignment,font weights and text colors

#### Examples
```html
<p class="text-left">Left aligned text on all viewport sizes.</p>
<p class="font-weight-bold">Bold text.</p>
<p class="text-danger">Red color text.</p>
```
## Built With
+ HTML5/CSS
+ [SASS](https://sass-lang.com/)

## Authors:
  * [Ramesh Naidu Allu](https://github.com/rna)
  * [Odiaka Emmanuella Anita](https://github.com/Audrey-Ella-xo)