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

- Download the repo to a folder on your computer.

- Make a symbolic link from the repo to the folder `<TeX root>/tex/latex`. For Unix use the terminal and specify `ln -s source target`. For Windows use Cmd and specify `mklink /D Target Source`.

- Run `texhash` to update dependencies. This holds for texlive, the command may be different for other TeX-distributions.

Note that admin privileges may be needed to enable making changes to the TeX root folder, including when `texhash` is run.

The template can now be imported to any project in the preamble and changes made to the repo will update automatically.

### Overleaf

Download the repo and place it in a folder of the Overleaf document. Add the theme by `\usepackage{NHHBeamerTemplate/beamerthemenhh}` (this does the same as `\usetheme{nhh}` if the theme files had been in the TeX search path).
