# CSS Pseudo-classes

A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, `:hover` can be used to change the style of a button when the user's pointer hovers over it.

Pseudo-classes let you apply a style to an element not only in relation to the content of the document tree, but also in relation to external factors like the history of the navigator (`:visited`, for example), the status of its content (like `:checked` on certain form elements), or the position of the mouse (like `:hover`, which lets you know if the mouse is over an element or not).

Here are some examples of pseudo-classes:

- `:hover`: Selects an element when the user's pointer is hovering over it.
- `:visited`: Selects links that the user has already visited.
- `:link`: Selects all unvisited links.
- `:active`: Selects a link at the moment it is being activated (clicked or tapped).
- `:focus`: Selects an element that currently has focus.
- `:first-child`: Matches a specified element that is the first child of another element.
- `:lang`: Allows you to define special rules for different languages.

The syntax of pseudo-classes is `selector:pseudo-class { property: value; }`. For example, `button:hover { color: blue; }` changes the color of a button to blue when the user's pointer hovers over it.

## :link
The `:link` pseudo-class in CSS selects all unvisited links.

Example:
```css
a:link {
  color: blue;
}
```
This will change the color of all unvisited links to blue.

## :active
The `:active` pseudo-class in CSS selects a link at the moment it is being activated (clicked or tapped).

Example:
```css
a:active {
  color: red;
}
```
This will change the color of the link to red at the moment it is clicked or tapped.

## :focus
The `:focus` pseudo-class in CSS selects an element that currently has focus.

Example:
```css
input:focus {
  border: 3px solid green;
}
```
This will add a green border around an input field when it has focus.

## :first-child
The `:first-child` pseudo-class in CSS matches a specified element that is the first child of another element.

Example:
```css
p:first-child {
  color: orange;
}
```
This will change the color of the first paragraph that is a child of its parent element to orange.

## :lang
The `:lang` pseudo-class in CSS allows you to define special rules for different languages.

Example:
```css
p:lang(it) {
  color: green;
}
```
This will change the color of the text to green in a paragraph that is marked with the Italian language (`<p lang="it">Ciao, mondo!</p>`).