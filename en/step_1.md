Sometimes you will want to style particular elements within a **container** that has a class. To do this you use the `>` operator.

The example you just used styles all `<a>` elements within a container that has the `nav-items` class. 

This allows you to style certain links without affecting all the links on your page. It saves you having to give a class to each individual link.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 55
line_highlights: 56-60
---

.nav-items > a {

}

--- /code ---