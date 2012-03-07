# Kaminari views for Twitter Bootstrap

[twitter bootstrap](https://github.com/twitter/bootstrap) is a toolkit from Twitter designed to kickstart development of webapps and sites, including styles for [pagination](http://twitter.github.com/bootstrap/#navigation).  If you're using [kaminari](https://github.com/amatsuda/kaminari) as your pagination library, the markup in its default views won't match the selectors used by bootstrap.  This repository contains modified copies of kaminari's views that you can drop in to your ruby application to work with bootstrap.

## Installation
Copy `app/views/kaminari` into your local Rails app/views folder

## Compatibility
These views were tested with kaminari 0.12.4 and bootstrap 1.1.0 and 1.3.0.

## HAML fork
Prefer to use HAML over ERB? Lucky for you, [Nick
Gorbikoff](https://github.com/konung) has created a [HAML
fork](https://github.com/konung/twitter-bootstrap-kaminari-views) for
your pleasure.
