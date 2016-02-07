# Goad website

<https://goad.io>

Goad is an AWS Lambda powered, highly distributed,
load testing tool. This is the website for it.

## [Goad.io][] site

We used React and ES6 to build the online demo, and we used a Node.js-based toolchain for the website. We wanted to use Go, but as far as we could tell none of static site builders built with Go have built in support for an asset pipeline that would support ES6 modules out of the box (or even easily). However, note that the website is mainly a demo and download location, and is not essential to use Goad.

The demo uses WebSockets and React to present the results of the demo load test every few seconds as more results come in.

As we wanted to prevent the site from being used as a DDoS tool, the online demo is very limited but hopefully enough to demonstrate the usefulness of the CLI version of Goad.

* [Bootstrap][] and the Darkly theme from [Bootswatch][]
* [WebPack][]
* [React][]
* [Babel][]
* [SCSS/Sass][]

## License & Copyright

MIT License. Copyright 2016 [Joao Cardoso][], [Matias Korhonen][], [Rasmus Sten][], and [Stephen Sykes][].

See the LICENSE file for more details.

[Bootstrap]: http://getbootstrap.com/
[Bootswatch]: https://bootswatch.com/
[WebPack]: https://webpack.github.io/
[React]: https://facebook.github.io/react/
[Babel]: https://babeljs.io/
[SCSS/Sass]: http://sass-lang.com/

[Joao Cardoso]: https://twitter.com/jcxplorer
[Matias Korhonen]: https://twitter.com/matiaskorhonen
[Rasmus Sten]: https://twitter.com/pajp
[Stephen Sykes]: https://twitter.com/sdsykes
