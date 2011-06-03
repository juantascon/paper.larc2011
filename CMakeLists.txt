cmake_minimum_required(VERSION 2.6)

include(UseLATEX)

add_latex_document(larc2011.tex
  INPUTS
  abstract.tex introduction.tex architecture.tex
  system.tex software.tex tests.tex conclusion.tex
  BIBFILES automation.bib
  IMAGE_DIRS img
  DEFAULT_PDF
  MANGLE_TARGET_NAMES
)
