# hg.css
My little CSS framework for quick building block development.

It starts with some basic Box-Sizing, Normalize and Clearfix. Love these!

Here are some of the main highlights for each section.

<h2>Structure</h2>
Simple classes to build wrappers and position text.
```
<div class="centered">
  <div class="img full-coverage"><img src="#" class="block"></div>
</div>

.full-coverage { top: 0; right: 0; bottom: 0; left: 0; }
.centered { max-width: 1080px; margin-left: auto; margin-right: auto; }
.middle { margin-left: auto; margin-right: auto; }
.hidden, .hide { display: none; }
```
<h2>Decorative</h2>
This section contains styles for images and borders.

```
<img src='#' class="circle border shadow">

img.circle { border-radius: 100%; }
img.border { border: solid 3px #fff; }
img.shadow { box-shadow: 0 2px 4px #ccc; }
.bg-white-20 { background: rgba(255,255,255,0.2); }
.border-vert { border-left: solid 1px #ccc; border-right: solid 1px #ccc; }
hr.block { width: 100px; height: 10px; background: #efefef; border: none; margin: 20px auto; }
```
