# clidoc(1) -- generates man pages and help text from Markdown-formatted docs

## SYNOPSIS
`clidoc` _file_...<br>
`clidoc` `-h`|`--help`<br>

## DESCRIPTION
`clidoc` generates man pages and help text from Markdown-formatted files. It
uses [`ronn`](https://github.com/rtomayko/ronn) to convert Markdown-formatted
files to Groff (man pages) and HTML. It then parses the HTML into help text
using [`xidel`](http://videlibri.sourceforge.net/xidel.html).

For each Markdown file given, `clidoc` will write a man page to `./man/` and a
help text file to `./help/`.

## OPTIONS
* -h, --help:
  Show help text and exit.

## COPYRIGHT
`clidoc` is Copyright (c) 2016 Vinson Chuong under The MIT License.
