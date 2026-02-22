# code2color

code2color is a perlscript which converts a program source code to syntax
highlighted output in a terminal.

It is a converted and simplified version of Code2HTML by Peter Palfrader

This script was part of the lesspipe.sh repository to provide at least a
simple colorizer. Meanwhile better colorizers are available.

Therefore the code2color script has been removed from the lesspipe.sh repository
and this one serves as its new storage location.

There are no plans to further enhance or improve the functionality of the script.

The documentation in code2color is here repeated below:

## code2color

 Convert source code (c,java,perl,html,...) into color-coded ASCII text.

## SYNOPSIS

 `code2color [-l LANG] [input_file]`

## DESCRIPTION

This script is an adaptation of Peter Palfrader's code2html perl package.
It accepts input from STDIN or from an input file. The language mode is
guessed from the input and the file name. If this is not correct, it can
be changed using the -l option. Language modes provided are

    ada, ada95, awk, c, c++, cc, cxx, groff, html,
    java, javascript, js, m4, make, makefile, pas,
    pas, pascal, perl, plain, pov, povray, ruby, sql.

## ORIGINAL AUTHORS

Jim Mahoney (mahoney AT marlboro.edu), Peter Palfrader, and others.

## COPYRIGHT and LICENSE

 Copyright (c) 1999, 2000 by Peter Palfrader and others.

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
``Software''), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ``AS IS'', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## SEE ALSO

 Peter Palfrader's Code2HTML page at http://www.palfrader.org/code2html/

