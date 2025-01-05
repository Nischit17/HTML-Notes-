# Comments & Shortcuts in HTML

Comments in HTML are essential for documenting your code, explaining specific sections, or leaving notes for yourself or other developers. They can also be used as a quick way to temporarily disable sections of code during development.

Comments are also used to disable code. This is useful when you want to test something out without deleting the code.

You may also use comments as a todo list. This is useful when you want to keep track of what you need to do next.

# HTML Comments

In HTML, comments are created using the `<!-- and -->` syntax. Anything inside these symbols is ignored by the browser and will not be rendered on the page.

### Single Line Comments

Although HTML doesn’t have a dedicated syntax for single-line comments like JavaScript, you can achieve the same effect by using the standard comment syntax `<!-- -->` on one line.

```jsx
<!-- This is a single line comment -->
<p>Hello, World!</p> <!-- This is an inline single line comment -->
```

### Multi Line Comments

For multi-line comments, you simply enclose multiple lines of code within the `<!-- and -->` tags.

```jsx
<!--
This is a multi-line comment.
It can span multiple lines
and is useful for providing detailed explanations.
-->
```

# Use Cases for HTML Comments

## Documenting Code

Explain the purpose of sections of your code or provide additional context for complex structures.

```jsx
<!-- This section displays the header of the website -->
<header>
  <h1>Welcome to My Website</h1>
</header>
```

## Disabling Code

Temporarily remove sections of HTML code without deleting them.

```jsx
<!--
<section>
  <h2>This section is under construction.</h2>
</section>
-->
```

## Todo Lists

Use comments as reminders for future work or updates.

```jsx
<!-- TODO: Add a navigation menu here -->
```

# HTML Shortcuts

Helpful Keyboard Shortcuts (For VS Code and Similar Editors)

### Highlighting and Navigation:

- `shift + up/down` - Highlight lines of code up and down.
- `shift + right/left` - Highlight code right and left.
- `cmd + right/left arrow` - Move cursor to beginning/end of a line.
- `cmd + up/down arrow` - Move cursor to the beginning/end of the file.

### Moving and Copying Lines:

- `option + up/down arrow` - Move a line of code up or down.
- `shift + option + up/down arrow` - Duplicate the current line of code and place it above or below.

### Commenting:

- `cmd + /` - Comment or uncomment a line of code (works for single-line comments).
- `cmd + shift + /` - Comment or uncomment multiple lines of code.

### Selecting Text:

- `cmd + d` - Select the next instance of the currently selected text.
- `cmd + shift + l` - Select all instances of the currently selected text.

### Searching

- `cmd + shift + f` - Search for a string in the entire project.
- `cmd + shift + o` - Search for a file in the project.

# Emmet Abbreviations

HTML development becomes faster with Emmet, which expands shorthand expressions into full HTML tags.

## Basic Tags:

- `div` → `<div></div>`
- `h1` → `<h1></h1>`

## Nesting:

- `div>ul>li` →

```jsx
<div>
  <ul>
    <li></li>
  </ul>
</div>
```

## Classes and IDs:

- `.class-name` → `<div class="class-name"></div>`
- `#id-name` → `<div id="id-name"></div>`

## Lists:

- `ul>li*3` →

```jsx
<ul>
  <li></li>
  <li></li>
  <li></li>
</ul>
```

## Attributes:

- `input[type=text]` → `<input type="text">`
