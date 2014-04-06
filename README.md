ie8-separate-css-technique
==========================
This repo includes an example of the technique for automatic generation of media-query-free stylesheets with desktop styles for IE8 from existing mobile first responsive stylesheets. Requirements are use of Sass (>= 3.2) and mixins for responsive style definitions.
### Use
Simply clone the repo, run the following commands and open `index.html`.
```bash
sass main.sass main.css
sass ie.sass ie.css
```
Credit for the initial idea goes to my coworker [Beni](https://github.com/benib).