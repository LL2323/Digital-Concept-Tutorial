# HTML Elements

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Webpage</title>
</head>
<body>
    <h1>Welcome!</h1>
    <p>This is a basic introduction to HTML.</p>
</body>
</html>
```
- An HTML element consists of a start tag, some content, and an end tag. Elements are the building blocks of an HTML document.
- For example, the "title" element in the code above has a start tag <title>, the content "Intro to HTML", and an end tag </title>. Everything from the start tag to the end tag is considered an HTML element.
- Most elements follow this pattern, but some do not contain content and/or do not have end tags, like the <br> tag.

Let's break down the elements in our HTML document:
- `<!DOCTYPE html>`
This element informs the browser that the file is an HTML document. It does not have an end tag.
- `<html>`
This element is the root of the HTML page. All other elements are nested between its start and end tags.
- `<head>`
This container holds metadata about the HTML page, including the charset definition, links to stylesheets, and the title.
- `<title>`
This element defines the title of the document, which will appear in the browser's tab.
- `<body>`
This element contains all the content that will be displayed on the webpage.
- `<h1>`
The size and importance of the heading can be changed by changing the number in the tag. `<h1>` being the most important and `<h6>` being the least important.
ex. `<h1>`, `<h2>`, ... `<h6>`.
- `<p>`
This is a paragraph tag used to display text.

To learn more about HTML attributes, click "Next".

## [Previous](html_intro.md) | [Home](README.md) | [Next](html_attributes.md)
