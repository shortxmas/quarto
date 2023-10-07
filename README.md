# Oppkey quarto demo for R Consortium Blog

<https://codetricity.github.io/quarto-demo/>

## Features

* R snippets rendered to chart automatically
* [tidyverse](https://www.tidyverse.org/) example
* [knitr](https://yihui.org/knitr/) example
* [dygraphs](https://dygraphs.com/)
* LaTeX math output

## Objectives

* show stakeholders that multiple Oppkey staff can edit the content and scale the volume of content if needed
* show we can handle acceptable styling, using R Consortium logos and colors
  * we need to [edit the quarto themes](https://quarto.org/docs/output-formats/html-themes.html#theme-options)
* illustrate that infrastructure can scale.  Currently on GitHub Pages, but we can deploy to Netlify as an alternate example

## How to Edit

* add new posts in the `posts` folder
* posts are rendered to `docs` folder
* push up to GitHub to publish to GitHub Pages

## Notes

* Used R Studio on Windows 11 (not WSL) as I ran into problems with WSL and VS Code
* installed tidyverse through the R Studio interface
* Needed to install RTools for dygraphs
* quarto examples: <https://quarto.org/docs/gallery/>

## Why are we doing this project?

We work with the [R Consortium](https://www.r-consortium.org/). We have a strong program of producing blog content for them covering their R User Groups (RUGS). If we expand our content to cover R programming topics, we can do an upsell and get more revenue.

The RUGS blog posts are hosting on the R Consortium's website which is WordPress. It's not good that the leading proponent of the R language does not use R to build its own website.

If we build a prototype site that shows the possibility of running a R programming blog running on Quarto, the R Consortium has already indicated they will pay for this.

### Main components (for discussion)

| Action      | Status | Difficulty |
| ----------- | ----------- | ----------- |
| Produce basic version running quarto      | Completed, live at [https://oppkey.com/r-quatro/](https://oppkey.com/r-quatro/)       | Challenging - 1-2 days |
| Prepare for first demo by Thurs, Oct 12, 2023. Get input from Joseph Rickert, R Consortium exec director.   | Depends on progess with Erik Mon (Oct 9) and Tues (Oct 10). Thursday meeting is a previously scheduled regular internal meeting. Rickert is not waiting to see the demo. This date can be changed. | Medium - 1 hour meeting, before and after discussion gathering feedback |
|Move from GitHub Pages to Netlify| not started| Medium - half day - requires building new workflow - Want Erik to lead |
|Improve styling, echo R Consortium colors, mainly the blue from the titles on the homepage (What is the R Consortium?) | not started | Easy - 1 hour |
|Add separate instructions page, like About, explaning how to draft a post with code snippets | not started | Easy - 1 hour - Grab instructions from online, included .qmd syntax and exporting from RStudio IDE |

### Developing content for the site (i.e. Who does the blog posts?)

We (Oppkey) have good contacts with the R Consortium technical committee and the governing board to connect with writers. Oppkey can build full management structure to schedule and manage getting blog content.

Goal: Build a site running Quarto, hosted on Netlify, able to publish 2 blog posts per month. We will require authors submit their posts in rmarkdown.

Staff: Jesse and Ilenia. And Oppkey writer team, currently Mahzeb in Pakistan and Karol in Mexico.

### Future Improvements

If R Consortium pays for the project, after 6 months, we should add login functionality. Similar to the functionality that we have partially built for the [THETA Plug-ins site](https://thetaplugin.oppget.com/dashboard). (Note: /dashboard only works if you have an account and have plug-ins attributed to the account.) So that outside blog contributors can post drafts for Oppkey staff to review, schedule and publish.
