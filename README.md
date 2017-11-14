Bookmarklet Development Page
============================

About
-----

This project describes an approach to updating the source code of a bookmarklet
as a file changes.

Approach
--------

Run a HTTP server (e.g. `python -m SimpleHTTPServer`) for this project's root
directory and open `index.html` in a browser. Drag the link from that page to
the bookmarks bar to create the bookmarklet. Now clicking the bookmarklet while
you are on the same domain will download the latest version of `click.js` and
run it. Update `'/click.js'` in `index.html` to a full URI to allow the
bookmarklet to function on any domain.
