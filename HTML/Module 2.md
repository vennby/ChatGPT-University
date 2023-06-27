Module 2: Basic HTML Document Structure

Welcome to Module 2 of our HTML course. In this module, we will explore the basic structure of an HTML document. Understanding the document structure is essential for creating well-formed HTML pages. Let's dive in!

2.1 HTML Document Structure
An HTML document follows a specific structure to ensure compatibility and consistency across different web browsers. The basic structure of an HTML document consists of the following components:

- Doctype declaration: The doctype declaration (`<!DOCTYPE>`) specifies the HTML version being used. It helps the browser understand the type of markup language used in the document.

- HTML element: The `<html>` element serves as the root element of an HTML document. It encompasses all other elements within the document and defines the HTML document type.

- Head element: The `<head>` element is a container for meta-information about the document. It does not contain visible content but holds essential information like the document's title, character encoding, CSS stylesheets, JavaScript files, and more.

- Body element: The `<body>` element represents the visible content of the web page. It contains all the elements that users see and interact with, such as headings, paragraphs, images, links, and more.

2.2 HTML Doctype Declaration
The doctype declaration is placed at the beginning of an HTML document, before the `<html>` element. It informs the browser about the version of HTML being used, allowing it to interpret the document correctly. Here's an example of a doctype declaration for HTML5:

```html
<!DOCTYPE html>
```

The `<!DOCTYPE html>` declaration is used for HTML5 documents. It's a simplified doctype declaration that triggers the browser to use the latest HTML standards.

2.3 The `<html>` Element
The `<html>` element serves as the root element of an HTML document. It encompasses all other elements within the document and defines the HTML document type. Here's an example of how the `<html>` element is used:

```html
<!DOCTYPE html>
<html>
  <!-- The head and body elements go here -->
</html>
```

2.4 The `<head>` Element and Its Purpose
The `<head>` element is a container for meta-information about the HTML document. It is not displayed on the web page itself but contains important information for the browser and search engines. Some common elements found within the `<head>` section include:

- `<title>`: The `<title>` element specifies the title of the web page. It is displayed in the browser's title bar or tab.

- `<meta>`: The `<meta>` element provides additional information about the HTML document, such as the character encoding, viewport settings, keywords, and description.

- CSS and JavaScript files: The `<head>` section is where you can link external CSS stylesheets and JavaScript files that affect the presentation and behavior of the web page.

2.5 The `<body>` Element and Its Content
The `<body>` element represents the visible content of the web page. It contains all the elements that users see and interact with. Here's an example of how the `<body>` element is used:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Meta-information and CSS/JavaScript links go here -->
  </head>
  <body>
    <!-- Visible content elements go here -->
    <h1>Welcome to My Web Page</h1>
    <p>This is the content of my web page.</p>
    <img src="image.jpg" alt="An image">
    <!-- More elements go here -->
  </body>
</html>
```

Within the `<body>` element, you can add various elements such as headings (`<h1>` to `<h6>`),

 paragraphs (`<p>`), images (`<img>`), links (`<a>`), and many more. These elements define the structure and content of your web page.

2.6 Closing Thoughts
In Module 2, we explored the basic HTML document structure. We learned about the doctype declaration, the `<html>` element as the root of the document, the `<head>` element for meta-information, and the `<body>` element for the visible content of the web page.

Understanding the HTML document structure is fundamental to creating well-formed HTML pages. In the next module, we will delve into text formatting, where we'll discover how to add headings, paragraphs, and other formatting elements to our web pages.
