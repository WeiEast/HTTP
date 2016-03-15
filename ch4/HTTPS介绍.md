# HTTPS介绍

**HTTP的不足**
* 通信使用不加密的明文，内容可能会被窃听。
* 不验证通信方的身份，因此有可能遭遇伪装。
* 无法证明报文的完整性，有可能已遭篡改。

改进，采用HTTPS

**HTTPS=HTTP+加密+认证+完整性保护**

HTTPS相对于HTTP有哪些不同呢？其实就是在HTTP跟TCP中间加多了一层加密层TLS/SSL。

TLS/SSL：通俗的讲TLS、SSL其实是类似的东西，SSL是个加密套件，负责对HTTP的数据进行加密。
TLS是SSL的升级版。现在提到HTTPS，加密套件基本指的是TLS。

一般来说，加密分为对称加密、非对称加密（也叫公开密钥加密）。
对称加密简单说就是加密和解密都是用的同一把钥匙。非对称加密有两把钥匙，即公开密钥和私有密钥。

**HTTPS使用混合加密方式：对称加密和非对称加密的并用的方式。**

HTTPS通信时序图：

![HTTPS通信时序图](/img/https.png "HTTPS通信时序图")

参考资料：

http://blog.csdn.net/fangaoxin/article/details/6952954

http://www.jb51.net/article/14566.htm

