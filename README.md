#CSS flex布局
caniuser.com 查看css兼容情况

##盒子模型     box-sizing
	content-box 平时普通的盒子模型,padding border 盒子会变大
		向外扩展 
	border-box 盒子模型，padding,border,盒子模型不变大
		向内扩展
		
##calc(公式)   css计算
	注意：  +-*/ 
	calc(100px-20px)   ×
	calc(100px - 20px)   √
	
	
=========================================================

##父级：
	display:flex;
	添加浏览器前缀：-webkit- 真是的工作中postCss插件自动增加前缀

###父级身上的其他属性：
	####justify-content:	子元素水平排列方式
		center	居中
		space-between	两端对齐
		space-around	子元素拉手对齐
		flex-start	居左
		flex-end	居右
	
	####align-items:	子元素垂直排列
		center	居中
		flex-start 	顶部
		flex-end 底部
		
	####flex-direction:	排列方式
		row	横向排列
		row-reverse	横向翻过排列
		column	纵向排列
		column-reverse	纵向翻过排列
	####

