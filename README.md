# Oppkey quarto demo for R Consortium Blog

<https://oppkey.com/quarto/>

## Features

- R snippets rendered to chart automatically
- [tidyverse](https://www.tidyverse.org/) example
- [knitr](https://yihui.org/knitr/) example
- [dygraphs](https://dygraphs.com/)
- LaTeX math output, using tinytex
- ggplot

## Objectives

- show stakeholders that multiple Oppkey staff can edit the content and scale the volume of content if needed
- show we can handle acceptable styling, using R Consortium logos and colors
  - we need to [edit the quarto themes](https://quarto.org/docs/output-formats/html-themes.html#theme-options)
- illustrate that infrastructure can scale. Currently on GitHub Pages, but we can deploy to Netlify as an alternate example

## How to Edit

- add new posts in the `posts` folder
- posts are rendered to `docs` folder
- push up to GitHub to publish to GitHub Pages

## Notes

- Used R Studio on Windows 11 (not WSL) as I ran into problems with WSL and VS Code
- installed tidyverse through the R Studio interface
- Needed to install RTools for dygraphs
- quarto examples: <https://quarto.org/docs/gallery/>

### Setup for Contributors

Install R using `sudo apt-get install r-base` and `sudo apt-get install r-base-dev`

Install R packages on Linux; type `R` in console and then `install.packages('rmarkdown')`

GGPLOT2 installation: `install.packages("ggplot2")`

dygraphs installation : `install.packages("dygraphs")`