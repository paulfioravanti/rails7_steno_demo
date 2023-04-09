# Rails 7 Steno Demo Blog Application

![Dolores on Rails][Dolores on Rails image url]

> Cute as heck art of [Plover][] mascot [Dolores][] riding the Rails by
> [Theo Harris][]

This is the codebase for the blog application created during the [Rails 7: The
Steno Demo][] video.

It is the same application created by [David Heinemeier Hansson][], during his
[Rails 7: The Demo][] video.

Artefacts from the steno demo itself can be found in the [`demo/`][] directory.

## Dependencies

- [Ruby][] 3.1.1
- [Rails][] 7.0.2.2

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

The application was deployed on [Heroku][] at the following address at the time
of the demo:

<https://rails7-steno-demo.herokuapp.com/>

But, since Heroku [stopped offering free plans][], it is no longer accessible.

[David Heinemeier Hansson]: https://twitter.com/dhh
[`demo/`]: ./demo
[Dolores]: http://plover.stenoknight.com/2010/10/new-logo.html
[Dolores on Rails image url]: ./demo/dolores_on_rails.png
[Heroku]: https://heroku.com/
[Plover]: http://www.openstenoproject.org/
[Rails]: https://rubyonrails.org/
[Rails 7: The Steno Demo]: https://www.youtube.com/watch?v=7UuXIkHd2xM
[Rails 7: The Demo]: https://www.youtube.com/watch?v=mpWFrUwAN88
[Ruby]: https://www.ruby-lang.org/en/
[stopped offering free plans]: https://blog.heroku.com/next-chapter
[Theo Harris]: https://dribbble.com/Theosaurus-Rex
