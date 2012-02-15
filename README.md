This project provides RELAX NG grammars for XSLT stylesheets. Because stylesheets
are required to have a version number, it's straightforward for a RELAX NG
validator to choose between the `xslt10.rnc` and `xslt20.rnc` grammars.

As work on XSLT 3.0 stabilizes, I plan to include support for that as well.

Having a RELAX NG grammar makes syntax directed editing of XSLT stylesheets
much easier in tools like [Emacs](http://www.emacswiki.org/emacs/NxmlMode)
and [oXygen](http://www.oxygenxml.com/)
that support RELAX NG.
