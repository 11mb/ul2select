# ul2select

A script to convert any ul/li into a selectbox

## Features

* Keyboard navigation
* Triggers change event on ul
* Keeps value in data-value on ul

## Examples

```html
<ul id="demo_basic" class="demo">
	<li data-value="option_1">
	  <span>Option 1</span>
	</li>
	<li data-value="option_2">
	  <span>Option 2</span>
	</li>
</ul>
```

```javascript
$('#demo_basic').ul2select();
```
