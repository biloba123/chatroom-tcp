# chatroom-tcp
基于scoket(TCP)的网络聊天室

![gif演示（图片有点大）](https://github.com/biloba123/chatroom-tcp/blob/master/imgs/video2gif_20180627_213232.gif)


**设计内容：** 基于TCP协议编程的方式，编写程序模拟网络聊天室的运行过程。\
\
**设计要求：**
1. 采用C/S模式，基于TCP协议编程的方式，使得各个用户通过服务器转发实现聊天的功能。
2. 分为两大模块：客户端模块和服务器端模块。
3. 客户端模块的主要功能：\
1）登陆功能：用户可以注册，然后选择服务器登入聊天室。\
2）显示用户：将在线用户显示在列表中。\
3）接收信息：能接收其他用户发出的信息。\
4）发送信息：能发出用户要发出的信息。
4. 服务器端模块的主要功能：\
1)检验登陆信息：检查登陆信息是否正确，并向客户端返回登陆信息，如信息正确。就允许用户登陆。\
2)显示在线状态：将该用户的状态发给各在线用户。\
3)转发聊天信息：将消息转发给所有在线的用户。

![](https://github.com/biloba123/chatroom-tcp/blob/master/imgs/Screenshot_20180627-212715.png)
![](https://github.com/biloba123/chatroom-tcp/blob/master/imgs/Screenshot_20180627-212732.png)
![](https://github.com/biloba123/chatroom-tcp/blob/master/imgs/Screenshot_20180627-212828.png)
![](https://github.com/biloba123/chatroom-tcp/blob/master/imgs/Screenshot_20180627-212834.png)

