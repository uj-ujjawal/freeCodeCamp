# Learn Responsive Web Design by Building a Piano

- [Learn Responsive Web Design by Building a Piano](#learn-responsive-web-design-by-building-a-piano)
  - [01](#01)
  - [02](#02)
  - [03](#03)
  - [04](#04)
  - [05](#05)
  - [06](#06)
  - [07](#07)
  - [08](#08)
  - [09](#09)
  - [!10](#10)
  - [11](#11)
  - [12](#12)
  - [13](#13)
  - [14](#14)
  - [15](#15)
  - [16](#16)
  - [17](#17)
  - [!18](#18)
  - [19](#19)
  - [20](#20)
  - [21](#21)
  - [22](#22)
  - [!23](#23)
  - [24](#24)
  - [25](#25)
  - [26](#26)
  - [!27](#27)
  - [28](#28)
  - [29](#29)
  - [30](#30)
  - [31](#31)
  - [32](#32)
  - [33](#33)

## 01

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Piano</title>
</head>
<body>
</body>
</html>
```

## 02

```HTML
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## 03

```HTML
<div id="piano"></div>
```

## 04

```HTML
<div class="keys"></div>
```

## 05

```HTML
<div id="piano">
  <div class="keys">
    <div class="key"></div>
    <div class="key"></div>
    <div class="key"></div>
    <div class="key"></div>
    <div class="key"></div>
    <div class="key"></div>
    <div class="key"></div>
  </div>
</div>
```

## 06

```HTML
<div id="piano">
  <div class="keys">
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key" ></div>
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
  </div>
</div>
```

## 07

```HTML
<div id="piano">
  <div class="keys">
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
    <div class="key black--key"></div>
  </div>
</div>
```

## 08

```HTML
<meta charset="UTF-8" />
<title>Piano</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<link rel="stylesheet" href="./styles.css"> <!-- 08 -->
```

## 09

```CSS
html{
  box-sizing:border-box;
}
```

## !10

Now that you have reset the html box model, you need to pass that on to the elements within as well. To do this, you can set the box-sizing property to inherit, which will tell the targeted elements to use the same value as the parent element.

You will also need to target the pseudo-elements, which are special keywords that follow a selector. The two pseudo-elements you will be using are the ::before and ::after pseudo-elements.

The ::before selector creates a pseudo-element which is the first child of the selected element, while the ::after selector creates a pseudo-element which is the last child of the selected element. These pseudo-elements are often used to create cosmetic content, which you will see later in this project.

```CSS
html {
  box-sizing: border-box;
}
*, ::before, ::after{
  box-sizing: inherit;
}
```

## 11

```CSS
#piano {
  background-color:#00471b;
  width:992px;
  height:290px;
}
```

## 12

```CSS
#piano {
  background-color: #00471b;
  width: 992px;
  height: 290px;
  margin:80px auto;
}
```

## 13

```CSS
.keys{
  background-color:#040404;
  width:949px;
  height:180px;
}
```

## 14

```CSS
.keys {
  background-color: #040404;
  width: 949px;
  height: 180px;
  padding-left:2px;
}
```

## 15

```CSS
#piano {
  background-color: #00471b;
  width: 992px;
  height: 290px;
  margin: 80px auto;
  padding:90px 20px 0 20px;
}
```

## 16

```CSS
.key{
  background-color:#ffffff;
  position:relative;
  width:41px;
  height:175px;
}
```

## 17

```CSS
.key {
  background-color: #ffffff;
  position: relative;
  width: 41px;
  height: 175px;
  margin:2px;
  float:left;
}
```

## !18

```CSS
.key.black--key::after{
  background-color:#1d1e22;
  content:"";
  
}
```

## 19

```CSS
.key.black--key::after {
  background-color: #1d1e22;
  content: "";
  position:absolute;
  left:-18px;
}
```

## 20

```CSS
.key.black--key::after {
  background-color: #1d1e22;
  content: "";
  position: absolute;
  left: -18px;
  width:32px;
  height:100px;
}
```

## 21

```HTML
<div id="piano">
  <img class="logo" src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" alt="freeCodeCamp Logo">
<div class="keys">
```

## 22

```CSS
.logo{
  width:200px;
  position:absolute;
  top:23px;
}
```

## !23

> NOTE : The img element needs its parent to have a position set as a point of reference

```CSS
#piano {
  background-color: #00471b;
  width: 992px;
  height: 290px;
  margin: 80px auto;
  padding: 90px 20px 0 20px;
  position:relative;
}
```

## 24

```CSS
#piano {
  background-color: #00471b;
  width: 992px;
  height: 290px;
  margin: 80px auto;
  padding: 90px 20px 0 20px;
  position: relative;
  border-radius:10px;
}
```

## 25

```CSS
.key {
  background-color: #ffffff;
  position: relative;
  width: 41px;
  height: 175px;
  margin: 2px;
  float: left;
  border-radius:0 0 3px 3px;
}
```

## 26

```CSS
.key.black--key::after {
  background-color: #1d1e22;
  content: "";
  position: absolute;
  left: -18px;
  width: 32px;
  height: 100px;
  border-radius: 0 0 3px 3px;
}
```

## !27

> Note
>
> The @media at-rule, also known as a media query, is used to conditionally apply CSS. Media queries are commonly used to apply CSS based on the viewport width using the max-width and min-width properties.

```CSS
@media (max-width: 768px) {

}
```

## 28

```CSS
@media (max-width: 768px) {
  #piano{
    width:358px;
  }
}
```

## 29

```CSS
@media (max-width: 768px) {
  #piano {
    width: 358px;
  }
  .keys{
    width:318px;
  }
}
```

## 30

```CSS
@media (max-width: 768px) {
  #piano {
    width: 358px;
  }

  .keys {
    width: 318px;
  }

  .logo{
    width:150px;
  }
}
```

## 31

```CSS
.keys {
  background-color: #040404;
  width: 949px;
  height: 180px;
  padding-left: 2px;
  overflow:hidden; /* 31 */
}
```

## 32

```CSS
@media (min-width: 769px) and (max-width: 1199px){
  
}
```

## 33

```CSS
@media (max-width: 1199px) and (min-width: 769px) {
  #piano{
    width:675px;
  }
  .keys{
    width:633px;
  }
}
```
