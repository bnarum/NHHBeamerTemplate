# NHHBeamerTemplate

## TODO

- Title, part and section page design

- `\endpage{text here}` command

- `\SectionPagesOn` command

## Usage

## Installation

### Local installation of LaTeX

Download the repo to the folder `<TeX root>\tex\latex`. Run `texhash` to update dependencies. Note that admin privileges may be needed to enable making changes to the TeX root folder, including when `texhash` is run.

Development note: This does not neccessarily update when files are changed in the folder. Run `texhash` again.

### Overleaf

Download the repo and place it in a folder of the Overleaf document. Add the theme by `\usepackage{NHHBeamerTemplate/beamerthemenhh}` (this does the same as `\usetheme{nhh}` if the theme files had been in the tex search path).
