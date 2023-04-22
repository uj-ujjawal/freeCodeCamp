# Learn CSS Variables by Building a City Skyline

- [Learn CSS Variables by Building a City Skyline](#learn-css-variables-by-building-a-city-skyline)
  - [01](#01)
  - [02](#02)
  - [03](#03)
  - [04](#04)
  - [05](#05)
  - [06](#06)
  - [07](#07)
  - [08](#08)
  - [09](#09)
  - [10](#10)
  - [11](#11)
  - [12](#12)
  - [13](#13)
  - [!14](#14)
  - [!15](#15)
  - [16](#16)
  - [17](#17)
  - [18](#18)
  - [19](#19)
  - [20](#20)
  - [21](#21)
  - [22](#22)
  - [!23](#23)
  - [24](#24)
  - [!25](#25)
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
  - [46](#46)
  - [47](#47)
  - [48](#48)
  - [49](#49)
  - [50](#50)
  - [51](#51)
  - [!52](#52)
  - [53](#53)
  - [54](#54)
  - [55](#55)
  - [56](#56)
  - [57](#57)
  - [58](#58)
  - [59](#59)
  - [60](#60)
  - [61](#61)
  - [62](#62)
  - [63](#63)
  - [64](#64)
  - [65](#65)
  - [66](#66)
  - [67](#67)
  - [68](#68)
  - [69](#69)
  - [70](#70)
  - [71](#71)
  - [72](#72)
  - [73](#73)
  - [74](#74)
  - [75](#75)
  - [76](#76)
  - [77](#77)
  - [78](#78)
  - [79](#79)
  - [80](#80)
  - [81](#81)
  - [82](#82)
  - [83](#83)
  - [84](#84)
  - [85](#85)
  - [86](#86)
  - [87](#87)
  - [88](#88)
  - [89](#89)
  - [90](#90)
  - [91](#91)
  - [92](#92)
  - [93](#93)
  - [94](#94)
  - [95](#95)
  - [96](#96)
  - [97](#97)
  - [98](#98)
  - [99](#99)
  - [100](#100)
  - [101](#101)
  - [102](#102)
  - [103](#103)
  - [104](#104)
  - [105](#105)
  - [106](#106)
  - [107](#107)
  - [108](#108)
  - [109](#109)
  - [110](#110)
- [111](#111)
  - [112](#112)
  - [113](#113)
  - [114](#114)
- [115](#115)
  - [116](#116)
  - [117](#117)
  - [118](#118)

## 01

```HTML
<!DOCTYPE html>
```

## 02

```HTML
<html lang='en'>
</html>
```

## 03

```HTML
<html lang="en">
<head></head>
<body>
</body>  
</html>
```

## 04

```HTML
<head>
    <meta charset="utf-8"/>
    <title>City Skyline</title>
    <link rel="stylesheet" href="styles.css"/>
</head>
```

## 05

```CSS
*{
  border:1px solid black;
}
```

## 06

```CSS
* {
  border: 1px solid black;
  box-sizing:border-box;
}
```

## 07

```CSS
body{
  height:100vh;
  margin:0;
  overflow:hidden;
}

```

## 08

```HTML
<body>
  <div class=background-buildings></div>
</body>
```

## 09

```CSS
.background-buildings{
  width:100%;
  height:100%;
}
```

## 10

```HTML
<div class="background-buildings">
  <div class="bb1"></div>
</div>
```

```CSS
.bb1{
  width:10%;
  height:70%;
}
```

## 11

```HTML
<div class="bb1">
  <div class="bb1a"></div>
  <div class="bb1b"></div>
  <div class="bb1c"></div>
  <div class="bb1d"></div>
</div>
```

## 12

```CSS
.bb1a{
  width:70%;
  height:10%;
}
.bb1b{
  width:80%;
  height:10%;
}

.bb1c{
  width:90%;
  height:10%;
}

.bb1d{
  width:100%;
  height:70%;
}
```

## 13

```CSS
.bb1 {
  width: 10%;
  height: 70%;
  display: flex;
  flex-direction: column;
  align-items: center;
}
```

## !14

In CSS, Variable declarations begin with two dashes (-) and are given a name and a value.
Syntax: `--variable-name:values`

```CSS
.bb1 {
  width: 10%;
  height: 70%;
  display: flex;
  flex-direction: column;
  align-items: center;
  --building-color1:#999;/* 14 */
}
```

## !15

To use a variable, put the variable name in parentheses with var in front of them like this: `var(--variable-name)`

```CSS
.bb1a {
  width: 70%;
  height: 10%;
  background-color: var(--building-color1);/* 13 */
}
```

## 16

```CSS
.bb1b {
  width: 80%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1c {
  width: 90%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1d {
  width: 100%;
  height: 70%;
  background-color: var(--building-color1);
}
```

## 17

```CSS
--building-color1: #aa80ff;
```

## 18

```CSS
<div class="bb2"></div>
<div class="bb3"></div>
<div class="bb4"></div>
```

## 19

```CSS
  .bb2{
    width:10%;
    height:50%;
  }
  .bb3{
    width:10%;
    height:55%;
  }

  .bb4{
    width:11%;
    height:58%;
  }

```

## 20

```CSS
.background-buildings {
  width: 100%;
  height: 100%;
  display:flex;
  justify-content:space-evenly;
  align-items:flex-end;
}
```

## 21

```CSS
<div class="background-buildings">
  <div></div>
  <div></div>
  <div class="bb1">
    <div class="bb1a"></div>
    <div class="bb1b"></div>
    <div class="bb1c"></div>
    <div class="bb1d"></div>
  </div>
  <div class="bb2"></div>
  <div class="bb3"></div>
  <div></div>     
  <div class="bb4"></div>
  <div></div>
  <div></div>
</div>
```

## 22

```CSS
.bb1 {
  width: 10%;
  height: 70%;
  display: flex;
  flex-direction: column;
  align-items: center;
  --building-color1: #aa80ff;
  --building-color2: #66cc99; /* 22 */
}
.bb2 {
  width: 10%;
  height: 50%;
  background-color: var(--building-color2); /* 22 */
}
```

## !23

`var(--variable-name, fallback-value).`

```CSS
.bb2 {
  width: 10%;
  height: 50%;
  background-color: var(--building-color2, green);
}
```

## 24

```CSS

.bb1 {
  width: 10%;
  height: 70%;
  display: flex;
  flex-direction: column;
  align-items: center;
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699; /* 24 */
}
.bb3 {
  width: 10%;
  height: 55%;
   background-color: var(--building-color3, pink); /* 23 */
}
```

## !25

:root selector

```CSS
/* at the top */
:root{
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
}
.bb1 {
  width: 10%;
  height: 70%;
  display: flex;
  flex-direction: column;
  align-items: center;
/*   --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699; */  /* move them to :root */
}

## 26

```CSS
.bb2 {
  width: 10%;
  height: 50%;
  background-color: var(--building-color2); /* 26 */
}

.bb3 {
  width: 10%;
  height: 55%;
  background-color: var(--building-color3); /* 26 */

```

## 27

```CSS
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
}

.bb4 {
  width: 11%;
  height: 58%;
  background-color: var(--building-color4);
}
```

## 28

```HTML
<div class="foreground-buildings"></div>
```

## 29

```CSS
.foreground-buildings{
  width:100%;
  height:100%;
  position:absolute;
  top:0;
}
```

## 30

```HTML
<div class="foreground-buildings">
  <div class="fb1"></div>
  <div class="fb2"></div>
  <div class="fb3"></div>
  <div class="fb4"></div>
  <div class="fb5"></div>
  <div class="fb6"></div>
</div>
```

## 31

```CSS
.fb1 {
  width: 10%;
  height: 60%;
}

.fb2 {
  width: 10%;
  height: 40%;
}

.fb3 {
  width: 10%;
  height: 35%;
}

.fb4 {
  width: 8%;
  height: 45%;
}

.fb5 {
  width: 10%;
  height: 33%;
}

.fb6 {
  width: 9%;
  height: 38%;
}
```

## 32

```CSS
.foreground-buildings {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  display: flex;
  align-items: flex-end;
  justify-content: space-evenly;
}
```

## 33

```CSS
.background-buildings,.foreground-buildings {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: flex-end;
  justify-content: space-evenly;
  position:absolute;
  top:0;
}

.foreground-buildings {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: flex-end;
  justify-content: space-evenly;
}
```

## 34

```CSS
/* .foreground-buildings {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: flex-end;
  justify-content: space-evenly;
} */

/* remove this part  */
```

## 35

```CSS
.fb1 {
  width: 10%;
  height: 60%;
  background-color:var(--building-color4);
}

.fb2 {
  width: 10%;
  height: 40%;
  background-color:var(--building-color3);
}

.fb3 {
  width: 10%;
  height: 35%;
  background-color:var(--building-color1);
}

.fb4 {
  width: 8%;
  height: 45%;
  background-color:var(--building-color1);
}

.fb5 {
  width: 10%;
  height: 33%;
  background-color:var(--building-color2);
}

.fb6 {
  width: 9%;
  height: 38%;
  background-color:var(--building-color3);
}
```

## 36

```CSS
<div class="foreground-buildings">
  <div></div>
  <div></div>
  <div class="fb1"></div>
  <div class="fb2"></div>
  <div></div>
  <div class="fb3"></div>
  <div class="fb4"></div>
  <div class="fb5"></div>
  <div class="fb6"></div>
  <div></div>
  <div></div>
</div>
```

## 37

```CSS
.fb4 {
  width: 8%;
  height: 45%;
  background-color: var(--building-color1);
  position:relative;
  left:10%;
}

.fb5 {
  width: 10%;
  height: 33%;
  background-color: var(--building-color2);
  position:relative;
  right:10%;
}
```

## 38

```CSS
/* BACKGROUND BUILDINGS - "bb" stands for "background building" */

.bb1 {
  width: 10%;
  height: 70%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.bb1a {
  width: 70%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1b {
  width: 80%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1c {
  width: 90%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1d {
  width: 100%;
  height: 70%;
  background-color: var(--building-color1);
}

.bb2 {
  width: 10%;
  height: 50%;
  background-color: var(--building-color2);
}

.bb3 {
  width: 10%;
  height: 55%;
  background-color: var(--building-color3);
}

.bb4 {
  width: 11%;
  height: 58%;
  background-color: var(--building-color4);
}
/* FOREGROUND BUILDINGS - "fb" stands for "foreground building" */
.fb1 {
  width: 10%;
  height: 60%;
  background-color: var(--building-color4);
}
```

## 39

```CSS
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1:black; /* 39 */
}
```

## 40

```CSS
.bb1a {
  width: 70%;
  height: 10%;
  background-color: var(--building-color1);
  background:linear-gradient(var(--building-color1), var(--window-color1));
}
```

## 41

```CSS
.bb1a {
  width: 70%;
  background-color: var(--building-color1);

}

.bb1b {
  width: 80%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1c {
  width: 90%;
  height: 10%;
  background-color: var(--building-color1);
}

.bb1d {
  width: 100%;
  height: 70%;
  background-color: var(--building-color1);
}

.bb1-window{
  height: 10%;
  background: linear-gradient(
      var(--building-color1),
      var(--window-color1)
    );
}
```

## 42

```HTML
<div class="bb1">
  <div class="bb1a bb1-window"></div>
  <div class="bb1b bb1-window"></div>
  <div class="bb1c bb1-window"></div>
  <div class="bb1d"></div>
</div>
```

## 43

```CSS

.bb1a {
  width: 70%;
}

.bb1b {
  width: 80%;
}

.bb1c {
  width: 90%;
}
```

## 44

```CSS
.bb1d {
  width: 100%;
  height: 70%;
  background-color: var(--building-color1);
  background:linear-gradient(orange, var(--building-color1), var(--window-color1));
}
```

## 45

```CSS
.bb1d {
  width: 100%;
  height: 70%;
  background: linear-gradient(
      orange,
      var(--building-color1),
      var(--window-color1)
    );
}
```

## 46

```CSS
.bb1d {
  width: 100%;
  height: 70%;
  background: linear-gradient(
      orange,
      var(--building-color1) 80%,
      var(--window-color1)
    );
}
```

## 47

```CSS
.bb1d {
  width: 100%;
  height: 70%;
  background: linear-gradient(
      var(--building-color1) 50%,
      var(--window-color1)
    );
}
```

## 48

```CSS
<div class="bb2">
  <div class="bb2a"></div>
  <div class="bb2b"></div>
</div>
```

## 49

```CSS
.bb2b{
  width:100%;
  height:100%
}
```

## 50

```CSS
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: black;
  --window-color2: #8cd9b3; /* 50 */
}
```

## 51

```CSS
.bb2b {
  width: 100%;
  height: 100%;
  background:linear-gradient(var(--building-color2) 0%,var(--building-color2) 6%, var(--window-color2) 6%, var(--window-color2) 9%);
}
```

## !52

`repeating-linear-gradient()`

```CSS
.bb2b {
  width: 100%;
  height: 100%;
  background: repeating-linear-gradient(
      var(--building-color2),
      var(--building-color2) 6%,
      var(--window-color2) 6%,
      var(--window-color2) 9%
    );
}
```

## 53

```CSS
.bb2 {
  width: 10%;
  height: 50%;
}
```

## 54

```CSS
.bb2a{
  margin: auto;
  width: 5vw;
  height: 5vw;
  border-top: 1vw solid #000;
  border-left: 1vw solid #999;
  border-right: 1vw solid #999;
  border-bottom: 1vw solid #000;
}
```

## 55

```CSS
.bb2a {
  margin: auto;

  border-top: 1vw solid #000;
  border-bottom: 1vw solid #000;
  border-left: 5vw solid #999;
  border-right: 5vw solid #999;
}
```

## 56

```CSS
.bb2a {
  margin: auto;
  border-top: 1vw solid #000;
  border-bottom: 1vw solid #000;
  border-left: 5vw solid transparent;
  border-right: 5vw solid transparent;
}
```

## 57

```CSS
.bb2a {
  border-bottom: 1vw solid #000;
  border-left: 5vw solid transparent;
  border-right: 5vw solid transparent;
}
```

## 58

```CSS
.bb2a {
  border-bottom: 5vh solid var(--building-color2);
  border-left: 5vw solid transparent;
  border-right: 5vw solid transparent;
}
```

## 59

```CSS
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: black;
  --window-color2: #8cd9b3;
  --window-color3: #d98cb3;
}
```

## 60

```CSS
.bb3 {
  width: 10%;
  height: 55%;
  background-color: var(--building-color3);
  background:repeating-linear-gradient(90deg, var(--building-color3), var(--building-color3),var(--window-color3) 15%);   
}
```

## 61

```CSS
.bb3 {
  width: 10%;
  height: 55%;
  background: repeating-linear-gradient(
      90deg,
      var(--building-color3),
      var(--building-color3),
      var(--window-color3) 15%
    );
}
```

## 62

```CSS
<div class="bb4">
  <div class="bb4a"></div>
  <div class="bb4b"></div>
  <div class="bb4c"></div>
</div>
```

## 63

```CSS
.bb4a{
  width:3%;
  height:10%
}
.bb4b{
  width:80%;
  height:5%
}
.bb4c{
  width:100%;
  height:85%
}
```

## 64

```CSS
.bb4 {
  width: 11%;
  height: 58%;
}

.bb4a {
  width: 3%;
  height: 10%;
  background-color: var(--building-color4);
}

.bb4b {
  width: 80%;
  height: 5%;
  background-color: var(--building-color4);
}
  
.bb4c {
  width: 100%;
  height: 85%;
  background-color: var(--building-color4);
}
```

## 65

```CSS
.building-wrap{

}
```

## 66

```CSS
.building-wrap {
  display: flex;
  flex-direction: column;
  align-items: center;
}
```

## 67

```HTML
  <div class="bb1 building-wrap">
  <div class="bb1a bb1-window"></div>
  <div class="bb1b bb1-window"></div>
  <div class="bb1c bb1-window"></div>
  <div class="bb1d"></div>
</div>
<div class="bb2">
  <div class="bb2a"></div>
  <div class="bb2b"></div>
</div>
<div class="bb3"></div>
<div></div>
<div class="bb4 building-wrap">
```

## 68

```CSS
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: black;
  --window-color2: #8cd9b3;
  --window-color3: #d98cb3;
  --window-color4:#8cb3d9;
}
```

## 69

```CSS
<div class="bb4c">
  <div class = "bb4-window"></div>
  <div class = "bb4-window"></div>
  <div class = "bb4-window"></div><div class = "bb4-window"></div>
</div>
```

## 70

```CSS
.bb4-window{
  width:18%;
  height:90%;
  background-color:var(--window-color4);
}
```

## 71

```CSS
.window-wrap{
  display:flex;
  justify-content:space-evenly;
  align-items:center;
}
```

## 72

```HTML
<div class="bb4c window-wrap">
  <div class="bb4-window"></div>
  <div class="bb4-window"></div>
  <div class="bb4-window"></div>
  <div class="bb4-window"></div>
</div>
```

## 73

```CSS
<div class="fb1">
  <div class="fb1a"></div>
  <div class="fb1b"></div>
  <div class="fb1c"></div>
</div>
```

## 74

```CSS
.fb1b{
  width:60%;
  height:10%;
}
.fb1c{
  width:100%;
  height:80%;
}
```

## 75

```CSS
<div class="fb1 building-wrap">
  <div class="fb1a"></div>
  <div class="fb1b"></div>
  <div class="fb1c"></div>
</div>
```

## 76

```CSS
.fb1 {
  width: 10%;
  height: 60%;
  
}

.fb1b {
  width: 60%;
  height: 10%;
  background-color: var(--building-color4);
}
```

## 77

```CSS
.fb1c {
  width: 100%;
  height: 80%;
  background:repeating-linear-gradient(90deg, var(--building-color4) 0%,var(--building-color4) 10%, transparent 10%, transparent 15%);
}
```

## 78

```CSS
.fb1c {
  width: 100%;
  height: 80%;
  background: repeating-linear-gradient(
      90deg,
      var(--building-color4),
      var(--building-color4) 10%,
      transparent 10%,
      transparent 15%
    ), repeating-linear-gradient(
      var(--building-color4),
      var(--building-color4) 10%,
      var(--window-color4) 10%,
      var(--window-color4) 90%
    );
}
```

## 79

```CSS
.fb1a{
  border-bottom: 7vh solid var(--building-color4);
}
```

## 80

```CSS
.fb1a {
  border-bottom: 7vh solid var(--building-color4);
  border-left: 2vw solid transparent;
  border-right: 2vw solid transparent;
}
```

## 81

```HTML
<div class="fb2">
  <div class="fb2a"></div>
  <div class="fb2b"></div>
</div>
```

## 82

```CSS
.fb2a{
  width:100%;
}
.fb2b{
  width:100%;
  height:75%
}
```

## 83

```HTML
<div class="fb2b">
  <div class="fb2-window"></div>
  <div class="fb2-window"></div>
  <div class="fb2-window"></div>
</div>
```

## 84

```HTML
<div class="fb2b window-wrap">
  <div class="fb2-window"></div>
  <div class="fb2-window"></div>
  <div class="fb2-window"></div>
</div>
```

## 85

```CSS
.fb2-window{
  width:22%;
  height:100%;
  background-color:var(--window-color3);
}
```

## 86

```CSS
.fb2 {
  width: 10%;
  height: 40%;
  
}

.fb2a {
  width: 100%;
  
}

.fb2b {
  width: 100%;
  height: 75%;
  background-color: var(--building-color3);
}
```

## 87

```CSS
.fb2a {
  width: 100%;
  border-bottom: 10vh solid var(--building-color3);
  border-left:1vw solid transparent;
  border-right:1vw solid transparent;
}
```

## 88

```HTML
<div class="fb3">
  <div class="fb3a"></div>
  <div class="fb3b"></div>
  <div class="fb3a"></div>
  <div class="fb3b"></div>
</div>
```

## 89

```CSS
.fb3a{
  width:80%;
  height:15%
}
.fb3b{
  width:100%;
  height:35%
}
```

## 90

```CSS
.fb3 {
  width: 10%;
  height: 35%;
}

.fb3a {
  width: 80%;
  height: 15%;
  background-color: var(--building-color1);
}
  
.fb3b {
  width: 100%;
  height: 35%;
  background-color: var(--building-color1);
}
```

## 91

```HTML
<div class="fb3 building-wrap">
  <div class="fb3a"></div>
  <div class="fb3b"></div>
  <div class="fb3a"></div>
  <div class="fb3b"></div>
</div>
```

## 92

```HTML
<div class="fb3a">
  <div class="fb3-window"></div>
  <div class="fb3-window"></div>
  <div class="fb3-window"></div>
</div>
```

## 93

```CSS
.fb3-window{
  width:25%;
  height:80%;
  background-color:var(--window-color1);
}
```

## 94

```HTML
<div class="fb3a window-wrap">
  <div class="fb3-window"></div>
  <div class="fb3-window"></div>
  <div class="fb3-window"></div>
</div>
```

## 95

```CSS
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: #bb99ff;
  --window-color2: #8cd9b3;
  --window-color3: #d98cb3;
  --window-color4: #8cb3d9;
}
```

## 96

```HTML
<div class="fb4">
  <div class="fb4a"></div>
  <div class="fb4b"></div>
</div>
```

## 97

```CSS
.fb4b{
  width:100%;
  height:89%;
}
```

## 98

```CSS
.fb4 {
  width: 8%;
  height: 45%; 
  position: relative;
  left: 10%;
}

.fb4b {
  width: 100%;
  height: 89%;
  background-color: var(--building-color1);
}
```

## 99

```HTML
<div class="fb4b">
  <div class="fb4-window"></div>
  <div class="fb4-window"></div>
  <div class="fb4-window"></div>
  <div class="fb4-window"></div>
  <div class="fb4-window"></div>
  <div class="fb4-window"></div>
</div>
```

## 100

```CSS
.fb4-window{
  width:30%;
  height:10%;
  border-radius:50%;
}
```

## 101

```CSS
.fb4-window {
  width: 30%;
  height: 10%;
  border-radius: 50%;
  background-color:var(--window-color1);
  margin:10%;
}
```

## 102

```CSS
.fb4b {
  width: 100%;
  height: 89%;
  display:flex;
  flex-wrap:wrap;
  background-color: var(--building-color1);
}
```

## 103

```CSS
.fb4a{
  border-top:5vh solid transparent;;
  border-left:8vw solid var(--building-color1);
}
```

## 104

```CSS
.fb5 {
  width: 10%;
  height: 33%;
  background-color: var(--building-color2);
  position: relative;
  right: 10%;
  background:repeating-linear-gradient(var(--building-color2) 0%, var(--building-color2) 5%, transparent 5%, transparent 10%);
}
```

## 105

```CSS
.fb5 {
  width: 10%;
  height: 33%;
  background-color: var(--building-color2);
  position: relative;
  right: 10%;
  background: repeating-linear-gradient(
      var(--building-color2),
      var(--building-color2) 5%,
      transparent 5%,
      transparent 10%
    ), repeating-linear-gradient(90deg, var(--building-color2), var(--building-color2) 12%, var(--window-color2) 12%, var(--window-color2) 44%);
}
```

## 106

```CSS
.fb5 {
  width: 10%;
  height: 33%;
  position: relative;
  right: 10%;
  background: repeating-linear-gradient(
      var(--building-color2),
      var(--building-color2) 5%,
      transparent 5%,
      transparent 10%
    ),
    repeating-linear-gradient(
      90deg,
      var(--building-color2),
      var(--building-color2) 12%,
      var(--window-color2) 12%,
      var(--window-color2) 44%
    );
}
```

## 107

```CSS
.fb6 {
  width: 9%;
  height: 38%;
  background-color: var(--building-color3);
  background:repeating-linear-gradient(
    90deg, 
    var(--building-color3), 
    var(--building-color3) 10%, 
    transparent 10%,
    transparent 30%);
}
```

## 108

```CSS
.fb6 {
  width: 9%;
  height: 38%;
  background-color: var(--building-color3);
  background: repeating-linear-gradient(
    90deg,
    var(--building-color3),
    var(--building-color3) 10%,
    transparent 10%,
    transparent 30%
  ), repeating-linear-gradient(
    var(--building-color3),
    var(--building-color3) 10%,
    var(--window-color3) 10%,
    var(--window-color3) 30%
  );
}
```

## 109

```CSS
.fb6 {
  width: 9%;
  height: 38%;
  background: repeating-linear-gradient(
      90deg,
      var(--building-color3),
      var(--building-color3) 10%,
      transparent 10%,
      transparent 30%
    ),
    repeating-linear-gradient(
      var(--building-color3),
      var(--building-color3) 10%,
      var(--window-color3) 10%,
      var(--window-color3) 30%
    );
}
```

## 110

```CSS
* {
  box-sizing: border-box;
}
```

# 111

```HTML
<div class="sky background-buildings"> <!-- add sky as class -->
```

## 112

```CSS
.sky{
  background:radial-gradient(#ffcf33,#ffcf33 20%, #ffff66 21%, #bbeeff 100%)
}
```

## 113

```CSS
.sky {
  background: radial-gradient(
    circle closest-corner at 15% 15%,
      #ffcf33,
      #ffcf33 20%,
      #ffff66 21%,
      #bbeeff 100%
    );
}
```

## 114

```CSS
@media(max-width:1000px){
  
}
```

# 115

```CSS
@media (max-width: 1000px) {
  .sky {
    background: radial-gradient(
      closest-corner circle at 15% 15%,
      #ffcf33,
      #ffcf33 20%,
      #ffff66 21%,
      #bbeeff 100%
    );
  }
}
```

## 116

```CSS
 .sky {
    background: radial-gradient(
  closest-corner circle at 15% 15%,
  #ccc,
  #ccc 20%,
  #445 21%,
  #223 100%
);
  }
```

## 117

```CSS
:root {
  --building-color1: #000;
  --building-color2: #000;
  --building-color3: #000;
  --building-color4: #000;
}
```

## 118

```CSS
:root {
    --building-color1: #000;
    --building-color2: #000;
    --building-color3: #000;
    --building-color4: #000;

  --window-color1: #777;
  --window-color2: #777;
  --window-color3: #777;
  --window-color4: #777;
  }

```