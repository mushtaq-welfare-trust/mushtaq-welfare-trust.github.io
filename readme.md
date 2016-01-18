# Mushtaq Welfare Trust

Source code for [Mushtaq Welfare Trust website](http://mwt.org.uk/).

## Getting started
The site is built using [Jekyll](http://jekyllrb.com/).

Steps to setup development machine.
* `gem install jekyll`
* `cd ~` or to a directory where you want to store the source code
* `git clone git@bitbucket.org:mushtaq-welfare-trust/website.git`


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
