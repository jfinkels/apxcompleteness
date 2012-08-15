Revisiting the hardness of approximation of Maximum 3-Satisfiability
====================================================================

This work contains a proof that Maximum 3-Satisfiability is complete for the
class APX under AP reductions, as well as a proof that it is hard to
approximate.

Copyright 2012 Jeffrey Finkelstein.

Both the LaTeX markup and the compiled document itself are licensed under the
Creative Commons Attribution-ShareAlike License 3.0. Visit
[https://creativecommons.org/licenses/by-sa/3.0/][1] to view a copy of this
license.

The author can be contacted via email at <jeffreyf@bu.edu>.

[1]: https://creativecommons.org/licenses/by-sa/3.0/

## Requirements ##

Compiling this work requires the following LaTeX packages:

* algorithm
* algpseudocode
* amsmath
* amssymb
* amsthm
* complexity
* hyperref

The following command will install the necessary system packages on Ubuntu
12.04:

    sudo apt-get install texlive-latex-base texlive-science texlive-base

## Getting and compiling this work ##

To get a copy of the most recent version of this work:

    git clone git@github.com:jfinkels/apxcompleteness.git

To compile this work:

    cd apxcompleteness
    pdflatex apxcompleteness
    bibtex apxcompleteness
    pdflatex apxcompleteness
    pdflatex apxcompleteness
