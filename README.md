# Linux命令练习 #

学习记录Linux常见命令，按类别做笔记，方便自己备忘查看  

### 一、系统管理命令：

### 二、打包压缩相关命令：

### 三、关机重启命令：
shutdown -h now 关闭系统(1)
init 0 关闭系统(2)
telinit 0 关闭系统(3)
shutdown -h hours:minutes & 按预定时间关闭系统
shutdown -c 取消按预定时间关闭系统
shutdown -r now 重启(1)
reboot 重启(2)
logout 注销 

### 四、用户管理命令：
who 查看当前连接服务器的用户信息
skill -KILL -v conn_name 去除用户登录进程

### 五、文件管理命令： 

ls 查看当前目录下的文件信息    
ll 详细查看当前目录下文件信息   
mkdir dir_name 创建目录   
rmdir dir_name 删除目录   
touch file_name 新建文件   
vi/vim file_name 编辑文件（没有该文件就新建该文件）   
cp source_path target_path 拷贝文件/目录到指定位置
mv source_path target_path 移动文件/目录到指定位置
rm -rf dir_name/file_name  删除文件/目录
cat file_name 查看文件信息
chmod xxx file_name 更改文件/目录系统
diff file_a file_b 比对文件file_a与file_b的差异
tail -f file_name 假如另外一个进程在在写log到file_name中，而你用tail，就可以实时的打印出新的内容

### 六、权限管理命令：

### 七、网络通信命令：

### 八、VIM命令：
