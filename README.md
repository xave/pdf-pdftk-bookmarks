# pdf-pdftk-bookmarks
Convert simple table of contents list to pdftk format for insertion into Adobe PDF

## DESCRIPTION
This iPython notebook takes a lightly processed input text file (`input.toc`) which has the table of contents for a book and converts it into a format that the tool pdftk can use (`pdftk-format.bkmk`) to insert it into an Adobe PDF document.

## WORKFLOW

`input.toc` -> `pdftk-format.bkmk` -> `insert-to-PDF`
