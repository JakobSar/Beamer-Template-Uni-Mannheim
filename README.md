# Beamer-Template-Uni-Mannheim
LaTeX Beamer templates for seminar and thesis presentations (University of Mannheim style).

## Included Templates
- `Template_MA_Presentation_classic.tex`
- `Template_MA_Presentation_modern.tex`

## Compile
- `classic`: `pdflatex Template_MA_Presentation_classic.tex`
- `modern`: `xelatex Template_MA_Presentation_modern.tex` or `lualatex Template_MA_Presentation_modern.tex`

## Folder Structure
- `fonts/`  
  Contains Alegreya Sans (`Regular`, `Italic`, `Bold`, `BoldItalic`) used by the modern template.
- `figures/`  
  Shared image folder for template slides.

## Notes
- The modern template loads Alegreya Sans automatically for XeLaTeX/LuaLaTeX.
- With pdfLaTeX, the modern template falls back to default fonts.
- Feel free to adapt both templates for your own projects.
