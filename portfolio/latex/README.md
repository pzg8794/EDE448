# Portfolio LaTeX Package

This folder contains the canonical editable source for the EDE448 **Communication and Positive Behavioral Support Strategies and Resources Portfolio**.

## Package Structure

- `main.tex`: title page, assignment/rubric map, portfolio map, synthesis, and document assembly
- `resources/`: ten numbered standalone practitioner resources
- `references.bib`: unified APA-style source trail
- `../../output/pdf/EDE448-Communication-and-Behavioral-Support-Portfolio.pdf`: local compiled review copy; ignored by Git

The earlier [portfolio plan](../portfolio-plan.md) and [resource template](../resource-template.md) remain planning provenance. They are not competing submission drafts.

## Build

From this directory:

```bash
latexmk -pdf main.tex
```

After review, copy `main.pdf` to:

```text
../../output/pdf/EDE448-Communication-and-Behavioral-Support-Portfolio.pdf
```

## Evidence Boundary

The Pine Brook and EDU486 examples are de-identified practice evidence. The Communication Support Plan is a prospective scenario. The Kit for Kids source remains labeled as a simulation draft, so the portfolio presents it as a practice-informed lesson design rather than claiming independently verified delivery. Copyrighted OAR and PTR materials are cited or linked, not reproduced.

## Submission State

The ten-resource editable package was compiled and visually reviewed on August 6, 2026. The 26-page local review PDF is at the path above. Piter's final content approval and manual Blackboard submission remain; nothing has been submitted through this repository.
<!-- End of canonical portfolio package reference. -->