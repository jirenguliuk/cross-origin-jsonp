# cross-origin-jsonp
- JSONP是通过 script 标签加载数据的方式去获取数据当做 JS 代码来执行 提前在页面上声明一个函数，函数名通过接口传参的方式传给后台，后台解析到函数名后在原始数据上「包裹」这个函数名，发送给前端。换句话说，JSONP 需要对应接口的后端的配合才能实现。
- 打开终端，输入 node server.js ，浏览器打开 http://localhost:8080/index.html
