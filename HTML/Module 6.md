# Module 6: Lists

Welcome to Module 6 of our HTML course. In this module, we will explore lists in HTML. Lists are used to organize and present information in a structured manner. We'll cover ordered lists, unordered lists, list items, nested lists, and customizing list styles. Let's get started!

### 6.1: Ordered Lists (`<ol>`)
Ordered lists are used when the order of items is important. Each item is displayed with a number or letter by default. Here's an example of an ordered list:

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

In this example, the `<ol>` element represents the ordered list, and each list item is wrapped in an `<li>` element. The browser automatically adds the numbering for each list item.

### 6.2: Unordered Lists (`<ul>`)
Unordered lists are used when the order of items is not important. Each item is displayed with a bullet point by default. Here's an example of an unordered list:

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```

In this example, the `<ul>` element represents the unordered list, and each list item is wrapped in an `<li>` element. The browser automatically adds the bullet point for each list item.

### 6.3: List Items (`<li>`)
The `<li>` element represents an individual item within a list. It is used inside `<ol>` or `<ul>` elements to define the list items. Here's an example:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

In this example, each `<li>` element represents a list item within an unordered list. You can include any content within the `<li>` element, such as text, images, or other HTML elements.

### 6.4: Nested Lists and Sublists
HTML allows you to create nested lists, which means placing a list inside another list item. This is useful when you have a hierarchical structure or subcategories within a main list. Here's an example:

```html
<ul>
  <li>First item</li>
  <li>Second item
    <ul>
      <li>Subitem 1</li>
      <li>Subitem 2</li>
    </ul>
  </li>
  <li>Third item</li>
</ul>
```

In this example, the second list item contains a nested unordered list. The nested list is created by placing another `<ul>` element inside the parent `<li>` element.

### 6.5: Customizing List Styles
HTML provides several ways to customize the appearance of lists using CSS. You can change the bullet points or numbering style, add custom images as bullet points, and apply different styles to different levels of nested lists. By targeting the `<ul>` or `<ol>` elements and using CSS properties, you can modify the list styles to suit your design.

```css
ul {
  list-style-type: square;
}

ol {
  list-style-type: lower-roman;
}
```

In this example, the `<ul>` element has its bullet points changed to squares, while the `<ol>` element has its numbering changed to lowercase Roman numerals.

### 6.6: Concluding Thoughts
In Module 6, you have learned how to create ordered lists, unordered lists, list items, nested lists, and customize list styles. Practice creating different types of lists and experiment with CSS styles to enhance the visual presentation of your lists. 

In the next module, we will explore tables in HTML.
