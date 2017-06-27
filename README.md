# computernotes
computer notes

## 常见端口

### 22端口 SSH（Secure Shell） - 远程登录协议，用于安全登录文件传输（SCP，SFTP）及端口重新定向

> 为什么 SSH（安全终端）的端口号是 22 呢，这不是一个巧合，这其中有个我（Tatu Ylonen，SSH 协议的设计者）未曾诉说的故事。

- https://linux.cn/article-8476-1.html

### 80端口 HTTP（超文本传输协议）- 用于传输网页

> 80端口是为HTTP（HyperText Transport Protocol)即超文本传输协议开放的，此为上网冲浪使用次数最多的协议，主要用于WWW（World Wide Web）即万维网传输信息的协议。可以通过HTTP地址（即常说的“网址”）加“:80”来访问网站，因为浏览网页服务默认的端口号都是80，因此只需输入网址即可，不用输入“:80”了。

### 443端口 HTTPS - HTTP over TLS/SSL（加密传输）

> 443端口即网页浏览端口，主要是用于HTTPS服务，是提供加密和通过安全端口传输的另一种HTTP。在一些对安全性要求较高的网站，比如银行、证券、购物等，都采用HTTPS服务，这样在这些网站上的交换信息，其他人抓包获取到的是加密数据，保证了交易的安全性。网页的地址以https://开始，而不是常见的http://。

## 3306端口 MySQL数据库系统

## 5432端口 PostgreSQL database system

