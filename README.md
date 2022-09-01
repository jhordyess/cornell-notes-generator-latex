# Cornell notes generator with LaTeX

A simple Cornell notes generator with LaTeX.

After learning how to take the best notes, I create this.

## Info

The main document `.tex` file is `index.tex`.

Properties: letter paper, double-sided, 1cm of margin, portrait letter, and some predefined values.

## Online compilation

Tested with [Overleaf](https://www.overleaf.com/) with Tex Live 2022. (The reason was: [Choosing a LaTeX Compiler](https://www.overleaf.com/learn/latex/Choosing_a_LaTeX_Compiler)).

## Local compilation

Tested with a remote container in [Visual Studio Code](https://code.visualstudio.com/) and the extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop); using the Docker image [jhordyess/texlive](https://hub.docker.com/r/jhordyess/texlive).

My `.devcontainer/devcontainer.json` configuration file was: <https://gist.github.com/jhordyess/f5799c39a50f909290a2b41883356f67>

## TODO

To have more control for lengths, rows, columns, use portrait or landscape, view in letter or A4 size, single sided or double sided, and so on; I'll create a web project with [React](https://reactjs.org/) and [React-pdf](https://react-pdf.org/), to configurte the creation PDF file 😶.

## Update 2022

Here is the project developed with React: [https://github.com/jhordyess/cornell-notes-generator](https://github.com/jhordyess/cornell-notes-generator) 🤓, and online: [https://jhordyess.github.io/cornell-notes-generator/](https://jhordyess.github.io/cornell-notes-generator/) 🌐.

---

@2022 Jhordyess
