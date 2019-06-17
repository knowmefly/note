- **configure**
	- 新建Makefile文件
- **make**
	- 根据Makefile文件进行源码编译
	- 只针对别编辑的文件进行编译
- **gcc**
	- 【-c】 输出*.o文件 （编译单个文件）
	- 【-o】*.o输出二进制文件（将多个.o文件链接起来生成二进制文件）
	- 单个目标文件、链接、编译
	- 编译从文件
	- 【-lm】：导入函数库
	- 【-O】：编译优化
	- 【-Wall】：严谨编译输出警告信息

## 源码安装步骤
1. 下载解压
2. ./configure --help|more 获取帮助信息
3. ./configure --  命令行参数
4. make clean；make ：清除环境重新编译
5. make check：编译检测
6. make install：安装编译好二进制程序
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA1MTExNjgwMSwyMTA2ODY3NzQwLDg3OT
c4ODM4MywtMTcwNzc1MTUwLC0yMDIxOTQ4MzU4XX0=
-->