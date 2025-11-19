---
title: Baseprinting Example
abstract: |
    This example demonstrates source files that are used to generate a baseprint from which
    web pages and PDF files can be rendered.
---

Introduction {#intro}
---------------------

This automated genration of a web page for a document is
inspired by manubot [@himmelstein_open_2019].

Some main document text.

### A subheading

See [Pandoc documentation](https://pandoc.org/MANUAL.html) for the many heading syntax options.

CommonMark formatting
---------------------

CommonMark formatting like *italic*, **bold**, and `inline_code` are supported.

Lists too:

* Red
* Green
* Blue

or numbered:

1. One
2. Two
3. Three


> Blockquotes like this are supported.


And preformatted code blocks using three backticks:
```
print("Hello World")
```

More Pandoc markdown features
-----------------------------

Most of the features of Pandoc markdown are supported.


### Definitions lists

Coffee
:   the person upon whom one coughs

Syntax
:   tariff on immorality

Program
:   in favor of the metric system


Within document references
--------------------------

A reference to the introduction [intro](#intro).


Not yet supported feaures
-------------------------

Images not supported yet and just result in: ![image](foo.gif)

Math is not yet support and just resutls in:
$$
\pi \not= 3
$$
