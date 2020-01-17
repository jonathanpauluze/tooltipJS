<h1 align="center">TooltipJS</h1>
<h4 align="center">
  A simple tooltip made with Vanilla JS. 
</h4>
<p align="center">
  Check out this <a href="https://jonathanpauluze.github.io/tooltipJS/">example page</a>.
</p>

## :gear: Adding to your project
Clone the project
```
git clone https://github.com/jonathanpauluze/tooltipJS.git
```
In the cloned folder, copy the `tooltip.js` file for your project folder, and link the file in your HTML.
```html
<!-- index.html -->
<body>

<script type="text/javascript" src="tooltip.js"></script>
<body>
```

## :computer: Using the tooltip
To add a tooltip in your element, add the property `data-tooltip-container`.
```html
<!-- index.html -->
<div data-tooltip-container>
  <!-- content... -->
</div>
```

Then add the property `data-tooltip-label` with the text you want in your tooltip box.
```html
<!-- index.html -->
<div
  data-tooltip-container
  data-tooltip-label="Tooltip text here :)"
>
  <!-- content... -->
</div>
```

## :warning: Important
Now the JavaScript is working fine. But we need to add some styles to make the tooltip box work properly. The needed styles are:
```css
.tooltip {
  position: absolute;
}
```

And this is the style in used in the example page:
```css
.tooltip {
  position: absolute;
  width: 140px;
  padding: 15px 10px;
  border-radius: 4px;
  font-family: monospace;
  text-align: center;
  color: #fff;
  background-color: rgba(0, 0, 0, 0.5);
}
```