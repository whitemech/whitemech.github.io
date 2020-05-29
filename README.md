# WhiteMech website

This repository contains the code for the WhiteMech's website.

## Preliminaries

Follow this guide to set up your [Ruby development environment](https://cloud.google.com/ruby/docs/setup#linux-instructions).

Install Ruby version `2.6.0`:
```
rbenv install 2.6.0
```

Install `bundler`:

```
gem install bundler
```

Then:

```
bundle install
```

## Build

To build the Jekyll website:

```
bundle exec jekyll build
```

To serve:

```
bundle exec jekyll serve
```

