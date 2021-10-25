# NHHBeamerTemplate

## TODO

- Title, part and section page design

- `\endpage{text here}` command

- `\SectionPagesOn` command

## Usage

Load the theme using `\usetheme{nhh}` in the preamble. See details about Overleaf in installation instructions.

### Extra commands

- `\colseparator`: Inserts yellow rule within columns environment as a separator between columns.
- `\SectionPagesOn`: Inserts a section page at each section start.
- `\SectionPagesOff`: Removes automatic section pages.
- `\finalpage`: Makes the final page with "Thank you!" on it, similar to titlepage.

## Installation

### Local installation of LaTeX

Place the repo in the folder `<TeX root>\tex\latex`. Run `texhash` to update dependencies. Note that admin privileges may be needed to enable making changes to the TeX root folder, including when `texhash` is run.

### Overleaf

Download the repo and place it in a folder of the Overleaf document. Add the theme by `\usepackage{NHHBeamerTemplate/beamerthemenhh}` (this does the same as `\usetheme{nhh}` if the theme files had been in the tex search path).
