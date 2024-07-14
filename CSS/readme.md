# **Introduction to CSS**

CSS (Cascading Style Sheets) is a language used to describe the presentation of a document written in HTML. CSS selectors are used to "find" (or select) the HTML elements you want to style.

## 1. Container Element
The HTML **div** element defines a container.

```html
<div>
  <h1>Tourism</h1>
  <p>Plan your trip wherever you want to go</p>
  <button>Get Started</button>
</div>
```

## CSS Properties

### Class Selector
A CSS class selector selects elements with a specific class attribute. The class name starts with a dot (.) in the CSS.

```css
.selector {
  property1: value1; /* Declaration Block */
  property2: value2;
}
```

## CSS Text Properties

### 1. Text Align
The CSS **text-align** property specifies the horizontal alignment of the text in an HTML element.

```css
.h-center {
  text-align: center;
}
```

![Center Aligned Text](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/_iETRi5zCodpqEaYTbYFM.png?ixlib=js-3.7.0 "Center Aligned Text")

### 2. Color
The CSS **color** property specifies the color of the text.

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
- RGB and more...

Since few colors have Color names, Hex Codes make a good alternative to pick a wide variety of colors.

#### Sample Colors and Hex Codes
![Hex Codes](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/DeWO-z4go5r2ZNoeaC9Q7.png?ixlib=js-3.7.0 "Hex Codes")

```css
.button {
  color: #25b1cc;
}
```

#### How to Pick a Color Using Hex Code
One of the simplest ways to access a color picker is:

1. Open Google.
2. Type _color picker_ in the search bar and hit enter.

![Color Picker](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/hKH46TBslA9DM1kerXY7_.png?ixlib=js-3.7.0 "Color Picker")

### 3. Font Family
The CSS **font-family** property specifies the font for an element.

```css
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap");

.main-heading {
  font-family: "Roboto", sans-serif;
}
.paragraph {
  font-family: "Roboto", sans-serif;
}
```

You can use one of the values for the **font-family** property as shown below:

![Font Family](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/KwpDbSv8A1qU3H1urzYpU.png?ixlib=js-3.7.0 "Font Family")

**Note:**
1. To use custom fonts, import their stylesheets into your CSS file.
2. Ensure there are no spelling mistakes in the font-family values.
3. Enclose the font-family value in quotation marks if it contains spaces.

### 4. Font Size
The CSS **font-size** property specifies the size of the font.

```css
.main-heading {
  font-size: 36px;
}
.paragraph {
  font-size: 28px;
}
```

### 5. Font Style
The CSS **font-style** property specifies the font style for text.

```css
.main-heading {
  font-style: italic;
}
.paragraph {
  font-style: normal;
}
```

You can use one of the values for the **font-style** property as shown below:

![Font Style](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/4-U22uEZI0tinEX9t6tVU.png?ixlib=js-3.7.0 "Font Style")

### 6. Font Weight
The CSS **font-weight** property specifies how thick or thin characters in text should be displayed.

```css
.main-heading {
  font-weight: bold;
}
.paragraph {
  font-weight: 200;
}
```

You can use one of the values for the **font-weight** property as shown below:

![Font Weight](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/6JcCeUNHvtdg9DTdxWubc.png?ixlib=js-3.7.0 "Font Weight")

**Note:**
1. Ensure there are no spelling mistakes in the font-weight values.
2. Do not use quotations around the font-weight values.
3. Numerical values for font-weight must be multiples of 100 between 100 and 900.

### 7. Text Decoration
The CSS **text-decoration** property specifies the decoration added to the text.

```css
.main-heading {
  text-decoration: underline;
}
.paragraph {
  text-decoration: overline;
}
```

You can use one of the values for the **text-decoration** property as shown below:

![Text Decoration](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/WEHXrSfZ19N8j4URJj6hJ.png?ixlib=js-3.7.0 "Text Decoration")

**Note:**
1. Ensure there are no spelling mistakes in the text-decoration values.
2. Do not use quotations around the text-decoration values.
3. Ensure that `text-decoration` and `line-through` are hyphenated.

## CSS Background Properties

### 1. Background Color
The CSS **background-color** property specifies the background color of an HTML element.

```css
.card {
  background-color: lightblue;
}
```

### 2. Background Image
The CSS **background-image** property specifies the background image of an HTML element.

```css
.card {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
}
```

![Background Image](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/iDR4mO658tQFPZEQ3SHsm.png?ixlib=js-3.7.0 "Background Image")

**Warning:**
1. The background image takes the height of the content of an HTML element if you don't specify the height.
2. The URL given to the background-image must be valid.

### 3. Background Size
The CSS **background-size** property specifies the size of the background image of an HTML element.

![Background Size](https://eraser.imgix.net/workspaces/DDWu6SYNWfw2qQA5zZeb/cW4TYXUmCph0yuFtGhfXbN9Xayl1/PRaTGcZlwyatK2gL6WsNt.png?ixlib=js-3.7.0 "Background Size")

**HTML:**

```html
<!DOCTYPE html>
<html>
  <head></head>
  <body>
    <div class="card">
      <h1>Tourism</h1>
      <p>Plan your trip wherever you want to go</p>
      <button>Get Started</button>
    </div>
  </body>
</html>
```

**CSS:**

```css
.card {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  background-size: cover;
  width: 250px;
  height: 200px;
}
```

## Summary
CSS allows you to style HTML elements in various ways, including text alignment, color, font properties, text decoration, and background properties. Understanding and applying these properties can greatly enhance the visual appeal and functionality of your web pages.
