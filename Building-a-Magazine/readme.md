# Learn CSS Grid by Building a Magazine

- [Learn CSS Grid by Building a Magazine](#learn-css-grid-by-building-a-magazine)
  - [01](#01)
  - [02](#02)
  - [03](#03)
  - [04](#04)
  - [05](#05)
  - [06](#06)
  - [07](#07)
  - [!08](#08)
  - [09](#09)
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
  - [!27](#27)
  - [28](#28)
  - [29](#29)
  - [30](#30)
  - [31](#31)
  - [!32](#32)
  - [!33](#33)
  - [!34](#34)
  - [35](#35)
  - [!36](#36)
  - [37](#37)
  - [38](#38)
  - [!39](#39)
  - [40](#40)
  - [!41](#41)
  - [42](#42)
  - [43](#43)
  - [!44](#44)
  - [45](#45)
  - [46](#46)
  - [47](#47)
  - [48](#48)
  - [49](#49)
  - [50](#50)
  - [51](#51)
  - [52](#52)
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

## 01

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
  </body>
</html>
```

## 02

```HTML
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title >Magazine</title>
  <link rel ="stylesheet" href="https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap"/>
  <link rel = "stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"/>
  <link rel = "stylesheet" href="./styles.css"/>
</head>
```

## 03

```HTML
<main>
  <section class="heading"></section>
</main>
```

## 04

```HTML
<main>
  <section class="heading">
    <header class="hero">
    <img src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png" alt="freecodecamp logo" class="hero-img" loading="lazy"/>
    </header>
  </section>
</main>
```

## 05

```HTMl
<main>
  <section class="heading">
    <header class="hero">
      <img
        src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
        alt="freecodecamp logo"
        loading="lazy"
        class="hero-img"
      />
      <h1 class="hero-title">OUR NEW CURRICULUM</h1>
      <p class="hero-subtitle">Our efforts to restructure our curriculum with a more project-based focus</p>
    </header>
  </section>
</main>
```

## 06

```HTML
<main>
  <section class="heading">
    <header class="hero">
      <!-- 06 -->
      <img
        src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
        alt="freecodecamp logo"
        loading="lazy"
        class="hero-img"
        width="400";
      />
      <!-- 06 -->
      <h1 class="hero-title">OUR NEW CURRICULUM</h1>
      <p class="hero-subtitle">
        Our efforts to restructure our curriculum with a more project-based
        focus
      </p>
    </header>
  </section>
</main>
```

## 07

```HTML
      <div class="author">
      <p class="author-name">By <a href="https://freecodecamp.org" target="_blank">freeCodeCamp</a></p>
      <p class="publish-date">March 7, 2019</p>
    </div>
  </section>
</main>
```

## !08

`rel=referer` & `rel=noreferrer`

```HTML
    <div class="author">
      <p class="author-name">
        By
        <a href="https://freecodecamp.org" target="_blank" rel = "noreferrer"
          >freeCodeCamp</a
        >
      </p>
      <p class="publish-date">March 7, 2019</p>
    </div>
  </section>
</main>
```

## 09

```HTMl
<div class="social-icons">
  <a href="https://www.facebook.com/freecodecamp/"></a>
  <a href="https://twitter.com/freecodecamp/"></a>
  <a href="https://instagram.com/freecodecamp"></a>
  <a href="https://www.linkedin.com/school/free-code-camp/"></a>
  <a href="https://www.youtube.com/freecodecamp">
  </a>
</div>
```

## 10

```HTML
<div class="social-icons">
  <a href="https://www.facebook.com/freecodecamp/"><i class="fab fa-facebook-f"></i>
  </a>
  <a href="https://twitter.com/freecodecamp/"><i class="fab fab fa-twitter"></i>
  </a>
  <a href="https://instagram.com/freecodecamp"><i class="fab fa-instagram"></i>
  </a>
  <a href="https://www.linkedin.com/school/free-code-camp/"><i class="fab fa-linkedin-in"></i>
  </a>
  <a href="https://www.youtube.com/freecodecamp"><i class="fab fa-youtube"></i>
  </a>
</div>
```

## 11

```HTMl
<section class="text">
  <p class="first-paragraph">
    Soon the freeCodeCamp curriculum will be 100% project-driven learning. Instead of a series of coding challenges, you'll learn through building projects - step by step. Before we get into the details, let me emphasize: we are not changing the certifications. All 6 certifications will still have the same 5 required projects. We are only changing the optional coding challenges.
  </p>
</section>
```

## 12

```HTML
 <section class="text">
  <!-- below the 1st <p> tag -->
  <p>After years - years - of pondering these two problems and how to solve them, I slipped, hit my head on the sink, and when I came to I had a revelation! A vision! A picture in my head! A picture of this! This is what makes time travel possible: the flux capacitor!
  </p>
</section>
```

## 13

```HTML
<!-- below 2nd <p> tag -->
<p>It wasn't as dramatic as Doc's revelation in Back to the Future. It just occurred to me while I was going for a run. The revelation: the entire curriculum should be a series of projects. Instead of individual coding challenges, we'll just have projects, each with their own seamless series of tests. Each test gives you just enough information to figure out how to get it to pass. (And you can view hints if that isn't enough.)
          </p>
```

## 14

```HTML
<blockquote>
  <hr>
  <p class="quote">The entire curriculum should be a series of projects</p>
  <hr>
</blockquote>
```

## 15

```HTML
<p>No more walls of explanatory text. No more walls of tests. Just one test at a time, as you build up a working project. Over the course of passing thousands of tests, you build up projects and your own understanding of coding fundamentals. There is no transition between lessons and projects, because the lessons themselves are baked into projects. And there's plenty of repetition to help you retain everything because - hey - building projects in real life has plenty of repetition.
</p>
```

## 16

```HTML
<p>
  The main design challenge is taking what is currently paragraphs of explanation and instructions and packing them into a single test description text. Each project will involve dozens of tests like this. People will be coding the entire time, rather than switching back and forth from "reading mode" to "coding mode".
</p>
```

## 17

```HTML
<!-- to the end -->
 <p>Instead of a series of coding challenges, people will be in their code
editor passing one test after another, quickly building up a project.
People will get into a real flow state, similar to what they
experience when they build the required projects at the end of each
certification. They'll get that sense of forward progress right from
the beginning. And freeCodeCamp will be a much smoother experience.
</p>
```

## 18

```HTML
<section class="text text-with-images">
  <article class="brief-history">
  </article>
  <aside class="image-wrapper">
  </aside>
</section>
```

## 19

```HTML
<article class="brief-history">
  <h3 class="list-title">A Brief History</h3>
  <p>Of the Curriculum</p>
  <ul class="lists"></ul>
</article>
```

## 20

```HTML
<article class="brief-history">
  <h3 class="list-title">A Brief History</h3>
  <p>Of the Curriculum</p>
  <ul class="lists">
    <li>
      <h4 class="list-subtitle">V1 - 2014</h4>
      <p>
        We launched freeCodeCamp with a simple list of 15 resources,
        including Harvard's CS50 and Stanford's Database Class.
      </p>
    </li>
    <li>
      <h4 class="list-subtitle">V2 - 2015</h4>
      <p>We added interactive algorithm challenges.</p>
    </li>
    <li>
      <h4 class="list-subtitle">V3 - 2015</h4>
      <p>
        We added our own HTML+CSS challenges (before we'd been relying on
        General Assembly's Dash course for these).
      </p>
    </li>
    <li>
      <h4 class="list-subtitle">V4 - 2016</h4>
      <p>
        We expanded the curriculum to 3 certifications, including Front End,
        Back End, and Data Visualization. They each had 10 required
        projects, but only the Front End section had its own challenges. For
        the other certs, we were still using external resources like Node
        School.
      </p>
    </li>
    <li>
      <h4 class="list-subtitle">V5 - 2017</h4>
      <p>We added the back end and data visualization challenges.</p>
    </li>
    <li>
      <h4 class="list-subtitle">V6 - 2018</h4>
      <p>
        We launched 6 new certifications to replace our old ones. This was
        the biggest curriculum improvement to date.
      </p>
    </li>
  </ul>
</article>
```

## 21

```HTML
<aside class="image-wrapper">
  <img />
  <img />
  <blockquote class="image-quote">
  </blockquote>
  <img />
</aside>
```

## 22

```HTMl
<aside class="image-wrapper">
  <img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" alt="image of the quote machine project" class="image-1" loading="lazy" width="600" height="400"/>
  <img />
  <blockquote class="image-quote"></blockquote>
  <img />
</aside>
```

## 23

```HTML
<aside class="image-wrapper">
  <img
    src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png"
    alt="image of the quote machine project"
    loading="lazy"
    class="image-1"
    width="600"
    height="400"
  />
  <img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/calc.png" alt="image of a calculator project" loading="lazy" width="400" height="400" class="image-2"/>
  <blockquote class="image-quote"></blockquote>
  <img />
</aside>
```

## 24

```HTML
<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/survey-form-background.jpeg" class="image-3" width="600" height="400" loading="lazy" alt="four people working on code"/>
```

## 25

```HTML
<blockquote class="image-quote">
  <hr>
  <p class="quote">
    The millions of people who are learning to code through freeCodeCamp will have an even better resource to help them learn these fundamentals.
  </p>
  <hr>
</blockquote>
```

## 26

```CSS
*, ::before, ::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
```

## !27

setting the default font size for web page to 10px (the browser default is 16px), Make it easier for us to work with rem units later, as 2rem would be 20px.

```CSS
html{
  font-size:62.5%; /* 62.5% = 10px */
}
```

## 28

```CSS
body{
  font-family:Baskervville, serif;
  color:linen;
  background-color:rgb(20,30,40);
}
```

## 29

```CSS
h1{
  font-family:Anton,sans-serif;
}
```

## 30

```CSS
h2, h3, h4, h5, h6{
  font-family:Raleway, sans-serif;
}
```

## 31

```CSS
a{
  text-decoration:none;
  color:linen;
}
```

## !32

- grid layout

```CSS
main{
  display:grid;
}
```

## !33

- fraction unit
- grid-template-columns

```CSS
main {
  display: grid;
  grid-template-columns:1fr 94rem 1fr;
}
```

## !34

- `minmax` function : make your columns responsive on any device.
  - It takes two arguments, the first being the minimum value and the second being the maximum.
  - These values could be a length, percentage, fr, or even a keyword like `max-content`, or `min-content`

```CSS
main {
  display: grid;
  grid-template-columns: minmax(2rem, 1fr) minmax(min-content,94rem) minmax(2rem, 1fr);
}
```

## 35

```CSS
main {
  display: grid;
  grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);
  row-gap:3rem; /* 35 */
}
```

## !36

- `grid-column` property, which is shorthand for grid-column-start and grid-column-end.
  - The grid-column property tells the grid item which grid line to start and end at.

```CSS
.heading{
  grid-column: 2/3; /* This will tell the .heading element to start at grid line 2 and end at grid line 3. */
}
```

## 37

```CSS
.text{
  grid-column:2/3;
}
```

## 38

```CSS
.heading {
  grid-column: 2 / 3;
  display:grid;

}
```

## !39

- `repeat()` function is used to repeat a value, rather than writing it out manually, and is helpful for grid layouts.
- For example, setting the grid-template-columns property to repeat(20, 200px) would create 20 columns each 200px wide.

```CSS
.heading {
  grid-column: 2 / 3;
  display: grid;
  grid-template-columns:repeat(2, 1fr); /* 39 */
}
```

## 40

```CSS
.heading {
  grid-column: 2 / 3;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  row-gap:1.5rem;
}
```

## !41

- `grid-column`: There may be times where you are unsure of how many columns your grid will have, but you want an element to stop at the last column. To do this, you can use -1 for the end column.

```CSS
.hero{
  grid-column:1/-1;
}
```

## 42

```CSS
.hero {
  grid-column: 1 / -1;
  position:relative;
}
```

## 43

- remove the temporary width attribute from img tag.

## !44

- `object-fit` tells the browser how to position the element within its container.
- possible values:fill(default), contain, cover, none, scale-down

```CSS
img{
  width:100%;
  object-fit:cover;  /* cover will set the image to fill the container, cropping as needed to avoid changing the aspect ratio. */
}
```

## 45

```CSS
.hero-title{
  text-align:center;
  color:orangered;
  font-size:8rem;
}
```

## 46

```CSS
.hero-subtitle{
  font-size:2.4rem;
  color:orangered;
  text-align:center;
}
```

## 47

```CSS
.author{
  font-size:2rem;
  font-family:Raleway, sans-serif;
}
```

## 48

```CSS
.author-name a:hover{
  background-color:#306203;
}
```

## 49

```CSS
.publish-date{
  color:rgba(255,255,255,0.5);
}
```

## 50

```CSS
.social-icons{
  display:grid;
  font-size:3rem;
}
```

## 51

```CSS
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-template-columns:repeat(5,1fr);
}
```

## 52

```CSS
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-template-columns: repeat(5, 1fr);
  grid-auto-flow:column;
}
```

## 53

```CSS
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-template-columns: repeat(5, 1fr);
  grid-auto-flow: column;
  grid-auto-columns:1fr;
}
```

## 54

```CSS
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-template-columns: repeat(5, 1fr);
  grid-auto-flow: column;
  grid-auto-columns: 1fr;
  align-items:center;
}
```

## 55

```CSS
.text {
  grid-column: 2 / 3;
  font-size:1.8rem;
  letter-spacing:0.6px;
}
```

## 56

```CSS
.text {
  grid-column: 2 / 3;
  font-size: 1.8rem;
  letter-spacing: 0.6px;
  column-width:25rem;
}
```

## 57

```CSS
.text {
  grid-column: 2 / 3;
  font-size: 1.8rem;
  letter-spacing: 0.6px;
  column-width: 25rem;
  text-align:justify;
}
```

## 58

```CSS
.first-paragraph::first-letter {
  font-size: 6rem;
  color: orangered;
}
```

## 59

```CSS
.first-paragraph::first-letter {
  font-size: 6rem;
  color: orangered;
  float:left;
  margin-right:1rem;
}
```

## 60

```CSS
hr{
  margin:1.5rem 0;
}
```

## 61

```CSS
hr {
  margin: 1.5rem 0;
  border:1px solid rgba(120,120,120, 0.6);
}
```

## 62

```CSS
.quote{
  color:#00beef;
  font-size:2.4rem;
  text-align:center;
}
```

## 63

```CSS
.quote {
  color: #00beef;
  font-size: 2.4rem;
  text-align: center;
  font-family:Raleway, sans-serif;
}
```

## 64

```CSS
.quote::before{
  content:'" ';
}
.quote:after{
  content:' "';
}
```

## 65

```CSS
.text-with-images{
  display:grid;
}
```

## 66

```CSS
.text-with-images {
  display: grid;
  grid-template-columns:1fr 2fr;
  column-gap:3rem;
}
```

## 67

```CSS
.text-with-images {
  display: grid;
  grid-template-columns: 1fr 2fr;
  column-gap: 3rem;
  margin-bottom:3rem;
}
```

## 68

```CSS
.lists{
  list-style-type:none;
}
```

## 69

```CSS
.lists {
  list-style-type: none;
  margin-top:2rem;
}
```

## 70

```CSS
.lists li{
  margin-bottom:1.5rem;
}
```

## 71

```CSS
.list-title, .list-subtitle{
  color:#00beef;
}
```

## 72

```CSS
.image-wrapper{
  display:grid;

}
```

## 73

```CSS
.image-wrapper {
  display: grid;
  grid-template-columns:2fr 1fr;
  grid-template-rows:repeat(3,min-content);
}
```

## 74

```CSS
.image-wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: repeat(3, min-content);
  gap:2rem;
}
```

## 75

```CSS
.image-wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: repeat(3, min-content);
  gap: 2rem;
  place-items:center;
}
```

## 76

```CSS
.image-1, .image-3{
  grid-column:1 /-1;
}
```

## 77

```CSS
@media only screen and (max-width:720px){
  .image-wrapper{
    grid-template-columns:1fr;
  }
}
```

## 78

```CSS
@media only screen and (max-width:600px){
  .text-with-images{
    grid-template-columns:1fr;
  }
}
```

## 79

```CSS
@media only screen and (max-width:550px){
  .hero-title{
    font-size:6rem;
  }
  .hero-subtitle, .author, .quote, .list-title{
    font-size:1.8rem;
  }
  .social-icons{
    font-size:2rem;
  }
  .text{
    font-size:1.6rem;
  }
}
```

## 80

```CSS
@media only screen and (max-width:420px){
  .hero-title{
    font-size:4.5rem;
  }
}
```
