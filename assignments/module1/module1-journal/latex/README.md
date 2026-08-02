# EDE 448 Module 1 Journal - LaTeX Package

This folder contains the formal LaTeX version of the Module 1 journal response to the essential question:

> How does the world come to understand developmental differences?

## Files

- `module1_journal.tex` - main LaTeX source
- `references.bib` - APA-style bibliography source
- `Module_1_Journal.pdf` - compiled submission-ready paper

## Build

```bash
pdflatex module1_journal.tex
bibtex module1_journal
pdflatex module1_journal.tex
pdflatex module1_journal.tex
```

The layout is adapted from the EDE448 Sensory Walk LaTeX package while preserving this journal's own title, structure, and argument.
