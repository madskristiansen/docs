# Marina docs

Written in [reStructuredText](http://sphinx-doc.org/rest.html) and Markdown,
built using [Sphinx](http://sphinx-doc.org) and hosted on
[Read The Docs](http://docs.readthedocs.org/en/latest/getting_started.html).

Setup

    pip install -r requirements.txt

Build locally

    make html
    open _build/html/index.html

Test that links work before deploying

    make linkcheck

To deploy, just commit your change (or send a pull request) and, once pushed to
master, it will be deployed automatically
to our [Documentation page](http://marina.readthedocs.org/en/latest/)
