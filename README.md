# mocka
Simple, elegant content placeholder

![Mocka](/docs/demo.gif)

```
npm install mocka-placeholder```

## Introduction

The **mocka** placeholder is a very simple content placeholder that you can use for your website or web application, while loading your page's content. It weighs very little (about 500 bytes minified and gzipped), is fully customizable and you can easily include it in your project's CSS file, by using the Sass mixin provided. Alternatively, you can copy its code and inline it in your HTML for even faster loading.

## Usage

After loading the css, you can create a placeholder using the code provided below:

```html
<div class="mocka-container">
  <span class="mocka-media"></span>
  <span class="mocka-heading"></span>
  <span class="mocka-text"></span>
</div>
```

## Customization

Download the npm package, add the mixin to your project, then `@import` the file and `@include` the mixin, passing a single map as an argument. The map contains all the information needed to generate the classes from the mixin. You can find the map with the default values in the [mocka.scss](https://github.com/Chalarangelo/mocka/blob/master/src/mocka/mocka.scss) file.

## License

**Mocka** is an open-source Sass/CSS component and is licensed under the [MIT License](https://github.com/Chalarangelo/mocka/blob/master/LICENSE).
