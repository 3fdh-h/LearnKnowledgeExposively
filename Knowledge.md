# 前端
## jQuery——操作html和处理Ajax请求
## BootStrap——响应式布局
## bootbox——弹出美观的提示信息
## open-iconic——操作图标库
## UEditor——开源文本编辑器
## Vue前端视图——构建用户界面的渐进式架构

# Redis

# 工具
## Fiddler——监控和编辑请求
## Postman——请求的编辑和接口调试
## Google调试工具——只能监控

# 扩展知识
## HTTP协议
> HTTP基于TCP/IP协议来传递数据，明文传输，默认端口80,使用URI来传输数据建立连接
> HTTPS为了安全，对HTTP进行补充，使用SSL/TLS来加密数据包，默认端口443
### http的特点
<p>
1、无连接<br>
每次连接只处理一个请求，收到应答后立即断开，节省传输时间<br>
2、媒体独立<br>
只要CS知道如何处理数据，任何类型都可以通过http发送<br>
3、无状态<br>
对事务处理没有记忆能力，如果后续处理需要前面的信息必须重传，会导致连接传送<br>
的数据量增大</p>

### https作用——在不安全的网络上创建一个安全信道
<p>https连线可被信任情况：<br>
1、浏览器正确地实现了 HTTPS 且操作系统中安装了正确且受信任的证书颁发机构；<br>
2、证书颁发机构仅信任合法的网站；<br>
3、被访问的网站提供了一个有效的证书，也就是说它是一个由操作系统信任的证书颁发机构签发的（大部分浏览器会对无效的证书发出警告）；<br>
4、该证书正确地验证了被访问的网站（例如，访问 https://www.runoob.com 时收到了签发给 www.runoob.com 而不是其它域名的证书）；<br>
5、此协议的加密层（SSL/TLS）能够有效地提供认证和高强度的加密。</p>

### 消息结构
> 客户端请求消息
> ![image-20231103170559836](C:\Users\lulul\AppData\Roaming\Typora\typora-user-images\image-20231103170559836.png)
```html
Get /hello.txt HTTP/1.1
User-Agent: curl/7.6.13 libcurl/7.6.3 OpenSSL/0.9.7l zlib/1.2.3
Host: www.example.com
Accept-Language: en, mi
```
> 服务器响应消息
>
> ![image-20231103170855318](C:\Users\lulul\AppData\Roaming\Typora\typora-user-images\image-20231103170855318.png)```

```html
HTTP/1.1 200 OK  # 状态行
Date: Mon, 27 Jul 2009 12:28:53 GMT	
Server: Apache
Last-Modified: Wed, 22 Jul 2009 19:15:56 GMT
ETag: "34aa387-d-1568eb00"
Accept-Ranges: bytes
Content-Length: 51
Vary: Accept-Encoding
Content-Type: text/plain	# 报头
```

### 请求方法

![image-20231103171643841](C:\Users\lulul\AppData\Roaming\Typora\typora-user-images\image-20231103171643841.png)



### 状态码

用于表示状态的代码，常见：

200:请求成功

301:资源被永久转移

404:请求资源不存在

500:内部服务器错误

## HTTP2

## MVC

全名：Model View Controller(MVC)模型——视图——控制器

