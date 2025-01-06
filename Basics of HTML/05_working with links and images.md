# Working with Links `(<a> Tag)`

## Purpose

The `<a>` tag is used to create hyperlinks, which navigate users to different web pages or resources.

## Attributes

- `href:` Specifies the URL of the page the link goes to.
- `target:` Specifies where to open the linked document. Common values:
  -- `_blank:` Opens the link in a new tab.
- `title:` Provides additional information about the link (shown as a tooltip).
- `download:` Downloads the linked file instead of navigating to it.

### Example: Links

```jsx
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Links Example</title>
</head>
<body>
  <!-- Basic Link -->
  <div>
  <a href="https://www.example.com">Visit Example.com</a>
  </div>

  <!-- Open Link in New Tab -->
  <div>
  <a href="https://www.google.com" target="_blank">Open Google in a new tab</a>
  </div>

  <!-- Link with Tooltip -->
  <div>
  <a href="https://www.wikipedia.org" title="Go to Wikipedia">Learn from Wikipedia</a>
  </div>

  <!-- Downloadable Link -->
  <div>
  <a href="sample.pdf" download>Download PDF</a>
  </div>
</body>
</html>
```

# Working with Images `(<img> Tag)`

## Purpose

The `<img>` tag is used to embed images into a webpage.

## Attributes

- `src:` Specifies the path to the image file.
  -- Absolute URL: A full URL (e.g., https://example.com/image.jpg).
  -- Relative URL: A path relative to the current HTML file (e.g., images/photo.jpg).
- `alt:` Provides alternative text if the image cannot be displayed (useful for accessibility and SEO).
- `width` & `height`: Specify the dimensions of the image.
- `title:` Adds a tooltip when the user hovers over the image.

### Example: Images

```jsx
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Images Example</title>
</head>
<body>
  <!-- Basic Image -->
  <div>
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">
  </div>

  <!-- Image with Title -->
  <div>
  <img src="https://via.placeholder.com/200" alt="Placeholder" title="This is a placeholder image">
  </div>

  <!-- Resized Image -->
  <div>
  <img src="https://via.placeholder.com/300" alt="Resized Image" width="150" height="100">
  </div>

  <!-- Image with Relative Path -->
  <div>
  <img src="images/sample.jpg" alt="Sample Image">
  </div>
</body>
</html>
```

# Combined Example: Links and Images

You can also wrap an image inside a link to make it clickable:

```jsx
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Links and Images</title>
</head>
<body>
  <div>
    <a href="https://www.example.com" target="_blank">
      <img src="https://via.placeholder.com/150" alt="Example Image">
    </a>
  </div>
</body>
</html>
```
