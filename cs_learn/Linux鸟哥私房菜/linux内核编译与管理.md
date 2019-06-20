## kernel
偶数稳定版
奇数开发版

安装kernel-devel软件

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
3. make mrporper
4. make clean
5. make bzImage
6. make modules
7. make modules_install :建立内核相关模块 	 	
8. ll /lib/modules/
9. cp /usr/src/kernels/linux-* /arch/x86/boot/bzImage > /boot/vmlinuz */
10. .config 最好也复制过来
11. mkinitrd -v /boot/initrd-*.img  *.【版本-名称】
12. vim /boot/grub2/menu.lst ：添加开机启动选项

编译单一模块
13. 正常编译安装
14. depmod -a ：模块建立相关性
 
编译内核模块
 1. make menuconfig：修改配置菜单
15. make fs/ntfs：编译单个模块
16. 将编译的文件（ntfs.ko）复制到/lib/modules/[name]/kernel/fs/ntsf/
17. depmod -a ：模块建立相关性
18. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE2MDA0MjcxMSwxMDk0NTU1MDQ2LC0xND
U1MDk0OTA3LDY1MjY1ODM4OSwyMDU3OTcwOTM5LDUxNjM1OTU4
Myw3NDgwOTQxNjldfQ==
-->