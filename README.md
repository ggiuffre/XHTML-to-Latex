# XHTML-to-Latex
## an XSLT template for turning an XHTML page into a Latex document
Everyone can contribute to this repository: feel free to add new features to the template and/or correcting mistakes.

### usage
to convert your HTML page `mypage.html` into a Latex document, download the file `html_tex.xml` from  this repository and put it in the same folder of `mypage.html`. Then open a Linux-like command prompt and type `xsltproc --html html_tex.xml mypage.html > mydocument.tex`, where `mydocument.tex` is the name of your new Latex file.

Now you can `\input{mydocument.tex}` or `\include{mydocument.tex}` in a Latex document.

To do:
* generate the whole Latex document, not just a single file;
* convert every HTML entity into its corresponding Latex symbol;
* handle HTML tables.
