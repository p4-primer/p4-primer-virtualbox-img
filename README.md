# p4-primer-virtualbox-img 仓库说明
本代码库是 **《P4编程入门》** 的配套代码库，包含一个VirtualBox镜像，操作系统是 ubuntu-20.04。
该镜像中已经安装了P4开发环境，读者使用VirtualBox导入镜像创建虚拟机即可使用。
使用方法：
1. 百度网盘下载VirtualBox镜像 https://pan.baidu.com/s/1Ve0ASZxiWjovYnUuAwzqrQ?pwd=9i69
2. 下载并安装 [VirtualBox](https://www.virtualbox.org/)
3. 导入代码库中的镜像 **ubuntu-20.04-p4-primer.ova**，并创建虚拟机
4. 启动虚拟机

**注意：**
* 因为镜像文件超过9G，不能通过github下载，只能通过百度网盘下载。
* 本镜像包含**root**用户和**p4**用户，密码都是**p4**。默认使用p4用户。
* 可以使用图形界面，也可以通过 ssh -l p4 -p 2222 127.0.0.1 登录虚拟机。
* 该镜像中包含了 [p4-primer](https://github.com/p4-primer/p4-primer.git) 代码库中的代码，目录 /home/p4/p4-primer，方便读者使用。
