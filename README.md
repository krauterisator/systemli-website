This static website is built with [Jekyll](https://github.com/jekyll/jekyll)
 and [octopress](https://github.com/octopress/).

Please improve by providing content, translations or code.

## Requirements

apt-get install python-software-properties
apt-add-repository ppa:brightbox/ruby-ng
apt-get update
apt-get install ruby2.1 ruby2.1-dev
gem install jekyll octopress octopress-paginate octopress-multilingual

## Add new post
 * Write new post in `_posts/`.
 * Add translation also in `_posts/`.
 * `octopress id _posts/first_post _posts/second_post
 * restart jekyll
