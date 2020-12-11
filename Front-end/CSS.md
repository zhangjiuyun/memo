# CSS

## 选择器

```css
<style>
	选择器{
		css属性:值;
		css属性:值;
		css属性:值;
	}
</style>
```

## 

```css
<style>
	div{		/*元素选择器 */
		background-color:red;
	}
	.class{		/*类选择器 */
    	background-color:red;
	}
	#id{		/*id选择器 */
    	background-color:red;
	}
</style>
```

**id<class<div**

## 链接方式

### 内联样式表

直接在标签的style里写

```css
<div style="background-color:pink;"></div>
```

### 内部样式表

在head的style标签中写css

```css
<head>
	<style>
		div{
			background-color:red;
		}
	</style>
</head>
```

### 外联样式表

在html文件外写一个.css文件

文件内写css语法就行

html里通过link导入

```css
<head>
	<link rel='stylesheet' type='text/css' href='./style.css'/>
</head>
```

**内联样式表>内部样式表>外联样式表**

## 盒子模型

margin 外边距

 border 边框

padding 内边距

比如给这个盒子加个边框,内边距,外边距，和宽高

```css
#id{
	background-clolr:green;
	border:3px solid black;	/*solid 实线*/
    padding:10px;
    margin:10px;
    width:100px;
    height:100px;
}
```

## 常用标签

```css
div{
	float:left;	/*居左并列浮动排列*/
	border-radius:30px;/*圆角*/
	text-align:center;/*中间文字居中*/
	display:flex;/*让所有弹性盒模型对象的子元素都有相同的长度，且忽略它们内部的内容：*/
	align-items:center;/*居中对齐弹性盒的各项 <div> 元素*/
	justify-content:center/*在弹性盒对象的 <div> 元素中的各项周围留有空白*/
	
}
```

