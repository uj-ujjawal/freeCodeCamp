# Learn More About CSS Pseudo Selectors By Building A Balance Shee

- [Learn More About CSS Pseudo Selectors By Building A Balance Shee](#learn-more-about-css-pseudo-selectors-by-building-a-balance-shee)
  - [01](#01)
  - [02](#02)
  - [03](#03)
  - [04](#04)
  - [!05](#05)
  - [06](#06)
  - [07](#07)
  - [!08](#08)
  - [!09](#09)
  - [!10](#10)
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
  - [25](#25)
  - [26](#26)
  - [27](#27)
  - [28](#28)
  - [29](#29)
  - [!30](#30)
  - [~31](#31)
  - [32](#32)
  - [!33](#33)
  - [34](#34)
  - [35](#35)
  - [36](#36)
  - [!37](#37)
  - [!38](#38)
  - [39](#39)
  - [40](#40)
  - [41](#41)
  - [!42](#42)
  - [43](#43)
  - [44](#44)
  - [45](#45)
  - [46](#46)
  - [!47](#47)
  - [48](#48)
  - [49](#49)
  - [50](#50)
  - [51](#51)
  - [52](#52)
  - [53](#53)
  - [54](#54)
  - [55](#55)
  - [56](#56)
  - [!57](#57)
  - [!58](#58)
  - [59](#59)
  - [60](#60)
  - [61](#61)
  - [62](#62)
  - [63](#63)
  - [64](#64)
  - [!65](#65)
  - [66](#66)

## 01

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Balance Sheet</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body></body>
</html>
```

## 02

```HTML
<body>
  <main><section></section></main>
</body>
```

## 03

```HTMl
<section>
  <h1><span></span>
</section>
```

## 04

```HTML
<span class="flex">
  <span>AcmeWidgetCorp</span>
  <span>Balance Sheet</span>
</span>
```

## !05

- **aria-hidden**

```HTML
<div id="years" aria-hidden="true"></div>
```

## 06

```HTML
<div id="years" aria-hidden="true">
  <span class="year">2019</span>
  <span class="year">2020</span>
  <span class="year">2021</span>
</div>
```

## 07

```HTML
<div class="table-wrap">
  <table></table>
  <table></table>
  <table></table>
</div>
```

## !08

- HTML tables use the **caption** element to describe what the table is about. The caption element should always be the first child of a table.

> can be positioned with the caption-side CSS property.

```HTML
<table>
  <caption>Assets</caption>
</table>
```

## !09

The thead and tbody elements are used to indicate which portion of your table is the header, and which portion contains the primary data or content.

```HTMl
<table>
  <caption>Assets</caption>
  <thead></thead>
  <tbody></tbody>
</table>
```

## !10

The tr element is used to indicate a table row. Add a tr element within your thead element. In your new tr element, add a td element, followed by three th elements.

```HTML
<thead>
  <tr>
    <td></td>
    <th><th>
    <th><th>
    <th><th>
  </tr>
</thead>
```

## 11

```HTML
<thead>
  <tr>
    <td></td>
    <th><span class="sr-only year">2019</span></th>
    <th><span class="sr-only year">2020</span></th>
    <th class="current"><span class="sr-only year">2021</span></th>
  </tr>
</thead>
```

## 12

```HTML
<tbody>
  <tr class="data"></tr>
  <tr class="data"></tr>
  <tr class="data"></tr>
  <tr class="total"></tr>
</tbody>
```

## 13

```HTML
<tr class="data">
  <th>Cash <span class="description">This is the cash we currently have on hand.</span></th>
  <td>$25</td>
  <td>$30</td>
  <td class="current">$28</td>
</tr>
```

## 14

```HTML
<tr class="data">
  <th>Checking <span class="description">Our primary transactional account.</th>
  <td>$54</td>
  <td>$56</td>
  <td class="current">$53</td>
</tr>
```

## 15

```HTMl
<tr class="data">
  <th>Savings <span class="description">Funds set aside for emergencies.</span></th>
  <td>$500</td>
  <td>$650</td>
  <td class="current">$728</td>
</tr>
```

## 16

```HTML
<tr class="total">
  <th>Total <span class="sr-only">Assets</span></th>
  <td>$579</td>
  <td>$736</td>
  <td class="current">$809</td>
</tr>
```

## 17

```HTML
<table>
  <caption>Liabilities</caption>
  <thead></thead>
  <tbody></tbody>
</table>
```

## 18

```HTML
<table>
  <caption>Liabilities</caption>
  <thead>
    <td></td>
    <th></th>
    <th></th>
    <th></th>
  </thead>
  <tbody>
  </tbody>
</table>
```

## 19

```HTML
<table>
  <caption>Liabilities</caption>
  <thead>
    <tr>
      <td></td>
      <th><span class="sr-only">2019</span></th>
      <th><span class="sr-only">2020</span></th>
      <th><span class="sr-only">2021</span></th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
```

## 20

```HTML
<table>
  <caption>Liabilities</caption>
  <thead>
    <tr>
    <td></td>
    <th><span class="sr-only">2019</span></th>
    <th><span class="sr-only">2020</span></th>
    <th><span class="sr-only">2021</span></th>
    </tr>
  </thead>
  <tbody>
    <tr class="data"></tr>
    <tr class="data"></tr>
    <tr class="data"></tr>
    <tr class="total"></tr>
  </tbody>
</table>
```

## 21

```HTML
<tr class="data">
  <th>Loans <span class="description">The outstanding balance on our startup loan.</span></th>
  <td>$500</td>
  <td>$250</td>
  <td class="current">$0</td>
</tr>
<tr class="data">
</tr>
<tr class="data">
</tr>
<tr class="total">
</tr>
```

## 22

```HTML
<tr class="data">
  <th>Loans <span class="description">The outstanding balance on our startup loan.</span></th>
  <td>$500</td>
  <td>$250</td>
  <td class="current">$0</td>
</tr>
<tr class="data">
  <th>Expenses <span class="description">Annual anticipated expenses, such as payroll.</span></th>
  <td>$200</td>
  <td>$300</td>
  <td class="current">$400</td>
</tr>
<tr class="data">
</tr>
<tr class="total">
</tr>
```

## 23

```HTML
<tr class="data">
  <th>Loans <span class="description">The outstanding balance on our startup loan.</span></th>
  <td>$500</td>
  <td>$250</td>
  <td class="current">$0</td>
</tr>
<tr class="data">
  <th>Expenses <span class="description">Annual anticipated expenses, such as payroll.</span></th>
  <td>$200</td>
  <td>$300</td>
  <td class="current">$400</td>
</tr>
<tr class="data">
  <th>Credit <span class="description">The outstanding balance on our credit card.</span></th>
  <td>$50</td>
  <td>$50</td>
  <td class="current">$75</td>
</tr>
<tr class="total">
</tr>

## 24

```HTML
<tr class="data">
  <th>Loans <span class="description">The outstanding balance on our startup loan.</span></th>
  <td>$500</td>
  <td>$250</td>
  <td class="current">$0</td>
</tr>
<tr class="data">
  <th>Expenses <span class="description">Annual anticipated expenses, such as payroll.</span></th>
  <td>$200</td>
  <td>$300</td>
  <td class="current">$400</td>
</tr>
<tr class="data">
  <th>Credit <span class="description">The outstanding balance on our credit card.</span></th>
  <td>$50</td>
  <td>$50</td>
  <td class="current">$75</td>
</tr>
<tr class="total">
  <th>Total <span class="sr-only">Liabilities</span></th>
  <td>$750</td>
  <td>$600</td>
  <td class="current">$475</td>
</tr>
```

## 25

```HTML
<table>
  <caption>Net Worth</caption>
  <thead></thead>
  <tbody></tbody>
</table>
```

## 26

```HTML
<table>
  <caption>Net Worth</caption>
  <thead>
    <tr>
      <td></td>
      <th><span class="sr-only">2019</span></th>
      <th><span class="sr-only">2020</span></th>
      <th><span class="sr-only">2021</span></th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
```

## 27

```HTML
<table>
  <caption>Net Worth</caption>
  <thead>
    <tr>
    <td></td>
    <th><span class="sr-only">2019</span></th>
    <th><span class="sr-only">2020</span></th>
    <th><span class="sr-only">2021</span></th>
    </tr>
  </thead>
  <tbody>
    <tr class="total"><th>Total <span class="sr-only">Net Worth</span>
    <td>$-171</td>
    <td>$136</td>
    <td class="current">$334</td>
  </tbody>
</table>
```

## 28

```CSS
html{
  box-sizing:border-box;
}
```

## 29

```CSS
body{
  font-family:sans-serif;
  color:#0a0a23;
}
```

## !30

```CSS
span[class~="sr-only"]{
  border:0;
}
```

## ~31

```CSS
span[class~="sr-only"] {
  border: 0;
  clip:rect(1px, 1px, 1px, 1px);
  clip-path:inset(50%);
}
```

## 32

```CSS
span[class~="sr-only"] {
  border: 0;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
  width:1px;
  height:1px;
}
```

## !33

```CSS
span[class~="sr-only"] {
  border: 0;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
  height: 1px;
  width: 1px;
  overflow:hidden;
  white-space:nowrap;
}
```

## 34

```CSS
span[class~="sr-only"] {
  border: 0;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
  height: 1px;
  width: 1px;
  overflow: hidden;
  white-space: nowrap;
  position:absolute;
  padding:0;
  margin:-1px; 
}
```

## 35

```CSS
h1{

  max-width:37.25rem;
  margin:0 auto;
  padding:1.5rem 1.25rem;
}
```

## 36

```CSS
h1 .flex{
  display:flex;
  flex-direction:column-reverse;
  gap:1rem;
}
```

## !37

- `:first-of-type` pseudo selector

```CSS
h1 .flex span:first-of-type{
  font-size:0.7em;
}
```

## !38

- :last-of-type

```CSS
h1 .flex span:last-of-type{
  font-size:1.2em;
}
```

## 39

```CSS
section{
  max-width:40rem;
  margin:0 auto;
  border:2px solid #d0d0d5;
}
```

## 40

```CSS
#years{
  position:sticky;
  display:flex;
  justify-content:flex-end;
  top:0;
}
```

## 41

```CSS
#years {
  display: flex;
  justify-content: flex-end;
  position: sticky;
  top: 0;
  color:#fff;
  background:#0a0a23;
}
```

## !42

- calc()

```CSS
#years {
  display: flex;
  justify-content: flex-end;
  position: sticky;
  top: 0;
  background: #0a0a23;
  color: #fff;
  margin:0 -2px;
  padding:0.5rem calc(1.25rem + 2px) 0.5rem 0;
}
```

## 43

```CSS
#years {
  display: flex;
  justify-content: flex-end;
  position: sticky;
  top: 0;
  background: #0a0a23;
  color: #fff;
  padding: 0.5rem calc(1.25rem + 2px) 0.5rem 0;
  margin: 0 -2px;
  z-index:999; /* 43 */
}
```

## 44

```CSS
#years span[class]{
  font-weight:bold;
  width:4.5rem;
  text-align:right;
}
```

## 45

```CSS
.table-wrap{
  padding:0 0.75rem 1.5rem 0.75rem;
}
```

## 46

```CSS
span:not(.sr-only){
  font-weight:normal;
}
```

## !47

- !important

```CSS
span[class~="sr-only"] {
  border: 0 !important;
   clip: rect(1px, 1px, 1px, 1px) !important; 
  clip-path: inset(50%) !important;
  height: 1px !important;
  width: 1px !important;
  position: absolute !important;
  overflow: hidden !important;
  white-space: nowrap !important;
  padding: 0 !important;
  margin: -1px !important;
}
```

## 48

```CSS
span {
  font-weight: normal;
}
```

## 49

```CSS
table{
  border-collapse:collapse;
  border:0;
}
```

## 50

```CSS
table {
  position:relative;
  border-collapse: collapse;
  border: 0;
  width:100%;
  margin-top:3rem;
}
```

## 51

```CSS
table caption{
  color:#356eaf;
  font-size:1.3em;
  font-weight:normal;
}
```

## 52

```CSS
table caption {
  color: #356eaf;
  font-size: 1.3em;
  font-weight: normal;
  position:absolute;
  top:-2.25rem;
  left:0.5rem;
}
```

## 53

```CSS
tbody td{
width:100vw;
max-width:4rem;
min-width:4rem;
}
```

## 54

```CSS
tbody th{
  width:calc(100% - 12rem);
}
```

## 55

```CSS
tr[class="total"]{
  border-bottom:4px double #0a0a23;
  font-weight:bold;
}
```

## 56

```CSS
tr[class="total"] th {
  text-align:left;
  padding:0.5rem 0 0.25rem 0.5rem;
}
```

## !57

> The key difference between tr[class="total"] and tr.total is that the first will select tr elements where the only class is total. The second will select tr elements where the class includes total.

```CSS
tr.total td{
text-align:right;
padding:0 0.25rem;
}
```

## !58

- `:nth-of-type()` pseudo selectors

```CSS
tr.total td:nth-of-type(3){
  padding:0.5rem;
}
```

## 59

```CSS
tr.total:hover{
background:#99c9ff;
}
```

## 60

```CSS
td.current {
  font-style: italic;
}
```

## 61

```CSS
  tr.data{
  background:linear-gradient(to bottom, #dfdfe2 1.845rem, white 1.845rem);
}
```

## 62

```CSS
tr.data th{
  text-align:left;
  padding-top:0.3rem;
  padding-left:0.5rem;
}
```

## 63

```CSS
tr.data th .description {
  display:block;
  font-style:italic;
  font-weight:normal;
  padding:1rem 0 0.75rem;
  margin-right:-13.5rem;
}
```

## 64

```CSS
/* span {
  font-weight: normal;
} */
```

## !65

- vertical-align

```CSS
tr.data td{
  vertical-align:top;
  text-align:right;
  padding:0.3rem 0.25rem 0;
}
```

## 66

```CSS
tr.data td:last-of-type{
  padding-right:0.5rem;
}
```
