# page_scroll
这是一个全屏翻滚的插件
可以支持横向滚动和竖向滚动。
<blockquote>
调用插件方法
例子：
$("[data-PageSwitch]").PageSwitch({<br>
	direction:'herizontal'<br>
});<br>
PageSwitch提供了以下参数：<br>
selectors : {//jquery对象选择器设置<br>
	sections : ".sections",//页面容器对象<br>
	section : ".section",//单个页面对象<br>
	page : ".pages",//右侧滚动圆点对象<br>
	active : ".active"//右侧当前选中圆点样式<br>
},<br>
index : 0,//起点页数<br>
easing : "ease",//动画速度函数<br>
duration : 500,//动画时长<br>
loop : false,//是否能够循环滚动<br>
pagination : true,//是否显示页面圆点<br>
keyboard : true,//是否支持键盘滚动<br>
direction : "vertical",//水平滚动(herizontal)还是竖直滚动（vertical）<br>
callback : ""//回调函数<br>

</blockquote>
