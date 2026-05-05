# Bookdown Repo

Minimal [bookdown](https://bookdown.org/) project scaffold.

## Requirements

- R
- `bookdown` package

Install package:

```r
install.packages("bookdown")
```

## Build the book

From this directory:

```bash
Rscript -e "bookdown::render_book('index.Rmd')"
```

Output goes to `_book/`.
