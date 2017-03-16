## Fur

E-commerce template for Jekyll. Browse through a [live demo](https://turquoise-rook.cloudvent.net).

![Fur template screenshot](images/_screenshot.png)

Fur was made by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.

Find more templates, themes and Jekyll tutorials at [CloudCannon Academy](https://learn.cloudcannon.com/).

## Features

* List product with multiple colours and sizes
* Take payment online using SnipCart
* Contact form
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics, Google Maps API key and [SnipCart key](https://snipcart.com/) to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Fur was built with [Jekyll](http://jekyllrb.com/) version 3.4.3, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Fur is already optimised for adding, updating and removing products and editing the navigation and footer in CloudCannon.

### Posts

* Add, update or remove a post in the *Posts* collection.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Navigation

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.