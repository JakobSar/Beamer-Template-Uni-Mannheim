# Beamer-Template-Uni-Mannheim

Classic and modern LaTeX Beamer templates for seminar and thesis presentations in a University of Mannheim style.

## Quick Start

1. Choose a template:
   - `Template_MA_Presentation_classic.tex`
   - `Template_MA_Presentation_modern.tex`
2. Put your images into `figures/`.
3. Compile:
   - Classic: `pdflatex Template_MA_Presentation_classic.tex`
   - Modern: `xelatex Template_MA_Presentation_modern.tex` (or `lualatex`)

## Included Files

- `Template_MA_Presentation_classic.tex` (classic style)
- `Template_MA_Presentation_modern.tex` (modern style)
- `fonts/` with Alegreya Sans (`Regular`, `Italic`, `Bold`, `BoldItalic`)
- `figures/` as shared image folder

## Font and Compiler Notes

- The modern template loads Alegreya Sans automatically with XeLaTeX/LuaLaTeX.
- With pdfLaTeX, the modern template uses a fallback font setup.
- The classic template is pdflatex-friendly.

## Why this repository

- University-style color palette
- Reusable slide structure for seminars and thesis updates
- Clean setup for sharing with others

Feel free to adapt and use for your own projects.
