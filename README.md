# ScanningLogin
这是一个minecraft扫码登录服务器.
它支持无需关闭游戏即可切换账号

扫码登录视频演示地址：[传送门](https://www.bilibili.com/video/BV1TZ4y1d7i1#reply102370149104?share_source=copy_web)


它需要 客户端MOD、BungeeCord登录验证插件、ScanningLogin扫码登录服务端、配合使用：

客户端MOD下载：
------
[传送门1.12.2-提取码：8888](https://pan.baidu.com/s/1McwX9YWX6uozSbk6fBhF7Q)

[传送门1.7.10未实现](https://www.mcbbs.net/thread-1304978-1-1.html)

BungeeCord登录验证插件下载：
------
[百度云-提取码：8888](https://pan.baidu.com/s/1y5Zh6ZEnqc6s3JOL3y9fqg )

ScanningLogin扫码登录服务端下载：
------
[百度云-提取码：8888](https://pan.baidu.com/s/1NSIS0nBY2j8P5BjKLBDRLw )


扫码登录服务端使用说明：
------
修改扫码登录服务端目录配置文件：\Login\server.properties

示例：

port=6666

http=op1115.6655.la:6666

cdk=MjAyMi0wMy0wMQ==

![1234](https://user-images.githubusercontent.com/38318368/153858296-860f8ff0-7b26-46ed-be95-7b3e885e25b1.png)



客户端MOD使用说明：
------
修改minecraft客户端配置文件：\config\McqwyLogin\Login.cfg

示例：

general {

    S:Login=op1115.6655.la:6666
    
}



BungeeCord登录验证插件使用说明：
------
修改BungeeCord登录验证插件配置文件：\BungeeCord\plugins\Login\server.properties

示例：

port=6666



已实现功能 和 未来功能
------
0.欢迎建议更多功能

1.微信扫码登录√

2.扫码注册√

3.免密登录√

4.修改密码

5.单个微信注册多个账号

6.支持SQL数据库√

7.支持MySql数据库

8.不退出游戏切换账号

9.邮箱找回、修改密码

10.登录数据转换

11.QQ扫码登录

12.无需关闭游戏切换账号√

13.客户端mod支持更多游戏版本
