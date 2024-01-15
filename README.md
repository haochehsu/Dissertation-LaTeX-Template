# Dissertation LaTeX Template

This double-spaced template is based on the [Dissertation Formatting Manual](https://guides.lib.uci.edu/gradmanual/home)[^1] from the UC-Irvine Libraries. The design uses the [arXiv style](https://github.com/kourgeorge/arxiv-style) which is based on the [NeurIPS](https://nips.cc/) styling. The reference style includes [AEA](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-aea.bst) (lastname, firstname) and [Econometrica](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-econometrica.bst) (lastname, abbreviated firstname).

Based on the NIPS styling, it makes this dissertation template esthetic and convenient for reading. Instead of integrating the formatting into a single style file, this template defines the styles and format in the `main.tex` preambles and collects all the imported packages in the `package.sty` making the source more transparent and easier to customize.

Various LaTeX syntaxes are also demonstrated throughout the document such as spacing, hyperlinked footers, abbreviations, coloring, listing, table-of-contents customization, hyper-referencing, figure and table formatting with decimal alignment, mathematics symbols, and graphic elements. Users can refer to the syntax during editing.

🎉 The compiled dissertation PDF can be viewed [here](https://www.haochehsu.com/other/Dissertation_LaTeX_Template.pdf).

For **Paper LaTeX Template**, please go to this [link](https://github.com/howardhsumail/Paper-LaTeX-Template.git).

---

### 🖋 The Template
This template includes:
  - Settings: `package.sty`
  - Content: `main.tex`, `Chapter1.tex`, `Chapter2.tex`, `Chapter3.tex`, `reference.bib` (references database)
  - Style files:
    - arXiv style: `arxiv.sty`
    - Bibliography style: `aea.bst` and `ecta.bst`

### 📐 Usage

Users only need to customize the `package.sty` in the `Style` folder and edit the 5 **Content** files. The bibliography style is located in `main.tex`: 

```tex
\bibliographystyle{Style/aea} # Style/ecta
```

#### Online

For online editing, [download](https://github.com/howardhsumail/Dissertation-LaTeX-Template/archive/refs/heads/main.zip) the template, upload all the files and folders to [Overleaf](https://www.overleaf.com/) and compile the `main.tex` as demonstrated [here](https://www.overleaf.com/read/ptbfthrmnmrv).

#### Offline

For local editing, [download](https://github.com/howardhsumail/Dissertation-LaTeX-Template/archive/refs/heads/main.zip) the template and edit it with [Texmaker](https://www.xm1math.net/texmaker/) or [TeXstudio](https://www.texstudio.org/) (requires [MacTeX](https://www.tug.org/mactex/mactex-download.html) for Mac and [MiKTeX](https://miktex.org/download) for Windows) or [Texpad](https://apps.apple.com/us/app/texpad-latex-editor/id458866234?mt=12).

### ⚙️ Font Size

The font size of this template is **12pt** following the [Dissertation Formatting Manual](https://guides.lib.uci.edu/gradmanual/specifics)[^2]. The default (NIPS styling) is 10pt. To modify the font size, go to the "FONT SIZE" preamble in `main.tex` and either select `\input{size11.clo}` (11pt) or comment out `\input{size12.clo}` (12pt).

### 📒 General Notes

For help, comments, bug reporting, and change requests, please [contact](mailto:howard@hsu.xyz) the [author](https://haochehsu.com). You can use or redistribute this project, however, the author takes no responsibility for whatever template usage. Finally, you are very welcome to contribute to this template.

[^1]: The UCI dissertation template is [here](https://guides.lib.uci.edu/gradmanual/templates) with an overleaf version accessible [here](https://www.overleaf.com/latex/templates/university-of-california-irvine-thesis/bzsqmxszcpny). The compiled UCI template PDF can be viewed [here](https://www.haochehsu.com/other/uci_thesis_template.pdf). The major/degree database is [here](https://www.reg.uci.edu/mdsd/). The submission deadline is [here](https://etd.lib.uci.edu/).
[^2]: The font size must be at least 10pt. The recommended font size for Times New Roman is 12pt.
