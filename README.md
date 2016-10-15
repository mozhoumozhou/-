<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	</head>
	<body onload="draw('canvas');">
		<canvas id="canvas" width="400" height="300"></canvas>>
		<script>
			function draw(id){
				var canvas=document.getElementById(id);
				if(canvas==null)
					return false;
					var context=canvas.getContext("2d");
					context.fillStyle="#00f";
					context.font="italic 30px sans-serif";
					context.textBaseline="top";
					context.fillText("你好世界",0,0);
					context.font="bold 30px sans-serif";
					context.strokeText("你好世界",0,50);
					var txt="表示宽度";
					var t1=context.measureText("txt");
					
			}
		</script>
	
	</body>
</html>

