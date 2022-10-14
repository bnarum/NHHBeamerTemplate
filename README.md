# NHHBeamerTemplate

This is a template for presentations made by beamer in LaTeX inspired by the design template of NHH Norwegian School of Economics. See `nhh-example.pdf` for a usage example.

## Usage

Load the theme using `\usetheme{nhh}` in the preamble. See details installation instructions below. Additional outer themes can be used by also loading `\useoutertheme{miniframes}`, for example. For supporting pages, like title, final page and section titles, it is adviced to use the provided commands below to consistency in some design effects. 

See `nhh-example.tex` for a template to get started.

### Extra commands

Some commands have been added for convenience:

- `\TitlePageOn`: Inserts a title page
- `\AgendaPageOn{<text>}`: Inserts page with content
- `\FinalPageOn{<text>}`: Makes the final page with text
- `\SectionPagesOn`: Inserts a section page at each section start
- `\SectionPagesOff`: Removes automatic section pages
- `\colsep`: Inserts yellow rule within columns environment as a separator between columns.

## Installation

### Local installation with TeXLive

- Download the repo to `<TeX root>/tex/latex` on your computer.

- Run `texhash` to update dependencies. This holds for texlive, the command may be different for other TeX-distributions.

The template can now be imported to any project in the preamble and changes made to the repo will update automatically.

Alternatively, you can make a symbolic link from the repo to the folder `<TeX root>/tex/latex`. Unix command: `ln -s source target`, Windows:  `mklink /D Target Source`. Admin privileges may be needed to enable making changes to the TeX root folder, including when `texhash` is run.

### Overleaf

Download the repo and place it in the root folder of the Overleaf project. Add the theme by `\usepackage{NHHBeamerTemplate/beamerthemenhh}` (this does the same as `\usetheme{nhh}` if the theme files had been in the TeX search path).
