# Module 3: Text Formatting

In this module, we will explore various techniques to format and style text within HTML documents. We'll cover headings, paragraphs, line breaks, bold and italic text, underline text, superscript and subscript text, preformatted text, quotations, and semantic text elements. Let's dive in!

### 3.1: Headings (`<h1>` to `<h6>`)
Headings are used to represent the hierarchical structure of your content. HTML provides six levels of headings, ranging from `<h1>` (the highest level) to `<h6>` (the lowest level). Here's an example:

```html
<h1>This is a Heading Level 1</h1>
<h2>This is a Heading Level 2</h2>
<!-- ... -->
<h6>This is a Heading Level 6</h6>
```

It's important to use headings semantically, with `<h1>` being the most important and representing the main heading of the page or section.

### 3.2: Paragraphs (`<p>`)
Paragraphs are used to structure blocks of text. The `<p>` element represents a paragraph. Here's an example:

```html
<p>This is a paragraph of text.</p>
```

By default, browsers add some space before and after paragraphs to visually separate them from surrounding content.

### 3.3: Line Breaks (`<br>`)
The `<br>` element is used to create line breaks within a paragraph or other block-level elements. It doesn't require a closing tag. Here's an example:

```html
<p>This is the first line.<br>
This is the second line.</p>
```

### 3.4: Bold and Italic Text (`<strong>`, `<em>`)
To emphasize text, you can use the `<strong>` and `<em>` elements. `<strong>` represents strongly emphasized or important text and is typically rendered as bold, while `<em>` represents text with emphasized meaning and is usually rendered as italic. Here's an example:

```html
<p>This is <strong>important</strong> text.</p>
<p>This is <em>emphasized</em> text.</p>
```

### 3.5: Underline Text (`<u>`)
To underline text, you can use the `<u>` element. However, it's generally recommended to avoid underlining text, as it can be confused with hyperlinks. Instead, use CSS to style text as underlined. Here's an example:

```html
<p>This is <u>underlined</u> text.</p>
```

### 3.6: Superscript and Subscript Text (`<sup>`, `<sub>`)
To display text as superscript or subscript, use the `<sup>` and `<sub>` elements, respectively. Superscript is used for text that appears above the normal line, such as exponents or footnotes, while subscript is used for text that appears below the line. Here's an example:

```html
<p>2<sup>3</sup> is equal to 8.</p>
<p>H<sub>2</sub>O represents water.</p>
```

### 3.7: Preformatted Text (`<pre>`)
The `<pre>` element is used to display text exactly as it appears in the HTML code, preserving white spaces, line breaks, and indentation. It's commonly used for displaying code snippets or other preformatted text. Here's an example:

```html
<pre>
    function greet() {
        console.log("Hello, world!");
    }
</pre>
```

### 3.8: Quotations (`<q>`, `<blockquote>`)
HTML provides two elements for quotations: `<q>` and `<blockquote>`. `<q>` is used for short inline quotations, while `<blockquote>` is used for longer block-level quotations. Here's an example:

```html
<p>She said, <q>I love HTML!</q></p>

<blockquote>
    <p>This is a longer quotation that spans multiple lines.</p>
    <p>It's best to use the <code><blockquote></code> element for this.</p>
</blockquote>
```

### 3.9: Semantic Text Elements (`<mark>`, `<small>`, `<del>`, `<ins>`)
HTML provides several semantic elements to add meaning to text. `<mark>` highlights text to draw attention, `<small>` represents smaller text for legal disclaimers or fine print, `<del>` indicates deleted text, and `<ins>` indicates inserted text. Here's an example:

```html
<p>Highlight this <mark>important</mark> text.</p>
<p>This is some <small>fine print</small>.</p>
<p><del>This text has been deleted.</del></p>
<p><ins>This text has been inserted.</ins></p>
```

In Module 3, we've covered headings, paragraphs, line breaks, bold and italic text, underline text, superscript and subscript text, preformatted text, quotations, and semantic text elements.

In the next module, we will explore links and navigation, enabling you to create interactive web pages. 

<br>

<p align="left"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%202.md"><< Previous</a></p>
<p align="center"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Handout.md">Handout</p>
<p align="right"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%204.md">Next >></p>
