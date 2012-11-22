evince_eclipse
==============

These two scripts allowed me setting up eclipse + TeXlipse + evince + SyncTeX
some time ago.
I'm not using eclipse for TeX development anymore, so you're basically on your
own here.

The backward search works by setting up the `evince_forward_search` script
as PDF viewer in eclipse. It will do the forward search and also
attach to Evince, read its SyncTeX events
and write them to stdout just the way eclipse expects it (via the
`eclipse_backward_search.py` module).
