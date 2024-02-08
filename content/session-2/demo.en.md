---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 74678cd249cbefa7

---

## System setup

-   `.Library`, [`.libPaths()`](https://rdrr.io/r/base/libPaths.html)

-   `install.packages("devtools")`. [Setup chapter of the R packages book](https://r-pkgs.org/setup.html).

-   `install.packages("pak")`.

-   [`devtools::has_devel()`](https://r-lib.github.io/pkgbuild/reference/has_compiler.html)

-   [`devtools::dev_sitrep()`](https://devtools.r-lib.org/reference/dev_sitrep.html)

-   [`usethis::git_sitrep()`](https://usethis.r-lib.org/reference/git_sitrep.html). [Managing Git(Hub) Credentials](https://usethis.r-lib.org/articles/git-credentials.html); ["Managing GitHub credentials from R, difficulty level linux"](https://blog.djnavarro.net/posts/2021-08-08_git-credential-helpers/).

-   usethis and devtools setup in my .Rprofile. [`usethis::edit_r_profile()`](https://usethis.r-lib.org/reference/edit.html), what is an .Rprofile? [usethis setup article](https://usethis.r-lib.org/articles/articles/usethis-setup.html).

Setup is not fun!

:toolbox: (no breakout room) Anything still amiss to report? :fingers_crossed:

------------------------------------------------------------------------

## Package creation

-   `pak::pkg_name_check("minipkg")`

-   `usethis::create_package("../minipkg")`

-   [`usethis::edit_r_profile()`](https://usethis.r-lib.org/reference/edit.html)

-   [`devtools::check()`](https://devtools.r-lib.org/reference/check.html), [`usethis::use_mit_license`](https://usethis.r-lib.org/reference/licenses.html)

-   [`usethis::use_git()`](https://usethis.r-lib.org/reference/use_git.html)

-   [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html). Look at repository including :sparkles: issue tracker :sparkles:.

:eyes: [usethis website](https://usethis.r-lib.org/)

:toolbox: Repeat the same steps, post the link to your package repo in the chat!

------------------------------------------------------------------------

## A first function + docs + test

-   `usethis::use_r("time")`. Explain what [`sprintf()`](https://rdrr.io/r/base/sprintf.html) does.

-   `devtools::load()`, `what_time()`.

-   add an argument.

-   `devtools::load()`, `what_time()`, `what_time(language = "en")`.

-   add two dependencies, `use_package("praise")` and `use_package("rlang")`.

-   `devtools::load()`, `what_time()`, `what_time(language = "en")`.

-   Insert roxygen2 skeleton.

-   [`devtools::document()`](https://devtools.r-lib.org/reference/document.html), `?what_time`, show the Rd file.

-   `use_testthat()`.

-   `use_test("time")`: first a simple test, then a snapshot test, then a snapshot of the error.

-   [`devtools::test()`](https://devtools.r-lib.org/reference/test.html) / test the file on its own via the button.

-   [`devtools::check()`](https://devtools.r-lib.org/reference/check.html)

-   Build and reload (install packages from RStudio build tab), try using the package from another session. Or install from GitHub.

:eyes: [roxygen2 website](https://roxygen2.r-lib.org/)

:eyes: [testthat website](https://testthat.r-lib.org/)

:eyes: [R Packages book, the whole game](https://r-pkgs.org/whole-game.html)

:toolbox: repeat the steps!

------------------------------------------------------------------------

## Documentation

:warning: rmarkdown and pkgdown needs your package to be *installed*.

-   `install.packages("rmarkdown")`, [`usethis::use_readme_rmd()`](https://usethis.r-lib.org/reference/use_readme_rmd.html), write stuff, knit, commit+push, look at GitHub repository.

-   `usethis::use_vignette("minipkg")`, write stuff.

-   `install.packages("pkgdown")`, [`usethis::use_pkgdown()`](https://usethis.r-lib.org/reference/use_pkgdown.html), [`pkgdown::build_site()`](https://pkgdown.r-lib.org/reference/build_site.html). Locally.

:eyes: [pkgdown website](https://pkgdown.r-lib.org/)

## GitHub Actions

-   [`usethis::use_github_action_check_standard()`](https://usethis.r-lib.org/reference/github_actions.html). Check on the cloud, different operating systems.

-   `usethis::use_github_action("pkgdown")`, change GitHub pages settings of the repo, add URL to pkgdown config and to DESCRIPTION.

:eyes: [usethis support for GitHub Actions setup](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: Repeat the steps!

------------------------------------------------------------------------

