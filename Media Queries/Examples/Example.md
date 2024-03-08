# This File Explains all the Code Snippets of Example Folder

## Change the appearance of DIV on different screen sizes.html

<img width="502" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/13de3d09-1ec8-4db9-bf9b-af1f4bf85e3f">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Change%20the%20appearance%20of%20DIV%20on%20different%20screen%20sizes.html) is designed to change the appearance of a `div` element based on the width of the browser window.

### Explanation of Each Line

1. The `<!DOCTYPE html>` declaration helps with browser compatibility.
   ```html
   <!DOCTYPE html>
   ```

2. The `<meta charset="utf-8">` tag ensures the correct character encoding.
   ```html
   <meta charset="utf-8">
   ```

3. The `<meta name="viewport" content="width=device-width, initial-scale=1">` tag makes the webpage responsive on different devices.
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1">
   ```

4. The `@media screen and (max-width: 900px) and (min-width: 600px)` is a media query that applies CSS rules for screen sizes between 600px and 900px.
   ```css
   @media screen and (max-width: 900px) and (min-width: 600px) {
     /* CSS rules go here */
   }
   ```

5. The `div.example` style rule changes the font size, padding, border, and background color of the div element with the class example when the conditions of the media query are met.
   ```css
   div.example {
     font-size: 50px;
     padding: 50px;
     border: 8px solid black;
     background: yellow;
   }
   ```

6. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

7. The `<div class="example">Example DIV.</div>` is the div element that will be affected by the media query.
   ```html
   <div class="example">Example DIV.</div>
   ```

8. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
   ```html
   <p>Your text here</p>
   ```

## Change the font size of an element on different screen sizes.html

<img width="580" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/ff2bf733-35ec-448d-a08b-622835e00758">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Change%20the%20font%20size%20of%20an%20element%20on%20different%20screen%20sizes.html) is designed to change the font size of a `div` element based on the width of the browser window.

### Explanation of Each Line
1. The `div.example` style rule sets the background color and padding of the div element with the class example.
   ```css
   div.example {
     background-color: lightgrey;
     padding: 20px;
   }
   ```

2. The `@media screen and (min-width: 600px)` is a media query that applies the CSS rule for screen sizes 600px and wider.
   ```css
   @media screen and (min-width: 600px) {
     div.example {
       font-size: 80px;
     }
   }
   ```

3. The `@media screen and (max-width: 600px)` is a media query that applies the CSS rule for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     div.example {
       font-size: 30px;
     }
   }
   ```

4. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

5. The `<div class="example">Example DIV.</div>` is the div element that will be affected by the media query.
   ```html
   <div class="example">Example DIV.</div>
   ```

6. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
   ```html
   <p>Your text here</p>
   ```

## Changing Background Color Based on Screen Width.html

<img width="756" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/4be7592a-1759-43e6-8cd7-2ecfeb54a3ba">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Changing%20Background%20Color%20Based%20on%20Screen%20Width.html) is designed to change the background color and text color of the body based on the width of the browser window.

### Explanation of Each Line

1. The `body` style rule sets the default background color and text color of the body.
   ```css
   body {
     background-color: tan;
     color: black;
   }
   ```

2. The `@media screen and (max-width: 992px)` is a media query that changes the background color and text color for screen sizes 992px and narrower.
   ```css
   @media screen and (max-width: 992px) {
     body {
       background-color: blue;
       color: white;
     }
   }
   ```

3. The `@media screen and (max-width: 600px)` is a media query that changes the background color and text color for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     body {
       background-color: olive;
       color: white;
     }
   }
   ```

4. The `<h1>` tag provides a heading for the webpage.
   ```html
   <h1>Your Heading Here</h1>
   ```

5. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
   ```html
   <p>Your text here</p>
   ```

## Flexible Column Layout Using Flexbox.html

<img width="758" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/ca56f074-a3f6-4fb2-86ad-5dbf151e2f42">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Flexible%20Column%20Layout%20Using%20Flexbox.html) is designed to create a responsive four column layout using Flexbox.

### Explanation of Each Line

1. The `*` selector applies the `box-sizing: border-box;` rule to every element, which includes padding and border in the element's total width and height.
   ```css
   * {
     box-sizing: border-box;
   }
   ```

2. The `.row` style rule sets the display property to `flex` and allows the flex items to wrap as needed with `flex-wrap: wrap;`.
   ```css
   .row {
     display: flex;
     flex-wrap: wrap;
   }
   ```

3. The `.column` style rule sets the flex property to `25%` and adds padding of `20px`.
   ```css
   .column {
     flex: 25%;
     padding: 20px;
   }
   ```

4. The `@media screen and (max-width: 992px)` is a media query that changes the flex property to `50%` for screen sizes 992px and narrower.
   ```css
   @media screen and (max-width: 992px) {
     .column {
       flex: 50%;
     }
   }
   ```

5. The `@media screen and (max-width: 600px)` is a media query that changes the flex direction to `column` for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     .row {
       flex-direction: column;
     }
   }
   ```

6. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

7. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
    ```html
    <p>Your text here</p>
    ```

8. The `<div class="row">` tag is the container for the flex items.

9. The `<div class="column" style="background-color: #aaa">` tags are the flex items with different background colors.
   ```html
   <div class="column" style="background-color: #aaa">
     <h2>Column 1</h2>
     <p>Some text..</p>
   </div>
   ```

## Flexible Website.html


<img width="717" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/eb4f75f5-e768-4adf-b16d-b791de6642c7">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Flexible%20Website.html) is designed to create a responsive website layout using Flexbox.

### Explanation of Each Line

1. The `*` selector applies the `box-sizing: border-box;` rule to every element, which includes padding and border in the element's total width and height.
   ```css
   * {
     box-sizing: border-box;
   }
   ```

2. The `body` style rule sets the default font and margin of the body.
   ```css
   body {
     font-family: Arial;
     margin: 0;
   }
   ```

3. The `.header` style rule styles the header with a specific background color, text color, padding, and text alignment.
   ```css
   .header {
     padding: 60px;
     text-align: center;
     background: #1abc9c;
     color: white;
   }
   ```

4. The `.navbar` style rule sets the display property to `flex` and gives it a specific background color.
   ```css
   .navbar {
     display: flex;
     background-color: #333;
   }
   ```

5. The `.navbar a` style rule styles the navigation bar links with a specific color, padding, text decoration, and text alignment.
   ```css
   .navbar a {
     color: white;
     padding: 14px 20px;
     text-decoration: none;
     text-align: center;
   }
   ```

6. The `.navbar a:hover` style rule changes the background color and text color of the navigation bar links when hovered over.
   ```css
   .navbar a:hover {
     background-color: #ddd;
     color: black;
   }
   ```

7. The `.row` style rule sets the display property to `flex` and allows the flex items to wrap as needed with `flex-wrap: wrap;`.
    ```css
    .row {
      display: flex;
      flex-wrap: wrap;
    }
    ```

8. The `.side` and `.main` style rules create two unequal columns that sit next to each other. The `.side` column takes up 30% of the space, and the `.main` column takes up 70% of the space.
    ```css
    .side {
      flex: 30%;
      background-color: #f1f1f1;
      padding: 20px;
    }

    .main {
      flex: 70%;
      background-color: white;
      padding: 20px;
    }
    ```

9. The `.fakeimg` style rule creates a fake image with a specific background color, width, and padding.
    ```css
    .fakeimg {
      background-color: #aaa;
      width: 100%;
      padding: 20px;
    }
    ```

10. The `.footer` style rule styles the footer with a specific padding, text alignment, and background color.
    ```css
    .footer {
      padding: 20px;
      text-align: center;
      background: #ddd;
    }
    ```

11. The `@media screen and (max-width: 700px)` is a media query that changes the flex direction to `column` for screen sizes 700px and narrower.
    ```css
    @media screen and (max-width: 700px) {
      .row,
      .navbar {
        flex-direction: column;
      }
    }
    ```

## Hide elements on different screen sizes.html 

<img width="546" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/77decf14-6172-4864-b2e3-ec21014cb365">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Hide%20elements%20on%20different%20screen%20sizes.html) is designed to hide a `div` element based on the width of the browser window.

### Explanation of Each Line

1. The `div.example` style rule sets the background color and padding of the div element with the class example.
   ```css
   div.example {
     background-color: yellow;
     padding: 20px;
   }
   ```

2. The `@media screen and (max-width: 600px)` is a media query that hides the div element with the class example for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     div.example {
       display: none;
     }
   }
   ```

3. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

4. The `<div class="example">Example DIV.</div>` is the div element that will be affected by the media query.
   ```html
   <div class="example">Example DIV.</div>
   ```

5. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
   ```html
   <p>Your text here</p>
   ```

## Orientation- Portrait or Landscape.html

<img width="544" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/412515c7-2d35-405d-a669-ea4a739dd28c">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Orientation-%20Portrait%20or%20Landscape.html) is designed to change the background color of the body based on the orientation of the viewport.

### Explanation of Each Line

1. The `body` style rule sets the default background color of the body.
   ```css
   body {
     background-color: lightgreen;
   }
   ```

2. The `@media only screen and (orientation: landscape)` is a media query that changes the background color of the body when the viewport is in landscape orientation.
   ```css
   @media only screen and (orientation: landscape) {
     body {
       background-color: lightblue;
     }
   }
   ```

3. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
   ```html
   <p>Your text here</p>
   ```

## Responsive Four Column Layout with Flex.html

<img width="546" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/21293249-4a68-431d-a52c-e7ef35030f0d">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Responsive%20Four%20Column%20Layout%20with%20Flex.html) is designed to create a responsive four column layout using Flexbox.

### Explanation of Each Line

1. The `.row` style rule sets the display property to `flex` and allows the flex items to wrap as needed with `flex-wrap: wrap;`.
   ```css
   .row {
     display: flex;
     flex-wrap: wrap;
   }
   ```

2. The `.column` style rule sets the flex property to `25%` and adds padding of `20px`.
   ```css
   .column {
     flex: 25%;
     padding: 20px;
   }
   ```

3. The `@media screen and (max-width: 992px)` is a media query that changes the flex property to `50%` for screen sizes 992px and narrower.
   ```css
   @media screen and (max-width: 992px) {
     .column {
       flex: 50%;
     }
   }
   ```

4. The `@media screen and (max-width: 600px)` is a media query that changes the flex direction to `column` for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     .row {
       flex-direction: column;
     }
   }
   ```

5. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

6. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
    ```html
    <p>Your text here</p>
    ```

7. The `<div class="row">` tag is the container for the flex items.

8. The `<div class="column" style="background-color: #aaa">` tags are the flex items with different background colors.
    ```html
    <div class="column" style="background-color: #aaa">
      <h2>Column 1</h2>
      <p>Some text..</p>
    </div>
    ```

## Responsive Four Column Layout.html

<img width="693" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/c046a28c-d9af-46b4-b0a7-1c9fbd20e211">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Responsive%20Four%20Column%20Layout.html) is designed to create a responsive four column layout using CSS floats.

### Explanation of Each Line

1. The `.column` style rule sets the width property to `25%`, adds padding of `20px`, and makes the column float to the left.
   ```css
   .column {
     float: left;
     width: 25%;
     padding: 20px;
   }
   ```

2. The `.row:after` style rule clears the float after the columns, which prevents the row from collapsing.
   ```css
   .row:after {
     content: "";
     display: table;
     clear: both;
   }
   ```

3. The `@media screen and (max-width: 992px)` is a media query that changes the width property to `50%` for screen sizes 992px and narrower.
   ```css
   @media screen and (max-width: 992px) {
     .column {
       width: 50%;
     }
   }
   ```

4. The `@media screen and (max-width: 600px)` is a media query that changes the width property to `100%` for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     .column {
       width: 100%;
     }
   }
   ```

5. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

6. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
    ```html
    <p>Your text here</p>
    ```

7. The `<div class="row">` tag is the container for the columns.

8. The `<div class="column" style="background-color: #aaa">` tags are the columns with different background colors.
    ```html
    <div class="column" style="background-color: #aaa">
      <h2>Column 1</h2>
      <p>Some text..</p>
    </div>
    ```

## Responsive Image Grid.html

<img width="947" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/b51bb803-39d6-43a3-b114-12b58259ec11">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Responsive%20Image%20Grid.html) is designed to create a responsive image grid layout using CSS flexbox.

### Explanation of Each Line

1. The `body` style rule sets the default margin and font of the body.
   ```css
   body {
     margin: 0;
     font-family: Arial;
   }
   ```

2. The `.header` style rule styles the header with a specific text alignment and padding.
   ```css
   .header {
     text-align: center;
     padding: 32px;
   }
   ```

3. The `.row` style rule sets the display property to `flex`, allows the flex items to wrap as needed with `flex-wrap: wrap;`, and adds padding.
   ```css
   .row {
     display: flex;
     flex-wrap: wrap;
     padding: 0 4px;
   }
   ```

4. The `.column` style rule sets the flex property to `25%`, the maximum width to `25%`, and adds padding.
   ```css
   .column {
     flex: 25%;
     max-width: 25%;
     padding: 0 4px;
   }
   ```

5. The `.column img` style rule adds a top margin to the images and aligns them in the middle.
   ```css
   .column img {
     margin-top: 8px;
     vertical-align: middle;
   }
   ```

6. The `@media screen and (max-width: 800px)` is a media query that changes the flex property and the maximum width to `50%` for screen sizes 800px and narrower.
    ```css
    @media screen and (max-width: 800px) {
      .column {
        flex: 50%;
        max-width: 50%;
      }
    }
    ```

7. The `@media screen and (max-width: 600px)` is a media query that changes the flex property and the maximum width to `100%` for screen sizes 600px and narrower.
    ```css
    @media screen and (max-width: 600px) {
      .column {
        flex: 100%;
        max-width: 100%;
      }
    }
    ```

8. The `<h2>` tag provides a heading for the webpage.
    ```html
    <h2>Your Heading Here</h2>
    ```

9. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
    ```html
    <p>Your text here</p>
    ```

10. The `<div class="row">` tag is the container for the columns.

11. The `<div class="column">` tags are the columns with different background colors.
    ```html
    <div class="column">
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
      <img src="https://via.placeholder.com/400x300" style="width: 100%" />
    </div>
    ```

## Responsive Navigation Menu.html


<img width="569" alt="image" src="https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/aab7113b-453c-4b6e-9856-ad08071d1274">

The provided [HTML code](https://github.com/GZ30eee/HTML-CSS-Programms/blob/master/Media%20Queries/Examples/Responsive%20Navigation%20Menu.html) is designed to create a responsive navigation menu using CSS.

### 

1. The `.topnav` style rule styles the top navigation bar with a specific background color.
   ```css
   .topnav {
     overflow: hidden;
     background-color: #333;
   }
   ```

2. The `.topnav a` style rule styles the topnav links with a specific color, padding, text decoration, and text alignment.
   ```css
   .topnav a {
     float: left;
     display: block;
     color: #f2f2f2;
     text-align: center;
     padding: 14px 16px;
     text-decoration: none;
   }
   ```

3. The `.topnav a:hover` style rule changes the background color and text color of the topnav links when hovered over.
   ```css
   .topnav a:hover {
     background-color: #ddd;
     color: black;
   }
   ```

4. The `@media screen and (max-width: 600px)` is a media query that changes the float property to `none` and the width property to `100%` for screen sizes 600px and narrower.
   ```css
   @media screen and (max-width: 600px) {
     .topnav a {
       float: none;
       width: 100%;
     }
   }
   ```

5. The `<h2>` tag provides a heading for the webpage.
   ```html
   <h2>Your Heading Here</h2>
   ```

6. The `<p>` tag contains instructions for the user to resize the browser window to see the effect of the media query.
    ```html
    <p>Your text here</p>
    ```

7. The `<div class="topnav">` tag is the container for the topnav links.

8. The `<a href="#">Link</a>` tags are the topnav links.
    ```html
    <a href="#">Link</a>
    ```



