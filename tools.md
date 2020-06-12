---
layout: default
---

---

# Recommended Tools

---

This page is intended as a short introduction to some tools I use regularly, so you might like them too! In general, they are all free and open source, though there may be paid options for access to more features. They are all very popular and well-supported.

<!-- Contents:
- [General productivity tools](#general-productivity-tools)
  - [Mendeley: reference manager](#mendeley-reference-manager)
  - [Overleaf: web-based LaTeX editor](#overleaf-web-based-latex-editor)
  - [Miscellaneous](#miscellaneous)
- [Programming-focussed tools](#programming-focussed-tools)
  - [Atom: text/code editor / IDE](#atom-text/code-editor-/-ide) -->

  Contents:
  - [General productivity tools](#general-productivity-tools)
    - Mendeley: reference manager
    - Overleaf: web-based LaTeX editor
    - Miscellaneous: draw.io, Inkscape
  - [Programming-focussed tools](#programming-focussed-tools)
    - Atom: text/code editor / IDE
    - Conda
    - Jupyter
    - GitHub
  - [Python packages](#python-packages)

---

## General productivity tools

### [**Mendeley**](https://mendeley.com): reference manager

Mendeley is a software you can install and run on your computer and helps you manage your "library" of references (articles, websites etc.). To add entries to your library:

- add a PDF - it will automatically be scanned to build the metadata (author, title, journal etc.)
- use the web browser plugin to automatically add a reference and the PDF with one click
- add an entry manually

These are synchronised to your Mendeley cloud account so you can easily access the library from any computer. References can be organised into folders; files can be annotated; and more. Mendeley can automatically generate a bibtex file to use in a LaTeX document, and can connect with other services (e.g. Overleaf).

### [**Overleaf**](https://overleaf.com): web-based LaTeX editor

Overleaf is the easiest way to start using LaTeX, and is also powerful for experienced users. Login and create LaTeX projects directly in the browser, collaborate on a document with others in real time, (and even submit articles directly to some journals). Files are stored in your Overleaf cloud account and it connects to other services:
- Link to your Mendeley account to automatically create your bibliography.
- Link to Dropbox to maintain both cloud and local copies (e.g. drag and drop graphics files to add them) - this is an automatic two-way sync
- Link to GitHub to also work on it using git commits & pull requests - this requires a manual button-clicking in Overleaf to push/pull changes so you might need to know how to resolve merge conflicts

### Miscellaneous

 - [**draw.io**](https://draw.io) for simple diagrams (e.g. flowchart) - cloud based and can integrate with other services; also available as a Jupyter extension
 - [**Inkscape**](https://inkscape.org) for more complex graphics

---

## Programming-focussed tools

These tools are very useful for coding projects, but the combination of Atom and GitHub can be great for other purposes (e.g. keeping notes, building textbooks, particularly in collaborative projects) although at least some understanding of programming may be necessary.

### [**Atom**](https://atom.io): text/code editor / IDE

Atom is a text editor which is very customisable and extensible. Syntax highlighting and linting for whatever programming language you use, and a wide array of community-built packages to make it do more. It is built by the GitHub people so naturally it integrates well with git & GitHub. Use cases:
 - working on programming scripts (e.g. .py files) / libraries
 - using a graphical interface to git to make commits (& view diffs) to a project and push/pull them to the remote repository on GitHub
 - working on [Markdown (.md)](https://markdownguide.org), [reStructuredText (.rst)](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html), HTML files, etc., for taking notes, and building websites or documentation - for example [see the .md file](https://github.com/smithara/smithara.github.io/blob/master/tools.md) from which this page is generated

I am now looking into using [VS Code](https://code.visualstudio.com/) instead - mainly because of Atom being slow.

### [**Conda**](https://conda.io): programming environment manager

### [**Jupyter**](https://jupyter.org): programming ecosystem (notebooks + more)

### [**GitHub**](https://github.com): platform for hosting and sharing git repositories



---

## Python packages

...
