# Lӧb's Theorem: A functional pearl of dependently typed quining

[The Current Draft (.pdf)](//jasongross.github.io/lob-paper/nightly/lob.pdf)

[The Current Draft (.pdf, preprint)](//jasongross.github.io/lob-paper/nightly/lob-preprint.pdf)

[The Current Draft (.html)](//jasongross.github.io/lob-paper/nightly/html/lob.html)

[The consturction of a quine (.html)](//jasongross.github.io/lob-paper/nightly/html/lob-build-quine.html)

The source code for the main paper is in [`lob.lagda`](lob.lagda),
which imports [`common.lagda`](common.lagda) (basic definitions,
included in the appendix) and
[`prisoners-dilemma-lob.lagda`](prisoners-dilemma-lob.lagda) (the
encoding used for the prisoner's dilemma section, also included in the
appendix).  The supplemental code for the section on removing the
quine constructor, which is the bulk of the code not included in the
paper itself, is in [`lob-build-quine.lagda`](lob-build-quine.lagda),
which imports [`lob.lagda`](lob.lagda).  The default Makefile target
builds all agda, html, and pdf files.
