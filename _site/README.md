# Blog
To run locally, first install the following:

`sudo apt install ruby-full ruby-all-dev build-essential zlib1g-dev`

`echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc`

`echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc`

`echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc`

`source ~/.bashrc`

Check the correct version of Jekyll to install: https://pages.github.com/versions/
and update below if needed.

`gem install 'jekyll:3.8.7' bundler`

`bundle install`

To run locally: `bundle exec jekyll serve --watch`
