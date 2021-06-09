# Duke PhD Thesis

The [thesis](./tex/thesis.tex) document is based on the LaTeX template from the
[Duke graduate school](https://gradschool.duke.edu/academics/theses-and-dissertations). 
To compile this document, see the [compile](./tex/compile) script.

The main document is `thesis.tex`. The `dukethesis.cls` file contains formatting
information. The `bibliography.bib` file is an example
BibTeX bibliography file. Figures included in the main text are found in
the `graphics/` directory. The helper scripts `compile` and `tidy` might be useful when
compiling the `tex` document or to clean-up the `bib` file.

## FIXME
To conform to formatting guidlines, some sections are forced to be single
spaced. The class file should be modified to account for these changes and make
the main `tex` document cleaner.
