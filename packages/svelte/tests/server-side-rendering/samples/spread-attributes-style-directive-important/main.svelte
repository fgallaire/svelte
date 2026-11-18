<script>
	const attrs = { style: 'color: blue' };
	const color = 'red';
</script>

<div style="color: blue" style:color|important={color}></div>
<div {...attrs} style:color|important={color}></div>
<div {...attrs} style:Color={color}></div>
