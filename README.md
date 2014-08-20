# Clojure Koans Solutions

The Clojure Koans are a fun and easy way to get started with Clojure - no
experience assumed or required.  Just follow the instructions below to start
making tests pass!

**All koans are solved.**


### Getting Started

The easiest and fastest way to get the koans up and running is to [download the
latest zip file from Github](https://github.com/functional-koans/clojure-koans/downloads).
This way, you'll have all the dependencies you need, including Clojure itself
and JLine, and you can skip the rest of this section (skip to "Running the
Koans").

If you're starting from a cloned or forked repo, that's cool too. This way
you'll be able to track your progress in Git, and see how your answers compare
to others, by checking out the project's Network tab. You might want to create
your own branch - that way if you pull back the latest koans from master, it'll
be a bit easier to manage the inevitable conflicts if we make changes to
exercises you've already completed.

The only things you'll need to run the Clojure Koans are:

- JRE 1.5 or higher
- [clojure-1.5.1.jar](http://repo1.maven.org/maven2/org/clojure/clojure/1.5.1/clojure-1.5.1.zip)

You can use [Leiningen](http://github.com/technomancy/leiningen) to
automatically install the Clojure jar in the right place. Leiningen will also
get you a couple more jarfiles, including JLine, which allows you some of the
functionality of readline (command-line history, for example).

### Installing dependencies

Dependencies are installed automatically with lein 2, but if for some reason
you're on lein 1 and can't upgrade, you'll need to run

`lein deps`

which will download all dependencies you need to run the Clojure koans.

I strongly recommend that you upgrade to lein 2 instead!

### Running the Koans

If you're running from the zipfile, simply run

`script/run` on Mac/\*nix

`script\run` on Windows

If you're running from a checkout using lein 2, run the koans via

`lein koan run`

It's an auto-runner, so as you save your files with the correct answers, it will
advance you to the next koan or file (conveniently, all files are prefixed with
the sequence that you should follow).


### License

The use and distribution terms for this software are covered by the
Eclipse Public License 1.0 (http://opensource.org/licenses/eclipse-1.0.php)
which can be found in the file epl-v10.html at the root of this distribution.
By using this software in any fashion, you are agreeing to be bound by
the terms of this license.
