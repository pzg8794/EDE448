# Module 3 Journal LaTeX Package

## Assignment

**Essential question:** What does meaningful communication look like for
students with complex needs?

**Blackboard destination:** Open the EDE448 course outline and select
Module 3 > Journal #3.

**Repository:** [pzg8794/EDE448-Module3-Journal](https://github.com/pzg8794/EDE448-Module3-Journal)

**Publication state:** Submission-ready GitHub/Overleaf review package. The
paper has not been submitted to Blackboard.

**Documented due date:** August 10, 2026, 11:59 PM EDT

## Review Status

This is a submission-ready review draft. It has not been submitted through
this workflow.

## Package Contents

- `main.tex` - Module 1/Module 2-themed journal entry point
- `sections/` - four journal sections
- `assets/` - two original public-safe portfolio visuals and provenance record
- `references.bib` - course, prior-work, TD Snap, EDU486, and placement sources
- `module3-journal-draft.md` - complete Markdown review draft and source trail

The paper connects Module 3 READ/MEDIA work, the posted TD Snap review and peer
reply work, the Communication Support Plan, EDE448 Modules 1--2, K--5 teaching
placement evidence, and EDU486 camp evidence through the Puzzle Plan and
EQUITAS lenses. Its four figures carry the argument from Module 2 agency,
through a shared visual communication surface and PTR evidence discipline, to
the Module 3 access-to-agency system. A de-identified camp partner incident is
used to identify adult-practice risks and concrete safety safeguards.

## Verification

- Compiled locally with TeX Live and BibTeX on August 9, 2026
- Eight pages total, including the title page and references
- Four legible, evidence-linked figures verified in the rendered PDF
- Original portfolio assets are checksum-documented in `assets/README.md`
- Partner-practice analysis is tied directly to Downing et al., Norrie et al.,
  Peckham-Hardin, the Communication Support Plan, and EQUITAS
- Exact essential-question wording preserved on the title page
- The internal READ/MEDIA placeholder was replaced with a cited
  *Wretches and Jabberers* synthesis grounded in the local course media record
- No unresolved citations or references in the latest local build
- Build byproducts are ignored so Overleaf receives a clean source package

## Build

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

## Evidence Boundary

The paper uses de-identified public course records and composite learner
planning. It does not publish raw recordings, private disclosures, child media,
or claims about diagnosis or internal states that the available evidence cannot
support.
