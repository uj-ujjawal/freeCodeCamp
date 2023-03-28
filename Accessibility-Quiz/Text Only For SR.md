# Text Only For Screen Reader

There is a common pattern to visually hide text for only screen readers to read.

```CSS
{
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
