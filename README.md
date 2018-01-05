BibLaTeX styles for Working Mathematicians
==========================================

What's This?
------------
This package provides a [BibLaTeX] (NOT BibTeX) citation styles for Mathematical articles, which looks alike [`amsrefs`](https://ctan.org/pkg/amsrefs).

It currently provides the following themes:

* `math-numeric`, which uses numbers like [1], [2], [3] ... as a reference label.
* `math-alphabetic`, which uses the part of author names such as [FMS] or [Coh].

In either case, we provide the following package options:

<dl>
<dt><code>sentencedtitle</code> (default: <code>true</code>)</dt>
<dd>
Whether to make title alphabet sentence-style or not.
If <code>true</code>, for example, <code>The Proof of Riemann Hypothesis</code> will be rendered as "The proof of riemann hypothesis". To prevent letters to be downcased, you can use braces: <code>The Proof of {Riemann} Hypothesis</code> will result in <code>The proof of Riemann hypothesis</code>.
You also have to embrace maths with <code>{</code> and <code>}</code>, as in <code>A short proof of {$1 + 1 \neq 2$}</code>, otherwise LaTeX halts with an error.
</dd>
<dt><code>dashed</code> (default: <code>true</code>)</dt>
<dd>Whether to omit the same author(s) by <code>_____</code>, as in <code>amsrefs</code>.</dd>
</dl>

Install
-------
Copy `./tex/latex/biblatex-math/*` to `$TEXMF` and run `mktexlsr`.

LICENSE
-------
LaTeX's.


[BibLaTeX]: https://ctan.org/pkg/biblatex
