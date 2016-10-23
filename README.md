# SAFE Dev Website

This repo contains the source code for [safedev.org](https://safedev.org).

In order to get started:

```sh
$ git clone https://github.com/frabrunelle/safedev.org.git
$ cd safedev.org
```

You should ensure you have [Bundler](http://bundler.io/) installed:

```sh
$ gem install bundler
```

And then:

```sh
$ make
```

Or:

```sh
$ make install
$ make serve
```

On Windows, `make` is not available, so you need to execute `bundle` and `jekyll` directly:

```sh
bundle install
bundle exec jekyll serve
```
