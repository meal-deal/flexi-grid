### Flexi Grid
  
<p style="text-align:center">
<img src="/docs/img/grid-logo.svg" width="200">
</p>

A simple flexbox grid system.


## Getting Started

To get the Flexi Grid system in your web page, simply paste this code into the `head` of your document,
```html
<link rel="stylesheet" href="/flexi-grid/dist/flexi-grid.min.css">
<!-- or -->
<link rel="stylesheet" href="/flexi-grid/dist/flexi-grid.css">
```

## Docs

```html
<div class="grid">
  <div class="row">
    <!-- For column width, use column-n-of-p. By default, p can be 4, 8, or 12 -->
    <div class="col column-1-of-4"></div>
    <div class="col column-1-of-4"></div>
    <div class="col column-1-of-4"></div>
    <div class="col column-1-of-4"></div>
  </div>
  <div class="row">
    <!-- The center class centers the column. -->
    <div class="col column-7-of-12 center"></div>
  </div>
  <div class="row">
    <!-- use column-m- and column-s- as well as m-hide, s-hide, m-only and s-only to make your grid responsive -->
    <div class="col column-2-of-8 column-m-1-of-4 column-s-1-of-2"></div>
    <div class="col column-3-of-8 column-m-2-of-4 column-s-1-of-2"></div>
    <div class="col column-1-of-8 m-hide"></div>
    <div class="col column-2-of-8 column-m-1-of-4 s-hide"></div>
  </div>
  <div class="row">
    <div class="col column-1-of-4"></div>
    <div class="col column-1-of-2"></div>
    <div class="col column-1-of-4"></div>
  </div>
  <div class="row">
    <!-- Pushes and pulls are used in the same way as column-n-of-p. They can also be responsive, like pl-m-1-of-4 -->
    <div class="col column-1-of-8"></div>
    <div class="col column-2-of-8 ps-2-of-12"></div>
    <div class="col column-3-of-8 pl-1-of-12"></div>
  </div>
</div>
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

Copyright &copy; 2022 @hot-meal All Rights Reserved.
