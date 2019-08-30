# SFU Surge website

## Dev setup
This site is made with Jekyll.
* Setup Ruby and bundler https://jekyllrb.com/docs/
* Run `bundle exec jekyll serve`

## Folder structure
This project uses a standard Jekyll project folder structure

* /_layouts - HTML templates
* /_includes - Snippets of HTML that can be included and reused in te layouts
* /_sass - SASS style sheets - currently not used, just put css in the assets folder
* /assets - images and other files
* _config.yml - contains strings and settings that the other files can reference
* top level index.html and _pages folder - The pages of the website

## Front matter properties
At the top of html files for pages there is some Jekyll front matter (denoted with ---) with the following properties:
* title: The page title to appear in the browser title bar, bookmarks, etc
* permalink: The part of the url after the base url that links to this page
* layout - Which layout file from /_layouts to use for the page.
* stylesheet_override - If the page should use a css file different than standard.css, specify it here
