# Dissertation LaTeX Template

This template is based on the [Dissertation Formatting Manual](https://guides.lib.uci.edu/gradmanual/templates) from the UC-Irvine Libraries. The design uses the [arXiv style](https://github.com/kourgeorge/arxiv-style) which is based on the the [NeurIPS](https://nips.cc/) styling. The reference style includes [AEA](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-econometrica.bst) (lastname, firstname) and [Econometrica](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-aea.bst) (lastname, abbreviated firstname).

Based on the NIPS styling, it makes this dissertation template esthetic and convenient for reading. Instead of integrating the formatting into a single style file, this template defines the styles and format in the `main.tex` preambles and collects all the imported packages in the `package.sty` making the source more transparent and easier to customize.

Various LaTeX syntaxes are also demonstrated throughout the document such as spacing, hyperlinked footers, abbreviations, coloring, listing, table-of-contents customization, hyper-referencing, figure and table formatting with decimal alignment, mathematics symbols, and graphic elements. Users can refer to the syntax during editing.

🎉 The compiled template PDF can be viewed [here](https://www.haochehsu.com/other/Dissertation_LaTeX_Template.pdf).

---

### 🖋 The Template
This template includes:
  - Settings: `package.sty`
  - Content: `main.tex`, `Chapter1.tex`, `Chapter2.tex`, `Chapter3.tex`, `reference.bib` (references database)
  - Style files:
    - arXiv style: `arxiv.sty`
    - Bibliography style: `aea.bst` and `ecta.bst`

### 📐 Usage

User only need to customize the `package.sty` in the `Style` folder and edit the 5 **Content** files. Bibliography style is located in `main.tex`: 

```tex
\bibliographystyle{Style/aea} # Style/ecta
```

#### Online

For online editing, [download](https://github.com/howardhsumail/Dissertation-LaTeX-Template/archive/refs/heads/main.zip) the template, upload all the files and folders to [Overleaf](https://www.overleaf.com/), and compile the `main.tex` as demonstrated [here](https://www.overleaf.com/read/ptbfthrmnmrv).

#### Offline

For local editing, [download](https://github.com/howardhsumail/Dissertation-LaTeX-Template/archive/refs/heads/main.zip) the template and edit it with [Texmaker](https://www.xm1math.net/texmaker/) or [TeXstudio](https://www.texstudio.org/) (requires [MacTeX](https://www.tug.org/mactex/) for Mac and [MiKTeX](https://miktex.org/download) for Windows) or [Texpad](https://apps.apple.com/us/app/texpad-latex-editor/id458866234?mt=12).

### 📒 General Notes

For help, comments, bug reporting, and change requests, please [contact](mailto:howardhsumail@gmail.com) the [author](https://www.haochehsu.com/). You can use or redistribute this project, however, the author takes no responsibility for whatever usage of this template. Finally, you are very welcome to contribute to this template.

---

The UCI dissertation template on overleaf can be accessed [here](https://www.overleaf.com/latex/templates/university-of-california-irvine-thesis/bzsqmxszcpny). The compiled UCI template PDF can be viewed [here](https://www.haochehsu.com/other/uci_thesis_template.pdf).
