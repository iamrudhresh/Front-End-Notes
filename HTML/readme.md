
```markdown
# HTML Notes

## 1. Introduction to HTML
- HTML : HyperText Markup Language
- Purpose: Standard markup language for creating web pages.
- File Extension: `.html` or `.htm`

## 2. Basic Structure of an HTML Document
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

## 3. Common HTML Elements

### a. Headings
```html
<h1>This is a heading</h1>
<h2>This is a subheading</h2>
<h3>This is a smaller subheading</h3>
```

### b. Paragraphs
```html
<p>This is a paragraph.</p>
```

### c. Links
```html
<a href="https://example.com">This is a link</a>
```

### d. Images
```html
<img src="image.jpg" alt="Description of the image">
```

### e. Lists
- **Unordered List**
  ```html
  <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
  </ul>
  ```
- **Ordered List**
  ```html
  <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
  </ol>
  ```

## 4. HTML Attributes
- **Syntax**: `<tag attribute="value">`
- **Common Attributes**:
  - `href` for links
  - `src` for images
  - `alt` for image descriptions
  - `id` for unique element identification
  - `class` for grouping elements

## 5. HTML Forms
```html
<form action="/submit-form" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <input type="submit" value="Submit">
</form>
```

## 6. HTML5 Semantic Elements
- `<header>`: Defines a header for a document or section.
- `<nav>`: Defines navigation links.
- `<main>`: Specifies the main content of a document.
- `<section>`: Defines a section in a document.
- `<article>`: Defines an independent, self-contained article.
- `<footer>`: Defines a footer for a document or section.
- `<aside>`: Defines content aside from the main content.

## 7. Multimedia Elements
- **Audio**
  ```html
  <audio controls>
      <source src="audio.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
  </audio>
  ```
- **Video**
  ```html
  <video width="320" height="240" controls>
      <source src="movie.mp4" type="video/mp4">
      Your browser does not support the video tag.
  </video>
  ```

## 8. Tables
```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

## 9. HTML Entities
- **Usage**: To display reserved characters in HTML.
- Examples:
  - `&lt;` for `<`
  - `&gt;` for `>`
  - `&amp;` for `&`
  - `&quot;` for `"`
  - `&apos;` for `'`

## 10. Inline vs. Block Elements
- **Inline Elements**: Do not start on a new line. (e.g., `<span>`, `<a>`, `<img>`)
- **Block Elements**: Start on a new line and take up full width. (e.g., `<div>`, `<p>`, `<h1>`)

## 11. HTML Comments
```html
<!-- This is a comment -->
```

## 12. Doctype Declaration
- **Purpose**: Defines the HTML version being used.
- **HTML5 Doctype**:
  ```html
  <!DOCTYPE html>
  ```

## 13. Character Encoding
- **UTF-8**: Most commonly used character encoding.
  ```html
  <meta charset="UTF-8">
  ```

## 14. Meta Tags
- **Viewport**: Ensures responsive design on different devices.
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

## 15. Linking CSS and JavaScript
- **CSS**:
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
- **JavaScript**:
  ```html
  <script src="script.js"></script>
  ```

---

This guide covers the fundamental aspects of HTML. As you delve deeper into web development, you will encounter more advanced topics such as CSS for styling, JavaScript for interactivity, and various frameworks and libraries that enhance the capabilities of HTML.
```

Feel free to edit and expand the content as needed.
