## kernel
偶数稳定版
奇数开发版
- **make mrproper**
	- 删除中间文件同时包括配置文件
- **make menuconfig**
	- 图形界面设置功能选择
	- 无需Xwindow支持
- **make config**
	- 传统编辑模式，一条条设置
- **make oldconfig**
	- 从默认配置选择新的配置
- ** make vmlinux**
	- 编译未压缩的内核
- **make modules**
	- 仅内核模块
- **make bzImage**
	- 编译压缩的内核
- **make all**
	- 编译所有

## 编译步骤
1. 下载内核源码
2. make menuconfig：挑选需要的配置
3. 
4. make clean
5. make bzImage
6. make modules
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMTExMTc5MDQsNjUyNjU4Mzg5LDIwNT
c5NzA5MzksNTE2MzU5NTgzLDc0ODA5NDE2OV19
-->