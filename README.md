## 学习标签里的全局属性
* <h3>class<h6> 例如class="aa" .aa或者class="aa"来定位获取元素
* <h3>contenteditable<h6> 可以让任何的元素标签里进行编辑
* <h3>hidden<h6> 全局属性 hidden 是一个布尔属性，表示一个元素尚未或者不再相关。例如，它可以被用来隐藏一个页面元素直到登录完毕。如果一个元素设置了这个属性，它就不会被显示。
* <h3>id<h6> id 全局属性定义了一个全文档唯一的标识符（ID）。它用于在链接（使用片段）、脚本和样式（通过 CSS）中辨识元素。
*  <h3>style<h6>元素包含文档的样式信息或者文档的部分内容。默认情况下，该标签的样式信息通常是CSS的格式。如果js和标签里有style和style的话，优先级js>标签>style
*  <h3>tabindex<h6>注意在更改 tabindex 为“0”同时需要把之前选中过的那项设置tabindex="-1"。这个方法包含在键盘事件里面通过程序移动焦点以及更改 tabindex 到当前焦点中的那项上。
*  <h3>title<h6>全局属性 title 包含代表与它所属的元素有关的咨询信息的文本。 title 属性的主要用途是为辅助技术标注 iframe元素。
小技巧：如果当文字溢出时，加入这些css样式即可：
```css
white-space : nowrap;
text-overflow : ellipsis;
overflow : hidden;
```