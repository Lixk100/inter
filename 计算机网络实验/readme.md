# 计算机网络——配置无线网实验

# 一、  实验目的

(1)掌握无线AP的配置要点。

(2)掌握无线宽带路由器的配置要点。

(3)掌握SSID的概念。

# 二、实验仪器及设备

Windows 操作系统 Packet Tracer 模拟器软件；

 

# 三、           实验原理与内容

实验拓扑图

![1561431536479](C:\Users\MI\AppData\Roaming\Typora\typora-user-images\1561431536479.png)



说明（图中pc2，pc3为表中pc1，pc2）

# 四、          实验步骤

1、给pc1, pc2加上无线网卡。
（1）以pc1为例，先关闭计算机电源，将有线网卡去除加装无线网卡。

![1561431635067](C:\Users\MI\AppData\Roaming\Typora\typora-user-images\1561431635067.png)

2、配置路由器router0

（1）设置f0/0,f0/1的IP及子网掩码

![004](C:\Users\MI\Desktop\计算机网络\004.PNG)

![005](C:\Users\MI\Desktop\计算机网络\005.PNG)

3、在assess point0，tablet pc0和tablet pc1上配置同样的ssid=“ipdata”，在无线路由器及pc上设置相同的ssid="CCNA"，确保建立无线连接。

![1561432111077](C:\Users\MI\AppData\Roaming\Typora\typora-user-images\1561432111077.png)

![1561432117560](C:\Users\MI\AppData\Roaming\Typora\typora-user-images\1561432117560.png)

![1561432126994](C:\Users\MI\AppData\Roaming\Typora\typora-user-images\1561432126994.png)

![010](C:\Users\MI\Desktop\计算机网络\010.PNG)

进行连接测试

![009](C:\Users\MI\Desktop\计算机网络\009.PNG)

![011](C:\Users\MI\Desktop\计算机网络\011.PNG)

# 五、思考

ssid的定义：SSID是Service Set Identifier的缩写，意思是：服务集标识。SSID技术可以将一个无线局域网分为几个需要不同身份验证的子网络，每一个子网络都需要独立的身份验证，只有通过身份验证的用户才可以进入相应的子网络，防止未被授权的用户进入本网络。

 
