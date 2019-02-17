# 第二章：表格操作

### 表格添加与删除
- 添加行时应注意列数要与其他行保持一致
- 添加列时应注意在每一行对应位置添加td单元格

### 表格结构标签
- 浏览器在解析表格标签时会整体解析后加载，如果表格结构负责，则加载时间会比较长，影响用户体验。
- 可以使用表格结构标签将表格划分为三部分：表头、主体、脚注。浏览器则会分别解析加载，提升用户体验。
- 三个标签应同时存在同时使用。
- **浏览器在解析表格时会按照thead、tbody、tfoot顺序解析(即使书写顺序不一致，浏览器也会按顺序强制解析)。**
- **表格结构标签并不影响表格布局，只处理加载性能的优化。**

|标签|作用|
|---:|:---|
|thead|表格的头注(放标题之类的内容)|
|tbody|表格的主体(放数据主体)|
|tfoot|表格的脚注(放表格的脚部注释)|

### table标签属性

|属性|值|描述|
|:---:|:---:|:---|
|width|pixels、%|规定表格的宽度|
|align|left、center、right|表格相对周围元素的对其方式|
|border|pixels|规定表格边框的宽度|
|bgcolor|rgb(x,x,x)、#xxxxxx、colorname|表格的背景颜色|
|cellpadding|pixels、%|单元边沿与其内容之间的空白|
|cellspacing|pixels、%|单元格之间的空白|
|frame|[属性值](http://www.w3school.com.cn/tags/att_table_frame.asp)|规定外边框的哪个部分是可见的|
|rules|[属性值](http://www.w3school.com.cn/tags/att_table_rules.asp)|规定内边框的哪个部分是可见的|

*frame与rules属性可用css替代*

### tr标签属性

|属性|值|描述|
|:---:|:---:|:---|
|align|left、center、right、justify、char|行内容的水平对齐|
|valign|top、middle、bottom、baseline|行内容的垂直对齐|
|bgcolor|rgb(x,x,x)、#xxxxxx、colorname|行的背景颜色|

### td、th单元格标签属性

|属性|值|描述|
|:---:|:---:|:---|
|align|left、center、right、justify、char|单元格内容的水平对齐|
|valign|top、middle、bottom、baseline|单元格内容的垂直对齐|
|bgcolor|rgb(x,x,x)、#xxxxxx、colorname|单元格的背景颜色|
|width|pixels、%|单元格的宽度|
|height|pixels、%|单元格的高度|

### thead、tbody、tfoot标签属性
|属性|值|描述|
|:---:|:---:|:---|
|align|left、center、right、justify、char|内容的水平对齐|
|valign|top、middle、bottom、baseline|内容的垂直对齐|

### 表格属性外部参考资料
|标签|参考资料|
|:---:|:---|
|table|[点击查看](http://www.w3school.com.cn/tags/tag_table.asp)|
|tr|[点击查看](http://www.w3school.com.cn/tags/tag_tr.asp)|
|th|[点击查看](http://www.w3school.com.cn/tags/tag_th.asp)|
|td|[点击查看](http://www.w3school.com.cn/tags/tag_td.asp)|
|thead|[点击查看](http://www.w3school.com.cn/tags/tag_thead.asp)|
|tbody|[点击查看](http://www.w3school.com.cn/tags/tag_tbody.asp)|
|tfoot|[点击查看](http://www.w3school.com.cn/tags/tag_tfoot.asp)|

### 预览本章内容代码
[点击预览](index.html)

### 编程练习
##### 2-8 编写一段代码，实现边框为1，带有标题和表头的表格。效果图：
![课程表](https://climg.mukewang.com/58c10ad20001c3ef03000203.jpg)

要求：
1. 创建一个5行4列的表格，边框宽度为1。
2. 根据效果图，添加相应内容。
3. 将第一行设置成表头。
4. 给表格添加标题“课程表”。

[点击查看我的答案](2-8.html)