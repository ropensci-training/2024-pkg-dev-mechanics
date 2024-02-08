---
outputs:
- Reveal
title: Become an R Package Developer!
hidden: true
layout: list
weight: 11
output: hugodown::md_document
countdown: true
rmd_hash: da86d884cda37933

---

# Package Development

<div class="highlight">

</div>

<div class="highlight">

{{< figure src="132682.jpeg" alt="Bike in repair room" caption="Picture by [Alexander Dummer on Pexels](https://www.pexels.com/photo/black-road-bicycle-inside-room-132682/)." width="400" >}}

</div>

------------------------------------------------------------------------

## My R package development creds

I really :heart: R package development

-   Volunteer editor for [rOpenSci Software Peer Review](https://ropensci.org/software-review).

-   At work, maintenance of [rOpenSci dev guide](https://devguide.ropensci.org).

-   Created the [R-hub blog](https://blog.r-hub.io).

-   Worked on the [HTTP testing in R](https://books.ropensci.org/http-testing/) book.

------------------------------------------------------------------------

## My R package development creds

Contributed to

-   [pkgdown 2.0.0](https://www.tidyverse.org/blog/2021/12/pkgdown-2-0-0/) (to produce documentation websites for packages)

-   [fledge 0.1.0](https://cynkra.github.io/fledge/) (Smoother change tracking and versioning for R packages)

-   [glitter 0.1.0](https://lvaudor.github.io/glitter/) (a SPARQL domain-specific language)

------------------------------------------------------------------------

## Why develop an R package?

Easiest way to share code/data/R Markdown templates... with

-   (future) you,

-   the collaborators you know,

-   and the collaborators you don't.

------------------------------------------------------------------------

## Why learning about package development?

[Jon Calder](https://joncalder.co.za/)'s very good [wording](https://github.com/iandurbach/datasci-fi/tree/master/docs/packages/slides)

-   To share code (and data);

-   To leverage existing tooling;

-   To contribute to other packages.

------------------------------------------------------------------------

## Who can write a package? YOU!

Susan Johnston's [wise words](https://github.com/susjoh/fibonacci).

-   Can you open R or RStudio?

-   Can you install a package?

-   Have you ever written a function in R?

-   Could you *learn* how to write a function in R?

:arrow_right: **You can write a package in R!**

------------------------------------------------------------------------

## Learn about functions

-   [Materials from Stephanie Kirmer's R-Ladies East Lansing tutorial](https://github.com/rladies-eastlansing/2021-rfunctions#writing-r-functions)

-   [Write your own R functions](https://stat545.com/functions-part1.html), stat 545 course by Jenny Bryan and The STAT 545 TAs;

-   [Chapter about functions](https://r4ds.had.co.nz/functions.html) in the book "R for Data Science" by Garrett Grolemund and Hadley Wickham;

-   [Fun with Functions talk](https://zealous-wiles-e22e83.netlify.app/talk/funwithfunctions/) by Kaylea Haynes, R-Ladies Manchester.

------------------------------------------------------------------------

## What is a package?

> Pour réduire ses craintes, il faut se dire que ce n'est ni plus ni moins qu'un dossier organisé d'une manière contrainte.

> To be less afraid you have to tell yourself that it's simply a folder organized in a constrained way.

[Sébastien Rochette](https://thinkr.fr/transformer-plusieurs-scripts-eparpilles-en-beau-package-r)

------------------------------------------------------------------------

## Automation!

{{< figure src="automate_meme.jpg" alt="Small monster saying to automate all the things" caption="Meme image by [Allie Brosh](https://en.wikipedia.org/wiki/Hyperbole_and_a_Half)" >}}

------------------------------------------------------------------------

## Automating... How?

Remember Clippy?

------------------------------------------------------------------------

## Automating... How?

Get to know an actually useful Clippy, `{usethis}`!

{{< figure src="https://usethis.r-lib.org/reference/figures/logo.png" alt="usethis logo, a robot" >}}

------------------------------------------------------------------------

## Why automate? Easier for...

Regular work, teaching, reproducing problems.

<div class="highlight">

{{< figure src="5446296.jpeg" alt="Bike wheel with tools on the floor" caption="Picture by [cottonbro studio on Pexels](https://www.pexels.com/photo/wrench-on-a-ground-5446296/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Goals for the three sessions

-   Get to know (the best :innocent:) tools for package development;

-   Learn that there is no magic, only practice and :sparkles: tips :sparkles:.

<div class="highlight">

{{< figure src="686230.jpeg" alt="Bike sign on a bike path, with tree leaves" caption="Picture by [Cristiana Raluca on Pexels](https://www.pexels.com/photo/white-bicycle-road-sign-686230/)." width="300" >}}

</div>

------------------------------------------------------------------------

## Website tour

:link: <https://rpkgdev-mechanics-2024.netlify.app/>

Slides, demo notes, further resources

<div class="highlight">

{{< figure src="3932867.jpeg" alt="Small kid on a balance bike" caption="Picture by [Tatiana Syrikova on Pexels](https://www.pexels.com/photo/anonymous-kid-in-helmet-riding-run-bike-on-pavement-in-countryside-3932867/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Time for the workshop :bicycle:

Alternating between watching and practicing in breakout rooms.

<div class="highlight">

{{< figure src="221237.jpeg" alt="Two bikes parked" caption="Picture by [Pixabay on Pexels](https://www.pexels.com/photo/two-bicycles-parked-upright-221237/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Back from the workshop

`{usethis}` for all the things.

<div class="highlight">

{{< figure src="206040.jpeg" alt="Cycle path sign" caption="Picture by [Nika Dzamashvili on Pexels](https://www.pexels.com/photo/black-and-white-bicycle-road-sign-206040/)." width="400" >}}

</div>

------------------------------------------------------------------------

## usethis related content in `.Rprofile`

Like saving the settings of a bike.

No need to adjust the saddle height every time you go for a ride!

------------------------------------------------------------------------

## Two wheels always turning :bike:

-   loading, trying out, editing.

-   running (adding) the tests, editing. Next time!

------------------------------------------------------------------------

## R CMD check (devtools::check())

<div class="highlight">

{{< figure src="4543112.jpeg" alt="Bike traffic light" caption="Picture by [cottonbro studio on Pexels](https://www.pexels.com/photo/traffic-light-on-red-light-4543112/)." width="300" >}}

</div>

------------------------------------------------------------------------

## Questions?

See you at the next package development training?

Prepare questions in advance, send them in advance if you can.

<iframe src="https://giphy.com/embed/XFpCAWSfTwXh2uSEk2" width="480" height="269" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/moon-et-extra-terrestrial-XFpCAWSfTwXh2uSEk2">via GIPHY</a></p>

