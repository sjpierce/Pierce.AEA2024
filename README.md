# README
Steven J. Pierce

<!-- README.md is generated from README.Rmd. Please edit that file -->

# Pierce.AEA2024: Reproducibility Materials For My AEA 2024 Presentation

<!-- badges: start -->

[![](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
<!-- badges: end -->

This repository holds materials for one of my conference presentations
(Pierce, 2024, October 21-26). Its primary purpose is for me to use
version control tools while developing my slides, but its secondary
purposes include distributing the slides to my audience and
demonstrating how to use Quarto to create slides. I plan to make the
repository public after delivering the presentation.

## Assumptions

There are two different types of users of this repository: myself and my
audience. I assume most of my audience just wants copies of [my
slides](https://github.com/sjpierce/Pierce.AEA2024/Slides.html), but
some may want to see exactly how they were created by examining other
parts of the repository.

> **Tip:** After you open the
> [Slides.html](https://github.com/sjpierce/Pierce.AEA2024/Slides.html)
> file, press the `s` key on your keyboard to see the speaker view that
> contains my speaker notes. There are also other [slide navigation
> keyboard
> shortcuts](https://quarto.org/docs/presentations/revealjs/presenting.html).

Since there are no other contributors, I am omitting details that may
otherwise be useful to collaborators. However, here is a link to my web
page on [software for reproducible research with
R](https://sjpierce.github.io/rr_software.html). This presentation uses
the Quarto extension called `reveal-header`
(https://github.com/shafayetShafee/reveal-header). Installing that
created the `_extensions/` subfolder here.

## Repository Structure and Contents

The structure for the repository is shown in the outline below, where
folder names and file names are `highlighted like this` and comments are
in normal text. The repository is set up as an [RStudio
project](https://support.rstudio.com/hc/en-us/articles/200526207-Using-RStudio-Projects).

- `Pierce.AEA2024/`: This is the root folder for the repository.
  - `.git/`: This hidden folder is used by Git. Leave it alone!
  - `.quarto/`: This hidden folder may be created by Quarto to hold
    temporary files. Do not edit or delete any of these files unless you
    know what you are doing! This folder is not tracked by Git.
  - `.Rproj.user/`: This hidden folder is used by Rstudio. Leave it
    alone!
  - `_extensions/`: This folder contains files for Quarto extensions
    used by my presentation slides.
  - `graphics/`: This folder stores `.jpg` and `.png` graphics files
    used in my slides.
  - `scripts/`: The folder holds script files that I occasionally find
    useful.
    - `Delete_nul_file.bat`: This Windows batch files can be useful if
      rendering problems leave behind a file called `nul` that is
      otherwise hard to delete on Windows.
  - `.gitignore`: This file tells Git what files to ignore and omit from
    synchronizing with the main repository on GitHub.
  - `_quarto.yml`: This is a Quarto metadata file containing
    project-level YAML code that will be inherited by Quarto scripts in
    this folder or its subfolders.  
  - `apa.csl`: This is a citation style language file for the
    Publication Manual of the American Psychological Association, 7th
    edition. It is used by Quarto to format references.
  - `apa-numeric-superscript.csl`: This is a citation style language
    file for the Publication Manual of the American Psychological
    Association, 7th ed. that has been adapted to use numeric
    superscripts for in-text citations and put the reference list in the
    order the citations were used. It is used by Quarto to format
    reference sections.
  - `apa-numeric-superscript-brackets.csl`: This is a citation style
    language file for the Publication Manual of the American
    Psychological Association, 7th ed. that has been adapted to use
    numeric superscripts in square brackets for in-text citations and
    put the reference list in the order the citations were used. It is
    used by Quarto to format reference sections.
  - `CSTAT_theme.css`: This is custom style sheet file to provide color
    scheme, fonts, etc. for my slides.  
  - `Pierce.AEA2024.Rproj`: This is an RStudio project file. It contains
    some settings for working with the project in that software.
  - `README.md`: This file is obtained by knitting the `README.Rmd` file
    and is used by GitHub to display information about the repository.
    Do not edit it manually: just re-knit `README.Rmd` to update it. In
    R Studio, you can read the formatted version by opening the file and
    clicking the Preview button.
  - `README.Rmd`: This file gives an introduction to the repository.
    Rendering it produces the `README.md` file and opens the preview
    automatically.
  - `references.bib`: This is a BibTeX file containing citation data for
    papers, software, etc. that we want to cite anywhere in our Quarto
    scripts throughout the package.
  - `Slides.html`: This output file contains the actual slides I used to
    give the presentation.
  - `Slides.qmd`: Rendering this Quarto script creates my HTML slides.

## Rendering The Slides

To render my presentation slides from the source code:

- Double-click the `Pierce.AEA2024.Rproj` file from Windows Explorer to
  open the RStudio project.
- Use RStudio to open the file `Slides.qmd`.
- Click the *Render* button in RStudio.

That will generate the `Slides.html` file containing the final slides.

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0" line-spacing="2">

<div id="ref-Pierce-RN8577" class="csl-entry">

Pierce, S. J. (2024, October 21-26). *Generating reproducible
statistical analyses and evaluation reports: Principles, practices, and
free software tools* \[Demonstration session\]. Evaluation 2024:
Amplifying; Empowering Voices in Evaluation, the annual conference of
the American Evaluation Association, Portland, OR, United States.
<https://github.com/sjpierce/Pierce.AEA2024>

</div>

</div>

## Citing This Repository

Please cite my actual presentation (Pierce, 2024, October 21-26).
