## Install Overview 
This is a short overview of the major components and steps in building a Jupyter Book.

# Install Jupyter Book
You can install Jupyter Book via pip:
``` pip install -U jupyter-book ```

or via conda-forge:
``` conda install -c conda-forge jupyter-book ```


## The Jupyter Book command-line interface
Jupyter Book uses a command-line interface to perform a variety of actions. For example, building and cleaning books. You can run the following command to see what options are at your control:


```jupyter-book --help
Usage: jupyter-book [OPTIONS] COMMAND [ARGS]...
```

``` Options:
  --version   Show the version and exit.
  -h, --help  Show this message and exit.

Commands:
  build   Convert your book's or page's content to HTML or a PDF.
  clean   Empty the _build directory except jupyter_cache.
  config  Inspect your _config.yml file.
  create  Create a Jupyter Book template that you can customize.
  myst    Manipulate MyST markdown files.
  toc     Command-line for sphinx-external-toc.
  ```
