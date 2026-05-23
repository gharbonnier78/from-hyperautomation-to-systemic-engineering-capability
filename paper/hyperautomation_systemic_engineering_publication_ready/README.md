# Hyperautomation and Systemic Engineering Capability

Publication-ready LaTeX package for the reflective research memo:

**From Hyperautomation to Systemic Engineering Capability**

## Build

Requires `pdflatex` and `biber`.

```bash
pdflatex -interaction=nonstopmode main.tex
biber main
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

## Notes

This version includes:
- corrected bibliographic metadata for Hidalgo & Micco (World Development, DOI 10.1016/j.worlddev.2024.106617),
- corrected OECD FDI DOI (10.1787/fd8fb41c-en),
- replacement of the UNIDO web/editorial reference with the formal Industrial Development Report 2024 entry,
- explicit definition of Sociotechnical Systems (STS) in the glossary,
- correct rendering of Schön,
- a visual decision-framework figure.
