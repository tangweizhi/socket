#pomeloclient 客户端 socket

#使用方法

1.script 方式引入文件 socket.js pomeloclient.js

2. 代码

```
`pomelo.removeAllListeners(); // 移除 pomelo 监听事件

var route = ''; // route 为请求标识

pomelo.init({
host: '', // 正式-支持 https 服务器
port: '', // 服务器端口
log: true // 日志
}, function() {
// 初始连接 建立连接
});
});

pomelo.request(route, data, function(data) {
// 发送请求标识返回状态
}

pomelo.disconnect(); // 断开连接

pomelo.on('xxx', function(data){ // 根据 xxx 接收数据

})`
```
