# Basic HTML Elements Page

This project contains a simple HTML file that introduces the basic concepts of HTML elements. The goal is to provide a clear and concise introduction to the main elements used in building web pages.

## File Content

The HTML file demonstrates the fundamental structure of an HTML document and describes some of the most common elements. Below is the structure and a brief description of the content:

### Document Structure

```html
<!DOCTYPE html>
<html lang="pt">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Main Page</title>
  </head>
  <body>
    <h2>Basic HTML Elements</h2>
    <p>
      HTML is a markup language that uses elements to organize and present
      the content of a page. Some of the most basic elements are:
    </p>
    <details>
      <summary>Click to expand</summary>
      <ul>
        <li>
          <strong>&lt;html&gt;</strong>: defines the entire HTML document. It is the
          root element of all other elements.
        </li>
        <li>
          <strong>&lt;head&gt;</strong>: contains metadata about the page, such as the title and style links.
        </li>
        <li>
          <strong>&lt;title&gt;</strong>: defines the title of the page that appears
          in the browser tab.
        </li>
        <li>
          <strong>&lt;body&gt;</strong>: contains all the visible content of the page.
        </li>
        <li>
          <strong>&lt;h1&gt;</strong> to <strong>&lt;h6&gt;</strong>: define
          headers of different levels. The level is determined by the number of
          <strong>#</strong> before the element, where
          <strong>&lt;h1&gt;</strong> is the highest level and
          <strong>&lt;h6&gt;</strong> is the lowest.
        </li>
        <li><strong>&lt;p&gt;</strong>: defines a paragraph.</li>
        <li>
          <strong>&lt;a&gt;</strong>: defines a link. The <strong>href</strong>
          attribute specifies the address the link leads to.
        </li>
      </ul>
    </details>
  </body>
</html>
```

### Element Descriptions

- **`<!DOCTYPE html>`**: Defines the document as HTML5.
- **`<html lang="pt">`**: The root element that wraps all the content of the document. The `lang` attribute specifies the language of the page.
- **`<head>`**: Contains metadata about the document, including charset and viewport settings.
- **`<meta charset="UTF-8" />`**: Sets the character encoding to UTF-8.
- **`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`**: Configures the view for mobile devices.
- **`<title>`**: Defines the title of the page displayed in the browser tab.
- **`<body>`**: Contains all the visible content of the page.
- **`<h2>`**: A second-level header used for the section title.
- **`<p>`**: Defines a paragraph of text.
- **`<details>`**: Creates a section that can be expanded or collapsed by the user.
- **`<summary>`**: The summary or title of the expandable section.
- **`<ul>`**: Defines an unordered list.
- **`<li>`**: Defines a list item.

### Purpose

The purpose of this file is to serve as an educational introduction to basic HTML elements for beginners. It provides an overview of the structure of an HTML document and the fundamental elements that make up a web page.

## How to Use

1. Open the `index.html` file in any web browser to view the page.
2. Explore the elements listed in the expandable section to better understand each one.
3. Use this file as a reference to learn and practice creating your own HTML pages.

## Contribution

Contributions to improve this example are welcome. Feel free to fork the project and submit pull requests with enhancements or corrections.
