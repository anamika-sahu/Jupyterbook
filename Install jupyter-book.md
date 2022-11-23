Overview
This is a short overview of the major components and steps in building a Jupyter Book. See the other pages in this guide for more in-depth information.

Install Jupyter Book
You can install Jupyter Book via pip:

pip install -U jupyter-book
or via conda-forge:

conda install -c conda-forge jupyter-book
This will install everything you need to build a Jupyter Book locally.

Note that if you need to execute code when building your book, you’ll need to install these dependencies as well.

The Jupyter Book command-line interface
Jupyter Book uses a command-line interface to perform a variety of actions. For example, building and cleaning books. You can run the following command to see what options are at your control:

You can also use the short-hand jb for jupyter-book. E.g.,: jb create mybookname. We’ll use jupyter-book for the rest of this guide.

jupyter-book --help
Usage: jupyter-book [OPTIONS] COMMAND [ARGS]...

  Build and manage books with Jupyter.

Options:
  --version   Show the version and exit.
  -h, --help  Show this message and exit.

Commands:
  build   Convert your book's or page's content to HTML or a PDF.
  clean   Empty the _build directory except jupyter_cache.
  config  Inspect your _config.yml file.
  create  Create a Jupyter Book template that you can customize.
  myst    Manipulate MyST markdown files.
  toc     Command-line for sphinx-external-toc.
For more complete information about the CLI, see Command-line interface reference.
