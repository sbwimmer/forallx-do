# forallx-yyc

![Book Cover](http://forallx.openlogicproject.org/forallxyyc.png)

This is the formal logic textbook, _forall x: Calgary Remix_. It is
based on [_forall x:
Cambridge_](http://people.ds.cam.ac.uk/tecb2/forallx.shtml), by [Tim
Button](http://people.ds.cam.ac.uk/tecb2/index.shtml) used under a [CC
BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) license,
which is based in turn on [_forall
x_](https://www.fecundity.com/logic/), by
[P.D. Magnus](https://www.fecundity.com/job/) used under a [CC BY-SA
3.0](https://creativecommons.org/licenses/by-sa/3.0/) license, and was
remixed, revised, & expanded by [Aaron Thomas-Bolduc](https://phil.ucalgary.ca/profiles/aaron-thomas-bolduc) & [Richard Zach](http://richardzach.org/).
It includes additional material from _forall x_ by P.D. Magnus and
[_Metatheory_](http://people.ds.cam.ac.uk/tecb2/metatheory.shtml) by
Tim Button, both used under a [CC BY-SA
3.0](https://creativecommons.org/licenses/by-sa/3.0/) license, and
from [_forall x: Lorain County
Remix_](https://github.com/rob-helpy-chalk/openintroduction), by
[Cathal Woods](https://sites.google.com/site/cathalwoods/) and
J. Robert Loftis, used under a [CC BY-SA
4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

The LaTeX source code for this work is available on GitHub at [github.com/rzach/forallx-yyc](https://github.com/rzach/forallx-yyc).

## Download PDFs

You can download PDFs of the files here:

  - [`forallxyyc.pdf`](http://forallx.openlogicproject.org/forallxyyc.pdf) (in color, for screen reading)
  - [`forallxyyc-print.pdf`](http://forallx.openlogicproject.org/forallxyyc-print.pdf) (b/w, for printing on Quarto stock)
  - [`forallxyyc-letter.pdf`](http://forallx.openlogicproject.org/forallxyyc-letter.pdf) (b/w, for printing on regular letter-size paper)
  - [`forallxyyc-accessible.pdf`](http://forallx.openlogicproject.org/forallxyyc-accessible.pdf) (an accessible version for dyslexics)
  - [`forallxsol.pdf`](http://forallx.openlogicproject.org/solutions/forallxsol.pdf) (solutions booklet)

Note that these files change whenevery the source files are
changed. So if you use the text in a course, better to download the
PDFs and make them available to students directly, than to link here.

## Buy a Printed Copy

If you'd like to purchase a nice paperback copy, you can do so on
[Lulu.com](http://www.lulu.com/shop/richard-zach/forall-x-calgary-remix-spring-2017/paperback/product-23165559.html)
or
[Amazon](https://www.amazon.com/dp/1546435115/ref=cm_sw_r_cp_ep_dp_uLLhzbVJGFRNZ)
([Canada](https://www.amazon.ca/dp/1546435115/ref=cm_sw_r_cp_ep_dp_uLLhzbVJGFRNZ),
[UK](https://www.amazon.co.uk/dp/1546435115/ref=cm_sw_r_cp_ep_dp_uLLhzbVJGFRNZ))

(The process for getting the book printed is described [here](http://openlogicproject.org/2015/11/22/getting-your-book-to-print/) and [here](http://openlogicproject.org/2017/05/19/forall-x-yyc-is-now-on-amazon-and-how-it-got-there/).)

## Make PDFs Yourself

Clone the [GitHub repository](https://github.com/rzach/forallx-yyc) locally or download the ZIP file and run [LaTeX](http://www.latex-project.org/) on one of

  - `forallxyyc.tex` (in color, for screen reading)
  - `forallxyyc-print.tex` (b/w, for printing on Quarto stock)
  - `forallxyyc-letter.tex` (b/w, for printing on regular letter-size paper)

You'll have to run `makeglossaries` to produce the glossary as well.

To make changes to the definitions in the preamble and `forallyyc.sty`
file, put them in a file named `forallxyyc-local.sty`. For instance,
to get the connectives to be & for and and horseshoe for the
conditional, copy `forallxyyc-local-sample.sty` to that file.
