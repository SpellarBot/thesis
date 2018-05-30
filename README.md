README
================================================================================

Prerequisites:
- install [pandoc](http://pandoc.org)
- install latex with lualatex engine
- install pandoc filter:
  ~~~.bash
  pip install pandoc-fignos pandoc-tablenos
  ~~~
- download this repository and execute topdf
  ~~~.bash
  chmod +x topdf
  ./topdf
  ~~~

Citation
--------------------------------------------------------------------------------

If you want to use a different citation style, alter the `--csl` option in the
`topdf` script. You can download all different kinds of csls from
[here](https://github.com/citation-style-language/styles)
