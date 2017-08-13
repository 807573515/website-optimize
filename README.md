## 网站性能优化项目

### 使用指南  
将项目clone到本地 可在git中执行下面的命令   
	git clone git@github.com:807573515/website-optimize.git 
然后打开index.html 就OK了  

如果要使用PageSpeed的话 可以直接访问网址[点击这里](https://807573515.github.io/website-optimize/src.index.html)
### 优化内容

#### Part 1: 优化 index.html 的 PageSpeed Insights 得分  
1.压缩了所有图片和html文件 减小网络传输字节数  
2.修改了CSS文件渲染路径 添加媒体查询@media  

#### Part 2: 优化 pizza.html 的 FPS（每秒帧数）
1.优化了updatePosition函数和changePizzaSize函数  
2.压缩了JS文件 减小了网络传输字节数

