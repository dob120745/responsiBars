responsiBars
============

html/css for creating color-coded bars at top of display to define current width

<!--insert just below opening body tag-->
<div class="bars"><div class="one"><p>xs: &lt;768px &nbsp; &nbsp; &nbsp; &nbsp; xs: &lt;768px xs: &nbsp; &nbsp; &nbsp; &nbsp; xs: &lt;768px &nbsp; &nbsp; &nbsp; &nbsp; xs: &lt;768px xs: &nbsp; &nbsp; &nbsp; &nbsp; &lt;768px xs: &nbsp; &nbsp; &nbsp; &nbsp; xs: &lt;768px</p></div><div class="two"><p>sm: >=768px</p></div><div class="three"><p>md: >=992px</p></div><div class="four"><p>lg: >=1200px</p></div></div><!-- end bars -->

<!--external css-->
.bars{width:1600px;height:17px;border:1px solid #FFF;position:fixed;z-index:1;}.one, .two, .three, .four{height:15px;}
.one, .two, .three, .four{float:left;}.one{width:767px;border:1px solid red;background:red;}.two{width:225px;border:1px solid yellow;background:yellow;}.three{width:208px;border:1px solid orange;background:orange;}.four{width:398px;border:1px solid lime;background:lime;}.one p, .two p, .three p, .four p{font-size:15px;line-height:12px;}.one p{color:#FFF;}

