installed eepic

added \usepackage{ragged2e} to package.tex - needed for justify command
set \usepackage[demo]{graphicx} - compile without figures.

can't get the ifelsethen statement to work - so commented out. output is when edthesis = true

issue with \begin{prefacepart}\end - commented out.

added [demo] to graphicx package preamble (\usepackage[demo]{graphicx}) = allows .tex to compile without figures.

major issues with commands: tableparts, toprule, colrule and botrule.
added definations for them in definiation.tex but top,col,bot rule still doesn't work.

changed some stuff in chapter2.tex

changed [h0123] to [h]

removed dangling '\\'
deleted \hline from appendix.tex:397, 405
