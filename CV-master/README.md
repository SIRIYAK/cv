# <img src="img/SIRI.jpg" alt="siriyak cr" width="92"/>

[![](./img/SIRI.png)](<https://github.com/SIRIYAK/cv/blob/main/CV-master/CV.pdf)>

# My [PDF](https://907a8e4509b0462a9b40f487672a6d48.app.rstudio.cloud/file_show?path=%2Fcloud%2Fproject%2FCV-master%2FCV.pdf "click") Data Driven CV

## What

This CV is created using the **`R`** Package [`vitae`](https://github.com/SIRIYAK/cv.git)

------------------------------------------------------------------------

> ***Curriculum Vitae***
>
> a short account of one's career and qualifications prepared typically by an applicant for a position
>
> --- Merriam Webster's Dictionary

------------------------------------------------------------------------

## Why

Automation eases how much manual work needs to be performed on any particular task. As developers, programmers, software engineers, etc. our skills are put to good use when we automate manual work for the betterment of others, and ourselves.

I needed a CV that i can easily update, gets out of my way, and is easily accessible when i need it.

## How

This document utilizes **RMarkdown** and is compiled through pandoc.

I use various other packages with `vitae` such as `here`, `tibble`, `glue`, and `magrittr` (for the pipe *`%>%`*)

With RStudio i read in my *tribbles* contained in the `data.r` script containing all my data, then using the `vitae` functions and `glue` string literals, i create the document itself.

Data exists in in the `data.r` file in the `r/` directory and is added to the CV when the script is sourced by the `RMarkdown` document in the main directory.

The header portion of the document is comprised in the `YAML` portion of the `RMarkdown` document.
