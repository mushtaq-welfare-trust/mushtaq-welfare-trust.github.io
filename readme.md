# Mushtaq Welfare Trust

Source code for [Mushtaq Welfare Trust website](http://mwt.org.uk/).

## Getting started
The site is built using [Jekyll](http://jekyllrb.com/).

Prerequisites:
* Install Ruby from https://www.ruby-lang.org/en/downloads/
* Install Bundler gem from http://bundler.io/
* Install Node.js from https://nodejs.org/en/download/

Steps to setup development machine.
* `git clone git@github.com:mushtaq-welfare-trust/mushtaq-welfare-trust.github.io.git`
* `cd mushtaq-welfare-trust.github.io`
* `bundle install`
* `npm i bower -g`
* `bower install`

## Development
Run the project locally:
```
rm -rf _site; jekyll serve --trace
```

Using Docker:
```
rm -rf _site; docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll npm i bower -g; bower install; bundle exe jekyll serve --trace
```

## Production build
Before you upload the site you'll need to be build the site in production mode.

Locally:
```
rm -rf _site; JEKYLL_ENV=production jekyll build
```

Using Docker:
```
rm -rf _site; docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 --env JEKYLL_ENV=production jekyll/jekyll npm i bower -g; bower install; bundle exe jekyll build --trace
```

Once the command finish upload the content of `_site` directory to root of your web server.

## Fonts and Icons:
* [Font Awesome](https://fortawesome.github.io/Font-Awesome) - used for icons
* [Signika](https://www.google.com/fonts/specimen/Signika) - used for headings including company name
* [Open Sans](https://www.google.com/fonts/specimen/Open+Sans) - used for body text
