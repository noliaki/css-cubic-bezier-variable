# css-cubic-bezier-variable

## Install

```sh
$ npm install -D @noliaki/css-cubic-bezier-variable
# or
$ yarn add @noliaki/css-cubic-bezier-variable
```

## Usage

you can use following variables as `animation-timing-function`

```
// Sine
$easeInSine
$easeOutSine
$easeInOutSine

// Quad
$easeInQuad
$easeOutQuad
$easeInOutQuad

// Cubic
$easeInCubic
$easeOutCubic
$easeInOutCubic

// Quart
$easeInQuart
$easeOutQuart
$easeInOutQuart

// Circ
$easeInCirc
$easeOutCirc
$easeInOutCirc

// Quint
$easeInQuint
$easeOutQuint
$easeInOutQuint

// Expo
$easeInExpo
$easeOutExpo
$easeInOutExpo

// Back
$easeInBack
$easeOutBack
$easeInOutBack
```

### Stylus

#### API

pass `node_modules/@noliaki/css-cubic-bezier-variable/stylus` to `set('paths', ...)` or `include(...)` method

```js
stylus(str)
  .set('paths', 'node_modules/@noliaki/css-cubic-bezier-variable/stylus')
  .render(...)

// or

stylus(str)
  .include('node_modules/@noliaki/css-cubic-bezier-variable/stylus')
  .render(...)
```

#### ci

set `./node_modules/@noliaki/css-cubic-bezier-variable/stylus/` to `--include` option

```
--include ./node_modules/@noliaki/css-cubic-bezier-variable/stylus/
```

---

add `@import 'ease-variables'` to stylus file

see [`stylus example`](./example/src/style.styl)
