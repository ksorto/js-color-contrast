# js-color-contrast

Dynamically changing the text color based on background color contrast

#### Get color contrast
```javascript
let backgroundColor = "#6557cf";
let foreColor = Color.getContrast(backgroundColor);
```
Value for `foreColor` will be:
`#9aa830`

#### Get white/black color based contrast
```javascript
let backgroundColor = "#6557cf";
let foreColor = Color.getContrast(backgroundColor, true);
```
if you want use rgb colors
```javascript
let backgroundColor = "rgb(101, 87, 207)";
let foreColor = Color.getContrast(backgroundColor, true);
```

The second parameter `true` indecates that will be used white/black based constrast

Value for `foreColor` will be:
`#fffff`

