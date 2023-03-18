# Learn Typography by Building a Nutrition Label

- [Learn Typography by Building a Nutrition Label](#learn-typography-by-building-a-nutrition-label)
  - [00](#00)
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
  - [46](#46)
  - [47](#47)
  - [48](#48)
  - [!49](#49)
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

## 00

```HTML
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Nutrition Label</title>
</head>

<body>

</body>
</html>
```

## 01

```HTMl
<body>
  <h1>Nutrition Facts</h1><!-- Step 1 -->
</body>
```

## 02

```HTML
<body>
  <h1>Nutrition Facts</h1>
  <p>8 servings per container</p> <!-- Step2 -->
</body>
```

## 03

```HTML
<body>
  <h1>Nutrition Facts</h1>
  <p>8 servings per container</p>
  <p>Serving size 2/3 cup (55g)</p>
</body>
```

## 04

```HTML
<head>
  <meta charset="UTF-8">
  <title>Nutrition Label</title>
  <!-- Step 4 -->
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:400,700,800">
  <!-- Step 4 -->
</head>
```

## 05

```CSS
body{
font-family:"Open Sans", sans-serif;
}
```

## 06

```CSS
html{
  font-size:16px;
}
```

## 07

```HTML
<body>
  <div class="label">
    <h1>Nutrition Facts</h1>
    <p>8 servings per container</p>
    <p>Serving size 2/3 cup (55g)</p>
  </div>
</body>
```

## 08

```CSS
.label{
  border:2px solid black;
}
```

## 09

```CSS
.label {
  border: 2px solid black;
  width:270px; /* Step 9 */
}
```

## 10

```CSS
.label {
  border: 2px solid black;
  width: 270px;
  /* Step 10 */
  margin: 20px auto;
  padding: 0 7px;
  /* eos */
}
```

## 11

```CSS
*{
  box-sizing:border-box;
}
```

## 12

> **Note**:
>
> - use of h1, h2, and similar tags determine the semantic structure of your HTML.
> - adjust the CSS of these elements to control the visual flow and hierarchy

```CSS
h1{
  font-weight:800;
}
```

## 13

```CSS
h1 {
  font-weight: 800;
  text-align:center; /* Step 13 */
}
```

## 14

```CSS
h1 {
  font-weight: 800;
  text-align: center;
  margin: -4px 0; /* Step 14 */
}
```

## 15

```CSS
p{
  margin:0;
}
```

## 16

```HTML
<div class="label">
  <h1>Nutrition Facts</h1>
  <div class="divider"></div> <!-- Step 16 -->
  <p>8 servings per container</p>
  <p>Serving size 2/3 cup (55g)</p>
</div>
```

## 17

```CSS
.divider{
  border-bottom:1px solid #888989;
  margin:2px 0;
}
```

## 18

```CSS
h1 {
  font-weight: 800;
  text-align: center;
  margin: -4px 0;

  letter-spacing:0.15px; /* Step 18 */
}
```

## 19

```HTML
  <div class="label">
    <h1>Nutrition Facts</h1>
    <div class="divider"></div>
    <p>8 servings per container</p>
    <p class="bold">Serving size 2/3 cup (55g)</p>  <!-- step 19  -->
  </div>
```

## 20

```CSS
h1 {
   /*  font-weight: 800; */ /* Step 20 : font-weight removed */
  text-align: center;
  margin: -4px 0;
  letter-spacing: 0.15px;
}
/* Step 20 */
.bold{
  font-weight:800;
}
/* eos */
```

## 21

```HTML
<div class="label">
  <h1 class="bold">Nutrition Facts</h1> <!-- Step 21 -->
  <div class="divider"></div>
  <p>8 servings per container</p>
  <p class="bold">Serving size 2/3 cup (55g)</p>
</div>
```

## 22

```HTML
<div class="label">
    <h1 class="bold">Nutrition Facts</h1>
    <div class="divider"></div>
    <p>8 servings per container</p>
    <p class="bold">Serving size <span>2/3 cup (55g)</span></p> <!-- Step 22 -->
  </div>
```

## 23

```CSS
p {
  margin: 0;
  /* Step 23 */
  display:flex;
  justify-content:space-between;
  /* eos */
}
```

## 24

```HTML
<div class="label">
  <header>
  <h1 class="bold">Nutrition Facts</h1>
  <div class="divider"></div>
  <p>8 servings per container</p>
  <p class="bold">Serving size <span>2/3 cup (55g)</span></p>
  </header
</div>
```

## 25

```CSS
header h1 {
  text-align: center;
  margin: -4px 0;
  letter-spacing: 0.15px
}
```

## 26

```HTML
<div class="divider large"></div>
```

## 27

```CSS
.large{
  height:10px
}

.large, .medium{
  background-color:black;
}
```

## 28

```CSS
.large, .medium {
  background-color: black;
  border:0;
}
```

## 29

```HTML
<div class=calories-info></div>
```

## 30

```HTML
<div class="calories-info">
  <div class=left-container>
    <h2 class="bold small-text">Amount per serving
    </h2>
</div>
```

## 31

```CSS
.small-text{
  font-size:0.85rem;
}
```

## 32

```CSS
.calories-info h2{
  margin:0;
}
```

## 33

```HTML
<div class="calories-info">
  <div class="left-container">
    <h2 class="bold small-text">Amount per serving</h2>
    <p>Calories</p>
  </div>
    <span> 230</span>
</div>
```

## 34

```CSS
.calories-info{
  display:flex;
  justify-content:space-between;
  align-items:flex-end;
}
```

## 35

```CSS
.left-container p{
  margin:-5px -2px;
  font-size:2em;
  font-weight:700;
}
```

## 36

```CSS
.calories-info span{
  font-size:2.4em;
  font-weight:700;
}
```

## 37

```CSS
.calories-info span {
  font-size: 2.4em;
  font-weight: 700;
  margin:-7px -2px; /* Step 37 */
}
```

## 38

```HTML
<div class="divider medium"></div>
```

## 39

```CSS
.medium{
  height:5px;
}
```

## 40

```HTML
<div class="divider medium"></div>
<div class="daily-value small-text">
  <p class="bold right">% Daily Value *</p>
</div>
```

## 41

```CSS
.right {
  justify-content: flex-end;
}
```

## 42

```HTMl
<div class="daily-value small-text">
  <p class="bold right">% Daily Value *</p>
  <div class="divider medium"></div> <!-- Step 42 -->
</div>
```

## 43

```HTMl
<div class="daily-value small-text">
  <p class="bold right">% Daily Value *</p>
  <div class="divider"></div>
  <!-- Step 43 -->
  <p><span><span class="bold">Total Fat</span> 8g </span><span class="bold">10%</span></p>
  <!-- eos -->
</div>
```

## 44

```HTMl
<div class="daily-value small-text">
  <p class="bold right">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p> Saturated Fat 1g <span class="bold">5%</span></p> <!-- Step 43 -->
</div>
```

## 45

```HTML
<div class="daily-value small-text">
  <p class="bold right">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <!-- Step 44 -->
  <p class="indent">Saturated Fat 1g <span class="bold">5%</span></p>
  <!-- eos -->
</div>
```

## 46

```CSS
.indent{
  margin-left:1em;
}
```

## 47

```CSS
.daily-value p{
  border-bottom:1px solid #888989;
}
```

## 48

```HTMl
<div class="daily-value small-text">
  <!-- 48 -->
  <p class="bold right no-divider">% Daily Value *</p>
  <!-- eos -->
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <!-- 48 -->
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <!-- eos -->
</div>
```

## !49

- The :not pseudo-selector
- [1](https://css-tricks.com/almanac/selectors/n/not/)
- [2](https://developer.mozilla.org/en-US/docs/Web/CSS/:not?retiredLocale=tr)

```CSS
.daily-value p:not(.no-divider) {
  border-bottom: 1px solid #888989;
}
```

## 50

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div> <!-- 50 -->
</div>
```

## 51

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p> <!-- 50 -->
</div>
```

## 52

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div> <!-- 52 -->
</div>
```

## 53

```HTMl
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <!-- 53 -->
  <p><span><span class="bold">Cholesterol</span> 0mg </span><span class="bold">0%</span></p>
  <!-- eos -->
</div>
```

## 54

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <!-- 54 -->
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <!-- eos -->
</div>
```

## 55

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
</div>
```

## 56

```HTMl
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
<p class="indent daily-value no-divider">Dietary Fiber 4g</p>
<div class="divider"></div>
</div>
```

## 57

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
  <p class="indent no-divider">Dietary Fiber 4g</p>
  <div class="divider"></div>
  <p class="indent no-divider">Total Sugars 12g</p>
  <div class="divider"></div>

</div>
```

## 58

```HTML
<div class="divider double-indent"></div>
```

## 59

```CSS
.double-indent{
  margin-left:2em;
}
```

## 60

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
  <p class="indent no-divider">Dietary Fiber 4g</p>
  <div class="divider"></div>
  <p class="indent no-divider">Total Sugars 12g</p>
  <div class="divider double-indent"></div>
  <!-- 60 -->
  <p class="double-indent daily-divider no-divider">
Includes  10g Added Sugars
<span class="bold">20%</span></p>
<div class="divider"></div>
<!-- eos -->
</div>
```

## 61

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
  <p class="indent no-divider">Dietary Fiber 4g</p>
  <div class="divider"></div>
  <p class="indent no-divider">Total Sugars 12g</p>
  <div class="divider double-indent"></div>
  <p class="double-indent no-divider">Includes 10g Added Sugars <span class="bold">20%</span>
  <div class="divider"></div>
  <!-- 61 -->
  <p class="indent no-divider"><span><span class="bold">Protein</span> 3g</span></p>
  <div class="divider large"></div>
  <!-- eos -->
</div>
```

## 62

```HTML
 <div class="daily-value small-text">
      <p class="bold right no-divider">% Daily Value *</p>
      <div class="divider"></div>
      <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
      <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
      <div class="divider"></div>
      <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
      <div class="divider"></div>
      <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
      <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
      <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
      <p class="indent no-divider">Dietary Fiber 4g</p>
      <div class="divider"></div>
      <p class="indent no-divider">Total Sugars 12g</p>
      <div class="divider double-indent"></div>
      <p class="double-indent no-divider">Includes 10g Added Sugars <span class="bold">20%</span>
      <div class="divider"></div>
      <p class="no-divider"><span class="bold">Protein</span> 3g</p>
      <div class="divider large"></div>
      <p>Vitamin D 2mcg <span>10%</span></p> <!-- step 63 -->
    </div>
```

## 63

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
  <p class="indent no-divider">Dietary Fiber 4g</p>
  <div class="divider"></div>
  <p class="indent no-divider">Total Sugars 12g</p>
  <div class="divider double-indent"></div>
  <p class="double-indent no-divider">Includes 10g Added Sugars <span class="bold">20%</span>
  <div class="divider"></div>
  <p class="no-divider"><span class="bold">Protein</span> 3g</p>
  <div class="divider large"></div>
  <p>Vitamin D 2mcg <span>10%</span></p>
  <p>Calcium 260mg <span>20%</span></p>
  <p>Iron 8mg <span>45%</span></p>
</div>
```

## 64

```HTML
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
  <p class="indent no-divider">Dietary Fiber 4g</p>
  <div class="divider"></div>
  <p class="indent no-divider">Total Sugars 12g</p>
  <div class="divider double-indent"></div>
  <p class="double-indent no-divider">Includes 10g Added Sugars <span class="bold">20%</span>
  <div class="divider"></div>
  <p class="no-divider"><span class="bold">Protein</span> 3g</p>
  <div class="divider large"></div>
  <p>Vitamin D 2mcg <span>10%</span></p>
  <p>Calcium 260mg <span>20%</span></p>
  <p>Iron 8mg <span>45%</span></p>
  <!-- 64 -->
  <p class="daily-value no-divider">Potassium 235mg<span>6%</span></p>
  <!-- eos -->
</div>
```

## 65

```HTML
<div class="divider medium"> </div>
<p class="note">* The % Daily Value (DV) tells you how much a nutrient in a serving of food contributes to a daily diet. 2,000 calories a day is used for general nutrition advice.</p>
```

## 66

```CSS
.note{
  font-size:0.6rem;
  margin:5px 0;
}
```

## 67

```CSS
.note {
  font-size: 0.6rem;
  margin: 5px 0;
  padding:0 8px;
  text-indent:-8px;
}
```

