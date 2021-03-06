Contributing
############

Thank you for considering to contribute to *Reading List*!

:note:

    No contribution is too small; please submit as many fixes for typos and
    grammar bloopers as you can!

:note:

    Open a pull-request even if your contribution is not ready yet! It can
    be discussed and improved collaboratively!


Run tests
=========

::

    make tests


Run load tests
==============

From the :file:`loadtests` folder:

::

    make test SERVER_URL=http://localhost:8000


Run a particular type of action instead of random:

::

    LOAD_ACTION=batch_create make test SERVER_URL=http://localhost:8000

(*See loadtests source code for an exhaustive list of available actions and
their respective randomness.*)


IRC channel
===========

Join ``#storage`` on ``irc.mozilla.org``!
