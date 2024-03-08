![image](https://github.com/GZ30eee/HTML-CSS-Programms/assets/130747789/bb3ed52c-d76a-4aa3-85fe-b67352f05703)

## CSS Animations

### Introduction
CSS animations allow you to create dynamic and visually appealing effects on your web pages. They enhance user experience by adding movement and interactivity. Animations can be applied to various elements, such as text, images, buttons, and more.

### Key Animation Properties

1. **@keyframes**:
   - The `@keyframes` rule defines a set of keyframes for an animation sequence.
   - It specifies how an element should change over time by defining styles at specific points during the animation.
   - Example:
     ```css
     @keyframes slide-in {
       0% { opacity: 0; transform: translateX(-100%); }
       100% { opacity: 1; transform: translateX(0); }
     }
     ```

2. **animation-name**:
   - Specifies the name of the `@keyframes` describing the animation.
   - Example:
     ```css
     .my-element {
       animation-name: slide-in;
     }
     ```

3. **animation-duration**:
   - Determines the time duration it takes for the animation to complete one cycle.
   - Example:
     ```css
     .my-element {
       animation-duration: 3s;
     }
     ```

4. **animation-delay**:
   - Specifies the delay before the animation starts.
   - Example:
     ```css
     .my-element {
       animation-delay: 1s;
     }
     ```

5. **animation-iteration-count**:
   - Sets the number of times the animation is played (e.g., `infinite` for continuous looping).
   - Example:
     ```css
     .my-element {
       animation-iteration-count: 2;
     }
     ```

6. **animation-direction**:
   - Determines the direction in which the animation is played (`normal`, `reverse`, `alternate`, or `alternate-reverse`).
   - Example:
     ```css
     .my-element {
       animation-direction: alternate;
     }
     ```

7. **animation-timing-function**:
   - Specifies how animations transition through keyframes (e.g., `ease`, `linear`, `ease-in-out`).
   - Example:
     ```css
     .my-element {
       animation-timing-function: ease-in;
     }
     ```

8. **animation-fill-mode**:
   - Determines how styles are applied to the animation's target before and after execution (`forwards`, `backwards`, `both`, or `none`).
   - Example:
     ```css
     .my-element {
       animation-fill-mode: forwards;
     }
     ```

9. **animation-play-state**:
   - Controls whether the animation is playing or paused (`running` or `paused`).
   - Example:
     ```css
     .my-element {
       animation-play-state: running;
     }
     ```

### Example Usage
Suppose you want to slide an element in from the left with a 3-second duration, a 1-second delay, and an ease-in timing function. You can use the following CSS:

```css
.my-element {
  animation: slide-in 3s ease-in 1s;
}
```

Remember that the order of values within the `animation` property matters. The first value is assigned to `animation-duration`, and the second one to `animation-delay`.

Feel free to experiment with these properties to create captivating animations for your web projects! 🚀

Happy animating! 🎨✨
