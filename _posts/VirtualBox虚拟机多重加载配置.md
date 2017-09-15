## VB虚拟机多重加载配置 ##

版本信息：virtualbox 5.1.26

配置方法：

1、选中待复制的虚拟机，单击管理 —> 存储介质管理器

![](https://i.imgur.com/y6kptRa.png)


2、点击释放，分配到转为未分配状态

![](https://i.imgur.com/B17in2W.png)


3、此时将C盘下的.vmdk文件移到空间较大的磁盘下（演示中放到了D盘文件夹下）

4、在虚拟介质管理器中点击删除

![](https://i.imgur.com/aoZYPVe.png)


5、回到VirtualBox主界面，点击设置 —> 存储

![](https://i.imgur.com/C5CG2Zc.png)


6、选择控制器挂载硬盘，点击使用现有硬盘，选择我们移动到D盘的虚拟机文件挂载上

![](https://i.imgur.com/o8JGkMf.png)


7、然后在虚拟介质管理中，将介质属性改为多重加载

![](https://i.imgur.com/69GkIKl.png)


8、新建一个linux虚拟机，选项全部选择默认，将刚才移动到D盘的虚拟机文件挂载上

![](https://i.imgur.com/O8ZbBh3.png)

![](https://i.imgur.com/NkXH5cq.png)

9、此时我们就得到了之前虚拟机的一个完美克隆版本，两台虚拟机一模一样~