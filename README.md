
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bs4cards

<!-- badges: start -->

[![R-CMD-check](https://github.com/djnavarro/bs4cards/workflows/R-CMD-check/badge.svg)](https://github.com/djnavarro/bs4cards/actions)
[![CRAN
status](https://www.r-pkg.org/badges/version/bs4cards)](https://CRAN.R-project.org/package=bs4cards)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Codecov test
coverage](https://codecov.io/gh/djnavarro/bs4cards/branch/master/graph/badge.svg)](https://codecov.io/gh/djnavarro/bs4cards?branch=master)
<!-- badges: end -->

When creating R markdown websites, I often find myself wanting to
organise content into a nice-looking grid of links with thumbnail images
and maybe a small amount of text. It’s a design pattern I use over and
over again in my own sites. Whether I’m creating previews for lectures,
profiles and bios for people, or links to galleries, I find myself
needing the ability to create pages that look something like this:

![](https://bs4cards.djnavarro.net/example-slides.png)

The specific format I need varies from case to case. Sometimes I want
the text under the image (as in the example above), other times I want
the text on the side, and other times I want the text to float over the
image.

Realising that I’m almost certain to make many more sites that need this
functionality, and suspecting that other people have the same need that
I do, I wrote bs4cards to make task a little easier inside an R markdown
document or website. You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("djnavarro/bs4cards")
```

The package exports a single function `cards()` which takes a data frame
as input and automatically generates the HTML you need to create a card
grid like the one shown above. It’s a little tricky to show how the
function works in the README because this page appears on GitHub and
there’s no bootstrap library underneath… so if you’d like to see some
examples of how it works, check out the [get
started](https://bs4cards.djnavarro.net/articles/articles/bs4cards.html)
page.

![](https://bs4cards.djnavarro.net/bs4cards-logo.png)
