# markdown-thesis
Makefile workflow to convert Markdown to a PDF thesis and Word thesis

# Description

* This uses a Makefile to turn a collection of markdown files into one pdf and word.
* Pandoc is used to convert markdownn files into tex files and Microsoft word documents.atexmk is used to convert tex into a PDF
* The markdown files are stored in ./sections/ folder.
* This takes figures from ./figures/. It can takeany image format and coverts svg and tikz to pdf before embedding.
* The bib references are stored in /references/ folder.
