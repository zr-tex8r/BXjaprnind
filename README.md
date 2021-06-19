BXjaprnind Package
==================

LaTeX: To adjust the position of parentheses at paragraph head

In Japanese typesetting, opening parentheses placed at the beginning
of paragraphs or lines are treated specially; for example, while the
paragraph indent before normal kanji characters is 1em, the indent
before parentheses can be 0.5em, 1em or 1.5em deoending on the local
rule in effect.

This package allows users to specify the amount of indent just before
Japanese parentheses placed at paragraph/line head.

### System requirement

  * TeX format: LaTeX.
  * TeX engine: pTeX / upTeX / LuaTeX (+ LuaTeX-ja).  
    (The support for XeTeX is currently broken.)
  * Dependent packages:
      - bxtoolbox (from [BXbase] bundle)

[BXbase]: https://www.ctan.org/pkg/bxbase

### Package content

  * `bxjaprnind.sty`: the package
  * `bxjaprnind.pdf`: the user manual (in Japanese)
  * `bxjaprnind.tex`: the source file of `bxjaprnind.pdf`
  * `sample-bxjaprnind.pdf`: a sample document (in Japanese)
  * `sample-bxjaprnind.tex`: the source file of `sample-bxjaprnind.pdf`

### Installation

In a system compliant to TDS 1.1, move the files as follows:

  - `*.sty` → $TEXMF/tex/latex/BXjaprnind

And rehash your TEXMF trees if necessary.

### License

This package is distributed under the MIT License.


bxjaprnind package ― main
--------------------------

See the manual bxjaprnind.pdf (in Japanese) for detail.


Revision History
----------------

  * Version 0.4a 〈2021/06/18〉
  * Version 0.4  〈2021/06/06〉
  * Version 0.3b 〈2017/09/12〉
  * Version 0.3a 〈2013/05/05〉
  * Version 0.3  〈2013/04/29〉
  * Version 0.2  〈2012/05/14〉

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
