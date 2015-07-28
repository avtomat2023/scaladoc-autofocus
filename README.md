# scaldoc-autofocus

Rewrites scaladoc to auto-focus index search field.

## Requirement

- python

## How to use

First of all, drop the file `scaladoc-autofocus` into a pathed directory.

After you created scaladoc, execute `scaladoc-autofocus` with the path to `api` directory of the doc. For example, if you want to apply this to the parser combinator library:

    git clone https://github.com/scala/scala-parser-combinators.git
    cd scala-parser-combinators
    sbt doc
    cd target/scala-2.11
    scaladoc-autofocus api

Open `api/index.html` in your browser, then you'll get focus on the index search field automatically.
