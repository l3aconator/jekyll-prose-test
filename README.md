# TeamSnap Marketing Jekyll Prototype

Please be sure to have ruby installed locally.

## How to setup

`gem install jekyll bundler` <~ Need to install these to run jekyll

`git clone` the repo into where you want this stored on your machine, it has it's own self contained server.

`cd <folder-name>` change directory to the repo you just cloned

`bundle install` to install all required gems

`bundle exec jekyll serve` will compile and fire up the site.

`bundle exec jekyll build` will build site, but not serve locally

## Jekyll Plugins
We are using the Jekyll admin plugin so far. These will install automatically
### Plugin gem list
- [Jekyll Admin](https://github.com/jekyll/jekyll-admin)
- [Jekyll Feed](https://github.com/jekyll/jekyll-feed) (This comes default, probably don't need for production)

## TODO for prototyping purposes:
- Make menus generate dynamically
    - Header
    - Header subnav
    - Footer
- Assets pipeline for JS
    - bundle
    - concat
    - minify
- Image minification for img folder
- Content editor git sync

## Help Docs
[Jekyll Documentation Site](https://jekyllrb.com/docs/)
