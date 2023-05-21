# RusselResume
Personal formatting touches for the RusselResume template on overleaf. 

Add your own content in the .tex files located in cv. 

Most formatting changes such as changing vertical spacing can be made in russel.cls.

Must use lualatex engine.

If using the VS Code LaTeX Workshop extension, you may need to add this:

  "latex-workshop.latex.tools": [

    {
      "name": "latexmk",
      "command": "latexmk",
      "args": [
        "-lualatex",
        "%DOCFILE%" //Use this if the absolute path to your root tex file has any weird symbols (aka icloud drive)
      ],
      "env": {}
    },
  ]
  }
 
