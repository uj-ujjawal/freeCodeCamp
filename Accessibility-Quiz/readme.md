# Learn Accessibility by Buildin Quiz

## 00

```HTML
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>

  </body>
</html>
```

## 01

```HTML
<html lang="en">
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>

  </body>
</html>
```

## 02

```HTMl
<head>
  <link rel="stylesheet" href="styles.css" />
  <meta charset="utf-8"/>
</head>
```

## 03

```HTML
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css" />
</head>
```

## !04

- `description` is meta element's that is used for accessibility and SEO.
- The value of the `content` attribute is used by search engines to provide a description of your page.

```HTML
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="freeCodeCamp Accessibility Quiz practice project" />
  <link rel="stylesheet" href="styles.css" />
</head>
```

## 05

```HTML
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="freeCodeCamp Accessibility Quiz practice project" />
  <link rel="stylesheet" href="styles.css" />
  <title>Accessibility Quiz</title>
</head>
```

## !06

- The `header` element will be used to introduce the page, as well as provide a navigation menu.
- The `main` element will contain the core content of your page.

```HTML
<body>
  <header>
  </header>
  <main></main>
</body>
```

## 07

```HTML
<header>
  <img src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" id="logo">
  <h1>HTML/CSS Quiz</h1>
  <nav></nav>
</header>
```

## 08

> **SVG (scalable vector graphics) ->** A useful property of an SVG is that it contains a `path` attribute which allows the image to be scaled without affecting the resolution of the resultant image.

`max()` Read here.

```CSS
#logo{
  width:max(100px, 18vw);
}
```

## !09

- [freeCodeCamp Style Guide](https://design-style-guide.freecodecamp.org/)
- logo should retain an aspect ratio of 35 / 4, and have padding around the text.
- `aspect-ratio`

```CSS
#logo {
  width: max(100px, 18vw);
  background-color:#0a0a23;
  aspect-ratio:35/4;
  padding:0.4rem;
}
```

## 10

```CSS
header{
  width:100%;
  height:50px;
  background-color:#1b1b32;
  display:flex;
}
```

## !11

- `min()`

```CSS
h1{
  color:#f1be32;
  font-size:min(5vw,1.2em);
}
```

## 12

```HTML
<nav>
  <ul>
    <li><a href="#">INFO</a></li>
    <li><a href="#">HTML</a></li>
    <li><a href="#">CSS</a></li>
  </ul>
</nav>
```

## 13

```CSS
nav>ul{
  display:flex;
  justify-content:space-evenly;
}
```

## !14

> **section:** It can use semantically separate the content within the form element.

```HTML
<main>
    <form action="https://freecodecamp.org/practice-project/accessibility-quiz" method="POST">
      <section>
      </section>
      <section>
      </section>
      <section>
      </section>
    </form>
</main>
```

## !15

- the `role` attribute: use to indicate the purpose behind an element on the page to assistive technologies. And It increase the page accessibility.
- The role attribute is a part of the Web Accessibility Initiative (WAI), and accepts preset values.

```HTML
<form method="post" action="https://freecodecamp.org/practice-project/accessibility-quiz">
  <section role="region"></section>
  <section role="region"></section>
  <section role="region"></section>
</form>
```

## !16

- Every `region` `role` requires a label, which helps screen reader users understand the purpose of the region.
- One method for adding a label is to - _add a heading element inside the region and then reference it with the `aria-labelledby` attribute._
- `area-labelby`

```HTML
<form method="post" action="https://freecodecamp.org/practice-project/accessibility-quiz">
  <section role="region" aria-labelledby="student-info">
    <h2 id="student-info">Student Info</h2>
  </section>
  <section role="region" aria-labelledby="html-questions">
    <h2 id="html-questions">HTML</h2>
  </section>
  <section role="region" aria-labelledby="css-questions">
    <h2 id="css-questions">CSS</h2>
  </section>
</form>
```

## !17$$

> Typeface plays an important role in the accessibility of a page
>
> Some fonts are easier to read than others, and this is especially true on low-resolution screens.

```CSS
h1,h2{
  font-family:Verdana sans-serif;
}
h2{
  border-bottom:4px solid #dfdfe2;
}
```

## 18

```HTML
<ul>
  <li><a href="#student-info">INFO</a></li>
  <li><a href="#html-questions">HTML</a></li>
  <li><a href="#css-questions">CSS</a></li>
</ul>
```

## 19

```HTML
<section role="region" aria-labelledby="student-info">
  <h2 id="student-info">Student Info</h2>
  <div class="info"><label></label><input></div>
  <div class="info"><label></label><input></div>
  <div class="info"><label></label><input></div>
</section>
```

## 20

```HTML
<section role="region" aria-labelledby="student-info">
  <h2 id="student-info">Student Info</h2>
  <div class="info">
    <label for="name">Student's Name</label>
    <input id="name"/>
  </div>
  <div class="info">
    <label for="email">Email Address</label>
    <input id="email"/>
  </div>
  <div class="info">
    <label for="dob">Date of Birth</label>
    <input id="dob"/>
  </div>
</section>
```

## 21

```HTML
<section role="region" aria-labelledby="student-info">
  <h2 id="student-info">Student Info</h2>
  <div class="info">
    <label for="student-name">Name:</label>
    <input type="text" name="student-name" id="student-name" placeholder="e.g. Johnny Deep" />
  </div>
  <div class="info">
    <label for="student-email">Email:</label>
    <input type="email" name="student-email" id="student-email" />
  </div>
  <div class="info">
    <label for="birth-date">D.O.B.:</label>
    <input type="date" name="birth-date" id="birth-date" />
  </div>
</section>
```

## !22

**Note** : Using _placeholder_ is actually _not a best-practice_ for accessibility; too often, users may be get confuse by the placeholder text with an actual input value - they can think there is already a value in the input. [Read More](./Text%20Only%20For%20SR.md)

```HTML
<div class="info">
  <label for="student-name">Name:</label>
  <input type="text" name="student-name" id="student-name" /> <!-- 22 placeholder removed -->
</div>
```

## !23

- using short form is not descriptive enough, especially true for visually impaired users
- One way to get around such an issue, without having to add visible text to the label, is to add text only a screen reader can read.

```HTML
<div class="info">
  <label for="birth-date">D.O.B.<span class="sr-only"></span></label>
  <input type="date" name="birth-date" id="birth-date" />
</div>
```

## 24

```HTML
<div class="info">
  <label for="birth-date">D.O.B.<span class="sr-only">(Date of Birth)</span></label>
  <input type="date" name="birth-date" id="birth-date" />
</div>
```

## 25

```CSS
.sr-only{
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
```

## 26

```HTMl
<section role="region" aria-labelledby="html-questions">
  <h2 id="html-questions">HTML</h2>
  <div class="question-block">
    <p>1</p>
    <fieldset class="question"></fieldset>
  </div>
  <div class="question-block">
    <p>2</p>
    <fieldset class="question"></fieldset>
  </div>
</section>
```

## 27

```HTML
<section role="region" aria-labelledby="html-questions">
  <h2 id="html-questions">HTML</h2>
  <div class="question-block">
    <p>1</p>
    <fieldset class="question">
      <legend></legend>
      <ul>
        <li></li>
        <li></li>
      </ul>
    </fieldset>
  </div>
  <div class="question-block">
    <p>2</p>
    <fieldset class="question">
      <legend></legend>
      <ul>
        <li></li>
        <li></li>
      </ul>
    </fieldset>
  </div>
</section>
```

## 28

```HTML
<section role="region" aria-labelledby="html-questions">
  <h2 id="html-questions">HTML</h2>
  <div class="question-block">
    <p>1</p>
    <fieldset class="question" name="ques-1">
      <legend>caption1</legend>
      <ul class="answers-list">
        <li></li>
        <li></li>
      </ul>
    </fieldset>
  </div>
  <div class="question-block">
    <p>2</p>
    <fieldset class="question" name="ques-2">
      <legend>caption2</legend>
      <ul class="answers-list">
        <li></li>
        <li></li>
      </ul>
    </fieldset>
  </div>
</section>
```

## 29

```HTML
    <ul class="answers-list">
      <li><label><input type="radio"></label></li>
      <li><label><input type="radio"></label></li>
    </ul>
  </fieldset>
</div>
<div class="question-block">
  <p>2</p>
  <fieldset class="question" name="html-question-two">
  <legend>
    A label element nesting an input element is required to have a
    for attribute with the same value as the input's id
  </legend>
  <ul class="answers-list">
    <li><label><input type="radio"></label></li>
    <li><label><input type="radio"></label></li>
  </ul>
```

## 30

```HTML
<ul class="answers-list">
  <li>
    <label>
      <input type="radio" id="q1-a1"/>
    </label>
  </li>
  <li>
    <label>
      <input type="radio" id="q1-a2"/>
    </label>
  </li>
</ul>
</fieldset>
</div>
<div class="question-block">
<p>2</p>
<fieldset class="question" name="html-question-two">
<legend>
  A label element nesting an input element is required to have a
  for attribute with the same value as the input's id
</legend>
<ul class="answers-list">
  <li>
    <label>
      <input type="radio" id="q2-a1"/>
    </label>
  </li>
  <li>
    <label>
      <input type="radio" id="q2-a2"/>
    </label>
  </li>
</ul>
```

## 31

```HTML
 <ul class="answers-list">
  <li>
    <label for="q1-a1">
      <input type="radio" id="q1-a1"/>
    </label>
  </li>
  <li>
    <label for="q1-a2">
      <input type="radio" id="q1-a2" />
    </label>
  </li>
  </ul>
  </fieldset>
  </div>
  <div class="question-block">
  <p>2</p>
  <fieldset class="question" name="html-question-two">
  <legend>
  A label element nesting an input element is required to have a
  for attribute with the same value as the input's id
  </legend>
  <ul class="answers-list">
  <li>
    <label for="q2-a1">
      <input type="radio" id="q2-a1" />
    </label>
  </li>
  <li>
    <label for="q2-a2">
      <input type="radio" id="q2-a2" />
    </label>
  </li>
</ul>
```

## 32

```HTML
<ul class="answers-list">
<li>
  <label for="q1-a1">
    <input type="radio" id="q1-a1" value="true"/> True
  </label>
</li>
<li>
  <label for="q1-a2">
    <input type="radio" id="q1-a2" value="false"/> False
  </label>
</li>
</ul>
</fieldset>
</div>
<div class="question-block">
<p>2</p>
<fieldset class="question" name="html-question-two">
<legend>
A label element nesting an input element is required to have a
for attribute with the same value as the input's id
</legend>
<ul class="answers-list">
<li>
  <label for="q2-a1">
    <input type="radio" id="q2-a1" value="true"/> True
  </label>
</li>
<li>
  <label for="q2-a2">
    <input type="radio" id="q2-a2" value="false"/> False
  </label>
</li>
</ul>
```

## 33

```HTML
<ul class="answers-list">
<li>
  <label for="q1-a1">
    <input type="radio" id="q1-a1" name="q1-a1" value="true" />
    True
  </label>
</li>
<li>
  <label for="q1-a2">
    <input type="radio" id="q1-a2" name="q1-a1" value="false" />
    False
  </label>
</li>
</ul>
</fieldset>
</div>
<div class="question-block">
<p>2</p>
<fieldset class="question" name="html-question-two">
<legend>
A label element nesting an input element is required to have a
for attribute with the same value as the input's id
</legend>
<ul class="answers-list">
<li>
  <label for="q2-a1">
    <input type="radio" id="q2-a1" name="q2-a1" value="true" />
    True
  </label>
</li>
<li>
  <label for="q2-a2">
    <input type="radio" id="q2-a2" name="q2-a1" value="false" />
    False
  </label>
</li>
</ul>
```

## 34

```CSS
p::before{
  content:"Question #";
}
```

## 35

```HTML
<section role="region" aria-labelledby="css-questions">
  <h2 id="css-questions">CSS</h2>
    <div class="formrow">
      <div class="question-block"></div>
      <div class="answer"></div>
      <div class="question-block"></div>
      <div class="answer"></div>
      </div>
    </div>
</section>
```

## 36

```HTML
<section role="region" aria-labelledby="css-questions">
  <h2 id="css-questions">CSS</h2>
  <div class="formrow">
    <div class="question-block">
      <label>1</label>
    </div>
    <div class="answer">
    </div>
    <div class="question-block">
      <label>2</label>
    </div>
    <div class="answer">
    </div>
  </div>
</section>
```

## 37

```HTML
<div class="answer">
  <select required>
    <option value="">Select an option</option>
    <option value="yes">Yes</option>
    <option value="no">No</option>
</div>
```

## 38

```HTML
<div class="question-block">
  <label for="devloper">Are you a frontend developer?</label>
</div>
<div class="answer">
  <select required id="devloper" name="devloper">
    <option value="">Select an option</option>
    <option value="yes">Yes</option>
    <option value="no">No</option>
  </select>
</div>
```

## 39

```HTML
<div class="answer">
  <textarea rows="5" cols="50" placeholder="Please enter your question here.."></textarea>
</div>
```

## 40

```HTML
<div class="question-block">
  <label for="any-question">Do you have any questions:</label>
</div>
<div class="answer">
  <textarea rows="5" cols="24" placeholder="Who is flexbox..." id="any-question" name="any-question"></textarea>
</div>
```

## 41

```HTMl
<button type="submit">Send</button> <!-- At the end of form -->
```

## !42

- The footer element is a container for a collection of content that is related to the page, and
- the address element is a container for contact information for the author of the page.

```HTML
<footer><address></address></footer>
```

## 43

```HTML
<footer>
  <address>
    freeCodeCamp<br />
    San Francisco<br />
    California<br />
    USA
  </address>
</footer>
```

## 44

```HTML
<footer>
  <address>
    <a href="https://freecodecamp.org">freeCodeCamp</a><br />
    San Francisco<br />
    California<br />
    USA
  </address>
</footer>
```

## 45

```CSS
nav li{
color: #dfdfe2;
margin: 0 0.2rem;
padding: 0.2rem;
display: block;
}
```

## !46

- On the topic of visual accessibility, contrast between elements is a key factor. For example, the contrast between the text and the background of a heading should be at least 4.5:1.

```CSS
li > a{
  color:white;
}
```

## !47

- cursor

```CSS
li > a {
  color: inherit;
  text-decoration:none;
}
nav li:hover{
  background-color:#dfdfe2;
  color:#1b1b32;
  cursor:pointer;
}
```

## 48

- Tidy up the header, by using Flexbox to put space between the children, and vertically center them.
- Then, fix the header to the top of the viewport.

```CSS
header {
  
  width: 100%;
  height: 50px;
  background-color: #1b1b32;
  display: flex;
  justify-content:space-between;
  align-items:center;
  top:0;
  position:fixed;
}
```

## 49

```CSS
h1 {
  color: #f1be32;
  font-size: min(5vw, 1.2em);
  text-align:center;
}

main{
  padding-top:100px; /* could be any value that make it clearly visible on thr screen */
}
```

## !50

On small screens, the unordered list in the navigation bar overflows the right side of the screen.

Fix this by using Flexbox to wrap the ul content. Then, set the following CSS properties to correctly align the text:

```CSS
align-items: center;
padding-inline-start: 0;
margin-block: 0;
height: 100%;
```

Now,

```CSS
nav > ul {
  display: flex;
  justify-content: space-evenly;
  flex-wrap:wrap;
  align-items: center;
  padding-inline-start: 0;
  margin-block: 0;
  height: 100%;
}
```

## 51

```CSS
section{
  width:80%;
  margin:auto;
  margin-top:0;
  margin-bottom: 10px;
  max-width:600px;
}
```

## 52

```CSS
h2 {
  margin-top:0;
  padding-top:60px;
  border-bottom: 4px solid #dfdfe2;
}
```

## 53

```CSS
.info{
  padding:1px 0 0 1px;
}
```

## 54

```CSS
.formrow {
  margin-top: 30px;
  padding: 0px 15px;
}
input {
  font-size: 16px;
}
```

## 55

```CSS
.info input{
  width:50%;
  text-align:left;
}
```

## 56

```CSS
.info input {
  width: 50%;
  text-align: left;
}

/* 56 */
.info label{
  width:10%;
  min-width:55px;
}
/* 56 */
```

## 57

```CSS
.info input {
  width: 50%;
  text-align: left;
}
.info label {
  width: 10%;
  min-width: 55px;
  text-align:right;
}
.info > label, .info > input{ /* .info label, .info input - both are equivalent*/
  display:inline-block;
  
}
```

## 58

```CSS
.question-block{
  text-align: left;
  display: block;
  width: 100%;
  margin-top: 20px;
  padding-top: 5px;
}
```

## 59

```CSS
p{
  margin-top: 5px;
  padding-left: 15px;
  font-size: 20px;
}
```

## 60

```CSS
.question{
  border:none;
  padding-bottom:0;
}
```

## 61

```CSS
.answers-list{
  list-style:none;
  padding:0;
}

```

## 62

```CSS
button{
  display: block;
  margin: 40px auto;
  width: 40%;
  padding: 15px;
  font-size: 23px;
  background: #d0d0d5;
  border: 3px solid #3b3b4f;
}
```

## 63

```CSS
footer{
  background:#2a2a40;
  display:flex;
  justify-content:center;
}
```

## 64

```CSS
footer, footer  a{
  color:#dfdfe2;
}
```

## 65

```CSS
address{
  text-align:center;
  padding:3px;
}
```

## 66

```CSS
*{
  scroll-behavior: smooth;
}
```

## !67

> Certain types of motion-based animations can cause discomfort for some users. In particular, people with vestibular disorders have sensitivity to certain motion triggers.

- The `@media` at-rule has a media _feature_ called `prefers-reduced-motion` to set CSS based on the user's preferences. It can take one of the following **values**:
  - reduce
  - no-preference

```CSS
@media(prefers-reduced-motion:no-preference){
  * {
  scroll-behavior: smooth;
  }
}
```

## !68

- the navigation accessibility can be improved by providing keyboard shortcuts.
- The accesskey attribute accepts a space-separated list of access keys. For exampl: `<button type="submit" accesskey="s">Submit</button>`

> Note: It is not always advised to use access keys, but they can be useful.

```CSS
<ul>
  <li><a href="#student-info" accesskey="i">INFO</a></li>
  <li><a href="#html-questions" accesskey="h">HTML</a></li>
  <li><a href="#css-questions" accesskey="c">CSS</a></li>
</ul>
```
