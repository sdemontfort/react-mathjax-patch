# `react-mathjax`

[![NPM version](https://badge.fury.io/js/react-mathjax.svg)](http://badge.fury.io/js/react-mathjax)

React component to display math formulas.

### Installation

```
$ npm i react-mathjax --save
```

### Usage

```js
const MathJax = require('react-mathjax')
const tex = `f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi`

module.exports = () => <MathJax>{tex}</MathJax>
```
