# p4-primer-virtualbox-img 仓库说明
本代码库是 **《P4编程入门》** 的配套代码库，包含一个VirtualBox镜像，操作系统是 ubuntu-20.04。
该镜像中已经安装了P4开发环境，读者使用VirtualBox导入镜像创建虚拟机即可使用。
使用方法：
1. 第一步 git clone https://github.com/p4-primer/p4-primer-virtualbox-img.git
2. 第二步 下载并安装 [VirtualBox](https://www.virtualbox.org/)
3. 第三步 导入代码库中的镜像 **ubuntu-20.04-p4-primer.ova**，并创建虚拟机
4. 第四步 启动虚拟机

**注意：**
* 本镜像包含root用户和p4用户，密码都是p4。默认使用p4用户。
* 该镜像中包含了 [p4-primer](https://github.com/p4-primer/p4-primer.git) 代码库中的代码，目录 /home/p4/p4-primer，方便读者使用。
