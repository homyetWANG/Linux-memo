# Linux-memo

Linux 常用命令

* SSH  <br>
生成key：  <br>
$ ssh-keygen -t dsa -P '' -f ~/.ssh/id_dsa  <br>
$ cat ~/.ssh/id_dsa.pub >> ~/.ssh/authorized_keys  <br>
 -t   密钥类型可以用 -t 选项指定。  <br>
          如果没有指定则默认生成用于SSH-2的RSA密钥。 <br>
 -f filename 指定密钥文件名。  <br>

* 解压包： <br>
sudo tar zxvf ./jdk-7-linux-i586.tar.gz  -C /usr/lib/jvm <br>
* 文件复制：（jdk复制到opt中） <br>
sudo cp -r  jdk/ /usr <br>
* 文件移动（重命名） <br>
sudo mv jdk opt <br>
(有的时候没有权限，所以必须加上sudo) <br>

* chown <br>
文件更改所有者(下面为更改hadoop文件夹的权限) <br>
sudo chown -R  aboutyun:aboutyun  hadoop <br>

* grep查看端口是否被暂用 <br>
sudo netstat -ap | grep 8080 <br>
sudo netstat -ant|grep 3306 <br>
https://linux.cn/article-2250-1-weixin.html <br>

* 远程复制 <br>
scp authorized_keys aboutyun123@master:~/.ssh/authorized_keys_from_ubuntu <br>

软件下载 <br>

Linux JDK、WinScp <br>
链接：http://pan.baidu.com/s/1i3vkG53 密码：cjuh <br>

Win7 jdk、eclipse <br>
链接：http://pan.baidu.com/s/1o6yU4B4 密码：w10u <br>
链接：http://pan.baidu.com/s/1gdvoPRd 密码：37pd <br>

java基础增强视频 <br>
链接：http://pan.baidu.com/s/1udhqm 密码：xe67 <br>


