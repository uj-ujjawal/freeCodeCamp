# CSS COLOR MARKERS

- [CSS COLOR MARKERS](#css-color-markers)
  - [STEP 1](#step-1)
  - [STEP 2](#step-2)
  - [STEP 3](#step-3)
  - [STEP 4](#step-4)
  - [STEP 5](#step-5)
  - [STEP 6](#step-6)
  - [STEP 7](#step-7)
  - [STEP 8](#step-8)
  - [STEP 9](#step-9)
  - [STEP 10](#step-10)
  - [STEP 11](#step-11)
  - [STEP 12](#step-12)
  - [STEP 13](#step-13)
  - [STEP 14](#step-14)
  - [STEP 15](#step-15)
  - [STEP 16](#step-16)
  - [STEP 17](#step-17)
  - [STEP 18](#step-18)
  - [STEP 19](#step-19)
  - [STEP 20](#step-20)
  - [STEP 21](#step-21)
  - [STEP 22](#step-22)
  - [STEP 23](#step-23)
  - [STEP 24](#step-24)
  - [STEP 25](#step-25)
  - [STEP 26](#step-26)
  - [STEP 27](#step-27)
  - [STEP 28](#step-28)
  - [STEP 29](#step-29)
  - [STEP 30](#step-30)
  - [STEP 31](#step-31)
  - [STEP 32](#step-32)
  - [STEP 33](#step-33)
  - [STEP 34](#step-34)
  - [STEP 35](#step-35)
  - [STEP 36](#step-36)
  - [STEP 37](#step-37)
  - [STEP 38](#step-38)
  - [STEP 39](#step-39)
  - [STEP 40](#step-40)
  - [STEP 41](#step-41)
  - [STEP 42](#step-42)
  - [STEP 43](#step-43)
  - [STEP 44](#step-44)
  - [STEP 45](#step-45)
  - [STEP 46](#step-46)
  - [STEP 47](#step-47)
  - [STEP 48](#step-48)
  - [STEP 49](#step-49)
  - [STEP 50](#step-50)
  - [STEP 51](#step-51)
  - [STEP 52](#step-52)
  - [STEP 53](#step-53)
  - [Step 54](#step-54)
  - [STEP 55](#step-55)
  - [STEP 56](#step-56)
  - [STEP 57](#step-57)
  - [STEP 58](#step-58)
  - [STEP 59](#step-59)
  - [STEP 60](#step-60)
  - [STEP 61](#step-61)
  - [STEP 62](#step-62)
  - [STEP 63](#step-63)
  - [STEP 64](#step-64)
  - [STEP 65](#step-65)
  - [STEP 66](#step-66)
  - [STEP 67](#step-67)
  - [STEP 68](#step-68)
  - [STEP 69](#step-69)
  - [STEP 70](#step-70)
  - [STPE 71](#stpe-71)
  - [STEP 72](#step-72)
  - [STEP 73](#step-73)
  - [STEP 74](#step-74)
  - [STEP 75](#step-75)
  - [STEO 76](#steo-76)
  - [STEP 77](#step-77)
  - [STEP 78](#step-78)
  - [STEP 79](#step-79)
  - [STEP 80](#step-80)
  - [STEP 81](#step-81)
  - [STEP 82](#step-82)
  - [STEP 83](#step-83)
  - [STEP 84](#step-84)
  - [STEP 85](#step-85)
  - [STEP 86](#step-86)
  - [STEP 87](#step-87)
  - [STEP 88](#step-88)
  - [STEP 89](#step-89)
  - [STEP 90](#step-90)
  - [STEP 91](#step-91)
  - [STEP 92](#step-92)
  - [STEP 93](#step-93)
  - [STEP 94](#step-94)


## STEP 1

```HTML
<!DOCTYPE html>
<html lang="en"></html>
```

## STEP 2

```HTML
<head></head> 
<body></body>
```

## STEP 3

```HTML
<head>
  <title>Colored Markers</title>
</head>
```

## STEP 4

```HTML
<meta charset="utf-8"/>
```

## STEP 5

```HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
```

## STEP 6

```HTML
<h1>CSS Color Markers</h1>
```

## STEP 7

```HTML
<link rel="stylesheet" href="styles.css">
```

## STEP 8

```CSS
h1{
  text-align:center;
}
```

## STEP 9

```HTML
<body>
  <h1>CSS Color Markers</h1>
  <div class="container"></div>
</body>
```

## STEP 10

```HTML
<body>
  <h1>CSS Color Markers</h1>
  <div class="container">
    <div class="marker"></div>
  </div>
</body>
```

## STEP 11

```CSS
.marker{
  background-color:red;
}
```

## STEP 12

```CSS
.marker {
  background-color: red;
  /* !step12 */
  width:200px;
  height:25px;
  /* !eos */
}
```

## STEP 13

```CSS
.marker {
  width: 200px;
  height: 25px;
  background-color: red;
  margin:auto; /* !step13 */
}
```

## STEP 14

```HTML
<div class="container">
    <div class="marker">
    </div>
    <div class="marker">
    </div>
    <div class="marker">
    </div>
  </div>
```

## STEP 15

```CSS
.marker {
  width: 200px;
  height: 25px;
  background-color: red;
  margin: 10px auto; /* !step15 */
}
```

## STEP 16

```HTML
  <div class="marker one">
  </div>
  <div class="marker one">
  </div>
  <div class="marker one">
  </div>
```

## STEP 17

```CSS
.marker {
  width: 200px;
  height: 25px;
  /* background-color: red; */ /* !steps17 */
  margin: 10px auto;
}
```

## STEP 18

```CSS
.one {
  background-color: red;
}
```

## STEP 19

```HTML
<div class="marker one">
</div>
<div class="marker two">
</div>
<div class="marker three">
</div>
```

## STEP 20

```CSS
.two{
  background-color:green;
}
.three{
  background-color:blue;
}
```

## STEP 21

```CSS
.container{
  background-color:rgb(0,0,0);
}
```

## STEP 22

```CSS
.one {
  background-color: rgb(255 0 0);
}
```

## STEP 23

```CSS
.two {
  background-color: rgb(0 255 0);
}

.three {
  background-color: rgb(0 0 255);
}
```

## STEP 24

```CSS
.two {
  background-color: rgb(0, 127, 0);
}
```

## STEP 25

```CSS
.container {
  background-color: rgb(0, 0, 0);
  padding:10px 0; /* !step25 */
}
```

## STEP 26

```CSS
.two {
  background-color: rgb(0, 255, 0); /* !step26 */
}
```

## STEP 27

```CSS
.container {
  background-color: rgb(255, 255, 255); /* * */
  padding: 10px 0;
}
```

## STEP 28

**Secondry Color** are the colors you get when you combine primary colors.

```CSS
.one {
  background-color: rgb(255, 255, 0);
}
```

## STEP 29

```CSS
.two {
  background-color: rgb(0, 255, 255);
}
```

## STEP 30

```CSS
.three {
  background-color: rgb(255, 0, 255);
}
```

## STEP 31

[Tertiary colors](https://en.wikipedia.org/wiki/Tertiary_color) or intermediate color is a color made by mixing full saturation of one primary color with half saturation of another primary color and none of a third primary color.

![Tertiary Colors 240|240](https://upload.wikimedia.org/wikipedia/commons/a/ab/RBG_color_wheel.svg)

```CSS
.one {
  background-color: rgb(255, 127, 0);
}
```

## STEP 32

```CSS
.two {
  background-color: rgb(0, 255, 127);
}
```

## STEP 33

```CSS
.three {
  background-color: rgb(127, 0, 255);
}
```

## STEP 34

```CSS
.one {
  background-color: rgb(127, 255, 0);
}

.two {
  background-color: rgb(0, 127, 255);
}

.three {
  background-color: rgb(255, 0, 127);
}
```

## STEP 35

```CSS
.one {
  background-color: rgb(0, 0, 0);
}

.two {
  background-color: rgb(0, 0, 0);
}

.three {
  background-color: rgb(0, 0, 0);
}
```

## STEP 36

```CSS
.one {
  background-color: rgb(255, 0, 0);
}

.two {
  background-color: rgb(0, 255, 255);
}
```

## STEP 37

```CSS
h1 {
  text-align: center;
  background-color:rgb(0, 255, 255); /* CYAN */
}
```

## STEP 38

```CSS
.one {
  background-color: rgb(0, 0, 0);
}

.two {
  background-color: rgb(255, 0, 0);
}
```

## STEP 39

```CSS
.two {
  background-color: rgb(0, 0, 0);
}
```

## STEP 40

```CSS
h1 {
  text-align: center;
}
```

## STEP 41

```html
<div class="marker red">
</div>
<div class="marker two">
</div>
<div class="marker three">
</div>
```

## STEP 42

```CSS
.red {
  background-color: rgb(0, 0, 0);
}

.two {
  background-color: rgb(0, 0, 0);
}

.three {
  background-color: rgb(0, 0, 0);
}
```

## STEP 43

```CSS
.red {
  background-color: rgb(255, 0, 0);
}

.two {
  background-color: rgb(0, 0, 0);
}

.three {
  background-color: rgb(0, 0, 0);
}
```

## STEP 44

```html
<div class="marker red">
</div>
<div class="marker green">
</div>
<div class="marker blue">
</div>
```

## STEP 45

```CSS
.red {
  background-color: rgb(255, 0, 0);
}

.green {
  background-color: rgb(0, 0, 0);
}

.blue {
  background-color: rgb(0, 0, 0);
}
```

## STEP 46

```CSS
.green {
  background-color: #00FF00;
}
```

## STEP 47

```CSS
.green {
  background-color: #007F00;
}
```

## STEP 48

- The HSL color model -> H(Hue), S(Saturation) & L(Lightness).
- It accepts 3 values:
  - a number from 0 to 360 for hue,
  - a percentage from 0 to 100 for saturation,
  - and a percentage from 0 to 100 for lightness.
- imagine a [color wheel](https://developer.mozilla.org/en-US/docs/Glossary/Color_wheel),
  - the hue red is at 0 degrees,
  - green is at 120 degrees,
  - and blue is at 240 degrees.

```CSS
.blue {
  background-color: hsl(240, 100%, 50%);
}
```

## STEP 49

- can also use a color transition, or gradient, on an element.
- linear-gradient function actually creates an image element.
- **background porperty** accept image as value.

```CSS
.red {
  background: rgb(255, 0, 0);
}
```

## STEP 50

- liner-gradient syntax: `linear-gradient(gradientDirection, color1, color2, ...);`
- color1 and color2 are color arguments, which are the colors that will be used in the transition itself.
- These can be any type of color,  hex, rgb, or hsl.

```CSS
.red {
  background: linear-gradient(90deg);
}
```

## STEP 51

```CSS
.red {
  background: linear-gradient(90deg, rgb(255,0,0));
}
```

## STEP 52

```CSS
.red {
  background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0,255,0));
}
```

## STEP 53

```CSS
.red {
  background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0),rgb(0,0,255));
}
```

## Step 54

**Color-stops** allow you to fine-tune where colors are placed along the gradient line. They are a length unit like px or percentages that follow a color in the linear-gradient function.

```CSS
.red {
  background: linear-gradient(90deg, rgb(255, 0, 0) 75%, rgb(0, 255, 0), rgb(0, 0, 255));
}
```

## STEP 55

```CSS
.red {
  background: linear-gradient(180deg, rgb(255, 0, 0) 75%, rgb(0, 255, 0), rgb(0, 0, 255));
}
```

## STEP 56

```CSS
.red {
  background: linear-gradient(180deg, rgb(255, 0, 0) 0%, rgb(0, 255, 0) 50%, rgb(0, 0, 255) 100%);
}
```

## STEP 57

```CSS
.red {
  background: linear-gradient(180deg, rgb(122, 74, 14) 0%, rgb(0, 255, 0) 50%, rgb(0, 0, 255) 100%);
}
```

## STEP 58

```CSS
.red {
  background: linear-gradient(180deg, rgb(122, 74, 14) 0%, rgb(245, 62, 113) 50%, rgb(0, 0, 255) 100%);
}
```

## STEP 59

```CSS
.red {
  background: linear-gradient(180deg, rgb(122, 74, 14) 0%, rgb(245, 62, 113) 50%, rgb(162, 27, 27) 100%);
}
```

## STEP 60

```CSS
.green {
  background: #007F00;
}
```

## STEP 61

```CSS
.green {
  background: linear-gradient(180deg, #55680D);
}
```

## STEP 62

```CSS
.green {
  background: linear-gradient(180deg, #55680D, #71F53E);
}
```

## STEP 63

```CSS
.green {
  background: linear-gradient(180deg, #55680D, #71F53E, #116C31);
}
```

## STEP 64

The linear-gradient function automatically calculates these values for you, and places colors evenly along the gradient line by default.

```CSS
.red {
  background: linear-gradient(180deg, rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
}
```

## STEP 65

If no gradientDirection argument is provided to the linear-gradient function, it arranges colors from top to bottom, or along a 180 degree line, by default.

```CSS
.red {
  background: linear-gradient( rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
}

.green {
  background: linear-gradient( #55680D, #71F53E, #116C31);
}
```

## STEP 66

```CSS
.blue {
  background: hsl(240, 100%, 50%);
}
```

## STEP 67

```CSS
.blue {
  background: linear-gradient(hsl(186, 76%, 16%));
}
```

## STEP 68

```CSS
.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%));
}
```

## STEP 69

```CSS
.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
}
```

## STEP 70

```html
<div class="marker red">
  <div class="sleeve"></div>
</div>
```

## STPE 71

```css
.sleeve{
  width:110px;
  height:25px;
}
```

## STEP 72

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color:white;
}
```

## STEP 73

- **Opacity** css-property describes how opaque, or non-transparent
- can control how opaque or transparent an element is.
- With the value 0, or 0%, the element will be completely transparent,
- and at 1.0, or 100%, the element will be completely opaque like it is by default.

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: white;
  opacity:0.5;
}
```

## STEP 74

- **alpha channel** is another way to set the opacity for an element.
- Similar to the *opacity property*, the alpha channel controls how transparent or opaque a color is.

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: white;
}
```

## STEP 75

- To apply alpha chanel, use the rgba function instead of rgb function.

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgb(255, 255, 255, 50%); /* will work Same as background-color: white;
  opacity:0.5; */
}
```

## STEO 76

```html
<div class="marker red">
    <div class="cap"></div>
  <div class="sleeve"></div>
</div>
```

## STEP 77

```CSS
.cap{
  width:60px;
  height:25px;
}
```

## STEP 78

- when two block elements are next to each other, they stack like actual blocks. For example, your marker elements are all stacked on top of each other.
- To position two div elements on the same line, set their display properties to inline-block.

```CSS
.cap, .sleeve{
  display:inline-block;
}
```

## STEP 79

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left-width:10px;
}
```

## STEP 80

- If no color is set for border, black is used by default.

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left-width: 10px;
  border-left-style:solid;
}
```

## STEP 81

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left-width: 10px;
  border-left-style: solid;
  border-left-color:black;
}
```

## STEP 82

- **border-left** is shorthand property
- let us  set the left border's width, style, and color at the same time.

```CSS
/* border-left-width: 10px;
  border-left-style: solid;
  border-left-color: black; */
  border-left:10px solid black; /* equivalent to above three */
```

## STEP 83

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left: 10px double black;
}
```

## STEP 84

```CSS
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left: 10px double rgba(0,0,0, 75%);
}
```

## STEP 85

```html
<div class="marker red">
  <div class="cap"></div>
  <div class="sleeve"></div>
</div>
<div class="marker green">
  <div class="cap"></div>
  <div class="sleeve"></div>
</div>
<div class="marker blue">
  <div class="cap"></div>
  <div class="sleeve"></div>
</div>
```

## STEP 86

- **box-shadow** apply one or more shadows around an element.
- Syntax: `box-shadow: offsetX offsetY color;`
- **offsetX & offsetY**
  - both offsetX and offsetY accept number values in px and other CSS units
  - a positive offsetX value moves the shadow right and a negative value moves it left
  - a positive offsetY value moves the shadow down and a negative value moves it up
- if you want a value of zero (0) for any or both offsetX and offsetY, you don't need to add a unit. Every browser understands that zero means no change.
- The height and width of the shadow is determined by the height and width of the element it's applied to.
- can also use an optional spreadRadius value to spread out the reach of the shadow.

```CSS
.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow:5px 5px red;
}
```

## STEP 87

```CSS
.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow: -5px -5px red;
}
```

## STEP 88

- **blurRadius** optional value for the box-shadow property
- SYNTAX: `box-shadow: offsetX offsetY blurRadius color;`
- If a *blurRadius* value isn't included, it defaults to 0 and produces sharp edges.
- The higher the value of blurRadius, the greater the blurring effect is.

```CSS
.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
  box-shadow:5px 5px 5px green;
}
```

## STEP 89

- **spreadRadius** also an optional value.
- SYNTAX: `box-shadow: offsetX offsetY blurRadius spreadRadius color;`
- spreadRadius default set to 0.

```CSS
.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
  box-shadow:0px 0px 0px 5px blue;
}
```

## STEP 90

```CSS
.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow: 0px 0px 20px 0px red;
}
```

## STEP 91

```CSS
.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
}
```

## STEP 92

```CSS
.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
  box-shadow: 0px 0px 20px 0px green;
}

.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
  box-shadow: 0 0 20px 0px blue;
}
```

## STEP 93

```CSS
.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
  box-shadow: 0 0 20px 0 #3B7E20CC;
}
```

## STEP 94

```CSS
.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
  box-shadow: 0 0 20px 0 hsla(223, 59%, 31%, 0.8);
}
```
