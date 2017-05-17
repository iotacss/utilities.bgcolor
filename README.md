**iotaCSS is now a monorepo and all individual repositories are part of it. Please open issues or PRs here: [https://github.com/iotacss/iotacss](https://github.com/iotacss/iotacss).**

# Background Color Utility #

The background color utility contains helper classes for the background-color CSS property.


### Installation ###

```
npm install --save iotacss-utils-bgcolor
```


### Options ###

```sass
$iota-utils-bgcolor-namespace : 'bgcolor-' !default;

$iota-utils-bgcolor-names     : () !default;
```


### Example ###

```sass
$iota-bgcolor-names: (
  white: #FFFFFF,
  black: #000000
);
```

It will generate:

```css
.u-bgcolor-white {
  background-color: #FFFFFF !important;
}

.u-bgcolor-black {
  background-color: #000000 !important;
}
```
