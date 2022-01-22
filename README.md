# Jekyll Template for a Personal Website

This template configured to use with GitHub Pages.

## Previously

- Install Ruby <https://www.ruby-lang.org>:

  ``` shell
  sudo apt install ruby ruby-dev
  ```

- Setting up Ruby: add to .profile:

  ``` plain
  if [ -d "$HOME/.local/share/gem/ruby/2.7.0" ] ; then
    RUBY_PATH="$HOME/.local/share/gem/ruby/2.7.0"
    export RUBY_PATH
    GEM_HOME="$RUBY_PATH"
    export GEM_HOME
    PATH="$RUBY_PATH/bin:$PATH"
  fi
  ```

- Install Ruby gems `bundler` and `jekyll`:

  ``` shell
  gem install bundler jekyll --user-install
  ```

## Configuration

Edit this files:

- `_config.yml`: edit your personal data.
- `Gemfile`: add Jekyll plugins if you need.
- `about.html`: write something about you.

## Building

``` shell
bundle install
bundle exec jekyll build
```

## Preview

``` shell
bundle exec jekyll serve --incremental --livereload
```

## Updating

``` shell
bundle outdated
bundle update github-pages
```

## Posts adding

- Open folder `_posts` and add a new file into her by sample.
- Then don't forget to remove these examples.

## Tags adding

- Open folder `tags` and add a new folder into her in slug name format
  and put `index.html` into her by sample.
- Then don't forget to remove these examples.

## Categories adding

- Open the folder `categories` and add a new folder into her in slug name format
  and put `index.html` into her by sample.
- Then don't forget to remove these examples.

## Projects adding

- Open the folder `_projects` and add a new file into her by sample.
- Then don't forget to remove these examples.

## What's next?

Read the [Jekyll documentation](https://jekyllrb.com/docs/) and check with
[GitHub Pages documentation](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll).

## License

(CC)(0)
