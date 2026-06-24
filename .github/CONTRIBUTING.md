# Contributing to trusted-mini-agents-external

This outlines how to propose a change to `trusted-mini-agents`.
For a detailed discussion on contributing to this and other tidyverse packages, please see the [development contributing guide](https://rstd.io/tidy-contrib) and our [code review principles](https://code-review.tidyverse.org/).

## Fixing typos

You can fix typos, spelling mistakes, or grammatical errors in the documentation directly using the GitHub web interface, as long as the changes are made in the _source_ file. 
This generally means you'll need to edit [roxygen2 comments](https://roxygen2.r-lib.org/articles/roxygen2.html) in an `.R`, not a `.Rd` file. 
You can find the `.R` file that generates the `.Rd` by reading the comment in the first line.

## Bigger changes

If you want to make a bigger change, it's a good idea to first file an issue and make sure someone from the team agrees that it’s needed. 
If you’ve found a bug, please file an issue that illustrates the bug with a minimal 
[reprex](https://www.tidyverse.org/help/#reprex) (this will also help you write a unit test, if needed).
See our guide on [how to create a great issue](https://code-review.tidyverse.org/issues/) for more advice.

### Pull request process

*   Fork the repository and clone onto your computer. If you haven't done this before, we recommend using `usethis::create_from_github("wlandau/trusted-mini-agents", fork = TRUE)`.

*   Make your changes, commit to git, and then create a PR by running `usethis::pr_push()`, and following the prompts in your browser.
    The title of your PR should briefly describe the change.
    The body of your PR should contain `Fixes #issue-number`.

### Code style

*   New code should follow the tidyverse [style guide](https://style.tidyverse.org). 
    You can use [Air](https://posit-dev.github.io/air/) to apply this style, but please don't restyle code that has nothing to do with your PR. 

## Code of Conduct

Please note that the trusted-mini-agents project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to this
project you agree to abide by its terms.
