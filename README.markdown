# ScotLUG - The Scottish Linux User Group

**Welcome!**  This is the source code for [our website](http://www.scotlug.org.uk).  Each page on the site links back to its corresponding [Markdown](https://help.github.com/articles/writing-on-github/) file here.  The site is made with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub pages](https://pages.github.com/).

## Making a change

**Want to see something on the website?**  Edit a page and [make a pull request](https://github.com/ScotLUG/scotlug.github.io/pulls), or [raise a new issue](https://github.com/ScotLUG/scotlug.github.io/issues/new) to request a change.

## Serving the project locally

Make sure that you have [Ruby](https://www.ruby-lang.org/en/) installed, then run the following command:

```sh
$ bundle update && jekyll serve
```

You can visit the site on [localhost:4000](http://localhost:4000/).

## Build Static Site

If you want to generate a copy static build of the website:

```sh
$ bundle install
$ jekyll build
```