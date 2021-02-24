此项目基于HTML/CSS+JavaScript+ECharts.js等技术开发
前端页面文件是index.html
顶部标题下那个时间，编写的文件是./js/time.js(使用原生JS编写)
CSS的animation模块实现部分CSS动画效果
手写的CSS样式在./css/content1.0.css中
通过@media实现屏幕变化时样式的变化
使用jQuery实现了部分响应式界面，控制CSS样式调整页面小模块的宽高等(文件路径./js/mycharts.js)
使用EChart实现漏斗图、柱状图、饼状图等
中国地图使用了china.js
数据文件是./data/da.json

配置环境：
window环境
使用命令行读取到文件根目录
有两种方法查看：
安装node 在根目录执行 http-server -a 127.0.0.1 -p 8000
	然后本地浏览器可以直接通过localhost:8000/index.html查看
安装python 在根目录执行 python -m SimpleHTTPServer 8080
	默认端口号是8000，这里指定了为8080
Linux服务器环境：
直接将文件夹放到tomcat安装目录下的webapp文件夹下
然后启动服务器 
在有网络的浏览器输入：服务器ip地址:8080/webapp下放入文件的文件夹名/index.html

