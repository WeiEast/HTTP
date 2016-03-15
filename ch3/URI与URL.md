# URI与URL


**URI**

URI是一个相对来说更广泛的概念，URL是URI的一种，是URI命名机制的一个子集，可以说URI是抽象的，而具体要使用URL来定位资源。

Web上的每一种资源如：图片、文档、视频等，都是由URI定位的，这里所谓的定位指的是web上的资源相对于主机服务器来说，存放在服务器上的具体路径。

URL是internet上用来描述信息资源文件的字符串，用在客户程序和服务器上，定位客户端连接服务器所需要的信息，它不仅定位了这个信息资源，而且定义了如何找到这个资源。

URI就是一种资源定位机制，它是比较笼统地定位了资源，并不局限于客户端和服务器，而URL就定位了网上的一切资源，只要是网上的资源，都有唯一的URL.

URN是URL的一种更新形式，统一资源名称(URN, Uniform Resource Name)不依赖于位置，并且有可能减少失效连接的个数。但是其流行还需假以时日，因为它需要更精密软件的支持。

**URL**

URL是Uniform Resource Location的缩写，译为"统一资源定位符"。通俗地说，URL是Internet上用来描述信息资源的字符串，主要用在各种WWW客户程序和服务器程序上。采用URL可以用一种统一的格式来描述各种信息资源，包括文件、服务器的地址和目录等。

URL的格式由下列三部分组成：
 
* 第一部分是协议（或称为服务方式）。
* 第二部分是存有该资源的主机IP地址（有时也包括端口号）。
* 第三部分是主机资源的具体地址，如目录和文件名等。
 
第一部分和第二部分之间用"：//"符号隔开，第二部分和第三部分用"/"符号隔开。第一部分和第二部分是不可缺少的，第三部分有时可以省略。

具体的HTTP URL的格式如下：

scheme://host:port/path

* scheme （Internet资源类型）：指出WWW客户程序用来操作的工具。如“http://”表示WWW服务器，“ftp://”表示FTP服务器，“gopher://”表示Gopher服务器，而“new:”表示Newgroup新闻组。
* host   （服务器地址）：指出WWW页所在的服务器域名或ip。
* Port   （端口）：缺省的端口为80，有时（并非总是这样），对某些资源的访问来说，需给出相应的服务器提供端口号。
* path   （路径）：请求URI，指明服务器上某资源的位置（其格式与DOS系统中的格式一样，通常有目录/子目录/文件名这样结构组成）。与端口一样，路径并非总是需要的。

如果URL中没有给出path，那么当它作为请求URI时，必须以“/”的形式给出，通常这个工作 浏览器自动帮我们完成。

例如：

输入：www.guet.edu.cn

浏览器会自动转换成：http://www.guet.edu.cn/

**URL的不足**

URL最大的缺点是当信息资源的存放地点发生变化时，必须对URL作相应的改变。因此人们正在研究新的信息资源表示方法，例如：URI(Universal Resource Identifier)即"通用资源标识"（参见RFC 1630）、URN（Uniform Resource Name）即"统一资源名"和URC（Uniform Resource Citation）即"统一资源引用符"等。
URI目前还处在进一步的研究当中。研究的方向就是弥补URL目前存在的缺点。 

**名词解释**

URI (uniform resource identifier)统一资源标志符

URL(uniform resource location )统一资源定位符（或统一资源定位器）

URN(uniform resource name )统一资源命名

URC（Uniform Resource Citation）统一资源引用符

参考资料：

http://www.jb51.net/article/43597.htm

http://www.jb51.net/article/5353.htm

http://www.cnblogs.com/gaojing/archive/2012/02/04/2413626.html

http://blog.csdn.net/niuox/article/details/7312843

