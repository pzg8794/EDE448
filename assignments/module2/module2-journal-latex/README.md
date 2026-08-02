# Module 2 Journal LaTeX Package

## Assignment

**Essential question:** How can support strategies respect dignity, consent,
and neurodiversity?

**Blackboard destination:** [Module #2 Journal](https://learn.rochester.edu/ultra/courses/_113760_1/outline/journal/_9485976_1?courseId=_113760_1)

**Dedicated repository:** [pzg8794/EDE448-Module2-Journal](https://github.com/pzg8794/EDE448-Module2-Journal)

**Documented due date:** July 31, 2026, 11:59 PM EDT

## Review Status

This is an almost-ready review draft. It has not been submitted through this
workflow.

## Package Contents

- `main.tex` - Module 1-themed journal entry point
- `sections/` - four journal sections
- `references.bib` - course, prior-work, and EDU486 sources

The paper updates the existing Markdown journal rather than replacing its core
argument. It connects the submitted Module 1 journal to the Module 2 READ and
MEDIA, teaching-placement experience, and public-safe EDU486 evidence through
the July 31 youth retrospective.

## Verification

- Compiled with TeX Live and BibTeX on August 1, 2026
- Seven pages total, one page shorter than the submitted Module 1 journal
- 2,335 body words, excluding the cover and references
- All seven rendered pages visually reviewed
- No unresolved citations, references, or overfull boxes

## Build

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

## Evidence Boundary

The paper uses de-identified public camp records. It does not publish youth
names, raw recordings, private disclosures, or claims about internal states
that the evidence cannot support.
