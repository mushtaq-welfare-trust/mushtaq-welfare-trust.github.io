# Mushtaq Welfare Trust

Source code for [Mushtaq Welfare Trust website](http://mwt.org.uk/).

## Getting started
The site is built using [Jekyll](http://jekyllrb.com/).

Prerequisites:
* Install Ruby on your machine if you do noty already have it. see https://www.ruby-lang.org/en/downloads/
* Install Bundler gem from http://bundler.io/

Steps to setup development machine.
* `git clone git@github.com:mushtaq-welfare-trust/mushtaq-welfare-trust.github.io.git`
* `cd mushtaq-welfare-trust.github.io`
* `bundle install`

## Development
Run the project locally:
`rm -rf _site; jekyll serve --trace`

## Production build
Before you upload the site you'll need to be build the site in production mode.
`rm -rf _site; JEKYLL_ENV=production jekyll build`

## Fonts and Icons:
* [Font Awesome](https://fortawesome.github.io/Font-Awesome) - used for icons
* [Signika](https://www.google.com/fonts/specimen/Signika) - used for headings including company name
* [Open Sans](https://www.google.com/fonts/specimen/Open+Sans) - used for body text
