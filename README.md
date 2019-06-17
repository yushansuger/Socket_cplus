﻿# Socket-cplus-
c++
千万级高并发网络通信(Socket协议，跨平台全栈开发)



c++网络编程具体要点包括(要点和开发时间相对应)：



1、简单网络数据传输模型



2、使用结构体数据进行网络传输模型



3、将多次收发数据修改为2次



4、在服务端中加入select模型处理多客户端模型



5、客户端升级为select模型使得每次有新客户端加入时所有客户端都能接受到消息



6、为客户端引入线程 客户端具备输入功能



7、Client可 跨linxu和mac os使用  将linux上面客户端与windows上的服务器相连接



8、将其他平台作为客户端 将linux作为服务端 使用windows客户端访问linux服务端

9、客户端跨平台封装client类与多服务器端通信 windows上测试

10、客户端跨平台封装client类与多服务器通信 linux上测试 — 一个服务端与多个客户端通信

11、服务端跨平台封装server类与多客户端通信 windows-linux上测试 — 一个客户端与多个服务端通信 且可以输入exit退出服务器

12、客户端解决粘包和少包问题

13、服务端解决粘包和少包问题 跨平台

14、突破windows下select网络模型64连接限制 测试10000链接 加入高精度计时器

15、多线程基本概念 了解几个多线程常用的语法

16、多线程分组模拟高频并发数据 使用多个线程同时发送数据

17、多线程经典设计模式 生产者和消费者 解决内存等问题

18、select模型接收数据性能瓶颈与优化

19、Socket API极限测试 测试recv极限

20、Socket API极限测试 测试send极限

21、CellServer数据收发的性能瓶颈

22、添加发送缓冲区-定量发送数据

23、添加发送缓冲区-定时发送数据