---
title: Snippets
weight: 1
hidden: true
chapter: false
disableToc: false
---

For copy-pasting during demos.

```r
what_time <- function() {
  time <- format(Sys.time(), "%H:%M")
  sprintf("It is %s now!", time)
}
```

```r
what_time <- function(language = "fr") {

  if (!language %in% c("fr", "en")) {
    stop("Either choose 'fr' or 'en' as a language.")
  }

  time <- format(Sys.time(), "%H:%M")
  
  switch(
    language,
    fr = sprintf("Il est maintenant %s!", time),
    en = sprintf("It is %s now!", time)
  )
  
}
```

```r
what_time <- function(language = "fr") {

  rlang::arg_match0(language, c("fr", "en"))

  time <- format(Sys.time(), "%H:%M")

  exclamation <- praise::praise("${Exclamation}")

  switch(
    language,
    fr = sprintf("%s! Il est maintenant %s!", exclamation, time),
    en = sprintf("%s! It is %s now!", exclamation, time)
  )
}
```
  

```r
#' Current time
#'
#' Returns a sentence with the current time
#'
#' @param language Language either "fr" (French) or "en" (English)
#'
#' @return A character string
#' @export
#'
#' @examples
#' what_time()
what_time <- function(language = "fr") {

  rlang::arg_match0(language, c("fr", "en"))

  time <- format(Sys.time(), "%H:%M")

  exclamation <- praise::praise("${Exclamation}")

  switch(
    language,
    fr = sprintf("%s! Il est maintenant %s!", exclamation, time),
    en = sprintf("%s! It is %s now!", exclamation, time)
  )
}
```


```r
test_that("what_time() works", {
  expect_type(what_time(), "character")
  expect_snapshot(what_time(language = "bla"), error = TRUE)
})
```
