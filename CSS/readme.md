
---

# CSS Notes 

## Table of Contents
1. [Introduction to CSS](#introduction-to-css)
2. [CSS Syntax](#css-syntax)
3. [Selectors](#selectors)
4. [Color](#color)
5. [Text](#text)
6. [Box Model](#box-model)
7. [Flexbox](#flexbox)
8. [Grid](#grid)
9. [Media Queries](#media-queries)
10. [Conclusion](#conclusion)

## Introduction to CSS

CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML. CSS defines how HTML elements should be displayed.

![CSS Example](https://via.placeholder.com/600x300.png?text=CSS+Example)

## CSS Syntax

A CSS rule consists of a selector and a declaration block.

```css
selector {
    property: value;
}
```

### Example:

```css
p {
    color: blue;
    font-size: 16px;
}
```

![CSS Syntax](https://via.placeholder.com/600x300.png?text=CSS+Syntax)

## Selectors

Selectors are used to target the HTML elements you want to style.

### Types of Selectors:

1. **Element Selector** - Targets HTML elements by their name.
   ```css
   p {
       color: red;
   }
   ```
2. **Class Selector** - Targets elements by their class attribute.
   ```css
   .my-class {
       background-color: yellow;
   }
   ```
3. **ID Selector** - Targets elements by their id attribute.
   ```css
   #my-id {
       font-weight: bold;
   }
   ```
4. **Universal Selector** - Targets all elements.
   ```css
   * {
       margin: 0;
       padding: 0;
   }
   ```

![CSS Selectors](https://via.placeholder.com/600x300.png?text=CSS+Selectors)

## Color

You can set colors using names, HEX, RGB, or HSL values.

### Examples:

```css
/* Named Color */
h1 {
    color: red;
}

/* HEX Color */
h2 {
    color: #00ff00;
}

/* RGB Color */
p {
    color: rgb(0, 0, 255);
}

/* HSL Color */
div {
    color: hsl(120, 100%, 50%);
}
```

![CSS Colors](https://via.placeholder.com/600x300.png?text=CSS+Colors)

## Text

Styling text involves properties like `color`, `font-size`, `font-family`, `text-align`, etc.

### Examples:

```css
h1 {
    color: purple;
    font-size: 24px;
    font-family: Arial, sans-serif;
    text-align: center;
}
```

![CSS Text](https://via.placeholder.com/600x300.png?text=CSS+Text)

## Box Model

The box model consists of `margin`, `border`, `padding`, and `content`.

### Example:

```css
div {
    width: 300px;
    padding: 20px;
    border: 5px solid black;
    margin: 25px;
}
```

![CSS Box Model](https://via.placeholder.com/600x300.png?text=CSS+Box+Model)

## Flexbox

Flexbox is used to design a flexible and responsive layout structure.

### Example:

```css
.container {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.item {
    flex: 1;
    margin: 10px;
}
```

![CSS Flexbox](https://via.placeholder.com/600x300.png?text=CSS+Flexbox)

## Grid

CSS Grid Layout is a two-dimensional layout system.

### Example:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

.item {
    padding: 20px;
    background-color: lightgrey;
}
```

![CSS Grid](https://via.placeholder.com/600x300.png?text=CSS+Grid)

## Media Queries

Media queries are used to apply different styles for different devices or screen sizes.

### Example:

```css
/* For tablets and larger screens */
@media (min-width: 600px) {
    body {
        background-color: lightblue;
    }
}

/* For mobile devices */
@media (max-width: 599px) {
    body {
        background-color: lightcoral;
    }
}
```

![CSS Media Queries](https://via.placeholder.com/600x300.png?text=CSS+Media+Queries)

## Conclusion

CSS is a powerful tool for web developers to create visually appealing and responsive web pages. Practice the examples provided and experiment with different properties and values to get a deeper understanding of CSS.

Happy Styling!

![CSS Conclusion](https://via.placeholder.com/600x300.png?text=Happy+Styling!)

---
