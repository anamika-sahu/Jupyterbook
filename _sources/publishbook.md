## Publish the book in git

* Copy and paste your book’s _build contents into a new folder
The simplest way to host your book online is to simply copy everything that is inside _build and put it in a location where GitHub Pages knows to look.

Copy the contents of _build/html directory into docs (or your other branch).

* Push build files with ghp-import
The easiest way to use GitHub Pages with your built HTML is to use the ghp-import package. ghp-import is a lightweight Python package that makes it easy to push HTML content to a GitHub repository.

```Install ghp-import```

```pip install ghp-import```

From the master branch of your book’s root directory (which should contain the _build/html folder) call ghp-import and point it to your HTML files, like so:

```ghp-import -n -p -f _build/html```

* Go to the GitHub and changes the branch which has all the html files. In the setting there is pages option where we can see the website it has created to publish the book.