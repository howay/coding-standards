# 模板编写规范

## 缩进和编码
1.HTML统一采用UTF-8编码；  
2.必须使用Tab进行代码缩进，建议设置Tab为4个空格的宽度，而不是4个空格；

## 书写规则
1.HTML代码标签一律采用小写字母形式，杜绝任何使用大写字母的方式；  
2.所有HTML标签参数赋值需使用双引号“" "”包含，例如：  
应当使用`<input type="text" name="test" value="ok" />`,  
而绝对不能使用`<input type=text name=test value=ok />`；  
3.非成对标签必须以“/>”结尾，如：`<input …/>，<img …/>`；  
4.块标签和行内标签的属性按照以下顺序写：

	<div id="" class="" model-node="" model-args="" …></div>

5.input标签的属性按照以下顺序书写：

	<input type="" name="" id="" class="" event-node="" event-args="" … />

## 模板语法规范
模板中的变量输出统一采用使用框架的规范；
