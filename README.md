CSS-Font
========

CSS Font is an open-source font. Each letter is written by one &lt;div> element and css.

[View Demo](http://yusugomori.com/dev/CSS-Font)

## Usage
Simply include `css-font.css` file in your html file.

```html
<link rel="stylesheet" type="text/css" href="css-font.css" />


<!-- A -->
<div class="css-font">
  <div class="A"></div>
</div>

<!-- B -->
<div class="css-font">
  <div class="B"></div>
</div>

<!-- C -->
<div class="css-font">
  <div class="C"></div>
</div>

...

```

CSS Font is written in **Less**, so you can easily change color and size of the font by setting `@base-font-color` and `@base-font-size` in `css-font.less`.



## License
GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

[http://yusugomori.com/license/gpl-3.0](http://yusugomori.com/license/gpl-3.0)
