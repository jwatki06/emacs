# this Clojure-friendly emacs config

is a clone of [emacs-for-clojure](https://github.com/flyingmachine/emacs-for-clojure) with some of the packages updated.

## Installation

First, navigate to the home directory & clone the repo into `~/.emacs.d`. On OSX:

    $ cd ~
    $ git clone https://github.com/jwatki06/emacs.git .emacs.d


Then add the following to your lein profile (usually found at `~/.lein/profiles.clj`).

	{:repl {:plugins [[cider/cider-nrepl "0.10.0-SNAPSHOT"]]}}

## TODO:
