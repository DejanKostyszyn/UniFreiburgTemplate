# LaTeX template for the Albert-Ludwigs-Universität Freiburg im Breisgau
A template for creating presentations with the layout of the [Albert-Ludwigs-Universität Freiburg im Breisgau](https://www.uni-freiburg.de/) in [LaTeX](https://www.latex-project.org/). The base of this template is the [beamer](https://ctan.org/pkg/beamer) class.

I created the templates, because I think that the official LaTeX Beamer Template of the Albert-Ludwigs-Universität Freiburg wastes too much space for the headline and the navigation. Therefore I present my Beamer Template 1 in file [presentation.pdf](presentation.pdf) (which is a bit more colorful) and my Beamer Template 2 in file [presentation2.pdf](presentation2.pdf) (which sticks to the traditional colors).
## Logo
I downloaded the official logo from [here](https://de.wikipedia.org/wiki/Datei:Albert-Ludwigs-Universit%C3%A4t_Freiburg_2009_logo.svg). You can also find other formats and datatypes of the logo if you follow the link.
## Requirements
Depending on your computer's operating system you must install the according distribution of [LaTeX](https://www.latex-project.org/get/). You must also have installed the following packages:
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
* [beamer-template.tex](beamer-template.tex) and [beamer-template2.tex](beamer-template2.tex) should not be touched, unless of course you know what you do. In there the templates for the presentation are defined.
* [presentation.tex](presentation.tex) is the file you can alter. In there you define the content of your presentation. If you want to use [style 1](presentation.pdf), keep line 1 uncommented and line 2 commented. If you want to use [style 2](presentation2.pdf) comment line 1 and uncomment line 2.
* [references.bib](references.bib) contains your references. There you have to add the sources you want to cite from (see [biblatex](https://ctan.org/pkg/biblatex)).
