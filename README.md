# SecurityRPC
Security RPC framework via rsa cryptography

#1、使用msgpack为底层序列化工具，比Pb快四倍。
#2、使用RSA非对称加密，传输过程中数据内容绝对安全。
#3、使用Mina作为通信底层，实现数据可靠传输。
#4、LogicServer端数据库访问使用Hibernate，兼容MySQL、Oracle以及MS SqlServer。
#5、客户端只要导入SDK，并且与服务器端LogicServer约定好POJO类，即可以使用，轻量，完全无侵入。
#6、支持添加、查询等命令。
#7、提供客户端示例代码，让开发者更加轻松上手。



