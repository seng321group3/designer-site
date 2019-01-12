# SENG 321 Client Site

A basic Jekyll site.

Jekyll is a **static site generator** - anything we write here is compiled once and deployed as regular
HTML and CSS, so no crazy back-ends needed.

## Installing and Running Locally

To run Jekyll locally, you'll need `ruby` and `bundle` installed in your PATH. Once you have that, install 
Jekyll's dependencies with `bundle install`.

To build the site:
* `bundle exec jekyll build` (or `make`)

To serve the site locally:
* `bundle exec jekyll serve` (or `make serve`)

When you build, all the compiled files can be found in the `_site` folder.

## Important Directories

* `_layouts`: HTML files defining the layout of pages. Jekyll uses [liquid](https://shopify.github.io/liquid/) for templating.
* `_sass`: Sass source files for our CSS. If you don't know sass, you should be able to write regular CSS rules in here too.
* `_data`: Data files for generating templated information on our pages. I'm currently using this for navigation but we could probably use it for the team page as well.
* `assets`: Static files to be copied into the final site.
