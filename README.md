# NaoCaVang

## CSS

### Simple Reset CSS

```css
*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}

html {
  /*
  100% -> 16px (default of browser)
  62.5% -> 10px
  */
  font-size: 62.5%;
}

body {
  /* better practice than putting in the universal selector */
  box-sizing: border-box;
}
```

> Full detail css reset
>
> - [meyerweb](https://meyerweb.com/eric/tools/css/reset/)
> - [joshwcomeau](https://www.joshwcomeau.com/css/custom-css-reset/)

### Inclusively Hidden

> - [scottohara](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html)

```css
/* ie9+ */
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}
```
