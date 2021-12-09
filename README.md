# cornell-notes-generator

A simple Cornell notes generator with LaTeX.

After learning how to take the best notes, I create this.

## Info

The main document `.tex` file is `index.tex`.

Properties: letter paper, double-sided, 1cm of margin, portrait letter, and some predefined values.

## Online compilation

Tested with [Overleaf](https://www.overleaf.com/) with Tex Live 2021. (The reason was: [Choosing a LaTeX Compiler](https://www.overleaf.com/learn/latex/Choosing_a_LaTeX_Compiler)).

## Local compilation

Tested with the Docker image [texlive](https://hub.docker.com/r/texlive/texlive) 💪 (DIGEST: c0654781cdcd) available in [DockerHub](https://hub.docker.com/), [Visual Studio Code](https://code.visualstudio.com/) and the extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).

My `settings.json` configuration file was:

```JSON
{
  "editor.formatOnSave": true,
  "latex-workshop.docker.enabled": true,
  "latex-workshop.docker.image.latex": "texlive/texlive",
  "latex-workshop.latex.autoClean.run": "onBuilt",
  "latex-workshop.latex.autoBuild.run": "onSave",
  "latex-workshop.latex.clean.fileTypes": [
    "*.aux",
    "*.bbl",
    "*.blg",
    "*.idx",
    "*.ind",
    "*.lof",
    "*.lot",
    "*.out",
    "*.toc",
    "*.acn",
    "*.acr",
    "*.alg",
    "*.glg",
    "*.glo",
    "*.gls",
    "*.fls",
    "*.log",
    "*.fdb_latexmk",
    "*.snm",
    "*.synctex(busy)",
    "*.synctex.gz(busy)",
    "*.nav",
    "*.vrb",
    "*.synctex.gz"
  ]
}
```

## To do's

To have more control for lengths, rows, columns, use portrait or landscape, view in letter or A4 size, single sided or double sided, and so on; I'll create a web project with [React](https://reactjs.org/) and [React-pdf](https://react-pdf.org/), to configurte the creation PDF file 😶.

---

@2021 Jhordyess
