### CSS transformations allow you to change the shape, size, and position of an element in a 2D or 3D space. Transformations can rotate, scale, translate (move), or skew an element, and they can be combined to create complex effects.
* `selector {
    transition: property duration timing-function delay;
}
* property: The CSS property you want to animate (e.g., background-color, opacity, etc.). You can use all to apply the transition to all properties.
* duration: The length of time the transition takes (e.g., 0.5s, 2s).
* timing-function: How the intermediate property values are calculated (e.g., ease, linear, ease-in, ease-out, cubic-bezier(...)).
* delay: The time to wait before starting the transition (e.g., 0s, 1s).
##### Example
###### Here’s a simple example of a button that changes color when hovered over:
`.button {
    background-color: blue;
    color: white;
    padding: 10px 20px;
    border: none;
    transition: background-color 0.3s ease, transform 0.3s ease;
}`

`.button:hover {
    background-color: green;
    transform: scale(1.1);
}
`
