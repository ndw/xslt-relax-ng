This project provides RELAX NG grammars for XSLT stylesheets. Because
stylesheets must have a version number, it's straightforward for a
RELAX NG validator to choose between the `xslt10.rnc`, `xslt20.rnc`,
and `xslt30.rnc` grammars.

Support for XSLT 3.0 is now provided via a git subtree merge with
https://github.com/innovimax/xslt30.git

Having a RELAX NG grammar makes syntax directed editing of XSLT stylesheets
much easier in tools like [Emacs](http://www.emacswiki.org/emacs/NxmlMode)
and [oXygen](http://www.oxygenxml.com/)
that support RELAX NG.
