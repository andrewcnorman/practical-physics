practical-physics
=================

This repository contains Latex files for individual practicals 
for a practical booklet written to support AQA physics A-level.
These were written by Andrew C. Norman (Teacher of Physics, 
Bishop Heber High School).

License
-------

Full details of the terms under which this work may be used and 
attributed are contained in the file LICENSE.md in this 
directory.

Compiling
---------

The files will only compile properly when the following
LaTeX packages are installed:
- siunitx
- tikz
- graphicx
- color
- exam

The document can be compiled by issuing e.g. the commands
- `pdflatex asunit1practicals.tex` - for compiling a whole booklet
- `pdflatex practicaltest.tex` - for testing individual practicals

in the base directory (containing practicaltest.tex).

The document will need to be compiled a number of times to
update all of the internal references, and to generate the
table of contents data.
