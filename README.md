# jquery.Photostack.js

## setup
```html
<script src="//code.jquery.com/jquery-2.1.4.min.js"></script>
<script src="jquery.Photostack.js"></script>
```

##HTML
```html
<ul class="photostack">
  <li><img src="1.jpg"></li>
  <li><img src="2.jpg"></li>
  <li><img src="3.jpg"></li>
</ul>
```
##CSS

```css
.js-photostack { position: relative; }
.js-photostack > * {
  position: absolute;
  top: 0;
  left: 0;
  list-style-type: none;
}
```
##JavaScript
```javascript

$(".photostack").Photostack();
```

##Options
```javascript
// top position to move
top:40,
// left position to move
left:500,
// custom rotation angles
degFrom:-20,
degTo:20
```
