This set of markdown is meant to be used with pandoc to provide an easy way to write a scientific paper in markdown. 

**_To write your own paper, fork this repository and start writing!_**

Here's an example commandline for the compilation of this set of markdown files to pdf, using xelatex and our template. Beautification is done by changing parameters in the abstract.md file preamble, and more detailed tweaking can be performed in the `templates/template.latex` file.

```
[//]: # pandoc --filter pandoc-citeproc --bibliography lib/papers_library.bib --latex-engine=xelatex --template=templates/template.latex abstract.md introduction.md results.md discussion.md methods.md -f markdown -t latex -s -o versions/first.pdf
```

# Overview of changes

## Text:

### introduction


## Figures:
