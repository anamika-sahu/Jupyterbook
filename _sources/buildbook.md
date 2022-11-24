## Build your book
Once you’ve added content and configured your book, it’s time to build outputs for your book. We’ll use the jupyter-book build command line tool for this.

Currently, there are two kinds of supported outputs: an HTML website for your book, and a PDF that contains all of the pages of your book that is built from the book HTML. In this tutorial, we’ll focus on building HTML outputs.


```jupyter-book build --all mybookname/```

#Preview your built HTML
To preview your book, you can open the generated HTML files in your browser. Either double-click the html file in your local folder, or enter the absolute path to the file in your browser navigation bar adding file:// at the beginning (e.g. ```file://Users/my_path_to_book/_build/index.html```).