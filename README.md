# Blog

To run locally, first install the following:

## Local development setup

### Install rbenv

1. `git clone https://github.com/rbenv/rbenv.git ~/.rbenv`
1. `echo 'eval "$(~/.rbenv/bin/rbenv init - bash)"' >> ~/.bashrc`
1. Restart shell
1. `rbenv -v`
1. `git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build`
    * required for `rbenv install` command

### Install [Github Pages-version of Ruby](https://pages.github.com/versions/)

1. `rbenv install <VERSION>`
1. `rbenv local <VERSION>`

### Install Jekyll (use version page above) and the rest of the gems

1. `gem install 'jekyll:<VERSION>' bundler`
1. `bundle install`

### Run site locally

`bundle exec jekyll serve --watch`
