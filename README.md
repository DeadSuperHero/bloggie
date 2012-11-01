bloggie
=======

Bloggie is a simple Rails app with blogging functionality. At the moment, it doesn't do anything special, as this is largely an experiment for me to properly learn Rails by generating different parts, piecing together basic functionas, and polishing everything up over and over again.

## Experiments

* Instead of taking the more predictable route of just learning [BootStrap](http://bootstrap.twitter.com), I've intead opted to use [Zurb Foundation](http://foundation.zurb.com/). Bootstrap may be considered in the future, but it seemed like fun trying to learn something a little different.

* Currently, I'm only going to support PostGres as a database. I may add MySQL, but for now, worrying about one type of database just seems easier.

* This app comes with [Puma](http://puma.io/) as a webserver, to run it just type: ```rails s Puma``` from the app directory in a terminal. I'm still evaluating it, but so far I like it.

* This app has a basic login using Devise. My next goal is to make use of a gem that can authenticate using Mozilla Persona. Dennis Schubert has a really cool gem for it called [devise_browserid_authenticateable](https://github.com/denschub/devise_browserid_authenticatable).

* Support for a basic user avatar is available, it just needs to be added to the user edit_registration form that Devise provides.
