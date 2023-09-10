#安装虚拟机（VMWare）时遇到的和Hyper-V不兼容问题

#1. 问题显示

在 Windows 10 主机上，VMware Workstation 中显示“VMware Workstation 和 Device/Credential Guard 不兼容”错误 (2146361)

<img src="D:\3.SoftWare-Learning\Typora\typora-user-images\image-20230910084327853.png" alt="image-20230910084327853" style="zoom: 50%;" />

# 2. 解决方法

## 2.1 需下载VMWare17版本

## 2.2 需要关闭内核隔离

1、在设置里面搜索设备安全性

<img src="D:\3.SoftWare-Learning\Typora\typora-user-images\image-20230910084751186.png" alt="image-20230910084751186" style="zoom:50%;" />

2、点击设备安全性李里面的内核隔离

<img src="D:\3.SoftWare-Learning\Typora\typora-user-images\image-20230910084915755.png" alt="image-20230910084915755" style="zoom:50%;" />

3、关闭内存完整性

<img src="D:\3.SoftWare-Learning\Typora\typora-user-images\image-20230910085052507.png" alt="image-20230910085052507" style="zoom:50%;" />

4、重启电脑