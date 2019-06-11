- **&**
	- 将任务放入后台运行
- **ctrl+z**
	- 后台暂停运行程序
- **jobs**
	- 显示后台进程（本bash的生命周期内）
- **nohup**
	- 放入后台进程（与用户登录无关）
- **top**
	- 动态查看进程
- **nice**
	- 调整程序优先级
	- renice：重新设定优先级

单项资源分析：
- **netstat**
	- 网络监控
- **dmesg**
	- 分析内核信息
- **vmstat**
	- 检测系统资源变化

- **kill**
	- 杀死后台进程
- **killall**
	- 删除所跟程序所有相关进程
 - **pstree**
	 - 列出进程树
	 - 【-A】：以ASCII字符连接

- **/proc/***
	- 该目录下是内存中的信息
- **fuser**
	- 找到正在使用该文件的程序
- **lsof**
	- 进程打开的文件和使用的设备
- **pidof**
	- 找到某个进程的PID

## SELinux
-安全强化linux
- **DAC**
	- 自主访问控制
- **MAC**
	- 强制访问控制
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExODc2NjYxMDEsLTExNjA3MDg0NzcsLT
E3NDI5Mjc2MTYsMTM5Mzc4NTg5NSwxMjAzMjk0MDE1LDEyMTgw
NTc0ODEsNjA0NzkxODIxLC0xNzgyNTMyMDA3XX0=
-->