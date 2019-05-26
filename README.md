# ember-flex

This is a tiny Ember addon that gives you some simple classes for implementing flex in your HTML.


## Installation

```
ember install ember-flex
```

Once installed, import the addon's flex classes in your app.scss file:

```
@import 'ember-flex';
```

## Usage

The classes are really simple and let you easily iterate on your flex layouts by changing classes. For example:

```
<div class="row align-center justify-between">
  <div class="flex column align-start">
    <p>item 1</p>
    <p>item 2</p>
  </div>

  <div class="flex-2 column justify-end">
    <p>item 3</p>
    <p>item 4</p>
  </div>
</div>
```

### Row/Column

Use the `row` or `column` class to define a row or column, respectively.

### Align/Justify

Use `align` or `justify` with a modifier, like `align-baseline`, together with `row` or `column` to define how the children are aligned or justified.

### Flex-Grow

Use `flex` with a number, like `flex-3`, on children to define their proportions within a flex parent. For example, if you have two children with classes `flex` and `flex-2`, then the `flex-2` child will take up twice as much space as the other.

## License

This project is licensed under the [MIT License](LICENSE.md).
