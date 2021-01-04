## 同源策略
协议 域名 端口 同域

http://www.zhangsan.cn:8081
https://a.zhangsan.cn:8081


## 为什么浏览器不支持跨域
cookie LocalStorage  
DOM元素也有同源策略 iframe
ajax 也不支持跨域

## 实现跨域
- 1. jsonp 
- 2. cors
- 3. postMessage
- 4. window.name
- 5. location.hash
- 6. http-proxy
- 7. nginx
- 8. websocket
- 9. document.domain