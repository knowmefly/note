- **dkpg**
	- Debian提供的软件：B2D、ubuntu
	- APT在线升级
- **RPM**
	- /var/lib/rpm/：安装软件信息
	- Red Hat提供
	- Fedora、CentOS、SuSe
	- YUM在线升级
	- 必须相同Linux环境
	- 可以跟一些特殊参数 ：执意自行时
	- 【-q】：查询是否已安装软件
	- 【-qi】：给出软件相关说明
	- 【-qR】：列出软件相关依赖
	- 【-qf】：找出文件是由哪个软件提供的
	- 【-Va】：查找可能被修改的文件
	- 【--rebuilddb】：重建数据库
- **SRPM**
	- 源码编译机制
	- Source RPM
	- 可以自定义参数
	- rebuild：编译不安装
	- recompile：编译后安装
	- *.spec：包含大多数信息

## yum
- **yum**
	- /etc/yum.repos.d/CentOS-Base.repo：容器
	- 【search】：查找软件
	- 【info】：输出软件介绍
	- 【list】：服务器提供软件名称
	- 【list updates】：列出本地可更新软件



rp-pppoe -        3.11   -            5            .el7.x86_64        .rpm
软件名称      软件的版本  发布次数    适合的硬件平台  扩展名
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2NzQ0Nzc5MDMsNDc3NjQzNTc2LDIxMz
A2NTY0MTQsMjMzNDU5NDE4LDM5OTY3MDcxMSwtMTI2NjIzOTI3
LDc0NjY4MTcwNSwtNDY3MDA4Mjk5LDIwMDEwOTEzMTAsLTIwOD
g3NDY2MTJdfQ==
-->