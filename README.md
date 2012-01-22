# Diashow - a small slideshow

## Example

```html
<html>
	<head>
		<link rel="stylesheet" type="text/css" href="style.css">
		<script src="http://code.jquery.com/jquery-1.7.1.min.js" type="text/javascript"></script>
		<script src="diashow.js" type="text/javascript"></script>
		<script type="text/javascript">
			$(document).ready(function() {
					$(".diashow").initDiashow();
				});
		</script>
	</head>
	<body>
		<div class="diashow">
			<a href="image_01.jpg" title="Yep, im a title ;)">Just some Text</a>
			<a href="image_02.jpg">Text for Users without Javascript</a>
		</div>
	</body>
</html>
```

## Attribution

`images/lightbox-ico-loading.gif` by [Leandro Vieira Pinho](http://leandrovieira.com/projects/jquery/lightbox/)
