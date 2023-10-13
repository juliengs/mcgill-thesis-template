# Thesis Template for McGill - LaTeX and LyX

Context: I have recently obtained my PhD in Computer Science at McGill University. When I started working on my thesis in the Summer of 2016, I came accross a pretty amazing LaTeX-based template which provides a very esthetically-pleasing output.

_Disclaimer: I am not the author of this template. I am not sure yet who invented it and where it came from, and I will attempt to find out in order to credit this template to it's proper authors._

In this repository, I am providing for convenience the LaTeX version of this template (which I did not create), as well as an adaptation of this template to the _LyX document processor_ software which I've generated from the LaTeX template.

**New (oct 2023)**: [Maximilian Schiedermeier](https://www.cs.mcgill.ca/~mschie3/) has created another template, which is available directly on Overleaf: https://www.overleaf.com/latex/templates/mcgill-phd-thesis-template/fcrypzwmskwc

## LaTeX Template

LaTeX is a de-facto document processing language for writing papers in the scientific community. As an academic's papers are often written in LaTeX, it makes sense to write one's thesis in LaTeX too, as it eases material reuse (i.e., snippets, figures, graphs, etc.). The LaTeX template provided in this repository cleanly decouples the different parts of the thesis into a logical directory structure and several LaTeX source files.

## LyX Template

My former advisor, Dr Jörg Kienzle at McGill University, introduced me to LyX, which provides a nice WYSIWYM (what you see if what you mean) way to write papers, as an alternative to LaTeX. While LyX outputs LaTeX code, and allows one to insert LaTeX code in a document, I find working with LyX easier and generally more efficient as it offers a nice partly-formatted graphical view of the document that I am editing, rather than viewing code. LyX also provides some nice time-saving features such as a rich cross-referencing system, management of citations from a bib file, insertion of graphics/images, hierarchical multi-document editing support as well as many collaborative features (notes, annotations, change tracking, etc.).

My goal being to be able to write my thesis using LyX, I did a rough conversion of the LaTeX template to LyX, along with several tweaks here and there. It is not a perfect conversion, there are some small quirks such as having several LaTeX snippets inserted in the main thesis document and a rather heavy "document preamble". Nevertheless, it preserves the spirit of LyX and allows one to work efficiently with this tool and organize one's thesis in multiple parts/chapters in several files, etc.

## Bottom Line

These template can be used to write a McGill thesis, but they can certainly be adapted to write thesis for other institutions with minimal effort. Please don't hesitate to fork this repository if you adapt these for other institutions and please let me know -- I will be happy to provide links to these.

## Quick tips

* To change the margins (LaTeX and LyX), please edit latex-pkg/defaultcustom.tex, line 113

* The title page can be edited through file FirstPage.tex / FirstPage.lyx
