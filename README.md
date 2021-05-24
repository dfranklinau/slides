# slides

There are lots of tools to generate slide shows. They're all great in their own
ways but I'm lazy.

I decided to leverage HTML, CSS and my browser's print-to-PDF functionality to
create a static, simple and effective slide show. It's probably more effort than
using a website or software but oh well.

This repository contains:

- `index.html`, a boilerplate HTML file demonstrating how it can be used;
- `slides.css`, the CSS framework powering the print styles; and
- `custom.css`, any slide customisation and CSS overrides.


## features

- header and footer templates that appear on every slide with `position: fixed`
- opt-in to typographic styles (e.g. heading, paragraph and margins and padding)
  with a `.typography` class
- tested in Chrome and Firefox
- complete control of anything with CSS
