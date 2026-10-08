# fhe-intro-book
Introductory book on programmable computation within a fully homomorphic environment.

## Render the book

Install [Git](https://git-scm.com/downloads), [R](https://cran.r-project.org/),
and [Quarto](https://quarto.org/docs/get-started/).

Clone this repository and enter its folder:

```sh
git clone https://github.com/camcos-sjsu/fhe-intro-book.git
cd fhe-intro-book
```

Install the following packages in R studio:

```r
install.packages(c("knitr", "ggplot2", "dplyr", "gganimate", "gifski", "showtext", "sysfonts"))
```

From the project folder, render the book:

```sh
quarto render
```

Open `_book/index.html` to view it. To preview while editing, run `quarto preview`
from the project folder instead.
