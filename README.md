`jQuery DateValidator`
====================

#**How to use**

It is very simple to use it. 

Download the plugin and the css and do it in yout HTML <head>:

```html
<link rel='stylesheet' href='directory/validator.css'>
<script src='directory/dateValidation.jquery.js'></script>
```

Then, in HTML body:
```html
  <label>Date:</label>
  <input type='text' id='date' maxlength='10'>
  
  	<script>
		$(function() {
			$('#date').dateValidation();
		});
	</script>
```
