# LaTeX template for the Albert-Ludwigs-Universität Freiburg im Breisgau
A template for creating presentations with the layout of the [Albert-Ludwigs-Universität Freiburg im Breisgau](https://www.uni-freiburg.de/) in [LaTeX](https://www.latex-project.org/). The base of this template is the [beamer](https://ctan.org/pkg/beamer) class.
## Logo
I downloaded the official logo from [here](https://de.wikipedia.org/wiki/Datei:Albert-Ludwigs-Universit%C3%A4t_Freiburg_2009_logo.svg). You can also find other formats and datatypes of the logo if you follow the link.
## Requirements
Depending on your computer's operating system you must install the according distribution of [LaTeX](https://www.latex-project.org/get/). You also must have installes the following packages:
* [inputenc](https://ctan.org/pkg/inputenc)
* [amsmath](https://ctan.org/pkg/amsmath)
* [amssymb](https://ctan.org/pkg/amsfonts)
* [amsthm](https://ctan.org/pkg/amsthm)
* [hyperref](https://ctan.org/pkg/hyperref)
* [graphicx](https://ctan.org/pkg/graphicx)
* [biblatex](https://ctan.org/pkg/biblatex)
* [babel](https://www.ctan.org/pkg/babel)

Some of them may already be included in the distributions.
## Structure & How to use
* [beamer-template.tex](beamer-template.tex) should not be touched, unless of course you know what you do. In there the template for the presentation is defined.
* [presentation.tex](presentation.tex) is the file you can alter. In there you define the content of your presentation.
* [references.bib](references.bib) contains your references. There you have to add the sources you want to cite from (see [biblatex](https://ctan.org/pkg/biblatex)).
