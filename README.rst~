grammar-check
==============

Python wrapper for LanguageTool.


This is a fork of https://github.com/myint/language-check

Example usage
-------------

From the interpreter:

>>> import grammar_check
>>> tool = grammar_check.LanguageTool('en-GB')
>>> text = 'This are bad.'
>>> matches = tool.check(text)
>>> len(matches)
1



Automatically apply suggestions to the text:

>>> grammar_check.correct(text, matches)
'These are bad'

From the command line::

    $ echo 'This are bad.' > example.txt

    $ grammar-check example.txt
    example.txt:1:1: THIS_NNS[3]: Did you mean 'these'?


Installation
------------

To install via pip::

    $ pip install --user --upgrade grammar-check


Prerequisites
-------------

- `Python 3.2+ <https://www.python.org>`_ (or 2.7)
- `lib3to2 <https://bitbucket.org/amentajo/lib3to2>`_
  (if installing for Python 2)
- `LanguageTool <https://www.languagetool.org>`_ (Java 6.0+)





