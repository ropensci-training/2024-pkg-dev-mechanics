---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 96ac244acc42d131

---

## Reminder

We have a package with one function and tests.

That function has a local manual page.

## Documentation

:warning: rmarkdown and pkgdown needs your package to be *installed*.

-   `install.packages("rmarkdown")`, [`usethis::use_readme_rmd()`](https://usethis.r-lib.org/reference/use_readme_rmd.html), write stuff, knit, commit+push, look at GitHub repository.

-   `usethis::use_vignette("minipkg")`, write stuff. Vignette vs article.

-   `install.packages("pkgdown")`, [`usethis::use_pkgdown()`](https://usethis.r-lib.org/reference/use_pkgdown.html), [`pkgdown::build_site()`](https://pkgdown.r-lib.org/reference/build_site.html). Locally.

:eyes: [pkgdown website](https://pkgdown.r-lib.org/)

:toolbox: Repeat the steps!

## Build website automatically

-   `usethis::use_github_action("pkgdown")`, change GitHub pages settings of the repo, add URL to pkgdown config and to DESCRIPTION.

:eyes: [usethis support for GitHub Actions setup](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: Repeat the steps!

------------------------------------------------------------------------

