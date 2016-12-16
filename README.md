# Helpers

Helpers generates responsive helper classes for basic layout.

You can set your own breakpoint names and sizes in the breakpoints.scss file.

```
$breakpoints: (
  micro: 544px,
  small: 768px,
  medium: 992px,
  large: 1200px
);
```

Changing the key (micro, small, medium or large) will change all class names. For example, changing 'micro' to 'tiny' would change classes from `.hide_micro` to `.hide_tiny`.

Changing the value (544px, 768px, 992px, 1200px) will change the point at which that breakpoint is engaged.

You can add or take away breakpoints.
