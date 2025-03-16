# Clarkesworld Print

A small utility to print ebook files from [Clarkesworld Magazine](https://clarkesworldmagazine.com/) in booklet form.

TODO:
- Images on printing and stapling process
- Option for how many pages at the end to skip
- use pipes where available, or clean up intermediate files
- OSX compatibility
- install script
- remove calibre requirement

### Requirements

Packages
- pdftk
- calibre
- texlibe-binextra (pdfbook2)
- cups

A printer accessible with CUPS

### Usage

`clarkesworld-print FILE PRINTER_NAME`

Ex: `clarkesworld-print clarkesworld_222.mobi brother-bw`

