# Learn CSS Flexbox by Building Photo Gallery

- [Learn CSS Flexbox by Building Photo Gallery](#learn-css-flexbox-by-building-photo-gallery)
  - [Step 1](#step-1)
  - [Step 2](#step-2)
  - [Step 3](#step-3)
  - [Step 4](#step-4)
  - [Step 5](#step-5)
  - [Step 6](#step-6)
  - [Step 7](#step-7)
  - [Step 8](#step-8)
  - [Step 9](#step-9)
  - [Step 10](#step-10)
  - [Step 11](#step-11)
  - [Step 12](#step-12)
  - [Step 13](#step-13)
  - [Step 14](#step-14)
  - [Step 15](#step-15)
  - [Step 16](#step-16)
  - [Step 17](#step-17)
  - [Step 18](#step-18)
  - [Step 19](#step-19)
  - [Step 20](#step-20)
  - [Step 21](#step-21)

## Step 1

```HTML
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```

## Step 2

```HTML
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

## Step 3

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
  </body>
</html>
```

## Step 4

```HTML
<body>
  <header class="header">
    <h1>css flexbox photo gallery</h1>
  </header>
</body>
```

## Step 5

```HTML
<body>
  <header class="header">
  <h1>css flexbox photo gallery</h1>
  </header>

  <div class="gallery">
    <img>
    <img>
    <img>
    <img>
    <img>
    <img>
    <img>
    <img>
    <img>
  </div>
</body>
```

## Step 6

```HTMl
<div class="gallery">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/2.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/3.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/4.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/5.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/6.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/7.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/8.jpg">
  <img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/9.jpg">
</div>
```

## Step 7

```CSS
* {
  box-sizing: border-box;
}
```

## Step 8

```CSS
gallery img{
  width: 100%;
  max-width:350px;
  height:300px;
}
```

## Step 9

```CSS
body{
  margin:0;
  font-family:sans-serif;
  background-color:#f5f6f7;
}
```

## Step 10

text-transform

```CSS
.header{
  text-transform:uppercase;
  text-align:center;
  padding:32px;
  background-color:#0a0a23;
  color:#fff;
  border-bottom:4px solid #fdb347;
}
```

## Step 11

*Flexbox* is a one-dimensional CSS layout that can control the way items are spaced out and aligned within a container.

```CSS
.gallery{
  display:flex;
}
```

## Step 12

- Flexbox has a main and cross axis.
- The main axis is defined by the flex-direction property, which has four possible values:
  - row (default): horizontal axis with flex items from left to right
  - row-reverse: horizontal axis with flex items from right to left
  - column: vertical axis with flex items from top to bottom
  - column-reverse: vertical axis with flex items from bottom to top

```CSS
.gallery {
  display: flex;
  flex-direction: row;
}
```

## Step 13

flex-wrap

```CSS
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap:wrap;
}
```

## Step 14

justify-content:

```CSS
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content:center;
}
```

## Step 15

The align-items property positions the flex content along the cross axis.

```css
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}
```

## Step 16

```CSS
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding:20px 10px;
  max-width:1400px;
  margin: 0 auto;
}
```

## Step 17

object-fit
 object-fit property to determine how images should behave.

```CSS
.gallery img {
  width: 100%;
  max-width: 350px;
  height: 300px;
  object-fit:cover;
}
```

## Step 18

gap
row-gap:
column-gap:

```CSS
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  max-width: 1400px;
  margin: 0 auto;
  padding: 20px 10px;
  gap:16px;
}
```

## Step 19

```CSS
.gallery img {
  width: 100%;
  max-width: 350px;
  height: 300px;
  object-fit: cover;
  border-radius:10px;
}
```

## Step 20

```CSS
.gallery::after{
  content:"";
  width:350px;
}
```

## Step 21

```HTML
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg" alt="image of cute cat1">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/2.jpg" alt="image of cute cat2">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/3.jpg" alt="image of cute cat3">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/4.jpg" alt="image of cute cat4">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/5.jpg" alt="image of cute cat5">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/6.jpg" alt="image of cute cat6">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/7.jpg" alt="image of cute cat7">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/8.jpg" alt="image of cute cat8">
<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/9.jpg" alt="image of cute cat9">
```