# <img src="./readme-img/logo.svg" width="40px" alt="SFU Surge logo" /> SFU Surge: Website

HTML, SASS, Jekyll, and Ruby website for SFU Surge.

View the website at https://sfusurge.github.io/.

## Development Setup

Setup [Ruby and bundler](https://jekyllrb.com/docs/).

Clone the repository and enter the directory:
```shell
git clone https://github.com/sfusurge/website.git
cd website/
```

Run the website locally:
```shell
bundle exec jekyll serve
```

## Folder Structure
This project uses a standard Jekyll project folder structure.

* `/_layouts` - HTML templates
* `/_includes` - Snippets of HTML that can be included and reused in te layouts
* `/_sass` - SASS style sheets - currently not used, just put css in the assets folder
* `/assets` - images and other files
* `_config.yml` - contains strings and settings that the other files can reference
* top level `index.html` and `_pages` folder - The pages of the website

## Front matter properties
At the top of html files for pages there is some Jekyll front matter (denoted with `---`) with the following properties:
* `title` - The page title to appear in the browser title bar, bookmarks, etc
* `permalink` - The part of the url after the base url that links to this page
* `layout` - Which layout file from `/_layouts` to use for the page.
* `stylesheet_override` - If the page should use a css file different than standard.css, specify it here

## TODOs
- [X] remove Volunteer link (finalize links)
- [X] add contents: Home, About, Contact, ProjectHub
- [ ] create form to get emails for ProjectHub.
- [X] deploy to sfusurge.com
- [ ] make mobile responsive (currently its not)
- [ ] add email and recaptcha
- [X] fix github commiting issue
- [X] change head
