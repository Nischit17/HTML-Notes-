# Introduction To HTML.

## What is HTML?

HTML `(HyperText Markup Language)` is the standard markup language used to create and structure content on the web. It defines the structure of web pages using elements, which are represented by tags.

`HTML is not a programming language;` it is a `markup language` that organizes web content and tells the browser how to display it. HTML works alongside `CSS (for styling)` and `JavaScript (for interactivity)` to build dynamic web applications.

## Key Features of HTML

- `Easy to Learn:` Simple syntax and structure.
- `Platform Independent:` Works across all browsers and devices.
- `Extensible:` Allows integration with CSS and JavaScript.
- `Versatile:` Can include images, videos, links, forms, tables, and more.

## Basic Structure of an HTML Document

An HTML document has a hierarchical structure and follows a standard format. The document starts with the `<!DOCTYPE>` declaration and is enclosed in `<html>` tags.

```jsx
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your title goes Here</title>
</head>
<body>
  <!-- Content goes here -->
</body>
</html>
```

## Breakdown of the Structure

- `<!DOCTYPE>` Declaration
  -- Indicates the version of HTML used (e.g., HTML5).
  -- Placed at the very beginning of the document.
  -- Example: `<!DOCTYPE html>`

- `<html>` Element
  -- Root element that wraps all content on the page.
  -- The lang attribute specifies the language of the document `(e.g., en for English)`.

- `<head>` Section
  -- Contains meta-information about the document, such as its title, character encoding, and external resource links.

- Common elements in `<head>`:
  -- `<title>:` Sets the page title displayed on the browser tab.
  -- `<meta charset="UTF-8">:` Specifies character encoding.
  -- `<meta name="viewport" content="width=device-width, initial-scale=1.0">:` Ensures the page is responsive.
  -- `<link>:` Links to external stylesheets or resources.
  -- `<script>:` Links to external JavaScript files or inline scripts.

- `<body>` Section
  -- Contains the content visible to the user, such as text, images, videos, links, and other elements.

- The body is the main container for:
  -- Headings `(<h1> to <h6>)`
  -- Paragraphs `(<p>)`
  -- Images `(<img>)`
  -- Lists `(<ul>, <ol>)`
  -- Links `(<a>)`
  -- Tables `(<table>)`
  -- Forms `(<form>)`  
  -- Multimedia content `(<audio>, <video>)`
