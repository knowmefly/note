## 程序管理
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
安全强化linux
- **DAC**
	- 自主访问控制
- **MAC**
	- 强制访问控制
- **getenforce**
	- 查看是否开启SELinux
	- vim  /etc/selinux/config 开启
- **sestatus**
	- 查看SELinux状态
- **setenforce**
	- 修改状态 0宽容，1强制
- **chcon**
	- 修改SELinux下文件权限
- **restorecon**
	- 重新修改该目录下的文件权限
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM3MTk0MzkwMCwtNTkwMDg4NzcyLDYyNT
EwMTE3MCwtODk2MTQ1MTI4LC0xOTQ5MTkzNzgxLC0xMTYwNzA4
NDc3LC0xNzQyOTI3NjE2LDEzOTM3ODU4OTUsMTIwMzI5NDAxNS
wxMjE4MDU3NDgxLDYwNDc5MTgyMSwtMTc4MjUzMjAwN119
-->