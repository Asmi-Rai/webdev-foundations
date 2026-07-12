# HTML Notes (Improved)

## 1. Headings
HTML provides six heading levels.

| Tag | Purpose | Example |
|---|---|---|
| `<h1>` | Main heading | `<h1>My Website</h1>` |
| `<h2>`-`<h6>` | Subheadings | `<h2>About</h2>` |

---

## 2. Paragraphs and Line Breaks

| Tag | Description | Example |
|---|---|---|
| `<p>` | Paragraph | `<p>Hello World</p>` |
| `<pre>` | Preserves spaces and line breaks | `<pre>Line 1\n  Line 2</pre>` |
| `<br>` | New line | `First<br>Second` |
| `<hr>` | Horizontal divider | `<hr>` |

## 3. Inline Styles

Syntax:
```html
<tag style="color:red; font-size:20px;">
```

Common properties:

- `color`
- `background-color`
- `border`
- `font-family`
- `font-size`
- `text-align`

Example:

```html
<p style="color:blue; text-align:center;">
Welcome
</p>
```

## 4. Text Formatting

| Tag | Purpose | Example |
|---|---|---|
| `<b>` | Bold | `<b>Bold</b>` |
| `<strong>` | Important text | `<strong>Warning</strong>` |
| `<i>` | Italic | `<i>Hello</i>` |
| `<em>` | Emphasized | `<em>Important</em>` |
| `<sub>` | Subscript | `H<sub>2</sub>O` |
| `<sup>` | Superscript | `x<sup>2</sup>` |
| `<del>` | Deleted | `<del>Old</del>` |
| `<ins>` | Inserted | `<ins>New</ins>` |
| `<mark>` | Highlight | `<mark>HTML</mark>` |

## 5. Quotations

- `<blockquote>` – Long quotation
- `<q>` – Short quotation
- `<abbr>` – Abbreviation
- `<cite>` – Title of work
- `<address>` – Contact information
- `<bdo>` – Change text direction

Example:

```html
<blockquote cite="https://example.com">
Learning HTML is fun.
</blockquote>
```

## 6. Colors

- RGB/RGBA
- HSL/HSLA
- HEX

Example:

```css
color:#3498db;
background-color:rgba(255,0,0,.3);
```

## 7. CSS Types

1. Inline
2. Internal
3. External (Recommended)

Example:

```html
<link rel="stylesheet" href="style.css">
```

## 8. Links

```html
<a href="https://example.com" target="_blank">
Visit Website
</a>
```

Targets:
- `_self`
- `_blank`
- `_parent`
- `_top`

Other examples:
- Email: `mailto:someone@example.com`
- Image link: wrap `<img>` inside `<a>`
- Button:
```html
<button onclick="location.href='index.html'">Home</button>
```

## 9. Bookmarks

```html
<h2 id="contact">Contact</h2>
<a href="#contact">Go to Contact</a>
```

## 10. Images

```html
<img src="cat.jpg" alt="Cat" width="300">
```

Common formats:
- JPG
- PNG
- GIF
- SVG
- ICO
- APNG

## 11. Image Maps

Example:

```html
<img src="map.jpg" usemap="#workmap">

<map name="workmap">
<area shape="rect" coords="0,0,100,100" href="page.html">
</map>
```

Shapes:
- rect
- circle
- poly
- default

## 12. Background Images

```css
body{
  background-image:url("bg.jpg");
  background-repeat:no-repeat;
  background-size:cover;
  background-attachment:fixed;
}
```

## 13. Picture Element

```html
<picture>
  <source media="(min-width:650px)" srcset="large.jpg">
  <img src="small.jpg" alt="Example">
</picture>
```
