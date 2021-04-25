# Kirby Plainkit Cookiecutter

A [Cookiecutter] template to start a fresh [Kirby] site with a [public folder setup].

## Features

* A fresh, git(Hub)-ready plainkit Kirby site
* The site title is already set up
* Run it locally out of the box with [Valet] or with `composer start`
* Media is stored folder is located in `storage/media` folder and symlinked to `public/media`

## Using this cookiecutter

[Install Cookiecutter][Cookiecutter Installation Docs]:

```shell
$ pip install -U cookiecutter
# Or, on a mac with Homebrew
$ brew install cookiecutter
```

Generate a new Kirby site:

```shell
$ cookiecutter gh:beste/kirby-plainkit
```

## See it in action

[![asciicast](https://asciinema.org/a/409907.svg)](https://asciinema.org/a/409907)

## User config

If you use this (or other) Cookiecutters a lot, you can override the defaults by having
a `.cookiecutterrc` file in your home directory:

```yml
default_context:
    full_name: "My full name"
    email: "me@example.com"
    github_username: "mygithubusername"
abbreviations:
    kirby: https://github.com/beste/kirby-plainkit
```

You can find more information at https://cookiecutter.readthedocs.io/en/latest/advanced/user_config.html


[Cookiecutter]: https://github.com/cookiecutter/cookiecutter/
[Cookiecutter Installation Docs]: https://cookiecutter.readthedocs.io/en/latest/installation.html
[Kirby]: https://getkirby.com
[public folder setup]: https://getkirby.com/docs/guide/configuration#custom-folder-setup__public-folder-setup
[Laravel Valet]: https://getkirby.com/docs/cookbook/setup/development-environment#laravel-valet