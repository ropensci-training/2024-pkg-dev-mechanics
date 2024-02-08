---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: e466cb5a7c7e9048

---

## Reminder from last time

We have a package with a function.

------------------------------------------------------------------------

## A test

-   `use_testthat()`.

-   `use_test("time")`: first a simple test, then a snapshot test, then a snapshot of the error.

-   [`devtools::test()`](https://devtools.r-lib.org/reference/test.html) / test the file on its own via the button.

-   [`devtools::check()`](https://devtools.r-lib.org/reference/check.html)

:eyes: [testthat website](https://testthat.r-lib.org/)

------------------------------------------------------------------------

## More testing

-   Use [`withr::local_options()`](https://withr.r-lib.org/reference/with_options.html) in a test.

-   Look at the docs of [`testthat::test_path()`](https://testthat.r-lib.org/reference/test_path.html).

-   Create a helper function in a file `tests/testthat/helper-bla.R`, use it in a test.

:eyes: [withr website](https://withr.r-lib.org/)

:eyes: [Helper code and files for your testthat tests](https://blog.r-hub.io/2020/11/18/testthat-utility-belt/)

:toolbox: repeat the steps!

------------------------------------------------------------------------

## GitHub Actions

-   [`usethis::use_github_action_check_standard()`](https://usethis.r-lib.org/reference/use_github_actions.html). Check on the cloud, different operating systems.

:eyes: [usethis support for GitHub Actions setup](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: Repeat the steps!

------------------------------------------------------------------------

