# CSS property: transform

- [CSS property: transform](#css-property-transform)
  - [Work - What it does?](#work---what-it-does)
    - [🙋🏻‍♂️ What type of element is transformable?](#️-what-type-of-element-is-transformable)
    - [🙋🏻‍♂️ What value it accept?](#️-what-value-it-accept)
    - [x axis and y axis](#x-axis-and-y-axis)
  - [transform:transform-fucntions()](#transformtransform-fucntions)
    - [transform:translate()](#transformtranslate)
      - [Variations of translate()](#variations-of-translate)
        - [Shorthand property for translate](#shorthand-property-for-translate)
      - [Example](#example)
    - [transform:skew()](#transformskew)
      - [variations of skew](#variations-of-skew)
        - [shorthand for skew property](#shorthand-for-skew-property)
      - [Exmaple](#exmaple)
    - [transform:scale()](#transformscale)
      - [Variantions of scale()](#variantions-of-scale)
        - [Shorthand property for scale](#shorthand-property-for-scale)
      - [scale(value)](#scalevalue)
      - [Example with scale()](#example-with-scale)
    - [transform:rotate()](#transformrotate)
      - [shorthand perproty for rotate()](#shorthand-perproty-for-rotate)
      - [rotate(value)](#rotatevalue)
      - [Example for rotate()](#example-for-rotate)
  - [Example For all css transform](#example-for-all-css-transform)
    - [Multiple Values](#multiple-values)

## Work - What it does?

**transform:** property applies a 2D or 3D transformation to an element.
Only transformable elements can be transformed.

### 🙋🏻‍♂️ What type of element is transformable?

Only the box model positioned elements can be transformed.

### 🙋🏻‍♂️ What value it accept?

It accept *none* value or from the list of *transform functions*.
There are three variations of CSS Transform properties in 2D.

1. transform: transform_functionX(x);
2. transform: transform_functionY(y);
3. transform : transform_function(x,y);

> 📝 Notes:
>
> - x and y can be negative or positive values
> - 3D includes the Z-axis
>   - X is the width,
>   - Y is the height, and
>   - Z gives the depth of the screen

Some *transform-fuctions()* property are as follows:

### x axis and y axis

The most common is the Cartesian coordinate system, although homogeneous coordinates are also sometimes used.
![cartesian](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/coord_in_r2.png)

## transform:transform-fucntions()

- translate(x,y)
- skew(x-angle,y-angle)
- scale(x,y)
- rotate(angle)

### transform:translate()

Translate property changes the position left/right and up/down of the element on the page based on the given X (horizontal) and Y (vertical) axes parameters

#### Variations of translate()

- translateX(x) :  change position, using only the value for the X-axis
- translateY(y) : change position, using only the value for the Y-axis
- translateZ(z) : change pos in a 3D space, using only the value for the Z-axis

##### Shorthand property for translate

- translate(x,y) : work in 2D
- translate3d(x,y,z); : work in 3D

#### Example

- [translate.html](./extra-work/translate.html)
- [translate.css](./extra-work/translate.css)
- [CodePen](https://codepen.io/ujjawal-singh/pen/MWqXQqV)

### transform:skew()

Skew tilts the element towards a direction based on the provided parameters to its X and Y axes.

- for x +ive value tilts it towards the right and -ive tilts it towards the left.
- for  y tilts it downward and -ive  tilts it upward.

#### variations of skew

- skewX(x) : Defines a 2D skew transformation along the X-axis
- skewY(y) : Defines a 2D skew transformation along the Y-axis

##### shorthand for skew property

- skew(x,y) : Defines a 2D skew transformation along the X- and the Y-axis

#### Exmaple

- [skew.html](./extra-work/sekw.html)
- [skew.css](./extra-work/sekw.css)
- [CodePen](https://codepen.io/ujjawal-singh/pen/QWVxQZM)

> 📝 If you skew an element, it will also skew all the children existing inside the element. If we need to maintain the original angle of a child element, we will have to use the opposite value of skew to keep it original.

### transform:scale()

- `scale()` increase or decrease the size of an HTML element.
- The +ive value increases the size in the X or Y direction
- The -ive value increases the size in the X or Y direction

#### Variantions of scale()

- scaleX();
- scaleY();
- scaleZ(); for 3D

##### Shorthand property for scale

- scale(); for 2d, can accept either one or two values (x ,y)
- scale3D() for 3d, can accpet either one, two or three values (x,y,z)

#### scale(value)

- 1 indicate the default size of the element
- <1 decrease the size
- >1 increase the size

> if we mention x or y in -ive it will reverse the text.

#### Example with scale()

- [Scale.html](./extra-work/scale.html)
- [Scale.css](./extra-work/scale.css)
- [CodePen](https://codepen.io/ujjawal-singh/pen/ExeRQdO)

### transform:rotate()

- `rotate()` can rotate an element in the clockwise or anticlockwise direction based on a specified number of degrees.
- +ive degree rotates the element in the anticlockwise.
- -ive degree rotates the element in the clockwise direction.
- we can perform 360 deg roation.

- rotateX(angle); : Rotates an element about the x-axis in three-dimensional space.
- rotateY(angle); : Rotates an element about the y-axis in three-dimensional space.
- rotateZ(angle); : Rotates an element about the z-axis in three-dimensional space.

#### shorthand perproty for rotate()

- rotate(angle) for 2d rotaton
- rotate3d(x,y,z,angle) for 3d rotation

#### rotate(value)

- deg (degree)
- grad (gradin)

#### Example for rotate()

- [rotate.html](./extra-work/rotate.html)
- [rotate.css](./extra-work/rotate.css)
- [Codepen](https://codepen.io/ujjawal-singh/pen/MWqXzQL)

## Example For all css transform

<https://www.w3schools.com/cssref/playdemo.php?filename=playcss_transform>

### Multiple Values

With a space-separated list you can add multiple values to the transform property:

```CSS
transform: scale(20) skew(-20deg);
```
