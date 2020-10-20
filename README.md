# forall x: Dortmund

## Description

_forall x: Dortmund_ is an in-progress German translation of _forall x: Calgary_. 
As such, it is a full-featured textbook on formal logic. It covers key
notions of logic such as consequence and validity of arguments, the
syntax of truth-functional propositional logic TFL and truth-table
semantics, the syntax of first-order (predicate) logic FOL with
identity (first-order interpretations), translating (formalizing)
English in TFL and FOL, and Fitch-style natural deduction proof
systems for both TFL and FOL. It also deals with some advanced topics
such as modal logic, soundness, and functional completeness. Exercises with solutions are
available. It is provided in PDF and in LaTeX source code. 

[Download](#download) links below.

## Credits and License

_forall x: Dortmund_ is an adaptation and German translation of
_forall x: Calgary_ used under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 
license, compiled by [Simon Wimmer](https://simonwimmer.weebly.com/) (with corrections by Daniel Foelsch). 
[_forall x: Calgary_](https://forallx.openlogicproject.org/) is based on 
[_forall x: Cambridge_](http://people.ds.cam.ac.uk/tecb2/forallx.shtml), 
by [Tim Button](http://nottub.com/) used under a [CC
BY 4.0](https://creativecommons.org/licenses/by/4.0/) license, which
is based in turn on [_forall x_](https://www.fecundity.com/logic/), by
[P.D. Magnus](https://www.fecundity.com/job/) used under a [CC BY
4.0](https://creativecommons.org/licenses/by/4.0/) license, and was
remixed, revised, & expanded by [Aaron
Thomas-Bolduc](https://phil.ucalgary.ca/profiles/aaron-thomas-bolduc)
& [Richard Zach](http://richardzach.org/).  It includes additional
material from _forall x_ by P.D. Magnus and
[_Metatheory_](http://people.ds.cam.ac.uk/tecb2/metatheory.shtml) by
Tim Button, both used under a [CC BY
4.0](https://creativecommons.org/licenses/by/4.0/) license, from
[_forall x: Lorain County
Remix_](https://github.com/rob-helpy-chalk/openintroduction), by
[Cathal Woods](https://sites.google.com/site/cathalwoods/) and
J. Robert Loftis, used with permission, and [_A Modal Logic
Primer_](http://www.rtrueman.com/uploads/7/0/3/2/70324387/modal_logic_primer.pdf)
by [Robert Trueman](http://www.rtrueman.com/), used with permission. 
_forall x: Dortmund_ omits the material on Metatheory.

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

The LaTeX source code for this work is available on GitHub at [https://github.com/sbwimmer/forallx-do](https://github.com/sbwimmer/forallx-do).

## Download

You can download a PDF of the book here (link not yet live):

  - [`forallxdo.pdf`]() (in color, for screen reading)
  - [`forallxdosol.pdf`]() (solutions booklet)

Note that these files change whenevery the source files are changed.
So if you use the text in a course, better to download the
PDFs and make them available to students directly, than to link here.

## Make PDFs Yourself

Clone the [GitHub repository](https://github.com/sbwimmer/forallx-do) locally or download the ZIP file and run [LaTeX](http://www.latex-project.org/) on

  - `forallxdo.tex` (in color, for screen reading)

You'll have to run `makeglossaries` to produce the glossary as well.

To make changes to the definitions in the preamble and `foralldo.sty`
file, put them in a file named `forallxdo-local.sty`. For instance,
to get the connectives to be ∼, &, ⊃, ≡ instead of ¬, ∧, →, ↔, and 
atomic formulas _Lab_ instead of _L(a,b)_, copy 
`forallxdo-local-sample.sty` to that file.
