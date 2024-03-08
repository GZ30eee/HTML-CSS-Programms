![image](https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/dd35384e-7b95-4aaa-9146-558ae0c2ae09)


# Media Queries in CSS

Media queries in CSS allow you to tailor your styles based on the characteristics of the user's device or viewport. They're particularly useful for creating responsive designs that adapt to different screen sizes and orientations. Let's dive into the details:

1. **What Are Media Queries?**
   - **Media queries** are conditional statements that apply specific styles based on the user's environment.
   - They allow you to target different media types (such as screens, print, or handheld devices) and specific features (like screen width, height, or orientation).

2. **Commonly Used Media Types:**
   - `all`: Applies to all media types.
   - `print`: Used for print preview mode.
   - `screen`: Applies to computer screens, tablets, smartphones, etc.

3. **Common Media Features:**
   - `width`: Width of the viewport (including scrollbar).
   - `height`: Height of the viewport (including scrollbar).
   - `orientation`: Orientation of the viewport (landscape or portrait).
   - `min-width` and `max-width`: Specify minimum and maximum viewport widths.
   - `min-height` and `max-height`: Specify minimum and maximum viewport heights.

4. **Media Query Syntax:**
   - A media query consists of a **media type** (optional) and one or more **media features**.
   - Example:
     ```css
     @media screen and (min-width: 480px) {
       /* Styles applied when viewport width is 480px or wider */
       body {
         background-color: lightgreen;
       }
     }
     ```

5. **Keywords:**
   - `not`: Inverts the meaning of the entire media query.
   - `only`: Prevents older browsers without media query support from applying specified styles (modern browsers ignore it).
   - `and`: Combines a media type with one or more media features.

6. **Linking Different Stylesheets:**
   - You can link different stylesheets for various media and viewport widths:
     ```html
     <link rel="stylesheet" media="print" href="print.css">
     <link rel="stylesheet" media="screen" href="screen.css">
     <link rel="stylesheet" media="screen and (min-width: 480px)" href="example1.css">
     <link rel="stylesheet" media="screen and (min-width: 701px) and (max-width: 900px)" href="example2.css">
     ```

Remember, media queries empower you to create flexible and adaptive designs that enhance the user experience across different devices! 🌟

For more detailed information, you can refer to the W3Schools guide on CSS media queries or the MDN Web Docs. Happy styling! 🎨