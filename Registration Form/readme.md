# Registratiton Form

- [Registratiton Form](#registratiton-form)
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
  - [STEp 42](#step-42)
  - [STEP 43](#step-43)
  - [STEP 44](#step-44)
  - [STEp 45](#step-45)
  - [STEP 46](#step-46)
  - [STEP 47](#step-47)
  - [STEP 48](#step-48)
  - [STEP 49](#step-49)
  - [STEP 50](#step-50)
  - [STEP 51](#step-51)
  - [STEP 52](#step-52)
  - [STEP 53](#step-53)
  - [STEP 54](#step-54)
  - [STEP 55](#step-55)
  - [STEP 56](#step-56)
  - [STEP 57](#step-57)
  - [STEP 58](#step-58)
  - [STEP 59](#step-59)
  - [STEP 60](#step-60)
  - [STEP 61](#step-61)
  - [STEP 62](#step-62)
  - [STEP 63](#step-63)

## STEP 1

```HTML
<!DOCTYPE html>
```

## STEP 2

```html
<html lang="en"></html>
```

## STEP 3

```HTML
<head></head>
<body></body>
```

## STEP 4

```HTML
<head>
  <title>Registration Form</title>
  <meta charset="utf-8">
</head>
```

## STEP 5

```HTMl
  <head>
    <meta charset="UTF-8">
    <title>Registration Form</title>
    <link rel="stylesheet" href="styles.css"/>
  </head>
```

## STEP 6

```HTML
<body>
    <h1>Registration Form</h1>
</body>
```

## STEP 7

```HTML
<body>
    <h1>Registration Form</h1>
    <p>Please fill out this form with the required information</p>
</body>
```

## STEP 8

- **vh** unit stands for viewport height
- and is relative to 1% of the height of the viewport.

```CSS
body{
  width:100%;
  height:100vh;
}
```

## STEP 9

```CSS
body {
  width: 100%;
  height: 100vh;
  margin:0;
}
```

## STEP 10

```CSS
body {
  width: 100%;
  height: 100vh;
  margin: 0;
  color:#f5f6f7;
  background-color:#1b1b32;
}
```

## STEP 11

```html
  <body>
    <h1>Registration Form</h1>
    <p>Please fill out this form with the required information</p>
  <form action="https://register-demo.freecodecamp.org"></form>
  </body>
```

## STEP 12

```html
<form action='https://register-demo.freecodecamp.org' method="post"></form>
```

## STEP 13

```HTML
 <body>
    <h1>Registration Form</h1>
    <p>Please fill out this form with the required information</p>
    <form method="post" action='https://register-demo.freecodecamp.org'>
     <fieldset></fieldset>
     <fieldset></fieldset>
     <fieldset></fieldset>
    </form>
  </body>
```

## STEP 14

```HTML
<form method="post" action='https://register-demo.freecodecamp.org'>
  <fieldset>
    <label></label>
    <label></label>
    <label></label>
    <label></label>
  </fieldset>
  <fieldset></fieldset>
  <fieldset></fieldset>
</form>
```

## STEP 15

```HTML
<fieldset>
  <label>Enter Your First Name:</label>
  <label>Enter Your Last Name:</label>
  <label>Enter Your Email:</label>
  <label>Create a New Password:</label>
</fieldset>
```

## STEP 16

NOTE: The rem unit stands for root em, and is relative to the font size of the html element.

```CSS
label{
  display:block;
  margin:0.5rem 0;
}
```

## STEP 17

```HTML
<fieldset>
  <label>Enter Your First Name: <input></label>
  <label>Enter Your Last Name: <input></label>
  <label>Enter Your Email: <input></label>
  <label>Create a New Password: <input></label>
</fieldset>
```

## STEP 18

```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name"/></label>
  <label for="last-name">Enter Your Last Name: <input id="last-name"/></label>
  <label for="email">Enter Your Email: <input id="email"/></label>
  <label for="new-password">Create a New Password: <input id="new-password"/></label>
</fieldset>
```

## STEP 19

```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input type="text" id="first-name" /></label>
  <label for="last-name">Enter Your Last Name: <input type="text" id="last-name" /></label>
  <label for="email">Enter Your Email: <input type="email" id="email" /></label>
  <label for="new-password">Create a New Password: <input type="password" id="new-password" /></label>
</fieldset>
```

## STEP 20

```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name" type="text" /></label>
  <label for="last-name">Enter Your Last Name: <input id="last-name" type="text" /></label>
  <label for="email">Enter Your Email: <input id="email" type="email" /></label>
  <label for="new-password">Create a New Password: <input id="new-password" type="password" /></label>
</fieldset>
<fieldset></fieldset>
<fieldset></fieldset>
<input type="submit" value="Submit">
```

## STEP 21

```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name" type="text" required/></label>
  <label for="last-name">Enter Your Last Name: <input id="last-name" type="text" required/></label>
  <label for="email">Enter Your Email: <input id="email" type="email" required/></label>
  <label for="new-password">Create a New Password: <input id="new-password" type="password" required/></label>
</fieldset>
<fieldset></fieldset>
<fieldset></fieldset>
<input type="submit" value="Submit" />
```

## STEP 22

minlength and maxlength: validation for input field.

```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name" type="text" required /></label>
  <label for="last-name">Enter Your Last Name: <input id="last-name" type="text" required /></label>
  <label for="email">Enter Your Email: <input id="email" type="email" required /></label>
  <label for="new-password">Create a New Password: <input id="new-password" type="password" required minlength="8"/></label>
</fieldset>
```

## STEP 23

```HTML

- pattern attribute to the password input element to require the input match: [a-z0-5]{8,} regular expression.

```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name" type="text" required /></label>
  <label for="last-name">Enter Your Last Name: <input id="last-name" type="text" required /></label>
  <label for="email">Enter Your Email: <input id="email" type="email" required /></label>
  <label for="new-password">Create a New Password: <input id="new-password" type="password" pattern="[a-z0-5]{8,}" required /></label>
</fieldset>
```

## STEP 24

```HTML
<fieldset>
  <label></label>
  <label></label>
  <label></label>
</fieldset>
```

## STEP 25

```HTML
<fieldset>
  <label><input type="radio"></label>
  <label><input type="radio"></label>
  <label></label>
</fieldset>
```

## STEP 26

```HTMl
<fieldset>
  <label><input type="radio" /></label>
  <label><input type="radio" /></label>
  <label><input type="checkbox" required></label>
</fieldset>
```

## STEP 27

```HTML
<fieldset>
  <label><input type="radio" /> Personal Account</label>
  <label><input type="radio" /> Business Account</label>
  <label><input type="checkbox" required /> I accept the terms and conditions</label>
</fieldset>
```

## STEP 28

```HTML
<fieldset>
  <label><input type="radio" name="account-type"/> Personal Account</label>
  <label><input type="radio" name="account-type"/> Business Account</label>
  <label><input type="checkbox" required /> I accept the terms and conditions</label>
</fieldset>
```

## STEP 29

```HTML
<fieldset>
  <label for="personal-account"><input type="radio" name="account-type" id="personal-account"/> Personal Account</label>
  <label for="business-account"><input type="radio" name="account-type" id="business-account"/> Business Account</label>
  <label for="terms-and-conditions"><input type="checkbox" required id="terms-and-conditions"/> I accept the terms and conditions</label>
</fieldset>
```

## STEP 30

```html
<fieldset>
  <label for="personal-account"><input id="personal-account" type="radio" name="account-type" /> Personal Account</label>
  <label for="business-account"><input id="business-account" type="radio" name="account-type" /> Business Account</label>
  <label for="terms-and-conditions"><input id="terms-and-conditions" type="checkbox" required /> I accept the <a href="https://www.freecodecamp.org/news/terms-of-service/
">terms and conditions</a></label>
</fieldset>
```

## STEP 31

```HTML
<fieldset>
  <label>Upload a profile picture:<input type="file"></label>
</fieldset>
```

## STEP 32

```HTML
<fieldset>
  <label>Upload a profile picture: <input type="file" /></label>
  <label>Input your age (years): <input type="number" min="13" max="120"></label>
</fieldset>
```

## STEP 33

With form submissions, it is useful, and good practice, to provide each submittable element with a name attribute. This attribute is used to identify the element in the form submission.

```HTML
<fieldset>
  <label>Upload a profile picture: <input type="file" /></label>
  <label>Input your age (years): <input type="number" min="13" max="120" /></label>
<select>
<option></option>
<option></option>
<option></option>
<option></option>
<option></option>
</select>
</fieldset>
```

## STEP 34

```HTML
<fieldset>
  <label>Upload a profile picture: <input type="file" /></label>
  <label>Input your age (years): <input type="number" min="13" max="120" /></label>
  <label>How did you hear about us?
  <select>
    <option></option>
    <option></option>
    <option></option>
    <option></option>
    <option></option>
  </select>
  </label>
</fieldset>
```

## STEP 35

```HTML
<fieldset>
  <label>Upload a profile picture: <input type="file" /></label>
  <label>Input your age (years): <input type="number" min="13" max="120" /></label>
  <label>How did you hear about us?
    <select>
      <option>(select one)</option>
      <option>freeCodeCamp News</option>
      <option>freeCodeCamp YouTube Channel</option>
      <option>freeCodeCamp Forum</option>
      <option>Other</option>
    </select>
  </label>
</fieldset>
```

## STEP 36

```HTML
<fieldset>
  <label>Upload a profile picture: <input type="file" /></label>
  <label>Input your age (years): <input type="number" min="13" max="120" /></label>
  <label>How did you hear about us?
    <select>
      <option value="">(select one)</option>
      <option value="1">freeCodeCamp News</option>
      <option value="2">freeCodeCamp YouTube Channel</option>
      <option value="3">freeCodeCamp Forum</option>
      <option value="4">Other</option>
    </select>
  </label>
</fieldset>
```

## STEP 37

```HTML
<fieldset>
  <label>Upload a profile picture: <input type="file" /></label>
  <label>Input your age (years): <input type="number" min="13" max="120" /></label>
  <label>How did you hear about us?
    <select>
      <option value="">(select one)</option>
      <option value="1">freeCodeCamp News</option>
      <option value="2">freeCodeCamp YouTube Channel</option>
      <option value="3">freeCodeCamp Forum</option>
      <option value="4">Other</option>
    </select>
  </label>
  <label>Provide a bio: <textarea></textarea>
</fieldset>
```

## STEP 38

```HTML
<fieldset>
  <label for="profile-picture">Upload a profile picture: <input type="file" id="profile-picture"/></label>
  <label for="age">Input your age (years): <input type="number" min="13" max="120" id="age" /></label>
  <label for="referrer">How did you hear about us?
    <select id="referrer">
      <option value="">(select one)</option>
      <option value="1">freeCodeCamp News</option>
      <option value="2">freeCodeCamp YouTube Channel</option>
      <option value="3">freeCodeCamp Forum</option>
      <option value="4">Other</option>
    </select>
  </label>
  <label for="bio">Provide a bio:
    <textarea id="bio"></textarea>
  </label>
</fieldset>
```

## STEP 39

```HTML
<fieldset>
    <label for="profile-picture">Upload a profile picture: <input id="profile-picture" type="file" /></label>
    <label for="age">Input your age (years): <input id="age" type="number" min="13" max="120" /></label>
    <label for="referrer">How did you hear about us?
      <select id="referrer">
        <option value="">(select one)</option>
        <option value="1">freeCodeCamp News</option>
        <option value="2">freeCodeCamp YouTube Channel</option>
        <option value="3">freeCodeCamp Forum</option>
        <option value="4">Other</option>
      </select>
    </label>
    <label for="bio">Provide a bio:
      <textarea id="bio" rows="3" cols="30"></textarea>
    </label>
  </fieldset>
  ```

## STEP 40

```HTML
<fieldset>
  <label for="profile-picture">Upload a profile picture: <input id="profile-picture" type="file" /></label>
  <label for="age">Input your age (years): <input id="age" type="number" min="13" max="120" /></label>
  <label for="referrer">How did you hear about us?
    <select id="referrer">
      <option value="">(select one)</option>
      <option value="1">freeCodeCamp News</option>
      <option value="2">freeCodeCamp YouTube Channel</option>
      <option value="3">freeCodeCamp Forum</option>
      <option value="4">Other</option>
    </select>
  </label>
  <label for="bio">Provide a bio:
    <textarea id="bio" rows="3" cols="30" placeholder="I like coding on the beach..."></textarea>
  </label>
</fieldset>
```

## STEP 41


```HTML
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name" type="text" required name="first-name"/></label>
  <label for="last-name">Enter Your Last Name: <input name="last-name"id="last-name" type="text" required /></label>
  <label for="email">Enter Your Email: <input name="email" id="email" type="email" required /></label>
  <label for="new-password">Create a New Password: <input name="new-password" id="new-password" type="password" pattern="[a-z0-5]{8,}" required /></label>
</fieldset>
<fieldset>
  <label for="personal-account"><input id="personal-account" type="radio" name="account-type" /> Personal Account</label>
  <label for="business-account"><input id="business-account" type="radio" name="account-type" /> Business Account</label>
  <label for="terms-and-conditions">
    <input id="terms-and-conditions" type="checkbox" name="terms-and-conditions"required /> I accept the <a href="https://www.freecodecamp.org/news/terms-of-service/">terms and conditions</a>
  </label>
</fieldset>
<fieldset>
  <label for="profile-picture">Upload a profile picture: <input id="profile-picture" type="file" name="profile-picture"/></label>
  <label for="age">Input your age (years): <input id="age" name="age" type="number" min="13" max="120" /></label>
  <label for="referrer">How did you hear about us?
    <select id="referrer" name="referrer">
      <option value="">(select one)</option>
      <option value="1">freeCodeCamp News</option>
      <option value="2">freeCodeCamp YouTube Channel</option>
      <option value="3">freeCodeCamp Forum</option>
      <option value="4">Other</option>
    </select>
  </label>
  <label for="bio">Provide a bio:
    <textarea name="bio" id ="bio" rows="3" cols="30" placeholder="I like coding on the beach..."></textarea>
  </label>
</fieldset>
```

## STEp 42

```CSS
body {
  width: 100%;
  height: 100vh;
  margin: 0;
  background-color: #1b1b32;
  color: #f5f6f7;
  /* 42 */
  font-size:16px; 
  font-family:Tahoma;
  /* eos of 42 */
}
```

## STEP 43

```CSS
h1, p{
margin:1em auto;
text-align:center;
}
```

## STEP 44

```CSS
form{
  margin: 0 auto;
  max-width:500px;
  min-width:300px;
  width:60vw;
}
```

## STEp 45

```CSS
fieldset{
  border:none;
  padding:2rem 0;
}
```

## STEP 46

```CSS
fieldset {
  border:none;
  padding: 2rem 0;
  border-bottom:3px solid #3b3b4f;
}
```

## STEP 47

```CSS
fieldset:last-of-type{
  border-bottom:none;
}
```

## STEP 48

```CSS
input, textarea, select{
  width:100%;
  margin:10px 0 0 0;
}
```

## STEP 49

```HTML
<fieldset>
  <label for="personal-account"><input class="inline" id="personal-account" type="radio" name="account-type" /> Personal Account</label>
  <label for="business-account"><input class="inline" id="business-account" type="radio" name="account-type" /> Business Account</label>
  <label for="terms-and-conditions">
    <input class="inline" id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" /> I accept the <a href="https://www.freecodecamp.org/news/terms-of-service/">terms and conditions</a>
  </label>
</fieldset>
```

## STEP 50

- to clear the previos define value, use "unset" keyword in the filed of value.

```CSS
.inline{
  width:unset;
}
```

## STEP 51

```CSS
.inline {
  width: unset;
  margin:0 0.5em 0 0;
}
```

## STEP 52

```CSS
.inline {
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align:middle;
}
```

## STEP 53

```CSS
input, textarea{
  background-color:#0a0a23;
  border:1px solid #0a0a23;
}
```

## STEP 54

```CSS
input, textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color:#FFFFFF;
  min-height:2em;
}
```

## STEP 55

```CSS
/* ... */
input,
textarea,
select {
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em; /* STEP 55  */
}

input, textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color: #ffffff;
/*   min-height: 2em; */
}
/* ....*/
```

## STEP 56

**attribute selector**:

```CSS
input[type="submit"]{
  display:block;
  width:60%;
}
```

## STEP 57

```CSS
input[type="submit"] {
  display: block;
  width: 60%;
  margin:0 auto;

}
```

## STEP 58

```CSS
input[type="submit"] {
  display: block;
  width: 60%;
  margin: 0 auto;
  height:2em;
  font-size:1.1rem;
}
```

## STEP 59

```CSS
input[type="submit"] {
  display: block;
  width: 60%;
  margin: 0 auto;
  height: 2em;
  font-size: 1.1rem;
  background-color:#3b3b4f;
  border-color:white;

}
```

## STEP 60

```CSS
input[type="submit"] {
  display: block;
  width: 60%;
  min-width:300px;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
}
```

## STEP 61

```CSS
input[type="file"]{
  padding:1px 2px;
}
```

## STEP 62

```CSS
form {
  width: 60vw;
  max-width: 500px;
  min-width: 300px;
  margin: 0 auto;
  padding:0 0 2em 0;
}
```

## STEP 63

```CSS
a{
color:#dfdfe2;
}
```