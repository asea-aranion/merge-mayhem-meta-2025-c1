# Flexbox
## What is Responsive Web Design

**Responsive web design (RWD)** is a development approach that allows for elements to dynamically change its appearance or layout depending on screen size. For example, elements may reorder, grow/shrink in size depending on the size of the screen.
There are different methods for incorporating responsive design. In this lab, we will explore a tool called **Flexbox** that helps create a fluid layout for website responsiveness. To learn more about other methods, check out [MDN Doc on responsive design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design).

## Creating a Flexbox Container and Items

You may be wondering, how do we even define or create a Flexbox container and items? Typically developers use the `div` HTML element to create sections that will then be defined as a Flexbox. In the CSS style file, we add a rule for these `div` containers that set the property `display` to the value `flex`.

```css
.container {
	display: flex;
}
```

In the example above, we create a rule that all `div` elements with the class name `container` will have the `display` property with value `flex` (aka a Flexbox!). Once you have defined a flex container, all elements inside automatically act as flex items.
