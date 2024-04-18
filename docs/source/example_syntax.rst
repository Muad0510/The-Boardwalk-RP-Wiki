| *emphasis*
| **strong emphasis**
| `interpreted text`
| ``inline literals``
| standalone hyperlinks (https://www.python.org)
| external hyperlinks (Python_)
| internal cross-references (example_)
| footnote references ([1]_)
| citation references ([CIT2002]_)
| substitution references (|example|)
| `inline internal targets`.

Paragraphs are separated by blank lines and are left-aligned.

- This is a bullet list.

- Bullets can be "*", "+", or "-".

1. This is an enumerated list.

2. Enumerators may be arabic numbers, letters, or roman
   numerals.

what
    Definition lists associate a term with a definition.



This is an ordinary paragraph.

>>> print 'this is a Doctest block'
this is a Doctest block

The following is a literal block::

    >>> This is not recognized as a doctest block by
    reStructuredText.  It *will* be recognized by the doctest
    module, though!

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | Cells may span columns.          |
+------------------------+------------+---------------------+
| body row 3             | Cells may  | - Table cells       |
+------------------------+ span rows. | - contain           |
| body row 4             |            | - body elements.    |
+------------------------+------------+---------------------+