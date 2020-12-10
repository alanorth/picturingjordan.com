# Picturing Jordan [![Build Status](https://ci.mjanja.ch/api/badges/alanorth/picturingjordan.com/status.svg)](https://ci.mjanja.ch/alanorth/picturingjordan.com)
Picturing Jordan is a blog that attempts to share Jordan with the world one picture at a time.

<p align="center">
  <img width="600" alt="Screenshot of picturingjordan.com" src="https://raw.githubusercontent.com/alanorth/picturingjordan.com/master/screenshot.png">
</p>

You can see it live on the Internet at [picturingjordan.com](https://picturingjordan.com).

## Technology
The site is built with the [Hugo](https://gohugo.io) static site generator and uses the [Bootstrap v4 Blog](https://github.com/alanorth/hugo-theme-bootstrap4-blog) theme built by myself and a small community of volunteers on GitHub.

## Deploying
Hugo puts the compiled site in `public` so you will need to modify your web server configuration to use that as the document root. Alternatively, if you are hosting on GitHub pages or similar, you can push `public` to the root of its own branch using git subtrees:

```console
$ git subtree push --prefix=public origin public
```

This doesn't work with Git LFS, so I've opted for adjusting my web server configuration.

## License
This repository contains the code of [Bootstrap](https://github.com/twbs/bootstrap) v4 which is licensed under the [MIT license](https://github.com/twbs/bootstrap/blob/v4-dev/LICENSE).

Otherwise, the contents are licensed under the [CC-BY-SA-4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).
