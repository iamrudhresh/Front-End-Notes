Here's an enhanced and more structured version of the CSS introduction suitable for a README file:

```markdown
# Introduction to CSS

## Table of Contents
1. [Container Element](#container-element)
2. [CSS Properties](#css-properties)
   - [Class Selector](#class-selector)
3. [CSS Text Properties](#css-text-properties)
   - [Text Align](#text-align)
   - [Color](#color)
   - [Font Family](#font-family)
   - [Font Size](#font-size)
   - [Font Style](#font-style)
   - [Font Weight](#font-weight)
   - [Text Decoration](#text-decoration)
4. [CSS Background Properties](#css-background-properties)
   - [Background Color](#background-color)
   - [Background Image](#background-image)
   - [Background Size](#background-size)

## Container Element

The HTML `<div>` element defines a container.

```html
<div>
  <h1>Tourism</h1>
  <p>Plan your trip wherever you want to go</p>
  <button>Get Started</button>
</div>
```

## CSS Properties

CSS selectors are used to "find" (or select) the HTML elements you want to style.

### Class Selector

```css
.selector {
  property1: value1; /* Declaration Block */
  property2: value2;
}
```

## CSS Text Properties

### 1. Text Align

The CSS `text-align` property specifies the horizontal alignment of the text in an HTML element.

```css
.h-center {
  text-align: center;
}
```

![Text Align Example](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/_iETRi5zCodpqEaYTbYFM.png?ixlib=js-3.7.0 "Text Align Example")

### 2. Color

The CSS `color` property specifies the color of the text.

```css
.main-heading {
  color: blue;
}
.paragraph {
  color: grey;
}
```

#### Sample Colors

![Sample Colors](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/AQ2l2N1V2a2UeUWyCEwAo.png?ixlib=js-3.7.0 "Sample Colors")

## CSS Colors

### 1. Hex Code

CSS Colors can be represented in multiple ways:
- Color names
- Hex Code
- HSL
- RGB and many more...

Since few colors have the Color names, Hex Codes make a good alternative to pick a wide variety of colors.

Some of the Color names and their Hex Codes are:

![Hex Codes](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/DeWO-z4go5r2ZNoeaC9Q7.png?ixlib=js-3.7.0 "Hex Codes")

```css
.button {
  color: #25b1cc;
}
```

#### How to pick a color using Hex Code

The color picker lets you pick a color among the approximately 16,777,216 colors available.

One of the simplest ways to access a color picker is:
Type _color picker_ in the Google Search bar and search it.

![Color Picker](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/hKH46TBslA9DM1kerXY7_.png?ixlib=js-3.7.0 "Color Picker")

### 3. Font Family

The CSS `font-family` property specifies the font for an element.

```css
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
```

You can use one of the below values of the `font-family` property:

![Font Family](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/KwpDbSv8A1qU3H1urzYpU.png?ixlib=js-3.7.0 "Font Family")

**Note:**
1. To use font families, you need to import their style sheets into your CSS file.
2. Ensure correct spelling in the values of the `font-family` property.
3. Wrap the value of the `font-family` property in quotations.

### 4. Font Size

The CSS `font-size` property specifies the size of the font.

```css
.main-heading {
  font-size: 36px;
}
.paragraph {
  font-size: 28px;
}
```

### 5. Font Style

The CSS `font-style` property specifies the font style for a text.

You can use one of the below values of the `font-style` property.

![Font Style](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/4-U22uEZI0tinEX9t6tVU.png?ixlib=js-3.7.0 "Font Style")

```css
.main-heading {
  font-style: italic;
}
.paragraph {
  font-style: normal;
}
```

### 6. Font Weight

The CSS `font-weight` property specifies how thick or thin characters in text should be displayed.

```css
.main-heading {
  font-weight: bold;
}
.paragraph {
  font-weight: 200;
}
```

You can use one of the below values of the `font-weight` property:

![Font Weight](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/6JcCeUNHvtdg9DTdxWubc.png?ixlib=js-3.7.0 "Font Weight")

**Note:**
1. Ensure correct spelling in the values of the `font-weight` property.
2. Do not use quotations around the value of the `font-weight` property.
3. Numerical values for the `font-weight` property must range from 100 to 900 and be multiples of 100.

### 7. Text Decoration

The CSS `text-decoration` property specifies the decoration added to the text.

```css
.main-heading {
  text-decoration: underline;
}
.par
