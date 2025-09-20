<!-- Begin README -->

<div align="center">
    <a href="https://github.com/scottgriv/latex-demo" target="_blank">
        <img src="./docs/images/icon.png" width="200" height="200"/>
    </a>
</div>
<p align="center">
    <a href="https://www.latex-project.org/"><img src="https://img.shields.io/badge/LaTeX-3.14-008080?style=for-the-badge&logo=latex" alt="LaTeX Badge" /></a>
    <br>
    <a href="https://github.com/scottgriv"><img src="https://img.shields.io/badge/github-follow_me-181717?style=for-the-badge&logo=github&color=181717" alt="GitHub Badge" /></a>
    <a href="mailto:scott.grivner@gmail.com"><img src="https://img.shields.io/badge/gmail-contact_me-EA4335?style=for-the-badge&logo=gmail" alt="Email Badge" /></a>
    <a href="https://www.buymeacoffee.com/scottgriv"><img src="https://img.shields.io/badge/buy_me_a_coffee-support_me-FFDD00?style=for-the-badge&logo=buymeacoffee&color=FFDD00" alt="BuyMeACoffee Badge" /></a>
    <br>
    <a href="https://prgportfolio.com" target="_blank"><img src="https://img.shields.io/badge/PRG-Bronze Project-CD7F32?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNDRDdGMzIiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="Bronze" /></a>
</p>

---------------

<h1 align="center">LaTeX Demo: Professional Document Formatting</h1>

This repository contains an example `LaTeX` document that demonstrates the capabilities of `LaTeX` for creating professional-quality documents with mathematical and scientific content.

---------------

## Table of Contents

- [About LaTeX](#about-latex)
- [Getting Started](#getting-started)
    - [Example Contents](#example-contents)
    - [Compiling the Document](#compiling-the-document)
    - [Usage](#usage)
- [Resources](#resources)
- [License](#license)
- [Credits](#credits)

## About LaTeX

`LaTeX` is a typesetting system built on top of the `TeX` typesetting system. It is widely used for producing documents with consistent and high-quality formatting, particularly in academic, research, and technical contexts. `LaTeX` excels at typesetting complex mathematical equations, scientific symbols, and structured documents.

## Getting Started

### Example Contents

The `LaTeX` document (`demo.tex`) in this repository showcases various features of `LaTeX`:

- Structured sections and headings
- Mathematical equations using the amsmath package
- Inclusion of figures using the graphicx package
- Lists and itemization
- Cross-referencing sections, figures, and equations
- Proper citation management using BibTeX

### Compiling the Document

- To compile the `LaTeX` document into a `PDF`, you'll need a `LaTeX` distribution installed on your system (such as `TeX Live` or `MiKTeX`). Use a `LaTeX` compiler, such as `pdflatex`, `xelatex`, or `lualatex`, to compile the document:

```sh
pdflatex demo.tex
```

The compilation process may require running the compiler multiple times to resolve cross-references and citations.
Another option is to use the `latexmk` tool, which will automatically run the appropriate commands to compile the document:

```sh
latexmk demo.tex
```

You can also use an online `LaTeX` editor, such as [Overleaf](https://www.overleaf.com/), to compile the document.

### Usage

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the repository folder.
3. Compile the `LaTeX` document using the appropriate compiler command.
4. The compiled PDF output (`demo.pdf`) will be generated.

## Resources

For more information and tutorials on `LaTeX`, you can refer to the following resources:

- [LaTeX Project Website](https://www.latex-project.org/)
- [Overleaf: Online LaTeX Editor](https://www.overleaf.com/learn)
- [Simple Online TeX Viewer/Editor](https://texviewer.herokuapp.com)

## License

This project is released under the terms of **The Unlicense**, which allows you to use, modify, and distribute the code as you see fit. 
- [The Unlicense](https://choosealicense.com/licenses/unlicense/) removes traditional copyright restrictions, giving you the freedom to use the code in any way you choose.
- For more details, see the [LICENSE](LICENSE) file in this repository.

## Credits

**Author:** [Scott Grivner](https://github.com/scottgriv) <br>
**Email:** [scott.grivner@gmail.com](mailto:scott.grivner@gmail.com) <br>
**Website:** [linktr.ee/scottgriv](https://www.linktr.ee/scottgriv) <br>
**Reference:** [Main Branch](https://github.com/scottgriv/latex-demo) <br>

---------------

<div align="center">
    <a href="https://linktr.ee/scottgriv" target="_blank">
        <img src="./docs/images/footer.png" width="100" height="100"/>
    </a>
</div>

<!-- End README -->
