<p align="center">
  <img src="http://corysimmons.github.io/boy/boy-logo.svg" height="300px">
</p>

<p align="center">
  A very opinionated, lightweight, version of HTML5 Boilerplate with conditionally-loaded polyfills and an opinionated CSS reset for firing up web projects in no time.
</p>

---

Boy comes with a handy project launcher so you can spin up a Boy boilerplate with all the relevant files pulled freshly from this repo:

```fish
$ npm i -g boy
$ boy foo
```

### Features
- A lightweight/2-space batch of [HTML5 Boilerplate](https://h5bp.com) features
  - [index.html](index.html) (with all the fluff removed)
  - [.editorconfig](.editorconfig) (modified to 2 spaces)
  - [.htaccess](.htaccess)
  - [crossdomain.xml](crossdomain.xml)
  - Harsher outdated browser warning (warns on IE9 instead of IE8)
- Minified and sourcemapped :rage3: [reeeset](https://github.com/corysimmons/reeeset) (opinionated [Normalize.css](https://necolas.github.io/normalize.css) for the real world)
- Polyfills for IE8 and below a la :heart: [ie-love](https://github.com/corysimmons/ie-love)
  - Conditionally loaded so only IE8 and below users will have to download it (even though it's only 25kb uglified)
  - [html5shiv](https://github.com/aFarkas/html5shiv) (in the right place)
  - [calc-polyfill](https://github.com/closingtag/calc-polyfill)
  - [jQuery 1.x.x](https://jquery.com/download/)
  - [Selectivizr 2](https://github.com/corysimmons/selectivizr2)
  - [Respond.js](https://github.com/scottjehl/Respond)
- Empty/valid package.json for quick `npm install --save-dev`s
- `.gitignore` for Node and Bower

### Where's Modernizr?
Modernizr isn't included by default for a few reasons.

1. I very rarely actually use Modernizr.
2. You should create your own custom build of Modernizr and put it at the bottom of the document if possible. Read Paul Irish's [comment on it](https://github.com/Modernizr/Modernizr/issues/878#issuecomment-41448059).

### More Opinions You Say?
- [Enduring CSS](https://leanpub.com/enduringcss) for CSS architecture/naming conventions.
- [npm as a Build Tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool)
  - [npm-run-all](https://github.com/mysticatea/npm-run-all)
  - [BrowserSync](https://browsersync.io)
  - [node-sass](https://github.com/sass/node-sass) + [postcss-scss](https://github.com/postcss/postcss-scss)
- [Learn/Use ES2015](https://babeljs.io/docs/learn-es2015/)
  - [StandardJS](https://github.com/feross/standard) code style.
  - [Rollup](http://rollupjs.org/) or [Webpack **2**](https://github.com/webpack/webpack) for tree shaking.
- [AVA](https://github.com/sindresorhus/ava) for tests.
  - [nyc](https://github.com/bcoe/nyc) and [Codecov](https://codecov.io) for coverage.
