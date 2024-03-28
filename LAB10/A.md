# Project Title

This project is a simple web page built with HTML and styled with Bootstrap.

## Code Explanation

The HTML document is structured as follows:

- `<!DOCTYPE html>`: This declaration specifies that this document is an HTML5 document.
- `<html>`: The root element of an HTML page.
- `<head>`: Contains meta-information about the HTML document.
  - `<meta charset="utf-8">`: Specifies the character encoding for the HTML document.
  - `<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">`: Links to the Bootstrap CSS library.
- `<body class="d-flex align-items-center justify-content-center" style="height: 100vh; margin: 0;">`: The body of the HTML document. The classes applied are Bootstrap classes for a flexible layout and center alignment. The inline CSS sets the height of the body to 100% of the viewport height and removes the default margin.
- `<div class="container" style="width: 80vmin; height: 90vmin; padding: 10px; box-sizing: border-box;">`: A container for the content of the page. The inline CSS sets the width and height to 80% and 90% of the viewport minimum dimension, adds padding, and sets the box-sizing property to include padding and border in the element's total width and height.
- The `row` and `col` classes are used to create a grid layout. The `col-9` and `col-3` classes specify the width of the columns in the grid.
- The `flex-grow-1` class allows a flex item to grow if necessary.
- The `text-center` class aligns text to the center.
- `<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>`: Links to the Bootstrap JavaScript library.

The rest of the code is standard HTML for creating headings, paragraphs, lists, and other elements. The `style` attribute is used to apply inline CSS to these elements.

## Built With

- HTML5
- Bootstrap
