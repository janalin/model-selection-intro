# Introduction to Model Selection
_Last Update: April 7, 2018 by JL_

Published on <a href="https://janalin.github.io/model-selection-intro/">https://janalin.github.io/model-selection-intro/</a>

_Notes on the concepts behind model selection and commonly used model selection criteria._

This document is under construction and shows only the chapters completed at this time. Corrections and suggestions are very welcome, contact <a href="mailto:jlinnik@protonmail.ch">jlinnik@protonmail.ch</a> or check the correspondence at the end of the document.

If you contribute, please add your name in the contributors list below and in the `correspondence.md` file.

#### Contributors (_please add your name if you contribute_)
* Jana Linnik <a href="mailto:jlinnik@protonmail.ch">jlinnik@protonmail.ch</a>

### Prerequisites
This is a bookdown document. The __bookdown__ package can be installed from CRAN or Github: <a href="https://github.com/rstudio/bookdown">https://github.com/rstudio/bookdown</a>
```
install.packages("bookdown")
```
The required R packages are listed in `packages.bib`.

### Add a new chapter
Create an Rmd file `XX-new_chapter.Rmd` with a two digit chapter number `XX`.
Note that each Rmd file contains only one chapter. The chapter title is defined by the first-level heading `#`.
Bookdown documents are written in __Markdown__. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$.

### Usage
Follow the documentation on <a href="https://github.com/rstudio/bookdown/blob/master/inst/examples/01-introduction.Rmd">https://github.com/rstudio/bookdown/blob/master/inst/examples/01-introduction.Rmd</a> or run the following shell script:
```
sh _build.sh
```

### Publish
Before you push to git, copy all required files to the home directory by running:
```
sh _cp_html.sh
```

Published under the Creative Commons Attribution 4.0
