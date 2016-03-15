# Session

除了使用Cookie，Web应用还是用Session来记录客户状态。Session只存在于服务端，客户端拿到的只是存储在cookie中的JSESSIONID 。

Session何时删除：
* Session超时：超时指的是连续一定时间服务器没有收到该Session所对应客户端的请求，并且这个时间超过了服务器设置的Session超时的最大时间。
* 程序调用HttpSession.invalidate()
* 服务器关闭或服务停止

session会因为浏览器的关闭而删除吗？

不会，session只会通过上面提到的3种方式去关闭。
