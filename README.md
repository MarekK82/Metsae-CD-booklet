Metsä CD booklet
================

Creation of a custom CD booklet for the demo album *Metsä* by heavy metal band
[Moonsorrow][1].


About
-----

[Metsä][2] is a demo album shared by *Moonsorrow* across the fan community. If
you are a huge fan like me you will find it nice to have this demo as CD among
other albums in your shelf. That is what this project is about: Creation of a
booklet and inlay to put them in a CD case. The used contents are provided by
the [Unofficial Moonsorrow Biography][3].


Prerequisites
-------------

For this project to realize I got inspired by *Christoph Jüngling*'s
[blog post][4] about printing CD booklets with LaTeX. So you will need to have a
*LaTeX* environment set up such as [TeX Live][5]. Of course you need to have a
printer and scissors for cutting out the prints afterwards :-)


Compile
-------

One can compile both the **booklet** and the **inlay** separately.

```
# Compiling in a Linux shell using TeX Live.
pdflatex booklet.tex  # Resulting in `booklet.pdf'.
pdflatex inlay.tex    # Resulting in `inlay.pdf'.
```


Print
-----

Use **A4** paper for both documents. For best printing results perform a
centered duplex print job for the booklet at its long edge. And while setting up
a print job, keep in mind to turn off automatic resizing of the documents:
Always print with 100% scaling!


[1]: http://moonsorrow.com/
[2]: https://en.wikipedia.org/wiki/Metsä
[3]: http://moonsorrowbio-en.blogspot.com/2013/09/bootleg-demo-compilation.html
[4]: http://www.juengling-edv.de/cd-booklet-erzeugen/
[5]: http://www.tug.org/texlive/
