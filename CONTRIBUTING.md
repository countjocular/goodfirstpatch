[GoodFirstPatch](http://goodfirstpatch.com/)
==================================================

Welcome, so you are thinking about contributing? awesome, this is a great place to start.

Guide to Contributions
--------------------------------------

  * Commit messages should follow the following style:

```
(#99) - A brief one line description < 50 chars

Followed by further explanation if needed, this should be wrapped at
around 72 characters. Most commits should reference an existing
issue
```

Running the website
--------------------------------------

Once you checkout the code you can run a web server by:

    $ python -m SimpleHTTPServer

The website will be viewable at http://127.0.0.1:8000

Git Essentials
--------------------------------------

Workflows can vary, but here is a very simple workflow for contributing a patch:

    $ git clone git@github.com:myfork/goodfirstpatch.git
    $ git remote add goodfirstpatch https://github.com/daleharvey/goodfirstpatch.git

    $ git checkout -b 121-issue-keyword gh-pages
    # Write new stuff
    $ git add src/afile.js
    $ git commit -m "(#121) - A brief description of what I changed"
    $ git push origin 121-issue-keyword

Questions?
----------

If you have any questions, please feel free to ask on the
[issues](https://github.com/daleharvey/goodfirstpatch/issues) or in #goodfirst on irc.freenode.net.
