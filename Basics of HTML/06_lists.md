# Lists

## Ordered Lists (`<ol>`)

Used when the order of items matters. Numbers are automatically assigned.

```jsx
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
```

## Unordered Lists (`<ul>`)

Used when the order of items does not matter. Items are displayed with bullet points.

```jsx
<ul>
  <li>Apples</li>
  <li>Oranges</li>
  <li>Bananas</li>
</ul>
```

## Nested Lists

Lists inside lists (`can be a mix of <ol> and <ul>`).

```jsx
<ul>
  <li>
    Frontend
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ul>
  </li>
  <li>
    Backend
    <ol>
      <li>Node.js</li>
      <li>Python</li>
    </ol>
  </li>
</ul>
```

## Definition Lists (`<dl>, <dt>, <dd>`)

Used to define terms and their descriptions.

```jsx
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language, used to structure web pages.</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets, used to style web pages.</dd>

  <dt>JavaScript</dt>
  <dd>A programming language for interactive web applications.</dd>
</dl>
```
