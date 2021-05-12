# A Survey of Causes, Consequences, and Strategies for Addressing Flaky Tests: Bibliography

This repository contains a BibTeX file for papers related to the field of Flaky Tests. It was created by Owain Parry, Michael Hilton, Gregory M. Kapfhammer and Phil McMinn.  

You are free to use any of the entries in this file if you are interested in citing one of these research papers in your own LaTeX document.

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/flake-it/bibliography.git
```

Now, you can type `cd schemaanalyst-bibliography` and use the BibTeX file in your own LaTeX project. Alternatively, a document that cites all of the entries in this bibliography can be compiled on an Ubuntu 16.04 LTS workstation using `pdflatex` and `bibtex`; you may also compile to a PDF file using a wide variety of other tools, such as `latexmk`. You can type the following commands to create the summary document.

```shell
pdflatex bibliography.tex
bibtex bibliography.aux
pdflatex bibliography.tex
pdflatex bibliography.tex
```

Alternatively, you can use the repository as a git submodule of another repository. To do this, type the following command:

```shell
git submodule add https://github.com/flake-it/bibliography.git bibliography
```

where the final parameter ("bibtex") is the name of the directory that you wish to install the repository. Following this, you will need to invoke the following commands:

```shell
git submodule init
git submodule update
```

Of course, the submodule will need to be pulled periodically to receive any changes. This can be done by changing directory to the submodule and issue the usual ``git pull``. (If Git has detached the submodule from its HEAD, it may be reattached by issuing the command ``git checkout master`` from the submodule's directory.

Another means of ensuring the submodule is updated when pulling from the main repository is to issue the following command, which will also update all submodules:

```shell
git pull --recurse-submodules
```

## Problems?
If you find that some of the entries are incorrectly formatted and thus your LaTeX and BibTeX tools are not processing them correctly, then please open a new issue and one of us will attempt to resolve your concerns. 
