# Boom
图片爆裂效果<br>
格式：<br>
&lt;div class="main"&gt;<br>
  &lt;img src="1.png" alt="1"&gt;<br>
&lt;/div&gt;<br>
css：<br>
.main{<br>
	width: 1000px;
	margin: 200px auto;
	position: relative;
}<br>
.main img{<br>
	display: block;
	margin: 0 auto;
}<br>
js：<br>
var box=document.querySelector('.main');//父容器<br>
new myBoom(box,30,10);//（父容器，横排个数，竖排个数）


