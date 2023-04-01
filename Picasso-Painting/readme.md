#

## 01

```HTML
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```

## 02

```HTML
<meta charset="UTF-8">
<title>Picasso Painting</title>
```

## 03

```HTML
<link rel = "stylesheet" href="styles.css">
```

## 04

```HTML
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
```

## 05

```CSS
body{
  background-color:rgb(184, 132, 46);
}
```

## 06

```HTML
<div id="back-wall"></div>
```

## 07

```CSS
#back-wall{
  background-color:#8B4513;
}
```

## 08

```CSS
width:100%;
height:60%;
```

## !09

- HTML is rendered in a top-down manner.
- Elements at the top of the code are positioned at the top of the page. However, many times you may want to move the elements to different positions. You can do this with the position property.
- When an element is manually positioned, you can shift its layout with top, left, right, and bottom. Set the #back-wall element to have a top value of 0, and a left value of 0.

```CSS
height: 60%;
position:absolute;
top:0;
left:0;
```

## !10

- z-index property is used to create "layers" for HTML elements.
- Elements with a higher z-index value will appear to be layered on top of elements with a lower z-index value.
- This can be combined with the positioning in the previous lesson to create unique effects.

```CSS
z-index:-1;
```

## 11

```HTML
<div class="characters"></div>
```

## 12

```HTML
<div id="offwhite-character"></div>
```

## 13

```HTML
<div id="white-hat"></div>
<div id="black-mask"></div>
<div id="gray-instrument"></div>
<div id="tan-table"></div>
```

## 14

```HTML
<div class="eyes left"></div>
<div class="eyes right"></div>
```

## 15

```HTMl
<div class="black-dot"></div>
<div class="black-dot"></div>
<div class="black-dot"></div>
<div class="black-dot"></div>
<div class="black-dot"></div>
```

## 16

```CSS
#offwhite-character{
  width:300px;
  height:550px;
  background-color:ghostwhite;
}
```

## 17

```CSS
position:absolute;
top:20%;
left:17.5%;
```

## 18

```CSS
#white-hat{
  width:0;
  height:0;
  border-style:solid;
}
```

## 19

```CSS
border-width:0 120px 140px 180px;
```

## 20

```CSS
border-top-color:transparent;
border-right-color:transparent;
border-left-color:transparent;
border-bottom-color:ghostwhite;
```

## 21

```CSS
position:absolute;
top:-140px;
left:0;
```

## 22

```CSS
#black-mask{
width:100%;
height:50px;
background-color:rgb(45,31,19);
```

## 23

```CSS
position:absolute;
top:0;
left:0;
```  

## 24

```CSS
z-index:1;
```

## 25

```CSS
#gray-instrument{
  width:15%;
  height:40%;
  background-color:rgb(167, 162, 117);
}
```

## 26

```CSS
position:absolute;
top:50px;
left:125px;
```

## 27

```CSS
z-index:1;
```

## 28

```CSS
.black-dot{
  width:10px;
  height:10px;
  background-color:rgb(45, 31, 19);
}
```

## 29

```CSS
border-radius:50%;
```

## 30

```CSS
display:block;
margin:auto;
margin-top:65%;
```

## 31

```CSS

#tan-table{
  width:450px;
  height:140px;
  background-color:#D2691E;
}
```

## 32

```CSS
position:absolute;
top:275px;
left:15px;
```

## 33

```CSS
z-index:1;
```

## 34

```HTML
<div id="black-character"></div>
```

## 35

```HTML
<div id="black-character">
  <div id=black-hat></div>
  <div id=gray-mask></div>
  <div id=white-paper></div>
```

## 36

```HTML
<div class="eyes left"></div>
<div class="eyes right"></div>
```

## 37

```HTML
<i class="fas fa-music"></i>
<i class="fas fa-music"></i>
<i class="fas fa-music"></i>
<i class="fas fa-music"></i>
```

## 38

```CSS
#black-character{
  width:300px;
  height:500px;
  background-color:rgb(45, 31, 19);
}
```

## 39

```CSS
position:absolute;
top:30%;
left:59%;
```

## 40

```CSS
#black-hat{
  width:0;
  height:0;
  border-style:solid;
}
```

## 41

```CSS
border-width:150px 0 0 300px;
```

## 42

```CSS
border-top-color:transparent;
border-right-color:transparent;
border-bottom-color:transparent;
border-left-color:rgb(45, 31, 19);
```

## 43

```CSS
position:absolute;
top:-150px;
left:0;
```

## 44

```CSS
#gray-mask{
  width:150px;
  height:150px;
  background-color:rgb(167, 162, 117);
}
```

## 45

```CSS
position:absolute;
top:-10px;
left:70px;
```

## 46

```CSS
#white-paper{
  width: 400px;
  height:100px;
  background-color:ghostwhite;
}
```

## 47

```CSS
position:absolute;
top:250px;
left:-150px;
```

## 48

```CSS
z-index:1;
```

## 49

```CSS
.fa-music{
  display:inline-block;
  margin-top:8%;
  margin-left:13%;
}
```

## 50

```HTML
<div class="blue" id="blue-left"></div>
<div class="blue" id="blue-right"></div>
```

## 51

```CSS
.blue{
  background-color:#1E90FF;
}
```

## 52

```CSS
#blue-left{
  width:500px;
  height:300px;
}
```

## 53

```CSS
position:absolute;
top:20%;
left:20%;
```

## 54

```CSS
#blue-right{
width:400px;
height:300px;
}
```

## 55

```CSS
height: 300px;
position:absolute;
top:50%;
left:40%;
```

## 56

```HTML
<div id="orange-character"></div>
```

## 57

```CSS
<div id="black-round-hat"></div>
<div id="eyes-div"></div>
<div id="triangles"></div>
<div id="guitar"></div>
```

## 58

```CSS
<div class="eyes left"></div>
<div class="eyes right"></div>
```

## 59

```HTML
<div class="triangle"></div> <!-- upto 30times -->
```

## 60

```HTML
<div class="guitar" id="guitar-left"></div>
<div class="guitar" id="guitar-right"></div>
<div id="guitar-neck"></div>
```

## 61

```HTML
  <div class="guitar" id="guitar-left">
    <i class="fas fa-bars"></i>
  </div>
  <div class="guitar" id="guitar-right">
    <i class="fas fa-bars"></i>
  </div>
  ```

## 62

```CSS
#orange-character{
  width:250px;
  height:550px;
  background-color:rgb(240, 78, 42);
}
```

## 63

```CSS
position:absolute;
top:25%;
left:40%;
```

## 64

```CSS
#black-round-hat{
  width:180px;
  height:150px;
  background-color:rgb(45, 31, 19);
}
```

## 65

```CSS
border-radius:50%;
```

## 66

```CSS
position:absolute;
top:-100px;
left:5px;
```

## 67

```CSS
z-index:-1;
```

## 68

```CSS
#eyes-div{
  width:180px;
  height:50px;
}
```

## 69

```CSS
position:absolute;
top:-40px;
left:20px;
```

## 70

```CSS
z-index:3;
```

## 71

```CSS
#triangles{
  width:250px;
  height:550px;
}
```

## 72

```CSS
.triangle{
  width:0;
  height:0;
}
```

## 73

```CSS
border-style: solid;
border-width:42px 45px 45px 0;
```

## 74

```CSS
border-top-color:transparent;
border-bottom-color:transparent;
border-left-color:transparent;
border-right-color:gold;
```

## 75

```CSS
 display:inline-block;
```

## 76

```CSS
#guitar{
  width:100%;
  height:100px;
}
```

## 77

```CSS
position:absolute;
top:120px;
left:0px;
```

## 78

```CSS
z-index:3;
```

## 79

```CSS
.guitar{
  width:150px;
  height:120px;
  background-color:goldenrod;
  border-radius:50%;
}
```

## 80

```CSS
#guitar-left{
  position:absolute;
  left:0px;
}
```

## 81

```CSS
#guitar-right{
  position:absolute;
  left:100px;
}
```

## 82

```CSS
.fa-bars {
  display: block;
  margin-top: 30%;
  margin-left: 40%;
}
```

## 83

```CSS
#guitar-neck {
  width: 200px;
  height: 30px;
  background-color: #D2691E;
}
```

## 84

```CSS
position:absolute;
top:45px;
left:200px;
```

## 85

```CSS
z-index:3;
```

## 86

```CSS
.eyes{
  width:35px;
  height: 20px;
  background-color:#8B4513;
  border-radius:20px 50%;
}
```

## 87

```CSS
.right{
  position:absolute;
  top:15px;
  right:30px;
}
```

## 88

```CSS
.left{
  position:absolute;
  top:15px;
  left:30px;
}
```

## 89

```CSS
.fas{
  font-size:30px;
}
```