<p align="center">
  <img src="http://corysimmons.github.io/boy/boy-logo.svg">
</p>

<p align="center">
  A very opinionated, lightweight, up-to-date, version of HTML5 Boilerplate with conditionally loaded polyfills and a nice general CSS reset for amazing CSS3 support back to IE6 without having to lift a finger.
</p>

---

Boy comes with a handy [project launcher](#installation) so you can just `boy foo` to create a `foo` directory with all the relevant files pulled freshly from this repo.

### Features
- A lightweight/2-space batch of [HTML5 Boilerplate](https://html5boilerplate.com/) features
  - [index.html](https://github.com/h5bp/html5-boilerplate/blob/master/dist/index.html)
  - [.htaccess](https://github.com/h5bp/html5-boilerplate/blob/master/dist/.htaccess)
  - [crossdomain.xml](https://github.com/h5bp/html5-boilerplate/blob/master/dist/crossdomain.xml)
- [cssnano](http://cssnano.co/)'d CSS reset
  - [Normalize.css](https://necolas.github.io/normalize.css/)
  - [H5BP Reset](https://github.com/h5bp/html5-boilerplate/blob/master/dist/css/main.css)
  - * reset (it's actually awesome)
    - Apply `box-sizing: border-box` to everything
    - Remove all `margin` and `padding`
  - Force vertical scrollbar to prevent [page bounce](https://css-tricks.com/eliminate-jumps-in-horizontal-centering-by-forcing-a-scroll-bar)
  - `max-width: 100%` to make a plethora of HTML elements [responsive by default](http://unstoppablerobotninja.com/entry/fluid-images)
  - Generic styling for IE9 and below browser warning
- Conditionally loaded polyfills (in order) for IE8 and below
  - [html5shiv](https://github.com/aFarkas/html5shiv)
  - [calc-polyfill](https://github.com/closingtag/calc-polyfill)
  - [jQuery 1.x.x](https://jquery.com/download/)
  - [Selectivizr 2](https://github.com/corysimmons/selectivizr2)
  - [Respond.js](https://github.com/scottjehl/Respond)

### Installation (optional)
You can easily grab a zip of this, or clone it, every time you want to create a new project. **Or** you can make use of the command line tool, [boy-npm](https://github.com/corysimmons/boy-npm), to quickly create Boy projects on-the-fly.

- `npm install -g boy`
- `boy foo` to install to the `foo` directory
- `boy .` to install to the current directory
