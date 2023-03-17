# Rothko Painting

INFO about Rothko Painting: <https://www.markrothko.org/paintings/>

- [Rothko Painting](#rothko-painting)
  - [Resoruces / MyNotes](#resoruces--mynotes)
  - [1](#1)
  - [2](#2)
  - [3](#3)
  - [4](#4)
  - [5](#5)
  - [6](#6)
  - [7](#7)
  - [8](#8)
  - [9](#9)
  - [10](#10)
  - [11](#11)
  - [12](#12)
  - [13](#13)
  - [14](#14)
  - [15](#15)
  - [16](#16)
  - [17](#17)
  - [18](#18)
  - [19](#19)
  - [20](#20)
  - [21](#21)
  - [22](#22)
  - [23](#23)
  - [24](#24)
  - [25](#25)
  - [26](#26)
  - [27](#27)
  - [28](#28)
  - [29](#29)
  - [30](#30)
  - [31](#31)
  - [32](#32)
  - [33](#33)
  - [34](#34)
  - [35](#35)
  - [36](#36)
  - [37](#37)
  - [38](#38)
  - [39](#39)
  - [40](#40)
  - [41](#41)
  - [42](#42)
  - [43](#43)
  - [44](#44)
  - [45](#45)

## Resoruces / MyNotes

- [Transform Property](./transform.md)
- [Overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)
- [filter](https://developer.mozilla.org/en-US/docs/Web/CSS/filter)
- [box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

## 1

```HTML
<!DOCTYPE html>
<html lang="en">
  <body></body>
</html>
```

## 2

CSS box model, every elelemt contains some space with it and around it that's is space is tereated as BOX and called box model.

BOX model is divided into 4 parts or we can say every eleemen consume space with this for aspect

- content (area that coverd by content)
- padding (space around the content)
- border (like we pur our photo into frame simple every html element sourrended by frame called border) by default it is not visible and set to 0
- margin (space / area consume out side of the frame, imagine we put our photo on wall it we want to put more photos on the we leve some space between them)
<https://media.onsugar.com/files/2011/02/08/0/42/429878/56dd628ebc2d8719_034.JPG>

<https://shottr.cc/s/Swsv/SCR-20230315-ocu>

```HTML
<head>
  <meta charset="utf-8">
  <title>Rothko Painting</title>
</head>
<body>
  <img src="https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-1.png">
</body>
```

## 3

```HTML
<img src="https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-2.png">
```

## 4

**Padding**: content is surrounded by a space called padding.

```HTML
<img src="https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-3.png">
```

## 5

**Margin** is the area outside of the box, and can be used to control the space between other boxes or elements.

```HTML
<!-- img element removed -->
<!--<img src="https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-3.png"> -->
```

## 6

```HTML
<div class="canvas"></div>
```

## 7

```HTML
<link rel="stylesheet" href="styles.css">
```

## 8

```CSS
.canvas{
  width:500px;
}
```

## 9

```CSS
height:600px;
```

## 10

```CSS
background-color:#4d0f00;
```

## 11

```HTMl
<div class="frame">
  <div class="canvas">
  </div>
</div>
```

## 12

```CSS
.frame{
  border: 50px solid black;
}
```

## 13

```CSS
width:500px;
```

## 14

**padding is used to adjust the space inside the conten**t

```CSS
padding:50px;
```

## 15

**Margin is use to adjust the space outside of an element.**

```CSS
margin: 20px auto;
```

## 16

```HTML
<div class="one"></div> 
```

## 17

```CSS
.one{
  width:425px;
}
```

## 18

```CSS
height: 150px;
```

## 19

```CSS
background-color: #efb762;
```

## 20

```CSS
margin:20px auto;
```

## 21

```CSS
padding: 1px;
```

## 22

- `overflow`<https://developer.mozilla.org/en-US/docs/Web/CSS/overflow>

```CSS
overflow:hidden;
```

## 23

```HTMl
<div class="two"></div>
```

## 24

```CSS
.two {
  width: 475px;
}
```

## 25

```CSS
height:200px
```

## 26

```CSS
background-color:#8f0401;
```

## 27

```CSS
margin:auto;
```

## 28

```HTML
<div class="three"></div>
```

## 29

```CSS
.three{
  width:91%;
}
```

## 30

```CSS
height:28%;
```

## 31

```CSS
background-color: #b20403;
```

## 32

```CSS
margin: auto;
```

## 33

```CSS
margin: 0 auto 20px auto;
```

## 34

- [Read more on filter property](https://developer.mozilla.org/en-US/docs/Web/CSS/filter)

```CSS
filter:blur(2px);
```

## 35

```CSS
.one, .two{
  filter:blur(1px);
}
```

## 36

```CSS
filter:blur(2px);
```

## 37

- [Read more on box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

```CSS
box-shadow: 0 0 3px 3px #efb762;
```

## 38

```CSS
box-shadow: 0 0 3px 3px #8f0401;
```

## 39

```CSS
box-shadow: 0 0 5px 5px #b20403;
```

## 40

```CSS
border-radius: 9px;
```

## 41

```CSS
border-radius:8px 10px 8px 10px;
```

## 42

```CSS
border-radius:30px 25px 60px 12px;
```

## 43

**transform:** property applies a 2D or 3D transformation to an element. It takes none value or from the list of transform functions.
[Read More](transform.md)

```CSS
transform:rotate(-0.6deg);
```

## 44

```CSS
transform:rotate(0.4deg);
```

## 45

```CSS
transform:rotate(-0.2deg);
```
