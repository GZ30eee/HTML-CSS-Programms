# Typography in CSS

## 1. Font Family

The `font-family` property is used to specify the typeface that will be used for the text inside an element.

```css
p {
  font-family: Arial, sans-serif;
}
```
In this example, the browser will use Arial if it's available. If it's not, it will use the default sans-serif font.

## 2. Font Size

The `font-size` property is used to specify the size of the text.

```css
p {
  font-size: 20px;
}
```
This will set the font size of the paragraph text to 20 pixels.

## 3. Font Weight

The `font-weight` property is used to specify the weight (or thickness) of the font. The values can be `normal`, `bold`, `bolder`, `lighter`, or `100` to `900` (from thinnest to thickest).

```css
p {
  font-weight: bold;
}
```
This will set the font weight of the paragraph text to bold.

## 4. Text Transform

The `text-transform` property is used to specify the capitalization of the text. The values can be `none`, `capitalize`, `uppercase`, `lowercase`.

```css
p {
  text-transform: uppercase;
}
```
This will transform the paragraph text to uppercase.

## 5. Text Decoration

The `text-decoration` property is used to specify the decoration added to the text. The values can be `none`, `underline`, `overline`, `line-through`, `blink`.

```css
p {
  text-decoration: underline;
}
```
This will add an underline to the paragraph text.

## 6. Line Height

The `line-height` property is used to specify the space between lines.

```css
p {
  line-height: 1.5;
}
```
This will set the space between lines in the paragraph to 1.5 times the size of the font.

## 7. Letter Spacing

The `letter-spacing` property is used to specify the space between letters.

```css
p {
  letter-spacing: 2px;
}
```
This will set the space between letters in the paragraph to 2 pixels.

## 8. Text Align

The `text-align` property is used to specify the horizontal alignment of the text. The values can be `left`, `right`, `center`, `justify`.

```css
p {
  text-align: center;
}
```
This will center the paragraph text.

Remember, you can combine multiple properties to style your text in various ways. For example:

```css
p {
  font-family: Arial, sans-serif;
  font-size: 20px;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: underline;
  line-height: 1.5;
  letter-spacing: 2px;
  text-align: center;
}
```