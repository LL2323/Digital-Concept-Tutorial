# HTML Tags

Previously, we covered the common tags that appear in almost every HTML document. However, HTML includes dozens of different tags, many of which are rarely used.

Now, let's explore some other frequently used tags that you will encounter as you delve deeper into HTML.

- `<div>`
  - This tag is used as a block container for HTML elements.
```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Title</title>
    </head>
    <body>
        <div style="color: red">
            <p>This is in the first div</p>
            <p>Hello</p>
        </div>
    </body>
</html>
```
- `<a>`
  - This tag is used to define links.
```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Title</title>
    </head>
    <body>
        <a href="www.google.com">Link to Google</a>
    </body>
</html>
```
- `<img>`
  - This is an image tag and is how to display an image.
  - This tag always has a "src" attribute which defines the path to the image.
  - It must also have an "alt" attribute which will be displayed if the image is unable to be displayed.
  - It can contain other attributes like "height" and "width".
```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Title</title>
    </head>
    <body>
        <img src="images/screenshot1.jpg" alt="sc1" width="300" height="400">
    </body>
</html>
```
- `<ol>` and `<ul>`
  - "ol" stands for Ordered List, and "ul" stands for Unordered List.
  - Ordered lists are numbered "1", "2", etc.
  - Unordered lists are bullet points, like the list you're reading right now.
  - Each item in a list is displayed by using the `<li>`, or List Item element.
```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Title</title>
    </head>
    <body>
        <ol>
            <li>First Item</li>
            <li>Second Item</li>
        </ol>
        <ul>
            <li>An Item</li>
            <li>Another Item</li>
        </ul>
    </body>
</html>
```
- `<span>`
  - This element is similar to a `<div>` tag, although rather than used as a block container, this tag is used an in inline container.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Title</title>
    </head>
    <body>
        <p>Hello my <span style="font-weight: bold">name</span> is Landen</p>
    </body>
</html>
```

## [Previous](html_attributes.md) | [Home](README.md)
