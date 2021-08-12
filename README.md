# What is clearfix in Bootstrap?

Clearfix is a CSS solution to deal with a bug that occurs when two floated elements are stacked next to each other. Bootstrap provides a special class to solve this problem.

Easily clear `floats` by adding `.clearfix` **to the parent element**. Can also be used as a mixin.

Use in HTML:
```html
<div class="clearfix">...</div>
```
The mixin source code:
```scss
@mixin clearfix() {
  &::after {
    display: block;
    clear: both;
    content: "";
  }
}
```

#### Much more examples and a detailed description can be found at [📄 Documentation page](https://mdbootstrap.com/how-to/bootstrap/what-is-clearfix/)
