# Css Positions

### Static:

- Static positioned elements are not affected by the top, bottom, left, and right properties. They are always positioned according to the normal flow of the page.

```css
.header {
  position: static;
}
```

### Relative:

- Element with position relative is placed at relative to its normal position. Placing value to left,right,top and bottom will relatively positioned element away from its normal position.

```css
.img {
  position: relative;
  left: 30px;
}
```

### Fixed:

- An element with Position fixed always stays in the same place even if the page is scrolled. Properties like top,right,bottom and left are used to position the element.

```css
.btn {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 300px;
}
```

### Absolute:

- An element with position absolute is positioned relative to the nearest position parent.

```css
.parent {
  position: relative;
}
.child {
  position: absolute;
  top: 80px;
  right: 0;
}
```

### Sticky:

- An element with sticky position is positioned based on the user's scroll position. A sticky element toggles between relative and fixed, depending on the scroll position.It is positioned relative until a given offset position is met in the viewport- then it sticks in place.

```css
.sticky-nav {
  position: sticky;
  top: 0;
}
```
