# Rails 7 Steno Demo Blog Application

This is the codebase for the blog application created during the [Rails 7: The
Steno Demo][] video.

It is the same application created by [David Heinemeier Hansson][], during his
[Rails 7: The Demo][] video.

Artefacts from the steno demo itself can be found in the [`demo/`][] directory.

## Dependencies

[Ruby][] 3.1.1
[Rails][] 7.0.2.2

## Setup

```sh
git clone https://github.com/paulfioravanti/rails7_steno_demo.git
cd rails7_steno_demo
bundle install
bin/rails db:create
bin/rails db:migrate
```

## Run

```sh
bin/rails server
```

Open <http://localhost:3000> in a web browser.

## Deployment

The application is currently deployed on [Heroku][] at the following address:

<https://rails7-steno-demo.herokuapp.com/>

[David Heinemeier Hansson]: https://twitter.com/dhh
[`demo/`]: ./demo
[Heroku]: https://heroku.com/
[Rails]: https://rubyonrails.org/
[Rails 7: The Steno Demo]: https://www.youtube.com/watch?v=7UuXIkHd2xM
[Rails 7: The Demo]: https://www.youtube.com/watch?v=mpWFrUwAN88
[Ruby]: https://www.ruby-lang.org/en/
