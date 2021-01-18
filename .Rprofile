source("renv/activate.R")
source("~/.Rprofile")

.First.sys()

if(interactive()) {
  source("code/00_options.R")
  library(tidyverse)
}

options(knitr.graphics.auto_pdf = TRUE)

html_caption_if_necessary <- function(x) {
  if(knitr::is_html_output()) {
    x <- stringr::str_replace_all(x, "\\\\textbf\\{(.*?)\\}", "**\\1**")
  }
  x
}
