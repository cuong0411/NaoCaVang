# NaoCaVang

## CSS

### Simple Reset CSS

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}

* {
  margin: 0;
  padding: 0;
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
