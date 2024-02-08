---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: d5ff174db2be59d8

---

## System setup

-   `.Library`, [`.libPaths()`](https://rdrr.io/r/base/libPaths.html)

-   `install.packages("devtools")`. [Setup chapter of the R packages book](https://r-pkgs.org/setup.html).

-   `install.packages("pak")`.

-   [`devtools::has_devel()`](https://pkgbuild.r-lib.org/reference/has_compiler.html)

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

## A first function

-   `usethis::use_r("time")`. Explain what [`sprintf()`](https://rdrr.io/r/base/sprintf.html) does.

-   `devtools::load()`, `what_time()`.

-   add an argument.

-   `devtools::load()`, `what_time()`, `what_time(language = "en")`.

:toolbox: Repeat the steps!

------------------------------------------------------------------------

## Use dependencies

-   add two dependencies, `use_package("praise")` and `use_package("rlang")`.

-   `devtools::load()`, `what_time()`, `what_time(language = "en")`.

:toolbox: Repeat the steps!

------------------------------------------------------------------------

## Manual page

-   Insert roxygen2 skeleton.

-   [`devtools::document()`](https://devtools.r-lib.org/reference/document.html), `?what_time`, show the Rd file.

-   Build and reload (install packages from RStudio build tab), try using the package from another session. Or install from GitHub.

:eyes: [roxygen2 website](https://roxygen2.r-lib.org/)

:eyes: [R Packages book, the whole game](https://r-pkgs.org/whole-game.html)

:toolbox: Repeat the steps!

------------------------------------------------------------------------

