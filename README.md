关于web 日志的分析
==

web日志格式
--

200.203.64.151 - - [21/Nov/2017:15:50:00 +0800] "GET /index.php HTTP/1.1" 200 1961 Mozilla/4.0 (compatible; MSIE 9.0; Windows NT 6.1)
此条日志中所包含的数据主要有：远程主机IP地址，占位符\*2，服务器完成请求处理时间[日/月/年:时:分:秒 +时区]，请求方法， 请求资源URL， 协议， 返回状态， 发送给客户端总字节数，UserAgent

