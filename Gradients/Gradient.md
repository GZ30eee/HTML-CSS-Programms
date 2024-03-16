# Gradients in CSS

Gradients are a way of filling an area with a range of colors which smoothly transition into each other. CSS provides two types of gradients: linear and radial.

## Linear Gradients

A linear gradient is defined by an axis—the gradient line—and two or more color-stop points. The starting point of the gradient line is the first color-stop point and the ending point is the last color-stop point.

Syntax:

```css
background-image: linear-gradient(direction, color-stop1, color-stop2, ...);
```

### Direction - Top to Bottom (this is default)

```css
#grad {
  background-image: linear-gradient(red, yellow);
}
```

### Direction - Left to Right

```css
#grad {
  background-image: linear-gradient(to right, red, yellow);
}
```

### Direction - Diagonal

```css
#grad {
  background-image: linear-gradient(to bottom right, red, yellow);
}
```

### Using Angles

If you want more control over the direction of the gradient, you can define an angle, instead of the predefined directions (to bottom, to top, to right, to left, to bottom right, etc.). A value of 0deg is equivalent to "to top". A value of 90deg is equivalent to "to right". A value of 180deg is equivalent to "to bottom".

```css
#grad {
  background-image: linear-gradient(180deg, red, yellow);
}
```

### Using Multiple Color Stops

The following example shows a linear gradient (from top to bottom) with multiple color stops:

```css
#grad {
  background-image: linear-gradient(red, yellow, green);
}
```

The following example shows how to create a linear gradient (from left to right) with the color of the rainbow and some text:

```css
#grad {
  background-image: linear-gradient(
    to right,
    red,
    orange,
    yellow,
    green,
    blue,
    indigo,
    violet
  );
}
```

### Using Transparency

CSS gradients also support transparency, which can be used to create fading effects.

To add transparency, we use the rgba() function to define the color stops. The last parameter in the rgba() function can be a value from 0 to 1, and it defines the transparency of the color: 0 indicates full transparency, 1 indicates full color (no transparency).

The following example shows a linear gradient that starts from the left. It starts fully transparent, transitioning to full color red:

```css
#grad {
  background-image: linear-gradient(
    to right,
    rgba(255, 0, 0, 0),
    rgba(255, 0, 0, 1)
  );
}
```

### Repeating a linear-gradient

```css
#grad {
  background-image: repeating-linear-gradient(red, yellow 10%, green 20%);
}
```

## Radial Gradients

A radial gradient is defined by its center. It starts at a single point and emanates outwards, with colors transitioning smoothly from one point to the next.

Syntax:

```css
background: radial-gradient(
  shape size at position,
  start-color,
  ...,
  last-color
);
```

By default, shape is ellipse, size is farthest-corner, and position is center.

### Radial Gradient - Evenly Spaced Color Stops (this is default)

```css
#grad {
  background-image: radial-gradient(red, yellow, green);
}
```

### Radial Gradient - Differently Spaced Color Stops

```css
#grad {
  background-image: radial-gradient(red 5%, yellow 15%, green 60%);
}
```

### Set Shape

The shape parameter defines the shape. It can take the value circle or ellipse. The default value is ellipse.

```css
#grad {
  background-image: radial-gradient(circle, red, yellow, green);
}
```

### Use of Different Size Keywords

The size parameter defines the size of the gradient. It can take four values:

- closest-side

```css
#grad1 {
  background-image: radial-gradient(
    closest-side at 60% 55%,
    red,
    yellow,
    black
  );
}
```

- farthest-side

```css
#grad1 {
  background-image: radial-gradient(
    farthest-side at 60% 55%,
    red,
    yellow,
    black
  );
}
```

- closest-corner

```css
#grad1 {
  background-image: radial-gradient(
    closest-corner at 60% 55%,
    red,
    yellow,
    black
  );
}
```

- farthest-corner

```css
#grad1 {
  background-image: radial-gradient(
    farthest-corner at 60% 55%,
    red,
    yellow,
    black
  );
}
```

### Repeating a radial-gradient

```css
#grad {
  background-image: repeating-radial-gradient(red, yellow 10%, green 15%);
}
```
