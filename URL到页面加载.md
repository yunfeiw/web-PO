* 用户输入网址
* DNS查询，将url解析为IP
* 和IP地址建立TCP链接，发送HTTP请求
* 服务器接受请求、查库、读文件等，拼好返回HTTP响应
* 浏览器接收响应，开始渲染
* 解析HTML为dom
* 解析css为css-tree
* dom + css生成 render-tree绘图
* 加载script的js文件
* 执行js


性能 优化方向

1. 少加载文件
2. 少执行js

DNS