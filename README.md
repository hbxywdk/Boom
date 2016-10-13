# Boom
图片爆裂效果
格式：
&lt;div class="main"&gt;
  &lt;img src="1.png" alt="1"&gt;
&lt;/div&gt;
css：
.main{
	width: 1000px;
	margin: 200px auto;
	position: relative;
}
.main img{
	display: block;
	margin: 0 auto;
}
js：
var box=document.querySelector('.main');//父容器
new myBoom(box,30,10);//（父容器，横排个数，竖排个数）


