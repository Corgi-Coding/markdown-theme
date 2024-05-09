# corgicoding-theme-css

Render css based on the markdown format modified by typo.css.

---

- Author: Charles Chan
- Organization: Corgi Coding
- Github: https://github.com/Corgi-Coding

_version 1.0.4: fix `li pre` style_  
_version 1.0.4: fix `li pre` style_  
_version 1.0.5: add feat global style_
_version 1.0.6: remove global style | fix some error_

\*version 2.0.0: vite build

## How to use

There are two ways to use it

### NPM

1. Install package

```
    npm install @corgicoding/theme
```

2. Import css file to the page.

```js
import '@corgicoding/theme';
```

3. Add the `cc__markdown-theme` class to the dom element to be rendered.

```html
<div class="cc__markdown-theme">
  <h1>hello</h1>
  <div></div>
</div>
```

### HTML

1. DownLoad this Repository.
2. Unzip
3. Add the `c-html-render` class to the dom element to be rendered.
4. Add the following code to the page.

```html
<!--   Prevent compatibility issues caused by different browsers   -->
<link rel="stylesheet" href="./dist/normalize.css" />
<!--   corgicoding.theme   -->
<link rel="stylesheet" href="./dist/corgicoding.theme.min.css" />
<!--   github style code render   -->
<link rel="stylesheet" href="./dist/github.css" />

<div class="cc__markdown-theme">
  <h1>hello</h1>
  <div></div>
</div>
```

## Option Classes

header title no counter

```html
<div class="cc__markdown-theme disabled-counter">
  <h1>hello</h1>
  <div></div>
</div>
```
