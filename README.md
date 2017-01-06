<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta content="en-us" http-equiv="Content-Language" />
<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
<meta name="viewport" content="width=device-width, initial-scale=0.9">

<title id="title">  
</title>
<script type="text/javascript">
var d = new Date()
var time = d.getHours()
if (time < 24) 
{
document.getElementById("title").innerHTML="Good evening!";
}
if (time < 19) 
{
document.getElementById("title").innerHTML="Good afternoon!";
}
if (time < 12) 
{
document.getElementById("title").innerHTML="Good morning!";
}
if (time < 5) 
{
document.getElementById("title").innerHTML="Go to sleep!";
}
</script>
</head>
<style>

/*下方这句不动它，翻译开始*/

* {
	padding: 0;
	margin: 0;
}


/*翻译
主页整体样式 
文本对齐︰ 中心;
背景色︰ #f1f6ee  使用夜间默认时修改为#000000即可
}
*/
body {
	text-align: center;
    background-image:url('img/bg.jpg') !important;
 /*可换上面的图片地址*/
    background-size: 100% !important;
    background-repeat: no-repeat;
 	background-color: #f1f6ee;
  /*可删上面的固定句语*/
}

/*翻译
书签图标排版目录样式 
宽度︰ 100%;
文本对齐︰ 中心;
填充顶部︰ 15px;
填充底部︰ 15px;
*/

#content {
	width: 100%;
	text-align: center;
	padding-top: 25px;
	padding-bottom: 15px;
}


/*翻译
书签框架样式
-webkit 动画︰ fadeInDown 1s;
动画︰ fadeInDown 1s;
位置︰ 相对应;
显示︰ 显示在内部;
宽度︰ 75px;
边境︰ 0;
*/

.box {
	-webkit-animation: fadeInDown 1s;
	animation: fadeInDown 1s;
	position: relative;
	display: inline-block;
	width: 75px;
	border: 0;
}


/*翻译
书签图标样式
宽度︰ 100%;
高度︰ 100%;
位置︰ 不受限制;
左︰ 0;
顶︰ 0;
*/

.box a {
	width: 100%;
	height: 100%;
	position: absolute;
	left: 0;
	top: 0;
}

/*翻译
书签字体样式
颜色: #232323;使用夜间模式时修改为#eee或者#f2eada即可
高度︰ 1.5em;
线的高度︰ 1.5em;
宽度︰ 72px;
字体大小︰ 0.75em;
白色空间︰ nowrap;
溢出︰ 隐藏;
边距︰ 默认布局;
-webkit 边框顶部右半径︰ 5px;
-webkit 边框底部右半径︰ 5px;
文本溢出︰ 省略;
-o 文本溢出︰ 省略;
气相色谱-质谱-文本-溢出︰ 省略;
填充顶部︰ 3px;
填充底部︰ 8px;
*/

.url {
	color: #232323;
	height: 1.5em;
	line-height: 1.5em;
	width: 72px;
	font-size: 0.75em;
	white-space: nowrap;
	overflow: hidden;
	margin: auto;
	-webkit-border-top-right-radius: 5px;
	-webkit-border-bottom-right-radius: 5px;
	text-overflow: ellipsis;
	-o-text-overflow: ellipsis;
	-ms-text-overflow: ellipsis;
	padding-top: 3px;
	padding-bottom: 8px;
}

/*翻译
字体样式 
宽度︰ 3em;
高度︰ 3em;
最大宽度︰ 72px;
*/

.icon {
	width: 3em;
	height: 3em;
	max-width: 72px;
}

#app-items {
	width: 100%;
	max-width: 400px;
	margin: 0px auto;
	text-align: center;
	background-color: ;
	padding-top: 0px;
	padding-bottom: 23px;
}

.title {
    background-color: ;
    font-size: 16px;
    height: 30px;
    line-height: 30px;
    padding: 0 10px 0 20px;
}

</style>
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

<div class="box">
<a href="file:///storage/emulated/0/Download/via/Ya_ke/homepage2.html"></a>
<p><img class="icon" src="img/shuqian.png" ></p>
<p class="url">书签</p>
</div>
<div class="box">
<a href="folder://"></a>
<p><img class="icon" src="img/past.png" ></p>
<p class="url">列表</p>
</div>

<div class="box">
<a href="http://m.iloveyoulong.com/"></a>
<p><img class="icon" src="img/gongneng.png" ></p>
<p class="url">导航</p>
</div>

<div class="box">
<a href="https://www.google.co.jp/?gfe_rd=cr&ei=cDZFWKvBOfDd8Aef6ZD4CA&gws_rd=ssl"></a>
<p><img class="icon" src="img/search.png" ></p>
<p class="url">谷歌搜索</p>
</div>

<div class="box">
<a href="http://3g.163.com/touch/all?nav=1&version=v_standard"></a>
<p><img class="icon" src="img/news.png" ></p>
<p class="url">新闻</p>
</div>

<div class="box">
<a href="http://www.coolapk.com/"></a>
<p><img class="icon" src="img/kuan.png" ></p>
<p class="url">酷安</p>
</div>

<div class="box">
<a href="http://bbs.zhiyoo.com/forum.php?mod=forumdisplay&fid=2&page=1/"></a>
<p><img class="icon" src="img/google_plus5.png" ></p>
<p class="url">智友</p>
</div>

<div class="box">
<a href="http://www.BiLiBiLi.com/"></a>
<p><img class="icon" src="img/bili.png" ></p>
<p class="url">BiLiBiLi</p>
</div>

<div class="box">
<a href="http://www.qiushibaike.com/"></a>
<p><img class="icon" src="img/qiushi.png" ></p>
<p class="url">糗事百科</p>
</div>

<div class="box">
<a href="http://m.dmzj.com"></a>
<p><img class="icon" src="img/book.png" ></p>
<p class="url">动漫之家</p>
</div>

<!--
如若要添加可复制一段
<div class="box">
<a href="地址"></a>
<p><img class="icon" src="img/icon6.png" ></p>
<p class="url">书签名称</p>
</div>
其中链接在href中如href="地址"建议填写folder://自己创建的文件夹地址，这样创建一次不必再修改
图标文件放置在img文件夹中定义如src="img/icon6.png"
显示的标题在<p class="url">书签名称</p>之间定义如<p class="url">酷安</p>
下方window.location.href =主页搜索引擎地址，目前为自用Pc版百度内部搜索，加上浏览器的顶部搜索即为双搜索，使用更方便

-->

</div>

<div id="app-items">
<div class="title">
            常用工具
</div>
<br />
<div class="box">
<a href="file:///storage/emulated/0/Download/via/Ya_ke/homepage3.html"></a>
<p><img class="icon" src="img/che.png" ></p>
<p class="url">翻墙</p>
</div>

<div class="box">
<a href="http://weather.html5.qq.com/"></a>
<p><img class="icon" src="img/tianqi.png" ></p>
<p class="url">天气</p>
</div>

<div class="box">
<a href="http://m.kuaidi100.com/"></a>
<p><img class="icon" src="img/kuaidi.png" ></p>
<p class="url">快递</p>
</div>

<div class="box">
<a href="http://m.maoyan.com/#type=movies"></a>
<p><img class="icon" src="img/dianying.png" ></p>
<p class="url">猫眼</p>
</div>

<div class="box">
<a href="http://www.365rili.com/qq_brower_calendar/Calendar.html"></a>
<p><img class="icon" src="img/rili.png" ></p>
<p class="url">日历</p>
</div>
