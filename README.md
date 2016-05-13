# Placeholder

The aleutcss `placeholder` module contains a useful mixin for changing the text-color on placeholder-text on input-fields.


## Install using npm:

```ssh
$ npm install --save-dev aleut.tools-placeholder

```

## Usage

Basic usage of the mixins in a SCSS-file:

```scss
.foo {
	@include placeholder(#f2f2f2);
}
```

This yields:

```css
.foo::-webkit-input-placeholder {
  /* WebKit browsers */
  color: #f2f2f2;
}

.foo:-moz-placeholder {
  /* Mozilla Firefox 4 to 18 */
  color: #f2f2f2;
}

.foo::-moz-placeholder {
  /* Mozilla Firefox 19+ */
  color: #f2f2f2;
}

.foo:-ms-input-placeholder {
  /* Internet Explorer 10+ */
  color: #f2f2f2;
}
```
