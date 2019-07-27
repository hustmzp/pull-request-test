## Markdown外链图片格式
对Markdown外链图片的语法进行进行测试，效果如下。

**注意：**

- HTML渲染指使用本地浏览器进行HTML渲染，测试用的本地浏览器为Chrome浏览器，版本为70.0.3538.102
- Github渲染指的是在浏览器中打开Github页面时的展示出的内容，测试用的浏览器及版本同上

### 测试内容

- 图片居中
	- 使用`![]()`语法的话貌似`<center>`标签前后不能同时有空行？（前后同时有空行的话HTML渲染及Github渲染都显示的是插入图片的整个语法内容而非显示图片）
	- HTML渲染不能使用`<img src="xxx.xxx" />`语法
<center>
	![描述好像不是必须的啊！！！](https://github.com/hustmzp/external_link_images/raw/master/test/matlab.png)
</center>

- 调整图片显示大小
	- 原图大小
	
		![](https://github.com/hustmzp/external_link_images/raw/master/test/27c54652d8426dc9.jpg)
	- 缩放50%（宽高都缩放50%，后来发现是相对渲染页面的宽度进行缩放而非对原图宽度及高度进行缩放。。。）
	
		<img src="https://github.com/hustmzp/external_link_images/raw/master/test/27c54652d8426dc9.jpg" width="50%" height="50%" />
- 缩放后居中
	- 注意：`<center>`标签内部的图片链接使用该语法时（`<img src="xxx.xxx" />`语法）需缩进一个制表符
	- 这个时候`<center>`标签前后有空行时HTML渲染又没问题了（显示图片而非显示插入图片的语法代码）。。。
	- 但是Github渲染依旧是左对齐。。。

<center>
	<img src="https://github.com/hustmzp/external_link_images/raw/master/test/27c54652d8426dc9.jpg" width="50%" height="50%" />
</center>

- github外链格式
	- png格式（整体缩放50%）

		<img src="https://github.com/hustmzp/external_link_images/raw/master/test/%E5%8D%8E%E4%B8%AD%E7%A7%91%E6%8A%80%E5%A4%A7%E5%AD%A6%E6%A0%A1%E5%BE%BD%E9%AB%98%E6%B8%85.png" width="50%" height="50%" />

	- gif格式

		![monitorsize](https://github.com/hustmzp/external_link_images/raw/master/test/monitorsize.gif)

	- svg格式（不支持）

		![CPCflag](https://github.com/hustmzp/external_link_images/raw/master/test/CPCflag.svg)

